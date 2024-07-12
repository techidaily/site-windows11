---
title: A Comprehensible Approach to Fixing Notepad Non-Openness in Windows
date: 2024-07-11T21:23:12.985Z
updated: 2024-07-12T21:23:12.985Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Comprehensible Approach to Fixing Notepad Non-Openness in Windows
excerpt: This Article Describes A Comprehensible Approach to Fixing Notepad Non-Openness in Windows
keywords: Notepad Accessibility,Windows Portability,OpenTextEdit Troubleshoot,Editing App Compatibility,Notepad Error Fixing,File Format Issue Resolve,Operating System Integration
thumbnail: https://thmb.techidaily.com/c40243a18120050792e9b2a35c08e8c187a7242ae42c21363a9149298cc2eac3.jpg
---

## A Comprehensible Approach to Fixing Notepad Non-Openness in Windows

 Notepad is a simple text editor app that comes pre-installed on your Windows computer. You can use it to view, create, and edit text files whenever needed. But what if Windows fails to open Notepad and you can’t use it?

 Several factors, ranging from a temporary app glitch to corrupt user account files, can prevent Notepad from opening on Windows. Fortunately, there are some quick fixes you can use to regain access to the Notepad app on Windows.

## 1\. Use Alternative Methods to Open Notepad

 Before you try any advanced solutions, see if you can open Notepad using the Run tool. Press**Win + R** to open the Run dialog box. Type**notepad** in the Open field and press**Enter** .

 If that doesn’t work, try opening Notepad through a command-line tool. Open the search menu to launch**Command Prompt** or**PowerShell** . In the console, type**notepad** and then press**Enter** .

![Open Notepad via Command-Line Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-notepad-via-command-line-tool.jpg)

 You could also ask Cortana to open Notepad. However, if none of these methods work, proceed to the next solution.

## 2\. Set Notepad as the Default Text Editor

 If Notepad is not set as the default text editor app on Windows, your text files may open in a different app. If you don't want that, use these steps to set Notepad as the default text editor app.

1. Open the**Start menu** and click the**gear icon** to launch the Settings app.
2. Navigate to the**Apps** tab.
3. Select**Default apps** from the right pane.
4. Scroll all the way down to the**Related settings** section.
5. Click**Choose defaults by file type** .
6. Type**.txt** in the search box and click the current default app.
7. Select**Notepad** and click the**Set default** button.  
![Set Notepad as Default Text Editor App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/set-notepad-as-default-text-editor-app-on-windows.jpg)

Try opening a few text files and see if they open in Notepad.

## 3\. Repair or Reset the Notepad App

 The built-in repair tool on Windows is quite efficient when it comes to fixing minor app-related issues. Microsoft recommends using this tool when an app fails to open or does not work as expected on your Windows computer.

To repair the Notepad app on Windows:

