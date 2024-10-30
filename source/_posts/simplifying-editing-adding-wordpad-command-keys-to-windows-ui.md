---
title: "Simplifying Editing: Adding WordPad Command Keys to Windows' UI"
date: 2024-10-28T16:57:47.003Z
updated: 2024-10-30T16:17:27.599Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Simplifying Editing: Adding WordPad Command Keys to Windows' UI"
excerpt: "This Article Describes Simplifying Editing: Adding WordPad Command Keys to Windows' UI"
keywords: Simplify Editing Process,WordPad Commands Integration,UI Enhancement Tips,Streamline Text Editing,User Interface Improvement,Keyboard Shortcuts in Windows,Efficient WordEditing Tools
thumbnail: https://thmb.techidaily.com/2e81f992123e17db59f89c6842ca48bb426d509215d95604071818ec4e7dc281.jpg
---

## Simplifying Editing: Adding WordPad Command Keys to Windows' UI

 Windows' WordPad app is either a limited word processor or an advanced text editor depending on how you look at it. Unlike Notepad, WordPad is a rich text editor that incorporates formatting and styling options for content. Therefore, it is a preferable alternative to Notepad for opening and editing TXT and RTF files.

 As such, you might want to add WordPad shortcuts to Windows 11’s context menu, so you can quickly access WordPad and open TXT/RTF documents with it. This is how you can set up context menu shortcuts for launching WordPad and opening files in it.

## How to Add a WordPad Shortcut to Windows 11’s Context Menu

 To create WordPad shortcuts on the right-click menu, you’ll need to do a bit of manual registry tweaking. The editing required is relatively straightforward, but you can back up the Windows registry beforehand if preferred. See[how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) if you need help.

You can add a basic WordPad shortcut to the context menu like this:

1. Click inside the**Type here to search** box at the top of Windows 11’s Start menu.
2. Type the keyword**regedit** in the search box to open the Registry Editor (see[how to open the Registry Editor for more methods](https://www.makeuseof.com/windows-11-open-registry-editor/) ).
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2052060/7443" target="_top" id="2052060">
  <img src="//a.impactradius-go.com/display-ad/7443-2052060" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2052060/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123737/7443" target="_top" id="2123737">
  <img src="//a.impactradius-go.com/display-ad/7443-2123737" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123737/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

9. Enter**wordpad.exe %1** in the**Value** box, and click**OK** to apply.  
![The wordpad.exe value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-wordpad-exe-value-data.jpg)

 Now you can close the Registry Editor and try out the**Open with WordPad** context menu shortcut. Launch File Explorer (see[how to launch File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) ), and navigate to a folder containing some TXT or RTF files. Right-click an RTF or TXT document and select**Show more options** . Click**Open with WordPad** to bring up the right-clicked document in that app.

## How to Erase the WordPad Context Menu Shortcuts

 If you ever change your mind about having WordPad context menu options, you can remove them by deleting their keys. To do so, you’ll need to open the following key locations in the Registry Editor:

`Computer\HKEY_CLASSES_ROOT\*\shell\Open with WordPad\command  
Computer\HKEY_CLASSES_ROOT\Directory\Background\shell\WordPad\command`

 Then right-click the**Open with WordPad** or**WordPad** key to select a**Delete** option. A dialogue box will open requesting confirmation to erase. Select**Yes** if you’re sure about deleting the key.

![The Delete option for registry keys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-delete-option2.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135351/19272" target="_top" id="2135351">
  <img src="//a.impactradius-go.com/display-ad/19272-2135351" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135351/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148641/16836" target="_top" id="2148641">
  <img src="//a.impactradius-go.com/display-ad/16836-2148641" border="0" alt="https://techidaily.com" width="254" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148641/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://facebook-video-footage.techidaily.com/new-a-new-era-of-creativity-pinpointing-the-best-10-budget-friendly-video-art-communities-on-youtube-for-2024/"><u>[New] A New Era of Creativity Pinpointing the Best 10 Budget-Friendly Video Art Communities on YouTube for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-how-to-make-instagram-slow-motion-video/"><u>[New] How to Make Instagram Slow Motion Video</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-a-deep-dive-into-moto-z2s-smarter-side/"><u>[Updated] A Deep Dive Into Moto Z2's Smarter Side</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-tactical-volume-management-in-live-mixing/"><u>[Updated] Tactical Volume Management in Live Mixing</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-copyright-definitions-and-implications-in-music/"><u>2024 Approved Copyright Definitions & Implications in Music</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-upgrading-to-big-sur-know-your-hardware-standards/"><u>2024 Approved Upgrading to Big Sur? Know Your Hardware Standards</u></a></li>
<li><a href="https://some-approaches.techidaily.com/comment-desactiver-la-fonction-autoresize-dans-handbrake-pour-un-recadrage-video-manuel-une-solution-detaillee/"><u>Comment Désactiver La Fonction 'Autoresize' Dans HandBrake Pour Un Recadrage Vidéo Manuel : Une Solution Détaillée</u></a></li>
<li><a href="https://windows11.techidaily.com/optimal-windows-solutions-for-video-file-editing-and-conversion/"><u>Optimal Windows Solutions for Video File Editing & Conversion</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/ps3-controller-integration-into-pc-systems-bypassing-motioninjoy/"><u>PS3 Controller Integration Into PC Systems - Bypassing MotionINJoy</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-to-remedying-post-windows-update-glitches/"><u>Quick Guide to Remedying Post-Windows Update Glitches</u></a></li>
<li><a href="https://windows11.techidaily.com/screen-separation-strategies-wallpapers-per-monitor-windows-style/"><u>Screen Separation Strategies: Wallpapers per Monitor, Windows Style</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-avoid-blackout-while-playing-windows-games/"><u>Strategies to Avoid Blackout While Playing Windows Games</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-epic-games-sign-in-problems-on-pc/"><u>Troubleshooting Epic Games Sign-In Problems on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-printer-offline-on-windows-11/"><u>Understanding 'Printer Offline' On Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-off-screen-app-functionality-win-1011s-best-recovery-approaches-6-key-techniques/"><u>Unlock Off-Screen App Functionality: Win 10/11'S Best Recovery Approaches (6 Key Techniques)</u></a></li>
</ul></div>

