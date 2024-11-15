---
title: "Maximize Efficiency and Security: Enabling PowerShell Execution Policies"
date: 2024-11-08T17:20:25.169Z
updated: 2024-11-15T16:36:46.978Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Maximize Efficiency and Security: Enabling PowerShell Execution Policies"
excerpt: "This Article Describes Maximize Efficiency and Security: Enabling PowerShell Execution Policies"
keywords: PowerShell Efficiency,Secure Policy Control,Execution Policy Management,PowerShell Security,Optimize PS Scripts,Enhanced Policy Settings,PowerShell Policy Safety
thumbnail: https://thmb.techidaily.com/b918b2416ccc3c3bc24e5dbb4922efd59cd6316c83a82113344d8ae306f1223c.jpg
---

## Maximize Efficiency and Security: Enabling PowerShell Execution Policies

 iPowerShell, by default, lets you run commands (cmdlets) via its console. To execute a script, you can create a notepad file with the script code, save it with a .ps1 file extension, and execute it via the PowerShell console. You can also directly paste the script onto the console for execution.

 However, if it’s your first time executing a script via PowerShell, you’ll encounter the "running script is disabled" error. By default, script execution on PowerShell is disabled as a security measure to prevent malicious scripts from running on your system. Here we show you the two ways to enable the scrip execution policy on Windows PowerShell.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Check Your Existing Execution Policy

![Powershell set execution policy undefined](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/powershell-set-execcution-policy-undefined.jpg)

 You can use a PowerShell cmdlet to get your current execution policy. Knowing your current execution policy is necessary to know if you need a policy change or not.

To get your current execution policy for the current user:

