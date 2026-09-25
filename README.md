# BeagleBone Black DRM/KMS Console

Embedded Linux project for integrating small displays with the Linux DRM/KMS
graphics stack on BeagleBone Black and using them as a Linux console.

## Initial target

- Board: BeagleBone Black
- Initial display controller: ST7735
- Build system: Buildroot
- Kernel graphics stack: DRM/KMS
- Console target: fbcon
- Initial goal: boot a clean BBB Buildroot image with UART, Ethernet, SSH and USB ECM.

ST7735 is the first bring-up target. The project is intentionally not tied to
one display controller.

## Development phases

1. Clean BBB Buildroot baseline
2. Ethernet + SSH + USB ECM
3. DRM/KMS kernel configuration
4. Display driver and Device Tree bring-up
5. DRM framebuffer testing
6. fbcon console
7. Boot-console optimization
8. Optional additional display controllers
