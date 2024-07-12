---
title: "Credential Control in Win11: Quick Ways to Unlock Passwords"
date: 2024-07-11T22:25:17.543Z
updated: 2024-07-12T22:25:17.543Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Credential Control in Win11: Quick Ways to Unlock Passwords"
excerpt: "This Article Describes Credential Control in Win11: Quick Ways to Unlock Passwords"
keywords: Win11 Credential Management,Quick Password Unlocking,Windows 11 Security,Access Control Systems,Enhanced Login Safety,Secure Password Hacks,Locked Account Solutions
thumbnail: https://thmb.techidaily.com/fdc25fa9e7d76ca87920564362f13d91c2db273783ec5bcb39c2377739cf581a.jpg
---

## Credential Control in Win11: Quick Ways to Unlock Passwords

 Credential Manager in Windows 11 stores all the username and password combinations that you use for websites you visit in Edge browsers, apps, or networks. Microsoft introduced Credential Manager with Windows 10 and since then it stores and manages all credentials in one place. You can even back up and remove credential entries that are obsolete.

 The most obvious method to access the Credential Manager is using the Control Panel. But do you know that there are other methods to access this password management too? We will list out all the possible ways to open it quickly. Let’s begin.

## 1\. Using Start Menu

 The Start menu is the most-visited section by Windows users. To access Credential Manager using the Start menu, repeat the following steps:

1. Press the**Win** key to open the Start menu.
2. Type**Credentials Manager** and click on the**Open** option.
3. The Credential Manager utility will launch on your system.

## 2\. Using Windows Search

 Alternatively, you can use the new and improved Windows Search tool to find and open Credential Manager on your system. Here’s how to do it:

1. Press**Win + S** to open the Windows Search utility.  
![Open Credentials Manager Using Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/open-credentials-manager-using-windows-search.jpg)
2. Type Credential Manager and click on the first relevant search result to open the tool.

## 3\. Using the Run Command Box

 You can launch Credentials Manager without using your mouse and clicking on options or the context menu using the Run command box. Repeat the following steps:

1. Press**Win + R** to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**control /name Microsoft.CredentialManager** in the text input box and press the**Enter** key.  
![Open Credentials Manager Using the Run Command Box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/open-credentials-manager-using-the-run-command-box.jpg)
3. Credential Manager will open in a separate control panel window.

## 4\. Using the File Explorer

 Credential Manager’s DLL file is located inside the SysWoW64 folder. You can access it using File Explorer and then run it using Control Panel. Ensure that you have administrator privileges to access the SysWOW64 folder before trying this method. Here’s how:

1. Press**Win + E** to [launch the File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) .
2. Go to the address bar, paste the following path, and press the**Enter** key:**C:\\Windows\\SysWOW64**
3. Once you are inside the SysWOW64 folder, locate the**keymgr.dll file** and right-click on it.
4. Select**Show more options** from the context menu and then click on the**Open with** option.
5. Scroll down and click on the**Choose an app on your PC** option.
6. Navigate to the C drive and click on the Windows folder. Then, open the SysWOW64 folder.
7. Find the**Control.exe** program and select it. Click on the**Open** button.  
![Open Credentials Manager Using the File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/open-credentials-manager-using-the-file-explorer.jpg)
8. Window Control Panel will be added to the list of supported programs.**Double-click** on it to open keymgr.dll file in Control Panel.

## 5\. Using the CMD

 You can use the Command Prompt to open Credential Manager directly. No need to navigate through Control Panel to locate the utility. Repeat the following steps:

1. Press**Win + R** to open the Run dialog box.
2. Type**cmd** and press**Ctrl + Shift + Enter** to launch Command Prompt with administrator privileges.
3. In the Command Prompt window, type the following command and press the**Enter** key:**control.exe keymgr.dll**  
![Open Credentials Manager Using the CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/open-credentials-manager-using-the-cmd.jpg)
4. Credentials Manager will launch on your system. Close the Command Prompt window.

## 6\. Using Control Panel

 Control Panel is the central hub for many system utilities and also contains Credential Manager. If you prefer the GUI method to open any Windows utility, you can use Control Panel. Repeat the following steps:

1. Press**Win + R** to launch the Run command box. Type**control** and press the**Enter** key.
2. In the Control Panel window, click on the**User Accounts** option.  
![Open Credentials Manager Using Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/open-credentials-manager-using-control-panel.jpg)
3. Lastly, click on the**Credential Manager** option to launch the tool.

