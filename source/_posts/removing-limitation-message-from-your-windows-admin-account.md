---
title: Removing Limitation Message From Your Windows Admin Account
date: 2024-08-27T16:09:00.892Z
updated: 2024-08-28T16:09:00.892Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Removing Limitation Message From Your Windows Admin Account
excerpt: This Article Describes Removing Limitation Message From Your Windows Admin Account
keywords: Unlock Windows Admin Access,Remove Admin Login Errors,Eliminate Admin Restrictions,Bypass Admin Lockout,Clear Admin Limitation Message,Disable Admin Denial Notice,Escape Admin Account Conflict
thumbnail: https://thmb.techidaily.com/3c560b5f84950935f235a17f57ab9b2b0c297df9b81f28e15578b876da96606b.jpg
---

## Removing Limitation Message From Your Windows Admin Account

 Some users have posted on troubleshooting forums about a “Page not available” error that occurs when they open Windows Security. The “Page not available” error message says, “Your IT Administrator has limited access to some areas of this app.” That error message appears within Windows Security, and users can’t access that app’s antivirus settings because of it.

 This error message suggests another administrative user has applied restrictions to Windows Security. However, it often arises on standalone PCs that aren’t connected to an organization network. This is how you can fix the “Your IT administrator has limited access” error.

## 1\. Change Your User Account to an Admin Account

 You shouldn’t usually need admin rights to access Windows Security. However, make sure you’re signed in to an admin account to ensure you have full system permissions. If you’re utilizing a standard account, change it to an administrator one. You can do that with one of the methods outlined in this guide to[changing user account type in Windows](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) .

![The Access work or school account settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/work-or-school-accounts.jpg)

## 2\. Uninstall Third-Party Security Software

 Have you installed a third-party antivirus app on your PC? If so, that security software could be by conflicting with Microsoft Defender and causing the “Page not available” error. Try uninstalling the third-party antivirus utility you’ve installed with a method in our guide to[removing Windows software](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) . Or utilize a dedicated removal tool for your antivirus app if there’s one available.

![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/uninstall-option-3.jpg)

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
## 3\. Remove Any Work or School Accounts

 Have you connected your PC with any school or work organization account? If so, such an account could be restricting access to Windows Security settings. Try disconnecting your PC from the school or work in Settings as follows:

1. Bring up Settings and click that app’s**Accounts** tab (or category).
2. Scroll down to select the**Access work or school navigation** option.
3. Click a connected work or school account to expand it.  
![The Access work or school account settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/work-or-school-accounts.jpg)
4. Press the**Disconnect** button and select**Yes** .
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->

## 4\. Disable the Turn Off Microsoft Defender Antivirus Policy

 Some Windows Pro and Enterprise users have confirmed they’ve fixed the “Page not available” error by disabling a**Turn off Microsoft Defender Antivirus** policy. So, check that policy setting even if you can’t recall changing it yourself. This is how you can check and disable the**Turn Off Microsoft Defender Antivirus** Group Policy setting in Windows Pro and Enterprise:

1. To access the file search box, hold the Windows logo key and press S.
2. Type**gpedit.msc** inside the file search box.
3. Double-click**gpedit.msc** to[open the Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) window.
4. Next, double-click**Computer Configuration** and**Administrative Templates** within Group Policy Editor’s sidebar.
5. Expand the**Windows Components** folder in the sidebar.

1. Click**Microsoft Defender Antivirus** to select that policy.  
![Microsoft Defender Antivirus settings in Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/microsoft-defender-antivirus-settings.jpg)
2. Then double-click**Turn off Microsoft Defender Antivirus** .
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->
3. Click**Disabled** if the**Turn off Microsoft Defender Antivirus** policy is enabled.  
![The Turn off Microsoft Defender Antivirus window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-turn-off-microsoft-defender-antivirus-window.jpg)
4. Select the policy’s**Apply** and**OK** options.
5. Double-click**Allow antimalware to startup with normal priority** and select to disable that policy as outlined in the previous two steps as well.  
![The Allow antimalware service to startup with normal priority window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-antimalware-service-window.jpg)
6. Next, click**Client Interface** within the Microsoft Defender Antivirus settings.  
<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
![Allow antimalware service to startup with normal priority](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/client-interface-setting.jpg)
7. Double-click the**Enable headless UI mode** policy to view it.  
![The Client Interface settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/enable-headless-ui-mode.jpg)
8. Select**Disabled** \>**Apply** \>**OK** in the Enable headless UI mode policy window.

