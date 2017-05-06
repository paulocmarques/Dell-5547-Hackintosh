macOS Sierra for Dell 5547 (i7)
-------------------------------

This is a working set of kexts and configurations for running macOS Sierra on an Dell 5547 (i7) laptop.
With Dell 5547 (i5) you can use just replace new "SSDT-PNLF.aml" with tutorial below. 

**Status**
 - Current version: macOS Sierra 10.12.4
 - Bootloader: Clover EFI
 - Working: CPU steps, sleep, audio, multitouch, FN keys, USB...
 - Not working: wifi, bluetooth, amd graphic, ...

**How to install macOS Sierra on Dell Inspiron 15 5000 series (5547)**

    https://www.youtube.com/playlist?list=PLvhWzoZfS-8r6Yi5sOGv7wpMo71yQ-Uk2

But I have change some thing and added.

**How to install** 
Option 1: Follow the instructions in the video list above.
Option 2: Follow steps below:

> 
 1. Create macOS Sierra bootable USB and install macOS Sierra (Video 1, 2).
 2. After the step install clover to **mac driver** on video 2, you just replace CLOVER folder by my CLOVER folder I included.
 3. Intall kexts in kexts folder by using Kext Utility.app in tools. (Rebuild cache kext after install).
 4. Reboot and see the result.


----------
Sorry for my poor English.

 