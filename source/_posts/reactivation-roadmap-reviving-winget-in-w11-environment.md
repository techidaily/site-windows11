---
title: "Reactivation Roadmap: Reviving Winget in W11 Environment"
date: 2024-09-09T12:05:51.548Z
updated: 2024-09-10T12:05:51.548Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Reactivation Roadmap: Reviving Winget in W11 Environment"
excerpt: "This Article Describes Reactivation Roadmap: Reviving Winget in W11 Environment"
keywords: W11 Winget Revival Guide,Winget Update Pathway,W11 Reactivate Winget,Winget Enhancement Roadmap,Reinstating Winget in W11,Restoring Winget Protocol,Winget Recovery Strategy
thumbnail: https://thmb.techidaily.com/235c9a836def3af64d14d9406f5da36fac525d1a6b5286ab03fa2d909747fb1b.jpg
---

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123475/16836" target="_top" id="2123475">
  <img src="//a.impactradius-go.com/display-ad/16836-2123475" border="0" alt="https://techidaily.com" width="300" height="75"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123475/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Reactivation Roadmap: Reviving Winget in W11 Environment

 Winget is a command-line tool that can download and install app packages from MS Store and the apps listed in its repository. It saves a lot of time that would be otherwise wasted in searching the Microsoft Store or the web for a particular app, downloading it, and then manually installing it.

 But some users report that Winget is not working on their PC. They face a "The system cannot execute the specified program" and cannot run any commands, This post will discuss multiple methods to resolve the issue and restore Winget to its working state. Let’s begin.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2136545/16384" target="_top" id="2136545">
  <img src="//a.impactradius-go.com/display-ad/16384-2136545" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ursime.pxf.io/i/5597632/2136545/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Reasons Why Winget Stops Working on Windows

 Here are the following reasons why Winget is not working on your Windows PC:

1. You are running an outdated version of the App Installer.
2. Winget servers are down, or you don’t have an active internet connection.
3. The app execution alias is not configured or inactive for Winget.
4. App Installer failed to add the PATH environment variable automatically while installing.

 Now, you know the reasons behind Winget not working issue. Try out these eight methods to resolve the issue and use your favorite package manager again.

## 1\. Close and Reopen Winget in the Terminal App

 Before moving on to advanced fixes, completely close the Command Prompt or PowerShell instance you are running on the PC. You can use the Task Manager to stop an unresponsive instance of either of these command-line tools.

 After that, open Command Prompt or PowerShell with administrator privileges on your system. Type Winget and press the **Enter** key to check if Winget works now.

