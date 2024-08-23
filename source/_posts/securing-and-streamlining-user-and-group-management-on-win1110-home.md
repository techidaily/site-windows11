---
title: Securing & Streamlining User and Group Management on WIN11/10 Home
date: 2024-08-22T21:31:58.157Z
updated: 2024-08-23T21:31:58.157Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Securing & Streamlining User and Group Management on WIN11/10 Home
excerpt: This Article Describes Securing & Streamlining User and Group Management on WIN11/10 Home
keywords: Win11 User Management,Win11 Group Control,Win11 Security Setup,Windows 11 Streamline,Admin Tools WIN11,ProgUser Groups Win10,Secure Win10/11 Users
thumbnail: https://thmb.techidaily.com/c2ff7acd78dea76e7429574a96f5d83925797a8b18bf953373ef1ee065acd190.jpg
---

## Securing & Streamlining User and Group Management on WIN11/10 Home

### Quick Links

* [Enable the Local Users and Groups Management Console in Windows 11/10 Home](#enable-the-local-users-and-groups-management-console-in-windows-11-10-home)
* [Manage Local Users and Groups Using the Command Prompt](#manage-local-users-and-groups-using-the-command-prompt)

### Key Takeaways

* Local Users and Groups Management is not available in Windows 11/10 Home editions. You need a third-party program to access it.
* You can use Lusrmgr.exe, a portable third-party alternative, to enable the Microsoft Management Console snap-in in Windows 11 Home. The Lusrmgr application provides additional features like account search and defining access times.
* The Command Prompt can also be used to manage users and groups without a third-party utility.

 Local Users and Groups Management is a shell application to manage local and remote computers and access system administrator tools. However, Local Users and Groups Management is unavailable in the Windows 11/10 Home editions, so you must rely on a third-party program to use it there.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
 To create a new user account with this Local User and Group Management tool:

1. Right-click on **User** and select **Create**. Then fill in the details for the new user account.
2. Click the **Advanced** button to configure the advanced account option, local path, and profile path.  
![lusrmgr create new user account screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-create-new-user.jpg)
3. Click on **Create** to add the new user account.
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->

 Similarly, you can edit, remove, rename, or add a password to the existing user account. You can also [enable the secret built-in administrator account](https://www.makeuseof.com/windows-11-enable-disable-built-in-administrator-account/) using the tool.

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Additional Features of the Lusrmgr App

![The search bar in lusrmgr application](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-search.jpg)

 Apart from the usual account management features, lusrmgr.exe provides additional functions not available in the native utility. For example, you can use the search function to find a specific account. This is useful for system administrators who manage multiple user accounts in an organization.

 Another handy feature is the ability to define access times for individual accounts. To set an access time, right-click on the username and select **Edit**. Next, open the **Account** tab and click on **Define access time**.

![lusrmgr define account access time screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/lusrmgr-define-access-time.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
 By default, the user accounts have no limit on access time. But you can define this by selecting a time block for different days.

 Since lusrmgr is a portable app, you can’t open it with the **lusrmgr.msc** command like the built-in app. To launch the program, double-click the executable file you downloaded and make the necessary changes to the user account or groups.

## 2\. Manage Local Users and Groups Using the Command Prompt

 You can use the "net localgroup" or "net user" command-line utility to manage users and groups on Windows 11/10\. It's a handy way to view, add, and delete local groups and users without using a third-party utility.

![How to Run the Command Prompt as an Administrator in Windows Thumbnail](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/how-to-run-the-command-prompt-as-an-administrator-in-windows-thumbnail.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://youtube-webster.techidaily.com/024-approved-rise-of-the-alternative-top-3-video-sharing-websites/"><u>[New] 2024 Approved  Rise of the Alternative  Top 3 Video Sharing Websites</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-economical-pc-streaming-with-simple-obs-configurations/"><u>[New] In 2024, Economical PC Streaming with Simple OBS Configurations</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-ultimate-11-list-streaming-audio-recorders-uncovered/"><u>[Updated] Ultimate #11 List  Streaming Audio Recorders Uncovered</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/bring-back-the-colors-lenovos-secret/"><u>Bring Back The Colors: Lenovo's Secret</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/discofest-unveiled-the-top-ten-themes-revealed/"><u>DiscoFest Unveiled  The Top Ten Themes Revealed</u></a></li>
<li><a href="https://windows11.techidaily.com/expanding-external-devices-in-explorers-side/"><u>Expanding External Devices in Explorer's Side</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-non-working-windows-performance-indicator/"><u>Fixing Non-Working Window's Performance Indicator</u></a></li>
<li><a href="https://windows11.techidaily.com/from-cr2-to-jpg-on-windows-a-comprehensive-conversion-guide/"><u>From CR2 to JPG on Windows: A Comprehensive Conversion Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-always-show-task-manager-on-top-of-other-open-windows/"><u>How to Always Show Task Manager on Top of Other Open Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-enable-or-disable-in-hand-typing-windows-10/"><u>How to Enable or Disable In-Hand Typing Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-enable-quake-mode-in-windows-terminal/"><u>How to Enable Quake Mode in Windows Terminal</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-manually-install-a-driver-in-windows-7-by-drivereasy-guide/"><u>How to Manually Install a Driver in Windows 7</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-open-the-calculator-in-windows-11/"><u>How to Open the Calculator in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/identify-and-secure-open-tcpip-in-windows/"><u>Identify and Secure Open TCP/IP in Windows</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-pgsharp-legal-when-you-are-playing-pokemon-on-itel-p40plus-drfone-by-drfone-virtual-android/"><u>In 2024, Is pgsharp legal when you are playing pokemon On Itel P40+? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-file-history-setting-glitch-in-windows-os/"><u>Mending File History Setting Glitch in Windows OS</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-an-ai-prompt-engineers-journey-steady-income-potential-revealed/"><u>Navigating an AI Prompt Engineer's Journey: Steady Income Potential Revealed</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-win11-settings-for-defaults/"><u>Navigating Win11 Settings for Defaults</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-freeze-frames-in-windows-league-of-legends/"><u>Overcoming Freeze Frames in Windows League of Legends</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-projection-failure-issue/"><u>Overcoming Windows Projection Failure Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/overhauling-fatal-exception-error-0x8007045d-on-pc/"><u>Overhauling Fatal Exception Error 0X8007045D on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/precision-in-diagnosis-navigating-through-windows-error-messages-with-command-line-skills/"><u>Precision in Diagnosis: Navigating Through Windows Error Messages with Command Line Skills</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaim-your-lost-5ghz-lan-link-in-windows-11-heres-how/"><u>Reclaim Your Lost 5GHz LAN Link in Windows 11 Here's How</u></a></li>
<li><a href="https://windows11.techidaily.com/regaining-power-a-windows-guide-to-net-repair-max-156/"><u>Regaining Power: A Windows Guide to .NET Repair (Max 156)</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-unreadable-messages-in-discord-chat/"><u>Remedying Unreadable Messages in Discord Chat</u></a></li>
<li><a href="https://windows11.techidaily.com/rewind-and-restore-key-applications-for-changing-createdmodified-dates/"><u>Rewind and Restore: Key Applications for Changing Created/Modified Dates</u></a></li>
<li><a href="https://screen-capture.techidaily.com/seamless-video-communication-in-whatsapp-web-for-laptops-and-desktops-for-2024/"><u>Seamless Video Communication in WhatsApp Web for Laptops and Desktops for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/secrets-to-amplifying-gopro-power-life-span/"><u>Secrets to Amplifying GoPro Power Life Span</u></a></li>
<li><a href="https://windows11.techidaily.com/simplified-guide-for-converting-bat-files-into-exes/"><u>Simplified Guide for Converting .bat Files Into EXEs</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-swiftly-eradicating-windows-steams-e84-error/"><u>Strategies for Swiftly Eradicating Windows Steam's E84 Error</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-data-management-in-windows-with-custom-commands/"><u>Streamlining Data Management in Windows with Custom Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/supercharge-win11s-notepad-with-astute-mentor/"><u>Supercharge Win11's Notepad with Astute Mentor</u></a></li>
<li><a href="https://windows11.techidaily.com/tailor-made-window-ordering-powertoy-guide-to-win-os-snaps/"><u>Tailor-Made Window Ordering: PowerToy Guide to Win OS Snaps</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/the-berry-battle-of-heat-management-mugurisu-4g-with-a-pink-twist-and-the-renowned-thermal-grizzlys-kryonaut/"><u>The Berry Battle of Heat Management: MUGURISU 4G with a Pink Twist and the Renowned Thermal Grizzly's Kryonaut</u></a></li>
<li><a href="https://windows11.techidaily.com/the-secret-of-eradicating-linguistic-line-from-win11-taskbar/"><u>The Secret of Eradicating Linguistic Line From Win11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-shortcut-compendium-windows-narrators-command-guide/"><u>The Ultimate Shortcut Compendium: Windows Narrator's Command Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/top-8-personalization-hacks-for-windows-1011-via-bubbleui/"><u>Top 8 Personalization Hacks for Windows 10/11 via BubbleUI</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-for-proper-thx-surround-sound/"><u>Troubleshooting Windows for Proper THX Surround Sound</u></a></li>
<li><a href="https://windows11.techidaily.com/two-email-systems-together-merging-gmail-and-outlook-in-windows/"><u>Two Email Systems Together: Merging Gmail and Outlook in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-customized-windows-power-schemes/"><u>Unlocking Customized Windows Power Schemes</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-widget-personalization-in-microsofts-latest-os/"><u>Unveiling Widget Personalization in Microsoft's Latest OS</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/what-does-enter-puk-code-mean-and-why-did-the-sim-get-puk-blocked-on-vivo-y36-device-by-drfone-android/"><u>What Does Enter PUK Code Mean And Why Did The Sim Get PUK Blocked On Vivo Y36 Device</u></a></li>
<li><a href="https://windows11.techidaily.com/what-is-winservicesexe-insights-for-windows-users/"><u>What Is WinServices.exe? Insights for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-note-saving-strategies-no-software/"><u>Windows 11 Note-Saving Strategies, No Software</u></a></li>
<li><a href="https://windows11.techidaily.com/wingetui-masterclass-enhancing-windows-11s-application-handling/"><u>WingetUI Masterclass: Enhancing Windows 11'S Application Handling</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>