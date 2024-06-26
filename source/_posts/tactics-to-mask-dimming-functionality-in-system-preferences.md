---
title: Tactics to Mask Dimming Functionality in System Preferences
date: 2024-06-25T12:38:58.415Z
updated: 2024-06-26T12:38:58.415Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tactics to Mask Dimming Functionality in System Preferences
excerpt: This Article Describes Tactics to Mask Dimming Functionality in System Preferences
keywords: Hide Dimming on macOS,Stealthy System Brightness Adjustment,Concealing Screen Brightness Change,Secret Brightness Tweak in Settings,Dimming Function Obfuscation,Masking Screen Adjustments,Preferences Privacy for Dim Control
thumbnail: https://thmb.techidaily.com/35cdbcc9d0463edeaedcfabc37b755463ffdb3615e7f86b0660ca31e9acd1987.jpg
---

## Tactics to Mask Dimming Functionality in System Preferences

 There are times when you need to step away from your PC, and if you’re gone long enough, the screen will automatically dim. Windows does this to preserve your battery, and you can adjust when your display should darken in the Power Options menu by editing the **Dim display after** option.

 If for some reason you can’t see the **Dim display after** option in the Power Options menu, or it’s there and you want to remove it, you can use PowerShell or the Registry Editor to show or hide it. Here’s how.

## How to Show or Hide the “Dim Display After” Option Using PowerShell

 First, launch Windows PowerShell. There are many [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/), but the easiest method is to press **Win + S** to open Windows Search. Then, enter **powershell** in the search box and click on **Windows PowerShell** when it appears in the search results.

![windows powershell in the windows search results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/windows-powershell-search.jpg)

 In PowerShell, enter the following command to show the **Dim Display after** option in the Power Options menu:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee -ATTRIB_HIDE

 To hide it, enter the following command:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee +ATTRIB_HIDE

 After entering the command you want, hit the **Enter** key on your keyboard for PowerShell to execute it. Afterward, the **Dim display after** option should appear or disappear accordingly in the Power Options menu.

## How to Show or Hide the “Dim display after” Option Using the Registry Editor

 Considering how vital the [Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is for the smooth operation of Windows, you might want to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you edit it. Afterward, open the Registry Editor by pressing **Win + R**, typing **regedit** in the text box, and clicking **OK**.

![regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/regedit.jpg)

 Click **Yes** to bypass the UAC prompt.

 In the address bar of the Registry Editor, copy and paste the following text into it:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\7516b95f-f776-4464-8c53-06167f40cc99\17aaa29b-8b43-4b94-aafe-35f64daaf1ee

 On the right panel, double-click the **Attributes** entry to open it up for editing.

![the attributes entry in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-dim-display-after-attributes-entry.jpg)

 Then, in the **Value data** text box, enter **1** to hide **Dim display after** in the Power Options menu or **2** to show it.

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

 Now you can open the Power Options menu (see [how to open the power options on Windows 10](https://www.makeuseof.com/windows-10-open-power-options/)) and check under **Display** to see if the **Dim display after** option is there or not.

## Controlling the “Dim Display After” Option in the Power Options Menu

 Now that you know how to show or hide **Dim display after**, you know what to do when you can’t find it in the Power Options menu or need to remove it. We recommend keeping it hidden and then bringing it up whenever you need it. This will make sure that no one messes with this important display setting when you’ve set it up perfectly.

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
<li><a href="https://windows11.techidaily.com/tackling-common-errors-during-windows-11-system-rollout/"><u>Tackling Common Errors During Windows 11 System Rollout</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-start-up-sequence-of-windows-os/"><u>Decoding the Start-Up Sequence of Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-change-the-task-manager-start-page-in-windows-11/"><u>How to Change the Task Manager Start Page in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-making-intellij-unison-function-in-win11/"><u>Quick Fixes: Making IntelliJ Unison Function in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/matchmaking-the-ideal-nvidia-driver-with-entertainment-goals/"><u>Matchmaking The Ideal Nvidia Driver With Entertainment Goals</u></a></li>
<li><a href="https://windows11.techidaily.com/quickfix-sniping-tool-problems-top-tips-revealed/"><u>QuickFix Sniping Tool Problems: Top Tips Revealed</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-differences-of-fix-focused-tools-dism-sfc-and-chkdsk/"><u>Understanding Differences of Fix-Focused Tools: DISM, SFC & CHKDSK</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-complete-haul-video-manual-from-shopping-to-screen-time/"><u>In 2024, The Complete Haul Video Manual  From Shopping to Screen Time</u></a></li>
<li><a href="https://audio-editing.techidaily.com/in-2024-behind-the-screens-the-leading-bgm-audio-selections/"><u>In 2024, Behind the Screens The Leading BGM Audio Selections</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/a-guide-infinix-note-30-5g-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>A Guide Infinix Note 30 5G Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://article-posts.techidaily.com/in-2024-go-beyond-basic-top-10-hidden-whatsapp-features/"><u>In 2024, Go Beyond Basic  Top 10 Hidden WhatsApp Features</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-revenue-riches-masterful-methods-for-monetizing-on-mobile-youtube/"><u>In 2024, Revenue Riches  Masterful Methods for Monetizing on Mobile YouTube</u></a></li>
<li><a href="https://extra-resources.techidaily.com/determining-your-promotion-budget-on-youtube/"><u>Determining Your Promotion Budget on YouTube</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-smart-shopping-for-cloud-storages-best-price-secrets-revealed/"><u>[Updated] Smart Shopping for Cloud Storages  Best Price Secrets Revealed</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/2024-approved-pc-video-editing-made-easy-gopro-quik-and-its-alternatives/"><u>2024 Approved PC Video Editing Made Easy GoPro Quik and Its Alternatives</u></a></li>
</ul></div>
