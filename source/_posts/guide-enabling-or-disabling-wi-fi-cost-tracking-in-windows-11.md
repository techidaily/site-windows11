---
title: "Guide: Enabling or Disabling Wi-Fi Cost Tracking in Windows 11"
date: 2024-07-11T21:57:13.091Z
updated: 2024-07-12T21:57:13.091Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Guide: Enabling or Disabling Wi-Fi Cost Tracking in Windows 11"
excerpt: "This Article Describes Guide: Enabling or Disabling Wi-Fi Cost Tracking in Windows 11"
keywords: Wi-Fi Cost Monitoring,Wifi Expense Control,Wi-Fi Usage Tracking,Windows 11 Wi-Fi Tracking,Enable/Disable Wi-Fi Costs,Windows Wi-Fi Expense Management,Tracking Wi-Fi Usage in Windows 11
thumbnail: https://thmb.techidaily.com/f47c079fa1fce90a8221b9c2c003a393b4231e2fbb42dbd4e99eb8971ba63ab6.jpg
---

## Guide: Enabling or Disabling Wi-Fi Cost Tracking in Windows 11

 If you're using a capped internet connection, such as a mobile hotspot, you'd want to limit your Windows PC's background data usage. That way, you ensure that background processes, like OneDrive or Steam, do not use up all your data while your computer's on.

 But how do you configure your PC to treat a Wi-Fi network as a metered or unmetered connection? Luckily, Windows 11 provides a couple of different ways to enable or disable metered connections for a Wi-Fi network. Let's go over both of them in detail.

## 1\. Enable or Disable Metered Connections for a Wi-Fi Network Using the Settings App

 The**Network & internet** section in the Settings app serves as a central location for all the network-related settings on Windows. You can visit that section to quickly enable or disable a metered connection for your computer's Wi-Fi network. Here are the steps for the same.

