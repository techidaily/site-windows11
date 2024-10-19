---
title: How to Enable and Utilize the Script Execution Policy in Windows PowerShell
date: 2024-10-11T17:05:36.668Z
updated: 2024-10-18T20:33:11.123Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Enable and Utilize the Script Execution Policy in Windows PowerShell
excerpt: This Article Describes How to Enable and Utilize the Script Execution Policy in Windows PowerShell
keywords: PowerShell Execution Control,Disable Script Risks,Windows Security Policies,Running PowerShell Scripts,Enhance Script Safety,Policy Script Activation,Secure PowerShell Usage
thumbnail: https://thmb.techidaily.com/6612d7a6b7e8b44ce845a24c9c71af5e69ea9f37b5bedb688c03953f127445f3.jpg
---

## How to Enable and Utilize the Script Execution Policy in Windows PowerShell

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

## How to Allow Scripts to Run in PowerShell using PowerShell

![Powershell set execcution policy remotesigned](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/powershell-set-execcution-policy-remotesigned.jpg)

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137976/21526" target="_top" id="2137976">
  <img src="//a.impactradius-go.com/display-ad/21526-2137976" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137976/21526" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139110/17108" target="_top" id="2139110">
  <img src="//a.impactradius-go.com/display-ad/17108-2139110" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139110/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Remove Script Execution Policy Using PowerShell

![set-execution-policy-undefined](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/set-execution-polify-undefined.jpg)

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398455/3022" target="_top" id="398455">
  <img src="//a.impactradius-go.com/display-ad/3022-398455" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398455/3022" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://bluettius.sjv.io/c/5597632/2139112/17108" target="_top" id="2139112">
  <img src="//a.impactradius-go.com/display-ad/17108-2139112" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139112/17108" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-freeing-up-youtube-views-no-more-grey-lines/"><u>[New] In 2024, Freeing Up YouTube Views No More Grey Lines</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/comprehensive-computer-tech-evaluations-by-toms-hardware-experts/"><u>Comprehensive Computer Tech Evaluations by Tom's Hardware Experts</u></a></li>
<li><a href="https://fox-that.techidaily.com/diy-fixes-how-to-enable-non-compatible-iphone-accessories/"><u>DIY Fixes: How to Enable Non-Compatible iPhone Accessories</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-sign-a-xltx-document-online-by-ldigisigner-sign-a-excel-sign-a-excel/"><u>How to sign a .xltx document online</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-solve-microsoft-office-365-glitches-error-30015-26/"><u>How to Solve Microsoft Office 365 Glitches: Error 30015-26</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-itel-p55t-to-outlook-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from Itel P55T to Outlook | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-teach-you-to-transfer-files-from-poco-c51-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways To Teach You To Transfer Files from Poco C51 to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/inverse-viewing-in-youtube-original-ideas-for-rewinders/"><u>Inverse Viewing in YouTube Original Ideas for Rewinders</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-resolve-non-installed-windows-store-apps/"><u>Methods to Resolve Non-Installed Windows Store Apps</u></a></li>
<li><a href="https://vp-tips.techidaily.com/1726227057768-movavi/"><u>Movavi 影片編碼器 - 完整免費版本可立即下載</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/pokemon-go-error-12-failed-to-detect-location-on-nubia-red-magic-8s-pro-drfone-by-drfone-virtual-android/"><u>Pokemon Go Error 12 Failed to Detect Location On Nubia Red Magic 8S Pro? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/tidy-up-win11-desktop-by-removing-highlighted-icon/"><u>Tidy up Win11 Desktop by Removing Highlighted Icon</u></a></li>
<li><a href="https://windows11.techidaily.com/tidying-up-your-pc-a-compact-guide-to-uninstallation-in-windows-11-108-chars/"><u>Tidying Up Your PC: A Compact Guide to Uninstallation in Windows 11 (108 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/top-7-sketch-tools-on-windows-11/"><u>Top 7 Sketch Tools on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-steps-for-reclaiming-lost-vpn-links-in-winpc/"><u>Unveiling Steps for Reclaiming Lost VPN Links in WinPC</u></a></li>
</ul></div>

