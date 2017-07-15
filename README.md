<i><b>List of commands:</b></i>

neopixelfx off [fadetime] [delay]
	switches the stripe off

neopixelfx on [fadetime] [delay]
	restores last state of the stripe

neopixelfx dim <i>dimvalue</i>
	dim stripe overall
	dimvalue 0-255

neopixelfx line <i>startpixel endpixel color</i>

neopixelfx one <i>pixel color</i>

neopixelfx all <i>color</i> [fadetime] [delay]
neopixelfx rgb <i>color</i> [fadetime] [delay]
neopixelfx fade <i>color</i> [fadetime] [delay]

neopixelfx colorfade <i>startcolor endcolor</i> [startpixel] [endpixel]

neopixelfx rainbow [speed]

neopixelfx kitt <i>color</i> [speed]

neopixelfx comet <i>color</i> [speed]

neopixelfx theatre <i>color</i> [backgroundcolor] [count] [speed]

neopixelfx scan <i>color</i> [backgroundcolor] [speed]

neopixelfx dualscan <i>color</i> [backgroundcolor] [speed]

neopixelfx twinkle <i>color</i> [backgroundcolor] [speed]

neopixelfx twinklefade <i>color</i> [count] [speed]

neopixelfx sparkle <i>color</i> [backgroundcolor] [speed]

neopixelfx fire [fps] [brightness] [cooling] [brightness]

neopixelfx stop
	stops the effect

neopixelfx statusrequest
	sends status
	
neopixelfx fadetime <i>value in ms</i>
neopixelfx fadedelay <i>value in +/- ms</i>
neopixelfx speed <i>value 0-50</i>
neopixelfx count <i>number of pixels</i>
neopixelfx bgcolor <i>color</i>
	sets default parameter

Use:

<i>needed:</i>
startcolor,endcolor,color,backgroundcolor -> targetcolor in hex format e.g. ff0000 for red

[optional]:
fadetime ->  fadetime per pixel in ms
delay ->  delay time to next pixel in ms, if delay < 0 fades from other end of the stripe


Based on WS2812FX, NeoPixelBus, Lights, NeoPixel - Basic and Candle modules

https://github.com/letscontrolit/ESPEasy
https://github.com/kitesurfer1404/WS2812FX
https://github.com/Makuna/NeoPixelBus
https://github.com/ddtlabs/ESPEasy-Plugin-Lights

Thank you to all developers
