---
title: Install Specter-Desktop
---


#### Download
Grab the latest release of the `Specter-Desktop` app:  
<https://github.com/cryptoadvance/specter-desktop/releases>

For Windows the installer is `specter_desktop_setup.exe` and for MacOS it is `SpecterDesktop-v0.x.x.dmg` (where `x.x` represent the current version number).

#### Connect Specter-Desktop to Your Bitcoin Core Node
If your node is run on the same computer as Specter, Specter will likely be able to automatically detect authentication info from a `.cookie` file that bitcoin core created on your computer.

TODO: add screenshot.

#### Connect Specter-Desktop to your external HDD/SSD 
Note that if you are using an external HDD or SSD for bitcoin core blockchain data, Specter-Desktop may not automatically find it. 
Set this in Specter configuration to point to your external drive bitcoin folder. 


{% include next_steps.md next_url="/setup-wallets" next_name="Setup Hardware Wallets" %}
