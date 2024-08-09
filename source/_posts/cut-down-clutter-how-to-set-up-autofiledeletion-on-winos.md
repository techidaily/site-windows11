---
title: "Cut Down Clutter: How to Set Up AutoFileDeletion on WINOS"
date: 2024-08-08T05:58:13.374Z
updated: 2024-08-09T05:58:13.374Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Cut Down Clutter: How to Set Up AutoFileDeletion on WINOS"
excerpt: "This Article Describes Cut Down Clutter: How to Set Up AutoFileDeletion on WINOS"
keywords: Clutter Reduction Tips,AutoFileManagement Windows,Deletion Schedule Setting,WINOS Organization Tricks,Simplify File Management,Automatic Deleted Files,Digital Decluttering Techniques
thumbnail: https://thmb.techidaily.com/e3528d506823cb6dca25eee03d51754fbb17fe96f4d59ce559e11e5be6c55331.jpg
---

## Cut Down Clutter: How to Set Up AutoFileDeletion on WINOS

 For many, a cluttered desktop and downloads folder is just a way of life—no matter how hard you try, they somehow always ends up disorganized. Need to do a bit of digital spring-cleaning? Fortunately, there are lots of ways you can keep your Windows 10 computer decluttered.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.

## 1\. Auto-Delete Old Files or Folders Using Storage Settings

 The Settings menu lets you do and manage a lot of stuff on your Windows computer. From updates to tweaking the Windows appearance—you can do almost everything. It's no surprise then that you can also use it for setting up an auto-deletion setting on your Windows. Here's how:

![storage settings on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/storage-settings-on-windows.jpg)

1. Go to **Settings > System > Storage**.
2. Toggle on the **Storage Sense** feature.
3. Then, click **Configure Storage Sense or run it now**.
4. Under **Temporary Files**, set up your desired time frames fore deleting files in the recycle bin and files in your Downloads folder.  
![storage sense in windows settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/storage-sense-in-windows-settings.jpg)

 Not all files in the Downloads folder will be deleted after the set time; just those that haven't been opened. This means if you download a file and want to open it later, it will still be deleted after the set time. If you turn this setting on, you should move anything out of the Downloads folder that you intend to keep.

 If you want, you can always turn off the setting by simply disabling the **Storage Sense** button later on.

<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
## 2\. Deleted Old Files or Folders With the Command Prompt

 Like most things on Windows, you can use the Command Prompt here as well. A replacement for the easy pin-and-point graphical user interface, the Command Prompt works with simple text-based commands to help you perform different admin functions and fix various troubleshooting issues on Windows.

 Here's how you can use it to fix your storage issues via the _ForFiles_ command on Windows:

1. Head to the **Start menu** search bar, type in 'cmd', and run the CMD as an administrator.
2. Now, to delete the files that you haven't modified in 30 days, type in the following command and hit **Enter**:  
`ForFiles /p "C:\path\to\folder"/s /d -30 /c "cmd /c del /q @file"`

 The "C:\\path\\to\\folder" and /d -30 here refer to the folder path from where you want to delete files and the specific time for which you'd like to delete your file. Replace them with the settings that suit you.

<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![command prompt on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/command-prompt-on-windows.jpg)

 Your files will be removed as quickly as soon as you hit the above commands.

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Use Task Scheduler on Windows

 Task Scheduler is a simple Windows tool that lets you easily automate your repetitive Windows tasks. Just set up the task, and the app will handle whatever you have asked it to do. When it comes to auto-deleting your files or folders, the _ForFiles_ command is what you will need to help you delete your older files or folders.

 Here's how you can automate the deletion:

