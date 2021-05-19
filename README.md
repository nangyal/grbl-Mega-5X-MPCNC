![GitHub Logo](https://github.com/fra589/grbl-Mega-5X/blob/edge/doc/images/Mega-5X-logo.svg)

---

## GRBL-MEGA-5X-MPCNC - Arduino Mega2560 only

Platformio added\
Dual endstop\
Adjusting out-of-square endtops

Configured for MPCNC RAMPS 1.4
[MPCNC](https://www.v1engineering.com/)

Forked from [fra589/grbl-Mega-5X](https://github.com/fra589/grbl-Mega-5X)

I added Settings for adjusting out-of-square endtops from
[johnboiles/grbl-Mega-5X](https://github.com/johnboiles/grbl-Mega-5X)

---
## My board is MKS-GEN L V1.0
so in my case


### OUTPUTS
- X, Y & Z motors are in their standard place of the RAMPS shield board,
- X2: E0
- Y2: E1
   | Axis number | Default axis name | Step pin | Direction pin | Disable pin |
   | :--- | :---: | :---: | :---: | :---: |
   | axis_1 | X1 | A0 | A1 | D38 |
   | axis_2 | Y1 | A6 | A7 | A2 |
   | axis_3 | Z | D46 | D48 | A8 |
   | axis_4 | X2 | D26 | D28 | D24 |
   | axis_5 | Y2 | D36 | D34 | D30 |
   | axis_6 (4th)| A  | D49 | D51 | D53 |
- Spindle enable is on D4
- Spindle direction is on D5
- Spindle PWM is on D8
- Coolant mist is on D9
- Coolant flood is on D10
### INPUTS
- Limit switches,
   - X1 limit min: D3
   - X2 limit min: D2 (originally X limit max)
   - Y1 limit min: D14,
   - Y2 limit min: D15 (originally Y limit max),
- Probe switch or sensor is on A15,
- Reset switch (soft reset) is on A9,
- Feed hold switch is on A10,
- Cycle start switch is on A11,
- Safety door switch is on A12,

You can find pinouts etc. in [doc/Ramps1.4](https://github.com/nangyal/grbl-Mega-5X-MPCNC/tree/edge/doc/Ramps1.4)

It may help\
https://github.com/fra589/grbl-Mega-5X/wiki/Limit-switches-and-homing

https://github.com/fra589/grbl-Mega-5X/wiki/Pinout-mapping-in-cpu_map.h

