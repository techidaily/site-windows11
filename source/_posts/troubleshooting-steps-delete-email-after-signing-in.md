---
title: "Troubleshooting Steps: Delete Email After Signing In"
date: 2024-06-25T12:23:35.638Z
updated: 2024-06-26T12:23:35.638Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Troubleshooting Steps: Delete Email After Signing In"
excerpt: "This Article Describes Troubleshooting Steps: Delete Email After Signing In"
keywords: Delete Email Login Fix,Remove Email Sign-In Issues,Clear Email Post-Login Errors,Eliminate Email Confirmation Trouble,Unlink Email After Logging In,Disconnect Email on Access,Erase Email Linking Issue
thumbnail: https://thmb.techidaily.com/64fc45e8712465207f2977b50077b33434cfc78bbcc61824e624b36663dd238a.jpg
---

## Troubleshooting Steps: Delete Email After Signing In

 If you frequently use your computer in public places, it's a good idea to remove your email address from the Windows login screen. This means people can't get your email address if they see your screen over your shoulder.

 You can accomplish this using the Settings app, Group Policy Editor, or Registry Editor. In this post, we've covered all these methods in detail.

## 1\. How to Hide Email Address From Windows Login Screen Using the Settings App

 The Windows Settings app provides a quick way to hide account information from the login screen. So, if you are in a rush, use the following steps to remove user email addresses from the Windows login screen.

1. Press**Win + I** or use one of the[many ways to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Accounts > Sign-in options** .
3. Under**Additional settings** , toggle off the switch next to **Show account details such as my email address on the sign-in screen** .  
![Hide Email From Windows Login Screen Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-settings-app.jpg)

## 2\. How to Hide Email Address From Windows Login Screen Using the Group Policy Editor

 The Group Policy Editor (or gpedit.msc) is a handy Windows tool for configuring advanced system settings. You can also this tool to hide your email address from the Windows login screen.

 Note that the Group Policy Editor is only available on Windows Professional, Education, and Enterprise editions. If your PC is running Windows Home, check out[how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

1. Press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the search box and select the first result that appears.
3. Use the left pane to navigate to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options** .
4. Double-click the **Interactive Logon: Display user information when the session is locked** policy on your right.
5. In the properties window, click the drop-down menu to select the**Do not display user information** option.
6. Click**Apply** followed by**OK** .  
![Hide Email From Windows Login Screen Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-group-policy-editor.jpg)
7. Next, double-click on the**Interactive logon: Do not display last user name** policy from the same section.
8. Select**Enabled** in the properties window.
9. Click**Apply** followed by**OK** to save changes.

## 3\. How to Hide Email Address From Windows Login Screen Using the Registry Editor

 If the above two methods don’t work for some reason, you can make changes to the Windows registry files to hide your email address from the login screen. For that, you’ll need to use the Registry Editor on Windows.

 When it comes to editing Registry files, it's important to be cautious as making incorrect changes can cause irreversible damage to your PC. We recommend you either back up all the registry files or create a restore point before you make any changes. If you need help with that, check our guides on[how to back up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and[how to create a restore point in Windows](https://www.makeuseof.com/windows-11-create-restore-point/) .

 Once you’re done with that, use the following steps to hide your email address from the Windows login screen via Registry Editor.

1. Press**Win + X** to open the Power User menu and select**Run** from the list.
2. Type**regedit** in the text box and press**Enter** to open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft > Windows > System** .
5. Right-click on the**System** key and select**New > DWORD (32-bit) Value** .
6. Rename the DWORD to**BlockUserFromShowingAccountDetailsOnSignin** .
7. Double-click on the newly created DWORD and enter**1** in the**Value data** field. Then, click**OK** .  
![Hide Email From Windows Login Screen Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-registry-editor.jpg)

 Exit the Registry Editor and restart your PC for the changes to take effect.

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
<li><a href="https://windows11.techidaily.com/troubleshooting-errors-when-opening-sound-devices-on-audacity/"><u>Troubleshooting Errors When Opening Sound Devices on Audacity</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-how-to-stop-game-proposals/"><u>Win11: How To Stop Game Proposals</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-frustration-with-non-responsive-photoshop/"><u>Tackling Frustration with Non-Responsive Photoshop</u></a></li>
<li><a href="https://windows11.techidaily.com/accurate-assessment-of-system-resources-in-windows-11/"><u>Accurate Assessment of System Resources in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-usb-resources-on-pcs/"><u>Enhancing USB Resources on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/guaranteeing-greatness-perfecting-palette-on-your-pc/"><u>Guaranteeing Greatness: Perfecting Palette on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-high-cpu-in-your-host-system/"><u>Taming High CPU in Your Host System</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-failed-jvm-launch-windows-guide/"><u>Remedying Failed JVM Launch: Windows Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-error-code-0x8007251d-in-microsofts-os-activation/"><u>Demystifying Error Code 0X8007251d in Microsoft's OS Activation</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-posting-videos-on-instagram-easy/"><u>[New] In 2024, Posting Videos on Instagram Easy</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-youtube-shorts-ultimate-guide/"><u>In 2024, YouTube Shorts Ultimate Guide</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-transform-your-memories-video-editing-secrets-for-beginners-for-2024/"><u>Updated Transform Your Memories Video Editing Secrets for Beginners for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-transform-your-photos-best-vignette-editing-apps-for-mobile/"><u>New Transform Your Photos Best Vignette Editing Apps for Mobile</u></a></li>
<li><a href="https://howto.techidaily.com/fix-huawei-nova-y91-android-system-webview-crash-2024-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Huawei Nova Y91 Android System Webview Crash 2024 Issue | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-optimal-chuckle-inducing-layout/"><u>In 2024, Optimal Chuckle-Inducing Layout</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-mastering-media-importer-strategies-in-windows-10/"><u>2024 Approved  Mastering Media Importer Strategies in Windows 10</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-top-10-affordable-video-editing-tools-for-indie-filmmakers/"><u>2024 Approved Top 10 Affordable Video Editing Tools for Indie Filmmakers</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/tag-with-your-favorite-show-podcast-on-ig-for-2024/"><u>Tag with Your Favorite Show  Podcast on IG for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-premier-media-mover-mp4-to-fb/"><u>[Updated] Premier Media Mover  MP4-to-FB</u></a></li>
</ul></div>
