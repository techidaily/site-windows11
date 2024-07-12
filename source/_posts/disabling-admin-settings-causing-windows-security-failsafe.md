---
title: Disabling Admin Settings Causing Windows Security Failsafe
date: 2024-07-11T22:22:13.728Z
updated: 2024-07-12T22:22:13.728Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Disabling Admin Settings Causing Windows Security Failsafe
excerpt: This Article Describes Disabling Admin Settings Causing Windows Security Failsafe
keywords: Disable Admin Features,Windows Security Lockdown,Safe Mode Failure,Admin Privilege Halt,Windows Protection Errors,Secure Settings Suspension,System Safeguard Issues
thumbnail: https://thmb.techidaily.com/177db7c45381f8f94f304fef5764a3ae21d49762f0d50b119bc79b8987d4ee6b.jpg
---

## Disabling Admin Settings Causing Windows Security Failsafe

 Some users have reported they can’t set Windows Security options because of an error that says, “This setting is managed by your administrator.” Those users see that error message just above options within the**Virus & threat protection** and**App & browser tabs** of that app. Consequently, they can’t turn on important Windows Security settings there that are grayed out and disabled.

 That issue has little to do with admin rights. Many users who encounter the issue are already utilizing Windows administrator accounts. This is how you can fix the “setting is managed by your administrator” error in Windows 11.

## 1\. Check for and Install Available Windows 11 Updates

 Although not the most likely potential solution, some users have said installing available Windows 11 updates helped them resolve this error. Patchers for Windows 11 usually address Windows bugs reported by users.

 If you're not sure how to do this, visit [how to install Windows 11 updates](https://www.makeuseof.com/windows-11-install-updates/) for a step-by-step guide.

