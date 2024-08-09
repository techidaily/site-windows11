---
title: How to Activate/Deactivate VM Security with Secure Boot on VirtualBox 7.0
date: 2024-08-08T06:08:16.725Z
updated: 2024-08-09T06:08:16.725Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Activate/Deactivate VM Security with Secure Boot on VirtualBox 7.0
excerpt: This Article Describes How to Activate/Deactivate VM Security with Secure Boot on VirtualBox 7.0
keywords: VirtualBox SecureBoot,VM ActivationVM Deactivation,SecureBoot VMControl,VirtualBox BootModeSecure,VM SecurityOnOffVirtualBox,On/OffVMSecuritySecure,SwitchSecureBootVMState
thumbnail: https://thmb.techidaily.com/f7921a39c56c18854a738fb18f72fdf7d073d94792cd13b7517a6bd96365dcaf.jpg
---

## How to Activate/Deactivate VM Security with Secure Boot on VirtualBox 7.0

 VirtualBox released version 7.0 in October 2022\. It is the first hypervisor to support the emulation of TPM chips along with all the other system components. VirtualBox also offers a Secure Boot feature in EFI mode for virtual machines. The main reason behind these two features was Microsoft's list of elaborate system requirements for Windows 11.

 Without emulation of the TPM 2.0 chip, users couldn't install Windows 11 on a virtual machine. But with VirtualBox 7.0 it is possible to enable Secure Boot and TPM for any Windows virtual machine. This post will elaborate on the methods to enable or disable TPM and Secure Boot for any VirtualBox virtual machine.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->
