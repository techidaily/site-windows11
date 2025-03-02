---
title: Leveraging PowerShell for User Account Control
date: 2025-02-25T20:44:13.235Z
updated: 2025-03-02T13:43:33.131Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Leveraging PowerShell for User Account Control
excerpt: This Article Describes Leveraging PowerShell for User Account Control
keywords: Powershell UAC Management,Enhanced UAC with PS,PowerShell Security Controls,Optimize UAC Using PowerShell,Efficient UAC via Scripting,Automate User Rights in PowerShell,UAC Policy Configuration PS
thumbnail: https://thmb.techidaily.com/21aecb659e7a5e8e968da4a0f8638ae8bdef383eb58685f2674b422f72c9c0b9.jpg
---

## Leveraging PowerShell for User Account Control

 When managing user accounts on a Windows PC, it often makes sense to use the Settings app. After all, it provides a graphical user interface that simplifies the process. But for those who'd rather manage the accounts with fewer clicks, they can use the **net user** command in Command Prompt to manage user accounts on Windows.

 In this guide, we're going to show you how to use the net user command to perform various actions on user accounts on a Windows computer.

## 1\. List All User Accounts

![list all user accounts with net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/list-all-user-accounts-with-net-user.jpg)

 Before you start managing user accounts with **net user**, it helps to know all the user accounts on your computer. To list them all, [open Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/), enter the below command, and hit the **Enter** key to run it:

`net user`

 Keep the names you see in mind, as you will need them as you use the **net user** command.

## 2\. Show All the Information of a User Account

![user account details while using net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/user-account-details-while-using-net-user.jpg)

 You can also bring up all the important information about a user by simply typing the **net user** command followed by the name of the user's name. Here's the basic syntax:

`net user Username`

 Let's say there's a user named "Jack" on the computer. To bring up their account information, you'd enter the below command, replacing **Username** in the above command structure with **Jack**:

`net user Jack`

 Once you run the command, you'll be able to see, the user's full name, when their password expires, when they last logged in, whether they're an administrator, and more.

