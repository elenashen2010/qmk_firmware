# There's a QMK console, open that first!
The rest of these instructions will be done in it.

# 1. Build firmware
You should have your QMK config setup already (Do `qmk config` to verify). So just run compile
```sh
qmk compile
```

If you don't have any config, do
```sh
qmk compile -kb <keyboard> -km <keymap>
```

It takes a minute, so be patient.

# 2. Flash firmware
1. Open QMK Toolbox
2. Click on open and select the firmware that was built previously. It should be opened to the correct folder already, but if not go to C:\Workspace\QMK\qmk_firmware
3. Put the keyboard into bootloader mode. On the GMMK Pro, you can press Fn+Backslash. For other keyboards, check the readme in the keyboard's respective folder within this project. QMK Toolbox should display a message when bootloader mode activates.
4. Click "Flash"
5. Done!

# Way more in depth instructions in the QMK docs!
https://docs.qmk.fm/newbs_building_firmware