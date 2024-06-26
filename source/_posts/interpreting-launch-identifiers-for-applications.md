---
title: Interpreting Launch Identifiers for Applications
date: 2024-06-25T11:57:37.057Z
updated: 2024-06-26T11:57:37.057Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Interpreting Launch Identifiers for Applications
excerpt: This Article Describes Interpreting Launch Identifiers for Applications
keywords: Launch ID Explained,App Identifier Meaning,Launch Significance,Understanding Launch Codes,Launch Keyword Guide,Decoding Launch Symbols,App Launch Reference
thumbnail: https://thmb.techidaily.com/23dc4857279699198e48a622a7713386fd30f7f47908caf6a0fe50229057f885.jpg
---

## Interpreting Launch Identifiers for Applications

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
<li><a href="https://windows11.techidaily.com/win11s-guide-to-stable-background-fixes/"><u>Win11's Guide to Stable Background Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-the-setup-of-new-non-operational-store-programs/"><u>Streamlining the Setup of New, Non-Operational Store Programs</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-restart-and-streamline-windows-update-processes/"><u>How to Restart and Streamline Windows Update Processes</u></a></li>
<li><a href="https://windows11.techidaily.com/uncharted-territory-innovations-to-windows-11s-explorer-interface/"><u>Uncharted Territory: Innovations to Windows 11'S Explorer Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-regain-control-over-non-responsive-overlays/"><u>Strategies to Regain Control over Non-Responsive Overlays</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-your-console-dreams-choose-windows-for-games/"><u>Unlocking Your Console Dreams: Choose Windows for Games</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprerant-users-resourceful-approach-to-processes-and-themes-in-windows-11/"><u>A Compreran't User's Resourceful Approach to Processes and Themes in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-app-crashes-in-windows-dealing-with-unhandled-exceptions/"><u>Overcoming App Crashes in Windows: Dealing with Unhandled Exceptions</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-exit-point-not-found-errors/"><u>Clearing Up Exit Point Not Found Errors</u></a></li>
<li><a href="https://techidaily.com/three-solutions-to-hard-reset-realme-gt-neo-5-drfone-by-drfone-reset-android-reset-android/"><u>Three Solutions to Hard Reset Realme GT Neo 5? | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-recordingratings-analyzer/"><u>2024 Approved  RecordingRatings Analyzer</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-comprehensible-guide-to-azure-voice-to-text/"><u>In 2024, Comprehensible Guide to Azure Voice to Text</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-navigating-the-nuances-of-social-cues-status-update/"><u>[New] In 2024, Navigating the Nuances of Social Cues  Status Update</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-navigating-overwatch-audio-capture-settings/"><u>In 2024, Navigating Overwatch Audio Capture Settings</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/become-an-elite-joiner-tips-for-tiktok-lives-for-2024/"><u>Become an Elite Joiner  Tips for TikTok Lives for 2024</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-can-we-bypass-oppo-reno-11f-5g-frp-by-drfone-android/"><u>In 2024, How Can We Bypass Oppo Reno 11F 5G FRP?</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-top-choices-for-unconventional-peer-to-peer-dialogue-platforms-safety-efficiency-pleasure-for-2024/"><u>New Top Choices for Unconventional Peer-to-Peer Dialogue Platforms Safety, Efficiency, Pleasure for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-the-ultimate-guide-to-macs-image-file-transformation-for-2024/"><u>[Updated] The Ultimate Guide to Mac's Image File Transformation for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-elevate-your-content-top-reasons-and-solutions-for-gaining-video-views/"><u>[New] 2024 Approved  Elevate Your Content  Top Reasons and Solutions for Gaining Video Views</u></a></li>
</ul></div>
