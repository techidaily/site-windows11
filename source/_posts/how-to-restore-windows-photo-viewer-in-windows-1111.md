---
title: How to Restore Windows Photo Viewer in Windows 11/11
date: 2024-07-11T21:35:08.862Z
updated: 2024-07-12T21:35:08.862Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Restore Windows Photo Viewer in Windows 11/11
excerpt: This Article Describes How to Restore Windows Photo Viewer in Windows 11/11
keywords: Win11PhotoViewerRestore,Windows11PhotoViewError,FixWindowsPhotosVC,PhotoVCWin11Fix,VCRestorationWindows11,ReinstatePhotoVCWin,WindowsPhotosVCRepair
thumbnail: https://thmb.techidaily.com/d08434487f817b4e37cfe7558cadbd43386d2a1219d74867c43320f3c0faf48e.jpg
---

## How to Restore Windows Photo Viewer in Windows 11/11

### Quick Links

* [How to Restore Windows Photo Viewer in Windows 10/11 Using the Registry](#how-to-restore-windows-photo-viewer-in-windows-10-11-using-the-registry)
* [How to Disable Windows Photo Viewer in Windows 10 and 11](#how-to-disable-windows-photo-viewer-in-windows-10-and-11)
* [Use One Photo Viewer](#use-one-photo-viewer)

### Key Takeaways

* Microsoft replaced the classic Windows Photo Viewer app in Windows 10 and 11 with the new Photos app.
* Fortunately, you can restore Windows Photo Viewer on your Windows computer using a registry hack.
* Additionally, you could try a third-party Windows Photo Viewer alternative like One Photo Viewer, as it offers a clean UI, better performance, and more features.

 Microsoft replaced the classic Photo Viewer app in Windows 10 and 11 with Photos, its modern, feature-rich image viewer. However, if you liked the simplicity of Photo Viewer, here's how you can bring it back in Windows 10 and 11\.

## How to Restore Windows Photo Viewer in Windows 10/11 Using the Registry

 You can enable the classic Windows Photo Viewer app using a Windows Registry script. The following Windows Registry script reconfigures and enables the Windows Photo Viewer app.

 Modifying your Windows Registry involves risk as incorrect modifications can cause your system to malfunction. If you intend to proceed with the steps below, first [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and [back up your Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). This will help you to recover your system if something goes wrong.

1. Press **Win + R** to open the **Run** dialog. Input **notepad** and click **OK**.
2. Copy and paste the following script into the Notepad file. This script activates the Windows Photo Viewer.  
`Windows Registry Editor Version 5.00 [HKEY_CLASSES_ROOT\Applications\Windowsphotoviewer.dll\shell\open] "MuiVerb"="@Windowsphotoviewer.dll,-3043" [HKEY_CLASSES_ROOT\Applications\Windowsphotoviewer.dll\shell\open\command] @="\"%SystemRoot%\\System32\\rundll32.exe\" \"%ProgramFiles%\\Windows Photo Viewer\\PhotoViewer.dll\", ImageView_Fullscreen %1" [HKEY_CLASSES_ROOT\Applications\Windowsphotoviewer.dll\shell\open\DropTarget] "Clsid"="{FFE2A43C-56B9-4bf5-9A79-CC6D4285608A}" [HKEY_CLASSES_ROOT\Applications\Windowsphotoviewer.dll\shell\print\command] @="\"%SystemRoot%\\System32\\rundll32.exe\" \"%ProgramFiles%\\Windows Photo Viewer\\PhotoViewer.dll\", ImageView_PrintTo %1" [HKEY_CLASSES_ROOT\Applications\Windowsphotoviewer.dll\shell\print\DropTarget] "Clsid"="{60fd46de-f830-4894-a628-6fa81bc0190d}"`  
![Notepad App Showing a Written Registry Script in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/notepad-app-showing-a-written-registry-script-in-windows-11.png)
3. Press **Ctrl + Shift + S** to open the **Save** dialog. Alternatively, go to **File > Save As**.
4. In the **Save as** dialog, enter **ActivateWindowsPhotoViewer.reg** as the file name. Click the **Save as** **type** drop-down and choose **All Files(\*.\*)**. Choose a location and **Save** the file to your drive.  
![Notepad App Showing a Save As Dialog in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/notepad-app-showing-a-save-as-dialog-in-windows-11.png)
5. Next, open **File Explorer**, browse to the location where you saved the file, double-click **ActivateWindowsPhotoViewer.reg**, and then click **Yes**. When a warning prompt appears, click **Yes**.
6. After the script is executed, you'll see a success message. Click **OK**.
7. To apply the changes, press **Win + X** to open the **Windows Power** **menu** and choose **Task Manager**.
8. In the **Process** tab, find and right-click on **Windows Explorer**, then click **Restart**. Your screen may flash momentarily as Windows Explorer restarts.  
![Windows 11 Task Manager Showing Restart Option for Windows Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-task-manager-showing-restart-option-for-windows-explorer.png)

 Since Windows Photos Viewer doesn't have its own .EXE file, [but only a .DLL](https://www.makeuseof.com/what-are-dll-files-on-windows/), you can't open it from the search bar in Windows. Instead, to open pictures in Photo Viewer, right-click on any image in **File Explorer**, go to **Open With > Choose another app**, and then scroll down and select **Windows Photo Viewer**. Choose **Just once** to open the image. If you select **Always**, Windows will set Photo Viewer as the default app for that image format.

![File Explorer Choose Another App Menu Showing Windows Photo Viewer App Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/file-explorer-choose-another-app-menu-showing-windows-photo-viewer-app-option.png)

## How to Disable Windows Photo Viewer in Windows 10 and 11

 To disable Windows Photo Viewer, you must undo the changes you made earlier to the Windows Registry. It's worth making a backup again before making the changes. Then:

1. Press **Win + R** to open the **Run** dialog. Input **notepad** and click **OK**.
2. Copy and paste the following script into the notepad file:  
`Windows Registry Editor Version 5.00 [-HKEY_CLASSES_ROOT\Applications\Windowsphotoviewer.dll]`  
![Notepad App Showing a Registry Script to Disable Windows Photo Viewer in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/notepad-app-showing-a-registry-script-to-disable-windows-photo-viewer-in-windows-11.png)
3. Press **Ctrl + Shift + S** to open the **Save** dialog.
4. Type **DeactivateWindowsPhotoViewer.reg** as the file name. Click the **Save as type** drop-down, choose **All files (\*.\*)**, then click **Save**.  
![Notepad App Showing a Save As Dialog to Disable Windows Photo Viewer in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/notepad-app-showing-a-save-as-dialog-to-disable-windows-photo-viewer-in-windows-11.png)
5. Double-click **DeactivateWindowsPhotoViewer.reg** to execute the script and follow the on-screen instructions.

 Once done, [restart Windows Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/), and the Photo Viewer app will be disabled.

## Use One Photo Viewer

![One Photo Viewer App Showing Right-Click Context Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/one-photo-viewer-app-showing-right-click-context-menu.png)

 One Photo Viewer is an excellent Windows Photo Viewer and [Windows Photos alternative](https://www.makeuseof.com/best-windows-10-photos-app-alternatives/). It's fast, free, and offers a clean interface by placing all the controls in the context menu, decluttering the toolbar area. Right-click the app interface to view the menu and access all the tools and settings.

 One Photo Viewer offers all the bells and whistles you expect of an image viewer, plus more. You can scroll through the images using the arrow keys or the dedicated buttons, zoom in and out, rotate, crop, resize, or adjust colors.

 It also supports RAW formats, including HEIC and WEBP animation, a slideshow from a folder or loaded images, custom keyboard shortcuts, and a color correction tool to make quick enhancements. You can also opt for the $3 Pro version to get two additional features: a toolbar for improved functionality and thumbnails for easier navigation.

**Download:** [One Photo Viewer](https://apps.microsoft.com/detail/9PM6W4F0XW3H) (Free, premium version available)

 That said, if you prefer to stick with a native option, give the built-in Windows Photos app another shot. It's not as bad as you may think upon first use.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-data.techidaily.com/ed-2024-approved-enhancing-video-impact-interpreting-youtube-metrics-wisely/"><u>[Updated] 2024 Approved  Enhancing Video Impact  Interpreting YouTube Metrics Wisely</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-routes-to-printer-control-in-windows-11-max-50-chars/"><u>Efficient Routes to Printer Control in Windows 11 (Max 50 Chars)</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/revolutionary-approaches-to-share-fb-videos-on-whatsapp/"><u>Revolutionary Approaches to Share FB Videos on WhatsApp</u></a></li>
<li><a href="https://windows11.techidaily.com/1719217852527-solve-low-brightness-woes-in-windows-11-easily/"><u>Solve Low-Brightness Woes in Windows 11 Easily!</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-tweaking-mouse-speeds-in-win-1011/"><u>The Ultimate Guide to Tweaking Mouse Speeds in Win 10/11</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-elevate-your-online-video-quality-mastery-in-finalcut-for-youtube/"><u>[Updated] 2024 Approved  Elevate Your Online Video Quality  Mastery in FinalCut for YouTube</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-videos-from-tecno-phantom-v-flip-by-fonelab-android-recover-video/"><u>How to Rescue Lost Videos from Tecno Phantom V Flip</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/effortless-fb-movie-access-top-8-tools-of-23/"><u>Effortless FB Movie Access  Top #8 Tools of '23</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-becoming-a-bull-or-bear-best-stock-vids-on-youtube/"><u>[Updated] In 2024, Becoming a Bull or Bear  Best Stock Vids on YouTube</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-odins-last-hope-the-ragnarok-revelation/"><u>[Updated] In 2024, Odin's Last Hope  The Ragnarok Revelation</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-your-experience-altering-device-settings-in-windows-11/"><u>Customize Your Experience: Altering Device Settings in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resurrect-a-dormant-windows-tab-key/"><u>Steps to Resurrect a Dormant Windows Tab Key</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/1714211965931-new-2024-approved-avs-video-editor-review-does-it-live-up-to-expectations/"><u>New 2024 Approved AVS Video Editor Review Does It Live Up to Expectations?</u></a></li>
<li><a href="https://windows11.techidaily.com/chronicle-of-windows-seven-enduring-traits-in-the-new-era-of-11/"><u>Chronicle of Windows: Seven Enduring Traits in the New Era of 11</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-update-codes-and-version-names-in-windows/"><u>Understanding Update Codes and Version Names in WINDOWS</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/viral-visualization-top-story-filter-guide-for-2024/"><u>Viral Visualization  Top Story Filter Guide for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-why-does-the-pokemon-go-battle-league-not-available-on-motorola-moto-g13-drfone-by-drfone-virtual-android/"><u>In 2024, Why does the pokemon go battle league not available On Motorola Moto G13 | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-groupcapture-hd-toolkit-fb-edition/"><u>[New] 2024 Approved  GroupCapture HD Toolkit, FB Edition</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/multiformat-manual-effortless-conversion-of-srt-files-for-2024/"><u>Multiformat Manual  Effortless Conversion of SRT Files for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-windows-index-settings/"><u>Configuring Windows Index Settings</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-revolutionize-digital-diaries-with-complimentary-tools/"><u>In 2024, Revolutionize Digital Diaries with Complimentary Tools</u></a></li>
<li><a href="https://vp-tips.techidaily.com/melodic-moments-to-augment-your-status/"><u>Melodic Moments to Augment Your Status</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/eliminate-video-card-errors-from-minecraft/"><u>Eliminate Video Card Errors From Minecraft</u></a></li>
<li><a href="https://windows11.techidaily.com/escape-without-errors-tips-for-a-well-functioning-key-on-windows/"><u>Escape Without Errors: Tips for a Well-Functioning Key on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-limitations-for-power-use-in-winos/"><u>Bypassing Limitations for Power Use in WinOS</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-from-clicks-to-cash-the-journey-of-youtubes-ajay-nagar-for-2024/"><u>[Updated] From Clicks to Cash  The Journey of YouTube's Ajay Nagar for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-to-open-adobe-ps-in-w11-after-updates/"><u>Step-by-Step to Open Adobe PS in W11 After Updates</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-in-2024-size-matters-how-aspect-ratio-influences-your-youtube-videos-engagement/"><u>New In 2024, Size Matters How Aspect Ratio Influences Your YouTube Videos Engagement</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-value-not-found-error-message-in-windows-setups/"><u>Solving 'Value Not Found' Error Message in Windows Setups</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-endorsed-top-10-for-windows-free-app-safety/"><u>Expert-Endorsed Top 10 for Windows FREE App Safety</u></a></li>
<li><a href="https://windows11.techidaily.com/the-special-features-that-define-artificited-computers/"><u>The Special Features that Define Artificited Computers</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-avoiding-frequent-sign-ins-on-ms-teams-platform/"><u>Solutions for Avoiding Frequent Sign-Ins on MS Teams Platform</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-unleash-your-creativity-top-online-lyric-video-making-platforms-for-2024/"><u>New Unleash Your Creativity Top Online Lyric Video Making Platforms for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-unleash-creativity-professional-insights-into-shooting-and-editing-stunning-slow-motion-content-for-instagram/"><u>[Updated] In 2024, Unleash Creativity  Professional Insights Into Shooting and Editing Stunning Slow Motion Content for Instagram</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-windows-aggregatorhostexe-functions-risks-and-safety-concerns/"><u>Decoding Windows' AggregatorHost.exe: Functions, Risks, and Safety Concerns</u></a></li>
<li><a href="https://windows11.techidaily.com/the-pathway-for-effortless-changes-of-file-extensions/"><u>The Pathway for Effortless Changes of File Extensions</u></a></li>
<li><a href="https://windows11.techidaily.com/window-wonderland-crafting-distinctive-displays-in-win-1011/"><u>Window Wonderland: Crafting Distinctive Displays in Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/a-step-by-step-for-erasing-sign-in-email-in-win/"><u>A Step-By-Step for Erasing Sign-In Email in Win</u></a></li>
<li><a href="https://windows11.techidaily.com/audio-visual-verification-a-windows-users-pre-meet-checklist/"><u>Audio Visual Verification: A Windows User’s Pre-Meet Checklist</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-smartphone-showcase-the-very-best-for-artistic-endeavors/"><u>[Updated] Smartphone Showcase  The Very Best for Artistic Endeavors</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-the-ultimate-guide-to-adaptive-igtv-video-dimensions-for-2024/"><u>[Updated] The Ultimate Guide to Adaptive IGTV Video Dimensions for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-prevalent-anydesk-errors-in-windows/"><u>Decoding Prevalent AnyDesk Errors in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/voice-activated-mastery-in-windows-11s-accessibility-features/"><u>Voice-Activated Mastery in Windows 11'S Accessibility Features</u></a></li>
<li><a href="https://windows11.techidaily.com/bringing-print-functionality-to-microsofts-secure-edge/"><u>Bringing Print Functionality to Microsoft's Secure Edge</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/key-features-to-look-for-in-a-video-to-audio-converter-a-beginners-guide/"><u>Key Features to Look for in a Video to Audio Converter A Beginners Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/easing-windows-woes-with-adobe-ps/"><u>Easing Windows Woes with Adobe PS</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-vigilance-understanding-and-monitoring-device-uptime/"><u>Windows 11 Vigilance: Understanding and Monitoring Device Uptime</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-usb-resources-on-pcs/"><u>Enhancing USB Resources on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-the-8-anomalies-in-windows-11s-ui/"><u>Dissecting the 8 Anomalies in Windows 11'S UI</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/mastering-the-art-of-online-meeting-recordings-with-google-for-2024/"><u>Mastering the Art of Online Meeting Recordings with Google for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/swiftly-overcoming-disruptions-after-a-windows-update/"><u>Swiftly Overcoming Disruptions After a Windows Update</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-essential-tutorial-infusing-motion-blur-into-faces-using-picsart/"><u>In 2024, The Essential Tutorial  Infusing Motion Blur Into Faces Using Picsart</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-spy-on-text-messages-from-computer-and-samsung-galaxy-m54-5g-drfone-by-drfone-virtual-android/"><u>How to Spy on Text Messages from Computer & Samsung Galaxy M54 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-disable-old-user-id-prompt-in-windows-login-screen/"><u>How to Disable 'Old User ID' Prompt in Windows Login Screen</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-scene-stealer-snapshot-study/"><u>2024 Approved  Scene-Stealer Snapshot Study</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-instagrammable-vs-trendy-will-likebeat-tiktok/"><u>[Updated] Instagrammable Vs. Trendy  Will LikeBeat TikTok?</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-the-ultimate-choice-for-live-event-recorders-top-10-for-2024/"><u>[Updated] The Ultimate Choice for Live Event Recorders (Top 10) for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-creating-content-from-home-macbook-cam-guide/"><u>[Updated] In 2024, Creating Content From Home  MacBook Cam Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/discovering-devhome-the-essential-guide-to-win11/"><u>Discovering DevHome: The Essential Guide to Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/top-screen-notebook-techniques-for-win-1011/"><u>Top-Screen Notebook Techniques for Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-fixing-the-application-was-unable-error/"><u>Understanding and Fixing The Application Was Unable Error</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-for-curtailing-windows-eyes-on-you/"><u>Tactics for Curtailing Windows' Eyes on You</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-unresponsive-spotify-on-windows-11/"><u>Troubleshooting Unresponsive Spotify on Windows 11</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/smart-techniques-to-capture-gotomeet-participants/"><u>Smart Techniques to Capture GoToMeet Participants</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-rectify-win-1011-onedrive-issues/"><u>Steps to Rectify Win 10/11 OneDrive Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-solve-no-device-camera-error-in-win11/"><u>Steps to Solve No Device: Camera Error in Win11</u></a></li>
<li><a href="https://youtube-help.techidaily.com/how-to-upload-videos-to-youtube-a-step-by-step-guide-for-2024/"><u>How To Upload Videos to YouTube [a Step-by-Step Guide] for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/low-cost-pc-performance-monitoring-programs-for-2024/"><u>Low-Cost PC Performance Monitoring Programs for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-digital-video-conquerors-ultimate-toolkit-list/"><u>[New] Digital Video Conquerors' Ultimate Toolkit List</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/essential-screen-recording-tools-a-comprehensive-educators-guide-for-2024/"><u>Essential Screen Recording Tools  A Comprehensive Educator's Guide for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-financial-gains-the-youtube-money-flow-from-1m-views/"><u>[Updated] 2024 Approved  Financial Gains  The Youtube Money Flow From 1M Views</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-combating-content-id-blocks-on-youtube-with-knowledge/"><u>[New] In 2024, Combating Content ID Blocks on YouTube with Knowledge</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-user-accounts-to-local-groups-policy-in-windows-11-and-11/"><u>Tailoring User Accounts to Local Groups Policy in Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-the-perfect-keys-list-for-win11s-narrator-control/"><u>Crafting the Perfect Keys List for Win11's Narrator Control</u></a></li>
</ul></div>
