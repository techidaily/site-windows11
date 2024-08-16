---
title: Enabling Forgotten Windows Add-Ons and Utilities in 7 Ways
date: 2024-08-15T15:32:59.307Z
updated: 2024-08-16T15:32:59.307Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enabling Forgotten Windows Add-Ons and Utilities in 7 Ways
excerpt: This Article Describes Enabling Forgotten Windows Add-Ons and Utilities in 7 Ways
keywords: Add-On Enablement Guide,Old Windows Extensions,Revive Windows Tools,Restore Forgotten Utils,Fix Deprecated Features,Update Missing Addons,Utilities Reinstatement Tips
thumbnail: https://thmb.techidaily.com/d0e21788f29958fdaba0fdac4398d13da9177082545009c2bddd22992fae44fc.jpg
---

## Enabling Forgotten Windows Add-Ons and Utilities in 7 Ways

 Optional features are those that you can add to get more functionality or support for certain file formats. For example, you can install different font packs or old Windows utilities like Paint and WordPad.

 If you're having trouble installing optional features, you're not alone. Sometimes optional features may fail to install due to corrupt system files, an outdated Windows version, or incorrect configuration settings.

 Fortunately, there are several ways to fix this problem and get the optional features running again. So, how can you fix the optional features not installing issue?

## 1\. Use the DISM Tool

 One of the first things you can try is using the Deployment Image Servicing and Management (DISM) tool. This tool is part of Windows, and you can use it to fix corrupt system files, including ones that could be causing problems when installing optional features.

To use the DISM tool, follow these steps:

