# arduino-max7219-led-interactive-scrolling-text-display
An interactive scrolling text display sketch for Arduino and MAX7219 8x8 LED display modules.
 
This is the code I use to control the MAX7219 8x8 LED modules from my Chinese "Geekcreit"-brand Arduino clone.
 
The first module is connected to the Uno like this:
 
Module: VCC -> Uno: 5V
Module: GND -> Uno: GND
Module: DIN -> Uno: D8
Module: CS  -> Uno: D9
Module: CLK -> Uno: D10
 
Additional modules are connected like this:
 
Module 2: VCC -> Module 1: VCC
Module 2: GND -> Module 1: GND
Module 2: DIN -> Module 1: DIN
Module 2: CS  -> Module 1: CS
Module 2: CLK -> Module 1: CLK
 
See the blog post at https://oneguyoneblog.com/2016/10/20/max7219-arduino-ticker-8x8-led-modules/
