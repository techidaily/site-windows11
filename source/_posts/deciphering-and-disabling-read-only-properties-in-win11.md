---
title: Deciphering and Disabling Read-Only Properties in Win11
date: 2024-07-11T22:28:46.115Z
updated: 2024-07-12T22:28:46.115Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Deciphering and Disabling Read-Only Properties in Win11
excerpt: This Article Describes Deciphering and Disabling Read-Only Properties in Win11
keywords: Win11 Read-Protect,Read-Only Disable Win11,Win11 Property Settings,Enable Windows 11 Changes,Disabling Read-Only Features,Altering Read-Only Windows 11,Modify Read-Only Properties Win11
thumbnail: https://thmb.techidaily.com/487b81e16ea9432c9b3bc7ae56246949ca490ff5dbda3843a3191dbeadf76d9d.jpg
---

## Deciphering and Disabling Read-Only Properties in Win11

 Do folders on your computer periodically revert to read-only mode, making it impossible to make changes? It can be frustrating, especially when you have to make final edits to your submission and the deadline is fast approaching.

 In this article, we'll explain why your folders revert to read-only mode and what you can do to prevent it.

## Why Are Your Folders Reverting to Read-Only Mode?

 Your folders revert to read-only mode for various reasons, including restrictions imposed by your administrator, an issue with a recent Windows update, or changes you make to Windows Defender or your antivirus settings. It can also happen due to possible restrictions from the security software you use to lock your folders.

 As you now understand why folders in your computer are reverting to read-only mode, let's look at some ways to fix it.

## 1\. Turn Off Folder Protection

 Do you use folder lock software to protect your data, but some of those protected folders become read-only at random? If so, the restrictions are likely imposed by the folder lock software. Thus, by turning off the security limitations for those folders, you might be able to fix the problem right away.

 If you don't use any folder lock software or turning off the protection doesn't help, move on to the next solution.

## 2\. Rule Out a Folder-Specific Issue

 Is only one folder reverting to read-only mode? If so, follow the below steps to remove the read-only attribute manually for that folder:

1. Go to the folder that is going read-only.
2. Right-click on it and select **Properties**.
3. In the **General** tab, uncheck the box for **Read-only**.
4. Click **Apply** and hit **OK**.  
![Unchecking the Box for Read-Only Option in the General Tab of Properties Window of the File on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/1-Unchecking-the-Box-for-Read-Only-Option-in-the-General-Tab-of-Properties-Window-of-the-File-on-Windows.jpg)

 If removing the attribute this way does not solve the problem, or if the problem involves multiple files, keep applying the remaining fixes.

 If you have encountered the issue on a work computer, you may not be able to apply a few fixes mentioned below. Thus, if you encounter an error saying you don't have permission to make any changes, it's best to let your IT admin handle it.

## 3\. Ensure an Administrator Hasn't Imposed Any Restrictions

 In Windows, administrators can restrict access to confidential data for specific users working on the same computer. If you see some files and folders in read-only mode, verify the administrator hasn't changed their permissions. Here's how you can find out:

1. Right-click the file or folder you see in read-only mode and select **Properties**.
2. In the **Properties** window, click the **Security** tab.
3. Choose your username from the available options.
4. Check the **Permissions for Users** section after selecting your account.  
![Checking the Permissions Window in the Security Tab in the File’s Properties on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Image-2-Checking-the-Permissions-Window-in-the-Security-Tab-in-the-File’s-Properties-on-Windows.jpg)

 You can't make changes to the files if you only have read-only permissions. If you believe the access was restricted by mistake, ask the administrator to grant you access.

 If you're an administrator, here's how you can change the access permissions of other users:

1. Log in with your administrator account.
2. Right-click the file or folder you see in read-only mode and select **Properties**.
3. In the **Properties** window, go to the **Security** tab.
4. Click the **Edit** button.  
![Clicking on Edit Button under Security Tab in Properties Window on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Image-3-Clicking-on-Edit-Button-under-Security-Tab-in-Properties-Window-on-Windows.jpg)
5. Choose the user you want to grant access to.
6. In the **Permissions for Users** window, check the box next to **Full control** under **Allow** column.  
![Checking the Box Next to Full Control under Allow Column in the Permissions for Users Window in Security Tab on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Image-4-Checking-the-Box-Next-to-Full-Control-under-Allow-Column-in-the-Permissions-for-Users-Window-in-Security-Tab-on-Windows.jpg)
7. After clicking **Apply**, hit **OK**.

 If you have multiple personal accounts on your computer, you can change permissions for each account using the administrator account similarly.

## 4\. Disable Ransomware Protection in the Windows Security Settings

 To combat ransomware threats and safeguard users' data, Microsoft has introduced a ransomware protection feature. By using this feature, users can prevent third-party apps from changing their files and folders without their permission.

 Although it's handy, it has a history of messing up file permissions. Therefore, if you've encountered the issue under discussion after enabling this feature, disabling it may help you fix it. The following steps will help you do that:

1. Open the Windows Security app by searching for **"Windows Security"** in Windows Search.
2. Go to **Virus and threat protection**.
3. Click on **Manage ransomware protection**.  
![Opening Manage Ransomware Protection Option under Virus and Threat Protection in Windows Security App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Image-5-Opening-Manage-Ransomware-Protection-Option-under-Virus-and-Threat-Protection-in-Windows-Security-App-on-Windows.jpg)
4. Turn off the toggle under **Controlled folder access**.  
![Disabling Ransomware Protection by Turning Off the Toggle under Controlled Folder Access in Windows Security App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Image-6-Disabling-Ransomware-Protection-by-Turning-Off-the-Toggle-under-Controlled-Folder-Access-in-Windows-Security-App-on-Windows.jpg)

 If disabling this feature doesn't resolve the problem, you may need to reset the entire Windows Defender Firewall settings.

## 5\. Reset the Windows Defender Firewall Settings

 Have you recently made changes to your Windows Defender Firewall settings and encountered this problem? If so, there's a good chance you've done something wrong. Therefore, resetting them may help you resolve the issue. Follow the below steps to reset Windows Defender Firewall settings:

1. Open the Control Panel app by searching for **"Control Panel"** in Windows Search.
2. Click **System and Security**.
3. Click **Windows Defender Firewall**.
4. In the left sidebar, click **Restore defaults**.  
![Opening Restore Defaults Option in Windows Defender Firewall Tab in System and Security Settings in Control Panel App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Image-7-Opening-Restore-Defaults-Option-in-Windows-Defender-Firewall-Tab-in-System-and-Security-Settings-in-Control-Panel-App-on-Windows.jpg)
5. Click **Restore defaults** button.
6. When the confirmation pop-up appears, select **Yes**.  
![Clicking on the Yes Button after Clicking on the Restore Defaults Button on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Image-8-Clicking-on-the-Yes-Button-after-Clicking-on-the-Restore-Defaults-Button-on-Windows.jpg)

## 6\. Disable Antivirus and Other Security Software

 If the folders that revert to read-only mode reside on the same drive where your operating system is installed, Microsoft Defender might temper the folder permissions.

 To rule out this potential cause, temporarily [turn off the Microsoft Defender Firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) and see if your folders stop reverting to read-only mode after that. If they do, whitelist those folders from Microsoft Defender and turn on the security suite again. If you use any third-party security software, disable that as well since it can also restrict your access.

 Whether disabling the built-in or third-party security suites fixes the issue or not, you should enable them again to keep your device protected from viruses.

## 7\. Forcefully Remove the Read-Only Attribute

 If none of the fixes have resolved the issue of folders reverting to read-only mode, you should remove the read-only attribute forcibly using Command Prompt. Here's how:

1. Search for **"Command Prompt"** in Windows Search and open the Command Prompt app.
2. Enter the following command by specifying the drive and pasting the path to the read-only folder.  
`attrib -s -h -r "Drive:\path_to_folder\*.*" /s /d`
3. Hit **Enter**.  
![Removing the Read-Only Attribute by Running the Command in Windows Command Prompt App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Image-9-Removing-the-Read-Only-Attribute-by-Running-the-Command-in-Windows-Command-Prompt-App-on-Windows.jpg)

## 8\. Run the SFC and CHKDSK Scans

 Corrupted system files and bad hard drive sectors can also alter the folder's permission access. Run the SFC and Chkdsk scans to ensure that's not the case. SFC can help you search for and fix corrupted system files, whereas Chkdsk can find bad sectors on your hard drive that could be causing the issue.

 If you've never run these scans before, check out our guide on [how to run SFC](https://www.makeuseof.com/system-file-checker-sfc-windows/) and [Chkdsk scans](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/). Hopefully, running these scans will fix the underlying issue with your files and folders. If neither of these scans finds any problems, proceed to the next step.

## 9\. Uninstall Any Recent Windows Updates

 If the issue under discussion occurred after installing a Windows update, you should uninstall it and revert to the previous version of Windows. Check out our article on [manually uninstalling Windows 10 and 11 updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) if you're unfamiliar with the process.

## 10\. Relocate the Folders to Another Drive

 While it may initially seem strange, relocating the folders whose permissions get restricted to another drive also resolved the issue for some users. Therefore, move your folders from one drive to another, remove the read-only attribute, and see if they revert to read-only again. If relocating the folder to a different drive does not resolve the issue, go to the next fix.

## 11\. Go to Previous Restore Point

 A System Restore allows Windows users to restore their system to its current state if they accidentally mess something up in the future. It's a quick way to undo changes that mess up your system.

 Thus, if uninstalling the Windows update also doesn't work, apply the restore point you created previously. This will undo any system changes that may have resulted in the issue under discussion and return your device to its original state.

 If you're unfamiliar with the process, check out our article that explains [how to perform a system restore in Windows 11](https://www.makeuseof.com/windows-11-create-restore-point/#how-to-use-restore-point-to-restore-your-windows-11-system). For Windows 10, the process is nearly the same.

## Keep Your Files and Folders Editable

 Hopefully, applying the fixes mentioned in the article will help you prevent your folder from reverting to read-only mode. Moreover, to stop files from opening in read-only mode in a specific app, such as OneNote, you'll have to change the app settings.

 In this article, we'll explain why your folders revert to read-only mode and what you can do to prevent it.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>