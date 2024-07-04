---
title: A Step-By-Step for Erasing Sign-In Email in Win
date: 2024-06-25T12:02:42.310Z
updated: 2024-06-26T12:02:42.310Z
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
<li><a href="https://windows11.techidaily.com/troubleshooting-deactivated-sliders-for-volume-control/"><u>Troubleshooting Deactivated Sliders for Volume Control</u></a></li>
<li><a href="https://windows11.techidaily.com/best-practices-for-avoidable-file-explorer-foibles/"><u>Best Practices for Avoidable File Explorer Foibles</u></a></li>
<li><a href="https://windows11.techidaily.com/saving-screen-time-by-hushing-file-explorer-tabs/"><u>Saving Screen Time by Hushing File Explorer Tabs</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-recurrent-enter-to-bios-in-windows-boot-cycle/"><u>Overcoming Recurrent Enter To BIOS in Windows Boot Cycle</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-for-correcting-windows-update-problems-0x30017/"><u>Expert Tips for Correcting Windows Update Problems (0X30017)</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-office-suites-strict-safe-mode-on-windows-operations/"><u>Troubleshooting Office Suite's Strict Safe Mode on Windows Operations</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-windows-activate-derailed-handbrake/"><u>Conquer Windows: Activate Derailed HandBrake</u></a></li>
<li><a href="https://windows11.techidaily.com/black-friday-extravaganza-save-big-612-forever-win10/"><u>Black Friday Extravaganza: Save Big - $6.12 Forever Win10</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-audiovisual-harmony-merging-audio-and-visual-elements-on-youtube-for-2024/"><u>[New] Audiovisual Harmony  Merging Audio and Visual Elements on YouTube for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-unlocking-viral-potential-through-strategic-fb-videos-for-2024/"><u>[Updated] Unlocking Viral Potential Through Strategic FB Videos for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/navigating-the-zoom-interface-a-focus-on-windows-10/"><u>Navigating the Zoom Interface  A Focus on Windows 10</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/from-frantic-movements-to-leisurely-views-crafting-spectacular-slow-motion-videos-for-instragram-for-2024/"><u>From Frantic Movements to Leisurely Views  Crafting Spectacular Slow Motion Videos for Instragram for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-in-2024-resonant-praise-sound-composer/"><u>New In 2024, Resonant Praise Sound Composer</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-become-a-color-grading-pro-utilizing-luts-within-adobes-suite/"><u>[New] Become a Color Grading Pro  Utilizing LUTs Within Adobe's Suite</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-infinix-smart-8-plus-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Infinix Smart 8 Plus without Losing Data | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/the-ultimate-tutorial-blocking-youtube-ads-on-all-platforms-for-2024/"><u>The Ultimate Tutorial  Blocking YouTube Ads on All Platforms for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-transform-videos-into-stunning-live-photos-with-these-top-apps/"><u>New Transform Videos Into Stunning Live Photos with These Top Apps</u></a></li>
</ul></div>
