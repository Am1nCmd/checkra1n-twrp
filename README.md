<a href="https://downthecrop.xyz/"><img src="https://github.com/downthecrop/checkra1n-twrp/raw/master/app/src/main/res/mipmap-xxxhdpi/ic_launcher_cr.png" title="checkra1n TWRP" alt="checkra1n TWRP"></a>

# checkra1n TWRP

> Automate TWRP commands to launch checkra1n on arm64 Android

Copies an OpenRecoveryScript (checkra1n.zip) file to `/data/checkra1n` and a recovery command to `/cache/recovery/command` to execute checkra1n for the next launch of TWRP

tl;dr one tap checkra1n execution for Android.


<a href="https://play.google.com/store/apps/details?id=com.downthecrop.checkra1n_kotlin"><img width="192px" src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png"><br>Google Play</a>

**Requirements**

- Rooted Android device
- USB-C to USB-A Adapter
- TWRP Custom Recovery
- Supported iOS/tvOS device

## Features

- Boots to TWRP and executes checkra1n with one button
- Provides DFU Instructions in App
- Automaically reboots to Android once it detects checkra1n is complete 

### Instructions

- **Root Required**
	- Open the App
	- Allow root/su permissions
	- Tap the reboot button

## FAQ/Info

- **Why run in recovery?**
    - TWRP provides an environment with fewer services fighting over the USB controller. checkra1n relies on a highly controlled data flow over USB.
- **Will this work with all Android phones?**
	- No. If you could already do this manually in TWRP, yes definitely. My Nexus 5X (2015) and Mi Mix 3 (2018) both work.
- <a href="https://help.ifixit.com/article/108-dfu-restore" target="_blank">`DFU Instructions`</a>

- **Blog Post**
	- <a href="https://downthecrop.xyz/blog/jailbreak-ios-device-with-android-phone-checkra1n-twrp-app/">https://downthecrop.xyz/blog/jailbreak-ios-device-with-android-phone-checkra1n-twrp-app/</a>
- **Demo/Tutorial Video**
	- <a href="https://www.youtube.com/watch?v=eIRkph1XfM0">https://www.youtube.com/watch?v=eIRkph1XfM0</a>

## Installation

Just download from the Play Store. These are alternatives for FOSS heads.

- APK Installer Release: <a href="https://github.com/downthecrop/checkra1n-twrp/raw/master/app/release/app-release.apk">app-release.apk</a>
- TWRP Script Release: <a href="https://github.com/downthecrop/checkra1n-twrp/releases/latest">checkra1n-twrp-flashable.zip</a>

---

## Support

I will not respond to errors or problems on Twitter but you should still follow me. Report problems here

- Twitter at <a href="http://twitter.com/downthecrop" target="_blank">`@downthecrop`</a>
- YouTube at <a href="http://youtube.com/downthecrop" target="_blank">`@downthecrop`</a>

---

## License

- BSD Zero Clause <a href="https://github.com/downthecrop/checkra1n-twrp/blob/master/LICENSE">LICENSE</a>
- Copyright 2020 © <a href="https://downthecrop.xyz/" target="_blank">downthecrop</a>.