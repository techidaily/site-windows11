---
title: Implementing Access Barriers for Insiders in Windows 11
date: 2024-08-31T22:09:32.605Z
updated: 2024-09-01T22:09:32.605Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Implementing Access Barriers for Insiders in Windows 11
excerpt: This Article Describes Implementing Access Barriers for Insiders in Windows 11
keywords: Insider Control in Win11,Access Restrictions Win11,Insider Account Management,Insider Permissions Windows,Win11 Security Barriers,Insider Privilege Limits,Enforce Access Control Win11
thumbnail: https://thmb.techidaily.com/3fbb28fdd30ab5cd77a4baca2551c9d92b27e18215ac7c02404eb389cacb68b2.jpg
---

## Implementing Access Barriers for Insiders in Windows 11

 Microsoft rolls out Insider builds to Windows Insiders before releasing them to the public. The preview is only intended for testing and feedback, and it provides access to the latest features & changes that will be included in the next release.

 However, it's good to remember that Insider builds can contain bugs or other issues that can lead to instability or data loss. If you are running an insider build and don't want anyone else to download the newer version, you can disable their access. Here's how it works.

## How to Stop Users From Getting Insider Preview Builds in Windows 11

 If you share your computer with others and don't want them to get the newer build, you need to prevent them from getting Insider Preview Builds in Windows 11\. There are basically three ways to achieve this, using System Settings, Group Policy Editor, or Registry Editor. For a detailed explanation of each, please see the following.

### 1\. Use the System Settings

 If you don't want someone to access the Insider builds, you can disable it from the Windows System settings. This option is hidden in the Windows Update settings, so you will need to navigate through the menus to find it. Here's how to do it:

1. Press **Win + I** to open System settings. You can also open it from the Start menu.
2. Once you're in System Settings, go to **Windows Update**.
3. Then navigate to **Windows Insider Programme** \> **Stop getting preview builds**.  
![Stop Getting Preview Builds in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/stop-getting-preview-builds-in-windows.jpg)
4. Now toggle the **Unenroll this device when the next version of Windows releases** switch to disable it.

 This will prevent the device from downloading further Insider builds even if someone initiates it manually.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->
### 2\. Use the Local Group Policy Editor

 Windows 11's Local Group Policy Editor provides you with a wide range of options for configuring system settings. In fact, you can use this tool to disable access to preview builds. However, you will not have access to the Local Group Policy editor if you use Windows Home Edition.

 For this to work, you must first [activate the Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). If it seems too complicated, you may skip it and move on to the next solution.

 Here are the steps you need to take to prevent other users from getting Insider Preview Builds

1. Press the **Win + R** keys to open the Run dialog box.
2. Type "gpedit.msc" into the text field, and then click the **OK** button to launch the Local Group Policy Editor.
3. In the Local Group Policy Editor, go to the following locations:  
`Computer Configuration > Administrative Templates > Windows Components > Data Collection and Preview Builds`
4. From the left menu, select the **Data Collection and Preview Builds** folder.
5. Then double-click on the **Toggle user control over Insider builds** on the right.  
![Block Insider Preview Builds Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Block-Insider-Preview-Builds-Using-Group-Policy.jpg)
6. Select the **Disabled** radio button in the dialog box that appears.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
![Toggle user control over Insider builds](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Toggle-user-control-over-Insider-builds.jpg)
7. After you've made your changes, click **Apply** and **OK** to save them
<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you have completed the steps above, you will need to restart your computer to ensure the changes are applied. After doing that, you'll no longer be able to install or receive Insider builds. If you ever need to give users access to Insider builds on your computer, open the Local Group Policy Editor again.

 Then, set "Toggle user control over Insider builds" either to the **Not Configured** or **Enabled** option. When you have finished making the changes, click Apply > OK.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4693127&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.videosoftdev.com/images/video_editor/screenshots/1.jpg" border="0">
VSDC Pro Video Editor is a light professional non-linear video editing suite for creating a movie of any complexity. It supports the most popular video/audio formats and codecs, including 4K, HD and GoPro videos. Preconfigured profiles make the creation of videos for various multimedia and mobile devices absolutely hassle-free.

Key features:

