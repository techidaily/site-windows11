---
title: "Account Annihilation: Simple Ways to Render User Non-Existent on Win11"
date: 2025-01-22T22:48:30.161Z
updated: 2025-01-29T18:04:05.397Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Account Annihilation: Simple Ways to Render User Non-Existent on Win11"
excerpt: "This Article Describes Account Annihilation: Simple Ways to Render User Non-Existent on Win11"
keywords: Win11 Deactivation Guide,User Eradication Methods,Eliminate Account Login,Safe System Lockdown,Windows 11 UX Annihilation,Non-Existent User Removal,Security
thumbnail: https://thmb.techidaily.com/a577227bca81f1377b01a00eba21acdee9d8dfcda26cad3482a8cc47d1c6fe1b.jpg
---

## Account Annihilation: Simple Ways to Render User Non-Existent on Win11

 You can create multiple users account on Windows 11 for yourself and others. This allows you to create different spaces for your personal and work tasks and enable others to share your computer and have their own spaces.

 But what if you need to stop someone from accessing their account without deleting it? While you can temporarily disable a user account on Windows 11 using the block sign-in option, there are a few other ways to disable specific or all user accounts on Windows 11.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HSFNIAYChbA?si=4TIlsUrYmY5vP2il" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Disable a User Account in Windows Settings

 Windows allows the system administrator to manage user accounts on Windows 11\. Not only can you [add a local user account](https://www.makeuseof.com/windows-11-create-local-user-account/) there, but you can also block sign-in to disable an account temporarily.

To disable user accounts via Settings:

1. Press**Win + I** to open the**Settings** panel.
2. In the left pane, click on the**Accounts** tab.  
![windows 11 settings account family](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-11-settings-account-family-1.jpg)
3. Next, in the right pane, scroll down and click on**Family** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xq2r4ZKM-Po?si=fA2DdEB1op-atCkz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Under**Your family** , scroll down and click on the account you want to disable.  
![windows 11 settings account family block sign in](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-11-settings-account-family-block-sign-in-1.jpg)
5. Next, click the**Block sign in** button and click**Block** in the confirmation dialog.  
![windows 11 settings account family allow sign in](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-11-settings-account-family-allow-sign-in-1.jpg)
6. If you need to enable the user account again, click the**Allow sign in** button and click**Allow** to confirm the action.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/f-yPCh24EsA?si=3z8FAd_lMZeAjug7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Note that you must log in to your administrator account to make changes to user accounts. Also, you can only block sign-in for members of**Your family** in the Family groups from Settings. If you need to disable a local user account, you must use the PowerShell and Command Prompt methods below.

## 2\. How to Disable a User Account Using Windows PowerShell

 If you need to disable and enable user accounts frequently, PowerShell can help you do it efficiently. To do this, you can use the Disable-LocalUser cmdlet and specify the user account name you want to disable.

To disable a user account using PowerShell:

1. Press**Win + X** to open the**WinX** menu.
2. Click on**Terminal (Admin)** . It will open Windows Terminal with PowerShell set as the default profile.
3. If not, click the drop-down icon in the**Terminal** tabs section and select**Windows PowerShell** .  
![powerhsell user account list view](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/powerhsell-user-account-list-view.jpg)
4. Next, type the following command to find all the user accounts on your PC:  
`Get-LocalUser`
5. Locate the user account name in the**Name** column.

1. Next, type the following command to disable the specified user account:  
`Disable-LocalUser -Name &ldquo;NewUser&rdquo;`
2. In the above command, replace**NewUser** with the user account name you want to disable.  
![powerhsell user account disable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/powerhsell-user-account-disable.jpg)
3. PowerShell will not return a success message after the user account is disabled.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XA_wP7rS9ww?si=LarMG3sEHAhSoL6q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. If you need to enable the account again, type the following command and press Enter:  
`Enable-LocalUser -Name &ldquo;NewUser&rdquo;`
5. In the above command replace NewUser with your user account name.

 When disabled, the user account will be hidden from your lock screen. To verify the same, press**Win + L** to [lock your Windows 11 computer](https://www.makeuseof.com/windows-11-ways-to-lock/) . Next, double-click on the lock screen to view the login screen. If disabled, the user account will appear on the lower left side of your screen.

## 3\. Disable a User Account Using the Command Prompt

 Another way to disable a local user account is via the Command Prompt. It is a command-line utility that you can use to disable Microsoft or local user accounts.

To disable a user account using Command Prompt:

1. Press**Win + R** to open**Run** .
2. Type**cmd** in the**Run** box. Next, press**OK** while holding the**Ctrl + Shift** key to open the elevated Command Prompt. Click**Yes** if prompted by User Account Control.
3. In the Command Prompt window, type the following command to find all the available user accounts on your PC:  
`net user`
4. Locate the user account name in the return list.  
![command prompt net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/command-prompt-net-user.jpg)
5. Next, type the following command to disable the specified user account:  
`net user NewUser /active:no`
6. In the above command, replace**NewUser** with the user account name you want to disable.  
![command prompt net user disable account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/command-prompt-net-user-disable-account.jpg)
7. Next, type**exit** and press Enter to close Command Prompt.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=LvxQhsEJoymsM2iZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

8. If you need to enable the account again, execute the following command:  
`net user NewUser /Active:yes`
9. Make sure to replace NewUser with the account name you want to enable.

## 4\. Disable a User Account From the Computer Management Console

 The Computer Management Console gives system administrators access to advanced tools such as Task Scheduler, Event Viewer, Device Manager, etc. Another useful Computer Management feature is Local Users and Groups.

 Local User and Groups lets you manage user accounts and groups on your Windows computer. While the Computer Management console is available on all versions of Windows, Local User and Groups is only available on the Pro, Edu, and Enterprise edition of the OS.

 To disable user accounts using the Local Users and Groups Management console:

1. Click on the**Search icon** in**Taskbar** .
2. Type**computer management** and click on**Computer Management** from the search result.
3. In the**Computer Management** console, expand**System Tools** .  
![computer management local users groups users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/computer-managemnet-local-users-groups-users.jpg)
4. Next, locate and select**Local Users and Groups.**
5. Select the**Users** folder**.**

1. In the right pane, you can view all the user accounts on your PC.
2. To disable a user account, right-click on the**User Account Name** and select**Properties** .  
![computer management local users groups users account is disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/computer-managemnet-local-users-groups-users-account-is-disabled.jpg)
3. In the**Properties** dialog, select the**Account is disabled** option.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Iz2LYWd8EqI?si=G_3CqFRAmeVPczjj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Click**Apply** and**OK** to save the changes.
5. To enable the account gain, uncheck the**Account is disabled** option and click**Apply** and**OK** .

### Disable User Account Using Local Users and Groups on Windows 11 Home

 Windows 11 Home users will have to rely on a third-party tool to disable a user account via the Local User and Groups console. Lusrmgr is a third-party snap-in that offers similar functionalities as the Local Users and Groups Management console.

 To install the tool, follow our guide to [enable Local User and Group Management on Windows 11](https://www.makeuseof.com/windows-home-edition-enable-local-user-group-management/) . Once done, follow the steps below:

1. Double-click on the**lusrmgr.exe** file to launch the application.
2. In the**Local users and groups** dialog, select**Users** .
3. Right-click on the user account you want to disable and select**Edit** .  
![run lusrmgr exe file edit account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/run-lusrmgr-exe-file-edit-account.jpg)
4. Next, open the**Account** tab.
5. Select the**Account is disabled** option.  
![run lusrmgr exe file edit account disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/run-lusrmgr-exe-file-edit-account-disabled.jpg)
6. Click**Apply** and**OK** to save the changes.

## There Are Many Ways to Disable a User Account on Windows 11

 Disabling a user account lets you restrict access to a specific user account without deleting the account completely. This way, if you need to restore the account at a later stage, you can enable it and continue using it without restoring files and folders.

 That said, removing a user account on Windows 11 is not a complicated process. Just log in to your administrator account and block sign-in or remove user accounts from Settings, and you're pretty much done.

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
<li><a href="https://some-approaches.techidaily.com/2024-approved-superior-choices-elite-webcam-holders/"><u>2024 Approved Superior Choices Elite Webcam Holders</u></a></li>
<li><a href="https://article-posts.techidaily.com/in-2024-essential-tips-for-crafting-engaging-haul-videos/"><u>In 2024, Essential Tips for Crafting Engaging Haul Videos</u></a></li>
<li><a href="https://buynow-help.techidaily.com/in-depth-analysis-why-the-samsung-galaxy-note-9-dominates-big-screen-phones/"><u>In-Depth Analysis: Why the Samsung Galaxy Note 9 Dominates Big Screen Phones</u></a></li>
<li><a href="https://windows11.techidaily.com/is-wsl-functional-post-windows-11-install-solutions-explored/"><u>Is WSL Functional Post-Windows 11 Install? Solutions Explored</u></a></li>
<li><a href="https://discover-guides.techidaily.com/lost-your-windows-11-recycle-bin-discover-these-7-effective-fixes-now/"><u>Lost Your Windows 11 Recycle Bin? Discover These 7 Effective Fixes Now!</u></a></li>
<li><a href="https://windows11.techidaily.com/morning-magic-startup-seamlessly-unlock-notepad-quickly/"><u>Morning Magic: Startup Seamlessly, Unlock Notepad Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-intricacies-of-w11s-auto-hdr/"><u>Navigating the Intricacies of W11's Auto HDR</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-vram-in-windows-a-comprehensive-guide-for-gamers/"><u>Optimizing VRAM in Windows - A Comprehensive Guide for Gamers</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-0x800700e1-in-win10-and-11-pcs/"><u>Overcoming 0X800700E1 in Win10 & 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/prime-virtual-machines-elevating-windows-11-tech/"><u>Prime Virtual Machines Elevating Windows 11 Tech</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/revolutionize-online-advertising-with-cookiebots-advanced-algorithms/"><u>Revolutionize Online Advertising with Cookiebot's Advanced Algorithms</u></a></li>
<li><a href="https://win-top.techidaily.com/soluciona-el-problema-de-la-particion-borrada-de-windows-accidentalmente-con-estos-pasos-faciles/"><u>Soluciona El Problema De La Partición Borrada De Windows Accidentalmente Con Estos Pasos Fáciles</u></a></li>
<li><a href="https://win-blog.techidaily.com/solving-no-rest-for-the-wicked-game-crashes-on-windows-a-step-by-step-guide/"><u>Solving 'No Rest for the Wicked' Game Crashes on Windows: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/sound-expertise-for-beginners-in-microsofts-new-os/"><u>Sound Expertise for Beginners in Microsoft's New OS</u></a></li>
<li><a href="https://windows11.techidaily.com/swiftly-adapt-windows-settings-via-hotkey-techniques/"><u>Swiftly Adapt Windows Settings via Hotkey Techniques</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-visual-flow-color-matching-and-grading-in-powerdirector-for-beginners-for-2024/"><u>Updated Visual Flow Color Matching and Grading in PowerDirector for Beginners for 2024</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/winning-against-driver-verifier-detected-violation-bluescreen-a-comprehensive-solution-for-windows/"><u>Winning Against 'Driver Verifier Detected Violation' Bluescreen: A Comprehensive Solution for Windows #</u></a></li>
</ul></div>

