---
title: Addressing Windows Photos Problem - Package Not Registered
date: 2024-07-11T22:18:20.089Z
updated: 2024-07-12T22:18:20.089Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Windows Photos Problem - Package Not Registered
excerpt: This Article Describes Addressing Windows Photos Problem - Package Not Registered
keywords: Photo Error Fix Windows,Unregistered Photo Issue,Windows Photos Troubleshoot,Resolve Photo Packaging,Correct Photos Package Error,Photo Registration Solve,Fix Photos Not Registering
thumbnail: https://thmb.techidaily.com/6471b67acfe8051c9c2c5b701d3d154a93913c9b510e1febb60299ae780985b8.jpg
---

## Addressing Windows Photos Problem - Package Not Registered

 Microsoft Photos is the default image viewer in Windows with which many users open picture files. However, some users can’t open images in Photos because of a “Package could not be registered” error. That issue arises for some Photos users when they try to open JPG or PNG images in that app.

 This is how you can fix the “Package could not be registered” error in Windows 11 and 10.

## 1\. Run the Windows Store Apps Troubleshooter

 Start your error troubleshooting with a troubleshooter for UWP apps on Microsoft Store. Windows Store Apps is a troubleshooter that could identify and resolve an issue with the Photos app. These are the steps for running that troubleshooter in Windows 11:

1. Simultaneously press the**Win + I** keyboard keys to bring up Settings.
2. Click**Troubleshoot** within the**System** tab of Settings.
3. Next, select**Other trouble-shooters** to reach the Windows troubleshooters in Settings.
4. Press the Windows Store Apps troubleshooter’s**Run** button.  
![The troubleshooters in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/other-troubleshooters-in-settings.jpg)
5. Then select to apply fixes suggested by the Windows Store App troubleshooter.  
![The Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-store-apps-troubleshooter.jpg)

 The same troubleshooter is also available within Windows 10’s Settings app. To access it, click the**Update & Security** category and**Troubleshoot** tab. Then you can select**Additional troubleshooters** to bring up the list of troubleshooting tools.

## 2\. Update Photos

 Updating Microsoft Store apps like Photos can fix issues with them. So, try updating Microsoft Photos like this:

1. Click**Start** and select Microsoft Store on that button’s menu.
2. Select Microsoft Store’s**Library** tab.
3. Click**Get updates** to see what apps need updating. MS Store will then automatically download and install an update for Photos if available.  
![The Get updates button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/get-updates-button.jpg)
4. Wait for the Photos app update to finish before closing Microsoft Store.

