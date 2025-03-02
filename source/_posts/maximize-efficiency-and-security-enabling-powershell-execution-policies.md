---
title: "Maximize Efficiency and Security: Enabling PowerShell Execution Policies"
date: 2025-02-26T18:49:59.402Z
updated: 2025-03-02T08:24:13.617Z
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

## How to Remove Script Execution Policy Using PowerShell

![set-execution-policy-undefined](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/set-execution-polify-undefined.jpg)

 If you want to disable script execution, set the execution policy to**Undefined** using th**e Set\_ExecutionPolicy** cmdlet. This is a default state and prevents PowerShell from executing any scripts.

To disable script execution using PowerShell:

1. Open PowerShell with elevated permission.
2. Next, type the following command and press enter to disable script execution for all users:  
`Set-ExecutionPolicy undefined`
3. The above command will set the execution policy default (undefined) for all the users. If you want to disable script execution for a specific scope, use the following command:  
`Set-ExecutionPolicy undefined -Scope CurrentUser`
4. The above command will disable script execution for**CurrentUser** .

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
<li><a href="https://youtube-tips.techidaily.com/n-2024-engage-audiences-writing-magical-youtube-description-templates-for-higher-views/"><u>[New] In 2024, Engage Audiences Writing Magical YouTube Description Templates for Higher Views</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/rofitability-playbook-the-ultimate-duo-of-dm-and-yo/"><u>[New] Profitability Playbook The Ultimate Duo of Dm & Yo</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-live-link-luxuries-are-codes-more-crucial-than-cables-in-2024/"><u>[Updated] Live Link Luxuries Are Codes More Crucial Than Cables, In 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/elevated-privileges-needed-resolving-operation-requires-elevation-errors-in-windows-11-10-and-7/"><u>Elevated Privileges Needed: Resolving 'Operation Requires Elevation' Errors in Windows 11, 10 & 7</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-lava-yuva-3-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Lava Yuva 3 to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-6-best-sim-unlock-services-that-actually-work-on-your-infinix-note-30-vip-device-by-drfone-android/"><u>In 2024, The 6 Best SIM Unlock Services That Actually Work On Your Infinix Note 30 VIP Device</u></a></li>
<li><a href="https://technical-tips.techidaily.com/labor-day-special-secure-your-home-with-the-affordable-blink-outdoor-amera-and-lightning-mount-combo-at-only-80-shop-now/"><u>Labor Day Special: Secure Your Home with the Affordable Blink Outdoor Amera and Lightning Mount Combo at Only $80 - Shop Now!</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-efficiency-your-ultimate-guide-to-wsl-2-and-docker/"><u>Maximizing Efficiency: Your Ultimate Guide to WSL 2 & Docker</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstating-windows-notification-banners/"><u>Reinstating Windows Notification Banners</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-windows-11-setup-without-internet/"><u>Step-by-Step: Windows 11 Setup Without Internet</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-printer-service-disabled-message-in-winos/"><u>Tackling Printer Service Disabled Message in WinOS</u></a></li>
<li><a href="https://some-skills.techidaily.com/ultimate-microphone-selection-for-high-res-video-shooting-for-2024/"><u>Ultimate Microphone Selection for High-Res Video Shooting for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-the-other-users-microsoft-account-problem/"><u>Unblocking the Other User’s Microsoft Account Problem</u></a></li>
<li><a href="https://windows11.techidaily.com/win-storage-management-finding-and-reducing-high-space-items/"><u>Win Storage Management: Finding and Reducing High-Space Items</u></a></li>
</ul></div>

