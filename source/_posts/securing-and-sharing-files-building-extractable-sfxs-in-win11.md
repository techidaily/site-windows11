---
title: "Securing and Sharing Files: Building Extractable SFXs in Win11"
date: 2024-07-11T21:20:43.334Z
updated: 2024-07-12T21:20:43.334Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Securing and Sharing Files: Building Extractable SFXs in Win11"
excerpt: "This Article Describes Securing and Sharing Files: Building Extractable SFXs in Win11"
keywords: File Security Win11,Extract SFX Tools,Share Securely Windows,SFX Creation Techniques,Safe File Transfer WinXP,Building SFX Files,Enhanced File Sharing Win11
thumbnail: https://thmb.techidaily.com/d09e418474d756f5a8ffe485c9482504fd4de6868009955288d3f3888a8492e7.jpg
---

## Securing and Sharing Files: Building Extractable SFXs in Win11

 An SFX archive is a special type of self-extracting archive you can create on Windows platforms. It is an executable archive that users can extract without any third-party extraction tools.

 You can use such archives to share groups of files with other users via emails, which they can easily extract by double-clicking SFX packages. This is how you can set up a self-extracting SFX archive in Windows 11.

## How to Set Up an SFX Archive With Windows 11's IExpress Wizard

 Windows 11 includes an IExpress wizard with which you can set up an SFX. You can utilize that tool to set up SFX archives for extracting files only or ones that run installation commands. Selecting that wizard's**Extract files and run installation command** option enables you to set up archives for installing apps.

 This is how to create an SFX archive for extracting files only with IExpress Wizard in Windows 11:

1. Open your Start menu and click inside the search box on it.
2. Type**IExpress** within the search box.
3. Right-click the**IExpress** search result and open that wizard with elevated permissions by selecting**Run as administrator** .
4. Click the**Create new Self Extraction Directive** **file** radio button.  
![The Create new Self Extraction Directive file option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/create-self-extracting-option.jpg)
5. Select the**Extract files only** option and**Next** .  
![The Extract files only option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/extract-files-only.jpg)

1. Enter the title**SFX archive** for the package title and click**Next** .
2. A confirmation prompt for extracting is an optional extra, but it’s a good idea to add one. To do so, select "Prompt user with" and input a confirmation message like "Do you wish to extract archive?"  
![The Prompt user with radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/prompt-user-with-radio-button.jpg)
3. Click**Next** and select the**Do not display license** radio button.
4. Select**Next** again and then click the**Add** button. Hold the**Ctrl** key to choose all the files you want to include within the archive and click**Open** .  
![The Add file option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/extract-package-option.jpg)
5. Click**Next** to proceed to a Show window step. Select the**Default** (recommended) option there.
6. Then select**Next** again to go to the finish message step. As it’s not especially important to have a finishing message, select the**No message** radio button.

Now we can get started using IExpress Wizard:

1. Click**Next** and press the**Browse** button to select the folder that will include your archive.
2. Input**SFX archive** in the**File name** box to match the one entered at step six and click**Save** .  
![The Save as window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/save-as-window.jpg)
3. Press**Next** to reach the options for saving a SED. Click the**Don’t Save** option there.  
![The Create new Self Extraction Directive file option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/create-new-self-extracting-archive-option.jpg)
4. Click**Next** twice more to create the archive.
5. Wait for the package creation process to finish. Then click the Finish button on the IExpress wizard window.

### Testing the SFX Archive Made With IExpress

 Now try extracting the files from your new self-extracting archive. Open the folder you selected to save the archive in. Then double-click the SFX archive.exe archive package.

 A confirmation message will pop up if you set one up as instructed for step seven. Click**Yes** and then press the**Browse** button to select a folder to extract the files. Select**OK** to extract the files in the archive to the chosen folder. Then go to whatever folder you extracted the archive’s files in to open them from them.

![An SFX archive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/sfx-archive-prompt.jpg)

 Selecting the**Don’t save SED** option means you can’t modify the self-extracting archive after creating it. If you would prefer the archive to be editable, select the**Save Self Extraction Directive** option instead. Then you can change the archive later by selecting the**Open existing Self Extraction Directive** file radio button within IExpress Wizard.

