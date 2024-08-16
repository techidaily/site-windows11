---
title: Mastering Unstoppable Methods to Turn Off MS Defender
date: 2024-08-15T16:08:20.881Z
updated: 2024-08-16T16:08:20.881Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering Unstoppable Methods to Turn Off MS Defender
excerpt: This Article Describes Mastering Unstoppable Methods to Turn Off MS Defender
keywords: Disabling MS Defender,Overcoming MS Protection,Stopping MS Security,Deactivating MS Safeguard,Bypassing MS Guard,Hacking MS Shields,Eliminate MS Monitor
thumbnail: https://thmb.techidaily.com/9f7aaa7e93668c79f588e2bdc07bd0199fd9952e273ede775f53891cdecae42d.jpg
---

## Mastering Unstoppable Methods to Turn Off MS Defender

 Microsoft bundles an antivirus program with every copy of the Windows operating system. Microsoft Defender was released in 2006 and has since been integral to every new Windows operating system release. Surprisingly, it is good at identifying and isolating malware on your system and offering real-time protection.

 But have you ever tried disabling Microsoft Defender? Unless you install a third-party antivirus program, it continues to run and monitor your system. Even if you disable the real-time protection, it turns back on after some time. Don’t worry! We will discuss multiple methods to disable Microsoft Defender for good.

