---
title: Tips to Avoid VSCode Crashing on New OS
date: 2024-08-27T16:09:20.157Z
updated: 2024-08-28T16:09:20.157Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tips to Avoid VSCode Crashing on New OS
excerpt: This Article Describes Tips to Avoid VSCode Crashing on New OS
keywords: NoCrashVSCodeOS,StableVSCodeUpdate,PreventVSCOSError,OptimizeVSCodePerformance,SecureVSCodeNewOS,MinimizeVSCodeStabilityIssues,EnhanceVSCodeSystemCompatibility
thumbnail: https://thmb.techidaily.com/487e676cadbed9c7366304118c5d69cbccc78efab49f48ed06a998718358fad4.jpg
---

## Tips to Avoid VSCode Crashing on New OS

 Visual Studio Code is a popular IDE widely preferred by programming enthusiasts. Microsoft revamped its user interface and made it available on Microsoft Store as well. You can even install multiple extensions in Visual Studio Code to make your programming experience better.

 But many users face abrupt crashes in the Visual Studio Code app which impedes their workflow. If you face the same issue repeatedly, don't worry. We will list out multiple fixes so that you can try and resolve the issue on your computer. Let's dive into the post.

## 1\. Terminate Visual Studio Code and Restart

 Before moving on to more complex fixes for the app, completely close Visual Studio Code using Task Manager and restart it. Here's how to do it:

