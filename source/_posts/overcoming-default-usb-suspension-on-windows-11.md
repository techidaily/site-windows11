---
title: Overcoming Default USB Suspension on Windows 11
date: 2024-07-11T21:55:18.412Z
updated: 2024-07-12T21:55:18.412Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Default USB Suspension on Windows 11
excerpt: This Article Describes Overcoming Default USB Suspension on Windows 11
keywords: Win11 USB Suspend Fix,W11 Device Shutdown Prevention,Bypassing Windows 11 USB Sleep,Resume USB on W11,Stop Default USB Suspend W11,Overcoming USB Shutdown in Win11,Avoid USB Suspension in Windows 11
thumbnail: https://thmb.techidaily.com/13322664753ec1bcb9b951122efdf005d8bc61a3a13c44fac0ae0c8584b8720e.jpg
---

## Overcoming Default USB Suspension on Windows 11

 Windows' USB selective suspend feature puts USB devices in a low-power state when not in use. While this can enhance battery life, it may cause problems with peripherals that require constant power.

 If you encounter issues with USB devices on your Windows 11 computer, consider disabling the USB selective suspend feature. Here’s how to do so on Windows 11\.

## Why You Might Want to Disable USB Selective Suspend

 Windows has various features to [prolong your laptop's battery life](https://www.makeuseof.com/windows-11-improve-battery-life/), one of which is USB selective suspend. While this feature is great, below are a few situations where you should disable it:

* If Windows fails to recognize a USB device, try turning off USB selective suspend and check if it makes any difference.
* USB selective suspend sometimes adds a small amount of latency, especially in gaming peripherals. So, you can turn it off to get immediate and responsive input from your gaming device.
* USB selective suspend might occasionally conflict with other power management settings, potentially leading to computer instability. If you've been experiencing power-related problems, disabling USB selective suspend could help.

 Now that you know the reason, let’s check out different ways to disable USB selective suspend on Windows 11\.

## 1\. Using the Device Manager

 The Device Manager on Windows is the go-to place to manage USB devices connected to your system. You can use it to [update outdated drivers](https://www.makeuseof.com/tag/find-replace-outdated-windows-drivers/), uninstall devices, and much more. It can also help you turn off the USB selective suspend feature.

 Follow these steps to disable USB selective suspend via the Device Manager:

1. Press the **Win + X** hotkey and choose **Device Manager** from the context menu.
2. Double-click on the **Universal Serial Bus controllers** node.  
![Universal Serial Bus controllers node in the Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/universal-serial-bus-controllers-node.jpg)
3. Right-click on any **Generic USB Hub** or **USB Root Hub** drivers and choose **Properties**.  
![USB Root Hub driver in the Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/usb-root-hub.jpg)
4. Switch to the **Power** **Management** tab and uncheck the **Allow the computer to turn off this device to save power** option. Then, click **OK** to save the changes.  
![Allow the computer to turn off this device to save power option in the Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/allow-the-computer-to-turn-off-this-device-to-save-power-option.jpg)

 Now, repeat the above steps for all the USB drivers for which you want to disable USB selective suspend.

## 2\. Using the Control Panel

 The Control Panel serves as the central hub of a Windows operating system, allowing users to perform a wide range of tasks. From simple actions like [changing your desktop wallpaper](https://www.makeuseof.com/windows-11-change-desktop-wallpaper/) to more complex operations like managing user accounts, you can do it all by accessing the Control Panel.

 Follow these steps to disable USB selective suspend via the Control Panel:

1. Press the **Win** key to open the **Start** **Menu**, type **Control** **Panel** in the search bar, and press Enter.
2. Navigate to **System and Security** \> **Power** **Options** \> **Change** **plan** **settings**.
3. Click the **Change** **advanced** **power settings** option.  
![Change advanced power settings option in Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-advanced-power-settings-option.jpg)
4. Double-click on the **USB settings** option and then expand **USB selective suspend setting**.  
![USB selective suspend setting in Power Option window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/usb-selective-suspend-setting.jpg)
5. Choose **Disabled** for both the **On battery** and **Plugged in** options.  
![Disabled option in Power Option window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disabled-option.jpg)
6. Click **Apply** \> **OK** to save the changes.

 The USB selective suspend feature is now disabled. Let's look at one more way to do so.

## 3\. Using Command Prompt

 Follow these steps to disable USB selective suspend via the Command Prompt:

1. Open the Start Menu, type **Command Prompt** in the search bar, and choose **Run as administrator** from the right pane.
2. Type the following command in the elevated Command Prompt window and press Enter.  
`powercfg /SETACVALUEINDEX SCHEME_CURRENT 2a737441-1930-4402-8d77-b2bebba308a3 48e6b7a6-50f5-4782-a5d4-53bb8f07e226 0`  
![Disable USB Selective Suspend command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-usb-selective-suspend.jpg)

 And you're done! The USB selective suspend feature is now disabled on your Windows computer. If you wish, you can easily turn it back on using the same navigation as shown above.

## USB Selective Suspend Is Good, but Not Perfect

 We've taken a look at how and when to disable USB selective suspend. As mentioned earlier, it can occasionally lead to system instability, introduce latency, or even cause your computer to fail to recognize the USB device. Therefore, disabling it might be preferable when power efficiency isn't a top priority for your system.

 However, if disabling USB selective suspend doesn't resolve the issue, there are various other troubleshooting steps you can take when Windows fails to recognize a USB device.

 If you encounter issues with USB devices on your Windows 11 computer, consider disabling the USB selective suspend feature. Here’s how to do so on Windows 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/synchronize-the-seconds-windows-time-repair-guide/"><u>Synchronize the Seconds: Windows Time Repair Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/tackle-non-selectable-text-in-windows-based-pdf-documents-easily/"><u>Tackle Non-Selectable Text in Windows-Based PDF Documents Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/the-complete-guide-to-image-spin-on-your-windows-11-pc/"><u>The Complete Guide to Image Spin on Your Windows 11 PC</u></a></li>
<li><a href="https://windows11.techidaily.com/thawing-the-frozen-menus-6-windows-remedies-explored/"><u>Thawing the Frozen Menus: 6 Windows Remedies Explored</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-geforce-experience-setting-retrieval-failure-on-windows-1111/"><u>Resolving 'GeForce Experience' Setting Retrieval Failure on Windows 11/11</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-av1-and-vp9-face-off-which-succeeds-more/"><u>2024 Approved  AV1 and VP9 Face-Off  Which Succeeds More?</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-securing-spotlight-uploading-imovie-to-vimeo-successfully/"><u>[Updated] In 2024, Securing Spotlight  Uploading iMovie to Vimeo Successfully</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-start-driver-verifier-manager/"><u>Steps to Start Driver Verifier Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-system-limitations-intel-hd-graphics-compatibility-fixes/"><u>Rectifying System Limitations: Intel HD Graphics Compatibility Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-high-memory-consumption-in-edges-webview2/"><u>Tackling High Memory Consumption in Edge's WebView2</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-architecting-top-quality-canon-chrono-films/"><u>2024 Approved  Architecting Top Quality Canon Chrono Films</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-interactions-between-devices-and-pc-slumber/"><u>Navigating Interactions Between Devices and PC Slumber</u></a></li>
<li><a href="https://windows11.techidaily.com/resetting-grammarly-settings-in-windows/"><u>Resetting Grammarly Settings in Windows</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-elevate-your-youtube-presence-with-custom-animated-subscription-buttons-in-filmora/"><u>[New] 2024 Approved  Elevate Your YouTube Presence with Custom Animated Subscription Buttons in Filmora</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-breaking-boundaries-in-video-content-creation-within-limit/"><u>[Updated] Breaking Boundaries in Video Content Creation (Within Limit)</u></a></li>
<li><a href="https://windows11.techidaily.com/why-choosing-windows-11-is-a-wise-decision-over-macos/"><u>Why Choosing Windows 11 Is a Wise Decision over MacOS</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-use-pokemon-go-joystick-on-oneplus-nord-ce-3-5g-drfone-by-drfone-virtual-android/"><u>How to use Pokemon Go Joystick on OnePlus Nord CE 3 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-completely-removing-wsl-in-win-11/"><u>Step-by-Step: Completely Removing WSL in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/redirecting-to-file-explorer-from-onedrive-menu/"><u>Redirecting to File Explorer From OneDrive Menu</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-still-using-pattern-locks-with-samsung-galaxy-z-flip-5-tips-tricks-and-helpful-advice-by-drfone-android/"><u>In 2024, Still Using Pattern Locks with Samsung Galaxy Z Flip 5? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-best-virtual-background-for-google-meet/"><u>2024 Approved  Best Virtual Background for Google Meet</u></a></li>
<li><a href="https://windows11.techidaily.com/recover-lost-pin-following-system-breakdown-on-windows-11/"><u>Recover Lost PIN Following System Breakdown on Windows 11</u></a></li>
<li><a href="https://howto.techidaily.com/gmail-not-working-on-samsung-galaxy-a14-4g-7-common-problems-and-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Gmail Not Working on Samsung Galaxy A14 4G 7 Common Problems & Fixes | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/skyrocket-your-typing-swift-input-strategies-for-win-1011-users/"><u>Skyrocket Your Typing: Swift Input Strategies for WIN 10/11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/power-up-your-vms-in-windows-using-these-top-6-enhancers/"><u>Power Up Your VMs in Windows Using These Top 6 Enhancers</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-solutions-to-the-windows-too-many-requests-challenge/"><u>Swift Solutions to the Windows Too Many Requests Challenge</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-troubleshooting-excel-display-issue-in-notepad/"><u>Remedy: Troubleshooting Excel Display Issue in Notepad</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-creative-channel-themes-get-them-for-free/"><u>[Updated] In 2024, Creative Channel Themes  Get Them for Free</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-license-validity-alert-on-windows-oses/"><u>Resolving License Validity Alert on Windows OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/system-saviors-the-10-best-windows-diagnostic-apps/"><u>System Saviors: The 10 Best Windows Diagnostic Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-taskbar-transparency-in-maxed-browser-screens/"><u>Solutions for Taskbar Transparency in Maxed Browser Screens</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-q500-typhoon-yuneecs-high-resolution-bliss/"><u>[Updated] Q500 Typhoon - Yuneec's High-Resolution Bliss</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-effortless-screen-capture-on-w10-os/"><u>[Updated] Effortless Screen Capture on W10 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/the-insiders-edge-building-snaps-with-powertoys/"><u>The Insider's Edge: Building Snaps with PowerToys</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-stopping-self-activating-store-app/"><u>Strategies for Stopping Self-Activating Store App</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-windows-11-search-with-custom-settings/"><u>Optimizing Windows 11 Search with Custom Settings</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-boost-your-revenue-yielding-earnings-from-youtube-at-500-followers/"><u>[New] 2024 Approved  Boost Your Revenue  Yielding Earnings From YouTube at 500 Followers</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-sound-and-microphone-discrepancies-in-valorant/"><u>Resolving Sound and Microphone Discrepancies in Valorant</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-breaking-barriers-of-breeze-overcoming-wind-induced-disturbances-in-sound-recordings-for-2024/"><u>New Breaking Barriers of Breeze Overcoming Wind-Induced Disturbances in Sound Recordings for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-complete-tutorial-to-launch-w11s-administrator-powershell/"><u>The Complete Tutorial to Launch W11's Administrator PowerShell</u></a></li>
<li><a href="https://windows11.techidaily.com/reducing-heavy-resource-use-by-news-apps-in-windows-os/"><u>Reducing Heavy Resource Use by News Apps in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-up-oculus-rift-as-a-windows-pc-vr-setup/"><u>Setting up Oculus Rift as a Windows PC VR Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/rectify-stalling-windows-guard-mechanism-in-win-11/"><u>Rectify Stalling Windows Guard Mechanism in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-not-found-errors-on-pc-windows/"><u>Overcoming 'Not Found' Errors on PC Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/prioritize-your-data-spotting-the-biggest-disk-space-eaters/"><u>Prioritize Your Data: Spotting the Biggest Disk Space Eaters</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-selection-of-cost-free-storage-solutions-for-windows-users/"><u>The Ultimate Selection of Cost-Free Storage Solutions for Windows Users</u></a></li>
<li><a href="https://audio-editing.techidaily.com/digital-venues-for-encountering-and-bonding-with-unknown-individuals-responsibly/"><u>Digital Venues for Encountering and Bonding with Unknown Individuals Responsibly</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-nvidia-experience-connectivity-issues-on-pcs/"><u>Remedying Nvidia Experience Connectivity Issues on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/uninstalling-the-default-software-on-win11-pcs/"><u>Uninstalling the Default Software on Win11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-default-windows-preferences-post-restart/"><u>Reviving Default Windows Preferences Post-Restart</u></a></li>
</ul></div>
