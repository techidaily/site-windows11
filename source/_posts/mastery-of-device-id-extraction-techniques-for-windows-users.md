---
title: Mastery of Device ID Extraction Techniques for Windows Users
date: 2024-07-11T21:41:29.854Z
updated: 2024-07-12T21:41:29.854Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastery of Device ID Extraction Techniques for Windows Users
excerpt: This Article Describes Mastery of Device ID Extraction Techniques for Windows Users
keywords: Windows ID Extraction,Device ID Mastery,Windows User Guide,Extracting IDs Windows,Technique Devices ID,WinID Extraction Methods,ID Extraction Windows
thumbnail: https://thmb.techidaily.com/501cfbb0674181793ce2cd8353fd1c77b58868d2c9678fbe9da8ac95eb395e1d.jpg
---

## Mastery of Device ID Extraction Techniques for Windows Users

 A hardware ID is a unique identification number given to hardware components. It’s associated with the devices that you attach to your PC or the ones already connected to it.

 This identification number can be helpful when you want to download the correct device drivers. That's because if you know the hardware ID, then you can use it to search for a specific driver online.

 Let’s discover the various ways to check your hardware IDs on Windows.

## 1\. Use the Device Manager

 The Device Manager is a tool that helps you tweak the settings for almost all the devices that are connected to your PC. You can also use this tool to update or reinstall the device drivers.

 Now, let’s check out how you can use the Device Manager to search for the hardware IDs:

