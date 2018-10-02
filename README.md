![Boot Manager](./src/assets/banner.jpg)

# Boot Manager

**Boot Manager** – Boot Manager is a handy utility to make it easier to reboot into your Boot Camp
windows drive, or even another macOS install. It will also not permanently change your startup disk
so once you reboot again, it’ll boot back to your standard OS. Choose to boot windows or another OS,
no more waiting around holding the option key. Great for bluetooth keyboard users where option key
might not always work.

Boot Manager is especially useful for people who use non-EFI graphics cards and therefore have
lost access to the startup manager when starting up their Mac.

## Features
### Quick Reboot
Quickly reboot into Windows or alternate macOS drives, no holding of option key or startup disk changing.

### Universal Compatibility
Enable menu bar only and have quick access to rebooting to your other operating systems.

### Reboot Helper
No more entering your password to reboot, authorize Boot Manager once and then be able to reboot quickly.

### Boot Camp on PCI-e SSD and SATA Controllers
Support for Boot Camp in EFI mode on PCI-e SSDs and SATA PCI-e controllers.

## Installing
1. Before installing you must disable the System Integrity Protection (a.k.a. SIP).

To disable the System Integrity Protection, you must restart on the recovery partition (Recovery HD) and
access the terminal in the Utilities menu and then execute the following command:

```
csrutil disable
```

2. Then go to the Releases section of the Boot Manager repository and download the latest installation
package, and install it normally by double-clicking on it.

## Copyright
- Copyright (c) 2017-2018 [Abdy Franco](http://abdyfran.co/)
- Copyright (c) 2013-2014 [Buttered Cat Software](http://buttered-cat.com)
