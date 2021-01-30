# 6 Pack_External Driver CNC Controller

<img src="https://github.com/bdring/6_Pack_External_Drivers/blob/main/images/photo1.jpg" width="600">

This [Grbl_ESP32](https://github.com/bdring/Grbl_Esp32) CNC controller is based on the [6 Pack CNC Controller](https://github.com/bdring/6-Pack_CNC_Controller), but this one is optimized for external stepper motor drivers. This is less flexible than the regular 6 Pack, but it has a few advantages if you only need to use external drivers.

- Smaller footprint
- No jumpers to set.
- Outputs 5V signals with enough current to driver the optically isolated inputs most driver use.
- Fully compatible with all the CNC I/O module of a 6 Pack.
- A couple of extra I2S0 output pins.

### Open Source

The design is open source. There is a JLCPCB assembly friendly BOM to get most of the SMT parts assembled. You still have to solder the SD card socket. That part is available at LCSC, but not part of the JLC assembly parts list. 