1. Press**Win + Q** to bring up the Windows search dialogue box.
2. Type**cmd** and click**Run as administrator** to open the Command Prompt.
3. Type**dism /online /cleanup-image /restorehealth** and press**Enter** .  
![DISM Windows Utility Overview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/dism-windows-utility.jpg)

 This will start the DISM tool and begin scanning your system for any corrupt or missing files. If it finds any issues with your computer, it will automatically repair them.

 Once the process is complete, you can restart your computer and try installing the optional feature again. If DISM does not work or throws an error code, make sure to go through the [DISM not working fixes](https://www.makeuseof.com/windows-11-dism-error-2-fix/) .

## 2\. Run the System File Checker or SFC Utility

 Another tool you can use to fix issues with optional feature installation is the System File Checker (SFC) utility.

 SFC is a command-line utility on Windows, which means you can use it from the Command Prompt itself. It is a useful tool for troubleshooting and repairing problems with the system files on your computer, similar to the DISM tool.

To check your system using SFC, follow these steps:

1. Open the Command Prompt with administrative rights using any of the [ways to open CMD as an admin on Windows](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
2. Type**sfc /scannow** and press**Enter** .  
![SFC Utility In Windows Overview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-utility-in-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
3. Once SFC scans for errors, make sure to restart your computer.

Want to know the best part?

 The best part is that the System File Checker not only helps you fix the optional features problem but also any other Windows issues. In fact, it's one of the best [ways to repair corrupted Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) .

## 3\. Reset the Windows Update Components

 Windows Update Components include all the services, tasks, and programs that work together to make sure your Windows system is up-to-date and secure.

 Resetting the Windows Update components might help solve the issue with optional feature installation. Here's how you can reset the Windows Update components easily:

1. Open the Command Prompt utility as an administrator.
2. Type the following commands one after the other, pressing**Enter** after each one:

`net stop wuauserv  
net stop cryptSvc  
net stop bits  
net stop msiserver  
ren C:\Windows\SoftwareDistribution SoftwareDistribution.old  
ren C:\Windows\System32\catroot2 catroot2.old  
net start wuauserv  
net start cryptSvc  
net start bits  
net start msiserver`

 This command will stop the Windows Update services, rename the**SoftwareDistribution** and**catroot2** folders, and then restart the services. This can help reset the update process and fix any issues that might be causing problems with optional feature installation.

![Update Components Reset In CMD Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/update-components-reset-in-cmd.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->

 While the commands may look intimidating, you don't need to worry, as all the commands mentioned above will not cause any harm to your system.​​​​

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
## 4\. Run the Windows Update Troubleshooter

 If the Command Prompt method did not work for you, you can use the Windows Update Troubleshooter to reset update components. This tool can help identify and fix problems with the update process, including issues that might be preventing optional features from installing.

Follow these steps to run the update troubleshooter on Windows:

1. Press**Win + I** to launch the Settings app.
2. Scroll down and click**Troubleshoot > Other troubleshooters.**  
![Troubleshooter Settings In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/troubleshooter-settings-in-windows.jpg)
3. Click**Run** next to**Windows Update** to run the troubleshooter.  
![Other Troubleshooters In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/other-troubleshooters-in-windows.jpg)
4. Follow the prompts to complete the troubleshooting process.

 If you're using Windows 10, the Windows Update Troubleshooter is in**Settings > Update & Security >** **Troubleshoot > Windows Update** .

 The troubleshooter will begin scanning your system for any issues with the update process and will offer suggestions for how to fix them. So, you just need to follow the prompts, and then try [installing the optional features](https://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) again.

## 5\. Update Windows to the Latest Version

 If the issue with optional feature installation is related to outdated system files, you may be able to fix it by updating Windows to the latest version.

 Updating Windows can help ensure that you have the latest security patches, bug fixes, and system files, which can help resolve any issues you may be experiencing.

Here's how you can update Windows to the latest version:

1. Press**Win + I** to open the Settings app.
2. Click on**Windows** **Update > Check for updates** on Windows 11\. For Windows 10, click on **Update & Security > Windows Update > Check for Updates** .  
![Windows Update In Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-update-in-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 That's it. Now, you can install any update that is available for your computer.

 By default, Windows automatically downloads and installs updates, but you can also check for updates manually by following the steps above.

## 6\. Restart the Windows Module Installer Service

 The Windows Module Installer service allows you to install, change, and remove Windows features and optional components. If it is not working properly, it can make it difficult to install optional features.

 Follow the below-given steps to restart the Windows Module Installer service:

1. Open Windows search and type**services** .
2. Select the best match to open the**Services** app.
3. Scroll down and find the**Windows Module Installer** service.
4. Right-click on the service and select**Restart** .  
![Windows Modules Installer Service In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-modules-installer-service.jpg)

 When you reset the module installer service, Windows tries to stop it and then start it again, which can help reset the installation process of optional features and fix any issues that might be causing problems.

 Once the service restarts, try installing the optional feature again, and it should work now.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 7\. Restore Windows Features Using PowerShell

 If all the above methods fail to work, restoring Windows features is your last resort. So, if you are unable to use or install an optional Windows feature, you might be able to fix the problem by using PowerShell to restore a particular feature.

 Here are the steps for restoring Windows features using the PowerShell:

1. Press**Win + X** to open the Power User menu.
2. Click on**Windows PowerShell (Admin)** or**Terminal (Admin)** .
3. Type the following command and press**Enter** :  
Get-WindowsOptionalFeature -Online  
![Get Optional Feature Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/get-optional-feature-command.jpg)  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
 This command will show you the**FeatureName** and**State** of every optional Windows feature that you can use. Make sure to copy the "**FeatureName** " of the feature that you want to enable on Windows.
4. To turn on a certain feature, use the following command and replace "**FEATURENAME** " with the feature's name that you copied earlier:  
Enable-WindowsOptionalFeature -Online -FeatureName FEATURENAME  
![Enable Optional Feature Command In PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/optional-feature-in-powershell.jpg)
5. Restart your computer for the changes to take effect.

 This will add the feature back to your system and should make it available for you to enable or disable in the features window.

 This method only allows you to restore a specific feature and, not all the features at once. So, you need to copy and paste the same command and edit the**FEATURENAME** every time.

 If these steps don't fix the problem, you may need to ask Microsoft or a technical support professional for more help.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## Get Back the Windows Optional Features

 Hopefully, the issue with optional features not installing on your system should be fixed now. In any case, it is important to keep your system up-to-date and to follow best practices for maintaining your computer properly to help prevent issues like this from occurring.


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
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-visual-data-extractor/"><u>[New] In 2024, Visual Data Extractor</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-unleash-creative-filmmaking-youtube-guides-and-extras/"><u>[New] Unleash Creative Filmmaking  YouTube Guides & Extras</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-in-2024-ultimate-5-display-choices-for-ps5/"><u>[Updated] In 2024, Ultimate 5 Display Choices  For PS5</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-premier-tips-for-capturing-the-excitement-of-online-cricket-matches/"><u>[Updated] Premier Tips for Capturing the Excitement of Online Cricket Matches</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-exploring-huawei-p10s-network-performance-and-coverage/"><u>2024 Approved  Exploring Huawei P10's Network Performance & Coverage</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-unlocking-time-lapse-potential-on-samsung-screens/"><u>2024 Approved  Unlocking Time-Lapse Potential on Samsung Screens</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-easy-ways-to-copy-contacts-from-motorola-moto-g14-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Easy Ways to Copy Contacts from Motorola Moto G14 to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/9-steps-to-resolve-windows-hello-fingerprint-lockout/"><u>9 Steps to Resolve Windows Hello Fingerprint Lockout</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerate-vm-performance-on-windows-6-precise-tips-and-tricks/"><u>Accelerate VM Performance on Windows: 6 Precise Tips & Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-your-productivity-with-w11-desktop-organization/"><u>Boost Your Productivity with W11 Desktop Organization</u></a></li>
<li><a href="https://windows11.techidaily.com/ceasing-chrome-notifications-on-windows-desktop/"><u>Ceasing Chrome Notifications on Windows Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/command-prompt-mastery-inserting-directories-into-windows-11-menu/"><u>Command Prompt Mastery: Inserting Directories Into Window's 11 Menu</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-now-updated-nvidia-rtx-3080-ti-drivers-supporting-windows-11-8-and-7-systems/"><u>Download Now: Updated NVIDIA RTX 3080 Ti Drivers Supporting Windows 11, 8, and 7 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-steps-to-revive-your-black-screen-windows-11/"><u>Easy Steps to Revive Your Black Screen Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminate-troubleshooting-roadblocks-for-compatibility-issues/"><u>Eliminate Troubleshooting Roadblocks for Compatibility Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-to-office-works-setup-on-win-11/"><u>Essential Guide to Office Works Setup on Win 11</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/focus-fluency-and-fast-learning-with-these-mental-exerciples/"><u>Focus, Fluency, and Fast Learning with These Mental Exerciples</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-open-installation-packages-resolving-windows-errors/"><u>Guide to Open Installation Packages: Resolving Windows Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-an-uninstall-shortcut-to-the-context-menu-in-windows-1110/"><u>How to Add an Uninstall Shortcut to the Context Menu in Windows 11/10</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-the-soft-bricked-xiaomi-redmi-note-12-proplus-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix the Soft Bricked Xiaomi Redmi Note 12 Pro+ 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-regain-missing-router-interface-on-pc/"><u>How to Regain Missing Router Interface on PC</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-5-most-effective-methods-to-unlock-apple-iphone-13-in-lost-mode-by-drfone-ios/"><u>In 2024, 5 Most Effective Methods to Unlock Apple iPhone 13 in Lost Mode</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-maximizing-potential-in-google-photos-features/"><u>In 2024, Maximizing Potential in Google Photos Features</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-ultimate-metaverse-advertising-playbook/"><u>In 2024, The Ultimate Metaverse Advertising Playbook</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-two-ways-to-track-my-boyfriends-samsung-galaxy-z-fold-5-without-him-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, Two Ways to Track My Boyfriends Samsung Galaxy Z Fold 5 without Him Knowing | Dr.fone</u></a></li>
<li><a href="https://driver-install.techidaily.com/install-legacy-canon-mx870-on-old-and-new-windows/"><u>Install Legacy Canon MX870 on Old & New Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-ais-pitfalls-the-risks-of-chatbots-in-windows-keys/"><u>Navigating AI's Pitfalls: The Risks of Chatbots in Windows Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-pc-performance-top-6-monitoring-apps-recommended-for-win/"><u>Optimize PC Performance: Top 6 Monitoring Apps Recommended for Win</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-for-frozen-downloads-restart-tracker-resume-progress/"><u>Quick-Fix for Frozen Downloads: Restart Tracker, Resume Progress</u></a></li>
<li><a href="https://windows11.techidaily.com/slowing-down-windows-11-shutdown-tips-for-live-tasks/"><u>Slowing Down Windows 11 Shutdown: Tips for Live Tasks</u></a></li>
<li><a href="https://windows11.techidaily.com/stopping-google-chrome-alerts-tips-for-windows/"><u>Stopping Google Chrome Alerts: Tips for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-controlling-file-compression-in-windows-11/"><u>Strategies for Controlling File Compression in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-strategy-become-system-admin-now/"><u>Swift Strategy: Become System Admin Now</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-for-overcoming-license-expiration-notice-in-win11/"><u>Tactics for Overcoming License Expiration Notice in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-to-bypass-admin-access-denied-message-on-pc/"><u>Tactics to Bypass 'Admin Access Denied' Message on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/the-6-best-to-do-list-apps-for-windows-10-and-11/"><u>The 6 Best To-Do List Apps for Windows 10 & 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-most-useful-tips-for-pokemon-go-ultra-league-on-huawei-nova-y91-drfone-by-drfone-virtual-android/"><u>The Most Useful Tips for Pokemon Go Ultra League On Huawei Nova Y91 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/the-phasing-out-of-microsofts-windows-xp-7-and-81-lifeline/"><u>The Phasing Out of Microsoft's Windows XP, 7 & 8.1 Lifeline</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/top-10-apps-for-creating-spectacular-instagram-reels/"><u>Top 10 Apps for Creating Spectacular Instagram Reels</u></a></li>
<li><a href="https://fox-http.techidaily.com/unseen-video-on-sony-a6400-whats-going-wrong-in-2024/"><u>Unseen Video on Sony A6400  What's Going Wrong, In 2024</u></a></li>
</ul></div>
