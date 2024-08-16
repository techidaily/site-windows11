---
title: "Circumventing Driver Checks in Windows: No Signatures, Any Installation"
date: 2024-08-15T15:44:16.159Z
updated: 2024-08-16T15:44:16.159Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Circumventing Driver Checks in Windows: No Signatures, Any Installation"
excerpt: "This Article Describes Circumventing Driver Checks in Windows: No Signatures, Any Installation"
keywords: Bypassing Windows Driver Signature,Unsigned Driver Installs,Driver Installation Without Signature,Avoiding Driver Auth Checks,No-Signature Windows Drivers,Easy Driver Install, No Signature,Bypassing Windows Auth for Drivers
thumbnail: https://thmb.techidaily.com/6816402dd23c56a105ec64bc0a33bec17942a9ec34c261fc2115b1bb0464ace8.jpg
---

## Circumventing Driver Checks in Windows: No Signatures, Any Installation

 Sometimes, Windows will block you from installing an unsigned driver, which is a driver you've downloaded elsewhere other than through a Windows Update or the device manufacturer's website. But if you need the driver, and you know it is perfectly safe, you can turn off driver signature enforcement and let it through.

 In this guide, we're going to show you several ways to do it.

## How to Disable Driver Signature Enforcement in the Startup Settings

 A temporary way to disable driver signature enforcement is through Startup Settings, allowing you to install the unsigned drivers. However, the moment you restart your PC, Windows will re-enable driver signature enforcement. The unsigned drivers you've installed will still work, but you may not be able to install new ones.

 To disable driver signature enforcement this way, you'll have to [access the Startup Settings screen](https://www.makeuseof.com/windows-startup-settings/). The **Disable driver signature enforcement** option will be the seventh one, so press **F7** or **7** on your keyboard to select it.

![windows 11 startup settings safe mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-startup-settings-safe-mode.jpg)

 Your computer will then restart, and when it reboots, you'll be able to install those unsigned drivers.

## How to Disable Driver Signature Enforcement in the Local Group Policy Editor

 You can also disable driver signature enforcement by tweaking the **Code signing for driver packages** policy in the Local Group Policy Editor (LGPE). Doing this will allow you to install unsigned drivers even if you restart your computer.

 Unfortunately, you can only natively access the LGPE if you're on Windows Pro or Enterprise Edition. However, there is a way to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

