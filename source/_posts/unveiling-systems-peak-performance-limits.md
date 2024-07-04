---
title: Unveiling System's Peak Performance Limits
date: 2024-06-25T11:58:07.112Z
updated: 2024-06-26T11:58:07.112Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unveiling System's Peak Performance Limits
excerpt: This Article Describes Unveiling System's Peak Performance Limits
keywords: Peak Performance Analysis,Max Performance Boundaries,System Optimization Thresholds,Efficiency Growth Points,Operational Limit Exploration,Productivity Cap Assessment,Output Maximization Study
thumbnail: https://thmb.techidaily.com/b291d1186c17a0e27af028a28ffb312d4304bf88d64275a707a4eb2f0cc766f8.jpg
---

## Unveiling System's Peak Performance Limits

 Have you ever tried to tweak the minimum and maximum processor states on your Windows PC, only to find them hidden? Or perhaps you want to hide the options to prevent others from tampering with them?

 Whichever you're trying to do, we're here to help by showing you how to add or remove them in the Power Options menu.

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

## How to Show or Hide the Minimum or Maximum Processor State Using the Registry Editor

 You can also show or hide these options using the Registry Editor. However, before you do so, create a restore point as a backup in case you make a mistake and need to return your Windows computer to a previously-working state. Check out[how to create a restore point in Command Prompt](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) for more information.

 After creating the system restore point, press**Win + R** to open the Run dialog box. Then, enter**regedit** in the text box and hit the**Enter** key to open the Registry Editor.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

 On the UAC prompt, click**Yes** to continue.

 To get to the key for the minimum processor state in the Registry editor, copy and paste the following file path into the Registry Editor’s address bar and hit**Enter** :

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\bc5038f7-23e0-4960-96da-33abaf5935ec`

 Right-click the**Attributes** value in the right panel and select**Modify** .

![modifying the attributes value in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-modify-attributes.jpg)

 Then, set**Value data** to**1** to hide the minimum processor state. To show it, set**Value data** to**2** .

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

 For the maximum processor state, enter the below file path in the Registry Editor's address bar to get to its key:

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\893dee8e-2bef-41e0-89c6-b55d0929964c`

 Double-click the**Attributes** entry to modify it, and then change**Value data** to**1** to hide the maximum processor state or**2** to show it.

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
<li><a href="https://windows11.techidaily.com/navigating-through-user-not-valid-windows-1111-errors/"><u>Navigating Through 'User Not Valid' Windows 11/11 Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-troubleshooting-for-winscombsvc-error/"><u>Essential Troubleshooting for WinScombSvc Error</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-frozen-pages-and-scrolling-issues-in-excel/"><u>Stop Frozen Pages and Scrolling Issues in Excel</u></a></li>
<li><a href="https://windows11.techidaily.com/an-insight-into-windows-audio-channel-separation/"><u>An Insight Into Windows' Audio Channel Separation</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-unlock-windows-credentials-management/"><u>Steps to Unlock Windows Credentials Management</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-caption-troubleshooting-made-simple/"><u>Win11 Caption Troubleshooting Made Simple</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-the-nullzero-error-fixes-for-new-users-on-win11/"><u>Stop the Null/Zero Error: Fixes for New Users on Win11</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-ultimate-picture-editor-tutorial/"><u>In 2024, The Ultimate Picture Editor Tutorial</u></a></li>
<li><a href="https://techidaily.com/vivo-v27e-support-forgotten-screen-lock-by-drfone-android-unlock-android-unlock/"><u>Vivo V27e support - Forgotten screen lock.</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-unraveling-the-mystery-of-individual-tiktok-tags/"><u>[Updated] 2024 Approved  Unraveling the Mystery of Individual TikTok Tags</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-cinematic-clarity-premium-handheld-stabilizers-selection/"><u>[Updated] Cinematic Clarity  Premium Handheld Stabilizers Selection</u></a></li>
<li><a href="https://extra-information.techidaily.com/mastering-undersea-video-7-easy-to-follow-techniques/"><u>Mastering Undersea Video  7 Easy-to-Follow Techniques</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-bridging-images-and-words-step-by-step-text-integration-guide/"><u>2024 Approved  Bridging Images & Words  Step-by-Step Text Integration Guide</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-a-perfect-guide-to-remove-or-disable-google-smart-lock-on-xiaomi-redmi-12-by-drfone-android/"><u>In 2024, A Perfect Guide To Remove or Disable Google Smart Lock On Xiaomi Redmi 12</u></a></li>
<li><a href="https://discord-videos.techidaily.com/pinnacle-non-discord-communities-online/"><u>Pinnacle Non-Discord Communities Online</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/unveiling-the-secret-sauce-for-astonishing-gifs-from-vimeo-videos-for-2024/"><u>Unveiling the Secret Sauce for Astonishing GIFs From Vimeo Videos for 2024</u></a></li>
</ul></div>
