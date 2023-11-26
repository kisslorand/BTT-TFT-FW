This is a bootloader patcher for the MKSTFT28EVO. It is only suitable for TFTs with GD32F305VCT6 MCU.
Do not use on any other TFT !!!

This patcher uploads a bootloader that changes following:
 - no more need for the "mks_font", "mks_pic" folders and "mks_config.txt" file for the FW update to be executed
 - FW update doesn't erase the SPI flash anymore, no need to update fonts, icons and config at every FW update
 - replaces the annoying long "beep" at boot with a short "chirp"

Usage:
Put it on the SD card as any other regular FW file and boot your printer with the SD inserted.
During the update you'll see a red dot and a progress bar. The progress bar will let you know when the upload of the patched bootloader is finished. Also, at the end of the patched bootloader flash procedure the red dot will change into a blinking green dot. That's when you can eject the SD card and copy to it your favorite FW file to be flashed over this bootloader patcher FW, reinsert the SD Card into the TFT and reboot it.

Attention!!! This is not a functional FW, it's only for uploading the patched bootloader, you must reupload your regular favorite FW after the bootloader patching FW has done its job.

Enjoy!

Yours truly
@kisslorand