## Why Does Microsoft Make It Difficult to Disable Microsoft Defender?

 Microsoft Defender offers robust security against malware and has evolved over time. You can use it to keep your system safe from malware and do not need to spend on any third-party antivirus app. But Microsoft realizes that users can expose their system to attackers if they disable Microsoft Defender completely.

 So, as a fail-safe method, Microsoft Defender turns back on after some time, even if you disable it. In the older version of Windows, disabling real-time protection was enough, but now it takes a lot more to disable Microsoft Defender.

 But what if you want to install and use a third-party app that Microsoft Defender repeatedly flags as malicious? Or if you want to reduce the load on your system resources? Well, then you have to dive deep into Windows Security settings and disable real-time protection as well as other associated protection measures.

 This guide will teach you how to disable Microsoft Defender permanently. It will stay off until you undo the steps you perform in this guide. If you only want Microsoft Defender to turn off for a short amount of time, check out [how to turn off Microsoft Defender](https://www.makeuseof.com/how-to-turn-off-microsoft-defender-windows-11/) for a more temporary solution.

## Disable Tamper Protection First

 Tamper Protection makes sure that no other apps can make changes to the Microsoft Defender settings on your computer. You don't need to [enable Tamper Protection](https://www.makeuseof.com/how-to-activate-tamper-protection-defender/) because it is active by default. If you want to completely disable Microsoft Defender (including real-time protection), you must disable Tamper Protection first. Here’s how to do it:

1. Press**Win + S** and type Windows Security. Click on the**Open** option to launch the app.
2. Click on the**Virus and threat protection** option on the home page.
3. Find the Virus and threat protection settings section and click on the**Manage settings** option.
4. Scroll down and click on the**Tamper Protection** toggle to disable it.  
![Disable Tamper Protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/Disable-Tamper-Protection-2.jpg)
5. Close the Windows Security app.

## How to Disable Microsoft Defender in Windows 11

 We have already disabled Tamper Protection, so it won't interfere when you disable Microsoft Defender using GPE, Registry Editor, or any third-party tool. Here are the following methods that work flawlessly to disable the inbuilt security app on Windows 11:

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. Disable Microsoft Defender Using Group Policy Editor

 Group Policy Editor is an excellent tool using which you can customize Windows settings with ease. However, it is only reserved for Windows Pro and Enterprise users. Check out [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) if you're using that version.

 Here’s how to disable Microsoft Defender using Group Policy Editor:

1. Press**Win + R** to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**gpedit.msc** in the text input area and press the Enter key.
2. Group Policy Editor will launch. Click on the**Computer Configuration** option on the home page.
3. Navigate to**Administrative Templates > Windows Components** .
4. Locate and click on the Microsoft Defender Antivirus option. Double-click on the**Turn-off Microsoft Defender Antivirus** policy to edit its settings.  
![Disable Windows Defender Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-defender-using-group-policy-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Select the**Enabled** radio button and click on the**Apply** button.
6. Lastly, click on the**OK** button and close the Group Policy Editor. Restart your system and open Windows Security.

### 2\. Disable Microsoft Defender Using Registry Editor

 Windows 11 Home users cannot use the Group Policy Editor. But you can tweak the registry to disable Microsoft Defender on your system. However, before making any changes, please create a registry backup and create a system restore point. That way, you can always undo any changes you make to the registry.

Repeat the following steps to disable Microsoft Defender:

1. Press**Win + S** to open Windows Search and type**Regedit** . Click on the**Run as administrator** button.
2. In the Registry Editor windows, go to the address bar and paste the following path:  
Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Microsoft Defender
3. Right-click and select**New > DWORD (32-bit) Value** .
4. \`Click on the newly created DWORD (32-bit) Value and name it**DisableAntiSpyware** .
5. Double-click on the DisableAntiSpyware value and set the**Value Dat** a to**1** . Keep the**Base** as**Hexadecimal** .  
![Disable Windows Defender Using Group Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-defender-using-group-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
6. Close the Registry Editor and restart your system to apply changes.
7. Launch Windows Security and visit the Virus and threat protection section. You will see a “ **No active antivirus provider. Your device is vulnerable.** ” message.

### 3\. Disable Microsoft Defender Using CMD

 You can even use the Command Prompt app to disable Microsoft Defender. All you need to do is paste a registry modification command, and it will keep Microsoft’s default antivirus solution out of the picture. Here’s how to do it:

1. Press**Win + R** to launch the Run command box. Type**cmd** in the text input area and press**Ctrl + Shift + Enter** key to launch Command Prompt with admin privileges.
2. Now, type the following command and press the enter key:  
reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Microsoft Defender" /v DisableAntiSpyware /t REG_DWORD /d 1 /f
3. You will see a “**The operation completed successfully.** ” message after the successful execution of the above command.  
![Disable Windows Defender Using CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-defender-using-cmd.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->
4. Type**exit** to close the Command Prompt window and restart your system.

### 4\. Disable Microsoft Defender Using Winaero Tweaker

 If you hate tweaking the registry or find running commands too complex, you can use a Windows customization program like Winaero Tweaker. It is a GUI application, so you will find it easier to search for various Windows settings and disable them in a few clicks.

Repeat the following steps:

1. Visit the [Winaero Tweaker download](https://winaero.com/download-winaero-tweaker/) page and download the installer file on your system.
2. Install Winaero Tweaker and right-click on the application and select the**Run as administrator** option.
3. Click on the search icon and type Defender. Click on the**Microsoft Defender \\ Disable Microsoft Defender** search result.  
![Disable Windows Defender Using Winaero Tweaker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-defender-using-winaero-tweaker.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Then, click on the**Disable Microsoft Defender** checkbox. Scroll down and click on the**Reboot now** button.
5. Wait for your computer to restart. Microsoft Defender will be inactive on your system.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 5\. Disable Microsoft Defender Using Ultimate Windows Tweaker

 Like Winaero Tweaker, the Ultimate Windows Tweaker is also a Windows customization app. You can easily enable and disable multiple Windows operating system settings and features which are otherwise very difficult to locate. Repeat the following steps:

1. Go to the [Ultimate Windows Tweaker download webpage](https://www.thewindowsclub.com/ultimate-windows-tweaker-4-windows-10) and download the tool.
2. Extract all its files into a separate folder. Then select the tool and run it with administrator privileges.
3. Click on the**Search For Tweaks** option and type defender. Then click on the**Go** button and select the**Disable Microsoft Defender** option from the list.
4. Select the checkbox next to the**Disable Microsoft Defender** option and click on the**Apply Tweaks** button. You will see a Windows popup that will inform you whether the tweak was successful or not.  
![Disable Windows Defender Using Ultimate Windows Tweaker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-defender-using-ultimate-windows-tweaker.jpg)
5. Finally, click on the**Close** button and restart your system.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
## Permanently Disable Microsoft Defender on Windows 11

 Microsoft Defender is a pain to disable on your system because of multiple fail-safe methods built into Windows Security. So, disable Tamper Protection and then process with a method to disable Microsoft Defender. However, do not leave your system open to malware infestation, and use a third-party antivirus if you don’t like Defender.


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
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-correct-disconnected-instagram-stories/"><u>[New] 2024 Approved  Correct Disconnected Instagram Stories</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-navigating-the-ins-and-outs-of-aiseesofts-screencast-functionality/"><u>[New] 2024 Approved  Navigating the Ins and Outs of Aiseesoft's Screencast Functionality</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-step-by-step-guide-to-pc-based-live-broadcasts-on-tiktok/"><u>[New] Step-by-Step Guide to PC-Based Live Broadcasts on TikTok</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-techniques-to-broadcast-youtube-media-on-facebook-platforms/"><u>[Updated] 2024 Approved  Techniques to Broadcast YouTube Media on Facebook Platforms</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-camera-glitches-ended-by-obs-fix/"><u>2024 Approved  Camera Glitches Ended by OBS Fix</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-immerse-in-pc-game-moments-capture-perfectly/"><u>2024 Approved  Immerse in PC Game Moments - Capture Perfectly</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/approved-legality-of-recording-on-youtube-platform/"><u>2024 Approved  Legality of Recording on YouTube Platform?</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-oppo-a78-5g-drfone-by-drfone-virtual-android/"><u>9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Oppo A78 5G | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/amp-up-your-humor-arsenal-kapwings-meme-creator-for-2024/"><u>Amp Up Your Humor Arsenal – Kapwing's Meme Creator for 2024</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/aussie-slang-unleashed-mastering-local-expressions/"><u>Aussie Slang Unleashed: Mastering Local Expressions</u></a></li>
<li><a href="https://howto.techidaily.com/bricked-your-poco-m6-pro-5g-heres-a-full-solution-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Bricked Your Poco M6 Pro 5G? Heres A Full Solution | Dr.fone</u></a></li>
<li><a href="https://article-files.techidaily.com/designing-your-own-instagram-notification-sounds-for-2024/"><u>Designing Your Own Instagram Notification Sounds for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-steps-to-disable-amdnvidia-graphics-extras/"><u>Easy Steps to Disable AMD/Nvidia Graphics Extras</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-tips-for-steam-streaming-woes/"><u>Effective Tips for Steam Streaming Woes</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-file-handling-in-windows-powertoys/"><u>Efficient File Handling in Windows PowerToys</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-techniques-for-purging-steams-dns-cache/"><u>Efficient Techniques for Purging Steam's DNS Cache</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-accessing-windows-emergency-tools/"><u>Efficiently Accessing Windows Emergency Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/effortlessly-organize-your-desks-icons/"><u>Effortlessly Organize Your Desk's Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-cortana-experience-use-of-vivetool/"><u>Elevate Cortana Experience: Use of ViveTool</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-podcasts-on-pc-select-5-freebies/"><u>Elevate Podcasts on PC: Select 5 Freebies</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-workflow-using-task-scheduler-for-batches/"><u>Elevate Your Workflow: Using Task Scheduler for Batches</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-ui-customization-adding-shortcut-keys-for-wordpad-to-menu-bar/"><u>Elevating UI Customization: Adding Shortcut Keys for Wordpad to Menu Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-blue-screen-due-to-unhandled-win-errors/"><u>Eliminating Blue Screen Due to Unhandled Win Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-non-appearing-screens-on-pc-startup/"><u>Eliminating Non-Appearing Screens on PC Startup</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-overlay-effects-in-nvidia-gpu-software/"><u>Eliminating Overlay Effects in Nvidia GPU Software</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-the-windows-error-code-0x8007251d-for-activation/"><u>Eliminating the Windows Error Code 0X8007251D for Activation</u></a></li>
<li><a href="https://windows11.techidaily.com/embracing-evenings-learning-paints-dark-mode-features/"><u>Embracing Evenings: Learning Paint's Dark Mode Features</u></a></li>
<li><a href="https://windows11.techidaily.com/embracing-independence-chatgpt-alternatives-for-windows-users/"><u>Embracing Independence: ChatGPT Alternatives for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-clear-xbox-audio-on-windows-11-interface/"><u>Enabling Clear Xbox Audio on Windows 11 Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/engage-your-windows-11-interface-adding-interactive-backdrops/"><u>Engage Your Windows 11 Interface: Adding Interactive Backdrops</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-live-performance-on-task-monitor-win-11/"><u>Enhance Live Performance on Task Monitor Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-your-workday-quick-setup-for-outlook-preview-in-windows-11/"><u>Enhance Your Workday: Quick Setup for Outlook Preview in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-your-workflow-top-5-windows-folder-techniques/"><u>Enhance Your Workflow: Top 5 Windows Folder Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-file-management-on-windows-11-with-new-actions/"><u>Enhancing File Management on Windows 11 with New Actions</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-performance-lowering-edges-resource-load/"><u>Enhancing Performance: Lowering Edge's Resource Load</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-storage-management-on-win-1011/"><u>Enhancing Storage Management on Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-cortana-records-are-saved-windows-method/"><u>Ensuring Cortana Records Are Saved: Windows Method</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-sharefake-gps-on-uber-for-honor-magic-6-lite-drfone-by-drfone-virtual-android/"><u>How to share/fake gps on Uber for Honor Magic 6 Lite | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-a-how-to-guide-on-bypassing-the-iphone-6-plus-icloud-lock-by-drfone-ios/"><u>In 2024, A How-To Guide on Bypassing the iPhone 6 Plus iCloud Lock</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-getting-the-pokemon-go-gps-signal-not-found-11-error-in-xiaomi-redmi-a2-drfone-by-drfone-virtual/"><u>In 2024, Getting the Pokemon Go GPS Signal Not Found 11 Error in Xiaomi Redmi A2 | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-hidefake-snapchat-location-on-your-samsung-galaxy-a34-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Hide/Fake Snapchat Location on Your Samsung Galaxy A34 5G | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-reset-gmail-password-on-huawei-p60-devices-by-drfone-android/"><u>In 2024, How to Reset Gmail Password on Huawei P60 Devices</u></a></li>
<li><a href="https://extra-skills.techidaily.com/mastering-simple-hdr-photography-methods-for-2024/"><u>Mastering Simple HDR Photography Methods for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/melodies-and-movements-uncovering-three-economical-methods-of-syncing-sound-with-iphone-videos/"><u>Melodies and Movements  Uncovering Three Economical Methods of Syncing Sound with iPhone Videos</u></a></li>
<li><a href="https://vp-tips.techidaily.com/packaging-to-prowess-marketings-unboxed-secrets/"><u>Packaging to Prowess  Marketing's Unboxed Secrets</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/proven-techniques-to-take-your-obs-studio-videos-to-new-heights-for-2024/"><u>Proven Techniques to Take Your OBS Studio Videos to New Heights for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/step-by-step-tutorial-activating-ai-capabilities-in-bing-app-on-android-platforms/"><u>Step-by-Step Tutorial: Activating AI Capabilities in Bing App on Android Platforms</u></a></li>
<li><a href="https://some-tips.techidaily.com/unlock-hidden-potential-boost-productivity-essential-activities-during-podcast-sessions-for-2024/"><u>Unlock Hidden Potential, Boost Productivity  Essential Activities During Podcast Sessions for 2024</u></a></li>
</ul></div>
