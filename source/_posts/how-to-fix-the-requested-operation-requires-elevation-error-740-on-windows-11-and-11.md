---
title: How to Fix the “Requested Operation Requires Elevation” Error 740 on Windows 11 & 11
date: 2024-09-05T02:17:40.957Z
updated: 2024-09-06T02:17:40.957Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix the “Requested Operation Requires Elevation” Error 740 on Windows 11 & 11
excerpt: This Article Describes How to Fix the “Requested Operation Requires Elevation” Error 740 on Windows 11 & 11
keywords: Windows 11 Error Fixing,Win11 Operation Elevation,Elevate Window Error,Solve Win11 Errors,Troubleshoot Win740,Eliminate WinError740,Windows 11 Fix Error 740
thumbnail: https://thmb.techidaily.com/15566fd0d6cad9f26c793e08c16498fac2c5b48034aed23a907d05190328dc6a.png
---

## How to Fix the “Requested Operation Requires Elevation” Error 740 on Windows 11 & 11

 Some users have reported in support forum posts that error 740 occurs when they try to run programs or access folders on Windows PCs. The error 740 message says, “The requested operation requires elevation.” Users can’t access software, folders, or files for which error 740 occurs.

 This is how you can fix error 740 within Windows 10 and 11\.

## 1\. Run the Affected Programs With Admin Rights

 The error 740 message mentions the need for operation elevation. That’s a hint to try running affected programs with elevated (administrator) rights. Check out this guide on [always running apps as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) to set affected EXE files to run with elevated rights.

![The Run this program as an administrator checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-this-program-as-an-administrator.jpg)

## 2\. Set Programs to Run in Compatibility Mode

 It’s also recommended to set older programs to run in compatibility mode. Doing so might address a compatibility issue causing error 740\. You can set an affected program to run in compatibility mode like this:

1. Open the affected software’s installation within File Explorer.
2. Right-click an affected program’s EXE (application file) and select **Properties** \> **Compatibility**.
3. Select **Run this program in compatibility mode for** and choose Windows 8 or an older platform on the drop-down menu. It’s best to select the Windows platform for which the publisher originally released the software.  
![The Run this program in compatibility mode drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-this-program-in-compatibility-mode.jpg)
4. Press the **Apply** \> **OK** buttons to set the compatibility mode setting.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123740/7443" target="_top" id="2123740">
  <img src="//a.impactradius-go.com/display-ad/7443-2123740" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123740/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Turn Off the User Account Control Feature

 User Account Control is the security feature that throws up notifications when programs try to make changes. UAC could be a potential cause of error 740 when it’s set very high. So, try turning off UAC before running affected apps. Our [guide to disabling User Account Control](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) tells you how to turn off that feature.

![The User Account Control Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/user-account-control-settings.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484950/16446" target="_top" id="1484950">
  <img src="//a.impactradius-go.com/display-ad/16446-1484950" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484950/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130875/7443" target="_top" id="2130875">
  <img src="//a.impactradius-go.com/display-ad/7443-2130875" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130875/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Adjust Folder Permission Settings

 This potential resolution is recommended for users who can’t access specific folders because of error 740\. In that scenario, this error can be a folder permissions issue that selecting the **Replace all child object permission entries** option could feasibly address.

 Try selecting the **Replace all child object permission** setting for an affected folder as follows:

1. Press **Win + E** to bring up File Explorer.
2. Open whatever directory contains the folder for which error 740 occurs.
3. Right-click the affected folder and select that directory’s **Properties** option.
4. Select **Security** on the window’s tab bar.
5. Click **Advanced** to access more security settings.  
![The Security tab and Advanced button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-security-tab3.jpg)
6. Select the **Replace all child object permissions entries with inheritable permission entries from this object** checkbox.  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135405/19272" target="_top" id="2135405">
  <img src="//a.impactradius-go.com/display-ad/19272-2135405" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135405/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Replace all child object permission entries checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/replace-all-child-objects-option.jpg)
7. Click **Apply** on the Advanced Security Settings window.
8. Select **Yes** when asked to continue.
9. Exit the folder’s properties window and restart your PC.

## 5\. Modify the Behavior of the UAC Elevation Prompt

 If your Windows PC has the Group Policy Editor, try changing the behavior of UAC’s elevation prompt with that tool. Selecting the **Elevate without prompting** setting for the User Account Control: Behavior policy could fix error 740 for some users.

 You can select that option within Windows Enterprise and Pro editions like this:

