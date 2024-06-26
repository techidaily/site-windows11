---
title: "Windows Right-Click Customization: Compatibility Tool Inclusion"
date: 2024-06-25T12:38:14.851Z
updated: 2024-06-26T12:38:14.851Z
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

 Before you go about making big changes to your Windows PC, it’s always a good idea to have some sort of backup in case things go wrong. To do that, we highly recommend reading our guide on[creating a system restore with Command Prompt](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) . If you want, you can also read our other guide on[how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) if you want to have a copy of it somewhere.

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

 Now you have one more way to[run the Program Compatibility Troubleshooter](https://www.makeuseof.com/run-program-compatibility-troubleshooter-windows/) .

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
<li><a href="https://windows11.techidaily.com/windows-11-user-mastery-group-and-admin-essentials-guide/"><u>Windows 11 User Mastery: Group & Admin Essentials Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-your-windows-11-journey-top-6-multitasking-android-apps/"><u>Enhancing Your Windows 11 Journey: Top 6 Multitasking Android Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-user-not-valid-windows-1111-errors/"><u>Navigating Through 'User Not Valid' Windows 11/11 Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-secure-logins-with-5-tips-against-key-conflicts-in-win11/"><u>Streamlining Secure Logins with 5 Tips Against Key Conflicts in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-dism-error-code-0x800f082f-on-windows-systems/"><u>Resolving DISM Error Code: 0X800F082F on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/smart-scheduling-for-improved-resource-allocation-on-android-wsl/"><u>Smart Scheduling for Improved Resource Allocation on Android WSL</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-open-installation-packages-resolving-windows-errors/"><u>Guide to Open Installation Packages: Resolving Windows Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/live-transcribing-made-easy-the-whisper-way/"><u>Live Transcribing Made Easy - The Whisper Way</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-software-management-using-the-windows-package-manager-wpm/"><u>Optimizing Software Management Using the Windows Package Manager (WPM)</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-filmmakers-guide-to-using-standardized-color-luts/"><u>[Updated] The Filmmaker's Guide to Using Standardized Color Luts</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/2024-approved-unbranded-video-editing-on-android-top-10-free-apps-reviewed/"><u>2024 Approved Unbranded Video Editing on Android Top 10 Free Apps Reviewed</u></a></li>
<li><a href="https://audio-editing.techidaily.com/in-2024-discovering-where-to-hear-frustrated-dogs-bark/"><u>In 2024, Discovering Where to Hear Frustrated Dogs Bark</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-regain-control-how-to-stop-a-glitching-tiktok-app/"><u>[New] Regain Control  How to Stop a Glitching TikTok App</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/global-menu-magic-top-international-dishes/"><u>Global Menu Magic  Top International Dishes</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-vpna-to-fake-gps-location-on-samsung-galaxy-a25-5g-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use VPNa to Fake GPS Location On Samsung Galaxy A25 5G | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/a-world-of-textual-wonder-traverse-these-top-10-sites-featuring-modern-font-designs-for-2024/"><u>A World of Textual Wonder  Traverse These Top 10 Sites Featuring Modern Font Designs for 2024</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/2024-approved-flavors-from-abroad-on-social-media/"><u>2024 Approved  Flavors From Abroad on Social Media</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-boost-engagement-with-creative-video-titling-and-tagging-techniques/"><u>[New] Boost Engagement with Creative Video Titling and Tagging Techniques</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-easy-listening-top-hits-from-facebook/"><u>[Updated] Easy Listening  Top Hits From Facebook</u></a></li>
</ul></div>