## Why Does Windows 11 Need TPM and Secure Boot?

 Windows 11 needs both a TPM chip and Secure Boot to offer robust protection against threats and not allow any malware to run when the system boots up. Secure Boot only allows signed drivers to load and the TPM chip helps in BitLocker drive data protection. So, both these features are pretty important from a security standpoint. Check out our guide on[what Secure Boot is and how it works](https://www.makeuseof.com/what-is-secure-boot-how-does-it-work/) for more information.

 While Windows 11 can work without Secure Boot and a TPM 2.0 chip, it won't be able to offer that extra layer of system protection it would do otherwise. Many features like Core-isolation, Data Encryption won't work. If you want to enable or disable these features for Windows 10 or 11 virtual machines, you can do so in VirtualBox 7.0.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Enable or Disable Secure Boot and TPM Support in VirtualBox 7.0

 Repeat the following steps to enable TPM 2.0 and Secure Boot in VirtualBox.

1. Press the**Win** key and search VirtualBox. Click on the first relevant search result to launch the app.
2. Click on a Windows virtual machine and then click on the**Settings** icon.
3. Navigate to the**System** settings option.
4. Find the**TPM** option. If it is set to none, click on the**arrow** icon to open the drop-down menu.
5. Select the TPM**v2.0** option from the list. Windows 11 won't work with anything lower but if you are using Windows 10 then you can pick**v1.2** from the list.
6. Scroll down and locate the**Extended Features** section. Click on the**Enable EFI (special OSes only)** option check box.
7. Then click on the**Enable Secure Boot** option check box.  
![Enable Secure Boot and TPM Support in VirtualBox 7.0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/enable-secure-boot-and-tpm-support-in-virtualbox-7-0.jpg)
8. Now, click on the**OK** button. The settings window will close automatically.
9. Go to the top area and click on the**Start** button to power on the Windows virtual machine.
10. Now, press the Win key and search Security. Open the**Windows security** app.
11. Navigate to the left-hand side menu and click on the**Device Security** option. Here, all Windows security features will be active.
12. To disable TPM and Secure Boot, reopen the virtual machine settings and set the TPM version to**None** . Uncheck the**Enable EFI (special OSes only)** option check box. Click on**OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->
### An Alternative Method to Check if TPM Is Active in the Windows Virtual Machine

Here's how to check TPM on Windows 11 virtual machine:

1. Press the**Win + R** key to launch the Run command box (see[how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways). Type**TPM.msc** and press the**Enter** key.  
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->
![check TPM on Windows 11 virtual machine 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-1.jpg)
2. TPM utility will launch. Navigate to the Manufacturer Information section.  
<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->
![check TPM on Windows 11 virtual machine 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-2.jpg)
3. If the Specification version entry showcases 2.0, it means that TPM chip emulation is successful.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->
## Manage TPM and Secure Boot Features in VirtualBox With Ease

 You can choose to keep both features active or not. After installing Windows 11 as a virtual machine, you can turn TPM and Secure Boot off and not face any issues with the operating system. However, remember that these are important from a security perspective.


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
<li><a href="https://article-tips.techidaily.com/new-2024-approved-drone-selections-on-a-budget-affordable-options-above/"><u>[New] 2024 Approved  Drone Selections on a Budget  Affordable Options Above</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-emulate-history-essential-ps1-games-for-pc-lovers-for-2024/"><u>[New] Emulate History  Essential PS1 Games for PC Lovers for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-experts-selection-17-programs-for-flawless-picture-editing/"><u>[New] Expert's Selection  17 Programs for Flawless Picture Editing</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-lapithexcellence-discovering-the-creme-de-la-creme-of-laps-backgrounds/"><u>[New] Lapithexcellence  Discovering the Crème De La Créme of Laps Backgrounds</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-legal-and-ethical-methods-boosting-your-tiktok-profile-for-2024/"><u>[New] Legal and Ethical Methods  Boosting Your TikTok Profile for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-shrouded-screen-images-techniques-for-redacting-info/"><u>[New] Shrouded Screen Images  Techniques for Redacting Info</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-leading-ipad-audio-recorder-software-list-3/"><u>[Updated] 2024 Approved  Leading iPad Audio Recorder Software List #3</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-framegauge-evaluator-suite-for-2024/"><u>[Updated] FrameGauge Evaluator Suite for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-the-ultimate-guide-key-drone-upgrades-and-supplies/"><u>[Updated] In 2024, The Ultimate Guide  Key Drone Upgrades & Supplies</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unleash-creativity-with-snapchats-advanced-zooming/"><u>[Updated] Unleash Creativity with Snapchat's Advanced Zooming</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-from-syncing-to-capturing-a-complete-itunes-journey/"><u>2024 Approved  From Syncing to Capturing  A Complete iTunes Journey</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-the-secret-behind-crafting-mesmerizing-slow-motion-media-for-instagram/"><u>2024 Approved  The Secret Behind Crafting Mesmerizing Slow Motion Media for Instagram</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-unveiling-the-secrets-of-facebook-lives-dual-display/"><u>2024 Approved  Unveiling the Secrets of Facebook Live's Dual Display</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-solutions-to-hard-reset-samsung-galaxy-m14-5g-phone-using-pc-drfone-by-drfone-reset-android-reset-android/"><u>3 Solutions to Hard Reset Samsung Galaxy M14 5G Phone Using PC | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/capturing-stills-in-time-a-guide-to-slow-motion-on-ig/"><u>Capturing Stills in Time  A Guide to Slow Motion on IG</u></a></li>
<li><a href="https://fox-access.techidaily.com/dji-inspire-2-complete-evaluation-for-2024/"><u>DJI Inspire 2  Complete Evaluation for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/easily-switch-your-windows-11-logon-technique-ditch-pin-embrace-password/"><u>Easily Switch Your Windows 11 Logon Technique: Ditch PIN, Embrace Password</u></a></li>
<li><a href="https://windows11.techidaily.com/easing-excessive-load-alert-for-gpt-window-use/"><u>Easing Excessive Load Alert for GPT Window Use</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-steps-for-activating-outlook-preview-in-windows-11-os/"><u>Easy Steps for Activating Outlook Preview in Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-methods-to-fix-error-code-0x80041015/"><u>Effective Methods to Fix Error Code 0X80041015</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-strategies-for-cleansing-steam-dns-cache/"><u>Effective Strategies for Cleansing Steam DNS Cache</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-playback-of-laggard-videos/"><u>Efficient Playback of Laggard Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-strategies-to-address-directdraw-errors-in-newer-windows-editions/"><u>Efficient Strategies to Address DirectDraw Errors in Newer Windows Editions</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-task-management-on-windows-11/"><u>Efficient Task Management on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-altering-windows-account-pin-code/"><u>Efficiently Altering Windows Account Pin Code</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-run-windows-11-news-and-video-sites-without-strain/"><u>Efficiently Run Windows 11 News & Video Sites without Strain</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-telnet-configuration-for-win11-users/"><u>Effortless Telnet Configuration for Win11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-performance-top-tools-to-tune-up-windows-pcs/"><u>Elevate Performance: Top Tools to Tune Up Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-to-the-top-with-these-key-windows-11-widgets/"><u>Elevate to the Top with These Key Windows 11 Widgets</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-webp-experience-with-these-4-windows-viewer-tools/"><u>Elevate WebP Experience with These 4 Windows Viewer Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-workflow-select-7-most-powerful-w11-widgets/"><u>Elevate Workflow: Select 7 Most Powerful W11 Widgets</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-application-display-enable-windows-11s-autocolor/"><u>Elevate Your Application Display - Enable Windows 11'S AutoColor</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-workflow-with-god-mode-add-on/"><u>Elevate Your Workflow with God Mode Add-On</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-workflow-on-windows-11-for-professionals/"><u>Elevating Workflow on Windows 11 for Professionals</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-your-app-setup-game-with-winstall-on-windows-11/"><u>Elevating Your App Setup Game with Winstall on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-the-error-unable-to-terminate-process-phenomenon/"><u>Eliminating the 'Error: Unable to Terminate Process' Phenomenon</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-unexpected-closure-notifications-from-roblox-games/"><u>Eliminating Unexpected Closure Notifications From Roblox Games</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-uninstall-troubles-with-epic-games-hub-w11/"><u>Eliminating Uninstall Troubles with Epic Games Hub W11</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-windows-0x800704b3-network-hurdles/"><u>Eliminating Windows' 0X800704B3 Network Hurdles</u></a></li>
<li><a href="https://windows11.techidaily.com/elusive-archive-tucked-away-zip-and-images-on-windows-11/"><u>Elusive Archive Tucked Away: ZIP & Images on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/embrace-the-best-of-both-worlds-windows-11-macos-in-parallels/"><u>Embrace the Best of Both Worlds: Windows 11, MacOS in Parallels</u></a></li>
<li><a href="https://windows11.techidaily.com/embracing-convenience-using-googles-nearby-share/"><u>Embracing Convenience: Using Google's Nearby Share</u></a></li>
<li><a href="https://windows11.techidaily.com/emulate-macos-style-5-methods-to-revamp-windows/"><u>Emulate macOS Style: 5 Methods to Revamp Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/enable-sd-card-view-in-file-explorer-puzzle-solved/"><u>Enable SD Card View in File Explorer Puzzle Solved</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-application-guard-printing-for-windows-11-users/"><u>Enabling Application Guard Printing for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-smooth-remote-play-via-windows-steam/"><u>Enabling Smooth Remote Play via Windows Steam</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-epic-launcher-performance-a-how-to/"><u>Enhancing Epic Launcher Performance: A How-To</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-mouse-cursor-prominence-in-windows-os/"><u>Enhancing Mouse Cursor Prominence in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-performance-win11-boot-routines/"><u>Enhancing Performance: Win11 Boot Routines</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-windows-event-viewer-functionality/"><u>Enhancing Windows Event Viewer Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-single-user-printer-operation-on-windows-11/"><u>Ensuring Single-User Printer Operation on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicating-hypervisorerr-bsod-in-windows-1011/"><u>Eradicating HYPERVISOR_ERR: BSOD in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/erase-webp-images-from-your-chrome-saved-collection-on-windows/"><u>Erase WebP Images From Your Chrome Saved Collection on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/error-2e-prevention-ensure-windows-update-works/"><u>Error 2E Prevention, Ensure Windows Update Works</u></a></li>
<li><a href="https://change-location.techidaily.com/how-can-i-get-more-stardust-in-pokemon-go-on-vivo-y56-5g-drfone-by-drfone-virtual-android/"><u>How can I get more stardust in pokemon go On Vivo Y56 5G? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-change-location-on-yik-yak-for-your-oppo-f25-pro-5g-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>In 2024, Change Location on Yik Yak For your Oppo F25 Pro 5G to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-tecno-spark-20-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Snapchat Location Spoofer to Protect Your Privacy On Tecno Spark 20? | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-ultimate-guide-10-cost-free-passport-image-makers/"><u>In 2024, The Ultimate Guide  10 Cost-Free Passport Image Makers</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/networking-galore-places-for-youtube-affiliate-marketing/"><u>Networking Galore  Places for YouTube Affiliate Marketing</u></a></li>
<li><a href="https://extra-skills.techidaily.com/quicken-your-visual-content-best-android-software-for-2024/"><u>Quicken Your Visual Content - Best Android Software for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-quickest-way-to-entertain-kapwing-memes-for-2024/"><u>The Quickest Way to Entertain - Kapwing Memes for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/ultimate-guide-to-get-the-meltan-box-pokemon-go-for-vivo-y56-5g-drfone-by-drfone-virtual-android/"><u>Ultimate guide to get the meltan box pokemon go For Vivo Y56 5G | Dr.fone</u></a></li>
<li><a href="https://driver-install.techidaily.com/update-pcs-graphics-capabilities-with-new-drivers/"><u>Update PC's Graphics Capabilities with New Drivers</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-techniques-for-quieting-the-soundscape-in-recorded-movies/"><u>Updated 2024 Approved Techniques for Quieting the Soundscape in Recorded Movies</u></a></li>
<li><a href="https://fake-location.techidaily.com/which-is-the-best-fake-gps-joystick-app-on-apple-iphone-8-drfone-by-drfone-virtual-ios/"><u>Which is the Best Fake GPS Joystick App On Apple iPhone 8? | Dr.fone</u></a></li>
</ul></div>
