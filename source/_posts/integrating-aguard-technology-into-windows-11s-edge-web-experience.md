---
title: Integrating Aguard Technology Into Windows 11'S Edge Web Experience
date: 2024-08-27T16:03:47.947Z
updated: 2024-08-28T16:03:47.947Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Integrating Aguard Technology Into Windows 11'S Edge Web Experience
excerpt: This Article Describes Integrating Aguard Technology Into Windows 11'S Edge Web Experience
keywords: TechEdge Windows 11,Windows AI Integration,AI Web Enhancement,Edge AI Features,Windows Neural Networks,AI-Powered Browsing,Edge Intelligence Upgrade
thumbnail: https://thmb.techidaily.com/4fe1c562a7e3ab45c8b1f68d5fb5d836545aa73283e591a5a7261febdc4cbc2c.jpg
---

## Integrating Aguard Technology Into Windows 11'S Edge Web Experience

 If you work in an environment that deals with sensitive data, then you must install Microsoft Defender Application Guard for Edge on your Windows computer. It opens Microsoft Edge in an isolated container so that suspicious or potentially harmful files will not be able to access trusted resources.

 In this guide, we will show you different methods to install Microsoft Defender Application Guard for Edge on your Windows 11 PC.

## 1\. How to Install Microsoft Defender Application Guard Using Windows Settings

 Installing Microsoft Defender Application Guard for Edge on your Windows PC is a quick and simple process. You just need to access the Windows Settings app, and then follow a few steps to enable the feature. Here's how to do it:

1. Press**Win + I** on your keyboard to open the Settings app. See our guide if you're[having trouble opening Windows Settings](https://www.makeuseof.com/fixes-unable-to-open-windows-settings/) .
2. On the left, click**Privacy and security** , and then on the right, click**Windows Security** .
3. Under the Protection areas, click**App & browser control** .
4. Then, on the Windows Security page, click the**Install Microsoft Defender Application Guard** link below Isolated browsing.  
![How to Install Microsoft Defender Application Guard Using Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/how-to-install-microsoft-defender-application-guard-using-windows-security.jpg)
5. If you see the UAC prompt on your computer screen, click Yes to confirm your action.
6. Next, check the box next to**Microsoft Defender Application Guard** and click**OK** .  
![Add Microsoft Defender Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/add-microsoft-defender-application-guard-for-edge.jpg)

 Once you perform the above steps, you must need to restart your computer to finish installing the requested changes. This way you can install the feature on your computer.

 If you have already installed Microsoft Defender Application Guard and want to uninstall it, the process is quite easy. All you need to do is follow the steps mentioned above until you reach the Windows Security page.

![Uninstall Microsoft Defender Application Guard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-defender-application-guard.jpg)

 Then click**Uninstall Microsoft Defender Application Guard** and uncheck the box next to**Microsoft Defender Application Guard** .

## 2\. How to Install Microsoft Defender Application Guard Using the Control Panel

 You can also install Microsoft Defender Application Guard for Edge on your Windows 11 computer using the classic Control Panel. Here's how to do it:

1. Search for**Control Panel** in the Start menu and open it.
2. Select**Programs and Features** from the menu items.
3. From the left pane, click**Turn Windows features on or off** .
4. Tick the box next to**Microsoft Defender Application Guard** and click**OK** .
5. Then restart your computer for the changes to take effect.

 In order to uninstall it, follow the same steps and uncheck the box next to**Microsoft Defender Application Guard** . Then click OK and reboot your computer to save the changes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
