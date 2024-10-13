---
title: Navigate Secure Boot Snags with These 5 Proven Fixes
date: 2024-10-08T18:28:19.681Z
updated: 2024-10-13T03:57:26.483Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigate Secure Boot Snags with These 5 Proven Fixes
excerpt: This Article Describes Navigate Secure Boot Snags with These 5 Proven Fixes
keywords: Secure Boot Troubleshooting,Boost Secure Boot,Resolve Boot Issues,Advanced Boot Fixing,Enhance System Security,Improve Boot Stability,Efficient Boot Solutions
thumbnail: https://thmb.techidaily.com/4cf629d041b7e9add58db2334da6e6c6bff213af23c974168630105d2e88b454.jpg
---

## Navigate Secure Boot Snags with These 5 Proven Fixes

 Secure Boot is a security feature that helps to ensure that only trusted applications are installed on the computer. Although this feature is enabled by default on most computers, you will still likely see the "Secure Boot state unsupported" error while installing Windows 11\.

 The error mainly appears when TPM is disabled on your computer. As such, if you're also facing the same problem, follow the fixes below to troubleshoot the problem for good.

## What Causes the "Secure Boot State Unsupported" Error?

[Secure Boot](https://www.makeuseof.com/what-is-secure-boot-how-does-it-work/) is a feature of modern computers that uses a digital signature to verify the authenticity of the system's software, especially the operating system's files. It is one of the minimum requirements to install Windows 11\.

 Although you can easily [bypass Windows 11's minimum requirements](https://www.makeuseof.com/bypass-windows-11-minimum-installation-requirements/), doing so would adversely affect your computer. You could expect your device to slow down or even crash on a frequent basis.

 Some of the common reasons behind the "Secure Boot state unsupported" error are:

1. You'll likely see the error message if TPM is disabled or not installed on your computer.
2. The error message will appear if Secure Boot is disabled in the BIOS.
3. You'll also encounter the error if BIOS mode is set to Legacy instead of UEFI.

 Now, let's dive into fixes that will help you eliminate the problem.

## 1\. Enable Secure Boot in BIOS

 You must enable Secure Boot in BIOS if you want to install Windows 11 on your computer. But before doing that, view Secure Boot's current state. Here's how to do it:

1. Press the **Win + R** hotkey to open the Run dialog box. Then, type **msinfo32,** and press **Enter**. It'll [open the System information window](https://www.makeuseof.com/windows-open-system-information/).
2. Click **System** **Summary** in the left panel.
3. Check the **Secure Boot State** in the right pane.  
![Secure Boot State in System Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Secure-Boot-State.jpg)

 If the Secure Boot status is **Off**, you'll have to enable it through your BIOS. To do that, follow the instructions:

1. Open the Settings menu by pressing the Win + I hotkey, and navigate to **System** \> **Recovery.**
2. Click **Restart now** next to **Advanced startup.** It'll restart your computer.  
![Restart Now option next to Advanced Startup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Restart-Now-option.jpg)
3. In the Advanced startup mode, choose **Troubleshoot** and then **Advanced options.**
4. Choose **UEFI Firmware Settings** and click **Restart.** I'll boot you straight into Windows UEFI BIOS.
5. Choose **BIOS Setup.**
6. Switch to **Secure Boot.**
7. Check the box before **Secure Boot Enable.**  
![Enable Secure Boot in BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Enable-Secure-Boot-1.jpg)

 Note that the steps to [enable Secure Boot](https://www.makeuseof.com/how-enable-tpm-secure-boot-before-upgrading-windows-11/) will be different for different manufacturers. You can check out your manufacturer's BIOS page to know how to do it on your computer.

 Once you've enabled Secure Boot, try to install Windows and check if the problem continues. If yes, then try the next solution on the list.

## 2\. Check and Enable TPM Support

 You must have the TPM chip installed on your computer to download Windows 11\. If the TPM chip is missing, you can still install Windows 11 by bypassing the minimum requirement, but then the "Secure Boot state unsupported" error will continue to bother you now and then.

 The problem in the discussion can also appear if TPM is disabled on your computer. To enable TPM, follow the below instructions:

1. Open the Run dialog box.
2. In the search bar, type **tpm.msc** and press Enter.
3. In the TPM management window, click **Actions** in the top bar.
4. Choose **Prepare the TPM** from the context menu.  
![Prepare the TPM in TPM Management Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Prepar-the-TPM.jpg)

 Restart your computer and check for the problem.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075475/7443" target="_top" id="2075475">
  <img src="//a.impactradius-go.com/display-ad/7443-2075475" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Choose UEFI as the BIOS' Mode

 Windows supports two BIOS modes–**UEFI** and **Legacy**. The difference between these two modes is in the process that the firmware uses to locate the boot target.

 You must install Windows using the new UEFI mode as it offers more security features than the Legacy BIOS mode.

 To choose UEFI as the BIOS mode, follow the below steps:

1. Open the BIOS page on your computer.
2. Choose **Boot Sequence** from the left panel.
3. Check the **UEFI option** under **Boot List** Options.  
![UEFI Option in BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/UEFI-Option.jpg)
4. Save the changes and restart your computer.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135373/19272" target="_top" id="2135373">
  <img src="//a.impactradius-go.com/display-ad/19272-2135373" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135373/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Again, the process will differ for different manufacturers; therefore, you must check your manufacturer's BIOS page to know how to do it on your computer.

## 4\. Convert the Partition Style From MBR to GPT

 In modern computers, the boot mode is set to UEFI and has GPT (GUID Partition Style) partition style. However, if your computer is using Legacy Boot mode and MBR (Master Boot Record) partition style, then you will face the problem at hand.

 The solution, in this case, is to convert the partition style from MBR to GPT. But before doing that, you must check your computer partition style. Here's how:

1. Press **Win + X** to open the **Power menu.**
2. Choose **Disk Management.**
3. In the Disk Management window, right-click on the hard disk drive and choose **Properties** from the context menu.  
![Properties option in Disk Management tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/properties-option.jpg)
4. Switch to the **Volumes** tab.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134236/18498" target="_top" id="2134236">
  <img src="//a.impactradius-go.com/display-ad/18498-2134236" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134236/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Check the **Partition style.** If it shows Master Boot Record (MBR), then you will have to convert it to GPT.  
![Partition Style in Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Partition-Style.jpg)

 To convert the MBR partition style to GPT, follow the below steps:

1. Open the **Start Menu** by pressing the **Windows** key.
2. Type **Command Prompt** in the search bar and click the **Run as administrator** option in right pane.
3. Type **mbr2gpt /validate /allowfullOS** and press Enter. This command will validate the partition.  
![Validate command option in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/validate-command.jpg)
4. Once the validation is complete, type **mbr2gpt /convert /allowfullOS** and press Enter.

 That's it. Windows will start converting the partition style. The process may take some time, depending on the size of your drive.

## 5\. Perform a Clean Boot

 Are you still facing the "Secure Boot state unsupported" error? If yes, then you will have to perform a clean boot to troubleshoot the issue. Check out our guide on [how to perform a clean boot on Windows](https://www.makeuseof.com/clean-boot-windows-11/) for more information.

 In the clean boot state, check if you're facing the error message again or not.

![System configuration window on desktop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/system-configuration-window.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139107/17108" target="_top" id="2139107">
  <img src="//a.impactradius-go.com/display-ad/17108-2139107" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139107/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If not, then it indicates that one of the services you disabled was causing the problem. To narrow it down, repeat the above process while slowly re-enabling the services until you see the error again.

 Once you find out which service is the culprit, consider downloading its driver update or running an SFC scan if it's a Windows-based service.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526">
  <img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## The "Secure Boot State Unsupported" Error, Fixed

 The "Secure Boot state unsupported" error is a very common issue that appears when you try to install Windows 11\. Fortunately, you can quickly troubleshoot this error by following the above fixes.

 But in the worst-case scenario, if none of the above fixes were helpful, then you will have to clean install Windows.

 The error mainly appears when TPM is disabled on your computer. As such, if you're also facing the same problem, follow the fixes below to troubleshoot the problem for good.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vp-tips.techidaily.com/new-comprehensive-examination-gopro-hero4-silver-version/"><u>[New] Comprehensive Examination GoPro HERO4 Silver Version</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-the-xbox-chronicles-essential-steps-in-gameplay-documentation/"><u>[New] The Xbox Chronicles Essential Steps in Gameplay Documentation</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-reimagining-received-gifts-the-joy-of-openness/"><u>[Updated] In 2024, Reimagining Received Gifts The Joy of Openness</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-adoption-trends-for-arvr-shopping/"><u>2024 Approved Adoption Trends for AR/VR Shopping</u></a></li>
<li><a href="https://windows11.techidaily.com/ace-your-adventures-optimal-full-hd-play-with-scummvm-and-windows-pcs/"><u>Ace Your Adventures: Optimal Full HD Play with ScummVM and Windows PCs</u></a></li>
<li><a href="https://howto.techidaily.com/authentication-error-occurred-on-zte-nubia-flip-5g-here-are-10-proven-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Authentication Error Occurred on ZTE Nubia Flip 5G? Here Are 10 Proven Fixes | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-ftdibussys-explaining-its-effect-on-memory-security/"><u>Deciphering ftdibus.sys: Explaining Its Effect on Memory Security</u></a></li>
<li><a href="https://windows11.techidaily.com/executing-policies-for-a-single-user-target-in-modern-windows-systems/"><u>Executing Policies for a Single-User Target in Modern Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-disabling-windows-surrounders/"><u>Guide to Disabling Windows Surrounders</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-multi-user-printer-errors-windows-11-guide/"><u>Handling Multi-User Printer Errors: Windows 11 Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-set-up-troubleshooter-shortcuts-in-windows-11-and-11/"><u>How to Set Up Troubleshooter Shortcuts in Windows 11 & 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-fake-gps-on-oneplus-11-5g-for-mobile-legends-drfone-by-drfone-virtual-android/"><u>In 2024, How To Fake GPS On OnePlus 11 5G For Mobile Legends? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-tips-and-tricks-for-setting-up-your-honor-magic-v2-phone-pattern-lock-by-drfone-android/"><u>In 2024, Tips and Tricks for Setting Up your Honor Magic V2 Phone Pattern Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/make-your-windows-life-easier-with-proper-installation-steps/"><u>Make Your Windows Life Easier with Proper Installation Steps</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/perfecting-your-videos-narrative-integrating-timestamps-smartly/"><u>Perfecting Your Video's Narrative Integrating Timestamps Smartly</u></a></li>
<li><a href="https://buynow-info.techidaily.com/the-ideal-choice-for-gamers-experience-excellence-with-asus-vg245h/"><u>The Ideal Choice for Gamers: Experience Excellence With Asus VG245H</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-your-console-dreams-choose-windows-for-games/"><u>Unlocking Your Console Dreams: Choose Windows for Games</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/what-legendaries-are-in-pokemon-platinum-on-infinix-hot-40-drfone-by-drfone-virtual-android/"><u>What Legendaries Are In Pokemon Platinum On Infinix Hot 40? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-photo-wizardry-made-easy-mastering-slideshow-creation-and-spot-repair/"><u>Windows 11'S Photo Wizardry Made Easy: Mastering Slideshow Creation & Spot Repair</u></a></li>
</ul></div>

