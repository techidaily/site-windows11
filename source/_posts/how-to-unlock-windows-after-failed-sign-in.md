---
title: How to Unlock Windows After Failed Sign-In
date: 2025-01-21T16:00:42.688Z
updated: 2025-01-22T20:23:21.860Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Unlock Windows After Failed Sign-In
excerpt: This Article Describes How to Unlock Windows After Failed Sign-In
keywords: Locked Windows Fix,Sign In Failure Resolve,Windows Unlock Methods,Bypass Login Errors,Access Denied Windows,Safe Mode for Windows,Reset Windows Passwords
thumbnail: https://thmb.techidaily.com/05a2bebe19d9c7fab4bc3ec91fa821946b0580297afafdcde864123fe0ad252d.jpg
---

## How to Unlock Windows After Failed Sign-In

 A PIN is a convenient way to sign into your computer. However, when you try to sign in with a PIN, you may encounter the "this sign-in option is disabled because of failed sign-in attempts" error. This is followed by a message asking you to use a different sign-in method or wait for 2 hours and try again.

 Windows may show this error for various reasons, including a temporary glitch, corrupted login PIN, or incorrect account configuration. Here, we guide you through a few troubleshooting steps to resolve the error and regain access to your computer.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RCYs8keh-Vs?si=uDC28-9yh-k6HLj4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Causes the "Sign-In Option Is Disabled Because of Failed Sign-In Attempts" Error?

 The error message indicates the possible causes for the error are multiple failed sign-in attempts or repeated shutdowns. However, in most instances, the error pops up without reason, even when you are using the correct PIN.

 To bypass this error, you can sign in using a different login option, such as a password. If you don't have a password, you'll need to wait at least 2 hours before attempting to sign in again.

 The exact reason for the issue is unknown. What we do know is that Windows uses a dictionary attack mitigation feature to prevent threat actors from breaking into your computer to gain unauthorized. When triggered, Windows will temporarily ignore the provided authorization, which, in this instance, is your sign-in PIN.

 Furthermore, common contributing factors to this error include a recent Windows upgrade, a corrupted login PIN or user profile, or a damaged Windows image.

 Fortunately, you can fix this error by resetting the login PIN and a registry tweak to disable the account lockout option. Follow all the steps in the given order, and you should be able to fix the error and log in to your Windows computer.

## 1\. Keep Your Device Powered On for Two Hours

 If you don't have an alternate sign-in option enabled or have forgotten the password, you'll need to wait for two hours and then try to sign in again with the sign-in PIN. Make sure your PC remains turned on for two hours for it to work.

 The two-hour cooling period seemingly comes with strings attached. Once you see the wait for two hours message after entering the PIN, reboot your computer. When the login screen appears, don't sign in immediately. Wait for two hours and then put in your PIN to sign in.

 That said, if you can't wait for two hours, try to log in using an alternate sign-in option, such as a password or biometric authentication. To use the alternate sign-in option, click the dotted icon under the Sign-in options in the error screen to log in with your password.

## 2\. Reset the Account Password from the Sign-In Screen

 If you have forgotten your password, you can reset your sign-in password from the sign-in screen. To confirm the authenticity of the user, Windows will need you to answer the security questions correctly to perform a reset.

 In some instances, Windows may prompt you to sign in with your Microsoft account password and send a 4-digit code to your backup email address to authenticate the password reset attempt.

 To reset a Windows account password:

1. On the login screen, type any password and hit **Enter**. Windows will show the password as incorrect; click **OK**.
2. Next, click the **Reset password** option.  
![reset account password security question windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/reset-account-password-security-question-windows.jpg)
3. Now, you must answer the three security questions and press **Enter**. If the password is correct, a password reset option will appear.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Dn-24B6AURY?si=ErES2KWVnintY6h9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![reset account password windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/reset-account-password-windows.jpg)
4. Enter your new password and then re-enter the password to confirm the same.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/NTQGoOOiJzs?si=zbZwflEfXgBY3qbs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Press **Enter** to sign-in to your user account.

 After a successful login, you can reset your PIN, disable the sign-in attempt threshold, and check the user profile configuration to see if your account is disabled. Needless to say, you must be signed to apply this fix.

 If you can't sign in, use a different user account on your computer and follow the steps below. If you have forgotten the account password, follow this resource to [reset a forgotten Windows administrator password](https://www.makeuseof.com/tag/3-ways-to-reset-the-forgotten-windows-administrator-password/).

 If you don't have an alternate user account setup, [enable the built-in administrator account in Windows 11](https://www.makeuseof.com/windows-11-enable-disable-built-in-administrator-account/). Skip to the later part of the article that shows how to enable the built-in administrator account without the need to sign in.

 Once you can sign in, follow these steps to check your account status.

