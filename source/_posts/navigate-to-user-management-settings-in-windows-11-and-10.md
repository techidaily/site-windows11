---
title: Navigate to User Management Settings in Windows 11 & 10
date: 2024-08-15T16:15:15.493Z
updated: 2024-08-16T16:15:15.493Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigate to User Management Settings in Windows 11 & 10
excerpt: This Article Describes Navigate to User Management Settings in Windows 11 & 10
keywords: Windows 11 User Management,Windows 10 User Access,Navigate User Controls (Windows),Manage Users in Win11/10,User Settings Window,Windows User Settings Nav,Windows User Management Guide
thumbnail: https://thmb.techidaily.com/8b607e0e604394629b363ae69329923c5b752c9a4c4af741aef58011df0d7554.jpg
---

## Navigate to User Management Settings in Windows 11 & 10

### Quick Links

* [Enable the Local Users and Groups Management Console in Windows 11/10 Home](#enable-the-local-users-and-groups-management-console-in-windows-11-10-home)
* [Manage Local Users and Groups Using the Command Prompt](#manage-local-users-and-groups-using-the-command-prompt)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
### Key Takeaways

* Local Users and Groups Management is not available in Windows 11/10 Home editions. You need a third-party program to access it.
* You can use Lusrmgr.exe, a portable third-party alternative, to enable the Microsoft Management Console snap-in in Windows 11 Home. The Lusrmgr application provides additional features like account search and defining access times.
* The Command Prompt can also be used to manage users and groups without a third-party utility.

 Local Users and Groups Management is a shell application to manage local and remote computers and access system administrator tools. However, Local Users and Groups Management is unavailable in the Windows 11/10 Home editions, so you must rely on a third-party program to use it there.

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
## Enable the Local Users and Groups Management Console in Windows 11/10 Home

 Like the Local Group Policy Editor, Local Users and Groups Management (lusrmgr.msc) is an advanced feature available only on Windows Pro, Education, and Enterprise.

 However, while you can use workarounds to [enable Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/), it is not possible to enable the Local Users and Groups Management snap-in console.

 Instead, you can use Lusrmgr.exe, a third-party alternative, to enable the Microsoft Management Console snap-in in Windows 11 Home. Lusrmgr.exe is similar to the built-in Local Users and Groups Management console. It is a portable application, and you can download it from GitHub for free.

 Here's how to download and use the Local User and Group Management tool on Windows 11 Home. Follow the same steps on a Windows 10 PC:

1. Open the [lusrmgr GitHub page](https://github.com/proviq/lusrmgr).
2. On the default **Code** tab, scroll down to the **Download** link to get the latest version of the file.
3. Once downloaded, double-click the **lusrmgr.exe**file to run the program.

![lusrmgr program home screen running on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-program.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->

 You will notice the lusrmgr application looks similar to [opening the native Local Users and Groups Management console](http://www.makeuseof.com/windows-open-local-users-and-groups/). However, the difference lies in the usability of the tool. Below are side-by-side images for the built-in lusrmgr console (left) and the third-party application (right) for reference.

![Lucal User and Groups app and lusrmgr app side by side comparison](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/lucal-user-and-gropups-app-and-lusrmgr.jpg)

 To create a new user account with this Local User and Group Management tool:

1. Right-click on **User** and select **Create**. Then fill in the details for the new user account.
2. Click the **Advanced** button to configure the advanced account option, local path, and profile path.  
![lusrmgr create new user account screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-create-new-user.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
3. Click on **Create** to add the new user account.

 Similarly, you can edit, remove, rename, or add a password to the existing user account. You can also [enable the secret built-in administrator account](https://www.makeuseof.com/windows-11-enable-disable-built-in-administrator-account/) using the tool.

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Additional Features of the Lusrmgr App

![The search bar in lusrmgr application](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-search.jpg)

 Apart from the usual account management features, lusrmgr.exe provides additional functions not available in the native utility. For example, you can use the search function to find a specific account. This is useful for system administrators who manage multiple user accounts in an organization.

 Another handy feature is the ability to define access times for individual accounts. To set an access time, right-click on the username and select **Edit**. Next, open the **Account** tab and click on **Define access time**.

![lusrmgr define account access time screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-define-access-time.jpg)

 By default, the user accounts have no limit on access time. But you can define this by selecting a time block for different days.

 Since lusrmgr is a portable app, you can’t open it with the **lusrmgr.msc** command like the built-in app. To launch the program, double-click the executable file you downloaded and make the necessary changes to the user account or groups.

## 2\. Manage Local Users and Groups Using the Command Prompt

 You can use the "net localgroup" or "net user" command-line utility to manage users and groups on Windows 11/10\. It's a handy way to view, add, and delete local groups and users without using a third-party utility.

![How to Run the Command Prompt as an Administrator in Windows Thumbnail](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/how-to-run-the-command-prompt-as-an-administrator-in-windows-thumbnail.jpg)

  First, open a Command Prompt window with administrative privilege. To do this, press the **Windows** key, type **cmd**, right-click on **Command Prompt**, and select **Run as administrator**.

 Below is a list of commands to view and manage local users and groups using the Command Prompt:

1. To view the name of the server and local groups on the computer, type:  
`net localgroup`
2. To view all users in a group, enter:  
`net localgroup [groupname]`
3. To create a new group, use the following command. Replace **xyz** with the group name you want to create:  
`net localgroup xyz /add`
4. To view all user accounts:  
`net user`
5. To create a new user account (replace **abc** with the username you want to add):  
`net user abc /add`

1. To view all the accounts with administrator privileges:  
`net localgroup administrator`
2. To add a user account to the administrator group (be sure to change **abc**, and **Administrator** to the group name if needed):  
`net localgroup Administrator abc /add`
3. To delete a local group:  
`net localgroup xyz /delete`
4. To delete a local user:  
`net user abc /delete`
5. If you need help with syntax for a specific command, use this:  
`net help <command>`

![Command Prompt screen with the net localgroup command displayed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/command-prompt-screen-with-the-net-localgroup-command-displayed.jpg)
<!-- affiliate ads begin -->

<!-- affiliate ads end -->

 The Local Users and Groups Management console is a handy utility for system administrators to manage local computers and connect remotely to compatible systems. However, if you are running Windows 11 Home and need to use the lusrmgr.msc tool, your only option is to use the third-party application from GitHub.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-crafting-success-on-facebook-a-beginners-and-pro-guide-compilation/"><u>[New] 2024 Approved  Crafting Success on Facebook  A Beginner's & Pro Guide Compilation</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-direct-from-mobile-how-to-upload-videos-on-twit/"><u>[New] 2024 Approved  Direct From Mobile  How to Upload Videos on Twit</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-becoming-an-expert-in-igtv-a-complete-overview-for-2024/"><u>[New] Becoming an Expert in IGTV  A Complete Overview for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-quick-and-easy-tips-for-creating-insta-groups/"><u>[New] Quick & Easy Tips for Creating Insta Groups</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-top-picks-superior-cloud-space-solutions/"><u>[New] Top Picks  Superior Cloud Space Solutions</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-leading-platforms-mimicking-twitters-network/"><u>[Updated] Leading Platforms Mimicking Twitter's Network</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-snapshot-sophistication-expert-advice-on-editing-magic/"><u>[Updated] Snapshot Sophistication  Expert Advice on Editing Magic</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-experts-pathway-to-purchasing-an-immaculate-4k-display/"><u>[Updated] The Expert's Pathway to Purchasing an Immaculate 4K Display</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-tricks-to-improve-instagram-video-load-speeds-mobile-for-2024/"><u>[Updated] Tricks to Improve Instagram Video Load Speeds (Mobile) for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-beijings-frost-touched-games-highlights-from-2022/"><u>2024 Approved  Beijing's Frost-Touched Games, Highlights From 2022</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-elevate-your-photos-utilizing-luts-in-adobes-image-editor/"><u>2024 Approved  Elevate Your Photos  Utilizing LUTs in Adobe's Image Editor</u></a></li>
<li><a href="https://article-files.techidaily.com/7-writing-linkedin-summary-tips-you-must-know/"><u>7 Writing LinkedIn Summary Tips You Must Know</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-process-system-isnt-responding-error-on-oneplus-ace-3-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Process System Isnt Responding Error on OnePlus Ace 3 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/dodge-the-delays-enhance-your-warfare-experience-in-bf2/"><u>Dodge the Delays: Enhance Your Warfare Experience in BF2</u></a></li>
<li><a href="https://windows11.techidaily.com/does-error-8024002e-prevent-windows-from-updating-try-these-fixes/"><u>Does Error 8024002E Prevent Windows From Updating? Try These Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/dual-monitors-double-delight-themed-wallpapers-for-win-1011/"><u>Dual Monitors, Double Delight: Themed Wallpapers for WIN 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/ease-definitions-into-your-workspace-quickly/"><u>Ease Definitions Into Your Workspace Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/easily-shift-your-mkv-files-to-mp4-on-windows/"><u>Easily Shift Your MKV Files to MP4 on Windows</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-call-history-from-galaxy-a34-5g-by-fonelab-android-recover-call-logs/"><u>Easy steps to recover deleted call history from Galaxy A34 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-way-to-show-images-in-windows-11/"><u>Easy Way to Show Images in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/efface-the-expiring-windows-license-notifications/"><u>Efface the Expiring Windows License Notifications</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-strategies-to-delete-print-sources-on-windows-11/"><u>Effective Strategies to Delete Print Sources on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiency-at-your-fingertips-uninstall-microsoft-edge-from-w11/"><u>Efficiency at Your Fingertips: Uninstall Microsoft Edge From W11</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-execution-with-ms-project-shortcuts/"><u>Efficient Execution with MS Project Shortcuts</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-strategies-to-bypass-windows-11s-tpm-lockdown/"><u>Efficient Strategies to Bypass Windows 11'S TPM Lockdown</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-techniques-overcoming-wwe-2k23-crash-issues-in-windows/"><u>Efficient Techniques: Overcoming WWE 2K23 Crash Issues in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-altering-windows-group-policies/"><u>Efficiently Altering Windows Group Policies</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-establish-microsoft-works-on-windows-11/"><u>Efficiently Establish Microsoft Works on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-unlock-recovery-options-for-your-pc/"><u>Efficiently Unlock Recovery Options for Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-empty-folder-search-and-removal-guide-for-windows-users/"><u>Effortless Empty Folder Search and Removal Guide for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-jotting-in-windows-11-no-apps-required/"><u>Effortless Jotting in Windows 11: No Apps Required</u></a></li>
<li><a href="https://windows11.techidaily.com/effortlessly-connect-and-communicate-with-imessage-on-your-pc/"><u>Effortlessly Connect and Communicate with iMessage on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/effortlessly-get-icloud-up-and-running-on-windows/"><u>Effortlessly Get iCloud Up and Running on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-pc-capabilities-a-comprehensible-wintoy-approach/"><u>Elevate PC Capabilities: A Comprehensible WinToy Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-pc-expertise-with-vivetool-on-windows/"><u>Elevate Your PC Expertise with ViVeTool on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-windows-experience-with-tpm-and-secure-boot-setup/"><u>Elevate Your Windows Experience with TPM & Secure Boot Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminate-installation-error-fix-oculus-for-winxc-and-winxi/"><u>Eliminate Installation Error: Fix Oculus for WinXC and WinXI</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-search-issues-on-windows-11-os/"><u>Eliminating Search Issues on Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/elusive-wi-fi-on-windows-how-to-hide-itself/"><u>Elusive Wi-Fi on Windows: How To Hide Itself</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-end-task-feature-for-optimized-window-management-in-windows-11-ui/"><u>Enabling End Task Feature for Optimized Window Management in Windows 11 UI</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-virtual-machine-speed-in-windows-a-6-step-guide/"><u>Enhance Virtual Machine Speed in Windows - A 6-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-your-workflow-top-windows-11-rdc-techniques/"><u>Enhance Your Workflow: Top Windows 11 RDC Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-performance-metrics-tracking-on-windows/"><u>Enhancing Performance Metrics Tracking on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-windows-photos-with-an-effortless-carousel-seven-step-guide/"><u>Enhancing Windows Photos with an Effortless Carousel, Seven-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicating-microsoft-edge-on-win11/"><u>Eradicating Microsoft Edge on Win11</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/how-to-restore-erased-information-on-your-iphone-with-stellars-help/"><u>How to Restore Erased Information on Your iPhone with Stellar's Help</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-nubia-z50-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, 4 solution to get rid of pokemon fail to detect location On Nubia Z50 Ultra | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/preparation-to-beat-giovani-in-pokemon-go-for-nokia-c110-drfone-by-drfone-virtual-android/"><u>Preparation to Beat Giovani in Pokemon Go For Nokia C110 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proactive-power-indicators-ensure-a-full-charge-with-windows-11-alerts/"><u>Proactive Power Indicators: Ensure a Full Charge with Windows 11 Alerts</u></a></li>
<li><a href="https://data-wizards.techidaily.com/revive-corrupt-movie-files-quickly-using-vlc-media-players-tools/"><u>Revive Corrupt Movie Files Quickly Using VLC Media Player's Tools</u></a></li>
</ul></div>
