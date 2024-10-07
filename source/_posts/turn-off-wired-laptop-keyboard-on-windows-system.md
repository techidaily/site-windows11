---
title: Turn Off Wired Laptop Keyboard on Windows System
date: 2024-09-30T23:30:48.580Z
updated: 2024-10-07T09:16:34.980Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Turn Off Wired Laptop Keyboard on Windows System
excerpt: This Article Describes Turn Off Wired Laptop Keyboard on Windows System
keywords: Disable Win Keyboard,Turnoff PC Keys,Halt Wired Keyboard,Mute Notebook Input,Stop Windows Keyboard,Shut Down Laptop Cables,Inactive PC Keys
thumbnail: https://thmb.techidaily.com/6b1891992681f1be8b20a193547f611a2de266588bbed170087f473de1cb604a.jpg
---

## Turn Off Wired Laptop Keyboard on Windows System

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
<a href="https://aligracehair.sjv.io/c/5597632/2135374/19272" target="_top" id="2135374">
  <img src="//a.impactradius-go.com/display-ad/19272-2135374" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135374/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<span id="1983446">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983446.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983446">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983446.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983446%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983446/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Disable the Built-in Keyboard Using an Incompatible Driver

 Another quirky solution to disable a built-in keyboard is to install an incompatible driver for the input device. Here's how to do it.

1. Open Device Manager and expand the **Keyboard** section.
2. Right-click on your laptop keyboard device and select **Update driver**.  
![Update the Relevant Keyboard Driver in Windows Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/5-update-the-relevant-keyboard-driver-in-windows-device-manager.jpg)
3. Select **Browse my computer for drivers**.  
![update driver search automatically for drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-search-automatically-for-drivers-device-manager.jpg)
4. Next, select **Let me pick from a list of available drivers on my computer**.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137413/7443" target="_top" id="2137413">
  <img src="//a.impactradius-go.com/display-ad/7443-2137413" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137413/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![update driver keyboard pick from list of available drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-keyboard-pick-from-list-of-available-drivers-device-manager.jpg)
5. Uncheck the **Show compatible hardware** option.
6. Select a random manufacturer under the **Manufacturer** column.  
![install incompatible keyboard driver windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/install-incompatible-keyboard-driver0windows.jpg)
7. Click **Next**. Click **Yes** if an **Update Driver Warning** dialog appears.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134233/18498" target="_top" id="2134233">
  <img src="//a.impactradius-go.com/display-ad/18498-2134233" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134233/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-building-brand-loyalty-through-emotional-fb-video-storytelling/"><u>[Updated] 2024 Approved Building Brand Loyalty Through Emotional FB Video Storytelling</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unlocking-gopros-full-potential/"><u>2024 Approved Unlocking GoPro's Full Potential</u></a></li>
<li><a href="https://extra-hints.techidaily.com/best-companionship-through-metaverse-adventures/"><u>Best Companionship Through Metaverse Adventures</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/bypassing-the-clutter-navigating-the-switch-eshops-abundance-of-low-quality-games/"><u>Bypassing the Clutter: Navigating the Switch eShop's Abundance of Low-Quality Games</u></a></li>
<li><a href="https://windows11.techidaily.com/finding-fix-for-non-functional-vss-in-win/"><u>Finding Fix for Non-Functional VSS in Win</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-steps-for-ms-office-installation-on-windows-1011/"><u>Guiding Steps for MS Office Installation on Windows 10/11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-atandt-apple-iphone-11-pro-with-3-methods-by-drfone-ios/"><u>How to Unlock AT&T Apple iPhone 11 Pro with 3 Methods</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-pokemon-go-error-12-failed-to-detect-location-on-xiaomi-14-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Pokemon Go Error 12 Failed to Detect Location On Xiaomi 14 Pro? | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-the-updated-method-to-bypass-vivo-y02t-frp-by-drfone-android/"><u>In 2024, The Updated Method to Bypass Vivo Y02T FRP</u></a></li>
<li><a href="https://windows11.techidaily.com/overcome-task-failures-restore-windows-schedules/"><u>Overcome Task Failures, Restore Windows Schedules</u></a></li>
<li><a href="https://win-able.techidaily.com/1723009748320-overcoming-hurdles-experience-la-noire-now-on-the-personal-computers/"><u>Overcoming Hurdles? Experience L.A. Noire Now on the Personal Computers!</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-error-code-0x0001-on-nvidias-geforce-with-windows-11/"><u>Resolving Error Code 0X0001 on Nvidia's GeForce with Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-phone-integration-for-retailers-using-windows-11-and-intel-unison/"><u>Seamless Phone Integration for Retailers Using Windows 11 & Intel Unison</u></a></li>
<li><a href="https://extra-resources.techidaily.com/syncopate-scenes-adding-music-to-videos-in-the-windows-11-era/"><u>Syncopate Scenes Adding Music to Videos in the Windows 11 Era</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unleashing-funimate-on-android-step-by-step-apk-tutorial-for-2024/"><u>Unleashing Funimate on Android - Step-by-Step APK Tutorial for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-of-a-flapping-discord-overlay-on-pc/"><u>Unraveling the Mystery of a Flapping Discord Overlay on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-superiority-win11-vs-macos-facts/"><u>Unveiling the Superiority: Win11 vs MacOS Facts</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-virtual-machines-matching-windows-11-specs/"><u>Winning Virtual Machines Matching Windows 11 Specs</u></a></li>
<li><a href="https://windows11.techidaily.com/wireless-gaming-ps3-pad-to-windows-network/"><u>Wireless Gaming: PS3 Pad to Windows Network</u></a></li>
</ul></div>

