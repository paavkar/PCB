# PCB projects

## Introduction

This repository is meant for my PCB projects.

## IoT-Device

This is a PCB project where I am trying to design my own IoT device.
The MCU used in this is STM32U585VI with a ESP32-C3-WROOM-02 as a WiFi co-processor.
The design includes a reset-boot logic to choose the boot mode (i.e. either to
bootloader or flash). Included is also a port for SWD. In this board, USB-C is
used in 2.0 speed to give the board power and program the board.

### Schematic

You can take a look at the schematic in this repo from this
<a href="/IoT-Device/schematic.pdf">link.</a>

## Metro-M4-Express-Shield

This project is a much more simpler one as it is only a shield for the Metro M4 Express.
The goal of this PCB project was to design a shield that adds WiFi functionality
to the development board. The WiFi-module used is the ESP32-WROOM-32E, which is
used as a base for the FireBeetle board.

### Schematic

The schematic is available on this repo from the following
<a href="/Metro-M4-Express-Shield/schematics/schematic.pdf">link.</a>
