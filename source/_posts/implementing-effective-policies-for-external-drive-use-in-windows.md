---
title: Implementing Effective Policies for External Drive Use in Windows
date: 2024-08-15T15:54:56.782Z
updated: 2024-08-16T15:54:56.782Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Implementing Effective Policies for External Drive Use in Windows
excerpt: This Article Describes Implementing Effective Policies for External Drive Use in Windows
keywords: Win External Storage Policy,Drive Usage Guidelines,Safe USB Practices,Data Protection Drives,Secure External Access,Optimize Device Usage,Windows Drive Management
thumbnail: https://thmb.techidaily.com/f5381cefae4db3e611ab844891c6d979a90ee4ce440fddff39e8b37de541c533.jpg
---

## Implementing Effective Policies for External Drive Use in Windows

 Want to prevent others from stealing your PC data through removable storage devices? Or do you want to protect your device from harmful files contained on removable storage devices?

 In this article, we’ll explore how you can prevent others from installing removable storage devices on Windows. That way, your device won't read any removable storage devices without your permission. Lastly, we’ll also show you how to allow others to install specific removable storage devices.

## How to Prevent Others From Installing Any Removable Storage Devices

 Let's start by checking out how you can prevent others from installing any removable storage device into your PC. You can do this using either the Local Group Policy Editor or the Registry Editor.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
<!-- affiliate ads end -->
### Using the Local Group Policy Editor

![Using a Windows laptop on a brown desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Using-a-Windows-laptop-on-a-brown-desk.jpg)
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

 The Local Group Policy Editor (LGPE) is a reliable tool for troubleshooting system errors. Interestingly, you can also use it for other tasks such as [preventing others from changing your Windows desktop background](https://www.makeuseof.com/stop-others-change-windows-desktop-background/).

 Now, here’s how to use the LGPE to prevent others from installing removable storage devices on Windows:

1. Press **Win + R** to open the Run command dialog box.
2. Type **gpedit.msc** and press **Enter** to open the LGPE.
3. Navigate to **Computer Configuration > Administrative Templates > System > Device Installation > Device Installation Restrictions**.
4. Double-click on the **Prevent installation of removable devices** option on the right-hand side.

![Clicking the prevent installation of removable devices option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Clicking-the-prevent-installation-of-removable-devices-option.jpg)
<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Select **Enabled** on the next screen to prevent others from installing removable storage devices into your PC. Alternatively, select **Disabled** or **Not Configured** to restore the default settings.

 Finally, press **Apply** and then press **OK** to save these changes.

 Struggling to access the LGPE on Windows Home? There are a few tricks you can apply to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). But if that sounds complicated to you, then skip to the Registry Editor method.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->
