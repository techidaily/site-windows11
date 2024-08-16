---
title: A Step-By-Step for Erasing Sign-In Email in Win
date: 2024-08-15T16:11:03.969Z
updated: 2024-08-16T16:11:03.969Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Step-By-Step for Erasing Sign-In Email in Win
excerpt: This Article Describes A Step-By-Step for Erasing Sign-In Email in Win
keywords: Win Email Sign-Out Guide,Windows Remove Login Mail,Clearing Win Signin E-Mail,Win Email Unlink Steps,Disable Win Login Email,Win Sign-In Email Removal,Erase Win Logon Email Process
thumbnail: https://thmb.techidaily.com/aa827fc3b79814207754c42d6a6a4c83088ec414afa88e6a5b8f7881f823fc3c.jpg
---

## A Step-By-Step for Erasing Sign-In Email in Win

 If you frequently use your computer in public places, it's a good idea to remove your email address from the Windows login screen. This means people can't get your email address if they see your screen over your shoulder.

 You can accomplish this using the Settings app, Group Policy Editor, or Registry Editor. In this post, we've covered all these methods in detail.

## 1\. How to Hide Email Address From Windows Login Screen Using the Settings App

 The Windows Settings app provides a quick way to hide account information from the login screen. So, if you are in a rush, use the following steps to remove user email addresses from the Windows login screen.