1. Open the**Start menu** and click the**gear-shaped icon** to [launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Network & internet** from the left sidebar.
3. Click on**Wi-Fi** from the right pane.
4. Go to**Manage known networks** .
5. Select the network you want to configure.
6. Enable the toggle next to**Metered connection** to set the Wi-Fi network as metered. If you want to set the network as an unmetered connection, disable the toggle.  
![Enable or Disable Metered Connection in Windows 11 Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/enable-or-disable-metered-connection-in-windows-11-using-settings-app.jpg)

 Note that you'll have to repeat the above steps for each Wi-Fi network separately. Following that, Windows will remember your network preferences.

## 2\. Enable or Disable Wi-Fi Metered Connections via the Command Prompt

 If you're a power user who prefers to make system changes with a command-line tool, you can use the [Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) to enable or disable metered connection for a Wi-Fi network on Windows. Here's how you can go about it.

1. Right-click the**Start icon** or use the**Win + X** keyboard shortcut to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the terminal window, type the following command and press**Enter** to view a list of network profiles on your computer:  
`netsh wlan show profiles`  
![Network Profiles in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-profiles-in-windows.jpg)
5. Note down the Wi-Fi network name for which you want to enable or disable the metered connection option.
6. Next, run the following command to determine whether your connection is metered or unmetered.  
`netsh wlan show profile name="Wi-Fi Name"`  
 Make sure you replace**Wi-Fi Name** in the above command with the actual name of the network noted in the last step.
7. Under the**Cost settings** section, check the value next to the**Cost** field. If it reads**Fixed** , the network is set as a metered connection. Conversely, if it reads**Unrestricted** , it is designated as an unmetered connection.
8. Type the following command and press**Enter** to mark the network as a metered connection.  
`netsh wlan set profileparameter name="Wi-Fi Name" cost=Fixed`  
![Disable Metered Connection in Windows 11 Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-metered-connection-in-windows-11-using-command-prompt.jpg)

 If you want to disable the metered connection for a network, run the following command instead.

`netsh wlan set profileparameter name="Wi-Fi Name" cost=Unrestricted`

 The Command Prompt should display a message once the network profile is updated. After that, you can close the terminal window.

 Aside from the above, you can view important details about your Wi-Fi network using the Command Prompt. If you're interested in doing that, check our guide on [the best commands to manage wireless networks on Windows](https://www.makeuseof.com/tag/commands-manage-wireless-networks-windows/) .

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
<li><a href="https://some-approaches.techidaily.com/the-ultimate-strategy-for-professional-gopro-filming-for-2024/"><u>The Ultimate Strategy for Professional Gopro Filming for 2024</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-nubia-z50-ultra-drfone-by-drfone-virtual-android/"><u>How to Get and Use Pokemon Go Promo Codes On Nubia Z50 Ultra | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-vpna-to-fake-gps-location-on-samsung-galaxy-m34-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Complete Tutorial to Use VPNa to Fake GPS Location On Samsung Galaxy M34 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/1719377597268-legacy-software-understanding/"><u>Legacy Software Understanding:</u></a></li>
<li><a href="https://windows11.techidaily.com/prying-into-hidden-taskbar-analysis-tool-in-windows-11/"><u>Prying Into Hidden Taskbar Analysis Tool in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/reestablish-wi-fi-masterful-solutions-for-windows-usb-adapters/"><u>Reestablish Wi-Fi: Masterful Solutions for Windows USB Adapters</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-caption-troubleshooting-made-simple/"><u>Win11 Caption Troubleshooting Made Simple</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-prime-5-podcast-options-for-your-iphone-experience/"><u>[Updated] Prime 5 Podcast Options for Your iPhone Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/re-establishing-printer-linkage-in-windows-11-setup/"><u>Re-Establishing Printer Linkage in Windows 11 Setup</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-elevate-your-tiktok-skills-with-voiceover/"><u>[Updated] 2024 Approved  Elevate Your TikTok Skills with Voiceover</u></a></li>
<li><a href="https://windows11.techidaily.com/a-guide-to-understanding-windows-program-files-format/"><u>A Guide to Understanding Windows' Program Files Format</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-manual-reverting-windows-to-a-previous-state/"><u>Step-by-Step Manual: Reverting Windows to a Previous State</u></a></li>
<li><a href="https://windows11.techidaily.com/playnite-extension-virtual-games-collection/"><u>Playnite Extension: Virtual Games Collection</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-addressing-undetectable-disks/"><u>Strategies for Addressing Undetectable Disks</u></a></li>
<li><a href="https://windows11.techidaily.com/reversal-of-extra-privileges-win11-standardization-tutorial/"><u>Reversal of Extra Privileges: Win11 Standardization Tutorial</u></a></li>
<li><a href="https://windows11.techidaily.com/the-uncharted-territory-windows-11-and-the-future-of-ai/"><u>The Uncharted Territory: Windows 11 and the Future of AI</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-auto-detection-errors/"><u>Overcoming Windows Auto Detection Errors</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-share-your-vibes-with-free-unmarked-tiktok-videos-for-2024/"><u>[Updated] Share Your Vibes with Free, Unmarked TikTok Videos for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/merge-your-world-connecting-android-and-windows-11-tablets/"><u>Merge Your World: Connecting Android and Windows 11 Tablets</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-reducing-browsing-impact-on-system-performance/"><u>Tips for Reducing Browsing Impact on System Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-update-halted-quick-solutions-for-a-perfect-installation/"><u>Windows Update Halted: Quick Solutions for a Perfect Installation</u></a></li>
<li><a href="https://youtube-web.techidaily.com/n-2024-cut-the-clutter-advanced-techniques-with-youtube-studio-editor/"><u>[New] In 2024, Cut the Clutter  Advanced Techniques with YouTube Studio Editor</u></a></li>
<li><a href="https://windows11.techidaily.com/newbies-in-the-windows-world-steer-clear-of-these-top-8-faux-pas/"><u>Newbies in the Windows World: Steer Clear of These Top 8 Faux Pas</u></a></li>
<li><a href="https://windows11.techidaily.com/a-beginners-guide-to-managing-windows-11-wins/"><u>A Beginner's Guide to Managing Windows 11 Wins</u></a></li>
<li><a href="https://windows11.techidaily.com/turning-on-hyper-v-simplified-your-win11-how-to/"><u>Turning On Hyper-V Simplified - Your Win11 How-To</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-hitting-the-high-scores-with-youtube-gaming-livestreams/"><u>In 2024, Hitting the High Scores with YouTube Gaming Livestreams</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-google-play-services-keeps-stopping-on-lava-storm-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What to Do if Google Play Services Keeps Stopping on Lava Storm 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-wi-fi-connectivity-hurdles-clearing-action-shortcomings/"><u>Overcoming Wi-Fi Connectivity Hurdles: Clearing Action Shortcomings</u></a></li>
<li><a href="https://windows11.techidaily.com/revive-the-disappearing-link-top-9-methods-for-win-11s-bluetooth-woes/"><u>Revive the Disappearing Link: Top 9 Methods for Win 11'S Bluetooth Woes</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-content-creators-den/"><u>2024 Approved  Content Creator's Den</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/harnessing-tech-acquiring-fb-status-video-content-for-2024/"><u>Harnessing Tech  Acquiring FB Status Video Content for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-and-fixing-invalid-temp-directories-on-win11/"><u>Preventing and Fixing Invalid Temp Directories on Win11</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-does-oppo-f23-5g-have-find-my-friends-drfone-by-drfone-virtual-android/"><u>In 2024, Does Oppo F23 5G Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/uniting-gmail-and-outlook-windows-setup-walkthrough/"><u>Uniting Gmail and Outlook: Windows Setup Walkthrough</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-correcting-incompatible-software-with-windows-operations/"><u>Strategies for Correcting Incompatible Software with Windows Operations</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-creative-processes-with-these-8-windows-best-apps/"><u>Streamline Creative Processes With These 8 Window's Best Apps</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-reimagining-pc-life-with-windows-11-setup/"><u>[Updated] Reimagining PC Life with Windows 11 Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/baffling-backup-concealed-control-center-settings/"><u>Baffling Backup: Concealed Control Center Settings</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-premium-free-excellence-analyzing-and-sharing-best-free-luts/"><u>2024 Approved  Premium-Free Excellence  Analyzing and Sharing Best Free LUTs</u></a></li>
<li><a href="https://article-helps.techidaily.com/stream-the-best-games-list-9/"><u>Stream the Best Games  List #9</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-apple-iphone-6-drfone-by-drfone-virtual-ios/"><u>In 2024, Here are Some Pro Tips for Pokemon Go PvP Battles On Apple iPhone 6 | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-master-list-top-free-photo-stockpile-locales/"><u>2024 Approved  Master List  Top Free Photo Stockpile Locales</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-unleash-your-artistry-top-10-music-video-creation-services/"><u>Updated In 2024, Unleash Your Artistry Top 10 Music Video Creation Services</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-how-to-loop-a-video-with-imovie-on-mac-and-iphone-for-2024/"><u>Updated How to Loop a Video with iMovie on Mac and iPhone for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11-secrets-with-devhome-insights/"><u>Unlocking Windows 11 Secrets with DevHome Insights</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-therere-two-ways-to-create-the-ken-burns-effect-in-final-cut-pro-using-the-automated-ken-burns-effect-tools-or-keyframes-check-this-article-to-find-/"><u>In 2024, Therere Two Ways to Create the Ken Burns Effect in Final Cut Pro Using the Automated Ken Burns Effect Tools or Keyframes. Check This Article to Find Out How-To</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/2024-approved-s-best-free-dvd-players-for-windows-10-a-comprehensive-list/"><u>2024 Approved S Best Free DVD Players for Windows 10 A Comprehensive List</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-access-disabled-sign-in-on-windows/"><u>Restoring Access: Disabled Sign-In on Windows</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/rank-your-download-preferences-with-our-top-5-list/"><u>Rank Your Download Preferences with Our Top 5 List</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/download-playback-streaming-youtube-videos-on-ios-securely-and-smoothly-for-2024/"><u>Download Playback  Streaming Youtube Videos on iOS Securely and Smoothly for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/ultimate-bundle-premier-cost-free-windows-11-assistants/"><u>Ultimate Bundle: Premier Cost-Free Windows 11 Assistants</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-premier-sites-for-digital-type-innovation/"><u>2024 Approved  Premier Sites for Digital Type Innovation</u></a></li>
<li><a href="https://printer-issues.techidaily.com/printer-problem-due-to-domain-service-outage/"><u>Printer Problem Due to Domain Service Outage</u></a></li>
<li><a href="https://windows11.techidaily.com/augmented-folder-actions-power-up-your-file-management/"><u>Augmented Folder Actions: Power Up Your File Management</u></a></li>
<li><a href="https://windows11.techidaily.com/rapid-and-secure-firmware-update-guide-for-surface-systems/"><u>Rapid & Secure Firmware Update Guide for Surface Systems</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-mastering-the-art-of-powerful-tiktok-campaigns/"><u>[New] In 2024, Mastering the Art of Powerful TikTok Campaigns</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-current-compendium-of-questions-for-captivating-audio-clips/"><u>In 2024, Current Compendium of Questions for Captivating Audio Clips</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-illustrators-toolkit-making-text-pop-in-3d/"><u>[Updated] The Illustrator's Toolkit  Making Text Pop in 3D</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-realme-narzo-60-5g-drfone-by-drfone-virtual-android/"><u>Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Realme Narzo 60 5G | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-tiktoks-rise-to-fame-through-twitters-top-10-list-for-2024/"><u>[Updated] TikTok's Rise to Fame Through Twitter’s Top 10 List for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/n-2024-getting-the-most-out-of-live-sports-on-youtube-tv/"><u>[New] In 2024, Getting the Most Out of Live Sports on YouTube TV</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/understanding-zooms-participant-clusters/"><u>Understanding Zoom's Participant Clusters</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-command-line-capabilities-in-latest-windows-releases/"><u>Boost Command-Line Capabilities in Latest Windows Releases</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-desktop-from-chaotic-to-customized-in-minutes/"><u>Win11 Desktop: From Chaotic to Customized, in Minutes</u></a></li>
<li><a href="https://windows11.techidaily.com/overhauling-write-operations-failure-fixes-on-windows/"><u>Overhauling Write Operations Failure Fixes on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/shaping-windows-11-square-it-off/"><u>Shaping Windows 11: Square It Off</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-2023s-top-contenders-gopro-hero5-vs-yi-4k-action-cameras/"><u>2024 Approved  2023'S Top Contenders  GoPro Hero5 Vs. Yi 4K Action Cameras</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-through-faulty-shift-in-windows/"><u>Navigate Through Faulty Shift in Windows</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-designing-effective-video-previews-for-channels/"><u>[New] 2024 Approved  Designing Effective Video Previews for Channels</u></a></li>
<li><a href="https://windows11.techidaily.com/are-file-thumbnails-not-showing-up-in-windows-11-heres-how-to-fix-it/"><u>Are File Thumbnails Not Showing Up in Windows 11? Here's How to Fix It</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-password-creation-companion-for-windows-users/"><u>The Ultimate Password Creation Companion for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-frozen-overlays-restoring-function-to-discord-ui/"><u>Addressing Frozen Overlays: Restoring Function to Discord UI</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/key-modern-tiktok-viral-phenomena-to-watch-for-2024/"><u>Key Modern TikTok Viral Phenomena to Watch for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-watch-hulu-outside-us-on-apple-iphone-se-2020-drfone-by-drfone-virtual-ios/"><u>How to Watch Hulu Outside US On Apple iPhone SE (2020) | Dr.fone</u></a></li>
</ul></div>
