---
title: "Maximize Efficiency and Security: Enabling PowerShell Execution Policies"
date: 2024-10-26T16:59:12.696Z
updated: 2024-10-30T16:17:46.092Z
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
<a href="https://appsumo.8odi.net/c/5597632/2037319/7443" target="_top" id="2037319">
  <img src="//a.impactradius-go.com/display-ad/7443-2037319" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037319/7443" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948905/19272" target="_top" id="1948905">
  <img src="//a.impactradius-go.com/display-ad/19272-1948905" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948905/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137222/26400" target="_top" id="2137222">
  <img src="//a.impactradius-go.com/display-ad/26400-2137222" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137222/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657396/16446" target="_top" id="1657396">
  <img src="//a.impactradius-go.com/display-ad/16446-1657396" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657396/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://fox-glue.techidaily.com/updated-endless-buffering-solving-photo-booth-freezes-for-2024/"><u>[Updated] Endless Buffering Solving Photo Booth Freezes for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-fundamental-concepts-of-cyber-narratives/"><u>[Updated] Fundamental Concepts of Cyber Narratives</u></a></li>
<li><a href="https://discover-bits.techidaily.com/1-how-to-create-a-cloned-bootable-usb-on-any-system-windows-11-10-8-and-7/"><u>1. How to Create a Cloned Bootable USB on Any System: Windows 11, 10, 8 & 7</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-kickstart-your-earnings-with-periscope-strategies/"><u>2024 Approved Kickstart Your Earnings with Periscope Strategies</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/deciding-between-streaming-giants-roku-vs-fire-tv-stick-features-faceoff-to-help-you-decide/"><u>Deciding Between Streaming Giants: Roku vs Fire TV Stick, Features Faceoff to Help You Decide</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-management-issues-5-approaches-with-windows-11-focus/"><u>Fixing Management Issues: 5 Approaches with Windows 11 Focus</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-through-the-signature-verification-failure-of-windows-1011/"><u>Guide Through the Signature Verification Failure of Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/hide-your-wireless-signal-windows-techniques/"><u>Hide Your Wireless Signal: Windows Techniques</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-create-an-apple-developer-account-from-iphone-6s-plus-by-drfone-ios/"><u>In 2024, How To Create an Apple Developer Account From iPhone 6s Plus</u></a></li>
<li><a href="https://android-unlock.techidaily.com/mastering-lock-screen-settings-how-to-enable-and-disable-on-vivo-y36-by-drfone-android/"><u>Mastering Lock Screen Settings How to Enable and Disable on Vivo Y36</u></a></li>
<li><a href="https://fox-blue.techidaily.com/premium-picks-the-ultimate-gopro-upgrades-for-2024/"><u>Premium Picks The Ultimate Gopro Upgrades for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/retrace-to-original-directory-view-in-windows-11/"><u>Retrace to Original Directory View in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-your-system-save-big-keys-fans-black-friday-treat-for-windows-11/"><u>Secure Your System, Save Big - Keys Fan's Black Friday Treat for Windows 11</u></a></li>
<li><a href="https://app-tips.techidaily.com/security-alert-kaspersky-password-manager-revealed-by-zdnet-for-creating-weak-brute-force-susceptible-passwords/"><u>Security Alert: Kaspersky Password Manager Revealed by ZDNet for Creating Weak, Brute-Force Susceptible Passwords</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solving-audio-driver-errors-in-your-dell-system-on-windows-83647-easily/"><u>Solving Audio Driver Errors in Your Dell System on Windows #8364;7 Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-cooling-computers-running-hot-w11/"><u>Steps for Cooling Computers Running Hot W11</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-a-shimmering-window-title-bar-in-win11/"><u>Tips for A Shimmering Window Title Bar in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-a-non-operational-media-player-in-windows-11/"><u>Troubleshooting a Non-Operational Media Player in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-disappearing-windows-screen/"><u>Troubleshooting Disappearing Windows Screen</u></a></li>
</ul></div>

