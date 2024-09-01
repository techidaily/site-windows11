---
title: "Unblocking Windows 11: How to Resolve Elevation Error #740"
date: 2024-08-31T22:18:27.827Z
updated: 2024-09-01T22:18:27.827Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unblocking Windows 11: How to Resolve Elevation Error #740"
excerpt: "This Article Describes Unblocking Windows 11: How to Resolve Elevation Error #740"
keywords: Fix Win11 Elevation Fail,Resolve Win11 Err740,Unblock Win11 Install,Remove Win11 Elevate Error,Correct Win11 Error 740,Eliminate Windows 11 Err740,Clear Elevation Issue Win11
thumbnail: https://thmb.techidaily.com/08b59308ea1479863a214168a367629cf0b1393331c870e52c284f342d82b8ac.jpeg
---

## Unblocking Windows 11: How to Resolve Elevation Error #740

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
## 3\. Turn Off the User Account Control Feature

 User Account Control is the security feature that throws up notifications when programs try to make changes. UAC could be a potential cause of error 740 when it’s set very high. So, try turning off UAC before running affected apps. Our [guide to disabling User Account Control](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) tells you how to turn off that feature.

![The User Account Control Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/user-account-control-settings.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
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
<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
![the-enabled-radio-button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-enabled-radio-button.jpg)
4. Select **Apply** to turn off Admin Approval Mode.
5. To close the policy window, select the **OK** option.

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
## 7\. Disable Third-Party Antivirus Software Packages

 Have you installed a third-party antivirus or security app on your PC? If you have, your third-party security software could be causing error 740 by blocking the EXE file you’re trying to run. This can happen when the antivirus software flags the application file as malicious.

 The potential solution, in this case, is to temporarily disable third-party antivirus software before trying to run affected programs. Look for and select an option that turns off the antivirus shield by right-clicking on the antivirus software’s system tray icon. If there are time options available, select to turn the real-time protection off for about an hour or so.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 If disabling the security software works, you don’t necessarily have to turn the security software off whenever you want to run the application file. Your antivirus software will probably include an exclusion list to which you can add trustworthy program file exceptions. Add the affected EXE file there to exclude it from the antivirus protection.

## 8\. Migrate to a New Admin User Account

 If the “requested operation requires elevation” error persists after trying other resolutions, your user account might be corrupted. Then you might need to create and utilize a new admin account to resolve this issue. You can migrate to that account by copying files from your old user account into the new one.

![The Add account option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/add-account-option.jpg)

 To apply this troubleshooting method for the “requested operation requires elevation” error, follow the instructions within this article about [how to fix Windows issues by creating new user accounts](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/). First, you’ll need to set up and sign in to the new admin account to see if the error occurs there. If not, transfer user files into the new account as covered there.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
## Get Error 740 Sorted on Windows

 The “requested operation requires elevation” error is an inconvenient admin access privilege issue many users have needed to fix. Users have resolved that issue by applying the potential resolutions in this guide. So, try applying those fixes for the “requested operation requires elevation” error in the order specified to find one that works on your Windows 10 or 11 PC.

 This is how you can fix error 740 within Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-posts.techidaily.com/new-2024-approved-enduring-connection-techniques-for-tiktok-profiles/"><u>[New] 2024 Approved  Enduring Connection Techniques for TikTok Profiles</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-transform-into-a-youtuber-best-tutorials-for-novices/"><u>[New] Transform Into a YouTuber  Best Tutorials for Novices</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-elevating-video-quality-incorporating-bb-and-lc-elements-in-fb/"><u>[Updated] 2024 Approved  Elevating Video Quality  Incorporating BB and LC Elements in FB</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-professional-stabilizers-roundup-securing-smooth-cinematography/"><u>[Updated] Professional Stabilizers Roundup  Securing Smooth Cinematography</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/approved-navigating-youtubes-seo-landscape-key-techniques/"><u>2024 Approved  Navigating YouTube's SEO Landscape  Key Techniques</u></a></li>
<li><a href="https://techtrends.techidaily.com/demystifying-net-neutrality-principles-benefits-and-challenges/"><u>Demystifying Net Neutrality: Principles, Benefits & Challenges</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/easy-connection-guide-setting-up-your-phone-as-an-interchangeable-control-for-ocul/"><u>Easy Connection Guide: Setting Up Your Phone as an Interchangeable Control for Ocul</u></a></li>
<li><a href="https://windows11.techidaily.com/expose-the-invisible-uncover-windows-11s-concealed-settings/"><u>Expose the Invisible: Uncover Windows 11'S Concealed Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-the-most-serious-javascript-problems-in-discord-on-w10w11-pcs/"><u>Fixing the Most Serious Javascript Problems in Discord on W10/W11 PCs</u></a></li>
<li><a href="https://android-location.techidaily.com/for-people-wanting-to-mock-gps-on-google-pixel-8-pro-devices-drfone-by-drfone-virtual/"><u>For People Wanting to Mock GPS on Google Pixel 8 Pro Devices | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/from-phones-playground-to-pc-realm-android-games-via-microsoft-and-google/"><u>From Phone's Playground to PC Realm: Android Games via Microsoft & Google</u></a></li>
<li><a href="https://tech-revival.techidaily.com/guarding-your-chats-how-to-avoid-chatgpt-saving-interactions/"><u>Guarding Your Chats: How to Avoid ChatGPT Saving Interactions</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-convert-mkv-to-mp4-in-windows/"><u>How to Convert MKV to MP4 in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-hide-the-language-bar-from-the-windows-11-taskbar/"><u>How to Hide the Language Bar From the Windows 11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reactivate-a-frozen-qbittorrent-tracker/"><u>How to Reactivate a Frozen qBittorrent Tracker</u></a></li>
<li><a href="https://windows11.techidaily.com/integrating-aguard-technology-into-windows-11s-edge-web-experience/"><u>Integrating Aguard Technology Into Windows 11'S Edge Web Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/journey-into-creativity-initiating-ms-paint-on-win11/"><u>Journey Into Creativity: Initiating MS Paint on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-rectifying-fatal-javascript-glitch-in-win-based-discord/"><u>Mastering the Art of Rectifying Fatal Javascript Glitch in Win-Based Discord</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-xpatch-troubleshooting/"><u>Mastering Windows XPatch Troubleshooting</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-guide-navigating-and-controlling-windows-fn-key/"><u>Mastery Guide: Navigating and Controlling Windows' Fn Key</u></a></li>
<li><a href="https://windows11.techidaily.com/microsoft-and-local-unpacking-key-contrasts-in-windows-login-mechanisms/"><u>Microsoft & Local: Unpacking Key Contrasts in Windows Login Mechanisms</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/new-a-brief-review-of-capcut-translate-with-alternative-for-2024/"><u>New A Brief Review of CapCut Translate With Alternative for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/no-more-maintenance-alert-post-support-for-windows-781/"><u>No More Maintenance Alert: Post-Support for Windows 7/8.1</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-up-safe-browsing-for-kids-on-windows-11/"><u>Setting Up Safe Browsing for Kids on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-your-response-invalid-captcha-mistake/"><u>Solving 'Your Response Invalid' CAPTCHA Mistake</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-windows-11-search-issue-unlocking-the-settings-apps-search-bar/"><u>Solving Windows 11 Search Issue: Unlocking the Settings App's Search Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/steady-app-placement-tips-for-windows-task-manager/"><u>Steady App Placement Tips for Windows Task Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-address-file-system-problems-in-win11/"><u>Strategies to Address File System Problems in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-solutions-overcome-blue-screen-on-win11s-hypervisor/"><u>Swift Solutions: Overcome Blue Screen on Win11's HYPERVISOR</u></a></li>
<li><a href="https://windows11.techidaily.com/tackle-microsoft-store-login-challenges/"><u>Tackle Microsoft Store Login Challenges</u></a></li>
<li><a href="https://windows11.techidaily.com/the-seamless-interweaving-of-folders-and-files/"><u>The Seamless Interweaving of Folders & Files</u></a></li>
<li><a href="https://windows11.techidaily.com/top-windows-climate-trackers-windows-1011/"><u>Top Windows Climate Trackers (Windows 10/11)</u></a></li>
<li><a href="https://win-forum.techidaily.com/1723010917603-troubleshooting-rocket-league-overcoming-launch-obstacles-easily/"><u>Troubleshooting Rocket League: Overcoming Launch Obstacles Easily!</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-mail-error-code-zero-x-eight-oh-three-one-f/"><u>Troubleshooting Windows Mail Error Code: Zero X Eight Oh Three One F</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-windows-hello-tips-for-fingerprint-issues/"><u>Unblocking Windows Hello: Tips for Fingerprint Issues</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>