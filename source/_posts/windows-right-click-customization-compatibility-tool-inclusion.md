---
title: "Windows Right-Click Customization: Compatibility Tool Inclusion"
date: 2025-02-23T21:37:40.758Z
updated: 2025-03-02T11:34:14.160Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows Right-Click Customization: Compatibility Tool Inclusion"
excerpt: "This Article Describes Windows Right-Click Customization: Compatibility Tool Inclusion"
keywords: Windows RClick,Customize Click,Right-Click Change,Tool for Windows,Compatibility Fix,Custom Tools Include,Right Click Update
thumbnail: https://thmb.techidaily.com/69a1f779573ffb1d9703aa1f0c2a82407b77bc35052e19faef90f3eeabcd3dc4.jpg
---

## Windows Right-Click Customization: Compatibility Tool Inclusion

 There are many ways to run the Compatibility Troubleshooter, but the easiest way is to do it from the context menu by right-clicking on a program and selecting**Troubleshoot Compatibility** . However, sometimes, this option can go missing, and the good news is that you can add it back with a couple of registry tweaks. Keep on reading to find out how.

## What to Do Before Tweaking the Registry Editor

 Before you go about making big changes to your Windows PC, it’s always a good idea to have some sort of backup in case things go wrong. To do that, we highly recommend reading our guide on [creating a system restore with Command Prompt](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) . If you want, you can also read our other guide on [how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) if you want to have a copy of it somewhere.

## How to Add a "Troubleshoot Compatibility" Option to the Context Menu With the Registry Editor

 Now that you know how to keep the Windows registry safe, it's time to change it with the Registry Editor. We are going to start by adding the**Troubleshoot Compatibility** option to the context menu for EXE files. Afterward, the steps for adding it to other programs are going to be similar. To do that, follow the steps below:

1. Press**Win + R** to open the Run dialog box, enter**regedit** in the text box, and hit the**Enter** key to open the Registry Editor.
2. First, we are going to add the Troubleshoot Compatibility option for the EXE files. Start by copying and pasting the below key path in the address of the Registry Editor and hit the**Enter** key:  
HKEY_CLASSES_ROOT\cmdfile\shellEx\ContextMenuHandlers
3. Right-click the**ContextMenuHandlers** key and then select**New > Key** and name it**Compatibility** . If it is already there, move on to the next step.  
![Adding a new key to the ContextMenuHandler key for the EXE files](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/new-key-compatibility-troubleshooter-context-menu.jpg)
4. Select the**Compatibility** key, double-click**Default** on the right, and set**Value data** to**{1d27f844-3a1f-4410-85ac-14651078412d}** .  
![Entering value data for a string value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enter-value-data.jpg)

 Next, you’re going to repeat the steps above to add the**Troubleshoot Compatibility** to the context menu of other BAT and CMD files. Just replace the key path in step two with**HKEY\_CLASSES\_ROOT\\batfile\\shellEx\\ContextMenuHandlers\\** for BAT files and**HKEY\_CLASSES\_ROOT\\cmdfile\\shellEx\\ContextMenuHandlers\\** for CMD files.

 Now when you right-click an EXE, BAT, or CMD file, you should see the**Troubleshoot Compatibility** option in the context menu.

![The Troubleshoot compatibility option in the context menu on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/troubleshoot-compatibility-context-menu.jpg)

 Now you have one more way to [run the Program Compatibility Troubleshooter](https://www.makeuseof.com/run-program-compatibility-troubleshooter-windows/) .

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
<li><a href="https://article-knowledge.techidaily.com/new-boosting-productivity-with-innovative-win11-features-for-2024/"><u>[New] Boosting Productivity with Innovative Win11 Features for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-tailoring-audio-how-to-download-and-customize-whatsapp-tones-on-devices/"><u>[New] Tailoring Audio How to Download & Customize WhatsApp Tones on Devices</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-resolving-face-swap-glitches-in-facebook-chat-for-2024/"><u>[Updated] Resolving Face Swap Glitches in Facebook Chat for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-boosting-engagement-interactive-features-of-zoom-on-win11-pcs/"><u>2024 Approved Boosting Engagement Interactive Features of Zoom on Win11 PCs</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-expert-tips-for-dealing-with-youtube-copyright-notifications/"><u>2024 Approved Expert Tips for Dealing With YouTube Copyright Notifications</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/diy-tricks-easily-hook-up-3-screens-to-your-laptop-or-desktop/"><u>DIY Tricks: Easily Hook Up 3 Screens to Your Laptop or Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-solutions-for-win10win11-stuck-with-pin-lock/"><u>Immediate Solutions for Win10/Win11 Stuck with PIN Lock</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-huawei-nova-y91-drfone-by-drfone-virtual-android/"><u>In 2024, 15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Huawei Nova Y91 | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unlocking-creative-potential-a-compreeved-guide-to-appending-text-in-photos-on-pc-and-mac/"><u>In 2024, Unlocking Creative Potential A Compreeved Guide to Appending Text in Photos on PC & Mac</u></a></li>
<li><a href="https://hardware-help.techidaily.com/navigating-the-latest-nvidia-geforce-210-driver-version-for-enhanced-compatibility-with-windows-11/"><u>Navigating the Latest NVIDIA GeForce 210 Driver Version for Enhanced Compatibility with Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11-moving-vintage-games-into-picture-storage/"><u>Navigating Windows 11: Moving Vintage Games Into Picture Storage</u></a></li>
<li><a href="https://windows11.techidaily.com/rejuvenating-windows-a-comprehensive-guide-of-13-tips/"><u>Rejuvenating Windows: A Comprehensive Guide of 13 Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-to-avoid-frustrating-steam-audio-drops/"><u>Tips to Avoid Frustrating Steam Audio Drops</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-setup-via-vmware-workstation-17-a-step-by-step-guide/"><u>Win11 Setup via VMware Workstation 17: A Step-by-Step Guide</u></a></li>
</ul></div>

