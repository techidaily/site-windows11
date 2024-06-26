---
title: Tackling the Non-Existence of PowerShell in Windows
date: 2024-06-25T12:05:18.148Z
updated: 2024-06-26T12:05:18.148Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling the Non-Existence of PowerShell in Windows
excerpt: This Article Describes Tackling the Non-Existence of PowerShell in Windows
keywords: PowerShell Absence Windows Impact,PowerShell Not In Windows,Windows Without PowerShell Features,Lack of PowerShell in Windows Systems,No PowerShell on Windows OS,Eliminating PowerShell From Windows,Removing PowerShell Functionality Windows-Wise
thumbnail: https://thmb.techidaily.com/bbcc4a007f0a07614972fe24eb730165421ff81b1eea5d7fad50043a76fd78c0.jpg
---

## Tackling the Non-Existence of PowerShell in Windows

 PowerShell is a handy tool that lets you automate tasks, troubleshoot various errors, and manage a variety of Windows settings. But what if it suddenly goes missing from your computer?

 If you use PowerShell frequently, it can be aggravating when Windows cannot find it. Thankfully, it’s possible to restore the missing PowerShell with a few troubleshooting tips. In this post, we'll walk you through all of them.

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

## 5\. Update Windows PowerShell

 If Windows still can't find PowerShell at this point, there could be a problem with the PowerShell app itself. You can try updating the PowerShell app to see if that makes any difference.

To update PowerShell on Windows:

1. Press**Win + X** to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. When the User Account Control (UAC) prompt shows up, select**Yes** .
4. Type the following command and press**Enter** .  
`winget install --id Microsoft.Powershell --source winget`  
![Update PowerShell on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Update-PowerShell-on-Windows.jpg)

 Windows will download and install the most recent version of PowerShell. Following that, you should be able to access PowerShell.

 Using Command Prompt isn't the only way to update PowerShell on Windows. If you want to learn other methods, check our guide on[how to install or update PowerShell on Windows](https://www.makeuseof.com/windows-11-powershell-install-update/) .

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
<li><a href="https://windows11.techidaily.com/essential-steps-for-activating-windows-11s-system-restore-feature/"><u>Essential Steps for Activating Windows 11'S System Restore Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-your-experience-adding-uninstall-shortcut-in-windows-10/"><u>Optimize Your Experience: Adding Uninstall Shortcut in Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-optimize-your-browsing-experience-use-defender-aguard-in-win-11-edge/"><u>How to Optimize Your Browsing Experience: Use Defender Aguard in Win 11 Edge</u></a></li>
<li><a href="https://windows11.techidaily.com/digital-transformation-for-windows-old-to-new-drivers/"><u>Digital Transformation for Windows: Old to New Drivers</u></a></li>
<li><a href="https://windows11.techidaily.com/win-back-missing-5ghz-connection-on-your-windows-pc/"><u>Win Back Missing 5GHz Connection on Your Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-unwanted-hibernation-usb-tweaks-for-windows-11/"><u>Avoid Unwanted Hibernation - USB Tweaks for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/6-quick-ways-to-fix-the-powerpoint-cant-save-file-error-in-windows-11/"><u>6 Quick Ways to Fix the PowerPoint Can't Save File Error in Windows 11</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/how-to-screen-record-on-hp-laptop-for-2024/"><u>How to Screen Record on Hp Laptop for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-nintendo-switch-prime-capture-experience-for-2024/"><u>[New] Nintendo Switch  Prime Capture Experience for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-mastering-online-meetings-with-these-budget-friendly-video-conferencing-services-for-2024/"><u>[Updated] Mastering Online Meetings with These Budget-Friendly Video Conferencing Services for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-how-to-capture-computer-screens-and-webcam-video-simultaneously-on-windows10-in-2024/"><u>[Updated] How to Capture Computer Screens and Webcam Video Simultaneously on Windows10, In 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-unveiling-the-art-of-recording-discord-conversations-in-real-time/"><u>In 2024, Unveiling the Art of Recording Discord Conversations in Real-Time</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-detailed-insights-into-camstudio-capture-functionality/"><u>[Updated] In 2024, Detailed Insights Into CamStudio Capture Functionality</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-use-phone-clone-to-migrate-your-realme-c67-5g-data-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Use Phone Clone to Migrate Your Realme C67 5G Data? | Dr.fone</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/in-2024-unleash-your-creativity-free-game-video-editing-software/"><u>In 2024, Unleash Your Creativity Free Game Video Editing Software</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-fake-gps-location-spoofer-a-good-choice-on-vivo-y28-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Is Fake GPS Location Spoofer a Good Choice On Vivo Y28 5G? | Dr.fone</u></a></li>
</ul></div>
