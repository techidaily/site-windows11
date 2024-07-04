---
title: "Detailed Guide: Turning Secure Boot and TPM On/Off in VBox"
date: 2024-06-25T12:34:47.331Z
updated: 2024-06-26T12:34:47.331Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Detailed Guide: Turning Secure Boot and TPM On/Off in VBox"
excerpt: "This Article Describes Detailed Guide: Turning Secure Boot and TPM On/Off in VBox"
keywords: VM Secure Boot Guide,TPM Control in Virtualbox,Enable VBOX TPM,Disable Secure Boot VBox,Turnoff VBox TPM,On/Off Secure Boot VM,Manage VBox TPM Settings
thumbnail: https://thmb.techidaily.com/b2e687db976d53413ad200065943dddbaf2bd03eb2c28e9e47c24fc4c8af2aa4.jpg
---

## Detailed Guide: Turning Secure Boot and TPM On/Off in VBox

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
<li><a href="https://windows11.techidaily.com/how-to-ditch-intels-onboard-graphics-in-windows/"><u>How to Ditch Intel's Onboard Graphics in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-windows-extract-error-1152-quickly/"><u>Eliminating Windows Extract Error 1152 Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-control-for-apps-and-browsers/"><u>Unveiling Windows Control for Apps & Browsers</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-frozen-overlays-restoring-function-to-discord-ui/"><u>Addressing Frozen Overlays: Restoring Function to Discord UI</u></a></li>
<li><a href="https://windows11.techidaily.com/safeguard-files-with-windows-controlled-access-feature/"><u>Safeguard Files with Window's Controlled Access Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-for-no-sound-when-screencasting-with-powerpoint/"><u>Troubleshooting for No Sound when Screencasting with PowerPoint</u></a></li>
<li><a href="https://windows11.techidaily.com/what-to-do-when-the-audio-services-are-not-responding-on-windows/"><u>What to Do When the Audio Services Are Not Responding on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/leap-into-connectivity-unlocking-windows-remote-desktop/"><u>Leap Into Connectivity: Unlocking Windows Remote Desktop</u></a></li>
<li><a href="https://howto.techidaily.com/fixing-persistent-pandora-crashes-on-realme-gt-neo-5-se-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixing Persistent Pandora Crashes on Realme GT Neo 5 SE | Dr.fone</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-gopro-video-editing-software-for-pc-quik-and-its-competitors-for-2024/"><u>Updated GoPro Video Editing Software for PC Quik and Its Competitors for 2024</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-the-ultimate-path-to-tiktok-fun-for-macbook-owners/"><u>[Updated] The Ultimate Path to TikTok Fun for MacBook Owners</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-ultimate-guide-to-selecting-and-utilizing-top-6-gopro-attachments-for-2024/"><u>The Ultimate Guide to Selecting & Utilizing Top 6 GOPRO Attachments for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/simplified-strategies-for-engaging-with-facebook-insights-for-2024/"><u>Simplified Strategies for Engaging with Facebook Insights for 2024</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/1713963020773-updated-follow-the-trend-of-making-slow-motion-videos-with-a-camera-lenta-capcut-template-learn-everything-about-capcut-and-find-its-alternatives-in-this-ar/"><u>Updated Follow the Trend of Making Slow-Motion Videos with a Camera Lenta CapCut Template. Learn Everything About CapCut and Find Its Alternatives in This Article for 2024</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-popular-sites-to-free-download-guitar-background-photos-and-music-for-2024/"><u>Updated Popular Sites to Free Download Guitar Background Photos and Music for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/n-2024-a-beginners-guide-to-elevating-auditory-experiences-on-youtube/"><u>[New] In 2024, A Beginner's Guide to Elevating Auditory Experiences on YouTube</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-ignite-conversations-tactics-for-facebook-impact/"><u>In 2024, Ignite Conversations  Tactics for Facebook Impact</u></a></li>
</ul></div>
