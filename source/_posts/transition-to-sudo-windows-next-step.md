---
title: "Transition to Sudo: Windows' Next Step"
date: 2024-11-20T23:18:05.324Z
updated: 2024-11-24T23:03:07.788Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Transition to Sudo: Windows' Next Step"
excerpt: "This Article Describes Transition to Sudo: Windows' Next Step"
keywords: SudoOSWindowsTransition,SudoForWindowsPCs,SudoNextStepWindows,UpgradingToSudoWin,TransitionToSudoWin,NextGenWindowsSudo,WindowsShiftToSudo
thumbnail: https://thmb.techidaily.com/1127690728774d68859773ac2967a71d9b05c7378c0abebd2da2f4a67474809a.jpg
---

## Transition to Sudo: Windows' Next Step

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iOVkXoUxLf4?si=QfC18T2cb5OkiaXo&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Enable the sudo Command on Windows

 If the sudo command isn't yet available for your version of Windows, you'll need to [sign up for Windows Insider](https://www.makeuseof.com/windows-11-insider-program-join/). This is a simple process, but be warned: the Developer and Canary options can be unstable, so don't use them on a PC you're not willing to lose data on.

 Once you're running a version of Windows that has the sudo command available, enabling it is a simple process. Open the **Settings** app, then select **System** on the left and **For developers** from the main area of the window.

 Here, scroll down and enable the checkbox that reads **Enable sudo**.

![Enabling sudo on Window in the Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/enabling-sudo-on-window-in-the-settings-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6KXVWj6Ar1M?si=Cd_jktmoN3e9OzH3&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Enable sudo via the Command Prompt

 If you're more command-line oriented, you can also enable sudo via the Commmand Prompt. Somewhat ironically, this requires you to run an elevated CMD window. Press the **Windows** key, type "command," then right-click on **Command Prompt** (or **PowerShell**) and select **Run as administrator**.

 In this prompt, run the following command:

`sudo config --enable enable`

![Enabling sudo on Windows via PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/enabling-sudo-on-windows-via-powershell.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Lp78eFEGwVU?si=-4orJBLvJJrggCJ2&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wVVp-GggK3U?si=RJb1ClNQV7GjTu_3&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Use the sudo Command on Windows

 After you've enabled the sudo command on Windows, it's simple to use. Simply prepend the `sudo` command to any command you'd typically need to run as an administrator, then accept the prompts that follow.

 An example from Microsoft uses the `netstat` command:

`sudo netstat -ab  
`

![Running a command on Windows via sudo](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/running-a-command-on-windows-via-sudo.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gSKkJrJ57EA?si=WDOmInPE9EgQa_tB&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-best-3d-software-for-dynamic-youtube-intros/"><u>[Updated] In 2024, Best 3D Software for Dynamic YouTube Intros</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-in-2024-step-by-step-tutorial-using-microsofts-movie-maker-on-w11/"><u>[Updated] In 2024, Step-By-Step Tutorial Using Microsoft's Movie Maker on W11</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-editing-game-changer-fcps-best-10-plugins/"><u>[Updated] The Editing Game Changer FCP's Best 10 Plugins</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-solutions-for-resolving-crackling-audio-issues-on-pcs-with-windows-107/"><u>Easy Solutions for Resolving Crackling Audio Issues on PCs with Windows 10/7</u></a></li>
<li><a href="https://windows11.techidaily.com/flawless-shopping-experience-eradicating-error-x80072f30-on-pc/"><u>Flawless Shopping Experience: Eradicating Error X80072F30 on PC</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-do-i-sign-a-doc-file-document-electronically-by-ldigisigner-sign-a-word-sign-a-word/"><u>How do i sign a .doc file document electronically</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-apple-iphone-11-asking-for-passcode-after-ios-1714-update-what-to-do-drfone-by-drfone-ios/"><u>In 2024, Apple iPhone 11 Asking for Passcode after iOS 17/14 Update, What to Do? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-can-i-use-a-fake-gps-without-mock-location-on-samsung-galaxy-s23-tactical-edition-drfone-by-drfone-virtual-android/"><u>In 2024, How Can I Use a Fake GPS Without Mock Location On Samsung Galaxy S23 Tactical Edition? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mobile-devices-enhancing-windows-microphone-use/"><u>Mobile Devices Enhancing Windows Microphone Use</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-blackwhite-display-issues-in-store-app/"><u>Overcoming Black/White Display Issues in Store App</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaiming-control-how-to-reactivate-non-responsive-keys/"><u>Reclaiming Control: How to Reactivate Non-Responsive Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-admin-controlled-security-settings-in-windows/"><u>Resolving Admin-Controlled Security Settings in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/starting-microsoft-paint-in-windows-11/"><u>Starting Microsoft Paint in Windows 11</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/stop-misplaced-story-tags-on-facebook-for-2024/"><u>Stop Misplaced Story Tags on Facebook for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/super-easy-ways-to-deal-with-lava-yuva-2-unresponsive-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Super Easy Ways To Deal with Lava Yuva 2 Unresponsive Screen | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-5-steps-for-non-functional-backlit-keys/"><u>Troubleshooting Windows: 5 Steps for Non-Functional Backlit Keys</u></a></li>
</ul></div>

