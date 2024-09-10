---
title: Redefining Privileges for Non-Administrative Windows Users
date: 2024-09-09T12:14:45.154Z
updated: 2024-09-10T12:14:45.154Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Redefining Privileges for Non-Administrative Windows Users
excerpt: This Article Describes Redefining Privileges for Non-Administrative Windows Users
keywords: Admin Access Deficit,Non-Admin Rights,User Privilege Redesign,Non-Windows Admin Limitations,Privileges for Regular Users,Windows Usage Without Admin,Reimagining User Privileges
thumbnail: https://thmb.techidaily.com/97bc8f701c5a50640871957d35ec4f8e16308c84bcc3926e5048675a7dfb62d5.png
---

## Redefining Privileges for Non-Administrative Windows Users

 By default, standard users on Windows can run programs with elevated privileges if they enter an administrator password when prompted by User Access Control (UAC).

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

<!-- affiliate ads begin -->
<span id="1304647">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1304647.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1304647">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1304647.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1304647%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1304647/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## The UAC Behaviors Available for Standard User Accounts

 Unlike when [changing UAC behaviors for administrator accounts](https://www.makeuseof.com/change-user-access-control-works-administrators-windows/), the behaviors for standard user accounts are a little more limited. According to the [Microsoft Learn](https://learn.microsoft.com/en-us/windows/security/threat-protection/security-policy-settings/user-account-control-behavior-of-the-elevation-prompt-for-standard-users) website, here are the behaviors you can choose and what they mean:

* **Automatically deny elevation requests**: This option returns an **Access denied** error message to standard users when they try to perform an operation that requires elevation of privilege. Most organizations that run desktops as standard users configure this policy to reduce help desk calls.
* **Prompt for credentials on the secure desktop**: When an operation requires elevation of privilege, the user is prompted on the secure desktop to enter a different username and password. If the user enters valid credentials, the operation continues with the applicable privilege.
* **Prompt for credentials**: An operation that requires elevation of privilege prompts the user to type an administrative username and password. If the user enters valid credentials, the operation continues with the applicable privilege.

 The default UAC behavior for standard user accounts is **Prompt for credentials**, but Microsoft recommends you change it to **Automatically deny elevation requests**. That way, only users with administrator accounts can decide how the UAC behaves and make choices that will keep the computer safe.

## How to Change the UAC Behavior for Standard Users in the Local Group Policy Editor

 The easiest way to change the way UAC behaves for standard users is to tweak the **User Account Control: Behavior of the elevation prompt for standard users** policy. To do that, [open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and follow the steps below.

 The Local Group Policy Editor isn't available by default on Windows Home. As such, check out [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Head to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options**.
2. Right-click the **User Account Control: Behavior of the elevation prompt for standard users** policy and select **Properties** in the menu.  
![modifying the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
3. Expand the dropdown and choose a different UAC behavior.  
<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014857/22899" target="_top" id="2014857">
  <img src="//a.impactradius-go.com/display-ad/22899-2014857" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014857/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![editing the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/editing-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
4. Click **OK**.

 Keep in mind that only administrators can change the behavior of the UAC. If a standard user tried to change it using the Local Group Policy Editor, for example, they'd probably get an **Access denied** error message.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123740/7443" target="_top" id="2123740">
  <img src="//a.impactradius-go.com/display-ad/7443-2123740" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123740/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Change the UAC Behavior for Standard Users in the Registry Editor

 If you're looking for another way to change UAC behavior for standard users, or the [Local Group Policy is not working](https://www.makeuseof.com/windows-local-group-policy-unresponsive/) on your computer, you can make changes in the Windows registry instead.

 Before you do that, however, we recommend you [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) to protect your computer in case you make a mistake. Once you do that, [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) and follow the steps below:

1. Copy **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System** and paste it into the address bar at the top of the Registry Editor.  
![the System key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/system-key-registry-editor.jpg)
2. Press **Enter** on your keyboard to go to the **System** key.
<!-- affiliate ads begin -->
<span id="1983472">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983472.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983472">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983472.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983472%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983472/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Right-click the **ConsentPromptBehaviorUser** value in the right panel and select **Modify**.  
![modifying the ConsentPromptBehaviorUser value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-consentpromptbehavioruser-in-registry-editor.jpg)
4. In the **Value data** text box, enter **0** for **Automatically deny elevation requests**, **1** for **Prompt for credentials on the secure desktop**, or **3** for **Prompt for credentials**.  
<!-- affiliate ads begin -->
<span id="1743243">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1743243.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19272-1743243">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1743243.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Faligracehair.sjv.io%2Fc%2F5597632%2F1743243%2F19272'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1743243/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![setting Value data for ConsentPromptbehavior Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/setting-value-data-for-consentpromptbehavior-registry-editor.jpg)
5. Click **OK**.

 Now restart your computer to allow the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2121334/18498" target="_top" id="2121334">
  <img src="//a.impactradius-go.com/display-ad/18498-2121334" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2121334/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Control UAC's Behavior for Standard Users on Windows

 UAC is an integral part of protecting your Windows computer from malicious programs that want to run with elevated privileges. While you can't make it elevate programs without prompting, you can make it stricter by setting it to **Automatically deny elevation requests**. And, as you can see, it is quite easy to do, whether you're using the Local Group Policy Editor or the Registry Editor.

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-knowledge.techidaily.com/new-2024-approved-fresh-conversation-starters-keeping-listeners-hooked/"><u>[New] 2024 Approved Fresh Conversation Starters Keeping Listeners Hooked</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/024-approved-optimizing-content-visibility-premier-tracking-applications-for-youtubers/"><u>[New] 2024 Approved Optimizing Content Visibility - Premier Tracking Applications for YouTubers</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-how-to-blur-background-in-zoom-with-ease-an-ultimate-guide/"><u>[New] How to Blur Background in Zoom with Ease An Ultimate Guide</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-reigning-tiktoks-on-twitter-a-viral-analysis-for-2024/"><u>[New] Reigning TikToks on Twitter A Viral Analysis for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-merge-moments-seamlessly-from-tiktok-to-facebook-for-2024/"><u>[Updated] Merge Moments Seamlessly From TikTok, To Facebook for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-proven-strategies-for-creating-superb-igtv-videos-on-smartphonesdlsrs/"><u>2024 Approved Proven Strategies for Creating Superb IGTV Videos on Smartphones/DLSRs</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/2024-approved-youtube-caption-implementation-essentials/"><u>2024 Approved YouTube Caption Implementation Essentials</u></a></li>
<li><a href="https://howto.techidaily.com/8-ultimate-fixes-for-google-play-your-samsung-galaxy-a05s-isnt-compatible-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Ultimate Fixes for Google Play Your Samsung Galaxy A05s Isnt Compatible | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/beat-the-hate-smoothly-add-tracks-into-your-video-on-windows-11-for-2024/"><u>Beat the Hate Smoothly Add Tracks Into Your Video on Windows 11 for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/effective-approaches-to-capturing-high-def-live-games/"><u>Effective Approaches to Capturing High-Def Live Games</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/embark-on-language-journey-with-googles-top-picks-mondly/"><u>Embark on Language Journey with Google's Top Picks - Mondly</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-to-resolve-powerpoint-print-issues-on-windows-os/"><u>Essential Tips to Resolve PowerPoint Print Issues on Windows OS</u></a></li>
<li><a href="https://fox-http.techidaily.com/exploring-the-depth-of-editing-with-gopro-studios-capabilities-for-2024/"><u>Exploring the Depth of Editing with GoPro Studio's Capabilities for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-erroneous-dual-camera-access-error-code-a00f4243/"><u>Fixing Erroneous Dual-Camera Access (Error Code: A00F4243)</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-utorrent-non-installation-on-pcs-running-windows-os/"><u>Fixing uTorrent Non-Installation on PCs Running Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-isdonedll-malfunction-a-guide-for-w10w11/"><u>Handling ISDone.dll Malfunction: A Guide for W10/W11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-eliminate-call-not-successful-problems-in-windows-malwarebytes/"><u>How to Eliminate Call Not Successful Problems in Windows Malwarebytes</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-merge-folders-and-files-in-windows-11-and-11/"><u>How to Merge Folders and Files in Windows 11 and 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-merge-windows-id-with-microsoft-profile/"><u>How to Merge Windows ID with Microsoft Profile</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-modify-microsoft-admin-for-windows-11-networks/"><u>How to Modify Microsoft Admin for Windows 11 Networks</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-rectify-windows-unsuccessful-auto-detect-of-network-proxy/"><u>How to Rectify Windows' Unsuccessful Auto Detect of Network Proxy</u></a></li>
<li><a href="https://tech-revival.techidaily.com/imposter-extension-snatches-fb-login-data/"><u>Imposter Extension: Snatches FB Login Data</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-ways-to-track-motorola-moto-e13-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Track Motorola Moto E13 without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-does-find-my-friends-work-on-nokia-c12-drfone-by-drfone-virtual-android/"><u>In 2024, Does find my friends work on Nokia C12 | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-can-i-catch-the-regional-pokemon-without-traveling-on-motorola-moto-g24-drfone-by-drfone-virtual-android/"><u>In 2024, How Can I Catch the Regional Pokémon without Traveling On Motorola Moto G24 | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-do-you-get-sun-stone-evolutions-in-pokemon-for-oneplus-ace-2v-drfone-by-drfone-virtual-android/"><u>In 2024, How Do You Get Sun Stone Evolutions in Pokémon For OnePlus Ace 2V? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-detect-and-stop-mspy-from-spying-on-your-oppo-a2-drfone-by-drfone-virtual-android/"><u>In 2024, How to Detect and Stop mSpy from Spying on Your Oppo A2 | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-is-youtubes-4-second-trick-effective/"><u>In 2024, Is YouTube's 4-Second Trick Effective?</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-pokemon-go-no-gps-signal-heres-every-possible-solution-on-honor-90-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Pokemon Go No GPS Signal? Heres Every Possible Solution On Honor 90 Pro | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-process-of-screen-sharing-motorola-moto-g24-to-pc-detailed-steps-drfone-by-drfone-android/"><u>In 2024, Process of Screen Sharing Motorola Moto G24 to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-syncing-audio-visual-elements-modern-approaches-to-creating-unified-media-experiences/"><u>In 2024, Syncing Audio-Visual Elements Modern Approaches to Creating Unified Media Experiences</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-vanguard-enterprises-of-spatial-display-tech/"><u>In 2024, Vanguard Enterprises of Spatial Display Tech</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-fast-startup-in-windows-11-installation/"><u>Mastering Fast Startup in Windows 11 Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-mouse-gestures-on-windows-11s-microsoft-edge/"><u>Mastering Mouse Gestures on Windows 11'S Microsoft Edge</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11s-character-display-tool/"><u>Mastering Windows 11'S Character Display Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-your-network-the-windows-iscsi-initiator-explained/"><u>Mastering Your Network: The Windows iSCSI Initiator Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-resuscitate-flaky-slack-notifications/"><u>Methods to Resuscitate Flaky Slack Notifications</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-back-to-default-windows-preferences/"><u>Navigating Back to Default Windows Preferences</u></a></li>
<li><a href="https://tech-revival.techidaily.com/1722108678886-navigating-legal-landscapes-the-advantages-and-disadvantages-of-hiring-a-local-lawyer-with-llm/"><u>Navigating Legal Landscapes: The Advantages & Disadvantages of Hiring a Local Lawyer with LL.M.</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/non-twitter-video-tweeting-hacks-for-the-modern-user/"><u>Non-Twitter Video Tweeting Hacks for the Modern User</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-yellow-screen-distortion-on-laptops/"><u>Overcoming Yellow Screen Distortion on Laptops</u></a></li>
<li><a href="https://windows11.techidaily.com/perfect-light-settings-on-windows-screens-with-best-brightools/"><u>Perfect Light Settings on Windows Screens with Best BrighTools</u></a></li>
<li><a href="https://windows11.techidaily.com/refine-your-mouses-click-speed-three-simple-adjustments/"><u>Refine Your Mouse's Click Speed: Three Simple Adjustments</u></a></li>
<li><a href="https://windows11.techidaily.com/resize-images-in-win11-a-step-by-step/"><u>Resize Images in Win11: A Step-by-Step</u></a></li>
<li><a href="https://extra-tips.techidaily.com/sensory-overload-vr-transforming-viewing-habits/"><u>Sensory Overload VR Transforming Viewing Habits</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-up-a-safe-workspace-windows-sandbox-11/"><u>Setting Up a Safe Workspace: Windows Sandbox 11</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/sonys-nw-ws623-critical-eye-on-style-choices/"><u>Sony's NW-WS623: Critical Eye on Style Choices</u></a></li>
<li><a href="https://windows11.techidaily.com/standby-tech-in-windows-os-a-comprehensive-analysis/"><u>Standby Tech in Windows OS: A Comprehensive Analysis</u></a></li>
<li><a href="https://windows11.techidaily.com/strategic-fixes-to-lower-wlanextexe-consumption/"><u>Strategic Fixes to Lower Wlanext.EXE Consumption</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-reversing-fatal-application-crashes/"><u>Techniques for Reversing Fatal Application Crashes</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-complete-handbook-detailed-techniques-to-refresh-your-gaming-keyboard/"><u>The Complete Handbook: Detailed Techniques to Refresh Your Gaming Keyboard</u></a></li>
<li><a href="https://windows11.techidaily.com/the-perfect-font-theme-match-for-your-notepad/"><u>The Perfect Font, Theme Match for Your Notepad</u></a></li>
<li><a href="https://sound-issues.techidaily.com/trouble-with-in-game-communication-heres-what-to-do-when-your-csgo-mic-fails/"><u>Trouble with In-Game Communication? Here's What to Do When Your CS:GO Mic Fails</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-printer-errors-another-computer/"><u>Troubleshooting Printer Errors: Another Computer?</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-update-failure-code-0x8024800c/"><u>Troubleshooting Windows Update Failure: Code 0X8024800C</u></a></li>
<li><a href="https://windows11.techidaily.com/turbo-valorant-setup-escape-the-01kbs-download-drought/"><u>Turbo Valorant Setup: Escape the 0.1KB/S Download Drought</u></a></li>
<li><a href="https://windows11.techidaily.com/tutorial-initiating-clipboard-operations-within-microsoft-edges-protected-environment-windows-11/"><u>Tutorial: Initiating Clipboard Operations Within Microsoft Edge's Protected Environment, Windows 11</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/unleash-a-flood-of-supporters-attain-a-million-ish-on-ig-each-month/"><u>Unleash a Flood of Supporters Attain a Million-Ish on IG Each Month</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-of-error-code-80080300-with-microsoft-teams/"><u>Unraveling the Mystery of Error Code 80080300 with Microsoft Teams</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-future-of-shopping-microsoft-ai-hub/"><u>Unveiling the Future of Shopping: Microsoft AI Hub</u></a></li>
<li><a href="https://windows11.techidaily.com/utilizing-the-newly-overhauled-widget-selection-window/"><u>Utilizing the Newly Overhauled Widget Selection Window</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-keyboard-graphic-helper/"><u>Windows 11'S Keyboard Graphic Helper</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-startup-a-quick-route-walkthrough/"><u>Windows Startup: A Quick Route Walkthrough</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-against-apexs-hurdles-in-windows-11-crashes/"><u>Winning Against Apex's Hurdles in Windows 11 Crashes</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>