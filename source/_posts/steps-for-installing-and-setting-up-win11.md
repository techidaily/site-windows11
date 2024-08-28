---
title: Steps for Installing and Setting Up Win11
date: 2024-08-27T16:10:20.353Z
updated: 2024-08-28T16:10:20.353Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps for Installing and Setting Up Win11
excerpt: This Article Describes Steps for Installing and Setting Up Win11
keywords: Win11 Setup Guide,Win11 Initialization Steps,Windows 11 Installation Procedures,Win11 Installation Process,Configuring Windows 11 OS,Win11 System Setup Instructions,Basic Win11 Configuration
thumbnail: https://thmb.techidaily.com/878905428de37ec37afcf7b8018e7d924bf2c1ca322a8100dfaafbd0ac4bcb97.jpg
---

## Steps for Installing and Setting Up Win11

 Microsoft requires your system to have an active internet connection to complete the Windows 11 setup. It asks you to log into your Microsoft account to download critical updates and new features before you can start using your freshly installed Windows operating system.

 This becomes an issue if you want to use a local user account or don’t have an active internet connection during setup. Luckily, there are a few workarounds to skip the Windows 11 network setup. Here we show you how to bypass this restriction and complete the Windows 11 setup without an internet connection.

## Why Does Windows 11's Setup Require an Internet Connection?

