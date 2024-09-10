---
title: Preserving Default Time on Windows PCs
date: 2024-09-09T12:15:01.797Z
updated: 2024-09-10T12:15:01.797Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Preserving Default Time on Windows PCs
excerpt: This Article Describes Preserving Default Time on Windows PCs
keywords: Save Windows Time Default,Maintain Windows Time Setting,Retain Standard PC Time,Preserve PC Time Standard,Keep Default Time Windows,Hold Default Time Windows PC,Uphold Windows Default Time
thumbnail: https://thmb.techidaily.com/e8596feeaa10b5decf0ac423846001bcbe9ce2de917f68ea7f6f367d6a2483c3.jpg
---

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134496/18498" target="_top" id="2134496">
  <img src="//a.impactradius-go.com/display-ad/18498-2134496" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134496/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Preserving Default Time on Windows PCs

 You’re using your Windows device and notice something strange in the date and time settings. Someone has changed the settings without your knowledge or permission. This makes it difficult to stay on schedule with tasks and activities. In this guide, we’ll show how to stop anonymous users from changing date and time settings on Windows computers.

<!-- affiliate ads begin -->
<a href="https://bluettiit.sjv.io/c/5597632/2114264/17093" target="_top" id="2114264">
  <img src="//a.impactradius-go.com/display-ad/17093-2114264" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettiit.sjv.io/i/5597632/2114264/17093" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How To Prevent Users From Changing the Date and Time on Windows

 There are two ways to prevent users from changing Windows date and time. The first is to use Group Policy Editor, a system administration tool designed to control computer behavior in an organization. While the second way is to use Registry Editor, which allows you to modify Windows registry settings.

 For both methods, you need administrative access to the computer to change it. Once you’ve made the changes, nobody can alter the date and time settings. Let’s look at each method in more detail.

## 1\. Use the Group Policy Editor

 If your computer is part of an organization and users often change the date and time, use Group Policy Editor to stop it. This will prevent those with limited access to the computer from altering the date and time. However, this method only works for Windows Pro, Enterprise, or Education Editions.

 So, if you have Windows Home Edition, this won’t work. In that case, you must first [activate the Group Policy Editor for Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). If it seems complicated, skip it and try the next solution instead.

 Follow these steps to prevent users from changing the date and time:

