# EzTrack
Web-based app that track joint movements to help patients recovering from joint traumas undergo their physical therapy at home. It is developped based on tracking.js and canvasjs.

tracking.js
https://github.com/eduardolundgren/tracking.js
http://trackingjs.com
files from tracking.js: tracking-min.js, stats.min.js, color_camera_gui.js

canvasjs
https://canvasjs.com
files from canvasjs: canvasjs.min.js

Refer to the demo video (demo video.m4v) for how this app works.

To use this app, just open index.html (with other files in the same directory) in a compatible browser on a device connected/built-in with a camera.

EzTrack tracks your joint angle, and angular velocity of the joint angle based on web-camera.
Currently it requires color stickers to work. By default exactly 1 red, 1 yellow and 1 blue stick are required, but you can customize it by editting the javascript in index.html

tracking.js relies on getUserMedia(), refer the link below for browser compatibility.
https://developer.mozilla.org/en-US/docs/Web/API/Navigator/getUserMedia#Browser_compatibility
