---
title: Rectifying Screen Resolution Problems in Windows OS
date: 2024-07-11T21:41:43.055Z
updated: 2024-07-12T21:41:43.055Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Rectifying Screen Resolution Problems in Windows OS
excerpt: This Article Describes Rectifying Screen Resolution Problems in Windows OS
keywords: Fix Windows Display Issue,Enhance Screen Clarity Win,Correct Res LCD Windows,Optimize Pixels Window,Resolve Screen Refresh PC,Adjust Windows Aspect Ratio,Improve Image Quality OS
thumbnail: https://thmb.techidaily.com/67bd9eb22eb0b577554d0f90d5db30aca97e4f163bbbccbbc666c03d517f249c.jpg
---

## Rectifying Screen Resolution Problems in Windows OS

 You could spend thousands on a monitor, but if you've managed to mess up with display settings in Windows, or within an app or game, it will ruin your viewing experience. In some cases, it could be the driver or a hardware component giving you trouble.

 Regardless of the reason for your viewing perils, we're going to help troubleshoot the display issue, so you can go back to enjoying high-quality viewing. We'll talk about the problems that can lead to a screen resolution issue and how you can fix them.

## 1\. Incorrect Resolution Settings

 Resolution can often change by itself on Windows because of a corrupted graphics driver, a new Windows update, or a conflicting third-party app. If this is the case with your display, you can easily fix it by changing the resolution settings.

 Press **Win + I** to launch Settings and navigate to **System > Display**. Click on the drop-down menu next to **Display Resolution** and select the recommended option from the list.

![changing resolution from settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/settings-resolution.jpg)

## 2\. Incorrect App-Specific Settings

 A third-party app may override the screen resolution you set on Windows and apply a resolution it requires to properly run and display its content. The most common example is games. Games typically have an option to change the resolution within their settings, and that's where you'll be able to control it.

 It doesn't require much fixing after you exit the app, though. In most cases, the resolution should revert to what you've set in Windows by default. If it doesn't, just go to Setting and change the resolution as explained in the previous section.

