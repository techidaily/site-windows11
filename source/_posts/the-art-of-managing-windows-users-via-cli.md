---
title: The Art of Managing Windows Users via CLI
date: 2024-08-22T21:40:37.161Z
updated: 2024-08-23T21:40:37.161Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Art of Managing Windows Users via CLI
excerpt: This Article Describes The Art of Managing Windows Users via CLI
keywords: WinUserCLIGuide,CommandLineAdmin,CLIUserManagement,AdminWindowsCLI,PowerShellWindowsUsers,CliUserManagementArt,WindowsUserCommandTools
thumbnail: https://thmb.techidaily.com/98381f75da9e421b6eb855209185ef7a1fbf0a3e49f7737dbe8956238d8582c9.jpg
---

## The Art of Managing Windows Users via CLI

 When managing user accounts on a Windows PC, it often makes sense to use the Settings app. After all, it provides a graphical user interface that simplifies the process. But for those who'd rather manage the accounts with fewer clicks, they can use the **net user** command in Command Prompt to manage user accounts on Windows.

 In this guide, we're going to show you how to use the net user command to perform various actions on user accounts on a Windows computer.

## 1\. List All User Accounts

![list all user accounts with net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/list-all-user-accounts-with-net-user.jpg)

 Before you start managing user accounts with **net user**, it helps to know all the user accounts on your computer. To list them all, [open Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/), enter the below command, and hit the **Enter** key to run it:

`net user`

 Keep the names you see in mind, as you will need them as you use the **net user** command.

## 2\. Show All the Information of a User Account

![user account details while using net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/user-account-details-while-using-net-user.jpg)

 You can also bring up all the important information about a user by simply typing the **net user** command followed by the name of the user's name. Here's the basic syntax:

`net user Username`

 Let's say there's a user named "Jack" on the computer. To bring up their account information, you'd enter the below command, replacing **Username** in the above command structure with **Jack**:

`net user Jack`

 Once you run the command, you'll be able to see, the user's full name, when their password expires, when they last logged in, whether they're an administrator, and more.

