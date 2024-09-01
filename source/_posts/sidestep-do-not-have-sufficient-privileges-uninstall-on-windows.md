---
title: "Sidestep 'Do Not Have Sufficient Privileges': Uninstall on Windows"
date: 2024-08-31T22:17:32.053Z
updated: 2024-09-01T22:17:32.053Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Sidestep 'Do Not Have Sufficient Privileges': Uninstall on Windows"
excerpt: "This Article Describes Sidestep 'Do Not Have Sufficient Privileges': Uninstall on Windows"
keywords: Sidestep DNP Error,Uninstall Windows Guide,Fix Privilege Issue,Remove Without Rights,Bypass DNP Message,Fix Uninstall Failure,Access Control Removal
thumbnail: https://thmb.techidaily.com/934c09a684ad314c00e00ed21a2e7539ae4858551b2266da80c837988bee503d.jpg
---

## Sidestep 'Do Not Have Sufficient Privileges': Uninstall on Windows

 Some users have reported an uninstall issue on Microsoft’s forum with an error message that says, “You do not have sufficient access to uninstall.” That error message pops up when users try to uninstall certain software in Windows 11/10\. As a result, users can’t uninstall whatever software packages that error occurs for.

 That error message highlights the issue is caused by insufficient access. However, the error can arise for users even when they have administrator privileges. This is how you can fix the “do not have sufficient access to uninstall” error in Windows 11/10\.

## 1\. Enable the Windows Admin Account

 First, make sure you’re utilizing an admin account. You can [activate a built-in Windows admin account](https://www.makeuseof.com/windows-11-enable-disable-built-in-administrator-account/) via the Command Prompt. Then log in to that built-in admin account and try uninstalling the software from there.

 Alternatively, you can switch a current standard user account to an admin one. Check out this guide to [changing Windows account types](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) for full instructions about how to do so.

## 2\. Run the Affected Software’s Uninstaller File as an Administrator

 Also, run the software’s uninstaller file as an administrator. The software’s installation directory will include its uninstaller file. Right-click that file to select a **Run as administrator** context menu option.

![The Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-as-administrator-option5.jpg)

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1896607/21553" target="_top" id="1896607"><img src="//a.impactradius-go.com/display-ad/21553-1896607" border="0" alt="" width="750" height="422"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1896607/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Troubleshoot With the Program Install and Uninstall Troubleshooter

 Windows doesn’t include any troubleshooter for fixing uninstallation issues. However, there is a Microsoft Program Install and Uninstall troubleshooter that might be useful for fixing the “You do not have sufficient access to uninstall” error. This is how you can run the Program Install and Uninstall troubleshooter:

1. Bring up the troubleshooter's [Microsoft download page](https://support.microsoft.com/en-us/topic/fix-problems-that-block-programs-from-being-installed-or-removed-cca7d1b6-65a9-3d98-426b-e9f927e1eb4d).
2. Then click on the **Download** troubleshooter button.
3. Double-click on the **MicrosoftProgram\_Install\_and\_Uninstall.meta.diagcab** troubleshooter file.  
![The Program Install and Uninstall troubleshooter window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/program-install-and-uninstall-troubleshooter.jpg)
4. Click on **Next** \> **Uninstalling** to bring up a program list.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
![The Uninstalling option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/uninstalling-option.jpg)
5. Then select the program you can’t uninstall and select **Next**.  
![The Program Install and Uninstall troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/program-list.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
## 4\. Turn Off User Account Control

 The “You do not have sufficient access to uninstall” error can sometimes arise because User Account Control is set to high. So, try temporarily turning UAC off before uninstalling the affected software. Our guide on [disabling User Account Control](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) tells you how to turn off UAC.

![The User Account Control settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/user-account-control.jpg)

## 5\. Set Full Control Permissions for the Software’s Installation Folder

 You might need to fix this error because the full user control permission setting isn’t set for the software installation’s folder. So, check the control permission settings for the software installation folder. This is how you can set full control permission for a folder:

1. Open the folder that contains the installation directory of the affected software.
2. Right-click on the installation folder and select **Properties**.  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/properties-option3.jpg)
3. Click **Edit** on the **Security** tab.
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
4. Select your user account name.
5. Click the **Full control** checkbox to select that setting if it’s not already.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/full-control-window.jpg)
6. Then select **Apply** \> **OK** on the folder’s permissions window.
7. Select **OK** to exit the properties window.
8. Repeat the above instructions for the program’s EXE (application) file.

