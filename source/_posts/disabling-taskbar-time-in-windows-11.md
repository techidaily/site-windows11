---
title: Disabling Taskbar Time in Windows 11
date: 2024-08-08T05:57:26.614Z
updated: 2024-08-09T05:57:26.614Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Disabling Taskbar Time in Windows 11
excerpt: This Article Describes Disabling Taskbar Time in Windows 11
keywords: Disable Taskbar Time,Turn Off Time Bar,Stop Taskbar Clock,Halt Windows Timeline,Eliminate Time Display,Deactivate Clock UI,Remove Taskbar Time
thumbnail: https://thmb.techidaily.com/01781fffdf7ecc74eaf5b3cf4180716493ded8344db51bb91021cea7376b2f5b.jpg
---

## Disabling Taskbar Time in Windows 11

 The system tray clock on the right side of the Windows taskbar shows the date and time. While most users find this information useful, others might consider it a source of distraction.

 As such, if you want to hide the clock and date from the taskbar, then this is the place where you need to be. We'll share three different ways by which you can configure the taskbar to hide or show the clock and date.

## 1\. Hide or Show the Clock and Date from the Taskbar by Using Windows System Settings

 The System Settings is the central hub of a Windows PC. You can use it to update Windows, manage privacy settings,[customize the taskbar](https://www.makeuseof.com/windows-11-customize-taskbar/) , and more.

 It's also one of the places from where you can configure the taskbar to hide or show the clock and date. You can do this by following the below instructions:

 This method only works for Windows 10\. If you are using Windows 11, you can try any other method in this article.

1. Open the**Settings** menu by pressing the**Win + I** hotkeys.
2. Choose the**Personalization** option.
3. Select**Taskbar** from the left panel.
4. Scroll down and click the**Turn system icon on or off** option under the**Notification** area.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->
![Turn system icons on or off option in Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-system-icons-on-or-off.png)
5. In the new window that crops up, disable the toggle next to**Clock.**  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3727260&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![Disable the Clock in System Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-the-clock.png)

 That's it. You've disabled the clock and date from the taskbar.

 To enable them again, head towards the above settings again and enable the toggle.

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=14095146&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8b6cc3ee5ec407721ce3bf5ff4c0f56b/PRO_BUY_728x90-EN.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. Hide or Show the Clock and Date from the Taskbar by Using the Local Group Policy Editor

 The next utility that will help you hide or show the clock and date from the taskbar is the Local Group Policy Editor. You can use this utility to manage Windows features, sign-in and shutdown processes, and more.

 The Local Group Policy Editor is disabled by default in the Windows Home edition. To enable it, check out our guide on how to [access the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 Nevertheless, here's how to use Local Group Policy Editor to configure the taskbar to hide the clock and date.

1. Open the Run dialog box, type**gpedit.msc,** and press Enter.
2. In the Local Group Policy Editor, select the**Administrative Templates** folder under**User configuration.**
3. Click the**Start Menu and Taskbar** folder.
4. Click the**Setting** option in the right pane.
5. Search for and right-click on the**Remove Clock from the system notification area** policy. Then, choose**Edit** from the context menu.
6. In the policy edit window, choose the**Enabled** option.  
![Disabling Clock and Date using the local group policy editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disabling-clock-and-date.jpg)
7. Click**Apply** \>**OK** to save the changes.

 Next,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) for changes to take effect.

 If you want to add the clock and date again to the taskbar, open the edit window of the Remove Clock from the system notification area policy, choose the Disabled option and save the settings.

## 3\. Hide or Show the Clock and Date from the Taskbar Using the Registry Editor

 The [Registry Editor](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is an extensive database of your Windows operating system configuration settings. You can use it to navigate the registry and edit its keys.

 Here's how to use the Registry Editor to hide the clock and date from the taskbar:

1. In the Run dialog box, type**regedit** and click**OK.** It'll [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Navigate to the following location:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies`
3. Right-click on the**Policies** key in the left panel, choose**New,** and then select**Key.**
4. Name the key**Explorer** and press Enter.  
<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
![Creating new key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/creating-new-key.jpg)
5. In the Explorer key, right-click on the blank space, and choose**New** \>**DWORD (32-bit Value)** .
6. Name the value**HideClock** and press Enter.
7. Right-click on the HideClock value, type**1** in the**Value data** section, and click**OK.**  
<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->
![Modifying HideClock Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/modifying-hideclock-value.jpg)

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Remove Any Distraction from the Taskbar

 The system tray clock helps you to keep track of the date and time. But if it has become a distraction or you want to keep the taskbar clean, you can use either of the above methods to configure the taskbar to hide the clock and date.


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
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-unleash-the-genius-ranked-top-8-film-watching-apps-iphone-edition/"><u>[New] 2024 Approved  Unleash the Genius  Ranked Top 8 Film-Watching Apps iPhone Edition</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-top-choice-android-sky-dumps-and-safes/"><u>[New] Top Choice  Android Sky Dumps & Safes</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-in-2024-design-principles-for-orderly-youtube-broadcasts/"><u>[Updated] In 2024, Design Principles for Orderly YouTube Broadcasts</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-essential-guide-to-saving-web-radio-broadcasts/"><u>[Updated] The Essential Guide to Saving Web Radio Broadcasts</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-from-canvas-to-crypto-top-7-artwork-conversion-platforms/"><u>2024 Approved  From Canvas to Crypto  Top 7 Artwork Conversion Platforms</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-from-snapchat-to-social-upload-videos-on-twit/"><u>2024 Approved  From Snapchat to Social  Upload Videos on Twit</u></a></li>
<li><a href="https://windows11.techidaily.com/a-curated-list-of-6-essential-android-apps-for-windows-11-users/"><u>A Curated List of 6 Essential Android Apps for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-failed-speech-recognition-startup-error-windows/"><u>Addressing 'Failed' Speech Recognition Startup Error Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-asymmetric-windows-headphone-output/"><u>Adjusting Asymmetric Windows Headphone Output</u></a></li>
<li><a href="https://howto.techidaily.com/authentication-error-occurred-on-samsung-galaxy-f04-here-are-10-proven-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Authentication Error Occurred on Samsung Galaxy F04? Here Are 10 Proven Fixes | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-admin-error-for-apps/"><u>Bypassing Windows Admin Error for Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/command-guide-win11-starting-high-privilege-powershell/"><u>Command Guide: Win11 - Starting High-Privilege PowerShell</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-your-window-preferences-on-win11/"><u>Customize Your Window Preferences on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/detailed-process-of-downloading-and-setting-up-windows-11-arm-iso/"><u>Detailed Process of Downloading and Setting up Windows 11 ARM ISO</u></a></li>
<li><a href="https://windows11.techidaily.com/diving-into-devs-how-to-use-the-dev-drive-on-windows-11/"><u>Diving Into Devs: How to Use the Dev Drive on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/early-bird-benefits-automatic-open-of-windows-sticky-notes/"><u>Early Bird Benefits: Automatic Open of Windows' Sticky Notes</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-your-pcs-performance-dispose-of-bloatware/"><u>Enhance Your PC's Performance: Dispose of Bloatware</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-hidden-windows-bar-when-browser-frames-are-enlarged/"><u>Fixing Hidden Windows Bar when Browser Frames Are Enlarged</u></a></li>
<li><a href="https://driver-download.techidaily.com/how-to-get-the-newest-nvidia-rtx-2070-super-drivers-on-your-pc-windows-1011-guide/"><u>How to Get the Newest NVIDIA RTX 2070 Super Drivers on Your PC: Windows 10/11 Guide</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-easy-alteration-rotate-film-frames-with-vlc/"><u>In 2024, Easy Alteration  Rotate Film Frames with VLC</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-unlock-apple-id-without-phone-number-from-iphone-12-mini-by-drfone-ios/"><u>In 2024, Unlock Apple ID without Phone Number From iPhone 12 mini</u></a></li>
<li><a href="https://extra-tips.techidaily.com/ios-and-android-leading-10-apps-for-captivating-stickers-on-images/"><u>IOS & Android  Leading 10 Apps for Captivating Stickers on Images</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/keep-your-creativity-alive-with-insta-content-sharing/"><u>Keep Your Creativity Alive with Insta Content Sharing</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-art-of-troubleshooting-windows-camera/"><u>Master the Art of Troubleshooting Windows Camera</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-error-correction-techniques/"><u>Mastering Windows Error Correction Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-windows-update-blockage-error-e/"><u>Mending Windows Update Blockage, Error E</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-file-system-woes-on-windows-11/"><u>Navigating File System Woes on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-non-detected-network-proxy-settings-in-windows/"><u>Overcoming Non-Detected Network Proxy Settings in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/phase-out-announcement-end-for-windows-781-on-microsoft-platforms/"><u>Phase-Out Announcement: End for Windows 7/8.1 on Microsoft Platforms</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/quick-fame-formula-amplify-your-insta-presence-with-content-for-2024/"><u>Quick Fame Formula  Amplify Your Insta Presence with Content for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaim-soundfulness-overcoming-muted-mouses-cry/"><u>Reclaim Soundfulness: Overcoming Muted Mouse's Cry</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-permission-problems-during-windows-1011-installer-errors/"><u>Remedying Permission Problems During Windows 10/11 Installer Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/revitalizing-the-old-guard-running-windows-11-on-pre-ultimate-pcs-via-to-go-and-rufus/"><u>Revitalizing the Old Guard: Running Windows 11 on Pre-Ultimate PCs via To Go & Rufus</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-cross-os-installation-of-kali-linux/"><u>Simplifying Cross-OS Installation of Kali Linux</u></a></li>
<li><a href="https://windows11.techidaily.com/snipping-tool-or-printscreen-best-windows-capture-strategy/"><u>Snipping Tool or Printscreen? Best Windows Capture Strategy</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-content-disconnected-error-on-windows-using-steam/"><u>Solving Content Disconnected Error on Windows Using Steam</u></a></li>
<li><a href="https://win-blog.techidaily.com/star-wars-squadrons-game-crashes-no-more-effective-troubleshooting-techniques-revealed/"><u>Star Wars Squadrons Game Crashes? No More! Effective Troubleshooting Techniques Revealed!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-changing-proxies-on-windows-11/"><u>Step-by-Step: Changing Proxies on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-permission-fixes-for-installer-problems/"><u>Streamlining Permission Fixes for Installer Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-unseen-wi-fi-in-windows/"><u>The Art of Unseen Wi-Fi in Windows</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/the-ultimate-list-for-fbs-most-popular-song-videos/"><u>The Ultimate List for FB's Most Popular Song Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/time-travel-tech-windows-7-product-key-for-11-activation/"><u>Time-Travel Tech: Windows 7 Product Key for 11 Activation</u></a></li>
<li><a href="https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-samsung-galaxy-a15-5g-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Troubleshooting Guide How to Fix an Unresponsive Samsung Galaxy A15 5G Screen | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-archive-file-history-in-windows-11/"><u>Unlocking the Archive: File History in Windows 11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/unveiling-the-power-of-slug-lines/"><u>Unveiling the Power of Slug Lines</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-second-shuffle-solved/"><u>Windows Second Shuffle Solved</u></a></li>
<li><a href="https://howto.techidaily.com/xiaomi-redmi-note-12-proplus-5g-screen-unresponsive-heres-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Xiaomi Redmi Note 12 Pro+ 5G Screen Unresponsive? Heres How to Fix It | Dr.fone</u></a></li>
</ul></div>
