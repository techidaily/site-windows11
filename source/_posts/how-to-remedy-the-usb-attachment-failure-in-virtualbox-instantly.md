---
title: How to Remedy the USB Attachment Failure in VirtualBox Instantly
date: 2024-08-27T16:06:02.994Z
updated: 2024-08-28T16:06:02.994Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Remedy the USB Attachment Failure in VirtualBox Instantly
excerpt: This Article Describes How to Remedy the USB Attachment Failure in VirtualBox Instantly
keywords: Fixing VirtualBox USB Errors,Quick VirtualBox USB Solutions,Unblock USB in VirtualBox,Immediate USB Fix VBox,Stop USB Failure VirtualBox,Resolve USB Attachments VM,Bypass VirtualBox USB Hurdles
thumbnail: https://thmb.techidaily.com/dccea8e74312ef3978115e47791b42d8d3af59ddef7b2d9a4c85759dfb53f1ee.jpg
---

## How to Remedy the USB Attachment Failure in VirtualBox Instantly

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

### 1\. Restart VirtualBox

 Before you move on to other advanced fixes, restart the VirtualBox application. If restarting the app doesn’t work, restart Windows. It will restart all the processes and services including the ones VirtualBox needs to function properly. Now, connect a USB device and try to attach it to a virtual machine in VirtualBox. If it still doesn’t show up, move to the next fix.

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. Check the USB Device on the Host System

 Before trying to attach the USB device to the VirtualBox virtual machine, first check if it shows up on your host system. Launch the File Explorer and go to This PC and check if the USB drive appears there. If you don’t see the USB drive, do as follows:

1. First, open Device Manager. There are many[different ways to open the Device Manager](https://www.makeuseof.com/windows-open-device-manager/) , but a quick way is to press**Win + R** to launch the Run command box. Type**devmgmt.msc** and press the**Enter** key to launch the Device Manager.  
![Check the USB Device on the Host System](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Check-the-USB-Device-on-the-Host-System.jpg)
2. Navigate to the**Disk Drives** option and click the**arrow** icon to expand the section.
3. Find the USB drive you connected to the host system. If it is not present in the list, pull it out and reconnect it to another USB port on your system.

 If the USB port on your system malfunctions, the USB drive won’t show up in Device Manager or File Explorer. But if the USB drive doesn’t appear in the device manager even after changing the port, it could have a hardware malfunction. In that case, try connecting another USB drive to VirtualBox virtual machine.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 3\. Install the VirtualBox Extension Pack

 VirtualBox can only attach USB 1.0 devices to a virtual machine. You need to install the extension pack to add USB 2.0 or 3.0 devices. Here’s how to do it.

1. Open VirtualBox on your system and navigate to**Help > About VirtualBox** . Note the version currently installed on your system.
2. Launch any web browser on your system and go to the[official VirtualBox download page](https://www.virtualbox.org/wiki/Downloads) .
3. Click on the build number which is present on your system. Scroll down and download its corresponding extension pack.
4. Now, open VirtualBox. Navigate to**File > Tools > Extension Pack Manager** .  
![_Install the VirtualBox Extension Pack](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/_Install-the-VirtualBox-Extension-Pack.jpg)
5. Click on the**Install** icon and select the extension pack file you downloaded in step 3.
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
### 5\. Configure the USB Controller in Virtual Machine Settings

 A mismatch in the USB controller settings can also produce the VirtualBox error. If you want to add a USB device to the VirtualBox virtual machine, you must select the correct USB controller option in the USB settings.

1. Open VirtualBox and click on the virtual machine to which you want to add the USB drive.
2. Click on the**Settings** icon on the top. Then click on the**USB** option in the list.
3. Firstly, click the**Enable USB controller** checkbox to enable the USB device attaching feature to the virtual machine.
4. Then, select the USB 2.0 or 3.0 controller option located below the**Enable USB controller** option.  
![Configure the USB Controller](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Configure-the-USB-Controller.jpg)
5. Now, click on the**Add new USB filter** and pick the USB device you want to connect to the virtual machine.
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
6. Click on the**OK** button and close the settings window. Start the virtual machine and check if the error pops up now.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->
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
4. Follow the on-screen prompts to uninstall VirtualBox from your system.
5. Now visit the[official VirtualBox website](https://www.virtualbox.org/wiki/Downloads) and download the app and the corresponding extension pack.
6. Open the download location and run the setup file. Follow the on-screen prompts to install and then install the extension pack as described in method 3.
7. Now, attach a USB device and start the virtual machine to check if the error code occurs or not.

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
<li><a href="https://facebook-video-share.techidaily.com/new-elevate-learning-top-15-youtube-experts-in-science-for-2024/"><u>[New] Elevate Learning  Top 15 YouTube Experts in Science for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-elevate-your-instagram-shots-with-strategic-borders-for-2024/"><u>[New] Elevate Your Instagram Shots With Strategic Borders for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-the-ultimate-guide-to-finding-instagram-filters-for-no-cost/"><u>[New] In 2024, The Ultimate Guide to Finding Instagram Filters for No Cost</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-3-effective-methods-to-archive-itunes-videos/"><u>[Updated] 2024 Approved  3 Effective Methods to Archive iTunes Videos</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-revealing-the-rich-detail-of-your-roblox-journey/"><u>[Updated] Revealing the Rich Detail of Your Roblox Journey</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-surviving-in-mc-6-home-ideas-for-2024/"><u>[Updated] Surviving in MC  6 Home Ideas for 2024</u></a></li>
<li><a href="https://fox-that.techidaily.com/8-effective-solutions-for-enabling-smscall-alerts-in-iphones-do-not-disturb-mode/"><u>8 Effective Solutions for Enabling SMS/Call Alerts in iPhone's Do Not Disturb Mode</u></a></li>
<li><a href="https://driver-error.techidaily.com/alleviating-driver-conflicts-device-venint33a0/"><u>Alleviating Driver Conflicts - Device VEN_INT33A0</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-locked-for-security-reasons-from-apple-iphone-13-pro-max-find-the-best-solution-here-by-drfone-ios/"><u>Apple ID Locked for Security Reasons From Apple iPhone 13 Pro Max? Find the Best Solution Here</u></a></li>
<li><a href="https://techidaily.com/best-fixes-for-oppo-reno-10-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Oppo Reno 10 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/crafting-conversational-magic-how-to-write-podcast-scripts/"><u>Crafting Conversational Magic  How to Write Podcast Scripts</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/easy-steps-on-how-to-create-a-new-apple-id-account-on-apple-iphone-7-by-drfone-ios/"><u>Easy Steps on How To Create a New Apple ID Account On Apple iPhone 7</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-overcoming-outlook-crashing-issues/"><u>Essential Guide: Overcoming Outlook Crashing Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-resolving-winerror-0x8007043c-on-media-creator/"><u>Guide to Resolving WinError 0X8007043C on Media Creator</u></a></li>
<li><a href="https://windows11.techidaily.com/hidden-window-11-customization-marvels/"><u>Hidden Window 11 Customization Marvels</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-correctly-evaluate-processor-load-using-task-manager/"><u>How to Correctly Evaluate Processor Load Using Task Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-semaphore-timeout-period-has-expired-error-0x80070079-in-windows-1110/"><u>How to Fix the “Semaphore Timeout Period Has Expired” Error 0X80070079 in Windows 11/10</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-get-past-a-non-starting-battlenet-interface/"><u>How to Get Past a Non-Starting Battle.net Interface</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-apple-iphone-6s-to-other-iphone-drfone-by-drfone-ios/"><u>How to Mirror Apple iPhone 6s to Other iPhone? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-reset-gmail-password-on-poco-x5-devices-by-drfone-android/"><u>How to Reset Gmail Password on Poco X5 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-switch-off-mobility-features-on-win-11/"><u>How To Switch Off Mobility Features on Win 11</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-10-fake-gps-location-apps-on-android-of-your-nokia-c22-drfone-by-drfone-virtual/"><u>In 2024, 10 Fake GPS Location Apps on Android Of your Nokia C22 | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-teach-you-to-transfer-files-from-oppo-a78-5g-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways To Teach You To Transfer Files from Oppo A78 5G to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-a-step-by-step-approach-to-mastering-360-video-edits-in-premiere-pro/"><u>In 2024, A Step-by-Step Approach to Mastering 360° Video Edits in Premiere Pro</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-can-we-bypass-samsung-galaxy-s23plus-frp-by-drfone-android/"><u>In 2024, How Can We Bypass Samsung Galaxy S23+ FRP?</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-find-ispoofer-pro-activation-key-on-apple-iphone-xs-max-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Find iSpoofer Pro Activation Key On Apple iPhone XS Max? | Dr.fone</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-streamlining-submission-a-podcasters-guide/"><u>In 2024, Streamlining Submission  A Podcaster's Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-art-of-regaining-win-folder-entry/"><u>Master the Art of Regaining Win Folder Entry</u></a></li>
<li><a href="https://windows11.techidaily.com/masterful-cursor-adjustments-on-windows-11-systems/"><u>Masterful Cursor Adjustments on Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-heic-jpeg-conversions-on-windows/"><u>Mastering HEIC-JPEG Conversions on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-networks-with-precision-windows-ping-mastery/"><u>Navigating Networks with Precision: Windows' Ping Mastery</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-make-amazing-videos-on-your-mac-top-rated-video-editing-tools/"><u>New Make Amazing Videos on Your Mac Top-Rated Video Editing Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/offline-browsing-of-onedrive-files-on-windows-pc/"><u>Offline Browsing of OneDrive Files on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-11s-uptime-failure-error-code-0x80246007/"><u>Overcoming Windows 11’S Uptime Failure: Error Code 0X80246007</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-access-to-command-prompt-easily-set-up-shortcuts/"><u>Quick Access to Command Prompt: Easily Set Up Shortcuts</u></a></li>
<li><a href="https://windows11.techidaily.com/reactivating-defenders-a-step-by-step-guide-for-five-common-issues/"><u>Reactivating Defenders: A Step-by-Step Guide for Five Common Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstate-audio-preferences-winvolume-issue-resolution/"><u>Reinstate Audio Preferences: WinVolume Issue Resolution</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-rpc-issues-on-windows-key-strategies/"><u>Resolving RPC Issues on Windows: Key Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-integration-outlook-preview-for-windows-11-users/"><u>Seamless Integration: Outlook Preview for Windows 11 Users</u></a></li>
<li><a href="https://extra-resources.techidaily.com/soulful-selection-candid-songs-that-perfectly-match-your-yes/"><u>Soulful Selection  Candid Songs that Perfectly Match Your 'Yes'</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-realign-file-history-configurations-in-windows/"><u>Steps to Realign File History Configurations in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-workflow-with-the-ultimate-win-11-guide/"><u>Streamline Your Workflow with the Ultimate Win 11 Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-windows-write-operations-error/"><u>Tackling Windows Write Operations Error</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-guide-to-windows-11-widget-bar-activation/"><u>The Essential Guide to Windows 11 Widget Bar Activation</u></a></li>
<li><a href="https://windows11.techidaily.com/the-secure-offline-window-improvement-process/"><u>The Secure, Offline Window Improvement Process</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-windows-11-help-app-restoration/"><u>Tips for Windows 11 Help App Restoration</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-windows-1011-8-innovative-personalization-techniques/"><u>Unlock Windows 10/11: 8 Innovative Personalization Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-secrets-of-winservicesexe/"><u>Unlocking the Secrets of Winservices.exe</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/unparalleled-video-intros-made-easy-with-online-tools/"><u>Unparalleled Video Intros Made Easy with Online Tools</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unveiling-8-compelling-arguments-for-teachers-and-ai/"><u>Unveiling 8 Compelling Arguments for Teachers and AI</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-mechanics-of-windows-11s-efficient-file-safety-measures/"><u>Unveiling the Mechanics of Windows 11'S Efficient File Safety Measures</u></a></li>
<li><a href="https://windows11.techidaily.com/what-to-do-when-your-recent-discord-updates-breakdown-on-windows/"><u>What to Do When Your Recent Discord Updates Breakdown on Windows</u></a></li>
</ul></div>
