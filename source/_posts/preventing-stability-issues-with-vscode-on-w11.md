---
title: Preventing Stability Issues with VSCode on W11
date: 2024-08-15T16:03:33.285Z
updated: 2024-08-16T16:03:33.285Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Preventing Stability Issues with VSCode on W11
excerpt: This Article Describes Preventing Stability Issues with VSCode on W11
keywords: VSCode Stability Fix,Code Editor Stability,W11 vsCode Tips,Stable VSCode W11,Editing Software Optimization,VSCode Performance Tips,Stability in VSCode on Windows 11
thumbnail: https://thmb.techidaily.com/12fbcccb55845f8983544f25e1cc6b0c0aa528d408cbc232f59c597fcdf5f91a.png
---

## Preventing Stability Issues with VSCode on W11

 Visual Studio Code is a popular IDE widely preferred by programming enthusiasts. Microsoft revamped its user interface and made it available on Microsoft Store as well. You can even install multiple extensions in Visual Studio Code to make your programming experience better.

 But many users face abrupt crashes in the Visual Studio Code app which impedes their workflow. If you face the same issue repeatedly, don't worry. We will list out multiple fixes so that you can try and resolve the issue on your computer. Let's dive into the post.

## 1\. Terminate Visual Studio Code and Restart

 Before moving on to more complex fixes for the app, completely close Visual Studio Code using Task Manager and restart it. Here's how to do it:

