---
title: "QuickFix Sniping Tool Problems: Top Tips Revealed"
date: 2024-07-11T21:44:49.511Z
updated: 2024-07-12T21:44:49.511Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes QuickFix Sniping Tool Problems: Top Tips Revealed"
excerpt: "This Article Describes QuickFix Sniping Tool Problems: Top Tips Revealed"
keywords: QuickFix Sniping Issue Help,Fix Sniping Tools Troubleshooting,Resolving Sniping Software Errors,Sniping Tool Tips & Solutions,Top Sniping Problem Fixes,Effective Sniping Correction Guide,Address Common Sniping Fails
thumbnail: https://thmb.techidaily.com/9dde14122d86332e2939d12b71c8c112849e5b475313180be25192ee619462eb.jpg
---

## QuickFix Sniping Tool Problems: Top Tips Revealed

 The Snipping Tool is an important feature of any Windows operating system; it allows users to capture, edit, and save screenshots directly onto their PC.

 However, since Windows Vista, the program hasn't been the most stable. Even as we moved onto Windows 10 and 11, the Snipping tool tended to run into strange issues. Such issues prompt the “Snipping tool not working” error repeatedly, which might hinder your workflow and slow you down.

 We have tracked down a few reasons why the Snipping Tool can stop working and how to easily resolve them. Let's have a look at how they can be dealt with.

## 1\. Restart the Windows File Explorer

 Let's start by going to the root of the problem. Since the Snipping Tool is a subset of the File Explorer service, it is most probable that the problem likely came from there. If File Explorer goes unresponsive, so too does the Snipping Tool.

 As such, restarting File Explorer may dislodge whatever's keeping the Snipping Tool from working correctly. To do this, press **Ctrl + Alt + Del**, then select **Task Manager**. Alternatively, you can press **CTRL + Shift + ESC** to jump directly into the Task Manager.

![Windows task manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/task-manager-1.jpg)

 Scroll down until you find **Windows Explorer** and right-click it. In the drop-down menu that appears, select **Restart.**

 You will notice your desktop will go through some weird changes while File Explorer restarts.

 For example, the taskbar will vanish, and your desktop wallpaper will turn completely black. However, this is totally normal, as all of these elements rely on File Explorer. When you restart the service, it forces all of these elements to restart too.

 Once everything looks okay again, try opening the Snipping Tool and using it.

## 2\. Look for Interfering Third-Party Software

 Sometimes, a program you've recently downloaded can interfere with the smooth running of the Snipping Tool. If you want to reach the bottom of all this mystery, one way to know for sure is by following these steps given below:

1. Type in "system configuration" in the **Start menu** search bar and open the **System Configuration** panel.
2. Switch to the **Services** tab on the top, and then select the option to **hide all the Microsoft services** at the bottom.
3. Disable any service that you think might be interfering with the Snipping Tool.
4. Once you disable it, try running the Snipping Tool once again. If it works properly, it means that the app was in conflict with the Snipping Tool. It should be kept disabled to keep the Snipping Tool on your Windows working properly.

![Services tab in the system configuration section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/system-configuration.jpg)

## 3\. Run the Scannow Tool

 If all else fails and your Snipping Tool still isn't working, you can still use the **scannow** command to repair and restore the damaged files that cause it to malfunction. You can achieve this with the help of the [Command Prompt feature](https://www.makeuseof.com/run-command-prompt-commands-desktop-shortcut/).

 Follow these steps to continue:

1. Type "command prompt" in the **Start menu** search bar and run it as administrator. To do this, either click on **Run as Administrator** on the right panel, or right-click the search result and click **Run as Administrator**.
2. Once inside Command Prompt, type the following command and hit Enter:  
`sfc /scannow`
3. Next, type the following command to launch the Snipping Tool manually:  
`snippingtool.exe`  
 Once done, check to see if the error still persists.

![Windows command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/command-prompt.jpg)

## 4\. Permit Snipping Tool to Run in the Background

 Snipping Tool also might not work if it lacks the necessary permission to run in the background. This means the app won't work unless you are active in the app's window. To rectify this, authorize the Snipping Tool's application to run in the background by following these steps:

1. Click the **Windows** icon and select **Settings** from the context menu.
2. Hit the **Privacy** button on the Settings page.
3. Scroll down to the panel on the left to locate **Background apps.**
4. Search for **Snip & Sketch** from the app list and ensure it's toggled on.

