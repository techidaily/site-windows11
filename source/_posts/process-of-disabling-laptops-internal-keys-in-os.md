---
title: Process of Disabling Laptop's Internal Keys in OS
date: 2024-08-15T15:31:17.074Z
updated: 2024-08-16T15:31:17.074Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Process of Disabling Laptop's Internal Keys in OS
excerpt: This Article Describes Process of Disabling Laptop's Internal Keys in OS
keywords: KeyDisableOS,LaptopsKeyLockout,DisableKeyOSInternal,LockKeysOSProcedure,TurnOffLaptopKeys,InternalKeysControl,OSKeyDisablingMethod
thumbnail: https://thmb.techidaily.com/38a10dded96ded9495ccb2173f240c20a69acb6b4b947c6dc175d30ce0f723b9.jpg
---

## Process of Disabling Laptop's Internal Keys in OS

 Sometimes you don't want your laptop's keyboard to take inputs. This is usually because you're plugging in an external keyboard, either because the built-in one is broken or you just want a larger typing space with a full-sized keyboard.

 However, since the keyboard is an integral part of your portable computer, disabling its primary input method is a little tricky. Here, we show you how to temporarily and permanently disable the laptop keyboard on Windows 10 and 11\.

## How to Find Your Laptop Keyboard in Device Manager

 Whether you want to disable your laptop keyboard temporarily or permanently, you will need to uninstall the input device from Device Manager.

 For this, you’ll need to identify the integrated keyboard in Device Manager. Since Device Manager will list all the recognized keyboards, including external keyboards, here’s how you can identify your laptop keyboard from the list.

 To identify the built-in keyboard in Device Manager:

1. Press **Win + R** to open **Run**.
2. Type **devmgmt.msc** and click **OK** to open Device Manager.
3. In Device Manager, expand the **Keyboards** section.  
![device manager keyboards 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/device-manager-keyboards-1.jpg)
4. Right-click on the first keyboard entry **(HID/Standard)** and select **Properties**.
5. In the **General** tab, check the **Location** section. If it says **Location 1** or **Plugged into keyboard port**, it is likely your laptop’s internal keyboard.
6. Bluetooth and USB keyboards will show **On Bluetooth Low Energy** and **On US Input Device**, respectively as its location.

 If you don't find your keyboard listed, make sure you have [set Device Manager to show hidden devices.](https://www.makeuseof.com/view-hidden-devices-in-windows/)

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## How to Disable the Laptop Keyboard Temporarily

 To disable your laptop’s keyboard temporarily:

1. Right-click on all the **HID** and **PS/2 Keyboard** entries with the **Properties Location** set to **Location 1** or **Plugged into keyboard.**  
![uninstall keyboard device device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/uninstall-keyboard-device-device-manager.jpg)
2. Next, select **Uninstall Device** from the context menu.
3. Click **Yes** to confirm the action.
4. That’s it. You have disabled your laptop’s internal keyboard successfully.

 That said, this is a temporary solution. As soon as you restart your system, Windows will look for the connected but unrecognized devices and install the necessary drivers to make them functional.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
## How to Disable Your Laptop Keyboard Permanently

