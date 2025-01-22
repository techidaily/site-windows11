---
title: The Ultimate Checklist for Saving and Recovering Notes
date: 2025-01-16T20:29:22.747Z
updated: 2025-01-22T18:28:24.122Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_dOmuXhsV6Y?si=aT6vgPbDx4ajjvdr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SDUPd69Qfls?si=uIGZG-riskwmVZYg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To restore the notes on another computer, open the Sticky Notes app (make sure the PC is connected to the internet) and sign in with your Microsoft account. Once signed in, the app will load all the notes you previously synced. Furthermore, every time you finish writing a Sticky Note or edit one, the app will automatically back it up to the cloud.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K4lRBnNnd9k?si=5e0MbdOz-fF6Ry_k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Manually Back Up and Restore Your Sticky Notes

 If you don't want to use a Microsoft account or want to have an extra backup of your sticky notes, then you can manually back them up yourself. While it's not as easy as just syncing them to the cloud, it can definitely come in handy when you don't have internet access and want to restore the notes.

 To manually back up your sticky notes, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.  
![opening tne Local State folder in Windows Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/opening-local-state-folder-in-windows-run.jpg)
3. In the **LocalState** folder, copy the **plum.sqlite** file.  

![the plum database for Sticky Notes on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/the-plum-database-for-sticky-notes-on-windows.jpg)
4. Paste the **plum.sqlite** file to an external drive, such as a flash drive or external SDD, or upload it to cloud storage, such as OneDrive or Google Drive, for safekeeping.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5OmJZ4Z8jgk?si=YIoEaPI8geoiFSYE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To manually restore your sticky notes on another Windows computer, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.
3. Go to where you saved the backup of your sticky notes (the **plum.sqlite** file) and copy it.
4. In the **LocalState** folder, delete the current **plum.sqlite** file.
5. Paste the backup **plum.sqlite** file in the **LocalState** folder.

 Now when you open Sticky Notes, it will load the **plum.sqlite** file, and you should see all your notes appear in the app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-G7cU8dYvuI?si=JaKqRcW6qq9CDvty" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-discover-the-perfect-moment-timing-your-insta-posts/"><u>[New] 2024 Approved Discover the Perfect Moment Timing Your Insta Posts</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-ideal-tools-to-capture-your-pcs-display-on-windows-10/"><u>[New] 2024 Approved Ideal Tools to Capture Your PC's Display on Windows 10</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-launching-an-impactful-instagram-live-session/"><u>[New] Launching an Impactful Instagram Live Session</u></a></li>
<li><a href="https://article-helps.techidaily.com/draft-an-engaging-giveaway-for-facebooks-social-impact/"><u>Draft an Engaging Giveaway for Facebook's Social Impact</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-you-through-ea-server-connection-troubles/"><u>Guiding You Through EA Server Connection Troubles</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-quickly-resolve-windows-11-error-0x800f0922/"><u>How To Quickly Resolve Windows 11 Error 0X800F0922</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-rectify-hypervisor-bsos-a-windows-expert-guide/"><u>How to Rectify Hypervisor BSOS: A Windows Expert Guide</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-top-iphones-video-editors-face-off-cameo-vs-filmorago/"><u>In 2024, Top iPhones' Video Editors Face-Off Cameo Vs. FilmoraGo</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-installation-of-windows-11-arm-from-iso/"><u>Mastering the Installation of Windows 11 ARM From ISO</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-self-lock-in-windows-os/"><u>Preventing Self-Lock in Windows OS</u></a></li>
<li><a href="https://extra-resources.techidaily.com/prime-chrome-audio-transformers-leading-web-based-text-to-speech-apps/"><u>Prime Chrome Audio Transformers Leading Web-Based Text-to-Speech Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-uninstall-guide-windows-11s-best-practices-102-chars/"><u>Quick Uninstall Guide: Windows 11'S Best Practices (102 Chars)</u></a></li>
<li><a href="https://driver-install.techidaily.com/safe-webcam-driver-for-pcs/"><u>Safe Webcam Driver for PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/super-fast-windows-query-with-everythingapp/"><u>Super-Fast Windows Query with EverythingApp</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-ultimate-walkthrough-for-proficiently-harnessing-the-power-of-the-wayback-machine/"><u>The Ultimate Walkthrough for Proficiently Harnessing the Power of the Wayback Machine</u></a></li>
<li><a href="https://buynow-info.techidaily.com/unpacking-the-value-of-mophies-ac-charging-solution-a-balance-between-expense-and-usability/"><u>Unpacking the Value of Mophie's AC Charging Solution - A Balance Between Expense and Usability</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-productivity-push-crafting-uwp-shortcuts/"><u>Windows 11 Productivity Push: Crafting UWP Shortcuts</u></a></li>
</ul></div>