## 2\. Reset the Windows Security and Settings Apps

 Users who’ve fixed the “setting is managed by your administrator” error have confirmed resetting the Windows Security and Settings apps can work. Resetting those apps will clear their data. You can reset Windows Security via Settings, as outlined in our [how to reset apps on Windows](https://www.makeuseof.com/windows-reset-app/) guide.

![The Reset button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reset-option.jpg)

 To reset Settings, you must open the Start menu and right-click the app’s shortcut. Select**App settings** to bring up some troubleshooting options for it. Then select the**Reset** troubleshooting option for the app.

## 3\. Uninstall Third-Party Antivirus Software

 Some third-party antivirus utilities can disable Windows Security features they effectively replace. If you’ve installed an overlapping third-party antivirus product, uninstalling it may resolve Windows Security’s administrator error. Uninstall antivirus software with a method within our guide on [how to remove Windows programs](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) to see if that resolves the issue.

![The uninstaller tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-uninstaller-tool.jpg)

 Should this solution work, the issue will likely reoccur if you reinstall the same third-party antivirus virus software. Then you would have to choose between using the third-party antivirus utility or Windows Security.

## 4\. Edit the Registry

 Many users have been able to fix the Windows Security administrator error by applying this confirmed registry solution. This registry tweak involves modifying a DWORD value, but you don’t need to delete any key. To apply this potential resolution, edit the registry like this:

1. Run the Windows Registry Editor app, which you can open with any method included in our [how to open Regedit](https://www.makeuseof.com/windows-11-open-registry-editor/) [g](https://www.makeuseof.com/windows-11-open-registry-editor/) uide.
2. Click inside the address box at the top of Registry Editor and erase the text in it.
3. Input this key path in the registry address bar and press**Return** :  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\DeviceGuard\Scenarios\HypervisorEnforcedCodeIntegrity`
4. Then double-click the**Enabled** DWORD within the**HypervisorEnforcedCodeIntegrity** key.  
![The HypervisorEnforced registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-hypervisor-key.jpg)
5. Clear the**Data value** box, and then input**0** there.
6. Select**OK** to set the**Enabled** DWORD’s value.  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/edit-dword-window.jpg)
7. Exit Registry Editor and click the**Power** \>**Restart** Start menu options.

## 5\. Set Group Policy’s Real-time Protection Settings to "Not Configured"

 A possibility for Windows 11 Pro and Enterprise users to consider is that Group Policy Editor could be blocking changes to Windows Security settings. If you can open Group Policy Editor on your PC, check real-time protection policy settings aren’t enabled there. This is how you can set real-time protection settings to not configured in Group Policy Editor:

1. Find Group Policy Editor by clicking the search magnifying glass icon and inputting**gpedit.msc** .
2. Select**gpedit.msc** to open the Group Policy Editor window.
3. Then select**Computer Configuration** to extend that category.
4. Double-click**Administrative Template** to access several setting categories.
5. Next, double-click**Windows Components** \>**Microsoft Defender Antivirus** \>**Real-time Protection** in the navigation sidebar.  
![The Real-time Protection policy settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-real-time-protection-policy-settings.jpg)
6. Double-click any policy setting that’s with an enabled state.
7. Then select the**Not configured radio** button.  
![The Not Configured radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/not-configured-option.jpg)
8. Click**Apply** \>**OK** in the window to set the change.
9. Repeat the previous three steps for all real-time protection policies set to enabled.

## 6\. Reinstall Windows Security

 You can’t reinstall Windows Security by uninstalling that app via Settings and downloading it from Microsoft Store. However, you can run a more general PowerShell command that reinstalls all apps pre-installed with Windows 11\. Try reinstalling Windows Security with that command as follows:

1. Open PowerShell with administrative rights. Our guide on [how to open PowerShell](https://www.makeuseof.com/windows-11-powershell-administrator/) includes various methods for opening that app.
2. Then input the following PowerShell command for reinstalling apps:  
`Get-AppXPackage -AllUsers | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reinstall app PowerShell command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reinstall-app-command.jpg)
3. Press**Enter** and wait for the command to finish.
4. Restart your laptop or desktop from the Start menu.

## 7\. Reinstall Windows 11 With the Media Creation Tool

 Reinstalling Windows 11 by downloading an ISO with Media Creation Tool is a drastic potential solution. However, users have confirmed updating Windows 11 in such a way works for fixing this error. Furthermore, you can select to preserve apps and files when reinstalling. This is how to reinstall Windows 11:

1. Download the latest Windows 11 ISO with the Media Creation Tool. Our guide on [how to download a Windows 11 ISO](https://www.makeuseof.com/windows-11-download-iso/) includes step-by-step instructions for how to do so.
2. Then double-click your downloaded Windows 11 ISO file.
3. Click**setup.exe** to open the Windows 11 installer.  
![The Windows 11 Setup window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-setup-window.jpg)
4. Select**Next** to initiate a system check.
5. Press the**Accept** button for the license terms.
6. The**Keep personal files and apps** option will probably be set by default at the ready-to-install stage. However, you click**Change what to keep** to make sure the**Keep personal files and apps** option is selected.  
![The Keep personal files and apps radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/keep-personal-files-option.jpg)
7. Then select**Next** to proceed to the last step.
8. Click**Install** to reinstall Windows 11.

## Change Windows Security’s Settings Again

 Those are the most widely cited ways to fix the “setting is managed by your administrator” error in Windows 11\. So, applying those potential resolutions will probably resolve the “setting is managed by your administrator” issue on your PC. Then you’ll be able to set all the options within Windows Security as required.

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
<li><a href="https://graphic-issues.techidaily.com/bad-video-card-drivers-crash-minecraft-on-windows-solved/"><u>Bad Video Card Drivers Crash Minecraft on Windows [Solved]</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/evaluation-report-elite-parrot-ar-drone-20-for-2024/"><u>Evaluation Report  Elite Parrot AR Drone 2.0 for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-classic-visuals-a-guide-to-shader-magic-in-retroarc/"><u>Crafting Classic Visuals: A Guide to Shader Magic in RetroArc</u></a></li>
<li><a href="https://windows11.techidaily.com/detailed-steps-to-fully-remove-wsl/"><u>Detailed Steps to Fully Remove WSL</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-honor-play-40c-get-deleted-phone-number-back-with-ease-and-safety-by-fonelab-android-recover-contacts/"><u>How to Honor Play 40C Get Deleted Phone Number Back with Ease and Safety</u></a></li>
<li><a href="https://windows11.techidaily.com/discovering-surface-laptop-studio-2-near-flawless-for-makers/"><u>Discovering Surface Laptop Studio 2: Near-Flawless for Makers</u></a></li>
<li><a href="https://windows11.techidaily.com/decode-subtitle-failures-in-prime-windows-11-collaboration/"><u>Decode Subtitle Failures in Prime, Windows 11 Collaboration</u></a></li>
<li><a href="https://windows11.techidaily.com/deletion-directives-for-software-in-windows-11-the-quick-way-116-chars/"><u>Deletion Directives for Software in Windows 11: The Quick Way (116 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/creating-custom-volume-control-commands-for-windows-11-users/"><u>Creating Custom Volume Control Commands for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/directing-biometric-access-control-for-windows-11-users/"><u>Directing Biometric Access Control for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/uniting-gmail-and-outlook-windows-setup-walkthrough/"><u>Uniting Gmail and Outlook: Windows Setup Walkthrough</u></a></li>
<li><a href="https://windows11.techidaily.com/diving-into-windows-n-types-benefits-and-downfalls/"><u>Diving Into Windows N Types: Benefits and Downfalls</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-advanced-gopro-editing-straightening-fisheye-lens/"><u>[Updated] Advanced GoPro Editing  Straightening Fisheye Lens</u></a></li>
<li><a href="https://windows11.techidaily.com/disable-windows-tracked-application-usage/"><u>Disable Windows' Tracked Application Usage</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/all-about-factory-reset-what-is-it-and-what-it-does-to-your-oppo-reno-11-5g-drfone-by-drfone-reset-android-reset-android/"><u>All About Factory Reset, What Is It and What It Does to Your Oppo Reno 11 5G? | Dr.fone</u></a></li>
<li><a href="https://ai-video.techidaily.com/updated-in-2024-translate-video-from-japanese-to-english-online-for-free/"><u>updated In 2024, Translate Video From Japanese to English Online for Free</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-incompatible-drivers-on-windows-11/"><u>Correcting Incompatible Drivers on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-reducing-browsing-impact-on-system-performance/"><u>Tips for Reducing Browsing Impact on System Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-dism-your-ultimate-toolkit-for-fixing-win11/"><u>Decoding DISM: Your Ultimate Toolkit for Fixing Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/turning-on-hyper-v-simplified-your-win11-how-to/"><u>Turning On Hyper-V Simplified - Your Win11 How-To</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-the-stop-motion-encyclopedia-from-studio-to-alternative-solutions/"><u>New In 2024, The Stop Motion Encyclopedia From Studio to Alternative Solutions</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-learn-to-record-professional-quality-audio-in-audacity-macos/"><u>[Updated] Learn to Record Professional Quality Audio in Audacity, MacOS</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-crash-reports-for-flawless-hardware-repairs/"><u>Decoding Crash Reports for Flawless Hardware Repairs</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-enable-usb-debugging-on-a-locked-poco-m6-5g-phone-by-drfone-android/"><u>How To Enable USB Debugging on a Locked Poco M6 5G Phone</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-the-purpose-of-pagefilesys-within-os-structure/"><u>Dissecting the Purpose of Pagefile.sys Within OS Structure</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-and-correcting-irq-glitches/"><u>Deciphering and Correcting IRQ Glitches</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-capturing-moving-images-mirrorless-versus-dslr/"><u>[New] 2024 Approved  Capturing Moving Images  Mirrorless Versus DSLR</u></a></li>
<li><a href="https://windows11.techidaily.com/ultimate-bundle-premier-cost-free-windows-11-assistants/"><u>Ultimate Bundle: Premier Cost-Free Windows 11 Assistants</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-s-best-mkv-editors-for-mac-trimming-made-easy-for-2024/"><u>Updated S Best MKV Editors for Mac Trimming Made Easy for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/create-a-gratis-local-gptclone-with-gpt4all-for-windows/"><u>Create a Gratis, Local GPTClone with GPT4All for Windows</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-software-to-fix-and-repair-corrupt-mp4movavi-video-files-of-vivo-y02t-by-stellar-video-repair-mobile-video-repair/"><u>Best software to Fix and Repair Corrupt MP4,MOV,AVI video files of Vivo Y02T</u></a></li>
<li><a href="https://windows11.techidaily.com/declutter-data-step-by-step-hdd-defrag-for-win11/"><u>Declutter Data: Step-by-Step HDD Defrag for Win11</u></a></li>
<li><a href="https://discord-videos.techidaily.com/how-to-add-roles-in-discord-for-2024/"><u>How to Add Roles in Discord for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/secrets-to-a-flawless-ps3-gameplay-record/"><u>Secrets to a Flawless PS3 Gameplay Record</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-the-art-of-instagram-live-broadcasting-made-simple-via-obs-for-2024/"><u>[New] The Art of Instagram Live Broadcasting Made Simple via OBS for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-alternative-film-choices-ranked-7-1/"><u>[Updated] In 2024, Alternative Film Choices  Ranked #7-1</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-imagesegment-scrutiny-review-for-2024/"><u>[Updated] ImageSegment Scrutiny Review for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/digital-revolution-at-your-fingertips-master-paint-updates/"><u>Digital Revolution at Your Fingertips - Master Paint Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/data-mastery-for-pcs-uncovering-5-top-notch-fileshare-tools/"><u>Data Mastery for PCs: Uncovering 5 Top-Notch Fileshare Tools</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-elite-audio-file-converter-free-conversion-of-professional-mpa-soundtracks-to-standardized-mp3-format/"><u>In 2024, Elite Audio File Converter Free Conversion of Professional MPA Soundtracks to Standardized MP3 Format</u></a></li>
<li><a href="https://windows11.techidaily.com/curing-white-screen-problems-on-store-platform/"><u>Curing White Screen Problems on Store Platform</u></a></li>
<li><a href="https://windows11.techidaily.com/clear-communication-test-your-mic-on-pc/"><u>Clear Communication: Test Your Mic on PC</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-mellow-moves-discover-top-20-serene-country-songs-for-groovy-dancing-tiktok/"><u>[Updated] In 2024, Mellow Moves  Discover Top 20 Serene Country Songs for Groovy Dancing (TikTok)</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-acclaimed-discord-screen-capture-apps-reviewed/"><u>[New] Acclaimed Discord Screen Capture Apps Reviewed</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-optimal-sonic-selections-android-centric/"><u>2024 Approved  Optimal Sonic Selections, Android-Centric</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-how-to-combine-multiple-videos-into-one-on-instagram/"><u>Updated How to Combine Multiple Videos Into One on Instagram</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-the-path-fixing-windows-11-writable-errors/"><u>Clearing the Path: Fixing Windows 11' Writable Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/decode-and-dissolve-rectifying-win11-webcam-issue-error-a00f4289/"><u>Decode & Dissolve: Rectifying Win11 Webcam Issue - Error A00F4289</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-back-to-basic/"><u>2024 Approved Back to Basic</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensible-guide-to-revoking-custom-search-on-windows-11/"><u>Comprehensible Guide to Revoking Custom Search on Windows 11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/streamsavvy-beyond-the-dacast-boundary-for-2024/"><u>StreamSavvy  Beyond the DaCast Boundary for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-another-program-uses-device-in-windows-sound-system/"><u>Correcting 'Another Program Uses Device' In Windows Sound System</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-3-innovative-methods-for-large-head-effects-in-tiktok-videos/"><u>[New] 2024 Approved  3 Innovative Methods for Large Head Effects in TikTok Videos</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/peak-level-hd-capture-best-screen-recorder-innovations-unveiled/"><u>Peak-Level HD Capture  Best Screen Recorder Innovations Unveiled</u></a></li>
<li><a href="https://extra-resources.techidaily.com/utilizing-zoom-to-upgrade-tiktok-video-aesthetics/"><u>Utilizing Zoom to Upgrade TikTok Video Aesthetics</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/strategic-planning-making-memorable-tiktok-videos/"><u>Strategic Planning  Making Memorable TikTok Videos</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-from-capture-to-sharing-fb-video-uploads-via-pc-plus-android/"><u>[New] 2024 Approved  From Capture to Sharing  FB Video Uploads via PC + Android</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-fatal-component-error-in-win10win11-system/"><u>Disabling Fatal Component Error in Win10/Win11 System</u></a></li>
<li><a href="https://windows11.techidaily.com/compreran-gaming-hurdles-enhance-gamesplay-on-windows/"><u>Compreran Gaming Hurdles: Enhance Gamesplay on Windows</u></a></li>
<li><a href="https://article-helps.techidaily.com/in-2024-metaverse-reflections-a-pioneering-collection-of-thoughts/"><u>In 2024, Metaverse Reflections  A Pioneering Collection of Thoughts</u></a></li>
<li><a href="https://youtube-web.techidaily.com/approved-an-owners-guide-to-playlist-permutations-in-yt/"><u>2024 Approved  An Owner's Guide to Playlist Permutations in YT</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-windows-audio-graph-isolation/"><u>Decoding Windows Audio Graph Isolation</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/in-2024-while-fiddling-with-solutions-to-complement-the-ordinary-text-messages-with-graphic-elements-people-also-ask-about-ways-to-add-emoji-to-photo-online/"><u>In 2024, While Fiddling with Solutions to Complement the Ordinary Text Messages with Graphic Elements, People Also Ask About Ways to Add Emoji to Photo Online. Stay Here to Get the Best Answers</u></a></li>
<li><a href="https://windows11.techidaily.com/concealed-compression-stashing-archives-in-windows-picture-files/"><u>Concealed Compression: Stashing Archives in Windows Picture Files</u></a></li>
<li><a href="https://windows11.techidaily.com/diagnosing-and-fixing-microsoft-windows-nearby-share-malfunction/"><u>Diagnosing and Fixing Microsoft Windows Nearby Share Malfunction</u></a></li>
<li><a href="https://windows11.techidaily.com/the-uncharted-territory-windows-11-and-the-future-of-ai/"><u>The Uncharted Territory: Windows 11 and the Future of AI</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-interval-for-automatic-logoff/"><u>Customizing Interval for Automatic Logoff</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-best-performers-top-10-innovative-4k-mirrorless-models/"><u>[New] Best Performers  Top 10 Innovative 4K Mirrorless Models</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-honor-x7b-to-laptop-without-usb-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos from Honor X7b to Laptop Without USB | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-network-analysis-on-windows-11-the-netstat-command-guide/"><u>Conquer Network Analysis on Windows 11: The Netstat Command Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/command-line-tip-disable-amdnvidia-gpu-enhancements/"><u>Command Line Tip: Disable AMD/Nvidia GPU Enhancements</u></a></li>
<li><a href="https://youtube-web.techidaily.com/el-transformation-unleash-potential-with-tubebuddy-for-2024/"><u>Channel Transformation  Unleash Potential with TubeBuddy for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-all-you-need-to-know-about-instagram-video-limits/"><u>2024 Approved  All You Need to Know About Instagram Video Limits</u></a></li>
</ul></div>