## How to Set Up an SFX Archive With 7-ZIP

 7-Zip is a freely available third-party extraction utility for Windows with which you can also set up self-extracting archives. You can set up SFX archives that have variable compression levels with 7-Zip. That software also enables you to [encrypt your files](https://www.makeuseof.com/windows-encrypt-files-folders/) within SFX packages. These are the steps for setting up SFX archives with 7-Zip.

1. Go to [the 7-Zip](https://www.7-zip.org/download.html) download page.
2. Install Z-Zip on your PC.
3. Open the 7-Zip File Manager software, and navigate to a folder that includes some files to include in the archive within 7-Zip’s window.
4. Select multiple files to add to an SFX archive by holding the**Ctrl** key.
5. Click the**Add** button.  
![The Add button in 7-Zip](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/7-zip-file-manager-window.jpg)
6. Select the**Create SFX archive** checkbox.  
![The Add to Archive window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/add-to-archive-window.jpg)
7. Click the**Archive** box’s ellipses button.
8. Choose a folder to save the SFX archive in and click**Open** .
9. Input a file name within the**Archive** box.
10. Press the**OK** button to create your new self-extracting archive.

Testing the SFX File With 7-ZIP

 Check out the new self-extracting archive in whatever folder you saved it in. Double-clicking the archive will bring up a 7-Zip self-extracting archive window. Click the button for the**Extract to** box to select a folder. Then click**Extract** to access the archive’s files in the selected folder.

![A 7-Zip self-extracting archive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/7-zip-archive.jpg)

 If you want to set a password for the archive, you can do so within 7-Zip’s "Add to archive" window. Input some text in the**Enter password** box there. Then users will need to input a password after double-clicking the self-extracting archive. The archive will have an AES-256 encryption method set.

 By default, compression is set to a standard level five. However, you can change that by clicking the**Compression** level drop-down menu. Select**Maximum** or**Ultra** on that menu to increase the compression. However, those compression options are also the slowest.

![The Compression Level drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/compression-level-options.jpg)

 You can also configure the archive’s compression with the**Word size** and**Dictionary** options. Setting a higher**Dictionary size** setting increases the compression. A higher**Word size** setting can also enhance the compression ratio for the LZMA method.

## Share Your Files Within Self-Extracting SFX Archives

 It’s easy to set up self-extracting SFX archives with both IExpress and 7-Zip. Creating such archives will enable you to attach more files to emails because they reduce the overall attachment data sizes. Furthermore, recipients of such archives won’t need any extraction software installed to open them up.

 However, note that self-extracting SFX archives aren’t cross-platform compatible. Users can only extract the archives on the same platform in which it was created. So, make sure you send your SFX archives to users with Windows PCs.

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
<li><a href="https://screen-capture.techidaily.com/endless-visual-streaming-services-for-2024/"><u>Endless Visual Streaming Services for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-simplified-guide-to-transform-vimeo-video-into-mp3/"><u>In 2024, Simplified Guide to Transform Vimeo Video Into MP3</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-unleashing-productivity-comprehensive-guide-to-recording-skype-conversations/"><u>[Updated] Unleashing Productivity  Comprehensive Guide to Recording Skype Conversations</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-no-supported-devices-found-in-windows-11/"><u>Overcoming No Supported Devices Found in Windows 11</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-exploring-new-and-growing-tiktok-trends/"><u>[New] Exploring New and Growing TikTok Trends</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-detect-and-dislodge-suddenly-installed-rav-antivirus/"><u>How to Detect & Dislodge Suddenly Installed Rav Antivirus</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-endure-no-more-teams-login-troubles-in-windows/"><u>How to Endure No More Teams Login Troubles in Windows</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-video-splitting-made-easy-a-step-by-step-guide-for-windows-live-movie-maker/"><u>Updated Video Splitting Made Easy A Step-by-Step Guide for Windows Live Movie Maker</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-2024-approved-top-7-video-joiners-with-no-watermark-or-logo/"><u>Updated 2024 Approved Top 7 Video Joiners with No Watermark or Logo</u></a></li>
<li><a href="https://windows11.techidaily.com/pushing-boundaries-my-quest-to-overcome-app-guard-censorship/"><u>Pushing Boundaries: My Quest to Overcome App Guard Censorship</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-streamline-creation-with-no-cost-high-quality-banner-templates/"><u>In 2024, Streamline Creation with No-Cost, High-Quality Banner Templates</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-5-best-screen-recorders-for-windows-11/"><u>[New] In 2024, 5 Best Screen Recorders For Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/liberating-windows-past-a-set-of-three-tactics/"><u>Liberating Windows Past - A Set of Three Tactics</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-do-you-get-sun-stone-evolutions-in-pokemon-for-motorola-moto-g34-5g-drfone-by-drfone-virtual-android/"><u>How Do You Get Sun Stone Evolutions in Pokémon For Motorola Moto G34 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-steps-for-altering-terminal-preference/"><u>Essential Steps for Altering Terminal Preference</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-best-frame-rate-selection-for-effective-slow-motion-capture/"><u>In 2024, Best Frame Rate Selection for Effective Slow Motion Capture</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-click-rate-three-methods-for-mouse-double-click-tweaking/"><u>Enhance Click Rate: Three Methods for Mouse Double-Click Tweaking</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-workflow-in-windows-11-run-command-innovation-guide/"><u>Elevate Your Workflow in Windows 11: Run Command Innovation Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-access-to-any-language-hotkeys-for-efficient-translation-in-windows-os/"><u>Quick Access to Any Language: Hotkeys for Efficient Translation in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/fast-startup-mastery-in-windows-11-a-comprehensible-guide/"><u>Fast Startup Mastery in Windows 11 - A Comprehensible Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/leveling-web-speeds-for-seamless-experience/"><u>Leveling Web Speeds for Seamless Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/fast-track-eliminate-extra-software-in-windows-11/"><u>Fast Track: Eliminate Extra Software in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-system-limit-fixing-gpt-windows-problems/"><u>Overcoming System Limit: Fixing GPT Windows Problems</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/locating-recorded-sounds-of-wolf-vocalizations-for-2024/"><u>Locating Recorded Sounds of Wolf Vocalizations for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-through-samsung-flow-connected-life-for-devices/"><u>Navigate Through Samsung Flow - Connected Life for Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/personalizing-windows-space-adding-this-pc-iconography/"><u>Personalizing Windows Space: Adding 'This PC' Iconography</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-file-write-permissions-correction-on-win/"><u>Mastering File Write Permissions Correction on Win</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-after-switching-from-xiaomi-14-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data After Switching From Xiaomi 14 to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-prime-action-mic-choices-for-clear-videos/"><u>[Updated] Prime Action Mic Choices for Clear Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-set-up-linux-and-linux-apps-on-a-windows-pc/"><u>How to Set Up Linux and Linux Apps on a Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/overcome-windows-obstacles-expert-advice-awaits/"><u>Overcome Windows Obstacles: Expert Advice Awaits!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-invisible-displays-when-gaming-on-win-os/"><u>Preventing Invisible Displays When Gaming on Win OS</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tuning-taskbars-date-and-time-presentation/"><u>Fine-Tuning Taskbar's Date & Time Presentation</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-productivity-with-windows-11-calendar/"><u>Maximizing Productivity with Windows 11 Calendar</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reactivate-lost-bluetooth-listings-dmi/"><u>How to Reactivate Lost Bluetooth Listings DMI</u></a></li>
<li><a href="https://extra-resources.techidaily.com/expert-techniques-for-enhanced-minecraft-zooms/"><u>Expert Techniques for Enhanced Minecraft Zooms</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-the-hidden-potential-in-windows-powertoys-10-applications/"><u>Discover the Hidden Potential in Windows PowerToys' 10 Applications</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-your-ultimate-source-list-the-top-picks-of-copyright-friendly-comic-soundtracks-websites-for-2024/"><u>Updated Your Ultimate Source List The Top Picks of Copyright-Friendly Comic Soundtracks Websites for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-10-best-spy-watches-for-your-oppo-find-n3-flip-drfone-by-drfone-virtual-android/"><u>In 2024, Top 10 Best Spy Watches For your Oppo Find N3 Flip | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/modifying-failed-login-lockout-timer-in-windows-1011/"><u>Modifying Failed Login Lockout Timer in Windows 10/11</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-secure-and-sync-your-cinematic-recordings-across-platforms/"><u>In 2024, Secure and Sync Your Cinematic Recordings Across Platforms</u></a></li>
<li><a href="https://windows11.techidaily.com/n-series-window-enigma-deciding-factors/"><u>N-Series Window Enigma: Deciding Factors</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-app-management-in-windows-the-power-of-winget/"><u>Mastering App Management in Windows: The Power of Winget</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-bridging-language-barriers-windows-media-player-subtitle-guide/"><u>2024 Approved  Bridging Language Barriers  Windows Media Player Subtitle Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/perfectly-presented-photos-mastering-the-art-of-crafting-captivating-slideshows-in-win11-photos-app/"><u>Perfectly Presented Photos: Mastering the Art of Crafting Captivating Slideshows in Win11 Photos App</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-new-submenus-to-windows-11s-desktop-context-menu/"><u>How to Add New Submenus to Windows 11’S Desktop Context Menu</u></a></li>
</ul></div>
