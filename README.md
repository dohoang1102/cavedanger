Cavedanger

Unfinished prototype of a cave flyer game for Mac OS X.
Uses Cocos2d + Box2D (http://www.cocos2d-iphone.org/).
Tested with XCode 4.2.1.

How to build:

level.svg contains the collision map (done with Inkscape).
Use make.php to convert level.svg to source code:

    php make.php level.svg > /tmp/level.inc

Then compile and run the XCode project.

<img src="https://github.com/sebcode/cavedanger/raw/master/screenshot.png">

- - - 
by Sebastian Volland
