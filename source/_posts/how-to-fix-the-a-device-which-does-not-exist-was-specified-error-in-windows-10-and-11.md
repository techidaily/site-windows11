---
title: How to Fix the “A Device Which Does Not Exist Was Specified” Error in Windows 10 & 11
date: 2024-08-15T16:16:32.196Z
updated: 2024-08-16T16:16:32.196Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix the “A Device Which Does Not Exist Was Specified” Error in Windows 10 & 11
excerpt: This Article Describes How to Fix the “A Device Which Does Not Exist Was Specified” Error in Windows 10 & 11
keywords: Windows 10 Error Fix,Windows 11 Error Resolution,WinError Device Non-Existent,Windows DevSpecification Error,Win10 Installation Troubleshoot,Win10 & 11 FatalError Solution,Fixing Unspecified Device in WinOS
thumbnail: https://thmb.techidaily.com/3afd30f31da7656743dda52f15a6af22d0fe17904a91a11b2b12cd01fcb4a3ee.jpg
---

## How to Fix the “A Device Which Does Not Exist Was Specified” Error in Windows 10 & 11

 Many users partition their hard drives or utilize external storage devices with their PCs. However, such drives become inaccessible when the “A device which does not exist was specified” error arises. Users have reported seeing this strange error message when they try to open connected external storage devices or drive partitions inside Windows File Explorer.

 That error is most unwelcome since it means users can’t open whatever drives it arises for. Consequently, they can’t access files on affected drives. This is how you can fix the “device which does not exist was specified” error in Windows 10 and 11.

## 1\. Plug the Affected Device Into a Different USB Slot

 If this error is affecting an external storage device, try reconnecting the USB drive. There might be an issue with the port you’ve connected the drive with. Plug the USB drive into a different port to see if the same error occurs.

 If you need to resolve this error for an internal drive, check the drive’s internal connections. To do that, you’ll need to open the case for a desktop PC. Then make sure none of the drive’s connection cables are in any way loose.

## 2\. Run the SFC Tool

 Users have confirmed the System File Checker tool can resolve this drive error. That highlights system file corruption can cause this issue, which an SFC scan will likely resolve. Our guide to[running a System File Checker scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) tells you how to execute the SFC command in Windows.