1. Open the Local Group Policy Editor. If you need help, check out the [ways to open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).
2. Next, double-click **Computer Configuration** to expand that sidebar navigation option.
3. Double-click **Windows Settings** and select **Security S** **ettings**.
4. Then go to **Local Policies** and **Security Options** to access User Account Control Policy settings.  
![Security Options within Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/security-options.jpg)
5. Double-click the **User Account Control: Behavior of the elevation prompt for administrators in Admin Approval Mode** policy.
6. Select the **Elevate without prompting** option on the drop-down menu.  
![The Elevate without prompting option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/elevate-without-prompting.jpg)
7. Click **Apply** to set the **Elevate without prompting policy**.
8. Select **OK** to close the policy setting’s window.
9. Then reboot Windows after closing Group Policy Editor.

## 6\. Disable Admin Approval Mode

 Admin Approval Mode prompts administrative users for task permissions when enabled. It’s a strict Group Policy Editor security policy that can potentially cause elevation issues. Follow these steps to turn off Admin Approval Mode.

1. Go to **Security Options** in Group Policy Editor as outlined for steps one to four of resolution five.
2. Double-click the **User Account Control: Admin Approval Mode for the Built-in Administrator account** policy setting.  
![The Admin Approval Mode policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/admin-approval-mode-policy.jpg)
3. Click the **Disabled** radio button if this policy is enabled.  
<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/352555/5172" target="_top" id="352555">
  <img src="//a.impactradius-go.com/display-ad/5172-352555" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/352555/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![the-enabled-radio-button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-enabled-radio-button.jpg)
4. Select **Apply** to turn off Admin Approval Mode.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2024329/7443" target="_top" id="2024329">
  <img src="//a.impactradius-go.com/display-ad/7443-2024329" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2024329/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. To close the policy window, select the **OK** option.

## 7\. Disable Third-Party Antivirus Software Packages

 Have you installed a third-party antivirus or security app on your PC? If you have, your third-party security software could be causing error 740 by blocking the EXE file you’re trying to run. This can happen when the antivirus software flags the application file as malicious.

 The potential solution, in this case, is to temporarily disable third-party antivirus software before trying to run affected programs. Look for and select an option that turns off the antivirus shield by right-clicking on the antivirus software’s system tray icon. If there are time options available, select to turn the real-time protection off for about an hour or so.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 If disabling the security software works, you don’t necessarily have to turn the security software off whenever you want to run the application file. Your antivirus software will probably include an exclusion list to which you can add trustworthy program file exceptions. Add the affected EXE file there to exclude it from the antivirus protection.

## 8\. Migrate to a New Admin User Account

 If the “requested operation requires elevation” error persists after trying other resolutions, your user account might be corrupted. Then you might need to create and utilize a new admin account to resolve this issue. You can migrate to that account by copying files from your old user account into the new one.

