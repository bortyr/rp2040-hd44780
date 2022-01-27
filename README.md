# Raspberry Pi Pico with HD44780 based on rp2040-hal

This project is based on [rp2040-project-template](https://github.com/rp-rs/rp2040-project-template)

![rp2040-hd44780](rp2040-hd44780.jpg)

## Quickstart

Wiring will depend on you 16x02 display (based on HD44780 controller). Remeber that Raspberry Pi Pico runs on 3.3V. 

Note: You can use resistor to VDD to make voltage diffrence. This will give you better contrast on the display 

`elf2uf2-rs tool` is configured as the default runner 

```sh
cargo run --release
```
