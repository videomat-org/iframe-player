# iframe-player
autoplay video player in an iframe (with random start time)

## but why?
* loading bar bug-fix on iphone ios
* call autoplay video with javascript immediately after the page is loaded
* example: https://videomat.org

## to do

### background video switch
low power mode on some devices disables autoplay completely. it is possible to check wether autoplay is working, to replace the video with an image, to prevent the play button, for example. could be tested with small hidden video, before the iframe is called. 

* https://developer.mozilla.org/en-US/docs/Web/API/HTMLMediaElement/paused