1. Press **Win + R** on your keyboard to open the Run window.
2. Type **gpedit.msc** in the text box and press Enter. This will open the Group Policy Editor window.
3. On the left side of the window, navigate to the following path:  
Computer Configuration > Administrative Templates > System > Locale Services
4. In the right-side pane, double-click on **Disallow user override of locale settings**.  
![Disallow user override of locale settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/disallow-user-override-of-locale-settings.jpg)
5. In the pop-up window, check the **Enabled** radio button.
<!-- affiliate ads begin -->
<span id="1531882">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1531882.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1531882">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1531882.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1531882%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1531882/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Then click **Apply** \> **OK** to save the changes.

 This will block anyone from changing the date and time settings on your computer. However, if you have administrative access to the computer, you can still alter the settings.

 If you want to revert to the default settings later, open Group Policy Editor again and change the value of Disallow user override of locale settings back to Not Configured or Disabled. This way, users can change the time and date again.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139122/17108" target="_top" id="2139122">
  <img src="//a.impactradius-go.com/display-ad/17108-2139122" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139122/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Tweak the Registry Editor

 If you’re using Windows Home Edition or have disabled the Group Policy Editor, use the Registry Editor to protect date and time settings. This method is more advanced and has a higher risk of system damage.

 In that case, [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it. Doing so will restore settings if something goes wrong.

 Follow these steps to stop users from changing the time and date via the registry:

1. [Open the Run command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **regedit** in the field and press Enter. This will [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. In the Registry Editor window, navigate to the following path:  
HKEY_CURRENT_USER\Software\Policies\Microsoft\Control Panel\International\
4. If the International folder doesn’t exist, create one. To do that, right-click on Control Panel and select **New** \> **Key**. Name it **International**.
5. Then right-click on **International** and select New > DWORD (32-bit) Value.
6. Name the newly created value **PreventUserOverrides**.
7. Double-click on the **PreventUserOverrides** DWORD value.  
![Use Registry Editor to Prevent Users From Chaning date and time settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/use-registry-editor-to-prevent-users-from-chaning-date-and-time-settings.jpg)
8. In the pop-up window, change the Value data to **1** and click **OK**.
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

 Once you’ve made the changes, close the Registry Editor window and restart your computer.

 To undo this restriction, delete the **PreventUserOverrides** DWORD value from the registry or change the value to **0**. Doing so will enable users to change the time and date again.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134237/18498" target="_top" id="2134237">
  <img src="//a.impactradius-go.com/display-ad/18498-2134237" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134237/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Stop Windows Time and Date Changes

 Now stop unauthorized users from changing the date and time settings on your Windows computer. This keeps your tasks and activities on track. If necessary, you can always undo this restriction.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-boosting-online-presence-top-30-freefire-hashtags-and-tag-strategies/"><u>[New] 2024 Approved Boosting Online Presence Top 30 FreeFire Hashtags and Tag Strategies</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-the-stream-wars-fb-live-youtube-live-and-twitters-periscope-face-off/"><u>[New] 2024 Approved The Stream Wars FB Live, YouTube Live, and Twitter's Periscope Face-Off</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-unveiling-the-truth-about-sharex-reviews-and-options/"><u>[New] 2024 Approved Unveiling the Truth About ShareX Reviews & Options</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-foremost-choices-customizable-mobile-alerts/"><u>[New] Foremost Choices Customizable Mobile Alerts</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-from-grayscale-to-graded-grandeur-color-artistry-for-2024/"><u>[New] From Grayscale to Graded Grandeur Color Artistry for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-golivebeam-simplified-method-to-broadcast-a-podcast-live-for-2024/"><u>[New] GoLiveBeam Simplified Method to Broadcast a Podcast Live for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-how-to-edit-titles-and-descriptions-of-igtv-videos-in-2024/"><u>[New] How to Edit Titles and Descriptions of IGTV Videos, In 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-2024-approved-gliding-giants-olympic-skate-tales/"><u>[Updated] 2024 Approved Gliding Giants Olympic Skate Tales</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-unleash-your-potential-with-instagram-tv-upload/"><u>[Updated] Unleash Your Potential with Instagram TV Upload</u></a></li>
<li><a href="https://windows11.techidaily.com/1-uncontrollable-mouse-movements-effective-solutions-to-regain-control/"><u>1. Uncontrollable Mouse Movements: Effective Solutions to Regain Control</u></a></li>
<li><a href="https://windows11.techidaily.com/2-seamless-integration-how-wsl-is-becoming-more-user-friendly-on-windows-pcs/"><u>2. Seamless Integration: How WSL Is Becoming More User-Friendly on Windows PCs</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-leveraging-kinemasters-strengths-for-video-magic-and-10-esteemed-competitors/"><u>2024 Approved Leveraging KineMaster's Strengths for Video Magic & 10 Esteemed Competitors</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-visionary-creatives-for-backdrops-pixelpioneers-realm/"><u>2024 Approved Visionary Creatives for Backdrops PixelPioneer's Realm</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-undelete-lost-music-from-meizu-by-fonelab-android-recover-music/"><u>Best Android Data Recovery - Undelete Lost Music from Meizu</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/bring-back-the-colors-in-twitch-streams/"><u>Bring Back the Colors in Twitch Streams</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-and-activate-your-realtek-asio-sound-controller-for-optimal-pc-performance-in-windows-navigator4/"><u>Download and Activate Your Realtek Asio Sound Controller for Optimal PC Performance in Windows Navigator_4</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-the-benefits-of-arm-based-copilotplus-computers-why-theyre-perfect-for-me/"><u>Exploring the Benefits of ARM-Based Copilot+ Computers: Why They're Perfect for Me</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-the-evolution-a-compelling-overview-of-windows-wallpaper-developments/"><u>Exploring the Evolution: A Compelling Overview of Windows Wallpaper Developments</u></a></li>
<li><a href="https://windows11.techidaily.com/further-issues-discovered-new-windows-updates-causing-devastating-bluescreens/"><u>Further Issues Discovered: New Windows Updates Causing Devastating Bluescreens</u></a></li>
<li><a href="https://windows11.techidaily.com/future-of-windows-11s-copilot-feature-understanding-the-phasing-out-process/"><u>Future of Windows 11'S Copilot Feature: Understanding the Phasing Out Process</u></a></li>
<li><a href="https://windows11.techidaily.com/get-superior-performance-for-windows-apps-on-macoslinux-with-crossover-24-at-promo-rates/"><u>Get Superior Performance for Windows Apps on macOS/Linux with CrossOver 24 at Promo Rates!</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-failed-to-launch-lunar-client-error-on-windows/"><u>How to Fix the “Failed to Launch Lunar Client” Error on Windows</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-android-to-apple-how-to-transfer-photos-from-vivo-x-fold-2-to-ipad-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Android to Apple How To Transfer Photos From Vivo X Fold 2 to iPad Easily | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-can-i-catch-the-regional-pokemon-without-traveling-on-infinix-note-30-vip-drfone-by-drfone-virtual-android/"><u>In 2024, How Can I Catch the Regional Pokémon without Traveling On Infinix Note 30 VIP | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-10-best-spy-watches-for-your-tecno-spark-20-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Top 10 Best Spy Watches For your Tecno Spark 20 Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/inside-look-7-windows-activities-harboring-risks/"><u>Inside Look: 7 Windows Activities Harboring Risks</u></a></li>
<li><a href="https://windows11.techidaily.com/lenovo-legion/"><u>Lenovo Legion</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-microsoft-code-companion-for-programmers/"><u>Leveraging Microsoft Code Companion for Programmers</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-learn-how-everything-works-on-lava-yuva-2-drfone-by-drfone-virtual-android/"><u>Life360 Learn How Everything Works On Lava Yuva 2 | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/macx-media-converter-seamlessly-transform-videos-into-itunes-format-for-ios-devices/"><u>MacX Media Converter - Seamlessly Transform Videos Into iTunes Format for iOS Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-customization-in-windows-11s-settings/"><u>Mastering Customization in Windows 11'S Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-performance-8-must-do-tasks-following-the-acquisition-of-a-new-windows-computer/"><u>Maximizing Performance: 8 Must-Do Tasks Following the Acquisition of a New Windows Computer</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mended-inaccessible-printer-connection/"><u>Mended Inaccessible Printer Connection</u></a></li>
<li><a href="https://windows11.techidaily.com/microsoft-successfully-addresses-persistent-problems-with-latest-windows-update-releases/"><u>Microsoft Successfully Addresses Persistent Problems with Latest Windows Update Releases</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-biggest-networking-sites-a-look-at-facebook-twitter-instagram-and-youtube/"><u>Navigating the Biggest Networking Sites: A Look at Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-major-windows-11-webcam-glitches-a-comprehensive-guide/"><u>Resolving Major Windows 11 Webcam Glitches: A Comprehensive Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/revamping-the-boring-windows-terminal-into-a-stylish-command-hub/"><u>Revamping the Boring Windows Terminal Into a Stylish Command Hub</u></a></li>
<li><a href="https://windows11.techidaily.com/say-goodbye-to-netflix-download-functionality-for-desktop-upcoming-changes-explained/"><u>Say Goodbye to Netflix Download Functionality for Desktop: Upcoming Changes Explained</u></a></li>
<li><a href="https://screen-recording.techidaily.com/simplified-steps-to-successful-screenshotsrecording-on-imac/"><u>Simplified Steps to Successful Screenshots/Recording on iMac</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-tutorial-on-locking-your-system-via-the-windows-11-command-line/"><u>Step-by-Step Tutorial on Locking Your System via the Windows 11 Command Line</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-microsoft-edge-by-disabling-redundant-features-techniques-and-tips/"><u>Streamlining Microsoft Edge by Disabling Redundant Features - Techniques and Tips</u></a></li>
<li><a href="https://tech-haven.techidaily.com/tech-disruption-identifying-vulnerable-occupations/"><u>Tech Disruption: Identifying Vulnerable Occupations?</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-12-improvements-for-a-future-release-what-users-hope-for-from-windows-12/"><u>The Essential 12 Improvements for a Future Release: What Users Hope For From Windows 12</u></a></li>
<li><a href="https://windows11.techidaily.com/the-nearly-complete-windows-11-update-for-2amz-may-2024-innovations-and-features-ahead/"><u>The Nearly Complete Windows 11 Update for 2Amz, May 2024: Innovations and Features Ahead!</u></a></li>
<li><a href="https://some-guidance.techidaily.com/tiktok-unboxers-guide-to-enhanced-video-engagement-and-likes-for-2024/"><u>TikTok Unboxers Guide to Enhanced Video Engagement and Likes for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/toggle-onoff-managing-your-gaming-experience-with-windows-10s-xbox-game-bar-feature/"><u>Toggle On/Off: Managing Your Gaming Experience with Windows 10'S Xbox Game Bar Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/top-10-fundamental-windows-terminal-commands-every-new-user-should-know/"><u>Top 10 Fundamental Windows Terminal Commands Every New User Should Know</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-techniques-for-resolving-memory-corruption-issues-in-windows-11/"><u>Top 5 Techniques for Resolving Memory Corruption Issues in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/top-7-linux-qualities-deserving-a-spot-in-the-next-windows-update/"><u>Top 7 Linux Qualities Deserving a Spot in the Next Windows Update</u></a></li>
<li><a href="https://windows11.techidaily.com/top-strategies-microsoft-should-implement-to-rescue-github-copilot-from-a-fate-similar-to-cortana/"><u>Top Strategies Microsoft Should Implement to Rescue GitHub Copilot From a Fate Similar to Cortana</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-messy-script-into-neat-text-with-microsoft-onenotes-new-feature/"><u>Transform Messy Script Into Neat Text with Microsoft OneNote's New Feature!</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-your-gaming-experience-how-microsofts-directsr-api-is-revolutionizing-pc-game-graphics/"><u>Transform Your Gaming Experience: How Microsoft's DirectSR API Is Revolutionizing PC Game Graphics</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-the-windows-license-permits-just-one-display-language-issue-expert-advice/"><u>Troubleshooting the 'Windows License Permits Just One Display Language' Issue - Expert Advice</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-11-issues-on-legacy-processors/"><u>Troubleshooting Windows 11 Issues on Legacy Processors</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-your-potential-the-best-three-tools-to-track-and-optimize-your-pc-gaming-experience/"><u>Unleash Your Potential: The Best Three Tools to Track and Optimize Your PC Gaming Experience</u></a></li>
<li><a href="https://some-skills.techidaily.com/unveiling-the-power-of-video-enhancement-sdr-to-dynamic-range-upconversion-for-2024/"><u>Unveiling the Power of Video Enhancement SDR to Dynamic Range Upconversion for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/weekly-tech-insights-atandt-data-leak-incident-and-latest-innovations-in-samsungs-phone-line-up/"><u>Weekly Tech Insights: AT&T Data Leak Incident & Latest Innovations in Samsung's Phone Line-Up</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-lifespan-extension-continuity-and-microsoft/"><u>Windows 11, Lifespan Extension, Continuity, and Microsoft.</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-devices-exposed-new-threats-in-the-ipv6-network-landscape/"><u>Windows Devices Exposed: New Threats in the IPv6 Network Landscape</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-xp-a-timeless-operating-system-with-unparalleled-longevity/"><u>Windows XP: A Timeless Operating System with Unparalleled Longevity</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-at-gaming-on-windows-11-a-step-by-step-performance-optimization-tutorial/"><u>Winning at Gaming on Windows 11: A Step-by-Step Performance Optimization Tutorial</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>