
PIC32LuaMZ
==========

Lua for PIC32MZ Processors.

After all that experiences and fun with Lua on PIC32(MX) MCUs
(see [github.com/FMMT666/PIC32Lua][2]), we're back with a 200MHz, 512bK RAM edition:

Lua for the [PIC32MZ][3] \o/

Upcoming attraction, nothing to see here (for now ;-).  


---

## REQUIREMENTS

  Although I created some custom boards, this software comes configured for the
  [PIC32MZ EC Starter Kit][4], which basically contains:
  
  - PIC32MZ2048ECH144 MCU
  - 24MHz external oscillator
  - ...

  If you own that, you'll only need MPLab-X and the XC32 compiler.


---

## NEXT STEPS

  - interfaces for in- and output (serial, USB, ...)
  - upgrading to a recent Lua version (not sure whether v5.3.3 is "too modern")
  - ports
  - all the other stuff from [here][2]
  - ...


---

## CHANGES

### V0.10, 2013/xx/xx
    - NEW: compiling, executing, but no IOs or user interaction possible
      (That wasn't actually true. It didn't work ;-)

### V0.11, 2016/07/30
    - NEW: compiling, really executing, but no IOs or user interaction possible


---

Have fun  
FMMT666(ASkr)  


[1]: http://www.askrprojects.net/software/pic32lua/index.html
[2]: https://github.com/FMMT666/PIC32Lua
[3]: http://www.microchip.com/design-centers/32-bit/architecture/pic32mz-family
[4]: http://www.microchip.com/DevelopmentTools/ProductDetails.aspx?PartNO=DM320006


