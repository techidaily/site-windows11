---
title: Add Compatibility Tool to Windows' Quick Access
date: 2025-01-15T16:10:05.686Z
updated: 2025-01-22T18:09:25.662Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Add Compatibility Tool to Windows' Quick Access
excerpt: This Article Describes Add Compatibility Tool to Windows' Quick Access
keywords: Quick Access Tool Addon,Compatibility Enhancer,Windows QuickTool,Compatibility Update,QuikAccess Accessory,Windows EasyTool,Compatibility Windows Fix
thumbnail: https://thmb.techidaily.com/8bb1efcd08c2d3c3707b37b1d9ac64c15c4d68acde1a08c23a7f1acea10d7dc6.jpg
---

## Add Compatibility Tool to Windows' Quick Access

 There are many ways to run the Compatibility Troubleshooter, but the easiest way is to do it from the context menu by right-clicking on a program and selecting**Troubleshoot Compatibility** . However, sometimes, this option can go missing, and the good news is that you can add it back with a couple of registry tweaks. Keep on reading to find out how.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c1yHj02oP3w?si=mwi3FyP0p68gkBqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What to Do Before Tweaking the Registry Editor

 Before you go about making big changes to your Windows PC, it’s always a good idea to have some sort of backup in case things go wrong. To do that, we highly recommend reading our guide on [creating a system restore with Command Prompt](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) . If you want, you can also read our other guide on [how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) if you want to have a copy of it somewhere.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K7fATC_lI7o?si=UFotPJqflDRZr-mv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Add a "Troubleshoot Compatibility" Option to the Context Menu With the Registry Editor

 Now that you know how to keep the Windows registry safe, it's time to change it with the Registry Editor. We are going to start by adding the**Troubleshoot Compatibility** option to the context menu for EXE files. Afterward, the steps for adding it to other programs are going to be similar. To do that, follow the steps below:

1. Press**Win + R** to open the Run dialog box, enter**regedit** in the text box, and hit the**Enter** key to open the Registry Editor.
2. First, we are going to add the Troubleshoot Compatibility option for the EXE files. Start by copying and pasting the below key path in the address of the Registry Editor and hit the**Enter** key:  
HKEY_CLASSES_ROOT\cmdfile\shellEx\ContextMenuHandlers
3. Right-click the**ContextMenuHandlers** key and then select**New > Key** and name it**Compatibility** . If it is already there, move on to the next step.  
![Adding a new key to the ContextMenuHandler key for the EXE files](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/new-key-compatibility-troubleshooter-context-menu.jpg)
4. Select the**Compatibility** key, double-click**Default** on the right, and set**Value data** to**{1d27f844-3a1f-4410-85ac-14651078412d}** .  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nWu29cqFjZA?si=TNZyCbPq68PQ0JIb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Entering value data for a string value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enter-value-data.jpg)

 Next, you’re going to repeat the steps above to add the**Troubleshoot Compatibility** to the context menu of other BAT and CMD files. Just replace the key path in step two with**HKEY\_CLASSES\_ROOT\\batfile\\shellEx\\ContextMenuHandlers\\** for BAT files and**HKEY\_CLASSES\_ROOT\\cmdfile\\shellEx\\ContextMenuHandlers\\** for CMD files.

 Now when you right-click an EXE, BAT, or CMD file, you should see the**Troubleshoot Compatibility** option in the context menu.

![The Troubleshoot compatibility option in the context menu on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/troubleshoot-compatibility-context-menu.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/W5aJC8okA8s?si=L2rnYAp-gmGlLQSf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now you have one more way to [run the Program Compatibility Troubleshooter](https://www.makeuseof.com/run-program-compatibility-troubleshooter-windows/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3UyJuZYzjt0?si=W87GeyzVKVORAk7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Run the Program Compatibility Troubleshooter Easily

 The Program Compatibility Troubleshooter is one of the best ways to fix compatibility issues on Windows. If you use it often, it helps to have the tool close. With the instructions above, you can add it to and run it from the context menu, which is extremely convenient.

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
<li><a href="https://facebook-record-videos.techidaily.com/new-android-audio-archive-a-curated-list-of-top-6-free-music-downloading-apps-for-2024/"><u>[New] Android Audio Archive A Curated List of Top 6 Free Music Downloading Apps for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-qzone-elites-brief-visits-to-snapchat/"><u>[New] In 2024, Qzone Elites' Brief Visits to Snapchat</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-5-best-ps2-emulators-android/"><u>2024 Approved 5 Best PS2 Emulators Android</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-elevating-the-profile-game-top-strategies-for-compelling-social-media-profiles/"><u>2024 Approved Elevating the Profile Game Top Strategies for Compelling Social Media Profiles</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-methods-to-mirror-samsung-galaxy-f34-5g-to-roku-drfone-by-drfone-android/"><u>3 Methods to Mirror Samsung Galaxy F34 5G to Roku | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/a-short-tale-on-wintoys-unveiling-a-compelling-windows-application/"><u>A Short Tale on 'WinToys': Unveiling a Compelling Windows Application</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-windows-11s-directive-non-empty-problem-0x80070091/"><u>Clearing Up Windows 11'S Directive Non-Empty Problem #0X80070091</u></a></li>
<li><a href="https://windows11.techidaily.com/control-windows-11s-emphasis-and-search-highlight/"><u>Control Windows 11'S Emphasis and Search Highlight</u></a></li>
<li><a href="https://windows11.techidaily.com/countering-compromised-windows-defender-on-win-11/"><u>Countering Compromised Windows Defender on Win 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/decoding-powerdirectors-latest-2024-software-masterclass/"><u>Decoding PowerDirector's Latest 2024 Software Masterclass</u></a></li>
<li><a href="https://solve-marvelous.techidaily.com/global-sales-surge-by-15-in-abbyys-2018-annual-performance-official-statement/"><u>Global Sales Surge by 15% in ABBYY's 2018 Annual Performance - Official Statement</u></a></li>
</ul></div>

