# StackRduino M0 PRO UF2 bootloader 
## Adafruit UF2 bootloader for the StackRduino M0 PRO .

### Step 1 - Clone Repository and Set Up Environment
```
git clone https://github.com/adafruit/uf2-samdx1
cd uf2-samdx1
```

### Step 2 Install ARM-Cross Compilers
```
sudo add-apt-repository ppa:team-gcc-arm-embedded/ppa
sudo apt-get update
sudo apt-get install gcc-arm-embedded
```

### Step 3 Compile Board
```
make BOARD=stackrduino_m0_pro
```

## Updating Firmware
### Option 1
- Attach StackRduino M0 PRO to your computer via USB.
- Double Tap 'reset' button to put board into UF2 Bootloader mode
- Download the update-bootloader-M0-PRO uf2 file 
- Copy update-bootloader-M0-PRO.uf2 to the USB Drive called "StackRduino"
- Done.
### Option 2
- Attach StackRduino M0 PRO to your computer via USB.
- Download the  update-bootloader-M0-PRO ino file 
- Open the file using the Arduino ide and select the board and port for the StackRduino M0 pro.
- Upload the bootloader via normall upload icon
- Done.
