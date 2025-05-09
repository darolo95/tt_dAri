<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

Wokwi project on D-flipflops ring to display "dAri" on 7seg display

## How to test

These are the inputs:

| In  | Signal | Function                           |
|-----|--------|------------------------------------|
| SW1 | `IN0`  | **Run**: Off = Reset; On = Run     |
| SW2 | `IN1`  | (Unused)                           |
| SW3 | `IN2`  | `state_init[0]`; Normally ON       |
| SW4 | `IN3`  | `state_init[1]`; Normally off      |
| SW5 | `IN4`  | `state_init[2]`; Normally off      |
| SW6 | `IN5`  | `state_init[3]`; Normally off      |
| SW7 | `IN6`  | (Unused)                           |
| SW8 | `IN7`  | **Blink control**: On = no blink   |

## External hardware

List external hardware used in your project (e.g. PMOD, LED display, etc), if any
