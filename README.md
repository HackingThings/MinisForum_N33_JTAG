# MinisForum_N33_JTAG

Required items:
1. A MinisForum N33 Mini PC - purchase link : https://www.amazon.com/gp/product/B0851W2D8R
2. BIOS SPI Programmer with 1.8v support , for example: https://www.amazon.com/dp/B07VNVVXW6
3. USB DCI capable cable , DIY or DataPro , for example https://www.datapro.net/products/usb-3-0-super-speed-a-a-debugging-cable.html
4. A host computer that is Intel 6th generation and above (for built-in DCI support)
5. Intel system studio, contains intel DAL and OpenIPC. (https://dynamicinstaller.intel.com/system-studio/)

File descriptioks:
- GOLD_SPI_Image_dci_and_cpu_debug_enabled.bin - Flash & Go , DCI and CPU debug have been enabled and the image is ready to go, just flash, boot into windows and start exploring.
- GOLD_SPI_Image_PT_PoC_Enabled.bin - a test image with Positive Technology TXE PoC exploit, setting the ME debug on and remains in a dead loop, for the more daring research.