## 6\. Uninstall the Software With an UninstallString Value

 Some users have resolved this error by uninstalling the affected software packages with their UninstallString values. You can do that by copying and pasting the UninstallString value for a program from the registry into the Command Prompt. These are the steps for uninstalling software with an UninstallString value:

1. Open Windows Search with **Win + S**.
2. Type in **regedit** to find the Registry Editor.
3. Select Registry Editor to launch that app.
4. Next, input this location into Registry Editor’s address bar:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Wow6432Node\Microsoft\Windows\CurrentVersion\Uninstall`
5. Click on the subkeys in the **Uninstall** key to view the **DisplayName** strings for them.

1. Select the key for the software you can’t install by identifying it with the **DisplayName** string.  
![DisplayName string](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/display-name.jpg)
2. Double-click on the key's **UninstallString** string.
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->
3. Copy the text in the **Value data** box by selecting it and pressing **Ctrl** \+ **C**.  
![The Edit String window for the UninstallString](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/edit-string-window3.jpg)
4. Open Command Prompt as an admin (See [how to open Command Prompt with admin permissions](https://www.makeuseof.com/windows-run-command-prompt-admin/)).
<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Click inside the Command Prompt and press **Ctrl** \+ **V** to paste in the string.  
![An uninstall command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/undostring-command.jpg)
6. Press **Enter** to run the command and remove the software.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
<!-- affiliate ads end -->

 Note that the above registry string is for 64-bit software. To find the strings for 32-bit software, you’ll need to go to this registry path:

`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Uninstall`

## 7\. Try Uninstalling the Software With a Third-Party Uninstaller Tool

 Third-party uninstaller tools have helped some users fix the “do not have sufficient access to uninstall” error. The [best third-party uninstaller tools](https://www.makeuseof.com/windows-11-uninstallers-stubborn-apps/) are superior to Windows’ Programs and Features applet for removing software. So, try uninstalling the software with a freely available utility like Revo Uninstaller, IObit Uninstaller, or Advanced Uninstaller Pro. This is how you can do that with IObit Uninstaller:

1. Open this [IObit Uninstaller](https://www.iobit.com/en/advanceduninstaller.php) download page.
2. Select **Free Download** to save IObit Uninstaller’s setup wizard within a folder.
3. Bring up the directory containing the **iobituninstaller.exe** file.
4. Double-click the **iobituninstaller.exe** file and click **Install** in the setup wizard.
5. Open IObit Uninstaller and select the **All programs** tab.  
![The IObit Uninstaller software](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-iobit-uninstaller-software.jpg)
6. Select the program and click **Uninstall**.
7. Click on the checkbox labeled **Automatically remove residual files**.
8. Select **Uninstall** to remove the software.  
![The Uninstall button in IObit Uninstaller](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-uninstall-button.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 8\. Uninstall the Software Within Safe Mode

 Safe mode is Windows troubleshooting mode in which only essential drivers and services run. Uninstalling affected software in that mode might work since it will disable things like UAC that can interfere with the uninstallation process. This guide about [entering Windows safe mode](https://www.makeuseof.com/windows-11-boot-safe-mode/) covers the different ways you can enter that mode.

 However, the safe mode also disables Windows Installer (MSI). So, you’ll need to tweak the registry to prevent the disabling of Windows Installer before entering safe mode. Edit the registry as follows:

1. Start the Registry Editor as covered in steps one to three of the sixth potential solution.
2. Then input the following registry key address:  
`HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\Control\SafeBoot\Minimal`
3. Click the **Minimal** key with your right mouse button and select **New**.
4. Select **Key** and input **MSIServer** within the text box. If that key already exists, then you need not set up a new key.  
![The New > Key option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-key-option.jpg)
5. Next, select the **MSIServer** key and double-click its **(Default)** string.
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
6. Enter **Service** in the **Value data** box and select **OK**.  
![The Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/edit-string-window4.jpg)
7. Then enter safe mode and try uninstalling the affected software.

<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Uninstall the Software You Need to Remove on Windows

 Although not guaranteed, there’s a pretty good chance one of the resolutions in this guide will resolve the “do not have sufficient access to uninstall” error on your PC. If not, consider troubleshooting the issue with a third-party PC repair tool.

 A more drastic troubleshooting method, like resetting Windows 11/10 or performing an in-place upgrade, might be required to fix system file and registry issues.

 That error message highlights the issue is caused by insufficient access. However, the error can arise for users even when they have administrator privileges. This is how you can fix the “do not have sufficient access to uninstall” error in Windows 11/10\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-epic-moments-in-gameplay-with-casters/"><u>[New] 2024 Approved  Epic Moments in Gameplay with Casters</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-epic-webcam-connectivity-quests/"><u>[New] In 2024, Epic Webcam Connectivity Quests</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-pioneering-your-path-in-youtube-livestreams-on-mobiles/"><u>[New] Pioneering Your Path in YouTube Livestreams on Mobiles</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-ff-insider-capture-features/"><u>[Updated] 2024 Approved  FF Insider Capture Features</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-enhancing-social-media-reach-a-deep-dive-into-instagram-and-obs-streaming-for-2024/"><u>[Updated] Enhancing Social Media Reach  A Deep Dive Into Instagram & OBS Streaming for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-step-by-step-guide-to-reverse-image-searching-on-instagram-for-2024/"><u>[Updated] Step-by-Step Guide to Reverse Image Searching on Instagram for 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-budget-friendly-filmmaking-choose-the-best-6-action-cameras/"><u>2024 Approved  Budget-Friendly Filmmaking  Choose the Best 6 Action Cameras</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-deciding-the-top-iphone-video-editor-cameo-or-filmorago/"><u>2024 Approved  Deciding the Top iPhone Video Editor  Cameo or FilmoraGo?</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/create-effective-youtube-advertisements-on-a-budget-for-2024/"><u>Create Effective YouTube Advertisements on a Budget for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/exploring-javas-game-world-what-catches-our-eye/"><u>Exploring Java's Game World: What Catches Our Eye</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-taskbar-upgrades-in-windows-11/"><u>Exploring Taskbar Upgrades in Windows 11</u></a></li>
<li><a href="https://win-blog.techidaily.com/fixing-cod-vanguard-pc-issues-bugs-and-stalling-gameplay-during-launch-2024-insights/"><u>Fixing COD Vanguard PC Issues: Bugs and Stalling Gameplay During Launch - 2024 Insights</u></a></li>
<li><a href="https://windows11.techidaily.com/future-proofing-windows-how-to-leverage-vivetool-advantages/"><u>Future-Proofing Windows: How to Leverage ViVeTool Advantages</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-modify-the-visual-cues-in-windows-11-search/"><u>How to Modify the Visual Cues in Windows 11 Search</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-prevent-and-cure-system-settings-failures-in-win11/"><u>How to Prevent and Cure System Settings Failures in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-rectify-shaky-cursor-on-modern-windows/"><u>How to Rectify Shaky Cursor on Modern Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-resurrect-a-freeze-fixing-error-code-x-in-windows-11/"><u>How to Resurrect a Freeze: Fixing Error Code X in Windows 11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-streamline-your-screen-time-step-by-step-towards-a-well-curated-playlist/"><u>In 2024, Streamline Your Screen Time  Step-by-Step Towards a Well-Curated Playlist</u></a></li>
<li><a href="https://windows11.techidaily.com/insider-secrets-the-edge-of-windows-for-gamers/"><u>Insider Secrets: The Edge of Windows for Gamers</u></a></li>
<li><a href="https://windows11.techidaily.com/insights-on-windows-portable-application-formats/"><u>Insights on Windows Portable Application Formats</u></a></li>
<li><a href="https://windows11.techidaily.com/keeping-taskmanager-above-all-windows/"><u>Keeping TaskManager Above All Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-charging-notifications-in-modern-windows-os/"><u>Leveraging Charging Notifications in Modern Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/masterclass-guide-to-overcoming-opengl-glitch-3/"><u>Masterclass Guide to Overcoming OpenGL Glitch #3</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-nat-type-adjustment-in-modern-windows-oses/"><u>Mastering NAT Type Adjustment in Modern Windows OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-system-debugging-locating-and-resolving-error-codes-via-windows-command-prompt/"><u>Mastering System Debugging: Locating & Resolving Error Codes via Windows Command Prompt</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/mastering-the-art-of-croatian-conversation-travels-must-have-skillset/"><u>Mastering the Art of Croatian Conversation: Travel's Must-Have Skillset</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-fixing-install-failed-on-windows-1011/"><u>Mastering the Art of Fixing Install Failed on Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11-keys-best-offers/"><u>Mastering Windows 11 Keys: Best Offers</u></a></li>
<li><a href="https://windows11.techidaily.com/methodology-purging-onedrive-icon-in-file-explorer/"><u>Methodology: Purging OneDrive Icon in File Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-windows-arp-cache-world-and-purge-processes-129-chars-exceeds-limit-adjusted-to-fit-better-clearing-windows-arp/"><u>Navigating the Windows ARP Cache World and Purge Processes (129 Chars, Exceeds Limit, Adjusted to Fit Better: Clearing Windows ARP</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-errors-fixing-the-termination-denial/"><u>Navigating Windows Errors - Fixing the Termination Denial</u></a></li>
<li><a href="https://windows11.techidaily.com/preserving-your-preferred-windows-volume-mixer-state/"><u>Preserving Your Preferred Windows Volume Mixer State</u></a></li>
<li><a href="https://windows11.techidaily.com/reigniting-your-wifi-detection-capabilities-in-win11/"><u>Reigniting Your Wifi Detection Capabilities in Win11</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/rev-up-your-recruiting-strategy-with-hot-tapes-for-2024/"><u>Rev Up Your Recruiting Strategy with Hot Tapes for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/revive-your-pc-navigating-through-windows-8-options/"><u>Revive Your PC: Navigating Through Windows' 8 Options</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-overcoming-steam-permissions-in-windows-11/"><u>Solutions for Overcoming Steam Permissions in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-for-removing-isdonedll-from-w11-pc/"><u>Step-By-Step Guide for Removing ISDone.dll From W11 PC</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-keeping-calculator-visible-at-top/"><u>Strategies for Keeping Calculator Visible at Top</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-knowledge-of-command-line-nicknames/"><u>The Essential Knowledge of Command Line Nicknames</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-access-control-corruption-resolution/"><u>Troubleshooting Windows: Access Control Corruption Resolution</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/ultimate-camera-verdict-wxf991s-4k/"><u>Ultimate Camera Verdict: WXF991's 4K</u></a></li>
<li><a href="https://windows11.techidaily.com/unchaining-the-microsoft-store-on-windows-11-devices/"><u>Unchaining the Microsoft Store on Windows 11 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-windows-arp-caches-deletion-guide/"><u>Understanding Windows ARP Caches: Deletion Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-cause-of-winmedia-error/"><u>Unveiling the Cause of WinMedia Error</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>