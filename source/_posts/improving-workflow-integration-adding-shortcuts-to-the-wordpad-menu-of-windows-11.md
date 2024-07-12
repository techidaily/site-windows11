---
title: "Improving Workflow Integration: Adding Shortcuts to the WordPad Menu of Windows 11"
date: 2024-07-11T21:31:50.799Z
updated: 2024-07-12T21:31:50.799Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Improving Workflow Integration: Adding Shortcuts to the WordPad Menu of Windows 11"
excerpt: "This Article Describes Improving Workflow Integration: Adding Shortcuts to the WordPad Menu of Windows 11"
keywords: WordPad Widget Shortcuts,Win11 Workflow Efficiency,Shortcuts in Windows 11,Integrating Window's Toolbar,Enhanced Text Editor Menu,Streamline Office Windows Tasks,Optimize WordPad Navigation
thumbnail: https://thmb.techidaily.com/0a7e98a47c507ce4d17e40879eab668bc44ad83b05fd8fefcba56a2f27460108.jpg
---

## Improving Workflow Integration: Adding Shortcuts to the WordPad Menu of Windows 11

 Windows' WordPad app is either a limited word processor or an advanced text editor depending on how you look at it. Unlike Notepad, WordPad is a rich text editor that incorporates formatting and styling options for content. Therefore, it is a preferable alternative to Notepad for opening and editing TXT and RTF files.

 As such, you might want to add WordPad shortcuts to Windows 11’s context menu, so you can quickly access WordPad and open TXT/RTF documents with it. This is how you can set up context menu shortcuts for launching WordPad and opening files in it.

## How to Add a WordPad Shortcut to Windows 11’s Context Menu

 To create WordPad shortcuts on the right-click menu, you’ll need to do a bit of manual registry tweaking. The editing required is relatively straightforward, but you can back up the Windows registry beforehand if preferred. See [how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) if you need help.

You can add a basic WordPad shortcut to the context menu like this:

