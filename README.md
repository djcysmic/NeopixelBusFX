List of commands:

neopixel off [fadetime] [delay]
	switches the stripe off

neopixel on [fadetime] [delay]
	restores last state of the stripe

neopixel dim [dimvalue]
	dimvalue 0-255

neopixel line startpixel endpixel color

neopixel one pixel color

neopixel all color [fadetime] [delay]
neopixel rgb color [fadetime] [delay]
neopixel fade color [fadetime] [delay]

neopixel colorfade startcolor endcolor [startpixel] [endpixel]

neopixel rainbow [speed]

neopixel kitt color [speed]

neopixel comet color [speed]

neopixel theatre color [backgroundcolor] [count] [speed]

neopixel scan color [backgroundcolor] [speed]

neopixel dualscan color [backgroundcolor] [speed]

neopixel twinkle color [backgroundcolor] [speed]

neopixel twinklefade color [count] [speed]

neopixel sparkle color [backgroundcolor] [speed]

neopixel fire [fps] [brightness] [cooling] [brightness]

neopixel stop
	stops the effect

Use:

needed:
color,backgroundcolor -> targetcolor in hex format e.g. ff0000 for red

[optional]:
fadetime ->  fadetime per pixel in ms
delay ->  delay time to next pixel in ms, if delay < 0 fades from other end of the stripe


Based on WS2812FX, NeoPixelBus, Lights, NeoPixel - Basic and Candle modules

https://github.com/letscontrolit/ESPEasy
https://github.com/kitesurfer1404/WS2812FX
https://github.com/Makuna/NeoPixelBus
https://github.com/ddtlabs/ESPEasy-Plugin-Lights

Thank you to all developers
