---
title: How to Correct the 'Audio Device Not Stopped' Error on Win
date: 2024-08-22T21:36:24.699Z
updated: 2024-08-23T21:36:24.699Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Correct the 'Audio Device Not Stopped' Error on Win
excerpt: This Article Describes How to Correct the 'Audio Device Not Stopped' Error on Win
keywords: Fixing Audio Stop Error Windows,Solving Win Audio Halt Issue,Win Audio Disconnect Remedy,Resolve Audio Device Crash in Windows,Correcting PC Sound Stoppage Error,Mend Audio Hardware Failure Windows,Eliminate Win Audio Malfunction
thumbnail: https://thmb.techidaily.com/0464d20c8383250ad5eec7dae311ce3366a21c1ceecc558739dbb36535dbfcf9.jpg
---

## How to Correct the 'Audio Device Not Stopped' Error on Win

 It’s advisable to safely eject a USB drive inserted in your Windows 11/10 PC. However, upon doing so, some users report seeing an error message that reads “Windows can’t stop your generic volume device.” Consequently, users can’t safely eject USB drives with their PCs on.

 Of course, you can still safely remove a USB drive with a PC off. However, many users still prefer to be able to safely eject their connected drives without shutting down their computer. This is how you can fix the “Windows can’t stop your generic volume device” error.

## 1\. Disable Background App Processes

 Disabling background app processes is the first thing you should try when you see the “Windows can’t stop your generic volume device” error. Even the error message suggests closing programs that could still be using the device.

 Make sure there aren’t any minimized software windows on your taskbar; close unneeded apps within the system tray area by right-clicking their icons and selecting exit options.

