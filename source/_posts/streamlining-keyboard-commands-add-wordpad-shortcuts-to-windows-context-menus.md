---
title: "Streamlining Keyboard Commands: Add Wordpad Shortcuts to Window's Context Menus"
date: 2024-09-09T12:09:21.822Z
updated: 2024-09-10T12:09:21.822Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Streamlining Keyboard Commands: Add Wordpad Shortcuts to Window's Context Menus"
excerpt: "This Article Describes Streamlining Keyboard Commands: Add Wordpad Shortcuts to Window's Context Menus"
keywords: Keyboard Shortcuts Windows,WordPad Menu Access,Streamline Command Input,Context Menu Enhancement,Efficient Typing Tips,Window Navigation Commands,Advanced Text Editing
thumbnail: https://thmb.techidaily.com/ecc3916e90aab64f99ff84f9c45d036bcf1e08682351feaa92b6a0ff146b14b9.jpg
---

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115947/19272" target="_top" id="2115947">
  <img src="//a.impactradius-go.com/display-ad/19272-2115947" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115947/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Streamlining Keyboard Commands: Add Wordpad Shortcuts to Window's Context Menus

 Windows' WordPad app is either a limited word processor or an advanced text editor depending on how you look at it. Unlike Notepad, WordPad is a rich text editor that incorporates formatting and styling options for content. Therefore, it is a preferable alternative to Notepad for opening and editing TXT and RTF files.

 As such, you might want to add WordPad shortcuts to Windows 11’s context menu, so you can quickly access WordPad and open TXT/RTF documents with it. This is how you can set up context menu shortcuts for launching WordPad and opening files in it.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2120867/26400?prodsku=mars" target="_top" id="2120867">
  <img src="//a.impactradius-go.com/display-ad/26400-2120867" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2120867/26400?prodsku=mars" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135404/19272" target="_top" id="2135404">
  <img src="//a.impactradius-go.com/display-ad/19272-2135404" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135404/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
9. Enter**wordpad.exe %1** in the**Value** box, and click**OK** to apply.  
![The wordpad.exe value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-wordpad-exe-value-data.jpg)

 Now you can close the Registry Editor and try out the**Open with WordPad** context menu shortcut. Launch File Explorer (see[how to launch File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) ), and navigate to a folder containing some TXT or RTF files. Right-click an RTF or TXT document and select**Show more options** . Click**Open with WordPad** to bring up the right-clicked document in that app.

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/1995803/22899" target="_top" id="1995803">
  <img src="//a.impactradius-go.com/display-ad/22899-1995803" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/1995803/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Erase the WordPad Context Menu Shortcuts

 If you ever change your mind about having WordPad context menu options, you can remove them by deleting their keys. To do so, you’ll need to open the following key locations in the Registry Editor:

`Computer\HKEY_CLASSES_ROOT\*\shell\Open with WordPad\command  
Computer\HKEY_CLASSES_ROOT\Directory\Background\shell\WordPad\command`

 Then right-click the**Open with WordPad** or**WordPad** key to select a**Delete** option. A dialogue box will open requesting confirmation to erase. Select**Yes** if you’re sure about deleting the key.

