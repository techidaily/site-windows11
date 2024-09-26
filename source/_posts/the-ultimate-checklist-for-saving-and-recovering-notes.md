---
title: The Ultimate Checklist for Saving and Recovering Notes
date: 2024-09-24T20:52:14.789Z
updated: 2024-09-26T20:46:24.364Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Ultimate Checklist for Saving and Recovering Notes
excerpt: This Article Describes The Ultimate Checklist for Saving and Recovering Notes
keywords: Note-Saving Tips,Quick Note Recovery,Idea Preservation,Essential Note Hacks,Effective Notes Saving,Recover Lost Memos,Best Note Strategies
thumbnail: https://thmb.techidaily.com/4a1fd1f32e402d9cdb76f6617f2af3bb610c32d546a576cbb651a68afaa24695.jpg
---

## The Ultimate Checklist for Saving and Recovering Notes

 Sticky Notes on Windows turn your computer into a virtual board for posting notes, reminders, lists, and pretty much anything that you need to remember at a glance. So it makes sense that you wouldn't want to lose them, whether you're switching computers or a problem with your PC has caused you to lose your data.

 In this guide, we're going to show you a couple of ways to back up your sticky notes on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Back Up and Restore YourSticky Notes Using a Microsoft Account

 The easiest way to back up your sticky notes is to use a Microsoft account, which stores the notes on the cloud. If you don't have one already, then you can [learn how to create a Microsoft account](https://www.makeuseof.com/your-microsoft-account-things-windows-user-should-know/) or skip to the next section to learn how to back up the notes manually.

 If you've been using Windows with your Microsoft account all along, the notes could be synced to the cloud already. If you're not, you can [switch from a local account to a Microsoft account](https://www.makeuseof.com/windows-switch-local-account-to-microsoft-account/) for that to happen.

 To be sure if Sticky Notes is syncing your notes already or, if you're using a local account, give the app the ability to do so, follow the steps below:

1. Connect your Windows PC to the internet and open Sticky Notes.
2. Click on **Settings** (the gear icon) in the top right corner.
3. If you've already signed in, you'll see the details of your Microsoft account at the top with a **Sign out** link. If that's the case, you can skip to step #7 to sync the notes. If you're not signed in, click **Sign in**.
4. In the **Use one of these accounts** section, select the Microsoft account you want to sign in with. If there are no accounts there, select either **Microsoft account** or **Work or school account** in the **Use a different account** section.
5. Click **Continue** and follow the instructions to complete the sign-in process.
6. Once you're signed in, click on **Settings** again in the top right corner.
7. Scroll down and click **Sync now**.  
![the Sync Now button in Sticky Notes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/sync-now-button-in-sticky-notes.jpg)

 To restore the notes on another computer, open the Sticky Notes app (make sure the PC is connected to the internet) and sign in with your Microsoft account. Once signed in, the app will load all the notes you previously synced. Furthermore, every time you finish writing a Sticky Note or edit one, the app will automatically back it up to the cloud.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130890/7443" target="_top" id="2130890">
  <img src="//a.impactradius-go.com/display-ad/7443-2130890" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130890/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Manually Back Up and Restore Your Sticky Notes

 If you don't want to use a Microsoft account or want to have an extra backup of your sticky notes, then you can manually back them up yourself. While it's not as easy as just syncing them to the cloud, it can definitely come in handy when you don't have internet access and want to restore the notes.

 To manually back up your sticky notes, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.  
![opening tne Local State folder in Windows Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/opening-local-state-folder-in-windows-run.jpg)
3. In the **LocalState** folder, copy the **plum.sqlite** file.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135353/19272" target="_top" id="2135353">
  <img src="//a.impactradius-go.com/display-ad/19272-2135353" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135353/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![the plum database for Sticky Notes on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/the-plum-database-for-sticky-notes-on-windows.jpg)
4. Paste the **plum.sqlite** file to an external drive, such as a flash drive or external SDD, or upload it to cloud storage, such as OneDrive or Google Drive, for safekeeping.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123732/7443" target="_top" id="2123732">
  <img src="//a.impactradius-go.com/display-ad/7443-2123732" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123732/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To manually restore your sticky notes on another Windows computer, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.
3. Go to where you saved the backup of your sticky notes (the **plum.sqlite** file) and copy it.
4. In the **LocalState** folder, delete the current **plum.sqlite** file.
5. Paste the backup **plum.sqlite** file in the **LocalState** folder.

 Now when you open Sticky Notes, it will load the **plum.sqlite** file, and you should see all your notes appear in the app.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148633/16836" target="_top" id="2148633">
  <img src="//a.impactradius-go.com/display-ad/16836-2148633" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148633/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Never Lose Your Sticky Notes Again

 Losing your sticky notes means you could lose potentially important information. So it makes sense to always have a copy stored somewhere in case you need to restore them. We recommend using your Microsoft account to back up the notes, considering it's convenient to both sync and restore them later on, but it's also a good idea to know that there's a manual option available.

 In this guide, we're going to show you a couple of ways to back up your sticky notes on Windows.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-blog.techidaily.com/024-approved-elevating-your-videos-visual-impact-youtubthumbnail-design-on-macos/"><u>[New] 2024 Approved Elevating Your Video's Visual Impact YoutubThumbnail Design on macOS</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-in-2024-synergy-between-humans-and-computers-through-gestures/"><u>[New] In 2024, Synergy Between Humans & Computers Through Gestures</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-capturecrafter-your-ultimate-guide-to-screen-recording/"><u>[Updated] 2024 Approved CaptureCrafter Your Ultimate Guide to Screen Recording</u></a></li>
<li><a href="https://windows11.techidaily.com/disable-automatic-snipping-tool-activation-by-prtscn-keypress-in-windows-11/"><u>Disable Automatic Snipping Tool Activation by PrtScn Keypress in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-system-interaction-in-command-prompt/"><u>Elevate Your System Interaction in Command Prompt</u></a></li>
<li><a href="https://windows11.techidaily.com/how-ai-copilot-enriches-windows-11-for-everyday-users/"><u>How AI Copilot Enriches Windows 11 for Everyday Users</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-tiktok-to-see-more-content-on-your-nokia-c12-pro-drfone-by-drfone-virtual-android/"><u>How to Change Location on TikTok to See More Content On your Nokia C12 Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-specified-user-does-not-have-a-valid-profile-app-error-in-windows-10-and-11/"><u>How to Fix the Specified User Does Not Have a Valid Profile App Error in Windows 10 & 11</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-epic-browser-recording-tools-for-the-ultimate-surfers-dream/"><u>In 2024, Epic Browser Recording Tools for the Ultimate Surfer's Dream</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-latest-guide-how-to-bypass-infinix-hot-40-pro-frp-without-computer-by-drfone-android/"><u>In 2024, Latest Guide How To Bypass Infinix Hot 40 Pro FRP Without Computer</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-superior-lineup-elite-webcam-mounts/"><u>In 2024, Superior Lineup Elite Webcam Mounts</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-what-does-enter-puk-code-mean-and-why-did-the-sim-get-puk-blocked-on-samsung-galaxy-f14-5g-device-by-drfone-android/"><u>In 2024, What Does Enter PUK Code Mean And Why Did The Sim Get PUK Blocked On Samsung Galaxy F14 5G Device</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/instagrams-edge-transforming-your-videography-with-precision-cropping-for-2024/"><u>Instagram's Edge Transforming Your Videography with Precision Cropping for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-performance-monitoring-pcs-ram-gpu-and-cpu/"><u>Maximizing Performance: Monitoring PC's RAM, GPU & CPU</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-app-crashes-in-windows-dealing-with-unhandled-exceptions/"><u>Overcoming App Crashes in Windows: Dealing with Unhandled Exceptions</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-resolving-cant-connect-issues-in-windows-11/"><u>Quick Guide: Resolving 'Can't Connect' Issues in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-secure-logins-with-5-tips-against-key-conflicts-in-win11/"><u>Streamlining Secure Logins with 5 Tips Against Key Conflicts in Win11</u></a></li>
<li><a href="https://win-solutions.techidaily.com/troubleshooting-common-initialization-problems-in-riot-games-valorant/"><u>Troubleshooting Common Initialization Problems in Riot Games' Valorant</u></a></li>
<li><a href="https://windows11.techidaily.com/winerror-correction-bypassing-the-perplexing-0x80072746-mail-issue/"><u>WinError Correction: Bypassing the Perplexing 0X80072746 Mail Issue</u></a></li>
</ul></div>

