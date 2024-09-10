---
title: Modify Account Lockout Frequency Post Failed Attempts with Ease, Win 11 Edition
date: 2024-09-09T12:00:21.631Z
updated: 2024-09-10T12:00:21.631Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Modify Account Lockout Frequency Post Failed Attempts with Ease, Win 11 Edition
excerpt: This Article Describes Modify Account Lockout Frequency Post Failed Attempts with Ease, Win 11 Edition
keywords: Account Lockout Control,Easy Unlock Limit Adjustment,Reset Lock Frequency Settings,Windows 11 Security Tweaks,Increase Failed Attempt Tolerance,Modify Unlock Threshold,Easy Account Lockout Adjustment
thumbnail: https://thmb.techidaily.com/200bad50912773155a76642b85b00bc52b52d7ab3430de1df3acbec7a4ce0fd7.jpg
---

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134496/18498" target="_top" id="2134496">
  <img src="//a.impactradius-go.com/display-ad/18498-2134496" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134496/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Modify Account Lockout Frequency Post Failed Attempts with Ease, Win 11 Edition

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098703/14409" target="_top" id="2098703">
  <img src="//a.impactradius-go.com/display-ad/14409-2098703" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098703/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134495/18498" target="_top" id="2134495">
  <img src="//a.impactradius-go.com/display-ad/18498-2134495" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134495/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  
![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134238/18498" target="_top" id="2134238">
  <img src="//a.impactradius-go.com/display-ad/18498-2134238" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134238/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.
<!-- affiliate ads begin -->
<span id="1983539">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983539.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983539">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983539.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983539%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983539/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135397/19272" target="_top" id="2135397">
  <img src="//a.impactradius-go.com/display-ad/19272-2135397" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135397/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-files.techidaily.com/new-clandestine-glimpse-at-fb-flashbacks-for-2024/"><u>[New] Clandestine Glimpse at Fb Flashbacks for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-efficient-group-coordination-with-skype-windows-mac/"><u>[New] Efficient Group Coordination with Skype (Windows, Mac)</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ixed-youtube-shorts-not-showing-up-for-2024/"><u>[New] Fixed YouTube Shorts Not Showing Up for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/aximizing-streaming-is-sub4sub-effective/"><u>[New] Maximizing Streaming Is Sub4Sub Effective?</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-elevate-your-visibility-with-youtube-branding-techniques-for-2024/"><u>[Updated] Elevate Your Visibility with YouTube Branding Techniques for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-scream-loud-with-joy-our-picks-from-the-best-funny-youtubers/"><u>[Updated] In 2024, Scream Loud with Joy Our Picks From the Best Funny YouTubers</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-news-endings-as-a-narrative-tool/"><u>[Updated] News Endings as a Narrative Tool</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-detailed-screencasting-techniques-systematic-approach/"><u>2024 Approved Detailed Screencasting Techniques Systematic Approach</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-restore-lost-airdrop-functionality-with-easy-solutions-for-iosmacos/"><u>2024 Approved Restore Lost Airdrop Functionality with Easy Solutions for iOS/macOS</u></a></li>
<li><a href="https://location-social.techidaily.com/3-things-you-must-know-about-fake-snapchat-location-on-tecno-spark-20-drfone-by-drfone-virtual-android/"><u>3 Things You Must Know about Fake Snapchat Location On Tecno Spark 20 | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/4-ways-to-transfer-music-from-nokia-c300-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>4 Ways to Transfer Music from Nokia C300 to iPhone | Dr.fone</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/easy-installation-get-your-latest-drivers-for-hp-devices-now/"><u>Easy Installation: Get Your Latest Drivers for HP Devices Now!</u></a></li>
<li><a href="https://windows11.techidaily.com/exposing-the-wacatacbml-trojan-your-ultimate-windows-protection-plan/"><u>Exposing the Wacatac.B!ml Trojan - Your Ultimate Windows Protection Plan</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-fresh-updates-for-your-epson-xp-420-printing-device-free-drivers-available/"><u>Get Fresh Updates for Your Epson XP-420 Printing Device – Free Drivers Available!</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-does-the-stardust-trade-cost-in-pokemon-go-on-realme-c67-4g-drfone-by-drfone-virtual-android/"><u>How does the stardust trade cost In pokemon go On Realme C67 4G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-correct-gl-error-3-with-nvidia-on-windows-oses/"><u>How to Correct GL Error 3 with Nvidia on WIndows OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-prevent-auto-restart-events-on-win11/"><u>How to Prevent Auto-Restart Events on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-troubleshoot-high-cpu-usage-with-the-windows-resource-monitor/"><u>How to Troubleshoot High CPU Usage With the Windows Resource Monitor</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-wash-away-your-computers-defender-past/"><u>How to Wash Away Your Computer's Defender Past</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-a-comprehensive-guide-to-mastering-zoom-win10/"><u>In 2024, A Comprehensive Guide to Mastering Zoom (Win10)</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-watch-youtube-green-screen-videos-and-get-your-green-screen-ideas/"><u>In 2024, Watch Youtube Green Screen Videos and Get Your Green Screen Ideas</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-law-filters-in-windows-an-experts-perspective/"><u>Leveraging LAW Filters in Windows – An Expert's Perspective</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-network-configurations-in-windows-os/"><u>Mastering Network Configurations in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-win11s-accessibility-keys/"><u>Mastering Win11's Accessibility Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-non-working-escape-keys-on-your-windows-system/"><u>Navigating Non-Working Escape Keys on Your Windows System</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-maze-of-chrome-profile-disruptions-on-desktop/"><u>Navigating the Maze of Chrome Profile Disruptions on Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-disconnection-issues-of-razer-hardware-in-win-1011/"><u>Overcoming Disconnection Issues of Razer Hardware in Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/precise-control-setup-adjusting-shortcut-locations-on-windows-11s-power-icon/"><u>Precise Control Setup: Adjusting Shortcut Locations on Windows 11'S Power Icon</u></a></li>
<li><a href="https://windows11.techidaily.com/regaining-access-post-failed-windows-login-attempt/"><u>Regaining Access Post Failed Windows Login Attempt</u></a></li>
<li><a href="https://windows11.techidaily.com/regaining-access-fixing-malwarebytes-service-errors-in-windows-1011/"><u>Regaining Access: Fixing Malwarebytes' Service Errors in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-lost-connection-re-list-bluetooth-in-dmi/"><u>Reviving Lost Connection: Re-List Bluetooth in DMI</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-connection-lost-5-easy-steps-for-a-fixed-usb-wi-fi-adapter/"><u>Seamless Connection Lost? 5 Easy Steps for a Fixed USB Wi-Fi Adapter</u></a></li>
<li><a href="https://windows11.techidaily.com/stay-ahead-postpone-windows-edge-tabs-on-w11/"><u>Stay Ahead: Postpone Windows Edge Tabs on W11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-tackle-missing-device-driver-issue-on-windows-startup/"><u>Steps to Tackle Missing Device Driver Issue on Windows Startup</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-cut-down-energy-use-of-wlanextexe/"><u>Strategies to Cut Down Energy Use of Wlanext.EXE</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-non-loading-drivers-in-windows-11/"><u>Troubleshooting Non-Loading Drivers in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-ignoring-local-lsa-warning/"><u>Troubleshooting Windows: Ignoring Local LSA Warning</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/ultimate-tutorial-setting-up-call-diversion-for-all-phones-explained/"><u>Ultimate Tutorial: Setting up Call Diversion for All Phones Explained</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>