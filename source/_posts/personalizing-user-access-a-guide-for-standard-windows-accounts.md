---
title: "Personalizing User Access: A Guide for Standard Windows Accounts"
date: 2024-09-09T12:04:13.174Z
updated: 2024-09-10T12:04:13.174Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Personalizing User Access: A Guide for Standard Windows Accounts"
excerpt: "This Article Describes Personalizing User Access: A Guide for Standard Windows Accounts"
keywords: Windows Access Personalization,Standard User Customization,Access Control Windows Guide,Personalize Windows Login,Window's Account Settings,Customizing User Environment,Secure Windows User Profile
thumbnail: https://thmb.techidaily.com/7e377b50c4e513bd18b3a4caf17d4fa401f54e28db3371c8a6654c909a09f9e7.png
---

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2135476/26400" target="_top" id="2135476">
  <img src="//a.impactradius-go.com/display-ad/26400-2135476" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2135476/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Personalizing User Access: A Guide for Standard Windows Accounts

 By default, standard users on Windows can run programs with elevated privileges if they enter an administrator password when prompted by User Access Control (UAC).

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

<!-- affiliate ads begin -->
<span id="1983474">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983474.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983474">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983474.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983474%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983474/22993" style="position:absolute;visibility:hidden;" border="0" />
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
![editing the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/editing-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
4. Click **OK**.
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137207/26400" target="_top" id="2137207">
  <img src="//a.impactradius-go.com/display-ad/26400-2137207" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137207/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Keep in mind that only administrators can change the behavior of the UAC. If a standard user tried to change it using the Local Group Policy Editor, for example, they'd probably get an **Access denied** error message.

## How to Change the UAC Behavior for Standard Users in the Registry Editor

 If you're looking for another way to change UAC behavior for standard users, or the [Local Group Policy is not working](https://www.makeuseof.com/windows-local-group-policy-unresponsive/) on your computer, you can make changes in the Windows registry instead.

 Before you do that, however, we recommend you [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) to protect your computer in case you make a mistake. Once you do that, [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) and follow the steps below:

1. Copy **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System** and paste it into the address bar at the top of the Registry Editor.  
![the System key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/system-key-registry-editor.jpg)
2. Press **Enter** on your keyboard to go to the **System** key.
<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139114/17108" target="_top" id="2139114">
  <img src="//a.impactradius-go.com/display-ad/17108-2139114" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139114/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Right-click the **ConsentPromptBehaviorUser** value in the right panel and select **Modify**.  
![modifying the ConsentPromptBehaviorUser value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-consentpromptbehavioruser-in-registry-editor.jpg)
4. In the **Value data** text box, enter **0** for **Automatically deny elevation requests**, **1** for **Prompt for credentials on the secure desktop**, or **3** for **Prompt for credentials**.  
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137209/26400" target="_top" id="2137209">
  <img src="//a.impactradius-go.com/display-ad/26400-2137209" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137209/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![setting Value data for ConsentPromptbehavior Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/setting-value-data-for-consentpromptbehavior-registry-editor.jpg)
5. Click **OK**.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118314/7443" target="_top" id="2118314">
  <img src="//a.impactradius-go.com/display-ad/7443-2118314" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118314/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now restart your computer to allow the changes to take effect.

## Control UAC's Behavior for Standard Users on Windows

 UAC is an integral part of protecting your Windows computer from malicious programs that want to run with elevated privileges. While you can't make it elevate programs without prompting, you can make it stricter by setting it to **Automatically deny elevation requests**. And, as you can see, it is quite easy to do, whether you're using the Local Group Policy Editor or the Registry Editor.

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://visual-screen-recording.techidaily.com/new-expert-advice-5-proven-methods-to-document-minecraft-on-apple-devices/"><u>[New] Expert Advice 5 Proven Methods to Document Minecraft on Apple Devices</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-step-by-step-voice-customization-in-free-fire-guide-included-no-cost/"><u>[New] Step-by-Step Voice Customization in Free Fire (Guide Included - No Cost)</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-perfecting-instagram-livestreams-with-obs-technology/"><u>[Updated] 2024 Approved Perfecting Instagram Livestreams with OBS Technology</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-precision-recording-a-stepwise-plan-for-pc-ios-macbooks/"><u>[Updated] 2024 Approved Precision Recording A Stepwise Plan for PC, iOS, MacBooks</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-epochs-epic-journey-best-free-mmo-games-roundup/"><u>[Updated] In 2024, Epoch's Epic Journey Best Free MMO Games Roundup</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-keeping-secrets-on-screen-tips-for-private-content-reduction/"><u>[Updated] Keeping Secrets on Screen Tips for Private Content Reduction</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-satire-skills-video-comedy-mastery-tips/"><u>[Updated] Satire Skills Video Comedy Mastery Tips</u></a></li>
<li><a href="https://location-fake.techidaily.com/6-ways-to-change-spotify-location-on-your-oppo-a58-4g-drfone-by-drfone-virtual-android/"><u>6 Ways to Change Spotify Location On Your Oppo A58 4G | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/choose-your-ideal-html-workspace-the-best-free-tools-for-windows-users/"><u>Choose Your Ideal HTML Workspace: The Best Free Tools for Windows Users</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/ditch-windows-10-photos-discover-the-best-photo-editing-alternatives/"><u>Ditch Windows 10 Photos Discover the Best Photo Editing Alternatives</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-to-resolve-powerpoint-print-issues-on-windows-os/"><u>Essential Tips to Resolve PowerPoint Print Issues on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/establishing-kids-internet-freedom-boundaries-on-windows-11/"><u>Establishing Kids' Internet Freedom Boundaries on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tuning-the-size-of-windows-taskbar/"><u>Fine-Tuning the Size of Windows Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-erroneous-dual-camera-access-error-code-a00f4243/"><u>Fixing Erroneous Dual-Camera Access (Error Code: A00F4243)</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-isdonedll-malfunction-a-guide-for-w10w11/"><u>Handling ISDone.dll Malfunction: A Guide for W10/W11</u></a></li>
<li><a href="https://windows11.techidaily.com/harmonizing-your-win-key-with-microsoft-profile-access/"><u>Harmonizing Your WIN Key with Microsoft Profile Access</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-eliminate-call-not-successful-problems-in-windows-malwarebytes/"><u>How to Eliminate Call Not Successful Problems in Windows Malwarebytes</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-rectify-windows-unsuccessful-auto-detect-of-network-proxy/"><u>How to Rectify Windows' Unsuccessful Auto Detect of Network Proxy</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-ensuring-longevity-for-androidmac-snapshots/"><u>In 2024, Ensuring Longevity for Android/Mac Snapshots</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-facebook-dating-for-your-samsung-galaxy-m14-4g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Location On Facebook Dating for your Samsung Galaxy M14 4G | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/in-2024-youtubes-revenue-per-million-views-an-insight/"><u>In 2024, YouTube's Revenue Per Million Views An Insight</u></a></li>
<li><a href="https://windows11.techidaily.com/insights-into-ftdibussys-windows-memory-safeguard-breach/"><u>Insights Into ftdibus.sys: Windows' Memory Safeguard Breach</u></a></li>
<li><a href="https://windows11.techidaily.com/is-windows-subsystem-pivotal-for-linux-desktops/"><u>Is Windows Subsystem Pivotal for Linux Desktops?</u></a></li>
<li><a href="https://windows11.techidaily.com/master-quick-settings-with-ease-on-your-win-11-pc/"><u>Master Quick Settings with Ease on Your Win 11 PC</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-network-access-enabling-telnet-on-win-10-and-11/"><u>Mastering Network Access: Enabling Telnet on Win 10 and 11</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-security-activating-tpm-and-secure-boot-for-windows-11-upgrades/"><u>Maximizing Security: Activating TPM & Secure Boot for Windows 11 Upgrades</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-resuscitate-flaky-slack-notifications/"><u>Methods to Resuscitate Flaky Slack Notifications</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-unexpected-errors-in-windows-security-fixes/"><u>Navigating Unexpected Errors in Windows Security Fixes</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-2024-approved-editing-like-a-pro-tips-and-tricks-for-sony-camcorder-video-editors/"><u>New 2024 Approved Editing Like a Pro Tips and Tricks for Sony Camcorder Video Editors</u></a></li>
<li><a href="https://extra-support.techidaily.com/no1-video-recorders-with-personalized-view-for-2024/"><u>No.1 Video Recorders with Personalized View for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-task-management-on-windows-10-and-11/"><u>Optimize Task Management on Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-your-pcs-auditory-experience-with-updated-drivers-guide/"><u>Optimize Your PC's Auditory Experience with Updated Drivers Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-yellow-screen-distortion-on-laptops/"><u>Overcoming Yellow Screen Distortion on Laptops</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-default-read-only-mode-for-words-email-attachments/"><u>Setting Default Read-Only Mode for Word's Email Attachments</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solved-overcome-microsoft-teams-audio-problems-for-users-of-windows-11-and-10/"><u>Solved! Overcome Microsoft Teams Audio Problems for Users of Windows 11 and 10</u></a></li>
<li><a href="https://windows11.techidaily.com/standby-tech-in-windows-os-a-comprehensive-analysis/"><u>Standby Tech in Windows OS: A Comprehensive Analysis</u></a></li>
<li><a href="https://windows11.techidaily.com/strategic-fixes-to-lower-wlanextexe-consumption/"><u>Strategic Fixes to Lower Wlanext.EXE Consumption</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/streamlining-video-conferences-background-shifts-in-google-meet-for-2024/"><u>Streamlining Video Conferences Background Shifts in Google Meet for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-reversing-fatal-application-crashes/"><u>Techniques for Reversing Fatal Application Crashes</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-windows-defense-plan-7-methods/"><u>The Ultimate Windows Defense Plan (7 Methods)</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-dfs-sudden-shutdown-issue-on-pc/"><u>Troubleshooting DF's Sudden Shutdown Issue on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-update-failure-code-0x8024800c/"><u>Troubleshooting Windows Update Failure: Code 0X8024800C</u></a></li>
<li><a href="https://windows11.techidaily.com/utilizing-the-newly-overhauled-widget-selection-window/"><u>Utilizing the Newly Overhauled Widget Selection Window</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-ispoofer-update-on-oppo-find-x7-drfone-by-drfone-virtual-android/"><u>Will iSpoofer update On Oppo Find X7 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-resetting-how-to-bring-back-microsoft-store-apps/"><u>Win 11 Resetting: How to Bring Back Microsoft Store Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-calmness-dial-down-the-hidden-processes/"><u>Win11 Calmness: Dial Down the Hidden Processes</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-startup-a-quick-route-walkthrough/"><u>Windows Startup: A Quick Route Walkthrough</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>