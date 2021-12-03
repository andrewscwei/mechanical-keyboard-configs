# DZ60 Presets for macOS

![](/layer1.png?raw=true)
![](/layer2.png?raw=true)
![](/layer3.png?raw=true)

## Setup

1. To configure key mappings, use the web [QMK Configurator](https://config.qmk.fm/#/dz60/**LAYOUT_directional**)
2. To flash a firmware to the keyboard, install the QMK Toolbox app:
    ```sh
    $ brew cask install qmk-toolbox
    ```

## Usage

1. In the configurator, import `layout.json`.
2. Make any necessary key mapping changes
3. Select **Firmware** to generate and download the keyboard firmware
4. Flash the firmware to the DZ60 keyboard:
    1. Open the [QMK Toolbox](https://github.com/qmk/qmk_toolbox/releases) app
    2. Ensure keyboard is unplugged
    3. Hold `SPACE + B` on keyboard while plugging it into computer to enter DFU mode
    4. Flash `*.hex` firmware file from the app.

> For more info see https://beta.docs.qmk.fm/newbs/newbs_flashing
