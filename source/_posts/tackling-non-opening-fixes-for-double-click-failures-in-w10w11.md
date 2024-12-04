---
title: "Tackling Non-Opening: Fixes for Double-Click Failures in W10/W11"
date: 2024-11-30T16:07:42.340Z
updated: 2024-12-04T04:04:25.252Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Tackling Non-Opening: Fixes for Double-Click Failures in W10/W11"
excerpt: "This Article Describes Tackling Non-Opening: Fixes for Double-Click Failures in W10/W11"
keywords: W10 Opening Issues,W11 Click Errors,Fix Double-Click,Non-Opening Solutions,Window Tackling,Update Failures,W10/W11 Troubleshoot
thumbnail: https://thmb.techidaily.com/dc54f112c78b3afb0110331eb25c5f493a4d3b2149d6ee352dfe8394d4845198.jpg
---

## Tackling Non-Opening: Fixes for Double-Click Failures in W10/W11

 Some users have posted on help chat forums about folders not opening when they double-click them in Windows File Explorer. This means users can’t access folders by double-clicking on directories. There isn’t a specific error message associated with this issue.

 This issue doesn’t necessarily mean users can’t open any folders, for they can still access directories by selecting **Open** on the right-click menu. However, selecting the **Open** context menu option isn’t the most ideal way to access them. If you can’t open folders by double-clicking them on your Windows 11/10 PC, try applying these potential fixes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OZQJUTr44rA?si=ADA0nD1VnXjR_sH0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Adjust File Explorer Options

 File Explorer has alternative single-click and double-click options for opening items. If single-click is set, double-clicking folders won’t open them. Try single-clicking a folder to see if that works. If it does, then you probably need to select the **Double-click to open an item** option like this:

1. Right-click on your taskbar’s **Start** button to select a **Search** shortcut.
2. Type "File Explorer options" to find a matching search result.
3. Click **File Explorer Options** to bring up the window with that title.
4. Select the **Double-click to open an item** radio button.  
![The Double-click to open an item option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/double-click-to-open-an-item-option.jpg)
5. Click the **Apply** button for saving settings.

6. Select **OK** to close the File Explorer Options window.

 If you find the **Double-click to open item** option is already selected, you could try selecting the single-click setting instead. That way, you might at least be able to access your folders by single-clicking them. Or, proceed with applying the other resolutions below.

## 2\. Adjust the Double-Click Mouse Speed

 The mouse **Double-click speed** setting can feasibly cause this issue if it’s set too fast. So, you might need to lower that setting a little bit. This is how you can adjust the mouse double-click speed:

1. First, bring up the tool for finding files with the **Windows** key + **S** hotkey that opens it.
2. Type the "mouse settings" keyword phrase.
3. Click **Mouse settings** to open a Settings window.
4. Next, click the **Additional mouse** options in Settings.  
![The Additional mouse settings option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/additional-mouse-settings.jpg)
5. Drag the **Double-click speed** bar’s slider left to slow it down.  

![The Double-click speed setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/double-click-speed-setting.jpg)
6. Select **Apply** and click **OK** to set the new double-click speed.

 The required double-click speed for opening folders will now be slower than before. So, you won’t need to double-click so quickly.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/W5aJC8okA8s?si=L2rnYAp-gmGlLQSf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Scan and Repair Windows System Files

 Microsoft advises users to run system file scans when Windows functions aren’t working right. In this case, there’s an issue with the folders’ double-click functionality.

 So, [run a System File Checker scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) to see if Windows Resource Protection detects any corrupted system files. If so, Windows Resource Protection will probably also repair the files detected, which could fix the double-clicking of folders not opening.

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-sfc-scannow3.jpg)

## 4\. Edit the Shell Registry Key

 Quite a few users have confirmed editing the **shell** registry key can fix the double-clicking of folders not working in Windows 11/10\. Those users changed that key’s **(Default)** string value to fix the issue. These are the steps for editing the **shell** key:

1. Press the **Windows** logo keyboard key + **R** to start Run.
2. Input a **regedit** (Registry Editor) Run command inside the **Open** box and select **OK**.
3. Bring up the shell key by inputting this path inside the registry address box:  
`Computer\HKEY_CLASSES_ROOT\Directory\shell`
4. Double-click **(Default)** inside the **shell** key.  
![The shell registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-shell-key.jpg)
5. If the **Value data** box is empty, or set differently, input **none** there as in the snapshot directly below.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LdVT_-3gESA?si=_HfjpbUEHSRKTXjt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![The (Default) string value for the shell registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-default-string-value.jpg)
6. Click **OK** to save the new **(Default)** string value.

 You might need to [restart File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) for this registry tweak to take effect. Alternatively, restart Windows and then try double-clicking a folder to see if it opens.

## 5\. Edit the Mouse Registry Key

 Double-click issues can arise when string values for the **Mouse** registry key have been altered from their default settings (typically by third-party apps). To be more specific, **MouseHoverWidth**, **MouseHoverHeight**, **DoubleClickHeight**, and **DoubleClickWidth** are four **Mouse** key strings you might need to restore to default values for to fix this issue.

 To do so, edit the **Mouse** registry key like this:

