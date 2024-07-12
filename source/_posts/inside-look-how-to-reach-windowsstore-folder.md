---
title: "Inside Look: How To Reach WindowsStore Folder"
date: 2024-07-11T21:43:34.638Z
updated: 2024-07-12T21:43:34.638Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Inside Look: How To Reach WindowsStore Folder"
excerpt: "This Article Describes Inside Look: How To Reach WindowsStore Folder"
keywords: Windows Store Access Guide,Reach App Folder Steps,Navigate to Windows Store,Finding WindowsStoreApps,Unlocking WindowsStore,Locate Windows Store Folder,Pathway to WindowsStore
thumbnail: https://thmb.techidaily.com/1d642682ec5cb6a6ea7cd33f84c3c6bed241d468dfb7fb68a3c7508632db1da6.jpg
---

## Inside Look: How To Reach WindowsStore Folder

 The Windows Operating System has a hidden folder called "WindowsApps." It stores Microsoft application files and other important files to enhance your Windows experience. The folder usually contains a large amount of reusable space. This is because it also contains those application files you uninstalled from your PC earlier.

 Thankfully, you can remove unnecessary files from the WindowsApps folder to free up some space. But it's a little hard to get to this folder because it's protected and hidden in Windows File Explorer. Here are some ways to access the WindowsApps Folder on Windows and make necessary changes to it.

