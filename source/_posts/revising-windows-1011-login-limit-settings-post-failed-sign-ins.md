---
title: Revising Windows 10/11 Login Limit Settings Post-Failed Sign-Ins
date: 2024-09-05T02:17:01.171Z
updated: 2024-09-06T02:17:01.171Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Revising Windows 10/11 Login Limit Settings Post-Failed Sign-Ins
excerpt: This Article Describes Revising Windows 10/11 Login Limit Settings Post-Failed Sign-Ins
keywords: Win10LoginLimits,Win10PostFailsignin,Win11LimitSettings,FailedSignInWindows,LimitLoginRevising,WindowsResetPasswords,SigninFailureOptions
thumbnail: https://thmb.techidaily.com/9778babca71d8c322c58ebdc5b0f6b1ae6df8f808a7e29b4ee7032e1868f5ab0.jpg
---

## Revising Windows 10/11 Login Limit Settings Post-Failed Sign-Ins

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  
![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  
![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.
4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<span id="1793213">
					<video width="864" height="1296" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1793213.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19135-1793213">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1793213.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftinyland.pxf.io%2Fc%2F5597632%2F1793213%2F19135'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793213/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vimeo-videos.techidaily.com/new-from-live-streaming-to-lively-gifs-harnessing-vimeo-content-for-2024/"><u>[New] From Live Streaming to Lively Gifs  Harnessing Vimeo Content for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-how-to-archive-your-minecraft-sessions-on-a-mac-computer-for-2024/"><u>[New] How to Archive Your Minecraft Sessions on a Mac Computer for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-cutting-edge-videotelephony-solutions-list/"><u>[Updated] In 2024, Cutting-Edge Videotelephony Solutions List</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-making-your-stories-more-accessible-a-captioning-guide/"><u>[Updated] In 2024, Making Your Stories More Accessible  A Captioning Guide</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-the-path-to-retrospective-facebook-content-mobile-plus-laptop-for-2024/"><u>[Updated] The Path to Retrospective Facebook Content (Mobile + Laptop) for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-steps-to-alter-windows-msi-service-status/"><u>Essential Steps to Alter Windows MSI Service Status</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-techniques-to-resurrect-an-unopenable-notepad-on-pc/"><u>Essential Techniques to Resurrect an Unopenable Notepad on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-grayed-out-extend-button-revive-it-for-discmgmt/"><u>Fix Grayed-Out Extend Button, Revive It for DiscMgmt</u></a></li>
<li><a href="https://windows11.techidaily.com/harnessing-bluescreenview-a-users-handbook/"><u>Harnessing BlueScreenView: A User's Handbook</u></a></li>
<li><a href="https://extra-resources.techidaily.com/heard-words-spoken-ideas-no-price/"><u>Heard Words, Spoken Ideas – No Price</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-keep-onedrive-available-offline-in-windows/"><u>How To Keep OneDrive Available Offline in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-run-an-unrestricted-chatgpt-alternative-on-windows-with-freedomgpt/"><u>How to Run an Unrestricted ChatGPT Alternative on Windows With FreedomGPT</u></a></li>
<li><a href="https://windows11.techidaily.com/identifying-perfect-shutdown-procedures-for-windows/"><u>Identifying Perfect Shutdown Procedures for Windows</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-access-your-iphone-xs-when-you-forget-the-passcode-by-drfone-ios/"><u>In 2024, How to Access Your iPhone XS When You Forget the Passcode?</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-pro-tips-for-effective-use-of-supplemental-film-sequences-b-roll/"><u>In 2024, Pro Tips for Effective Use of Supplemental Film Sequences (B-Roll)</u></a></li>
<li><a href="https://windows11.techidaily.com/innovative-design-techniques-for-customizing-windows-outlook-calendars/"><u>Innovative Design Techniques for Customizing Windows Outlook Calendars</u></a></li>
<li><a href="https://windows11.techidaily.com/integrating-custom-widgets-into-the-windows-11-interface/"><u>Integrating Custom Widgets Into the Windows 11 Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/leverage-efficiency-with-terminal-as-preferred-cli/"><u>Leverage Efficiency with Terminal as Preferred CLI</u></a></li>
<li><a href="https://windows11.techidaily.com/maintain-disk-space-utilize-automatic-deletion-in-windows-11/"><u>Maintain Disk Space: Utilize Automatic Deletion in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-copying-custom-powertoys-configurations/"><u>Mastering the Art of Copying Custom PowerToys Configurations</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/maximize-gaming-together-the-ultimate-guide-to-sharing-titles-with-friends-on-xbox-one/"><u>Maximize Gaming Together: The Ultimate Guide to Sharing Titles with Friends on Xbox One</u></a></li>
<li><a href="https://windows11.techidaily.com/migrating-your-qbittorrent-setup-seamlessly-across-pcs/"><u>Migrating Your qBittorrent Setup Seamlessly Across PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/mystery-non-edge-processes-in-task-manager/"><u>Mystery: Non-Edge Processes in Task Manager?</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-to-index-settings-on-windows/"><u>Navigate to Index Settings on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-for-swifter-loading-of-apps-from-microsoft-store/"><u>Navigating for Swifter Loading of Apps From Microsoft Store</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-the-maze-of-0x80860010-application-overload/"><u>Navigating Through the Maze of 0X80860010 Application Overload</u></a></li>
<li><a href="https://windows11.techidaily.com/overcome-sign-in-obstacles-to-microsofts-cloud-storage/"><u>Overcome Sign-In Obstacles to Microsoft's Cloud Storage</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-overcoming-windows-error-code-xffffff/"><u>Quick Guide: Overcoming Windows Error Code XFFFFFF</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-remedy-for-screens-that-tick-in-windows-11/"><u>Quick Remedy for Screens that Tick in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/reinvigorating-your-pc-delving-into-windows-8-revival-techniques/"><u>Reinvigorating Your PC: Delving Into Windows' 8 Revival Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-stalled-grammarly-checkup-in-windows-810/"><u>Reviving Stalled Grammarly Checkup in Windows 8/10</u></a></li>
<li><a href="https://windows11.techidaily.com/sifting-through-windows-logins-the-good-the-bad-and-the-ugly/"><u>Sifting Through Windows Logins: The Good, The Bad & The Ugly</u></a></li>
<li><a href="https://windows11.techidaily.com/speedy-data-retrieval-on-pc-embracing-everythingapp/"><u>Speedy Data Retrieval on PC: Embracing EverythingApp</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-non-functional-google-nearby-share-window/"><u>Steps to Resolve Non-Functional Google Nearby Share Window</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-erasing-windows-11s-task-view/"><u>The Art of Erasing Windows 11'S Task View</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-guide-to-windows-pe-file-structure/"><u>The Essential Guide to Windows PE File Structure</u></a></li>
<li><a href="https://windows11.techidaily.com/the-journey-to-disabling-user-account-control-uac-in-windows-11/"><u>The Journey to Disabling User Account Control (UAC) in WIndows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-bypassing-cannot-end-task-error-in-windows/"><u>Tips for Bypassing 'Cannot End Task Error' In Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-on-preventing-windows-notepad-hangouts/"><u>Tips on Preventing Windows Notepad Hangouts</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-code-0xa00f4289-in-windows-webcam-errors/"><u>Troubleshooting Code 0xA00F4289 in Windows Webcam Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-stuck-chrome-on-win11-easy-methods-here/"><u>Troubleshooting Stuck Chrome on Win11 – Easy Methods Here</u></a></li>
<li><a href="https://windows11.techidaily.com/unclog-your-windows-11-mailcalendar-access/"><u>Unclog Your Windows 11 Mail/Calendar Access</u></a></li>
<li><a href="https://windows11.techidaily.com/unseen-users-missed-links-how-to-open-elusive-sites-on-windows/"><u>Unseen Users, Missed Links: How to Open Elusive Sites on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unseen-workers-taskers-edge-anomalies/"><u>Unseen Workers: Tasker’s Edge Anomalies</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-kinemaster-for-mac-a-step-by-step-installation-guide/"><u>Updated 2024 Approved KineMaster for Mac A Step-by-Step Installation Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-arp-caching-explained-and-tips-for-clears/"><u>Windows ARP Caching Explained & Tips for Clears</u></a></li>
<li><a href="https://windows11.techidaily.com/winerror-unraveled-expert-advice-on-fixing-windows-scripts/"><u>WinError Unraveled: Expert Advice on Fixing Windows Scripts</u></a></li>
<li><a href="https://windows11.techidaily.com/wsl-enabling-linux-on-windows-rise/"><u>WSL Enabling: Linux on Windows Rise</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>