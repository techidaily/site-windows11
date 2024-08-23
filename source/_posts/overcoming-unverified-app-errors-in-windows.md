---
title: Overcoming Unverified App Errors in Windows
date: 2024-08-22T21:40:04.962Z
updated: 2024-08-23T21:40:04.962Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Unverified App Errors in Windows
excerpt: This Article Describes Overcoming Unverified App Errors in Windows
keywords: Fixing Windows App Crashes,Bypass Unchecked App Issues,Solve Win Errors,Troubleshoot Unverified Apps,Resolve Unknown Program Failures,Eliminate Windows Unauthorized Errors,Correcting Erroneous WinApps
thumbnail: https://thmb.techidaily.com/0b724e890933179083e665890982beb41082b155ef2ba061d1c67bef15f0d934.jpg
---

## Overcoming Unverified App Errors in Windows

 Have you encountered the error"the app you're trying to install isn't a Microsoft-verified app"while installing an app? The error occurs if you have configured your system to only install apps from the Microsoft Store. You could have set this permission on purpose, or it might have been set by default.

 Other than that, a corrupted Microsoft Store cache, installing an app from an unofficial source, and enabling Windows S mode can also cause the error. Below, you will find a few checks and fixes you should apply to resolve the error and install the app successfully.

## 1\. Install the App From the Microsoft Store

 Considering you get the error when downloading apps outside the Microsoft Store, it makes sense to first check if the same app is available there. If the app is available, you can download it from there, and there won't be any need to go through advanced troubleshooting.

 Therefore, [open the Microsoft Store](https://www.makeuseof.com/windows-open-microsoft-store/) and search for the app. If you find the app in the store, click the **Get** button to install it. However, if the app isn't available in the store and can only be downloaded from another source, ensure it is safe to download.

## 2\. Make Sure the App You're Downloading Is Safe

 Microsoft doesn't allow untrusted publishers to list their apps on the Microsoft Store. If you haven't found the app on the store, it could be unsafe and infect your computer. Thus, ensure that the app you want to download is secure before downloading.

 To determine if an app is safe, copy its download link and paste it into [VirusTotal's URL search box](https://www.virustotal.com/gui/home/url). After that, press **Enter**.

![Check the Authenticity of a Software by Entering its URL in VirusTotal’s Official Website](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/1-check-the-authenticity-of-a-software-by-entering-its-url-in-virustotal-s-official-website.jpg)

 If the scanner doesn't find any problems with the download link, it's probably safe. After ensuring that, you can apply the remaining fixes to enable app installation outside the store.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Change the Operating System App Settings

 Microsoft cares about the safety and security of its Windows users. To facilitate that, Windows offers a feature that blocks the installation of apps outside the Microsoft Store. The downside of enabling this feature is that it prevents users from installing popular and safe applications from the web.

 When users try to install an app with this restriction turned on, Windows will likely display an error message saying that the app isn't a Microsoft-verified app. Therefore, to avoid encountering the error described above, you should allow Windows to install apps outside the Microsoft Store.

 To modify the app permissions on Windows 10, follow the steps below:

1. Open the **Settings** app.
2. Open **Apps** settings and select **Apps and Features** from the left sidebar.
3. Select **Anywhere** from the dropdown menu under **Choose where to get apps**.

 To modify app permissions on Windows 11, open the **Settings** app, select the **Apps** tab, and then go to **Advanced app settings**.

![Go to Advanced Apps Settings in Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/2-go-to-advanced-apps-settings-in-windows-settings-app.jpg)

 Select **Anywhere** from the dropdown menu next to **Choose where to get apps**.

![Select Anywhere From the Dropdown Menu Next to Choose Where to Get Apps Option in Apps Settings in Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/3-select-anywhere-from-the-dropdown-menu-next-to-choose-where-to-get-apps-option-in-apps-settings-in-windows-settings-app.jpg)

## 4\. Turn Off the App Install Control Policy

 The App Install Control is a Microsoft Defender SmartScreen feature that prevents users from installing apps outside the Microsoft Store. It does this to prevent users from infecting their devices with third-party applications.

 Therefore, you should turn off this feature to remove any restrictions. To turn it off, follow these steps:

1. Open the Local Group Policy Editor. To do this, check out[how to open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) if you're not using Windows Home edition, and learn [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) if you are.
2. Navigate to **Computer Configuration > Administrative Templates > Windows Components > Windows Defender SmartScreen > Explorer**.  
![Go to Explorer Folder by Navigating to the Path in Windows Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/4-go-to-explorer-folder-by-navigating-to-the-path-in-windows-local-group-policy-editor.jpg)
3. Open the policy for **Configure App Install Control**.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Select **Disabled** to turn off this feature.  
![Disable the Policy for Configure App Install Control in Windows Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/5-disable-the-policy-for-configure-app-install-control-in-windows-local-group-policy-editor.jpg)

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Change the App Install Control Permission in the Registry Editor

 To modify the App Install Control permissions via the Registry Editor, follow the below steps:

1. Open the Registry Editor.
2. Navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer**.  
![Go to Explorer Folder by Navigating to the Path in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/6-go-to-explorer-folder-by-navigating-to-the-path-in-windows-registry-editor.jpg)
3. Right-click on **Explorer** and select **New > String value**.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
![Create New String Value in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/7-create-new-string-value-in-windows-registry-editor.jpg)
4. Name this new value **"AicEnabled."**  
![Name the Newly Created String Value AicEnabled in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/8-name-the-newly-created-string-value-aicenabled-in-windows-registry-editor.jpg)
5. Double-click on the newly created string and type "**Anywhere"** in the **Value data** field.  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->
![Type Anywhere in the Value Data Field of Newly Created String in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/9-type-anywhere-in-the-value-data-field-of-newly-created-string-in-windows-registry-editor.jpg)
6. Restart the computer for the changes to take effect.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->

 If the above Registry tweak does not resolve the issue, turn off S mode.

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

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Successfully Install Third-Party Applications Again on Windows

 Microsoft blocks the installation of third-party apps for your security, but it's pointless if it prevents you from installing vital apps. Hopefully, you now better understand why the Microsoft Store presents the "the app you're trying to install isn't a Microsoft-verified app" error. Following the fixes above will enable you to download the apps from unofficial sources.

 Have you encountered the error"the app you're trying to install isn't a Microsoft-verified app"while installing an app? The error occurs if you have configured your system to only install apps from the Microsoft Store. You could have set this permission on purpose, or it might have been set by default.

 Other than that, a corrupted Microsoft Store cache, installing an app from an unofficial source, and enabling Windows S mode can also cause the error. Below, you will find a few checks and fixes you should apply to resolve the error and install the app successfully.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-zero.techidaily.com/024-approved-the-novices-route-to-revenue-in-the-youtube-realm/"><u>[New] 2024 Approved  The Novice's Route to Revenue in the YouTube Realm</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-fixed-obs-audio-capture-issue/"><u>[New] In 2024, Fixed OBS Audio Capture Issue</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-how-to-view-facebook-stories-anonymously2/"><u>[New] In 2024, How to View Facebook Stories Anonymously2</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-navigate-through-iphone-screen-saving-fast/"><u>[New] In 2024, Navigate Through iPhone Screen Saving Fast</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-top-music-choices-for-captivating-video-experiences/"><u>[New] Top Music Choices for Captivating Video Experiences</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-capture-perfection-iphone-camera-skills-guide/"><u>[Updated] Capture Perfection  IPhone Camera Skills Guide</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-the-insiders-look-at-creating-viral-fb-cover-videos/"><u>[Updated] In 2024, The Insider's Look at Creating Viral FB Cover Videos</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-techniques-for-quality-controlled-skype-call-captures/"><u>[Updated] Techniques for Quality-Controlled Skype Call Captures</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-top-5-pro-digital-cameras-for-smooth-twitch-broadcasts-for-2024/"><u>[Updated] Top 5 Pro Digital Cameras for Smooth Twitch Broadcasts for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-and-update-razer-chroma-enabled-naga-mouse-drivers-for-windows/"><u>Download & Update: Razer Chroma-Enabled Naga Mouse Drivers for Windows</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/edit-videos-for-free-top-software-without-watermarks-this-year/"><u>Edit Videos for Free Top Software Without Watermarks This Year</u></a></li>
<li><a href="https://tech-revival.techidaily.com/enterprises-dilemma-the-5-significant-reasons-against-chatgpt/"><u>Enterprises' Dilemma: The 5 Significant Reasons Against ChatGPT</u></a></li>
<li><a href="https://windows11.techidaily.com/expedite-your-epic-experience-with-enhanced-setup/"><u>Expedite Your Epic Experience with Enhanced Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/from-phone-to-desktop-embracing-android-gaming-with-google-play/"><u>From Phone to Desktop: Embracing Android Gaming with Google Play</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-always-show-task-manager-on-top-of-other-open-windows/"><u>How to Always Show Task Manager on Top of Other Open Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-open-the-calculator-in-windows-11/"><u>How to Open the Calculator in Windows 11</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/how-to-regain-visibility-on-a-tiktok-ban-list/"><u>How to Regain Visibility on a TikTok Ban List</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-data-from-iphone-12-pro-to-other-iphone-15-pro-max-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 12 Pro To Other iPhone 15 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-use-wi-fi-and-ethernet-at-the-same-time-on-windows/"><u>How to Use Wi-Fi and Ethernet at the Same Time on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/implementing-extended-firewall-protection-for-windows-11/"><u>Implementing Extended Firewall Protection for Windows 11</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-6-ways-to-change-spotify-location-on-your-apple-iphone-13-pro-max-drfone-by-drfone-virtual-ios/"><u>In 2024, 6 Ways to Change Spotify Location On Your Apple iPhone 13 Pro Max | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-boosting-your-stream-quality-with-zoom-and-fb-live/"><u>In 2024, Boosting Your Stream Quality with ZOOM & FB Live</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-change-location-on-yik-yak-for-your-poco-x6-pro-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>In 2024, Change Location on Yik Yak For your Poco X6 Pro to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-guide-to-mirror-your-lava-yuva-3-to-other-android-devices-drfone-by-drfone-android/"><u>In 2024, Guide to Mirror Your Lava Yuva 3 to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-a-lost-oneplus-ace-2-pro-for-free-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track a Lost OnePlus Ace 2 Pro for Free? | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-quickcapture-ultimate-scan/"><u>In 2024, QuickCapture Ultimate Scan</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-hardware-cooling-on-microsoft-pcs/"><u>Mastering Hardware Cooling on Microsoft PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-require-privilege-woes-winerror-740-breakthroughs/"><u>Navigating 'Require Privilege' Woes: WinError 740 Breakthroughs</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-family-safety-in-windows-11-for-guardians/"><u>Navigating Family Safety in Windows 11 for Guardians</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-win11-settings-for-defaults/"><u>Navigating Win11 Settings for Defaults</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-freeze-frames-in-windows-league-of-legends/"><u>Overcoming Freeze Frames in Windows League of Legends</u></a></li>
<li><a href="https://windows11.techidaily.com/prtscn-not-for-snip-stop-windows-11s-snipping-tool-by-default/"><u>PrtScn Not for Snip: Stop Windows 11'S Snipping Tool by Default</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-methods-to-enable-fingertip-writing-on-windows-pcs/"><u>Quick Methods to Enable Fingertip Writing on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstating-zoom-functionality-in-windows-11-error-1132/"><u>Reinstating Zoom Functionality in Windows 11 Error 1132</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-display-issue-with-error-x0001-geforce/"><u>Resolving Display Issue with Error X0001, GeForce</u></a></li>
<li><a href="https://windows11.techidaily.com/searching-for-ideal-windows-hello-friendly-camera/"><u>Searching for Ideal Windows Hello-Friendly Camera</u></a></li>
<li><a href="https://windows11.techidaily.com/setup-smart-energy-saving-with-automatic-wakesleep-mode/"><u>Setup Smart Energy Saving with Automatic Wake/Sleep Mode</u></a></li>
<li><a href="https://facebook.techidaily.com/social-spheres-meld-facebook-and-instagrams-bond-deepens/"><u>Social Spheres Meld: Facebook & Instagram's Bond Deepens</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-to-counteract-windows-11-error-x80049dd3/"><u>Step-by-Step Guide to Counteract Windows 11 Error X80049DD3</u></a></li>
<li><a href="https://tech-revival.techidaily.com/step-by-step-utilizing-anthropics-claude-tools/"><u>Step-by-Step: Utilizing Anthropic's Claude Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-data-management-in-windows-with-custom-commands/"><u>Streamlining Data Management in Windows with Custom Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-stopping-self-opening-search-bar-in-win11/"><u>Tips for Stopping Self-Opening Search Bar in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/top-secret-tips-for-accessing-win11s-credential-vault-in-under-a-minute/"><u>Top Secret Tips for Accessing Win11's Credential Vault in Under a Minute</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-for-unresponsive-win11-media-player/"><u>Troubleshooting for Unresponsive Win11 Media Player</u></a></li>
<li><a href="https://some-guidance.techidaily.com/ultimate-audio-compilations-for-video-production-for-2024/"><u>Ultimate Audio Compilations for Video Production for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-the-power-of-your-digital-brush-on-windows-11-with-paint-cocreator-for-ai-artistry/"><u>Unleash the Power of Your Digital Brush on Windows 11 with Paint Cocreator for AI Artistry</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-knowledge-about-batch-files-in-windows/"><u>Unlocking Knowledge About Batch Files in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-1111-discord-install-obstructions/"><u>Unlocking Windows 11/11 Discord Install Obstructions</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-not-found-in-windows-os-fixes/"><u>Unraveling 'Not Found' In Windows OS Fixes</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-imovie-manual-a-detailed-method-for-including-audio-files/"><u>Updated IMovie Manual A Detailed Method for Including Audio Files</u></a></li>
<li><a href="https://windows11.techidaily.com/what-lies-behind-the-numbers-in-windows-updates/"><u>What Lies Behind the Numbers in Windows Updates?</u></a></li>
<li><a href="https://windows11.techidaily.com/windowing-ways-to-keep-notes-above-the-rest/"><u>Windowing Ways to Keep Notes Above the Rest</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-mastery-integrating-custom-directories-into-menus/"><u>Windows 11 Mastery: Integrating Custom Directories Into Menus</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-note-saving-strategies-no-software/"><u>Windows 11 Note-Saving Strategies, No Software</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>