1. Head to the **Start menu** search bar, type in 'task scheduler', and select the best match.
2. Right-click on **Task Scheduler Library** and select **New Folder**.
3. Put in any name and click on **OK**.
4. Right-click on the recently created folder and select the **Create Task** option.  
![task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/task-scheduler.jpg)
5. In the **Name** box, enter a name for the task.
6. Now, in the **General** tab, under the **Security options** section, select the **Run whether the user is logged on or not** option.
7. Make sure the **Do not store password** checkbox is unselected.
8. Click on the **Triggers** tab and select the **New** button.
9. Select **On a schedule** option using the **Begin the task** setting.  
![new trigger section on task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-trigger-section-on-windows.jpg)
10. Under the **Settings** section, set up the timings of the tasks you'd like to run. Finally, click on **OK**.

 Now, head to the **Actions** tab and click on the **New** button. From the **Actions** drop-down menu, select the **Start a program** option.

 In the Program/script box, type in the following command:

`ForFiles`

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![new action tab on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-action-tab-on-windows.jpg)

 Similarly, in the **Add arguments** box, type in the following command:

`/p "C:\path\to\folder"/s /d -30 /c "cmd /c del /q @file"`

 In the above command, tweak the _"C:\\path\\to\\folder_" to the path of the folder where your files are and replace "_/d -30_" with actual number you'd like pick. So, your command will become something like this:

`/p "%userprofile%\Users\[Your Username]\Downloads" /s /d -30 /c "cmd /c del /q @file"`

 Click on **OK**. Finally, from the **Settings** tab, check the following checkboxes and then click on **OK**:

* Allow task to be run on demand.
* Run the task as soon as possible after a scheduled start is missed.
* If the task fails, restart every.

<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![new action setting on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-action-setting-on-windows.jpg)

 That's it—finalize the changes by clicking **OK** once again, and you will be done in no time. From here forward, your files will be automatically deleted within the specified time. Of course, if you later change your mind you can always reverse this setting by simply deleting the new folder your created in first step (which in our case, will be **New Folder 1**).

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Auto-Deleting Old Files or Folders on a Windows Computer

 Keeping unnecessary files on your computer is seldom useful. They eat up memory space, hamper your PC's performance, and clog the file organization. Setting up auto-delete instructions, with whichever method you prefer, lets you rid your PC of this extra baggage.

 However, we'd add that auto-removing files or folders from your PC is just one part of cleaning up your Windows. There are many other important hacks such as removing unused apps, terminating pointless background processes, and tweaking settings to whatever is most relevant to your situation. So, make sure you follow all the best principles for running your Windows as smoothly as possible.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-pocket-guide-retaining-twitter-media-on-your-cellphone/"><u>[New] 2024 Approved  Pocket Guide  Retaining Twitter Media on Your Cellphone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-ultimate-showdown-battle-royales-top-titles/"><u>[New] 2024 Approved  Ultimate Showdown  Battle Royale's Top Titles</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-unlocking-the-power-of-words-in-google-meet-discussions/"><u>[New] 2024 Approved  Unlocking the Power of Words in Google Meet Discussions</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-exploring-the-boundaries-64128gb-for-vids/"><u>[New] Exploring the Boundaries  64/128GB for Vids</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-enhance-team-engagement-with-microsoft-teams-snap-camera-feature/"><u>[New] In 2024, Enhance Team Engagement with Microsoft Teams' Snap Camera Feature</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-insights-into-instagrams-selfie-verification-for-2024/"><u>[New] Insights Into Instagram's Selfie Verification for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-socialsnatcher-hd-extractor/"><u>[Updated] 2024 Approved  SocialSnatcher HD Extractor</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-advanced-hd-screen-capture-gadgets-for-2024/"><u>[Updated] Advanced HD Screen Capture Gadgets for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-awesome-free-webcam-games-for-computer-for-2024/"><u>[Updated] Awesome Free Webcam Games for Computer for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-effortless-integration-of-xbox-and-facebook-streams/"><u>[Updated] Effortless Integration of Xbox and Facebook Streams</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-fb-video-conversion-wizardry-turning-hd-to-high-quality-mp4-for-free-for-2024/"><u>[Updated] FB Video Conversion Wizardry – Turning HD to High-Quality MP4, For Free for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-flip-the-script-how-to-turn-your-instagram-visuals-into-viral-stars/"><u>[Updated] In 2024, Flip the Script  How to Turn Your Instagram Visuals Into Viral Stars</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-recipe-reels-reimagined-the-top-7-edible-videography-secrets/"><u>[Updated] Recipe Reels Reimagined  The Top 7 Edible Videography Secrets</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-simplified-guide-fb-video-to-mp3-audio-transformations-for-2024/"><u>[Updated] Simplified Guide  FB Video to MP3 Audio Transformations for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-nativescreenvid-chrome-os-recording-tool/"><u>2024 Approved  NativeScreenVid  Chrome OS Recording Tool</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-screen-selection-simplified-ultrawide-versus-uhd-4k-demystified/"><u>2024 Approved  Screen Selection Simplified  UltraWide Versus UHD 4K Demystified</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensive-guide-to-hyper-v-installation-in-win-11-home/"><u>A Comprehensive Guide to Hyper-V Installation in Win 11 Home</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-operational-optimization-top-windows-pct-strategies/"><u>Achieve Operational Optimization: Top Windows PCT Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/adapting-the-oculus-quest-2-for-windows-os-virtual-reality/"><u>Adapting the Oculus Quest 2 for Windows OS Virtual Reality</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/copyright-definitions-and-implications-in-music-for-2024/"><u>Copyright Definitions & Implications in Music for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-xc0000142-issue-in-windows-11-10/"><u>Correcting XC0000142 Issue in Windows 11, 10</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-edge-windows-gadgets-2024s-must-haves-list/"><u>Cutting-Edge Windows Gadgets - 2024'S Must-Haves List</u></a></li>
