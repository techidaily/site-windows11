---
title: "Boosting Speed with WordPad: Embedding Keyboard Macros Into Windows Menu"
date: 2024-06-25T12:27:24.588Z
updated: 2024-06-26T12:27:24.588Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Boosting Speed with WordPad: Embedding Keyboard Macros Into Windows Menu"
excerpt: "This Article Describes Boosting Speed with WordPad: Embedding Keyboard Macros Into Windows Menu"
keywords: Boosting Speed,WordPad Keys,Embedded Macros,Keyboard Macros,Menu Enhancement,Accelerated Input,Text Editing Speed
thumbnail: https://thmb.techidaily.com/270179364474a44da1eaeda7613c10f10260fff7aad4cae0d60acb9733eadc20.jpg
---

## Boosting Speed with WordPad: Embedding Keyboard Macros Into Windows Menu

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

 Now you can close the Registry Editor and try out the**Open with WordPad** context menu shortcut. Launch File Explorer (see[how to launch File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) ), and navigate to a folder containing some TXT or RTF files. Right-click an RTF or TXT document and select**Show more options** . Click**Open with WordPad** to bring up the right-clicked document in that app.

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
<li><a href="https://windows11.techidaily.com/ending-dual-access-to-your-camera-error-0xa00f4243/"><u>Ending Dual Access to Your Camera (Error 0xA00F4243)</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-hd-strategy-for-classics-gaming-on-windows-via-scummvm/"><u>The Ultimate HD Strategy for Classics Gaming on Windows via ScummVM</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-differences-of-fix-focused-tools-dism-sfc-and-chkdsk/"><u>Understanding Differences of Fix-Focused Tools: DISM, SFC & CHKDSK</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-strategy-become-system-admin-now/"><u>Swift Strategy: Become System Admin Now</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-update-codes-and-version-names-in-windows/"><u>Understanding Update Codes and Version Names in WINDOWS</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-create-custom-snap-layouts-in-windows-with-powertoys/"><u>How to Create Custom Snap Layouts in Windows With PowerToys</u></a></li>
<li><a href="https://windows11.techidaily.com/top-solutions-for-windows-pin-access-issues-10plus11/"><u>Top Solutions for Windows PIN Access Issues (10+11)</u></a></li>
<li><a href="https://windows11.techidaily.com/blocking-windows-update-prompts/"><u>Blocking Windows Update Prompts</u></a></li>
<li><a href="https://windows11.techidaily.com/crystal-clear-in-minutes-mastering-fuzzy-window-fixes/"><u>Crystal Clear in Minutes: Mastering Fuzzy Window Fixes</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-how-to-effortlessly-eradicate-unwanted-youtube-post-comments/"><u>[New] In 2024, How to Effortlessly Eradicate Unwanted Youtube Post-Comments</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-exploring-the-best-places-to-get-bell-ringing-sounds/"><u>New Exploring the Best Places to Get Bell Ringing Sounds</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-use-pokemon-go-joystick-on-tecno-spark-go-2024-drfone-by-drfone-virtual-android/"><u>How to use Pokemon Go Joystick on Tecno Spark Go (2024)? | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-change-your-apple-id-on-iphone-x-with-or-without-password-by-drfone-ios/"><u>In 2024, How To Change Your Apple ID on iPhone X With or Without Password</u></a></li>
<li><a href="https://youtube-web.techidaily.com/novice-to-pro-your-step-by-step-guide-to-youtube-live-images-for-2024/"><u>From Novice to Pro  Your Step-by-Step Guide to YouTube Live Images for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/7-fixes-for-unfortunately-phone-has-stopped-on-honor-play-7t-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Fixes for Unfortunately, Phone Has Stopped on Honor Play 7T | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-social-snack-spectacle-10-viral-food-trends/"><u>[Updated] Social Snack Spectacle  10 Viral Food Trends</u></a></li>
<li><a href="https://extra-tips.techidaily.com/choosing-the-best-action-cam-hero-vs-keymission-170-for-2024/"><u>Choosing the Best Action Cam  Hero Vs Keymission 170 for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/8-quick-fixes-unfortunately-snapchat-has-stopped-on-honor-play-40c-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Quick Fixes Unfortunately, Snapchat has Stopped on Honor Play 40C | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-unwrapping-utopia-creating-magical-unboxing-moments/"><u>[New] Unwrapping Utopia  Creating Magical Unboxing Moments</u></a></li>
</ul></div>
