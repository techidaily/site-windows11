---
title: Boost Security in VirtualBox via Secure Boot Toggle
date: 2024-06-25T12:19:10.090Z
updated: 2024-06-26T12:19:10.090Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Boost Security in VirtualBox via Secure Boot Toggle
excerpt: This Article Describes Boost Security in VirtualBox via Secure Boot Toggle
keywords: VirtualBox Boost,Enhance VBox Security,Secure Boot Switch,Activate Secure Mode,Turn on Secure Boot,VBox Safety Toggle,Lock Box for Secure Access
thumbnail: https://thmb.techidaily.com/675815b145dcafd84fe359ee4ac52511e6c57ba8907f6c40cdafb2c11a8f5a83.jpg
---

## Boost Security in VirtualBox via Secure Boot Toggle

 VirtualBox released version 7.0 in October 2022\. It is the first hypervisor to support the emulation of TPM chips along with all the other system components. VirtualBox also offers a Secure Boot feature in EFI mode for virtual machines. The main reason behind these two features was Microsoft's list of elaborate system requirements for Windows 11.

 Without emulation of the TPM 2.0 chip, users couldn't install Windows 11 on a virtual machine. But with VirtualBox 7.0 it is possible to enable Secure Boot and TPM for any Windows virtual machine. This post will elaborate on the methods to enable or disable TPM and Secure Boot for any VirtualBox virtual machine.

## Why Does Windows 11 Need TPM and Secure Boot?

 Windows 11 needs both a TPM chip and Secure Boot to offer robust protection against threats and not allow any malware to run when the system boots up. Secure Boot only allows signed drivers to load and the TPM chip helps in BitLocker drive data protection. So, both these features are pretty important from a security standpoint. Check out our guide on[what Secure Boot is and how it works](https://www.makeuseof.com/what-is-secure-boot-how-does-it-work/) for more information.

 While Windows 11 can work without Secure Boot and a TPM 2.0 chip, it won't be able to offer that extra layer of system protection it would do otherwise. Many features like Core-isolation, Data Encryption won't work. If you want to enable or disable these features for Windows 10 or 11 virtual machines, you can do so in VirtualBox 7.0.

## How to Enable or Disable Secure Boot and TPM Support in VirtualBox 7.0

 Repeat the following steps to enable TPM 2.0 and Secure Boot in VirtualBox.

1. Press the**Win** key and search VirtualBox. Click on the first relevant search result to launch the app.
2. Click on a Windows virtual machine and then click on the**Settings** icon.
3. Navigate to the**System** settings option.
4. Find the**TPM** option. If it is set to none, click on the**arrow** icon to open the drop-down menu.
5. Select the TPM**v2.0** option from the list. Windows 11 won't work with anything lower but if you are using Windows 10 then you can pick**v1.2** from the list.
6. Scroll down and locate the**Extended Features** section. Click on the**Enable EFI (special OSes only)** option check box.
7. Then click on the**Enable Secure Boot** option check box.  
![Enable Secure Boot and TPM Support in VirtualBox 7.0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/enable-secure-boot-and-tpm-support-in-virtualbox-7-0.jpg)
8. Now, click on the**OK** button. The settings window will close automatically.
9. Go to the top area and click on the**Start** button to power on the Windows virtual machine.
10. Now, press the Win key and search Security. Open the**Windows security** app.
11. Navigate to the left-hand side menu and click on the**Device Security** option. Here, all Windows security features will be active.
12. To disable TPM and Secure Boot, reopen the virtual machine settings and set the TPM version to**None** . Uncheck the**Enable EFI (special OSes only)** option check box. Click on**OK** to save the changes.

### An Alternative Method to Check if TPM Is Active in the Windows Virtual Machine

Here's how to check TPM on Windows 11 virtual machine:

1. Press the**Win + R** key to launch the Run command box (see[how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways). Type**TPM.msc** and press the**Enter** key.  
![check TPM on Windows 11 virtual machine 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-1.jpg)
2. TPM utility will launch. Navigate to the Manufacturer Information section.  
![check TPM on Windows 11 virtual machine 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-2.jpg)
3. If the Specification version entry showcases 2.0, it means that TPM chip emulation is successful.

## Manage TPM and Secure Boot Features in VirtualBox With Ease

 You can choose to keep both features active or not. After installing Windows 11 as a virtual machine, you can turn TPM and Secure Boot off and not face any issues with the operating system. However, remember that these are important from a security perspective.


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
<li><a href="https://windows11.techidaily.com/how-to-tweak-the-mouse-pointer-accessibility-settings-on-windows-11/"><u>How to Tweak the Mouse Pointer Accessibility Settings on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-window-11s-missing-clickables-problem/"><u>Solving Window 11'S Missing Clickables Problem</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-non-functional-shortcuts-with-windows-snips/"><u>Avoiding Non-Functional Shortcuts with Windows Snips</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-efficiency-advanced-tips-for-task-juggling-in-windows-11/"><u>Unlock Efficiency: Advanced Tips for Task Juggling in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-endorsed-top-10-for-windows-free-app-safety/"><u>Expert-Endorsed Top 10 for Windows FREE App Safety</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-resolving-windows-service-response-errors/"><u>Guide to Resolving Windows Service Response Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-reset-of-windows-icon-positions/"><u>Swift Reset of Windows Icon Positions</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-discord-from-launching-with-every-system-boots/"><u>Preventing Discord From Launching with Every System Boots</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-mysteries-of-ram-in-windows-devices/"><u>Decoding the Mysteries of RAM in Windows Devices</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-linguistic-inputs-utilize-no-fee-required/"><u>In 2024, Linguistic Inputs, Utilize No Fee Required</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-high-quality-action-captured-by-the-ion-pro-3-camera/"><u>2024 Approved  High-Quality Action Captured by the ION Pro 3 Camera</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/2024-approved-secrets-unveiled-saving-twitter-gifs-for-later-use/"><u>2024 Approved  Secrets Unveiled  Saving Twitter GIFs for Later Use</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-accurate-ranking-of-top-free-subtitle-makers-srt-online/"><u>In 2024, Accurate Ranking of Top Free Subtitle Makers (Srt) Online</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-trim-your-videos-like-a-pro-a-kapwing-tutorial/"><u>Updated Trim Your Videos Like a Pro A Kapwing Tutorial</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unraveling-iphones-audio-mystery-ringtone-adjustments/"><u>2024 Approved  Unraveling iPhone's Audio Mystery  Ringtone Adjustments</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/top-10-iconic-song-selections-for-inspiring-short-film-scenes-for-2024/"><u>Top 10 Iconic Song Selections for Inspiring Short Film Scenes for 2024</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-march-madness-score-big-with-our-exclusive-filmora-coupon-code/"><u>New 2024 Approved March Madness Score Big with Our Exclusive Filmora Coupon Code</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/in-2024-say-goodbye-to-shaky-videos-the-best-free-online-stabilizers/"><u>In 2024, Say Goodbye to Shaky Videos The Best Free Online Stabilizers</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-head-to-head-showdown-final-cut-pro-or-lumafusion-for-video-editing/"><u>Updated In 2024, Head-to-Head Showdown Final Cut Pro or LumaFusion for Video Editing?</u></a></li>
</ul></div>
