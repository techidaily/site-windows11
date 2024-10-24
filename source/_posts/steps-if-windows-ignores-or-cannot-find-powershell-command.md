---
title: Steps if Windows Ignores or Cannot Find PowerShell Command
date: 2024-10-19T17:48:34.039Z
updated: 2024-10-24T18:35:21.544Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps if Windows Ignores or Cannot Find PowerShell Command
excerpt: This Article Describes Steps if Windows Ignores or Cannot Find PowerShell Command
keywords: Windows PowerShell Troubleshooting,Fixing Windows PowerShell Errors,Resolving PowerShell Not Found Issue,Overcoming PowerShell Ignores Commands,PowerShell Command Execution on Windows,Tips for Windows PowerShell Recognition,Restoring PowerShell Functionality in Windows
thumbnail: https://thmb.techidaily.com/5f1d20c9cdc38cb1d77f47c43dee5a5d477e2ff178ada3de9653ceb21ae65a7a.jpg
---

## Steps if Windows Ignores or Cannot Find PowerShell Command

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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134490/18498" target="_top" id="2134490">
  <img src="//a.impactradius-go.com/display-ad/18498-2134490" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134490/18498" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135359/19272" target="_top" id="2135359">
  <img src="//a.impactradius-go.com/display-ad/19272-2135359" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135359/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1868571/19272" target="_top" id="1868571">
  <img src="//a.impactradius-go.com/display-ad/19272-1868571" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868571/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Sign in with your newly created account, and see if Windows can find PowerShell now.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082530/7443" target="_top" id="2082530">
  <img src="//a.impactradius-go.com/display-ad/7443-2082530" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082530/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://fox-access.techidaily.com/updated-2024-approved-explore-template-treasures-to-craft-unique-corporate-emblems/"><u>[Updated] 2024 Approved Explore Template Treasures to Craft Unique Corporate Emblems</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-how-to-use-periscope-cost-benefits-and-signup-guide/"><u>2024 Approved How to Use Periscope Cost, Benefits & Signup Guide</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1723964507915-2024s-premier-selection-of-raspberry-pi-housing-solutions-find-your-perfect-fit-today/"><u>2024'S Premier Selection of Raspberry Pi Housing Solutions - Find Your Perfect Fit Today</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-fingerprint-login-for-windows-11-users/"><u>Configuring Fingerprint Login for Windows 11 Users</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-reno-11f-5g-frp-by-drfone-android/"><u>In 2024, Step-by-Step Tutorial How To Bypass Oppo Reno 11F 5G FRP</u></a></li>
<li><a href="https://article-files.techidaily.com/in-2024-volume-control-strategies-in-logic-pro-productions/"><u>In 2024, Volume Control Strategies in Logic Pro Productions</u></a></li>
<li><a href="https://windows11.techidaily.com/matchmaking-the-ideal-nvidia-driver-with-entertainment-goals/"><u>Matchmaking The Ideal Nvidia Driver With Entertainment Goals</u></a></li>
<li><a href="https://fix-guide.techidaily.com/proven-ways-to-fix-there-was-a-problem-parsing-the-package-on-honor-x50i-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Proven Ways to Fix There Was A Problem Parsing the Package on Honor X50i | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-complication-windows-11-plus-nvidia-x0001/"><u>Rectifying Complication: Windows 11 + Nvidia X0001</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-computer-tech-expert-reviews-and-insights/"><u>Tom's Computer Tech: Expert Reviews and Insights</u></a></li>
<li><a href="https://some-guidance.techidaily.com/top-9-tecnicas-efectivas-para-reducir-el-tamano-de-videos-para-email-marketing/"><u>Top 9 Técnicas Efectivas Para Reducir El Tamaño De Videos Para Email Marketing</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secrets-to-successful-os-transition-in-virtual-worlds/"><u>Unveiling the Secrets to Successful OS Transition in Virtual Worlds</u></a></li>
</ul></div>

