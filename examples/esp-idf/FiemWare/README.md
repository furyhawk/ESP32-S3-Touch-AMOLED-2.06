# Brookesia Default Firmware Source

[简体中文](README_ZH.md)

This ESP-IDF project is the source for the default firmware delivery in the
parent directory. Build it with ESP-IDF `v5.5.5` as documented in
[`../README.md`](../README.md). The generated `flash_args` from the final build
is the sole input plan for the FactoryOnly combined image.

The project is intentionally outside `examples/`: it is a product firmware
delivery source, not a default CI example. Compilation does not constitute
flashing or HIL validation.