•	Import from any devices and cams, including GoPro and drones. All formats supported. Сurrently the only free video editor that allows users to export in a new H265/HEVC codec, something essential for those working with 4K and HD.
•	Everything for hassle-free basic editing: cut, crop and merge files, add titles and favorite music
•	Visual effects, advanced color correction and trendy Instagram-like filters   
•	All multimedia processing done from one app: video editing capabilities reinforced by  a video converter, a screen capture, a video capture, a disc burner and a YouTube uploader
•	Non-linear editing: edit several files with simultaneously 
•	Easy export to social networks: special profiles for YouTube, Facebook, Vimeo, Twitter and Instagram
•	High quality export – no conversion quality loss, double export speed even of HD files due to hardware acceleration
•	Stabilization tool will turn shaky or jittery footage into a more stable video automatically. 
•	Essential toolset for professional video editing: blending modes, Mask tool, advanced multiple-color Chroma Key  
</a>
<!-- affiliate ads end -->
### 3\. Tweak the Registry Editor

 Tweaking the Registry Editor is another method you can use to prevent users from getting Insider Preview Builds in Windows 11\. The process is easy and only requires a few steps. It is important, however, not to [accidentally mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/) while doing so.

 If you edit the wrong keys, you may seriously damage your device. For this reason, you should always [back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before making any changes to it.

 To prevent other users from getting Insider Preview Builds, follow these steps:

1. [Open the Run Command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. In the search field, type "regedit" and click **OK**.
3. You will see a UAC window on your screen. Click **Yes** to confirm your action.
4. When you're in the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\PreviewBuilds`
5. If you don't find the PreviewBuilds key there, you will have to create it. In order to do this, right-click on the **Windows** key and select **New** \> **Key**.
6. Specify **PreviewBuilds** as the file name and hit Enter to save it.
7. In the right pane, right-click on an empty area and select **New > DWORD (32-bit) Value**.
8. This DWORD key should have the name **AllowBuildPreview**.
9. Click twice on the newly created DWORD key to open a pop-up menu.  
![Block Insider Preview Builds Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Block-Insider-Preview-Builds-Using-Registry-Editor.jpg)
10. Set the value data to **0** and choose the Hexadecimal base.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
<!-- affiliate ads end -->
11. Click **OK** to save the changes.

 When you're done making these changes, restart your computer. If you ever need to roll back the changes, you can do so whenever you like.

 To do this, right-click the AllowBuildPreview key in the Registry Editor and choose **Modify**. You then need to set the Value data to **1** and hit **OK** to apply the changes.

## Do I Need to Enroll in the Windows Insider Program?

 Windows Insider Program is a feature that allows you to try out new builds and features of Windows OS before they become publicly available. It is a great way to get early access to new features and provide feedback to Microsoft. The program is free to join, and you can opt out at any time.

 If you are considering joining the Windows Insider Program, here are a few things to keep in mind:

1. First, you should be aware that by joining the program, you will be sharing information with Microsoft about your device and how you use it. This information will help Microsoft improve Windows 10 for all users.
2. The second thing you should know is how beta testing works. When you join the Windows Insider Program, you can test out the new features and give feedback to Microsoft. It is important to note that you will be using pre-release software that could be unstable. Some of these builds may have bugs or other issues that could cause problems for your computer.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## Why Would You Want to Prevent Access to Insider Builds?

 There are a few reasons people may want to prevent access to insider builds:

1. Insider builds are usually released before the public version, which means there could be more bugs and glitches.
2. It often contains new features that aren't ready for everyone to use, and some prefer the stability of the older versions.
3. Last but not least, insider builds are often released more frequently. As a result, they are harder to maintain, and some people would prefer a slower update rate for public builds.

## The Windows Insider Preview Build, Now Disabled

 If you want to prevent others from downloading and installing Insider Preview Builds on your Windows 11, you can turn off the Insider Preview feature on your computer. There are two ways to do this, either through the Group Policy Editor or through the Registry Editor. You can learn more about this in the article.

 However, it's good to remember that Insider builds can contain bugs or other issues that can lead to instability or data loss. If you are running an insider build and don't want anyone else to download the newer version, you can disable their access. Here's how it works.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-webster.techidaily.com/ed-in-2024-download-free-youtube-pics-and-templates/"><u>[Updated] In 2024, Download Free YouTube Pics & Templates!</u></a></li>
<li><a href="https://android-unlock.techidaily.com/a-complete-guide-to-oem-unlocking-on-oppo-reno-11-pro-5g-by-drfone-android/"><u>A Complete Guide To OEM Unlocking on Oppo Reno 11 Pro 5G</u></a></li>
<li><a href="https://tech-haven.techidaily.com/chatgpt-intelligence-is-it-declining-or-remains-robust-according-to-openai/"><u>ChatGPT Intelligence: Is It Declining or Remains Robust According to OpenAI?</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-insights-into-utilizing-microsofts-system-restore-feature/"><u>Essential Insights Into Utilizing Microsoft's System Restore Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-incompatible-fingerprint-error-on-windows-os/"><u>Fixing Incompatible Fingerprint Error on Windows OS</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-change-location-on-facebook-dating-for-your-infinix-note-30-5g-drfone-by-drfone-virtual-android/"><u>How to Change Location On Facebook Dating for your Infinix Note 30 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-your-windows-license-will-expire-soon-error-on-windows-10-and-11/"><u>How to Fix the “Your Windows License Will Expire Soon” Error on Windows 10 and 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-solve-microsoft-office-365-glitches-error-30015-26/"><u>How to Solve Microsoft Office 365 Glitches: Error 30015-26</u></a></li>
<li><a href="https://windows11.techidaily.com/ifas-best-laptops-of-2023-now/"><u>IFA's Best Laptops of 2023, Now!</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-elevate-your-conversation-game-mastering-the-art-of-sending-gifs-in-snapchat/"><u>In 2024, Elevate Your Conversation Game  Mastering the Art of Sending GIFs in Snapchat</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-a-network-locked-oppo-find-x7-phone-by-drfone-android/"><u>In 2024, How to Unlock a Network Locked Oppo Find X7 Phone?</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-transform-your-browsing-with-ms-edges-pip/"><u>In 2024, Transform Your Browsing with MS Edge's PIP</u></a></li>
<li><a href="https://fake-location.techidaily.com/is-pgsharp-legal-when-you-are-playing-pokemon-on-oppo-a78-5g-drfone-by-drfone-virtual-android/"><u>Is pgsharp legal when you are playing pokemon On Oppo A78 5G? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/ispoofer-is-not-working-on-realme-c67-5g-fixed-drfone-by-drfone-virtual-android/"><u>iSpoofer is not working On Realme C67 5G? Fixed | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/keyboard-shortcut-wisdom-shrinking-down-software-in-win11/"><u>Keyboard Shortcut Wisdom: Shrinking Down Software in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-resolve-non-installed-windows-store-apps/"><u>Methods to Resolve Non-Installed Windows Store Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-lossed-renderer-failures-in-overwatch-2-gameplay/"><u>Overcoming Lossed Renderer Failures in Overwatch 2 Gameplay</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-playback-problem-in-wmp/"><u>Overcoming Playback Problem in WMP</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-resource-drain-tackling-edges-view2-process/"><u>Overcoming Resource Drain: Tackling Edge's View2 Process</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-based-qbittorrent-halt-problems/"><u>Overcoming Windows-Based qBittorrent Halt Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/pinpointing-powerful-policies-in-windows-systems/"><u>Pinpointing Powerful Policies in Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-devices-from-suspending-during-energy-saver/"><u>Preventing Devices From Suspending During Energy Saver</u></a></li>
<li><a href="https://windows11.techidaily.com/restore-windows-teams-screen-sharing/"><u>Restore Windows Teams Screen Sharing</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/restored-win-graphics-capability/"><u>Restored Win Graphics Capability</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-camera-apps-error-0xa00f425d-on-windows-devices/"><u>Solving Camera App's Error 0xA00F425D on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/speed-ahead-overcoming-low-valorant-download-speeds-in-windows/"><u>Speed Ahead: Overcoming Low Valorant Download Speeds in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-translations-hotkey-tips-for-windows-11-language-switching/"><u>Streamline Translations: Hotkey Tips for Windows 11 Language Switching</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlined-strategy-for-downloading-adobe-on-microsoft-platform/"><u>Streamlined Strategy for Downloading Adobe on Microsoft Platform</u></a></li>
<li><a href="https://windows11.techidaily.com/tidy-up-win11-desktop-by-removing-highlighted-icon/"><u>Tidy up Win11 Desktop by Removing Highlighted Icon</u></a></li>
<li><a href="https://windows11.techidaily.com/tidying-up-your-pc-a-compact-guide-to-uninstallation-in-windows-11-108-chars/"><u>Tidying Up Your PC: A Compact Guide to Uninstallation in Windows 11 (108 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/top-7-sketch-tools-on-windows-11/"><u>Top 7 Sketch Tools on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-steps-for-reclaiming-lost-vpn-links-in-winpc/"><u>Unveiling Steps for Reclaiming Lost VPN Links in WinPC</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-unveiled-a-dive-into-widgets/"><u>Windows 11 Unveiled - A Dive Into Widgets</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-woes-get-your-arrows-back-to-normal/"><u>Windows Woes? Get Your Arrows Back to Normal</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>