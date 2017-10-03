<b>ATTENTION! Due to an implementation in FHEM the main command has changed to "nfx"!<br>
For now it is also possible to use the old main command "neopixelfx", but maybe I will kick it out at later versions.</b>

<i><b>List of commands:</b></i><br>

nfx off [fadetime] [delay]<br>
o switches the stripe off<br>

nfx on [fadetime] [delay]<br>
o restores last state of the stripe<br>

nfx dim <i>dimvalue</i><br>
o dim stripe overall<br>
o dimvalue 0-255<br>

nfx line <i>startpixel endpixel color</i><br>

nfx one <i>pixel color</i><br>

nfx all <i>color</i> [fadetime] [delay]<br>
nfx rgb <i>color</i> [fadetime] [delay]<br>
nfx fade <i>color</i> [fadetime] [delay]<br>

nfx colorfade <i>startcolor endcolor</i> [startpixel] [endpixel]<br>

nfx rainbow [speed]<br>

nfx kitt <i>color</i> [speed]<br>

nfx comet <i>color</i> [speed]<br>

nfx theatre <i>color</i> [backgroundcolor] [count] [speed]<br>

nfx scan <i>color</i> [backgroundcolor] [speed]<br>

nfx dualscan <i>color</i> [backgroundcolor] [speed]<br>

nfx twinkle <i>color</i> [backgroundcolor] [speed]<br>

nfx twinklefade <i>color</i> [count] [speed]<br>

nfx sparkle <i>color</i> [backgroundcolor] [speed]<br>

nfx wipe color [dotcolor] [speed]<br>

nfx dualwipe color [dotcolor] [speed]<br>

nfx fire [fps] [brightness] [cooling] [sparking]<br>

nfx faketv [startpixel] [endpixel]<br>
Paste faketv.h in ./src<br>

nfx stop<br>
o stops the effect<br>

nfx statusrequest<br>
o sends status<br>
	
nfx fadetime <i>value in ms</i><br>
nfx fadedelay <i>value in +/- ms</i><br>
nfx speed <i>value 0-50</i><br>
nfx count <i>number of pixels</i><br>
nfx bgcolor <i>color</i><br>
o sets default parameter

Use:<br>

<i>needed:</i><br>
startcolor,endcolor,color,backgroundcolor, dotcolor -> targetcolor in hex format e.g. ff0000 for red<br>

[optional] : <br>
fadetime ->  fadetime per pixel in ms<br>
delay ->  delay time to next pixel in ms, if delay < 0 fades from other end of the stripe<br>
speed -> 0-50, speed < 0 for reverse


Based on Adafruit Fake TV Light for Engineers, WS2812FX, NeoPixelBus, Lights, NeoPixel - Basic and Candle modules<br>

https://learn.adafruit.com/fake-tv-light-for-engineers/overview<br>
https://github.com/Makuna/NeoPixelBus<br>
https://github.com/letscontrolit/ESPEasy<br>
https://github.com/kitesurfer1404/WS2812FX<br>
https://github.com/ddtlabs/ESPEasy-Plugin-Lights<br>

Thank you to all developers
