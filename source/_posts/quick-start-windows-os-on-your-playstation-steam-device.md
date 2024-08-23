---
title: "Quick Start: Windows OS on Your PlayStation Steam Device"
date: 2024-08-22T21:35:42.763Z
updated: 2024-08-23T21:35:42.763Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Quick Start: Windows OS on Your PlayStation Steam Device"
excerpt: "This Article Describes Quick Start: Windows OS on Your PlayStation Steam Device"
keywords: WinOS PlayStation Streaming,Quick Windows Setup PS4,Windows Launch Steam PSVR,Fast Start PC PlayStation,OS Installation PS+Gaming,Steam Play Window OS,Rapid Setup PS Vita OS
thumbnail: https://thmb.techidaily.com/29c87a2813101a91590a08620c363a707a12be2c13cdc82a6c440d60f80e5fd3.jpg
---

## Quick Start: Windows OS on Your PlayStation Steam Device

### Quick Links

* [Why You Should Install Windows on Your Steam Deck](#why-you-should-install-windows-on-your-steam-deck)
* [What You Need to Install Windows on Your Steam Deck](#what-you-need-to-install-windows-on-your-steam-deck)
* [How to Install Windows on Your Steam Deck](#how-to-install-windows-on-your-steam-deck)
* [Potential Issues and Solutions While Installing Windows on Your Steam Deck](#potential-issues-and-solutions-while-installing-windows-on-your-steam-deck)

### Key Takeaways

* Installing Windows on your Steam Deck allows you to access a familiar operating system and use the device as a work laptop or desktop replacement.
* To install Windows on your Steam Deck, you need a USB flash drive or SD card, Ventoy software, a GParted ISO, and a Windows 11 ISO.
* Follow our step-by-step guide to install Ventoy, partition your SSD, install Windows 11, and then install Windows drivers for proper functionality on your Steam Deck.

 Do you want to have a familiar operating system or Game Pass on your Steam Deck? You can dual-boot SteamOS with Windows on the device. Here’s a thorough guide on installing Windows 11 on your Steam Deck.

## Why You Should Install Windows on Your Steam Deck

![Steam Deck surrounded by peripherals](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2024/01/steam-deck-surrounded-by-peripherals.JPG)

Jhet Borja/MUO

 If you’re someone who owns a PC, the chances are very high that you’re running Windows on it. Windows is familiar to many and is fairly easy to use.

 While not having a mouse and keyboard on your Steam Deck will pose some navigation issues, having an operating system that’s familiar to you and that you know how to use might be worth that sacrifice.

 Having Windows on your Steam Deck can also make it a work laptop or desktop replacement. You can easily use Photoshop, Microsoft Office apps, Lightroom, and all the usual suspects on Windows—so long as you’re willing to bring around a mouse and keyboard. Thankfully, there are plenty of [Steam Deck accessories](https://www.makeuseof.com/essential-steam-deck-accessories/) that can make doing real work on it a breeze.

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What You Need to Install Windows on Your Steam Deck

 You only need a few things to install Windows on your Steam Deck, most of which are software. But you will need a few hardware accessories as well.

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Hardware

 For hardware, you really only need a USB flash drive and a USB-C hub to plug it into your Steam Deck. You can also [install an SD card on your Steam Deck](https://www.makeuseof.com/how-to-install-steam-deck-sd-card/) as long as it's decently fast. A USB 3.0 or higher flash drive or a UHS-I or higher SD card would suffice, but we wouldn’t suggest anything slower.

 We also highly suggest using a separate PC as we've done in this guide, but you can also use your Steam Deck and follow similar steps using the Linux version of Ventoy.

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Ventoy

 The first piece of software is Ventoy, a program that allows you to boot multiple ISOs from one external storage device without needing to format it to add a different ISO. This will avoid the back-and-forth formatting of the storage device used, making it easier to go back in case you make a mistake along the way.

![Ventoy Windows zip file from GitHub](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/ventoy-windows-zip-file-from-github.jpg)

 Head to [Ventoy’s GitHub page](https://github.com/ventoy/Ventoy/) and on the right side, click on **Releases**. Scroll down to **Assets** and click on the ZIP folder that says Windows on it. Extract the contents into a folder on your PC.

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### GNOME Partition Editor (GParted) ISO

![downloading GParted amd64 version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/downloading-gparted-amd64-version.jpg)

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
 GParted is an ISO used to create partitions on your internal SSD on your Steam Deck. The new partition will be where you’ll place the Windows installation. To download it, head to [GParted.org](https://gparted.org/download.php) and click on the **amd64.iso** download file.

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->
### Windows 11 ISO

 To put Windows onto your Steam Deck, you’ll of course need the installer. You can easily find this on [Microsoft’s Windows 11 page](https://www.microsoft.com/en-ca/software-download/windows11).

![Downloading Windows 11 ISO from Microsoft](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/downloading-windows-11-iso-from-microsoft.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
 Head to the **Download Windows 11 Disk Image (ISO)** option and on the dropdown menu, select **Windows 11 (multi-edition ISO)**. Click on **Download**, then select your language. It should then give you another download button to download the Windows ISO that is about 6GB to 7GB in size.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
### Windows Drivers for Steam Deck

![Downloading Windows Drivers for Steam Deck](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/downloading-windows-drivers-for-steam-deck.jpg)

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
 Windows doesn’t support all the Steam Deck’s hardware straight from the get-go. Fortunately, Steam has provided Windows drivers so that your audio, Wi-Fi, Bluetooth, SD card reader, and APU are all working properly.

 You can find and download the Windows drivers for your Steam Deck on the [Steam Deck Windows Resources support page](https://help.steampowered.com/en/faqs/view/6121-ECCD-D643-BAA8). Extract all of them into a single folder so that you can paste it onto your SD card or flash drive later.

## How to Install Windows on Your Steam Deck

 If you’ve got your flash drive or SD card ready with all the software downloaded, you can now start turning your Steam Deck into a Windows experience. In our case, we’ll be using an SD card so that we don’t need to deal with a USB hub or a dock.

### 1\. Install Ventoy on Your Flash Drive or SD Card

 To be able to run both the GParted and the Windows 11 ISOs from one SD card without needing to format it multiple times, you’ll need to use Ventoy. This will make things way more convenient.

![Run Ventoy2Disk from extracted folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/run-ventoy2disk-from-extracted-folder.jpg)

 To install Ventoy on your flash drive or SD card, you’ll want to plug it into your PC and open the Ventoy folder you extracted earlier. Then click on **Ventoy2Disk.exe**.

![Selected SD card to install Ventoy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/selected-sd-card-to-install-ventoy.jpg)

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
 You’ll then select the storage device you want to store Ventoy on. In our case, it’s the 32GB SD card. Click **Install**.

![Ventoy Drive with all ISOs and Windows Drivers inside](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/ventoy-drive-with-all-isos-and-windows-drivers-inside.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
 Now that Ventoy is installed, copy over GParted, the Windows 11 ISO, and a folder containing the Windows drivers for the Steam Deck. You can now insert the SD card into the Steam Deck.

### 2\. Enter the Steam Deck Boot Manager

 Next, you’ll need to boot from the SD card or flash drive you’ve connected to the Steam Deck using the device's boot manager.

![Volume down and power button to enter Steam Deck boot manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/volume-down-and-power-button-to-enter-steam-deck-boot-manager.JPG)

Jhet Borja/MUO

 To do this, shut down your Steam Deck first. Once it’s off, hold down the volume down button and power button until you hear a chime. Once you hear the chime, let go of the power button, but keep holding down the volume down button until the boot manager shows, like in the image below.

![No SteamOS option in boot manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/no-steamos-option-in-boot-manager.JPG)

Jhet Borja/MUO

 If you hold down the power button after the chime, you’ll most likely end up turning your Steam Deck off again.

 Once you’re in the boot manager, select the SD card or flash drive. This should show Ventoy and both the Windows and GParted ISOs.

### 3\. Use GParted to Partition Your Internal SSD

 You'll now need to partition your Steam Deck's SSD. If you don't, you most likely won't be able to install Windows 11 on the /home partition, and you'll also end up wiping SteamOS from your drive.

 If you want just Windows on your Steam Deck, you can also use Ventoy to wipe all partitions and either leave the combined partition as unallocated or format it as NTFS. We don't suggest this, however, as SteamOS really is the best way to experience the Steam Deck. It's better to have the option to switch between the two than be stuck with just Windows.

![GParted ISO on Ventoy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/gparted-iso-on-ventoy.JPG)

Jhet Borja/MUO

 On Ventoy, select GParted to run it. You can run it in normal mode, but if that doesn’t work, grub2 might do it.

![Enter GParted Live first option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/enter-gparted-live-first-option.JPG)

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
Jhet Borja/MUO

 Once GParted is open, you’ll be greeted with a few things before you can get to partitioning. Firstly, you’ll need to select the settings. Pick the first one—**GParted Live (Default Settings)**.

![GParted Don't touch keymap option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/gparted-don-t-touch-keymap-option.JPG)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
 Next, select **Don’t touch keymap** and then select your language. If you’re just going to use English, we suggest just pressing A on the Steam Deck until you reach the main screen.

![Selecting Steam Deck SSD in GParted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/selecting-steam-deck-ssd-in-gparted.JPG)

Jhet Borja/MUO

 Finally, you’re ready to partition your SSD. By this point, you can plug in your mouse and keyboard to make it easier to navigate. If your SD card or flash drive is the only thing you can see, switch it to your SSD on the upper right drop-down menu.

![Resizing home partition on Steam Deck SSD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/resizing-home-partition-on-steam-deck-ssd.JPG)

Jhet Borja/MUO

 To partition your SSD, right-click (left trigger) on the **/home** partition or the largest partition on the SSD. Click on **Resize/Move** and move the right wall to the left, leaving the empty space as a new unallocated partition.

 In our case, we’re leaving around 250 GB or about 250,000 MiB for Windows 11\. Click on the **Resize/Move** button on the bottom right to make your changes.

![Unallocated partition on GParted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/unallocated-partition-on-gparted.JPG)

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
Jhet Borja/MUO

 Finally, click on the **green check mark** in the toolbar. Forgetting to do this will not apply your partition changes.

 The software will then process the new partition sizes, which may take a few minutes depending on how big your SSD is. Once it’s done, you can now press the power button to exit GParted and power down.

### 4\. Windows 11 Setup on the Steam Deck

 Now you're ready to install Windows on your Steam Deck. Before you go to the boot manager though, unplug any other USB devices you used earlier except the flash drive. This prevents the ISOs or Ventoy from malfunctioning.

![Windows 11 ISO on Ventoy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-iso-on-ventoy.JPG)

Jhet Borja/MUO

 Go back to the boot manager (with the volume down button and the power button) and select the SD card or flash drive once again. With Ventoy open, this time select the Windows 11 ISO.

![I don't have a product key option during Windows 11 setup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/i-don-t-have-a-product-key-windows-11-setup.JPG)

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
Jhet Borja/MUO

 Just follow the setup by choosing the right language and keyboard layout until you reach the Windows key section. There, you can safely choose **I don’t have a product key** if you don’t have one.

![Entering partition size Windows 11 setup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/entering-partition-size-windows-11-setup.JPG)

Jhet Borja/MUO

 Proceed until you reach the **Where do you want to install Windows?** screen. You’ll want to scroll to the very bottom and click the drive that says **Unallocated space**. Next, click **New,** and it’ll automatically add the right size for you. So just click **Apply**.

 It will then start installing Windows onto that partition. Once Windows 11 is installed, you’ll have to go through another setup process.

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
### 5\. Install the Windows Drivers for the Steam Deck

 Once you’ve installed Windows, you can now install the drivers for your Steam Deck.

![Windows Drivers from Steam](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-drivers-from-steam.png)

 To do this, open up your File Explorer and click on the Ventoy drive. Open the folder we told you to place the Steam Deck drivers inside and start with any one of them.

 If you’re prompted to restart, don’t do it yet. You can restart once you’ve installed all the drivers to make it easier.

![Installing Steam Deck audio driver part 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/installing-steam-deck-audio-driver-part-1.png)

 Proceed to click on **Install** for the other drivers, but you may find that the audio drivers do not have an executable. To install the two audio drivers, simply right-click (left trigger) on the file that says **Setup information** and click **Install**.

 Once they’re all installed, you can now restart your Steam Deck. If things didn’t go so smoothly, you can refer to the section below to find your issue and the solution for it.

## Potential Issues and Solutions While Installing Windows on Your Steam Deck

 We’ve compiled a few issues that we came across during our installation and found solutions to them so that you don’t have to scour the internet to find fixes.

<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->
### ISOs Show a Black Screen or Don't Boot Up

 If the ISOs aren’t working properly, just press the power button once to exit and shut down. This is most likely due to other USB devices plugged into your Steam Deck like a keyboard and mouse. This is why we used an SD card in our installation. Remove all USB devices except your flash drive or use a USB-C flash drive if possible.

 If this doesn’t work, you may also try to delete the other ISO from the SD card or flash drive. You may also try reinstalling Ventoy as a last resort, but this will format the drive so make sure you have everything in a folder that you can easily paste onto the drive.

### The Windows 0x80300001 Error

![Selecting partition created in GParted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/selecting-partition-created-in-gparted.JPG)

Jhet Borja/MUO

 This error will most likely pop up because the partition you want to install Windows on isn’t in NTFS format or a blank unallocated partition.

![Wrong ext4 partition format for Windows on GParted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/wrong-ext4-partition-format-for-windows-on-gparted.JPG)

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
Jhet Borja/MUO

 You may have created a new partition as ext4 in GParted instead of leaving the unallocated partition as it is. If you insist on creating a new partition in GParted, make sure it’s in NTFS format and not ext4\.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
### Windows Cannot Install Drivers

![Windows cannot install required files error](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-cannot-install-required-files-error.JPG)

<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
Jhet Borja/MUO

 If you’re near the end of your Windows installation and it suddenly says it cannot install drivers, other USB devices may be interfering with the installation.

 Shut down your Steam Deck by holding down the power button and unplug any USB devices except your flash drive or SD card. Don’t plug in any USB devices during the installation to avoid this issue.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
### You Can’t Find SteamOS in the Boot Manager

![No SteamOS option in boot manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/no-steamos-option-in-boot-manager.JPG)

Jhet Borja/MUO

 If you want to go back to SteamOS and can’t find it in the boot manager, you should shut down your Steam Deck and go to the BIOS instead.

 To enter the BIOS, hold down the volume up button and the power button until you hear the chime. Let go of the power button but hold down the volume up button until you enter the BIOS.

![Selecting steamcl.efi in Steam Deck BIOS to boot into SteamOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/selecting-steamcl-efi-in-steam-deck-bios-to-boot-into-steamos.JPG)

Jhet Borja/MakeUseOf

 Once you’re in the BIOS, select **Boot from file > eps > efi > steamos > steamcl.efi**. This should boot you back into SteamOS.

 Now that you’re in SteamOS, you can put it back onto the boot manager by entering desktop mode.

![Konsole command to make SteamOS appear in boot manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/konsole-command-to-make-steamos-appear-in-boot-manager-1.JPG)

 On desktop mode, click on the Steam Deck icon on the bottom left and open Konsole. You can search for it by bringing up the keyboard by clicking on the text box and pressing on the Steam button + X.

 Then type:

`sudo efibootmgr -c -L "SteamOS" -l "\EFI\steamos\steamcl.efi" -d /dev/nvme0n1p1`

![Steam Deck user password](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/steam-deck-user-password.jpg)

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
 In case you don’t have a sudo account and can’t add the command, go to **Settings > Users** then assign a username and password. You can then try adding the same command in Konsole and adding your password after pressing Enter. It will then show your boot options.

 If you can see steamcl.efi with an asterisk next to its boot order number, it means that it’s in your boot manager now. You can verify it by shutting your Steam Deck down and entering the boot manager.

### Steam Deck Navigation and Controls on Windows

 If you’re having a hard time with the Steam Deck controls on Windows and want to use the controls like on SteamOS, download Steam and have it open.

![Enabling Steam Input for Xbox Controllers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/enabling-steam-input-for-xbox-controllers.jpg)

 Then go to **Steam > Settings > Controller > Enable Steam Input for Xbox Controllers**. You should then be able to use both trackpads like on SteamOS. You may also configure it by scrolling down and editing it on the **Non-game controller layouts**.

 The Steam Deck is a very versatile device as it’s not just a full-on gaming device, but also a full-on PC. Installing Windows on it will allow you to use it similarly to your desktop PC for regular writing work, but also for more intensive work like video and photo editing.

 We hope this guide has helped you figure out how to install Windows on your Steam Deck and fix some of the issues you might face while doing so.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-hints.techidaily.com/new-a-deep-dive-into-samsungs-picture-perfection-app/"><u>[New] A Deep Dive Into Samsung's Picture Perfection App</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-in-2024-easy-steps-for-correcting-your-tiktok-profile-age/"><u>[New] In 2024, Easy Steps for Correcting Your TikTok Profile Age</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-elevating-your-content-game-strategic-use-of-igtv-hashtags/"><u>[New] In 2024, Elevating Your Content Game  Strategic Use of IGTV Hashtags</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-save-fb-pages-with-a-click-top-8-tools-available-online-and-free/"><u>[Updated] Save FB Pages with a Click  Top 8 Tools Available Online & FREE</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-avoid-the-frustration-fast-paced-methods-to-create-captions-for-your-fb-videos/"><u>2024 Approved  Avoid the Frustration - Fast-Paced Methods to Create Captions for Your FB Videos</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-comprehensive-guide-to-streaming-and-archiving-minecraft-on-mac/"><u>2024 Approved  Comprehensive Guide to Streaming and Archiving Minecraft on Mac</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-make-everyday-banter-hilarious-text-meme-genration/"><u>2024 Approved  Make Everyday Banter Hilarious  Text Meme Gen'ration</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-solutions-to-find-your-realme-narzo-n53-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>3 Solutions to Find Your Realme Narzo N53 Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/additional-tips-about-sinnoh-stone-for-samsung-galaxy-a14-4g-drfone-by-drfone-virtual-android/"><u>Additional Tips About Sinnoh Stone For Samsung Galaxy A14 4G | Dr.fone</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/beneath-blue-waves-expert-tips-for-creating-stunning-underwater-footage-using-gopro-for-2024/"><u>Beneath Blue Waves  Expert Tips for Creating Stunning Underwater Footage Using GoPro for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/customize-your-iphone-for-different-geographic-area/"><u>Customize Your iPhone for Different Geographic Area</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-unsynchronized-file-uploads-in-chrome-win-edition/"><u>Fix Unsynchronized File Uploads in Chrome, Win Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-your-teammers-disconnected-screens/"><u>Fix Your Teammers’ Disconnected Screens</u></a></li>
<li><a href="https://extra-resources.techidaily.com/frame-finesse-selecting-superior-video-cams-for-slow-motion/"><u>Frame Finesse  Selecting Superior Video Cams for Slow Motion</u></a></li>
<li><a href="https://windows11.techidaily.com/getting-to-know-you-your-pc-unveiling-the-brand-and-model/"><u>Getting to Know You (Your PC): Unveiling the Brand and Model</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-conquering-unexplained-obs-recordings-glitches/"><u>Guide to Conquering Unexplained OBS Recordings Glitches</u></a></li>
<li><a href="https://extra-information.techidaily.com/harnessing-zoom-for-impactful-youtube-livestream-presentations/"><u>Harnessing Zoom for Impactful YouTube Livestream Presentations</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-carry-out-a-thorough-sfc-scan-in-windows/"><u>How to Carry Out a Thorough SFC Scan in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-camera-apps-0xa00f429f-error-in-windows-10-and-11/"><u>How to Fix the Camera App’s 0xA00F429F Error in Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reroute-malwarebytes-database-access-post-error/"><u>How to Reroute Malwarebytes' Database Access Post Error</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-unlock-apple-id-without-phone-number-from-iphone-12-by-drfone-ios/"><u>In 2024, Unlock Apple ID without Phone Number From iPhone 12</u></a></li>
<li><a href="https://facebook.techidaily.com/interpreting-the-subtleties-of-fb-icons-effectively/"><u>Interpreting the Subtleties of FB Icons Effectively</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-mouse-drivers-for-efficient-windows-use/"><u>Mastering Mouse Drivers for Efficient Windows Use</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-onedrive-files-on-pc-without-internet/"><u>Mastering OneDrive Files on PC without Internet</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-efficiency-with-customized-troubleshooters-shortcuts/"><u>Maximizing Efficiency with Customized Troubleshooters Shortcuts</u></a></li>
<li><a href="https://windows11.techidaily.com/outdated-pcs-needing-an-alternative-to-windows/"><u>Outdated PCs Needing an Alternative to Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-admin-controlled-feature-malfunctions-on-windows-11/"><u>Overcoming Admin Controlled Feature Malfunctions on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-obstacles-with-windows-safeguard-issues/"><u>Overcoming Obstacles with Windows Safeguard Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/personalized-scheduling-in-outlook-for-windows-enthusiasts/"><u>Personalized Scheduling in Outlook for Windows Enthusiasts</u></a></li>
<li><a href="https://sound-issues.techidaily.com/quick-solutions-fixing-google-hangouts-mic-issues-effortlessly/"><u>Quick Solutions: Fixing Google Hangouts Mic Issues Effortlessly</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-zero-error-in-the-windows-store/"><u>Remedying Zero-Error in the Windows Store</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-your-system-mastering-the-art-of-expanded-pins-in-win1011/"><u>Secure Your System: Mastering the Art of Expanded Pins in Win10/11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/solving-the-mystery-resolving-cygwin1dll-file-not-found/"><u>Solving the Mystery: Resolving 'Cygwin1.dll' File Not Found</u></a></li>
<li><a href="https://windows11.techidaily.com/speedy-windows-discord-cutting-down-latency-issues/"><u>Speedy Windows Discord: Cutting Down Latency Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/start-menu-no-more-unwanted-advertisements/"><u>Start Menu, No More Unwanted Advertisements!</u></a></li>
<li><a href="https://windows11.techidaily.com/tackle-clipchamps-windows-11-setup-obstacles-with-precision/"><u>Tackle ClipChamp's Windows 11 Setup Obstacles with Precision</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-installation-error-with-oculus-on-w11w10/"><u>Tackling Installation Error with Oculus on W11/W10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-format-rejection-by-windows-vlc/"><u>Tackling the Format Rejection by Windows-VLC</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-unfreezing-the-windows-update-troubleshooter/"><u>The Art of Unfreezing the Windows Update Troubleshooter</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-keyboard-quest-6-ways-to-find-out-your-pcs-model/"><u>The Ultimate Keyboard Quest - 6 Ways to Find Out Your PC's Model</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/the-ultimate-tutorial-setting-up-your-arduino-by-downloading-the-right-windows-drivers/"><u>The Ultimate Tutorial: Setting Up Your Arduino by Downloading the Right Windows Drivers</u></a></li>
<li><a href="https://windows11.techidaily.com/tweaking-taskbar-width-in-win11/"><u>Tweaking Taskbar Width in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-global-communication-navigating-languages-with-shortcuts-on-windows/"><u>Unlock Global Communication: Navigating Languages with Shortcuts on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-secrets-behind-windows-system-updates/"><u>Unraveling the Secrets Behind Windows System Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/what-does-microsoft-copilot-offer-programmers/"><u>What Does Microsoft Copilot Offer Programmers?</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-10-steps-to-rectify-defective-usb-hardware/"><u>Windows 10: Steps to Rectify Defective USB Hardware</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-tickout-restoring-clock-consistency/"><u>Windows Tickout: Restoring Clock Consistency</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>