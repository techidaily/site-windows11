---
title: Bypassing Verification Barrier when Installing Non-Microsoft Apps
date: 2024-08-15T15:17:55.271Z
updated: 2024-08-16T15:17:55.271Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Bypassing Verification Barrier when Installing Non-Microsoft Apps
excerpt: This Article Describes Bypassing Verification Barrier when Installing Non-Microsoft Apps
keywords: Bypass Verification,Non-Microsoft Apps,Installation Hurdles,Unofficial Software,Security Loopholes,Alternative Apps,Microsoft Barrier Skip
thumbnail: https://thmb.techidaily.com/cf88e87b734b5b9f59ddbd2f8f99680f9b1ec3ba8de831308f2fd3fe15c5bbed.jpg
---

## Bypassing Verification Barrier when Installing Non-Microsoft Apps

 Have you encountered the error"the app you're trying to install isn't a Microsoft-verified app"while installing an app? The error occurs if you have configured your system to only install apps from the Microsoft Store. You could have set this permission on purpose, or it might have been set by default.

 Other than that, a corrupted Microsoft Store cache, installing an app from an unofficial source, and enabling Windows S mode can also cause the error. Below, you will find a few checks and fixes you should apply to resolve the error and install the app successfully.

## 1\. Install the App From the Microsoft Store

 Considering you get the error when downloading apps outside the Microsoft Store, it makes sense to first check if the same app is available there. If the app is available, you can download it from there, and there won't be any need to go through advanced troubleshooting.

 Therefore, [open the Microsoft Store](https://www.makeuseof.com/windows-open-microsoft-store/) and search for the app. If you find the app in the store, click the **Get** button to install it. However, if the app isn't available in the store and can only be downloaded from another source, ensure it is safe to download.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Make Sure the App You're Downloading Is Safe

 Microsoft doesn't allow untrusted publishers to list their apps on the Microsoft Store. If you haven't found the app on the store, it could be unsafe and infect your computer. Thus, ensure that the app you want to download is secure before downloading.

 To determine if an app is safe, copy its download link and paste it into [VirusTotal's URL search box](https://www.virustotal.com/gui/home/url). After that, press **Enter**.

![Check the Authenticity of a Software by Entering its URL in VirusTotal’s Official Website](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/1-check-the-authenticity-of-a-software-by-entering-its-url-in-virustotal-s-official-website.jpg)
<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->

 If the scanner doesn't find any problems with the download link, it's probably safe. After ensuring that, you can apply the remaining fixes to enable app installation outside the store.

## 3\. Change the Operating System App Settings

 Microsoft cares about the safety and security of its Windows users. To facilitate that, Windows offers a feature that blocks the installation of apps outside the Microsoft Store. The downside of enabling this feature is that it prevents users from installing popular and safe applications from the web.

 When users try to install an app with this restriction turned on, Windows will likely display an error message saying that the app isn't a Microsoft-verified app. Therefore, to avoid encountering the error described above, you should allow Windows to install apps outside the Microsoft Store.

 To modify the app permissions on Windows 10, follow the steps below:

1. Open the **Settings** app.
2. Open **Apps** settings and select **Apps and Features** from the left sidebar.
3. Select **Anywhere** from the dropdown menu under **Choose where to get apps**.

 To modify app permissions on Windows 11, open the **Settings** app, select the **Apps** tab, and then go to **Advanced app settings**.

![Go to Advanced Apps Settings in Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/2-go-to-advanced-apps-settings-in-windows-settings-app.jpg)
<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Select **Anywhere** from the dropdown menu next to **Choose where to get apps**.

![Select Anywhere From the Dropdown Menu Next to Choose Where to Get Apps Option in Apps Settings in Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/3-select-anywhere-from-the-dropdown-menu-next-to-choose-where-to-get-apps-option-in-apps-settings-in-windows-settings-app.jpg)

## 4\. Turn Off the App Install Control Policy

 The App Install Control is a Microsoft Defender SmartScreen feature that prevents users from installing apps outside the Microsoft Store. It does this to prevent users from infecting their devices with third-party applications.

 Therefore, you should turn off this feature to remove any restrictions. To turn it off, follow these steps:

1. Open the Local Group Policy Editor. To do this, check out [how to open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) if you're not using Windows Home edition, and learn [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) if you are.
2. Navigate to **Computer Configuration > Administrative Templates > Windows Components > Windows Defender SmartScreen > Explorer**.  
![Go to Explorer Folder by Navigating to the Path in Windows Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/4-go-to-explorer-folder-by-navigating-to-the-path-in-windows-local-group-policy-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Open the policy for **Configure App Install Control**.
4. Select **Disabled** to turn off this feature.  
![Disable the Policy for Configure App Install Control in Windows Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/5-disable-the-policy-for-configure-app-install-control-in-windows-local-group-policy-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Change the App Install Control Permission in the Registry Editor

 To modify the App Install Control permissions via the Registry Editor, follow the below steps:

1. Open the Registry Editor.
2. Navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer**.  
![Go to Explorer Folder by Navigating to the Path in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/6-go-to-explorer-folder-by-navigating-to-the-path-in-windows-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Right-click on **Explorer** and select **New > String value**.  
![Create New String Value in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/7-create-new-string-value-in-windows-registry-editor.jpg)
4. Name this new value **"AicEnabled."**  
![Name the Newly Created String Value AicEnabled in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/8-name-the-newly-created-string-value-aicenabled-in-windows-registry-editor.jpg)
5. Double-click on the newly created string and type "**Anywhere"** in the **Value data** field.  
![Type Anywhere in the Value Data Field of Newly Created String in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/9-type-anywhere-in-the-value-data-field-of-newly-created-string-in-windows-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Restart the computer for the changes to take effect.

 If the above Registry tweak does not resolve the issue, turn off S mode.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Disable Windows S Mode

 Windows S mode is primarily the most secure environment you can get in Windows. It mainly serves as a means of protecting your children and keeping sensitive documents away from prying eyes.

 When this mode is active, users can only download apps from the Microsoft Store, can't use the command line or code editors, and can't modify the Windows Registry Editor.

 Therefore, if you have recently bought a new device and this mode is enabled there by default, Windows will probably throw the error if you attempt to install any app outside the store. Therefore, you should make sure it isn't enabled and disable it if it is.

 To determine whether your device is running S mode, open the **Settings** app, select the **System** tab on the left, and open the **About** page.

 If the S mode is enabled on your device, you'll see it there. If the feature is active, turn it off by following these steps:

1. Open the **Settings** app.
2. Navigate to the **System** tab and go to **Activation**.
3. Click on **Go to the store** under **Switch to Windows 11 Home/Pro**, which will take you to the Microsoft Store page where you can opt out of S mode.
4. Click the **Get** button and follow the on-screen instructions to get out of S mode.

## 7\. Run the Windows Store Apps Troubleshooter

 If the Windows S mode isn't enabled, and you haven't restricted your operating system from downloading apps from outside Microsoft, the error could be caused by an underlying issue with the Microsoft Store. To ensure this is not the case, you should run the Windows Store Apps troubleshooter, which is a built-in tool for troubleshooting issues with the Store.

 If you've never run the troubleshooter before, refer to our guide on [how to run a troubleshooter on Windows 10 or 11](https://www.makeuseof.com/run-troubleshooter-windows-10-11/).

## Successfully Install Third-Party Applications Again on Windows

 Microsoft blocks the installation of third-party apps for your security, but it's pointless if it prevents you from installing vital apps. Hopefully, you now better understand why the Microsoft Store presents the "the app you're trying to install isn't a Microsoft-verified app" error. Following the fixes above will enable you to download the apps from unofficial sources.

 Have you encountered the error"the app you're trying to install isn't a Microsoft-verified app"while installing an app? The error occurs if you have configured your system to only install apps from the Microsoft Store. You could have set this permission on purpose, or it might have been set by default.

 Other than that, a corrupted Microsoft Store cache, installing an app from an unofficial source, and enabling Windows S mode can also cause the error. Below, you will find a few checks and fixes you should apply to resolve the error and install the app successfully.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-clips.techidaily.com/new-cutting-edge-strategies-for-igtv-backgrounds-for-2024/"><u>[New] Cutting-Edge Strategies for IGTV Backgrounds for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-navigate-to-facebooks-recently-viewed-videos/"><u>[New] In 2024, Navigate to Facebook's Recently Viewed Videos</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-in-2024-picturepuns-comic-creation-tool/"><u>[New] In 2024, PicturePuns  Comic Creation Tool</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-effortless-streams-screening-netflix-on-mac-professionally-for-2024/"><u>[Updated] Effortless Streams  Screening Netflix on Mac Professionally for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/a-beginners-guide-to-managing-windows-11-wins/"><u>A Beginner's Guide to Managing Windows 11 Wins</u></a></li>
<li><a href="https://windows11.techidaily.com/a-guide-to-understanding-windows-program-files-format/"><u>A Guide to Understanding Windows' Program Files Format</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-camera-app-malfunction-in-windows-11/"><u>Addressing Camera App Malfunction in Windows 11</u></a></li>
<li><a href="https://buynow-info.techidaily.com/affordable-home-safety-with-remobells-compact-doorbell-for-less-than-a-hundred-dollars/"><u>Affordable Home Safety with RemoBell's Compact Doorbell for Less Than a Hundred Dollars</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/blueprint-for-dominating-in-tiktoks-top-10-strategies-for-2024/"><u>Blueprint for Dominating in TikTok's Top 10 Strategies for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/connecting-the-dots-compatibility-of-ps-vr-headset-and-personal-computers/"><u>Connecting the Dots: Compatibility of PS VR Headset and Personal Computers</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-the-not-an-empty-directory-alert-error-code-0x80070091-in-win11/"><u>Conquering the Not an Empty Directory Alert (Error Code: 0X80070091) in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-windows-upgrade-glitch-error-0xc1900101/"><u>Decoding Windows Upgrade Glitch: Error #0xC1900101</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/demystifying-informal-language-slang-explained/"><u>Demystifying Informal Language: Slang Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-secure-transfer-of-textual-data-via-edges-guardspace-win11-version/"><u>Enabling Secure Transfer of Textual Data via Edges Guardspace, Win11 Version</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/essential-iphone-gps-guides-unveiling-the-top-5-navigation-apps/"><u>Essential iPhone GPS Guides: Unveiling the Top 5 Navigation Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tuning-win11-startup-processes/"><u>Fine-Tuning Win11 Startup Processes</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-reinstalling-failing-drivers-in-win11-system/"><u>Guide to Reinstalling Failing Drivers in Win11 System</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-through-utorrent-sync-failures-on-windows-devices/"><u>Guiding Through uTorrent Sync Failures on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-bypass-windows-defenders-exclusive-software-lockdown/"><u>How to Bypass Windows Defender's Exclusive Software Lockdown</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-stabilize-an-unstable-printer-on-windows/"><u>How to Stabilize an Unstable Printer on Windows</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-use-pokemon-emerald-master-ball-cheat-on-lava-blaze-pro-5g-drfone-by-drfone-virtual-android/"><u>How to Use Pokémon Emerald Master Ball Cheat On Lava Blaze Pro 5G | Dr.fone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-effective-strategies-for-capturing-online-gatherings-mac-pc/"><u>In 2024, Effective Strategies for Capturing Online Gatherings (Mac, PC)</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-reset-a-locked-vivo-s18-pro-phone-by-drfone-android/"><u>In 2024, How to Reset a Locked Vivo S18 Pro Phone</u></a></li>
<li><a href="https://windows11.techidaily.com/invisible-disk-hiding-tricks-in-win11w10/"><u>Invisible Disk Hiding Tricks in Win11/W10</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-tecno-pop-8-drfone-by-drfone-virtual-android/"><u>Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Tecno Pop 8 | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/mastering-content-delivery-uploading-and-sharing-videos-on-instagram-desktop-for-2024/"><u>Mastering Content Delivery  Uploading and Sharing Videos on Instagram Desktop for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/motorola-moto-g14-can-t-play-mp4-video-files-by-aiseesoft-video-converter-play-mp4-on-android/"><u>Motorola Moto G14 can't play MP4 video files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-obstacles-in-package-registration-on-windows-1011/"><u>Overcoming Obstacles in Package Registration on Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-and-fixing-invalid-temp-directories-on-win11/"><u>Preventing and Fixing Invalid Temp Directories on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/prying-into-hidden-taskbar-analysis-tool-in-windows-11/"><u>Prying Into Hidden Taskbar Analysis Tool in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolve-poor-internet-access-in-windows-apps-now/"><u>Resolve Poor Internet Access in Windows Apps Now</u></a></li>
<li><a href="https://windows11.techidaily.com/reversal-of-extra-privileges-win11-standardization-tutorial/"><u>Reversal of Extra Privileges: Win11 Standardization Tutorial</u></a></li>
<li><a href="https://windows11.techidaily.com/revive-the-disappearing-link-top-9-methods-for-win-11s-bluetooth-woes/"><u>Revive the Disappearing Link: Top 9 Methods for Win 11'S Bluetooth Woes</u></a></li>
<li><a href="https://windows11.techidaily.com/revive-vanished-steam-game-icons-immediately/"><u>Revive Vanished Steam Game Icons Immediately</u></a></li>
<li><a href="https://windows11.techidaily.com/simple-steps-for-stellar-cursors-in-windows-1011/"><u>Simple Steps for Stellar Cursors in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-addressing-undetectable-disks/"><u>Strategies for Addressing Undetectable Disks</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-freelancers-companion-easy-and-affordable-audio-effect-additions/"><u>The Freelancer's Companion  Easy and Affordable Audio Effect Additions</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-invalid-temp-paths-on-w11-systems/"><u>Troubleshooting Invalid Temp Paths on W11 Systems</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/unlimited-view-of-youtube-cover-pics-no-payment-required-for-2024/"><u>Unlimited View of YouTube Cover Pics  No Payment Required for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/unveil-tiktoks-most-effective-typefaces-for-video-growth-this-year-for-2024/"><u>Unveil TikTok's Most Effective Typefaces for Video Growth This Year for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/why-your-realme-12-proplus-5g-screen-might-be-unresponsive-and-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Your Realme 12 Pro+ 5G Screen Might be Unresponsive and How to Fix It | Dr.fone</u></a></li>
</ul></div>