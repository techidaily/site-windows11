---
title: Recover Lost PIN Following System Breakdown on Windows 11
date: 2024-06-25T12:26:00.770Z
updated: 2024-06-26T12:26:00.770Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Recover Lost PIN Following System Breakdown on Windows 11
excerpt: This Article Describes Recover Lost PIN Following System Breakdown on Windows 11
keywords: Lost PIN Recovery,Windows 11 Fix,System Breakdown Troubleshooting,PIN Security Recovery Steps,Restore Lost Windows Credentials,Breakdown Fix Guide,Data Recovery for PC Users
thumbnail: https://thmb.techidaily.com/459b794516e41ca817af82c1c22066d193c455f4891dd7a8e040210befb5bf6c.jpg
---

## Recover Lost PIN Following System Breakdown on Windows 11

 On Windows 10 and 11, you can log in with a password or PIN. On compatible systems, you can also use iris scan and fingerprint unlock. While a PIN makes the login process faster than a password, you may encounter the Something happened and your PIN isn't available error when trying to sign in using the same.

 Similarly, something went wrong and your PIN isn't available (status: 0xc000006d) is another variation of the error. These errors are often triggered due to a bad security update, issues with the NGC folder, and system file corruption.

 Here are a few troubleshooting steps to help you fix this errorand log in with your PIN successfully on Windows 11.

## 1\. Login With the Account Password

 If you have set up a Microsoft user account or local user account, you can use it to log in with a password. Once done, you can reset the login PIN to fix the problem. Here's how to do it.

 Note that the below steps will not work for Microsoft account if you have enabled the **Only allow Windows Hello sign-in for Microsoft account on this device** option.

1. On the lock screen, press any key to view the**Sign-in** screen.
2. Next, click on**Sign-in options** to view the available options.  
![sign in options windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sign-in-options-windows-11.jpg)
3. Click the**Key** icon to select the**password sign-in** option.  
![sign in options windows 11 password](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sign-in-options-windows-11-password.jpg)
4. Type in your password and press**Enter** to log in.

 Now that you can log in to your account, follow these steps to change your PIN:

1. Press**Win + I** to open**Settings** .
2. Open the**Account** tab in the left pane.
3. Next, click on the**Sign-in options.**  
![windows 11 sign in options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-11-sign-in-options-1.jpg)
4. Click on**PIN (Windows Hello).**
5. Here, you will see the options to**Change PIN** and**Remove PIN** . To change your PIN, you must know your old PIN. So, we'll proceed with**Remove PIN** to remove the current PIN and then add a new one.
6. So, click on the**Remove** button for**Remove this sign-in option** . Click on**Remove** once more to confirm the action.  
![windows 11 sign in options remove pin confirm](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-11-sign-in-options-remove-pin-confirm-1.jpg)
7. Now you need to verify your admin credentials. So, enter your user account password and click**OK** . Windows will remove your PIN successfully.
8. Next, click on**Set up to add a new PIN** . Enter your user account password to verify the account.  
![windows 11 sign in options add new pin 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-11-sign-in-options-add-new-pin-1.jpg)
9. In the**Set up a PIN** dialog, type a new PIN for your account. Repeat the same in the**confirm PIN** field and click**OK** .

 If you want, you can also add letters and symbols to your PIN to make it secure. Make sure to select the**Include letters and symbols** option in the**Set up a PIN** dialog and then add your new PIN.

 To test your new PIN, press**Win + L** to lock your screen. Next, enter the new PIN in the login screen to confirm the changes.

## What If I Don't Remember My Account Password?

 If you have forgotten your account password, you can reset it from the sign-in screen by answering the security questions for your account.

To reset your user account password:

1. On the login screen, click on**Sign-in options.**
2. Select the**Password** option. Here, enter anything as your password and press**Enter** . Windows will show the**Password is incorrect** screen. Click**OK** .  
![the password is incorrect](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-password-is-incorrect.jpg)
3. Next, click on the**Reset Password** option. This will open the reset password dialog.  
![reset password lock screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-password-lock-screen.jpg)
4. Next, you need to answer the three security questions and press**Enter** .
5. When successful, Windows will ask you to enter your new password. So, enter your new password and confirm the same. Press enter to save the password.

 Now you can sign in with your new account password. Next, change your PIN following the steps described above.

