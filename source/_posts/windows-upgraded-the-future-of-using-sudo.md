---
title: "Windows Upgraded: The Future of Using Sudo"
date: 2025-01-02T20:32:24.085Z
updated: 2025-01-04T00:10:21.023Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows Upgraded: The Future of Using Sudo"
excerpt: "This Article Describes Windows Upgraded: The Future of Using Sudo"
keywords: Windows Upgrade Secrets,Sudo Usage Insights,Modern OS Enhancement,Sudo Power Evolution,System Update Trends,Command-Line Optimization,Windows Tech Advancement
thumbnail: https://thmb.techidaily.com/99216a5fd24020f4e914206166919d3aff0939ed370c089abccf39caae51dc78.jpg
---

## Windows Upgraded: The Future of Using Sudo

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DxUX4R6Cf7c?si=prHevNQJivSkIfUt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* The sudo command on Windows lets you run commands with elevated privileges.
* Microsoft is introducing sudo in Windows 11 to make using the command line more convenient.
* Enable sudo via Settings, the Command Prompt, or PowerShell.

 If you're a fan of tweaking your Windows setup, you often need to run "elevated" or Administrator-level commands. You're probably used to doing this by running a Command Prompt as administrator, but it's about to get a lot easier with sudo on Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aIx71tPaWKg?si=lG5OiUe-M6eBJf5b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Does the sudo Command Do?

 Despite the general focus on configuring everything through the Settings apps and easy-to-use configuration wizards on Windows, every once in a while, you still need to type in commands. Many of these won't work with your standard user account. Instead, you need to run them as an administrator. Requiring administrator permissions is still a relatively new concept in Windows, but it was prevalent for far longer in older operating systems.

 It was so prevalent that operating system developers thought about a solution to the problem decades ago. Unix installations had, and still do have, a `su` command, which means "switch user." This would allow you to switch accounts to any other user, but could also let you run as the administrator, or superuser, account of the system by default.

 This solution worked, but logging in as the administrator to run one command seemed like overkill. As a solution, developers created the sudo command, which means either "switch user and do," or "superuser do," depending on various opinions. Long story short, the sudo command lets you easily run one command with elevated privileges—we've covered [the differences between su and sudo](http://www.makeuseof.com/sudo-vs-su/) if you're curious.

 This means that the sudo command is roughly equivalent to right-clicking on the Command Prompt app, selecting **Run as administrator**, and running a command, like `do_something`. With the help of the sudo command, you don't need to worry about remembering to run the Command Prompt as administrator. Instead, simply type `sudo do_something`, and the command will work in exactly the same way.

## Which Windows Versions Can Run the sudo Command?

 Microsoft is adding the sudo command to Windows 11, and considering that support for Windows 10 is winding down, we don't expect to see the command coming there anytime soon. At the time of writing, the sudo command is only available for Windows Insider participants (builds 26045 and later), specifically those on the Developer and [Windows Canary channels](https://www.makeuseof.com/what-is-windows-insider-canary-channel/).

 Unlike some features that Microsoft tests in these versions, it seems fairly likely that sudo is going to arrive on the operating system soon.

