---
title: The Ultimate Checklist for Saving and Recovering Notes
date: 2024-10-27T17:23:29.224Z
updated: 2024-10-30T16:21:44.471Z
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
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411">
  <img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Manually Back Up and Restore Your Sticky Notes

 If you don't want to use a Microsoft account or want to have an extra backup of your sticky notes, then you can manually back them up yourself. While it's not as easy as just syncing them to the cloud, it can definitely come in handy when you don't have internet access and want to restore the notes.

 To manually back up your sticky notes, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.  
![opening tne Local State folder in Windows Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/opening-local-state-folder-in-windows-run.jpg)
3. In the **LocalState** folder, copy the **plum.sqlite** file.  

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136620/26400" target="_top" id="2136620">
  <img src="//a.impactradius-go.com/display-ad/26400-2136620" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136620/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![the plum database for Sticky Notes on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/the-plum-database-for-sticky-notes-on-windows.jpg)
4. Paste the **plum.sqlite** file to an external drive, such as a flash drive or external SDD, or upload it to cloud storage, such as OneDrive or Google Drive, for safekeeping.

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098702/14409" target="_top" id="2098702">
  <img src="//a.impactradius-go.com/display-ad/14409-2098702" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098702/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To manually restore your sticky notes on another Windows computer, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.
3. Go to where you saved the backup of your sticky notes (the **plum.sqlite** file) and copy it.
4. In the **LocalState** folder, delete the current **plum.sqlite** file.
5. Paste the backup **plum.sqlite** file in the **LocalState** folder.

 Now when you open Sticky Notes, it will load the **plum.sqlite** file, and you should see all your notes appear in the app.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130873/7443" target="_top" id="2130873">
  <img src="//a.impactradius-go.com/display-ad/7443-2130873" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130873/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-info.techidaily.com/updated-pro-tip-guide-to-integrating-photos-and-videos-into-windows-10-for-2024/"><u>[Updated] Pro-Tip Guide to Integrating Photos and Videos Into Windows 10 for 2024</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-unveiling-methods-for-scaling-up-tiktok-video-importation-for-2024/"><u>[Updated] Unveiling Methods for Scaling Up TikTok Video Importation for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-upgraded-guide-to-android-based-vr-and-full-sphere-films/"><u>[Updated] Upgraded Guide to Android-Based VR and Full-Sphere Films</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-taking-your-photos-and-videos-to-new-heights/"><u>2024 Approved Taking Your Photos and Videos to New Heights</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-guide-to-fixing-webcam-error-codes-on-w1011/"><u>Expert Guide to Fixing Webcam Error Codes on W10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-users-through-printer-access-errors/"><u>Guiding Users Through Printer Access Errors</u></a></li>
<li><a href="https://solve-lab.techidaily.com/hassle-free-methods-for-uploading-high-and-standard-definition-videos-to-your-youtube-account-using-a-mac/"><u>Hassle-Free Methods for Uploading High & Standard Definition Videos to Your YouTube Account Using a Mac</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-life360-notify-when-you-log-out-on-realme-gt-3-drfone-by-drfone-virtual-android/"><u>In 2024, Does Life360 Notify When You Log Out On Realme GT 3? | Dr.fone</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-navigating-to-youtubes-video-editor-interface/"><u>In 2024, Navigating to YouTube's Video Editor Interface</u></a></li>
<li><a href="https://techidaily.com/innovative-strides-at-abbyy-with-patrick-jeans-recent-promotion-to-cpo-and-cto-roles/"><u>Innovative Strides at ABBYY with Patrick Jean's Recent Promotion to CPO and CTO Roles</u></a></li>
<li><a href="https://windows11.techidaily.com/maintaining-originality-of-windows-safescreensaver/"><u>Maintaining Originality of Windows SafeScreensaver</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/mondly-triumphs-engaging-70-million-learners-globally/"><u>Mondly Triumphs – Engaging 70 Million Learners Globally</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/restore-noise-to-silent-twitter-video-posts/"><u>Restore Noise to Silent Twitter Video Posts</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-integration-of-google-play-store-in-win11/"><u>Seamless Integration of Google Play Store in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-systems-crafting-a-window-11-routine-with-controlled-downtime-and-updates/"><u>Seamless Systems: Crafting a Window 11 Routine with Controlled Downtime and Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-your-windows-11-experience/"><u>Streamlining Your Windows 11 Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-clear-sound-top-5-free-windows-cutters/"><u>Unleash Clear Sound: Top 5 Free Windows Cutters</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-full-potential-install-and-configure-wsl/"><u>Unlocking Full Potential: Install and Configure WSL</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-at-wifi-less-windows-11-setup/"><u>Winning at Wifi-Less Windows 11 Setup</u></a></li>
</ul></div>

