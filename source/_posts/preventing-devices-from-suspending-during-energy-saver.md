---
title: Preventing Devices From Suspending During Energy Saver
date: 2024-08-27T16:03:11.509Z
updated: 2024-08-28T16:03:11.509Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Preventing Devices From Suspending During Energy Saver
excerpt: This Article Describes Preventing Devices From Suspending During Energy Saver
keywords: Energy Saver Mode,Device Auto Suspend,Prevent Power Save,Avoid Suspension,Safe Sleep Settings,Energy Efficient Controls,Stop Device Hibernate
thumbnail: https://thmb.techidaily.com/7f531620a49852bbff7e687b5f3193b68bdfdcb0db935514f90e93325010d261.jpg
---

## Preventing Devices From Suspending During Energy Saver

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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
## 2\. Using the Control Panel

 The Control Panel serves as the central hub of a Windows operating system, allowing users to perform a wide range of tasks. From simple actions like [changing your desktop wallpaper](https://www.makeuseof.com/windows-11-change-desktop-wallpaper/) to more complex operations like managing user accounts, you can do it all by accessing the Control Panel.

 Follow these steps to disable USB selective suspend via the Control Panel:

1. Press the **Win** key to open the **Start** **Menu**, type **Control** **Panel** in the search bar, and press Enter.
2. Navigate to **System and Security** \> **Power** **Options** \> **Change** **plan** **settings**.
3. Click the **Change** **advanced** **power settings** option.  
![Change advanced power settings option in Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-advanced-power-settings-option.jpg)
4. Double-click on the **USB settings** option and then expand **USB selective suspend setting**.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
![USB selective suspend setting in Power Option window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/usb-selective-suspend-setting.jpg)
5. Choose **Disabled** for both the **On battery** and **Plugged in** options.  
<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Disabled option in Power Option window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disabled-option.jpg)
6. Click **Apply** \> **OK** to save the changes.
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The USB selective suspend feature is now disabled. Let's look at one more way to do so.

## 3\. Using Command Prompt

 Follow these steps to disable USB selective suspend via the Command Prompt:

1. Open the Start Menu, type **Command Prompt** in the search bar, and choose **Run as administrator** from the right pane.
2. Type the following command in the elevated Command Prompt window and press Enter.  
`powercfg /SETACVALUEINDEX SCHEME_CURRENT 2a737441-1930-4402-8d77-b2bebba308a3 48e6b7a6-50f5-4782-a5d4-53bb8f07e226 0`  
![Disable USB Selective Suspend command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-usb-selective-suspend.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->
 And you're done! The USB selective suspend feature is now disabled on your Windows computer. If you wish, you can easily turn it back on using the same navigation as shown above.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
## USB Selective Suspend Is Good, but Not Perfect

 We've taken a look at how and when to disable USB selective suspend. As mentioned earlier, it can occasionally lead to system instability, introduce latency, or even cause your computer to fail to recognize the USB device. Therefore, disabling it might be preferable when power efficiency isn't a top priority for your system.

 However, if disabling USB selective suspend doesn't resolve the issue, there are various other troubleshooting steps you can take when Windows fails to recognize a USB device.

 If you encounter issues with USB devices on your Windows 11 computer, consider disabling the USB selective suspend feature. Here’s how to do so on Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-http.techidaily.com/new-how-to-trim-video-in-windows-10-photos-easily/"><u>[New] How to Trim Video in Windows 10 Photos Easily</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-boost-your-post-with-three-video-border-methods/"><u>[Updated] 2024 Approved  Boost Your Post with Three Video Border Methods</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-fine-tuning-minecrafts-ram-for-better-gaming-results/"><u>[Updated] Fine-Tuning Minecraft's RAM for Better Gaming Results</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-ideal-tools-leading-mac-video-recording-programs-for-2024/"><u>[Updated] Ideal Tools  Leading Mac Video Recording Programs for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-harness-the-power-of-youtube-and-facebook-streaming-old-video-content/"><u>[Updated] In 2024, Harness the Power of YouTube & Facebook  Streaming Old Video Content</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-essential-guide-to-capturing-vr-gaming-sessions/"><u>2024 Approved  Essential Guide to Capturing VR Gaming Sessions</u></a></li>
<li><a href="https://win-forum.techidaily.com/accelerate-your-pc-booting-windows-11-faster-with-simple-tricks/"><u>Accelerate Your PC: Booting Windows 11 Faster with Simple Tricks</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/elevate-your-asmr-sessions-with-these-microphones/"><u>Elevate Your ASMR Sessions with These Microphones</u></a></li>
<li><a href="https://hardware-help.techidaily.com/enhance-your-rig-free-icue-configuration-tool-for-windows-11-and-windows-10-enthusiasts/"><u>Enhance Your Rig: Free iCUE Configuration Tool for Windows 11 and Windows 10 Enthusiasts</u></a></li>
<li><a href="https://screen-recording.techidaily.com/eyevision-recorder-ultimate-for-2024/"><u>EyeVision Recorder Ultimate for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/guaranteeing-presence-of-startup-applications/"><u>Guaranteeing Presence of Startup Applications</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-spotify-location-after-moving-to-another-country-on-oneplus-11r-drfone-by-drfone-virtual-android/"><u>How to Change Spotify Location After Moving to Another Country On OnePlus 11R | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-extracting-files-to-the-temporary-location-error-1152-in-windows-1110/"><u>How to Fix the “Extracting Files to the Temporary Location” Error 1152 in Windows 11/10</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-no-audio-output-device-is-installed-error-on-windows/"><u>How to Fix the No Audio Output Device Is Installed Error on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-hide-the-power-button-from-the-start-menu-on-windows-10-and-11/"><u>How to Hide the Power Button From the Start Menu on Windows 10 & 11</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-unlock-icloud-activation-lock-and-icloud-account-on-apple-iphone-11-by-drfone-ios/"><u>How to Unlock iCloud Activation Lock and iCloud Account On Apple iPhone 11?</u></a></li>
<li><a href="https://windows11.techidaily.com/idea-integration-with-obsidians-creative-canvas/"><u>Idea Integration with Obsidian's Creative Canvas</u></a></li>
<li><a href="https://windows11.techidaily.com/ifas-premier-laptop-showcase-the-ultimate-finds/"><u>IFA's Premier Laptop Showcase - The Ultimate Finds</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-simplified-tutorial-mastering-meets-background-blur/"><u>In 2024, Simplified Tutorial  Mastering Meet's Background Blur</u></a></li>
<li><a href="https://windows11.techidaily.com/lost-thumbnail-images-on-windows-11-a-step-by-step-resolution/"><u>Lost Thumbnail Images on Windows 11: A Step-by-Step Resolution</u></a></li>
<li><a href="https://windows11.techidaily.com/malware-softwares-impact-on-system-ram-allocation/"><u>Malware Software's Impact on System RAM Allocation</u></a></li>
<li><a href="https://windows11.techidaily.com/master-windows-11-workflow-activating-outlook-preview-app/"><u>Master Windows 11 Workflow: Activating Outlook Preview App</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-passwords-in-windows-11-the-ultimate-4-allies/"><u>Mastering Passwords in Windows 11: The Ultimate 4 Allies</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-browser-management-in-windows/"><u>Mastering the Art of Browser Management in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-repair-of-windows-hyper-v-error-0x8009030e/"><u>Mastering the Repair of Windows Hyper-V Error 0X8009030E</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-charge-readiness-notification-tips-for-win11-users/"><u>Maximizing Charge Readiness: Notification Tips for Win11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-through-windows-pen-pad-malfunctions/"><u>Navigate Through Windows Pen Pad Malfunctions</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-nvidias-failed-configuration-retrieval-in-1011-windows/"><u>Overcoming NVIDIA's Failed Configuration Retrieval in 10/11 Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/personalizing-permanent-trash-settings-in-windows-1011/"><u>Personalizing Permanent Trash Settings in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/power-up-windows-for-video-on-demand-via-dynamic-transcoding-by-tdarr/"><u>Power Up Windows for Video-on-Demand via Dynamic Transcoding by Tdarr</u></a></li>
<li><a href="https://windows11.techidaily.com/preparing-your-devices-for-a-win-11-app-transfer-transition/"><u>Preparing Your Devices for a Win 11 App Transfer Transition</u></a></li>
<li><a href="https://windows11.techidaily.com/reactivating-deactivated-rulesets-in-office-365windows-outlook/"><u>Reactivating Deactivated Rulesets in Office 365/Windows Outlook</u></a></li>
<li><a href="https://windows11.techidaily.com/record-games-like-a-pro-with-windows-and-intels-command-center/"><u>Record Games Like a Pro with Windows & Intel's Command Center</u></a></li>
<li><a href="https://windows11.techidaily.com/reignite-windows-update-success-with-this-guide/"><u>Reignite Windows Update Success With This Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-for-color-discrepanenas-of-store-interface/"><u>Remedy for Color Discrepanenas of Store Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-ease-capped-chatgpt-use/"><u>Strategies to Ease Capped ChatGPT Use</u></a></li>
<li><a href="https://windows11.techidaily.com/swiftly-solve-error-code-1132-in-microsofts-zoom-app/"><u>Swiftly Solve Error Code 1132 in Microsoft's Zoom App</u></a></li>
<li><a href="https://windows11.techidaily.com/system-sync-up-top-tactics-to-troubleshoot-unsupported-boots/"><u>System Sync-Up: Top Tactics to Troubleshoot Unsupported Boots</u></a></li>
<li><a href="https://windows11.techidaily.com/the-hidden-value-in-preserving-your-windows-11-notification-alerts/"><u>The Hidden Value in Preserving Your Windows 11 Notification Alerts</u></a></li>
<li><a href="https://windows11.techidaily.com/the-significance-of-aliases-in-application-launches/"><u>The Significance of Aliases in Application Launches</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-accessing-photos-via-windows-11s-explorer/"><u>Tips for Accessing Photos via Windows 11'S Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/transformative-notations-boosting-usability-with-comments-in-windows-11/"><u>Transformative Notations: Boosting Usability with Comments in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-obs-errors-unknown-failure-recorded/"><u>Troubleshooting OBS Errors: Unknown Failure Recorded</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-1110-stop-pin-connection-hurdle/"><u>Troubleshooting Windows 11/10: Stop PIN Connection Hurdle</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-resolving-isdonedll-faults-on-windows-11/"><u>Troubleshooting: Resolving ISDone.dll Faults on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-microsoft-store-app-in-windows-11-os/"><u>Unlocking Microsoft Store App in Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11s-veiled-bar-search-feature/"><u>Unlocking Windows 11'S Veiled Bar Search Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/upgrade-your-windows-to-a-dynamic-tiling-desktop-with-fancywm/"><u>Upgrade Your Windows to a Dynamic Tiling Desktop With FancyWM</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-arm-setup-via-iso-file-instructions-inside/"><u>Windows 11 ARM Setup Via ISO File - Instructions Inside</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-bar-through-time-1985-2023-retrospective/"><u>Windows Bar Through Time: 1985-2023 Retrospective</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>