![The Add account option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/add-account-option.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043639/7443" target="_top" id="2043639">
  <img src="//a.impactradius-go.com/display-ad/7443-2043639" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043639/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 To apply this troubleshooting method for the “requested operation requires elevation” error, follow the instructions within this article about [how to fix Windows issues by creating new user accounts](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/). First, you’ll need to set up and sign in to the new admin account to see if the error occurs there. If not, transfer user files into the new account as covered there.

<!-- affiliate ads begin -->
<span id="1983582">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983582.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983582">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983582.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983582%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983582/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get Error 740 Sorted on Windows

 The “requested operation requires elevation” error is an inconvenient admin access privilege issue many users have needed to fix. Users have resolved that issue by applying the potential resolutions in this guide. So, try applying those fixes for the “requested operation requires elevation” error in the order specified to find one that works on your Windows 10 or 11 PC.

 This is how you can fix error 740 within Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-premium-podcasters-at-universities/"><u>[New] 2024 Approved  Premium Podcasters at Universities</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-swiftly-rotate-videos-in-vlc-for-smooth-viewing/"><u>[New] 2024 Approved  Swiftly Rotate Videos in VLC for Smooth Viewing</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-step-by-step-vsco-image-enhancement/"><u>[New] Step-by-Step VSCO Image Enhancement</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-ultimate-cheat-sheet-for-using-movie-maker-on-win11/"><u>[New] The Ultimate Cheat Sheet for Using Movie Maker on Win11</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-winning-the-subscriber-race-on-youtube/"><u>[New] Winning the Subscriber Race on YouTube</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-showcase-mastery-weaving-youtube-into-instagram-tales/"><u>[Updated] 2024 Approved  Showcase Mastery  Weaving YouTube Into Instagram Tales</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-elevate-your-social-media-presence-with-these-5-igtv-tips-for-2024/"><u>[Updated] Elevate Your Social Media Presence with These 5 IGTV Tips for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-enhance-your-channels-voice-dive-into-the-world-of-banner-makers-apps-for-2024/"><u>[Updated] Enhance Your Channel's Voice  Dive Into the World of Banner Makers (Apps) for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-in-2024-tomtom-bandit-action-camera-review/"><u>[Updated] In 2024, TomTom Bandit Action Camera Review</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-tweaking-the-viewers-journey-the-art-of-custom-thumbnail-design-in-twitter/"><u>[Updated] In 2024, Tweaking the Viewer's Journey  The Art of Custom Thumbnail Design in Twitter</u></a></li>
<li><a href="https://article-posts.techidaily.com/budget-friendly-chinese-vr-gear-for-2024/"><u>Budget-Friendly Chinese VR Gear for 2024</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/comprehensive-guide-why-your-google-pixel-7-pro-needs-a-sturdy-screen-shield/"><u>Comprehensive Guide: Why Your Google Pixel 7 Pro Needs a Sturdy Screen Shield</u></a></li>
<li><a href="https://windows11.techidaily.com/establishing-controls-over-insider-build-exposure/"><u>Establishing Controls Over Insider Build Exposure</u></a></li>
<li><a href="https://buynow-help.techidaily.com/exploring-the-performance-of-apples-latest-m1-powered-macbook-air-13/"><u>Exploring the Performance of Apple's Latest M1 Powered MacBook Air 13</u></a></li>
<li><a href="https://windows11.techidaily.com/gateway-to-gaming-glory-using-dosbox-x-for-pc-classics/"><u>Gateway to Gaming Glory: Using DOSBox-X for PC Classics</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-exit-android-factory-mode-on-vivo-v30-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Exit Android Factory Mode On Vivo V30 Pro? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-0x0000004e-error-in-windows-10-and-11/"><u>How to Fix the 0X0000004E Error in Windows 10 and 11</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-the-complete-guide-to-xiaomi-redmi-note-13-5g-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Complete Guide to Xiaomi Redmi Note 13 5G FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-unlocking-iphone-6s-lock-screen-3-foolproof-methods-that-actually-work-drfone-by-drfone-ios/"><u>In 2024, Unlocking iPhone 6s Lock Screen 3 Foolproof Methods that Actually Work | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/is-sleep-hibernate-or-shutdown-best-for-your-windows-computer/"><u>Is Sleep, Hibernate, or Shutdown Best for Your Windows Computer?</u></a></li>
<li><a href="https://windows11.techidaily.com/master-linux-without-wsl/"><u>Master Linux without WSL</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-errors-in-windows-performance-dashboard/"><u>Overcoming Errors in Windows Performance Dashboard</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-wows-unexpected-shutdown-error-132-on-win11/"><u>Quick Fixes for WoW’s Unexpected Shutdown (Error 132) on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaiming-control-from-a-wildly-wandering-mouse/"><u>Reclaiming Control From a Wildly Wandering Mouse</u></a></li>
<li><a href="https://windows11.techidaily.com/reconfiguring-saving-preferences-for-pubg-on-pc/"><u>Reconfiguring Saving Preferences for PUBG on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-spontaneous-command-triggers-in-os/"><u>Remedying Spontaneous Command Triggers in OS</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-disappearing-windows-during-bootup/"><u>Resolving Disappearing Windows During Bootup</u></a></li>
<li><a href="https://windows11.techidaily.com/sayonara-to-sluggish-keys-top-tricks-for-win-11s-faster-typing/"><u>Sayonara to Sluggish Keys: Top Tricks for Win 11'S Faster Typing</u></a></li>
<li><a href="https://windows11.techidaily.com/seamlessly-switch-windows-11-walls-to-reflect-each-screens-style/"><u>Seamlessly Switch Windows 11 Walls to Reflect Each Screen's Style</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-a-blissful-experience-with-no-bluescreens-on-win11/"><u>Secure a Blissful Experience with No Bluescreens on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-your-virtual-world-steps-for-epic-save-safety/"><u>Securing Your Virtual World: Steps for Epic Save Safety</u></a></li>
<li><a href="https://windows11.techidaily.com/shelve-the-start-of-edge-windows-11s-solution/"><u>Shelve the Start of Edge: Windows 11'S Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/simplified-gpo-analysis-via-gpresult-command/"><u>Simplified GPO Analysis via GPResult Command</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-strategies-for-enhancing-virtual-memory-on-windows-11-systems/"><u>Tailored Strategies for Enhancing Virtual Memory on Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-overcoming-admin-restrictions-on-setup-errors/"><u>Techniques for Overcoming Admin Restrictions on Setup Errors</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/the-most-effective-9-microphone-capture-tools-online-2e-for-2024/"><u>The Most Effective 9 Microphone Capture Tools Online (2E) for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/the-ultimate-guide-to-vivo-y100i-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>The Ultimate Guide to Vivo Y100i Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://some-tips.techidaily.com/ultimate-devices-for-home-and-office-for-2024/"><u>Ultimate Devices for Home and Office for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-and-fixing-windows-11-search-errors/"><u>Unblocking and Fixing Windows 11 Search Errors</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>