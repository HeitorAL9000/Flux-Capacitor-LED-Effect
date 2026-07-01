# PIC12F683 Flux Capacitor LED Effect

A simple **Back to the Future inspired Flux Capacitor LED effect** built around a **PIC12F683** microcontroller.

This project uses **3 lines of 5 LEDs** arranged in a **Y configuration** to visually resemble the famous Flux Capacitor from the DeLorean time machine. The LEDs run a smooth one-direction chase effect with fade-in and fade-out, and a push button allows the user to cycle through **5 different speed presets**.

## Features

* Flux Capacitor inspired LED layout
* 3 branches of 5 LEDs in a Y configuration
* Smooth fade-in / fade-out animation
* One-direction chase effect
* 5 selectable speed presets
* Push button speed control
* Runs from 5V
* Uses a PIC12F683 with internal oscillator
* No external crystal required

## Project Concept

The goal of this project was to create a compact LED effect inspired by the **Flux Capacitor** from *Back to the Future*.

The LEDs are arranged as three arms in a **Y shape**, with **5 LEDs per arm**, giving the appearance of energy flowing through the Flux Capacitor. The chase effect and soft fades help recreate the look of the animated light movement.

## Hardware

### Microcontroller

* PIC12F683

### Controls

* 1 push button for speed selection

### Power

* 5V supply

### LED Arrangement

The physical build consists of:

* 3 LED branches
* 5 LEDs per branch
* Total: **15 LEDs**

These are arranged in a **Y configuration** to mimic the Flux Capacitor shape.

## Firmware Behaviour

The firmware creates a smooth chasing light effect with fade-in and fade-out transitions.

* LEDs animate in one direction
* Each step fades in, holds briefly, and fades out
* The push button cycles through **5 speed presets**
* Designed to give the impression of energy flowing through the Flux Capacitor arms

## Speed Control

A push button is connected to the PIC input and used to cycle between 5 preset animation speeds:

1. Very fast
2. Fast
3. Medium
4. Slow
5. Very slow

## PIC Configuration

The project uses the internal oscillator of the PIC12F683, so no external crystal is needed.

Important configuration settings:

* **Oscillator:** INTOSCIO
* **Watchdog Timer:** OFF
* **MCLR:** Disabled
* **Power-up Timer:** ON recommended
* **Code Protection:** OFF

## Tools Used

* MPLAB X IDE
* XC8 compiler
* PIC programmer (PICkit or compatible)

## Applications

This project is suitable for:

* Back to the Future props
* Decorative electronics
* Learning PIC microcontroller programming
* LED animation experiments
* Custom light effects for enclosures or display builds

## Inspiration

Inspired by the iconic **Flux Capacitor** from the *Back to the Future* films.

## Future Improvements

Possible future upgrades:

* brightness control
* sound-reactive mode
* random pulse mode
* startup animation
* larger LED arrays
* PCB version shaped like a Flux Capacitor

<img width="2160" height="1913" alt="3D_PCB2_2026-07-01_02" src="https://github.com/user-attachments/assets/69a0681b-34de-454d-8e7d-e5f13fb7fefe" />
<img width="2160" height="1945" alt="3D_PCB2_2026-07-01" src="https://github.com/user-attachments/assets/0a1cd46a-53d5-42c8-a005-ac88e0b81abf" />
