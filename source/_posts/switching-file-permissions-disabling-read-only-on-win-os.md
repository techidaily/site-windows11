---
title: "Switching File Permissions: Disabling Read-Only on Win OS"
date: 2024-08-15T16:00:23.149Z
updated: 2024-08-16T16:00:23.149Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Switching File Permissions: Disabling Read-Only on Win OS"
excerpt: "This Article Describes Switching File Permissions: Disabling Read-Only on Win OS"
keywords: Change File Read-Only Windows,Remove Read-Only Windows Files,Enable Edit Windows Files,Modify Windows File Permissions,Disable Read-Only Windows Setting,Adjust File Access in Win OS,Delete Read-Only Windows Attribute
thumbnail: https://thmb.techidaily.com/fed19fb5539928ceb1f098e4df501aac24d80c5bb6000047d745afbd7491bdcb.jpg
---

## Switching File Permissions: Disabling Read-Only on Win OS

 When a file is marked as read-only on Windows, you can only view it and not change it in any way. This essentially protects important files from unauthorized changes.

 On Windows, you can set or remove the read-only attribute for a file by modifying its properties. Alternatively, you can also run a command in Command Prompt or Windows PowerShell to do the same. In this article, we take a look at all of them.

## 1\. How to Change the Read-Only Attribute for Files by Modifying Properties

 The easiest way to set or remove the read-only attribute for a file on Windows is by modifying its properties. Here’s how you can go about it.

