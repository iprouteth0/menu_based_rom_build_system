# easy_rom_builder by iprouteth0
Menu based system for building a11 ROMs..  WIP

Simply clone this repo and run the following script to start.  There are currently only two devices, but new devices will be added in the future.

If you have not already done so, install git.

```
sudo apt-get update ; sudo apt-get install -y git
```

```
mkdir ~/android/ ; cd ~/android/
git clone https://github.com/iprouteth0/easy_rom_builder.git
cd easy_rom_builder/
. RomMenu.sh
```

A menu option for adding additional devices is now available in the device menu.  There may be some odditiy in behavior until I've refined this additional option.  In the mean time, feel free to use the option.  Just remember you will need to add your own sources script using this naming convention: codename-clone_sources.sh.  All device/vendor/kernel trees should be cloned from within that sub-script.  Also any changes needed to adapt device trees to ROM source should be done here as well.  Please see my ginna and olivewood examples for this.

Devices current included in the script
- [x] Motorola E 2020
- [x] Xiaomi 8a Dual
- [ ] Samsung Galaxy S10+ series (WIP)

Huge thanks go to my mentor @PizzaG who I worked on the origin scripts to this project with.
