# EnderS-1KlipperBackup


Public welcome to my BACKUp for ENDER S-1
-- Stock Mainboard STM32F103RET6
--Neopixels
-- EZABL (12mm)
-- 5015 parts cooling fan on sprite extruder





The file that is labeled PIS.cfg is for running the input shaper that makes everything so easy. needs to be included in the printer.cfg

Portable Input Shaper

![image](https://user-images.githubusercontent.com/100983669/197179734-e44c7ee7-e113-40f2-87cc-bc77cafa632e.png)


The start

Realize the idea of Nero3D of this video: https://www.youtube.com/watch?v=W_VHbT_tsZw, thanks for his sharing.
Advantage

    Base on popular RP2040 chip

    Portable and you can use it on multiple Klipper firmware based 3D printer with same configuration file. Save your time.

    Size is small and easy to dock on print head(AfterBurner, StealthBurner or even other print head) as we designed different holes on it with essential fasteners for you to install it on print head.

    USB-C port

Firmware
menuconfig

![image](https://user-images.githubusercontent.com/100983669/197179809-b6dc4c4b-e027-402d-9077-a20c6a083081.png)


config

Use PIS.cfg, and add it to your printer.cfg by

[include PIS.cfg]

how to flash

    Press and hold the button

    Connect it to your PC with USB-C cable

    Release the button

    Folder named RPI-RP2 popup, copy the klipper.uf2 to the folder

    Wait for several seconds, when finished folder will closed automatically

    Done

Attention

Make sure you flash PIS the same Klipper version as your machine. I recommend you update Klipper to latest version.