## 2\. Check if the Winget Servers Are Down

 Winget is an online tool that needs a robust internet connection to search for a package in various repositories and then download and install them. If the Winget servers are down or inactive, it won’t be able to fetch results from repositories. So, check if Winget servers are down using [DownDetector](https://redirect.viglink.com/?format=go&jsonp=vglnk%5F168667664973511&key=eac202ea7a96cf485281d6c4ffa2069e&libId=liuggg0i0103es17000ULlmtlntd&loc=https%3A%2F%2Fwww.makeuseof.com%2Fhow-to-fix-0x8004def5-onedrive-error-code-windows-11%2F&ccpaConsent=1---&v=1&opt=true&optExText=false&out=https%3A%2F%2Fdowndetector.com%2F&ref=https%3A%2F%2Fwww.makeuseof.com%2Fauthor%2Fabhishekkumar-mishra%2F&title=9%20Ways%20to%20Fix%20the%200x8004def5%20OneDrive%20Error%20Code%20on%20Windows%2011&txt=DownDetector) or a similar website.

 You can also check if your Windows PC can connect to the internet. Simply open a web browser and access a website or run a web-based app to confirm internet connectivity. If the servers are down, you will have to wait until they come up live again to use Winget.

## 3\. Perform a Complete System Shutdown

 Windows uses Fast Startup to hibernate kernel-level processes and if any of these glitch, they remain in that state after your power on the system. So, perform a complete shutdown to close and relaunch all the core services and then try to run Winget. Here’s how to do it:

1. Press **Win + R** to open the Run dialog box. Type **cmd** and press **Ctrl + Shift + Enter** keys to [open the Command Prompt with administrator privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Now, type the following command and press the Enter key: **shutdown /s /f /t 0**  
![Completely Shutdown your PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/completely-shutdown-your-pc.jpg)
3. Your system will shut down. It will take longer than a usual shutdown because Windows will close everything.
<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098700/14409" target="_top" id="2098700">
  <img src="//a.impactradius-go.com/display-ad/14409-2098700" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098700/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Power on your system and try to run Winget using the Terminal app to check if it works now.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137210/26400" target="_top" id="2137210">
  <img src="//a.impactradius-go.com/display-ad/26400-2137210" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137210/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Update App Installer

 Winget is a part of Windows 10 and 11 now and is shipped to PCs using the App Installer application. If you haven’t updated the App Installer in a while, you can face issues in running Winget and managing packages. Winget is included only in version 1.11.11451 or higher of the App Installer. If you have a version older than that, you cannot use Winget from the terminal.

![Update App Installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/update-app-installer.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137229/26400" target="_top" id="2137229">
  <img src="//a.impactradius-go.com/display-ad/26400-2137229" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137229/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 So, open Microsoft Store and check the library section for any pending updates for the App Installer. Manually search and install the update and check if Winget works now.

## 5\. Enable the App Execution Alias

 If the App Execution Alias for Winget is disabled, it won’t work when you try accessing Winget from the terminal. So, you must enable it in the app settings. Repeat the following steps:

1. Right-click on the **Start** button to open the **Power User** menu. Click on the **Settings** app.
2. Navigate to the left-hand side menu and click on the **Apps** option.
3. Now, click on the **Advanced app settings** option. Then click on the **App execution aliases** option.
4. Locate the **Windows Package Manager Client** option. Check the toggle next to it. If it is disabled, click on it to **enable** the app execution alias for the app.  
![Enable the App Execution Alias-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/enable-the-app-execution-alias-1.jpg)
5. Close the Settings app.

## 6\. Manually Add the Path Environment Variable

 Ae wrongly configured Winget path can also produce errors. So, you must manually add the correct path in Environment Variables using the Advanced System Properties window. Repeat the following steps:

1. Press **Win + R** to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **sysdm.cpl ,3** in the text box and press the **Enter** key to open **Advanced System Properties**.
2. Click on the **Environment Variables** button. Click on the **Path** entry and then click on the **Edit** button.
3. Now, click on the New button and paste the following path: **%UserProfile%\\AppData\\Local\\Microsoft\\WindowsApps**  
![Manually Add the Path Environment Variable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/manually-add-the-path-environment-variable.jpg)
4. Click on the **OK** button. Restart your PC.
<!-- affiliate ads begin -->
<span id="2135471">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2135471.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2135471">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2135471.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2135471%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2135471/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Open the Terminal app and check if Winget works or not.

## 7\. Re-register Winget Using PowerShell

 If Winget isn’t working on your PC, you can re-register it using PowerShell. Since it is a part of the App Installer which is a system app, it is possible to re-register it. Repeat the following steps:

1. Press **Win + R** to open the Run dialog box. Type **PowerShell** and press the **Ctrl + Shift + Enter** keys at once.
2. The PowerShell window will launch with admin rights. Paste the following code and press the **Enter** key to execute it:  
`Add-AppxPackage -DisableDevelopmentMode -Register "C:\Program Files\WindowsApps\Microsoft.Winget.Source_2021.718.1322.843_neutral__8wekyb3d8bbwe\AppXManifest.xml" -Verbose`
3. You won’t see any confirmation message after the command executes successfully. Close the PowerShell window and restart your PC.  
![Re-register Winget Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/re-register-winget-using-powershell.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2120866/26400?prodsku=mars" target="_top" id="2120866">
  <img src="//a.impactradius-go.com/display-ad/26400-2120866" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2120866/26400?prodsku=mars" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 8\. Try Some Generic Windows Fixes

 If none of the methods work for you, try our generic fixes like SFC and DISM scans that find and fix the system file corruption and service Windows Image components. You must [run the SFC scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) first and allow it to find and replace the corrupt system files, if any. After that, [run the DISM scan](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) in online mode.

 After running these scans, you can use System Restore to revert the PC to a point in time when everything worked fine. Lastly, you can perform a complete system reset. You can choose the Keep my files option to preserve all your files while [factory resetting Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/).

<!-- affiliate ads begin -->
<span id="701707">
					<video width="1536" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/701707.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/7443-701707">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/701707.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:960px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fappsumo.8odi.net%2Fc%2F5597632%2F701707%2F7443'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/701707/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Make Winget Functional Again

 Winget is a fantastic package manager that helps you control and manage app packages from the terminal. Ensure robust internet connectivity and check if the app execution alias is active for Winget. Manually reconfigure the PATH for Winget and re-register the App Installer using PowerShell. If you want a GUI version of Winget, you can try Winstall which helps you batch-install apps.

 But some users report that Winget is not working on their PC. They face a "The system cannot execute the specified program" and cannot run any commands, This post will discuss multiple methods to resolve the issue and restore Winget to its working state. Let’s begin.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-remedying-obs-fullscreen-disruption/"><u>[New] 2024 Approved Remedying OBS Fullscreen Disruption</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-unlocking-potential-how-to-maximize-whiteboards-in-zoom-meets/"><u>[New] 2024 Approved Unlocking Potential How to Maximize Whiteboards in Zoom Meets</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-best-extensions-to-capture-firefox/"><u>[New] In 2024, Best Extensions to Capture Firefox</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-2024-approved-maker-milestones-subscriber-and-interactive-feature-prizes/"><u>[Updated] 2024 Approved Maker Milestones Subscriber & Interactive Feature Prizes</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-web-surfing-on-film-the-best-screen-recording-apps-of-today/"><u>[Updated] 2024 Approved Web Surfing on Film The Best Screen Recording Apps of Today</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-insta-turn-techniques-flipping-your-photos-and-gaining-followers/"><u>[Updated] In 2024, Insta-Turn Techniques Flipping Your Photos and Gaining Followers</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-tune-up-the-mundane-how-to-add-custom-ringtones-and-sounds-for-a-unique-auditory-experience-on-android/"><u>[Updated] Tune Up the Mundane How to Add Custom Ringtones & Sounds for a Unique Auditory Experience on Android</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-iconic-vhs-visuals-to-transform-video-projects/"><u>2024 Approved Iconic VHS Visuals to Transform Video Projects</u></a></li>
<li><a href="https://screen-capture.techidaily.com/advanced-tricks-for-ios-screenshots-just-got-updated/"><u>Advanced Tricks for iOS Screenshots - Just Got Updated</u></a></li>
<li><a href="https://windows11.techidaily.com/gateway-to-gaming-glory-using-dosbox-x-for-pc-classics/"><u>Gateway to Gaming Glory: Using DOSBox-X for PC Classics</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-0x0000004e-error-in-windows-10-and-11/"><u>How to Fix the 0X0000004E Error in Windows 10 and 11</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-reset-apple-id-and-apple-password-on-iphone-11-by-drfone-ios/"><u>How to Reset Apple ID and Apple Password On iPhone 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-behind-the-lens-mastery-5-essential-cinematographic-insights/"><u>In 2024, Behind the Lens Mastery 5 Essential Cinematographic Insights</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-still-using-pattern-locks-with-infinix-smart-8-hd-tips-tricks-and-helpful-advice-by-drfone-android/"><u>In 2024, Still Using Pattern Locks with Infinix Smart 8 HD? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://windows11.techidaily.com/is-sleep-hibernate-or-shutdown-best-for-your-windows-computer/"><u>Is Sleep, Hibernate, or Shutdown Best for Your Windows Computer?</u></a></li>
<li><a href="https://howto.techidaily.com/itel-p55t-bootloop-problem-how-to-fix-it-without-data-loss-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Itel P55T Bootloop Problem, How to Fix it Without Data Loss | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/master-linux-without-wsl/"><u>Master Linux without WSL</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-top-rated-motion-graphics-software-for-text-tracking-for-2024/"><u>New Top-Rated Motion Graphics Software for Text Tracking for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-errors-in-windows-performance-dashboard/"><u>Overcoming Errors in Windows Performance Dashboard</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/portuguese-cantonese-and-others-macaus-languages/"><u>Portuguese, Cantonese & Others: Macau's Languages</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaiming-control-from-a-wildly-wandering-mouse/"><u>Reclaiming Control From a Wildly Wandering Mouse</u></a></li>
<li><a href="https://windows11.techidaily.com/reconfiguring-saving-preferences-for-pubg-on-pc/"><u>Reconfiguring Saving Preferences for PUBG on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-spontaneous-command-triggers-in-os/"><u>Remedying Spontaneous Command Triggers in OS</u></a></li>
<li><a href="https://windows11.techidaily.com/removing-windows-forbidden-permission-block/"><u>Removing Windows Forbidden Permission Block</u></a></li>
<li><a href="https://windows11.techidaily.com/sayonara-to-sluggish-keys-top-tricks-for-win-11s-faster-typing/"><u>Sayonara to Sluggish Keys: Top Tricks for Win 11'S Faster Typing</u></a></li>
<li><a href="https://windows11.techidaily.com/seamlessly-switch-windows-11-walls-to-reflect-each-screens-style/"><u>Seamlessly Switch Windows 11 Walls to Reflect Each Screen's Style</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-a-blissful-experience-with-no-bluescreens-on-win11/"><u>Secure a Blissful Experience with No Bluescreens on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-your-virtual-world-steps-for-epic-save-safety/"><u>Securing Your Virtual World: Steps for Epic Save Safety</u></a></li>
<li><a href="https://windows11.techidaily.com/shelve-the-start-of-edge-windows-11s-solution/"><u>Shelve the Start of Edge: Windows 11'S Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/simplified-gpo-analysis-via-gpresult-command/"><u>Simplified GPO Analysis via GPResult Command</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/solved-how-to-transfer-from-apple-iphone-13-to-iphone-15-drfone-by-drfone-transfer-from-ios/"><u>Solved How To Transfer From Apple iPhone 13 to iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-resurrecting-non-responsive-windows-batch-jobs/"><u>Strategies for Resurrecting Non-Responsive Windows Batch Jobs</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-strategies-for-enhancing-virtual-memory-on-windows-11-systems/"><u>Tailored Strategies for Enhancing Virtual Memory on Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-overcoming-admin-restrictions-on-setup-errors/"><u>Techniques for Overcoming Admin Restrictions on Setup Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/the-5-best-apps-to-skyrocket-your-productivity-on-windows-10-or-11/"><u>The 5 Best Apps to Skyrocket Your Productivity on Windows 10 or 11</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/the-ultimate-manual-to-assembling-a-top-tier-4k-editing-pc/"><u>The Ultimate Manual to Assembling a Top-Tier 4K Editing PC</u></a></li>
<li><a href="https://fox-that.techidaily.com/troubleshoot-iphone-13-glitches-with-these-6-easy-fixes/"><u>Troubleshoot iPhone 13 Glitches with These 6 Easy Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-non-functioning-windows-event-log/"><u>Troubleshooting Non-Functioning Windows Event Log</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/understanding-and-maintaining-optimal-battery-performance-on-your-android-smartphone/"><u>Understanding and Maintaining Optimal Battery Performance on Your Android Smartphone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/unearthing-timeless-treasures-a-classic-lit-exploration/"><u>Unearthing Timeless Treasures A Classic Lit Exploration</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-full-potential-of-text-with-snipping-tool-on-win-11/"><u>Unlock Full Potential of Text with Snipping Tool on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/windows-masterclass-silent-images-for-hidden-archives/"><u>Windows Masterclass: Silent Images for Hidden Archives</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>