<li><a href="https://windows11.techidaily.com/dealing-with-misentered-characters-in-windows-os/"><u>Dealing with Misentered Characters in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-your-global-ip-on-win-os-via-cli/"><u>Demystifying Your Global IP on WIN OS via CLI</u></a></li>
<li><a href="https://hardware-help.techidaily.com/effortless-setup-how-to-update-your-microsoft-ergo-keyboard-drivers/"><u>Effortless Setup: How to Update Your Microsoft Ergo Keyboard Drivers</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-your-gameplay-overcoming-lags-in-warfare/"><u>Elevating Your Gameplay: Overcoming Lags in Warfare</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-pc-sounds-with-windows-11s-mixer-feature/"><u>Enhance PC Sounds with Windows 11'S Mixer Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-reliability-of-your-windows-interface/"><u>Enhancing Reliability of Your Windows Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-controlling-windows-11s-content-filter/"><u>Guide: Controlling Windows 11’S Content Filter</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-how-to-deactivate-amdnvidia-vr-boosting/"><u>Guide: How to Deactivate AMD/Nvidia VR Boosting</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-spotify-location-after-moving-to-another-country-on-motorola-moto-g73-5g-drfone-by-drfone-virtual-android/"><u>How to Change Spotify Location After Moving to Another Country On Motorola Moto G73 5G | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-change-your-infinix-note-30-vip-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How to Change Your Infinix Note 30 VIP Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-sign-doc-file-free-by-ldigisigner-sign-a-word-sign-a-word/"><u>How to sign .doc file free</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-unbrick-a-dead-tecno-pova-5-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Unbrick a Dead Tecno Pova 5 | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-best-3d-blu-ray-players/"><u>In 2024, Best 3D Blu-Ray Players</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-expert-tips-for-navigating-youtubes-comprehensive-comments-section/"><u>In 2024, Expert Tips for Navigating YouTube's Comprehensive Comments Section</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-meizu-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Meizu Phones with/without a PC</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-pro-tips-for-captivating-vr-videos-top-9-strategies/"><u>In 2024, Pro Tips for Captivating VR Videos  Top 9 Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-file-restoration-top-8-techniques-for-windows/"><u>Mastering File Restoration: Top 8 Techniques for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-files-6-methods-to-retrieve-windows-11-paths/"><u>Mastering Files: 6 Methods to Retrieve Windows 11 Paths</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-internet-connection-league-of-legends-on-windows/"><u>Mastering Internet Connection: League of Legends on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-fixing-windows-11s-5ghz-connectivity/"><u>Mastering the Art of Fixing Windows 11'S 5GHz Connectivity</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-of-device-id-extraction-techniques-for-windows-users/"><u>Mastery of Device ID Extraction Techniques for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-freeze-flaws-in-adobes-pc-artist-suite/"><u>Mending Freeze Flaws in Adobe's PC Artist Suite</u></a></li>
<li><a href="https://windows11.techidaily.com/microsofts-surface-studio-2-a-step-towards-perfection/"><u>Microsoft's Surface Studio 2 - A Step Towards Perfection?</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-nitpicking-colors-8-tips-for-a-neutral-desktop/"><u>Navigating Nitpicking Colors: 8 Tips for a Neutral Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11s-s-mode-is-it-worth-considering/"><u>Navigating Windows 11'S 'S Mode': Is It Worth Considering?</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-pen-pad-glitches/"><u>Overcoming Windows Pen-Pad Glitches</u></a></li>
<li><a href="https://windows11.techidaily.com/prtscn-and-snipping-tool-link-in-windows-11-prevent-connection/"><u>PrtScn & Snipping Tool Link in Windows 11: Prevent Connection</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-setup-google-play-on-windows-11/"><u>Quick Setup: Google Play on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/recover-hidden-5ghz-link-in-windows-11-using-these-fixes/"><u>Recover Hidden 5GHz Link in Windows 11 Using These Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-could-not-create-vm-problems-in-microsoft-os/"><u>Remedying 'Could Not Create VM' Problems in Microsoft OS</u></a></li>
<li><a href="https://windows11.techidaily.com/resuscitate-stalled-excel-performance-in-windows-environment/"><u>Resuscitate Stalled Excel Performance in Windows Environment</u></a></li>
<li><a href="https://location-social.techidaily.com/simple-and-effective-ways-to-change-your-country-on-youtube-app-of-your-realme-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>Simple and Effective Ways to Change Your Country on YouTube App Of your Realme 12 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-language-input-change-keyboard-layouts-in-win-11/"><u>Simplifying Language Input: Change Keyboard Layouts in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-to-extending-windows-1011-contextual-commands/"><u>Step-by-Step Guide to Extending Windows 10/11 Contextual Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-solve-missing-dll-rockalldlldll-error/"><u>Steps to Solve Missing DLL: Rockalldll.dll Error</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-windows-update-fixes-for-error-0x800736cc/"><u>Streamlining Windows Update Fixes for Error 0X800736CC</u></a></li>
<li><a href="https://windows11.techidaily.com/taskers-edge-enigma-hidden-processes/"><u>Tasker's Edge Enigma: Hidden Processes?</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-essential-quartet-of-social-media-understanding-facebook-twitter-instagram-and-youtube/"><u>The Essential Quartet of Social Media: Understanding Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-print-guide-to-making-your-powerpoint-shine-on-a-windows-system/"><u>The Ultimate Print Guide to Making Your PowerPoint Shine on a Windows System</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-battlenet-accessibility-on-1011-systems/"><u>Unlocking Battle.net Accessibility on 10/11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11s-printer-interface-max-48-chars/"><u>Unlocking Windows 11'S Printer Interface (Max 48 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/unplugged-no-more-six-methods-to-restore-functioning-network-hardware-on-your-pc/"><u>Unplugged No More: Six Methods to Restore Functioning Network Hardware on Your PC</u></a></li>
<li><a href="https://ai-voice.techidaily.com/updated-2024-approved-authors-recommended-the-best-text-voice-generators-for-all-platforms/"><u>Updated 2024 Approved Authors Recommended The Best Text Voice Generators for All Platforms</u></a></li>
<li><a href="https://windows11.techidaily.com/utilizing-windows-widgets-for-real-time-resource-tracking/"><u>Utilizing Windows Widgets for Real-Time Resource Tracking</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-and-discord-fixing-the-deadly-js-error-quickly/"><u>Win 11 and Discord: Fixing The Deadly JS Error Quickly</u></a></li>
</ul></div>
