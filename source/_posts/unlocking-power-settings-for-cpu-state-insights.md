---
title: Unlocking Power Settings for CPU State Insights
date: 2024-06-25T12:29:07.045Z
updated: 2024-06-26T12:29:07.045Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unlocking Power Settings for CPU State Insights
excerpt: This Article Describes Unlocking Power Settings for CPU State Insights
keywords: CPU Performance Tuning,Advanced CPU States,Energy Efficient CPUs,Power Management Techniques,CPU Insight Analysis,Temperature Control Systems,Optimize CPU State
thumbnail: https://thmb.techidaily.com/65fba9a952c6564fd879ce858daef732be8f2531c9874f65aafa43e482841322.jpg
---

## Unlocking Power Settings for CPU State Insights

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
<li><a href="https://windows11.techidaily.com/mastery-of-internet-options-tweaks-for-windows-11/"><u>Mastery of Internet Options Tweaks for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/altering-winterrals-visual-theme/"><u>Altering WinTerral's Visual Theme</u></a></li>
<li><a href="https://windows11.techidaily.com/backtracking-your-pc-with-ease-using-system-restore/"><u>Backtracking Your PC with Ease Using System Restore</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-offline-status-of-valve-games-via-steam-desktop-client/"><u>Addressing Offline Status of Valve Games via Steam Desktop Client</u></a></li>
<li><a href="https://windows11.techidaily.com/controlling-winoss-priority-setting-for-hardware-acceleration/"><u>Controlling WinOS's Priority Setting for Hardware Acceleration</u></a></li>
<li><a href="https://windows11.techidaily.com/low-ram-footprint-webbrowsers-an-intensive-benchmark-analysis/"><u>Low RAM Footprint Webbrowsers: An Intensive Benchmark Analysis</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-to-open-adobe-ps-in-w11-after-updates/"><u>Step-by-Step to Open Adobe PS in W11 After Updates</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/disable-screen-lock-on-honor-90-pro-by-drfone-android-unlock-android-unlock/"><u>Disable screen lock on Honor 90 Pro</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-unveiling-the-best-screen-recording-experience-on-windows/"><u>In 2024, Unveiling the Best Screen Recording Experience on Windows</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/ipad-video-editing-made-easy-top-5-apps/"><u>IPad Video Editing Made Easy Top 5 Apps</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-vivo-y17s-to-samsung-galaxy-s21-ultra-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos From Vivo Y17s to Samsung Galaxy S21 Ultra | Dr.fone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-essential-steps-for-chromakey-magic/"><u>[Updated] In 2024, Essential Steps for Chromakey Magic</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-perfect-pictures-quick-pixlr-tricks-for-beginners/"><u>In 2024, Perfect Pictures  Quick Pixlr Tricks for Beginners</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-frp-on-xiaomi-redmi-12-by-drfone-android/"><u>How to Bypass FRP on Xiaomi Redmi 12?</u></a></li>
<li><a href="https://howto.techidaily.com/11-ways-to-fix-it-when-my-xiaomi-redmi-k70-pro-wont-charge-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Ways to Fix it When My Xiaomi Redmi K70 Pro Wont Charge | Dr.fone</u></a></li>
</ul></div>
