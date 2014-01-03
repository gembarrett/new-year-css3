New Years Eve CSS3 experiment
=============

Experiment in CSS3 animation

This 12-hour experiment in CSS3 animation demonstrates the use of CSS3 keyframes (fireworks), sprites (background image), and other transition styles. 

- index.html: where the animation takes place
- css: contains folders for the SASS and final, minified stylesheet
- Gruntfile.js: contains the configuration used to make Grunt watch, process and minify the CSS and images
- images: actually only contains one image - the background sprite
- node_modules: contains the Grunt task set-ups
- package.json: further configuration of the Grunt tasks

Any bug submissions or suggestions for improvements or  features (I'd like to add snow to the animation at some point) gratefully received.

For further info about this project, please contact me at gem@gembarrett.com. The rest of my portfolio is at gembarrett.com if you're curious :)


Glitches I am currently working on:
- flash of fireworks outside specified area
- compatibility with touch-devices (currently the JS provides a temporary fix for iOS, but breaks for Android)
- occasional background flash on initial background-position change animation
