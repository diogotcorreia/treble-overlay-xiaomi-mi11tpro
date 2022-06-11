# Treble Overlay for Xiaomi 11T Pro

This Magisk module places the Treble Overlay on `/system/product/overlay`, since `/system` is read-only on Magisk systems.

Overlays can be found in [phhusson's repository](https://github.com/phhusson/vendor_hardware_overlay).
At the moment, an overlay for this is device is only [available on a PR](https://github.com/phhusson/vendor_hardware_overlay/pull/557).

## Using this Module

1. Download the zip from the [releases tab](https://github.com/diogotcorreia/treble-overlay-xiaomi-mi11tpro)
2. Move it to your device (through `adb push` for example)
3. Install the module using Magisk

## Building

You can use the provided APK from the repo, or replace it with a modified overlay.

To generate the zip file for Magisk, run

```
make
```

You must be running a Linux system and have `make` installed. Otherwise, you can zip the files manually.

### Cleaning Up

To delete the generated artifacts, run

```
make clean
```
