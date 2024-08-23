---
title: Essential Steps to Locate GPO in Windows OS
date: 2024-08-22T21:40:10.603Z
updated: 2024-08-23T21:40:10.603Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Essential Steps to Locate GPO in Windows OS
excerpt: This Article Describes Essential Steps to Locate GPO in Windows OS
keywords: Find GPO Windows,Windows GPOP Search,Navigate GPO Windows,GPO Locator Windows,Identify Window's GPO,Access GPO in OS,Windows GPO Settings
thumbnail: https://thmb.techidaily.com/e68430bcb106e10e6ed671e16682f01d022f0799c626556c343ddc595fa9cde5.jpg
---

## Essential Steps to Locate GPO in Windows OS

 Changing a group policy is something that many Windows users will have to do at some point in their life. However, knowing the path to a particular setting in the Local Group Policy Editor (LGPE) is not so simple, considering the sheer scale of the folders and subfolders within the tool.

 In this guide, we're going to show you three ways to search for the group policies you need so you don't get lost.

## 1\. Search Using the Local Group Policy Editor's Filter Option

 Press **Win + S** to bring up Windows Search, search for **edit group policy**, and click on **Edit group policy** in the search results. This will launch the LGPE.

 Only the Pro and Enterprise editions of Windows come with the LGPE pre-installed, but there is a way you can [access the LGPE on Home editions](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 In the left pane, right-click the **Administrative Templates** folder (it's the only folder that allows you to search this way), and click **Filter On** to enable filtering. Right-click the folder again, and this time, select **Filter Options**.

![the menu that shows up when you right-click Administrative Templates in the Loca Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/lgpe-search-filter-option.jpg)

 In the Filter Options dialog box, make sure to check the **Enable Keyword Filters** checkbox. Next, in the text box next to **Filter for word(s)**, enter the search terms for the policy or, if you know it, the exact name of the policy.

![the Filter Options dialog box with the Enable Keywords and filter text box part showing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/lgpe-search-filter-options-search-phrase-windows.jpg)

 In the dropdown next to that filter text box, you can choose the following options:

* **Any**: The policy you’re searching for contains one or more of the words entered in the filter text box.
* **All**: The policy you’re searching for contains each word entered in the filter text box.
* **Exact**: The policy you're searching for contains the exact phrase entered in the filter text box.

 Next, check the **Enable Requirement Filters** checkbox and click the **Select All** button (this means you want to search for the policy on all platforms). Then, click **OK**.

![the Filter Options dialog box showing the requirements section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/lgpe-search-filter-option-requirements-filters.jpg)

 Back in the LGPE, you should start to see the folders and policies decrease in number since others have been filtered out. To quickly find the policy you were searching for, click **All Settings**.

![All Settings selected in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/lgpe-search-filter-results-windows.jpg)

 While editing, keep in mind that changing the right [group policies can make your PC better](https://www.makeuseof.com/tag/12-ways-windows-group-policy-can-make-pc-better/), or, if you tweak the wrong one, make it worse.

## 2\. Search Using the Group Policy Website

 Besides using filters in the LGPE, you can also use the [Group Policy Search](https://gpsearch.azurewebsites.net/) website. While on the site, click the **filter icon** in the top left corner and uncheck all the products you don’t want to include in the search.

![filtering out products on the Group Policy Search website](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/gps-website-filters.jpg)

 Click on the search box at the top, enter the search terms for the policy, and hit the **Enter** key. If you want to do an exact search, be sure to put the search string within quotes, like “disable context menu,” for example.

![searching for a group policy on the Group Policy Search website](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/gps-website-searching-policy.jpg)

 The search policy will appear in the second column, so click on it to reveal more information about it in a pop-up. You will see where to find the policy in the LGPE directly under the heading.

![the search results on the Group Policy Search website](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/gps-website-searching-policy-results.jpg)

 Where it says **Key**, you can see where to find the setting in the Registry Editor.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->
## 3\. Search Using the Group Policy Settings Reference

 If you prefer something offline and a little easier to access compared to searching with the LGPE's filters and the Group Policy Search website, Microsoft has a document you can use. So, download the [Group Policy Settings Reference](https://www.microsoft.com/en-us/download/details.aspx?id=25250) sheet and open it in Excel.

 To search for a policy, click on the **filter icon** next to the **Policy Setting Name** heading in the **C** column. In the text box that says **Search**, type in search terms for the policy you want to find, and then hit the **Enter** key.

![searching the group policy reference sheet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/group-policy-reference-sheet-text-filter.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The policies that match the search terms will appear in column **C**. You can find the location of the policy in column **E** under the **Policy Path** heading.

![the results of searching for a group policy in the reference sheet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/group-policy-reference-sheet-policy-path.jpg)

<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 That’s the folder you need to look at in the LGPE to find the policy that you need to edit.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
## Find the Group Policy You Need on Windows

 Now you should be able to find the group policies you need to make your PC better. We know how overwhelming it can be to use the Local Group Policy Editor, but with these tools, it should become a little easier. And if your edits don't take effect right away, there’s a way for you to manually refresh the LGPE to apply the settings immediately.

 In this guide, we're going to show you three ways to search for the group policies you need so you don't get lost.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-the-ultimate-checklist-for-recording-whatsapp-discussions/"><u>[New] 2024 Approved  The Ultimate Checklist for Recording WhatsApp Discussions</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-amplify-online-impact-through-savvy-templates-design/"><u>[New] Amplify Online Impact Through Savvy Templates Design</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-breaking-down-lgs-360-camera-updates-and-features-for-2024/"><u>[New] Breaking Down LG's 360 Camera Updates & Features for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-2024-approved-scouting-the-best-cameras-for-aspiring-muso-videographers/"><u>[Updated] 2024 Approved  Scouting the Best Cameras for Aspiring Muso Videographers</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-craft-your-storyline-three-ways-to-border-instagram-videos/"><u>[Updated] Craft Your Storyline  Three Ways to Border Instagram Videos</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-drones-in-a-rivalry-dji-inspire-one-vs-gopro-karma-x/"><u>[Updated] Drones in a Rivalry  DJI Inspire One Vs GoPro Karma X</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-leveraging-technology-for-optimal-fb-stream-recording/"><u>[Updated] In 2024, Leveraging Technology for Optimal FB Stream Recording</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-masterful-video-cropping-elevate-your-content-game-on-instagram/"><u>[Updated] In 2024, Masterful Video Cropping  Elevate Your Content Game on Instagram</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-navigating-the-future-of-fb-advertising-key-predictions/"><u>[Updated] Navigating the Future of FB Advertising – Key Predictions</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-steps-to-sign-in-with-google-meet-laptop-and-mobile/"><u>[Updated] Steps to Sign-In with Google Meet (Laptop & Mobile)</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-subscribers-manual-engaging-on-social-media-platforms/"><u>[Updated] The Subscriber's Manual  Engaging on Social Media Platforms</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-ultimate-list-groundbreayer-vr-gloves-reviewed/"><u>[Updated] Ultimate List  Groundbreayer VR Gloves Reviewed</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-10-best-online-destinations-for-accessible-images/"><u>2024 Approved  10 Best Online Destinations for Accessible Images</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-instagrams-hidden-details-uncovering-story-viewer-truths/"><u>2024 Approved  Instagram's Hidden Details  Uncovering Story Viewer Truths</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-the-video-producers-route-to-royalty-free-soundtracks/"><u>2024 Approved  The Video Producer’s Route to Royalty-Free Soundtracks</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/android-unlock-code-sim-unlock-your-samsung-galaxy-a05-phone-and-remove-locked-screen-by-drfone-android/"><u>Android Unlock Code Sim Unlock Your Samsung Galaxy A05 Phone and Remove Locked Screen</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/detailed-full-rotation-cam-insight/"><u>Detailed Full-Rotation Cam Insight</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-non-initialization-of-qt-engine-in-software-applications/"><u>Fixing Non-Initialization of Qt Engine in Software Applications</u></a></li>
<li><a href="https://windows11.techidaily.com/forewarned-is-forearmed-top-8-windows-11-no-nos-for-neophytes/"><u>Forewarned Is Forearmed: Top 8 Windows 11 No-Nos for Neophytes</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/freecam-x-live-streaming-software-reviewed-for-2024/"><u>FreeCam X Live Streaming Software Reviewed for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-restore-functional-drag-and-drop-in-windows-11/"><u>Guide: Restore Functional Drag-and-Drop in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/harnessing-powertoys-for-seamless-international-mouse-usage/"><u>Harnessing PowerToys for Seamless International Mouse Usage</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-can-we-unlock-our-xiaomi-redmi-note-12r-phone-screen-by-drfone-android/"><u>How Can We Unlock Our Xiaomi Redmi Note 12R Phone Screen?</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-downgrade-iphone-15-pro-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade iPhone 15 Pro without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-fix-apple-iphone-12-pro-unavailable-issue-with-ease-by-drfone-ios/"><u>How To Fix Apple iPhone 12 Pro Unavailable Issue With Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-msvcr120dll-missing-error-on-windows/"><u>How to Fix the Msvcr120.dll Missing Error on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-this-app-has-been-blocked-for-your-protection-error-on-windows/"><u>How to Fix This App Has Been Blocked for Your Protection Error on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-spur-microsoft-edge-speed-in-windows-1011/"><u>How to Spur Microsoft Edge Speed in Windows 10/11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-vivo-v30-location-by-number-drfone-by-drfone-virtual-android/"><u>How to Track Vivo V30 Location by Number | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-motorola-edge-40-pro-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Motorola Edge 40 Pro to New Android? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-ways-to-track-vivo-y78plus-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Track Vivo Y78+ without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-motorola-razr-40-ultra-drfone-by-drfone-virtual/"><u>In 2024, 9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Motorola Razr 40 Ultra | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-funimate-decoded-a-step-by-step-journey/"><u>In 2024, Funimate Decoded  A Step-by-Step Journey</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-special-features-virtual-location-on-apple-iphone-7-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, How To Use Special Features - Virtual Location On Apple iPhone 7 Plus? | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-vegas-pro-2021-reviewed-a-sports-betting-journey/"><u>In 2024, Vegas Pro 2021 Reviewed – A Sports Betting Journey</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/leading-the-virtual-conversation-with-social-media/"><u>Leading the Virtual Conversation with Social Media</u></a></li>
<li><a href="https://some-guidance.techidaily.com/leveraging-kinemasters-strengths-for-video-magic-and-10-esteemed-competitors-for-2024/"><u>Leveraging KineMaster's Strengths for Video Magic & 10 Esteemed Competitors for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-multi-os-environments-windows-host-for-linux-virtual-machines/"><u>Mastering Multi-OS Environments: Windows Host for Linux Virtual Machines</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-rainmeter-hiccups-with-easy-fixes/"><u>Mastering Window's Rainmeter Hiccups with Easy Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-wsl-enabling-linux-in-windows-environment/"><u>Mastering WSL: Enabling Linux in Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-of-overcoming-windows-activation-fault-error-0x803f700f/"><u>Mastery of Overcoming Windows Activation Fault: Error 0X803F700f</u></a></li>
<li><a href="https://windows11.techidaily.com/modifying-account-lockout-period-post-failed-logon/"><u>Modifying Account Lockout Period Post-Failed Logon</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-top-10-best-websites-like-omegle/"><u>New 2024 Approved Top 10 Best Websites Like Omegle</u></a></li>
<li><a href="https://windows11.techidaily.com/onoff-switch-controlling-windows-energy-saving-mode/"><u>On/Off Switch: Controlling Windows' Energy-Saving Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-wallet-growth-unlocking-windows-11-pro-offers/"><u>Optimize Wallet Growth - Unlocking Windows 11 Pro Offers</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-0xc00000f-issue-on-your-pc-easily/"><u>Overcoming 0Xc00000f Issue on Your PC Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-printer-connection-glitches-in-windows/"><u>Overcoming Printer Connection Glitches in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/pro-tips-selecting-superior-windows-11-drawers/"><u>Pro Tips: Selecting Superior Windows 11 Drawers</u></a></li>
<li><a href="https://windows11.techidaily.com/proactive-pc-management-utilizing-command-prompt-for-timely-detection-and-correction-of-windows-errors/"><u>Proactive PC Management: Utilizing Command Prompt for Timely Detection & Correction of Windows Errors</u></a></li>
<li><a href="https://location-social.techidaily.com/proven-ways-in-how-to-hide-location-on-life360-for-motorola-edgeplus-2023-drfone-by-drfone-virtual-android/"><u>Proven Ways in How To Hide Location on Life360 For Motorola Edge+ (2023) | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/race-the-rate-unveiling-windows-techniques-for-measuring-ethernet-speed/"><u>Race the Rate: Unveiling Windows Techniques for Measuring Ethernet Speed</u></a></li>
<li><a href="https://windows11.techidaily.com/reconnecting-solo-side-headphones-to-windows-os/"><u>Reconnecting Solo Side Headphones to Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-security-fault-in-1011-edition/"><u>Resolving Windows Security Fault in 10/11 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/resurrecting-the-clock-actions-to-restore-windows-server-time/"><u>Resurrecting the Clock: Actions to Restore Windows Server Time</u></a></li>
<li><a href="https://windows11.techidaily.com/revealing-indexers-control-accessibility/"><u>Revealing Indexer's Control Accessibility</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-your-computer-with-windows-hello-fingerprint/"><u>Securing Your Computer with Windows Hello Fingerprint</u></a></li>
<li><a href="https://windows11.techidaily.com/starting-diagnostics-five-quick-steps-in-windows/"><u>Starting Diagnostics: Five Quick Steps in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/synchronizing-seamlessly-accessing-cloud-storage-from-windows-directories/"><u>Synchronizing Seamlessly: Accessing Cloud Storage From Windows Directories</u></a></li>
<li><a href="https://windows11.techidaily.com/tech-guide-extending-windows-menu-options-in-xp-7-8-and-10/"><u>Tech Guide: Extending Windows Menu Options in XP, 7, 8 & 10</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/the-hidden-powerhouses-in-your-instagram-toolkit/"><u>The Hidden Powerhouses in Your Instagram Toolkit</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-ultimate-handbook-to-drone-video-editing-for-2024/"><u>The Ultimate Handbook to Drone Video Editing for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/time-saving-routines-for-capturing-vimeo-media-for-2024/"><u>Time-Saving Routines for Capturing Vimeo Media for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/trail-clearing-techniques-deciphering-and-erasing-windows-history/"><u>Trail-Clearing Techniques: Deciphering and Erasing Windows History</u></a></li>
<li><a href="https://windows11.techidaily.com/trouble-on-windows-discover-assistance-methods/"><u>Trouble on Windows? Discover Assistance Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-invalid-system-name-in-windows-11/"><u>Troubleshooting Invalid System Name in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-restrictions-of-secure-boot-and-tpm-using-rufus/"><u>Unlocking the Restrictions of Secure Boot & TPM Using Rufus</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-premium-weather-apps-for-windows-11/"><u>Unveiling Premium Weather Apps for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/why-do-computers-have-a-windows-batch-file/"><u>Why Do Computers Have a Windows Batch File?</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-addressing-discord-installation-issues/"><u>Win 11: Addressing Discord Installation Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-advancements-what-the-new-update-brings-in/"><u>Windows 11 Advancements: What the New Update Brings In</u></a></li>
<li><a href="https://windows11.techidaily.com/workaround-to-avoid-discord-autostarting-on-pc/"><u>Workaround to Avoid Discord Autostarting on PC</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>