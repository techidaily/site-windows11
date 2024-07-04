---
title: Navigate Through Fingertip Writing Options in Windows System
date: 2024-06-25T12:31:24.818Z
updated: 2024-06-26T12:31:24.818Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigate Through Fingertip Writing Options in Windows System
excerpt: This Article Describes Navigate Through Fingertip Writing Options in Windows System
keywords: Fingertip Typing Windows,Touch Keyboard Windows,Windows Gesture Control,Tap Input Windows,Direct Keys Windows,Swipe Writing Windows,On-Screen Mouse Windows
thumbnail: https://thmb.techidaily.com/98351be0d04e2b45fd40ed227ba896a84193b786b4aa1a37bd43c93403b74a19.png
---

## Navigate Through Fingertip Writing Options in Windows System

 The fingertip writing feature in Windows allows users to write on a touch-enabled device using their fingertips, without a stylus or a pen. You can use it to input text directly into documents or applications easily.

 Below, we talk about the different ways to enable or disable the fingertip writing feature in the Handwriting Panel in Windows.

## 1\. Use the Settings App to Enable/Disable Fingertip Writing

 The easiest, most straightforward way to enable or disable the fingertip writing feature is by using the Settings app. You can make these changes in the Bluetooth & devices section and do not need to have administrative access to the system as well.

Here is how you can proceed:

1. Press the**Win** +**I** keys to open the Settings app.
2. Choose**Bluetooth & devices** from the left pane.
3. Move to the right side of the window and click on**Pen & Windows Ink** .  
![Access the Pen & Windows Ink section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/pen-and-windows-ink.jpg)
4. Expand the**Use your handwriting to enter text** section under Handwriting.
5. Checkmark the box associated with**Write with your fingertip** .  
![Write with your fingertip option in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/write-with-you-fingertip-1.jpg)

 You can now close the Settings app if you want. To disable the feature in the future, simply follow these steps again and uncheck the Write with your fingertip option.

## 2\. Enable/Disable Fingertip Writing via the Registry Editor

 If the "Write with your fingertip" option is disabled in the Settings app, you can also make these changes using the Registry Editor.

 Windows Registry is a powerful tool that is typically used to manage important system settings and configurations. This is an administrative-level utility, so you will need to log into your administrator account if you are using a standard user account to use it. You can also[convert your standard user account into an administrator account](https://www.makeuseof.com/windows-standard-adminstrator-account-differences/) .

 Once you have logged into Windows as an administrator,[create a Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) , just to be safe.

Then, proceed with these steps:

1. Press the**Win** +**R** keys together to open Run.
2. Type "regedit" in the text field of Run and click**Enter** .
3. Click**Yes** in the User Account Control prompt.
4. Once you have launced the Registry Editor, navigate to the location below:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\TabletTip`
5. Right-click on**TableTip** and choose**New** \>**Key** .  
![Create a new key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/create-new-key.jpg)

1. Name this key as EmbeddedInkControl.
2. Now, move to the right pane and right-click anywhere on an empty space.
3. Choose**New** \>**DWORD (32-bit) Value** .
4. Rename this key as EnableInkingWithTouch.
5. Double-click on**EnableInkingWithTouch** and under Value data, type 1\. This will enable the fingertip writing feature.  
![Enter 1 under Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enableinking-with-touch.jpg)
6. Click**OK** to save the changes.
7. Close the Registry Editor and restart your computer.

 Upon reboot, you should be able to use the fingertip writing feature. To disable this feature, follow the aforementioned steps again and change the value data of the EnableInkingWithTouch key to 0.

## 3\. Enable/Disable Fingertip Writing Via the Group Policy Editor

 The third way of enabling/disabling the fingertip writing feature is via the Group Policy Editor. Like the Windows Registry, this utility also allows the administrators to manage the advanced-level system settings in Windows.

 To use the Group Policy Editor for managing the fingertip writing feature, follow these steps:

1. Press the**Win** +**R** keys simultaneously to open Run.
2. Type "gpedit.msc" in Run and click**Enter** .
3. Click**Yes** in the User Account Control prompt.
4. Once you are in the Group Policy Editor, navigate to the location below:  
`Computer Configuration > Administrative Templates > Windows Components > Handwriting`
5. Locate the**Handwriting Panel Default Mode Docked** policy in the right pane and double-click on it.  
![Access the Handwriting panel default mode docked policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/handwriting-policy.jpg)
6. To enable the feature, choose**Not configured** . If you want to disable it, choose**Disable** .  
![Enable the handwriting panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-handwriting-panel-1.jpg)
7. Click**Apply** \>**OK** to save the changes.

 You can now close the Group Policy Editor and begin using the fingertip writing feature with ease.

## Use Your Fingertips to Write Away on Windows

 The fingertip writing feature can be a great tool for those who do not prefer using a stylus or a writing pen. You can use it to take handwritten notes and have them automatically converted into digital text which you then further organize and share.

 The three methods we have listed above should help you manage this feature easily. However, it is important to exercise caution and create a backup before you make any changes to the system settings and configurations.


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
<li><a href="https://windows11.techidaily.com/transitioning-from-iphones-calendar-to-windows-smoothly/"><u>Transitioning From iPhone's Calendar to Windows Smoothly</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-black-screens-with-simple-win11-tweaks/"><u>Resolving Black Screens with Simple Win11 Tweaks</u></a></li>
<li><a href="https://windows11.techidaily.com/securely-clearing-email-details-post-login/"><u>Securely Clearing Email Details Post-Login</u></a></li>
<li><a href="https://windows11.techidaily.com/upgrade-your-win11s-connectivity-with-these-high-priority-solutions/"><u>Upgrade Your Win11's Connectivity with These High-Priority Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/window-watchers-sticky-pad-software-reviews-8-picks/"><u>Window Watchers: Sticky Pad Software Reviews (8 Picks)</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-11-camera-app-eradicating-error-a00f425d/"><u>Troubleshooting Windows 11 Camera App: Eradicating Error A00F425D</u></a></li>
<li><a href="https://windows11.techidaily.com/legacy-unlocks-employing-a-windows-7-key-in-11-setup/"><u>Legacy Unlocks: Employing a Windows 7 Key in 11 Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/scrutinizing-underused-windows-features-for-system-checks/"><u>Scrutinizing Underused Windows Features for System Checks</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-mastering-xbox-screencast-capture-techniques-for-2024/"><u>[Updated] Mastering Xbox Screencast Capture Techniques for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-screen-sense-how-aspect-ratio-selection-impacts-viewer-experience-for-2024/"><u>New Screen Sense How Aspect Ratio Selection Impacts Viewer Experience for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/the-complete-guide-to-infinix-note-30-pro-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>The Complete Guide to Infinix Note 30 Pro FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-bringing-back-tunes-to-twitters-video-posts-for-2024/"><u>[Updated] Bringing Back Tunes to Twitter's Video Posts for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-compre-cooked-tweets-the-complete-tweet-vids-guide/"><u>[New] In 2024, Compre Cooked Tweets  The Complete Tweet Vids Guide</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/crafting-gentle-volume-declines-in-premiere-pro-videos/"><u>Crafting Gentle Volume Declines in Premiere Pro Videos</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-exploring-the-future-of-interactive-headsets/"><u>2024 Approved  Exploring the Future of Interactive Headsets</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-converting-yt-to-igtv-3-effective-methods/"><u>[Updated] Converting YT to IGTV  3 Effective Methods</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-essential-amazon-discoveries-the-hottest-tiktok-trends/"><u>In 2024, Essential Amazon Discoveries  The Hottest TikTok Trends</u></a></li>
</ul></div>
