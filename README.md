# Lazy Action Recovery Builder |TWRP / PBRP / OFRP / SHRP|
Compile your first custom recovery via Github Actions - with ldcheck setup.

## How to Use
1. Fork this repository.

2. Go to `Action` tab > `All workflows` > Pick which Build you need (`TWRP or PBRP or OFRP or SHRP`) > `Run workflow`, then pick required information from each drop-down list:
 - Manifest Branch (*12.1, *11.0, *10.0, *9.0, *8.1, *7.1, *6.0, etc.)
 - Device Tree (Your device tree repository link)
 - Device Tree Branch (Your device tree repository branch)
 - Device Name (Your device codename)
 - Device Path (device/brand/codename)
 - Build Target (boot, reecovery, vendorboot)
 - LDCHECK (path to your target binary file, ie. `system/bin/qseecomd`)
   - If you are building manually/locally and you want to use ldcheck for checking dependencies, visit [THIS](https://github.com/TeamWin/android_device_qcom_twrp-common/tree/android-11#using-ldcheck-to-find-dependencies) this for guide.

## Thanks/Credits
 - [CaptainThrowback](https://github.com/CaptainThrowback)
 - [azwhikaru](https://github.com/azwhikaru)
 - [cd-Crypton](https://github.com/cd-Crypton)
 - [that1](https://github.com/that1)
 - [carlodandan](https://github.com/carlodandan)
 - And to all Contributors in every repositories and scripts I used.

---
## Copyright Notice
 ```
  /*
  *  Copyright (C) 2020-2024 The OrangeFox Recovery Project
  *
  * This program is free software: you can redistribute it and/or modify
  * it under the terms of the GNU General Public License as published by
  * the Free Software Foundation, either version 3 of the License, or
  * (at your option) any later version.
  *
  * This program is distributed in the hope that it will be useful,
  * but WITHOUT ANY WARRANTY; without even the implied warranty of
  * MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
  * GNU General Public License for more details.
  *
  * You should have received a copy of the GNU General Public License
  * along with this program.  If not, see <http://www.gnu.org/licenses/>.
  *
  */
  ```