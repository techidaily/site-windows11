---
title: Changing Default User Directory Labels (Windows 11)
date: 2024-08-15T15:15:53.271Z
updated: 2024-08-16T15:15:53.271Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Changing Default User Directory Labels (Windows 11)
excerpt: This Article Describes Changing Default User Directory Labels (Windows 11)
keywords: Win11 UserDir Change,Windows 11 Directory Update,Label Edit Windows 11,Redefine Win11 Labels,Changing User Label Windows,Renaming User Folder Windows 11,Update Default Windows Paths
thumbnail: https://thmb.techidaily.com/be8413a30f19599698e9b5b7f7e17b9eb5081fbfdcc13de42954a869c3e7944e.png
---

## Changing Default User Directory Labels (Windows 11)

### Key Takeaways

* Windows 11 creates a default user profile folder based on the first five characters of your account name, but you can change it using a registry hack.
* Changing the user profile folder name can cause issues with some Microsoft Store apps, but signing out and signing back in may fix the problem.
* To change the user profile folder name, create a new administrator account, modify the registry entries associated with your user account, and then rename the user profile folder in File Explorer.

 When you create a new user account in Windows 11, the operating system automatically creates a new user profile folder in C:\\Users\\Username. However, this default user profile folder name is not always what you want.

 Windows, by default, will use the first five characters of your user account name as the profile folder name. If you don’t like the user profile folder name, you can change it using a registry hack. Here, we show you how to change the name of the user profile folder in Windows 11\.

