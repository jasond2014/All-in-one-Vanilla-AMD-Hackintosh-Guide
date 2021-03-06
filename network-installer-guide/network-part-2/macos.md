---
description: Installing Clover by using the installer package.
---

# From macOS

1. Rename the downloaded `XXXX.pkg` to `XXXX.dmg`
2. Double click on it and a it will mount a new volume
3. Go into the new volume and copy BaseSystem.dmg to desktop.
4. Go to disk utility. Click **View &gt; Show all devices** and find your USB **\(the whole disk instead of a partition, check out the gif below to know what I am talking\)** and format it to:  `Name:   [whatever you want] Format: Mac OS Extended (Journaled)  Scheme: GUID Partition Map`
5. Now, choose your **USB partition** click Restore button in Disk Utility and choose Image...
6. Choose BaseSystem.dmg on desktop and press Restore.
7. This should take some time depending on your USB speed.
8. Go to [Install and Configuring Clover in macOS](../../clover-installtion/usb-clover/usb-clover-macos.md) after finishing this part.

![Steps 1 - 3](../../.gitbook/assets/ezgif-4-c4f2b894d040.gif)

![Steps 4 - 7](../../.gitbook/assets/restoring-to-usb.gif)