## 5\. Run a PowerShell Command

 Running a set-MpPreference PowerShell command is a widely confirmed potential resolution for the “Page not available” error. The confirmed command disables Microsoft Defender’s UI lockdown mode. You can run that PowerShell command like this:

1. Activate the Windows search utility.
2. Input a**PowerShell** search phrase to find that command-line app.
3. Open PowerShell with elevated permissions by right-clicking the search result for that command-line app and selecting**Run as administrator** .
4. Input this**MpPreference** command and press**Return** :  
`set-MpPreference -UILockdown`  
![The set-Mppreference PowerShell command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-set-mppreference-command.jpg)
5. Exit PowerShell and open Windows Security again to see if the error persists.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Repair/Reset Windows Security

 Windows Security is a UWP app for which you can select**Repair** and**Reset** Settings options that can resolve various issues. Those options are there to help users fix apps that aren’t working right. So, try selecting Windows Security’s**Repair** and**Reset** options to see if they make any difference.

![The Reset button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/repair-button.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
 Our article[about resetting Windows apps](https://www.makeuseof.com/windows-reset-app/) tells you how to access the**Reset** button. The**Repair** button is just above the**Reset** option. It’s recommended to select**Repair** first since that doesn’t affect app data.

## 7\. Modify the Registry via Command Prompt

 Users also confirm that running a series of Command Prompt commands that modify the registry can resolve the “Page not available” issue. As those are reg delete commands, we recommend you back up the registry before applying this potential fix. Then try running the registry commands for erasing policies like this:

 Open the utility for finding files and apps with the**Windows** logo +**S** key combination.

1. Find the Command Prompt by typing in a**CMD** search phrase.
2. Click the Command Prompt app with the mouse’s right button to select a**Run as administrator** context menu option.
3. Execute the following commands separately, pressing**Enter** after inputting each one:  
`reg delete "HKLM\Software\Microsoft\Windows\CurrentVersion\Policies" /f  

reg delete "HKLM\Software \Microsoft\WindowsSelfHost" /f  

reg delete "HKLM\Software\Policies" /f  

reg delete "HKLM\Software\WOW6432Node\Microsoft\Policies" /f  

reg delete "HKLM\Software\WOW6432Node\Microsoft\Windows\CurrentVersion\Policies" /f  

reg delete "HKLM\SOFTWARE\Policies\Microsoft\Windows Defender" /v DisableAntiSpyware  

reg delete "HKCU\Software\Microsoft\Windows\CurrentVersion\Policies" /f  

reg delete "HKCU\Software\Microsoft\WindowsSelfHost" /f  

reg delete "HKCU\Software\Policies" /f  

reg delete "HKLM\Software\Microsoft\Policies" /f`
4. Input**exit** in the Command Prompt to close the app.  
![The reg delete command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reg-delete.jpg)
5. Open the Start menu, select**Power** , and press the**Restart** button.
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->

## 8\. Perform a System Restore

 If the “Page not available” error remains after applying other potential solutions, try performing a system restore. That might work if you can select a restore point predating the “Page not available” error on your PC. Rolling Windows back to an earlier time could undo any system changes that caused the issue to arise.

![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-resotre-window.jpg)

<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Our guide on[creating and utilizing restore points](https://www.makeuseof.com/windows-11-create-restore-point/) provides instructions for rolling back Windows with System Restore. Choose the oldest restore point you can. However, remember that you’ll probably need to reinstall some software packages installed after the restore point’s date.

## Start Utilizing Windows Security Again

 The potential solutions covered in this guide address many of the primary causes for that error occurring. So, they’ll probably get the “Page not available” error sorted on most users’ Windows 11/10 PCs. Fixing the “Page not available” error will enable you to access all the settings in Windows Security again.

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
<li><a href="https://some-techniques.techidaily.com/new-exclusive-android-3d-video-enthusiasts-choice/"><u>[New] Exclusive Android 3D Video Enthusiasts' Choice</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-top-tier-ways-to-preserve-lol-competitions-for-2024/"><u>[Updated] Top-Tier Ways to Preserve LOL Competitions for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-clip-curator-platform/"><u>2024 Approved  Clip Curator Platform</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-eye-catchers-of-tomorrow-discovering-6-future-oriented-genres/"><u>2024 Approved  Eye Catchers of Tomorrow  Discovering 6 Future-Oriented Genres</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-transfer-tactics-for-youtube-to-dailymotion-success/"><u>2024 Approved  Transfer Tactics for YouTube to Dailymotion Success</u></a></li>
<li><a href="https://extra-hints.techidaily.com/a-complete-list-where-to-find-high-quality-music-files/"><u>A Complete List  Where to Find High-Quality Music Files</u></a></li>
<li><a href="https://buynow-info.techidaily.com/compact-and-convenient-laptop-charging-gadgets-dominating-2024s-best-sellers/"><u>Compact and Convenient Laptop Charging Gadgets Dominating 2024'S Best-Sellers</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-overcoming-outlook-crashing-issues/"><u>Essential Guide: Overcoming Outlook Crashing Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-resolving-winerror-0x8007043c-on-media-creator/"><u>Guide to Resolving WinError 0X8007043C on Media Creator</u></a></li>
<li><a href="https://windows11.techidaily.com/hidden-window-11-customization-marvels/"><u>Hidden Window 11 Customization Marvels</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-correctly-evaluate-processor-load-using-task-manager/"><u>How to Correctly Evaluate Processor Load Using Task Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-get-past-a-non-starting-battlenet-interface/"><u>How to Get Past a Non-Starting Battle.net Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-switch-off-mobility-features-on-win-11/"><u>How To Switch Off Mobility Features on Win 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-androids-best-podcast-discoveries/"><u>In 2024, Android's Best Podcast Discoveries</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-frp-hijacker-by-hagard-download-and-bypass-your-realme-narzo-60-pro-5g-frp-locks-by-drfone-android/"><u>In 2024, FRP Hijacker by Hagard Download and Bypass your Realme Narzo 60 Pro 5G FRP Locks</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-pause-life360-location-sharing-for-apple-iphone-se-2020-drfone-by-drfone-virtual-ios/"><u>In 2024, How To Pause Life360 Location Sharing For Apple iPhone SE (2020) | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-poco-c55-drfone-by-drfone-virtual-android/"><u>In 2024, Why Your WhatsApp Location is Not Updating and How to Fix On Poco C55 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/keyboard-prodigy-tips-for-windows-photoshop/"><u>Keyboard Prodigy Tips for Windows Photoshop</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-art-of-regaining-win-folder-entry/"><u>Master the Art of Regaining Win Folder Entry</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-heic-jpeg-conversions-on-windows/"><u>Mastering HEIC-JPEG Conversions on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-windows-11-typing-troubles-addressing-zerox-code-0x80049dd3/"><u>Navigating Through Windows 11 Typing Troubles: Addressing Zerox (Code: 0X80049DD3)</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-resource-already-active-issue-on-windows-11/"><u>Overcoming Resource Already Active Issue on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-11s-uptime-failure-error-code-0x80246007/"><u>Overcoming Windows 11’S Uptime Failure: Error Code 0X80246007</u></a></li>
<li><a href="https://technical-tips.techidaily.com/prioritizing-features-a-guide-to-selecting-the-perfect-smart-tv-among-options/"><u>Prioritizing Features: A Guide to Selecting the Perfect Smart TV Among Options</u></a></li>
<li><a href="https://windows11.techidaily.com/reactivating-defenders-a-step-by-step-guide-for-five-common-issues/"><u>Reactivating Defenders: A Step-by-Step Guide for Five Common Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstate-audio-preferences-winvolume-issue-resolution/"><u>Reinstate Audio Preferences: WinVolume Issue Resolution</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-rpc-issues-on-windows-key-strategies/"><u>Resolving RPC Issues on Windows: Key Strategies</u></a></li>
<li><a href="https://location-social.techidaily.com/set-your-preferred-job-location-on-linkedin-app-of-your-realme-gt-neo-5-se-drfone-by-drfone-virtual-android/"><u>Set Your Preferred Job Location on LinkedIn App of your Realme GT Neo 5 SE | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-realign-file-history-configurations-in-windows/"><u>Steps to Realign File History Configurations in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-windows-write-operations-error/"><u>Tackling Windows Write Operations Error</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-guide-to-windows-11-widget-bar-activation/"><u>The Essential Guide to Windows 11 Widget Bar Activation</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-windows-11-help-app-restoration/"><u>Tips for Windows 11 Help App Restoration</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-windows-1011-8-innovative-personalization-techniques/"><u>Unlock Windows 10/11: 8 Innovative Personalization Techniques</u></a></li>
</ul></div>