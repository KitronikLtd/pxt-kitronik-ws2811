# pxt-kitronik-ws2811

A driver for WS2811 ICs in MakeCode.

## Usage

### sendBuffer

The package exposes ``Kitronik_WS2811.sendBuffer`` that bit-bangs a buffer for WS2811 ICs over a pin.

### setBufferMode

This function allows to specify the color layout in the buffer.

```
#define LIGHTMODE_RGB 1
#define LIGHTMODE_RGBW 2
#define LIGHTMODE_RGB_RGB 3
```

## ~ hint
 
**Bluetooth disabled**: This package disables BLE as the real time requirements of the WS2811 conflict with the BLE stack.

## ~

## Simulator support

The ``sendBuffer`` function is supported by the micro:bit simulator!

## License

MIT

## Supported targets

* for PXT/microbit

(The metadata above is needed for package search.)


## Code of Conduct

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
