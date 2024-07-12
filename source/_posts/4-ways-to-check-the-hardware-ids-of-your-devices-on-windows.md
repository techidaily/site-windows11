---
title: 4 Ways to Check the Hardware IDs of Your Devices on Windows
date: 2024-07-11T22:12:13.999Z
updated: 2024-07-12T22:12:13.999Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 4 Ways to Check the Hardware IDs of Your Devices on Windows
excerpt: This Article Describes 4 Ways to Check the Hardware IDs of Your Devices on Windows
keywords: Windows Device ID Check,Hardware IDs in Windows,PC Component Identification,Windows Serial Number Finder,Device Model Retrieval Windows,USB-HID Reporting,CPU Identifier Extraction
thumbnail: https://thmb.techidaily.com/6b26f43d7c441fdc486228c15693f43761df84b70dc520fe3fec90378bd8cb5b.jpg
---

## 4 Ways to Check the Hardware IDs of Your Devices on Windows

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
<li><a href="https://windows11.techidaily.com/how-to-pin-gmail-to-the-taskbar-on-a-windows-pc/"><u>How to Pin Gmail to the Taskbar on a Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/ensure-smooth-os-operation-autoupdate-and-change-amd-drivers/"><u>Ensure Smooth OS Operation: Autoupdate & Change AMD Drivers</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-use-phone-clone-to-migrate-your-honor-90-gt-data-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Use Phone Clone to Migrate Your Honor 90 GT Data? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-11-zoom-malfunction-1132/"><u>Overcoming Windows 11 Zoom Malfunction #1132</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-insiders-list-of-best-screencasting-software-win-edition-for-2024/"><u>[Updated] Insider's List of Best Screencasting Software, Win Edition for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-pc-management-with-customized-windows-troubleshooters-buttons/"><u>Optimize PC Management with Customized Windows Troubleshooters Buttons</u></a></li>
<li><a href="https://windows11.techidaily.com/lessen-malware-apps-resource-usage-for-performance-gain/"><u>Lessen Malware App’s Resource Usage for Performance Gain</u></a></li>
<li><a href="https://windows11.techidaily.com/perfecting-the-process-setting-up-msoffice-in-windows-11/"><u>Perfecting the Process: Setting Up MSOffice in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/revive-lost-control-secrets-for-steam-in-windows/"><u>Revive Lost Control: Secrets for Steam in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-pc-performance-hurdles-with-intel-graphics-updates/"><u>Remedying PC Performance Hurdles with Intel Graphics Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-non-existent-device-alerts-on-windows-1011/"><u>Resolving Non-Existent Device Alerts on Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-something-went-wrong-office-error-on-windows/"><u>How to Fix the “Something Went Wrong” Office Error on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/decreasing-cpu-and-ram-usage-tackling-unrealcefsubprocess-issues/"><u>Decreasing CPU and RAM Usage: Tackling UnrealCEFSubprocess Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-system-shutdown-alerts-due-to-roblox-glitches/"><u>Overcoming System Shutdown Alerts Due to Roblox Glitches</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-change-lock-screen-wallpaper-on-realme-12-proplus-5g-by-drfone-android/"><u>In 2024, How to Change Lock Screen Wallpaper on Realme 12 Pro+ 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-strategies-for-effortless-integration-of-directories-win-11/"><u>Expert Strategies for Effortless Integration of Directories, Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-muted-audio-recordings-in-obs-studio-on-windows-11-pcs/"><u>How to Fix Muted Audio Recordings in OBS Studio on Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/end-the-ebb-and-flow-top-strategies-for-smooth-windows-streaming/"><u>End the Ebb and Flow: Top Strategies for Smooth Windows Streaming</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/024-approved-discover-the-best-no-cost-soundtracks-for-video-production/"><u>[New] 2024 Approved  Discover the Best No-Cost Soundtracks for Video Production</u></a></li>
<li><a href="https://windows11.techidaily.com/gpresult-command-guide-for-policy-reporting/"><u>GPResult Command Guide for Policy Reporting</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-charge-awareness-customizing-battery-indicators-in-win11/"><u>Boosting Charge Awareness: Customizing Battery Indicators in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-a-faulty-windows-11-temporary-storage/"><u>Fixing a Faulty Windows 11 Temporary Storage</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-craft-professional-scenes-access-these-top-8-free-green-screen-backdrops-sites/"><u>[Updated] 2024 Approved  Craft Professional Scenes - Access These Top 8 Free Green Screen Backdrops Sites</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-strategies-for-overcoming-windows-error-code-0x80040610/"><u>Essential Strategies for Overcoming Windows Error Code 0X80040610</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-work-around-microsoft-verified-app-restrictions/"><u>Methods to Work Around Microsoft-Verified App Restrictions</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-windows-security-entry-error/"><u>Navigating Through Windows 'Security Entry Error'</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-install-hyper-v-on-windows-11-home/"><u>How to Install Hyper-V on Windows 11 Home</u></a></li>
<li><a href="https://windows11.techidaily.com/ideal-guide-efficiently-change-heic-images-to-jpeg-format-on-windows-11/"><u>Ideal Guide: Efficiently Change HEIC Images to JPEG Format on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-blank-login-issues-on-win1011-pcs/"><u>Clearing Up Blank Login Issues on WIN10/11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-default-usb-suspension-on-windows-11/"><u>Overcoming Default USB Suspension on Windows 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-conquer-the-vr-world-your-first-vr-adventure/"><u>[New] Conquer the VR World  Your First VR Adventure</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-unlocking-hidden-potential-how-to-use-video-filters-on-zoom/"><u>[Updated] 2024 Approved  Unlocking Hidden Potential  How To Use Video Filters on Zoom</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-camera-app-malfunctions-windows-0xa00f429f-error/"><u>Overcoming Camera App Malfunctions: Windows' 0XA00F429F Error</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-unlocking-image-clarity-techniques-for-online-cropping/"><u>2024 Approved  Unlocking Image Clarity  Techniques for Online Cropping</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-terminal-personalize-colors-and-style/"><u>Mastering Terminal: Personalize Colors & Style</u></a></li>
<li><a href="https://windows11.techidaily.com/brushstrokes-begin-accessing-microsoft-paint-in-windows-11/"><u>Brushstrokes Begin: Accessing Microsoft Paint in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-download-fonts-for-all-languages-on-windows/"><u>How to Download Fonts for All Languages on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/activate-virtualization-your-step-by-step-guide-for-win-11-homes/"><u>Activate Virtualization: Your Step by Step Guide for Win 11 Homes</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/2024-approved-split-screen-video-editing-made-easy-free-online-and-offline-solutions/"><u>2024 Approved Split Screen Video Editing Made Easy Free Online and Offline Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/maximize-your-taskbar-attaching-items-in-windows-11/"><u>Maximize Your Taskbar: Attaching Items in Windows 11</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-magix-samplitudes-standout-features-are-they-meriting-top-spot-for-2024/"><u>New MAGIX Samplitudes Standout Features Are They Meriting Top Spot for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-most-common-blue-screen-errors-on-windows/"><u>How to Fix the Most Common Blue Screen Errors on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-failed-jvm-launch-windows-guide/"><u>Remedying Failed JVM Launch: Windows Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/quelling-overzealousness-after-a-peak-life-period-on-windows/"><u>Quelling Overzealousness After a Peak Life Period on Windows</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-google-frp-on-g54-5g-by-drfone-android-unlock-remove-google-frp/"><u>How To Bypass Google FRP on G54 5G</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-path-to-exceptional-editing-with-kinemaster/"><u>The Path to Exceptional Editing with Kinemaster</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-incomplete-updates-in-your-windows-based-discord/"><u>Handling Incomplete Updates in Your Windows-Based Discord</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-from-raw-footage-to-polished-highlights/"><u>[New] 2024 Approved  From Raw Footage to Polished Highlights</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-for-inverted-keyboard-input-windows/"><u>Quick Fix for Inverted Keyboard Input Windows</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-amass-a-thousand-tactics-for-monthly-instagram-following/"><u>[New] Amass a Thousand  Tactics for Monthly Instagram Following</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/in-2024-why-mp3-converter-windows-should-be-your-go-to-tool-an-insiders-look/"><u>In 2024, Why Mp3 Converter Windows Should Be Your Go-To Tool An Insiders Look</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-audience-allure-3-ultimate-video-growth-methods/"><u>[Updated] In 2024, Audience Allure  3 Ultimate Video Growth Methods</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/peak-popularity-on-reddit-10-most-upvoted-stories-for-2024/"><u>Peak Popularity on Reddit  10 Most Upvoted Stories for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/beginners-manual-discovering-windows-aids-and-assists/"><u>Beginner's Manual: Discovering Windows Aids and Assists</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-a-quick-guide-to-xiaomi-redmi-note-12-pro-5g-frp-bypass-instantly-by-drfone-android/"><u>In 2024, A Quick Guide to Xiaomi Redmi Note 12 Pro 5G FRP Bypass Instantly</u></a></li>
<li><a href="https://windows11.techidaily.com/fast-factor-essential-steps-for-assessing-lan-router-speed/"><u>Fast Factor: Essential Steps for Assessing LAN Router Speed</u></a></li>
</ul></div>
