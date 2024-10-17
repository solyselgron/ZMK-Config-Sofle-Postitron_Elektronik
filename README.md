# ZMK-Config-Sofle-Postitron_Elektronik

## Specsifications
- 2 x Sofle V2 PCB Keyboard
- 2 x NRF52840 controller
- 2 x 2 x Lithium Polymer battery 640mAH
- 2 x Oled
- 2 x Encoder EC11
- 2 x 12 LED RGB


# # HOW to FLASH
- first you need to get firmware on this repository. go to tab "Actions" , click to your last commit that successfully to compile, you can see green marking berfore name of your commit. if you see red marking on side of name your marking its mena you code is failed to compile. 
- after click your commit, you will direct to new page. go to bottom page, you will see file with label firmware, you can download it. this is zip file that contains 2 file firmware with uf2 extension for left side and right side.
- get your keyboard, you need to flash on each side. the left firmware is for left side keyboard and it is same with right firmware for right keyboard.
- Connect your left keyboard to your PC. get allen key that you can get on package the keyboard. Double click the reset button on left keyboard with allen key.
- then you should see a file explorer window open in the NICENANO directory.
- Simply drag and drop your chosen firmware file into this folder, making sure you select the correct half.
- Disconnect the left keyboard from your PC and repeat the steps for the right keyboard.
- You have now successfully flashed the ZMK firmware to your keyboard 
<p align="center">
    <img src="nicenano-folder.gif" width="75%" height="75%">
</p>