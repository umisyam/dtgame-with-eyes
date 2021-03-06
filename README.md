THE DT GAME - for your eyes
==============

Based on Eyewriter 1.0
Download raw Eyewriter 1.0 code here: https://github.com/eyewriter/eyewriter-1.0

**Modifications**

We added code, so you can plug in your Playstation Eye Camera and you're good to go to use the preexisting code.
To actually play the game we added an additional scene(mode) and for simplicity deleted other scenes that we don't need right now.

*Addons needed*
- ofxOsc
- ofxXmlSettings
- ofxOpenCv
- ofxPS3EyeGrabber (Download here: https://github.com/bakercp/ofxPS3EyeGrabber)
- ofxKinect

*Physical components needed*
Hack the PSEye and swap the camera with a tele lens (the view field is very narrow in comparison). Add IR Leds to enhance the contrast in the eye (brings out the pupil). Noticed in tests, some eye colors work better than others.
![](https://github.com/228miles/dtgame-with-eyes/blob/master/documentation/pseye.jpg)

$10 – [PSEye](http://www.amazon.com/gp/product/B000VTQ3LU/ref=oh_aui_detailpage_o07_s00?ie=UTF8&psc=1)

$9 – [Lens](http://www.amazon.com/gp/product/B00N3ZPTE6/ref=oh_aui_detailpage_o06_s00?ie=UTF8&psc=1)

$6 – [Lens Mount](http://www.ebay.com/itm/111500226186?_trksid=p2060778.m2749.l2649&ssPageName=STRK%3AMEBIDX%3AIT)

$9 – IR Leds (20 pieces)

$5 – 9 Volt Battery
 
**Demo**

![](https://github.com/228miles/dtgame-with-eyes/blob/master/documentation/eyetracking2.jpg)
![](https://github.com/228miles/dtgame-with-eyes/blob/master/documentation/eyetracking1.png)

Calibration process (look at the circle).
![](https://github.com/228miles/dtgame-with-eyes/blob/master/documentation/eyetracking_calibration.jpg)

Here you can see the actual game. The green circle shows you the position of the eye gaze. Its vertical position is mapped to the position of the game's main character.
![](https://github.com/228miles/dtgame-with-eyes/blob/master/documentation/game.png)
