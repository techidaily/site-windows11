---
title: "Maximize Efficiency and Security: Enabling PowerShell Execution Policies"
date: 2024-10-05T04:08:19.167Z
updated: 2024-10-07T05:59:57.284Z
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
<a href="https://aligracehair.sjv.io/c/5597632/1959773/19272" target="_top" id="1959773">
  <img src="//a.impactradius-go.com/display-ad/19272-1959773" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959773/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Allow Scripts to Run in PowerShell using PowerShell

![Powershell set execcution policy remotesigned](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/powershell-set-execcution-policy-remotesigned.jpg)

<!-- affiliate ads begin -->
<span id="1975636">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975636.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975636">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975636.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975636%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975636/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

## How to Remove Script Execution Policy Using PowerShell

![set-execution-policy-undefined](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/set-execution-polify-undefined.jpg)

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1166360/14483" target="_top" id="1166360">
  <img src="//a.impactradius-go.com/display-ad/14483-1166360" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://electronicx.pxf.io/i/5597632/1166360/14483" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2135393/19272" target="_top" id="2135393">
  <img src="//a.impactradius-go.com/display-ad/19272-2135393" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135393/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://twitter-videos.techidaily.com/new-breaking-tiktok-trends-twitters-1-list-unveiled/"><u>[New] Breaking TikTok Trends Twitter's #1 List Unveiled</u></a></li>
<li><a href="https://article-files.techidaily.com/new-hardware-hurdles-whats-necessary-for-big-sur/"><u>[New] Hardware Hurdles What's Necessary for Big Sur?</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-mastering-instagram-filters-applying-them-to-old-memories/"><u>[Updated] 2024 Approved Mastering Instagram Filters Applying Them to Old Memories</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-googles-ar-stickers-an-overview-with-comparison-to-rival-products/"><u>[Updated] Google's AR Stickers An Overview with Comparison to Rival Products</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-mkv-mastery-best-mac-app-compilation/"><u>[Updated] MKV Mastery Best Mac App Compilation</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-youtubing-green-magic-ideas-that-come-to-life-for-2024/"><u>[Updated] Youtubing Green Magic – Ideas That Come to Life for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/5-ways-to-reset-samsung-galaxy-a14-4g-without-volume-buttons-drfone-by-drfone-reset-android-reset-android/"><u>5 Ways to Reset Samsung Galaxy A14 4G Without Volume Buttons | Dr.fone</u></a></li>
<li><a href="https://win-amazing.techidaily.com/how-to-quickly-obtain-your-easycap-drivers-for-free/"><u>How to Quickly Obtain Your EasyCAP Drivers for Free</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-card-on-tecno-pop-7-pro-online-without-jailbreak-by-drfone-android/"><u>How to Unlock SIM Card on Tecno Pop 7 Pro online without jailbreak</u></a></li>
<li><a href="https://windows11.techidaily.com/maintaining-originality-of-windows-safescreensaver/"><u>Maintaining Originality of Windows SafeScreensaver</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-from-digital-songs-to-physical-cds-using-imgburn-windows-for-mp3-conversion/"><u>Quick Guide: From Digital Songs to Physical CDs - Using ImgBurn (Windows) for Mp3 Conversion</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-systems-crafting-a-window-11-routine-with-controlled-downtime-and-updates/"><u>Seamless Systems: Crafting a Window 11 Routine with Controlled Downtime and Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-your-workspace-with-enabled-wsl-in-windows/"><u>Tailoring Your Workspace with Enabled WSL in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-clear-sound-top-5-free-windows-cutters/"><u>Unleash Clear Sound: Top 5 Free Windows Cutters</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-full-potential-install-and-configure-wsl/"><u>Unlocking Full Potential: Install and Configure WSL</u></a></li>
</ul></div>

