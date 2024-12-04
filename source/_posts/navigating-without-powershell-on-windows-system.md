---
title: Navigating Without PowerShell on Windows System
date: 2024-12-02T18:38:40.528Z
updated: 2024-12-04T00:08:34.490Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating Without PowerShell on Windows System
excerpt: This Article Describes Navigating Without PowerShell on Windows System
keywords: Windows No PS Command Guide,PowerShellless Windows Troubleshooting,Navigate Windows Without PowerShell,Windows System PowerShell-Free,Windows Tasks without PowerShell,Execute Windows Commands Sans PowerShell,Managing Windows Systems Sans PowerShell
thumbnail: https://thmb.techidaily.com/6fd0cef62e823c305fb86e64196b6559e3c33c787060e717fb517085eb725bc3.jpg
---

## Navigating Without PowerShell on Windows System

 PowerShell is a handy tool that lets you automate tasks, troubleshoot various errors, and manage a variety of Windows settings. But what if it suddenly goes missing from your computer?

 If you use PowerShell frequently, it can be aggravating when Windows cannot find it. Thankfully, it’s possible to restore the missing PowerShell with a few troubleshooting tips. In this post, we'll walk you through all of them.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eu4vwlZcMvM?si=4vEczfVU4BUUFP-t" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Make Sure Windows PowerShell Is Enabled

 On Windows, you can enable or disable optional features and programs from the Control Panel. To start, you need to ensure that PowerShell isn’t disabled on your computer. Here’s how to check.