## How to Enable the sudo Command on Windows

 If the sudo command isn't yet available for your version of Windows, you'll need to [sign up for Windows Insider](https://www.makeuseof.com/windows-11-insider-program-join/). This is a simple process, but be warned: the Developer and Canary options can be unstable, so don't use them on a PC you're not willing to lose data on.

 Once you're running a version of Windows that has the sudo command available, enabling it is a simple process. Open the **Settings** app, then select **System** on the left and **For developers** from the main area of the window.

 Here, scroll down and enable the checkbox that reads **Enable sudo**.

![Enabling sudo on Window in the Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/enabling-sudo-on-window-in-the-settings-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6xGqSETroqA?si=4C1GPgXi-AksR_oO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Enable sudo via the Command Prompt

 If you're more command-line oriented, you can also enable sudo via the Commmand Prompt. Somewhat ironically, this requires you to run an elevated CMD window. Press the **Windows** key, type "command," then right-click on **Command Prompt** (or **PowerShell**) and select **Run as administrator**.

 In this prompt, run the following command:

`sudo config --enable enable`

![Enabling sudo on Windows via PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/enabling-sudo-on-windows-via-powershell.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5FWCFI3f_cs?si=Kt2Onr_E4c616tbH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/umvX4ZdWbxk?si=tPXL0-Kzf9SQaY8z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Use the sudo Command on Windows

 After you've enabled the sudo command on Windows, it's simple to use. Simply prepend the `sudo` command to any command you'd typically need to run as an administrator, then accept the prompts that follow.

 An example from Microsoft uses the `netstat` command:

`sudo netstat -ab  
`

![Running a command on Windows via sudo](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/running-a-command-on-windows-via-sudo.jpg)

 This feature may seem a tad unnecessary—and for many people, it is. That said, if you spend your day running command after command on Windows and wish for the simplicity of the sudo command, its addition will make your life easier.

 Microsoft seems committed to its implementation of sudo, even going so far as to release [sudo on GitHub](http://github.com/microsoft/sudo) as open source. If reading this entices you to learn more about what goes on under the hood in Windows, make sure to take a look at our list of [commands every Windows user should know](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/).

 If you're a fan of tweaking your Windows setup, you often need to run "elevated" or Administrator-level commands. You're probably used to doing this by running a Command Prompt as administrator, but it's about to get a lot easier with sudo on Windows.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-http.techidaily.com/new-2024-approved-top-9-innovative-websites-offering-unique-3d-graffiti-typefaces/"><u>[New] 2024 Approved Top 9 Innovative Websites Offering Unique 3D Graffiti Typefaces</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-crafting-content-step-by-step-guide-to-youtube-video-editing-for-2024/"><u>[Updated] Crafting Content Step by Step Guide to YouTube Video Editing for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-enhancing-artistic-photographs-with-illustrators-motion-blur/"><u>[Updated] In 2024, Enhancing Artistic Photographs with Illustrator's Motion Blur</u></a></li>
<li><a href="https://discover-excellent.techidaily.com/acronis-true-image-remains-unmatched-in-cloning-features-opgelopen-review/"><u>Acronis True Image Remains Unmatched in Cloning Features - Opgelopen Review</u></a></li>
<li><a href="https://youtube-data.techidaily.com/al-video-conquerors-ultimate-toolkit-list/"><u>Digital Video Conquerors' Ultimate Toolkit List</u></a></li>
<li><a href="https://windows11.techidaily.com/get-the-most-from-wsl-2-top-methods-on-windows-based-systems/"><u>Get the Most From WSL 2: Top Methods on Windows-Based Systems</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-samsung-galaxy-a25-5g-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Samsung Galaxy A25 5G to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-samsung-galaxy-f54-5g-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>How to Unlock Samsung Galaxy F54 5G Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-steam-achievements-redo/"><u>Mastering the Art of Steam Achievements Redo</u></a></li>
<li><a href="https://windows11.techidaily.com/methodology-to-revive-windows-steam-iconage/"><u>Methodology to Revive Windows Steam Iconage</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-windows-performance-by-curbing-tiworkerexe-resources/"><u>Optimizing Windows Performance by Curbing TiWorker.exe Resources</u></a></li>
<li><a href="https://windows11.techidaily.com/quiet-the-clicks-fixes-to-resurrect-spacebar-volume-control/"><u>Quiet the Clicks: Fixes to Resurrect Spacebar Volume Control</u></a></li>
<li><a href="https://windows11.techidaily.com/reconciling-excel-and-windows-notepad-compatibility/"><u>Reconciling: Excel and Windows Notepad Compatibility</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-screen-no-pin-mastery-for-projector-mode-win11/"><u>Secure Screen, No-Pin Mastery for Projector Mode Win11</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ring-titles-and-tags-for-top-youtube-performance-for-2024/"><u>Tailoring Titles and Tags for Top YouTube Performance for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-ultimate-how-to-configuring-safe-senders-list-feature-in-apples-mail-app-for-macos/"><u>The Ultimate How-To: Configuring Safe Senders List Feature in Apple's Mail App for macOS</u></a></li>
<li><a href="https://windows11.techidaily.com/title-customizing-icon-separation-in-winoss-1011/"><u>Title: Customizing Icon Separation in WinOSs (10/11)</u></a></li>
</ul></div>

