# web-audio-surf

A basic version of AudioSurf with BabylonJS.

## todo:

* create cube and test collision
* parse music track to get length - decide on music seconds -> mesh unit size in game
* once unit size is known update track length
* check how to play audio - play file
* add start button so music isn't always playing
* move player along track (if start button pressed) so rocket reaches end of track as the music ends
* make particles smaller until "start" is pressed? Maybe also blue, then move it to red as it powers up
* split audio amplitude? into 3 parts (high/mid/low) to determine where boxes go
* draw cubes at the high/mid/low points on track (z axis: -2 , 0, 2)
* move track and cubes along towards player
* add score increment whenever the rocket hits the box
* add in another type of shape which is negative if player touches (subtracts score)
* based on tempo of track change cube colours so "faster/harder" sections get more points
* add random height mapping to track so it looks cooler?
