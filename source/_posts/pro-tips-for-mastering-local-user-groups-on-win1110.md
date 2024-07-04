---
title: Pro Tips for Mastering Local User Groups on Win11/10
date: 2024-06-25T12:02:16.204Z
updated: 2024-06-26T12:02:16.204Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Pro Tips for Mastering Local User Groups on Win11/10
excerpt: This Article Describes Pro Tips for Mastering Local User Groups on Win11/10
keywords: Win11 SEO,Local Group Lead,Win10 Optimization,User Engagement Tips,Local Networking Tricks,Pro UX Strategies,Win11 Best Practices
thumbnail: https://thmb.techidaily.com/423415d175d6eec024525c4afdad758a2e4f561184514d4182ee660b64af6137.jpg
---

## Pro Tips for Mastering Local User Groups on Win11/10

### Quick Links

* [Enable the Local Users and Groups Management Console in Windows 11/10 Home](#enable-the-local-users-and-groups-management-console-in-windows-11-10-home)
* [Manage Local Users and Groups Using the Command Prompt](#manage-local-users-and-groups-using-the-command-prompt)

### Key Takeaways

* Local Users and Groups Management is not available in Windows 11/10 Home editions. You need a third-party program to access it.
* You can use Lusrmgr.exe, a portable third-party alternative, to enable the Microsoft Management Console snap-in in Windows 11 Home. The Lusrmgr application provides additional features like account search and defining access times.
* The Command Prompt can also be used to manage users and groups without a third-party utility.

 Local Users and Groups Management is a shell application to manage local and remote computers and access system administrator tools. However, Local Users and Groups Management is unavailable in the Windows 11/10 Home editions, so you must rely on a third-party program to use it there.

## Enable the Local Users and Groups Management Console in Windows 11/10 Home

 Like the Local Group Policy Editor, Local Users and Groups Management (lusrmgr.msc) is an advanced feature available only on Windows Pro, Education, and Enterprise.

 However, while you can use workarounds to [enable Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/), it is not possible to enable the Local Users and Groups Management snap-in console.

 Instead, you can use Lusrmgr.exe, a third-party alternative, to enable the Microsoft Management Console snap-in in Windows 11 Home. Lusrmgr.exe is similar to the built-in Local Users and Groups Management console. It is a portable application, and you can download it from GitHub for free.

 Here's how to download and use the Local User and Group Management tool on Windows 11 Home. Follow the same steps on a Windows 10 PC:

1. Open the [lusrmgr GitHub page](https://github.com/proviq/lusrmgr).
2. On the default **Code** tab, scroll down to the **Download** link to get the latest version of the file.
3. Once downloaded, double-click the **lusrmgr.exe**file to run the program.

![lusrmgr program home screen running on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-program.jpg)

 You will notice the lusrmgr application looks similar to [opening the native Local Users and Groups Management console](http://www.makeuseof.com/windows-open-local-users-and-groups/). However, the difference lies in the usability of the tool. Below are side-by-side images for the built-in lusrmgr console (left) and the third-party application (right) for reference.

![Lucal User and Groups app and lusrmgr app side by side comparison](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/lucal-user-and-gropups-app-and-lusrmgr.jpg)

 To create a new user account with this Local User and Group Management tool:

1. Right-click on **User** and select **Create**. Then fill in the details for the new user account.
2. Click the **Advanced** button to configure the advanced account option, local path, and profile path.  
![lusrmgr create new user account screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-create-new-user.jpg)
3. Click on **Create** to add the new user account.

 Similarly, you can edit, remove, rename, or add a password to the existing user account. You can also [enable the secret built-in administrator account](https://www.makeuseof.com/windows-11-enable-disable-built-in-administrator-account/) using the tool.

### Additional Features of the Lusrmgr App

![The search bar in lusrmgr application](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-search.jpg)

 Apart from the usual account management features, lusrmgr.exe provides additional functions not available in the native utility. For example, you can use the search function to find a specific account. This is useful for system administrators who manage multiple user accounts in an organization.

 Another handy feature is the ability to define access times for individual accounts. To set an access time, right-click on the username and select **Edit**. Next, open the **Account** tab and click on **Define access time**.

![lusrmgr define account access time screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-define-access-time.jpg)

 By default, the user accounts have no limit on access time. But you can define this by selecting a time block for different days.

 Since lusrmgr is a portable app, you can’t open it with the **lusrmgr.msc** command like the built-in app. To launch the program, double-click the executable file you downloaded and make the necessary changes to the user account or groups.

## 2\. Manage Local Users and Groups Using the Command Prompt

 You can use the "net localgroup" or "net user" command-line utility to manage users and groups on Windows 11/10\. It's a handy way to view, add, and delete local groups and users without using a third-party utility.

![How to Run the Command Prompt as an Administrator in Windows Thumbnail](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/how-to-run-the-command-prompt-as-an-administrator-in-windows-thumbnail.jpg)

  First, open a Command Prompt window with administrative privilege. To do this, press the **Windows** key, type **cmd**, right-click on **Command Prompt**, and select **Run as administrator**.

 Below is a list of commands to view and manage local users and groups using the Command Prompt:

1. To view the name of the server and local groups on the computer, type:  
`net localgroup`
2. To view all users in a group, enter:  
`net localgroup [groupname]`
3. To create a new group, use the following command. Replace **xyz** with the group name you want to create:  
`net localgroup xyz /add`
4. To view all user accounts:  
`net user`
5. To create a new user account (replace **abc** with the username you want to add):  
`net user abc /add`

1. To view all the accounts with administrator privileges:  
`net localgroup administrator`
2. To add a user account to the administrator group (be sure to change **abc**, and **Administrator** to the group name if needed):  
`net localgroup Administrator abc /add`
3. To delete a local group:  
`net localgroup xyz /delete`
4. To delete a local user:  
`net user abc /delete`
5. If you need help with syntax for a specific command, use this:  
`net help <command>`

![Command Prompt screen with the net localgroup command displayed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/command-prompt-screen-with-the-net-localgroup-command-displayed.jpg)

 The Local Users and Groups Management console is a handy utility for system administrators to manage local computers and connect remotely to compatible systems. However, if you are running Windows 11 Home and need to use the lusrmgr.msc tool, your only option is to use the third-party application from GitHub.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/from-handheneld-to-hardware-android-titles-on-windows-via-google-service/"><u>From Handheneld to Hardware: Android Titles on Windows via Google Service</u></a></li>
<li><a href="https://windows11.techidaily.com/cut-the-cord-joining-dualshock-to-pc/"><u>Cut the Cord: Joining DualShock to PC</u></a></li>
<li><a href="https://windows11.techidaily.com/winservicesexe-what-it-is-and-fixing-errors/"><u>Winservices.exe: What It Is and Fixing Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/enrich-your-windows-setup-with-personal-menus/"><u>Enrich Your Windows Setup with Personal Menus</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-role-of-ai-in-windows-11-updates/"><u>Unveiling the Role of AI in Windows 11 Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-your-workflow-with-windows-11s-widget-toolbar/"><u>Boost Your Workflow with Windows 11'S Widget Toolbar</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-xc0000142-issue-in-windows-11-10/"><u>Correcting XC0000142 Issue in Windows 11, 10</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-does-the-stardust-trade-cost-in-pokemon-go-on-nubia-z50-ultra-drfone-by-drfone-virtual-android/"><u>How does the stardust trade cost In pokemon go On Nubia Z50 Ultra? | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/mastering-visual-impact-a-comprehensive-guide-to-zooms-video-filters-for-2024/"><u>Mastering Visual Impact  A Comprehensive Guide to Zoom's Video Filters for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/fusing-iphones-audio-and-visuals-together-for-2024/"><u>Fusing iPhones' Audio and Visuals Together for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-unlock-your-youtube-potential-expert-tips-on-writing-video-outlines/"><u>In 2024, Unlock Your YouTube Potential  Expert Tips on Writing Video Outlines</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-mastering-snapchats-secret-stories-creation-guide/"><u>[Updated] Mastering Snapchat's Secret Stories Creation Guide</u></a></li>
<li><a href="https://extra-information.techidaily.com/peak-workshop-masterpiece-insight/"><u>Peak Workshop Masterpiece Insight</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-vimeo-captions-101-the-essential-guide/"><u>2024 Approved  Vimeo Captions 101  The Essential Guide</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-7-phone-number-locators-to-track-vivo-y200-location-drfone-by-drfone-virtual-android/"><u>In 2024, Top 7 Phone Number Locators To Track Vivo Y200 Location | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-seamless-switch-to-virtual-reality-your-phones-next-step/"><u>In 2024, Seamless Switch to Virtual Reality  Your Phone's Next Step</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>