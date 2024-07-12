---
title: Essential Tips to Overcome Window's Code Error
date: 2024-07-11T21:11:02.862Z
updated: 2024-07-12T21:11:02.862Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Essential Tips to Overcome Window's Code Error
excerpt: This Article Describes Essential Tips to Overcome Window's Code Error
keywords: Solve Windows Coding Errors,Fixing Error in Windows DevCode,Avoid Common CodeError Windows,Best Practices for ErrorWinCodes,Debugging Tips,Eliminate Errors in Windows Dev,Mastering Windows Code Issue Fix
thumbnail: https://thmb.techidaily.com/b59734d21ac4befa6d882d663a57d13f768195f331fa0eea08a7ad594a08d5e2.jpg
---

## Essential Tips to Overcome Window's Code Error

 Microsoft frequently releases updates to fix security issues, and introduce new features and stability to the Windows OS. But not all updates install smoothly on your system and trigger an error code while doing so. Many users share their woes with the 0x80073712 update error code with the error message that some files are missing from the system.

 If you experience the same update error code and are unable to install the latest Windows update, don’t worry. We will list out all the possible fixes that you can try to resolve the 0x80073712 error code.

## 1\. Use the Windows Troubleshooter

 Before jumping onto major fixes, leverage the in-built troubleshooter on Windows 10 and 11\. It tries to find out existing problems with Windows Update and try to fix them. Repeat the following steps:

1. Press**Win + I** to launch the settings app.
2. Navigate to the**System > Troubleshoot** section.
3. Click on the**Other Troubleshooter** option.
4. Locate the**Windows Update troubleshooter** option from the list.
5. Then, click on the**Run** button to start the troubleshooter.  
![Windows Update Troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-update-troubleshooter.jpg)
6. Wait for the Windows Update troubleshooter to identify problems. Click on the**Next** button.
7. Close the troubleshooter window and reattempt the Windows update installation.

## 2\. Perform a Complete system shutdown

 Windows OS enables the fast startup option by default. Even if you restart your system, or shut it down, it preserves the system state using hibernate. So, you need to perform a complete system shutdown and then power it back on to close and restart all background services.

Here’s how to perform a complete system shutdown:

1. Press**Win + X** to launch the Power user menu. Scroll down and select the**Terminal (Admin)** option from the list.
2. The Terminal app will open with an instance of a command prompt with admin privileges.
3. Type the**shutdown /s /f /t 0** command and press the**enter** key.
4. Your system will power off. It will take a tad bit longer that a normal shutdown procedure.
5. Now, restart your Windows PC and try to install the Windows update.

## 3\. Restart Windows Update services

 Windows Update uses a bunch of background services to fetch and download updates. If these services aren’t running automatically, you will encounter an error. These include**Windows Update Service** ,**Windows Installer Service** ,**Cryptographic Services** , and**Background Intelligent Transfer Service** .

Repeat the following steps to start the necessary services:

1. Press**Win + R** to [launch the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**services.msc** and press the**enter** key
2. Services utility will launch on your system. Now locate the**Background Intelligent Transfer** service in the list.
3. Double-click on the BITS service to open the**properties** window. Set the**Startup Type** as**Automatic** and click on the**Apply** button.  
![Disabling Windows Update Services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/disabling-windows-update-services.jpg)
4. Click on the**OK** button and close the Properties windows. Now, right-click on the service and select the**Start** option from the context menu.
5. Similarly, set all the services as automatic and manually start them.
6. **Close** the Services window and reattempt the Windows update.

## 4\. Run the Disk Cleanup Tool

 Disk Cleanup can wipe the delivery optimization files, old Windows update files as well as the Temp folder. If files in these locations are corrupted, they can interfere with the normal update process. Here’s how to run disk cleanup on Windows:

1. Press**Win + S** to open the search utility in Windows.
2. Type**cleanmgr.exe** and press the enter key to open the Disk Cleanup tool.
3. It will select the system drive (C) by default. Click on the**OK** button to continue.
4. Select the checkboxes of files that you want the tool to clean up. Then, click on the**Clean up system files** button.  
![Disk Cleanup App in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/disk-cleanup-app-in-windows-11.jpg)
5. Disk Cleanup will close and redirect you to pick the appropriate drive. Click on the**OK** button.
6. Lastly, click on the**Delete files** button.

## 5\. Rename the SoftwareDistribution Folder

 Windows update stores its content in the SoftwareDistribution folder. Since it is located inside the Windows folder in the C drive, you mustn’t delete it. Instead, you can rename the folder to force the update service to recreate the folder again.

Repeat the following steps:

1. Open the Start menu and search CMD. Press Ctrl + Shift + Enter to open the command prompt with admin privileges.
2. Type the following commands to stop all the Windows update-related services:  
 net stop wuauserv net stop cryptSvc net stop bits net stop msiserver  
![Rename the SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/rename-the-softwaredistribution-folder.jpg)
3. Once these services stop running, type**cls** in the command prompt windows. Then enter the following commands:  
 ren C:\\Windows\\SoftwareDistribution SoftwareDistribution.old ren C:\\Windows\\System32\\catroot2 Catroot2.old  
![Rename the SoftwareDistribution Folder 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/rename-the-softwaredistribution-folder-2.jpg)
4. Both the above commands rename the**SoftwareDistribution** folder and**Catroot2** folder.
5. Now, you need to restart all the Windows services you stopped in step 3\. Enter the following commands:  
net start wuauserv net start cryptSvc net start bits net start msiserver  
![Rename the SoftwareDistribution Folder 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/rename-the-softwaredistribution-folder-3.jpg)
6. Lastly,**restart** your system and visit the following folder location:**C:\\Windows** . You will notice that there is a new SoftwareDistribution folder in that location.
7. Open the Windows update in Settings and try to download and install updates.

## 6\. Delete the Pending.xml file

 The pending.xml file contains all the pending Windows update tasks. Oftentimes, it can interfere with installing new updates because there are already multiple incomplete old update tasks. So, you must delete this file and proceed with the Windows update.

Retrace the following steps to delete the pending.xml file:

1. Log in with an administrator account. Then, press**Win + E** to launch the file explorer.
2. Navigate to the**C:\\Windows\\WinSxS** folder.
3. Locate the**pending.xml** in the**WinSxS** folder and right-click on it.
4. Press the**Shift** key and click on the**Delete** option.
5. Restart your computer.

## 7\. Manually Download Windows Updates

 If you are unable to download a specific Windows update using the Settings page, consider a direct download and install approach. Visit the Microsoft Update Catalog website and search for the KB update you want to download. However, you first have to check the corresponding update number which is failing to download and install on your system.

![Manually Download Windows Updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/manually-download-windows-updates.jpg)

## 8\. Reset Windows

 Resetting Windows is the last resort you have if none of the above methods work in your favor. However, before learning [how to perform a Windows system reset](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) , try out general fixes such as [SFC, CHKDSK, and DISM](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) scans on your system. Also,[disable Windows Defender](https://www.makeuseof.com/how-to-turn-off-windows-defender/) and try updating your system before hitting the reset button.

## Update Windows Without Hiccups

 Windows updates can be tricky to install sometimes. Use the inbuilt troubleshooter to identify and fix problems. After that restart, all the crucial Windows update services and run the Disk Cleanup tool. If everything else fails, try doing a manual update or performing a Windows Reset.


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
<li><a href="https://windows11.techidaily.com/techniques-for-correcting-failed-java-setup-in-windows/"><u>Techniques for Correcting Failed Java Setup in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-winpcs-fatal-pink-flash/"><u>Troubleshooting WinPC's Fatal Pink Flash</u></a></li>
<li><a href="https://windows11.techidaily.com/10-swift-routes-to-the-control-panel-interface/"><u>10 Swift Routes to the Control Panel Interface</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-the-angle-advantage-guide-mastering-the-art-of-spinning-photos-for-social-media-triumphs/"><u>[New] In 2024, The Angle Advantage Guide  Mastering the Art of Spinning Photos for Social Media Triumphs</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-constructive-cuts-streamlined-approaches-for-length-adjustments-on-vimeo/"><u>[Updated] 2024 Approved  Constructive Cuts  Streamlined Approaches for Length Adjustments on Vimeo</u></a></li>
<li><a href="https://windows11.techidaily.com/maximize-time-management-on-pc-choose-from-these-5-exciting-windows-clock-saver-apps/"><u>Maximize Time Management on PC: Choose From These 5 Exciting Windows Clock Saver Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-workspace-potential-discover-the-best-window-folder-methods/"><u>Unlock Workspace Potential: Discover the Best Window Folder Methods</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-2024-approved-elevate-your-content-top-5-reaction-video-makers/"><u>New 2024 Approved Elevate Your Content Top 5 Reaction Video Makers</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-your-win-1011-menu-options/"><u>Reviving Your Win 10/11 Menu Options</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-mirthful-montage-mastering-7-comical-video-vignettes/"><u>[Updated] Mirthful Montage  Mastering 7 Comical Video Vignettes</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/online-auditory-hygiene-methods-to-purify-sound-recordings-of-digital-transmission-for-2024/"><u>Online Auditory Hygiene Methods to Purify Sound Recordings of Digital Transmission for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-fix-corrupt-video-files-of-oppo-a38-using-video-repair-utility-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>How to Fix corrupt video files of Oppo A38 using Video Repair Utility on Windows?</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-best-free-imovie-equivalent-for-windows-11-and-10-pcs-for-2024/"><u>New Best Free iMovie Equivalent for Windows 11 and 10 PCs for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-any-tecno-phone-password-using-emergency-call-by-drfone-android/"><u>How To Unlock Any Tecno Phone Password Using Emergency Call</u></a></li>
<li><a href="https://windows11.techidaily.com/monitor-positioning-tactics-in-windows/"><u>Monitor Positioning Tactics in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unbridled-upgrade-choose-bare-essentials-win11/"><u>Unbridled Upgrade: Choose Bare Essentials Win11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-understanding-apples-audio-content-guidelines/"><u>[Updated] Understanding Apple’s Audio Content Guidelines</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-improve-steam-download-speeds-on-windows/"><u>Strategies to Improve Steam Download Speeds on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-address-aw-snap-in-google-chrome-on-pc/"><u>Steps to Address Aw, Snap! In Google Chrome on PC</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/in-2024-youtube-themes-made-easy-by-the-coolest-logo-and-icon-stores-online/"><u>In 2024, YouTube Themes Made Easy by the Coolest Logo & Icon Stores Online</u></a></li>
<li><a href="https://windows11.techidaily.com/supercharge-utorrent-downloads-elevate-your-file-speed/"><u>Supercharge uTorrent Downloads, Elevate Your File Speed</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-remedy-unsupported-audio-device-in-windows-os/"><u>Steps to Remedy Unsupported Audio Device in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/maximize-output-win-based-time-management-apps-reviewed/"><u>Maximize Output: Win-Based Time Management Apps Reviewed</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-audio-extraction-masterclass-the-top-10-tools-and-techniques-every-editor-should-know/"><u>Updated Audio Extraction Masterclass The Top 10 Tools and Techniques Every Editor Should Know</u></a></li>
<li><a href="https://extra-support.techidaily.com/master-the-melodies-secrets-to-adding-soundtracks-on-insta-for-2024/"><u>Master the Melodies  Secrets to Adding Soundtracks on Insta for 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reasons-for-vivo-s17t-stuck-on-boot-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Vivo S17t Stuck on Boot Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-pin-count-on-the-w11-start-screen/"><u>Boosting Pin Count on the W11 Start Screen</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/planning-to-use-a-pokemon-go-joystick-on-honor-70-lite-5g-drfone-by-drfone-virtual-android/"><u>Planning to Use a Pokemon Go Joystick on Honor 70 Lite 5G? | Dr.fone</u></a></li>
<li><a href="https://audio-editing.techidaily.com/in-2024-the-complete-beginners-guide-to-voice-recording-on-your-computer-with-audacity/"><u>In 2024, The Complete Beginners Guide to Voice Recording on Your Computer with Audacity</u></a></li>
<li><a href="https://windows11.techidaily.com/simplify-system-upkeep-automatic-driver-replacement-for-amd/"><u>Simplify System Upkeep: Automatic Driver Replacement for AMD</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-the-barrier-of-windows-11-updates/"><u>Breaking Down the Barrier of Windows 11 Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-faster-typing-the-powertoys-way/"><u>Unlock Faster Typing: The PowerToys Way</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-full-potential-of-taskbar-in-win11/"><u>Unlock the Full Potential of Taskbar in Win11</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/effortless-igtv-video-downloads-ios-and-android-guide-for-2024/"><u>Effortless IGTV Video Downloads  IOS & Android Guide for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-a-tutorial-for-adding-vintage-touches-instagram-filters-on-existing-media-for-2024/"><u>[New] A Tutorial for Adding Vintage Touches  Instagram Filters on Existing Media for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-passcode-alterations-effortlessly/"><u>Navigating Windows Passcode Alterations Effortlessly</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-expand-start-menu-pin-scope/"><u>Strategies to Expand Start Menu Pin Scope</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-to-manipulating-fax-cover-pages-on-win11/"><u>Step-by-Step Guide to Manipulating Fax Cover Pages on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/skyrocketing-speed-for-battlenet-downloads-on-your-pc/"><u>Skyrocketing Speed for Battle.net Downloads on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-address-failed-downloads-in-windows-1011/"><u>Strategies to Address Failed Downloads in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-potential-of-windows-without-using-the-compatibility-tool/"><u>Unlock Potential of Windows without Using the Compatibility Tool.</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-how-to-sprinkle-new-colors-into-your-past-media-with-instagram/"><u>In 2024, How to Sprinkle New Colors Into Your Past Media with Instagram</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-2024-approved-imovie-secrets-techniques-for-sharper-sound-in-video-editing/"><u>New 2024 Approved IMovie Secrets Techniques for Sharper Sound in Video Editing</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-steam-install-errors-on-windows-11/"><u>Navigating Through Steam Install Errors on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategizing-your-path-through-original-diablo/"><u>Strategizing Your Path Through Original Diablo</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-mastering-video-cropping-and-export-for-instagram-posts/"><u>[New] 2024 Approved  Mastering Video Cropping & Export for Instagram Posts</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-ultimate-free-toolset-for-win11-pcs/"><u>Unveiling the Ultimate Free Toolset for Win11 PCs</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-the-path-to-prominence-with-powerful-instagram-video-narratives-for-2024/"><u>[New] The Path to Prominence with Powerful Instagram Video Narratives for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/smoothing-out-chrome-profile-hitches-on-windows-systems/"><u>Smoothing Out Chrome Profile Hitches on Windows Systems</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-analyzing-peak-engagement-for-podcast-drops/"><u>2024 Approved  Analyzing Peak Engagement for Podcast Drops</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-address-and-rectify-windows-app-error-0x800700c6/"><u>Steps to Address and Rectify Windows App Error 0X800700c6</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/in-2024-mavericks-video-creator-bringing-your-vision-to-life/"><u>In 2024, Mavericks Video Creator Bringing Your Vision to Life</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-fast-film-techniques-taking-screens-on-a-dell/"><u>[Updated] 2024 Approved  Fast Film Techniques  Taking Screens on a Dell</u></a></li>
</ul></div>
