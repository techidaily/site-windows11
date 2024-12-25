---
title: Exiting Others' User Sessions on Win 11
date: 2024-12-22T16:25:02.736Z
updated: 2024-12-25T17:47:02.405Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Exiting Others' User Sessions on Win 11
excerpt: This Article Describes Exiting Others' User Sessions on Win 11
keywords: Session Exit Win11,Win11 Unauthorized Logoff,End Users Win11 Sessions,Control Session Win11 Access,Prevent Others' Login Win11,Secure Windows 11 User Exit,Manage User Lockout Win11
thumbnail: https://thmb.techidaily.com/f14703ab2e75a5e3ef7cee5c0a7ee5ddd2895b6cfd7b5126052dee0bd06c1845.jpg
---

## Exiting Others' User Sessions on Win 11

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c1yHj02oP3w?si=mwi3FyP0p68gkBqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Right-click on the user account and select **Sign off**.  
![Users Tab in Task Manager with Logoff Option in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/users-tab-in-task-manager-with-logoff-option-in-windows-11.jpg)
5. Click **Sign out user**. Windows will close all the open apps and running processes and then log out the user.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2ipTu54inBo?si=gRegjvtVq5gm_PHo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UoBCgLTmznE?si=MXXiGsd2qpd_DrzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Process Explorer Exe File Run as Administrator Option in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-exe-file-run-as-administrator-option-in-windows-11.jpg)
3. Open the **ProcessExplorer** folder, right-click on **procexp64.exe**, and select **Run as administrator**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-yZKNLxj3po?si=-RbF6nCJEVlHWP-M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Process Explorer App User Option Selected in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-app-user-option-selected-in-windows-11.jpg)
4. In the **Process Explorer** window, click **Users** to view all the active user sessions.  
![Process Explorer App User Account Logoff Option Selected in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-app-user-account-logoff-option-selected-in-windows-11.jpg)
5. Hover your cursor over the user account name and select **Logoff**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YZma8PBO0D8?si=9-qQgGVTuChYd27a" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Process Explorer will sign out the selected user account from your computer. If you get an [access denied error](https://www.makeuseof.com/windows-11-fix-access-denied-error/), run the procexp64.exe executable with administrator privileges and try again.

## Ask Other Users Before You Sign Them Out

 When you log off other users, any unsaved work in their accounts is lost. So do consider that before you apply the above methods. Logging off from a Windows account in a multi-user PC is a good habit because it reduces the chance of data loss and frees up the computer's resources for others. Always request others to sign off when their work is finished.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/new-earn-through-engagement-securing-youtube-partnership-membership-for-2024/"><u>[New] Earn Through Engagement Securing YouTube Partnership Membership for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-exploring-youtubes-regular-income-mechanism/"><u>[Updated] 2024 Approved Exploring YouTube's Regular Income Mechanism</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-from-novice-to-pro-building-an-insta-highlight-showcase/"><u>[Updated] In 2024, From Novice to Pro Building an Insta Highlight Showcase</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-grow-your-streams-money-potential-anywhere-on-devices/"><u>2024 Approved Grow Your Stream's Money Potential Anywhere on Devices</u></a></li>
<li><a href="https://howto.techidaily.com/app-wont-open-on-your-samsung-galaxy-a54-5g-here-are-all-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>App Wont Open on Your Samsung Galaxy A54 5G? Here Are All Fixes | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/digital-heavyweights-decoded-a-tour-through-the-worlds-top-10-internet-hubs/"><u>Digital Heavyweights Decoded: A Tour Through the World's Top 10 Internet Hubs</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-non-working-windows-performance-indicator/"><u>Fixing Non-Working Window's Performance Indicator</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-open-the-calculator-in-windows-11/"><u>How to Open the Calculator in Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-share-location-in-messenger-on-poco-m6-pro-5g-drfone-by-drfone-virtual-android/"><u>How to Share Location in Messenger On Poco M6 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/identify-and-secure-open-tcpip-in-windows/"><u>Identify and Secure Open TCP/IP in Windows</u></a></li>
<li><a href="https://technical-tips.techidaily.com/mpeg-mp3-conversion-tool-con-movavi-il-modo-piu-semplice-per-trasformare-i-tuoi-file-multimediali/"><u>MPEG MP3 Conversion Tool Con Movavi – Il Modo Più Semplice per Trasformare I Tuoi File Multimediali</u></a></li>
<li><a href="https://win-answers.techidaily.com/no-more-freezes-troubleshoot-your-google-chrome-for-smooth-browsing/"><u>No More Freezes: Troubleshoot Your Google Chrome for Smooth Browsing</u></a></li>
<li><a href="https://windows11.techidaily.com/overhauling-fatal-exception-error-0x8007045d-on-pc/"><u>Overhauling Fatal Exception Error 0X8007045D on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-unreadable-messages-in-discord-chat/"><u>Remedying Unreadable Messages in Discord Chat</u></a></li>
<li><a href="https://windows11.techidaily.com/the-secret-of-eradicating-linguistic-line-from-win11-taskbar/"><u>The Secret of Eradicating Linguistic Line From Win11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/two-email-systems-together-merging-gmail-and-outlook-in-windows/"><u>Two Email Systems Together: Merging Gmail and Outlook in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-customized-windows-power-schemes/"><u>Unlocking Customized Windows Power Schemes</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-widget-personalization-in-microsofts-latest-os/"><u>Unveiling Widget Personalization in Microsoft's Latest OS</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/what-pokemon-evolve-with-a-dawn-stone-for-honor-magic-5-lite-drfone-by-drfone-virtual-android/"><u>What Pokémon Evolve with A Dawn Stone For Honor Magic 5 Lite? | Dr.fone</u></a></li>
</ul></div>