1. Bring up Registry Editor as instructed for the first two steps of the previous potential solution.
2. Next, go to the **Mouse** key by entering this path within Registry Editor’s address bar:  
`Computer\HKEY_CURRENT_USER\Control Panel\Mouse`
3. Double-click the **MouseHoverWidth** string.  
![The Mouse key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/mouse-key.jpg)
4. If set any differently, input **4** inside the **Value data** box and select **OK**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XS1nQCe95LU?si=A2dhdFkSAI61_nKA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![The MouseHoverWidth string value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-mousehoverwidth-string-value.jpg)
5. Repeat the previous two steps for the **MouseHoverHeight**, **DoubleClickHeight**, and **DoubleClickWidth** strings in the **Mouse** key. Set their values to **4**, just like you did for the **MouseHoverWidth**string.

 When you’ve finished adjusting those string values, exit the Registry Editor and restart your PC. If you find all those strings are already set to four, you don’t need to change them.

## 6\. Turn Off Controlled Folder Access

 Some users have said they fixed the double-clicking of folders not working by turning off controlled folder access. Controlled folder access is the Windows Security feature that blocks unauthorized apps from modifying contents inside protected directories. Thus, enabling that feature restricts folder access.

 So, try turning off controlled folder access like this:

1. Open Windows Security by double-clicking the small shield icon inside the system tray area of your taskbar.
2. Click **Virus & threat protection** in Windows Security’s left navigation sidebar.  
![The tab sidebar in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-security-s-tab-sidebar.jpg)
3. Scroll down a little and click on **Manage ransomware protection**.  

![The Manage ransomware protection](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/manage-ransomware-protection.jpg)
4. Click the **Controlled folder access** toggle switch to turn off that setting.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lxv4NM-89CU?si=Uj5rOkhrwZ_6QIuW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![The Controlled folder access setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/controlled-folder-access-setting.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K4lRBnNnd9k?si=5e0MbdOz-fF6Ry_k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Then, go into File Explorer and try opening some folders again to see if disabling that security feature makes a difference. If it does, then it’s probably best to leave controlled folder access off.

## 7\. Revert Windows to a Restore Point

 Rolling Windows back to a saved restoration point is one of the last things to try if no other potential fixes for this issue work. Applying this potential fix will undo system changes made and remove software installed after your chosen restore point date.

 However, it’s only worth reverting Windows if you can select a restore point that will roll back the OS to a time when you could open folders by double-clicking them.

![The System Restore tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-system-restore-tool.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/AcAYRX0cwwA?si=DxqWU39vqksZbe1s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To apply this potential fix, check out our guide on [utilizing System Restore](https://www.makeuseof.com/use-system-restore-windows/). The System Restore tool will need to be enabled for you to select a restoration point. Be prepared to reinstall software packages a selected restore point deletes, which you can check by clicking **Scan for affected programs** in System Restore.

## Make Double-Clicking Open Folders on Windows Again

 Those potential fixes for double-clicking folders not working will probably resolve that Windows 11/10 issue in most cases. We can’t promise they’re guaranteed, but lots of users have confirmed some of them work.

 Beyond those possible resolutions, you might have to try something more drastic, like a full system reset or in-place Windows upgrade.

 This issue doesn’t necessarily mean users can’t open any folders, for they can still access directories by selecting **Open** on the right-click menu. However, selecting the **Open** context menu option isn’t the most ideal way to access them. If you can’t open folders by double-clicking them on your Windows 11/10 PC, try applying these potential fixes.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-5-key-steps-to-transforming-videos-into-cash-on-vimeo/"><u>[New] In 2024, 5 Key Steps to Transforming Videos Into Cash on Vimeo</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-imovie-why-does-it-alter-my-videos-for-2024/"><u>[Updated] IMovie Why Does It Alter My Videos for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-future-of-titles-an-innovators-playbook-for-videos/"><u>2024 Approved The Future of Titles An Innovator's Playbook for Videos</u></a></li>
<li><a href="https://sound-issues.techidaily.com/diagnosing-and-repairing-mpow-microphone-problems-in-the-windows-environment/"><u>Diagnosing and Repairing MPOW Microphone Problems in the Windows Environment</u></a></li>
<li><a href="https://review-topics.techidaily.com/identify-missing-or-malfunctioning-hardware-drivers-with-windows-device-manager-on-windows-10-by-drivereasy-guide/"><u>Identify missing or malfunctioning hardware drivers with Windows Device Manager on Windows 10</u></a></li>
<li><a href="https://tech-hub.techidaily.com/mastering-the-art-of-scriptwriting-for-youtube-using-chatgpt-techniques/"><u>Mastering the Art of Scriptwriting for YouTube Using ChatGPT Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-autominimize-a-step-by-step-process/"><u>Overcoming AutoMinimize: A Step-by-Step Process</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-interrupts-with-fixing-breakpoints/"><u>Overcoming Windows Interrupts with Fixing Breakpoints</u></a></li>
<li><a href="https://windows11.techidaily.com/perfecting-desktop-aesthetics-sticky-notes-on-w11w10/"><u>Perfecting Desktop Aesthetics: Sticky Notes on W11/W10</u></a></li>
<li><a href="https://os-tips.techidaily.com/reclaim-your-memories-effective-strategies-for-finding-and-restoring-missing-videos-on-ios-devices/"><u>Reclaim Your Memories: Effective Strategies for Finding and Restoring Missing Videos on iOS Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/timely-troubleshooting-your-chrome-clock-glitch/"><u>Timely Troubleshooting: Your Chrome Clock Glitch</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-screen-management-guide-for-dual-displays/"><u>Windows 11 Screen Management Guide for Dual Displays</u></a></li>
</ul></div>