## 3\. Check Your Account Status Using Local Users and Groups

 Windows system administrators can manage user accounts and groups on a local computer using the Microsoft Management Console (MMC) snap-in, Local User, and Groups. To fix the problem, check if the account is configured as locked or disabled in the account properties.

 Local Users and Groups is only available on the Pro and Enterprise edition of the OS. If you are using Home, skip to the next solution.

1. Press **Win + R** to open Run.
2. Type **lusrmgr.msc** and click **OK**. This will open the **Local User and Groups** snap-in.
3. Double-click on the **Users** folder.
4. Locate and right-click on your user account name.  
![local users and groups account properties windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/local-users-and-groups-account-peroperties-windows.jpg)
5. Next, select **Properties**.  

![local users and groups unselect account is disabled account is locked out](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/local-users-and-groups-unselect-account-is-disabled-account-is-locked-out.jpg)
6. In the **Properties** dialog, open the **General** tab.

7. Here, uncheck Account is disabled, and Account is locked out option.
8. Click **Apply** and **OK** to save the changes.

 If both the options are already unchecked, proceed to the next solution.

## 4\. Reset the Windows Account PIN

 Assuming the problem is due to a corrupt account PIN, a PIN reset can help you fix the problem. You can [change your account PIN in Windows](https://www.makeuseof.com/change-account-pin-windows/) from the Settings app. You'll need to authenticate the PIN change process with your current PIN, so keep that handy.

 If you have forgotten your PIN, use the I forgot my PIN option to reset your PIN using your Microsoft account. After resetting the PIN, log in with the new PIN and check if the error is resolved.

 If that doesn't work, run the following batch script to remove Pin for all users. However, you must be signed in with an administrator account to execute this script. Here's how to do it.

1. Open the Notepad app. Search for **Notepad** in Windows search and open the app.  
![script remove pin win user account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/sccript-remove-pin-win-user-account.jpg)
2. Next, copy and paste the following script into the Notepad file:  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PUDdKOsEN74?si=tkZf-KVinjuwmgx9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`@echo off  
powershell -windowstyle hidden -command "Start-Process cmd -ArgumentList'/s,/c,'  
'takeown /f C:\Windows\ServiceProfiles\LocalService\AppData\Local\Microsoft\NGC /r /d y'  
'& icacls C:\Windows\ServiceProfiles\LocalService\AppData\Local\Microsoft\NGC /grant administrators:F /t'  
'& RD /S /Q C:\Windows\ServiceProfiles\LocalService\AppData\Local\Microsoft\Ngc'  
' & MD C:\Windows\ServiceProfiles\LocalService\AppData\Local\Microsoft\Ngc'  
'& icacls C:\Windows\ServiceProfiles\LocalService\AppData\Local\Microsoft\Ngc /T /Q /C /RESET'  
"-Verb runAs  
`
3. Press **Ctrl + S** to open the Save dialog and name the file **Remove-Win-Account-PIN.bat**.  
![save remove win account pin batch script](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/save-remove-win-account-pin-batch-script.jpg)
4. Next, click the **Save as type** drop-down and select **All files**.

5. Click **Save** to create the batch script.

 To execute the script, double-click on it and click Yes when prompted by User Account Control.

 Upon execution, the script will PIN for all the user accounts on your computer. Once done, you can [set up a new PIN for your user account on Windows](https://www.makeuseof.com/setup-remove-pin-windows-11/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OdlXe5RELW0?si=Iz1H1QnLQVw-Eu3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Change the Account Lockout Threshold Policy

 Like the dictionary attack mitigation feature, the administrator can configure a local computer to specify the maximum number of incorrect login attempts. This is done by modifying the Account lockout threshold policy in Group Policy Editor.

 Similar to Local Users and Groups, by default, the Group Policy Editor is only available on the Pro, Enterprise, and Education editions of the Windows operating system. While not included out of the box, you can still [enable Group Policy Editor in Windows Home using a batch script hack](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To change the Account Lockout Policy:

1. Press **Win + R** to open **Run.**
2. Type **gpedit.msc** and click **OK** to open the **Group Policy Editor**.
3. Next, in Group Policy Editor, navigate to the following location:  
`Computer Configuration\Windows Settings\Security Settings\Account Policies\Account Lockout Policy`
4. In the right pane, double-click on **Account lockout threshold**.  
![account lockout threshold gpedit windows modify](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/account-lockout-threshold-gpedit-windows-modify.jpg)
5. Type **0** in the **Account will not lock out** field.  

![account lockout threshold gpedit windows modify o value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/account-lockout-threshold-gpedit-windows-modify-o-value.jpg)
6. Click **Apply** and **OK** to save the changes.

## 6\. Edit the Account Lockout Policy Using Registry Editor

 You can also configure the account lockout policy on your machine via the Windows Registry. It is also helpful if you are using the Windows Home edition without Group Policy Editor.

 Making modifications to the Windows Registry involves risk.[Create a restore point](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) and [make a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before applying any changes to the registry entries.

 To change the Account Lockout policy in Registry Editor:

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK** to open **Registry Editor**.
3. In Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\RemoteAccess\Parameters\AccountLockout`
4. In the right pane, locate and right-click on **MaxDenials**.  
![modify Maxdenials registry DWORD value registry editor 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/modify-maxdenials-registry-dword-value-registry-editor-1.jpg)
5. Select **Modify**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LW6wNx3XAj8?si=VaIuFIIx8MM_RhUR" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![modify Maxdenials registry DWORD value registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/modify-maxdenials-registry-dword-value-registry-editor.jpg)
6. Type **0** in the **Value data** field and click **OK** to save the changes.

7. Close Registry Editor and reboot your computer to apply the changes.

 After the restart, you can sign in without receiving the sign-in is disabled notification. If the issue persists, [try to clear the TPM on Windows](https://www.makeuseof.com/clear-tpm-windows-11/). This can be a tricky solution depending on how your account is set up. Clearing TPM may lock you out of your computer. Attempt this only if you have a password-based sign-in option enabled.

 If all else fails, try third-party recovery tools like the Trinity Rescue Kit. It is a useful little utility that can help you reset your password.

## Resolving the "Disabled Sign-In Options Due to Failed Attempts" Error on Windows

 Windows 10 and 11 computers can act up and lock you out of your system due to a glitch or system malfunction. However, you can bypass this cooling period by signing in with an account password or a PIN reset.

 Windows may show this error for various reasons, including a temporary glitch, corrupted login PIN, or incorrect account configuration. Here, we guide you through a few troubleshooting steps to resolve the error and regain access to your computer.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-sharing-excellence-twitch-live-to-your-facebook-circle/"><u>[New] In 2024, Sharing Excellence Twitch Live to Your Facebook Circle</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-in-2024-from-dull-to-dynamic-adding-animated-effects-to-instagram-stories/"><u>[Updated] In 2024, From Dull to Dynamic Adding Animated Effects to Instagram Stories</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-precision-based-adjustments-for-maximum-impact-on-instagram-tv/"><u>[Updated] In 2024, Precision-Based Adjustments for Maximum Impact on Instagram TV</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-laughterbox-easy-entry-endless-entertainment/"><u>[Updated] LaughterBox Easy Entry, Endless Entertainment</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-streamlined-design-integrating-gamers-banner-templates/"><u>[Updated] Streamlined Design Integrating Gamers' Banner Templates</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/approved-rapid-rise-to-affiliate-hit-the-pivotal-10000-view-mark/"><u>2024 Approved Rapid Rise to Affiliate Hit the Pivotal 10,000 View Mark</u></a></li>
<li><a href="https://tech-revival.techidaily.com/chatgpt-and-your-writing-potential-pitfalls-of-automated-text-summary-services/"><u>ChatGPT and Your Writing: Potential Pitfalls of Automated Text Summary Services</u></a></li>
<li><a href="https://win-dash.techidaily.com/drying-processes-reduce-woods-moisture-content-affecting-its-thermal-properties-and-potentially-its-density-if-cellular-structure-collapses/"><u>Drying Processes Reduce Wood's Moisture Content, Affecting Its Thermal Properties and Potentially Its Density if Cellular Structure Collapses</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-bluescreenview-an-in-depth-analysis/"><u>Leveraging BlueScreenView - An In-Depth Analysis</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-error-code-0xc00ce556-in-windows/"><u>Navigating the Error Code 0xC00CE556 in WINDOWS</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-audiovisual-integration-incorporating-audio-waveform-and-creative-animation-into-davinci-resolve/"><u>New Audiovisual Integration Incorporating Audio Waveform and Creative Animation Into DaVinci Resolve</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-and-slim-filesystem-setting-up-auto-delete-in-win11/"><u>Secure and Slim Filesystem: Setting Up Auto Delete in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/simplified-approach-to-batch-convert-heic-files-to-jpeg-in-windows-11/"><u>Simplified Approach to Batch Convert HEIC Files to JPEG in Windows 11</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/simplifying-tough-professional-communications-with-gpt-3/"><u>Simplifying Tough Professional Communications with GPT-3</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshoot-unresponsive-inputs-when-waking-up-win11/"><u>Troubleshoot Unresponsive Inputs When Waking up Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-steam-friendship-disconnect-on-pc/"><u>Troubleshooting Steam Friendship Disconnect on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-potential-top-winning-apps-from-ms-store-2023/"><u>Unleash Potential: Top Winning Apps From MS Store, 2023</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-your-pc-easily-windows-hello-fingerprint-guide/"><u>Unlock Your PC Easily: Windows Hello Fingerprint Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-blue-screen-mystery-0xc0000001/"><u>Unraveling Blue Screen Mystery - 0xC0000001</u></a></li>
</ul></div>