## But First, Some Potential Issues That May Arise From These Steps

 While the registry hack should help you successfully change your user account folder name, it can lead to some complications. For example, some of your Microsoft Store apps, including OneDrive and Outlook, can stop working.

 Try to sign out and sign in to your app as a quick fix. If that does not work, you’ll need to move the existing path and define the new correct path after changing the user folder name.

 Also, [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and exercise extreme caution while changing your user name folder. Incorrect modification to the Windows Registry can cause serious issues and may require reinstallation of the operating system.

## How to Create a New Administrator User Account in Windows 11

 To change your current user profile name, log into a different administrator account. You cannot modify an existing user account profile path from the same account.

 To do this, you can [enable and use the built-in administrator account in Windows 11](https://www.makeuseof.com/windows-11-enable-disable-built-in-administrator-account/). If not, follow these steps to create a new administrator account in Windows 11\.

 To create a new administrator account:

1. Press **Win + I** to open **Settings**.
2. Open the **Accounts** tab in the left pane.
3. Click on **Family & other users** in the right pane.  
![Windows 11 add user account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/Windows-11-add-user-account.png)
4. Click **Other users.** This option is useful to create a local user account without a Microsoft Account.  
![Add other user account in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/add-other-user-account-windows-11.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
5. Next, click on **I don’t have this person’s sign-in information.**  
![Creating a local user account without a Microsoft account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/create-local-user-account-without-Microsoft-account.png)
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. Click on **Add a user** **without a Microsoft account.**
2. Type a name for the user account. Leave the password field empty and click **Next**.
3. Click on the new user account and click **Change account type.**
4. Click the drop-down for **Account type** and select **Administrator**.
5. Click **OK** to save the changes.

 Now, you can log in with your new administrator account. To do this, click **Start**, then click on the user profile name, and select **Sign out.** Next, sign in with the new administrator account.

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Change the User Profile Folder Name Using the Registry Editor

 You can modify the registry entries associated with your user account to change the user profile folder name in Windows 11\.

 This process involves modifying your registry entries, so we recommend you create a restore point. You can [use the restore point to restore your PC](https://www.makeuseof.com/use-system-restore-windows/) if something goes wrong during the process.

 To change the user profile folder name:

1. Sign out from your current user account and log in with a built-in or newly created administrator account
2. Next, press **Win + R** to open the **Run** dialog.
3. Type **netplwiz** and click **OK** to open the **User Accounts** dialog.
4. Here, select your **user account** and click on **Properties**.  
![User accounts properties.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/user-accounts-properties.jpg)
5. In the **User Properties** dialog, you’ll see your **User name** and **Full name.**

1. Type a name for your user name, click **OK** and **Apply**.  
![user account user name](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/user-acount-user-name.jpg)
2. Close the **User Account** dialog and perform a restart.
3. Next, open the Command Prompt. To do this, press **Win + R,** type **cmd,** and click **OK**.  
![SID command prompt user account.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/SID-command-prompt-user-account.png)
4. In the Command Prompt window, type the following command to view **SID (Security Identifier)** for all user accounts:  
`wmic useraccount get name,SID`
5. Here, note the **SID** for the user account you want to change the user profile folder name. In this case, the **SID** for the username **tashr** is **S-1-5-21-200486166-247335145-1769094253-1001.**

 Now that we have the SID, we must enter it into the Registry Editor. To do that, follow these steps:

1. Press **Win + R**, type **regedit,** and click **OK** to open **Registry Editor.**
2. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\ProfileList`
3. Inside the **ProfileList** key, locate and click on the key name identical to the **SID** you noted earlier.
4. In the right pane, right-click on **ProfileImagePath** value and select **Modify**.  
![Modify profile image path in the registry editor.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/modify-profile-image-path-registry-editor.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
5. Enter a name you want for the profile folder and click **OK**.  
![add new name profile image path registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/add-new-name-profile-image-path-registry-editor.png)
6. Close the Registry Editor and Command Prompt window if open.
7. Next, press **Win + E** to open File Explorer and navigate to **C:\\Users\\.**  
![Rename user profile folder name.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/rename-user-profile-folder-name.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
8. Select your **user profile** and press **F2** to rename it. Enter a new name for your user profile (it must match the user name entered in the Registry Editor).
9. Click away and then click **Continue** to save the changes.

 You may sometimes encounter the "You can’t perform this action" error when renaming the folder. This error often occurs if you switch to a different administrator account without signing out from the primary user account. Alternatively, restart your PC and repeat the steps to rename the user profile folder without the error.

 Next, log out from your current account and sign in to the user account with the new user folder name. Open File Explorer and navigate to **C:\\Users\\**, and you should be able to use the previous profile with the new pathname.

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
## Renaming the Default User Profile Folder in Windows 11, Made Easy

 While you can rename the user account in Windows 11 using the Control Panel, doing so will not change the user profile folder name. You need to modify the ProfileImagePath value in the Registry Editor with a different administrator account. Once done, you can remove the new administrator user account to declutter your login screen.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-guidance.techidaily.com/new-online-gallery-guide-sites-and-plugins-for-superb-photoframes/"><u>[New] Online Gallery Guide  Sites & Plugins for Superb Photoframes</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-video-dominance-on-instagram-designing-a-pro-marketing-approach/"><u>[New] Video Dominance on Instagram  Designing a Pro-Marketing Approach</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/2023how-to-share-videos-on-twitter-on-your-phone-without-retweeting-for-2024/"><u>2023|How to Share Videos on Twitter on Your Phone Without Retweeting for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/5-ways-to-close-multiple-apps-simultaneously-on-windows/"><u>5 Ways to Close Multiple Apps Simultaneously on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/6-expert-windows-programs-for-video-editors/"><u>6 Expert Windows Programs for Video Editors</u></a></li>
<li><a href="https://windows11.techidaily.com/6-underestimated-downsides-of-saving-on-activation-keys/"><u>6 Underestimated Downsides of Saving on Activation Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/a-compreenasian-approach-to-fixing-winget-on-windows-11/"><u>A Compreenasian Approach to Fixing Winget on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerate-your-typing-on-win-1011-top-7-tricks-revealed/"><u>Accelerate Your Typing on WIN 10/11: Top 7 Tricks Revealed</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerating-edge-browsing-performance-on-win10win11/"><u>Accelerating Edge Browsing Performance on Win10/Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-one-side-output-in-windows-10-headphones/"><u>Addressing One Side Output in Windows 10 Headphones</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-windows-settings-for-visible-sticky-notes/"><u>Adjusting Windows Settings for Visible Sticky Notes</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-techniques-locating-ip-and-mac-in-windows-ps/"><u>Advanced Techniques: Locating IP & MAC in Windows PS</u></a></li>
<li><a href="https://buynow-info.techidaily.com/amazon-luna-gaming-experience-evaluation-exceptional-smoothness-in-cloud-based-play/"><u>Amazon Luna Gaming Experience Evaluation: Exceptional Smoothness in Cloud-Based Play</u></a></li>
<li><a href="https://windows11.techidaily.com/audible-improvements-for-windows-users-stepwise-audio-driver-revamp/"><u>Audible Improvements for Windows Users: Stepwise Audio Driver Revamp</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-panic-recover-lost-data-with-these-steps/"><u>Avoid Panic, Recover Lost Data with These Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-blue-screen-blues-fixing-error-740-on-winos/"><u>Avoiding Blue Screen Blues: Fixing Error 740 on WINOS</u></a></li>
<li><a href="https://windows11.techidaily.com/beating-steam-disk-write-failures-on-windows-pc/"><u>Beating Steam Disk Write Failures on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/becoming-an-admin-in-pc-command-console/"><u>Becoming an Admin in PC Command Console</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-windows-vram-a-step-by-step-guide/"><u>Boosting Windows VRAM: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-11-mode-switch-failures/"><u>Bypassing Windows 11 Mode Switch Failures</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-update-four-techniques/"><u>Bypassing Windows Update: Four Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/captivating-holiday-vistas-through-designed-panes/"><u>Captivating Holiday Vistas Through Designed Panes</u></a></li>
<li><a href="https://windows11.techidaily.com/character-inspector-easy-steps-for-windows-11/"><u>Character Inspector: Easy Steps for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/chkdsk-sfc-and-dism-windows-tools-unveiled-and-explained/"><u>CHKDSK, SFC & DISM: Windows Tools Unveiled and Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/christmas-theme-makeovers-for-windows-11/"><u>Christmas Theme Makeovers for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-storage-alerts-and-errors-on-windows/"><u>Clearing Up Storage Alerts & Errors on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/compulsory-uninstall-guide-for-windows-11-printers/"><u>Compulsory Uninstall Guide for Windows 11 Printers</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-account-lockout-reset-in-successive-login-attempts-windows-1011/"><u>Configuring Account Lockout Reset in Successive Login Attempts Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/confronting-and-overcoming-failed-capture-issues-in-windows/"><u>Confronting and Overcoming Failed Capture Issues in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-the-unseen-scroll-phenomenon-in-windows/"><u>Conquer the Unseen Scroll Phenomenon in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-win11s-startup-configuration-for-unmatched-performance/"><u>Conquer Win11's Startup Configuration for Unmatched Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/constructing-a-contextual-update-prompt-mechanism/"><u>Constructing a Contextual Update Prompt Mechanism</u></a></li>
<li><a href="https://windows11.techidaily.com/cursor-on-display-redeeming-darkened-win1011-screens/"><u>Cursor on Display: Redeeming Darkened Win10/11 Screens</u></a></li>
<li><a href="https://windows11.techidaily.com/cut-through-the-frustration-swift-solutions-for-ms-teams-error-80080300-in-win11/"><u>Cut Through the Frustration: Swift Solutions for MS Teams Error 80080300 in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-windows-11-editions-matching-home-to-pro-features/"><u>Decoding Windows 11 Editions: Matching Home to Pro Features</u></a></li>
<li><a href="https://windows11.techidaily.com/decreasing-cpu-load-in-setup-hosts/"><u>Decreasing CPU Load in Setup Hosts</u></a></li>
<li><a href="https://windows11.techidaily.com/delving-into-the-spiritual-command-center-of-windows-11/"><u>Delving Into the Spiritual Command Center of Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/desktop-dynamics-shift-unveiling-the-latest-os-features/"><u>Desktop Dynamics Shift: Unveiling the Latest OS Features</u></a></li>
<li><a href="https://windows11.techidaily.com/detecting-correct-credentials-vs-error-logins-on-your-winpc/"><u>Detecting Correct Credentials vs Error Logins on Your WinPC</u></a></li>
<li><a href="https://windows11.techidaily.com/disable-auto-updates-in-windows-and-office-instantly/"><u>Disable Auto-Updates in Windows & Office Instantly</u></a></li>
<li><a href="https://windows11.techidaily.com/dive-into-windows-powertoys-the-ultimate-guide-to-its-best-uses/"><u>Dive Into Windows PowerToys: The Ultimate Guide to Its Best Uses</u></a></li>
<li><a href="https://windows11.techidaily.com/diving-into-windows-n-types-benefits-and-downfalls/"><u>Diving Into Windows N Types: Benefits and Downfalls</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/elevating-posts-how-to-trend-on-social-media/"><u>Elevating Posts  How to Trend on Social Media</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-go-beyond-boundaries-with-panasonic-hx-a1-wearable-camera/"><u>In 2024, Go Beyond Boundaries with Panasonic HX-A1 Wearable Camera</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-special-features-virtual-location-on-nubia-red-magic-9-proplus-drfone-by-drfone-virtual-android/"><u>In 2024, How To Use Special Features - Virtual Location On Nubia Red Magic 9 Pro+? | Dr.fone</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-best-video-makers-with-music-for-android-and-iphone/"><u>New 2024 Approved Best Video Makers with Music for Android and iPhone</u></a></li>
<li><a href="https://howto.techidaily.com/reliable-user-guide-to-fix-lava-blaze-pro-5g-running-slow-and-freezing-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reliable User Guide to Fix Lava Blaze Pro 5G Running Slow and Freezing | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/1719298315535-solving-your-full-screen-capture-predicament-with-snip-and-sketch/"><u>Solving Your Full-Screen Capture Predicament with Snip & Sketch.</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-how-to-fix-swtor-game-launch-problems/"><u>Troubleshooting: How to Fix 'SWTOR' Game Launch Problems</u></a></li>
</ul></div>
