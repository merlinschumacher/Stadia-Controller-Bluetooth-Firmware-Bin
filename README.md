# Stadia Controller Bluetooth Firmware Files
The binary files for the Stadia Controller Bluetooth firmware

The update process in Chrome on [stadia.com/controller](https://stadia.com/controller) loads the files in the following order:

1. restricted_ivt_flashloader.bin (https://stadia.google.com/controller/data/restricted_ivt_flashloader.bin)
2. flashloader_fcb_get_vendor_id.bin (https://stadia.google.com/controller/data/flashloader_fcb_get_vendor_id.bin)
3. bruce_pvt_a_prod_signed.bin (https://stadia.google.com/controller/data/bruce_pvt_a_prod_signed.bin)

The controller needs to have a charge of at least 10%.
Holding "..." and powering the Controller up seems to enable a firmware update mode.
Pressing "...", "Google Assistant", "Y" and "A" triggers some kind of unlock mode.