![System tray icons](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/system-tray-programs.jpg)

 Beyond the taskbar and system tray, you’ll need to look for and disable background app processes with Task Manager. Task Manager is a tool that provides a comprehensive overview of app and service background processes.

 Our guide on [fixing too many background processes running](https://www.makeuseof.com/windows-pc-too-many-background-processes/) provides more detail on how to terminate unneeded background apps and services with Task Manager.

## 2\. End and Restart the Windows Explorer Process

 Some users confirm ending and restarting the File Explorer process fixes the “Windows can’t stop your generic volume device” error. That highlights File Explorer is causing the error and needs to be stopped from utilizing the USB drive.

 Follow these steps to end and restart File Explorer:

1. Right-click a taskbar space and select the **Task Manager** context menu option.
2. Scroll down the **Processes** tab in Task Manager until you see Windows Explorer.
3. Right-click Windows Explorer and select **End task**. Your desktop will go blank, but restarting Explorer will restore it.  
![The End task option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/end-task-option.jpg)
4. Click Task Manager’s **File** menu.
5. Select **Run new task** on the menu.
6. Then input **explorer** in Create new task.  
![The Create a new task tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-create-a-new-task-window.jpg)
7. Select **Create this task with administrative privileges**.
8. Click **OK** to restart Explorer.

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Troubleshoot the Device

 You can troubleshoot a USB device by running the Hardware and Devices troubleshooter with the drive connected. That troubleshooter might address some drive ejection issues.

 The Hardware and Devices troubleshooter isn’t listed in Settings. However, you can still find and use it by opening it via the Command Prompt using these steps:

1. Press **Windows** key **+** **S** to activate a file search tool, and input Command Prompt within its text box.
2. Select **Command Prompt** to open it from the search results.
3. Input and execute this Hardware and Devices command:  
`msdt.exe -id DeviceDiagnostic`  
![The Hardware and Devices troubleshooter command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hardware-and-devices-troubleshooter.jpg)
4. Click **Next** to run the troubleshooting tool.  
![The Hardware and Devices troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hardware-and-devices-troubleshooter4.jpg)
5. The troubleshooter might ask you to select a device. If it does, select your connected USB storage device.  
<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254762&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/11_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
![A USB Attached option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/usb-attached-option.jpg)
6. Click **Apply this fix** if the Hardware and Devices troubleshooter suggests a resolution.

## 4\. Select the Quick Removal Option

 Selecting the **Quick Removal** option is another confirmed fix for the “Windows can’t stop your generic volume device” error. The **Quick Removal** option disables write caching. You can select the **Quick Removal** option for an affected drive using the following steps:

1. Click File Explorer’s taskbar shortcut and select This PC.
2. Right-click your USB drive and select **Properties**.
3. Click the **Hardware** tab.  
![The Hardware tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-hardware-tab.jpg)
4. Then press the **Properties** button.
<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Click **Change settings** to bring up another window.  
![The Change settings button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-settings-button.jpg)
6. Select **Policies** in the second window.
7. Then click the **Quick removal (default)** option.  
![The Quick removal radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/quick-removal-option.jpg)
8. Select **OK** to exit the device properties window.
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
## 5\. Deselect the Index Drive Setting

 Having file indexing enabled for an external USB drive can cause the “Windows can’t stop your generic volume” error. If that option is enabled, files copied onto your USB drive will be indexed, which can keep it in use for some time after transferring lots of files onto it.

 Follow these steps to deselect indexing for a USB drive:

1. Go to This PC in File Explorer.
2. Right-click the USB drive connected and select **Properties**.
3. Deselect the **Allow files on this drive to have contents indexed in addition to file properties** option.  
![The Allow files on this drive to have contents indexed box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/index-option.jpg)
4. Select **Apply** and **OK** to set the drive’s new setting.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Set the Connected USB Drive to Be in Offline Mode

 A lot of users have fixed the “Windows can’t stop your generic volume device” error by setting their USB drives into offline mode. So, try setting your connected USB drive to offline mode with the DiskPart command-line line tool using these steps:

1. Press the **Windows** logo + **R** key combo for activating Run.
2. Input **cmd** into Run, and press **Ctrl** \+ **Shift** \+ **Enter** to [open Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
3. Then input this Diskpart command and hit **Enter**:  
`diskpart`
4. To view a drive list, input the following text and press **Return**:  
`list disk`  
![The diskpart command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/list-disk-command.jpg)
5. Next, execute this command to select your USB drive:  
`select disk <drive number>`
6. Finally, set the selected disk to offline by executing this command:  
`offline disk`  
![The offline command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/offline-command.jpg)

<!-- affiliate ads begin -->

<!-- affiliate ads end -->
 You will need to replace **<drive number>** for the select disk command with the actual number of your USB drive listed by Diskpart. For example, if your USB drive is disk 1, the required command would look like this:

`select disk 1`

 Setting a drive offline changes its status to missing. You can set the same drive back to an online status by repeating steps one to five above and then executing this command:

`online disk`

## 7\. Assign a Different Letter to the USB Drive

 Some users have also resolved the “Windows can’t stop your generic volume device” by changing the letters of their USB drives. Assigning a different letter to a USB drive will disconnect it from certain processes.

 You can even change the drive letter back to what it originally was another time. To apply this fix, check out this [guide to changing a drive’s letter in Windows](https://www.makeuseof.com/tag/change-drive-letter-windows/).

![The Disk Management tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disk-management-window.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Safely Eject Your USB Drive

 Removing a USB drive from a PC without safely ejecting it can corrupt the data on it. So, it’s not a good idea to ignore the “Windows can’t stop your generic volume device” error.

 Applying the potential solutions covered here will resolve the error for most users. Then, you can safely remove your USB drive in Windows 11/10 with alternative methods.

 Of course, you can still safely remove a USB drive with a PC off. However, many users still prefer to be able to safely eject their connected drives without shutting down their computer. This is how you can fix the “Windows can’t stop your generic volume device” error.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-files.techidaily.com/new-10-best-apps-for-editing-igtv-vertical-videos-for-2024/"><u>[New] 10 Best Apps for Editing IGTV Vertical Videos for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-best-bits-of-bulb-tech-top-17-choices/"><u>[New] 2024 Approved  Best Bits of Bulb Tech - Top 17 Choices</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-key-commodities-for-your-company-8-indispensable-tools-that-cant-be-ignored/"><u>[New] In 2024, Key Commodities for Your Company  8 Indispensable Tools That Can’t Be Ignored</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-quick-cinematic-creations-your-ultimate-guide-to-at-home-filmmaking-hacks/"><u>[New] Quick Cinematic Creations  Your Ultimate Guide to At-Home Filmmaking Hacks</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-breathtaking-cinematography-with-5-best-slow-motion-cameras-for-2024/"><u>[Updated] Breathtaking Cinematography with 5 Best Slow-Motion Cameras for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-captivate-audiences-quickly-shortcuts-for-youtube-trailers-with-filmora/"><u>[Updated] Captivate Audiences Quickly  Shortcuts for YouTube Trailers with Filmora</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-expert-filmmaking-skills-on-youtube-and-diverse-platforms-for-2024/"><u>[Updated] Expert Filmmaking Skills on YouTube and Diverse Platforms for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-instagram-success-secrets-maximizing-post-performance/"><u>2024 Approved  Instagram Success Secrets  Maximizing Post Performance</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-preeminent-5-photo-background-changer-tools-iphone-x87-edition/"><u>2024 Approved  Preeminent 5 Photo Background Changer Tools  IPhone X/8/7 Edition</u></a></li>
<li><a href="https://unlock-android.techidaily.com/7-ways-to-unlock-a-locked-xiaomi-14-ultra-phone-by-drfone-android/"><u>7 Ways to Unlock a Locked Xiaomi 14 Ultra Phone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/a-complete-guide-to-oem-unlocking-on-itel-p40-by-drfone-android/"><u>A Complete Guide To OEM Unlocking on Itel P40</u></a></li>
<li><a href="https://tech-haven.techidaily.com/crafting-advanced-ai-queries-navigating-anthropics-claude-3-innovations-in-the-prompt-store/"><u>Crafting Advanced AI Queries: Navigating Anthropic’s Claude 3 Innovations in the Prompt Store</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/discover-these-15-complimentary-antimalware-applications/"><u>Discover These 15 Complimentary Antimalware Applications</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/essential-quick-tricks-mastering-the-ios-shortcuts-feature-on-your-iphoneipad/"><u>Essential Quick Tricks: Mastering the iOS Shortcuts Feature on Your iPhone/iPad</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-error-code-e84-on-steam-for-windows/"><u>How to Fix the Error Code E84 on Steam for Windows</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-nokia-xr21-drfone-by-drfone-virtual-android/"><u>In 2024, How PGSharp Save You from Ban While Spoofing Pokemon Go On Nokia XR21? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-your-oppo-reno-8t-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Your Oppo Reno 8T Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://fox-blue.techidaily.com/in-2024-unleash-the-potential-a-comprehensively-curated-list-of-nft-creating-engines/"><u>In 2024, Unleash the Potential  A Comprehensively Curated List of NFT-Creating Engines</u></a></li>
<li><a href="https://windows11.techidaily.com/instant-wallpaper-update-the-simple-windows-method/"><u>Instant Wallpaper Update: The Simple Windows Method</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11s-fast-flip-buttons/"><u>Mastering Windows 11'S Fast Flip Buttons</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-in-moving-between-focused-and-unfocused-states-within-windows-terminal/"><u>Mastery in Moving Between Focused and Unfocused States Within Windows Terminal</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-of-access-control-regedit-in-win11/"><u>Mastery of Access Control: RegEdit in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-tasks-like-a-pro-admin-mode-for-task-manager-on-windows-11/"><u>Navigate Tasks Like a Pro: Admin Mode for Task Manager on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-through-time-windows-11-file-history-essentials/"><u>Navigate Through Time: Windows 11 File History Essentials</u></a></li>
<li><a href="https://program-issues.techidaily.com/optimizing-playtime-preventing-manor-lords-from-crashing-on-your-computer/"><u>Optimizing Playtime: Preventing Manor Lords From Crashing on Your Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/skip-bloatware-embrace-pure-windows-11-experience/"><u>Skip Bloatware: Embrace Pure Windows 11 Experience!</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-the-invalid-system-id-issue-on-windows-11/"><u>Solving the Invalid System ID Issue on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-enforce-local-policies-to-a-specific-user-in-windows-11/"><u>Steps to Enforce Local Policies to a Specific User in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-microsoft-store-glitch-error-code-0x800704cf/"><u>Steps to Resolve Microsoft Store Glitch (Error Code 0X800704CF)</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-repairing-crashing-ccleaner-in-windows-1011/"><u>Strategies for Repairing Crashing CCleaner in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-tracking-storage-spent-on-apps/"><u>Strategies for Tracking Storage Spent on Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-fix-windows-11-assistive-application/"><u>Strategies to Fix Windows 11 Assistive Application</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-presentations-windows-11-remove-pin-lock/"><u>Streamline Presentations: Windows 11, Remove PIN Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-screen-hotkey-based-program-minimization-techniques/"><u>Streamline Your Screen: Hotkey-Based Program Minimization Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-guide-to-identify-your-graphic-model-in-win11/"><u>Swift Guide to Identify Your Graphic Model in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-guidance-for-choosing-between-nvidia-gamestudio-drivers/"><u>Tailored Guidance for Choosing Between Nvidia Game/Studio Drivers</u></a></li>
<li><a href="https://fox-that.techidaily.com/troubleshooting-tips-for-overcoming-mmi2-no-sim-card-provisioning-errors/"><u>Troubleshooting Tips for Overcoming 'MMI2 - No SIM Card Provisioning' Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/tweaking-device-settings-on-windows-11-a-step-by-step-guide/"><u>Tweaking Device Settings on Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/upside-down-visuals-instagrams-guide-to-flipping-and-sharing-videos/"><u>Upside Down Visuals  Instagram's Guide to Flipping & Sharing Videos</u></a></li>
<li><a href="https://howto.techidaily.com/why-does-my-oppo-reno-10-proplus-5g-keep-turning-off-by-itself-6-fixes-are-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Does My Oppo Reno 10 Pro+ 5G Keep Turning Off By Itself? 6 Fixes Are Here | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-breaks-boundaries-with-iosmacwindows-pc-support/"><u>Windows Breaks Boundaries with iOS/Mac/Windows PC Support</u></a></li>
<li><a href="https://windows11.techidaily.com/zeroing-out-wsl-complete-uninstallation-in-windows-11/"><u>Zeroing Out WSL: Complete Uninstallation in Windows 11</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>