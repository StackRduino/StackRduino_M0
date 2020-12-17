# CircuitPython Firmware for the StackRduino M0 PRO

### Set Up Build Environment
```
git clone https://github.com/adafruit/circuitpython/
cd circuitpython/
git submodule update --init --recursive
make -C mpy-cross
cd circuitpython/ports/atmel-samd/
```

### Build Steps
The default board is debug. You can build a different one using:
```
make -j8 BOARD=stackrduino_m0_pro
```
Further instruction: https://learn.adafruit.com/building-circuitpython/build-circuitpython



## Updating Firmware
- Attach StackRduino M0 PRO to your computer via USB.
- Double Tap 'reset' button to put board into UF2 Bootloader mode
- Copy firmware.uf2 from the build folder to the USB Drive called "StackRduino".
- Wait for CircuitPython to be installed (about 5 seconds).
- Done.
