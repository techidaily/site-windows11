---
title: Identifying Programs by Their Launch Shorthand Labels
date: 2024-06-25T12:09:28.528Z
updated: 2024-06-26T12:09:28.528Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Identifying Programs by Their Launch Shorthand Labels
excerpt: This Article Describes Identifying Programs by Their Launch Shorthand Labels
keywords: ShortLabelID,LaunchShorthand,ProgramIDSearch,ShorthandProgramID,LaunchCodeMatching,IdentifyShortLabels,LabelIDIdentification
thumbnail: https://thmb.techidaily.com/227bd0353ed763348ef514468bae7b22e2b22e0109d88910437782328b50ad10.jpg
---

## Identifying Programs by Their Launch Shorthand Labels

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
<li><a href="https://windows11.techidaily.com/diminishing-high-cpu-impact-of-tiworkerexe-applications/"><u>Diminishing High CPU Impact of TiWorker.exe Applications</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-to-managing-comic-files-in-windows-11/"><u>Comprehensive Guide to Managing Comic Files in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/making-disabled-overlays-functional-again-on-windows-pc/"><u>Making Disabled Overlays Functional Again on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-folder-shuffle-showhide-system-directories/"><u>Windows 11 Folder Shuffle: Show/Hide System Directories</u></a></li>
<li><a href="https://windows11.techidaily.com/best-non-procreate-sketch-tools-for-windows-pc/"><u>Best Non-Procreate Sketch Tools for Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-connection-stability-fixed-windows-lol-issues/"><u>Mastering Connection Stability: Fixed Windows LoL Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/securely-shifting-your-streaming-application-across-hardware/"><u>Securely Shifting Your Streaming Application Across Hardware</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-tip-addressing-winscomrsvc-system-crashes/"><u>Quick Tip: Addressing WinscomrsVc System Crashes</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/brightening-a-video-doesnt-need-to-be-complicated-this-article-will-discuss-how-to-brighten-up-your-videos-easily-using-premiere-pro/"><u>Brightening a Video Doesnt Need to Be Complicated. This Article Will Discuss How to Brighten up Your Videos Easily Using Premiere Pro</u></a></li>
<li><a href="https://extra-tips.techidaily.com/craft-your-own-film-finale-templates-no-cost-for-2024/"><u>Craft Your Own Film Finale Templates, No Cost for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-deciphering-youtubes-new-earning-standards/"><u>[New] 2024 Approved  Deciphering YouTube's New Earning Standards</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-vidvibes-merge-android-and-ios-insta-photos/"><u>[New] 2024 Approved  VidVibes  Merge Android & iOS Insta Photos</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-uncovering-old-facebook-stories-with-ease/"><u>[Updated] 2024 Approved  Uncovering Old Facebook Stories with Ease</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-ultimate-non-timebound-screen-recording-selection/"><u>[New] 2024 Approved  Ultimate Non-Timebound Screen Recording Selection</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-two-ways-to-track-my-boyfriends-sony-xperia-10-v-without-him-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, Two Ways to Track My Boyfriends Sony Xperia 10 V without Him Knowing | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-reawakening-dormant-connections-with-your-obs-cam/"><u>In 2024, Reawakening Dormant Connections with Your OBS Cam</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-adding-value-with-recommendations/"><u>2024 Approved  Adding Value with Recommendations</u></a></li>
</ul></div>
