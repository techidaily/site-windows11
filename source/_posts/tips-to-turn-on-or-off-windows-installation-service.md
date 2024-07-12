---
title: Tips to Turn On or Off Windows Installation Service
date: 2024-07-11T21:56:44.874Z
updated: 2024-07-12T21:56:44.874Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tips to Turn On or Off Windows Installation Service
excerpt: This Article Describes Tips to Turn On or Off Windows Installation Service
keywords: Enable Windows Service,Disable Windows Service,Windows Setup Tips,Start Windows Install,Turn Windows On/Off,Control Windows Installer,Windows Service Control
thumbnail: https://thmb.techidaily.com/d9567f73a6de787d2d45f5ed6e24adff2914444a4a5e563757f01047c1bbc480.jpg
---

## Tips to Turn On or Off Windows Installation Service

 Are you looking for a way to disable the Windows Installer Service on your device? This essential component of your operating system performs all necessary installation processes, but can sometimes interfere with other programs.

 Fortunately, there are three ways in which it can be disabled—using the Windows Service tool, Group Policy Editor, or Registry Editor. Check out our guide below to learn how.

## 1\. Use Windows Services

 Windows services are critical programs that typically initiate when you start your computer. It runs silently in the background and provides essential features to run the operating system. If you're looking to enable or disable Windows Installer service using this tool, do the following.

 To begin, press**Win + R** on your keyboard to launch the Run dialog box. In the text box, type**services.msc** , and hit enter. This will open the Services window.

![Disable Windows Installer Service Using Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-services-window.jpg)

 In the window that opens, scroll down until you find**Windows Installer** service then double-click on it for a properties window to open.

 Once you're in the Properties window, click the**Startup type** drop-down menu and select**Automatic** . Now move over towards the**Service status** section and click**Stop** .

![Disable Windows Installer Service Using Windows Services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-windows-services.jpg)

 After you've done that, click**Apply** and then**OK** to save the changes. You have now successfully disabled the Windows Installer service on Windows 11.

 If you ever need to re-enable the service, follow the same procedure and click**Start** in the Service status section.

