<i><b>List of commands:</b></i><br>

nfx off [fadetime, default:1000] [delay +/-ms, default:20]<br>
o switches the stripe off<br>

nfx on [fadetime, default:1000] [delay +/-ms, default:20]<br>
o restores last state of the stripe<br>

nfx dim <i>dimvalue</i><br>
o dim stripe overall<br>
o dimvalue 0-255, default:255<br>

nfx line <i>startpixel endpixel color</i><br>

nfx one <i>pixel color</i><br>

nfx all <i>color</i> [fadetime, default:1000] [delay +/-ms, default:20]<br>
nfx rgb <i>color</i> [fadetime, default:1000] [delay +/-ms, default:20]<br>
nfx fade <i>color</i> [fadetime, default:1000] [delay +/-ms, default:20]<br>

nfx hsv <i>hue[0-360] saturation[0-100] brightness[0-100]</i> [fadetime, default:1000] [delay +/-ms, default:20]<br>

nfx colorfade <i>startcolor endcolor</i> [startpixel] [endpixel]<br>
o startpixel default: 0<br>
o endpixel default:pixelcount-1<br>

nfx rainbow [speed]<br>
o speed +/- 0-50, default: 1<br>

nfx kitt <i>color</i> [speed]<br>
o speed +/- 0-50, default: 25<br>

nfx comet <i>color</i> [speed]<br>
o speed +/- 0-50, default: 25<br>

nfx theatre <i>color</i> [backgroundcolor] [count] [speed]<br>
o count default: 1<br>
o speed +/- 0-50, default: 25<br>

nfx scan <i>color</i> [backgroundcolor] [speed]<br>
o speed +/- 0-50, default: 25<br>

nfx dualscan <i>color</i> [backgroundcolor] [speed]<br>
o speed +/- 0-50, default: 25<br>

nfx twinkle <i>color</i> [backgroundcolor] [speed]<br>
o speed +/- 0-50, default: 25<br>

nfx twinklefade <i>color</i> [count] [speed]<br>
o count default: 1<br>
o speed +/- 0-50, default: 25<br>

nfx sparkle <i>color</i> [backgroundcolor] [speed]<br>
o speed +/- 0-50, default: 25<br>

nfx wipe color [dotcolor] [speed]<br>
o speed +/- 0-50, default: 25<br>

nfx dualwipe color [dotcolor] [speed]<br>
o speed +/- 0-50, default: 25<br>

nfx fire [fps] [brightness] [cooling] [sparking]<br>
o fps default: 50<br>
o brightness 0-255, default: 31<br>
o cooling 20-100, default: 50<br>
o sparking 50-200, default: 120<br>

nfx fireflicker [intensity] [speed]<br>
o intensity default: 3<br>
o speed +/- 0-50, default: 25<br>

nfx faketv [startpixel] [endpixel]<br>
Paste faketv.h in ./src<br>
o startpixel default: 0<br>
o endpixel default:pixelcount-1<br>

nfx simpleclock [bigtickcolor] [smalltickcolor] [hourcolor] [minutecolor] [secondcolor] [backgroundcolor]<br>
o bigtickcolor, default: 505050<br>
o smalltickcolor, default: 101010<br>
o hourcolor, default: 0000FF<br>
o minutecolor, default: 00FF00<br>
o secondcolor, default: FF0000 - color of the second hand - can be set to "off" to turn the second hand completly off<br>
o backgroundcolor, default: 000000<br>

nfx stop<br>
o stops the effect<br>

nfx statusrequest<br>
o sends status<br>
	
nfx fadetime <i>value in ms</i>, Default: 1000<br>
nfx fadedelay <i>value in +/- ms</i>, Default: 20<br>
nfx speed <i>value 0-50</i>, Default: 25<br>
nfx count <i>number of pixels</i>, Default: 1<br>
nfx bgcolor <i>color</i>, Default: 000000<br>
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
