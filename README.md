# Portfolio / Personal Website
Webpage redesign for myself

To remember:
- make sure sass is installed: http://sass-lang.com/install
- cd into the stylesheets folder
- $sass --watch wenevergo.scss:outofstyle.css

*To Do:*

*Phase 1:*
- replace columns classes with @include
- ~~typography~~
- color palette
- media queries 
- ~~find a lightweight jquery slider to use for portfolio~~
- add email form
- add social links
- add shape details
- add footer
- ~~replace lorem ipsum with real copy~~
- launch!

*Phase 2:*
- add animations
- optimize/refactor

--------------
--------------

*Where I Left Off:*
- *11/2/2015*: Added video header to ramennoodle branch, need to convert mp4 to ogv and webm formats. Figure out why it's not quite full screen (is it just my laptop again??). Also re-align bio div underneath video. Would like to add b&w/sepia/otherwise monochromatic filter on video - can do in pure CSS or external editing required? To optimize: compress video!

- *11/3/2015*: Converted video and now it works because i didn't spell the file name wrong. yay. still looking to add "filter"

- *11/11/2015*: Added "filter" to video, added some examples of portfolio work. 

-- Still need to add some things including: WC16 branding, WC17 branding, bangkok tshirts, webinars logo, TWM logo, photo of hand lettered business cards (depending on rxn). 
--Fix typography: headlines should be bolder and stand out more from the body text. 
--Color should be addressed: find a different grey dammit. Maybe background should stay white and some highlights in grey (contact? to give balance to the page?).  
--Need to add caption/more info to zoom in of portfolio projects
--Add link to printable resume 

- *11/17/2015*: Added "skills" section. Made some style changes ~but it seems they weren't quite writing to the css file correctly~ to the correct css file. 

- *11/20/2015*: Made lots of changes to the video, but it essentially looks the same. Added a greyscale filter, decided not to do the gradient. changed background to white. Made headers bold. Still figuring out zoom to caption on carousel. Added jQuery show on click, but now I can't get it to hide. Not sure how to re-render the script after the new featherlight (lightbox) divs are generated, which is causing problems in how I expect to click to hide. Probably going about this in a really roundabout way.
	_Left to do_:
	- figure out how to hide .carouselDetails after clicking to close box
	- OR just find a better carousel that has that functionality built in. May need to hunt around more, look at slick slider again.
	- Figure out how to incorporate skillshare classes, here's a link to completed classes: https://www.skillshare.com/mkmckenzie/completed
	- make responsive cause it looks like straight nonsense on a small screen right now. ref for media queries in sass: http://thesassway.com/intermediate/responsive-web-design-in-sass-using-media-queries-in-sass-32