## 3\. Add and Delete a User Account

 To add a new user in Command Prompt, you need to use the **net user** command followed by the name of the new account, the desired password you wish to set, and the **/add** switch (this tells **net user** that you're adding a user). Here's the basic syntax of the command:

`net user Username Password /add`

 Keep in mind that all you'll be creating here is a local account, but you can always [switch a local account to a Microsoft account](https://www.makeuseof.com/windows-switch-local-account-to-microsoft-account/) later on. Here's an example of the command in action:

`net user Jill Pa$w0rd /add`

 After you run that command, you'll see that the new user, **Jill**, has been added to your computer. To delete an account, just replace the **/add** switch with **/delete** without specifying the password. Here's how:

`net user Jill /delete`

 Now net user will remove the account from the computer.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
## 4\. Enable and Disable a User Account

![deactivating an account with net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/deactivating-an-account-with-net-user.jpg)

 If there's a user you wish to temporarily restrict so they can't access their account, you can simply disable it instead of deleting it. Here's the basic syntax of that action, making sure to use the **/active:no** switch at the end of the command to tell **net user** you're disabling it:

`net user Username /active:no`

 So, here's an example of what disabling an account would look like after replacing **Username** with the name of the actual user account:

`net user Jack /active:no`

 And if you want to enable a disabled account, you just have to change the **/active:no** switch to **/active:yes**.

## 5\. Enable and Disable a Domain User Account

 Sometimes, you might not want a user to access all the resources in a particular domain. The easier way to restrict them is to disable their account in that domain. You can do this by adding the **/domain** switch to the syntax discussed in the previous section.

 Here's the syntax for disabling an account on a particular domain using **net user**, making sure to replace **Username** with the name of the user you want to disable:

`net user Username /domain /active:no`

 If you want to enable an account on a domain, just use the **/active:yes** switch in the above command structure instead.

## 6\. Set User Account Login Times

 If you want to specify the times someone can log in, you can use the **/time** parameter to specify the account login times. You can use the basic syntax below:

`net user Username /time login_times`

 In the above command structure, replace **Username** with the user you want to limit the login times for, and **login\_times** with a time range in the format **D-D,00:00**. Here's an example of how you'd do this:

`net user Jack /time:M-F,09:00-17:00`

 As per the example above, that user can only log in from Monday to Friday between 9 a.m. and 5 p.m. If Jack tried to log in, he'd get a message saying **Your account has time restrictions that prevent you from signing in**.

 To remove the time restrictions, you'd use the below command:

`net user Jack /time:all`

 Now Jack can go back to logging in whenever he wants.

## 7\. Set User Account Expiry Date

![setting an account expiriation date with net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/setting-an-account-expiriation-date-with-net-user.jpg)

 By default, accounts are set to never expire, but you can change that if you have a user you want to be active for a specific period of time. You will need to use the **/expires** parameter while specifying the year, month, and expiration date. Here's the basic command structure:

`net user Username /expires:DD/MM/YYYY`

 An example of this in action would be:

`net user Jack /expires:27/07/2024`

 With the above command, Windows will disable the on the date you've set above.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->
## 8\. Change the Password of a User Account

 You can also use the **net user** command to [change the password of a user account in Command Prompt](https://www.makeuseof.com/tag/quick-tip-change-the-windows-user-password-via-command-line/). This will make it so that you can quickly change the password of any local account with a single command, instead of having to do it through the Settings app, which requires many clicks.

 The beauty of it is that you can also use it to change passwords for multiple accounts without leaving the Command Prompt window.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
## 9\. Change the Password of a Domain User Account

 You can also change the password of a user on a domain by appending the **/domain** switch at the end of the command for changing a user account. The syntax for this is as follows:

`net user Username NewPassword /domain`

 Again this has to be a local domain user account for this to work. So, if you [changed the user account from a Microsoft account to a local account](https://www.makeuseof.com/how-to-switch-windows-from-microsoft-account-to-local-account/), you'll need to switch it back to use the command.

## 10\. Set a Password Policy for Users

![setting an account policy with net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/setting-account-policy-with-net-user.jpg)

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If you need a particular user to change the password during their next login, you can use the **net user** command along with the **/passwordchg:yes** parameter (by default, the parameter is **/passwordchg:no**). Here's the basic syntax:

`net user Username /passwordchg:yes`

 Here's an example of what that would look like in Command Prompt:

`net user Jack /passwordchg:yes`

 So, the next time Jack logs into the computer, he will get a prompt asking him to change his password before he can access his user account.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->
## 11\. Set a Home Directory for Users

 When creating a new user profile using **net user**, you can set the home directory, which is where Windows will store the user's personal files and settings. By default, Windows places the home directory of each user account in **This PC > Local Disk (C:) > Users**. To change this with **net user** during account creation, the basic syntax is as follows:

`net user Username Password /add /homedir:Path-to-directory`

 A real-world example of this would be:

`net user Jack Pa$w0rd /add /homedir:D:\Other Users\Jack`

 The above command will place the home directory of **Jack**, as it creates the account, in the **D:\\Other Users\\Jack** folder.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
## Take Control of Your Computer's Users Accounts With the Net User Command

 Net user is a simple command to understand, allowing you to effectively manage your accounts from one location: Command Prompt. Of course, we haven't covered everything here, as there are too many parameters and switches to cover in a single guide.

 With that said, after you've understood how to perform the **net user** actions we've covered, you'll be on your way to managing accounts on Windows much quicker.

 In this guide, we're going to show you how to use the net user command to perform various actions on user accounts on a Windows computer.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-control-over-your-ig-content-exposure/"><u>[New] 2024 Approved  Control Over Your IG Content Exposure</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/est-12-youtube-gaming-intro-makers-free-and-paid-for-2024/"><u>[New] Best 12 YouTube Gaming Intro Makers - Free and Paid for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-best-screen-replay-applications-for-windowsmacos/"><u>[New] Best Screen Replay Applications for Windows/macOS</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-build-a-custom-facebook-coverage-for-2024/"><u>[New] Build a Custom Facebook Coverage for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-decoding-the-latest-shifts-in-facebook-landscape/"><u>[New] Decoding the Latest Shifts in Facebook Landscape</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-in-depth-review-the-full-story-of-theta-s-technology/"><u>[New] In-Depth Review  The Full Story of Theta S Technology</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-pinnacle-business-cloud-haven/"><u>[New] Pinnacle Business Cloud Haven</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/he-art-of-choosing-and-utilizing-cc-license-types-for-2024/"><u>[New] The Art of Choosing and Utilizing CC License Types for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-enhanced-mp4-streaming-for-facebook-networks/"><u>[Updated] 2024 Approved  Enhanced MP4 Streaming for Facebook Networks</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-premier-screener-for-capturing-high-quality-videos/"><u>[Updated] Premier Screener for Capturing High-Quality Videos</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-screensnapper-pro-the-ultimate-guide-to-capturing-your-world-for-2024/"><u>[Updated] ScreenSnapper Pro  The Ultimate Guide to Capturing Your World for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-crafting-star-stirred-stories-for-your-whatsapp-bio/"><u>2024 Approved  Crafting Star-Stirred Stories for Your WhatsApp Bio</u></a></li>
<li><a href="https://driver-download.techidaily.com/download-and-installation-process-mbox-2-driver-updates-on-windows-systems/"><u>Download & Installation Process: MBox 2 Driver Updates on Windows Systems</u></a></li>
<li><a href="https://android-frp.techidaily.com/easy-guide-how-to-bypass-realme-gt-5-frp-android-10111213-by-drfone-android/"><u>Easy Guide How To Bypass Realme GT 5 FRP Android 10/11/12/13</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/efficient-name-alteration-for-meet-sessions-laptopmobile-for-2024/"><u>Efficient Name Alteration for Meet Sessions (Laptop/Mobile) for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/explore-football-fantasyland-how-to-thrive-in-ocm-without-spending-money/"><u>Explore Football Fantasyland: How to Thrive in OCM Without Spending Money</u></a></li>
<li><a href="https://windows11.techidaily.com/five-free-methods-to-jot-down-on-windows-11/"><u>Five Free Methods to Jot Down on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-device-freeze-addressing-error-0x887a0006-windows/"><u>Fixing Device Freeze: Addressing Error 0X887A0006 Windows</u></a></li>
<li><a href="https://buynow-info.techidaily.com/fujitsu-scansnap-ix1600-your-complete-guide-to-the-most-reliable-desktop-document-scanner-reviewed/"><u>Fujitsu ScanSnap iX1600: Your Complete Guide to the Most Reliable Desktop Document Scanner Reviewed</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/fusing-live-streams-combining-cameras-plus-monitors-for-2024/"><u>Fusing Live Streams  Combining Cameras + Monitors for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-overcoming-wrong-character-display/"><u>Guide to Overcoming Wrong Character Display</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-unsuccessful-execution-calls-in-malwarebytes-software/"><u>Handling Unsuccessful Execution Calls in Malwarebytes Software</u></a></li>
<li><a href="https://windows11.techidaily.com/hiding-login-details-deactivating-security-questions-on-windows-11/"><u>Hiding Login Details: Deactivating Security Questions on Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-spotify-location-after-moving-to-another-country-on-vivo-x90s-drfone-by-drfone-virtual-android/"><u>How to Change Spotify Location After Moving to Another Country On Vivo X90S | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-xiaomi-mix-fold-3-drfone-by-drfone-virtual-android/"><u>How to get the dragon scale and evolution-enabled pokemon On Xiaomi Mix Fold 3? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-identify-hard-drive-specs-on-windows/"><u>How to Identify Hard Drive Specs on Windows</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-ace-driving-realism-series-best-5/"><u>In 2024, Ace Driving Realism Series (Best 5)</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-broadcast-your-play-obs-studio-techniques/"><u>In 2024, Broadcast Your Play - OBS Studio Techniques</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-facebook-today-key-changes-for-users/"><u>In 2024, Facebook Today  Key Changes for Users</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-a-network-locked-realme-c33-2023-phone-by-drfone-android/"><u>In 2024, How to Unlock a Network Locked Realme C33 2023 Phone?</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-removing-device-from-apple-id-for-your-iphone-14-pro-max-by-drfone-ios/"><u>In 2024, Removing Device From Apple ID For your iPhone 14 Pro Max</u></a></li>
<li><a href="https://windows11.techidaily.com/integrating-taskbar-on-modern-windows-11-tablets/"><u>Integrating Taskbar on Modern Windows 11 Tablets</u></a></li>
<li><a href="https://windows11.techidaily.com/journey-to-enhanced-productivity-integrating-android-and-windows-11-devices/"><u>Journey to Enhanced Productivity: Integrating Android and Windows 11 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-of-access-control-regedit-in-win11/"><u>Mastery of Access Control: RegEdit in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-through-time-windows-11-file-history-essentials/"><u>Navigate Through Time: Windows 11 File History Essentials</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-and-fixing-windows-registry-failsafe/"><u>Navigating and Fixing Windows Registry Failsafe</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-2024-approved-top-5-free-online-imovie-alternatives-2023-update/"><u>New 2024 Approved Top 5 Free Online iMovie Alternatives 2023 Update</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-reviving-access-with-past-login-details/"><u>Overcoming Reviving Access with Past Login Details</u></a></li>
<li><a href="https://win-answers.techidaily.com/overcoming-the-ultimate-challenge-debugging-ue4s-gobi-bug-in-back-4-blood-game/"><u>Overcoming the Ultimate Challenge: Debugging UE4's Gobi Bug in Back 4 Blood Game</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-value-uncertainty-issues-in-windows-10/"><u>Overcoming Value Uncertainty Issues in Windows 10</u></a></li>
<li><a href="https://network-issues.techidaily.com/quick-techniques-for-removing-windows-graphic-drivers/"><u>Quick Techniques for Removing Windows Graphic Drivers</u></a></li>
<li><a href="https://windows11.techidaily.com/reactivating-non-functional-outlook-email-banners/"><u>Reactivating Non-Functional Outlook Email Banners</u></a></li>
<li><a href="https://windows11.techidaily.com/skip-bloatware-embrace-pure-windows-11-experience/"><u>Skip Bloatware: Embrace Pure Windows 11 Experience!</u></a></li>
<li><a href="https://windows11.techidaily.com/strategic-approach-to-overcoming-wows-unrecoverable-error-132/"><u>Strategic Approach to Overcoming WoW’s Unrecoverable Error 132</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-fix-windows-11-assistive-application/"><u>Strategies to Fix Windows 11 Assistive Application</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-guide-to-identify-your-graphic-model-in-win11/"><u>Swift Guide to Identify Your Graphic Model in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-rockalldll-dll-not-found-on-windows-xpvista/"><u>Tackling 'Rockalldll' DLL Not Found on Windows XP/Vista</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-hard-drive-errors-on-windows/"><u>Tackling Hard Drive Errors on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/trigger-microsoft-word-to-open-email-attachments-in-read-pane/"><u>Trigger Microsoft Word to Open Email Attachments in Read Pane</u></a></li>
<li><a href="https://windows11.techidaily.com/tweaking-device-settings-on-windows-11-a-step-by-step-guide/"><u>Tweaking Device Settings on Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://change-location.techidaily.com/ultimate-guide-to-get-the-meltan-box-pokemon-go-for-samsung-galaxy-s21-fe-5g-2023-drfone-by-drfone-virtual-android/"><u>Ultimate guide to get the meltan box pokemon go For Samsung Galaxy S21 FE 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/unheard-voices-in-meet-solving-windows-microphone-problems/"><u>Unheard Voices in Meet: Solving Windows Microphone Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/unhurried-mobile-migration-with-easy-installation-in-windows-11/"><u>Unhurried Mobile Migration with Easy Installation in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-secure-file-transfer-limitations-on-windows-11/"><u>Unlocking Secure File Transfer Limitations on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-the-definitive-list-of-11-strategies-for-the-credential-manager/"><u>Unlocking Windows: The Definitive List of 11 Strategies for the Credential Manager</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-speed-up-or-slow-down-top-gif-editors-online-and-offline/"><u>Updated In 2024, Speed Up or Slow Down Top GIF Editors Online and Offline</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-world-unravested-formulating-and-examining-diagnostic-data/"><u>Windows World Unravested: Formulating & Examining Diagnostic Data</u></a></li>
<li><a href="https://windows11.techidaily.com/wintools-strategy-the-ultimate-performance-boost/"><u>WinTools Strategy: The Ultimate Performance Boost</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>