![The Delete option for registry keys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-delete-option2.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134249/18498" target="_top" id="2134249">
  <img src="//a.impactradius-go.com/display-ad/18498-2134249" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134249/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<span id="1938136">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1938136.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1938136">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1938136.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1938136%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1938136/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://twitter-videos.techidaily.com/new-cross-social-smiles-top-meme-picks-on-reddit-and-twitter/"><u>[New] Cross-Social Smiles Top Meme Picks on Reddit & Twitter</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-securely-amplifying-your-tiktok-presence-wisely/"><u>[New] In 2024, Securely Amplifying Your TikTok Presence Wisely</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-ultimate-guide-for-sustainable-visual-recording/"><u>[New] In 2024, Ultimate Guide for Sustainable Visual Recording</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-leveraging-brand-partnerships-for-youtube-content-creators/"><u>[New] Leveraging Brand Partnerships for YouTube Content Creators</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-struggle-to-cultivate-freshness-in-vr-realms/"><u>[New] The Struggle to Cultivate Freshness in VR Realms</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-the-ultimate-guide-to-mobile-snapchat-recording/"><u>[Updated] 2024 Approved The Ultimate Guide to Mobile Snapchat Recording</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-2024-approved-visual-jokes-on-the-go-no-cost-with-creatememe/"><u>[Updated] 2024 Approved Visual Jokes on the Go No Cost with CreateMeme</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-capture-the-magic-our-list-of-top-12-cameras-for-exceptional-vlogs-for-2024/"><u>[Updated] Capture the Magic Our List of Top 12 Cameras for Exceptional Vlogs for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-incorporate-subtitles-for-improved-viewing-wmp-guide/"><u>[Updated] Incorporate Subtitles for Improved Viewing WMP Guide</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-compilation-of-top-5-mkv-apps-for-mac/"><u>2024 Approved Compilation of Top 5 MKV Apps for Mac</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/conversion-gratuita-de-video-wmv-a-mp4-en-linea-metodos-eficientes-para-todos-los-dispositivos/"><u>Conversión Gratuita De Video WMV a MP4 en Línea: Métodos Eficientes Para Todos Los Dispositivos</u></a></li>
<li><a href="https://win-forum.techidaily.com/discover-enhanced-system-cleaning-capabilities-with-revo-uninstaller-pro-v5-update/"><u>Discover Enhanced System Cleaning Capabilities with Revo Uninstaller Pro v5 Update</u></a></li>
<li><a href="https://games-able.techidaily.com/elevate-xbox-graphics-with-an-additional-laptop-screen/"><u>Elevate Xbox Graphics with an Additional Laptop Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/establishing-kids-internet-freedom-boundaries-on-windows-11/"><u>Establishing Kids' Internet Freedom Boundaries on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-insights-into-the-world-of-hdr-technology-for-windows-11/"><u>Expert Insights Into the World of HDR Technology for Windows 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/find-businesses-and-events-amidst-you-the-poi-guide-for-savvy-travelers/"><u>Find Businesses and Events Amidst You - The POI Guide for Savvy Travelers</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-empty-directory-problem-microsofts-0x80070091-error-explained/"><u>Fixing 'Empty Directory' Problem - Microsoft's 0X80070091 Error Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/harmonizing-your-win-key-with-microsoft-profile-access/"><u>Harmonizing Your WIN Key with Microsoft Profile Access</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-your-apple-iphone-11-pro-location-on-twitter-drfone-by-drfone-virtual-ios/"><u>How to Change your Apple iPhone 11 Pro Location on Twitter | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-elevate-windows-11-audio-capabilities-dolby-atmos/"><u>How to Elevate Windows 11 Audio Capabilities - Dolby Atmos</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-eliminate-0x800700e9-on-xbox-game-pass-and-windows-11/"><u>How to Eliminate 0X800700E9 on Xbox Game Pass & Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-make-sure-your-temp-folder-is-valid-error-in-windows-11/"><u>How to Fix the Make Sure Your Temp Folder Is Valid Error in Windows 11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-infinix-zero-5g-2023-turbo-phone-without-any-data-loss-by-drfone-android/"><u>How to Unlock Infinix Zero 5G 2023 Turbo Phone without Any Data Loss</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-additional-tips-about-sinnoh-stone-for-oppo-find-x6-drfone-by-drfone-virtual-android/"><u>In 2024, Additional Tips About Sinnoh Stone For Oppo Find X6 | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-your-tecno-pop-7-pro-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Your Tecno Pop 7 Pro Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-the-top-8-tiktok-hacks-for-maximizing-income/"><u>In 2024, The Top 8 TikTok Hacks for Maximizing Income</u></a></li>
<li><a href="https://windows11.techidaily.com/insights-into-ftdibussys-windows-memory-safeguard-breach/"><u>Insights Into ftdibus.sys: Windows' Memory Safeguard Breach</u></a></li>
<li><a href="https://windows11.techidaily.com/is-windows-subsystem-pivotal-for-linux-desktops/"><u>Is Windows Subsystem Pivotal for Linux Desktops?</u></a></li>
<li><a href="https://windows11.techidaily.com/master-quick-settings-with-ease-on-your-win-11-pc/"><u>Master Quick Settings with Ease on Your Win 11 PC</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-network-access-enabling-telnet-on-win-10-and-11/"><u>Mastering Network Access: Enabling Telnet on Win 10 and 11</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-split-your-videos-with-ease-top-5-free-mpeg-splitters/"><u>New In 2024, Split Your Videos with Ease Top 5 Free MPEG Splitters</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-your-pcs-auditory-experience-with-updated-drivers-guide/"><u>Optimize Your PC's Auditory Experience with Updated Drivers Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/powershell-mastery-for-windows-administrators/"><u>PowerShell Mastery for Windows Administrators</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-auto-opens-of-windows-11s-search-bar/"><u>Preventing Auto-Opens of Windows 11'S Search Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/proactive-measures-to-increase-virtual-memory-in-windows-11-operations/"><u>Proactive Measures to Increase Virtual Memory in Windows 11 Operations</u></a></li>
<li><a href="https://windows11.techidaily.com/resetting-and-redoing-reactivating-ms-store-for-windows-users/"><u>Resetting and Redoing: Reactivating MS Store for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-functionality-of-your-windows-11-key/"><u>Restoring Functionality of Your Windows 11 Key</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-ultimate-voice-changer-a-detailed-manual-on-morphvox-transformation-for-2024/"><u>The Ultimate Voice Changer A Detailed Manual on MorphVOX Transformation for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-windows-defense-plan-7-methods/"><u>The Ultimate Windows Defense Plan (7 Methods)</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-system-calls-failure-on-win1011/"><u>Troubleshooting System Calls Failure on Win10/11</u></a></li>
<li><a href="https://some-skills.techidaily.com/understanding-periscope-features-pricing-and-how-to-join-for-2024/"><u>Understanding Periscope Features, Pricing & How To Join for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unfreezing-wow-update-windows-troubleshooting-guide/"><u>Unfreezing WoW Update: Windows Troubleshooting Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-system32-location-in-windows-11/"><u>Unveiling System32 Location in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-resetting-how-to-bring-back-microsoft-store-apps/"><u>Win 11 Resetting: How to Bring Back Microsoft Store Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-streamline-your-screens-with-a-three-column-board-setup/"><u>Windows 11: Streamline Your Screens with a Three-Column Board Setup</u></a></li>
</ul></div>