![List of Background Apps](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/background-apps-windows.jpg)

## 5\. Update Graphics Drivers

 Sometimes outdated or corrupt graphic drivers are the culprit behind a non-functioning Snipping Tool. Their core responsibility is capturing and processing the screenshot into a format the Windows device understands.

 If it’s outdated, it won’t translate the images appropriately and become incompatible with your computer, resulting in the "Snipping Tool not working" error. Hence, in this scenario, the key is to update these drivers to their latest build.

 Follow these steps to continue:

1. Right-click on the **Windows** icon and select **Device Manager** from the pop-up list.
2. Navigate to **Display adapters,** expand it, and right-click on the available driver.
3. Select **Update driver > Search automatically for drivers.** The system will quickly scan for any available drivers and install them.  
![Update Graphics Driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/update-graphics-driver.jpg)
4. Restart your Windows device.

## 6\. Update Your Windows Computer

 Windows regularly releases updates that fix your PC’s bugs, bring in new features and security-related patches, and generally make your Windows experiences much more accessible and better than before.

 If you haven’t done so in a while, now might be a good time to [update your Windows version](https://www.makeuseof.com/update-windows-manually/). Because this outdated Windows version might very well be the cause of your PC’s bugs or errors.

 So, head to Settings by pressing **Windows Key + I** and select **Windows Update**. The Windows Update app will start scanning your system automatically, and from there, all you have to do is click on **Download & install**and your Windows will be updated.

![windows update menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-update.jpg)

 If this didn't fix the Snipping Tool on your Windows either, jump to the next trick below.

## 7\. Disable Focus

[Focus, earlier known as Focus Assist](http://www.makeuseof.com/microsoft-windows-11-focus-assist-update/), is one of those apps that proves everything has pros and cons. If you’re prone to distraction, you might have used the app already and successfully wiped out many distractions from notifications and random pop-ups.

 However, along with these notifications and other random pings, the feature also blocks out many useful apps—this includes Snipping Tool as well. So, disabling the Focus Assist app can help out here.

 Follow these steps to disable Focus Assist on Windows:

1. Head to the **Start menu** search bar, type in ‘settings,’ and select the best match.
2. From the **Settings** window, choose **System > Focus Assist**.
3. Now toggle off the **Focus assist** features, and you’ll be good to go.

![focus feature on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/focus-feature-on-windows-1.jpg)

 That’s it—when you have the Focus feature disabled, try out the Snipping Tool again. It should be working now in most cases.

## 8\. Reset the Snipping Tool App

 Sometimes things go awry for the weirdest reasons you can’t explain; your apps on Windows are no exception from accidents of such kind.

 When you find any of your Windows apps in a place like this, one of the best tricks is to give the app a quick reset. The reset will bring your app to default settings where everything works smoothly.

 Follow these steps to reset the Snipping Tool app:

1. Launch the Settings app and head to **Apps > Installed apps**.
2. From there scroll down, find the Snipping tool, and then click on **Advanced options**.
3. Find the **Reset** section and then click on the **Reset** button.

![Windows snipping tool reset](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/snipping-tool-reset-1.jpg)

 You’ll get asked for a confirmation for the reset. Click on **Reset** to finally go ahead with the reset, and wait for a check sign to appear before the button. As soon as the button appears, your app will have been reset.

 If the Snipping Tool error was caused because of an abrupt mistake in the app, it should be resolved by the end of the above steps.

## 9\. Enable the Auto Copy Feature

 If someone has disabled the auto-save feature on Snipping Tool, the screenshots won’t be saved in your default location automatically.

 To make sure that’s not the case, launch the Snipping Tool and click on the **Settings** menu (the ellipses icon from the top-right corner).

![Windows snipping tool settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/snipping-tool-settings-1.jpg)

 Once done, toggle on **Automatically save screenshots**. When you have this setup your screenshots will be saved instantly, solving your Snipping Tool errors for good.

## Expanding More on the Snipping Tool

 Because the Snipping Tool is associated with taking screenshots, its importance can’t be understated. Screenshots are an easy way to communicate data and not being able to use this function can leave you in a lurch.

 There’s no doubt about the Snipping Tool being an integral part of the Windows OS; therefore, it is also essential to make full use of this function. Knowing all the useful tips and tricks, shortcuts, and how to make your own hotkeys will make it much easier to capture, edit, and save your screenshots on your Windows PC.

 However, since Windows Vista, the program hasn't been the most stable. Even as we moved onto Windows 10 and 11, the Snipping tool tended to run into strange issues. Such issues prompt the “Snipping tool not working” error repeatedly, which might hinder your workflow and slow you down.

 We have tracked down a few reasons why the Snipping Tool can stop working and how to easily resolve them. Let's have a look at how they can be dealt with.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/essential-fixes-for-common-windows-os-office-problems/"><u>Essential Fixes for Common Windows OS Office Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-unveiled-the-backup-and-sync-technological-advancements/"><u>Windows 11 Unveiled: The Backup & Sync Technological Advancements</u></a></li>
<li><a href="https://windows11.techidaily.com/getting-acquainted-with-the-windows-odbc-system/"><u>Getting Acquainted with the Windows ODBC System</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-cant-detect-camera-error-on-windows-11-pc/"><u>Fixing Can't Detect Camera Error on Windows 11 PC</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-breaking-boundaries-custom-font-use-in-after-effects/"><u>[Updated] Breaking Boundaries  Custom Font Use in After Effects</u></a></li>
<li><a href="https://windows11.techidaily.com/insightful-tips-for-timely-ping-execution-on-windows-pcs/"><u>Insightful Tips for Timely Ping Execution on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/when-should-you-consider-purging-pagefilesys/"><u>When Should You Consider Purging Pagefile.sys?</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-lenovo-thinkphone-drfone-by-drfone-virtual-android/"><u>How PGSharp Save You from Ban While Spoofing Pokemon Go On Lenovo ThinkPhone? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/enable-word-to-always-present-email-attachments-in-reading-view-format/"><u>Enable Word to Always Present Email Attachments in Reading View Format</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-text-entry-learning-from-typingaid/"><u>Boost Text Entry: Learning From TypingAid</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-unlock-the-secrets-capturing-apple-devices-for-engaging-videos/"><u>2024 Approved  Unlock the Secrets  Capturing Apple Devices for Engaging Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/combat-window-settings-malfunctions-now/"><u>Combat Window Settings Malfunctions Now</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-silencing-game-recommendations-on-w11/"><u>Guide to Silencing Game Recommendations on W11</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-beyond-acid-pro-innovative-vector-editors-reviewed/"><u>2024 Approved  Beyond ACID Pro  Innovative Vector Editors Reviewed</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-yuzu-emulation-speed-in-windows/"><u>Elevating Yuzu Emulation Speed in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/digital-dot-delights-top-8-desktop-note-alternatives/"><u>Digital Dot Delights: Top 8 Desktop Note Alternatives</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-counteract-install-net-core-now-on-pc/"><u>How to Counteract Install .NET Core Now on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-duo-app-configurations-to-resolve-errors/"><u>Correcting Duo App Configurations to Resolve Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-alleviate-windows-1011s-devastating-discord-js-failure/"><u>How to Alleviate Windows 10/11'S Devastating Discord JS Failure</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-mac-os-look-in-windows-try-these-5-techniques-first/"><u>Unlock the Mac OS Look in Windows - Try These 5 Techniques First</u></a></li>
<li><a href="https://extra-tips.techidaily.com/funimate-pro-unboxed-your-essential-apk-guide/"><u>Funimate Pro Unboxed  Your Essential APK Guide</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-frp-from-xiaomi-by-drfone-android/"><u>How to Bypass FRP from Xiaomi?</u></a></li>
<li><a href="https://extra-tips.techidaily.com/best-of-the-best-photo-overlays-and-text-editors-review-for-2024/"><u>Best of the Best  Photo Overlays & Text Editors Review for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-reboot-mastery-conducting-a-pure-boot/"><u>Windows 11 Reboot Mastery: Conducting a Pure Boot</u></a></li>
<li><a href="https://windows11.techidaily.com/beyond-boundaries-3-tools-that-elevate-pc-audio-above-100/"><u>Beyond Boundaries: 3 Tools That Elevate PC Audio Above 100%%</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-how-to-go-frame-by-frame-on-youtube-video-5-methods/"><u>[Updated] In 2024, How to Go Frame by Frame on YouTube Video? [5 Methods]</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-3-ways-to-create-motion-text-effects-for-your-video/"><u>2024 Approved 3 Ways to Create Motion Text Effects for Your Video</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tuning-windows-filename-metadata/"><u>Fine-Tuning Windows Filename Metadata</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-10-best-reaper-plugins-you-need-to-know-free-download/"><u>Updated 10 Best Reaper Plugins You Need to Know (Free Download)</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-magical-mastery-top-video-magic-from-youtube-pros/"><u>2024 Approved  Magical Mastery  Top Video Magic From YouTube Pros</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-link-zoom-calls-to-iphoneandroid-events-seamlessly/"><u>[New] 2024 Approved  Link Zoom Calls to iPhone/Android Events Seamlessly</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-compiled-list-of-top-3ip-ipad-voice-recorders/"><u>[New] Compiled List of Top 3iP iPad Voice Recorders</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/smoothen-your-mobile-videos-with-these-top-rated-free-android-apps/"><u>Smoothen Your Mobile Videos with These Top-Rated Free Android Apps</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-2024-approved-get-ready-to-edit-the-best-free-game-video-editing-software/"><u>New 2024 Approved Get Ready to Edit The Best Free Game Video Editing Software</u></a></li>
<li><a href="https://windows11.techidaily.com/what-is-ftdibussys-on-windows-and-why-does-it-disable-memory-integrity/"><u>What Is ftdibus.sys on Windows and Why Does It Disable Memory Integrity?</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-windows-1011-unsigned-update-errors/"><u>Eliminating Windows 10/11 'Unsigned' Update Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-paths-blocked-by-shared-printers/"><u>Clearing Paths Blocked by Shared Printers</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-remove-the-two-factor-authentication-on-iphone-7-plus-by-drfone-ios/"><u>In 2024, How To Remove the Two Factor Authentication On iPhone 7 Plus</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-why-is-ipogo-not-working-on-apple-iphone-xr-fixed-drfone-by-drfone-virtual-ios/"><u>In 2024, Why is iPogo not working On Apple iPhone XR? Fixed | Dr.fone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-advanced-array-manipulations-and-sorting-algorithms/"><u>[Updated] 2024 Approved  Advanced Array Manipulations and Sorting Algorithms</u></a></li>
<li><a href="https://windows11.techidaily.com/get-a-free-glimpse-into-the-realm-of-ocm-football/"><u>Get a FREE Glimpse Into the Realm of OCM Football</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-routes-to-examine-and-clean-up-windows-10s-past-actions/"><u>Easy Routes to Examine & Clean Up Windows 10'S Past Actions</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-window-wizardry-how-to-reactivate-off-screen-apps/"><u>Windows 11 Window Wizardry: How to Reactivate Off-Screen Apps</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/formulating-attractive-instagram-story-captions-for-2024/"><u>Formulating Attractive Instagram Story Captions for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/keeping-windows-screensaver-status-intact-from-user-changes/"><u>Keeping Windows Screensaver Status Intact From User Changes</u></a></li>
<li><a href="https://windows11.techidaily.com/leap-into-connectivity-unlocking-windows-remote-desktop/"><u>Leap Into Connectivity: Unlocking Windows Remote Desktop</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/what-is-a-sim-network-unlock-pin-get-your-samsung-galaxy-xcover-6-pro-tactical-edition-phone-network-ready-by-drfone-android/"><u>What Is a SIM Network Unlock PIN? Get Your Samsung Galaxy XCover 6 Pro Tactical Edition Phone Network-Ready</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-steps-for-muting-windows-11-tabs/"><u>Essential Steps for Muting Windows 11 Tabs</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-ultimate-guide-to-the-best-7-effortless-vocal-eradicator-software/"><u>Updated 2024 Approved Ultimate Guide to the Best 7 Effortless Vocal Eradicator Software</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/ultimate-9-hidden-media-extractors/"><u>Ultimate 9 Hidden Media Extractors</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/2024-approved-top-mp4-editor-for-windows-8-professional-video-editing-made-easy/"><u>2024 Approved Top MP4 Editor for Windows 8 Professional Video Editing Made Easy</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/ultimate-list-most-compelling-zombie-themed-video-games/"><u>Ultimate List  Most Compelling Zombie-Themed Video Games</u></a></li>
<li><a href="https://android-unlock.techidaily.com/downloading-samfw-frp-tool-30-for-lava-by-drfone-android/"><u>Downloading SamFw FRP Tool 3.0 for Lava</u></a></li>
<li><a href="https://windows11.techidaily.com/detailed-exploration-retrieving-the-true-nature-of-device-ids-in-windows/"><u>Detailed Exploration: Retrieving the True Nature of Device IDs in Windows</u></a></li>
</ul></div>