![lets connect you to a network](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/lets-connect-you-to-a-network.png)

 According to Microsoft, you need an active internet connection to perform updates and download and use some features. In addition, Windows 11 Home edition requires a Microsoft Account to complete device setup on first use.

 However, this may not be feasible due to many reasons. First, you may want to use a local user account, but connecting to the Internet will force you to log in with a Microsoft account. The second potential issue is the [missing WiFi drivers to connect to the network](https://www.makeuseof.com/windows-11-missing-wi-fi-option/). Finally, the unavailability of a working Internet connection is another reason you may want to bypass this restriction.

 In Windows 10, bypassing this restriction was easy. You could click on the "I don't have internet" option and proceed to create a local user account and complete the setup.

 Windows 11, however, stops at the "Let’s connect you to a network" screen with the "Next" button grayed out. Windows 11 Pro, Enterprise and Education users can click on "I don’t have internet" and proceed to complete the setup with a local user account; however, Home edition users don't have this option.

 Here are a few workarounds to install Windows 11 Home without an active Internet connection.

## 1\. Bypass Out-of-the-Box-Experience (OOBE) Internet Requirement

 You can bypass the Let’s connect you to a network screen using the OOBE \\BYPASSNRO command in Command Prompt.

 When executed, it runs an existing CMD script, bypassnro.cmd, stored in the System32 folder to modify the Windows registry. This modification allows you to complete the Windows 11 setup without an Internet connection.

 To complete the Windows 11 setup without internet:

1. Make sure your computer is not connected to the Internet.
2. Next, boot your computer with the Windows installation media. Skip to **Step 9** below if you are already on the **Let's connect you to a network** screen.
3. When the **Windows Setup** dialog appears, select your preferred language, time, and keyboard input layout and click **Next**.  
![Windows-11-setup-screen-install-now](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-11-setup-screen-install-now.jpg)
4. Click **Install Now.**  
![Windows 11 setup i dont have product key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-11-setup-i-dont-have-product-key.jpg)
5. Enter your product key. If you don't have a product key, click the **I don't have a product key** link in the bottom right corner. If you are upgrading from Windows 10 and had Windows 11 previously installed, the operating system will automatically recognize and validate the Windows product key linked to your computer hardware.

1. Next, if prompted, select the edition of Windows 11 you want to install.
2. Check the box to accept terms and click **Next**.
3. Select **Custom: Install Windows Only (Advanced).**  
![Windows 11 setup select installation drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-11-setup-select-installation-drive.jpg)
4. Select the installation drive and click **Next**. Wait for Windows to finish installation and restart your computer.
5. In the setup screen, select your region and keyboard layout.

1. Once in the **Let’s connect you to a network** screen, press **Shift + F10** to launch the **Command Prompt.**  
![oobe bypass nro command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/oobe-bypass-nro-command-prompt.jpg)
2. In the Command Prompt window, type the following command and press **Enter**:  
`OOBE\BYPASSNRO`
3. Upon successful execution, your system will restart and relaunch the OOBE dialog.  
![Windows-11-setup-select-installation-i-don't-have-internet-connection](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-11-setup-select-installation-i-don-t-have-internet-connection.jpg)
4. Follow the on-screen instructions to complete the setup. When you reach the **Let’s connect you to a network screen**, click on **I don’t have Internet** option.
5. Next, click on **Continue with limited setup.**  
![Windows 11 setup select installation continue with limited setup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-11-setup-select-installation-continue-with-limited-setup.jpg)
6. Accept the **License Agreement** and proceed to create your local user account.

 Make sure to add security questions. This will help you recover your local user account in case you forget your password. Once done, follow the on-screen instructions to complete the setup.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35408920&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/FR-200-1.png" border="0">Glarysoft File Recovery Pro - Helps to recover your lost file/data, even permanently deleted data. </a>
<!-- affiliate ads end -->
## 2\. End Network Connection Flow Process Using Task Manager

 You can bypass the "let’s connect you to a network" screen by killing the **oobenetworkconnectionflow.exe** process using the Windows Task Manager.

 Since you already have Windows 11 installed at this stage, you can [launch the Task Manager](https://www.makeuseof.com/how-to-access-task-manager-on-windows-11/) on top of your setup wizard using Command Prompt and kill the process.

 To skip the Windows 11 network setup using Task Manager:

1. Assuming you are in the **Let’s connect you to a network screen**, press **Shift + F10** to launch the Command Prompt.
2. In the Command Prompt window, type **taskmgr** and hit enter to launch **Task Manager.**  
![open task manager command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/open-task-manager-command-prompt.png)
3. Alternatively, use the **Ctrl + Shift + Esc** shortcut to launch Task Manager without Command Prompt.
<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Click **More Details** to open Task Manager in full view.
5. In the **Processes** tab, locate **Network Connection Flow.** Use the search bar in Task Manager to find the Network Connection Flow process.  
![Windows 11 setup select installation task manager kill network connection flow](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-11-setup-select-installation-task-manager-kill-network-connection-flow.jpg)
6. Select the **Network Connection Flow** process and then click the **End task** button. Wait for the process to end and then close the Task Manager.
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
7. Type **exit** in the Command Prompt and hit enter.

 Now you will be back in the setup wizard. It will show some loading animation and then proceed to the next step. Here enter your name and password to [create a local user account in Windows 11](http://www.makeuseof.com/ways-to-create-local-user-account-windows/) and complete the setup.

## 3\. Directly Kill Network Connection Flow Using the Command Prompt

![end network connection flow command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/end-network-connection-flow-command-prompt.png)

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
 If you are unable to end the Network Connect Flow through Task Manager, you can directly kill it using the Command Prompt. Here’s how to do it.

1. At the Let’s connect you to a network screen, press **Shift + F10** to launch Command Prompt.
2. In the Command prompt window, type the following command and hit enter to execute:  
`taskkill /F /IM oobenetworkconnectionflow.exe`
3. Once executed, close the Command Prompt window to continue with the setup.

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Skip Let’s Connect You to a Network Page with Alt + F4

 This workaround is more of a hit-or-miss but seems to have helped a few users. When at the **Let's connect you to a network screen**, pressthe **Alt + F4** keyboard shortcut to close the mandatory Internet connection required window. Incidentally, you can use this shortcut to close active windows/programs when working on your desktop as well.

 For more such handy shortcuts, explore our [ultimate guide to Windows 11 keyboard shortcuts](https://www.makeuseof.com/windows-11-keyboard-shortcuts/).

 If successful, Windows 11 will skip the current screen and move to the next step. Once you're past this step, you can create a local user account and then complete the setup.

<!-- affiliate ads begin -->
<iframe id="iframe_672" src="//a.impactradius-go.com/gen-ad-code/5597632/1959812/17834/" width="720" height="300" scrolling="no" frameborder="0" marginheight="0" marginwidth="0"></iframe>
<!-- affiliate ads end -->
## Completing the Windows 11 Setup Without Internet Access

 You can follow one of the four methods listed above to skip the let’s connect you to a network window and complete the Windows 11 setup without the internet.

 That said, once you finish the setup and create a local user account, connect to the Internet to download critical security updates and features. You may also notice a few missing icons after the initial setup. Windows will download these icons when you connect to the Internet next time.

 This becomes an issue if you want to use a local user account or don’t have an active internet connection during setup. Luckily, there are a few workarounds to skip the Windows 11 network setup. Here we show you how to bypass this restriction and complete the Windows 11 setup without an internet connection.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-dissecting-popularity-ten-facts-about-reels-unmasked/"><u>[New] In 2024, Dissecting Popularity  Ten Facts About Reels, Unmasked</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-unveiling-the-techniques-of-premium-vr-gametime-captures/"><u>[New] In 2024, Unveiling the Techniques of Premium VR Gametime Captures</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-online-meme-maker/"><u>[New] Online MEME Maker</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-syncing-twitter-to-snapchat-video-uploading-techniques/"><u>[New] Syncing Twitter to Snapchat  Video Uploading Techniques</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-the-ultimate-overview-dji-inspire-1-reviewed/"><u>[New] The Ultimate Overview  DJI Inspire 1 Reviewed</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-top-10-games-like-gta-v/"><u>[Updated] In 2024, Top 10 Games Like GTA V</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-prime-channel-themes-igniting-viewer-motivation/"><u>[Updated] Prime Channel Themes  Igniting Viewer Motivation</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-quickly-locating-your-curated-music-compilation-on-youtube/"><u>[Updated] Quickly Locating Your Curated Music Compilation on Youtube</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/approved-curating-creator-rewards-on-video-platforms/"><u>2024 Approved  Curating Creator Rewards on Video Platforms</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-step-by-step-process-to-preserve-instagrams-ephemeral-content/"><u>2024 Approved  Step-by-Step Process to Preserve Instagram's Ephemeral Content</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-the-best-5-programs-for-snagging-facebook-feeds/"><u>2024 Approved  The Best 5 Programs for Snagging Facebook Feeds</u></a></li>
<li><a href="https://howto.techidaily.com/9-quick-fixes-to-unfortunately-touchwiz-has-stopped-of-vivo-y100-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Quick Fixes to Unfortunately TouchWiz has stopped Of Vivo Y100 5G | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-honor-x9a-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Honor X9a Hard Reset | Dr.fone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/direct-directions-simple-techniques-for-laptop-screening-dell/"><u>Direct Directions  Simple Techniques for Laptop Screening (Dell)</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/essential-tips-for-crafting-youtube-image-marketing/"><u>Essential Tips for Crafting YouTube Image Marketing</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-guide-to-streamline-program-access-via-context-menu/"><u>Expert Guide to Streamline Program Access via Context Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-nullify-windows-aural-overdrive/"><u>How To Nullify Windows Aural Overdrive</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-your-samsung-galaxy-s24-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Your Samsung Galaxy S24 Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-quicktime-magic-precise-timelapse-shots-with-samsung/"><u>In 2024, Quicktime Magic  Precise Timelapse Shots with Samsung</u></a></li>
<li><a href="https://windows11.techidaily.com/legacys-latest-look-instructions-for-windows-11-using-to-go-and-rufus-technology/"><u>Legacy's Latest Look: Instructions for Windows 11, Using To Go & Rufus Technology</u></a></li>
<li><a href="https://windows11.techidaily.com/making-windows-easier-personalized-text-transcription-using-ahk-and-whisper/"><u>Making Windows Easier: Personalized Text Transcription Using AHK & Whisper</u></a></li>
<li><a href="https://windows11.techidaily.com/microsoft-and-native-accounts-key-differences-unpacked-in-os-windows/"><u>Microsoft & Native Accounts: Key Differences Unpacked in OS Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-unyielding-mode-switches-on-win11/"><u>Overcoming Unyielding Mode Switches on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-operation-failure-x709/"><u>Overcoming Windows Operation Failure X709</u></a></li>
<li><a href="https://windows11.techidaily.com/pinpointing-your-internet-ip-using-terminal-commands/"><u>Pinpointing Your Internet IP Using Terminal Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/pioneering-the-future-running-windows-11-on-legacy-pcs-through-to-go-and-rufus/"><u>Pioneering the Future: Running Windows 11 on Legacy PCs Through To Go & Rufus</u></a></li>
<li><a href="https://vp-tips.techidaily.com/plain-story-formulation/"><u>Plain Story Formulation</u></a></li>
<li><a href="https://windows11.techidaily.com/privacy-control-remove-your-email-in-login-screen/"><u>Privacy Control: Remove Your Email in Login Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-preventing-windows-dwarf-fortress-crashes/"><u>Quick Guide: Preventing Windows-Dwarf Fortress Crashes</u></a></li>
<li><a href="https://fix-guide.techidaily.com/realme-v30t-stuck-on-screen-finding-solutions-for-stuck-on-boot-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Realme V30T Stuck on Screen – Finding Solutions For Stuck on Boot | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaim-missing-flight-copilot-on-new-os-ws11/"><u>Reclaim Missing Flight Copilot on New OS WS11</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-disconnected-messages-in-windows-discord/"><u>Rectifying Disconnected Messages in Windows Discord</u></a></li>
<li><a href="https://windows11.techidaily.com/resolve-your-black-screen-woes-with-simple-tricks-for-win11/"><u>Resolve Your Black Screen Woes with Simple Tricks for Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/reversing-roblox-errors-on-microsoft-os/"><u>Reversing Roblox Errors on Microsoft OS</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-code-0xc0000142-on-windows-xp-1011/"><u>Solving Code 0XC0000142 on Windows XP, 10/11</u></a></li>
<li><a href="https://article-files.techidaily.com/strategies-to-avoid-overuse-of-b-roll-in-cinematography-for-2024/"><u>Strategies to Avoid Overuse of B-Roll in Cinematography for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/tech-tricks-blend-taskbar-language-feature-win11-style/"><u>Tech Tricks: Blend Taskbar Language Feature, Win11 Style</u></a></li>
<li><a href="https://windows11.techidaily.com/the-quintessence-of-productivity-win-11s-top-7-widgets/"><u>The Quintessence of Productivity: Win 11’S Top 7 Widgets</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-and-techniques-for-windows-11-diagnostic-rehabilitation/"><u>Tips and Techniques for Windows 11 Diagnostic Rehabilitation</u></a></li>
<li><a href="https://techidaily.com/today-i-configure-mt4-and-mt5-accounts-for-running-a-local-trade-copier-tm-together-with-any-other-forex-ea-by-mt4copier-guide/"><u>Today I Configure MT4 and MT5 Accounts for Running a Local Trade Copier™ Together With Any Other Forex EA</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-unavailable-roblox-due-to-user-configs-on-windows/"><u>Troubleshooting Unavailable Roblox Due to User Configs on WINDOWS</u></a></li>
<li><a href="https://windows11.techidaily.com/tutorial-empowering-end-task-capability-on-windows-11/"><u>Tutorial: Empowering End Task Capability on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unfolding-windows-solutions-for-stubborn-folders-on-double-click/"><u>Unfolding Windows: Solutions for Stubborn Folders on Double-Click</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-file-past-mastering-windows-11s-history-access/"><u>Unlocking File Past: Mastering Windows 11'S History Access</u></a></li>
<li><a href="https://driver-install.techidaily.com/1720062905625-update-g580-drivers-in-a-blink/"><u>Update G580 Drivers in a Blink!</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-over-common-mmc-snapshot-glitches/"><u>Winning Over Common MMC Snapshot Glitches</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>