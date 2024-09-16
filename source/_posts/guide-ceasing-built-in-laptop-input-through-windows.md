---
title: "Guide: Ceasing Built-In Laptop Input Through Windows"
date: 2024-09-10T19:52:43.207Z
updated: 2024-09-15T16:22:16.133Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Guide: Ceasing Built-In Laptop Input Through Windows"
excerpt: "This Article Describes Guide: Ceasing Built-In Laptop Input Through Windows"
keywords: Built-In Laptop Input Guide,Disabling Windows Keyboard,Keyboard Removal Windows Steps,Removing Laptop Touchpad,Navigate without Laptop Keys,Touchpad Disable in Win OS,Eliminating Built-In Laptop Inputs
thumbnail: https://thmb.techidaily.com/333b95c20ee75bfb354881848c952d7c6576f1601ed8967bdbaf6f2fda50fa89.jpg
---

## Guide: Ceasing Built-In Laptop Input Through Windows

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

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2005183/22899" target="_top" id="2005183">
  <img src="//a.impactradius-go.com/display-ad/22899-2005183" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2005183/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<span id="1983471">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983471.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983471">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983471.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983471%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983471/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

8. Once installed, close Device Manager and reboot your computer.

 After the restart, your laptop keyboard will stop working. If you need to install the correct driver again to enable the keyboard, right-click on the keyboard device and select **Update driver**. Next, select **Search automatically for drivers**. Windows will look for a compatible driver and install it.

![update driver search automatically for drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-search-automatically-for-drivers-device-manager.jpg)

 Alternatively, select **Browse my computer for drivers** in the Update Drivers dialogue. Next, select **Let me pick from a list of available drivers on my computer**. Make sure the **Show compatible hardware** option is enabled. Select an **HID Keyboard Device** driver from the list and click **Next**.

![install compatible hardware driver keyboard device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/install-compatible-hardware-driver-keyboard-device-manager.jpg)

 Wait for the driver to install. Once done, reboot your computer, and the keyboard will start working again.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137209/26400" target="_top" id="2137209">
  <img src="//a.impactradius-go.com/display-ad/26400-2137209" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137209/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://extra-information.techidaily.com/new-behind-stock-image-memes-stories-that-stood-the-test/"><u>[New] Behind Stock Image Memes Stories That Stood the Test</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-excellent-cameras-facing-panel-first-choice/"><u>[New] Excellent Cameras Facing Panel First Choice</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-the-ultimate-skype-recorder-guide/"><u>[Updated] 2024 Approved The Ultimate Skype Recorder Guide</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-cost-effective-streaming-on-low-cost-pcs/"><u>[Updated] Cost-Effective Streaming on Low-Cost PCs</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-photographic-prowess-proven-strategies-for-captivating-edits/"><u>2024 Approved Photographic Prowess Proven Strategies for Captivating Edits</u></a></li>
<li><a href="https://tech-revival.techidaily.com/clarification-needed-why-you-wont-find-an-authentic-chatgpt-application-for-your-pc-it-could-be-a-scam/"><u>Clarification Needed: Why You Won't Find an Authentic ChatGPT Application for Your PC – It Could Be a Scam!</u></a></li>
<li><a href="https://blog-min.techidaily.com/easiest-guide-how-to-clone-oppo-reno-11f-5g-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Easiest Guide How to Clone Oppo Reno 11F 5G Phone? | Dr.fone</u></a></li>
<li><a href="https://win-able.techidaily.com/enhancements-complete-solving-frame-rate-drops-and-stuttering-in-assassins-creed-valhalla-pc/"><u>Enhancements Complete: Solving Frame Rate Drops & Stuttering in Assassin's Creed Valhalla (PC)</u></a></li>
<li><a href="https://windows11.techidaily.com/hdd-or-ssd-windows-methods-to-identify-storage-disks/"><u>HDD or SSD? Windows Methods to Identify Storage Disks</u></a></li>
<li><a href="https://windows11.techidaily.com/innovative-finger-movements-win11-keybindings-unveiled/"><u>Innovative Finger Movements: Win11 Keybindings Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/key-insights-into-microsoft-family-safety-usage/"><u>Key Insights Into Microsoft Family Safety Usage</u></a></li>
<li><a href="https://windows11.techidaily.com/keyboardmouse-wake-issues-in-windows-11/"><u>Keyboard/Mouse Wake Issues in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/master-your-words-real-time-speech-to-text-with-whisper/"><u>Master Your Words: Real-Time Speech-to-Text with Whisper</u></a></li>
<li><a href="https://windows11.techidaily.com/regaining-lost-plans-windows-11-power-reset/"><u>Regaining Lost Plans: Windows 11 Power Reset</u></a></li>
<li><a href="https://windows11.techidaily.com/simplify-your-routine-nircmds-command-shortcuts-expertise/"><u>Simplify Your Routine: NirCmd's Command Shortcuts Expertise</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/subtitled-freely-top-10-tools-for-youtubes-text-extractors-for-2024/"><u>Subtitled Freely Top 10 Tools for YouTube's Text Extractors for 2024</u></a></li>
</ul></div>