1. Press **Win + S** to bring up Windows Search, enter **group policy** in the Search box, and select **Edit group policy** in the Search results.  
![Open Group Policy Editor Using Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-group-policy-editor-using-windows-search.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->
2. Once the LGPE opens up, head to **User Configuration > Administrative Templates > System > Driver Installation**.
3. Right-click **Code signing for driver packages** and select **Edit**.  
![editing the Code signing for driver packages policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/editing-the-code-signing-for-driver-packages-policy.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Click the **Enabled** radio button, and then, in the **Options** section, click on the dropdown and select **Ignore**.  
![enabling the Code signing for driver packages policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/enabling-the-code-signing-for-driver-packages-policy.jpg)
5. Click on **OK**.

 If you want to enable driver signature enforcement again, go back to step #4 and set the radio button to **Not configured**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
<!-- affiliate ads end -->
## How to Disable Driver Signature Enforcement in PowerShell

 Another way to disable driver signature enforcement is by running the command to turn off integrity checks in PowerShell (you'll have to run it as an administrator). And just like with the Local Group Policy Editor, it will remain disabled until you enable it again.

 Follow the steps below to turn off driver signature enforcement in PowerShell:

 You can disable driver signature enforcement by [opening Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) if you prefer it over PowerShell.

1. Right-click **Start** and select **Terminal (Admin)** on Windows 11 or **Windows PowerShell (Admin)** on Windows 10\.
2. Click **Yes** on the UAC prompt.
3. Copy **bcdedit /set nointegritychecks on** and paste it into PowerShell.  
![turning off driver signature enforcement in Terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/turning-off-driver-signature-enforcement-in-terminal.jpg)
4. Hit **Enter** to run the command.

 To turn on driver signature enforcement again, replace the command in step #3 with **bcdedit /set nointegritychecks off**.

 One potential problem you can run into when trying to turn off driver signature enforcement this way is an error stating **The value is protected by Secure Boot policy and cannot be modified or deleted**.

![Secure Boot error in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/secure-boot-error-powershell.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->

 If that is the case, you can try [turning off Secure Boot](https://www.makeuseof.com/tag/disable-secure-uefi-dual-boot/) and trying again. But if you don't want to do this, using Startup Settings and the Local Group Policy Editor is perfectly okay.

 You can also put Windows in test mode, which disables driver signature enforcement, allowing you to install those unsigned drivers. To enter test mode, follow the steps below (keep in mind that you may run into the Secure Boot error):

1. Right-click **Start** and select **Terminal (Admin)** on Windows 11 or **Windows PowerShell (Admin)** on Windows 10\.
2. Click **Yes** on the UAC prompt.
3. Copy **bcdedit /set testsigning on** and paste it into PowerShell.  
![turning on Test Mode in Terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/turning-on-test-mode-in-terminal.jpg)
<!-- affiliate ads begin -->
<span id="1793213">
					<video width="1080" height="1620" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19135-1793213">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:1080px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftinyland.pxf.io%2Fc%2F5597632%2F1793213%2F19135'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793213/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Hit **Enter** to run the command.

 Now restart your computer, and when it boots back up, it will be in test mode. After you're done installing those drivers, don't forget to disable test mode. The command to do that is **bcdedit /set testsigning off**.

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Now You Can Install Unsigned Drivers on Windows

 Installing unsigned drivers on Windows is not recommended, since they can lead to unexpected behavior. However, if you trust the driver, there's no reason why the OS should block you from installing it. Just use one of the methods mentioned above, and you should be able to install and use unsigned drivers on your Windows PC.

 In this guide, we're going to show you several ways to do it.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-channel-growth-essential-steps-for-youtube-backlink-creation-for-2024/"><u>[New] Channel Growth  Essential Steps for YouTube Backlink Creation for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-flawlessimage-advanced-bg-eraser-app/"><u>[New] FlawlessImage  Advanced BG Eraser App</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-gamings-finest-top-12-tycoon-games-ensuring-hours-of-fun-for-2024/"><u>[New] Gaming's Finest - Top 12 Tycoon Games Ensuring Hours of Fun for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/iew-count-rewards-on-youtube-per-million/"><u>[New] View Count Rewards on YouTube – Per Million?</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-overcoming-facebook-message-app-video-send-errors/"><u>[Updated] 2024 Approved  Overcoming Facebook Message App Video Send Errors</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-a-symphony-of-streams-harmonizing-your-multiple-youtube-views/"><u>[Updated] A Symphony of Streams  Harmonizing Your Multiple YouTube Views</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-fast-fixes-for-capturing-games-on-devices-for-2024/"><u>[Updated] Fast Fixes for Capturing Games on Devices for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-boost-your-meeting-impact-with-efficient-screen-sharing/"><u>[Updated] In 2024, Boost Your Meeting Impact with Efficient Screen Sharing</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/3-ways-for-android-pokemon-go-spoofing-on-samsung-galaxy-m14-4g-drfone-by-drfone-virtual-android/"><u>3 Ways for Android Pokemon Go Spoofing On Samsung Galaxy M14 4G | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/candids-canvas-transforming-photos-with-editing-tips-for-2024/"><u>Candid's Canvas  Transforming Photos with Editing Tips for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/easily-unlock-your-vivo-x90s-device-sim-by-drfone-android/"><u>Easily Unlock Your Vivo X90S Device SIM</u></a></li>
<li><a href="https://android-frp.techidaily.com/easy-guide-to-oneplus-frp-bypass-with-best-methods-by-drfone-android/"><u>Easy Guide to OnePlus FRP Bypass With Best Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/effortlessly-switching-files-between-formats-in-windows/"><u>Effortlessly Switching Files Between Formats in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-fatigued-performance-in-win10plusedge-browser/"><u>Fixing Fatigued Performance in Win10+Edge Browser</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/follower-fallout-on-instagram-how-to-spot-it-for-2024/"><u>Follower Fallout on Instagram  How to Spot It for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/gaming-past-present-atlasos-enablement/"><u>Gaming Past, Present: AtlasOS Enablement</u></a></li>
<li><a href="https://windows11.techidaily.com/hidden-screens-revealed-the-most-effective-6-techniques-to-recover-off-screen-apps-in-win/"><u>Hidden Screens Revealed: The Most Effective 6 Techniques to Recover Off-Screen Apps in Win</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-disable-amdnvidia-graphics-ui-extras/"><u>How to Disable AMD/Nvidia Graphics UI Extras</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-ignore-microsofts-app-verification-warnings/"><u>How to Ignore Microsoft's App Verification Warnings</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reactivate-a-unresponsive-windows-start-button/"><u>How to Reactivate a Unresponsive Window's Start Button</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-resolve-offline-printer-problems-in-os/"><u>How To Resolve Offline Printer Problems in OS</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-revert-your-windows-backup-settings/"><u>How To Revert Your Windows Backup Settings</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-ways-to-stop-parent-tracking-your-apple-iphone-15-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, Ways to stop parent tracking your Apple iPhone 15 Pro | Dr.fone</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/in-depth-look-at-the-style-and-performance-of-the-fitbit-charge-4/"><u>In-Depth Look at the Style and Performance of the Fitbit Charge 4</u></a></li>
<li><a href="https://windows11.techidaily.com/isolating-and-resolving-unilateral-sound-issue-on-win-os/"><u>Isolating and Resolving Unilateral Sound Issue on WIN OS</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/mastering-social-media-tags-leading-tools-reviewed-fbtwitterinsta-for-2024/"><u>Mastering Social Media Tags  Leading Tools Reviewed (FB/Twitter/Insta) for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-calculators-dark-scheme/"><u>Mastering Windows Calculator's Dark Scheme</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-connecting-to-dropbox-and-google-drive-directly/"><u>Mastering Windows: Connecting to Dropbox & Google Drive Directly</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-and-resolving-steam-setup-errors-with-win11/"><u>Navigating and Resolving Steam Setup Errors with Win11</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-contacts-from-oppo-by-fonelab-android-recover-contacts/"><u>Possible solutions to restore deleted contacts from Oppo .</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-battlenet-being-inaccessible-in-windows-1011/"><u>Quick Fixes for Battle.net Being Inaccessible in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-fixing-windows-updates-error-xcode-0x80246007/"><u>Solutions for Fixing Windows Updates Error – XCode 0X80246007</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-to-file-transfer-problems-on-windows-1011/"><u>Solutions to File Transfer Problems on Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-failed-page-loading-on-ms-store/"><u>Steps to Resolve Failed Page Loading on MS Store</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-tackle-stranded-error-on-xbox-app-windows-devices/"><u>Steps to Tackle 'Stranded' Error on Xbox App Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-resolve-windows-1110s-nvidia-access-problem/"><u>Strategies to Resolve Windows 11/10'S NVidia Access Problem</u></a></li>
<li><a href="https://fake-location.techidaily.com/the-best-8-vpn-hardware-devices-reviewed-on-itel-p55-5g-drfone-by-drfone-virtual-android/"><u>The Best 8 VPN Hardware Devices Reviewed On Itel P55 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-collection-of-task-management-tools-for-windows-11-users/"><u>The Ultimate Collection of Task Management Tools for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-file-download-issues-on-windows-11-6/"><u>Troubleshooting File Download Issues on Windows 11 (6)</u></a></li>
<li><a href="https://tech-hub.techidaily.com/ultimate-list-6-leading-chatgpt-addons-for-your-vs-code-workflow/"><u>Ultimate List: 6 Leading ChatGPT Addons for Your VS Code Workflow</u></a></li>
<li><a href="https://windows11.techidaily.com/unchained-gpt-on-your-machine-using-freedomgpt/"><u>Unchained GPT on Your Machine: Using FreedomGPT</u></a></li>
<li><a href="https://windows11.techidaily.com/what-are-windows-bsod-memory-dumps-and-how-can-they-help-you/"><u>What Are Windows BSoD Memory Dumps, and How Can They Help You?</u></a></li>
</ul></div>
