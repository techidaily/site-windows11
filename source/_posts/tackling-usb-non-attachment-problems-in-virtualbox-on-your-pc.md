---
title: Tackling USB Non-Attachment Problems in VirtualBox on Your PC
date: 2024-08-22T21:31:13.105Z
updated: 2024-08-23T21:31:13.105Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling USB Non-Attachment Problems in VirtualBox on Your PC
excerpt: This Article Describes Tackling USB Non-Attachment Problems in VirtualBox on Your PC
keywords: VirtualBox USB Issues,USB Attach/Detach Troubleshoot,Fixing VirtualBox USB Errors,Manage VirtualBox USB Connections,Optimize USB in VirtualBox,Resolve VM USB Problems,Streamline VirtualBox USB Settings
thumbnail: https://thmb.techidaily.com/c74a6f4cbc3131991d1108cc0cd3851c9f4624d9f7132bc54e3318b3d6ad9b70.jpg
---

## Tackling USB Non-Attachment Problems in VirtualBox on Your PC

 VirtualBox lets you run many operating systems in a virtual environment without affecting your host system files. It is a great hypervisor platform perfect for trying out any operating system without installing it alongside your host operating system. But many users face an issue while connecting a USB device to their VirtualBox Virtual machine.

 VirtualBox does support USB devices out of the box but requires an extension pack to enable USB 2.0 and USB 3.0 devices. If you see the ‘Failed to Attach the USB Device’ error every time you try to connect a USB device, don’t fret. We will list out the possible reasons why you see the error code along with multiple fixes to resolve the issue.

## Reasons for the "Failed to Attach the USB Device" Error

Here are some possible reasons for the VirtualBox USB devices error.

1. The USB drive is corrupt or the USB port is not working.
2. You haven’t installed the correct VirtualBox extension pack on your system.
3. You are running an outdated version of VirtualBox.
4. You haven’t added the USB device to the virtual machine using USB settings.

 Now, you know the possible reasons why VirtualBox throws an error code when you connect a USB device. Here are the following methods you can try to fix the error code and successfully connect the USB device to the virtual machine.

## How to Fix the "Failed to Attach the USB Device" Error in Windows

 Now that we know what's potentially causing the issue, let's explore the fixes.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. Restart VirtualBox

 Before you move on to other advanced fixes, restart the VirtualBox application. If restarting the app doesn’t work, restart Windows. It will restart all the processes and services including the ones VirtualBox needs to function properly. Now, connect a USB device and try to attach it to a virtual machine in VirtualBox. If it still doesn’t show up, move to the next fix.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
### 2\. Check the USB Device on the Host System

 Before trying to attach the USB device to the VirtualBox virtual machine, first check if it shows up on your host system. Launch the File Explorer and go to This PC and check if the USB drive appears there. If you don’t see the USB drive, do as follows:

1. First, open Device Manager. There are many[different ways to open the Device Manager](https://www.makeuseof.com/windows-open-device-manager/) , but a quick way is to press**Win + R** to launch the Run command box. Type**devmgmt.msc** and press the**Enter** key to launch the Device Manager.  
![Check the USB Device on the Host System](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Check-the-USB-Device-on-the-Host-System.jpg)
2. Navigate to the**Disk Drives** option and click the**arrow** icon to expand the section.
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Find the USB drive you connected to the host system. If it is not present in the list, pull it out and reconnect it to another USB port on your system.

 If the USB port on your system malfunctions, the USB drive won’t show up in Device Manager or File Explorer. But if the USB drive doesn’t appear in the device manager even after changing the port, it could have a hardware malfunction. In that case, try connecting another USB drive to VirtualBox virtual machine.

### 3\. Install the VirtualBox Extension Pack

 VirtualBox can only attach USB 1.0 devices to a virtual machine. You need to install the extension pack to add USB 2.0 or 3.0 devices. Here’s how to do it.

1. Open VirtualBox on your system and navigate to**Help > About VirtualBox** . Note the version currently installed on your system.
2. Launch any web browser on your system and go to the[official VirtualBox download page](https://www.virtualbox.org/wiki/Downloads) .
3. Click on the build number which is present on your system. Scroll down and download its corresponding extension pack.
4. Now, open VirtualBox. Navigate to**File > Tools > Extension Pack Manager** .  
![_Install the VirtualBox Extension Pack](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/_Install-the-VirtualBox-Extension-Pack.jpg)
5. Click on the**Install** icon and select the extension pack file you downloaded in step 3.
<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Click on the**Install** button, accept the**EULA** and click on the**I Agree** button.
7. Wait for the extension pack to install.
8. Run the virtual machine and try to connect the USB device to it.

### 4\. Update VirtualBox

 An outdated version of VirtualBox can encounter errors. So, you need to update VirtualBox to fix the underlying bugs and get access to new features offered by the developers. Here’s how to update VirtualBox on Windows.

1. Launch VirtualBox on your system. It will automatically notify you if a newer version is available. You can go to**Help > About VirtualBox** and check the current version info there.
2. Then, navigate to**Help > VirtualBox Web Site** . It will redirect you to the official website.
3. Click on the**Downloads** section and download the latest version. Also, download the corresponding extension pack.
4. Close the VirtualBox app and end all associated processes using Task Manager.
5. Run the downloaded executable file and follow the on-screen instructions to install it on your system. Also, install the extension pack as illustrated in Method 3 above.
6. Now, try to connect the USB device to the virtual machine using the settings menu.

### 5\. Configure the USB Controller in Virtual Machine Settings

 A mismatch in the USB controller settings can also produce the VirtualBox error. If you want to add a USB device to the VirtualBox virtual machine, you must select the correct USB controller option in the USB settings.

1. Open VirtualBox and click on the virtual machine to which you want to add the USB drive.
2. Click on the**Settings** icon on the top. Then click on the**USB** option in the list.
3. Firstly, click the**Enable USB controller** checkbox to enable the USB device attaching feature to the virtual machine.
4. Then, select the USB 2.0 or 3.0 controller option located below the**Enable USB controller** option.  
![Configure the USB Controller](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Configure-the-USB-Controller.jpg)
5. Now, click on the**Add new USB filter** and pick the USB device you want to connect to the virtual machine.
6. Click on the**OK** button and close the settings window. Start the virtual machine and check if the error pops up now.

### 6\. Reinstall the VBox USB drivers

 Corrupt or missing VBox USB drivers on your system could cause the Virtual Box error code. Reinstalling the USB drivers can fix the driver issue and allow USB devices to connect with the virtual machine.

1. Launch File Explorer on your Windows system. Visit the following path:**C:\\Program Files\\Oracle\\VirtualBox\\drivers\\USB**
2. Navigate to the**Device** subfolder and find the**VBoxUSB.inf** file.
3. Right-click on the file and select the**Install** option.
4. Now, navigate to the**Filters** subfolder and locate the**VBoxUSBMon.inf** file.
5. Right-click on the file and select the**Install** option.
6. Close Virtual Box and restart your system. Connect the USB device to the virtual machine and check whether the error code pops up.

### 7\. Reinstall VirtualBox

 If all the above methods don’t solve the ‘Failed to Attach the USB Device’ Error code, consider reinstalling the VirtualBox app on your system. Here’s how to do it.

1. Press the**Win + R** key to launch the Run command box (see[how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways). Type**appwiz.cpl** and press the enter key. The Programs and Features window will launch.
2. Locate VirtualBox from the list of installed programs and double-click on it.  
![Reinstall VirtualBox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Reinstall-VirtualBox.jpg)
3. **UAC** will pop up. Click on**Yes** to continue.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411"><img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Follow the on-screen prompts to uninstall VirtualBox from your system.
5. Now visit the[official VirtualBox website](https://www.virtualbox.org/wiki/Downloads) and download the app and the corresponding extension pack.
6. Open the download location and run the setup file. Follow the on-screen prompts to install and then install the extension pack as described in method 3.
7. Now, attach a USB device and start the virtual machine to check if the error code occurs or not.

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
## Easily Connect USB Devices to Your Virtual Machine Once More

 VirtualBox needs the extension pack to enable connectivity for USB 2.0 and 3.0 devices. Check your USB devices for errors and verify that they mount properly on the host system. Reinstall USB drivers if you face the error again. Lastly, remove VirtualBox from the system and do a fresh installation.


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
<li><a href="https://facebook-video-files.techidaily.com/new-2024-approved-echoes-of-everyday-events/"><u>[New] 2024 Approved  Echoes of Everyday Events</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-rhythmic-repository-perfect-dj-templates-instantly-downloadable/"><u>[New] 2024 Approved  Rhythmic Repository  Perfect DJ Templates, Instantly Downloadable</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-unleash-creative-potential-with-free-effs/"><u>[New] 2024 Approved  Unleash Creative Potential with Free Effs!</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-affordable-facetime-replacements-for-android-for-2024/"><u>[New] Affordable FaceTime Replacements for Android for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-connect-to-a-real-time-tiktok-livestayers-world/"><u>[New] Connect to a Real-Time TikTok Livestayer's World</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-harness-the-power-of-keywords-top-selection-software-unveiled-for-2024/"><u>[New] Harness the Power of Keywords  Top Selection Software Unveiled for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-capture-and-share-immedienas-unprecedented-journey-with-dslr-and-facebook-live/"><u>[New] In 2024, Capture and Share Immedienas Unprecedented Journey with DSLR & Facebook LIVE</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-capturing-adrenaline-with-the-latest-yi-technology/"><u>[Updated] 2024 Approved  Capturing Adrenaline with the Latest Yi Technology</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-beauty-blogging-101-starting-up-as-an-aesthetic-vlogger-for-2024/"><u>[Updated] Beauty Blogging 101  Starting Up as an Aesthetic Vlogger for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-epicmosaic-insta-video-fusion-for-iosandroid/"><u>[Updated] EpicMosaic  Insta Video Fusion for iOS/Android</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-subtle-reduction-of-volume-in-fl-studio/"><u>[Updated] In 2024, Subtle Reduction of Volume in FL Studio</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-which-livestreaming-tool-wins-obs-or-bandicam/"><u>[Updated] In 2024, Which Livestreaming Tool Wins  OBS or Bandicam?</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-integrating-picture-in-picture-the-essentials-of-ms-edge/"><u>[Updated] Integrating Picture-in-Picture  The Essentials of MS Edge</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-unveil-the-power-of-vrecorder-installs-demystified/"><u>2024 Approved  Unveil the Power of VRecorder  Installs Demystified</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-insights-selecting-the-right-os-for-gaming-glory/"><u>Expert Insights: Selecting the Right OS for Gaming Glory</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-strategies-for-windows-activation-failure-0x803f700f/"><u>Expert Strategies for Windows Activation Failure: 0X803F700f</u></a></li>
<li><a href="https://windows11.techidaily.com/festive-glamour-unveiled-in-decorative-windows/"><u>Festive Glamour Unveiled in Decorative Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-error-lost-access-to-ubisoft-game-launcher/"><u>Fixing Windows Error: Lost Access to Ubisoft Game Launcher</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/gear-up-with-smart-techniques-elevating-your-ps4-gameplay-capture-abilities-for-2024/"><u>Gear Up with Smart Techniques  Elevating Your PS4 Gameplay Capture Abilities for 2024</u></a></li>
<li><a href="https://sound-issues.techidaily.com/get-your-creative-pebble-audio-players-up-and-running-with-these-proven-repair-techniques/"><u>Get Your Creative Pebble Audio Players Up and Running with These Proven Repair Techniques</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-on-lenovo-thinkphone-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location on Lenovo ThinkPhone | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-error-code-e84-on-steam-for-windows/"><u>How to Fix the Error Code E84 on Steam for Windows</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-audiovisual-debut-breakdown/"><u>In 2024, Audiovisual Debut Breakdown</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-how-to-intercept-text-messages-on-apple-iphone-xs-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Intercept Text Messages on Apple iPhone XS | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-innovative-ways-to-document-your-virtual-sessions-mac-and-pc-edition/"><u>In 2024, Innovative Ways to Document Your Virtual Sessions - Mac & PC Edition</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-mastering-the-art-of-navigating-telegram-web-applications/"><u>In 2024, Mastering the Art of Navigating Telegram Web Applications</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-outlining-expenses-creating-a-music-video/"><u>In 2024, Outlining Expenses  Creating a Music Video</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-pokemon-go-error-12-failed-to-detect-location-on-honor-magic-6-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Pokemon Go Error 12 Failed to Detect Location On Honor Magic 6 Pro? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/innovative-synergy-windows-enables-iphone-and-ipad-with-desktop-power/"><u>Innovative Synergy: Windows Enables iPhone & iPad with Desktop Power</u></a></li>
<li><a href="https://windows11.techidaily.com/instant-wallpaper-update-the-simple-windows-method/"><u>Instant Wallpaper Update: The Simple Windows Method</u></a></li>
<li><a href="https://windows11.techidaily.com/launching-wordpad-windows-users-handbook/"><u>Launching WordPad: Windows User's Handbook</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/learn-how-to-lock-stolen-your-apple-iphone-15-plus-properly-by-drfone-ios/"><u>Learn How To Lock Stolen Your Apple iPhone 15 Plus Properly</u></a></li>
<li><a href="https://windows11.techidaily.com/masterful-manipulation-of-your-identity-name-on-windows-11/"><u>Masterful Manipulation of Your Identity Name on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11s-context-menu-with-additional-software-icons/"><u>Mastering Windows 11'S Context Menu with Additional Software Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11s-fast-flip-buttons/"><u>Mastering Windows 11'S Fast Flip Buttons</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-errors-with-amd-195-setup/"><u>Mastering Windows Errors with AMD 195 Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-maintaining-your-note-apps-data/"><u>Mastery Over Maintaining Your Note App's Data</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-muted-powershell-scripts-four-tactics-to-counter-error-message/"><u>Mastery Over Muted PowerShell Scripts: Four Tactics to Counter Error Message</u></a></li>
<li><a href="https://windows11.techidaily.com/microsoft-family-safety-your-complete-reference/"><u>Microsoft Family Safety: Your Complete Reference</u></a></li>
<li><a href="https://windows11.techidaily.com/minmax-cpu-states-navigating-windows-power-control/"><u>Min/Max CPU States: Navigating Windows Power Control</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-glance-at-recent-files-in-windows/"><u>Quick Glance at Recent Files in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/reinitializing-windows-updates-a-step-by-step-guide/"><u>Reinitializing Windows Updates: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-unsupported-boots-a-5-step-windows-guide/"><u>Resolving Unsupported Boots: A 5-Step Windows Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-disappearing-results-from-windows-1011-search-tool/"><u>Solving Disappearing Results From Windows 10/11 Search Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-microsoft-store-glitch-error-code-0x800704cf/"><u>Steps to Resolve Microsoft Store Glitch (Error Code 0X800704CF)</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlined-method-for-enabling-windows-11-calculator/"><u>Streamlined Method for Enabling Windows 11 Calculator</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-guidance-for-choosing-between-nvidia-gamestudio-drivers/"><u>Tailored Guidance for Choosing Between Nvidia Game/Studio Drivers</u></a></li>
<li><a href="https://network-issues.techidaily.com/titans-triumph-god-of-war-fixes/"><u>Titans Triumph: God of War Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/unearthing-bsod-traces-within-windows-vista2008/"><u>Unearthing BSOD Traces Within Windows Vista/2008</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-productivity-a-guide-to-making-multiple-directories-at-once-in-windows/"><u>Unleashing Productivity: A Guide to Making Multiple Directories at Once in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-full-potential-of-windows-11s-tabbed-views/"><u>Unlock the Full Potential of Windows 11'S Tabbed Views</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-10-product-key-our-guide-to-the-top-deals/"><u>Windows 10 Product Key: Our Guide to the Top Deals</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/winview-now-sharp-and-clear/"><u>WinView Now Sharp and Clear</u></a></li>
</ul></div>