## 2\. Delete the NGC Folder

![delete ngc folder windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/delete-ngc-folder-windows-11-1.jpg)

 If the issue persists when signing in with a PIN, check the NGC folder for permission issues. The NGC folder is where Windows stores your login information. If the folder is corrupted or lacks sufficient permission, it can result in the Something happened and your PIN isn't available error.

 To fix the corrupted folder, you'll need to delete the folder and let Windows recreate it. Here's how to delete the NGC folder to add a new PIN to your account.

To delete your NGC folder:

1. Make sure you log in with an administrator account.
2. Press**Win + E** to open**File Explorer** .
3. Click on**View > Show** and select**Hidden Items** . Make sure Hidden Item option has a check mark.  
![show hidden item file explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/show-hidden-item-file-explorer.jpg)
4. Next, navigate to the following path:  
`C:\Windows\ServiceProfiles\LocalService\AppData\Local\Microsoft`
5. Next, right-click on the**Ngc** folder and select**Delete** . Click on**Delete** again to confirm the action.

 If you see the**You need permission to perform this action** prompt, you'll need to[take the folder ownership on Windows](https://www.makeuseof.com/windows-10-11-own-folder/) to delete the folder. After taking ownership, try to delete the Ngc folder again, and you should be able to fix the error. Once done, you can set up a new PIN from the sign-in options in the Settings app.

## 3\. Uninstall Windows Updates

![advanced options uninstall updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/advanced-options-uninstall-updates-3.jpg)

 If you determine the error to have appeared after installing a Windows update, uninstalling the same should help you undo the changes and fix the error.

 There are[many ways to uninstall updates in Windows 10 and 11](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) , including from the Settings app and Windows Recovery Environment. If you are unable to sign in using a password, you can use the Windows Recovery Environment method to uninstall Windows updates.

