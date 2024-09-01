### **Bash Battery script**

Bash Battery script to fill the gap when using KDE Plasma 6 with its power management which requires to uninstall or deactivate TLP. TLP provides functions like to charge a battery of a ThinkPad to 100% and switch back to a battery preserving charging threshold of for example 80%. Without TLP one need to do this manually again.

The intention of using shell code is not to have to install another script language = less dependencies.

Available functionality:
1) Overview on battery details
2) Set the charging thresholds to max
3) Set the charging thresholds to conservative values
4) Charge the battery to max and set the charging
   thresholds to conservative values

Current limited to BAT0 = only one installed battery is supported

#### Requirements

All can be met by Linux distributions like Debian 11 or Arch Linux.

* Bash
* Battery supported by kernel

#### Parameters for the command line module

```
usage: (sudo) batt [prot] [full] [fullcharge] [help]

prot        set battery to conservative charging thresholds 
full        set battery to maximum charging thresholds
fullcharge  charge the battery once to maximum
help        show parameter overview
```
