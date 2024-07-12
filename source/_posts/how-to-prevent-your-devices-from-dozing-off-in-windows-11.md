---
title: How to Prevent Your Devices From Dozing Off in Windows 11
date: 2024-07-11T21:17:14.428Z
updated: 2024-07-12T21:17:14.428Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Prevent Your Devices From Dozing Off in Windows 11
excerpt: This Article Describes How to Prevent Your Devices From Dozing Off in Windows 11
keywords: Wake Windows Devices,Prevent Device Sleep,Stay Awake PCs,Keep Windows Active,Stop PC Idle Time,Avoid System Slumber,Alert Windows Mode
thumbnail: https://thmb.techidaily.com/0b6ddfcc355a034bc5a8feec71361dd4191fefb9c46706aa01bde874e33ab2b8.jpeg
---

## How to Prevent Your Devices From Dozing Off in Windows 11

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
<li><a href="https://windows11.techidaily.com/streamlining-security-refreshing-windows-group-policies/"><u>Streamlining Security: Refreshing Windows Group Policies</u></a></li>
<li><a href="https://windows11.techidaily.com/automating-agendas-integrating-ifttt-with-to-do/"><u>Automating Agendas: Integrating IFTTT with To-Do</u></a></li>
<li><a href="https://windows11.techidaily.com/what-is-the-windows-portable-executable-file-format/"><u>What Is the Windows Portable Executable File Format?</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-from-click-to-convert-a-guide-to-effective-social-media-sales-techniques/"><u>In 2024, From Click to Convert  A Guide to Effective Social Media Sales Techniques</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-direct-download-and-conversion-best-youtube-to-mp3-software/"><u>[Updated] 2024 Approved  Direct Download & Conversion  Best YouTube to MP3 Software</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/the-art-of-decibel-decline-uncovering-sound-management-with-audacity/"><u>The Art of Decibel Decline Uncovering Sound Management with Audacity</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-non-persistent-print-device-selection/"><u>Troubleshooting: Non-Persistent Print Device Selection</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-beyond-illusory-boundaries-understanding-the-spectrum-vr-ar-and-mr/"><u>2024 Approved  Beyond Illusory Boundaries  Understanding the Spectrum (VR, AR, & MR)</u></a></li>
<li><a href="https://windows11.techidaily.com/1719373513910-reawaken-chrome-on-win11-essential-troubleshooting-steps/"><u>Reawaken Chrome on Win11 – Essential Troubleshooting Steps.</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-windows-0xfffffff-confusion-quick-fixes/"><u>Clearing Windows' 0XFFFFFFF Confusion: Quick Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-windows-task-error-0x8007000f-quickly/"><u>Correcting Windows Task Error 0X8007000F Quickly</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-uncover-vanished-watch-video-preview/"><u>2024 Approved  Uncover Vanished Watch Video Preview</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-solutions-to-the-display-startup-failure-issue/"><u>Effective Solutions to the “Display Startup Failure” Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/converting-ical-data-for-smooth-windows-11-use/"><u>Converting iCal Data for Smooth Windows 11 Use</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-insiders-guide-to-captivating-unboxing-on-ig/"><u>2024 Approved  The Insider's Guide to Captivating Unboxing on IG</u></a></li>
<li><a href="https://windows11.techidaily.com/secret-menu-additions-a-step-by-step-guide-in-win-10/"><u>Secret Menu Additions: A Step-by-Step Guide in Win 10</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-file-error-puzzle-finding-solution-for-0x80070570-on-windows-11/"><u>Decoding the File Error Puzzle - Finding Solution for 0X80070570 on Windows 11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-beyond-youtube-elite-video-sharing-hubs-revealed-for-2024/"><u>[New] Beyond YouTube  Elite Video Sharing Hubs Revealed for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-efficient-application-batch-deployment-via-winstall/"><u>Windows 11: Efficient Application Batch Deployment via Winstall</u></a></li>
<li><a href="https://windows11.techidaily.com/declutter-your-disk-space-auto-deletion-settings-for-windows-11/"><u>Declutter Your Disk Space: Auto-Deletion Settings for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-code-workflows-with-windows-11s-developer-environment/"><u>Streamlining Code Workflows with Windows 11'S Developer Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-enhancing-your-search-system/"><u>Windows 11: Enhancing Your Search System</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-an-old-pc-heres-why-you-might-want-to-ditch-windows/"><u>Reviving an Old PC? Here's Why You Might Want to Ditch Windows</u></a></li>
<li><a href="https://some-guidance.techidaily.com/superior-psd-design-transformations-for-2024/"><u>Superior PSD Design Transformations for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-microsoft-store-glitches-error-x80072f17-guide/"><u>Correcting Microsoft Store Glitches: Error X80072F17 Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-telnet-configuration-three-essential-steps-for-wins-oses/"><u>Secure Telnet Configuration: Three Essential Steps for Wins OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-setup-of-microsofts-powertoys-win11/"><u>Effortless Setup of Microsoft's PowerToys (Win11)</u></a></li>
<li><a href="https://windows11.techidaily.com/direct-access-linux-forget-wsl/"><u>Direct Access: Linux, Forget WSL</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-error-x80780119/"><u>Troubleshooting Windows' Error X80780119</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-11-free-apps-to-check-imei-on-apple-iphone-se-2022-by-drfone-ios/"><u>Top 11 Free Apps to Check IMEI on Apple iPhone SE (2022)</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-unwind-and-learn-top-relaxing-tiktok-dances/"><u>[Updated] In 2024, Unwind and Learn  Top Relaxing TikTok Dances</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-overcoming-printer-not-connected-problems/"><u>Win11: Overcoming Printer Not Connected Problems</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-prime-alert-tones-selective-websites-guide/"><u>2024 Approved  Prime Alert Tones  Selective Websites Guide</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-best-10-free-jpg-to-gif-conversion-tools/"><u>2024 Approved  Best 10 Free JPG to GIF Conversion Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/deciding-on-the-best-nvidia-driver-type/"><u>Deciding on the Best Nvidia Driver Type</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-league-of-legends-playability-on-pc/"><u>Restoring League of Legends Playability on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/best-android-apps-for-windows-computer-enthusiasts/"><u>Best Android Apps for Windows Computer Enthusiasts</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-screenshotting-windows-security-alerts/"><u>Techniques for Screenshotting Windows' Security Alerts</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-potential-the-top-7-ways-to-optimize-windows-11-use-42/"><u>Unlocking Potential: The Top 7 Ways to Optimize Windows 11 Use (42)</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-windows-update-error-0x8024800c/"><u>Tackling Windows Update: Error 0X8024800C</u></a></li>
<li><a href="https://extra-tips.techidaily.com/detailed-instruction-set-converting-any-gif-to-a-perfect-sticker-in-social-media-apps/"><u>Detailed Instruction Set  Converting Any GIF to a Perfect Sticker in Social Media Apps</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-build-your-dreamy-oriental-villas-in-minecraft/"><u>[Updated] In 2024, Build Your Dreamy Oriental Villas in Minecraft</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-c0000005-crashes-on-windows-systems/"><u>Combatting C0000005 Crashes on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-remedying-error-code-0x80300024/"><u>Understanding and Remedying Error Code: 0X80300024</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-defender-how-to-deactivate-it/"><u>Windows 11 Defender: How to Deactivate It</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-work-with-non-verified-windows-apps/"><u>Techniques to Work with Non-Verified Windows Apps</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-expert-tips-for-sharing-videos-the-ultimate-youtube-photo-poster/"><u>[Updated] Expert Tips for Sharing Videos  The Ultimate YouTube Photo Poster</u></a></li>
<li><a href="https://windows11.techidaily.com/transforming-ideas-to-art-the-leading-7-drawing-apps-for-win10-users/"><u>Transforming Ideas to Art: The Leading 7 Drawing Apps for Win10 Users</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-navigate-nearby-landscapes-on-roblox-easily/"><u>2024 Approved  Navigate Nearby Landscapes on Roblox Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/switch-onoff-windows-filter-keys-guide/"><u>Switch On/Off: Window's Filter Keys Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-variances-microsoft-account-versus-conventional-local-login/"><u>Unveiling Variances: Microsoft Account Versus Conventional Local Login</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-step-up-your-film-game-on-instagram-with-border-tips/"><u>[New] Step up Your Film Game on Instagram with Border Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/ditch-the-dated-wallpapers-triple-technique-trick/"><u>Ditch the Dated Wallpapers: Triple Technique Trick</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-how-to-reroute-your-onedrive-storage/"><u>Windows 11: How to Reroute Your OneDrive Storage</u></a></li>
<li><a href="https://windows11.techidaily.com/1719374357320-seven-big-mistakes-new-users-could-make-in-windows-11-to-avoid/"><u>Seven Big Mistakes New Users Could Make in Windows 11 - To Avoid!</u></a></li>
</ul></div>