## 4\. Perform a System Restore Using Restore Point

 Windows creates automatic restore points before a major change is made to your system, including installing an update. You can use the restore point to restore your PC to an earlier time when it was working without an error.

 If you can log in to your PC, follow the instructions to[use a restore point to restore your Windows 11 system](https://www.makeuseof.com/windows-11-create-restore-point/) . If not, here is how to use the system restore point from Windows Recovery Environment.

1. From the sign-in screen, click on the**Power** icon in the bottom left corner.
2. Next, press and hold the**Shift** key and click on**Restart** . Click on**Restart anyway** if a confirmation prompt appears. Make sure to hold the Shift key until the PC starts to restart.  
![choose an option windows recovery environment](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/choose-an-option-windows-recovery-environment-1.jpg)
3. In the**System Recovery** section, click on**Troubleshoot** .  
![choose an option windows recovery environment advanced options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/choose-an-option-windows-recovery-environment-advanced-options-1.jpg)
4. Next, select**Advanced options** .
5. Click on**System Restore.**  
![choose an option windows recovery environment advanced options system restore](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/choose-an-option-windows-recovery-environment-advanced-options-system-restore-1.jpg)

1. Next, your system will restart in the**System Restore** environment.  
![system restore windows recovery environment 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/system-restore-windows-recovery-environment-1.jpg)
2. Click on your user account name under**Choose an account to continue.**
3. Next, you'll need to enter the password for the selected account and click**Continue** . If your user account doesn't have a password, then press**Enter** to continue without the password.
4. In the**System Restore** dialog, select the most recent restore point and click**Next** .
5. Follow on-screen instructions to complete the system restore. Your PC will restart with a success or failure message. Once the restore is complete, try to log in with the same PIN to see if the error is resolved.

## 5\. Perform a Startup Repair

![advanced options startup repair](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/advanced-options-startup-repair-3.jpg)

 Startup repair is a built-in troubleshooting tool on Windows to fix issues with files required to boot the OS. You can run Startup Repair from the Windows Recovery Environment. Here's how to do it.

1. In the sign-in screen, click on the**Power** icon. Then press and hold the**Shift** key and click on**Restart** . Hold the key until the PC restarts.
2. Next, under**Choose an option,** go to**Troubleshoot > Advanced Options.**
3. Click on**Startup Repair** . Windows will start diagnosing your PC and repair any issues with the startup files.

## 6\. Perform a System Reset

![reset this pc windows 11 recovery](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-this-pc-windows-11-recovery-1.jpg)

 A system reset helps you reset your computer to its factory default removing all the system settings and configuration, including login credentials.

 Windows reset lets you keep or remove your personal files and then reinstall Windows. However, you'll need to reinstall all your third-party apps from scratch.

To perform a system reset:

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, click on**Recovery** .
3. Under reset**Reset this PC** , click on**Reset PC** .
4. Under **Choose an option, you can choose to keep or remove your files** . Confirm the option to reset your PC.

 If you are unable to sign in, follow this guide to[factory reset Windows 11 without the admin password](https://www.makeuseof.com/windows-11-factory-reset-without-admin-password/) .

## Restore the PIN Sign-in Functionality on Windows 11

 Windows may refuse to accept your sign-in PIN if the folder containing the information is corrupted or due to system file issues. Before trying any advanced troubleshooting steps, try to use an alternate login method to sign in and remove and change your PIN. If not, you can use system repair to fix startup issues or restore your PC using a restore point.

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
<li><a href="https://windows11.techidaily.com/unraveling-windows-onedrive-error-for-immediate-folder-addition/"><u>Unraveling Windows OneDrive Error for Immediate Folder Addition</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-compelling-desktop-imagery-on-windows-11/"><u>Crafting Compelling Desktop Imagery on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-variances-between-exe-and-msi-software-packages/"><u>Unveiling the Variances Between EXE & MSI Software Packages</u></a></li>
<li><a href="https://windows11.techidaily.com/synchronize-the-seconds-windows-time-repair-guide/"><u>Synchronize the Seconds: Windows Time Repair Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-and-protect-enabling-powershell-script-policy/"><u>Optimize & Protect: Enabling PowerShell Script Policy</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11-for-spatial-aural-enhancement/"><u>Navigating Windows 11 for Spatial Aural Enhancement</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-win11-uis-image-summaries/"><u>Customize Win11 UI's Image Summaries</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-monetary-mastery-for-your-social-media-channel-fb-video-wisdom/"><u>[Updated] In 2024, Monetary Mastery for Your Social Media Channel  FB Video Wisdom</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-fix-locked-apple-id-on-iphone-14-by-drfone-ios/"><u>How to Fix Locked Apple ID on iPhone 14</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-audio-conversion-made-simple-our-top-6-picks-for-2024/"><u>New Audio Conversion Made Simple Our Top 6 Picks for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-the-ultimate-instagram-reel-playbook/"><u>[Updated] In 2024, The Ultimate Instagram Reel Playbook</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-reset-a-locked-xiaomi-redmi-note-13-proplus-5g-phone-by-drfone-android/"><u>How to Reset a Locked Xiaomi Redmi Note 13 Pro+ 5G Phone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-google-pixel-8-pro-to-samsung-galaxy-s21-ultra-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos From Google Pixel 8 Pro to Samsung Galaxy S21 Ultra | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-meizu-21-to-mac-drfone-by-drfone-android/"><u>How to Mirror Meizu 21 to Mac? | Dr.fone</u></a></li>
<li><a href="https://audio-editing.techidaily.com/in-2024-crafting-silent-elegance-the-art-of-audio-ducking-in-video-editing-with-adobe-premiere-pro-on-mac/"><u>In 2024, Crafting Silent Elegance The Art of Audio Ducking in Video Editing with Adobe Premiere Pro on Mac</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-from-video-to-song-instagrams-mp3-conversion-process/"><u>[Updated] In 2024, From Video to Song  Instagram's Mp3 Conversion Process</u></a></li>
</ul></div>
