---
title: Illustrating Maximum & Minimum CPU Stages on Windows
date: 2024-07-11T21:47:44.063Z
updated: 2024-07-12T21:47:44.063Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Illustrating Maximum & Minimum CPU Stages on Windows
excerpt: This Article Describes Illustrating Maximum & Minimum CPU Stages on Windows
keywords: CPU Stage Illustration,Min Max CPU Cycle,CPU Performance Limits,Windows CPU Timing,Optimal CPU Usage,CPU Speed Analysis,Stages in PC CPU
thumbnail: https://thmb.techidaily.com/62d72eb39093270995757df1adc43019ed0e362b73decee245e264928d768a5a.jpg
---

## Illustrating Maximum & Minimum CPU Stages on Windows

 Have you ever tried to tweak the minimum and maximum processor states on your Windows PC, only to find them hidden? Or perhaps you want to hide the options to prevent others from tampering with them?

 Whichever you're trying to do, we're here to help by showing you how to add or remove them in the Power Options menu.

## How to Show or Hide the Minimum or Maximum Processor State Using Command Prompt

 To use Command Prompt to show or hide these power states, press**Win + R** to open Windows Run. Then, enter**cmd** in the text box and hit the**Enter** key on your keyboard. You can also use one of the many [ways to open the Command Prompt on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .

![Cmd in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/win11-cmd.jpg)

To show the minimum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR 893dee8e-2bef-41e0-89c6-b55d0929964c -ATTRIB_HIDE`

To hide the minimum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR 893dee8e-2bef-41e0-89c6-b55d0929964c +ATTRIB_HIDE`

To show the maximum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR bc5038f7-23e0-4960-96da-33abaf5935ec -ATTRIB_HIDE`

To hide the maximum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR bc5038f7-23e0-4960-96da-33abaf5935ec +ATTRIB_HIDE`

 After you have typed in the command you want in the CMD window, hit the**Enter** key on your keyboard to run it.

## How to Show or Hide the Minimum or Maximum Processor State Using the Registry Editor

 You can also show or hide these options using the Registry Editor. However, before you do so, create a restore point as a backup in case you make a mistake and need to return your Windows computer to a previously-working state. Check out [how to create a restore point in Command Prompt](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) for more information.

 After creating the system restore point, press**Win + R** to open the Run dialog box. Then, enter**regedit** in the text box and hit the**Enter** key to open the Registry Editor.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

 On the UAC prompt, click**Yes** to continue.

 To get to the key for the minimum processor state in the Registry editor, copy and paste the following file path into the Registry Editor’s address bar and hit**Enter** :

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\bc5038f7-23e0-4960-96da-33abaf5935ec`

 Right-click the**Attributes** value in the right panel and select**Modify** .

![modifying the attributes value in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-modify-attributes.jpg)

 Then, set**Value data** to**1** to hide the minimum processor state. To show it, set**Value data** to**2** .

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

 For the maximum processor state, enter the below file path in the Registry Editor's address bar to get to its key:

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\893dee8e-2bef-41e0-89c6-b55d0929964c`

 Double-click the**Attributes** entry to modify it, and then change**Value data** to**1** to hide the maximum processor state or**2** to show it.

## Add or Remove the Minimum and Maximum Processor States From Power Options

 Setting the minimum or maximum processor state on your Windows computer is vital to helping you get the performance you want from it. If you can’t see these options in the Power Options menu, you can easily reveal them with either Command Prompt or the Registry Editor. And after you’re done tweaking the states, you can hide them for their protection.


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
<li><a href="https://windows11.techidaily.com/streamline-creative-processes-with-these-8-windows-best-apps/"><u>Streamline Creative Processes With These 8 Window's Best Apps</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-unveiling-the-hottest-books-on-social-medias-reading-stage/"><u>[New] Unveiling the Hottest Books on Social Media's Reading Stage</u></a></li>
<li><a href="https://windows11.techidaily.com/a-guide-to-understanding-windows-program-files-format/"><u>A Guide to Understanding Windows' Program Files Format</u></a></li>
<li><a href="https://windows11.techidaily.com/are-file-thumbnails-not-showing-up-in-windows-11-heres-how-to-fix-it/"><u>Are File Thumbnails Not Showing Up in Windows 11? Here's How to Fix It</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-s-most-popular-online-video-reversal-services/"><u>Updated In 2024, S Most Popular Online Video Reversal Services</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11-secrets-with-devhome-insights/"><u>Unlocking Windows 11 Secrets with DevHome Insights</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-desktop-from-chaotic-to-customized-in-minutes/"><u>Win11 Desktop: From Chaotic to Customized, in Minutes</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-outlooks-glitch-the-path-to-fixed-error-0x80072746/"><u>Conquering Outlook's Glitch: The Path to Fixed Error 0X80072746</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-asus-rog-phone-8-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Asus ROG Phone 8 | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-ultimate-guide-to-get-the-meltan-box-pokemon-go-for-honor-x50-gt-drfone-by-drfone-virtual-android/"><u>In 2024, Ultimate guide to get the meltan box pokemon go For Honor X50 GT | Dr.fone</u></a></li>
<li><a href="https://ai-voice.techidaily.com/best-5-tiktok-voice-generators-you-should-try-for-2024/"><u>Best 5 TikTok Voice Generators You Should Try for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-success-vs-failure-in-user-credentials-entry-on-pcs/"><u>Decoding Success vs Failure in User Credentials Entry on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-update-halted-quick-solutions-for-a-perfect-installation/"><u>Windows Update Halted: Quick Solutions for a Perfect Installation</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-earning-through-youtube-navigating-revenue-without-ads/"><u>In 2024, Earning Through YouTube  Navigating Revenue Without Ads</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-command-line-capabilities-in-latest-windows-releases/"><u>Boost Command-Line Capabilities in Latest Windows Releases</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-hearing-heroism-essential-online-picks-for-tts-files/"><u>2024 Approved  Hearing Heroism  Essential Online Picks for TTS Files</u></a></li>
<li><a href="https://extra-hints.techidaily.com/adding-eye-catching-text-to-vids-without-costs/"><u>Adding Eye-Catching Text to Vids Without Costs</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/comprehensive-guide-to-screen-capturing-in-windows-8-for-2024/"><u>Comprehensive Guide to Screen Capturing in Windows 8 for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-cost-effective-pc-video-archive-tools/"><u>[New] In 2024, Cost-Effective PC Video Archive Tools</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-emergency-recovery-for-a-misplaced-tiktok-refresh-for-2024/"><u>[New] Emergency Recovery for a Misplaced TikTok Refresh for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/1719377597268-legacy-software-understanding/"><u>Legacy Software Understanding:</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-optimal-webp-to-jpg-transformation-guide/"><u>2024 Approved  Optimal WebP-to-JPG Transformation Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/a-beginners-guide-to-managing-windows-11-wins/"><u>A Beginner's Guide to Managing Windows 11 Wins</u></a></li>
<li><a href="https://windows11.techidaily.com/uniting-gmail-and-outlook-windows-setup-walkthrough/"><u>Uniting Gmail and Outlook: Windows Setup Walkthrough</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-password-creation-companion-for-windows-users/"><u>The Ultimate Password Creation Companion for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/turning-on-hyper-v-simplified-your-win11-how-to/"><u>Turning On Hyper-V Simplified - Your Win11 How-To</u></a></li>
<li><a href="https://windows11.techidaily.com/concealed-item-choices-win-10plus-menu-tactics/"><u>Concealed Item Choices: Win 10+ Menu Tactics</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-reducing-browsing-impact-on-system-performance/"><u>Tips for Reducing Browsing Impact on System Performance</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/content-creation-in-the-digital-age-audio-vs-visual-for-2024/"><u>Content Creation in the Digital Age  Audio vs Visual for 2024</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/discover-the-essential-steps-for-editing-a-music-video-in-this-guide-learn-about-aspect-ratio-and-the-first-cut-process-to-create-a-visually-captivating-vid/"><u>Discover the Essential Steps for Editing a Music Video in This Guide. Learn About Aspect Ratio and the First Cut Process to Create a Visually Captivating Video</u></a></li>
<li><a href="https://win11.techidaily.com/analyzing-surface-laptop-go-3-processor-boost-and-critique/"><u>Analyzing Surface Laptop Go 3: Processor Boost and Critique</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-top-obs-configurations-on-frugal-devices/"><u>[New] 2024 Approved  Top OBS Configurations on Frugal Devices</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-essential-tips-for-hosting-a-successful-facebook-live-event/"><u>[New] Essential Tips for Hosting a Successful Facebook Live Event</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-frozen-overlays-restoring-function-to-discord-ui/"><u>Addressing Frozen Overlays: Restoring Function to Discord UI</u></a></li>
<li><a href="https://windows11.techidaily.com/the-uncharted-territory-windows-11-and-the-future-of-ai/"><u>The Uncharted Territory: Windows 11 and the Future of AI</u></a></li>
<li><a href="https://windows11.techidaily.com/ultimate-bundle-premier-cost-free-windows-11-assistants/"><u>Ultimate Bundle: Premier Cost-Free Windows 11 Assistants</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-seamless-slideshow-on-ig/"><u>2024 Approved  Seamless SlideShow on IG</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-leading-alternatives-to-twitter-ranked-best/"><u>[New] In 2024, Leading Alternatives to Twitter, Ranked Best</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-deciphering-content-control-youtube-vs-creative-commons-license/"><u>[Updated] 2024 Approved  Deciphering Content Control  YouTube Vs. Creative Commons License</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-9-samsung-galaxy-a05-monitoring-apps-for-parental-controls-drfone-by-drfone-virtual-android/"><u>Top 9 Samsung Galaxy A05 Monitoring Apps for Parental Controls | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/effortless-instagram-media-export-top-20-free-mp4-converters-online-for-2024/"><u>Effortless Instagram Media Export  Top 20 Free MP4 Converters Online for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/augmented-folder-actions-power-up-your-file-management/"><u>Augmented Folder Actions: Power Up Your File Management</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-free-video-capture-test-apowersoft-and-more/"><u>[New] 2024 Approved  Free Video Capture Test  Apowersoft & More</u></a></li>
<li><a href="https://windows11.techidaily.com/command-prompt-magic-utilize-windows-wsl-feature/"><u>Command Prompt Magic: Utilize Windows' WSL Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/dealing-with-nvidias-geforce-x0001-error-on-w10w11/"><u>Dealing with Nvidia's GeForce X0001 Error on W10/W11</u></a></li>
<li><a href="https://windows11.techidaily.com/baffling-backup-concealed-control-center-settings/"><u>Baffling Backup: Concealed Control Center Settings</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-innovative-approaches-to-tiktok-lives-from-desktop-devices/"><u>[Updated] In 2024, Innovative Approaches to TikTok Lives From Desktop Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-caption-troubleshooting-made-simple/"><u>Win11 Caption Troubleshooting Made Simple</u></a></li>
</ul></div>
