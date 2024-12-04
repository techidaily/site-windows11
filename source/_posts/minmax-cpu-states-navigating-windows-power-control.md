---
title: "Min/Max CPU States: Navigating Windows Power Control"
date: 2024-11-28T21:19:06.712Z
updated: 2024-12-03T18:22:37.072Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Min/Max CPU States: Navigating Windows Power Control"
excerpt: "This Article Describes Min/Max CPU States: Navigating Windows Power Control"
keywords: CPU Min-Max States,CPU State Limits,Windows Power Ctrl,System State Management,Battery Life Optimization,Energy Saving Techniques,Performance Control Windows
thumbnail: https://thmb.techidaily.com/859749633d2fe977555173ddfc42dda3acc4bf2fd5329788d0569c467b1120f3.jpg
---

## Min/Max CPU States: Navigating Windows Power Control

 Have you ever tried to tweak the minimum and maximum processor states on your Windows PC, only to find them hidden? Or perhaps you want to hide the options to prevent others from tampering with them?

 Whichever you're trying to do, we're here to help by showing you how to add or remove them in the Power Options menu.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HtM7d4dpN1I?si=2vN_xgVGD4eYGORu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show or Hide the Minimum or Maximum Processor State Using Command Prompt

 To use Command Prompt to show or hide these power states, press**Win + R** to open Windows Run. Then, enter**cmd** in the text box and hit the**Enter** key on your keyboard. You can also use one of the many[ways to open the Command Prompt on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .

![Cmd in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/win11-cmd.jpg)

To show the minimum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR 893dee8e-2bef-41e0-89c6-b55d0929964c -ATTRIB_HIDE`

To hide the minimum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR 893dee8e-2bef-41e0-89c6-b55d0929964c +ATTRIB_HIDE`

To show the maximum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR bc5038f7-23e0-4960-96da-33abaf5935ec -ATTRIB_HIDE`

To hide the maximum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR bc5038f7-23e0-4960-96da-33abaf5935ec +ATTRIB_HIDE`

 After you have typed in the command you want in the CMD window, hit the**Enter** key on your keyboard to run it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LW6wNx3XAj8?si=VaIuFIIx8MM_RhUR" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show or Hide the Minimum or Maximum Processor State Using the Registry Editor

 You can also show or hide these options using the Registry Editor. However, before you do so, create a restore point as a backup in case you make a mistake and need to return your Windows computer to a previously-working state. Check out[how to create a restore point in Command Prompt](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) for more information.

 After creating the system restore point, press**Win + R** to open the Run dialog box. Then, enter**regedit** in the text box and hit the**Enter** key to open the Registry Editor.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XoC2TGp1PLY?si=iH9xs76NhWn4pP-E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 On the UAC prompt, click**Yes** to continue.

 To get to the key for the minimum processor state in the Registry editor, copy and paste the following file path into the Registry Editor’s address bar and hit**Enter** :

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\bc5038f7-23e0-4960-96da-33abaf5935ec`

 Right-click the**Attributes** value in the right panel and select**Modify** .

![modifying the attributes value in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-modify-attributes.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YZma8PBO0D8?si=9-qQgGVTuChYd27a" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Then, set**Value data** to**1** to hide the minimum processor state. To show it, set**Value data** to**2** .

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

 For the maximum processor state, enter the below file path in the Registry Editor's address bar to get to its key:

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\893dee8e-2bef-41e0-89c6-b55d0929964c`

 Double-click the**Attributes** entry to modify it, and then change**Value data** to**1** to hide the maximum processor state or**2** to show it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Un9G2_OdSRI?si=vAcGbco8DuWt4ypP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Add or Remove the Minimum and Maximum Processor States From Power Options

 Setting the minimum or maximum processor state on your Windows computer is vital to helping you get the performance you want from it. If you can’t see these options in the Power Options menu, you can easily reveal them with either Command Prompt or the Registry Editor. And after you’re done tweaking the states, you can hide them for their protection.

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
<li><a href="https://youtube-lab.techidaily.com/024-approved-top-online-solution-automatic-video-to-text/"><u>[New] 2024 Approved Top Online Solution Automatic Video to Text</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-speaking-through-screens-effective-communication-on-youtube-for-2024/"><u>[New] Speaking Through Screens Effective Communication on YouTube for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-understanding-luts-transforming-images-magic/"><u>[New] Understanding LUTs Transforming Images Magic</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-core-ideas-behind-online-story-crafting/"><u>2024 Approved Core Ideas Behind Online Story Crafting</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-methods-to-cut-edges-background-activity/"><u>Effective Methods to Cut Edge's Background Activity</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-microsoft-shop-errors-0x80131500/"><u>Eliminating Microsoft Shop Errors #0X80131500</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-taskbar-clarity-separate-groups-on-win-11/"><u>Enhance Taskbar Clarity: Separate Groups on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-efficiency-microsoft-adds-artificial-intelligence-to-windows-11-taskbar/"><u>Enhancing Efficiency: Microsoft Adds Artificial Intelligence to Windows 11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-note-visibility-with-windows-tools/"><u>Enhancing Note Visibility with Windows Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-performance-with-virtual-memory-on-windows-11/"><u>Enhancing Performance with Virtual Memory on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-wi-fi-setup-accuracy-ensuring-complete-actions/"><u>Enhancing Wi-Fi Setup Accuracy: Ensuring Complete Actions</u></a></li>
<li><a href="https://windows11.techidaily.com/epic-launcher-insights-best-practices-for-saving-your-playtime/"><u>Epic Launcher Insights: Best Practices for Saving Your Playtime</u></a></li>
<li><a href="https://tech-revival.techidaily.com/kostenlose-video-downloads-aus-twitter-fur-pcs-iphones-and-android-gerate-einfache-anleitung/"><u>Kostenlose Video-Downloads Aus Twitter Für PCs, iPhones & Android Geräte – Einfache Anleitung</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/record-your-favorite-moments-8-methods-to-capture-tiktok-videos-using-various-devices-with-ease/"><u>Record Your Favorite Moments: 8 Methods to Capture TikTok Videos Using Various Devices with Ease</u></a></li>
<li><a href="https://sound-issues.techidaily.com/reviving-audio-on-your-pc-expert-tips-to-address-conexant-smartaudio-hds-sound-problem-in-windows-10/"><u>Reviving Audio on Your PC: Expert Tips to Address Conexant SmartAudio HD's Sound Problem in Windows 10</u></a></li>
<li><a href="https://some-approaches.techidaily.com/top-rated-mp4-codec-tools-for-flawless-hd-video-conversion/"><u>Top Rated MP4 Codec Tools for Flawless HD Video Conversion</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/unlocking-the-secrets-of-high-quality-twitch-broadcasts/"><u>Unlocking the Secrets of High-Quality Twitch Broadcasts</u></a></li>
</ul></div>

