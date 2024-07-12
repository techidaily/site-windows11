---
title: "Pushing Boundaries: My Quest to Overcome App Guard Censorship"
date: 2024-07-11T21:24:48.492Z
updated: 2024-07-12T21:24:48.492Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Pushing Boundaries: My Quest to Overcome App Guard Censorship"
excerpt: "This Article Describes Pushing Boundaries: My Quest to Overcome App Guard Censorship"
keywords: Boundary Push,Overcoming AppCensor,Quest for Freedom,Censorship Challenges,App Security Breach,Guard Override Techniques,Digital Rights Advocacy
thumbnail: https://thmb.techidaily.com/318f85e5a53d5f60469d32582133c5ee92bbc0ceb979fd63de287576e36507bb.jpg
---

## Pushing Boundaries: My Quest to Overcome App Guard Censorship

 Microsoft's Application Guard for Edge is a great tool to shield your browsing from malicious interference. For extra protection, both the camera and microphone are deactivated by default in this environment; however, there may be times when you need these features enabled to utilize certain web applications.

 If that’s the case, follow this guide which will show you how to enable the camera and microphone in Application Guard for Edge on Windows 11\. ​​​​​​

## 1\. How to Enable the Camera and Microphone via Windows Settings

 To enable the camera and microphone in Application Guard for Edge, follow the steps below:

1. Click on Start, type**Settings** and press**Enter** .
2. On the left side of the screen, select**Privacy & security** .
3. Click the**Windows Security** option on the right.
4. Then, on the next screen, select**App & browser control** .
5. In the new window that opens, click**Change Application Guard settings** under Isolated browsing.
6. Look for the**Camera and microphone** option, and then toggle it on.  
![Enable Camera and Microphone in Application Guard Using Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-camera-and-microphone-in-application-guard-using-windows-settings.jpg)
7. If the UAC prompt appears, click**Yes** to continue.

 After you perform the above action, restart your computer for the changes to take effect. Upon restarting, all your camera and microphone settings should now be applied to the Application Guard for Edge.

 In case you need to turn off the feature again, just follow the same steps and toggle the Camera and microphone option to Off. That’s all there is to it.

## 2\. How to Enable the Camera and Microphone Using Registry Editor

 If you are more comfortable using the registry editor, you can enable your camera and microphone for Application Guard for Edge. All you need to do is open up the registry folder, make a few easy modifications, and restart your computer so that they can take effect.

 However, before you make any changes, it's essential that you [create a backup of the registry file](https://www.makeuseof.com/tag/backup-restore-windows-registry/) just in case something goes wrong.

 To enable your mic & camera with the help of this tool, follow these steps:

1. Search for**regedit** in the Windows search bar and click on the result to open the registry editor. To find out more, see [how to open the registry](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. When the UAC prompt appears, click**Yes** to confirm.
3. In the Registry Editor window, go to the following location:  
Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Hvsi  
 Copy and paste the given location into the address bar at the top of the registry window and press Enter to quickly jump to the folder.
4. If you don't see the**Hvsi** key there, you need to create it first. In order to do this, right-click on the**Microsoft** folder and select**New > Key** .
5. Name the file**Hvsi** , then hit**Enter** to save it.  
![Creating a new DWORD (32-bit) Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-dword-enableclipboard-key.jpg)
6. Right-click on Hvsi, choose**New > DWORD (32-bit) Value** , then name it**EnableCameraMicrophoneRedirection** .
7. Now double-click on the newly created DWORD key, and you will see a pop-up window appear.
8. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Camera and Microphone in Application Guard Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-camera-and-microphone-in-application-guard-using-registry-editor.jpg)
9. Then click**OK** to save the changes.

 Once you've done editing the registry, restart your computer to apply the changes. After restarting, Edge's Application Guard will be able to access your camera and microphone hardware for websites that require it.

 If you want to revert the changes, simply set the EnableCameraMicrophoneRedirection key’s value back to**0** and restart your computer.

