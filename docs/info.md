<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This demo module implements an 8-bit adder. It takes an 8-bit value from the dedicated inputs (`ui_in`) and adds it to the 8-bit bidirectional input bus (`uio_in`), driving the resulting 8-bit sum onto the dedicated outputs (`uo_out`).

## How to test

Drive an 8-bit value onto `ui_in` and another 8-bit value onto `uio_in`. Observe that `uo_out` reflects `ui_in + uio_in`.

## External hardware

None.