![The sfc /scannow](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/sfc-scannow.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
<!-- affiliate ads end -->

## 3\. Run a Check Disk Scan for the Drive

 You might need to fix the “device which does not exist was specified” error because your drive has some bad sectors. Running a CHKDSK (Check Disk) scan command is a potential remedy for bad drive sectors. This is how you can run the Windows Check Disk tool from the Command Prompt:

1. Open the search tool by simultaneously pressing the**Windows** logo +**S** keys.
2. Enter the search phrase**cmd** inside the text box.
3. Click**Run as administrator** to start Command Prompt with elevated permissions.
4. Then execute the Check Disk scan by inputting this command:  
`chkdsk X: /f /r`  
![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/chkdsk-scan.jpg)
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->
5. Press**Enter** to initiate the scan.

 You’ll need to replace X in the above command with the actual letter of the affected drive you need to scan. For example, the command for a drive labeled D would be:

`chkdsk D: /f /r`

## 4\. Try Changing the Drive’s Letter

 Changing the affected drive’s letter is a potential fix that users have confirmed to work. You can change the drive’s letter with the Disk Management tool like this:

1. If you need to fix this issue for an external drive, connect that storage device to your PC.
2. Open Disk Management by right-clicking**Start** and selecting the shortcut for that tool.
3. Right-click the affected drive and select**Change Drive Letter and Paths** .  
![The Change Drive Letter and Paths option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-drive-letter-paths.jpg)
4. Press the**Change** button.  
![The Change Drive Letter window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-drive-letter-window.jpg)
5. Click the drop-down menu for the**Assign the following drive lette** r option.  
![The Assign the following drive letter option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/assign-the-following-drive-letter.jpg)
6. Select a drive letter that you’ve never used.
7. Click**OK** on the Change Drive Letter or Path window.
8. Select**Yes** on the Disk Management confirmation dialog.

## 5\. Rescan a Drive

 Disk Management includes a**Rescan Disk** option for troubleshooting drives. That option detects disk changes and updates drive info accordingly when selected. So, rescanning the disk is a viable troubleshooting method for resolving this “device which does not exist” error. This is how you can rescan a drive:

1. Plug the drive into your PC if necessary.
2. Bring up the Disk Management tool.
3. Click the drive for which the error occurs in Disk Management.
4. Then click the**Action** menu.  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/properties-option2.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
<!-- affiliate ads end -->
5. Select**Rescan Disks** on the menu.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Select the Full Control Option for a Drive Location

 The “device which does not exist” error can arise because of restricted drive permissions. In that scenario, users need to select a**Full control** permission option for their drives. These are the steps for selecting the**Full control** permission setting:

1. First, activate the file management tool with Explorer’s**Windows** logo +**E** hotkey.
2. Then click**This PC** in Explorer’s left sidebar.
3. Right-click the affected drive to select**Properties** .  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/properties-option2.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->
4. Click the drive’s**Security** tab.
5. If the**Full control** option isn’t ticked, click the**Edit** button.
6. Select the**Allow** box for the**Full control** option.  
![The Full control option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/full-control-checkbox.jpg)
<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Click**Apply** \>**OK** on the drive’s permissions window.

## 7\. Reinstall the Affected Drive

 If you need to fix this issue for an external storage device, try reinstalling the affected drive. Doing so will reinstall the drivers for the affected storage device. This is how you can reinstall the drive:

Insert the affected drive into one of your PC’s USB ports.

1. Click**Start** with the right mouse button to select a**Device Manager** shortcut.
2. Double-click**Disk drives** in Device Manager.
3. Right-click your drive and select**Uninstall device** .  
![The Uninstall device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/uninstall-device2.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
4. Then select the**Uninstall** option on the dialog box prompt.  
![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/uninstall-option3.jpg)
<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
5. Disconnect the drive plugged into the PC.
6. Plug the drive back into the computer to reinstall its driver.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
## 8\. Update Your Motherboard’s Chipset Driver

 It might be necessary for some users to update motherboard drivers to fix this issue. To do so manually, you’ll need the motherboard model and manufacturer details. You can check those details as follows:

1. Open the Windows search box, and type a**System Information** keyword there.
2. Click**System Information** to view that app’s window.
3. Note down the**BaseBand Product** and**BaseBand Manufacturer** details.  
![Baseboard specs in System Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/baseboard-specs.jpg)
4. [Open the Command Prompt](https://www.makeuseof.com/windows-11-open-command-prompt/) if the System Information app doesn’t include a serial number for the motherboard.
5. Execute this baseboard command:  
`wmic baseboard get product,Manufacturer,version,serialnumber`  
![The baseboard command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/baseboard-command.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Copy and paste the serial number for the motherboard shown within the Command Prompt into Notepad or another text editor.

 Then open the download section of your motherboard manufacturer’s website. Select your motherboard model and download its latest chipset driver from there. You can install the new driver for your motherboard with the downloaded driver (setup.exe) package file.

 The driver package might be included within a ZIP archive, which you’ll need to extract as outlined within this guide to[unzipping files in Windows](https://www.makeuseof.com/unzip-files-windows-10/) .

## Access Your Drive Again on Windows

 Those potential solutions will probably fix the “device which does not exist” drive error for most users. If they’re not enough, there could be an issue with your PC’s motherboard headers. In that case, consider taking your PC to a reputable repair service to resolve such an issue.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-data.techidaily.com/024-approved-navigating-best-options-expert-picks-from-top-9-free-logomakers/"><u>[New] 2024 Approved  Navigating Best Options  Expert Picks From Top 9 Free Logomakers</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/he-cinematographers-journey-shooting-top-notch-youtube-content/"><u>[New] The Cinematographer's Journey  Shooting Top-Notch YouTube Content</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-trending-tutorial-tracker-for-2024/"><u>[New] Trending Tutorial Tracker for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-2024-approved-mastering-basic-tone-alterations-in-ps/"><u>[Updated] 2024 Approved  Mastering Basic Tone Alterations in PS</u></a></li>
<li><a href="https://windows11.techidaily.com/a-clearer-path-to-organization-compact-explorer-setup/"><u>A Clearer Path to Organization: Compact Explorer Setup</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/advantages-and-disadvantages-understanding-the-pros-and-cons-of-webex/"><u>Advantages & Disadvantages: Understanding the Pros and Cons of WebEx</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-barriers-regaining-computer-management-access/"><u>Breaking Down Barriers: Regaining Computer Management Access</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-installer-glitches-on-latest-windows-versions/"><u>Combatting Installer Glitches on Latest Windows Versions</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-a-comfortable-computing-environment-configuring-active-periods-and-managing-updates-in-windows-11/"><u>Crafting a Comfortable Computing Environment: Configuring Active Periods & Managing Updates in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/debunking-myths-the-necessity-and-risks-of-pagefilesys/"><u>Debunking Myths: The Necessity and Risks of Pagefile.sys</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-fixes-for-windows-hellos-recognition-failures/"><u>Essential Fixes for Windows Hello's Recognition Failures</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-tackling-windows-11-logins/"><u>Essential Guide: Tackling Windows 11 Logins</u></a></li>
<li><a href="https://windows11.techidaily.com/five-innovative-ways-to-personalize-windows-11-search/"><u>Five Innovative Ways to Personalize Windows 11 Search</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-blue-screen-in-win11-5-methods-to-prevent-hybrid-errors/"><u>Fixing Blue Screen in Win11: 5 Methods to Prevent Hybrid Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-persistent-vscode-crashes-on-windows-11/"><u>Fixing Persistent VSCode Crashes on Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-check-distance-and-radius-on-google-maps-for-your-realme-c33-2023-drfone-by-drfone-virtual-android/"><u>How to Check Distance and Radius on Google Maps For your Realme C33 2023 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-onedrive-cloud-operation-was-unsuccessful-error-in-windows-10-and-11/"><u>How to Fix the OneDrive Cloud Operation Was Unsuccessful Error in Windows 10 & 11</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-digital-mastery-top-10-instagram-enhancers/"><u>In 2024, Digital Mastery  Top 10 Instagram Enhancers</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-itel-s23plusfrp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Itel S23+FRP Lock</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-looking-for-a-location-changer-on-vivo-v27-look-no-further-drfone-by-drfone-virtual-android/"><u>In 2024, Looking For A Location Changer On Vivo V27? Look No Further | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-luminary-megascape-ultimate-4k-integrated-hubs/"><u>In 2024, Luminary MegaScape  Ultimate 4K Integrated Hubs</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-the-magnificent-art-of-pokemon-go-streaming-on-asus-rog-phone-7-ultimate-drfone-by-drfone-virtual-android/"><u>In 2024, The Magnificent Art of Pokemon Go Streaming On Asus ROG Phone 7 Ultimate? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/keep-your-windows-control-panel-running-smoothly/"><u>Keep Your Windows Control Panel Running Smoothly</u></a></li>
<li><a href="https://buynow-info.techidaily.com/leading-online-vendors-that-specialize-in-high-quality-tv-units/"><u>Leading Online Vendors That Specialize in High-Quality TV Units</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-batch-filename-changes-with-powertoys/"><u>Mastering Batch-Filename Changes with PowerToys</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-directx-downloading-and-updating-steps/"><u>Mastering DirectX: Downloading & Updating Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-based-in-game-voice-sync-with-valorant/"><u>Mastering Windows-Based In-Game Voice Sync with Valorant</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-a-stuck-discord-interface-element-on-your-system/"><u>Mending a Stuck Discord Interface Element on Your System</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-resolve-code-0x0001-glitch-in-w10w11-setup/"><u>Methods to Resolve Code 0X0001 Glitch in W10/W11 Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/moment-by-moment-synchronize-windows-clock/"><u>Moment by Moment: Synchronize Windows Clock</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-auto-lock-settings-in-windows/"><u>Navigate Auto-Lock Settings in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/overcome-could-not-initialize-vm-error-on-pc/"><u>Overcome 'Could Not Initialize VM' Error on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-absence-of-display-on-remote-workspace-win/"><u>Overcoming Absence of Display on Remote Workspace Win</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-obstacles-inaccessible-network-router-interface/"><u>Overcoming Obstacles: Inaccessible Network Router Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-windows-1111-shop-glitch-x800704cf/"><u>Preventing Windows 11/11 Shop Glitch X800704CF</u></a></li>
<li><a href="https://windows11.techidaily.com/reimagining-taskbar-functionality-essential-upgrades-to-improve-microsofts-user-interface/"><u>Reimagining Taskbar Functionality: Essential Upgrades to Improve Microsoft's User Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/removing-the-rust-of-access-denied-in-windows/"><u>Removing the Rust of 'Access Denied' In Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-and-streamlined-drive-access-via-new-os-win11/"><u>Secure & Streamlined Drive Access via New OS (Win11)</u></a></li>
<li><a href="https://windows11.techidaily.com/sparkle-up-windows-11-for-the-festive-season/"><u>Sparkle Up Windows 11 for the Festive Season</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-re-establish-winning-online-wol-experience/"><u>Steps to Re-Establish Winning Online WoL Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-non-attached-usb-device-dilemma-in-virtualbox-environment/"><u>Tackling Non-Attached USB Device Dilemma in VirtualBox Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-spotify-connection-errors-in-win11/"><u>Tackling Spotify Connection Errors in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/take-control-of-your-workflow-learn-these-essential-cmd-commands/"><u>Take Control of Your Workflow: Learn These Essential CMD Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-windows-notepad-malfunctions/"><u>Taming Windows Notepad Malfunctions</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-tab-navigation-windows-11-enhanced-guide/"><u>The Art of Tab Navigation: Windows 11 Enhanced Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/the-path-to-professional-print-perfection-nine-key-techniques-for-powerpoint-on-pcs/"><u>The Path to Professional Print Perfection: Nine Key Techniques for PowerPoint on PCs</u></a></li>
<li><a href="https://dvd-bd.techidaily.com/transforming-mpeg-4-media-into-dvd-discs-with-ease-the-ultimate-4-step-process/"><u>Transforming MPEG-4 Media Into DVD Discs with Ease: The Ultimate 4-Step Process</u></a></li>
<li><a href="https://windows11.techidaily.com/triggering-the-verification-toolset-for-win11-systems/"><u>Triggering the Verification Toolset for Win11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-silent-reading-mode-on-ms-word-for-win-users/"><u>Troubleshooting Silent Reading Mode on MS Word for Win Users</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/turbo-transfer-efficient-youtube-listings-for-2024/"><u>Turbo Transfer  Efficient YouTube Listings for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-image-precision-with-windows-11s-blurring-feature-in-photos-app/"><u>Unlocking Image Precision with Windows 11'S Blurring Feature in Photos App</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-your-digital-contents-full-value-winning-at-powerpoint-prints-in-windows/"><u>Unlocking Your Digital Content's Full Value: Winning at PowerPoint Prints in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-and-fixing-windows-11s-error-1132-in-zoom-app/"><u>Unraveling and Fixing Windows 11'S Error 1132 in Zoom App</u></a></li>
<li><a href="https://tech-revival.techidaily.com/voice-controlled-ai-takes-the-wheel-mercedes-benz-adds-chatgpt-feature/"><u>Voice-Controlled AI Takes the Wheel: Mercedes-Benz Adds ChatGPT Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/win10s-method-for-onedrive-placement-shift/"><u>Win10's Method for OneDrive Placement Shift</u></a></li>
</ul></div>