![disable ps 2 port 18042prt command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/disable-ps-2-port-18042prt-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->

 If you want to disable your laptop keyboard permanently, you can disable your laptop’s built-in keyboard driver PS/2 i8042prt service using the Command Prompt. We'll use the sc command-line utility to configure the service and set its start parameter to disabled.

 To disable the laptop keyboard permanently:

1. Press the **Win key** and type **cmd** in the Windows search bar.
2. Right-click on **Command Prompt** and select **Run as Administrator**. Click **Yes** when the UAC prompt appears.
3. In the Command Prompt window, type the following command and press Enter:  
`sc config i8042prt start= disabled`
4. When the success message appears, close the Command Prompt, and restart your PC. After the restart, your laptop keyboard will stop registering any inputs.

 Note that, for this to work, you will need to uninstall your keyboard from Device Manager as shown above and restart your PC.

 If you change your mind and want to re-enable the keyboard, you can use the following command in an [elevated Command Prompt](https://www.makeuseof.com/windows-11-open-command-prompt/).

`sc config i8042prt start= auto`

 Once you see the success message, restart your PC to apply the changes.

## Disable the Built-in Keyboard Using an Incompatible Driver

 Another quirky solution to disable a built-in keyboard is to install an incompatible driver for the input device. Here's how to do it.

1. Open Device Manager and expand the **Keyboard** section.
2. Right-click on your laptop keyboard device and select **Update driver**.  
![Update the Relevant Keyboard Driver in Windows Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/5-update-the-relevant-keyboard-driver-in-windows-device-manager.jpg)
3. Select **Browse my computer for drivers**.  
![update driver search automatically for drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-search-automatically-for-drivers-device-manager.jpg)
4. Next, select **Let me pick from a list of available drivers on my computer**.  
![update driver keyboard pick from list of available drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-keyboard-pick-from-list-of-available-drivers-device-manager.jpg)
5. Uncheck the **Show compatible hardware** option.
6. Select a random manufacturer under the **Manufacturer** column.  
![install incompatible keyboard driver windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/install-incompatible-keyboard-driver0windows.jpg)
7. Click **Next**. Click **Yes** if an **Update Driver Warning** dialog appears.
8. Once installed, close Device Manager and reboot your computer.

 After the restart, your laptop keyboard will stop working. If you need to install the correct driver again to enable the keyboard, right-click on the keyboard device and select **Update driver**. Next, select **Search automatically for drivers**. Windows will look for a compatible driver and install it.

![update driver search automatically for drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-search-automatically-for-drivers-device-manager.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->

 Alternatively, select **Browse my computer for drivers** in the Update Drivers dialogue. Next, select **Let me pick from a list of available drivers on my computer**. Make sure the **Show compatible hardware** option is enabled. Select an **HID Keyboard Device** driver from the list and click **Next**.

![install compatible hardware driver keyboard device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/install-compatible-hardware-driver-keyboard-device-manager.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->

 Wait for the driver to install. Once done, reboot your computer, and the keyboard will start working again.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
## Disable Your Laptop Keyboard Permanently on Windows

 The built-in chiclet keyboard on your laptop is the primary input method available, so there is no way to disable it with a single click. Also, you wouldn’t want to disable your keyboard accidentally. If you determine your keyboard to have gone rogue and typing on its own, you can permanently disable it using the Command Prompt and Device Manager.

 That said, apart from the hardware issues, your laptop keyboard can act up for many other reasons. To fix your keyboard, check for pending driver updates, use the built-in troubleshooter, or simply disable the individual keys.

 Sometimes you don't want your laptop's keyboard to take inputs. This is usually because you're plugging in an external keyboard, either because the built-in one is broken or you just want a larger typing space with a full-sized keyboard.

 However, since the keyboard is an integral part of your portable computer, disabling its primary input method is a little tricky. Here, we show you how to temporarily and permanently disable the laptop keyboard on Windows 10 and 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-capture.techidaily.com/new-dive-deep-into-google-meet-a-free-host-and-participants-guide/"><u>[New] Dive Deep Into Google Meet  A Free Host & Participant's Guide</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-elite-7-film-downloader-apps/"><u>[New] Elite 7 Film Downloader Apps</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-premium-collection-of-animated-texts/"><u>[New] Premium Collection of Animated Texts</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-turning-viewership-into-cash-with-carminati-ajay/"><u>[New] Turning Viewership Into Cash with Carminati (Ajay)</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-ultimate-hash-tracker-list-for-major-social-media-sites-fbtwitterinsta-for-2024/"><u>[New] Ultimate Hash Tracker List for Major Social Media Sites (FB/Twitter/Insta) for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/audio-visual-verification-a-windows-users-pre-meet-checklist/"><u>Audio Visual Verification: A Windows User’s Pre-Meet Checklist</u></a></li>
<li><a href="https://article-files.techidaily.com/behind-the-scenes-the-magic-of-quantum-hdr-for-2024/"><u>Behind the Scenes  The Magic of Quantum HDR for 2024</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/break-of-dawn-greetings-a-multilingual-morning-salutation-list/"><u>Break of Dawn Greetings: A Multilingual Morning Salutation List</u></a></li>
<li><a href="https://windows11.techidaily.com/bringing-print-functionality-to-microsofts-secure-edge/"><u>Bringing Print Functionality to Microsoft's Secure Edge</u></a></li>
<li><a href="https://windows11.techidaily.com/chronicle-of-windows-seven-enduring-traits-in-the-new-era-of-11/"><u>Chronicle of Windows: Seven Enduring Traits in the New Era of 11</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-windows-index-settings/"><u>Configuring Windows Index Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-the-perfect-keys-list-for-win11s-narrator-control/"><u>Crafting the Perfect Keys List for Win11's Narrator Control</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-prevalent-anydesk-errors-in-windows/"><u>Decoding Prevalent AnyDesk Errors in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/easing-windows-woes-with-adobe-ps/"><u>Easing Windows Woes with Adobe PS</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-routes-to-printer-control-in-windows-11-max-50-chars/"><u>Efficient Routes to Printer Control in Windows 11 (Max 50 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-usb-resources-on-pcs/"><u>Enhancing USB Resources on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/escape-without-errors-tips-for-a-well-functioning-key-on-windows/"><u>Escape Without Errors: Tips for a Well-Functioning Key on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/hidden-panels-revealed-recovering-offscreen-windows-in-edges-os/"><u>Hidden Panels Revealed: Recovering Offscreen Windows in Edges OS</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-open-the-internet-options-in-windows-11/"><u>How to Open the Internet Options in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-stop-recurring-disk-full-issues-in-windows/"><u>How to Stop Recurring Disk Full Issues in Windows</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-navigating-the-world-of-gopro-timelapses-efficiently/"><u>In 2024, Navigating the World of GoPro Timelapses Efficiently</u></a></li>
<li><a href="https://windows11.techidaily.com/keep-your-data-and-save-space-win11s-secure-drive-management-methods-max-156-chars/"><u>Keep Your Data and Save Space: Win11's Secure Drive Management Methods (Max 156 Chars)</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/navigating-youtube-shorts-thumbnail-losses/"><u>Navigating YouTube Shorts Thumbnail Losses</u></a></li>
<li><a href="https://fix-guide.techidaily.com/nokia-g22-not-receiving-texts-10-hassle-free-solutions-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Nokia G22 Not Receiving Texts? 10 Hassle-Free Solutions Here | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-recurring-edge-shortcut-installations/"><u>Preventing Recurring Edge Shortcut Installations</u></a></li>
<li><a href="https://windows11.techidaily.com/re-establishing-malwarebytes-service-connections-in-win-oses/"><u>Re-Establishing Malwarebytes' Service Connections in Win OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/removing-geforce-graphical-overlay-feature/"><u>Removing GeForce Graphical Overlay Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/revealing-concealed-elements-a-guide-to-windows-11-ui/"><u>Revealing Concealed Elements: A Guide to Windows 11 UI</u></a></li>
<li><a href="https://windows11.techidaily.com/sling-verification-sluggishness-top-strategies-for-speedy-updates/"><u>Sling Verification Sluggishness: Top Strategies for Speedy Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-eliminating-nvidias-visual-boost/"><u>Step-by-Step: Eliminating NVIDIA's Visual Boost</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/the-most-useful-tips-for-pokemon-go-ultra-league-on-poco-x5-drfone-by-drfone-virtual-android/"><u>The Most Useful Tips for Pokemon Go Ultra League On Poco X5 | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/the-premier-nintendo-switch-cartridge-holsters-of-2024/"><u>The Premier Nintendo Switch Cartridge Holsters of 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-photo-resizing-on-windows-11-6-steps/"><u>The Ultimate Guide to Photo Resizing on Windows 11 – 6 Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-reboot-mastery-conducting-a-pure-boot/"><u>Windows 11 Reboot Mastery: Conducting a Pure Boot</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-unveiled-the-backup-and-sync-technological-advancements/"><u>Windows 11 Unveiled: The Backup & Sync Technological Advancements</u></a></li>
</ul></div>