## What Is the WindowsApps Folder?

 You can find the WindowsApps folder under the **C:\\Program Files** directory in Windows 10 and 11\. This folder has all the files related to UWP packages or Windows apps that you get from the Microsoft Store or that come preinstalled on Windows OS.

 The problem is that a basic Windows user or even a system administrator user account can't access or change the files in the folder. This is because it is owned by a Microsoft account named "TrustedInstaller." We've already covered [everything about TrustedInstaller](https://www.makeuseof.com/tag/what-is-trustedinstaller-and-why-does-it-keep-me-from-renaming-files/) and how to disable it in detail.

![WindowsApps Hidden Folder In Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/WindowsApps-Hidden-Folder.jpg)

 Even if you uninstall or debloat some of the apps on Windows, the core application files are not removed from the WindowsApps folder. So, there are chances that such apps will reappear after a new Windows update.

 This is why we recommend using one of the [popular software uninstallers for Windows](http://www.makeuseof.com/windows-11-uninstallers-stubborn-apps/). Because these tools not only uninstall an app completely but also clean up any leftovers and traces from all the secured folders.

 If you don't know what you're doing—modifying or deleting the files in the WindowsApps folder could cause system errors or even cause the Windows operating system to crash.

 There are many ways to access the WindowsApps folder and bypass the protection to gain access to the necessary files.

## Method 1\. How to Access WindowsApps via File Explorer

 You can easily find the WindowsApps folder in the Windows File Explorer by unhiding the respective folder first. However, to access the folder and make changes to the files—you need to gain some extra rights by changing the ownership.

 Follow these steps to view the WindowsApps folder first:

1. Open the Windows File Explorer (**Win + E**) and go to the **C:\\Program Files** directory.  
![Program Files Directory In Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Program-Files-Directory-In-Explorer.jpg)
2. Now, click the **View** options button at the top of the File Explorer.
3. Click or hover over the **Show** button and select the **Hidden items** option to enable it.  
![File Explorer View Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/file-explorer-view-options.jpg)

 That's it. Now, you can see theWindowsApps folder in the same directory.

 If you try to open it, you'll see an information popup saying, "You have been denied permission." So, to actually access that folder and gain exclusive read and write rights—you've got to do a bit more.

### Change Ownership Properties to Get Access

 For the next steps, you need a user account with administrative rights. If you're a beginner, you must know [everything about the Administrator account](https://www.makeuseof.com/tag/windows-administrator-account-everything-need-know/) to understand the steps better.

 Follow the steps mentioned below to change the ownership rights and access the required folder:

1. Select the **WindowsApps** folder and right-click on it.
2. Once the context menu appears, select **Properties** from the list. You can also use a quick shortcut to open the folder properties, i.e., **Alt + Enter**.  
![WindowsApps Properties Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/WindowsApps-Properties-Option.jpg)
3. Now, under the **Properties** window. Click the **Security** tab and then the **Advanced** option locatedright at the bottom.  
![WindowsApps Security Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/WindowsApps-Security-Properties.jpg)
4. Once you've opened the Advanced Security Settings window, click the **Change** text next to Owner.
5. Now, click **Advanced > Find Now > Administrator on the following screen**.  
![Advanced Security Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/advanced-security-properties.jpg)
6. Finally, click **OK** to select the Administrator as the owner and again **OK** to save the changes.  
![User Group Selection Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/User-Group-Selection-Window.jpg)
7. Then, tick the checkbox before the **Replace owner on sub containers and objects** text.
8. Now, click the **Apply** button, followed by the **OK** button, to initiate the process of transferring ownership.  
![WindowsApps Advanced Security Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/WindowsApps-Advanced-Security-Settings.jpg)
9. Once done, click the **OK** button on the next pop-up.

 If you followed the steps above to take ownership of the WindowsApps folder, you can now move or delete files from that folder.

 When you don't pause automatic software installations from the Microsoft store, the WindowsApps folder occupies a considerable bit of disc space. So, it becomes essential for you to access this folder once and check for the files that you no longer need.

 Moreover, you can also check out some [free tools for taking control of files and folders](https://www.makeuseof.com/take-ownership-of-windows-files-and-folders-with-these-tools/) on Windows. Such tools allow you to take full ownership of all your files and folders with a single click.

## Method 2\. How to Access WindowsApps via a PowerShell Command

 The File Explorer-based method is pretty complicated for a newbie. Use PowerShell to complete your job if you're looking for an easy-to-go method. Using Windows PowerShell is a pretty straightforward and automated way of doing the same thing.

 Follow these steps to access the WindowsApps folder using PowerShell:

 1\. Launch the Windows start menu or Windows search by pressing **Win + Q**.

 2\. Type in **PowerShell** and click the **Run as Administrator** option to run PowerShell with administrator rights. Besides, you must also know some other [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) for future usage.

![PowerShell In Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/PowerShell-In-Windows-Search.jpg)

 4\. In Powershell, run the following command and press the Enter key:

`takeown /f &ldquo;C:\Program Files\WindowsApps&rdquo; /r`

![Change Ownership Command In Shell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Change-Ownership-Command-In-Shell.jpg)

 The above command will restore all the files or folder ownership to the system administrator. It will take some time for your administrator user account to become the owner of the WindowsApps folder and everything in it.

 The access you gain by executing the above process is similar to that of the Windows File Explorer-based method. You have just automated the process and eliminated the unhiding of system files. Now, you can back up, clear some space, or make changes to the Windows apps' back-end files.

 If you're facing crashes while executing the file, make sure to check out some [effective ways to fix PowerShell crash errors](http://www.makeuseof.com/windows-powershell-has-stopped-working-error-fix/).

## 3\. How to Access WindowsApps via a Registry Hack

 There's another quick way to do the same thing with just a few steps. If you cannot use the PowerShell method stated above, you can use a simple registry hack to access the files in one go.

 Here's how you can take full ownership of the context menu for your files and folders and get to the WindowsApps folder:

1. Download the [Take Ownership registry](https://www.majorgeeks.com/files/details/take%5Ffull%5Fownership%5Fof%5Ffiles%5Ffolders%5Fregistry%5Fhack.html) file.
2. Extract the zip and open the **Add Take Ownership to Context menu** registry file.  
![Take Ownership Registry File In Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Take-Ownership-Registry-File.jpg)
3. On the next screen, click **Yes** to add it to the registry.
4. Next, exit the popup by clicking **OK** and navigate to the **C:\\Program Files** directory.
5. Select the **WindowsApps** folder and right-click on it.
6. From the context menu, click the **Take Ownership** option.  
![Take Ownership Context Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Take-Ownership-Context-Menu.jpg)
7. In the Command Prompt, you must [give User Account Control Administrator rights](https://www.makeuseof.com/tag/user-account-control-windows-10/) for the registry hack to work. After that, please wait a few minutes for the window to close. Soon, it will display success messages constantly in the Command Prompt.

 Once finished, you'll no longer face the "You've been denied permission" error on clicking the WindowsApps folder.

## Enjoy Unrestricted Access to the WindowsApps Folder

 Using one of the provided methods, you should now be able to view the hidden files and folders inside the WindowsApps folder. Now that you know everything about it, you can easily make changes to the UWP packages that are safe.

 Moreover, in the WindowsApps folder—you can remove Windows app remnants, open any software directly from the .EXE file, and inspect all removed packages, among other things.

 The Windows Operating System has a hidden folder called "WindowsApps." It stores Microsoft application files and other important files to enhance your Windows experience. The folder usually contains a large amount of reusable space. This is because it also contains those application files you uninstalled from your PC earlier.

 Thankfully, you can remove unnecessary files from the WindowsApps folder to free up some space. But it's a little hard to get to this folder because it's protected and hidden in Windows File Explorer. Here are some ways to access the WindowsApps Folder on Windows and make necessary changes to it.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://techidaily.com/how-to-upgrade-or-downgrade-apple-iphone-6s-plus-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Upgrade or Downgrade Apple iPhone 6s Plus Without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-windows-error-code-31-a-troubleshooting-manual/"><u>Navigating Through Windows Error Code 31: A Troubleshooting Manual</u></a></li>
<li><a href="https://windows11.techidaily.com/insight-into-application-usage-on-windows-pc/"><u>Insight Into Application Usage on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-your-sign-in-overcoming-access-restrictions-in-win/"><u>Secure Your Sign-In: Overcoming Access Restrictions in Win</u></a></li>
<li><a href="https://windows11.techidaily.com/maintaining-taskbars-presence-in-maxed-browser-views/"><u>Maintaining Taskbar's Presence in Maxed Browser Views</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-locked-status-tips-for-windows-users-153-chars/"><u>Preventing Locked Status: Tips for Windows Users (153 Chars)</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/about-xiaomi-14-pro-frp-bypass-by-drfone-android/"><u>About Xiaomi 14 Pro FRP Bypass</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-2024-approved-5-premium-android-audio-editors-your-must-have-tools-for-perfect-sound/"><u>New 2024 Approved 5 Premium Android Audio Editors Your Must-Have Tools for Perfect Sound</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstating-unblocked-access-for-microsoft-store-app-in-win11/"><u>Reinstating Unblocked Access for Microsoft Store App in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/fasten-outlook-pace-on-pc-essential-tips/"><u>Fasten Outlook Pace on PC - Essential Tips</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-2024-approved-voice-creation-made-easy-online-9-free-generators-to-convert-text/"><u>Updated 2024 Approved Voice Creation Made Easy Online 9 Free Generators to Convert Text!</u></a></li>
<li><a href="https://windows11.techidaily.com/redefining-user-experience-the-changing-landsinas-of-w10-and-w11/"><u>Redefining User Experience: The Changing Landsinas of W10 & W11</u></a></li>
<li><a href="https://windows11.techidaily.com/from-oops-to-on-point-8-fixes-for-pink-desktop-displays/"><u>From Oops to On Point: 8 Fixes for Pink Desktop Displays</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-power-of-precision-in-slug-line-writing-techniques/"><u>[New] The Power of Precision in Slug Line Writing Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-achieve-stable-gameplay-and-fps-boost-in-roblox/"><u>Strategies to Achieve Stable Gameplay & FPS Boost in Roblox</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-top-10-airplay-apps-in-poco-x5-for-streaming-drfone-by-drfone-android/"><u>In 2024, Top 10 AirPlay Apps in Poco X5 for Streaming | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/improving-startup-order-in-windows-11/"><u>Improving Startup Order in Windows 11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-mirthful-mayhem-makers/"><u>[Updated] Mirthful Mayhem Makers</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unleash-your-potential-with-outstanding-android-time-lapse-videos/"><u>[Updated] Unleash Your Potential with Outstanding Android Time-Lapse Videos</u></a></li>
<li><a href="https://extra-skills.techidaily.com/moviecraft-analysis-in-depth-exploration-for-2024/"><u>MovieCraft Analysis – In-Depth Exploration for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-hidefake-snapchat-location-on-your-infinix-gt-10-pro-drfone-by-drfone-virtual-android/"><u>How to Hide/Fake Snapchat Location on Your Infinix GT 10 Pro | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-can-honor-90-promirror-share-to-pc-drfone-by-drfone-android/"><u>How Can Honor 90 ProMirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-a-non-responsive-resource-monitor-steps-for-windows-11-users/"><u>Navigating a Non-Responsive Resource Monitor: Steps for Windows 11 Users</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-deciphering-instagram-video-glitches-and-finding-silence-free-viewing/"><u>[New] Deciphering Instagram Video Glitches and Finding Silence-Free Viewing</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/perfect-synchronization-enhancing-audio-visual-with-subtitles-in-wmp/"><u>Perfect Synchronization  Enhancing Audio-Visual with Subtitles in WMP</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-soft-dependency-management-in-win-environments/"><u>Exploring Soft Dependency Management in Win Environments</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-guide-forcibly-disabledelete-printer-on-pc/"><u>Immediate Guide: Forcibly Disable/Delete Printer on PC</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/beginners-guide-to-iphone-screen-capture/"><u>Beginner's Guide to iPhone Screen Capture</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-tallying-up-mr-beasts-billions/"><u>In 2024, Tallying Up Mr. Beast's Billions</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-chrome-freeze-windows-edition/"><u>Overcoming Chrome Freeze: Windows Edition</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-instant-sharing-with-media-files-twitters-guide/"><u>[New] 2024 Approved  Instant Sharing with Media Files  Twitter's Guide</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/updated-in-2024-best-photo-slideshow-maker-how-to-make-a-photo-slideshow/"><u>Updated In 2024, Best Photo Slideshow Maker How to Make a Photo Slideshow</u></a></li>
<li><a href="https://screen-capture.techidaily.com/free-software-showdown-for-premium-audio-capture-tools-for-2024/"><u>Free Software Showdown for Premium Audio Capture Tools for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/laugh-your-way-through-twitter-with-the-top-gif-app-2024/"><u>Laugh Your Way Through Twitter with the Top GIF App - 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-malfunctioning-windows-easy-fixes-at-hand/"><u>Mastery Over Malfunctioning Windows: Easy Fixes at Hand!</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/how-to-reverse-videos-on-android-for-2024/"><u>How to Reverse Videos on Android  for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-dxgierrordevicehung-in-win1011/"><u>Overcoming DXGI_ERROR_DEVICE_HUNG in Win10/11</u></a></li>
<li><a href="https://fake-location.techidaily.com/which-is-the-best-fake-gps-joystick-app-on-vivo-x-fold-2-drfone-by-drfone-virtual-android/"><u>Which is the Best Fake GPS Joystick App On Vivo X Fold 2? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-oppo-a18-phone-without-pin-by-drfone-android/"><u>How to Unlock Oppo A18 Phone without PIN</u></a></li>
<li><a href="https://windows11.techidaily.com/simple-steps-to-enable-windows-11s-search-feature-in-task-manager/"><u>Simple Steps to Enable Windows 11'S Search Feature in Task Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-efficiently-techniques-bypassing-ls-command/"><u>Navigating Windows Efficiently: Techniques Bypassing LS Command</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-the-ipogo-get-you-banned-and-how-to-solve-it-on-infinix-hot-30-5g-drfone-by-drfone-virtual-android/"><u>Will the iPogo Get You Banned and How to Solve It On Infinix Hot 30 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/taste-titans-top-culinary-bloggers-and-youtubers/"><u>Taste Titans  Top Culinary Bloggers & YouTubers</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-powershell-for-user-account-control/"><u>Leveraging PowerShell for User Account Control</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-best-free-online-video-cutters-top-picks/"><u>New Best Free Online Video Cutters Top Picks</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-overcome-windows-memory-errors/"><u>Steps to Overcome Windows Memory Errors</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/unleash-your-creativity-12-free-animation-apps-for-windows-and-mac-for-2024/"><u>Unleash Your Creativity 12 Free Animation Apps for Windows and Mac for 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-flash-dead-xiaomi-13-ultra-safely-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Flash Dead Xiaomi 13 Ultra Safely | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/remote-server-files-via-nas-sharing/"><u>Remote Server Files via NAS Sharing</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-upgrade-to-virtualbox-70-on-windows-11/"><u>How to Upgrade to VirtualBox 7.0 on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-invalid-temp-directories-in-windows-11/"><u>Resolving Invalid Temp Directories in Windows 11</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/enhance-your-musical-journey-on-discord-with-top-audio-aids/"><u>Enhance Your Musical Journey on Discord with Top Audio Aids</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-non-detecting-speakers-or-headphones-in-winos/"><u>Fixing Non-Detecting Speakers or Headphones in WinOS</u></a></li>
<li><a href="https://windows11.techidaily.com/recovering-faulty-tab-key-on-your-pc/"><u>Recovering Faulty Tab Key on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/impact-breakdown-the-eradication-of-taskbar-chat-in-windows-11/"><u>Impact Breakdown: The Eradication of Taskbar Chat in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-for-genuine-adobe-error-message/"><u>Quick Fix for Genuine Adobe Error Message</u></a></li>
</ul></div>
