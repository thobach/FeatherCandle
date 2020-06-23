# FeatherCandle
Animated candle using Adafruit Feather and Adafruit CharliePlex FeatherWing 15x7 LED array

Clone of [wbphelps/FeatherCandle](https://github.com/wbphelps/FeatherCandle) which is based on Adafruit/FirePendant, modified for the Feather. Loops a canned animation sequence on two displays.

Arduino sketch is comprised of 'FeatherCandle.ino' and 'data7x15.h' -- latter contains animation frames packed into PROGMEM array holding bounding rectangle + column-major pixel data for each frame (consumes most of the flash space on the ATmega328).

The 'frames.zip' archive contains the animation source PNG images and a python script, convert.py, which processes all the source images into the required data.h format. The PNG images were generated via Adobe Premiere and Photoshop from [Free Stock Video by user 'dietolog' on Videezy.com](https://www.videezy.com/fire-and-smoke/788-candle-light-stock-video).

# Parts
* 1x [Adafruit HUZZAH32 – ESP32 Feather Board](https://www.adafruit.com/product/3405)
* 2x [Adafruit 15x7 CharliePlex LED Matrix FeatherWing - Warm White](https://www.adafruit.com/product/3163)
* 1x [Wentronic S 166 Schiebeschalter](https://www.amazon.de/gp/product/B000OH5PH2/ref=ppx_yo_dt_b_asin_title_o00_s00?ie=UTF8&psc=1)
* 1x [VinCorp 1x Lipo Akku 1s 3,7V 2500mAh JST PH Stecker](https://www.amazon.de/gp/product/B0863PZPSM/ref=ppx_yo_dt_b_asin_title_o01_s00?ie=UTF8&psc=1)
* wires
* plywood
* black acrylic paint
* wood glue

# Wiring
* LIPO battery to Adafruit HUZZAH32
* 3V and Ground of Adafruit HUZZAH32 to each FeatherWing, [see pinout of FeatherWing](https://learn.adafruit.com/adafruit-15x7-7x15-charlieplex-led-matrix-charliewing-featherwing/pinouts)
* SDA and ACL of Adafruit HUZZAH32 to each FeatherWing, [see pinout of FeatherWing](https://learn.adafruit.com/adafruit-15x7-7x15-charlieplex-led-matrix-charliewing-featherwing/pinouts)
* connect jumper 0x77 with a solder jumper on one of the FeatherWing's, [see instructions](https://learn.adafruit.com/adafruit-15x7-7x15-charlieplex-led-matrix-charliewing-featherwing/pinouts)

# Laser cut carvings
Adobe Illustrator files for and instructions for  laser cut carvings will follow

# Assembly
Pictures will follow
