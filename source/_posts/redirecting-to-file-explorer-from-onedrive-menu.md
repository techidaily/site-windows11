---
title: Redirecting to File Explorer From OneDrive Menu
date: 2024-07-11T21:46:56.601Z
updated: 2024-07-12T21:46:56.601Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Redirecting to File Explorer From OneDrive Menu
excerpt: This Article Describes Redirecting to File Explorer From OneDrive Menu
keywords: Redirect OneDrive FS,File Explorer Share,ONEDRIVE Open Files,Direct OneDrive Explorer,Access Files OneDrive,Navigate OneDrive FS,OneDrive to Explorer
thumbnail: https://thmb.techidaily.com/74722f9cb9d89019ce2bd2f1c80c266bfc2adc6c2152da5539a4a5d5cb3e57e3.jpg
---

## Redirecting to File Explorer From OneDrive Menu

 When you launch Windows File Explorer, it automatically takes you to the "Quick Access" view. This page displays shortcuts to recently accessed folders and files and lists your favorite folders. It might be convenient for some users but not for others who prefer easy access to their cloud storage.

 Read this comprehensive guide if you want File Explorer to open OneDrive instead of Quick Access.

## 1\. Use the Folder Options

 If you want to make OneDrive the starting point of your File Explorer, you can do so using folder options. Here's how to do it:

1. Open the Start menu and type **File Explorer** in the search box. When the File Explorer icon appears, click it to launch the app. You can also use **Win + E** to open the program quickly.
2. In the File Explorer window, look for **See more** (three dots) at the top. Clicking on it opens the Folder Options dialog box.  
![Open Folder Options in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-folder-options-in-file-explorer.jpg)
3. On the General tab, click the **Open File Explorer to** drop-down menu and select "Username Personal". Here, "Username" refers to your Windows account name.  
![Open File Explorer to OneDrive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-file-explorer-to-onedrive.jpg)
4. Click **Apply** \> **OK** to close the dialog box.

 From now on, opening File Explorer will automatically launch OneDrive rather than Quick Access.

