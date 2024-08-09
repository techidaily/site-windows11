---
title: Exiting Others' User Sessions on Win 11
date: 2024-08-08T06:08:52.209Z
updated: 2024-08-09T06:08:52.209Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Exiting Others' User Sessions on Win 11
excerpt: This Article Describes Exiting Others' User Sessions on Win 11
keywords: Session Exit Win11,Win11 Unauthorized Logoff,End Users Win11 Sessions,Control Session Win11 Access,Prevent Others' Login Win11,Secure Windows 11 User Exit,Manage User Lockout Win11
thumbnail: https://thmb.techidaily.com/f14703ab2e75a5e3ef7cee5c0a7ee5ddd2895b6cfd7b5126052dee0bd06c1845.jpg
---

## Exiting Others' User Sessions on Win 11

### Quick Links

* [Sign Out Other Users Using the Task Manager](#sign-out-other-users-using-the-task-manager)
* [Sign Out Other Users Using the Command Prompt](#sign-out-other-users-using-the-command-prompt)
* [Log Off Other Users Using Process Explorer](#log-off-other-users-using-process-explorer)
* [Ask Other Users Before You Sign Them Out](#ask-other-users-before-you-sign-them-out)

### Key Takeaways

* To sign out other users on Windows 11, you can use Task Manager, Command Prompt, or Process Explorer.
* The Task Manager method works on any version of Windows, while the Command Prompt option only works for Pro and above versions of Windows. Process Explorer requires a separate download.
* Be sure to consider any unsaved work before logging off a user.

 Each active user session on your PC means your computer's resources are shared with others, which can impact system performance. If someone is not actively using their session, you can log off the idle user from your account to reclaim those system resources.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
## 1\. Sign Out Other Users Using the Task Manager

 The Task Manager's **Users** tab keeps track of all the user sessions active on your computer. You can use it to manage user accounts on Windows, switch between different user accounts, and sign off other user accounts. If you only need to [sign out of your current session on Windows 11](https://www.makeuseof.com/windows-11-how-to-sign-out/), the process is much simpler, though.

 You must be logged in as an administrator to sign off other user accounts; [check if your user account has administrator rights](https://www.makeuseof.com/check-windows-account-admin-rights/) if you're not sure. Importantly, when you sign out a user, the user's unsaved data might be lost. So tread carefully.

 To sign out other users using Task Manager:

1. Right-click on **Start** and select **Task Manager**. Alternatively, use the keyboard shortcut **Ctrl + Shift + Esc**.
2. In Task Manager, open the **Users** tab in the left pane which displays the number of users currently logged in. If not visible, click the **Open Navigation** button (three horizontal bars) in the top left corner.  
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->
![Winx Menu Task Manager Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/winx-menu-task-manager-windows-11.png)
3. In the **Users** tab, locate the account you want to sign off.
4. Right-click on the user account and select **Sign off**.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
![Users Tab in Task Manager with Logoff Option in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/users-tab-in-task-manager-with-logoff-option-in-windows-11.jpg)
5. Click **Sign out user**. Windows will close all the open apps and running processes and then log out the user.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. Sign Out Other Users Using the Command Prompt

 On Windows 11 Pro, Edu, and Enterprise editions, you can use Command Prompt's "query sessions" command to check and log off active user accounts. This command is unlikely to work on a Windows 11 Home, limiting your options.

 To sign out other users using Command Prompt:

1. Press the **Win** key and type **cmd**.
2. Right-click on **Command Prompt** and select **Run as administrator**.
3. In the Command Prompt window, type the following command to view all the active user sessions with a query:  
`query session`
4. The output will show all the active user sessions on your computer. Make a note of the user account **ID** you want to sign out. In this instance, we have **Tashreef** as **1** and **Guest21** as **3** under the **ID** column.  
![Command Prompt With Query Session Command Running on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/command-prompt-with-query-session-command-running-on-windows-11.jpeg)
5. Type the following command to sign out the specified user. Replace **2** below with the user account ID you want to sign out:  
`Logoff 3`
6. Upon successful execution, Windows will sign out the specified user account.  
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698998&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/MacBook_Pro_lyrx-withsinger-tv.png" border="0">LYRX is an easy-to-use karaoke software with the professional features karaoke hosts need to perform with precision. LYRX is karaoke show hosting software that supports all standard karaoke file types as well as HD video formats, and it’s truly fun to use. 
LYRX Karaoke Software MAC/WINDOWS (Includes Activation For 3 Machines)</a>
<!-- affiliate ads end -->
![Command Prompt With Logoff Command Running on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/command-prompt-with-logoff-command-running-on-windows-11.jpg)
7. Once done, type **exit** and press Enter to close the Command Prompt.

## 3\. Log Off Other Users Using Process Explorer

 Process Explorer is part of [Windows Sysinternal Tools, a suite of system administration utilities](http://www.makeuseof.com/windows-sysinternals-guide/) from Microsoft. Though the freeware is popular among developers and system admins, anyone can use Process Explorer to use some of its advanced features.

 Process Explorer is a powerful tool that maps all currently active processes and DLL files to the accounts running them. Our purpose is to show you how to use its user management feature to kick out other user sessions.

1. Go to Microsoft's official [Process Explorer page](https://learn.microsoft.com/en-us/sysinternals/downloads/process-explorer) and download Process Exploreras a zip file to a location on your desktop.  
![Download Process Explorer Web Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/download-process-explorer-web-page.jpg)
2. Right-click on the **ProcessExplorer.zip** archive, and select **Extract All**. Select a location and extract the folder.  
![Process Explorer Exe File Run as Administrator Option in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-exe-file-run-as-administrator-option-in-windows-11.jpg)
3. Open the **ProcessExplorer** folder, right-click on **procexp64.exe**, and select **Run as administrator**.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
![Process Explorer App User Option Selected in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-app-user-option-selected-in-windows-11.jpg)
4. In the **Process Explorer** window, click **Users** to view all the active user sessions.  
![Process Explorer App User Account Logoff Option Selected in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-app-user-account-logoff-option-selected-in-windows-11.jpg)
5. Hover your cursor over the user account name and select **Logoff**.

 Process Explorer will sign out the selected user account from your computer. If you get an [access denied error](https://www.makeuseof.com/windows-11-fix-access-denied-error/), run the procexp64.exe executable with administrator privileges and try again.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
## Ask Other Users Before You Sign Them Out

 When you log off other users, any unsaved work in their accounts is lost. So do consider that before you apply the above methods. Logging off from a Windows account in a multi-user PC is a good habit because it reduces the chance of data loss and frees up the computer's resources for others. Always request others to sign off when their work is finished.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-extracting-image-files-from-youtube-browser-based-os-techniques/"><u>[New] 2024 Approved  Extracting Image Files From Youtube  Browser-Based, OS Techniques</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-transform-your-work-from-home-experience-with-skype-screen-sharing-techniques/"><u>[New] 2024 Approved  Transform Your Work-From-Home Experience with Skype Screen Sharing Techniques</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-free-tools-make-screencapture-a-breeze-for-tv-lovers/"><u>[New] Free Tools Make ScreenCapture a Breeze for TV Lovers</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-insiders-guide-to-instagrams-music-licensing-policies/"><u>[New] The Insider’s Guide to Instagram's Music Licensing Policies</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-the-ultimate-social-surge-amass-1k-on-ig-each-month-for-a-million-dream-for-2024/"><u>[New] The Ultimate Social Surge  Amass 1K on IG Each Month for a Million Dream for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-harness-speed-in-collage-making-for-facebook-shares/"><u>[Updated] Harness Speed in Collage Making for Facebook Shares</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-win-11-guide-to-storing-mov-files-effectively/"><u>[Updated] In 2024, Win 11 Guide to Storing .mov Files Effectively</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-viewpoint-visionaries-capturing-the-essence-with-3-viewpoint-strategies-in-reactions/"><u>[Updated] Viewpoint Visionaries  Capturing the Essence with 3 Viewpoint Strategies in Reactions</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-overcoming-unnatural-motion-blur-in-uav-videos/"><u>2024 Approved  Overcoming Unnatural Motion Blur in UAV Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/a-stepwise-guide-to-banishing-the-onedrive-icon-from-explorer/"><u>A Stepwise Guide to Banishing the OneDrive Icon From Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/banishing-0x800704b3-error-from-your-win1011-system/"><u>Banishing 0X800704B3 Error From Your Win10/11 System</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-back-color-to-extend-volume-option-in-diskmgmt/"><u>Bring Back Color to Extend Volume Option in DiskMgmt</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-to-managing-comic-files-in-windows-11/"><u>Comprehensive Guide to Managing Comic Files in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-the-hidden-potential-in-windows-powertoys-10-applications/"><u>Discover the Hidden Potential in Windows PowerToys' 10 Applications</u></a></li>
<li><a href="https://location-social.techidaily.com/does-find-my-friends-work-on-poco-x6-pro-drfone-by-drfone-virtual-android/"><u>Does find my friends work on Poco X6 Pro | Dr.fone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/easily-capturing-iphone-screens-on-the-go-for-2024/"><u>Easily Capturing iPhone Screens on the Go for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-combatting-windows-not-found-problem/"><u>Essential Tips: Combatting Windows Not Found Problem</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-how-to-activate-intel-wireless-functionality/"><u>Essential Tips: How to Activate Intel Wireless Functionality</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-cast-apple-iphone-se-2020-to-chromecast-drfone-by-drfone-ios/"><u>How to Cast Apple iPhone SE (2020) to Chromecast? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-endure-no-more-teams-login-troubles-in-windows/"><u>How to Endure No More Teams Login Troubles in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-make-win11s-canvas-come-alive-the-guide-to-creating-intriguing-ai-images-via-paint-tool-sai/"><u>How to Make Win11's Canvas Come Alive: The Guide to Creating Intriguing AI Images via Paint Tool SAI</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-additional-tips-about-sinnoh-stone-for-tecno-spark-20-proplus-drfone-by-drfone-virtual-android/"><u>In 2024, Additional Tips About Sinnoh Stone For Tecno Spark 20 Pro+ | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-did-your-apple-iphone-11-passcode-change-itself-unlock-it-now-drfone-by-drfone-ios/"><u>In 2024, Did Your Apple iPhone 11 Passcode Change Itself? Unlock It Now | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-network-locked-sim-card-inserted-on-your-samsung-galaxy-z-fold-5-phone-unlock-it-now-by-drfone-android/"><u>In 2024, Network Locked SIM Card Inserted On Your Samsung Galaxy Z Fold 5 Phone? Unlock It Now</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unheard-voices-on-youtube-livestream-success-beyond-1000-supporters/"><u>In 2024, Unheard Voices on YouTube  Livestream Success Beyond 1000 Supporters</u></a></li>
<li><a href="https://hardware-help.techidaily.com/lenovo-usb-drivers-effortless-solutions-to-common-issues-and-errors/"><u>Lenovo USB Drivers: Effortless Solutions to Common Issues and Errors</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ring-the-art-of-audio-capture-sans-microphone/"><u>Mastering the Art of Audio Capture Sans Microphone</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-productivity-with-windows-11-calendar/"><u>Maximizing Productivity with Windows 11 Calendar</u></a></li>
<li><a href="https://windows11.techidaily.com/microsofts-helpers-quick-fixes-for-window-woes/"><u>Microsoft's Helpers: Quick Fixes for Window Woes!</u></a></li>
<li><a href="https://windows11.techidaily.com/n-series-window-enigma-deciding-factors/"><u>N-Series Window Enigma: Deciding Factors</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-bt-speakers-volume-level-on-windows-11-pcs/"><u>Optimizing BT Speakers Volume Level on Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-system-limit-fixing-gpt-windows-problems/"><u>Overcoming System Limit: Fixing GPT Windows Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/personalize-your-desktop-space-win-os-snap-configurations/"><u>Personalize Your Desktop Space: Win OS Snap Configurations</u></a></li>
<li><a href="https://windows11.techidaily.com/pursue-peak-performance-customizing-graphics-settings-for-games/"><u>Pursue Peak Performance: Customizing Graphics Settings for Games</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-error-code-0xc00000f-quickly/"><u>Resolving Windows Error Code 0Xc00000f Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-vibrance-to-dull-desktop-windows-effects/"><u>Restoring Vibrance to Dull Desktop Windows Effects</u></a></li>
<li><a href="https://windows11.techidaily.com/rise-above-ethernet-ceiling-overcome-the-windows-100mbps-limit/"><u>Rise Above Ethernet Ceiling: Overcome the Windows 100Mbps Limit</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-synthesis-how-meditation-transforms-cognition-and-emotion/"><u>Seamless Synthesis: How Meditation Transforms Cognition & Emotion</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-into-a-single-source-for-phone-calls-with-unison-w11/"><u>Simplifying Into a Single Source for Phone Calls with Unison W11</u></a></li>
<li><a href="https://windows11.techidaily.com/solve-no-errors-on-win11-quick-fix-guide/"><u>Solve No Errors on Win11 - Quick Fix Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-0x80072efd-in-win1110s-microsoft-store/"><u>Solving 0X80072EFD in Win11/10's Microsoft Store</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-amend-non-interactive-menu-bar-on-windows-11/"><u>Steps to Amend Non-Interactive Menu Bar on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-code-4-error-a-compre-cookie-guide/"><u>Tackling the Code 4 Error: A Compre Cookie Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-windows-cars-keyboard-magic-boosts-speed/"><u>Top 5 Windows Cars: Keyboard Magic Boosts Speed</u></a></li>
<li><a href="https://windows11.techidaily.com/transformingnotepadlighttodarkwin/"><u>TransformingNotepadLightToDarkWin</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-power-of-search-implementing-it-in-win11s-task-monitor/"><u>Unlock the Power of Search: Implementing It in Win11's Task Monitor</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>