## 3\. How to Install Microsoft Defender Application Guard Using Local Group Policy Editor

 Another method to install Microsoft Defender Application Guard is through the Local Group Policy Editor. This method requires some advanced knowledge and might be challenging for some users but don't worry; if you follow the steps, you'll be okay.

 You'll also find that if you're on Windows Home, the below instructions won't work. This is because it's not enabled by default on Home. Fortunately, you can learn[how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before you perform this fix.

 Follow the steps given below to install Microsoft Defender Application Guard using Local Group Policy Editor:

1. Press the**Win + R** shortcut key to launch the Run window.
2. Type**gpedit.msc** in the dialog box and press Enter or click**OK** .
3. In the Local Group Policy Editor window, navigate to the following path:  
`Computer Configuration > Administrative Templates > Windows Components > Microsoft Defender Application Guard`
4. Now go to the right pane and double-click on the **Turn On Microsoft Defender Application Guard in Managed Mode** policy.  
![Microsoft Defender Application Guard Using Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/microsoft-defender-application-guard-using-local-group-policy-editor.jpg)
5. This will open a new window, select the**Enabled** checkbox.
<!-- affiliate ads begin -->

<!-- affiliate ads end -->
6. You can now go to**Options** and change it to**2** or**3** .  
![Turn on Microsoft Defender Application Guard in Managed Mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/turn-on-microsoft-defender-application-guard-in-managed-mode.jpg)
7. Once done, click**Apply** and then**OK** to save all the changes you have made.
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->

 Now restart your computer and Microsoft Defender Application Guard will be installed on your PC.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. How to Install Microsoft Defender Application Guard Using Command Prompt

 If you are comfortable with the command prompt, you can also install Microsoft Defender Application Guard using the Command Prompt. Follow the steps here:

1. Right-click on Start and select**Run** from the menu list.
2. In the dialog box, type**cmd** and then press**Ctrl + Shift + Enter** on your keyboard.
3. If UAC prompts, click**Yes** to run the command prompt with admin access.
4. In the elevated command prompt window, type the following command and hit Enter:  
`Dism /online /Enable-Feature /FeatureName:"Windows-Defender-ApplicationGuard"​`
5. When Command Prompt asks you to restart, type**Y** and hit Enter to complete this operation.

 Once you restart your computer, Microsoft Defender Application Guard will be installed and ready to use. In case you want to uninstall the Application Guard, you can do so by using the same command prompt steps. Just make sure to run the following command instead:

`Dism /online /Disable-Feature /FeatureName:"Windows-Defender-ApplicationGuard"​`

 At this point, you may be asked to restart your computer. To proceed, type**Y** and press Enter. After restarting, you will have successfully installed Microsoft Defender Application Guard on your system.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
## 5\. How to Install Microsoft Defender Application Guard Using Windows PowerShell

 Alternatively, you can use Windows PowerShell to install Microsoft Defender Application Guard for Edge on Windows 11\. This is also a command-line process but is different from the Command Prompt application. Follow these steps to install Microsoft Defender Application Guard using Windows PowerShell:

1. Open Windows PowerShell with admin access. If you need help, see our guide on[how to open Windows PowerShell as an administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. Once you're in the PowerShell window, type the following command:  
`Enable-WindowsOptionalFeature -Online -FeatureName "Windows-Defender-ApplicationGuard"​`
3. Now press**Enter** on your keyboard to execute it.
4. When PowerShell asks you to restart your computer, type**Y** and hit Enter.

 Upon restarting the computer, you will have successfully installed Microsoft Defender Application Guard on your system. Now you can make sure that you are browsing in a secure and protected environment.

 If you ever want to uninstall Microsoft Defender Application Guard, you can do so by using the same PowerShell command. Just make sure to use**Disable** \-WindowsOptionalFeature instead of**Enable** . So, this way the command should look like this:

`Disable-WindowsOptionalFeature -Online -FeatureName "Windows-Defender-ApplicationGuard"​`

 Now press Enter on your keyboard to execute the command and restart your system. Once it is done, Microsoft Defender Application Guard will be uninstalled from your PC.

 This is how you can install and uninstall Microsoft Defender Application Guard using Windows PowerShell on Windows 11.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get Microsoft Defender Application Guard and Stay Safe

 Microsoft Defender Application Guard uses isolated secure containers to protect your device from malicious files and threats. In the above-described methods, you can follow the installation steps and remain safe while browsing the web.


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
<li><a href="https://article-posts.techidaily.com/new-2024-approved-bedtime-videos-breakdown-stories-and-reviews/"><u>[New] 2024 Approved  Bedtime Videos Breakdown  Stories and Reviews</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-instagrams-hidden-pathway-extract-more-filters-for-free-effortlessly/"><u>[New] 2024 Approved  Instagram’s Hidden Pathway  Extract More Filters for Free Effortlessly</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-from-idea-to-airtime-crafting-compelling-content-live/"><u>[New] From Idea to Airtime  Crafting Compelling Content Live</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-comprehensive-hand-tracking-explained/"><u>[Updated] Comprehensive Hand Tracking Explained</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-essential-5-platforms-beyond-twitter/"><u>[Updated] In 2024, Essential 5 Platforms Beyond Twitter</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-record-webcam-video-with-vlc-for-2024/"><u>[Updated] Record Webcam Video with VLC for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-revel-in-the-wonders-of-asmrs-positive-effects/"><u>[Updated] Revel in the Wonders of ASMR's Positive Effects</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-youtube-video-magic-best-tools-for-effortless-webm-conversion-for-2024/"><u>[Updated] YouTube Video Magic  Best Tools for Effortless WebM Conversion for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/11-proven-solutions-to-fix-google-play-store-not-working-issue-on-motorola-moto-g23-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Proven Solutions to Fix Google Play Store Not Working Issue on Motorola Moto G23 | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-content-creation-in-todays-revenue-landscape/"><u>2024 Approved  Content Creation in Today’s Revenue Landscape</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/additional-tips-about-sinnoh-stone-for-htc-u23-pro-drfone-by-drfone-virtual-android/"><u>Additional Tips About Sinnoh Stone For HTC U23 Pro | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/essential-knowledge-for-hosting-effective-split-screen-events-on-facebook-for-2024/"><u>Essential Knowledge for Hosting Effective Split Screen Events on Facebook for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-editing-at-hand-with-powertoys-tools/"><u>Expert Editing at Hand with PowerToys Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-non-initialized-disks-a-windows-guide/"><u>Fixing Non-Initialized Disks: A Windows Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-this-app-package-is-not-supported-for-installation-on-windows/"><u>How to Fix This App Package Is Not Supported for Installation on Windows</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-jailbreak-icloud-locked-apple-iphone-15-pro-max-by-drfone-ios/"><u>How to jailbreak iCloud locked Apple iPhone 15 Pro Max</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reactivate-frozen-taskbar-and-menu/"><u>How to Reactivate Frozen Taskbar & Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-refresh-the-group-policy-settings-on-windows/"><u>How to Refresh the Group Policy Settings on Windows</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-deleted-samsung-galaxy-m54-5g-pictures-an-easy-method-explained-by-fonelab-android-recover-pictures/"><u>How to Restore Deleted Samsung Galaxy M54 5G Pictures  An Easy Method Explained.</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-how-can-i-get-more-stardust-in-pokemon-go-on-apple-iphone-12-pro-max-drfone-by-drfone-virtual-ios/"><u>In 2024, How can I get more stardust in pokemon go On Apple iPhone 12 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-twilight-assessment-diverse-ideas/"><u>In 2024, Twilight Assessment  Diverse Ideas</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-unveiling-the-secrets-of-xiaomis-screen-capture-functionality/"><u>In 2024, Unveiling the Secrets of Xiaomi's Screen Capture Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/integrate-bandwidth-status-into-windows-shell/"><u>Integrate Bandwidth Status Into Windows Shell</u></a></li>
<li><a href="https://windows11.techidaily.com/jump-starting-windows-setup-with-nine-troubleshooting-steps/"><u>Jump-Starting Windows Setup with Nine Troubleshooting Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-network-stability-in-windows-1011/"><u>Navigating Network Stability in Windows 10/11</u></a></li>
<li><a href="https://android-frp.techidaily.com/oppo-f23-5g-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>Oppo F23 5G ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-file-history-error-in-windows-os/"><u>Overcoming the File History Error in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-unpredictable-printer-selections/"><u>Remedying Unpredictable Printer Selections</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-missed-game-content-with-steam-on-win11/"><u>Resolving Missed Game Content with Steam on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-unlisted-bluetooth-on-pc/"><u>Resolving Unlisted Bluetooth on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-11-invalid-computer-identifier/"><u>Resolving Windows 11: Invalid Computer Identifier</u></a></li>
<li><a href="https://fox-direct.techidaily.com/sierra-maximizing-your-icloud-drive-experience-for-2024/"><u>Sierra  Maximizing Your iCloud Drive Experience for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-correcting-windows-xps-c0000005-error/"><u>Steps to Correcting Windows XP's C0000005 Error</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlined-methods-to-transform-your-windows-11-initiation/"><u>Streamlined Methods to Transform Your Windows 11 Initiation</u></a></li>
<li><a href="https://windows11.techidaily.com/swiftly-delve-into-windows-system-statistics/"><u>Swiftly Delve Into Windows System Statistics</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-black-screen-phenomenon-post-boot/"><u>Tackling Black Screen Phenomenon Post-Boot</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-to-reinforce-stability-and-persistence-of-nvidia-cp-saves/"><u>Tactics to Reinforce Stability and Persistence of Nvidia CP Saves</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-rectify-the-windows-activation-problem-0x803f700f/"><u>Techniques to Rectify the Windows Activation Problem: 0X803F700f</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-art-of-virtual-environments-in-cinema-for-2024/"><u>The Art of Virtual Environments in Cinema for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-pc-failure-at-windows-11-upgrade/"><u>Troubleshooting PC Failure at Windows 11 Upgrade</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-secrets-of-your-system-quick-guide-for-model-names/"><u>Unlock the Secrets of Your System: Quick Guide for Model Names</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11-with-a-retired-windows-7-key/"><u>Unlocking Windows 11 with a Retired Windows 7 Key</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-file-system-errors-on-windows/"><u>Unraveling File System Errors on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-4-secrets-how-to-delete-a-disks-division-in-windows/"><u>Unveiling 4 Secrets: How to Delete a Disk's Division in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-power-of-windows-nettools/"><u>Unveiling the Power of Windows NetTools</u></a></li>
</ul></div>