1. Press**Win + R** to open the Run dialog.
2. Type**control** in the box and press**Enter** to open Control Panel.
3. Click the drop-down menu in the top right corner to select**Large icons** .
4. Go to**Programs and Features** .
5. Click the**Turn Windows features on or off** link from the left pane.
6. When the User Account Control (UAC) prompt appears, select**Yes** to continue.
7. In the Windows Features dialog, locate**Windows PowerShell** and select its checkbox.
8. Click**OK** to save the changes.  
![Enable PowerShell on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Enable-PowerShell-on-Windows.jpg)

 Restart your computer after this (see[how to restart a Windows computer](https://www.makeuseof.com/windows-restart-methods/) ) and then try to launch PowerShell using the search menu.

## 2\. Launch PowerShell Using Run Command or File Explorer

 If you are unable to open PowerShell via the search menu, you can try using the Run dialog box. Press**Win + R** to open the Run dialog. Type**powershell** in the box and press**Enter** . If you want to launch PowerShell with admin rights, press**Ctrl + Shift + Enter** instead.

![Open PowerShell via Run Command on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Open-PowerShell-via-Run-Command-on-Windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JAkb8Bv3AU4?si=2rHwnZYTzTLieKgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can also open PowerShell from the File Explorer address bar. To do so, press**Win + E** to open File Explorer. Type**PowerShell** in the address bar and press**Enter** .

## 3\. Create a Desktop Shortcut for PowerShell

 Windows may fail to open PowerShell if it does not know the exact file path to the PowerShell executable file. If that’s the case, you can manually locate the PowerShell executable file on your computer and create a desktop shortcut for it. Here are the steps for doing the same.

1. Right-click on the**Start icon** to open the Power User menu and select**File Explorer** from the list.
2. Navigate to**This PC** .
3. Head over to**C: > Windows > SysWOW64** and locate**WindowsPowerShell** folder.
4. Open the WindowsPowerShell folder and go to the**v1.0** folder.
5. Double-click on the PowerShell executable file and see if it works. If it does, right-click on it and select**Send to > Desktop (create shortcut)** .  
![Create Desktop Shortcut for PowerShell on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Create-Desktop-Shortcut-for-PowerShell-on-Windows.jpg)

 You can then use the newly created desktop shortcut to launch PowerShell. For added convenience, you can assign a keyboard shortcut to PowerShell. To learn more about this, check our guide on[how to assign keyboard shortcuts to programs in Windows](https://www.makeuseof.com/windows-keyboard-shortcuts-programs/) .

## 4\. Scan Your Computer for Corrupted System Files

 Damaged or corrupted system files can also interfere with Windows operations and prevent PowerShell from launching. Fortunately, your Windows PC comes with a few built-in tools, such as SFC (System File Checker) and DISM (or Deployment Image Servicing and Management) that can help you with such issues. If Windows suffers from system file corruption, running these tools will fix the problem.

To run the SFC scan on Windows:

1. Click the magnifying glass icon on the taskbar or press**Win + S** to open the search menu.
2. Type**command prompt** in the search box and select**Run as administrator** from the right panel.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Type**SFC /scannow** in the console and press**Enter** .

 The SFC scan will start verifying the integrity of your system files and fix any issues with them. The scan might take a while, so be patient.

 Next, you need to run the DISM scan. This is another diagnostic tool that Windows offers. It can automatically detect any issues with the system image and fix them. If you want to learn more about them, check out our guide on the[differences between CHKDSK, SFC, and DISM](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) .

 To run DISM,[open Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) again. Paste the following command in the console and press**Enter** .

`DISM.exe /Online /Cleanup-image /Restorehealth`

![DISM Scan Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/DISM-Scan-Windows.jpg)

 Wait for the command to execute successfully, and then restart your PC. Following that, see if Windows can find PowerShell on your computer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3koT_-kvbks?si=sQV7FzPiz6GYITrE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Update Windows PowerShell

 If Windows still can't find PowerShell at this point, there could be a problem with the PowerShell app itself. You can try updating the PowerShell app to see if that makes any difference.

To update PowerShell on Windows:

1. Press**Win + X** to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. When the User Account Control (UAC) prompt shows up, select**Yes** .
4. Type the following command and press**Enter** .  
`winget install --id Microsoft.Powershell --source winget`  
![Update PowerShell on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Update-PowerShell-on-Windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mHFtYJppXFk?si=ylFaAT4nXqCmlV8F" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Windows will download and install the most recent version of PowerShell. Following that, you should be able to access PowerShell.

 Using Command Prompt isn't the only way to update PowerShell on Windows. If you want to learn other methods, check our guide on[how to install or update PowerShell on Windows](https://www.makeuseof.com/windows-11-powershell-install-update/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/poI1NQxHfjc?si=ZLG0wziYcTKIKwL5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Create a New User Account

 It's possible that the PowerShell not opening problem is limited to your current user account. In that case, you can create and switch to a new user account and see if that works.

To create a new user account on Windows, use these steps.

1. Open the start menu and click the**gear icon** to open the Settings app.
2. Navigate to**Accounts** .
3. Select**Other users** .
4. Click the**Add account** button.
5. Click on **I don't have this person's sign-in information** and follow the on-screen prompts to create a new user account.  
![Microsoft Account Sign-In](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Microsoft-Account-Sign-In.jpg)

 Sign in with your newly created account, and see if Windows can find PowerShell now.

## Access Windows PowerShell Again

 Hopefully, one of the above fixes has proven useful, and you're able to access PowerShell once again. If not, you may have to consider resetting your Windows computer as a last resort.

 PowerShell isn't the only command-line tool available on Windows. You can also use the Command Prompt to communicate with your system.

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
<li><a href="https://fox-boxes.techidaily.com/new-in-2024-top-offline-speech-to-text-transcription-apps/"><u>[New] In 2024, Top Offline Speech-to-Text Transcription Apps</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-speedy-social-stardom-likes-plus-videos-on-instagram-guide/"><u>[Updated] 2024 Approved Speedy Social Stardom Likes + Videos on Instagram Guide</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-harmonizing-photos-with-musical-scores/"><u>2024 Approved Harmonizing Photos With Musical Scores</u></a></li>
<li><a href="https://android-location.techidaily.com/for-people-wanting-to-mock-gps-on-nubia-red-magic-9-proplus-devices-drfone-by-drfone-virtual/"><u>For People Wanting to Mock GPS on Nubia Red Magic 9 Pro+ Devices | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-full-guide-to-bypass-vivo-s18-pro-frp-by-drfone-android/"><u>In 2024, Full Guide to Bypass Vivo S18 Pro FRP</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-multiview-tech-with-windows/"><u>Mastering Multiview Tech with Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11-sign-in-shift-move-from-pin-to-password-effortlessly/"><u>Mastering Windows 11 Sign-In Shift: Move From PIN to Password Effortlessly</u></a></li>
<li><a href="https://extra-hints.techidaily.com/proart-pa-329q-review-the-ultimate-4k-workstation-display/"><u>ProArt PA 329Q Review The Ultimate 4K Workstation Display</u></a></li>
<li><a href="https://windows11.techidaily.com/quickfire-processes-identifying-graphic-card-model-windows-11/"><u>Quickfire Processes: Identifying Graphic Card Model, Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/simplified-integration-how-to-set-up-linux-in-your-win10-box/"><u>Simplified Integration: How to Set Up Linux in Your Win10 Box</u></a></li>
<li><a href="https://windows11.techidaily.com/the-secret-behind-timeless-game-aesthetics-retroarcs-shaders/"><u>The Secret Behind Timeless Game Aesthetics - RetroArc's Shaders</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-ultimate-strategy-for-merging-chatgpt-and-whatsapp-in-your-customer-service-approach/"><u>The Ultimate Strategy for Merging ChatGPT and WhatsApp in Your Customer Service Approach</u></a></li>
<li><a href="https://some-tips.techidaily.com/the-vanguard-of-radio-theatre-composition-for-2024/"><u>The Vanguard of Radio-Theatre Composition for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-11-free-apps-to-check-imei-on-oneplus-11-5g-phones-by-drfone-android/"><u>Top 11 Free Apps to Check IMEI on OnePlus 11 5G Phones</u></a></li>
<li><a href="https://windows11.techidaily.com/uncover-the-file-location-for-your-desktop-images/"><u>Uncover the File Location for Your Desktop Images</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-edges-ongoing-role-in-win11-systems/"><u>Understanding Edge's Ongoing Role in Win11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-full-potential-of-windows-11-search-here/"><u>Unlock the Full Potential of Windows 11 Search Here</u></a></li>
</ul></div>

