---
title: How to Fix the “An Attempt Was Made to Reference a Token” Error in Windows 11/10
date: 2024-06-25T12:40:30.722Z
updated: 2024-06-26T12:40:30.722Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix the “An Attempt Was Made to Reference a Token” Error in Windows 11/10
excerpt: This Article Describes How to Fix the “An Attempt Was Made to Reference a Token” Error in Windows 11/10
keywords: Windows Error Fix Guide,Resolve Windows 11/10 Tokens Error,Stop Reference Token Issue,Solve Windows Token Error,Debugging Windows XP/10/11 Tokens,Correct Windows 10/11 Token Errors,Fixing Windows Token Reference Error
thumbnail: https://thmb.techidaily.com/3dd5b17c533ab88ed9cc0f3b00c7a2aa3b7c864b4f9c2a1611133710cbbaabe1.jpg
---

## How to Fix the “An Attempt Was Made to Reference a Token” Error in Windows 11/10

 Windows includes numerous pre-installed apps and tools like File Explorer, Device Manager, and Microsoft Management Console users often need to access. However, some users have reported they can’t access those pre-installed apps or others because of an error that says, “an attempt was made to reference a token that does not exist.” That error pops up when some users try to open Explorer or other native tools.

 Does the same error message pop up when you try to access Explorer, Device Manager, or another native Windows tool? If yes, try applying these potential remedies for the “reference a token” error.

## 1\. End and Restart File Explorer

 If the “reference a token” error occurs when you try to access File Explorer or folders, try restarting the Explorer process. Some users who’ve needed to fix the token reference error have said ending that Windows Explorer process and starting it again worked for them. You can end and restart Explorer as follows:

1. [Launch Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) by simultaneously pressing the **Ctrl** \+ **Shift** \+ **Esc** keyboard keys.
2. Scroll down to the Windows Explorer on the **Processes** tab.
3. Then right-click Windows Explorer and select **End task**.  
![The End task option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/end-task-option.jpg)
4. Select **End process** to confirm. The background Windows desktop will go blank when you do that, and restarting Explorer will restore it.
5. Click **File** at the top of Task Manager.  
![The Run new task option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/run-new-task.jpg)
6. Select **Run new task** to access a Create new task box.
7. Input **Explorer.exe** inside the **Open** text box.  
![The Create new task window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/create-new-task.jpg)
8. Select **Create this task with administrative privileges** and click **OK** to restart Explorer.

## 2\. Reregister Windows DLL Files

 Users who’ve needed to fix the “reference a token” error have confirmed reregistering the Windows DLL (Dynamic Link Library) files works. That highlights the token reference error can occur because some Windows DLL files aren’t correctly registered. This is how you can reregister Windows DLL files:

1. Bring up the **Type here to search** text box for finding files with the **Windows** logo key + **S** hotkey.
2. Next, type a **CMD** search phrase in the file finder text box.
3. Right-click on **Command Prompt** inside the file search tool to select **Run as administrator**.
4. Now enter and execute this command for reregistering DLL files:  
`for /f %s in ('dir /b *.dll') do regsvr32 /s %s`  
![The reregister DLL command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/reregister-dll-commands.jpg)
5. Wait for the command to finish reregistering DLLs.
6. Close your Command Prompt app, bring up the Start menu, and select **Restart**.

## 3\. Try Some More Generic Windows Fixes

 If nothing has worked, try these Windows fixes that can fix a wide variety of errors, including this one.

### Scan and Repair System Files With SFC

 The “reference a token” error is often a result of corrupted Windows system files. So, repairing system files is a likely potential solution for that error. You can check for and repair corrupted system files by [running the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) within the Command Prompt.

![The sfc /scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/sfc-scannow-command5.jpg)

### Go Back to a Previous Windows Build Version

 If the “reference a token” error occurs after a recent Windows feature update, restoring the previous build version might resolve that issue. However, you can only restore a previous build version for a limited period. This is how you can restore a previous Windows build version:

1. Activate the file search box and input the keyword **recovery options**.
2. Select **Recovery** **options** to bring up Settings.
3. Click the **Go back** or **Get started** button for restoring the previous Windows version.  
![The Get started button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/get-started-button.jpg)

 If that option is grayed out, you can also try restoring the previous Windows build from the **Advanced options** menu. Open recovery options in Settings as outlined in steps one and two above and click **Restart** **now**. Then select **Troubleshoot** \> **Advanced** options and the **Go back** **to previous build** option if available.