### Using the Registry Editor

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)
<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->

 The Registry Editor is another reliable tool you can use for tweaking system settings and troubleshooting PC issues.

 However, this tool is quite sensitive. So, it’s often worth [backing up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first before editing its keys.

 Now, here’s how to use the Registry Editor to prevent others from installing removable storage devices on Windows:

1. Press **Win + R** to open the Run command dialog box.
2. Type **Regedit** and press **Enter** to open the Registry Editor.
3. Copy-paste the following command into the address bar and press **Enter**:

HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows

 From there, follow these steps:

1. Right-click on the **Windows** folder and select **New > Key**. From there, name this key as **DeviceInstall** and press **Enter**.
2. Right-click on the **DeviceInstall** key and select **New > Key**. Next, name the key as **Restrictions** and press **Enter**.
3. Click the **Restrictions** folder, right-click on a blank space on the right, and then select **New > DWORD (32-bit) Value**. From there, name the value as **DenyRemovableDevices** and press **Enter**.

![Clicking the DenyRemovableDevices value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Clicking-the-DenyRemovableDevices-value.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->

 Now, follow these steps:

1. Double-click on the **DenyRemovableDevices** value.
2. Set the **Value data** as **1** and then press **OK** to prevent others from installing storage devices into your PC. Alternatively, set the **Value data** as **0** and press **OK** to allow others to install removable storage devices on your PC.
3. Close the Registry Editor and restart your device to save these changes.

## How to Prevent Others From Installing Specific Removable Storage Devices

 In some instances, you might want to prevent others from installing specific removable storage devices. So, let’s show you how you can do that using either the LGPE or the Registry Editor.


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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-channel-expansion-at-wallet-friendly-costs/"><u>[New] 2024 Approved  Channel Expansion at Wallet-Friendly Costs</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-storage-solutions-ps5s-top-10-external-units/"><u>[New] 2024 Approved  Storage Solutions  PS5's Top 10 External Units</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-unlocking-stream-potential-your-journey-with-obs-youtube-and-twitch/"><u>[New] 2024 Approved  Unlocking Stream Potential  Your Journey with OBS, YouTube, & Twitch</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-pixelpioneer-8-version-visual-conjurer/"><u>[New] PixelPioneer  8-Version Visual Conjurer</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-crafting-squares-for-viral-videos-in-a-social-media-world/"><u>[Updated] 2024 Approved  Crafting Squares for Viral Videos in a Social Media World</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-cross-platform-collaboration-for-sharing-facebook-videos/"><u>[Updated] Cross-Platform Collaboration for Sharing Facebook Videos</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-dslr-vs-mirrorless-optimal-choice-for-video-production/"><u>[Updated] DSLR vs Mirrorless  Optimal Choice for Video Production</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-gifs-and-graphics-iphone-laughter/"><u>[Updated] GIFs & Graphics  IPhone Laughter</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-youtube-mastery-starts-here-building-and-monetizing-your-channel/"><u>[Updated] YouTube Mastery Starts Here  Building and Monetizing Your Channel</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-bypass-samsungs-vr-camera-here-are-your-top-alternatives/"><u>2024 Approved  Bypass Samsung’s VR Camera - Here Are Your Top Alternatives</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-from-idea-to-implementation-guiding-vendors-in-youtube-sponsorships/"><u>2024 Approved  From Idea to Implementation  Guiding Vendors in Youtube Sponsorships</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/assessing-the-riches-of-mr-beast-for-2024/"><u>Assessing the Riches of Mr. Beast for 2024</u></a></li>
<li><a href="https://driver-download.techidaily.com/download-and-install-epson-et-4550-printing-software-for-windows-step-by-step/"><u>Download & Install Epson ET-4550 Printing Software for Windows - Step by Step</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-compatibility-nightmares-in-windows-without-troubleshooting-tools/"><u>Fix Compatibility Nightmares in Windows without Troubleshooting Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-store-failure-codes/"><u>Fixing Windows Store Failure Codes</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-self-clearing-windows-recycle-bin/"><u>Guide to Self-Clearing Windows Recycle Bin</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-no-supported-devices-problem-in-windows-update/"><u>Handling 'No Supported Devices' Problem in Windows Update</u></a></li>
<li><a href="https://android-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-sony-xperia-10-v-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Sony Xperia 10 V Phones with/without a PC</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-my-lava-blaze-2-location-is-wrong-drfone-by-drfone-virtual-android/"><u>How to Fix My Lava Blaze 2 Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-halt-windows-desktop-keys-effectively/"><u>How to Halt Windows Desktop Keys Effectively</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-repair-unable-to-fetch-error-in-nvidia-geforce-experience/"><u>How To Repair 'Unable To Fetch' Error in NVIDIA GeForce Experience</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-cutting-edge-strategies-for-dynamic-igtv-backgrounds/"><u>In 2024, Cutting-Edge Strategies for Dynamic IGTV Backgrounds</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-comprehensive-shoppers-guide-for-top-360cams/"><u>In 2024, The Comprehensive Shopper’s Guide for Top 360Cams</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-repairing-windows-email-failures-error-code-0x800713f/"><u>Mastering the Art of Repairing Windows' Email Failures (Error Code 0X800713F)</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-task-scheduler-for-file-batch-execution/"><u>Mastering Windows Task Scheduler for File Batch Execution</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/mastery-in-making-your-instagrams-seamless/"><u>Mastery in Making Your Instagrams Seamless</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-two-users-shared-ms-login-fails/"><u>Navigating Through Two Users' Shared MS Login Fails</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/prime-20-anime-openers-soundscape/"><u>Prime 20 Anime Openers' Soundscape</u></a></li>
<li><a href="https://windows11.techidaily.com/proven-tactics-for-heic-to-jpeg-conversion-process-on-windows-11-systems/"><u>Proven Tactics for Heic to JPEG Conversion Process on Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-html-errors-in-windows-11-mail-app-email-views/"><u>Rectifying HTML Errors in Windows 11 Mail App Email Views</u></a></li>
<li><a href="https://windows11.techidaily.com/redefining-phones-role-in-windows-11-networking/"><u>Redefining Phones' Role in Windows 11 Networking</u></a></li>
<li><a href="https://windows11.techidaily.com/reinvigorate-discolored-volume-settings-in-win/"><u>Reinvigorate Discolored Volume Settings in Win</u></a></li>
<li><a href="https://windows11.techidaily.com/rejuvenating-win11-drive-non-destructive-freeing-methods-max-156-chars/"><u>Rejuvenating Win11 Drive: Non-Destructive Freeing Methods (Max 156 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-problematic-windows-protection-protocol/"><u>Resolving Problematic Windows Protection Protocol</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-accessibility-to-essential-windows-command-center/"><u>Restoring Accessibility to Essential Windows Command Center</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-a-static-backdrop-on-modern-windows-11-pcs/"><u>Secure a Static Backdrop on Modern Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/steering-users-clear-of-disconnection-hurdles-from-nvidia/"><u>Steering Users Clear of Disconnection Hurdles From Nvidia</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-entering-windows-11-home-settings/"><u>Step-by-Step: Entering Windows 11 Home Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-tackle-physical-ram-limitations-on-windows-vmware/"><u>Steps to Tackle Physical RAM Limitations on Windows VMware</u></a></li>
<li><a href="https://games-able.techidaily.com/strategies-for-mending-or-swapping-faulty-nintendo-switches/"><u>Strategies for Mending or Swapping Faulty Nintendo Switches</u></a></li>
<li><a href="https://driver-install.techidaily.com/swift-solutions-to-m-audio-driver-hiccups/"><u>Swift Solutions to M-Audio Driver Hiccups</u></a></li>
<li><a href="https://tech-revival.techidaily.com/tackling-chatgpts-recent-legal-hurdles-insights-into-revamped-google-news-platforms-and-how-to-maintain-strong-mobile-signals-while-vacationing/"><u>Tackling ChatGPT's Recent Legal Hurdles: Insights Into Revamped Google News Platforms & How to Maintain Strong Mobile Signals While Vacationing</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/television-and-social-media-4-ways-to-broadcast-fb-live-for-2024/"><u>Television & Social Media  4 Ways To Broadcast FB Live for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-optimizing-win-11s-taskbar/"><u>The Ultimate Guide to Optimizing Win 11'S Taskbar</u></a></li>
<li><a href="https://fox-that.techidaily.com/troubleshooting-full-screen-captures-in-safari-a-comprehensive-guide/"><u>Troubleshooting Full-Screen Captures in Safari: A Comprehensive Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/uncovering-and-correcting-cant-access-mail-errors-in-windows-11-mail-app/"><u>Uncovering and Correcting Can't Access Mail Errors in Windows 11 Mail App</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unveiling-the-future-the-anticipated-arrival-of-gpt-5-explained/"><u>Unveiling the Future: The Anticipated Arrival of GPT-5 Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-transition-phasing-out-old-traits/"><u>Windows Transition: Phasing Out Old Traits</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-strategies-for-simultaneous-folder-proliferation-on-windows-systems/"><u>Winning Strategies for Simultaneous Folder Proliferation on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-windows-timers-for-efficient-pomodoros/"><u>Winning Windows Timers for Efficient Pomodoros</u></a></li>
</ul></div>
