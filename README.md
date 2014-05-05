HighResolutionStatistics
Ritvik Choudhary
========

#### Performance Monitor ####

This class provides a simple info box that will help you monitor your code performance.
So far available for Actionscript and HaXe.

* **FPS** Frames per second, how many frames were rendered in 1 second. The higher the number the better.
* **MS** Milliseconds needed to render a frame. The lower the number the better.
* **MEM** Memory your code is using, if it increases per frame is VERY wrong.
* **MAX** Maximum memory the application reached.

### Usage ###

	addChild( new Stats() );

### Controls ###

* **CLICK** Top-half / bottom-half part of the panel to increase/decrease the FPS of the application.


