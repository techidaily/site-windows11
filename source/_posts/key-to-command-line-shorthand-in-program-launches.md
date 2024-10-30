---
title: Key to Command Line Shorthand in Program Launches
date: 2024-10-26T17:04:48.450Z
updated: 2024-10-30T16:34:23.887Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Key to Command Line Shorthand in Program Launches
excerpt: This Article Describes Key to Command Line Shorthand in Program Launches
keywords: CommandLineShortcuts,ScriptLaunchTips,TerminalEfficiency,ShellShorthandBasics,ProgramLaunchKeys,CLIAliasMastery,LaunchScriptQuickly
thumbnail: https://thmb.techidaily.com/275ca9774c095e0be2ae30797f9894bae65deae9ea5691cd95cdc33842a228b1.jpg
---

## Key to Command Line Shorthand in Program Launches

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918679/19272" target="_top" id="1918679">
  <img src="//a.impactradius-go.com/display-ad/19272-1918679" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918679/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

In Windows 10:

1. If you're using Windows 10, you'll find the aliases in**Settings > Apps & features** .
2. Click the**App execution aliases** link near the top of the Apps & features page.
3. You can then enable and disable aliases using the switches.

![app aliases in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win10.jpg)

 By default, in both Windows 10 and 11, you can only enable or disable existing app aliases. But if you don't mind editing the Registry, you can create new aliases for many other apps.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1959712/19272" target="_top" id="1959712">
  <img src="//a.impactradius-go.com/display-ad/19272-1959712" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959712/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130885/7443" target="_top" id="2130885">
  <img src="//a.impactradius-go.com/display-ad/7443-2130885" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130885/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Right-click in the right pane and select**New > String value** . Name the string**path** . The change the Value data to the same path as above, but without the app filename.

 You can now close the Registry Editor. The new App Execution Alias will now be available to use in the Windows CLIs.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139109/17108" target="_top" id="2139109">
  <img src="//a.impactradius-go.com/display-ad/17108-2139109" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139109/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://youtube-tips.techidaily.com/ed-in-2024-youtubers-ultimate-guide-10-keys-to-unique-short-form-videos/"><u>[Updated] In 2024, Youtubers' Ultimate Guide 10 Keys to Unique Short-Form Videos</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-tracing-treasure-trails-fast-friending-fundamentals/"><u>[Updated] Tracing Treasure Trails Fast Friending Fundamentals</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-focus-on-the-details-with-videoleaps-zooming-feature/"><u>2024 Approved Focus on the Details with Videoleap's Zooming Feature</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-maximizing-youtube-clicks-with-imagery/"><u>2024 Approved Maximizing YouTube Clicks with Imagery</u></a></li>
<li><a href="https://driver-download.techidaily.com/easy-access-latest-toshiba-peripherals-device-drivers-for-seamless-windows-integration/"><u>Easy Access: Latest Toshiba Peripherals' Device Drivers for Seamless Windows Integration</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-the-benefits-of-arm-based-copilotplus-computers-why-theyre-perfect-for-me/"><u>Exploring the Benefits of ARM-Based Copilot+ Computers: Why They're Perfect for Me</u></a></li>
<li><a href="https://some-techniques.techidaily.com/from-frames-to-frequencies-the-video-transformation-for-2024/"><u>From Frames to Frequencies The Video Transformation for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-enhancing-accessibility-with-vimeo-subtitles/"><u>In 2024, Enhancing Accessibility with Vimeo Subtitles</u></a></li>
<li><a href="https://windows11.techidaily.com/microsoft-successfully-addresses-persistent-problems-with-latest-windows-update-releases/"><u>Microsoft Successfully Addresses Persistent Problems with Latest Windows Update Releases</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-microsoft-edge-by-disabling-redundant-features-techniques-and-tips/"><u>Streamlining Microsoft Edge by Disabling Redundant Features - Techniques and Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/top-7-linux-qualities-deserving-a-spot-in-the-next-windows-update/"><u>Top 7 Linux Qualities Deserving a Spot in the Next Windows Update</u></a></li>
<li><a href="https://unlock-android.techidaily.com/unlocking-made-easy-the-best-10-apps-for-unlocking-your-xiaomi-device-by-drfone-android/"><u>Unlocking Made Easy The Best 10 Apps for Unlocking Your Xiaomi Device</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-lifespan-extension-continuity-and-microsoft/"><u>Windows 11, Lifespan Extension, Continuity, and Microsoft.</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-at-gaming-on-windows-11-a-step-by-step-performance-optimization-tutorial/"><u>Winning at Gaming on Windows 11: A Step-by-Step Performance Optimization Tutorial</u></a></li>
</ul></div>

