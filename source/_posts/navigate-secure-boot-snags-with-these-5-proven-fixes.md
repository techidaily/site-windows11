---
title: Navigate Secure Boot Snags with These 5 Proven Fixes
date: 2024-09-09T11:58:17.198Z
updated: 2024-09-10T11:58:17.198Z
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135348/19272" target="_top" id="2135348">
  <img src="//a.impactradius-go.com/display-ad/19272-2135348" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135348/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115943/19272" target="_top" id="2115943">
  <img src="//a.impactradius-go.com/display-ad/19272-2115943" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115943/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Choose **UEFI Firmware Settings** and click **Restart.** I'll boot you straight into Windows UEFI BIOS.
5. Choose **BIOS Setup.**
6. Switch to **Secure Boot.**
7. Check the box before **Secure Boot Enable.**  
![Enable Secure Boot in BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Enable-Secure-Boot-1.jpg)

 Note that the steps to [enable Secure Boot](https://www.makeuseof.com/how-enable-tpm-secure-boot-before-upgrading-windows-11/) will be different for different manufacturers. You can check out your manufacturer's BIOS page to know how to do it on your computer.

 Once you've enabled Secure Boot, try to install Windows and check if the problem continues. If yes, then try the next solution on the list.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123468/16836" target="_top" id="2123468">
  <img src="//a.impactradius-go.com/display-ad/16836-2123468" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123468/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Check and Enable TPM Support

 You must have the TPM chip installed on your computer to download Windows 11\. If the TPM chip is missing, you can still install Windows 11 by bypassing the minimum requirement, but then the "Secure Boot state unsupported" error will continue to bother you now and then.

 The problem in the discussion can also appear if TPM is disabled on your computer. To enable TPM, follow the below instructions:

1. Open the Run dialog box.
2. In the search bar, type **tpm.msc** and press Enter.
3. In the TPM management window, click **Actions** in the top bar.
4. Choose **Prepare the TPM** from the context menu.  
![Prepare the TPM in TPM Management Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Prepar-the-TPM.jpg)

<!-- affiliate ads begin -->
<span id="1983475">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983475.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983475">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983475.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983475%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983475/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Restart your computer and check for the problem.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115945/19272" target="_top" id="2115945">
  <img src="//a.impactradius-go.com/display-ad/19272-2115945" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115945/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2123750/7443" target="_top" id="2123750">
  <img src="//a.impactradius-go.com/display-ad/7443-2123750" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123750/7443" style="position:absolute;visibility:hidden;" border="0" />
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
5. Check the **Partition style.** If it shows Master Boot Record (MBR), then you will have to convert it to GPT.  
![Partition Style in Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Partition-Style.jpg)

<!-- affiliate ads begin -->
<span id="2127886">
					<video width="576" height="1024" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2127886.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2127886">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2127886.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2127886%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2127886/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://aligracehair.sjv.io/c/5597632/2115912/19272" target="_top" id="2115912">
  <img src="//a.impactradius-go.com/display-ad/19272-2115912" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115912/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If not, then it indicates that one of the services you disabled was causing the problem. To narrow it down, repeat the above process while slowly re-enabling the services until you see the error again.

 Once you find out which service is the culprit, consider downloading its driver update or running an SFC scan if it's a Windows-based service.

## The "Secure Boot State Unsupported" Error, Fixed

 The "Secure Boot state unsupported" error is a very common issue that appears when you try to install Windows 11\. Fortunately, you can quickly troubleshoot this error by following the above fixes.

 But in the worst-case scenario, if none of the above fixes were helpful, then you will have to clean install Windows.

 The error mainly appears when TPM is disabled on your computer. As such, if you're also facing the same problem, follow the fixes below to troubleshoot the problem for good.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-social-media-synergy-merging-instagram-and-facebook-feeds/"><u>[New] In 2024, Social Media Synergy  Merging Instagram & Facebook Feeds</u></a></li>
<li><a href="https://youtube-data.techidaily.com/o-cost-sound-transformation-ultimate-10-youtube-tools/"><u>[New] No-Cost Sound Transformation  Ultimate 10 YouTube Tools</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-2024-approved-superior-smartphone-editors-elevating-your-gopro-shots/"><u>[Updated] 2024 Approved  Superior Smartphone Editors Elevating Your GoPro Shots</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-photography-toolkit-a-comprehensive-app-analysis/"><u>[Updated] Photography Toolkit  A Comprehensive App Analysis</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/30-innovative-ideas-to-supercharge-your-fb-promotions/"><u>30 Innovative Ideas to Supercharge Your FB Promotions</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/5-lifelong-benefits-of-multilingual-mastery/"><u>5 Lifelong Benefits of Multilingual Mastery</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/capture-save-analyze-the-top-8-sound-techniques-for-2024/"><u>Capture, Save, Analyze  The Top 8 Sound Techniques for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/clearing-the-darkness-remedies-for-invisible-gaming-captures-by-obs/"><u>Clearing the Darkness  Remedies for Invisible Gaming Captures by OBS</u></a></li>
<li><a href="https://some-guidance.techidaily.com/comparing-kmplayer-and-vlc-a-detailed-guide-on-the-top-two-video-players/"><u>Comparing KMPlayer and VLC: A Detailed Guide on the Top Two Video Players</u></a></li>
<li><a href="https://fox-that.techidaily.com/correcting-discrepancies-in-your-iphones-screen-time-website-log-entries/"><u>Correcting Discrepancies in Your iPhone's Screen Time Website Log Entries</u></a></li>
<li><a href="https://extra-information.techidaily.com/cut-the-haze-sharpen-your-photos-with-topeditstools/"><u>Cut the Haze, Sharpen Your Photos with #TopEditsTools</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/foster-viewer-connection-easy-anime-subscribe-buttons-for-youtube-creators-for-2024/"><u>Foster Viewer Connection  Easy Anime Subscribe Buttons for YouTube Creators for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-adjust-inaccurate-task-manager-cpu-indicators/"><u>Guide to Adjust Inaccurate Task Manager CPU Indicators</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-to-rectify-window-11s-non-responsive-menu-bar/"><u>Guidelines to Rectify Window 11'S Non-Responsive Menu Bar</u></a></li>
<li><a href="https://android-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-meizu-21-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Meizu 21 Phones with/without a PC</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-oppo-a56s-5g-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my Oppo A56s 5G Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-infinix-note-30-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Infinix Note 30 in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-turn-off-find-my-apple-iphone-12-mini-when-phone-is-broken-drfone-by-drfone-ios/"><u>How to Turn Off Find My Apple iPhone 12 mini when Phone is Broken? | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-unlock-iphone-se-2022-when-we-dont-have-apple-id-or-password-by-drfone-ios/"><u>How to Unlock iPhone SE (2022) When We Dont Have Apple ID or Password?</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-special-features-virtual-location-on-nokia-g22-drfone-by-drfone-virtual-android/"><u>How To Use Special Features - Virtual Location On Nokia G22? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-after-switching-from-samsung-galaxy-z-flip-5-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data After Switching From Samsung Galaxy Z Flip 5 to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://article-tips.techidaily.com/in-2024-trendsetters-pictures-origins-explored/"><u>In 2024, Trendsetters' Pictures  Origins Explored</u></a></li>
<li><a href="https://extra-information.techidaily.com/inside-acid-pro-benchmarking-alternatives/"><u>Inside ACID Pro  Benchmarking Alternatives</u></a></li>
<li><a href="https://windows11.techidaily.com/is-wsl-functional-post-windows-11-install-solutions-explored/"><u>Is WSL Functional Post-Windows 11 Install? Solutions Explored</u></a></li>
<li><a href="https://windows11.techidaily.com/master-fn-key-tips-on-activation-and-deactivation/"><u>Master Fn Key: Tips on Activation and Deactivation</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-app-packages-with-winget-on-win11-tips-and-tricks/"><u>Mastering App Packages with Winget on Win11 - Tips and Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-web-control-panel-adjustments-in-windows-11/"><u>Mastering Web Control Panel Adjustments in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/morning-magic-startup-seamlessly-unlock-notepad-quickly/"><u>Morning Magic: Startup Seamlessly, Unlock Notepad Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-intricacies-of-w11s-auto-hdr/"><u>Navigating the Intricacies of W11's Auto HDR</u></a></li>
<li><a href="https://windows11.techidaily.com/navigational-aid-for-windows-component-services-utility/"><u>Navigational Aid for Windows' Component Services Utility</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-vram-in-windows-a-comprehensive-guide-for-gamers/"><u>Optimizing VRAM in Windows - A Comprehensive Guide for Gamers</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-0x800700e1-in-win10-and-11-pcs/"><u>Overcoming 0X800700E1 in Win10 & 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-excessive-cpu-activity-a-solution-guide/"><u>Overcoming Excessive CPU Activity: A Solution Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/prime-virtual-machines-elevating-windows-11-tech/"><u>Prime Virtual Machines Elevating Windows 11 Tech</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-at-hand-assigning-shortcuts-for-win-11-problem-tools/"><u>Quick Fixes at Hand: Assigning Shortcuts for Win 11 Problem Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-solutions-to-csgo-opens-issue-w11/"><u>Quick Solutions to CS:GO Opens Issue W11</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-tips-how-to-overcome-restricted-file-viewers-in-windows/"><u>Quick Tips: How to Overcome Restricted File Viewers in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/redefine-restoring-windows-11-explorer-view-order/"><u>Redefine: Restoring Windows 11 Explorer View Order</u></a></li>
<li><a href="https://windows11.techidaily.com/revisiting-the-classics-uncovering-7-older-windows-functionalities-in-11/"><u>Revisiting the Classics: Uncovering 7 Older Windows Functionalities in 11</u></a></li>
<li><a href="https://sound-issues.techidaily.com/reviving-unplugged-realtek-high-fidelity-sound-systems-a-step-by-step-guide/"><u>Reviving Unplugged Realtek High-Fidelity Sound Systems: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-sound-management-in-windows-11/"><u>Simplifying Sound Management in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/sound-expertise-for-beginners-in-microsofts-new-os/"><u>Sound Expertise for Beginners in Microsoft's New OS</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-overcome-msstore-error-0x00000000-in-windows-10/"><u>Steps to Overcome MsStore Error 0X00000000 in Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlined-windows-11-upsize-an-in-place-methodology-overview/"><u>Streamlined Windows 11 Upsize: An In-Place Methodology Overview</u></a></li>
<li><a href="https://windows11.techidaily.com/swiftly-adapt-windows-settings-via-hotkey-techniques/"><u>Swiftly Adapt Windows Settings via Hotkey Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-negate-erroneous-security-alarms-from-chrome-web-app/"><u>Techniques to Negate Erroneous Security Alarms From Chrome Web App</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/top-7-shooter-games-you-must-play-today-for-2024/"><u>Top 7 Shooter Games You Must Play Today for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/top-techniques-for-maximizing-windows-11-features/"><u>Top Techniques for Maximizing Windows 11 Features</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-chrome-blackout-on-pcs/"><u>Troubleshooting Chrome Blackout on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-non-operational-event-viewer/"><u>Troubleshooting Non-Operational Event Viewer</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-fixing-virtualbox-efail-windows-error/"><u>Understanding and Fixing Virtualbox E_FAIL (Windows) Error</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-the-resistance-to-windows-11s-latest-release/"><u>Understanding the Resistance to Windows 11'S Latest Release</u></a></li>
<li><a href="https://win-blog.techidaily.com/why-does-century-age-of-ashes-keep-crashing-solutions-and-tips-for-gamers/"><u>Why Does Century: Age of Ashes Keep Crashing? Solutions and Tips for Gamers</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>