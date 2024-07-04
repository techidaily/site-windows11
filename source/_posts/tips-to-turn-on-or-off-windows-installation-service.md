---
title: Tips to Turn On or Off Windows Installation Service
date: 2024-06-25T12:34:33.355Z
updated: 2024-06-26T12:34:33.355Z
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

 You can also use the group policy editor to enable or disable the Windows Installer service on your Windows computer system. However, it is important to note that this tool only works on Windows Pro and Enterprise editions. Therefore, if you are using Windows Home Edition, you must first[activate the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 To disable the service using the group policy editor, do the following:

1. Click on Start and type in**gpedit.msc** , then press**Enter** to[launch the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) .
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

1. Press**Win + X** , type**regedit** , and press**Enter** to launch the Registry Editor. To learn more, see our guide on how to[open the Registry Editor on Windows](https://www.makeuseof.com/windows-11-open-registry-editor/) .
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
<li><a href="https://windows11.techidaily.com/erase-secure-questions-a-guide-to-altering-local-account-in-win-11/"><u>Erase Secure Questions: A Guide to Altering Local Account in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-battlenet-speed-a-win-pc-strategy-guide/"><u>Boosting Battle.net Speed: A Win-PC Strategy Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-windows-pc-boosters-for-speed-and-efficiency/"><u>Top 5 Windows PC Boosters for Speed and Efficiency</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-and-personalize-the-ultimate-desktop-guide-for-win11-users/"><u>Streamline & Personalize: The Ultimate Desktop Guide for Win11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-the-typhoon-of-erratic-windows-mouse-wheel/"><u>Taming the Typhoon of Erratic Windows Mouse Wheel</u></a></li>
<li><a href="https://windows11.techidaily.com/clandestine-control-center-hidepower-command-of-windows-11/"><u>Clandestine Control Center: Hidepower Command of Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tuning-taskbars-date-and-time-presentation/"><u>Fine-Tuning Taskbar's Date & Time Presentation</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-delete-icloud-account-from-apple-iphone-se-without-password-by-drfone-ios/"><u>In 2024, How to Delete iCloud Account From Apple iPhone SE without Password?</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-free-mov-video-editors-no-watermark-no-cost/"><u>New Free MOV Video Editors No Watermark, No Cost</u></a></li>
<li><a href="https://techidaily.com/how-to-install-the-latest-iosipados-beta-version-on-apple-iphone-6-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Install the Latest iOS/iPadOS Beta Version on Apple iPhone 6? | Dr.fone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-the-comprehensive-tutorial-for-gameplay-logging-enthusiasts-for-2024/"><u>[Updated] The Comprehensive Tutorial for Gameplay Logging Enthusiasts for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/proiphone-close-up-techniques-unlocking-creative-vision-for-2024/"><u>Proiphone Close-Up Techniques  Unlocking Creative Vision for 2024</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-3-effective-ways-to-unlock-icloud-account-without-password-from-iphone-8-by-drfone-ios/"><u>In 2024, 3 Effective Ways to Unlock iCloud Account Without Password From iPhone 8</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-how-to-change-ratio-of-video-in-a-quick-and-easy-way/"><u>Updated How to Change Ratio of Video in a Quick & Easy Way</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-enhancing-your-playback-quality-tips-for-roblox-recordings-mac/"><u>[Updated] In 2024, Enhancing Your Playback Quality  Tips for Roblox Recordings (Mac)</u></a></li>
</ul></div>