1. [Open File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and navigate to the file for which you want to change the read-only attribute.
2. Right-click on your file and select**Properties** .
3. Under the**General** tab, check or uncheck the**Read-only** box.
4. Click**Apply** followed by**OK** .  
![Change Read-Only Attribute by Modifying Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-by-Modifying-Properties.jpg)

 Note that Windows may prevent you from changing the read-only attribute of a file if you don’t have the necessary permissions to modify the folder in which the file is located. In that case, you must take ownership of the folder first. If you need help, check our guide on [how to take ownership of folders on Windows](<http://How> to Take Ownership of Folders in Windows 10 & 11) .

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## 2\. How to Change the Read-Only Attribute for Files Using the Command Prompt

 Command Prompt is one of two command-line tools available on Windows. You can use it to run batch files, troubleshoot errors, and perform various other tasks. It also lets you change a file's read-only attribute with a single command. Here are the steps you need to follow.

1. Right-click on the file for which you want to modify the read-only attribute and select**Copy as path** .
2. Press**Win + X** to open the Power User menu.
3. Select**Terminal (Admin)** from the list.
4. Select**Yes** when the User Account Control (UAC) prompt appears.
5. In the console, type the following command and press**Enter** to set your file as read-only.  
`attrib +r "FilePath"`

 Replace**FilePath** in the above command with the actual path of the file copied earlier.

![Change Read-Only Attribute With Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-With-Command-Prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->

 Once you run the above command, the file will be set as read-only. Likewise, if you want to remove the read-only attribute for a file, use this command:

`attrib -r "FilePath"`

 Once you remove the read-only attribute for a file, you should be able to edit or modify it.

 Like using Command Prompt? Check our guide to learn [how to master Command Prompt on Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) .

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. How to Change the Read-Only Attribute for Files Using Windows PowerShell

 You can also run a command in [Windows PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) to change the read-only attribute for a file.

To change the read-only attribute using PowerShell:

1. Right-click on the file for which you want to change the read-only attribute and select**Copy as path** .
2. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
3. Type**Windows PowerShell** and select**Run as Administrator** .
4. Select**Yes** when the User Account Control (UAC) prompt shows up.
5. Paste the following command and press**Enter** to set your file as read-only.  
`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $True`

 Replace**FilePath** in the above command with the actual path of the file copied earlier.

![Change Read-Only Attribute With PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-With-PowerShell.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->

 Alternatively, if you want to remove the read-only attribute for a file, use this command:

`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $False`

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Modifying the Read-Only Attribute for Files on Windows

 It’s worth noting that most system files on Windows will have the read-only attribute by default. So, make sure you don't modify them by mistake. For your other files, you can pick any of the above methods listed above to set or unset their read-only attribute.

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
<li><a href="https://screen-capture.techidaily.com/new-in-2024-unveiling-techniques-for-effective-display-saving-on-dell/"><u>[New] In 2024, Unveiling Techniques for Effective Display Saving on Dell</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-the-ultimate-list-of-androids-best-music-video-apps/"><u>[New] The Ultimate List of Android's Best Music Video Apps</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-top-5-valheim-seed-recommendations-for-bountiful-crops/"><u>[New] Top 5 Valheim Seed Recommendations for Bountiful Crops</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-from-picture-to-paragraph-text-on-windows-and-mac-photos/"><u>[Updated] From Picture to Paragraph  Text on Windows & Mac Photos</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-beyond-reality-comparing-vr-augmented-and-mixed-tech/"><u>[Updated] In 2024, Beyond Reality  Comparing VR, Augmented & Mixed Tech</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-visualverve-tips-for-resizing-images-in-instagram/"><u>2024 Approved  VisualVerve  Tips for Resizing Images in Instagram</u></a></li>
<li><a href="https://facebook.techidaily.com/agile-operations-top-lite-android-workhorses/"><u>Agile Operations: Top Lite Android Workhorses</u></a></li>
<li><a href="https://windows11.techidaily.com/alleviating-overuse-of-wmi-in-windows-installer/"><u>Alleviating Overuse of WMI in Windows Installer</u></a></li>
<li><a href="https://buynow-help.techidaily.com/amazon-echo-show-5-generation-4-redesign-and-features-explored-in-review/"><u>Amazon Echo Show 5 - Generation 4 Redesign & Features Explored in Review</u></a></li>
<li><a href="https://windows11.techidaily.com/best-approaches-to-regulate-device-connections-in-windows/"><u>Best Approaches to Regulate Device Connections in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-productivity-select-6-crucial-android-apps-for-windows-11/"><u>Boosting Productivity: Select 6 Crucial Android Apps for Windows 11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/bypass-iphone-6-plus-activation-lock-without-apple-id-by-drfone-ios-unlock-ios-unlock/"><u>Bypass iPhone 6 Plus activation lock without Apple ID</u></a></li>
<li><a href="https://windows11.techidaily.com/camouflage-computing-integrating-archives-into-digital-image-win/"><u>Camouflage Computing: Integrating Archives Into Digital Image WIN</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/capture-moments-on-a-dime-kodaks-fz53-explored/"><u>Capture Moments on a Dime - Kodak's FZ53 Explored</u></a></li>
<li><a href="https://windows11.techidaily.com/create-a-convenient-windows-environment-portable-software-icons/"><u>Create a Convenient Windows Environment: Portable Software Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/diagnosing-absent-monitor-display-issue/"><u>Diagnosing Absent Monitor Display Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/downloading-woes-how-to-fix-windows-11-transfer-issues-2/"><u>Downloading Woes: How to Fix Windows 11 Transfer Issues (2)</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-steps-to-correct-windows-11-0x800f0922-error/"><u>Effective Steps to Correct Windows 11 0X800F0922 Error</u></a></li>
<li><a href="https://tech-hub.techidaily.com/efficient-workflows-await-4-insider-secrets-for-utilizing-chatgpt-in-time-management/"><u>Efficient Workflows Await: 4 Insider Secrets for Utilizing ChatGPT in Time Management</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-camera-app-crash-microsofts-windows-error-0xa00f425d/"><u>Eliminating Camera App Crash: Microsoft's Windows Error 0xA00F425D</u></a></li>
<li><a href="https://windows11.techidaily.com/file-location-artistry-in-windows-11-exploring-best-practices-6-advanced-methods/"><u>File Location Artistry in Windows 11: Exploring Best Practices (6 Advanced Methods)</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tune-your-system-control-delete-confirmations/"><u>Fine-Tune Your System: Control Delete Confirmations</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-rectifying-memory-issues-on-pcs/"><u>Guide to Rectifying Memory Issues on PCs</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-access-your-iphone-12-when-you-forget-the-passcode-by-drfone-ios/"><u>How to Access Your iPhone 12 When You Forget the Passcode?</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-nvidia-control-panel-not-saving-settings-in-windows-11/"><u>How to Fix the NVIDIA Control Panel Not Saving Settings in Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-tecno-camon-30-pro-5g-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Tecno Camon 30 Pro 5G to New Android? | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-achieving-broadcast-excellence-your-guide-to-youtubes-live-360-videos/"><u>In 2024, Achieving Broadcast Excellence  Your Guide to YouTube's Live 360 Videos</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-delete-gmail-account-withwithout-password-on-oneplus-open-by-drfone-android/"><u>In 2024, Delete Gmail Account With/Without Password On OnePlus Open</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-from-youtube-to-webm-unveiling-the-premium-converters/"><u>In 2024, From YouTube to WebM  Unveiling the Premium Converters</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-to-fix-pokemon-go-route-not-working-on-vivo-s17t-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix Pokemon Go Route Not Working On Vivo S17t? | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-unlock-apple-id-from-your-apple-iphone-12-pro-without-security-questions-by-drfone-ios/"><u>In 2024, How to Unlock Apple ID From your Apple iPhone 12 Pro without Security Questions?</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-oppo-a78-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>In 2024, How to Unlock Oppo A78 Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/innovative-approach-to-3d-text-in-photoediting/"><u>Innovative Approach to 3D Text in PhotoEditing</u></a></li>
<li><a href="https://windows11.techidaily.com/innovative-windows-search-techniques-that-dont-use-ls/"><u>Innovative Windows Search Techniques That Don't Use LS</u></a></li>
<li><a href="https://driver-download.techidaily.com/install-or-upgrade-hp-laserjet-p1606dn-driver-on-your-windows-pc-full-guide/"><u>Install or Upgrade HP LaserJet P1606dn Driver on Your Windows PC – Full Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/instant-change-of-windows-dashboard-background/"><u>Instant Change of Windows Dashboard Background</u></a></li>
<li><a href="https://windows11.techidaily.com/master-syncing-how-to-rectify-non-syncing-in-ms-to-do/"><u>Master Syncing: How to Rectify Non-Syncing In MS To Do</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-memory-management-for-edges-webview2/"><u>Mastering Memory Management for Edge's WebView2</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-speedier-net-transfers-on-battlenet-windows/"><u>Mastering Speedier Net Transfers on Battle.net Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-window-terminals-shutdown-procedures-entryexit-tactics/"><u>Mastering Window Terminal's Shutdown Procedures: Entry/Exit Tactics</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/mastermind-best-gk-quiz-video-sources-2024/"><u>Mastermind  Best GK Quiz Video Sources 2024</u></a></li>
<li><a href="https://facebook.techidaily.com/meta-us-officially-verified-sign-up-now/"><u>Meta US: Officially Verified Sign-Up Now</u></a></li>
<li><a href="https://fake-location.techidaily.com/methods-to-change-gps-location-on-motorola-razr-40-drfone-by-drfone-virtual-android/"><u>Methods to Change GPS Location On Motorola Razr 40 | Dr.fone</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/microsoft-surface-duo-evaluation-an-unpolished-glitch-ridden-pricey-device/"><u>Microsoft Surface Duo Evaluation: An Unpolished, Glitch-Ridden, Pricey Device</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-your-way-installing-google-maps-on-pc/"><u>Navigating Your Way: Installing Google Maps on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-0x800700e9-error-within-xbox-game-pass-and-windows-11/"><u>Rectifying 0X800700E9 Error Within Xbox Game Pass & Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/rediscover-the-lost-treasures-within-windows-11s-features/"><u>Rediscover the Lost Treasures Within Windows 11'S Features</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolved-how-to-address-iphones-external-device-recognition-error/"><u>Resolved: How to Address iPhone's External Device Recognition Error</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-black-screens-with-simple-win11-tweaks/"><u>Resolving Black Screens with Simple Win11 Tweaks</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-solo-side-windows-earbud-sound-problems/"><u>Resolving Solo Side Windows Earbud Sound Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-access-to-disabled-windows-apps/"><u>Restoring Access to Disabled Windows Apps</u></a></li>
<li><a href="https://common-error.techidaily.com/simple-solutions-thawing-out-your-unresponsive-pc/"><u>Simple Solutions: Thawing Out Your Unresponsive PC</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-to-reduce-high-wmi-cpu-consumption/"><u>Solutions to Reduce High WMI CPU Consumption</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-mending-non-responsive-windows-network/"><u>Strategies for Mending Non-Responsive Windows Network</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-visual-comfort-notebook-themes-and-fonts-in-windows-11/"><u>Tailoring Visual Comfort: Notebook Themes and Fonts in Windows 11</u></a></li>
<li><a href="https://techidaily.com/the-easiest-methods-to-hard-reset-oneplus-ace-2v-drfone-by-drfone-reset-android-reset-android/"><u>The Easiest Methods to Hard Reset OnePlus Ace 2V | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-complex-windows-partition-unification/"><u>The Ultimate Guide to Complex Windows Partition Unification</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/top-6-appsservices-to-trace-any-apple-iphone-xs-location-by-mobile-number-drfone-by-drfone-virtual-ios/"><u>Top 6 Apps/Services to Trace Any Apple iPhone XS Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/top-methods-to-enhance-utorrent-download-speed-win-edition/"><u>Top Methods to Enhance uTorrent Download Speed, WIN Edition</u></a></li>
<li><a href="https://buynow-help.techidaily.com/top-review-of-rca-video-doorbell-camera-delivers-superior-security-quality/"><u>Top Review of RCA Video Doorbell Camera - Delivers Superior Security Quality</u></a></li>
<li><a href="https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-motorola-moto-g24-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Troubleshooting Guide How to Fix an Unresponsive Motorola Moto G24 Screen | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-storage-type-ssd-vs-hdd/"><u>Unveiling Storage Type: SSD vs HDD</u></a></li>
<li><a href="https://network-issues.techidaily.com/unveiling-the-secret-to-smooth-graphic-switching-in-windows-11/"><u>Unveiling the Secret to Smooth Graphic Switching in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-and-edge-background-runs-how-to-control/"><u>Win11 and Edge Background Runs - How to Control</u></a></li>
</ul></div>
