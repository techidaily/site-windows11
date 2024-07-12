---
title: A Step-By-Step for Erasing Sign-In Email in Win
date: 2024-07-11T21:19:58.954Z
updated: 2024-07-12T21:19:58.954Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Step-By-Step for Erasing Sign-In Email in Win
excerpt: This Article Describes A Step-By-Step for Erasing Sign-In Email in Win
keywords: Win Email Sign-Out Guide,Windows Remove Login Mail,Clearing Win Signin E-Mail,Win Email Unlink Steps,Disable Win Login Email,Win Sign-In Email Removal,Erase Win Logon Email Process
thumbnail: https://thmb.techidaily.com/aa827fc3b79814207754c42d6a6a4c83088ec414afa88e6a5b8f7881f823fc3c.jpg
---

## A Step-By-Step for Erasing Sign-In Email in Win

 If you frequently use your computer in public places, it's a good idea to remove your email address from the Windows login screen. This means people can't get your email address if they see your screen over your shoulder.

 You can accomplish this using the Settings app, Group Policy Editor, or Registry Editor. In this post, we've covered all these methods in detail.

## 1\. How to Hide Email Address From Windows Login Screen Using the Settings App

 The Windows Settings app provides a quick way to hide account information from the login screen. So, if you are in a rush, use the following steps to remove user email addresses from the Windows login screen.