1. Right-click on the**Start** button to open the[Power User menu](https://www.makeuseof.com/windows-power-menu-guide/) . Click on the**Task Manager** option.
2. Locate the Visual Studio Code process in the list of active processes.
3. Right-click on it and click on the**End Task** option from the context menu. It will close Visual Studio Code app and all its associated processes.  
![Terminate Visual Studio Code and Restart](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/terminate-visual-studio-code-and-restart.jpg)
4. Close the Task Manager window and open the Start menu.
5. Type Visual Studio Code and run the app with administrator privileges. Check if it encounters a crash now.

## 2\. Reboot your System

 Restarting the system is the oldest trick in the book. It might not sound effective but resolves most of the system issues. Restarting a system helps in closing all the active processes and services, clearing the system memory, and relaunching them. Due to this, any services or apps that aren't working will also restart afresh.

**Right-click** on the Start button and select the**Restart** option from the Power user menu. After the system restarts, run the Visual Studio Code with administrator permissions and check if it crashes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
<!-- affiliate ads end -->
## 3\. Disable Hardware Acceleration

 Hardware acceleration can cause problems on the low-spec system running the Visual Studio app. There isn’t an option for this feature in the app settings. So, you must modify the argv.json file to disable it. Here's how:

1. Launch Visual Studio Code and click on the**Settings** icon in the bottom left corner.
2. Select the**Command Palette** option from the settings menu and click on the**Preferences: Configure Runtime Arguments** option.
3. Now, enter the following command in the argv.json file:**"disable-hardware-acceleration": true**  
![Disable Hardware Acceleration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-hardware-acceleration.jpg)
4. Press**Ctrl+ S** to save the changes to the file.
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
5. Restart the app and check if it crashes now.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Perform a Clean Boot

 Often, third-party apps and services can interfere with other apps and cause app freezes and crashes. So, to rule out this possibility, do a[clean boot of your Window system](https://www.makeuseof.com/clean-boot-windows-11/) with only Microsoft-related services enabled on startup.

 If Visual Studio Code works fine after a clean boot, retry the clean boot while enabling some third-party service. Repeat this process until you find the problematic service or app.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4742929&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/boxshot(2).png" border="0">Kanto Player Professional</a>
<!-- affiliate ads end -->
## 5\. Disable Visual Studio Code Extensions

 Visual Studio Code needs extensions to extend language and debugger support for various programming languages. If you use extensions, you must find and remove the troublesome ones. Here's how to do it:

1. Launch Visual Studio Code and press**Ctrl+ Shift + X** to open the extensions settings.
2. Click on the**Installed** option to display all the extensions installed in the Visual Studio Code app.
3. Right-click on any extension and select the**Disable** option from the context menu.  
![Disable Visual Studio Code Extensions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-visual-studio-code-extensions.jpg)
4. Repeat this process for all extensions to disable them.
5. Now restart the Visual Studio Code app and run it for some time without any extensions. If it doesn't crash, an extension is probably the reason behind the crash.
6. To identify the extension, revisit the Extension settings in the app and right-click on a disabled extension. Select the**Enable** option.
7. Check if Visual Studio Code encounters a crash when this extension is active. Repeat the process to find the culprit extension and remove it from the app.

## 6\. Exclude Visual Studio Code in Windows Defender

 Antivirus programs do not play nicely with apps and programs and often wrongly flag them. So, add an exclusion for the Visual Studio Code app. If you use a third-party antivirus on your system, add an exclusion for the Visual Studio Code app directory by accessing its settings. You can even[temporarily disable Windows Security](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) and run the app to check if it crashes now.

## 7\. Update Visual Studio Code

 If you are using a very old version of Visual Studio Code and are facing abrupt crashes, then you must update the app. A new app update brings security improvements and bug fixes which could exist in the old version of the app. Here’s how to update the app:

1. Open Visual Studio Code and click on the**Settings** icon.
2. Select the**Check for updates** option from the context menu.  
![Update the Visual Studio Code](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/update-the-visual-studio-code.jpg)
3. If there is an update available, download and install it and restart your computer.
4. Launch the app again and use it for some time while keeping an eye out for crashes.

## 8\. Roll Back the Last Windows Update

 Windows updates can break system features or not sit well with third-party apps. If you encounter the app crash issue after a recent update,[manually uninstall the most recent Windows update](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) on your computer. It will revert all the new changes made to your system.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
## 9\. Reinstall Visual Studio Code

 If the app installation is severely corrupt and unfixable, then a simple app reset won’t be effective. Instead, you must completely remove Visual Studio Code from your system and then reinstall it.

 Repeat the following steps to reinstall Visual Studio Code using Winget:

1. Press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**cmd** in the text input box and press**Ctrl + Shift + Enter** to launch the command prompt with administrator rights.
3. Accept the UAC prompt and click on the**Yes** button.
4. Type the following command and press enter key:**Winget list**
5. Copy the ID of the Visual Studio Code app and paste it after the following command:**winget uninstall \[App ID\]**  
winget uninstall Microsoft.VisualStudioCode
6. Wait for the uninstallation to complete. Restart your system.  
![Reinstall Visual Studio Code 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reinstall-visual-studio-code-1.jpg)
7. Launch the Command Prompt with admin privileges again.
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
8. Then type the following command and press the enter key:**winget install Microsoft.VisualStudioCode**  
![Reinstall Visual Studio Code 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reinstall-visual-studio-code-2.jpg)
9. It will take a while to download and install the app on your system. You won’t need to interact with the installer window or grant any permissions.
10. Run Visual Studio Code now and check if the app encounters any crashes now.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
## 10\. Use the Web Version

 Microsoft even offers a[web version of Visual Studio Code](https://vscode.dev/) which you can use as a temporary solution. You can sign in to the web version and sync your files and settings. Moreover, you can install a PWA from the browser of Visual Studio Code and launch it directly from your desktop.

## Visual Studio Code Won’t Crash Anymore on Windows 11

 Microsoft’s popular IDE is the go-to tool of programmers. If its crashes abruptly, the projects can get delayed by quite a bit. Start with basic troubleshooting and then disable hardware acceleration on your system. After that, disable extensions and perform a clean boot. Add an exclusion for the app in the antivirus program. Lastly, if nothing works, reinstall the Visual Studio Code app on your system.


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
<li><a href="https://youtube-sure.techidaily.com/024-approved-creating-compelling-channel-names-simplified/"><u>[New] 2024 Approved  Creating Compelling Channel Names Simplified</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-digital-companion-fb-stories-collector/"><u>[Updated] In 2024, Digital Companion - FB Stories Collector</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-quest-masters-choice-celebrating-gaming-epics-anew-for-2024/"><u>[Updated] Quest Masters' Choice  Celebrating Gaming Epics Anew for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-optimizing-video-playback-sizes-on-youtube/"><u>2024 Approved  Optimizing Video Playback Sizes on YouTube</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-ultimate-guide-to-securing-photographic-backdrops/"><u>2024 Approved  Ultimate Guide to Securing Photographic Backdrops</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/discover-the-best-free-3d-animation-apps-for-android-iphone-and-ipad-for-2024/"><u>Discover the Best Free 3D Animation Apps for Android, iPhone, and iPad for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/fixes-for-corrupted-files-in-windows-10-and-11/"><u>Fixes for Corrupted Files in Windows 10 and 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-absence-of-file-notifications-in-windows-11/"><u>Fixing Absence of File Notifications in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-halt-windows-11-data-harvesting/"><u>Guide to Halt Windows 11 Data Harvesting</u></a></li>
<li><a href="https://some-techniques.techidaily.com/how-can-i-stop-my-videos-from-flipping-on-instagram-for-2024/"><u>How Can I Stop My Videos From Flipping on Instagram for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-adobe-photoshop-2021-2023-not-opening-on-windows-10-and-11/"><u>How to Fix Adobe Photoshop 2021-2023 Not Opening on Windows 10 & 11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-xiaomi-redmi-12-5g-phone-with-broken-screen-by-drfone-android/"><u>How to Unlock Xiaomi Redmi 12 5G Phone with Broken Screen</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-complete-guide-for-apple-iphone-12-lock-screen-drfone-by-drfone-ios/"><u>In 2024, Complete Guide For Apple iPhone 12 Lock Screen | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-essential-history-series-youtube-recommendations-for-learners/"><u>In 2024, Essential History Series  YouTube Recommendations for Learners</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-powershell-to-gauge-file-sizes-in-os/"><u>Leveraging PowerShell to Gauge File Sizes in OS</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-time-transferring-classic-titles-to-photos/"><u>Navigating Through Time: Transferring Classic Titles to Photos</u></a></li>
<li><a href="https://windows11.techidaily.com/procurement-primer-essential-considerations-for-laptop-shoppers/"><u>Procurement Primer: Essential Considerations for Laptop Shoppers</u></a></li>
<li><a href="https://windows11.techidaily.com/proven-methods-to-uncover-the-hidden-mac-addresses-on-windows-11/"><u>Proven Methods to Uncover the Hidden MAC Addresses on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-start-windows-os-on-your-playstation-steam-device/"><u>Quick Start: Windows OS on Your PlayStation Steam Device</u></a></li>
<li><a href="https://windows11.techidaily.com/reboot-and-reclaim-resetting-ms-store-in-windows-1011/"><u>Reboot and Reclaim: Resetting MS Store in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-administrative-functionality-in-microsoft-tools/"><u>Restoring Administrative Functionality in Microsoft Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-functionality-in-windows-services-explorer-with-these-7-steps/"><u>Restoring Functionality in Windows Services Explorer with These 7 Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-play-eradicating-xbox-service-block/"><u>Seamless Play: Eradicating Xbox Service Block</u></a></li>
<li><a href="https://windows11.techidaily.com/stability-in-app-placement-for-task-manager-users/"><u>Stability in App Placement for Task Manager Users</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-correcting-windows-backup-defaults/"><u>Steps for Correcting Windows Backup Defaults</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-enable-user-sign-in-following-windows-setback/"><u>Steps to Enable User Sign-In Following Windows Setback</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-dealing-with-non-downloading-errors-on-windows/"><u>Strategies for Dealing with Non-Downloading Errors on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-rectifying-c0000005-on-windows-7vista/"><u>Strategies for Rectifying C0000005 on Windows 7/Vista</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-windows-security-hurdles-with-precision-and-care/"><u>Tackling Windows Security Hurdles with Precision & Care</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/top-6-nutrition-tracking-apps-you-should-try-today/"><u>Top 6 Nutrition Tracking Apps You Should Try Today</u></a></li>
<li><a href="https://windows11.techidaily.com/top-ways-to-resolve-black-screens-in-win1111-pro/"><u>Top Ways to Resolve Black Screens in Win11/11 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-directx-installation-issues/"><u>Troubleshooting DirectX Installation Issues</u></a></li>
<li><a href="https://fake-location.techidaily.com/ultimate-guide-to-free-pptp-vpn-for-beginners-on-infinix-hot-30i-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Free PPTP VPN For Beginners On Infinix Hot 30i | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/ultimate-spots-for-discovering-rich-gold-text-effects/"><u>Ultimate Spots for Discovering Rich, Gold Text Effects</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-administrative-potential-with-advanced-task-management-in-win11/"><u>Unleash Administrative Potential with Advanced Task Management in Win11</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/vivo-y27s-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>Vivo Y27s ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://article-posts.techidaily.com/what-to-do-with-icloud-drives-desktop-anddocuments-access-in-sierra-for-2024/"><u>What to Do with iCloud Drive’s Desktop &Documents Access in Sierra for 2024</u></a></li>
</ul></div>