## 3\. Repair and Reset the Photos Apps

 Repairing or resetting Photos will likely fix the “Package could not be registered” if that app has corrupted files or data. You can select adjacent**Repair** and**Reset** troubleshooting options for Photos within Settings’ Apps & Features tool. To apply this solution, follow the instructions in our guide for [resetting Microsoft Store apps](https://www.makeuseof.com/windows-reset-app/) . Select the**Repair** option first and**Reset** second if necessary.

![The Repair and Reset buttons for Photos](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-repair-reset-buttons.jpg)

## 4\. Run the Deployment Image and System File Checker Tools

 The “Package could not be registered” error can also be due to Windows system file corruption. That much has been confirmed by users who’ve said that running Deployment Image Servicing Management and System File Checker scans fixed this issue on their PCs. You can apply this potential solution by [opening the Command Prompt with admin rights](https://www.makeuseof.com/windows-11-open-command-prompt/) and running these separate DISM and SFC commands:

`DISM.exe /Online /Cleanup-image /Restorehealth`

`sfc /scannow`

 Run the Deployment Image Servicing Management scan command before the System File Checker tool. Leave the Command Prompt open until it shows a Windows Resource Protection message for the SFC scan. If it says Windows Resource Protection repaired files, this resolution might have resolved the “Package could not be registered” error.

## 5\. Reinstall Photos

 If the “Package could not be registered” error persists after applying the resolutions above, you might need to reinstall Photos to fix it. This solution is the most likely one to fix a corrupted Photos app. You can uninstall and reinstall Photos with PowerShell like this:

1. Start PowerShell with a method in our guide to [opening PowerShell as an administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. Then input this command for uninstalling PowerShell and hit**Enter** :  
`Get-AppxPackage Microsoft.Windows.Photos | Remove-AppxPackage`  
![The uninstall Photos command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/remove-photos-command.jpg)
3. To reinstall Photos, input this PowerShell command and press**Enter** :  
`Get-AppxPackage -allusers Microsoft.Windows.Photos | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reinstall Photos app command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reinstall-photos-app.jpg)
4. Restart your PC after reinstalling Photos.

## 6\. Reset Windows

 If you’ve tried all other resolutions suggested here, there could be a deeper Windows issue causing the “Package could not be registered” Photos error. Then a system reset could be needed to remedy that deeper issue. Resetting Windows will refresh the platform’s components and restore it to a default state.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reset-this-pc-tool.jpg)

 This is suggested as a last resort because you’ll need to reinstall third-party software installed before resetting Windows. However, you can select to keep user files such as photos, documents, videos, etc. Our [guide to resetting Windows 10 and 11](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) tells you how to perform a factory reset.

## Open Your Images in Photos Again

 One of the above resolutions will likely resolve the “Package Could not be Registered” error on your Windows 11/10 PC. However, remember there are plenty of third-party app alternatives you can open your images with if that Photos error persists. IrfanView, XnView, and FastStone Image Viewer are among the best Photos alternatives that are freely available.

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
<li><a href="https://on-screen-recording.techidaily.com/in-2024-saving-your-digital-dialogue-a-quick-guide-to-fb-chat-recordings/"><u>In 2024, Saving Your Digital Dialogue  A Quick Guide to FB Chat Recordings</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensible-approach-to-fixing-notepad-non-openness-in-windows/"><u>A Comprehensible Approach to Fixing Notepad Non-Openness in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/harmonize-workflow-setting-active-hours-on-windows-11-for-peace-of-mind/"><u>Harmonize Workflow: Setting Active Hours on Windows 11 for Peace of Mind</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-make-your-retro-games-look-like-they-used-to-with-retroarchs-shaders/"><u>How to Make Your Retro Games Look Like They Used to With RetroArch’s Shaders</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/unleash-your-brands-potential-on-igtv-with-these-top-10-tactics-for-2024/"><u>Unleash Your Brand’s Potential on IGTV with These Top 10 Tactics for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-windows-pe-file-system/"><u>Decoding Windows' PE File System</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-samsung-galaxy-z-flip-5-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset Samsung Galaxy Z Flip 5 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/visualize-resource-consumption-windows-tray-update-guide/"><u>Visualize Resource Consumption: Windows Tray Update Guide</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-becoming-an-active-participant-in-tiktok-lives/"><u>In 2024, Becoming an Active Participant in TikTok Lives</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-bypass-icloud-by-checkra1n-even-from-apple-iphone-6-if-youve-tried-everything-by-drfone-ios/"><u>In 2024, How To Bypass iCloud By Checkra1n Even From Apple iPhone 6 If Youve Tried Everything</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-error-code-963-on-google-play-of-tecno-camon-20-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Error Code 963 on Google Play Of Tecno Camon 20 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/unlock-vivo-y36-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>Unlock Vivo Y36 Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-realme-11-5g-to-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Realme 11 5G To Phone | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-apple-images-not-importing-correctly-on-windows/"><u>Addressing Apple Images Not Importing Correctly on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerating-file-transfers-on-microsoft-store/"><u>Accelerating File Transfers on Microsoft Store</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-ways-to-track-huawei-nova-y71-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Track Huawei Nova Y71 without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/1719293285605-windows-11-woes-re-opening-chrome-made-simple/"><u>Windows 11 Woes: Re-Opening Chrome Made Simple.</u></a></li>
<li><a href="https://windows11.techidaily.com/what-purpose-does-a-directory-like-windows-bt-serve/"><u>What Purpose Does a Directory Like Windows ~BT Serve?</u></a></li>
<li><a href="https://windows11.techidaily.com/faster-task-management-display-in-windows-11-os/"><u>Faster Task Management Display in Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windowsstore-app-folder-hidden-entry-points/"><u>Unveiling WindowsStore App Folder Hidden Entry Points</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/chatcam-video-saver-app-for-2024/"><u>ChatCam Video Saver App for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-notepad-in-w11-with-intelligent-guide/"><u>Enhance Notepad in W11 with Intelligent Guide</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-soundwave-success-adding-audio-to-your-instastory/"><u>[Updated] 2024 Approved  Soundwave Success  Adding Audio to Your InstaStory</u></a></li>
<li><a href="https://windows11.techidaily.com/all-the-paint-3d-keyboard-shortcuts-you-must-know/"><u>All the Paint 3D Keyboard Shortcuts You Must Know</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-photo-wizardry-made-easy-mastering-slideshow-creation-and-spot-repair/"><u>Windows 11'S Photo Wizardry Made Easy: Mastering Slideshow Creation & Spot Repair</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-change-your-apple-iphone-14-plus-apple-id-on-macbook-by-drfone-ios/"><u>In 2024, How To Change Your Apple iPhone 14 Plus Apple ID on MacBook</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-windows-default-no-spotify-autoplay/"><u>Avoid Windows Default: No Spotify Autoplay</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-google-frp-on-infinix-by-drfone-android-unlock-remove-google-frp/"><u>How To Bypass Google FRP on Infinix</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-windows-users-through-system-slumber/"><u>Guiding Windows Users Through System Slumber</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-windows-dism-failure-0x800f082f-quickly/"><u>Eliminating Windows' DISM Failure 0X800F082F Quickly</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-premier-audio-broadcasts-networks-for-2024/"><u>[Updated] Premier Audio Broadcasts Networks for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-your-console-dreams-choose-windows-for-games/"><u>Unlocking Your Console Dreams: Choose Windows for Games</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-the-art-of-bio-storytelling-on-social-media-platforms/"><u>In 2024, The Art of Bio Storytelling on Social Media Platforms</u></a></li>
<li><a href="https://windows11.techidaily.com/ease-into-accessibility-windows-fundamentals-for-novices/"><u>Ease Into Accessibility: Windows Fundamentals for Novices</u></a></li>
<li><a href="https://windows11.techidaily.com/1719261046850-experience-gptclone-at-home-for-free-on-windows/"><u>Experience GPTClone at Home for FREE on Windows</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-easy-steps-on-how-to-create-a-new-apple-id-account-on-apple-iphone-14-pro-drfone-by-drfone-ios/"><u>In 2024, Easy Steps on How To Create a New Apple ID Account On Apple iPhone 14 Pro | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/crafting-quick-cut-channel-sequences-for-2024/"><u>Crafting Quick-Cut Channel Sequences for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/top-10-fixes-for-phone-keep-disconnecting-from-wi-fi-on-tecno-spark-20c-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 10 Fixes for Phone Keep Disconnecting from Wi-Fi On Tecno Spark 20C | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/11-proven-solutions-to-fix-google-play-store-not-working-issue-on-huawei-p60-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Proven Solutions to Fix Google Play Store Not Working Issue on Huawei P60 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-advice-fixing-common-apex-freezes-on-w11/"><u>Expert Advice: Fixing Common Apex Freezes on W11</u></a></li>
<li><a href="https://facebook.techidaily.com/securing-chats-anticipating-facebooks-e2ee-move/"><u>Securing Chats: Anticipating Facebook's E2EE Move</u></a></li>
<li><a href="https://windows11.techidaily.com/curtailing-spontaneous-console-appearance-triggers/"><u>Curtailing Spontaneous Console Appearance Triggers</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-oneplus-nord-3-5g-drfone-by-drfone-virtual-android/"><u>9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On OnePlus Nord 3 5G | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-xiaomi-redmi-k70-pro-to-mac-drfone-by-drfone-android/"><u>In 2024, How to Mirror Xiaomi Redmi K70 Pro to Mac? | Dr.fone</u></a></li>
</ul></div>