1. [Open Windows PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. Type the following command in the PowerShell console and hit Enter:  
`get-executionpolicy`
3. Since you have encountered an error when executing the script, the return will likely show**Restricted** as your current execution policy.
4. If you need to view the execution policy for all the supported scopes:  
`get-executionpolicy -list`

 You’ll need to change the execution policy to RemoteSigned to run local scripts without the error. You can change the execution policy from the Settings app and PowerShell.

## How to Enable PowerShell Execution Policy Using the Settings App

 You can change and set the PowerShell execution policy to RemoteSigned using the Settings app. All you have to do is tweak the PowerShell settings in the developers' section to change the execution policy to enable PowerShell script execution.

To change execution policy using Settings:

1. Press**Win + I** to open Se**t** tings.
2. Open the**Privacy & Security** tab in the left pane.
3. Next, click on**For developers.**  
![windows 11 for developers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-for-developers.jpg)
4. Click to expand the**PowerShell** section.

5. Toggle the switch to **change the execution policy to allow local PowerShell scripts to run without signing - Require signing for remote scripts** .  
![enable powershell script execution windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-powershell-script-execution-windows-11-settings.jpg)
6. Once done, open PowerShell, type get**executionpolicy,** and press**Enter** . The execution policy for the current user is now set to**RemoteSigned.**

7. If you need to disable the execution policy, toggle the PowerShell switch and set it to**Off** .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997648/19272" target="_top" id="1997648">
  <img src="//a.impactradius-go.com/display-ad/19272-1997648" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997648/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Allow Scripts to Run in PowerShell using PowerShell

![Powershell set execcution policy remotesigned](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/powershell-set-execcution-policy-remotesigned.jpg)

 You can use a[PowerShell cmdlet](https://www.makeuseof.com/windows-powershell-commands-cmdlets/) to set the execution policy to RemoteSigned. The command-line interface makes it easy to change execution policy quickly without using the Settings app.

 Also, the Settings app can only enable or disable the RemoteSigned execution policy. Whereas PowerShell lets you set other policies and scopes as well.

To change the execution policy using PowerShell:

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Set-ExecutionPolicy RemoteSigned`
3. If prompted, press**A** to confirm the action. This will set the**RemoteSigned** execution policy for all users. If you want to set the execution policy for the**Current User** only, use the Scope parameter followed by the username.
4. For example, to set the**RemoteSigned** execution policy for**CurrentUser** , use the following command:  
`Set-ExecutionPolicy RemoteSgined -Scope CurrentUser`
5. Replace**CurrentUser** in the above command with other users (Scope) as per your requirement.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151865/7443" target="_top" id="2151865">
  <img src="//a.impactradius-go.com/display-ad/7443-2151865" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151865/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Remove Script Execution Policy Using PowerShell

![set-execution-policy-undefined](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/set-execution-polify-undefined.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123738/7443" target="_top" id="2123738">
  <img src="//a.impactradius-go.com/display-ad/7443-2123738" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123738/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you want to disable script execution, set the execution policy to**Undefined** using th**e Set\_ExecutionPolicy** cmdlet. This is a default state and prevents PowerShell from executing any scripts.

To disable script execution using PowerShell:

1. Open PowerShell with elevated permission.
2. Next, type the following command and press enter to disable script execution for all users:  
`Set-ExecutionPolicy undefined`
3. The above command will set the execution policy default (undefined) for all the users. If you want to disable script execution for a specific scope, use the following command:  
`Set-ExecutionPolicy undefined -Scope CurrentUser`
4. The above command will disable script execution for**CurrentUser** .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529">
  <img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Understanding Execution Policies and Scopes

 Simply put, PowerShell’s execution policy is a policy that controls how PowerShell executes config files and scripts. The intended purpose is to prevent users from accidentally running malicious scripts. The seven PowerShell execution policies are **Default, Restricted, RemoteSigned, AllSigned, Unrestricted, Bypass, and Undefined** .

 The below table briefly explains all the PowerShell execution policies:

| Execution Policy | Enforcement                                                                                                    |
| ---------------- | -------------------------------------------------------------------------------------------------------------- |
| Default          | Sets the default execution policy as Restricted on Windows Client and RemoteSigned on Windows Server.          |
| AllSigned        | Allows execution of publisher signed scripts.                                                                  |
| Bypass           | Unrestricted execution of scripts for larger applications.                                                     |
| RemoteSigned     | Allows locally written script execution. Requires digital signatures for scripts downloaded from the internet. |
| Restricted       | Doesn’t allow script execution, but only individual PowerShell commands.                                       |
| Undefined        | Sets execution policy to Restricted for Windows clients and RemoteSigned for Windows Server.                   |
| Unrestricted     | Allow unsigned script execution with a warning for the scripts downloaded from the internet.                   |

### Execution Policy Scope

 You can set execution policy for a particular scope in PowerShell. The five execution policy scopes are**MachinePolicy, UserPolicy, Process, CurrentUser,** and**LocalMachine** .

The below table briefly explains all the execution policy scopes:

| Execution Policy Scope | Enforcement                                                                              |
| ---------------------- | ---------------------------------------------------------------------------------------- |
| UserPolicy             | Configured by a Group Policy for the current user.                                       |
| Machine Policy         | Configured by a Group Policy for all the users.                                          |
| CurrenUser             | Configured for the current user and stored in HKEY\_CURRENT\_MACHINE registry subkey.    |
| LocalMachine           | Configured for all users and stored in HKEY\_CURRENT\_MACHINE registry subkey.           |
| Process                | Affects current PowerShell session and automatically deleted when the session is closed. |

## Add or Remove PowerShell Script Execution Policy on Windows

 Script execution on PowerShell is disabled by default for Windows clients and set to RemoteSigned for Windows server. Power users, however, can change execution policies to run local, signed, and unsigned PowerShell scripts.

 Alternatively, you can bypass the PowerShell execution policy by pasting the script into a PowerShell console or ECHO your script into PowerShell standard input. This is useful if you want to execute scripts without changing the execution policy.

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
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-avoid-the-fake-out-maintaining-authenticity-in-likes/"><u>[Updated] 2024 Approved Avoid the Fake-Out Maintaining Authenticity in Likes</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-mastering-the-mix-of-sound-and-slides-in-powerpoint-presentations/"><u>[Updated] Mastering the Mix of Sound and Slides in PowerPoint Presentations</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-the-leaderboard-of-the-best-web-capture-apps/"><u>2024 Approved The Leaderboard of the Best Web Capture Apps</u></a></li>
<li><a href="https://tech-hub.techidaily.com/5bcc6zaa5a6244gm6yg444g244cb44k544og44os44kq5yyw44gx44gm44gp44km44kl44ov44oq44o86zplusz5qw95asj5oplusb44oe44o844oriq/"><u>専門家が選ぶ、ステレオ化してくれるフリー音楽変換ツール!</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/elite-uploader-mp4-files-directly-for-fb/"><u>Elite Uploader MP4 Files Directly for FB</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-hidefake-snapchat-location-on-your-realme-narzo-n55-drfone-by-drfone-virtual-android/"><u>How to Hide/Fake Snapchat Location on Your Realme Narzo N55 | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-quick-guide-capturing-video-and-audio-from-youtube/"><u>In 2024, Quick Guide Capturing Video & Audio From YouTube</u></a></li>
<li><a href="https://tech-hub.techidaily.com/labor-day-tech-bonanza-snag-the-latest-ipad-pro-for-a-whopping-700-discount-at-zdnets-special-promotion/"><u>Labor Day Tech Bonanza! Snag the Latest iPad Pro for a Whopping $700 Discount at ZDNet's Special Promotion</u></a></li>
<li><a href="https://windows11.techidaily.com/modify-winterrals-theme-picture/"><u>Modify WinTerral's Theme Picture</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-to-overcome-the-errortoomanypatterns-in-wsl/"><u>Quick Fixes to Overcome the ERROR_TOO_MANY_PATTERNS in WSL</u></a></li>
<li><a href="https://fox-blue.techidaily.com/refinement-of-screen-focus-how-to-zoom-on-microsoft-teams/"><u>Refinement of Screen Focus How to Zoom on Microsoft Teams</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-unsuccessful-discord-updates-for-windows-users/"><u>Resolving Unsuccessful Discord Updates for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/seven-strong-points-that-make-windows-10-preferable-over-win11/"><u>Seven Strong Points That Make Windows 10 Preferable over Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-note-management-on-obsidian-canvas/"><u>The Art of Note Management on Obsidian Canvas</u></a></li>
<li><a href="https://windows11.techidaily.com/voice-commands-mastery-keyboard-shortcut-compendium-on-win-11/"><u>Voice Commands Mastery: Keyboard Shortcut Compendium on Win 11</u></a></li>
</ul></div>