1. Right-click on the**Start** button to open the [Power User menu](https://www.makeuseof.com/windows-power-menu-guide/) . Click on the**Task Manager** option.
2. Locate the Visual Studio Code process in the list of active processes.
3. Right-click on it and click on the**End Task** option from the context menu. It will close Visual Studio Code app and all its associated processes.  
![Terminate Visual Studio Code and Restart](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/terminate-visual-studio-code-and-restart.jpg)
4. Close the Task Manager window and open the Start menu.
5. Type Visual Studio Code and run the app with administrator privileges. Check if it encounters a crash now.

## 2\. Reboot your System

 Restarting the system is the oldest trick in the book. It might not sound effective but resolves most of the system issues. Restarting a system helps in closing all the active processes and services, clearing the system memory, and relaunching them. Due to this, any services or apps that aren't working will also restart afresh.

**Right-click** on the Start button and select the**Restart** option from the Power user menu. After the system restarts, run the Visual Studio Code with administrator permissions and check if it crashes.

## 3\. Disable Hardware Acceleration

 Hardware acceleration can cause problems on the low-spec system running the Visual Studio app. There isn’t an option for this feature in the app settings. So, you must modify the argv.json file to disable it. Here's how:

1. Launch Visual Studio Code and click on the**Settings** icon in the bottom left corner.
2. Select the**Command Palette** option from the settings menu and click on the**Preferences: Configure Runtime Arguments** option.
3. Now, enter the following command in the argv.json file:**"disable-hardware-acceleration": true**  
![Disable Hardware Acceleration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-hardware-acceleration.jpg)
4. Press**Ctrl+ S** to save the changes to the file.
5. Restart the app and check if it crashes now.

<!-- affiliate ads begin -->
<span id="1993652">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Perform a Clean Boot

 Often, third-party apps and services can interfere with other apps and cause app freezes and crashes. So, to rule out this possibility, do a [clean boot of your Window system](https://www.makeuseof.com/clean-boot-windows-11/) with only Microsoft-related services enabled on startup.

 If Visual Studio Code works fine after a clean boot, retry the clean boot while enabling some third-party service. Repeat this process until you find the problematic service or app.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->
## 5\. Disable Visual Studio Code Extensions

 Visual Studio Code needs extensions to extend language and debugger support for various programming languages. If you use extensions, you must find and remove the troublesome ones. Here's how to do it:

1. Launch Visual Studio Code and press**Ctrl+ Shift + X** to open the extensions settings.
2. Click on the**Installed** option to display all the extensions installed in the Visual Studio Code app.
3. Right-click on any extension and select the**Disable** option from the context menu.  
![Disable Visual Studio Code Extensions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-visual-studio-code-extensions.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
4. Repeat this process for all extensions to disable them.
5. Now restart the Visual Studio Code app and run it for some time without any extensions. If it doesn't crash, an extension is probably the reason behind the crash.
6. To identify the extension, revisit the Extension settings in the app and right-click on a disabled extension. Select the**Enable** option.
7. Check if Visual Studio Code encounters a crash when this extension is active. Repeat the process to find the culprit extension and remove it from the app.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
## 6\. Exclude Visual Studio Code in Windows Defender

 Antivirus programs do not play nicely with apps and programs and often wrongly flag them. So, add an exclusion for the Visual Studio Code app. If you use a third-party antivirus on your system, add an exclusion for the Visual Studio Code app directory by accessing its settings. You can even [temporarily disable Windows Security](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) and run the app to check if it crashes now.

## 7\. Update Visual Studio Code

 If you are using a very old version of Visual Studio Code and are facing abrupt crashes, then you must update the app. A new app update brings security improvements and bug fixes which could exist in the old version of the app. Here’s how to update the app:

1. Open Visual Studio Code and click on the**Settings** icon.
2. Select the**Check for updates** option from the context menu.  
![Update the Visual Studio Code](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/update-the-visual-studio-code.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
3. If there is an update available, download and install it and restart your computer.
4. Launch the app again and use it for some time while keeping an eye out for crashes.

## 8\. Roll Back the Last Windows Update

 Windows updates can break system features or not sit well with third-party apps. If you encounter the app crash issue after a recent update,[manually uninstall the most recent Windows update](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) on your computer. It will revert all the new changes made to your system.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## 9\. Reinstall Visual Studio Code

 If the app installation is severely corrupt and unfixable, then a simple app reset won’t be effective. Instead, you must completely remove Visual Studio Code from your system and then reinstall it.

 Repeat the following steps to reinstall Visual Studio Code using Winget:

1. Press**Win + R** to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**cmd** in the text input box and press**Ctrl + Shift + Enter** to launch the command prompt with administrator rights.
3. Accept the UAC prompt and click on the**Yes** button.
4. Type the following command and press enter key:**Winget list**
5. Copy the ID of the Visual Studio Code app and paste it after the following command:**winget uninstall \[App ID\]**  
winget uninstall Microsoft.VisualStudioCode
6. Wait for the uninstallation to complete. Restart your system.  
![Reinstall Visual Studio Code 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reinstall-visual-studio-code-1.jpg)
7. Launch the Command Prompt with admin privileges again.
8. Then type the following command and press the enter key:**winget install Microsoft.VisualStudioCode**  
![Reinstall Visual Studio Code 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reinstall-visual-studio-code-2.jpg)
9. It will take a while to download and install the app on your system. You won’t need to interact with the installer window or grant any permissions.
10. Run Visual Studio Code now and check if the app encounters any crashes now.

## 10\. Use the Web Version

 Microsoft even offers a [web version of Visual Studio Code](https://vscode.dev/) which you can use as a temporary solution. You can sign in to the web version and sync your files and settings. Moreover, you can install a PWA from the browser of Visual Studio Code and launch it directly from your desktop.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
<!-- affiliate ads end -->
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
<li><a href="https://facebook-video-content.techidaily.com/new-automatic-video-launch-on-your-facebook-page/"><u>[New] Automatic Video Launch on Your Facebook Page</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-accessible-visual-aids-for-youtube-videos/"><u>[Updated] 2024 Approved  Accessible Visual Aids for YouTube Videos</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-comprehensive-guide-to-advanced-screen-capture-via-adobe-captive-for-2024/"><u>[Updated] Comprehensive Guide to Advanced Screen Capture via Adobe Captive for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-seamless-techniques-for-swift-removal-of-your-youtube-comments/"><u>[Updated] In 2024, Seamless Techniques for Swift Removal of Your Youtube Comments</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/5-ways-to-restart-motorola-defy-2-without-power-button-drfone-by-drfone-reset-android-reset-android/"><u>5 Ways to Restart Motorola Defy 2 Without Power Button | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/a-systematic-approach-to-fixing-the-zeroxc000003e-issue/"><u>A Systematic Approach to Fixing the ZeroXc000003e Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/balancing-audio-dynamics-for-bluetooth-devices/"><u>Balancing Audio Dynamics for Bluetooth Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-efail-error-code-0x80004005-in-virtualbox/"><u>Combatting E_FAIL (Error Code: 0X80004005) in Virtualbox</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-hacks-for-identifying-windows-age/"><u>Expert Hacks for Identifying Windows Age</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-to-retrieve-the-missing-windows-product-patch/"><u>Expert Tips to Retrieve the Missing Windows Product Patch</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-bsod-errors-tackling-interrupt-exceptions-on-windows-11/"><u>Fixing BSOD Errors: Tackling Interrupt Exceptions on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-writing-permission-failure-in-windows-10-and-11/"><u>Fixing Writing Permission Failure in Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/flipping-a-non-working-search-bar-in-windows-11s-settings/"><u>Flipping a Non-Working Search Bar in Windows 11’S Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-network-error-0x800704b3-in-windows-11-and-11/"><u>How to Fix the Network Error 0X800704b3 in Windows 11 & 11</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-unlock-icloud-activation-lock-and-icloud-account-on-apple-iphone-7-by-drfone-ios/"><u>How to Unlock iCloud Activation Lock and iCloud Account On Apple iPhone 7?</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-implementing-the-virtual-screen-grid-in-google-meet/"><u>In 2024, Implementing the Virtual Screen Grid in Google Meet</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-outlining-operational-offshoots/"><u>In 2024, Outlining Operational Offshoots</u></a></li>
<li><a href="https://some-guidance.techidaily.com/incandescent-ideas-innovations-for-stellar-cinematography-for-2024/"><u>Incandescent Ideas  Innovations for Stellar Cinematography for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/initiating-changes-accessing-fax-editor-in-the-newest-os/"><u>Initiating Changes: Accessing Fax Editor in the Newest OS</u></a></li>
<li><a href="https://windows11.techidaily.com/keyboard-knots-unraveling-win10-functional-issues/"><u>Keyboard Knots: Unraveling WIN10 Functional Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-labels-for-efficient-file-management-on-windows-11/"><u>Leveraging Labels for Efficient File Management on Windows 11</u></a></li>
<li><a href="https://technical-tips.techidaily.com/navigating-social-footprints-how-to-pinpoint-people-who-shared-your-post-on-facebook/"><u>Navigating Social Footprints: How to Pinpoint People Who Shared Your Post on Facebook</u></a></li>
<li><a href="https://windows11.techidaily.com/perfecting-the-art-shrink-or-enlarge-apps-using-shortcut-on-win11/"><u>Perfecting the Art: Shrink or Enlarge Apps Using Shortcut on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-to-tackling-error-1053-unresponsive-windows-services/"><u>Quick Guide to Tackling Error 1053: Unresponsive Windows Services</u></a></li>
<li><a href="https://windows11.techidaily.com/reactivate-quieted-slack-feedback-in-win-11-systems/"><u>Reactivate Quieted Slack Feedback in Win 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/reboot-to-reconnect-reviving-ethernet-net-access/"><u>Reboot to Reconnect: Reviving Ethernet Net Access</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-integration-effortlessly-managing-tabs-in-windows-11/"><u>Seamless Integration: Effortlessly Managing Tabs in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-unstartable-windows-vms-with-vmware/"><u>Solutions for Unstartable Windows VMs with VMware</u></a></li>
<li><a href="https://windows11.techidaily.com/speeding-up-typing-typingaids-expertise/"><u>Speeding Up Typing: TypingAid's Expertise</u></a></li>
<li><a href="https://windows11.techidaily.com/stepwise-strategy-for-full-removal-of-wsl-on-windows-11/"><u>Stepwise Strategy for Full Removal of WSL on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-disconnect-untrusted-users-from-windows-11/"><u>Techniques to Disconnect Untrusted Users From Windows 11</u></a></li>
<li><a href="https://techidaily.com/the-best-electronic-signature-way-to-sign-dotx-file-documents-online-by-ldigisigner-sign-a-word-sign-a-word/"><u>The best electronic signature way to sign .dotx file documents online</u></a></li>
<li><a href="https://windows11.techidaily.com/the-hidden-dangers-in-bot-made-win-11-codes/"><u>The Hidden Dangers in Bot-Made Win 11 Codes</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-resolving-unresponsiveness-in-your-windows-downloads-hub/"><u>Tips for Resolving Unresponsiveness in Your Windows Downloads Hub</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-for-no-sound-when-screencasting-with-powerpoint/"><u>Troubleshooting for No Sound when Screencasting with PowerPoint</u></a></li>
<li><a href="https://windows11.techidaily.com/unfolding-wxpxo11-dilemnas-fixes-for-non-openable-folders-after-double-clicks/"><u>Unfolding WXP/XO11 Dilemnas: Fixes for Non-Openable Folders After Double-Clicks</u></a></li>
<li><a href="https://media-tips.techidaily.com/universal-aiff-file-playback-software-for-pcs-and-mobile-devices-windows-mac-ios-android/"><u>Universal AIFF File Playback Software for PCs and Mobile Devices (Windows, Mac, iOS, Android)</u></a></li>
<li><a href="https://win-solutions.techidaily.com/update-overcoming-launch-difficulties-with-resident-evil-village/"><u>Update: Overcoming Launch Difficulties with Resident Evil Village</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-edit-your-way-to-success-top-vlog-video-editing-software-free-and-paid/"><u>Updated In 2024, Edit Your Way to Success Top Vlog Video Editing Software Free & Paid</u></a></li>
<li><a href="https://windows11.techidaily.com/upgrade-your-win11s-connectivity-with-these-high-priority-solutions/"><u>Upgrade Your Win11's Connectivity with These High-Priority Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/verify-the-validity-three-ways-to-check-windows-11/"><u>Verify the Validity: Three Ways to Check Windows 11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/virtual-world-bonding-top-10-collaborative-games/"><u>Virtual World Bonding - Top 10 Collaborative Games</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-strategy-enhancing-hard-drive-performance/"><u>Win11 Strategy: Enhancing Hard Drive Performance</u></a></li>
</ul></div>
