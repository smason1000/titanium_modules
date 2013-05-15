# Change Log
<pre>
v2.1.2
          Minor fix for title and rotate - they were mixed up in 2.1.1

v2.1.1    Added the tiltEnabled property to enable/disable tilt gestures.
	  Added the rotateEnabled property to enable/disable rotation gestures.
	  Fixed a bug where left or right view was not being set correctly
	  Problem was with the if statement resetting the view if button or view (left/right) was null
		and the other wasn't.  It was getting overwritten

v2.1.0    Added the pinchangedragstate event to the Map View.
		  Supported custom views for the pin.
		  Added the enableZoomControls" property to enable/disable zoom controls.
		  Added the support of leftButton, leftView, rightButton and leftView for annotations.
		  Added the setLocation and zoom methods.

v2.0.0    Initial Release
