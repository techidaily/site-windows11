---
title: Overcoming Admin-Restricted Setup Issues in Windows
date: 2024-09-09T11:58:27.975Z
updated: 2024-09-10T11:58:27.975Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Admin-Restricted Setup Issues in Windows
excerpt: This Article Describes Overcoming Admin-Restricted Setup Issues in Windows
keywords: WinAdmin Restrictions Fix,Windows Permissions Guide,Unlocking OS Configurations,Bypass Admin Limits (Win),User-Friendly OS Setup,Access Control Adjustments,Secure OS Customization
thumbnail: https://thmb.techidaily.com/f75585e4daf78953dd0ce1cfd0b26209fab1e9c588003fe7de564148a8e3e23c.jpg
---

## Overcoming Admin-Restricted Setup Issues in Windows

 Installing software is usually a smooth process on Windows 10 and 11 PCs. However, sometimes installation hiccups can arise. For instance, some users have reported this error message appears when they try to install Windows software packages, “The system administrator has set policies to prevent this installation.”

 Users cannot install whatever programs for which that system administrator error arises. The error message suggests this issue is due to some kind of enforced admin settings. You can fix the “system administrator has set policies” error by applying the resolutions below.

## 1\. Run the Software’s Setup File as An Administrator

 First, start with the easiest of potential solutions. They don’t get much simpler than running the affected software’s installation file with administrative rights. Right-click the setup file for the software you can’t install and select **Run as administrator** on its context menu.