## 7\. Using a Desktop Shortcut

 A desktop shortcut can save much time in Credential Manager on the system. Since it is not an executable program but a DLL file, merely making a desktop shortcut won’t work. Instead, we will create a shortcut of the Credential Manager DLL file and configure it to open with Control Panel.

 Repeat the following steps to create a shortcut for Credential Manager:

1. Press**Win + D** to switch to Desktop.
2. Right-click on the Desktop and select the**New > Shortcut** option from the context menu.
3. In the Create Shortcut window, paste the following text in the Location box:**control.exe /name Microsoft.CredentialManager**  
![Open Credentials Manager Using a Desktop Shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/open-credentials-manager-using-a-desktop-shortcut.jpg)
4. Click on the**Next** button. Name the shortcut**Credential Manager** and click on the**Finish** button.
5. Now, double-click on the shortcut to open Credential Manager.

## 8\. Using the Settings App

 Microsoft hasn’t moved all Control Panel options to the Settings app. But it is possible to search and access Credential Manager inside the Settings app. Here’s how to do it:

1. **Right-click** on the Start button to open the Power User menu. Select the**Settings** option from the menu.
2. Navigate to the top-left corner and click on the**Find a setting** option.  
![Open Credentials Manager Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/open-credentials-manager-using-the-settings-app.jpg)
3. Type**Credential Manager** and click on the first relevant search result for the utility.

## 9\. Using a PowerShell Command

 Like the Command Prompt, you can use PowerShell to open Credential Manager with a simple one-line command. Here’s how to do it:

