---
title: "Optimizing Security: Adjusting Lockout Count After Failed Attempts"
date: 2024-09-09T12:05:59.537Z
updated: 2024-09-10T12:05:59.537Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Optimizing Security: Adjusting Lockout Count After Failed Attempts"
excerpt: "This Article Describes Optimizing Security: Adjusting Lockout Count After Failed Attempts"
keywords: Cybersecurity Optimization,Account Lockout Limits,Secure Access Control,Failed Login Management,Intrusion Prevention Tactics,Password Reset Strategy,Attack Deterrence Policies
thumbnail: https://thmb.techidaily.com/f15d1bc826d6244cad0ae98fe7b4565620a90c9525864662d718cce49121a5e7.jpg
---

## Optimizing Security: Adjusting Lockout Count After Failed Attempts

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  
<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014848/22899" target="_top" id="2014848">
  <img src="//a.impactradius-go.com/display-ad/22899-2014848" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014848/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  
![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115930/19272" target="_top" id="2115930">
  <img src="//a.impactradius-go.com/display-ad/19272-2115930" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115930/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136612/26400" target="_top" id="2136612">
  <img src="//a.impactradius-go.com/display-ad/26400-2136612" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136612/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.
<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123480/16836" target="_top" id="2123480">
  <img src="//a.impactradius-go.com/display-ad/16836-2123480" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123480/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137209/26400" target="_top" id="2137209">
  <img src="//a.impactradius-go.com/display-ad/26400-2137209" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137209/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<span id="1982459">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982459.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982459">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982459.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982459%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982459/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-bridging-social-media-posting-tweets-on-fb/"><u>[New] 2024 Approved Bridging Social Media Posting Tweets on FB</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-the-art-of-concluding-videos-crafting-impactful-vimeo-ends/"><u>[New] 2024 Approved The Art of Concluding Videos Crafting Impactful Vimeo Ends</u></a></li>
<li><a href="https://youtube-data.techidaily.com/o-youtubers-get-paid-monthly-for-2024/"><u>[New] Do YouTubers Get Paid Monthly for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/n-2024-halt-autoplay-youtube-recommendations/"><u>[New] In 2024, Halt Autoplay YouTube Recommendations</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-share-your-picture-posting-to-youtube-basics/"><u>[New] Share Your Picture Posting to YouTube Basics</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-stream-like-never-before-turning-on-youtubes-av1/"><u>[New] Stream Like Never Before Turning On YouTube's AV1</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-which-streaming-application-leads-the-race-wirecast-or-obs/"><u>[New] Which Streaming Application Leads the Race, Wirecast or OBS?</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-making-magic-mobile-best-phones-for-media-crafting/"><u>[Updated] Making Magic Mobile Best Phones for Media Crafting</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-restoring-missing-sounds-in-obs-recordings/"><u>[Updated] Restoring Missing Sounds in OBS Recordings</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-stepwise-unveiling-effect/"><u>2024 Approved Stepwise Unveiling Effect</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-the-complete-kinemaster-blueprint-for-flawless-green-screen-techniques/"><u>2024 Approved The Complete Kinemaster Blueprint for Flawless Green Screen Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-inaccessible-folders-in-windows-outlook-a-comprerani-guide/"><u>Fixing Inaccessible Folders in Windows Outlook: A Comprerani Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-adjust-inaccurate-task-manager-cpu-indicators/"><u>Guide to Adjust Inaccurate Task Manager CPU Indicators</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-to-rectify-window-11s-non-responsive-menu-bar/"><u>Guidelines to Rectify Window 11'S Non-Responsive Menu Bar</u></a></li>
<li><a href="https://win-dash.techidaily.com/hassle-free-guide-download-and-configure-new-amd-graphics-drivers-instantly/"><u>Hassle-Free Guide: Download & Configure New AMD Graphics Drivers Instantly</u></a></li>
<li><a href="https://fox-that.techidaily.com/1721467132142-how-to-find-an-iphone-app-thats-gone-missing-easy-steps-inside/"><u>How to Find an iPhone App That's Gone Missing - Easy Steps Inside</u></a></li>
<li><a href="https://techidaily.com/how-to-free-up-apple-iphone-12-space-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>How To Free Up Apple iPhone 12 Space | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-turn-off-google-location-to-stop-tracking-you-on-oppo-reno-8t-5g-drfone-by-drfone-virtual-android/"><u>How to Turn Off Google Location to Stop Tracking You on Oppo Reno 8T 5G | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-use-google-assistant-on-your-lock-screen-of-honor-magic-6-pro-phone-by-drfone-android/"><u>How to Use Google Assistant on Your Lock Screen Of Honor Magic 6 Pro Phone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-best-free-iphone-14-pro-max-imei-checker-by-drfone-ios/"><u>In 2024, Best Free iPhone 14 Pro Max IMEI Checker</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-streamline-document-creation-with-microsoft-word-speech-recognition/"><u>In 2024, Streamline Document Creation with Microsoft Word Speech Recognition</u></a></li>
<li><a href="https://buynow-help.techidaily.com/in-depth-look-at-googles-pixelbook-go-top-notch-chrome-experience-for-a-hefty-price-tag/"><u>In-Depth Look at Google's Pixelbook Go: Top-Notch Chrome Experience for a Hefty Price Tag</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-app-packages-with-winget-on-win11-tips-and-tricks/"><u>Mastering App Packages with Winget on Win11 - Tips and Tricks</u></a></li>
<li><a href="https://fox-http.techidaily.com/mastering-flight-control-best-motor-selections-unveiled-for-2024/"><u>Mastering Flight Control Best Motor Selections Unveiled for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-web-control-panel-adjustments-in-windows-11/"><u>Mastering Web Control Panel Adjustments in Windows 11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/maximizing-productivity-with-three-monitors-a-user-friendly-guide-for-multi-display-pc-setup/"><u>Maximizing Productivity with Three Monitors: A User-Friendly Guide for Multi-Display PC Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-intricacies-of-w11s-auto-hdr/"><u>Navigating the Intricacies of W11's Auto HDR</u></a></li>
<li><a href="https://windows11.techidaily.com/navigational-aid-for-windows-component-services-utility/"><u>Navigational Aid for Windows' Component Services Utility</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-0x800700e1-in-win10-and-11-pcs/"><u>Overcoming 0X800700E1 in Win10 & 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-excessive-cpu-activity-a-solution-guide/"><u>Overcoming Excessive CPU Activity: A Solution Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-failed-rpc-calls-a-windows-focused-guide/"><u>Overcoming Failed RPC Calls: A Windows-Focused Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/pinpoint-win-logins-the-differentiator-between-right-and-wrong-entries/"><u>Pinpoint Win Logins: The Differentiator Between Right & Wrong Entries</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-solutions-to-csgo-opens-issue-w11/"><u>Quick Solutions to CS:GO Opens Issue W11</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-tips-how-to-overcome-restricted-file-viewers-in-windows/"><u>Quick Tips: How to Overcome Restricted File Viewers in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/redefine-restoring-windows-11-explorer-view-order/"><u>Redefine: Restoring Windows 11 Explorer View Order</u></a></li>
<li><a href="https://windows11.techidaily.com/revisiting-the-classics-uncovering-7-older-windows-functionalities-in-11/"><u>Revisiting the Classics: Uncovering 7 Older Windows Functionalities in 11</u></a></li>
<li><a href="https://windows11.techidaily.com/sound-expertise-for-beginners-in-microsofts-new-os/"><u>Sound Expertise for Beginners in Microsoft's New OS</u></a></li>
<li><a href="https://extra-information.techidaily.com/step-by-step-guide-to-iphones-dynamic-images/"><u>Step-by-Step Guide to iPhone's Dynamic Images</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-overcome-msstore-error-0x00000000-in-windows-10/"><u>Steps to Overcome MsStore Error 0X00000000 in Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlined-windows-11-upsize-an-in-place-methodology-overview/"><u>Streamlined Windows 11 Upsize: An In-Place Methodology Overview</u></a></li>
<li><a href="https://windows11.techidaily.com/swiftly-adapt-windows-settings-via-hotkey-techniques/"><u>Swiftly Adapt Windows Settings via Hotkey Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-negate-erroneous-security-alarms-from-chrome-web-app/"><u>Techniques to Negate Erroneous Security Alarms From Chrome Web App</u></a></li>
<li><a href="https://windows11.techidaily.com/the-complete-process-for-adding-widgets-on-windows-11/"><u>The Complete Process for Adding Widgets on Windows 11</u></a></li>
<li><a href="https://discover-cloud.techidaily.com/the-ultimate-guide-to-quick-and-secure-video-conversion-tools-on-windows-1110/"><u>The Ultimate Guide to Quick and Secure Video Conversion Tools on Windows 11/10</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/three-ways-to-sim-unlock-xiaomi-redmi-note-12-pro-4g-by-drfone-android/"><u>Three Ways to Sim Unlock Xiaomi Redmi Note 12 Pro 4G</u></a></li>
<li><a href="https://windows11.techidaily.com/top-techniques-for-maximizing-windows-11-features/"><u>Top Techniques for Maximizing Windows 11 Features</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-and-personalize-your-pc-with-alomwares-mastery/"><u>Transform and Personalize Your PC With AlomWare's Mastery</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-chrome-blackout-on-pcs/"><u>Troubleshooting Chrome Blackout on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-memory-feature-disabled-in-win11/"><u>Troubleshooting Memory Feature Disabled in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-non-operational-event-viewer/"><u>Troubleshooting Non-Operational Event Viewer</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-the-resistance-to-windows-11s-latest-release/"><u>Understanding the Resistance to Windows 11'S Latest Release</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-silent-keys-troubleshooting-tactics-for-windows-pcs/"><u>Unlock Silent Keys: Troubleshooting Tactics for Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/whats-next-after-0x800f0845-error/"><u>What's Next After 0X800f0845 Error?</u></a></li>
<li><a href="https://win11.techidaily.com/win11s-comprehensive-navshortcut-compendium/"><u>Win11's Comprehensive NavShortcut Compendium</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-mastery-constructing-clutter-free-directories/"><u>Windows 11 Mastery: Constructing Clutter-Free Directories</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>