1. Press**Win + I** or use one of the [many ways to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Accounts > Sign-in options** .
3. Under**Additional settings** , toggle off the switch next to **Show account details such as my email address on the sign-in screen** .  
![Hide Email From Windows Login Screen Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-settings-app.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## 2\. How to Hide Email Address From Windows Login Screen Using the Group Policy Editor

 The Group Policy Editor (or gpedit.msc) is a handy Windows tool for configuring advanced system settings. You can also this tool to hide your email address from the Windows login screen.

 Note that the Group Policy Editor is only available on Windows Professional, Education, and Enterprise editions. If your PC is running Windows Home, check out [how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

1. Press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the search box and select the first result that appears.
3. Use the left pane to navigate to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options** .
4. Double-click the **Interactive Logon: Display user information when the session is locked** policy on your right.
5. In the properties window, click the drop-down menu to select the**Do not display user information** option.
6. Click**Apply** followed by**OK** .  
![Hide Email From Windows Login Screen Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-group-policy-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Next, double-click on the**Interactive logon: Do not display last user name** policy from the same section.
8. Select**Enabled** in the properties window.
9. Click**Apply** followed by**OK** to save changes.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. How to Hide Email Address From Windows Login Screen Using the Registry Editor

 If the above two methods don’t work for some reason, you can make changes to the Windows registry files to hide your email address from the login screen. For that, you’ll need to use the Registry Editor on Windows.

 When it comes to editing Registry files, it's important to be cautious as making incorrect changes can cause irreversible damage to your PC. We recommend you either back up all the registry files or create a restore point before you make any changes. If you need help with that, check our guides on [how to back up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [how to create a restore point in Windows](https://www.makeuseof.com/windows-11-create-restore-point/) .

 Once you’re done with that, use the following steps to hide your email address from the Windows login screen via Registry Editor.

1. Press**Win + X** to open the Power User menu and select**Run** from the list.
2. Type**regedit** in the text box and press**Enter** to open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft > Windows > System** .
5. Right-click on the**System** key and select**New > DWORD (32-bit) Value** .
6. Rename the DWORD to**BlockUserFromShowingAccountDetailsOnSignin** .
7. Double-click on the newly created DWORD and enter**1** in the**Value data** field. Then, click**OK** .  
![Hide Email From Windows Login Screen Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->

 Exit the Registry Editor and restart your PC for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Hiding Your Email Address From the Windows Login Screen Is Easy

 As we just saw, hiding your personal information from the Windows login screen barely takes a couple of minutes, regardless of the method you employ.


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
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-choosing-the-right-fps-30-or-60-which-is-better/"><u>[New] 2024 Approved  Choosing the Right FPS  30 or 60, Which Is Better?</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-revolutionize-your-mac-streaming-experience/"><u>[New] Revolutionize Your Mac Streaming Experience</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-sage-scripts-for-soundplays/"><u>[New] Sage Scripts for Soundplays</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-the-path-to-success-utilizing-youtube-metrics-effectively/"><u>[New] The Path to Success  Utilizing YouTube Metrics Effectively</u></a></li>
<li><a href="https://windows11.techidaily.com/15-paths-to-recover-missing-windows-system-time-functionality/"><u>15 Paths to Recover Missing Windows System Time Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/5-key-steps-to-resolve-hypervisor-error-bsod-in-winos/"><u>5 Key Steps to Resolve Hypervisor Error BSOD in WINOS</u></a></li>
<li><a href="https://windows11.techidaily.com/9-ways-to-fix-mails-notifications-not-working-on-windows/"><u>9 Ways to Fix Mail's Notifications Not Working on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/a-closer-look-at-windows-11s-backup-processing-methods/"><u>A Closer Look at Windows 11'S Backup Processing Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/a-step-by-step-guide-to-fixing-windows-rare-errors/"><u>A Step-by-Step Guide to Fixing Windows’ Rare Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/a-visual-journey-to-custom-window-design-with-winbubbles-insights/"><u>A Visual Journey to Custom Window Design with WinBubble's Insights</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerating-your-gaming-experience-update-radeon-drivers-now/"><u>Accelerating Your Gaming Experience: Update Radeon Drivers Now</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-peak-performance-with-multi-task-proficiency-on-windows-11-pcs/"><u>Achieve Peak Performance with Multi-Task Proficiency on Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-java-not-installing-a-windows-fixers-manual/"><u>Addressing Java Not Installing: A Windows Fixer's Manual</u></a></li>
<li><a href="https://windows11.techidaily.com/adopting-a-black-background-on-windows-calculator/"><u>Adopting a Black Background on Windows Calculator</u></a></li>
<li><a href="https://windows11.techidaily.com/augmenting-user-interface-windows-embellished-by-portables/"><u>Augmenting User Interface: Windows, Embellished by Portables</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-spontaneous-windows-11-lockups-and-shuts/"><u>Avoid Spontaneous Windows 11 Lockups & Shuts</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-failure-of-services-on-windows-with-error-1053-fixes/"><u>Avoiding Failure of Services on Windows with Error 1053 Fixes</u></a></li>
<li><a href="https://driver-install.techidaily.com/1720062477779-bamboo-drivers-just-a-click-away/"><u>Bamboo Drivers, Just a Click Away</u></a></li>
<li><a href="https://windows11.techidaily.com/beneath-radar-outstanding-windows-11-customization/"><u>Beneath Radar: Outstanding Windows 11 Customization</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-efficiency-on-pc-best-apps-for-personalized-time-themed-screen-saver-creation/"><u>Boost Efficiency on PC: Best Apps for Personalized Time-Themed Screen Saver Creation</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-productivity-with-these-5-advanced-windows-folder-hacks/"><u>Boost Productivity with These 5 Advanced Windows Folder Hacks</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-browsing-security-enhanced-graphics-on-edge/"><u>Boosting Browsing Security: Enhanced Graphics on Edge</u></a></li>
<li><a href="https://windows11.techidaily.com/bridging-linux-and-windows-gap-with-shared-tools/"><u>Bridging Linux & Windows Gap with Shared Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-frozen-wow-post-update-phases/"><u>Bypassing Frozen WoW Post-Update Phases</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-microsofts-restrictive-security-measures/"><u>Bypassing Microsoft’s Restrictive Security Measures</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/can-i-bypass-a-forgotten-phone-password-of-poco-by-drfone-android/"><u>Can I Bypass a Forgotten Phone Password Of Poco?</u></a></li>
<li><a href="https://windows11.techidaily.com/clarity-masterclass-fixes-that-bring-life-to-fuzzy-screens/"><u>Clarity Masterclass: Fixes That Bring Life to Fuzzy Screens</u></a></li>
<li><a href="https://windows11.techidaily.com/command-line-carnival-exciting-stunts-for-your-terminal/"><u>Command Line Carnival: Exciting Stunts for Your Terminal</u></a></li>
<li><a href="https://windows11.techidaily.com/command-line-enhancement-for-taskmanager-windows-11/"><u>Command Line Enhancement for TaskManager (Windows 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-c0000005-on-windows-operating-systems/"><u>Conquering C0000005 on Windows Operating Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/control-your-machines-invisible-operations-on-window-11/"><u>Control Your Machine's Invisible Operations on Window 11</u></a></li>
<li><a href="https://windows11.techidaily.com/converting-batch-files-into-executable-formats-on-pcs/"><u>Converting Batch Files Into Executable Formats on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-dual-monitor-mishaps-on-your-pc/"><u>Correcting Dual Monitor Mishaps on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-internal-audio-issues-with-audacity-windows-11/"><u>Correcting Internal Audio Issues with Audacity (Windows 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/crucial-factors-to-evaluate-before-buying-a-windows-laptop/"><u>Crucial Factors to Evaluate Before Buying a WIndows Laptop</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-windows-layout-fancywm-power-up/"><u>Customize Windows Layout: FancyWM Power Up</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-windows-blue-screen-code-0x0000003b-breakdown-and-fixes/"><u>Deciphering Windows Blue Screen: Code 0X0000003B Breakdown & Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-and-rectifying-windows-steams-error-e84/"><u>Demystifying and Rectifying Windows Steam's Error E84</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-the-advantages-of-microsofts-copilot-key-for-windows-11/"><u>Demystifying the Advantages of Microsoft's Copilot Key for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/deploying-flask-and-socketio-for-windows-file-transfers-via-server/"><u>Deploying Flask and SocketIO for Windows File Transfers via Server</u></a></li>
<li><a href="https://windows11.techidaily.com/deploying-microsofts-ai-companion-via-vivetool/"><u>Deploying Microsoft's AI Companion via ViveTool</u></a></li>
<li><a href="https://windows11.techidaily.com/directing-biometric-access-control-for-windows-11-users/"><u>Directing Biometric Access Control for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/diving-deep-into-data-6-windows-properties-paths/"><u>Diving Deep Into Data: 6 Windows Properties Paths</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-install-the-latest-iosipados-beta-version-on-iphone-13-mini-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Install the Latest iOS/iPadOS Beta Version on iPhone 13 mini? | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-stop-life360-from-tracking-you-on-vivo-s18-drfone-by-drfone-virtual-android/"><u>How to Stop Life360 from Tracking You On Vivo S18? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-move-contacts-from-nokia-g42-5g-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Move Contacts From Nokia G42 5G to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-revolutionary-entry-points-for-zooids/"><u>In 2024, Revolutionary Entry Points for Zooids</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-the-best-apps-for-recording-and-editing-reaction-videos-on-the-go/"><u>New In 2024, The Best Apps for Recording and Editing Reaction Videos on the Go</u></a></li>
<li><a href="https://windows11.techidaily.com/1719293003975-winning-over-window-devices-no-more-naming-clashes/"><u>Winning Over Window Devices: No More Naming Clashes</u></a></li>
</ul></div>
