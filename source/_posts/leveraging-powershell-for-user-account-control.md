---
title: Leveraging PowerShell for User Account Control
date: 2024-07-11T21:56:20.341Z
updated: 2024-07-12T21:56:20.341Z
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
<li><a href="https://ios-pokemon-go.techidaily.com/the-best-ispoofer-alternative-to-try-on-apple-iphone-15-plus-drfone-by-drfone-virtual-ios/"><u>The Best iSpoofer Alternative to Try On Apple iPhone 15 Plus | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/android-freedom-the-most-popular-top-10-fb-video-extraction-tools-for-2024/"><u>Android Freedom  The Most Popular Top 10 FB Video Extraction Tools for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-disruption-fix-windows-gaming-woe-errors/"><u>Avoid Disruption, Fix Windows' Gaming WoE Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/altering-windows-11-identity-new-username-guide/"><u>Altering Windows 11 Identity: New UserName Guide</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-from-basics-to-brilliance-mastering-the-art-of-macbook-air-screen-capture/"><u>In 2024, From Basics to Brilliance  Mastering the Art of MacBook Air Screen Capture</u></a></li>
<li><a href="https://windows11.techidaily.com/a-shortcut-to-starting-wordpad-on-your-pc/"><u>A Shortcut to Starting WordPad on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/a-detailed-approach-to-fixing-windows-error-code-30005/"><u>A Detailed Approach to Fixing Windows Error Code: 30005</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-ultimate-guide-on-motorola-edge-40-neo-frp-bypass-by-drfone-android/"><u>In 2024, Ultimate Guide on Motorola Edge 40 Neo FRP Bypass</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-seamless-transition-from-tv-to-facebook-lives/"><u>2024 Approved  Seamless Transition  From TV to Facebook Lives</u></a></li>
<li><a href="https://windows11.techidaily.com/adding-windows-update-alerts-tooltip-menu-entry/"><u>Adding Windows Update Alerts Tooltip Menu Entry</u></a></li>
<li><a href="https://windows11.techidaily.com/balancing-cpu-and-memory-use-after-news-downloads/"><u>Balancing CPU & Memory Use After News Downloads</u></a></li>
<li><a href="https://extra-hints.techidaily.com/easy-acquisition-of-individual-ending-music-files/"><u>Easy Acquisition of Individual Ending Music Files</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-innovating-film-viewing-with-iphone-tricks/"><u>2024 Approved  Innovating Film Viewing with iPhone Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-decibels-on-windows-integrated-bt-audio/"><u>Boosting Decibels on Windows-Integrated BT Audio</u></a></li>
<li><a href="https://windows11.techidaily.com/a-practical-approach-to-windows-network-file-transfer-via-python/"><u>A Practical Approach to Windows Network File Transfer via Python</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-browsing-security-enhanced-graphics-on-edge/"><u>Boosting Browsing Security: Enhanced Graphics on Edge</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-the-premier-7-apps-transforming-mobile-video-streaming-on-youtube/"><u>[New] The Premier 7 Apps Transforming Mobile Video Streaming on YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-windows-settings-for-visible-sticky-notes/"><u>Adjusting Windows Settings for Visible Sticky Notes</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unrestricted-gaming-beats-digital-download/"><u>[Updated] Unrestricted Gaming Beats  Digital Download</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-low-power-options-for-better-battery-life/"><u>Adjusting Low-Power Options for Better Battery Life</u></a></li>
<li><a href="https://windows11.techidaily.com/7-proven-methods-to-enhance-your-windows-11-experience-35/"><u>7 Proven Methods to Enhance Your Windows 11 Experience (35)</u></a></li>
<li><a href="https://windows11.techidaily.com/7-ways-to-get-the-most-out-of-windows-11/"><u>7 Ways to Get the Most Out of Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/a-guide-to-uncovering-your-systems-identity-quickly/"><u>A Guide to Uncovering Your System's Identity Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/alternative-pathway-for-opening-file-explorer-through-onedrive/"><u>Alternative Pathway for Opening File Explorer Through OneDrive</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-techniques-locating-ip-and-mac-in-windows-ps/"><u>Advanced Techniques: Locating IP & MAC in Windows PS</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-complications-resetting-terminal-on-win11/"><u>Avoid Complications: Resetting Terminal on Win11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-launching-your-sports-network-from-a-mac-desktop/"><u>[Updated] Launching Your Sports Network From a Mac Desktop</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-expertly-convert-your-content-to-stellar-hd-with-top-tools/"><u>In 2024, Expertly Convert Your Content to Stellar HD with Top Tools</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-decoding-the-significance-of-each-tiktok-element-for-2024/"><u>[Updated] Decoding the Significance of Each TikTok Element for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/elite-internet-recorder-choices-7-to-try-for-2024/"><u>Elite Internet Recorder Choices - 7 to Try for 2024</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-rhythm-reconnaissance-leading-song-recognition-apps-you-must-have-on-your-android-gadget/"><u>New 2024 Approved Rhythm Reconnaissance Leading Song Recognition Apps You Must Have on Your Android Gadget</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-how-to-use-preview-app-on-mac-complete-guide/"><u>[New] How to Use Preview App on Mac [Complete Guide]</u></a></li>
<li><a href="https://windows11.techidaily.com/batch-heic-to-jpeg-images-in-windows-environment/"><u>Batch Heic to Jpeg Images in Windows Environment</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-vivo-s17t-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Vivo S17t? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-windows-11s-task-manager-launch-interface/"><u>Adjusting Windows 11'S Task Manager Launch Interface</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-20-best-copyright-free-pubg-montage-thumbnail/"><u>In 2024, 20 Best Copyright-Free PUBG Montage Thumbnail</u></a></li>
<li><a href="https://fox-glue.techidaily.com/advanced-techniques-to-leverage-windows-11-pro/"><u>Advanced Techniques to Leverage Windows 11 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/broken-binkey-bastion-proceed-prudently-not-promptly/"><u>Broken Binkey Bastion: Proceed Prudently, Not Promptly</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/11-window-wisdom-the-secret-techniques-youve-missed-out-on-for-2024/"><u>11 Window Wisdom  The Secret Techniques You've Missed Out On for 2024</u></a></li>
</ul></div>
