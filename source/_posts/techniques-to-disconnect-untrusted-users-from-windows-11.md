---
title: Techniques to Disconnect Untrusted Users From Windows 11
date: 2024-06-25T12:36:16.081Z
updated: 2024-06-26T12:36:16.081Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Techniques to Disconnect Untrusted Users From Windows 11
excerpt: This Article Describes Techniques to Disconnect Untrusted Users From Windows 11
keywords: Win11 Security Block,Halt Rogue Access,Disconnect Unregistered Users,Prevent Unknown Login,Secure User Exits,Wipe Offshore Logins,Windows 11 UX Lockout
thumbnail: https://thmb.techidaily.com/7fc466e5e2b7732daf41c9b5f420c5c5add88815dae1954866b21ab967027c21.jpg
---

## Techniques to Disconnect Untrusted Users From Windows 11

### Quick Links

* [Sign Out Other Users Using the Task Manager](#sign-out-other-users-using-the-task-manager)
* [Sign Out Other Users Using the Command Prompt](#sign-out-other-users-using-the-command-prompt)
* [Log Off Other Users Using Process Explorer](#log-off-other-users-using-process-explorer)
* [Ask Other Users Before You Sign Them Out](#ask-other-users-before-you-sign-them-out)

### Key Takeaways

* To sign out other users on Windows 11, you can use Task Manager, Command Prompt, or Process Explorer.
* The Task Manager method works on any version of Windows, while the Command Prompt option only works for Pro and above versions of Windows. Process Explorer requires a separate download.
* Be sure to consider any unsaved work before logging off a user.

 Each active user session on your PC means your computer's resources are shared with others, which can impact system performance. If someone is not actively using their session, you can log off the idle user from your account to reclaim those system resources.

## 1\. Sign Out Other Users Using the Task Manager

 The Task Manager's **Users** tab keeps track of all the user sessions active on your computer. You can use it to manage user accounts on Windows, switch between different user accounts, and sign off other user accounts. If you only need to [sign out of your current session on Windows 11](https://www.makeuseof.com/windows-11-how-to-sign-out/), the process is much simpler, though.

 You must be logged in as an administrator to sign off other user accounts; [check if your user account has administrator rights](https://www.makeuseof.com/check-windows-account-admin-rights/) if you're not sure. Importantly, when you sign out a user, the user's unsaved data might be lost. So tread carefully.

 To sign out other users using Task Manager:

1. Right-click on **Start** and select **Task Manager**. Alternatively, use the keyboard shortcut **Ctrl + Shift + Esc**.
2. In Task Manager, open the **Users** tab in the left pane which displays the number of users currently logged in. If not visible, click the **Open Navigation** button (three horizontal bars) in the top left corner.  
![Winx Menu Task Manager Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/winx-menu-task-manager-windows-11.png)
3. In the **Users** tab, locate the account you want to sign off.
4. Right-click on the user account and select **Sign off**.  
![Users Tab in Task Manager with Logoff Option in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/users-tab-in-task-manager-with-logoff-option-in-windows-11.jpg)
5. Click **Sign out user**. Windows will close all the open apps and running processes and then log out the user.

## 2\. Sign Out Other Users Using the Command Prompt

 On Windows 11 Pro, Edu, and Enterprise editions, you can use Command Prompt's "query sessions" command to check and log off active user accounts. This command is unlikely to work on a Windows 11 Home, limiting your options.

 To sign out other users using Command Prompt:

1. Press the **Win** key and type **cmd**.
2. Right-click on **Command Prompt** and select **Run as administrator**.
3. In the Command Prompt window, type the following command to view all the active user sessions with a query:  
`query session`
4. The output will show all the active user sessions on your computer. Make a note of the user account **ID** you want to sign out. In this instance, we have **Tashreef** as **1** and **Guest21** as **3** under the **ID** column.  
![Command Prompt With Query Session Command Running on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/command-prompt-with-query-session-command-running-on-windows-11.jpeg)
5. Type the following command to sign out the specified user. Replace **2** below with the user account ID you want to sign out:  
`Logoff 3`
6. Upon successful execution, Windows will sign out the specified user account.  
![Command Prompt With Logoff Command Running on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/command-prompt-with-logoff-command-running-on-windows-11.jpg)
7. Once done, type **exit** and press Enter to close the Command Prompt.

## 3\. Log Off Other Users Using Process Explorer

 Process Explorer is part of [Windows Sysinternal Tools, a suite of system administration utilities](http://www.makeuseof.com/windows-sysinternals-guide/) from Microsoft. Though the freeware is popular among developers and system admins, anyone can use Process Explorer to use some of its advanced features.

 Process Explorer is a powerful tool that maps all currently active processes and DLL files to the accounts running them. Our purpose is to show you how to use its user management feature to kick out other user sessions.

1. Go to Microsoft's official [Process Explorer page](https://learn.microsoft.com/en-us/sysinternals/downloads/process-explorer) and download Process Exploreras a zip file to a location on your desktop.  
![Download Process Explorer Web Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/download-process-explorer-web-page.jpg)
2. Right-click on the **ProcessExplorer.zip** archive, and select **Extract All**. Select a location and extract the folder.  
![Process Explorer Exe File Run as Administrator Option in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-exe-file-run-as-administrator-option-in-windows-11.jpg)
3. Open the **ProcessExplorer** folder, right-click on **procexp64.exe**, and select **Run as administrator**.  
![Process Explorer App User Option Selected in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-app-user-option-selected-in-windows-11.jpg)
4. In the **Process Explorer** window, click **Users** to view all the active user sessions.  
![Process Explorer App User Account Logoff Option Selected in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-app-user-account-logoff-option-selected-in-windows-11.jpg)
5. Hover your cursor over the user account name and select **Logoff**.

 Process Explorer will sign out the selected user account from your computer. If you get an [access denied error](https://www.makeuseof.com/windows-11-fix-access-denied-error/), run the procexp64.exe executable with administrator privileges and try again.

## Ask Other Users Before You Sign Them Out

 When you log off other users, any unsaved work in their accounts is lost. So do consider that before you apply the above methods. Logging off from a Windows account in a multi-user PC is a good habit because it reduces the chance of data loss and frees up the computer's resources for others. Always request others to sign off when their work is finished.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/improving-startup-order-in-windows-11/"><u>Improving Startup Order in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-win-network-unreachable-issue/"><u>Overcoming WIN Network Unreachable Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-to-curtail-excessive-wmi-worker-use/"><u>Tips to Curtail Excessive WMI Worker Use</u></a></li>
<li><a href="https://windows11.techidaily.com/5-ways-to-fix-the-windows-family-safety-feature-not-working/"><u>5 Ways to Fix the Windows Family Safety Feature Not Working</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-preserves-7-ancient-features-for-modern-use/"><u>Windows 11 Preserves 7 Ancient Features for Modern Use</u></a></li>
<li><a href="https://windows11.techidaily.com/smart-task-management-microsofts-ai-copilot-for-windows-11-enhances-workflow/"><u>Smart Task Management: Microsoft's AI Copilot for Windows 11 Enhances Workflow</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-address-geforce-nows-error-code-xc0f1103f/"><u>How To Address GeForce Now's Error Code Xc0f1103f</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-ultimate-guide-to-free-premiere-pro-template-hacks/"><u>In 2024, The Ultimate Guide to Free Premiere Pro Template Hacks</u></a></li>
<li><a href="https://screen-capture.techidaily.com/the-ultimate-guide-to-the-top-webcams-for-windows-10/"><u>The Ultimate Guide to the Top Webcams for Windows 10</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/the-essential-guide-to-building-youtube-music-playlists/"><u>The Essential Guide to Building YouTube Music Playlists</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-battlefield-geniuses-discovering-the-quintessential-7-total-war-experiences/"><u>In 2024, Battlefield Geniuses  Discovering the Quintessential 7 Total War Experiences</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-linux-loves-video-editing-10-alternatives-to-adobe-premiere-pro/"><u>New 2024 Approved Linux Loves Video Editing 10 Alternatives to Adobe Premiere Pro</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-complete-users-manual-for-fcp-power-users/"><u>2024 Approved  The Complete User's Manual for FCP Power Users</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-reimagining-blockbuster-favorites-7-swap/"><u>In 2024, Reimagining Blockbuster Favorites - #7 Swap</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-cutting-edge-tips-for-making-masterpieces-with-snaps/"><u>2024 Approved  Cutting-Edge Tips for Making Masterpieces with Snaps</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-unveiling-20-must-try-youtube-tricks-to-boost-views/"><u>2024 Approved  Unveiling 20 Must-Try YouTube Tricks to Boost Views</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>