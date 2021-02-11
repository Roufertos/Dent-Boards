# Dentuino Core for SAMD21 CPU

This repository contains the source code and configuration files of the Arduino Core
for Atmel's SAMD21 processor (used on the F21).

## Installation on Arduino IDE

This core is available as a package in the Arduino IDE cores manager.
Just open the "Boards Manager" and install the package called:

"Arduino SAMD Boards (32-bit ARM Cortex-M0+)"

 1. Open the **Preferences** of the Arduino IDE.
  2. Add this URL `http://downloads.arduino.cc/Hourly/samd/package_samd-hourly-build_index.json` in the **Additional Boards Manager URLs** field, and click OK.
  3. Open the **Boards Manager** (menu Tools->Board->Board Manager...)
  4. Install **Arduino SAMD core - Hourly build**
  5. Select one of the boards under **SAMD Hourly build XX** in Tools->Board menu
  6. Compile/Upload as usual

## License and credits

This core has been developed by Arduino LLC in collaboration with Atmel.

```
  Copyright (c) 2015 Arduino LLC.  All right reserved.

  This library is free software; you can redistribute it and/or
  modify it under the terms of the GNU Lesser General Public
  License as published by the Free Software Foundation; either
  version 2.1 of the License, or (at your option) any later version.

  This library is distributed in the hope that it will be useful,
  but WITHOUT ANY WARRANTY; without even the implied warranty of
  MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
  See the GNU Lesser General Public License for more details.

  You should have received a copy of the GNU Lesser General Public
  License along with this library; if not, write to the Free Software
  Foundation, Inc., 51 Franklin St, Fifth Floor, Boston, MA  02110-1301  USA
```