### Go Back to a Previous Restore Point

 System Restore is another tool that can resolve system file issues causing the “reference a token” error, but only if you have that utility enabled on your PC. If there’s a suitable restore point on your PC, you can roll back Windows to a previous point in time that predates the token reference error. Doing so might undo updates and other system changes that triggered the issue.

![The System Restore tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/system-restore-point.jpg)

 To apply this resolution, check out our [article about creating and utilizing restore points](https://www.makeuseof.com/windows-11-create-restore-point/). Choose a restore point that will roll Windows back to when you didn’t need to fix the token reference error. However, note that a system restore point will remove software packages installed after its date.

### Reset Windows

 Resetting Windows 11/10 is a last resort for fixing the “reference a token” error that will probably work. It’s best to save this probable resolution until last because you’ll need to reinstall all third-party UWP and desktop apps installed before the reset. You can apply this possible resolution as instructed within method one of our [how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/#:~:text=To%20run%20a%20Windows%20factory,%3E%20Update%20%26%20Security%20%3E%20Recovery.) guide.

## Get the “Reference a Token” Error Sorted Out

 The “reference a token” error is serious when users can’t access essential native apps like File Explorer because of it. In many cases, corrupted Windows files are usually the culprit. Most of the resolutions in this guide will address that cause, and restarting File Explorer can also work when the issue affects that app or folders.

 Does the same error message pop up when you try to access Explorer, Device Manager, or another native Windows tool? If yes, try applying these potential remedies for the “reference a token” error.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/how-to-recover-and-reset-itunes-when-its-not-working/"><u>How to Recover and Reset iTunes When It's Not Working</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-chromes-dark-window/"><u>Clearing Up Chrome's Dark Window</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-onedrive-cloud-operation-was-unsuccessful-error-in-windows-10-and-11/"><u>How to Fix the OneDrive Cloud Operation Was Unsuccessful Error in Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-dynamic-ui-embracing-the-new-widget-era/"><u>Windows 11'S Dynamic UI: Embracing the New Widget Era</u></a></li>
<li><a href="https://windows11.techidaily.com/curtailing-spontaneous-console-appearance-triggers/"><u>Curtailing Spontaneous Console Appearance Triggers</u></a></li>
<li><a href="https://windows11.techidaily.com/inside-look-how-to-reach-windowsstore-folder/"><u>Inside Look: How To Reach WindowsStore Folder</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-reversion-of-graphics-settings-for-optimal-viewing/"><u>Quick Reversion of Graphics Settings for Optimal Viewing</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-combatting-windows-not-found-problem/"><u>Essential Tips: Combatting Windows Not Found Problem</u></a></li>
<li><a href="https://windows11.techidaily.com/show-your-connection-status-update-windows-icon-bar/"><u>Show Your Connection Status: Update Windows Icon Bar</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-learn-how-everything-works-on-samsung-galaxy-m54-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Learn How Everything Works On Samsung Galaxy M54 5G | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-change-your-sim-pin-code-on-your-poco-c65-phone-by-drfone-android/"><u>In 2024, How To Change Your SIM PIN Code on Your Poco C65 Phone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-the-ultimate-blueprint-adopting-mobizen-screen-recording-skills/"><u>[New] 2024 Approved  The Ultimate Blueprint  Adopting Mobizen Screen Recording Skills</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/rating-cognitive-science-into-organizational-leadership-practices-for-2024/"><u>Integrating Cognitive Science Into Organizational Leadership Practices for 2024</u></a></li>
<li><a href="https://iphone-location.techidaily.com/in-2024-how-to-change-your-location-on-apple-iphone-se-2022-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Change Your Location on Apple iPhone SE (2022) | Dr.fone</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/epic-video-editing-add-mind-blowing-effects-to-your-videos/"><u>Epic Video Editing Add Mind-Blowing Effects to Your Videos</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-4-ways-to-trace-samsung-galaxy-f15-5g-location-drfone-by-drfone-virtual-android/"><u>Top 4 Ways to Trace Samsung Galaxy F15 5G Location | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-ios-meets-android-an-in-depth-look-at-facial-tech/"><u>2024 Approved  IOS Meets Android  An In-Depth Look at Facial Tech</u></a></li>
<li><a href="https://some-techniques.techidaily.com/evaluating-sns-hdr-pros-value-and-comparisons-for-2024/"><u>Evaluating SNS HDR Pro's Value & Comparisons for 2024</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/ipogo-will-be-the-new-ispoofer-on-apple-iphone-se-2022-drfone-by-drfone-virtual-ios/"><u>iPogo will be the new iSpoofer On Apple iPhone SE (2022)? | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>