![The Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-run-as-administrator-option.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2128844/7443" target="_top" id="2128844">
  <img src="//a.impactradius-go.com/display-ad/7443-2128844" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2128844/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Enable the Built-in Windows Admin Account

 It has been confirmed by some users that activating and logging into the built-in (hidden) Windows admin account can fix the “system administrator has set policies” error. It’s recommended to try that even if your current user account is an administrative one. You can do that by following the instructions for the Command Prompt method in our guide to [enabling the built-in Windows administrator account](https://www.makeuseof.com/windows-11-enable-disable-built-in-administrator-account/).

![The net user administrator /active:yes command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/net-user-admin-account-command.jpg)

<!-- affiliate ads begin -->
<a href="https://smilemakers.pxf.io/c/5597632/2123901/26106" target="_top" id="2123901">
  <img src="//a.impactradius-go.com/display-ad/26106-2123901" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://smilemakers.pxf.io/i/5597632/2123901/26106" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 When you’ve activated the account, restart your Windows PC. Then sign in to the newly activated admin account and try installing the software you need from there. Disable the built-in administrator account when you’re done with it.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135363/19272" target="_top" id="2135363">
  <img src="//a.impactradius-go.com/display-ad/19272-2135363" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135363/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Turn Off UAC (User Account Control)

 User Account Control is a security screen that can hinder the installation of programs when set at its highest setting. To ensure UAC isn’t causing any issues with installing software, temporarily turn off User Account Control by selecting its lowest **Never notify** option. You can apply this potential fix by disabling User Account Control with one of the methods in our [guide to turning off UAC](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/).

![The User Account Control Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-uac-settings.jpg)

## 4\. Run or Restart the Windows Installer Service

 Windows Installer is a service that needs to be running for users to install software with MSI packages. So, check that service is enabled and running. Even if it is, restarting that service might also resolve the “system administrator has set policies” error. This is how you can run or restart Windows Installer:

1. To access the file finder tool, right-click **Start** and select the **Search** shortcut.
2. Next, input a **services** search phrase.
3. Click the **Services** app found by the search tool.
4. Double-click **Windows Installer** to see that service’s property settings.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-services-window.jpg)
5. If the service is stopped, click its **Start** button. Or select **Stop** and **Start** to restart Windows Installer.  
![The Windows Installer Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-windows-installer-properties-service-window.jpg)
6. Select **Apply** \> **OK** to save the Windows Installer service settings.
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134489/18498" target="_top" id="2134489">
  <img src="//a.impactradius-go.com/display-ad/18498-2134489" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134489/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<span id="1983553">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983553.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983553">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983553.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983553%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983553/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Change Group Policy Settings

 Lots of users have fixed the “system administrator has set policies” error by setting the Windows Installer policy to never disable Windows Installer. However, you will need to access Local Group Policy Editor, available in the Windows Pro and Enterprise editions, to apply this potential fix. If you can utilize that tool, change the **Turn Off Windows Installer** policy like this:

1. Press **Win + R**, input the **gpedit.msc** command, and click **OK** to [openLocal Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).
2. Double-click on **Computer Configuration** and **Administrative Templates** inside Group Policy’s left sidebar.
3. Then go to **Windows Components** \> **Windows Installer** to access policy settings.
4. Double-click the **Turn off Windows Installer** policy setting.  
![The Turn off Windows Installer policy setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-installer-policy-settings.jpg)
5. Select **Enabled** if that option isn’t already set.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130875/7443" target="_top" id="2130875">
  <img src="//a.impactradius-go.com/display-ad/7443-2130875" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130875/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Then click **Never** on the **Disable Windows Installer** drop-down menu.  
![The Never option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-never-option.jpg)
7. Select the policy window’s **Apply** and **OK** options.

 On top of that, delete software restriction policies. These are the steps for deleting software restriction policies:

1. Double-click **Windows Settings** \> **Security Settings** in Group Policy’s sidebar.
2. Right-click **Software Restriction Policies** and select **Delete Software Restriction Policies** if that option is available.  
![delete-software-restriction-policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/delete-software-restriction-policies.jpg)
3. Click **Yes** to confirm the deletion of software restriction policies.

 Some users also say they went even further and created a new software restriction policy in Group Policy Editor to resolve the “system administrator has set policies” error. You can try doing that after selecting to delete software restriction policies. Create a new software restriction policy like this:

1. Click **Software Restriction Policies** with the right mouse button to select **New Software Restriction Policies**.  
![The New Software Restriction Policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/new-software-restriction-policies.jpg)
2. Double-click on **Enforcement**.  
![The Software Restriction Policies object types](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-enforcement-option.jpg)
3. Select the **All users except local administrators** radio button.  
![The Enforcement Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-enforcement-properties-window.jpg)
4. Click the Enforcement Properties window’s **Apply** and **OK** options.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115933/19272" target="_top" id="2115933">
  <img src="//a.impactradius-go.com/display-ad/19272-2115933" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115933/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. [Run Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/#:~:text=Press%20the%20Win%20%2B%20R%20on,Command%20Prompt%20with%20administrative%20privileges.) via the search utility.
6. Enter and execute this command for updating the policy:  
`gpupdate /force`
7. Exit the Command Prompt app and restart Windows.

<!-- affiliate ads begin -->
<span id="1977020">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977020.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977020">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977020.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977020%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977020/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Edit the Installer Registry Key

 Editing an **Installer** registry key is a widely confirmed fix for the “system administrator has set policies” error. This registry tweak involves setting a **DisableMSI** DWORD value. You may also need to create a new **Installer** key from scratch if it’s not already there. These are the steps for applying this registry solution:

1. Click on the taskbar magnifying glass or Search box.
2. Type in a **regedit** search term to locate the Registry Editor app.
3. Select **Registry Editor** to start that app.
4. Input this path inside the Registry Editor address bar:  
`HKEY_LOCAL_MACHINE\Software\Policies\Microsoft\Windows\`
5. If you can’t see an **Installer** subkey, right-click the **Windows** key and select **New** \> **Key**. Users who can select an existing **Installer** subkey within the **Windows** key can skip through to step seven.  
![The New > Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-new-key-options.jpg)

1. Enter **Installer** for the new key’s name.
2. Right-click the **Installer** key and select **New** \> **DWORD (32-bit) Value**.
3. Enter **DisableMSI** to be the title of the new DWORD.  
![the-disable-msi-dword](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-disable-msi-dword.jpg)
4. Double-click **DisableMSI** inside the **Installer** key.
5. Make sure the **DisableMSI** value is set to **0**.  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-edit-dword-window.jpg)
6. Select **OK** to set the **DisableMSI** value.
<!-- affiliate ads begin -->
<span id="1993645">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993645.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993645">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993645.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993645%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993645/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Close Registry Editor and restart your PC.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123739/7443" target="_top" id="2123739">
  <img src="//a.impactradius-go.com/display-ad/7443-2123739" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123739/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get Your Windows Software Installed

 The “system administrator has set policies” error is an old Windows issue many users have fixed with the troubleshooting methods covered in this guide. So, those are tried and tested resolutions that will likely fix the “system administrator has set policies” error on your PC. Then you can get all the Windows 10 and 11 software you need installed.

 Users cannot install whatever programs for which that system administrator error arises. The error message suggests this issue is due to some kind of enforced admin settings. You can fix the “system administrator has set policies” error by applying the resolutions below.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-ppt-presentations-merging-audio-and-imagery-fluently/"><u>[New] 2024 Approved PPT Presentations Merging Audio & Imagery Fluently</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-nailing-the-technique-for-snapchat-screen-time-lapses/"><u>[Updated] In 2024, Nailing the Technique for Snapchat Screen Time-Lapses</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-ultimate-haul-video-guide-from-camera-to-final-cut/"><u>[Updated] The Ultimate Haul Video Guide From Camera to Final Cut</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-straightforward-approach-turn-video-upside-down-with-vlc/"><u>2024 Approved Straightforward Approach Turn Video Upside Down with VLC</u></a></li>
<li><a href="https://buynow-info.techidaily.com/2024s-finest-body-cams-authorized-law-enforcement-equipment/"><u>2024'S Finest Body Cams - Authorized Law Enforcement Equipment</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-invalid-input-alerts-on-your-visual-interface-device/"><u>Dealing with Invalid Input Alerts on Your Visual Interface Device</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/discover-the-best-dolby-atmos-movie-titles-for-a-cinematic-adventure-right-in-your-living-room-top-15-picks/"><u>Discover the Best Dolby Atmos Movie Titles for a Cinematic Adventure Right in Your Living Room (Top 15 Picks)</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/displaying-your-pc-desktop-on-tv-screens-via-google-cast-an-in-depth-tutorial/"><u>Displaying Your PC Desktop On TV Screens Via Google Cast - An In-Depth Tutorial</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-and-update-the-corsair-k55-keyboard-drivers-easy-guide/"><u>Download & Update the Corsair K55 Keyboard Drivers - Easy Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-adjusting-low-power-modes-in-windows/"><u>Essential Tips: Adjusting Low-Power Modes in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-the-notorious-0xc00d36b4-windows-sound-issue/"><u>Fixing the Notorious 0XC00D36B4 Windows Sound Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/harness-the-power-of-folder-and-file-unification-in-windows-11/"><u>Harness the Power of Folder & File Unification in Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-my-apple-iphone-7-plus-location-is-wrong-drfone-by-drfone-virtual-ios/"><u>How to Fix My Apple iPhone 7 Plus Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-your-browser-is-managed-by-your-organization-on-chrome-and-edge-for-windows/"><u>How to Fix Your Browser Is Managed by Your Organization on Chrome and Edge for Windows</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-life360-on-windows-pc-for-tecno-spark-10-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Use Life360 on Windows PC For Tecno Spark 10 5G? | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-optimizing-igtv-videos-editing-strategies/"><u>In 2024, Optimizing IGTV Videos Editing Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/insider-tips-for-manual-windows-security-scanning/"><u>Insider Tips for Manual Windows Security Scanning</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-downloads-weighing-choco-against-wm/"><u>Mastering Windows Downloads: Weighing Choco Against WM</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-machine-identification-in-under-150-characters/"><u>Mastering Windows Machine Identification in Under 150 Characters</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-delete-temp-files-easily/"><u>Mastering Windows: Delete Temp Files Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/optimal-6-tracking-applications-to-enhance-pc-productivity/"><u>Optimal 6 Tracking Applications to Enhance PC Productivity</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-0x80246007-update-obstacle-on-windows-1011/"><u>Overcoming 0X80246007 Update Obstacle on Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-services-woes-a-guide-to-fixing-the-non-operational-tool/"><u>Overcoming Windows Services Woes: A Guide to Fixing the Non-Operational Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/perfecting-battery-status-alerts-windows-edition/"><u>Perfecting Battery Status Alerts: Windows Edition</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reasons-for-infinix-note-30-pro-stuck-on-startup-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Infinix Note 30 Pro Stuck on Startup Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/recovering-lost-access-to-windows-command-center/"><u>Recovering Lost Access to Windows Command Center</u></a></li>
<li><a href="https://windows11.techidaily.com/removing-aw-snap-from-your-chrome-browser-on-windows/"><u>Removing “Aw, Snap!” From Your Chrome Browser on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/reverse-webp-images-in-chrome-for-windows-users/"><u>Reverse WebP Images in Chrome for Windows Users</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/review-mophie-ac-powerstation-is-it-worth-its-high-cost/"><u>Review: Mophie AC Powerstation - Is It Worth Its High Cost?</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-deadlocked-files-on-windows-11-a-guide-1/"><u>Reviving Deadlocked Files on Windows 11: A Guide (1)</u></a></li>
<li><a href="https://windows11.techidaily.com/simple-steps-reactivating-and-customizing-the-old-photo-viewer-in-win11/"><u>Simple Steps: Reactivating and Customizing the Old Photo Viewer in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-the-windows-search-interface-no-graphics/"><u>Simplifying the Windows Search Interface: No Graphics</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-freezes-aps-for-pcs/"><u>Taming Freezes: APS for PCs</u></a></li>
<li><a href="https://technical-tips.techidaily.com/troubleshooting-tips-solving-wii-cant-read-disc-issues/"><u>Troubleshooting Tips: Solving 'Wii Can't Read Disc' Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-resolving-stranded-on-xbox-app-in-windows-devices/"><u>Troubleshooting: Resolving 'Stranded' On Xbox App in Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/unclutter-your-windows-desktop-space/"><u>Unclutter Your Windows Desktop Space</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-ftdibussys-the-enigma-of-memory-standards-violation/"><u>Unveiling ftdibus.sys: The Enigma of Memory Standards Violation</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secrets-of-microsoft-family-safety/"><u>Unveiling the Secrets of Microsoft Family Safety</u></a></li>
<li><a href="https://windows11.techidaily.com/update-mail-and-calendars-style-them-with-fav-photos/"><u>Update Mail & Calendars: Style Them with Fav Photos</u></a></li>
<li><a href="https://windows11.techidaily.com/websites-as-apps-step-by-step-windows-installation/"><u>Websites as Apps: Step-by-Step Windows Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/why-your-wi-fi-mouse-isnt-working-quick-fixes-for-windows/"><u>Why Your Wi-Fi Mouse Isn't Working? Quick Fixes for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/winvolume-fix-resetting-saving-settings-for-audio/"><u>WinVolume Fix: Resetting Saving Settings for Audio</u></a></li>
<li><a href="https://windows11.techidaily.com/your-route-to-a-maps-integrated-windows-experience/"><u>Your Route to a Maps-Integrated Windows Experience</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>