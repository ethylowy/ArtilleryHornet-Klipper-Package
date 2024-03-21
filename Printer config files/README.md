# Printer config files
Those files are from my printer, as an example, what they should look like, when all is set up and ready.

adxl.cfg is for external ADXL345 chip wired to Raspberry Pico, and is included (as commented line) in printer.cfg.
If You want to run Input Shaper, just hook-up the cable, and uncomment [include] section in printer.cfg.
After running the calibration, just edit input_shaper.cfg, uncomment and enter proper values there.