## 3\. Problems With the Hardware

 The resolution issue could also result from hardware issues. There are two components you need to check: the graphics card, and the display cable.

 When your display's resolution is higher than the resolution that either or both of these hardware components support, you could have a problem.

 For instance, if you're using an integrated graphics card or a very old one, your 4K display probably won't live up to your expectations. On the other hand, if you're using a single or double-link DVI, 4K isn't an option.

 If you're using an HDMI cable, you'll need to check for two things. First up is the type of HDMI cable. A category 3 HDMI supports 4K @60Hz. But there's another variable in this equation. You need to check what type of HDMI your graphics card supports. You'll need HDMI 1.3 at a minimum to view 4K @60Hz.

 If the issue is with your cable, try switching from [HDMI to DisplayPort](https://www.makeuseof.com/displayport-vs-hdmi/). If that's not an option, you'll need to spend some money upgrading your hardware.

 You can also diagnose problems with the hardware using the Hardware and Devices troubleshooter that is built into Windows by default.

 Here is how you can run it:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type "cmd" in Run and press **Ctrl** \+ **Shift** \+ **Enter** to open Command Prompt as an administrator.
3. Click **Yes** in the User Account Control prompt.
4. Once you are inside the Command Prompt, execute the command below:  
msdt.exe -id DeviceDiagnostic  
![The Hardware and Devices troubleshooter command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/hardware-troubleshooter-command.jpg)
5. In the following dialog, click **Next** and wait for the troubleshooter to scan the system. If it finds an issue, it will notify you and suggest a fix. In that case, click on **Apply this fix**.  
![Run the Hardware and Devices Troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/run-the-hardware-and-devices-troubleshooter.jpg)

## 4\. Faulty or Corrupt Display Drivers

 Drivers are necessary for your hardware to function properly. If your display driver is corrupt or outdated, it could lead to a problem with your display. Fortunately, it's easy to update the display or graphics driver. Below, we walk you through the steps of both updating and reinstalling drivers in detail.

### Update Drivers

 Press **Win + R**, type **devmgmt.msc**, and press **Enter** to launch Device Management. Expand the category called **Display adapters** by clicking on the tiny arrow to its left. Right-click on the display adapter you want to update and select **Update driver**.

![updating the driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/update-driver.jpg)

 You can search for drivers automatically, but there's a good chance Windows won't find anything. The second option will let you install the driver manually.

 To use the second option, you'll need to first download driver installation files from the manufacturer's website. When you're done, add the driver folder's location in the wizard and follow the wizard's prompts.

![updating the drivers manually](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/update-manual.jpg)

### Rollback or Reinstall Drivers

 In some cases, the updated driver can cause a problem instead of fixing it. If you started encountering the resolution issue after an update, consider rolling back the updated driver. Doing so uninstalls the updated driver and reverts to the previous driver.

 You'll first need to check if the option to roll back is available. You can do this by clicking on the relevant device and selecting properties. Switch to the **Driver** tab and select **Roll Back Driver**. If the option isn't grayed out, it's available. Click on it and follow the on-screen prompts to roll back the driver.

![rolling back the driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/roll-back-driver.jpg)

 Finally, if updating the driver or rolling it back to a previous version has not worked for you, you can consider reinstalling the driver using the manufacturer's website. Follow the steps in our guide on [cleanly installing and reinstalling GPU drivers on Windows](https://www.makeuseof.com/how-to-cleanly-install-and-reinstall-gpu-drivers-on-windows/) for step-by-step instructions on this.

## 5\. An Incorrect Display Adapter Mode

 If you've got multiple monitors connected to your PC, and one or more of them seem to have a resolution problem, try checking the Display Mode settings on Windows. If you're duplicating a display on two screens that have different resolutions, one of them will have the wrong resolution.

 Unfortunately, there's no way to use the right resolution for each screen when using duplicate screens. You can either "extend" the display, or use the Display Adapter mode to select the right resolution for one display and let the other one stay as-is.

 To change the Display Adapter mode, go to **Settings** and navigate to **System > Display > Advanced Display**. Click on **Display adapter properties for Display 1** (click this option for the relevant display). Click on **List All Modes**, select the correct resolution, and click **OK**.

![changing the display mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/display-mode.jpg)

## 6\. Incorrect Font and Icon Sizes

 If you've set the correct resolution, but the text and icons on your screen appear too small, you might consider [tweaking the DPI](https://www.makeuseof.com/how-to-configure-display-scaling-windows-10/) (Dots Per Inch). Usually, this happens on small-sized high-resolution screens, like a 4K screen 15.6-inch.

 Changing DPI scaling is pretty easy, but not recommended. You might end up with illegible text and fuzzy-looking apps. Plus, it can often be difficult to revert to the original settings. If you decide to go ahead, be conservative with changing these numbers. The smaller the change, the better.

 You can change DPI scaling by going to Settings and navigating to **System > Display**. Click on the right arrow next to Custom scaling. On the next screen, you'll see a box where you need to enter a number between 100 and 500\. That's the percentage for DPI scaling you'd like to use.

![changing DPI scaling on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/custom-scaling.jpg)

## Windows Resolution Issues Resolved

 Hopefully, you were able to identify the issue and fix it. If you're facing a resolution issue while gaming, you might be tempted to choose the highest resolution from within the game. However, for you to be able to run the game at that resolution, your hardware will need to support it. It's best to get a basic idea of the best gaming resolution for your PC before you change it.

 Regardless of the reason for your viewing perils, we're going to help troubleshoot the display issue, so you can go back to enjoying high-quality viewing. We'll talk about the problems that can lead to a screen resolution issue and how you can fix them.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/ace-your-development-setup-with-top-wsl-2-tricks/"><u>Ace Your Development Setup with Top WSL 2 Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/bridging-the-gap-for-stuck-files-in-windows-11-ecosystems/"><u>Bridging the Gap for Stuck Files in Windows 11 Ecosystems</u></a></li>
<li><a href="https://windows11.techidaily.com/bold-stealth-for-your-wi-fi-on-windows-pcs/"><u>Bold Stealth for Your Wi-Fi on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-back-windows-photo-viewer-a-1111-edition-guide/"><u>Bring Back Windows Photo Viewer: A 11/11 Edition Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/1719309112975-stuck-in-chrome-unfreeze-windows-11-with-simple-fixes/"><u>Stuck in Chrome? Unfreeze Windows 11 with Simple Fixes!</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensive-overview-using-bluescreenview/"><u>A Comprehensive Overview: Using BlueScreenView</u></a></li>
<li><a href="https://android-frp.techidaily.com/easy-guide-to-poco-x6-pro-frp-bypass-with-best-methods-by-drfone-android/"><u>Easy Guide to Poco X6 Pro FRP Bypass With Best Methods</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/peering-into-the-world-of-luts-and-their-effect-on-pixels-for-2024/"><u>Peering Into the World of LUTs and Their Effect on Pixels for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-panic-recover-lost-data-with-these-steps/"><u>Avoid Panic, Recover Lost Data with These Steps</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-gastronomic-gala-top-food-videos-sweeping-social-media/"><u>[New] 2024 Approved  Gastronomic Gala  Top Food Videos Sweeping Social Media</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-crafting-wisdom-for-the-virtual-realm-30plus-metaverse-quotes/"><u>2024 Approved  Crafting Wisdom for the Virtual Realm  30+ Metaverse Quotes</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-printer-usage-errors-efficiently/"><u>Bypassing Printer Usage Errors Efficiently</u></a></li>
<li><a href="https://windows11.techidaily.com/build-your-windows-own-text-to-speech-converter-with-whisper-and-autohotkey/"><u>Build Your Window's Own Text-To-Speech Converter with Whisper and AutoHotkey</u></a></li>
<li><a href="https://windows11.techidaily.com/accessing-stealthed-elements-in-windows-11-ui/"><u>Accessing Stealthed Elements in Windows 11 UI</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-up-your-pc-set-auto-update-plus-modify-amd-video/"><u>Boost Up Your PC: Set Auto Update + Modify AMD Video</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-boot-speed-with-simple-steps-in-windows-11-setup/"><u>Boosting Boot Speed with Simple Steps in Windows 11 Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/becoming-an-expert-learner-with-these-7-windowing-strategies/"><u>Becoming an Expert Learner with These 7 Windowing Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/bridging-windows-prefixes-with-microsoft-services/"><u>Bridging Windows Prefixes with Microsoft Services</u></a></li>
<li><a href="https://windows11.techidaily.com/brightening-up-dull-desktop-windows-appearance/"><u>Brightening Up Dull Desktop Windows Appearance</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-personalized-settings-alomwares-pathway-to-customization/"><u>Achieve Personalized Settings - AlomWare's Pathway to Customization</u></a></li>
<li><a href="https://windows11.techidaily.com/a-closer-look-at-devhome-enhancing-windows-11-performance/"><u>A Closer Look at DevHome: Enhancing Windows 11 Performance</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-increase-your-channels-reach-with-these-2-tricks/"><u>[New] 2024 Approved  Increase Your Channel's Reach with These 2 Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/breakdown-how-law-filters-transform-your-windows-experience/"><u>Breakdown: How LAW Filters Transform Your Windows Experience</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/unleash-your-inner-toon-16-fantastic-cartoonizer-apps-for-2024/"><u>Unleash Your Inner Toon 16 Fantastic Cartoonizer Apps for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerating-windows-11-app-launches/"><u>Accelerating Windows 11 App Launches</u></a></li>
<li><a href="https://driver-install.techidaily.com/swift-driver-refresh-for-windows-oses-10-81-and-7-steps/"><u>Swift Driver Refresh for Windows OSes - 10, 8.1, & 7 Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-through-windows-tpm-restrictions-with-ease/"><u>Breaking Through Windows TPM Restrictions with Ease</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-google-frp-lock-on-poco-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock on Poco Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/batch-folder-generation-in-windows-11-for-efficiency-boost/"><u>Batch Folder Generation in Windows 11 for Efficiency Boost</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-the-high-demand-of-ntoskrnlexe-processes/"><u>Addressing the High Demand of Ntoskrnl.exe Processes</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-honor-90-lite-frp-by-drfone-android/"><u>In 2024, Step-by-Step Tutorial How To Bypass Honor 90 Lite FRP</u></a></li>
<li><a href="https://windows11.techidaily.com/christmas-theme-makeovers-for-windows-11/"><u>Christmas Theme Makeovers for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/chkdsk-sfc-and-dism-windows-tools-unveiled-and-explained/"><u>CHKDSK, SFC & DISM: Windows Tools Unveiled and Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/actions-for-correcting-windows-11-0x800f0922-error/"><u>Actions for Correcting Windows 11 0X800F0922 Error</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-top-5-best-free-mod-video-editors-for-2024/"><u>Updated Top 5 Best Free MOD Video Editors for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-errors-manage-deps-for-virtualbox-on-windows/"><u>Avoid Errors: Manage Deps for VirtualBox on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/aging-gracefully-with-your-grans-windows-machine/"><u>Aging Gracefully with Your Gran’s Windows Machine</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/sdk-innovations-for-android-the-updated-rankings-of-facebook-video-downloading-tools-for-2024/"><u>SDK Innovations for Android  The Updated Rankings of Facebook Video Downloading Tools for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/bypass-chaos-with-these-three-windows-reset-methods/"><u>Bypass Chaos with These Three Windows Reset Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-game-session-rejection-by-steams-vac/"><u>Avoiding Game Session Rejection by Steam's VAC</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-pc-screen-to-vivo-s18e-phones-drfone-by-drfone-android/"><u>How to Mirror PC Screen to Vivo S18e Phones? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/accessible-windows-for-new-users-and-learners/"><u>Accessible Windows for New Users & Learners</u></a></li>
<li><a href="https://windows11.techidaily.com/bridging-linux-and-windows-gap-with-shared-tools/"><u>Bridging Linux & Windows Gap with Shared Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/applying-local-group-policies-to-individual-users-windows-11-guide/"><u>Applying Local Group Policies to Individual Users: Windows 11 Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-your-cursors-appearance-in-windows-os/"><u>Boosting Your Cursor's Appearance in Windows OS</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-leading-tech-macs-finest-video-recording-software/"><u>2024 Approved  Leading Tech  Mac's Finest Video Recording Software</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-unleashing-your-cameras-potential-with-top-rated-drones-gimbals/"><u>2024 Approved  Unleashing Your Camera's Potential with Top-Rated Drones Gimbals</u></a></li>
<li><a href="https://windows11.techidaily.com/bootstrapping-your-windows-version-patch-edition/"><u>Bootstrapping Your Windows Version: Patch Edition</u></a></li>
<li><a href="https://android-unlock.techidaily.com/the-ultimate-guide-to-vivo-y100i-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>The Ultimate Guide to Vivo Y100i Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-strategies-for-overcoming-win11-installer-challenges/"><u>Advanced Strategies for Overcoming Win11 Installer Challenges</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensive-list-of-10-ways-to-fine-tune-windows-11-screens/"><u>A Comprehensive List of 10 Ways to Fine-Tune Windows 11 Screens</u></a></li>
<li><a href="https://windows11.techidaily.com/a-detailed-guide-turning-off-windows-update-restrictions/"><u>A Detailed Guide: Turning Off Windows Update Restrictions</u></a></li>
</ul></div>