## Your Camera and Mic Is Now Supported in Edge Application Guard

 Application Guard for Edge is a tool that serves as an extra layer of protection from malicious websites and other threats. By default, your camera and microphone are disabled to ensure maximum security. In this guide, we've explained two quick ways in which you can easily activate these features - via Windows Settings or Registry Editor.


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
<li><a href="https://video-ai-editor.techidaily.com/updated-2024-approved-the-ultimate-list-of-video-tag-editors-for-windows-and-macos/"><u>Updated 2024 Approved The Ultimate List of Video Tag Editors for Windows and macOS</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-historys-high-scorers-on-reddit-top-10-list/"><u>In 2024, History's High Scorers on Reddit - Top 10 List</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-celebrating-conversations-reddits-momentous-discussions-top-10/"><u>[Updated] Celebrating Conversations  Reddit's Momentous Discussions (Top 10)</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-the-cycle-of-unresponsive-photoshop-on-windows/"><u>Breaking the Cycle of Unresponsive Photoshop on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/bygone-brilliance-reviving-retro-gameplay-with-dosbox-x/"><u>Bygone Brilliance: Reviving Retro Gameplay with DOSBox-X</u></a></li>
<li><a href="https://windows11.techidaily.com/a-step-by-step-approach-to-crafting-slideshows-and-fixing-flaws-in-win11s-photos-app/"><u>A Step-by-Step Approach to Crafting Slideshows & Fixing Flaws in Win11's Photos App</u></a></li>
<li><a href="https://windows11.techidaily.com/1719329062784-overcoming-full-screen-capture-annoyances-with-these-4-strategies/"><u>Overcoming Full-Screen Capture Annoyances with These 4 Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-techniques-for-windows-partition-consolidation/"><u>Advanced Techniques for Windows Partition Consolidation</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-isolating-subject-with-affinity/"><u>[New] Isolating Subject with Affinity</u></a></li>
<li><a href="https://windows11.techidaily.com/5-best-alternatives-for-windows-snipping-efficient-screen-grab-techniques/"><u>5 Best Alternatives for Windows Snipping: Efficient Screen Grab Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-problems-with-software-installations-from-windows-store/"><u>Addressing Problems with Software Installations From Windows Store</u></a></li>
<li><a href="https://windows11.techidaily.com/autopilot-off-stopping-chromes-unwanted-tab-openings/"><u>Autopilot Off: Stopping Chrome's Unwanted Tab Openings</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-leading-vr-accessories-the-top-10-countdown/"><u>In 2024, Leading VR Accessories  The Top 10 Countdown</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-back-your-bandsaw-methods-for-fixing-lost-windows-time/"><u>Bring Back Your Bandsaw: Methods for Fixing Lost Windows Time</u></a></li>
<li><a href="https://windows11.techidaily.com/a-step-by-step-approach-to-dotnet-repair-on-pcs-max-156/"><u>A Step-by-Step Approach to DotNet Repair on PCs (Max 156)</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-masterclass-setting-up-your-first-facebook-page-for-2024/"><u>[New] Masterclass  Setting Up Your First Facebook Page for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-from-conference-room-to-youtube-google-meet-broadcasting/"><u>[New] 2024 Approved  From Conference Room to Youtube  Google Meet Broadcasting</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-missed-emojis-activating-the-latest-on-windows-11/"><u>Avoiding Missed Emojis: Activating the Latest on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-the-blank-screen-top-techniques-to-recover-vanished-panes-in-windows-11/"><u>Avoid the Blank Screen: Top Techniques to Recover Vanished Panes in Windows 11</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/how-to-remove-background-noise-and-mute-clip-in-premiere-pro/"><u>How to Remove Background Noise and Mute Clip in Premiere Pro</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-videos-from-oneplus-by-fonelab-android-recover-video/"><u>How to Rescue Lost Videos from OnePlus</u></a></li>
<li><a href="https://windows11.techidaily.com/adapting-to-new-gear-your-powertoys-configuration-guide/"><u>Adapting To New Gear: Your PowerToys Configuration Guide</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/full-guide-to-catch-100-iv-pokemon-using-a-map-on-infinix-note-30-vip-racing-edition-drfone-by-drfone-virtual-android/"><u>Full Guide to Catch 100 IV Pokémon Using a Map On Infinix Note 30 VIP Racing Edition | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-can-i-bypass-a-forgotten-phone-password-of-samsung-galaxy-a05-by-drfone-android/"><u>In 2024, Can I Bypass a Forgotten Phone Password Of Samsung Galaxy A05?</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-troublesome-dism-error-0x800f082f/"><u>Bypassing Windows' Troublesome DISM: Error 0X800F082F</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-the-ultimate-guide-to-simple-iphone-screencasting/"><u>[New] The Ultimate Guide to Simple iPhone Screencasting</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-your-windows-11-search-with-these-five-essentials/"><u>Boost Your Windows 11 Search with These Five Essentials</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-quit-notifications-from-roblox-on-your-computer/"><u>Avoiding Quit Notifications From Roblox on Your Computer</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/lueprint-making-inspiring-lifestyle-broadcasts-for-2024/"><u>[New] Blueprint  Making Inspiring Lifestyle Broadcasts for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/solitary-voice-collective-applause-a-podcast-journey-for-2024/"><u>Solitary Voice, Collective Applause  A Podcast Journey for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/advance-work-efficiency-with-windows-smart-launcher-tool/"><u>Advance Work Efficiency with Windows' Smart Launcher Tool</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-in-depth-look-at-camstudios-capturing-capabilities/"><u>[Updated] 2024 Approved  In-Depth Look at CamStudio's Capturing Capabilities</u></a></li>
<li><a href="https://windows11.techidaily.com/a-practical-manual-for-windowss-pink-flash-dilemnas/"><u>A Practical Manual for Windows's Pink Flash Dilemnas</u></a></li>
<li><a href="https://windows11.techidaily.com/1719322271213-microsoft-to-do-not-sync-follow-these-steps-now/"><u>Microsoft To-Do Not Sync? Follow These Steps Now!</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-how-you-handle-deleted-items-on-pc/"><u>Adjusting How You Handle Deleted Items on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-roblox-code-403-blocks-on-pc/"><u>Addressing Roblox Code 403 Blocks on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-graphics-problem-3-for-windows-11-users/"><u>Addressing Graphics Problem #3 for Windows 11 Users</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-why-does-facebook-use-a-blue-icon-insights-into-chat-communication/"><u>[New] Why Does Facebook Use a Blue Icon? Insights Into Chat Communication</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/vn-video-editor-app-review-editing-made-easy-on-android-for-2024/"><u>VN Video Editor App Review Editing Made Easy on Android for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/unmasking-the-vanished-youtube-recommendations-on-facebook-for-2024/"><u>Unmasking the Vanished YouTube Recommendations on Facebook for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/breach-limitation-threshold-unleash-higher-ethernet-speeds-on-windows/"><u>Breach Limitation Threshold: Unleash Higher Ethernet Speeds on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-your-win-11-typing-efficiency-8-input-lag-remedies/"><u>Boost Your Win 11 Typing Efficiency: 8 Input Lag Remedies</u></a></li>
<li><a href="https://windows11.techidaily.com/calculate-and-track-power-consumption-for-your-pc-windows-edition/"><u>Calculate and Track Power Consumption for Your PC: Windows Edition</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-full-review-of-logitechs-ultimate-4k-professional-cam/"><u>[New] In 2024, Full Review of Logitech's Ultimate 4K Professional Cam</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-optimizing-your-youtube-video-preservation/"><u>[Updated] Optimizing Your YouTube Video Preservation</u></a></li>
<li><a href="https://some-approaches.techidaily.com/understanding-the-essence-of-luts-for-professional-photography-for-2024/"><u>Understanding the Essence of LUTs for Professional Photography for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/augmenting-macos-capabilities-via-windows-applications/"><u>Augmenting macOS Capabilities via Windows Applications</u></a></li>
<li><a href="https://windows11.techidaily.com/beating-steam-disk-write-failures-on-windows-pc/"><u>Beating Steam Disk Write Failures on Windows PC</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/1713962091636-updated-discover-the-best-video-frame-rate-converters-for-smooth-playback-including-online-and-offline-options-learn-how-to-convert-frame-rates-for-free-and/"><u>Updated Discover the Best Video Frame Rate Converters for Smooth Playback, Including Online and Offline Options. Learn How to Convert Frame Rates for Free and Elevate Your Video Quality with These Top 8 Tools for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-unlock-the-6th-richest-strategies-for-successful-ig/"><u>[New] Unlock the 6Th Richest Strategies for Successful IG</u></a></li>
<li><a href="https://windows11.techidaily.com/asus-zenbook-14-the-windows-mac-battle-continues/"><u>ASUS Zenbook 14: The Windows-Mac Battle Continues</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-preeminent-video-reports-on-desktops/"><u>[New] 2024 Approved  Preeminent Video Reports on Desktops</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-leading-8-flawless-recorder-picks/"><u>[New] 2024 Approved  Leading 8 Flawless Recorder Picks</u></a></li>
<li><a href="https://windows11.techidaily.com/5-clever-cmd-gimmicks-to-spice-up-your-day/"><u>5 Clever CMD Gimmicks to Spice Up Your Day</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensive-fix-manual-for-widespread-rainmeter-problems/"><u>A Comprehensive Fix Manual for Widespread Rainmeter Problems</u></a></li>
<li><a href="https://extra-resources.techidaily.com/inside-the-innovations-a-detailed-look-at-powerdirector-24-release/"><u>Inside the Innovations  A Detailed Look at PowerDirector '24 Release</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-gaps-in-time-remaining-estimates-of-windows-11-laptops/"><u>Addressing Gaps in Time Remaining Estimates of Windows 11 Laptops</u></a></li>
<li><a href="https://windows11.techidaily.com/cease-windows-logging-for-app-execution-dates/"><u>Cease Windows' Logging for App Execution Dates</u></a></li>
<li><a href="https://windows11.techidaily.com/building-your-signature-input-scheme-on-win11/"><u>Building Your Signature Input Scheme on Win11</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/unlock-the-potential-of-youtube-videos-the-ultimate-chapter-addition-technique/"><u>Unlock the Potential of YouTube Videos  The Ultimate Chapter Addition Technique</u></a></li>
<li><a href="https://windows11.techidaily.com/7-top-choices-no-cost-win-compatible-players/"><u>7 Top Choices: No-Cost Win-Compatible Players</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-pinnacletrack-audio-editor-comprehensive-mp3-tagging-capabilities-for-windows-and-mac/"><u>New 2024 Approved PinnacleTrack Audio Editor Comprehensive MP3 Tagging Capabilities for Windows & Mac</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-itel-p40-drfone-by-drfone-virtual-android/"><u>4 solution to get rid of pokemon fail to detect location On Itel P40 | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-quick-tip-find-your-youtube-comments-anytime-anywhere/"><u>[New] Quick Tip  Find Your YouTube Comments Anytime, Anywhere</u></a></li>
<li><a href="https://windows11.techidaily.com/a-journey-into-innovation-windows-11-writes-the-next-chapter/"><u>A Journey Into Innovation - Windows 11’ Writes the Next Chapter</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-cast-zte-axon-40-lite-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>How to Cast ZTE Axon 40 Lite Screen to PC Using WiFi | Dr.fone</u></a></li>
</ul></div>