## 2\. Use Local Group Policy Editor

 You can also use the group policy editor to enable or disable the Windows Installer service on your Windows computer system. However, it is important to note that this tool only works on Windows Pro and Enterprise editions. Therefore, if you are using Windows Home Edition, you must first [activate the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 To disable the service using the group policy editor, do the following:

1. Click on Start and type in**gpedit.msc** , then press**Enter** to [launch the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) .
2. On the left side of the window, navigate to the path:  
`Computer Configuration > Administrative Templates > Windows Components > Windows Installer`
3. Now move to the right and double-click on the policy named**Turn off Windows Installer** .  
![Disable Windows Installer Service Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-group-policy.jpg)
4. In the window that opens, select**Enabled** in the radio box.
5. Under Options, click the drop-down menu and select**Always** .
6. Then click**Apply** and**OK** to save changes.

 That's all there is to it. The Windows Installer service will now be disabled on your system. To re-enable it, simply follow the same steps, but set "Turn off Windows Installer" to**Not Configured** .

## 3\. Use the Registry Editor

 Registry Editor is another method you can use to enable or disable the Windows Installer service on any version of Windows, even Home Edition. But make sure to proceed with caution as any incorrect changes can corrupt your system and force you to reinstall Windows. So be mindful and remember to back up your registry before making any modifications.

 To enable or disable this service using Registry Editor, follow these steps:

1. Press**Win + X** , type**regedit** , and press**Enter** to launch the Registry Editor. To learn more, see our guide on how to [open the Registry Editor on Windows](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. If prompted with a UAC warning, click**Yes** to continue.
3. Now once you're in, navigate to the following path:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\msiserver`
4. In the right panel, double-click on**Start** and change its value from**2** to**4** .  
![Disable Windows Installer Service Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-registry-editor.jpg)

 Once you put the Value data, make sure the Base is set to**Hexadecimal** , then click**OK** . Now close the registry editor and restart your computer for the changes to take effect.

## Turning Off the Windows Installer Service Made Easy

 If Windows Installer Service is creating issues or hindering another application, you can easily turn it off with one of the three methods outlined in our guide. See which method works best for you and get back to what matters most.


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
<li><a href="https://windows11.techidaily.com/a-step-by-step-for-erasing-sign-in-email-in-win/"><u>A Step-By-Step for Erasing Sign-In Email in Win</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-the-8-anomalies-in-windows-11s-ui/"><u>Dissecting the 8 Anomalies in Windows 11'S UI</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-change-oppo-reno-11-pro-5g-lock-screen-clock-in-seconds-by-drfone-android/"><u>In 2024, How To Change Oppo Reno 11 Pro 5G Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-the-hidden-weapons-for-social-media-dominance-on-instagram/"><u>In 2024, The Hidden Weapons for Social Media Dominance on Instagram</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-the-essential-guide-to-verifying-your-youtube-profile/"><u>[New] 2024 Approved  The Essential Guide to Verifying Your YouTube Profile</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-routes-to-printer-control-in-windows-11-max-50-chars/"><u>Efficient Routes to Printer Control in Windows 11 (Max 50 Chars)</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-the-ultimate-guide-to-the-best-video-editors-not-on-youtoo/"><u>[New] The Ultimate Guide to the Best Video Editors Not on YouToo</u></a></li>
<li><a href="https://windows11.techidaily.com/hidden-panels-revealed-recovering-offscreen-windows-in-edges-os/"><u>Hidden Panels Revealed: Recovering Offscreen Windows in Edges OS</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-from-outdated-to-outstanding-personalizing-your-tiktok-profile/"><u>2024 Approved  From Outdated to Outstanding  Personalizing Your TikTok Profile</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-itel-a60s-frp-by-drfone-android/"><u>In 2024, Step-by-Step Tutorial How To Bypass Itel A60s FRP</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-utorrent-client-not-downloading-files-or-stuck-on-connecting-to-peers-on-windows/"><u>How to Fix the uTorrent Client Not Downloading Files or Stuck on Connecting to Peers on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/easing-windows-woes-with-adobe-ps/"><u>Easing Windows Woes with Adobe PS</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-usb-resources-on-pcs/"><u>Enhancing USB Resources on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-windows-aggregatorhostexe-functions-risks-and-safety-concerns/"><u>Decoding Windows' AggregatorHost.exe: Functions, Risks, and Safety Concerns</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-find-rich-ambiance-for-video-content/"><u>In 2024, Find Rich Ambiance for Video Content</u></a></li>
<li><a href="https://windows11.techidaily.com/chronicle-of-windows-seven-enduring-traits-in-the-new-era-of-11/"><u>Chronicle of Windows: Seven Enduring Traits in the New Era of 11</u></a></li>
<li><a href="https://windows11.techidaily.com/escape-without-errors-tips-for-a-well-functioning-key-on-windows/"><u>Escape Without Errors: Tips for a Well-Functioning Key on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/free-media-titans-for-effortless-windows-experience/"><u>Free Media Titans for Effortless Windows Experience</u></a></li>
<li><a href="https://extra-information.techidaily.com/access-your-screen-star-downloadable-rights-for-2024/"><u>Access Your Screen Star  Downloadable Rights for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-the-perfect-keys-list-for-win11s-narrator-control/"><u>Crafting the Perfect Keys List for Win11's Narrator Control</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-prevalent-anydesk-errors-in-windows/"><u>Decoding Prevalent AnyDesk Errors in Windows</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-unveiling-15-favorite-youtube-video-intros-for-2024/"><u>[Updated] Unveiling 15 Favorite YouTube Video Intros for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-instaflash-compile-your-pics-fast-for-2024/"><u>[New] InstaFlash  Compile Your Pics Fast for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-deleted-photos-on-blaze-curve-5g-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to Retrieve deleted photos on Blaze Curve 5G</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-social-media-showdown-continues-the-ongoing-debate-on-igtv-and-youtube/"><u>[Updated] Social Media Showdown Continues  The Ongoing Debate on IGTV and YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-your-experience-altering-device-settings-in-windows-11/"><u>Customize Your Experience: Altering Device Settings in Windows 11</u></a></li>
<li><a href="https://discord-videos.techidaily.com/how-to-craft-strikingly-attractive-pfps-for-your-discolife-in-discord/"><u>How To Craft Strikingly Attractive Pfps for Your DiscoLife in Discord</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-synchronized-sound-and-picture-zone-online/"><u>2024 Approved  Synchronized Sound & Picture Zone Online</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-elite-7-dslr-options-superior-for-professional-videography/"><u>2024 Approved  Elite 7 DSLR Options Superior for Professional Videography</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-endorsed-top-10-for-windows-free-app-safety/"><u>Expert-Endorsed Top 10 for Windows FREE App Safety</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-30-must-have-youtube-intros-tools-for-beginners-all-free/"><u>[Updated] In 2024, 30 Must-Have YouTube Intros Tools for Beginners, All Free</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-vlc-recorder-functionality-check/"><u>[Updated] In 2024, VLC Recorder  Functionality Check</u></a></li>
<li><a href="https://windows11.techidaily.com/audio-visual-verification-a-windows-users-pre-meet-checklist/"><u>Audio Visual Verification: A Windows User’s Pre-Meet Checklist</u></a></li>
<li><a href="https://windows11.techidaily.com/bringing-print-functionality-to-microsofts-secure-edge/"><u>Bringing Print Functionality to Microsoft's Secure Edge</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-windows-index-settings/"><u>Configuring Windows Index Settings</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-maximize-visibility-resizing-your-youtube-images-effectively/"><u>[Updated] Maximize Visibility  Resizing Your YouTube Images Effectively</u></a></li>
<li><a href="https://windows11.techidaily.com/discovering-devhome-the-essential-guide-to-win11/"><u>Discovering DevHome: The Essential Guide to Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-it-fast-dealing-with-microsoft-store-errors-in-1011-systems/"><u>Fix It Fast: Dealing with Microsoft Store Errors in 10/11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-limitations-for-power-use-in-winos/"><u>Bypassing Limitations for Power Use in WinOS</u></a></li>
</ul></div>