1. Press**Win + Run** to open the Run command dialog box. Alternatively, check out [the various ways to access the Run command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**devmgmt.msc** and press**Enter** to open the Device Manager.
3. Expand the category for the device you want to look up. For example, expand the**Keyboards** category if you want the hardware ID for your keyboard.
4. Right-click on the relevant device and select**Properties** .
5. Navigate to the**Details** tab.
6. Click the**Property** drop-down menu and select**Hardware Ids** . You should see the hardware ID results in the "Value" box.

![Clicking the Property drop-down menu and selecting Hardware Ids](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/clicking-the-property-drop-down-menu-and-selecting-hardware-ids.jpg)

 You might often see more than one ID in the "Value" box. In such instances, you should only focus on the hardware ID that appears at the top.

 Don’t confuse a hardware ID with a compatible ID. A hardware ID is a unique identification number given to a specific device. Meanwhile, a compatible ID is a generic identification number given to a group of devices.

## 2\. Use the Command Prompt

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

 The Command Prompt is an incredible tool that helps you access most apps, configure system settings, and troubleshoot device issues. You can also perform other tricks with it, such as checking the hardware IDs for your devices.

Let’s check out the steps you need to follow:

1. Press**Win + R** to open the Run command dialog box.
2. Type**CMD** and press**Ctrl + Shift + Enter** to open an elevated Command Prompt.
3. Type the following command to get a list of all your drivers and devices:

`Dism /Online /Get-Drivers /all /Format:Table`

![Displaying device information on the Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/displaying-device-information-on-the-command-prompt.jpg)

 Now, let’s say you want the hardware ID for the mouse. Here’s how you can search for it:

1. Scroll down on the Command Prompt results and locate**Mouse** in the "Class Name" category.
2. In the same row, check the option that appears in the "Published Name" category.

![Selecting the mouse option "msmouse" in the Command Prompt results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/selecting-the-mouse-option-in-the-command-prompt-results-1.jpg)

 In this case, the option in the "Published Name" category is**msmouse.inf** .

 Now that you've found the "Published Name" result for the mouse, here's how you can use it to find the hardware ID:

1. Open a new**Command Prompt** window by following the previous steps.
2. Type the following command and replace**Published Name** with the relevant command:

`Dism /Online /Get-DriverInfo /Driver:Published Name`

 For example, we discovered earlier that the "Published Name" result for the mouse is**msmouse.inf** . If we insert this into the command above, then the result should be as follows:

`Dism /Online /Get-DriverInfo /Driver:msmouse.inf`

 Now, press**Enter** once you’ve typed in the correct command. From there, locate the "Hardware ID" option from the results.

![Selecting the Hardware ID option in the Command Prompt screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/selecting-the-hardware-id-option-in-the-command-prompt-screen.jpg)

## 3\. Use PowerShell

 Alternatively, you can also check the hardware IDs using [Windows PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) . It’s another incredible tool that allows you to run various commands.

 Let’s explore how you can check the hardware IDs using this tool:

1. Press**Win + R** to open the Run command dialog box.
2. Type**PowerShell** and press**Ctrl + Shift + Enter** to open the elevated PowerShell window.
3. Type the following command to get a list of your drivers and devices:

`Get-PnpDevice -PresentOnly | Sort-Object -Property &ldquo;Class&rdquo; | Format-Table -AutoSize`

![PowerShell window displaying device information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/powershell-window-displaying-device-information.jpg)

 Now, look for your target device under the "FriendlyName" category.

 For example, let’s say your target device is the keyboard. In this case, the option that appears in the "FriendlyName" category for the keyboard is**Standard PS/2 Keyboard** .

 After finding your target device, check the**Instance ID** (the value that appears in the last column).

![Selecting the Keyboard option from the PowerShell command options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/selecting-the-keyboard-option-from-the-powershell-command-options.jpg)

 For the keyboard, the Instance ID is**ACPI\\IDEA0102\\4&15E808EC&0** .

 Now that you've found the Instance ID, here’s how you can use it to find the hardware ID:

1. Open an**elevated PowerShell window** as per the previous steps.
2. Type the following command and replace the**Instance Id** command with the relevant option:

`Get-PnpDeviceProperty -InstanceId "Instance Id" | Format-Table -AutoSize`

 If we use the Instance ID for the keyboard (ACPI\\IDEA0102\\4&15E808EC&0), then the command should be as follows:

`Get-PnpDeviceProperty -InstanceId "ACPI\IDEA0102\4&15E808EC&0" | Format-Table -AutoSize`

 Now, press**Enter** to run the command. From there, look for the**DEVPKEY\_Device\_HardwareIds** option under the**KeyName** category.

 Next, look for the corresponding value in the "Data" category. The value that appears in this section is the hardware ID.

![Selecting the hardware ID option on PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/selecting-the-hardware-id-option-on-powershell.jpg)

 In this case, the hardware ID for the keyboard (which appears in the "Data" category) is**ACPI\\VEN\_IDEA&DEV\_0102** .

## 4\. Use the Windows Device Console

 The Device Console (DevCon) is a feature that shows you detailed information about the devices on your computer. This tool can also help you configure, install, remove, enable, or disable devices.

 Interestingly, this tool allows you to view the hardware IDs of multiple apps simultaneously. Unfortunately, the Device Console isn’t built-in on your device. This means you need to download and install it first.

 Let’s check out how you can install this tool and use it to check the hardware IDs:

1. Download and install the [Windows Drivers Kit](https://learn.microsoft.com/en-us/windows-hardware/drivers/other-wdk-downloads) from the Microsoft website. When you're on the site, head to the**Step 2: Install the WDK** section and pick an app that’s compatible with your device.
2. Once you’ve installed the tool, open**File Explorer** and navigate to **This PC > Local Disk (C:) > Program Files (x86) > Windows Kits > 10 > Tools** . If you’re using Windows 11, the path should be **This PC > Local Disk (C:) > Program Files (x86) > Windows Kits > 11 > Tools** .
3. Access the**x64** (64-bit) folder if you're using a 64-bit device or the**x86** (32-bit) folder if you use a 32-bit PC. If you’re unsure what to pick,[check your Windows PC specs](https://www.makeuseof.com/ways-to-check-your-windows-10-essential-pc-specs/) first.

![Selecting the x64 folder in the Tools section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/selecting-the-x64-folder-in-the-tools-section.jpg)

Once you’re in the correct folder, follow these steps:

1. Click the**File Explorer address bar** .
2. Type**CMD** and then press**Enter** . This will run the Command Prompt within the current folder.

![Typing the CMD command in the File Explorer address bar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/typing-the-cmd-command-in-the-file-explorer-address-bar.jpg)

 From there, type the following command into the Command Prompt and press**Enter** :

`devcon hwids *`

![Displaying hardware IDs using DevCon](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/displaying-hardware-ids-using-devcon.jpg)

 This will show you the details of all the devices on your computer. The results will also contain the hardware IDs.

 For example, we've highlighted the hardware ID for the**Standard PS/2 Keyboard** in the image below.

![Selecting the hardware ID for the Standard PS2 Keyboard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/selecting-the-hardware-id-for-the-standard-ps2-keyboard.jpg)

 Remember, if there’s more than one hardware ID, always pick the first option. This means the hardware ID for the keyboard, in the example above, is**ACPI\\VEN\_IDEA&DEV\_0102** .

 If you want to explore the Device Console in detail, check out [the various ways to use Dev Con](https://learn.microsoft.com/en-us/windows-hardware/drivers/devtest/devcon-examples) on the Microsoft website.

## You've Successfully Found the Hardware IDs of Your Devices

 Hardware IDs make it easy for you to identify all your devices and drivers. The good news is that it's quite easy to find these IDs.

 If you want to check your hardware IDs quickly, try the Device Manager method in this article. Otherwise, any of the other methods we’ve covered should help.


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
<li><a href="https://windows11.techidaily.com/rectifying-0x800700e9-error-within-xbox-game-pass-and-windows-11/"><u>Rectifying 0X800700E9 Error Within Xbox Game Pass & Windows 11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-time-saving-photo-enhancement-adding-dates-to-pictures/"><u>2024 Approved  Time-Saving Photo Enhancement  Adding Dates to Pictures</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-start-guide-to-windows-11-apps/"><u>Quick Start Guide to Windows 11 Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-black-screens-with-simple-win11-tweaks/"><u>Resolving Black Screens with Simple Win11 Tweaks</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-solo-side-windows-earbud-sound-problems/"><u>Resolving Solo Side Windows Earbud Sound Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-to-reduce-high-wmi-cpu-consumption/"><u>Solutions to Reduce High WMI CPU Consumption</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-address-systemsettings-errors-in-windows-11/"><u>Steps to Address SystemSettings Errors in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-your-touch-to-the-world-of-win11-keybindings/"><u>Tailoring Your Touch to the World of Win11 Keybindings</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-scriptwriting-secrets-penning-podcast-episodes-that-resonate/"><u>In 2024, Scriptwriting Secrets  Penning Podcast Episodes That Resonate</u></a></li>
<li><a href="https://video-capture.techidaily.com/best-webcams-on-windows-10-top-applications-reviewed-for-2024/"><u>Best Webcams on Windows  10 Top Applications Reviewed for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-enhancing-visual-impact-of-youtube-thumbnails-neon-edition/"><u>In 2024, Enhancing Visual Impact of YouTube Thumbnails - Neon Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/a-step-by-step-guide-to-fix-windows-non-functional-start/"><u>A Step-by-Step Guide to Fix Window's Non-Functional Start</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-invisible-broadcasts-anonymous-instagram-live-tips/"><u>[Updated] Invisible Broadcasts  Anonymous Instagram Live Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/reimagining-fn-key-usage-within-windows-11-platform/"><u>Reimagining FN Key Usage Within Windows 11 Platform</u></a></li>
<li><a href="https://windows11.techidaily.com/top-methods-to-enhance-utorrent-download-speed-win-edition/"><u>Top Methods to Enhance uTorrent Download Speed, WIN Edition</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-personalized-video-setups-a-beginners-guide-to-selfies-on-youtube/"><u>[Updated] Personalized Video Setups  A Beginner's Guide to Selfies on YouTube</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-creating-simple-videos-top-10-youtube-projects-anyone-can-do-for-2024/"><u>[Updated] Creating Simple Videos  Top 10 YouTube Projects Anyone Can Do for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/1719291887266-eliminating-obstacles-in-capturing-whole-screen-with-windows-snipping-tool/"><u>Eliminating Obstacles in Capturing Whole-Screen with Windows Snipping Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-unable-to-connect-error-with-malwarebytes-in-windows/"><u>Resolving Unable to Connect Error with Malwarebytes in Windows</u></a></li>
<li><a href="https://games-able.techidaily.com/switch-into-action-clearing-connection-snags/"><u>Switch Into Action! Clearing Connection Snags</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-11s-hidden-calendar-and-email-fixes/"><u>Unveiling Windows 11'S Hidden Calendar & Email Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-tips-avoiding-discords-auto-start-and-update-checks/"><u>Windows Tips: Avoiding Discord's Auto-Start & Update Checks</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-complex-windows-partition-unification/"><u>The Ultimate Guide to Complex Windows Partition Unification</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-storage-type-ssd-vs-hdd/"><u>Unveiling Storage Type: SSD vs HDD</u></a></li>
<li><a href="https://windows11.techidaily.com/three-strategies-to-redo-windows-11-user-preferences/"><u>Three Strategies to Redo Windows 11 User Preferences</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-samsung-galaxy-f04-to-other-android-devices-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Samsung Galaxy F04 to Other Android Devices Devices? | Dr.fone</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/outsmarting-tiktoks-unseen-ban-a-recovery-plan/"><u>Outsmarting TikTok's Unseen Ban  A Recovery Plan</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-celestial-journey-enhanced-by-these-sj4000-gear-must-haves/"><u>[Updated] Celestial Journey Enhanced by These SJ4000 Gear Must-Haves</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-leaders-shaping-the-marvel-online-experience/"><u>[Updated] Leaders Shaping the Marvel Online Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-access-to-disabled-windows-apps/"><u>Restoring Access to Disabled Windows Apps</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-solutions-to-find-your-realme-v30t-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Solutions to Find Your Realme V30T Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-unraveling-failed-system-call-issues-in-win1011/"><u>Steps to Unraveling 'Failed System Call' Issues in Win10/11</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/deciphering-the-superior-video-sharing-platform-tiktok-or-youtube-shorts/"><u>Deciphering the Superior Video-Sharing Platform  TikTok or YouTube Shorts?</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-visual-comfort-notebook-themes-and-fonts-in-windows-11/"><u>Tailoring Visual Comfort: Notebook Themes and Fonts in Windows 11</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-how-to-use-voicemod-on-discord-desktop-and-mobile-for-2024/"><u>[Updated] How To Use Voicemod On Discord [Desktop and Mobile] for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-erase-no-server-errors-in-pc-apex-legends-(156-chars/"><u>Strategies To Erase No-Server Errors in PC Apex Legends (<156 Chars)</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/expert-iphone-techniques-for-stunning-scenery-shots/"><u>Expert iPhone Techniques for Stunning Scenery Shots</u></a></li>
<li><a href="https://facebook.techidaily.com/flexible-fonts-for-friendly-forums-messenger-tips/"><u>Flexible Fonts for Friendly Forums: Messenger Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-package-not-registered-image-glitches-in-win11/"><u>Unraveling 'Package Not Registered' Image Glitches in Win11</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-mastering-bandicam-key-takeaways-and-tips/"><u>[New] 2024 Approved  Mastering Bandicam - Key Takeaways and Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-high-cpu-in-your-host-system/"><u>Taming High CPU in Your Host System</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-and-edge-background-runs-how-to-control/"><u>Win11 and Edge Background Runs - How to Control</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-mending-non-responsive-windows-network/"><u>Strategies for Mending Non-Responsive Windows Network</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-factory-unlock-your-telstra-apple-iphone-6s-by-drfone-ios/"><u>How To Factory Unlock Your Telstra Apple iPhone 6s</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-crafting-engaging-tiktok-tracks-with-visuals/"><u>[New] In 2024, Crafting Engaging TikTok Tracks with Visuals</u></a></li>
<li><a href="https://windows11.techidaily.com/stepwise-guide-to-deploying-themes-from-microsoft-store/"><u>Stepwise Guide to Deploying Themes From Microsoft Store</u></a></li>
<li><a href="https://windows11.techidaily.com/rediscover-the-lost-treasures-within-windows-11s-features/"><u>Rediscover the Lost Treasures Within Windows 11'S Features</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-spice-up-your-instagram-feed-incorporate-video-loops/"><u>[New] Spice Up Your Instagram Feed  Incorporate Video Loops</u></a></li>
<li><a href="https://windows11.techidaily.com/which-browser-takes-up-less-memory-and-cpu-on-windows-macos/"><u>Which Browser Takes Up Less Memory and CPU On Windows, macOS?</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-mend-windows-network-proxy-errors/"><u>Steps to Mend Windows Network Proxy Errors</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-leveraging-instagram-hashtags-to-amplify-social-media-impact-for-2024/"><u>[New] Leveraging Instagram Hashtags to Amplify Social Media Impact for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/regain-usb-connectivity-in-windows-os-amidst-issues/"><u>Regain USB Connectivity in Windows OS Amidst Issues</u></a></li>
</ul></div>
