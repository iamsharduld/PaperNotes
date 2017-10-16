## My Mac Notes

TLDR; Important notes related to Mac

### [Create bootable installer for MacOS](https://support.apple.com/en-us/HT201372)
1. Download Installer: App Store downloads it to *Applications folder* as a single file with a name that begins with *Install*
2. Terminal: *createinstallmedia*
  ```
  createinstallmedia --volume [volumepath(usb)] --applicationpath [installerpath]
  sudo /Applications/Install\ OS\ X\ El\ Capitan.app/Contents/Resources/createinstallmedia --volume /Volumes/MyVolume --applicationpath /Applications/Install\ OS\ X\ El\ Capitan.app
  ```

### [How to Dualboot Mac and Windows](https://www.laptopmag.com/articles/dual-boot-windows-os-x-mac)

### [Installing Xcode, Homebrew, Git, RVM, Ruby & Rails on Mac OS X](https://www.moncefbelyamani.com/how-to-install-xcode-homebrew-git-rvm-ruby-on-mac/)

```
bash <(curl -s https://raw.githubusercontent.com/monfresh/laptop/master/laptop)
```