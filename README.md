## Playing never gonna give you up on EV3
LEGO Mindstorms EV3 limits sound only to 8 seconds 
but it doesn't limit the amount of audio clip you have
So all you need to split it to 8 seconds segment and then import all the files

If you want to make your own, you can use the following ffmpeg command to split it

   ```ffmpeg -i your_mp3.mp3 -f segment -segment_time 7.8 -c copy %01d.mp3```
   
  Note that i put it 7.8 seconds so it can be under the limit without any problems

I might later add for NXT and maybe RCX
so 
## TODO
 - [x] EV3
 - [ ] NXT
 - [ ] RCX

