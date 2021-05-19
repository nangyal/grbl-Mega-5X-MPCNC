![GitHub Logo](https://github.com/fra589/grbl-Mega-5X/blob/edge/doc/images/Mega-5X-logo.svg)

---

GRBL-MEGA-5X-MPCNC - Arduino Mega2560 only

Dual endstop
Adjusting out-of-square endtops

Configured for MPCNC RAMPS 1.4
[MPCNC](https://www.v1engineering.com/)

Forked from [fra589/grbl-Mega-5X](https://github.com/fra589/grbl-Mega-5X)

I added Settings for adjusting out-of-square endtops from
[johnboiles/grbl-Mega-5X](https://github.com/johnboiles/grbl-Mega-5X)

My board is MKS-GEN L V1.0
so in my case

the endstops are
X1 limit min: D3
X2 limit min: D2 (originaly x limit max)
Y1 limit min: D14
Y2 limit min: D15 (originaly y limit max)

Probe : A15

You can find pinouts etc. in doc/Ramps1.4 [doc/Ramps1.4](https://github.com/nangyal/grbl-Mega-5X-MPCNC/tree/edge/doc/Ramps1.4)

It may help
https://github.com/fra589/grbl-Mega-5X/wiki/Limit-switches-and-homing

https://github.com/fra589/grbl-Mega-5X/wiki/Pinout-mapping-in-cpu_map.h