1. Click inside the**Type here to search** box at the top of Windows 11’s Start menu.
2. Type the keyword**regedit** in the search box to open the Registry Editor (see [how to open the Registry Editor for more methods](https://www.makeuseof.com/windows-11-open-registry-editor/) ).
3. Erase the current location from the Registry Editor’s address bar.
4. Enter this shell key location inside the registry address bar and hit**Return** :  
`Computer\HKEY_CLASSES_ROOT\Directory\Background\shell\`
5. Right-click**shell** in the Registry Editor’s sidebar to select a**New** option.

1. Select**Key** to add a new registry key.  
![The New and Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-new-key-options.jpg)
2. Enter**WordPad** in the text box for the new key.
3. Then right-click the new**WordPad** key and select the**New** \>**Key** options again.
4. Input**command** for the subkey’s title.  
![The WordPad key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-command-subkey.jpg)
5. Select the command key in the sidebar, and then double-click its**(Default)** string.
6. Input this path in the**Value** box:  
`"C:\Program Files\Windows NT\Accessories\wordpad.exe"`
7. Click**OK** to save the value, and exit the Registry Editor.  
![An Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/an-edit-string-window2.jpg)

 Now you can open WordPad from the desktop context menu in Windows 11\. Right-click anywhere on the desktop background and select**Show more options** to access the classic menu. Selecting the new**WordPad** option on that menu will open the app’s window.

![The WordPad context menu shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-wordpad-shortcut.jpg)

## How to Add an Open with WordPad Shortcut to Windows 11’s Context Menu

 The basic WordPad shortcut launches the app, but you’ll need to open documents from its**File** tab manually. Instead, you can add a second context menu option for opening files with WordPad. That right-click option will provide a shortcut for opening documents in WordPad directly from File Explorer. This is how to add an**Open with WordPad** option to the context menu:

1. Open Registry Editor as outlined in the first three steps for adding a WordPad shortcut to the context menu.
2. Then clear out the address bar, and input this location path there:  
`HKEY_CLASSES_ROOT\*\shell`
3. Next, click the**shell** key with the right mouse button and select**New** .
4. Click the**Key** option for adding new registry entries.
5. Input**Open with WordPad** for the new key’s title.
6. Right-click**Open with Wordpad** and select**New** \>**Key** to add a subkey.
7. Type**command** in the text box for the subkey.  
![The Open with WordPad key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-with-wordpad-key.jpg)
8. Double-click the**(Default)** string for the new command subkey you just added.
9. Enter**wordpad.exe %1** in the**Value** box, and click**OK** to apply.  
![The wordpad.exe value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-wordpad-exe-value-data.jpg)

 Now you can close the Registry Editor and try out the**Open with WordPad** context menu shortcut. Launch File Explorer (see [how to launch File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) ), and navigate to a folder containing some TXT or RTF files. Right-click an RTF or TXT document and select**Show more options** . Click**Open with WordPad** to bring up the right-clicked document in that app.

## How to Erase the WordPad Context Menu Shortcuts

 If you ever change your mind about having WordPad context menu options, you can remove them by deleting their keys. To do so, you’ll need to open the following key locations in the Registry Editor:

`Computer\HKEY_CLASSES_ROOT\*\shell\Open with WordPad\command  
Computer\HKEY_CLASSES_ROOT\Directory\Background\shell\WordPad\command`

 Then right-click the**Open with WordPad** or**WordPad** key to select a**Delete** option. A dialogue box will open requesting confirmation to erase. Select**Yes** if you’re sure about deleting the key.

![The Delete option for registry keys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-delete-option2.jpg)

## Make the Most of Your WordPad Context Menu Shortcuts

 So, why add Notepad to Windows 11’s context menu when you set up WordPad shortcuts on it instead? Such shortcuts will give you direct access to a somewhat overlooked and underrated advanced text editor that can handle documents with images in them. You can utilize WordPad as a lightweight document viewer for looking at and even editing ODT, DOCX, TXT, and RTF files.

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
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-exploring-audible-wilderness-wolves-in-vocal-display/"><u>New 2024 Approved Exploring Audible Wilderness Wolves in Vocal Display</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-transform-your-videos-on-demand-freedom-through-editing-android-edition/"><u>2024 Approved  Transform Your Videos on Demand  Freedom Through Editing, Android Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-microsoft-store-glitches-error-x80072f17-guide/"><u>Correcting Microsoft Store Glitches: Error X80072F17 Guide</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-learn-to-cut-out-the-unwanted-a-guide-to-erasing-background/"><u>[New] Learn to Cut Out the Unwanted  A Guide to Erasing Background</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-windows-task-error-0x8007000f-quickly/"><u>Correcting Windows Task Error 0X8007000F Quickly</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/esizing-google-trends-insights-for-videography-ideas/"><u>Synthesizing Google Trends Insights for Videography Ideas</u></a></li>
<li><a href="https://windows11.techidaily.com/experts-selection-7-best-windows-photos-apps-reviewed/"><u>Expert's Selection: 7 Best Windows Photos Apps Reviewed</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-navigating-the-soundscape-downloading-and-instaling-vrecorder/"><u>[New] 2024 Approved  Navigating the Soundscape  Downloading and Instaling VRecorder</u></a></li>
<li><a href="https://windows11.techidaily.com/converting-ical-data-for-smooth-windows-11-use/"><u>Converting iCal Data for Smooth Windows 11 Use</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-online-orbiters-youtube-personalities-at-the-zenith/"><u>2024 Approved  Online Orbiters  YouTube Personalities at the Zenith</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-productivity-essential-win11-and-command-tips-for-efficiency/"><u>Elevate Productivity: Essential Win11 and Command Tips for Efficiency</u></a></li>
<li><a href="https://windows11.techidaily.com/simplify-and-beautify-your-w11-desktop-with-ease/"><u>Simplify & Beautify Your W11 Desktop with Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/ditch-the-dated-wallpapers-triple-technique-trick/"><u>Ditch the Dated Wallpapers: Triple Technique Trick</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-the-blueprint-to-a-stellar-tiktok-promotion-strategy/"><u>[Updated] In 2024, The Blueprint to a Stellar TikTok Promotion Strategy</u></a></li>
<li><a href="https://windows11.techidaily.com/identifying-superior-video-encoders-for-windows-computing/"><u>Identifying Superior Video Encoders for Windows Computing</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-joke-jingles-top-online-ringtone-sources/"><u>2024 Approved  Joke Jingles  Top Online Ringtone Sources</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-from-global-reach-to-engagement-deciphering-igtv-and-youtubes-strategies/"><u>2024 Approved  From Global Reach to Engagement  Deciphering IGTV & YouTube’s Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/from-raw-esd-to-refined-iso-windows-conversion-techniques/"><u>From Raw ESD to Refined ISO: Windows Conversion Techniques</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-2024-approved-best-way-to-freeze-frame-in-final-cut-pro/"><u>Updated 2024 Approved Best Way to Freeze-Frame in Final Cut Pro</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-efficient-use-of-slug-lines-in-content-writing/"><u>2024 Approved  The Efficient Use of Slug Lines in Content Writing</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-for-invisible-login-window-in-win1011/"><u>Quick Fix for Invisible Login Window in Win10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-c0000005-crashes-on-windows-systems/"><u>Combatting C0000005 Crashes on Windows Systems</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-essential-recording-software-for-engaging-online-gatherings-google-meet/"><u>In 2024, Essential Recording Software for Engaging Online Gatherings (Google Meet)</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-innovative-design-and-graphics-free-and-affordable-sources/"><u>[Updated] Innovative Design and Graphics  Free & Affordable Sources</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/disabled-apple-iphone-11-pro-max-how-to-unlock-a-disabled-apple-iphone-11-pro-max-drfone-by-drfone-ios/"><u>Disabled Apple iPhone 11 Pro Max How to Unlock a Disabled Apple iPhone 11 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-functional-link-to-mb-services-on-win11-devices/"><u>Restoring Functional Link to MB Services on Win11 Devices</u></a></li>
<li><a href="https://extra-tips.techidaily.com/1716361790420-twitch-vs-youtube-an-in-depth-comparative-analysis/"><u>Twitch vs YouTube  An In-Depth Comparative Analysis</u></a></li>
<li><a href="https://windows11.techidaily.com/slashing-gpu-energy-on-desktop-window-manager/"><u>Slashing GPU Energy on Desktop Window Manager</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/engage-your-audience-discover-the-top-5-tiktok-caption-styles/"><u>Engage Your Audience  Discover the Top 5 TikTok Caption Styles</u></a></li>
<li><a href="https://windows11.techidaily.com/from-vocal-inputs-to-text-output-a-comprehensible-guide-for-windows-users/"><u>From Vocal Inputs to Text Output: A Comprehensible Guide for Windows Users</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-videopad-video-editor-review-a-closer-look-at-its-capabilities-and-limitations/"><u>2024 Approved Videopad Video Editor Review A Closer Look at Its Capabilities and Limitations</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-save-your-android-and-mac-snapchat-footage-effectively/"><u>[New] In 2024, Save Your Android & Mac Snapchat Footage Effectively</u></a></li>
<li><a href="https://windows11.techidaily.com/method-to-rectify-the-zero-x-error-on-windows-11s-mail-app/"><u>Method to Rectify the Zero X Error on Windows 11’S Mail App</u></a></li>
<li><a href="https://windows11.techidaily.com/declutter-your-disk-space-auto-deletion-settings-for-windows-11/"><u>Declutter Your Disk Space: Auto-Deletion Settings for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/sky-high-internet-beyond-100mbps-overcoming-windows-speed-ceiling/"><u>Sky-High Internet Beyond 100Mbps: Overcoming Windows' Speed Ceiling</u></a></li>
<li><a href="https://windows11.techidaily.com/deciding-on-the-best-nvidia-driver-type/"><u>Deciding on the Best Nvidia Driver Type</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-steps-for-finding-absent-registry-program/"><u>Immediate Steps for Finding Absent Registry Program</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-unwanted-tiktok-reset-regain-access-and-videos/"><u>[Updated] 2024 Approved  Unwanted TikTok Reset – Regain Access and Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-to-windows-ease-of-access-in-5-steps/"><u>Navigating to Windows Ease of Access in 5 Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-setup-of-microsofts-powertoys-win11/"><u>Effortless Setup of Microsoft's PowerToys (Win11)</u></a></li>
<li><a href="https://windows11.techidaily.com/master-your-gaming-journey-optimizing-ps1-experience-in-win-using-duckstations-guide/"><u>Master Your Gaming Journey: Optimizing PS1 Experience in WIN Using Duckstation's Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/shrouding-outage-with-code-0xc00d36b4-in-windows/"><u>Shrouding Outage with Code 0XC00D36B4 in Windows</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/old-hollywood-techniques-for-modern-filmmakers-for-2024/"><u>Old Hollywood Techniques for Modern Filmmakers for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-solutions-for-error-0x80042306-during-system-restore/"><u>Expert Solutions for Error 0X80042306 During System Restore</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-powerpoint-supported-video-format-and-user-tips-for-2024/"><u>Updated Powerpoint Supported Video Format and User Tips for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/getting-ahead-with-vivetool-on-windows-future-features/"><u>Getting Ahead with ViVeTool on Windows: Future Features</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/ipogo-will-be-the-new-ispoofer-on-tecno-pova-6-pro-5g-drfone-by-drfone-virtual-android/"><u>iPogo will be the new iSpoofer On Tecno Pova 6 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-alt-key-code-issues-in-windows-systems/"><u>Solving ALT Key Code Issues in Windows Systems</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-use-pokemon-go-joystick-on-tecno-spark-20c-drfone-by-drfone-virtual-android/"><u>How to use Pokemon Go Joystick on Tecno Spark 20C? | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/instagram-illumination-best-covered-ig-highlights-on-the-move/"><u>Instagram Illumination  Best-Covered IG Highlights on the Move</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-pro-tips-uncovering-12-prime-websites-for-affordable-images/"><u>[Updated] Pro Tips  Uncovering 12 Prime Websites for Affordable Images</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-an-attempt-was-made-to-reference-a-token-error-in-windows-1110/"><u>How to Fix the “An Attempt Was Made to Reference a Token” Error in Windows 11/10</u></a></li>
<li><a href="https://windows11.techidaily.com/integrating-image-browsing-into-file-explorer/"><u>Integrating Image Browsing Into File Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-restart-and-streamline-windows-update-processes/"><u>How to Restart and Streamline Windows Update Processes</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/learn-to-quickly-cut-videos-using-built-in-windows-features-for-2024/"><u>Learn to Quickly Cut Videos Using Built-In Windows Features for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-from-zero-to-hero-steps-to-construct-your-channels-backlinks/"><u>2024 Approved  From Zero to Hero  Steps to Construct Your Channel's Backlinks</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/quick-refresher-green-screen-film-tech-basics-for-2024/"><u>Quick Refresher  Green Screen Film Tech Basics for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/reignite-your-windows-11-search-top-11-fixes-here/"><u>Reignite Your Windows 11 Search: Top 11 Fixes Here</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-address-geforce-nows-error-code-xc0f1103f/"><u>How To Address GeForce Now's Error Code Xc0f1103f</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-a-step-by-step-guide-to-elevate-your-stream-on-youtube/"><u>2024 Approved  A Step-by-Step Guide to Elevate Your Stream on YouTube</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-formulating-final-fact-finding-flourishes/"><u>2024 Approved  Formulating Final Fact-Finding Flourishes</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/mi-11-mini-your-gateway-to-professional-screen-recording/"><u>Mi 11 Mini  Your Gateway to Professional Screen Recording</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-iconic-highlights-from-the-2022-figure-skate-world/"><u>In 2024, Iconic Highlights From the 2022 Figure Skate World</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-the-frustrations-of-code-1132-on-win-1011/"><u>Resolving the Frustrations of Code 1132 on Win 10/11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-without-backup-on-meizu-21-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to recover deleted photos from Android Gallery without backup on Meizu 21</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-windows-0xfffffff-confusion-quick-fixes/"><u>Clearing Windows' 0XFFFFFFF Confusion: Quick Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-barriers-in-superuser-command-activation/"><u>Overcoming Barriers in Superuser Command Activation</u></a></li>
<li><a href="https://android-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-from-poco-x6-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock from Poco X6 Phones with/without a PC</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-solutions-to-the-display-startup-failure-issue/"><u>Effective Solutions to the “Display Startup Failure” Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-restoring-bluetooth-visibility-win/"><u>Steps for Restoring Bluetooth Visibility WIN</u></a></li>
<li><a href="https://windows11.techidaily.com/shedding-windows-history-lightly-with-these-triads/"><u>Shedding Windows History Lightly with These Triads</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-top-animals-in-play-essential-android-titles-reviewed/"><u>[Updated] 2024 Approved  Top Animals in Play  Essential Android Titles Reviewed</u></a></li>
<li><a href="https://windows11.techidaily.com/direct-access-linux-forget-wsl/"><u>Direct Access: Linux, Forget WSL</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-in-2024-top-10-freely-accessible-tiktok-video-editing-tools-compatible-with-mac/"><u>[Updated] In 2024, Top 10 Freely Accessible TikTok Video Editing Tools Compatible with Mac</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-file-error-puzzle-finding-solution-for-0x80070570-on-windows-11/"><u>Decoding the File Error Puzzle - Finding Solution for 0X80070570 on Windows 11</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-tracing-back-rooms-filled-with-angry-pooch-barks/"><u>Updated Tracing Back Rooms Filled With Angry Pooch Barks</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-lexis-audio-mastery-101-an-entry-level-editors-primer-for-2024/"><u>Updated Lexis Audio Mastery 101 An Entry-Level Editors Primer for 2024</u></a></li>
</ul></div>
