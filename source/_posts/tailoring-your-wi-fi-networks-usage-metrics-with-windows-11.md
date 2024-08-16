---
title: Tailoring Your Wi-Fi Network's Usage Metrics with Windows 11
date: 2024-08-15T16:16:52.070Z
updated: 2024-08-16T16:16:52.070Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tailoring Your Wi-Fi Network's Usage Metrics with Windows 11
excerpt: This Article Describes Tailoring Your Wi-Fi Network's Usage Metrics with Windows 11
keywords: Wi-Fi Usage Monitoring,Win11 NetMetrics,Wifi Performance Track,Windows 11 Usage Insights,Network Metric Tailor,Wi-Fi Optimization Tools,Data Analysis Windows 11
thumbnail: https://thmb.techidaily.com/5961427253350c1b74e1650e9c2f8a99858d6dfe3a81786842ed520231401b1b.jpg
---

## Tailoring Your Wi-Fi Network's Usage Metrics with Windows 11

 If you're using a capped internet connection, such as a mobile hotspot, you'd want to limit your Windows PC's background data usage. That way, you ensure that background processes, like OneDrive or Steam, do not use up all your data while your computer's on.

 But how do you configure your PC to treat a Wi-Fi network as a metered or unmetered connection? Luckily, Windows 11 provides a couple of different ways to enable or disable metered connections for a Wi-Fi network. Let's go over both of them in detail.

## 1\. Enable or Disable Metered Connections for a Wi-Fi Network Using the Settings App

 The**Network & internet** section in the Settings app serves as a central location for all the network-related settings on Windows. You can visit that section to quickly enable or disable a metered connection for your computer's Wi-Fi network. Here are the steps for the same.

