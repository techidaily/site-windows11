---
title: Process of Disabling Laptop's Internal Keys in OS
date: 2024-06-25T12:38:51.002Z
updated: 2024-06-26T12:38:51.002Z
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

## How to Disable the Laptop Keyboard Temporarily

 To disable your laptop’s keyboard temporarily:

1. Right-click on all the **HID** and **PS/2 Keyboard** entries with the **Properties Location** set to **Location 1** or **Plugged into keyboard.**  
![uninstall keyboard device device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/uninstall-keyboard-device-device-manager.jpg)
2. Next, select **Uninstall Device** from the context menu.
3. Click **Yes** to confirm the action.
4. That’s it. You have disabled your laptop’s internal keyboard successfully.

 That said, this is a temporary solution. As soon as you restart your system, Windows will look for the connected but unrecognized devices and install the necessary drivers to make them functional.

## How to Disable Your Laptop Keyboard Permanently

![disable ps 2 port 18042prt command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/disable-ps-2-port-18042prt-command-prompt.jpg)

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

 Alternatively, select **Browse my computer for drivers** in the Update Drivers dialogue. Next, select **Let me pick from a list of available drivers on my computer**. Make sure the **Show compatible hardware** option is enabled. Select an **HID Keyboard Device** driver from the list and click **Next**.

![install compatible hardware driver keyboard device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/install-compatible-hardware-driver-keyboard-device-manager.jpg)

 Wait for the driver to install. Once done, reboot your computer, and the keyboard will start working again.

## Disable Your Laptop Keyboard Permanently on Windows

 The built-in chiclet keyboard on your laptop is the primary input method available, so there is no way to disable it with a single click. Also, you wouldn’t want to disable your keyboard accidentally. If you determine your keyboard to have gone rogue and typing on its own, you can permanently disable it using the Command Prompt and Device Manager.

 That said, apart from the hardware issues, your laptop keyboard can act up for many other reasons. To fix your keyboard, check for pending driver updates, use the built-in troubleshooter, or simply disable the individual keys.

 Sometimes you don't want your laptop's keyboard to take inputs. This is usually because you're plugging in an external keyboard, either because the built-in one is broken or you just want a larger typing space with a full-sized keyboard.

 However, since the keyboard is an integral part of your portable computer, disabling its primary input method is a little tricky. Here, we show you how to temporarily and permanently disable the laptop keyboard on Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-11-eliminating-invisible-logins/"><u>Troubleshooting Windows 11: Eliminating Invisible Logins</u></a></li>
<li><a href="https://windows11.techidaily.com/system-saviors-the-10-best-windows-diagnostic-apps/"><u>System Saviors: The 10 Best Windows Diagnostic Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/effortlessly-upgrading-windows-11-in-place/"><u>Effortlessly Upgrading Windows 11 in Place</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-linguistic-landscapes-smoothly-via-keyboard-shortcuts-in-win1011/"><u>Navigate Linguistic Landscapes Smoothly via Keyboard Shortcuts in Win10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-intellij-unison-not-working-a-guide-for-users-of-windows-11/"><u>Fixing IntelliJ Unison Not Working: A Guide for Users of Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-powertoys-navigating-globally-peering-deeply/"><u>Mastering PowerToys: Navigating Globally, Peering Deeply</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-guide-syncing-with-apples-calendar-app/"><u>Windows 11 Guide: Syncing with Apple's Calendar App</u></a></li>
<li><a href="https://windows11.techidaily.com/from-handheneld-to-hardware-android-titles-on-windows-via-google-service/"><u>From Handheneld to Hardware: Android Titles on Windows via Google Service</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-cause-of-display-driver-non-startups/"><u>Deciphering the Cause of Display Driver Non-Startups</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-the-essential-guide-to-scraping-social-footage-facebook-videos/"><u>2024 Approved  The Essential Guide to Scraping Social Footage  Facebook Videos</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-easy-guide-online-tools-to-save-your-youtube-videos-for-2024/"><u>[Updated] Easy Guide  Online Tools to Save Your YouTube Videos for 2024</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/the-top-ogg-conversion-software-our-expert-takeaways-for-2024/"><u>The Top OGG Conversion Software Our Expert Takeaways for 2024</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/how-to-create-loop-videos-with-filmora-for-2024/"><u>How to Create Loop Videos with Filmora for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/catch-or-beat-sleeping-snorlax-on-pokemon-go-for-oppo-reno-9a-drfone-by-drfone-virtual-android/"><u>Catch or Beat Sleeping Snorlax on Pokemon Go For Oppo Reno 9A | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-how-to-set-a-viral-song-as-your-phones-personal-melody/"><u>In 2024, How To Set a Viral Song as Your Phone's Personal Melody</u></a></li>
<li><a href="https://howto.techidaily.com/9-quick-fixes-to-unfortunately-touchwiz-has-stopped-of-realme-narzo-60-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Quick Fixes to Unfortunately TouchWiz has stopped Of Realme Narzo 60 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-maximizing-engagement-a-pathway-to-higher-subscriber-numbers/"><u>In 2024, Maximizing Engagement  A Pathway to Higher Subscriber Numbers</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-unlocking-creativity-incorinasive-use-of-luts-in-video-editing/"><u>In 2024, Unlocking Creativity  Incorinasive Use of LUTs in Video Editing</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-10-free-location-spoofers-to-fake-gps-location-on-your-oppo-find-n3-drfone-by-drfone-virtual/"><u>In 2024, 10 Free Location Spoofers to Fake GPS Location on your Oppo Find N3 | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>