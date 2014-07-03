#DX50 Sound Unlocked

DX50 custom firmware. Clear detailed sound!

##INSTALL

1. Donwload [latest version](https://github.com/dm1try/dx50_sound_unlocked/raw/master/releases/dx50_sound_unlocked_1.1.0.7z)
2. Install like any other stock firmware.

##USE

### First boot
On first boot you should see "Formats" screen with two options:

-  All formats
-  FLAC/APE/DSD only (without mp3, EQ, gappless)

Firmware already has a clear detailed sound but when you choose only losless formats a soundstage would be a little bit better.

*On the next boot your last choice would be used automatically.*

###"Formats" screen
You can activate the "Formats" screen again using "Hold" switch.
Set the "Hold" switch to ON and reboot a player.

###Technical details
This firmware fully based on original 1.5.0 (**Thanks, iBasso guys!**).

Changes:

- removed android `lib/soundfx`
- used different configs for MangoPlayer(lossy/lossless) to prevent degrading sound quality for lossless formats because of using FFMPEG/EQ
- used HIGH irr bandwidth for WM8740 (can be switched)

That's all. Cheers!

[iBasso DX50 page](http://ibasso.com/en/products/show.asp?ID=81)

[iBasso Downloads](http://ibasso.com/en/download/index.asp)