## 2\. Using the Registry Editor

 You can also use the Registry Editor to set OneDrive as your default File Explorer view. But be warned: if you make an incorrect change to the system registry, you could damage your computer. We recommend [backing up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it.

 Once backed up, follow these steps to make OneDrive the default view:

1. [Open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **regedit** in the text box and hit **Enter**.
3. If you're prompted for permission, select **Yes** to continue. The Registry Editor window will open.
4. In the Registry Editor window, navigate to this path:  
`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. In the right pane, locate and double-click the **LaunchTo** entry. If the entry isn't present, you'll need to create it. For that, right-click on the **Advanced** folder and select **New > DWORD (32-bit) Value**. Name the value "LaunchTo" and press Enter. Doing so will create a new DWORD in the registry.  
![Set File Explorer to Open OneDrive Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/set-file-explorer-to-open-onedrive-using-registry.jpg)
6. Double-click on this newly created value and set its value to **4**.
7. Click **OK** and close the registry window.

 After that, restart your computer for the changes to take effect. Once your PC restarts, launch File Explorer. With this method, you will launch File Explorer directly to your cloud storage without navigating through Quick Access.

## 3\. Using a Reg File

 The third and final method to set OneDrive as the default view involves using a reg file. It contains the necessary instructions that modify the registry on your behalf. So, if you're not comfortable using the registry editor, this is the right way to go.

 To create the reg file, follow these steps:

1. Right-click on your desktop and select **New > Text Document**.
2. Name the file **OneDrive.reg** and hit **Enter**.
3. Now open the file in a text editor such as Notepad.
4. Copy and paste the following code into the text document:  
`<code>Windows Registry Editor Version 5.00  

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced]  
"LaunchTo"=dword:00000004`
5. After pasting the given code, click **File** \> **Save as**.
6. In the Save as dialog box, select **All files** from the Save as type drop-down menu and hit Enter. Make sure the file is saved as a **.reg** file and not as a .txt file.  
![Open File Explorer to OneDrive Using REG File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-file-explorer-to-onedrive-using-reg-file.jpg)
7. Double-click the REG file you just created. If you're prompted for permission to change your computer, click **Yes**.
8. Finally, restart your computer for the changes to take effect.

 After your system restarts, launch File Explorer. You'll see OneDrive as the main view instead of Quick Access.

## Set File Explorer to Open OneDrive Instead of Quick Access

 There you have it; three different methods to make OneDrive your default File Explorer view. If you like, you can also change other folder views, such as Downloads or This PC, using the same techniques we discussed above. I hope this guide helped you get things done quickly and easily.

 Read this comprehensive guide if you want File Explorer to open OneDrive instead of Quick Access.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/the-ultimate-list-of-6-performance-monitor-apps-for-pcs/"><u>The Ultimate List of 6 Performance Monitor Apps For PCs</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-comprehensive-guide-to-top-5-free-windows-screen-recorders/"><u>2024 Approved  Comprehensive Guide to Top 5 Free Windows Screen Recorders</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-adjusting-touchpad-sensitivity-in-windows/"><u>The Ultimate Guide to Adjusting Touchpad Sensitivity in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-lost-nvidia-configuration-a-guide-for-winx-users/"><u>Restoring Lost NVIDIA Configuration: A Guide for WinX Users</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-best-10-apps-to-enhance-your-instagram-story-slideshow/"><u>Updated Best 10 Apps to Enhance Your Instagram Story Slideshow</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-spotify-location-after-moving-to-another-country-on-apple-iphone-se-2020-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Change Spotify Location After Moving to Another Country On Apple iPhone SE (2020) | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-audiophiles-choice-premium-asmr-recording-mics/"><u>[New] Audiophiles' Choice  Premium ASMR Recording Mics</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-tips-for-optimizing-wsl-2-on-modern-windows/"><u>Top 5 Tips for Optimizing WSL 2 on Modern Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-windows-update-failure-error-0x8024800c/"><u>Correcting Windows Update Failure (Error 0X8024800C)</u></a></li>
<li><a href="https://windows11.techidaily.com/access-control-microphone-and-camera-via-edge-protection/"><u>Access Control: Microphone and Camera via Edge Protection</u></a></li>
<li><a href="https://windows11.techidaily.com/reveal-hidden-5ghz-networks-on-windows-11-quick-remedies/"><u>Reveal Hidden 5GHz Networks on Windows 11: Quick Remedies</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-windows-no-audio-output-issue/"><u>Solving Windows: 'No Audio Output' Issue</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-the-ultimate-guide-to-vocalizing-your-tiktok-content/"><u>2024 Approved  The Ultimate Guide to Vocalizing Your TikTok Content</u></a></li>
<li><a href="https://windows11.techidaily.com/split-screen-style-selecting-separate-themes-for-each-windows-display/"><u>Split Screen Style: Selecting Separate Themes for Each Windows Display</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-up-a-permanent-delete-toolbar-in-windows-1011s-trash/"><u>Setting Up a Permanent Delete Toolbar in Windows 10/11'S Trash</u></a></li>
<li><a href="https://windows11.techidaily.com/caution-not-to-use-chatbots-for-windows-key-formation/"><u>Caution: Not to Use Chatbots For Windows Key Formation</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/iphone-tips-achieve-softened-images-in-4-easy-steps/"><u>IPhone Tips  Achieve Softened Images in 4 Easy Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/reconciling-windows-game-bar-with-inferior-hardware/"><u>Reconciling Windows Game Bar with Inferior Hardware</u></a></li>
<li><a href="https://windows11.techidaily.com/silencing-the-cacophony-soundcard-irq-fixes/"><u>Silencing the Cacophony: Soundcard IRQ Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-image-enhancement-building-engaging-slideshows-and-fixing-windows-11-photo-flaws/"><u>The Art of Image Enhancement: Building Engaging Slideshows & Fixing Windows 11 Photo Flaws</u></a></li>
<li><a href="https://windows11.techidaily.com/altering-winterrals-visual-theme/"><u>Altering WinTerral's Visual Theme</u></a></li>
<li><a href="https://windows11.techidaily.com/revitalizing-fall-guys-gaming-experience-after-disconnections-on-windows/"><u>Revitalizing Fall Guys Gaming Experience After Disconnections on Windows</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-boost-your-brand-twitter-ads-guide-for-2024/"><u>[Updated] Boost Your Brand  Twitter Ads Guide for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-from-everyday-snaps-to-professional-videos-the-top-9-mobile-filmmaking-gadgets/"><u>[New] 2024 Approved  From Everyday Snaps to Professional Videos - The Top 9 Mobile Filmmaking Gadgets</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-closed-folder-issues-via-double-clicks-in-w10w11/"><u>Resolving Closed Folder Issues via Double-Clicks in W10/W11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-disabling-onedrive-icon-on-windows-11-explore/"><u>Strategies for Disabling OneDrive Icon on Windows 11 Explore</u></a></li>
<li><a href="https://windows11.techidaily.com/best-windows-11-weather-software-compared/"><u>Best Windows 11 Weather Software Compared</u></a></li>
<li><a href="https://windows11.techidaily.com/refinement-of-your-touchpad-settings-for-optimal-interaction/"><u>Refinement of Your Touchpad Settings for Optimal Interaction</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-forth-the-lost-frames-off-screen-recovery-in-edge-os/"><u>Bring Forth the Lost Frames: Off-Screen Recovery in Edge OS</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-elevate-with-25-customization-tips/"><u>Windows 11: Elevate with 25 Customization Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/tricks-save-and-access-onedrive-around-clients/"><u>Tricks: Save & Access OneDrive Around Clients</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-11-eliminating-invisible-logins/"><u>Troubleshooting Windows 11: Eliminating Invisible Logins</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-resizing-discover-the-top-six-efficient-methods/"><u>Windows 11 Resizing: Discover the Top Six Efficient Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-win1011-system-breakdown-code-0xc0000001/"><u>Addressing Win10/11 System Breakdown: Code 0xC0000001</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-code-0x0001-complication-in-windows-11/"><u>Unraveling Code 0X0001 Complication in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-meaning-of-0xc000003e-hexadecimal-errors/"><u>Decoding the Meaning of 0xC000003E Hexadecimal Errors</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-unhandled-exception-strategies-to-mitigate-on-pc/"><u>Simplifying Unhandled Exception: Strategies to Mitigate on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/change-to-dark-theme-in-the-windows-calculator/"><u>Change to Dark Theme in the Windows Calculator</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionize-your-security-crafting-unique-lock-patterns-for-windows-11/"><u>Revolutionize Your Security: Crafting Unique Lock Patterns for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-complete-gamers-manual-to-winning-with-windows/"><u>The Complete Gamers' Manual to Winning With Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-search-bar-autonomy-in-windows-11-interface/"><u>Preventing Search Bar Autonomy in Windows 11 Interface</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-in-2024-master-the-art-of-costless-sound-transformation-and-advanced-audio-editing-in-filmora-videos/"><u>New In 2024, Master the Art of Costless Sound Transformation and Advanced Audio Editing in Filmora Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-windowed-discord-for-flawless-search-experience/"><u>Optimizing Windowed Discord for Flawless Search Experience</u></a></li>
<li><a href="https://android-unlock.techidaily.com/can-i-bypass-a-forgotten-phone-password-of-meizu-21-by-drfone-android/"><u>Can I Bypass a Forgotten Phone Password Of Meizu 21?</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-the-journey-to-high-end-gaming-with-disconitro-on-discord/"><u>[Updated] 2024 Approved  The Journey to High-End Gaming with DiscoNitro on Discord</u></a></li>
<li><a href="https://windows11.techidaily.com/break-the-silence-of-a-disconnected-usb-wi-fi-adapter-on-pcs/"><u>Break the Silence of a Disconnected USB Wi-Fi Adapter on PCs</u></a></li>
</ul></div>
