---
title: Sudo's Arrival in Windows OS Explained
date: 2024-06-25T12:22:34.139Z
updated: 2024-06-26T12:22:34.139Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Sudo's Arrival in Windows OS Explained
excerpt: This Article Describes Sudo's Arrival in Windows OS Explained
keywords: Windows Sudo Guide,Sudo Functionality,Windows Operating System,Understanding Sudo,Windows Security Features,OS Command Line Usage,Sudo in Windows Update
thumbnail: https://thmb.techidaily.com/c80fad792e3cb229a3e653969139437b39335328a63ecf71a877586d96fe497a.jpg
---

## Sudo's Arrival in Windows OS Explained

### Key Takeaways

* The sudo command on Windows lets you run commands with elevated privileges.
* Microsoft is introducing sudo in Windows 11 to make using the command line more convenient.
* Enable sudo via Settings, the Command Prompt, or PowerShell.

 If you're a fan of tweaking your Windows setup, you often need to run "elevated" or Administrator-level commands. You're probably used to doing this by running a Command Prompt as administrator, but it's about to get a lot easier with sudo on Windows.

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

### Enable sudo via the Command Prompt

 If you're more command-line oriented, you can also enable sudo via the Commmand Prompt. Somewhat ironically, this requires you to run an elevated CMD window. Press the **Windows** key, type "command," then right-click on **Command Prompt** (or **PowerShell**) and select **Run as administrator**.

 In this prompt, run the following command:

`sudo config --enable enable`

![Enabling sudo on Windows via PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/enabling-sudo-on-windows-via-powershell.jpg)

## How to Use the sudo Command on Windows

 After you've enabled the sudo command on Windows, it's simple to use. Simply prepend the `sudo` command to any command you'd typically need to run as an administrator, then accept the prompts that follow.

 An example from Microsoft uses the `netstat` command:

`sudo netstat -ab  
`

![Running a command on Windows via sudo](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/running-a-command-on-windows-via-sudo.jpg)

 This feature may seem a tad unnecessary—and for many people, it is. That said, if you spend your day running command after command on Windows and wish for the simplicity of the sudo command, its addition will make your life easier.

 Microsoft seems committed to its implementation of sudo, even going so far as to release [sudo on GitHub](http://github.com/microsoft/sudo) as open source. If reading this entices you to learn more about what goes on under the hood in Windows, make sure to take a look at our list of [commands every Windows user should know](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/).

 If you're a fan of tweaking your Windows setup, you often need to run "elevated" or Administrator-level commands. You're probably used to doing this by running a Command Prompt as administrator, but it's about to get a lot easier with sudo on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/hidden-panels-revealed-recovering-offscreen-windows-in-edges-os/"><u>Hidden Panels Revealed: Recovering Offscreen Windows in Edges OS</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-alternate-pdf-reader-on-windows/"><u>Configuring Alternate PDF Reader on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-your-windows-onedrive-hurdles-now/"><u>Fix Your Windows OneDrive Hurdles Now</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-graphics-glitch-d3d11-error-fixes-for-win11win10/"><u>Conquering Graphics Glitch: D3D11 Error Fixes for Win11/Win10</u></a></li>
<li><a href="https://windows11.techidaily.com/bypass-windows-11-lock-screen-swiftly/"><u>Bypass Windows 11 Lock Screen Swiftly</u></a></li>
<li><a href="https://windows11.techidaily.com/reinitializing-your-steam-gaming-milestones/"><u>Reinitializing Your Steam Gaming Milestones</u></a></li>
<li><a href="https://windows11.techidaily.com/8-ways-to-fix-the-windows-pin-not-working-in-windows-10-and-11/"><u>8 Ways to Fix the Windows PIN Not Working in Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-completely-removing-wsl-in-win-11/"><u>Step-by-Step: Completely Removing WSL in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-wisdom-efficiently-eliminate-partitioned-areas-on-your-pc/"><u>Windows Wisdom: Efficiently Eliminate Partitioned Areas on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/dealing-with-nvidias-geforce-x0001-error-on-w10w11/"><u>Dealing with Nvidia's GeForce X0001 Error on W10/W11</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-the-activation-lock-on-your-ipad-and-apple-iphone-12-without-apple-account-by-drfone-ios/"><u>In 2024, How to Remove the Activation Lock On your iPad and Apple iPhone 12 without Apple Account</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-screenplay-sensation-roundup/"><u>[Updated] Screenplay Sensation Roundup</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/various-methods-to-transfer-pictures-from-apple-iphone-15-pro-max-to-pc-drfone-by-drfone-transfer-from-ios/"><u>Various Methods to Transfer Pictures from Apple iPhone 15 Pro Max to PC | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/easily-unlock-your-realme-gt-5-device-sim-by-drfone-android/"><u>Easily Unlock Your Realme GT 5 Device SIM</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-harmonious-sound-editing-guide-advantages-disadvantages-and-substitutes/"><u>Updated 2024 Approved Harmonious Sound Editing Guide Advantages, Disadvantages, and Substitutes</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-do-i-stop-someone-from-tracking-my-nokia-g310-drfone-by-drfone-virtual-android/"><u>How Do I Stop Someone From Tracking My Nokia G310? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-undelete-lost-music-from-motorola-moto-g14-by-fonelab-android-recover-music/"><u>Best Android Data Recovery - Undelete Lost Music from Motorola Moto G14</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-slow-motion-and-fast-motion-effects-in-camtasia/"><u>Updated In 2024, Slow Motion and Fast Motion Effects in Camtasia</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-styling-your-content-a-compreran-guide-to-insta-photo-watermarks/"><u>[Updated] 2024 Approved  Styling Your Content  A Compreran Guide to Insta Photo Watermarks</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-the-educators-resourceful-recorder-companion/"><u>[New] The Educator's Resourceful Recorder Companion</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>