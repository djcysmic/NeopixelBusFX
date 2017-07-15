<i><b>List of commands:</b></i><br>

neopixelfx off [fadetime] [delay]<br>
o switches the stripe off<br>

neopixelfx on [fadetime] [delay]<br>
o restores last state of the stripe<br>

neopixelfx dim <i>dimvalue</i><br>
o dim stripe overall<br>
o dimvalue 0-255<br>

neopixelfx line <i>startpixel endpixel color</i><br>

neopixelfx one <i>pixel color</i><br>

neopixelfx all <i>color</i> [fadetime] [delay]<br>
neopixelfx rgb <i>color</i> [fadetime] [delay]<br>
neopixelfx fade <i>color</i> [fadetime] [delay]<br>

neopixelfx colorfade <i>startcolor endcolor</i> [startpixel] [endpixel]<br>

neopixelfx rainbow [speed]<br>

neopixelfx kitt <i>color</i> [speed]<br>

neopixelfx comet <i>color</i> [speed]<br>

neopixelfx theatre <i>color</i> [backgroundcolor] [count] [speed]<br>

neopixelfx scan <i>color</i> [backgroundcolor] [speed]<br>

neopixelfx dualscan <i>color</i> [backgroundcolor] [speed]<br>

neopixelfx twinkle <i>color</i> [backgroundcolor] [speed]<br>

neopixelfx twinklefade <i>color</i> [count] [speed]<br>

neopixelfx sparkle <i>color</i> [backgroundcolor] [speed]<br>

neopixelfx fire [fps] [brightness] [cooling] [brightness]<br>

neopixelfx stop<br>
o stops the effect<br>

neopixelfx statusrequest<br>
o sends status<br>
	
neopixelfx fadetime <i>value in ms</i><br>
neopixelfx fadedelay <i>value in +/- ms</i><br>
neopixelfx speed <i>value 0-50</i><br>
neopixelfx count <i>number of pixels</i><br>
neopixelfx bgcolor <i>color</i><br>
o sets default parameter

Use:<br>

<i>needed:</i><br>
startcolor,endcolor,color,backgroundcolor -> targetcolor in hex format e.g. ff0000 for red<br>

[optional] : <br>
fadetime ->  fadetime per pixel in ms<br>
delay ->  delay time to next pixel in ms, if delay < 0 fades from other end of the stripe<br>


Based on WS2812FX, NeoPixelBus, Lights, NeoPixel - Basic and Candle modules<br>

https://github.com/Makuna/NeoPixelBus<br>
https://github.com/letscontrolit/ESPEasy<br>
https://github.com/kitesurfer1404/WS2812FX<br>
https://github.com/ddtlabs/ESPEasy-Plugin-Lights<br>

Thank you to all developers