1. Press**Win + I** or use one of the [many ways to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Accounts > Sign-in options** .
3. Under**Additional settings** , toggle off the switch next to **Show account details such as my email address on the sign-in screen** .  
![Hide Email From Windows Login Screen Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-settings-app.jpg)

## 2\. How to Hide Email Address From Windows Login Screen Using the Group Policy Editor

 The Group Policy Editor (or gpedit.msc) is a handy Windows tool for configuring advanced system settings. You can also this tool to hide your email address from the Windows login screen.

 Note that the Group Policy Editor is only available on Windows Professional, Education, and Enterprise editions. If your PC is running Windows Home, check out [how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

1. Press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the search box and select the first result that appears.
3. Use the left pane to navigate to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options** .
4. Double-click the **Interactive Logon: Display user information when the session is locked** policy on your right.
5. In the properties window, click the drop-down menu to select the**Do not display user information** option.
6. Click**Apply** followed by**OK** .  
![Hide Email From Windows Login Screen Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-group-policy-editor.jpg)
7. Next, double-click on the**Interactive logon: Do not display last user name** policy from the same section.
8. Select**Enabled** in the properties window.
9. Click**Apply** followed by**OK** to save changes.

## 3\. How to Hide Email Address From Windows Login Screen Using the Registry Editor

 If the above two methods don’t work for some reason, you can make changes to the Windows registry files to hide your email address from the login screen. For that, you’ll need to use the Registry Editor on Windows.

 When it comes to editing Registry files, it's important to be cautious as making incorrect changes can cause irreversible damage to your PC. We recommend you either back up all the registry files or create a restore point before you make any changes. If you need help with that, check our guides on [how to back up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [how to create a restore point in Windows](https://www.makeuseof.com/windows-11-create-restore-point/) .

 Once you’re done with that, use the following steps to hide your email address from the Windows login screen via Registry Editor.

1. Press**Win + X** to open the Power User menu and select**Run** from the list.
2. Type**regedit** in the text box and press**Enter** to open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft > Windows > System** .
5. Right-click on the**System** key and select**New > DWORD (32-bit) Value** .
6. Rename the DWORD to**BlockUserFromShowingAccountDetailsOnSignin** .
7. Double-click on the newly created DWORD and enter**1** in the**Value data** field. Then, click**OK** .  
![Hide Email From Windows Login Screen Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-registry-editor.jpg)

 Exit the Registry Editor and restart your PC for the changes to take effect.

## Hiding Your Email Address From the Windows Login Screen Is Easy

 As we just saw, hiding your personal information from the Windows login screen barely takes a couple of minutes, regardless of the method you employ.


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
<li><a href="https://android-pokemon-go.techidaily.com/how-to-fix-pokemon-go-route-not-working-on-oneplus-12r-drfone-by-drfone-virtual-android/"><u>How to Fix Pokemon Go Route Not Working On OnePlus 12R? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/7-ways-to-fix-the-application-made-too-many-requests-error-0x80860010-on-windows/"><u>7 Ways to Fix the Application Made Too Many Requests Error (0X80860010) on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/asus-zenbook-14-the-windows-mac-battle-continues/"><u>ASUS Zenbook 14: The Windows-Mac Battle Continues</u></a></li>
<li><a href="https://android-location-track.techidaily.com/9-best-phone-monitoring-apps-for-infinix-smart-7-drfone-by-drfone-virtual-android/"><u>9 Best Phone Monitoring Apps for Infinix Smart 7 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/advance-work-efficiency-with-windows-smart-launcher-tool/"><u>Advance Work Efficiency with Windows' Smart Launcher Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/building-your-signature-input-scheme-on-win11/"><u>Building Your Signature Input Scheme on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-quit-notifications-from-roblox-on-your-computer/"><u>Avoiding Quit Notifications From Roblox on Your Computer</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-best-youtube-shorts-video-editor-tools-for-ios-and-android-devices-for-2024/"><u>[New] Best YouTube Shorts Video Editor Tools for iOS & Android Devices for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/can-i-bypass-a-forgotten-phone-password-of-honor-90-lite-by-drfone-android/"><u>Can I Bypass a Forgotten Phone Password Of Honor 90 Lite?</u></a></li>
<li><a href="https://windows11.techidaily.com/1719329062784-overcoming-full-screen-capture-annoyances-with-these-4-strategies/"><u>Overcoming Full-Screen Capture Annoyances with These 4 Strategies</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/1715859915208-new-pinnacle-playtime-the-greatest-action-adventure-game-lineup-ever/"><u>[New] Pinnacle Playtime  The Greatest Action-Adventure Game Lineup Ever!</u></a></li>
<li><a href="https://windows11.techidaily.com/a-practical-manual-for-windowss-pink-flash-dilemnas/"><u>A Practical Manual for Windows's Pink Flash Dilemnas</u></a></li>
<li><a href="https://fake-location.techidaily.com/the-best-8-vpn-hardware-devices-reviewed-on-lenovo-thinkphone-drfone-by-drfone-virtual-android/"><u>The Best 8 VPN Hardware Devices Reviewed On Lenovo ThinkPhone | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-linux-with-windows-technologies-and-features/"><u>Boosting Linux With Windows Technologies and Features</u></a></li>
<li><a href="https://windows11.techidaily.com/changing-onedrive-storage-address-in-windows-10/"><u>Changing OneDrive Storage Address in Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-resetting-video-issue-for-smooth-windows-use/"><u>Addressing Resetting Video Issue for Smooth Windows Use</u></a></li>
<li><a href="https://windows11.techidaily.com/cease-windows-logging-for-app-execution-dates/"><u>Cease Windows' Logging for App Execution Dates</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-pitfalls-of-unknown-not-initialized-disks-on-windows/"><u>Avoiding Pitfalls of Unknown Not Initialized Disks on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-gaps-in-time-remaining-estimates-of-windows-11-laptops/"><u>Addressing Gaps in Time Remaining Estimates of Windows 11 Laptops</u></a></li>
<li><a href="https://windows11.techidaily.com/1719373142604-sidestep-common-snip-and-sketch-screenshot-hurdles-4-fixes/"><u>Sidestep Common Snip & Sketch Screenshot Hurdles: 4 Fixes.</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-remote-classroom-video-archive/"><u>[New] 2024 Approved  Remote Classroom Video Archive</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-activate-and-use-life360-ghost-mode-on-apple-iphone-12-drfone-by-drfone-virtual-ios/"><u>How To Activate and Use Life360 Ghost Mode On Apple iPhone 12 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/clandestine-data-storage-zip-archives-in-image-files-for-windows-enthusiasts/"><u>Clandestine Data Storage: ZIP Archives in Image Files for Windows Enthusiasts</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-your-windows-11-search-with-these-five-essentials/"><u>Boost Your Windows 11 Search with These Five Essentials</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/best-3-samsung-galaxy-xcover-6-pro-tactical-edition-emulator-for-mac-to-run-your-wanted-android-apps-drfone-by-drfone-android/"><u>Best 3 Samsung Galaxy XCover 6 Pro Tactical Edition Emulator for Mac to Run Your Wanted Android Apps | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensive-guide-to-wipeout-ms-audit-reports-on-your-pc/"><u>A Comprehensive Guide to Wipeout MS Audit Reports on Your PC</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-inside-the-world-of-zdsoft-video-capturing/"><u>[New] Inside the World of ZDSoft Video Capturing</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-vagrant-boot-failures-on-win11plusvmware/"><u>Addressing Vagrant Boot Failures on Win11+VMware</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-introducing-10-elusive-instagram-story-visionaries/"><u>[Updated] In 2024, Introducing 10 Elusive Instagram Story Visionaries</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/did-your-iphone-13-passcode-change-itself-unlock-it-now-by-drfone-ios/"><u>Did Your iPhone 13 Passcode Change Itself? Unlock It Now</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-how-you-handle-deleted-items-on-pc/"><u>Adjusting How You Handle Deleted Items on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-troublesome-dism-error-0x800f082f/"><u>Bypassing Windows' Troublesome DISM: Error 0X800F082F</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-10-xiaomi-redmi-note-12-pro-4g-android-sim-unlock-apk-by-drfone-android/"><u>Top 10 Xiaomi Redmi Note 12 Pro 4G Android SIM Unlock APK</u></a></li>
<li><a href="https://windows11.techidaily.com/adapting-to-new-gear-your-powertoys-configuration-guide/"><u>Adapting To New Gear: Your PowerToys Configuration Guide</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/visual-flow-mastery-with-simple-transitions/"><u>Visual Flow Mastery with Simple Transitions</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-amplify-your-voice-on-youtube-mastery-through-tubebuddy/"><u>[New] 2024 Approved  Amplify Your Voice on YouTube - Mastery Through TubeBuddy</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-journey-beyond-the-frantic-crafting-epic-slow-motion-content-for-instragram/"><u>2024 Approved  Journey Beyond the Frantic  Crafting Epic Slow Motion Content for Instragram</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-elevate-your-videos-with-free-sound-effects-a-final-cut-pro-tutorial/"><u>New Elevate Your Videos with Free Sound Effects A Final Cut Pro Tutorial</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-data-from-realme-gt-5-pro-by-fonelab-android-recover-data/"><u>Easy steps to recover deleted data from Realme GT 5 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/augmenting-macos-capabilities-via-windows-applications/"><u>Augmenting macOS Capabilities via Windows Applications</u></a></li>
<li><a href="https://windows11.techidaily.com/5-best-alternatives-for-windows-snipping-efficient-screen-grab-techniques/"><u>5 Best Alternatives for Windows Snipping: Efficient Screen Grab Techniques</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-oneplus-ace-2-pro-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your OnePlus Ace 2 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-slowdowns-in-gpsvc-windows-errors/"><u>Bypassing Slowdowns in GPSVC Windows Errors</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-online-video-rotation-made-easy-top-picks/"><u>In 2024, Online Video Rotation Made Easy Top Picks</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-share-location-in-messenger-on-samsung-galaxy-a15-5g-drfone-by-drfone-virtual-android/"><u>How to Share Location in Messenger On Samsung Galaxy A15 5G? | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-timeless-titans-a-list-of-the-top-10-classic-adventure-games/"><u>[Updated] Timeless Titans  A List of the Top 10 Classic Adventure Games</u></a></li>
</ul></div>