1. Right-click the Start icon or press**Win + X** to open the Power User menu.
2. Select**Installed apps** from the list.
3. Scroll down or use the search tool to locate**Notepad** on the app list.
4. Click the**three-dot menu icon** next to Notepad and select**Advanced options** .
5. Scroll down to the Reset section and click the**Repair** button.  
![Repair or Reset the Notepad App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/repair-or-reset-the-notepad-app.jpg)

 You should see a checkmark next to the Repair button once the process is complete. Then, try to [open the Notepad app](https://www.makeuseof.com/windows-11-open-notepad/) again.

 If repairing the Notepad app does not make any difference, you can try resetting it. Here are the steps for the same.

1. Press**Win + S** to open the search menu.
2. Type**Notepad** in the search box and select**App settings** .
3. Under the Reset section, click the**Reset** button.

 Windows will reset the Notepad app to its default version, which should resolve any issues with it.

## 4\. Reinstall the Notepad App

 You can also try uninstalling and reinstalling the Notepad app on your computer. To do so, you’ll need to access the [optional features on Windows](https://www.makeuseof.com/tag/windows-10-optional-features-guide/) . Here’s how you can go about it.

1. Press**Win + I** to launch the Settings app.
2. Navigate to**Apps > Optional features** .
3. Click on**Notepad** to expand it.
4. Click the**Uninstall** button.  
![Uninstall Notepad App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/uninstall-notepad-app-on-windows.jpg)
5. Wait for Windows to uninstall Notepad from your computer.
6. Next, click the**View features** button at the top.
7. Type**Notepad** in the search box.
8. Tick the**Notepad (system)** checkbox and click**Next** .
9. Click**Install** .  
![Install Notepad App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/install-notepad-app-on-windows.jpg)

 Wait for Windows to install Notepad on your computer and then try to open it using the search menu.

## 5\. Run the SFC and DISM Scans

 Corrupted system files could also interfere with system processes and prevent Notepad from opening. The System File Checker (SFC) is a built-in utility that can help you repair system files on Windows. It basically scans your system for damaged system files and replaces them with their cached versions.

To run the SFC scan on Windows:

1. Click the magnifying icon on the taskbar to open the search menu.
2. Type**command prompt** in the box and select**Run as administrator** .
3. When the User Account Control (UAC) prompt appears, select**Yes** to continue.
4. In the console, input the following command and press**Enter** :  
`sfc /scannow`

 Wait for the scan to complete and then enter the following command to run the DISM (or Deployment Image Servicing and Management) scan. It will try to detect and repair any issues with the system image.

`DISM.exe /Online /Cleanup-image /Restorehealth`

![DISM Scan in Windows Terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/dism-scan-in-windows-terminal.jpg)

 After the scan is complete, restart your PC and see if you can access Notepad.

## 6\. Perform a Clean Boot

 At times, third-party apps and background services can conflict with Windows processes and cause problems like the one discussed here. One way to verify this possibility is to boot your computer in a clean boot state, where it only runs with essential apps and services.

 If you perform a clean boot and Notepad opens normally, it means that the culprit causing the issue got disabled. If you'd like to learn more about the topic, check out our guide on [how to perform a clean boot on Windows](https://www.makeuseof.com/how-perform-clean-boot-windows-10/) and follow the steps listed there.

## 7\. Create Another User Account

 If some of the files in your user account have become corrupt, you may have difficulty performing simple tasks like opening an app. If that seems to be the case, your best option is to create and switch to a new user account.

To create a new user account on Windows:

1. Use one of the [many ways to open the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Accounts > Other users** .
3. Click the**Add account** button.
4. In the Microsoft account window, click **I don't have this person's sign-in information** .  
![Microsoft Account Sign-In Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/microsoft-account-sign-in-window.jpg)

 Follow the on-screen prompts to create a new user account. Make sure you give the new account administrative privileges so that you can [move your personal files and data to the new account](https://www.makeuseof.com/windows-10-copy-files-between-user-accounts/) with ease.

 Once you sign in with your newly created account, Notepad should open without problems.

## Start Using Notepad Again

 Hopefully, the solutions provided above have helped, and you’re able to use Notepad again. However, if none of the above solutions work, you can perform a system restore to undo any recent changes that may have caused the problem.


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
<li><a href="https://windows11.techidaily.com/unlock-the-power-of-search-implementing-it-in-win11s-task-monitor/"><u>Unlock the Power of Search: Implementing It in Win11's Task Monitor</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-startup-opening-sticky-notes-seamlessly-on-pc/"><u>Streamlining Startup: Opening Sticky Notes Seamlessly on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-your-view-simple-fixes-for-windows-11-screen-haze/"><u>Transform Your View: Simple Fixes for Windows 11 Screen Haze</u></a></li>
<li><a href="https://windows11.techidaily.com/what-is-a-keygen-examining-its-impacts-and-cleanup-techniques-for-pcs/"><u>What Is a Keygen? Examining Its Impacts and Cleanup Techniques for PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-personalize-with-direct-drawing/"><u>Windows 11: Personalize with Direct Drawing</u></a></li>
<li><a href="https://extra-tips.techidaily.com/elevating-your-listening-game-with-androids-top-6-podcast-apps/"><u>Elevating Your Listening Game with Android’s Top 6 Podcast Apps</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-do-samsung-galaxy-a54-5g-screen-sharing-drfone-by-drfone-android/"><u>In 2024, How To Do Samsung Galaxy A54 5G Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-your-windows-10-past-insights-on-activity-logs/"><u>Unlocking Your Windows 10 Past: Insights on Activity Logs</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-process-for-ram-recalibration-on-win-11/"><u>Step-by-Step Process for RAM Recalibration on Win 11</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-prioritizing-visibility-a-guide-to-insta-highlights-perfection/"><u>[Updated] In 2024, Prioritizing Visibility  A Guide to Insta Highlights Perfection</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-remove-remote-management-from-iphone-8-plus-by-drfone-ios-unlock-ios-unlock/"><u>How to Remove remote management from iPhone 8 Plus?</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/top-best-free-luts-for-premiere-pro-for-2024/"><u>Top Best Free LUTs For Premiere Pro for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-error-trouble-with-compatibility-tool-here-are-quick-solutions/"><u>Windows Error: Trouble with Compatibility Tool? Here Are Quick Solutions.</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-bridging-the-gap-between-individual-images-using-picshot/"><u>In 2024, Bridging the Gap Between Individual Images Using Picshot</u></a></li>
<li><a href="https://windows11.techidaily.com/a-stepwise-guide-to-banishing-the-onedrive-icon-from-explorer/"><u>A Stepwise Guide to Banishing the OneDrive Icon From Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-fixing-windows-office-error-0x80041015/"><u>Solutions for Fixing Windows Office Error 0X80041015</u></a></li>
<li><a href="https://windows11.techidaily.com/personalizing-windows-space-adding-this-pc-iconography/"><u>Personalizing Windows Space: Adding 'This PC' Iconography</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-from-hobbyist-to-host-mac-sports-channel-creation/"><u>[Updated] In 2024, From Hobbyist to Host  Mac Sports Channel Creation</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-windows-operations-formulating-and-scrutinizing-reports/"><u>Understanding Windows Operations: Formulating & Scrutinizing Reports</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-obs-full-screen-nightmare-ended/"><u>[New] Obs Full-Screen Nightmare Ended</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-synthesis-how-meditation-transforms-cognition-and-emotion/"><u>Seamless Synthesis: How Meditation Transforms Cognition & Emotion</u></a></li>
<li><a href="https://extra-resources.techidaily.com/exploring-windows-11-essential-upgrades/"><u>Exploring Windows 11  Essential Upgrades</u></a></li>
<li><a href="https://unlock-android.techidaily.com/mastering-android-device-manager-the-ultimate-guide-to-unlocking-your-vivo-s18-pro-device-by-drfone-android/"><u>Mastering Android Device Manager The Ultimate Guide to Unlocking Your Vivo S18 Pro Device</u></a></li>
<li><a href="https://windows11.techidaily.com/top-10-uses-for-windows-powertoys-tools/"><u>Top 10 Uses for Windows PowerToys Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-windows-cars-keyboard-magic-boosts-speed/"><u>Top 5 Windows Cars: Keyboard Magic Boosts Speed</u></a></li>
<li><a href="https://windows11.techidaily.com/perfectly-presented-photos-mastering-the-art-of-crafting-captivating-slideshows-in-win11-photos-app/"><u>Perfectly Presented Photos: Mastering the Art of Crafting Captivating Slideshows in Win11 Photos App</u></a></li>
<li><a href="https://windows11.techidaily.com/9-ways-to-fix-the-0x8004def5-onedrive-error-code-on-windows-11/"><u>9 Ways to Fix the 0X8004def5 OneDrive Error Code on Windows 11</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/how-to-make-a-memorable-honeymoon-video-for-2024/"><u>How to Make a Memorable Honeymoon Video for 2024</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-forgot-locked-iphone-se-2020-password-learn-the-best-methods-to-unlock-drfone-by-drfone-ios/"><u>In 2024, Forgot Locked iPhone SE (2020) Password? Learn the Best Methods To Unlock | Dr.fone</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-2024-approved-steps-to-resume-interrupted-stream-on-fb/"><u>[Updated] 2024 Approved  Steps to Resume Interrupted Stream on FB</u></a></li>
<li><a href="https://windows11.techidaily.com/tackle-interruptexception-in-win11-blue-screen/"><u>Tackle INTERRUPT_EXCEPTION in Win11 Blue Screen</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-strategic-insights-into-making-emotional-connection-with-customer-success-videos/"><u>[New] Strategic Insights Into Making Emotional Connection with Customer Success Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-access-to-any-language-hotkeys-for-efficient-translation-in-windows-os/"><u>Quick Access to Any Language: Hotkeys for Efficient Translation in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-error-code-3-nvidias-win10-and-11-woes/"><u>Tackling Error Code 3: NVIDIA's Win10 & 11 Woes</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/the-ultimate-selection-of-cost-free-high-quality-video-editors-for-2024/"><u>The Ultimate Selection of Cost-Free, High-Quality Video Editors for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-0x80072efd-in-win1110s-microsoft-store/"><u>Solving 0X80072EFD in Win11/10's Microsoft Store</u></a></li>
<li><a href="https://windows11.techidaily.com/pushing-boundaries-my-quest-to-overcome-app-guard-censorship/"><u>Pushing Boundaries: My Quest to Overcome App Guard Censorship</u></a></li>
<li><a href="https://windows11.techidaily.com/swipe-to-learn-comparing-windows-10-ui-with-windows-11/"><u>Swipe to Learn: Comparing Windows 10 UI with Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-savvy-buyers-guide-to-finding-windows-11-deals/"><u>The Savvy Buyer's Guide to Finding Windows 11 Deals</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-a-polished-w11-workspace/"><u>Quick Fixes for a Polished W11 Workspace</u></a></li>
<li><a href="https://printer-issues.techidaily.com/curing-repeated-printer-errors-in-windows-107-environments/"><u>Curing Repeated Printer Errors in Windows 10/7 Environments</u></a></li>
<li><a href="https://windows11.techidaily.com/unmasking-profit-making-mechanisms-for-w11-at-microsoft/"><u>Unmasking Profit Making Mechanisms for W11 at Microsoft</u></a></li>
<li><a href="https://windows11.techidaily.com/speedy-boot-ups-in-windows-11-discover-the-best-practices/"><u>Speedy Boot-Ups in Windows 11 – Discover the Best Practices</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-instagrams-hidden-details-uncovering-story-viewer-truths/"><u>2024 Approved  Instagram's Hidden Details  Uncovering Story Viewer Truths</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-best-mac-image-sorter/"><u>2024 Approved  Best Mac Image Sorter</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-elevate-your-brand-discovering-the-essential-5-youtube-strategies/"><u>2024 Approved  Elevate Your Brand  Discovering the Essential 5 YouTube Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-times-ticking-off-align-it-back/"><u>Windows Time's Ticking Off? Align It Back!</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-undelete-lost-messages-from-21-by-fonelab-android-recover-messages/"><u>Best Android Data Recovery - Undelete Lost Messages from 21</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-a-found-apple-iphone-11-pro-max-by-drfone-ios/"><u>How To Unlock A Found Apple iPhone 11 Pro Max?</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/mastering-the-game-discover-these-top-12-pc-clickers/"><u>Mastering the Game  Discover These Top 12 PC Clickers</u></a></li>
<li><a href="https://windows11.techidaily.com/strike-balance-not-conflict-choose-one-antivirus-on-your-windows-pc/"><u>Strike Balance, Not Conflict: Choose One Antivirus on Your Windows PC</u></a></li>
</ul></div>