## 3\. Add and Delete a User Account

 To add a new user in Command Prompt, you need to use the **net user** command followed by the name of the new account, the desired password you wish to set, and the **/add** switch (this tells **net user** that you're adding a user). Here's the basic syntax of the command:

`net user Username Password /add`

 Keep in mind that all you'll be creating here is a local account, but you can always [switch a local account to a Microsoft account](https://www.makeuseof.com/windows-switch-local-account-to-microsoft-account/) later on. Here's an example of the command in action:

`net user Jill Pa$w0rd /add`

 After you run that command, you'll see that the new user, **Jill**, has been added to your computer. To delete an account, just replace the **/add** switch with **/delete** without specifying the password. Here's how:

`net user Jill /delete`

 Now net user will remove the account from the computer.

## 4\. Enable and Disable a User Account

![deactivating an account with net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/deactivating-an-account-with-net-user.jpg)

 If there's a user you wish to temporarily restrict so they can't access their account, you can simply disable it instead of deleting it. Here's the basic syntax of that action, making sure to use the **/active:no** switch at the end of the command to tell **net user** you're disabling it:

`net user Username /active:no`

 So, here's an example of what disabling an account would look like after replacing **Username** with the name of the actual user account:

`net user Jack /active:no`

 And if you want to enable a disabled account, you just have to change the **/active:no** switch to **/active:yes**.

## 5\. Enable and Disable a Domain User Account

 Sometimes, you might not want a user to access all the resources in a particular domain. The easier way to restrict them is to disable their account in that domain. You can do this by adding the **/domain** switch to the syntax discussed in the previous section.

 Here's the syntax for disabling an account on a particular domain using **net user**, making sure to replace **Username** with the name of the user you want to disable:

`net user Username /domain /active:no`

 If you want to enable an account on a domain, just use the **/active:yes** switch in the above command structure instead.

## 6\. Set User Account Login Times

 If you want to specify the times someone can log in, you can use the **/time** parameter to specify the account login times. You can use the basic syntax below:

`net user Username /time login_times`

 In the above command structure, replace **Username** with the user you want to limit the login times for, and **login\_times** with a time range in the format **D-D,00:00**. Here's an example of how you'd do this:

`net user Jack /time:M-F,09:00-17:00`

 As per the example above, that user can only log in from Monday to Friday between 9 a.m. and 5 p.m. If Jack tried to log in, he'd get a message saying **Your account has time restrictions that prevent you from signing in**.

 To remove the time restrictions, you'd use the below command:

`net user Jack /time:all`

 Now Jack can go back to logging in whenever he wants.

## 7\. Set User Account Expiry Date

![setting an account expiriation date with net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/setting-an-account-expiriation-date-with-net-user.jpg)

 By default, accounts are set to never expire, but you can change that if you have a user you want to be active for a specific period of time. You will need to use the **/expires** parameter while specifying the year, month, and expiration date. Here's the basic command structure:

`net user Username /expires:DD/MM/YYYY`

 An example of this in action would be:

`net user Jack /expires:27/07/2024`

 With the above command, Windows will disable the on the date you've set above.

## 8\. Change the Password of a User Account

 You can also use the **net user** command to [change the password of a user account in Command Prompt](https://www.makeuseof.com/tag/quick-tip-change-the-windows-user-password-via-command-line/). This will make it so that you can quickly change the password of any local account with a single command, instead of having to do it through the Settings app, which requires many clicks.

 The beauty of it is that you can also use it to change passwords for multiple accounts without leaving the Command Prompt window.

## 9\. Change the Password of a Domain User Account

 You can also change the password of a user on a domain by appending the **/domain** switch at the end of the command for changing a user account. The syntax for this is as follows:

`net user Username NewPassword /domain`

 Again this has to be a local domain user account for this to work. So, if you [changed the user account from a Microsoft account to a local account](https://www.makeuseof.com/how-to-switch-windows-from-microsoft-account-to-local-account/), you'll need to switch it back to use the command.

## 10\. Set a Password Policy for Users

![setting an account policy with net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/setting-account-policy-with-net-user.jpg)

 If you need a particular user to change the password during their next login, you can use the **net user** command along with the **/passwordchg:yes** parameter (by default, the parameter is **/passwordchg:no**). Here's the basic syntax:

`net user Username /passwordchg:yes`

 Here's an example of what that would look like in Command Prompt:

`net user Jack /passwordchg:yes`

 So, the next time Jack logs into the computer, he will get a prompt asking him to change his password before he can access his user account.

## 11\. Set a Home Directory for Users

 When creating a new user profile using **net user**, you can set the home directory, which is where Windows will store the user's personal files and settings. By default, Windows places the home directory of each user account in **This PC > Local Disk (C:) > Users**. To change this with **net user** during account creation, the basic syntax is as follows:

`net user Username Password /add /homedir:Path-to-directory`

 A real-world example of this would be:

`net user Jack Pa$w0rd /add /homedir:D:\Other Users\Jack`

 The above command will place the home directory of **Jack**, as it creates the account, in the **D:\\Other Users\\Jack** folder.

## Take Control of Your Computer's Users Accounts With the Net User Command

 Net user is a simple command to understand, allowing you to effectively manage your accounts from one location: Command Prompt. Of course, we haven't covered everything here, as there are too many parameters and switches to cover in a single guide.

 With that said, after you've understood how to perform the **net user** actions we've covered, you'll be on your way to managing accounts on Windows much quicker.

 In this guide, we're going to show you how to use the net user command to perform various actions on user accounts on a Windows computer.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-record-videos.techidaily.com/new-dodging-doubts-a-guide-to-vloggings-most-common-anxieties-for-2024/"><u>[New] Dodging Doubts A Guide to Vlogging's Most Common Anxieties for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/n-2024-dialing-in-the-perfect-aspect-ratio-for-youtube-images/"><u>[New] In 2024, Dialing in the Perfect Aspect Ratio for YouTube Images</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-a-comprehensive-guide-to-personalizing-video-images/"><u>[Updated] A Comprehensive Guide to Personalizing Video Images</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-in-2024-best-nine-essential-live-gaming-services/"><u>[Updated] In 2024, Best Nine Essential Live Gaming Services</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-beyond-the-ordinary-superior-share-like-software/"><u>2024 Approved Beyond the Ordinary Superior Share-Like Software</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-integrating-aesthetic-enhancements-into-windows-photos-audio-plus-visuals/"><u>2024 Approved Integrating Aesthetic Enhancements Into Windows Photos Audio + Visuals</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-fixes-for-unresponsive-windows-defender-security-shield/"><u>Essential Fixes for Unresponsive Windows Defender Security Shield</u></a></li>
<li><a href="https://tech-hub.techidaily.com/innovative-worldbuilding-with-chatgpt-unleash-your-creative-potential/"><u>Innovative Worldbuilding with ChatGPT: Unleash Your Creative Potential</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/kid-friendly-mirari-alarm-clock-unveiled-a-comprehensive-product-review/"><u>Kid-Friendly Mirari Alarm Clock Unveiled: A Comprehensive Product Review</u></a></li>
<li><a href="https://android-unlock.techidaily.com/mastering-android-device-manager-the-ultimate-guide-to-unlocking-your-vivo-v27e-device-by-drfone-android/"><u>Mastering Android Device Manager The Ultimate Guide to Unlocking Your Vivo V27e Device</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-new-era-of-win-pc-memory-capacity/"><u>Navigating the New Era of Win PC Memory Capacity</u></a></li>
<li><a href="https://windows11.techidaily.com/power-through-print-settings-in-win11-quick-guide-max-48-chars/"><u>Power Through Print Settings in Win11 - Quick Guide (Max 48 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-recovery-actions-save-vanished-windows-content/"><u>Quick Recovery Actions: Save Vanished Windows Content</u></a></li>
<li><a href="https://games-able.techidaily.com/remedying-steams-content-not-loading-problem/"><u>Remedying Steam's Content Not Loading Problem</u></a></li>
<li><a href="https://windows11.techidaily.com/stepping-up-stalled-safety-settings-on-win-11/"><u>Stepping Up Stalled Safety Settings on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-system-recovery-focus-on-net-max-156/"><u>Streamlining System Recovery: Focus on .NET (Max 156)</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-smooth-gaming-on-windows-eradicate-errors/"><u>Unleash Smooth Gaming on Windows, Eradicate Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-divine-control-windows-11s-spiritual-command-center-guide/"><u>Unlocking Divine Control: Windows 11'S Spiritual Command Center Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/winrar-archive-integrity-preventing-checksum-error-messages/"><u>WinRAR Archive Integrity: Preventing Checksum Error Messages</u></a></li>
</ul></div>

