# GoogleChromeBackgoundAffect
This replicates the fade-out affect of images seen on Google’s Chrome Cast.

Instructions:

This requires a web server that can execute php code.  It requires one php script to create an array with the image names.

Images are stored in ”img/bg” directory.

*** VERY IMPORTANT ***
You must have a minimum of four images in that directory.

pocChromeAffect.js :

You can adjust the fade-out rate here and delay between the affect.  Change the 3000 for duration of fade-out affect and  9000 for the delay between.

Every 1000 is equal to one second.

$(thisDivIsOnTop).delay( 9000 ).animate({opacity: 0}, 3000,

Demo:

http://mo-de.net/GoogleChromeBackgroundAffect/chromeAffect.html

Bugs:

Image flickers on Firefox.  Any help fixing this would be greatly appreciated.  I narrowed it down to jQuery's behavior at the end of changing the opacity.

On Github:
https://github.com/lindylex/GoogleChromeBackgoundAffect
