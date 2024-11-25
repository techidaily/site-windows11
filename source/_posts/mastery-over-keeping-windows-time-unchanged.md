---
title: Mastery over Keeping Windows Time Unchanged
date: 2024-11-23T16:45:51.849Z
updated: 2024-11-24T22:21:05.010Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastery over Keeping Windows Time Unchanged
excerpt: This Article Describes Mastery over Keeping Windows Time Unchanged
keywords: WinTimeSyncMastery,StableWindowsClock,NoChangeTimeWin,SyncTimeNoShift,PreciseWinTime,UnalteredWindowsTime,ConstantTimeWin
thumbnail: https://thmb.techidaily.com/b46dad75221e4740026b09a7187d9a5f274b77721a6e7c2a0a28f40e4058b1a9.jpg
---

## Mastery over Keeping Windows Time Unchanged

 You’re using your Windows device and notice something strange in the date and time settings. Someone has changed the settings without your knowledge or permission. This makes it difficult to stay on schedule with tasks and activities. In this guide, we’ll show how to stop anonymous users from changing date and time settings on Windows computers.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/620kcQ7Dw7w?si=a5ussGs5HV7sG3hF&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How To Prevent Users From Changing the Date and Time on Windows

 There are two ways to prevent users from changing Windows date and time. The first is to use Group Policy Editor, a system administration tool designed to control computer behavior in an organization. While the second way is to use Registry Editor, which allows you to modify Windows registry settings.

 For both methods, you need administrative access to the computer to change it. Once you’ve made the changes, nobody can alter the date and time settings. Let’s look at each method in more detail.

## 1\. Use the Group Policy Editor

 If your computer is part of an organization and users often change the date and time, use Group Policy Editor to stop it. This will prevent those with limited access to the computer from altering the date and time. However, this method only works for Windows Pro, Enterprise, or Education Editions.

 So, if you have Windows Home Edition, this won’t work. In that case, you must first [activate the Group Policy Editor for Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). If it seems complicated, skip it and try the next solution instead.

 Follow these steps to prevent users from changing the date and time:

1. Press **Win + R** on your keyboard to open the Run window.
2. Type **gpedit.msc** in the text box and press Enter. This will open the Group Policy Editor window.
3. On the left side of the window, navigate to the following path:  
Computer Configuration > Administrative Templates > System > Locale Services
4. In the right-side pane, double-click on **Disallow user override of locale settings**.  
![Disallow user override of locale settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/disallow-user-override-of-locale-settings.jpg)
5. In the pop-up window, check the **Enabled** radio button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RBN1gYY5hUs?si=p89CMiMzeJzU0wGu&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Then click **Apply** \> **OK** to save the changes.

 This will block anyone from changing the date and time settings on your computer. However, if you have administrative access to the computer, you can still alter the settings.

 If you want to revert to the default settings later, open Group Policy Editor again and change the value of Disallow user override of locale settings back to Not Configured or Disabled. This way, users can change the time and date again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4DJKH1uY7P0?si=tCG66XVlbwSKoATj&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Tweak the Registry Editor

 If you’re using Windows Home Edition or have disabled the Group Policy Editor, use the Registry Editor to protect date and time settings. This method is more advanced and has a higher risk of system damage.

 In that case, [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it. Doing so will restore settings if something goes wrong.

 Follow these steps to stop users from changing the time and date via the registry:

1. [Open the Run command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **regedit** in the field and press Enter. This will [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. In the Registry Editor window, navigate to the following path:  
HKEY_CURRENT_USER\Software\Policies\Microsoft\Control Panel\International\
4. If the International folder doesn’t exist, create one. To do that, right-click on Control Panel and select **New** \> **Key**. Name it **International**.
5. Then right-click on **International** and select New > DWORD (32-bit) Value.
6. Name the newly created value **PreventUserOverrides**.
7. Double-click on the **PreventUserOverrides** DWORD value.  
![Use Registry Editor to Prevent Users From Chaning date and time settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/use-registry-editor-to-prevent-users-from-chaning-date-and-time-settings.jpg)
8. In the pop-up window, change the Value data to **1** and click **OK**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/465CTOm8om0?si=63RxowNMCFA4fPUa&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you’ve made the changes, close the Registry Editor window and restart your computer.

 To undo this restriction, delete the **PreventUserOverrides** DWORD value from the registry or change the value to **0**. Doing so will enable users to change the time and date again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DBMTAJBx-X4?si=sje5pFJXiHzJJGbP&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Stop Windows Time and Date Changes

 Now stop unauthorized users from changing the date and time settings on your Windows computer. This keeps your tasks and activities on track. If necessary, you can always undo this restriction.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-clips.techidaily.com/new-digital-dollars-at-a-click-monetization-made-simple-on-fb-for-2024/"><u>[New] Digital Dollars at a Click Monetization Made Simple on FB for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-splitcams-journey-to-video-excellence-an-overview/"><u>[New] In 2024, SplitCam's Journey to Video Excellence An Overview</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/nleash-creativity-with-top-9-free-tools-to-craft-your-brand-for-2024/"><u>[New] Unleash Creativity with Top 9 Free Tools to Craft Your Brand for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/effective-ways-to-diagnose-and-fix-a-malfunctioning-computer-using-chatgpt/"><u>Effective Ways to Diagnose and Fix a Malfunctioning Computer Using ChatGPT</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirroring-infinix-note-30-drfone-by-drfone-android/"><u>How to Screen Mirroring Infinix Note 30? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-login-fixes-for-denied-users/"><u>Mastering Windows Login Fixes for Denied Users</u></a></li>
<li><a href="https://windows11.techidaily.com/resetting-your-grammarly-installation-on-a-pc/"><u>Resetting Your Grammarly Installation on a PC</u></a></li>
<li><a href="https://windows11.techidaily.com/skip-past-stalled-wow-65-updates-on-pc/"><u>Skip Past Stalled WoW 6.5 Updates on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-to-fixed-outlooks-non-previewable-files-problem/"><u>Solutions to Fixed Outlook's Non-Previewable Files Problem</u></a></li>
<li><a href="https://windows11.techidaily.com/synchronized-shutdown-a-windows-user-written-guide/"><u>Synchronized Shutdown: A Windows User' Written Guide</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/the-2023-shift-in-facebooks-video-presentation-style-for-2024/"><u>The 2023 Shift in Facebook’s Video Presentation Style for 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-cod-black-ops-cold-war-issue-understanding-and-fixing-error-code-80070057/"><u>Troubleshooting Cod: Black Ops Cold War Issue – Understanding and Fixing Error Code 80070057</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-evolution-the-significant-changes-from-w10-to-w11/"><u>Windows Evolution: The Significant Changes From W10 to W11</u></a></li>
<li><a href="https://win-able.techidaily.com/wsappx-explained-managing-high-resource-usage-on-your-computer/"><u>WSAPPX Explained: Managing High Resource Usage on Your Computer</u></a></li>
</ul></div>

