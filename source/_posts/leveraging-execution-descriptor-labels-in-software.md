---
title: Leveraging Execution Descriptor Labels in Software
date: 2024-06-25T12:26:48.034Z
updated: 2024-06-26T12:26:48.034Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Leveraging Execution Descriptor Labels in Software
excerpt: This Article Describes Leveraging Execution Descriptor Labels in Software
keywords: Exec Desc Labeling,Software SDL Efficiency,Label-Driven Dev Enhance,Improve Code Maintenance,Label Optimization Software,ExecDesk Acceleration Tech,SDL Application Advance
thumbnail: https://thmb.techidaily.com/888d11958fd59cee20dd0880994e49d2be75696460e14e09acd5a7ef9a37fabd.jpg
---

## Leveraging Execution Descriptor Labels in Software

 If you're trying to open an app like Microsoft Paint in the Run Dialog and see an error message, it could be caused by your app aliases. But what exactly are App Execution Aliases, where do you find them, and how do you use them?

## What Are App Execution Aliases?

 An alias is an alternative name given to something. The most obvious example is the codename given to a spy or undercover agent. On Windows, aliases have nothing to do with spying. Instead, they are used for streamlining tasks, such as entering commands.

 Windows 10 and 11 both allow aliases to be declared for some apps by default. The available apps vary but are often those commonly associated with command line tools. Giving an app an alias allows it to be executed using a shorter title rather than the full name or path.

 App aliases can be used in several[Windows Command Line Interfaces](https://www.makeuseof.com/what-is-cli-what-does-it-stand-for/) (CLI), including the Run Dialog, Command Prompt, and[PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) . If you use these tools with any regularity, app aliases can help to streamline entering commands.

## How to Enable App Execution Aliases in Settings

 You can enable and disable aliases for compatible apps in the main settings in both Windows 10 and 11\. If more than one app uses the same alias name, you can choose which has the alias applied to it.

In Windows 11:

1. Open**Settings > Apps** , and look for**Advanced app settings** .
2. In the advanced app settings, click**App execution aliases** to see the list of compatible apps.
3. Use the slider switches to enable or disable the alias for each app. You can see the alias name below each app.

![app aliases in windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win11.jpg)

In Windows 10:

1. If you're using Windows 10, you'll find the aliases in**Settings > Apps & features** .
2. Click the**App execution aliases** link near the top of the Apps & features page.
3. You can then enable and disable aliases using the switches.

![app aliases in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win10.jpg)

 By default, in both Windows 10 and 11, you can only enable or disable existing app aliases. But if you don't mind editing the Registry, you can create new aliases for many other apps.

## Create App Execution Aliases in Registry Editor

 Before editing or creating registry keys, it is advisable to[create a full backup of the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . Of course, you should also ensure you understand how to restore the Registry from that backup.

 The process below for creating app execution aliases in the Registry Editor should be the same in both Windows 10 and 11.

1. Open**Windows Search** , type**Registry Editor** , and click on the search result to open it.
2. In the editor, navigate to **HKEY\_CURRENT\_USER\\Software\\Microsoft\\Windows\\CurrentVersion\\App Paths** .
3. Next, right-click on the**App Paths** key in the left-hand pane, and select**New > Key** .
4. Give the new key an alias name that relates to the app and ends with .exe. For example, if the alias is for Calendar, call it something like cal.exe.
5. With the alias selected, double-click the**Default** value in the right-hand pane.  
![editing app aliases in registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-regedit.jpg)
6. In the Value data field, you will need to enter the full path to the app executable file. For example**C:\\Program Files (x86)\\Calendar.exe** .
7. Right-click in the right pane and select**New > String value** . Name the string**path** . The change the Value data to the same path as above, but without the app filename.

 You can now close the Registry Editor. The new App Execution Alias will now be available to use in the Windows CLIs.

## Using and Creating App Execution Aliases

 Entering commands into tools such as Command Prompt and PowerShell can be laborious. You can streamline that process by enabling or creating aliases for apps that commonly feature in those commands. Why type out a full path to an executable file when you can point to it with a few keystrokes?


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
<li><a href="https://windows11.techidaily.com/hidden-windows-11-theme-treasures-revealed/"><u>Hidden Windows 11 Theme Treasures Revealed</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-visuals-how-to-fix-an-invisible-login-window-in-win1011/"><u>Restoring Visuals: How to Fix an Invisible Login Window in WIN10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-windows-crash-0x800f0831-solution/"><u>Mastery Over Windows Crash: 0X800f0831 Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/unbroken-streams-winos-stability-verification-guide/"><u>Unbroken Streams: WinOS Stability Verification Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/strip-windows-11-of-the-store-application/"><u>Strip Windows 11 of the Store Application</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-stop-the-mouse-from-freezing-in-excel/"><u>How to Stop the Mouse From Freezing in Excel</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-error-0x00000709-in-windows/"><u>Addressing Error 0X00000709 in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-file-error-puzzle-finding-solution-for-0x80070570-on-windows-11/"><u>Decoding the File Error Puzzle - Finding Solution for 0X80070570 on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-address-geforce-nows-error-code-xc0f1103f/"><u>How To Address GeForce Now's Error Code Xc0f1103f</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-tackling-windows-11-logins/"><u>Essential Guide: Tackling Windows 11 Logins</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-discovering-realistic-insectoid-noise-samples/"><u>In 2024, Discovering Realistic Insectoid Noise Samples</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/whats-next-after-virtualdub-a-review-of-the-top-video-editing-alternatives-for-2024/"><u>Whats Next After Virtualdub? A Review of the Top Video Editing Alternatives for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-fashion-filming-simplified-for-macos-users/"><u>[New] In 2024, Fashion Filming Simplified for MacOS Users</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-my-spouse-from-spying-on-my-tecno-camon-20-drfone-by-drfone-virtual-android/"><u>How to Stop My Spouse from Spying on My Tecno Camon 20 | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/elevating-ad-effectiveness-for-youtube-for-2024/"><u>Elevating Ad Effectiveness for YouTube for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-revamping-screen-recording-a-critical-look-at-camstudios-new-features/"><u>[New] Revamping Screen Recording - A Critical Look at CamStudio's New Features</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-2-ways-to-fade-in-text-in-premiere-pro/"><u>2024 Approved 2 Ways to Fade in Text in Premiere Pro</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-warriors-pantheon-valhalla-rebirth-for-2024/"><u>[Updated] Warriors' Pantheon  Valhalla Rebirth for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-explore-best-asmr-apps-both-sides-of-the-os/"><u>[Updated] In 2024, Explore Best ASMR Apps, Both Sides of the OS</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-your-realme-10t-5g-location-on-twitter-drfone-by-drfone-virtual-android/"><u>How to Change your Realme 10T 5G Location on Twitter | Dr.fone</u></a></li>
</ul></div>