1. Open the**Start menu** and click the**gear-shaped icon** to[launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Network & internet** from the left sidebar.
3. Click on**Wi-Fi** from the right pane.
4. Go to**Manage known networks** .
5. Select the network you want to configure.
6. Enable the toggle next to**Metered connection** to set the Wi-Fi network as metered. If you want to set the network as an unmetered connection, disable the toggle.  
![Enable or Disable Metered Connection in Windows 11 Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/enable-or-disable-metered-connection-in-windows-11-using-settings-app.jpg)

 Note that you'll have to repeat the above steps for each Wi-Fi network separately. Following that, Windows will remember your network preferences.

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Enable or Disable Wi-Fi Metered Connections via the Command Prompt

 If you're a power user who prefers to make system changes with a command-line tool, you can use the[Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) to enable or disable metered connection for a Wi-Fi network on Windows. Here's how you can go about it.

1. Right-click the**Start icon** or use the**Win + X** keyboard shortcut to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the terminal window, type the following command and press**Enter** to view a list of network profiles on your computer:  
`netsh wlan show profiles`  
![Network Profiles in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-profiles-in-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->
5. Note down the Wi-Fi network name for which you want to enable or disable the metered connection option.
6. Next, run the following command to determine whether your connection is metered or unmetered.  
`netsh wlan show profile name="Wi-Fi Name"`  
 Make sure you replace**Wi-Fi Name** in the above command with the actual name of the network noted in the last step.
7. Under the**Cost settings** section, check the value next to the**Cost** field. If it reads**Fixed** , the network is set as a metered connection. Conversely, if it reads**Unrestricted** , it is designated as an unmetered connection.
8. Type the following command and press**Enter** to mark the network as a metered connection.  
`netsh wlan set profileparameter name="Wi-Fi Name" cost=Fixed`  
![Disable Metered Connection in Windows 11 Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-metered-connection-in-windows-11-using-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you want to disable the metered connection for a network, run the following command instead.

`netsh wlan set profileparameter name="Wi-Fi Name" cost=Unrestricted`

 The Command Prompt should display a message once the network profile is updated. After that, you can close the terminal window.

 Aside from the above, you can view important details about your Wi-Fi network using the Command Prompt. If you're interested in doing that, check our guide on[the best commands to manage wireless networks on Windows](https://www.makeuseof.com/tag/commands-manage-wireless-networks-windows/) .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
<!-- affiliate ads end -->
## Efficiently Manage Your Data With Metered Connection

 Enabling or disabling the metered connection option for Wi-Fi networks in Windows is relatively simple, regardless of the method you use.

 If you have a limited data plan, you can also set a data usage limit for your Wi-Fi connection. This way, Windows will notify you when you approach the set data limit.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://remote-screen-capture.techidaily.com/new-discover-the-potential-of-screencastify-recorder/"><u>[New] Discover the Potential of Screencastify Recorder</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-five-to-fiveteen-tactics-against-oculus-discomfort-for-2024/"><u>[New] Five to Fiveteen  Tactics Against Oculus Discomfort for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-hidden-history-unveiled-understanding-off-facebook-data/"><u>[New] Hidden History Unveiled  Understanding Off-Facebook Data</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-digital-audio-wizardry-turning-fb-videos-into-mp3/"><u>[New] In 2024, Digital Audio Wizardry  Turning FB Videos Into MP3</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-vrecorder-integration-from-download-to-deployment/"><u>[New] VRecorder Integration  From Download to Deployment</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-essential-steps-for-saving-tweets-visuals-in-android-app/"><u>[Updated] Essential Steps for Saving Tweets' Visuals in Android App</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-zoom-into-your-workspace-learn-screen-casting-via-ezvide/"><u>[Updated] In 2024, Zoom Into Your Workspace  Learn Screen Casting via EZvide</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-premier-nintendo-switch-fighting-apps-list-max-156-for-2024/"><u>[Updated] Premier Nintendo Switch Fighting Apps List (Max 156) for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-premium-fb-extra-tools-secure-file-grabber-enhanced-firefox-use-for-2024/"><u>[Updated] Premium FB Extra Tools  Secure File Grabber, Enhanced Firefox Use for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-achieving-stunning-light-conditions-with-an-iphone/"><u>2024 Approved  Achieving Stunning Light Conditions with an iPhone</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-best-android-experience-with-rich-3d-content/"><u>2024 Approved  Best Android Experience with Rich 3D Content</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-invisible-vibes-dimming-music-on-computers/"><u>2024 Approved  Invisible Vibes  Dimming Music on Computers</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-iphone-a-revolutionary-approach-to-hdr-imaging/"><u>2024 Approved  IPhone  A Revolutionary Approach to HDR Imaging</u></a></li>
<li><a href="https://windows11.techidaily.com/5-reasons-to-steer-clear-from-inexpensive-windows-keys/"><u>5 Reasons to Steer Clear From Inexpensive Windows Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerate-search-results-in-windows-11-with-these-11-fixes/"><u>Accelerate Search Results in Windows 11 with These 11 Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-obs-record-failure-a-comprehensive-guide-for-windows-users/"><u>Addressing OBS Record Failure: A Comprehensive Guide for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-pcs-duration-before-lockdown/"><u>Adjusting PC's Duration Before Lockdown</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-non-functional-shortcuts-with-windows-snips/"><u>Avoiding Non-Functional Shortcuts with Windows Snips</u></a></li>
<li><a href="https://extra-resources.techidaily.com/beginning-participating-in-and-organizing-group-video-calls-zoom-for-android-devices/"><u>Beginning, Participating in, and Organizing Group Video Calls (Zoom) for Android Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-chains-of-stuck-files-win11-download-guide-2/"><u>Breaking Chains of Stuck Files: WIN11 Download Guide (2)</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/chuckle-and-cry-the-top-instagram-memes-that-make-you-giggle-for-2024/"><u>Chuckle & Cry  The Top Instagram Memes that Make You Giggle for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-blue-screen-5-tactics-for-win11-hybrid-issue-fixes/"><u>Conquer Blue Screen: 5 Tactics for Win11 Hybrid Issue Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/corrective-measures-for-discord-search-dysfunction/"><u>Corrective Measures for Discord Search Dysfunction</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-compelling-desktop-imagery-on-windows-11/"><u>Crafting Compelling Desktop Imagery on Windows 11</u></a></li>
<li><a href="https://article-posts.techidaily.com/cutting-edge-editing-tools-unveiled-for-2024/"><u>Cutting Edge Editing Tools Unveiled for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-impact-of-copilot-key-on-your-windows-11-pc-performance/"><u>Deciphering the Impact of Copilot Key on Your Windows 11 PC Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/discovering-the-power-of-wintoys-a-step-by-step-analysis-for-windows-users/"><u>Discovering the Power of WinToys: A Step-by-Step Analysis for Windows Users</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/elite-no-price-fb-photovideo-magic-maker-for-2024/"><u>Elite No-Price FB Photo/Video Magic Maker for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-troubleshooting-for-winscombsvc-error/"><u>Essential Troubleshooting for WinScombSvc Error</u></a></li>
<li><a href="https://some-techniques.techidaily.com/evaluating-video-space-on-a-64gb-card-for-2024/"><u>Evaluating Video Space on a 64GB Card for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-silent-mode-glitches-on-windows-word-reading-feature/"><u>Fix Silent Mode Glitches on Windows' Word Reading Feature</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/get-rid-of-filmora-watermark-with-or-without-subscription-for-2024/"><u>Get Rid of Filmora Watermark With or Without Subscription for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-change-the-task-manager-start-page-in-windows-11/"><u>How to Change the Task Manager Start Page in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-win11-outshines-macos-on-key-fronts/"><u>How Win11 Outshines MacOS on Key Fronts</u></a></li>
<li><a href="https://windows11.techidaily.com/image-integration-insights-securely-stashing-files-on-windows-11/"><u>Image Integration Insights: Securely Stashing Files on Windows 11</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-audacity-audio-basics-for-new-mac-users/"><u>In 2024, Audacity Audio Basics for New Mac Users</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-harness-the-power-of-dual-screen-on-apple-devices-via-safari/"><u>In 2024, Harness the Power of Dual Screen on Apple Devices via Safari</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-change-country-on-app-store-for-apple-iphone-6-with-7-methods-by-drfone-ios/"><u>In 2024, How To Change Country on App Store for Apple iPhone 6 With 7 Methods</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-how-to-insert-youtube-playlists-seamlessly-into-a-website/"><u>In 2024, How to Insert YouTube Playlists Seamlessly Into a Website</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-skype-tone-searching-made-easy-pick-from-the-4-ace-lists/"><u>In 2024, Skype Tone Searching Made Easy  Pick From the 4 Ace Lists</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-smart-techniques-to-capture-gotomeet-participants/"><u>In 2024, Smart Techniques to Capture GoToMeet Participants</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-steady-visual-storytelling-techniques/"><u>In 2024, Steady Visual Storytelling Techniques</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-tips-for-successful-video-game-broadcasting/"><u>In 2024, Tips for Successful Video Game Broadcasting</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-what-to-do-if-your-apple-iphone-11-pro-max-has-bad-esn-or-blacklisted-imei-by-drfone-ios/"><u>In 2024, What to do if your Apple iPhone 11 Pro Max has bad ESN or blacklisted IMEI?</u></a></li>
<li><a href="https://windows11.techidaily.com/linux-vs-windows-a-comprehensive-gamers-guide/"><u>Linux Vs. Windows: A Comprehensive Gamer's Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/lost-and-found-how-to-find-the-disappeared-enhancements-on-windows-11/"><u>Lost and Found: How to Find the Disappeared Enhancements on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-art-of-3d-painting-with-these-tips/"><u>Master the Art of 3D Painting with These Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-inaccessible-game-on-windows-steam/"><u>Navigating Through Inaccessible Game on Windows Steam</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-pushing-boundaries-incorporating-photography-into-audio-experiences-audiovisual-trends-2023/"><u>New 2024 Approved Pushing Boundaries Incorporating Photography Into Audio Experiences Audiovisual Trends 2023</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-your-pre-win11-system-efficiently/"><u>Optimize Your Pre-Win11 System Efficiently</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-geforce-error-xc0f1103f-in-windows-systems/"><u>Overcoming GeForce Error XC0F1103F in Windows Systems</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/quick-focus-effortless-viewport-changes-on-iphone-for-2024/"><u>Quick Focus  Effortless Viewport Changes on iPhone for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/revamping-network-defenses-with-these-5-steps/"><u>Revamping Network Defenses with These 5 Steps</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/score-your-youtube-content-with-these-free-sounds-for-2024/"><u>Score Your YouTube Content With These Free Sounds for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-windows-notepad-notebook-errors/"><u>Solutions for Windows Notepad Notebook Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-active-directory-related-printer-errors-on-w11/"><u>Steps to Resolve Active Directory-Related Printer Errors on W11</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-and-simplify-game-setup-in-xbox-app/"><u>Streamline and Simplify Game Setup in Xbox App</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-tasks-essential-folders-tweaks-for-windows-users/"><u>Streamline Tasks: Essential Folders Tweaks for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/surging-past-connectivity-hurdles-in-win-and-ea-games/"><u>Surging Past Connectivity Hurdles in Win and EA Games</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-port-reset-failed-issue-in-windows-11/"><u>Tackling 'Port Reset Failed' Issue in Windows 11</u></a></li>
<li><a href="https://os-tips.techidaily.com/trouble-with-iphone-personal-hotspot-here-are-proven-solutions-to-restore-connectivity/"><u>Trouble with iPhone Personal Hotspot? Here Are Proven Solutions to Restore Connectivity</u></a></li>
<li><a href="https://windows11.techidaily.com/turbocharging-your-battlenet-downloads-on-windows-pcs/"><u>Turbocharging Your Battle.net Downloads on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/tweak-your-pc-reduce-memorycpu-waste-from-apps/"><u>Tweak Your PC: Reduce Memory/CPU Waste From Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-fixing-the-windows-error-0x800704b3/"><u>Understanding and Fixing the Windows Error: 0X800704B3</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-data-power-discover-four-routes-to-opening-disk-management-in-win11/"><u>Unleash Data Power: Discover Four Routes to Opening Disk Management in Win11</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/unpacking-the-sequencing-of-a-20mb-file/"><u>Unpacking the Sequencing of a 20MB File</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secrets-of-windows-11s-compatibility-diagnostic/"><u>Unveiling the Secrets of Windows 11’S Compatibility Diagnostic</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-2024-approved-find-moan-sound-effect/"><u>Updated 2024 Approved Find Moan Sound Effect</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-the-best-free-web-integrated-daw-software-ranked-your-guide-for-2024/"><u>Updated The Best Free, Web-Integrated DAW Software Ranked - Your Guide for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-ping-wisdom-utilizing-tools-for-maximum-efficiency/"><u>Windows Ping Wisdom: Utilizing Tools for Maximum Efficiency</u></a></li>
</ul></div>
