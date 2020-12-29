# PrusaSlicer_Anet_A8_Config

PrusaSlicer 2.3 config for Anet A8 with Marlin firmware.

Largely follows the recommendations of Thomas Sanladerer here: https://toms3d.org/2020/12/28/prusaslicer-2-3/

Only difference is first layer height 0.35 mm and 200% first layer extrusion width, as that appeared to make prints stick better on my glass-bed equipped Anet A8.

Used on the following Anet A8 config:
* Glass bed
* Various self-printed improvements (braces, belt stiffeners etc.)
* Bed re-wired/resoldered for safety
* Flashed with Marlin (exactly this config: https://github.com/skohlbr/Marlin/commits/sk_anet_a8_pull_upstream_adjusted_acc_jerk)

So should work for stock Anet A8 just fine. Only created a PLA config, as I don't user other filament types at the moment.



Created on Ubuntu 18.04 with PrusaSlicer 2.3.0-rc2+linux-x64.



