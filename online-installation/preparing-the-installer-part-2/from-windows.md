---
description: We'll use MakeInstall in gibMacOS folder.
---

# From Windows

1. Now, run MakeInstall.bat inside the gibMacOS folder.
2. Your USB should appear. Enter the number in front of your usb USB and press Enter.
3. It will format your USB. After that, drag and drop the downloaded macOS folder \(`gibMacOS/macOS Downloads/publicrelease/xxx-xxxxx - xx.xx.x macOS xxxx`\) to the cmd window and press enter.
4. It will start to extract the resources and restore them to your USB drive. This will take some time depending your USB speed. Be patient \(again\)!
5. After restoring the resources, the script will automatically install Clover \(boot-loader\) to your USB.
6. **AMD Users, skip this step.** By the time you are restoring the resources, go to this [site](https://hackintosh.gitbook.io/-r-hackintosh-vanilla-desktop-guide/config.plist-basics) and find the sample config file for your cpu architecture at the bottom of the config explanation. Download it.
7. Once finish, you should be able to see a new partition called `CLOVER` is mounted. Go into `CLOVER/EFI/CLOVER` . Replace the original one with the downloaded sample config.plist \(AMD Users: Use the one inside the Zen or 15H:16H folder\).
