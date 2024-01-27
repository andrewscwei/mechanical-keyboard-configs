# WhiteFox True Fox Configuration for macOS

![](/whitefox/layout.png?raw=true)

## Setup

To configure key mappings, ~~either use the (recommended) [web configurator](https://configurator.input.club/?layout=WhiteFox-TheTrueFox) or~~ install the IC Configurator app:

```sh
$ brew cask install kiibohd-configurator
```

You can also download the latest version of the IC Configurator app here: https://kiibohd.github.io/wiki/#/Quickstart.

## Usage

1. In the configurator, import `map.json`
2. Make any necessary key mapping changes
3. Select **Download Firmware**
4. Flash the firmware to the connected WhiteFox keyboard:
    ```sh
    $ dfu-util -D kiibohd.dfu.bin
    ```
    > See https://kiibohd.github.io/wiki/#/Quickstart.

## Resources

Wiki: https://kiibohd.github.io/wiki/#/
