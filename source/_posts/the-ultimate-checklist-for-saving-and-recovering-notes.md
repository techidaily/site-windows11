---
title: The Ultimate Checklist for Saving and Recovering Notes
date: 2024-10-23T19:51:41.997Z
updated: 2024-10-24T20:07:43.856Z
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
<a href="https://appsumo.8odi.net/c/5597632/2100526/7443" target="_top" id="2100526">
  <img src="//a.impactradius-go.com/display-ad/7443-2100526" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Manually Back Up and Restore Your Sticky Notes

 If you don't want to use a Microsoft account or want to have an extra backup of your sticky notes, then you can manually back them up yourself. While it's not as easy as just syncing them to the cloud, it can definitely come in handy when you don't have internet access and want to restore the notes.

 To manually back up your sticky notes, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.  
![opening tne Local State folder in Windows Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/opening-local-state-folder-in-windows-run.jpg)
3. In the **LocalState** folder, copy the **plum.sqlite** file.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934138/19272" target="_top" id="1934138">
  <img src="//a.impactradius-go.com/display-ad/19272-1934138" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934138/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![the plum database for Sticky Notes on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/the-plum-database-for-sticky-notes-on-windows.jpg)
4. Paste the **plum.sqlite** file to an external drive, such as a flash drive or external SDD, or upload it to cloud storage, such as OneDrive or Google Drive, for safekeeping.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139119/17108" target="_top" id="2139119">
  <img src="//a.impactradius-go.com/display-ad/17108-2139119" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139119/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To manually restore your sticky notes on another Windows computer, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.
3. Go to where you saved the backup of your sticky notes (the **plum.sqlite** file) and copy it.
4. In the **LocalState** folder, delete the current **plum.sqlite** file.
5. Paste the backup **plum.sqlite** file in the **LocalState** folder.

 Now when you open Sticky Notes, it will load the **plum.sqlite** file, and you should see all your notes appear in the app.

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098701/14409" target="_top" id="2098701">
  <img src="//a.impactradius-go.com/display-ad/14409-2098701" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098701/14409" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-footage.techidaily.com/new-bite-size-broadcasting-battle-which-platform-dominates-in-shorter-videos-in-2024/"><u>[New] Bite-Size Broadcasting Battle Which Platform Dominates in Shorter Videos, In 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/levate-your-online-presence-choosing-the-right-webcam-for-2024/"><u>[New] Elevate Your Online Presence Choosing the Right Webcam for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-exploring-originality-how-to-uncover-roots-of-instagram-visuals/"><u>[New] Exploring Originality How to Uncover Roots of Instagram Visuals</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-metaverse-inspiration-enhanced-by-ar-and-vr-for-2024/"><u>[Updated] Metaverse Inspiration Enhanced by AR & VR for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-delayed-auditory-feedback-on-pcs/"><u>Addressing Delayed Auditory Feedback on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-spec-deficit-errors-from-windows-game-bar/"><u>Addressing Spec Deficit Errors From Window's Game Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-photo-snapshots-in-windows-11/"><u>Adjusting Photo Snapshots in Windows 11</u></a></li>
<li><a href="https://os-tips.techidaily.com/airtag-enhancers-and-tools-expert-picks-for-the-latest-and-greatest/"><u>AirTag Enhancers and Tools - Expert Picks for the Latest & Greatest</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-your-windows-11-search-with-these-five-essentials/"><u>Boost Your Windows 11 Search with These Five Essentials</u></a></li>
<li><a href="https://windows11.techidaily.com/clandestine-data-storage-zip-archives-in-image-files-for-windows-enthusiasts/"><u>Clandestine Data Storage: ZIP Archives in Image Files for Windows Enthusiasts</u></a></li>
<li><a href="https://windows11.techidaily.com/conveniently-embedding-passwords-into-windows-text-archives/"><u>Conveniently Embedding Passwords Into Windows Text Archives</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-classic-visuals-a-guide-to-shader-magic-in-retroarc/"><u>Crafting Classic Visuals: A Guide to Shader Magic in RetroArc</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-the-oculus-quest-for-windows-vr-use/"><u>Customizing the Oculus Quest for Windows VR Use</u></a></li>
<li><a href="https://article-posts.techidaily.com/digitize-creativity-our-top-list-for-engaging-with-3d-typographic-websites/"><u>Digitize Creativity Our Top List for Engaging with 3D Typographic Websites</u></a></li>
<li><a href="https://windows11.techidaily.com/dism-tactics-restoring-windows-11-os-images/"><u>DISM Tactics: Restoring Windows 11 OS Images</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-unbrick-a-dead-realme-c67-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Unbrick a Dead Realme C67 5G | Dr.fone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-a-new-era-advanced-webcam-techniques/"><u>In 2024, A New Era Advanced Webcam Techniques</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-honor-magic-vs-2-location-by-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Honor Magic Vs 2 Location by Number | Dr.fone</u></a></li>
<li><a href="https://buynow-help.techidaily.com/navigating-webex-effectively-key-advantages-and-disadvantages-for-remote-collaboration-tools/"><u>Navigating Webex Effectively: Key Advantages & Disadvantages for Remote Collaboration Tools</u></a></li>
</ul></div>