1. Press**Win + S** to [open Windows Search](https://www.makeuseof.com/windows-search-use-guide/) .
2. Type**PowerShell** and click on the**Run as administrator** option in the right pane.
3. Type the following command in the PowerShell window and press the**Enter** key:**start-process control.exe keymgr.dll**  
![Open Credentials Manager Using a PowerShell Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/open-credentials-manager-using-a-powershell-command.jpg)
4. Credential Manager will open. Type the**exit** command in the PowerShell window and press the**Enter** key to close it.

## 10\. Using a Batch File

 A batch file is a more convenient method to open Credential Manager whenever you need it. You can place it on the desktop and run it with administrator privileges just like a shortcut. Repeat the following steps to create a batch file:

1. Press**Win + D** to switch to the Desktop. Right-click on the desktop and select the**New > Text Document** option.
2. Open the empty text document and paste the following code snippet:  
`@echo off powershell.exe control.exe keymgr.dll`
3. Press**Ctrl + Shift + S** to open the**Save as** window. Name the file “**CredMgr.bat** ” and click on the**Save** button.  
![Open Credentials Manager Using a Batch File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/open-credentials-manager-using-a-batch-file.jpg)
4. Close the Notepad file. Navigate to the location where you saved the CredMgr.bat file.
5. Right-click on it and select the**Run as administrator** option.
6. The PowerShell window will launch and close automatically. Credential Manager will launch on your system.

## 11\. Using the Task Manager

 You can open Credentials Manager by running a new task in Task Manager. Here’s how to do it:

1. Press**Win + R** to open the Run command box. Type**taskmgr** in the text input area and press the**Enter** key to open Task Manager.
2. In the Task Manager window, click on the**Run new task** button.  
![Open Credentials Manager Using the Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/open-credentials-manager-using-the-task-manager.jpg)
3. Type**control.exe keymgr.dll** in the Create new task window and click on the**OK** button.
4. Credential Manager will open in a new window. Exit the Task Manager window.

## Check Your Credentials on Windows Quickly With These Tips

 Windows Credential Manager is an excellent utility that automatically saves usernames and login pairs without installing a separate application. Even if you don’t use the feature for saving passwords of your favorite websites, you can still save login information of all the Windows apps which you use.


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
<li><a href="https://win11.techidaily.com/top-4-strategies-for-windows-pct-success/"><u>Top 4 Strategies for Windows PCT Success</u></a></li>
<li><a href="https://windows11.techidaily.com/diagnosing-partially-functioning-windows-earphones/"><u>Diagnosing Partially Functioning Windows Earphones</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-the-advantages-of-microsofts-copilot-key-for-windows-11/"><u>Demystifying the Advantages of Microsoft's Copilot Key for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/dazzling-holiday-windows-a-celebration-of-joy-and-light/"><u>Dazzling Holiday Windows: A Celebration of Joy & Light</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-essential-tips-on-calculating-your-youtube-traffic-and-earnings/"><u>[New] 2024 Approved  Essential Tips on Calculating Your YouTube Traffic & Earnings</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/crucial-techniques-for-documenting-lol-wars/"><u>Crucial Techniques for Documenting LOL Wars</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/recording-with-precision-perfecting-ios-device-features-on-youtube/"><u>Recording with Precision  Perfecting iOS Device Features on YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-drives-c-vs-d-explanation/"><u>Deciphering Drives: C: Vs D: Explanation</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-top-3-premier-audio-amplification-websites-for-mp3s/"><u>In 2024, Top 3 Premier Audio Amplification Websites for MP3s</u></a></li>
<li><a href="https://windows11.techidaily.com/combining-audioscapes-and-visuals-snipping-tool-guide-max-156/"><u>Combining Audioscapes & Visuals: Snipping Tool Guide (Max 156)</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-idle-computing-with-auto-sleep-in-w10w11/"><u>Conquering Idle Computing with Auto Sleep in W10/W11</u></a></li>
<li><a href="https://windows11.techidaily.com/coherent-organization-of-windows-files-max-156/"><u>Coherent Organization of Windows Files (Max 156)</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-graphics-output-dpi-adjustment-guide/"><u>Customizing Graphics Output: DPI Adjustment Guide</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-bring-your-beat-to-facebook-ios-and-android-edition/"><u>[New] Bring Your Beat to Facebook - iOS & Android Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/create-your-own-windows-speech-recognition-app-with-autohotkey-and-whisper/"><u>Create Your Own Window's Speech Recognition App with AutoHotkey and Whisper</u></a></li>
<li><a href="https://windows11.techidaily.com/digital-dilemma-deciphered-7-strategies-to-reopen-browsers-in-win-os/"><u>Digital Dilemma Deciphered: 7 Strategies to Reopen Browsers in WIN OS</u></a></li>
<li><a href="https://windows11.techidaily.com/command-line-conjuring-windows-new-feature/"><u>Command Line Conjuring: Windows' New Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/delving-into-what-windows-11s-new-updates-signify-for-users/"><u>Delving Into What Windows 11'S New Updates Signify For Users</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-exhaustive-analysis-of-gecata-playback-device/"><u>In 2024, Exhaustive Analysis of Gecata Playback Device</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-streamlined-techniques-for-rapid-mac-screen-recording/"><u>[Updated] Streamlined Techniques for Rapid Mac Screen Recording</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-uncovering-if-itop-justifies-its-market-presence/"><u>[New] Uncovering If ITop Justifies Its Market Presence</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/2024-approved-elite-sound-weaver-the-ultimate-mac-mp3-experience/"><u>2024 Approved Elite Sound Weaver The Ultimate Mac MP3 Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/cracked-codekeepers-stay-secure-in-the-now/"><u>Cracked Codekeepers: Stay Secure in the Now</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-toolwiz-evaluation-the-top-choice-in-mobile-editing-for-2024/"><u>[New] Toolwiz Evaluation  The Top Choice in Mobile Editing for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/expanding-creative-horizons-with-custom-fonts-in-after-effects/"><u>Expanding Creative Horizons with Custom Fonts in After Effects</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-another-users-microsoft-account-on-shared-device/"><u>Disabling Another User's Microsoft Account on Shared Device</u></a></li>
<li><a href="https://windows11.techidaily.com/construct-ai-driven-artistry-with-win11-and-paint-tool-sai-your-ultimate-guide-to-image-creation/"><u>Construct AI-Driven Artistry with Win11 & Paint Tool SAI: Your Ultimate Guide to Image Creation</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-a-user-friendly-guide-for-shortcut-placement-on-desktop/"><u>Crafting a User-Friendly Guide for Shortcut Placement on Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-the-oculus-quest-for-windows-vr-use/"><u>Customizing the Oculus Quest for Windows VR Use</u></a></li>
<li><a href="https://windows11.techidaily.com/decrease-resource-load-managing-news-app-consumption/"><u>Decrease Resource Load: Managing News App Consumption</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-words-best-writing-software-for-windows-users/"><u>Conquer Words: Best Writing Software for Windows Users</u></a></li>
<li><a href="https://howto.techidaily.com/authentication-error-occurred-on-gionee-f3-pro-here-are-10-proven-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Authentication Error Occurred on Gionee F3 Pro? Here Are 10 Proven Fixes | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/cleanse-your-screen-history-3-strategies/"><u>Cleanse Your Screen History - 3 Strategies</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-in-2024-generate-hits-adobe-made-memes/"><u>[New] In 2024, Generate Hits  Adobe-Made Memes</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-change-oppo-k11x-lock-screen-password-by-drfone-android/"><u>How To Change Oppo K11x Lock Screen Password?</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-rectifying-the-pink-screen-dilemma/"><u>Decoding and Rectifying the Pink Screen Dilemma</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-the-blocked-app-notification-issue/"><u>Clearing Up the Blocked App Notification Issue</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-xiaomi-redmi-note-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, What is the best Pokemon for pokemon pvp ranking On Xiaomi Redmi Note 12 Pro+ 5G? | Dr.fone</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-stop-worrying-if-your-adobe-premiere-playback-slows-down-this-guide-will-show-you-the-best-solutions-to-resolve-this-issue-and-a-perfect-alternative-for/"><u>New Stop Worrying if Your Adobe Premiere Playback Slows Down. This Guide Will Show You the Best Solutions to Resolve This Issue and a Perfect Alternative for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/comparative-overview-of-installation-methods-exe-and-msi-files/"><u>Comparative Overview of Installation Methods: Exe & Msi Files</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-file-damage-enigma-winning-over-error-0x80070570-on-windows-11/"><u>Deciphering the File Damage Enigma - Winning Over Error 0X80070570 on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/command-line-convenience-with-windows-task-scheduler/"><u>Command Line Convenience with Windows Task Scheduler</u></a></li>
<li><a href="https://some-techniques.techidaily.com/explore-the-power-of-easy-video-editing-in-photos-and-windows-11-for-2024/"><u>Explore the Power of Easy Video Editing in Photos & Windows 11 for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/compact-guide-best-windows-forecasting-tools/"><u>Compact Guide: Best Windows Forecasting Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/directing-system-thermal-output-with-customization/"><u>Directing System Thermal Output with Customization</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-unleash-creativity-ranked-free-drawing-apps-for-mac/"><u>[Updated] Unleash Creativity  Ranked FREE Drawing Apps for Mac</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-win11s-cursor-blackout-quickly/"><u>Clearing Up Win11's Cursor Blackout Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-an-efficient-menu-choice-for-regular-system-checks-on-win11plus11/"><u>Crafting an Efficient Menu Choice for Regular System Checks on Win11+11</u></a></li>
<li><a href="https://howto.techidaily.com/why-your-honor-magic-6-lite-screen-might-be-unresponsive-and-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Your Honor Magic 6 Lite Screen Might be Unresponsive and How to Fix It | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-facebook-dating-for-your-vivo-v29e-drfone-by-drfone-virtual-android/"><u>How to Change Location On Facebook Dating for your Vivo V29e | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-6-ways-to-transfer-contacts-from-zte-nubia-flip-5g-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 6 Ways To Transfer Contacts From ZTE Nubia Flip 5G to iPhone | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-the-past-updating-decrepit-windows-cards/"><u>Clearing the Past: Updating Decrepit Windows Cards</u></a></li>
<li><a href="https://windows11.techidaily.com/cool-off-cycles-in-the-world-of-computers/"><u>Cool-Off Cycles in the World of Computers</u></a></li>
<li><a href="https://windows11.techidaily.com/defensive-operations-mastering-windows-unauthorized-prevention/"><u>Defensive Operations: Mastering Windows Unauthorized Prevention</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-after-effects-guide-to-elevating-song-visualization/"><u>In 2024, After Effects Guide to Elevating Song Visualization</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-privacy-protection-in-video-editing-top-face-blurring-techniques/"><u>New Privacy Protection in Video Editing Top Face Blurring Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-microsofts-window-file-format-cab-for-ease-of-use/"><u>Deciphering Microsoft's Window File Format (CAB) for Ease of Use</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-parsing-setback-code-0xc00ce556/"><u>Conquering Parsing Setback: Code 0xC00CE556</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/bridging-platforms-for-broad-sharing-instagram-and-facebook/"><u>Bridging Platforms for Broad Sharing  Instagram & Facebook</u></a></li>
<li><a href="https://windows11.techidaily.com/dealing-with-filehistoryfaults-in-windows-os/"><u>Dealing with FileHistoryFaults in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/command-your-way-through-windows-11-nircmd-tips-and-tricks/"><u>Command Your Way Through Windows 11: NirCmd Tips & Tricks</u></a></li>
<li><a href="https://extra-hints.techidaily.com/newbies-guide-to-vlogging-gear-and-software-insights/"><u>Newbie's Guide to Vlogging  Gear and Software Insights</u></a></li>
</ul></div>
