---
title: "Demystifying the Incompatible GPU Mystery: Wins11 & Win10 Edition"
date: 2024-07-11T21:51:45.484Z
updated: 2024-07-12T21:51:45.484Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Demystifying the Incompatible GPU Mystery: Wins11 & Win10 Edition"
excerpt: "This Article Describes Demystifying the Incompatible GPU Mystery: Wins11 & Win10 Edition"
keywords: Win10/Win11 GPU,Wins11 GPU Guide,Incompatibility in GPUs,Win11 GPU Support,GPU Upgrade Tips,Cross-Version GPUs,GPU Performance Windows
thumbnail: https://thmb.techidaily.com/76bc2de184e61e693dbac8bc5f62288cf6610a7d170abd91534f7a21873e1f18.png
---

## Demystifying the Incompatible GPU Mystery: Wins11 & Win10 Edition

 The “D3D11-compatible GPU” error is a common game-related error for both Windows 10 and 11\. You usually see this error message when you try to start certain affected games. It will present an error message that reads “a D3D11-compatible GPU (feature level 11, shader model-5) is required to run the engine," and affected games don’t start.

 This error has been more widely reported for Fortnite but also occurs for other Windows game titles. If you're struggling with this same issue, here is how you can fix the “D3D11-compatible GPU” error in Windows 10 and 11\.

## 1\. Install Any Available Windows Updates

 When you update Windows, your computer will also update DirectX This is important, as DirectX is a gaming and multimedia API. The “D3D11-compatible GPU” error message references Direct3D 11, a part of DirectX. As the “D3D11-compatible GPU” error is linked with DirectX, it’s recommended that you install all available Windows updates and see if that solves the error.

 Here is how you can check for and install updates in Windows:

1. Click **Start** with the mouse’s right button to select Search.
2. Input the keyword **updates** in the search tool.
3. Select the **Check for updates** search result to open Settings.  
![The Check for updates button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/check-for-updates-button-1.jpg)
4. Click the **Windows Update** tab’s **Check for updates** option. Selecting that option will automatically download and install available patch updates in Windows.
5. Select **Restart now** if the Windows Update tab presents that option to you.

 If you see any optional updates listed there, click their **Download and install** buttons. That includes the current Windows 11, version 22H2 update, or any other new build version, which you should select to upgrade to if available.

## 2\. Scan Your System Files With SFC

 To check for possible system file corruption causing the “D3D11-compatible GPU” error, run a System File Checker (SFC) scan. The SFC tool will scan for and repair corrupted system files in Windows. You can run an SFC scan like this:

1. Open Windows Search (see [how to find Windows Search](https://www.makeuseof.com/windows-search-use-guide/) if you need help opening it) and type **cmd** into it.
2. Right-click **Command Prompt** in the search results and select **Run as administrator**.
3. Run the SFC scan by typing in and executing this command:  
`sfc /scannow`  
![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/sfc-scannow-command-1.jpg)
4. Wait for the System File Checker to finish its scanning and show an outcome message.

## 3\. Set the Game to Utilize a Dedicated Graphics Card

 Does your PC have integrated and discrete (dedicated) graphics adapters? If it does, make sure the affected game is utilizing your PC’s dedicated GPU. To do so, you can select a **High-performance** graphics option for the game via Settings. Our [guide to choosing a preferred graphics card](https://www.makeuseof.com/windows-10-choose-preferred-gpu/) for an app tells you how to set a dedicated GPU for a game in Settings.

![The High performance radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/high-performance-radio-button.jpg)

 Or you could select to disable your PC’s integrated GPU instead. That will ensure all your games utilize the PC’s superior dedicated graphics adapter. You can disable the integrated GPU like this:

1. Open Device Manager, which you can access by pressing the **Windows** key + **X** and clicking on that utility’s shortcut.
2. Double-click on the **Display adapters** category to view graphics adapters.  
![The Disable device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-device-option.jpg)
3. Click on your PC’s integrated graphics adapter to select **Disable**.
4. Select **Yes** on the dialog box that asks you to provide additional confirmation.

## 4\. Update the Driver for Your Graphics Card

 Sometimes, updating your graphical processing unit (GPU) drivers fixes the “D3D11-compatible GPU” error. If your graphics card’s driver is outdated, updating it could be the solution.

 We recommend users manually download and install the latest drivers for their graphics cards from the NVIDIA, Intel, or AMD websites. Our guide on [how to update graphics drivers on Windows](https://www.makeuseof.com/update-graphics-drivers-in-windows-10/) has more info on the topic if you need help.

## 5\. Repair or Update Visual C++ Redistributables on Your PC

 The “D3D11-compatible GPU” error can sometimes be due to missing or corrupted Microsoft Visual C++ Redistributable runtime libraries. So, you may need to repair or install a runtime library on your PC.

 Here is how you can select to repair Visual C++ Redistributables via Apps & Features:

1. Open the **Apps & Features** Settings tab using one of the methods outlined in [how to open the Apps & features tool on Windows](https://www.makeuseof.com/9-ways-to-open-the-apps-features-tool-in-windows-11/).
2. Type **Microsoft Visual C++** in the search box at the top of Apps & features.
3. Then click the three-dot menu button for a Microsoft Visual C++ Redistributable to repair there.
4. Select the **Modify** option.  
![The Modify option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-modify-option-1.jpg)
5. Press the **Repair** button in the Visual C++ window that opens.  
![The Repair button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-repair-option-1.jpg)
6. Repeat the previous two steps for all Microsoft Visual C++ Redistributables listed in Apps & features.

 Or you may need to install some missing Visual C++ Redistributables libraries. You can install the latest runtime libraries with the Microsoft Visual C++ 2015-2022 Redistributable pack like this:

1. Navigate to Microsoft’s [Visual C++ Redistributable](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170) download page.
2. Click the X64 download link for Visual Studio 2015-2022.  
![The X64 download link for Visual Studio 2015-2022](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-x64-download-link-1.jpg)
3. Your browser will likely include a tab or menu that shows downloaded files. Open that **Downloads** tab, which has a **Ctrl** + **J** hotkey in the Firefox, Opera, Edge, and Chrome browsers.  
![The Downloads tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-downloads-tab-1.jpg)
4. Then click **VC\_redist.x64.exe** to bring up the window shown below.  
![The Microsoft Visual C++ 2022 window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/microsoft-visual-C-window-1.jpg)
5. If your PC is missing some runtime libraries, the Microsoft Visual C++ 2015-2022 Redistributable window will have an **Install** option. Click that **Install** button.
6. Select the **Restart now** option after updating libraries.

## 6\. Install the DirectX Runtime Libraries

 The DirectX End-User Runtime Web Installer has helped some users resolve the “D3D11-compatible GPU” error. That installer replaces missing or corrupted DirectX files. These are the steps for installing runtime libraries with the DirectX End-User Runtime Web Installer:

1. Open Microsoft’s [DirectX End-User Runtime Web Installer](https://www.microsoft.com/en-gb/download/details.aspx?id=35) download webpage.
2. Select that page’s **Download** option.
3. Next, click the dxwebsetup.exe file in the download section of your browser.
4. Select the radio button for the **I accept the agreement** option inside the DirectX setup wizard.  
![The DirectX setup wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/directx-setup-wizard-1.jpg)
5. Click **Next** to view the Bing Bar offer.
6. If you don’t want the extra software, uncheck the selected **Install the Bing Bar** option.
7. Press the DirectX Setup wizard’s **Next** button.
8. Click **Finish** in the wizard.
9. Restart your Windows laptop or desktop.

## 7\. Set Affected Games to Run With DirectX 11

 If you can, try setting an affected game to run with DirectX 11 instead of DX12\. Of course, you won’t be able to do that though the game’s settings screen if it doesn’t start in the first place.

 However, you can set games to run with DirectX 11 with command line arguments in Epic Games and Steam. This is how to set an affected game to run with DirectX 11 in Epic Games and Steam:

### How to Force DirectX 11 on Epic Games

 For any titles on Epic Games:

1. Bring up Epic Games Launcher’s window.
2. Click the user account button near the top-right corner of the Epic Games Launcher window.
3. Select the **Settings** menu option.  
![The Settings option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-settings-option-1.jpg)
4. Click an affected game’s title to expand options for it.
5. Then select the game’s **Additional Command Line Arguments** checkbox.  
![The Additional Command Line Arguments checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/additonal-command-line-arguments-box-1.jpg)
6. Input **d3d11** in the text box for the command line argument.

### How to Force DirectX 11 on Steam

 Likewise, if you're a fan of Steam:

1. Bring up the Steam client software.
2. Select **Library** along the top of Steam’s window.
3. Right-click whatever game the “D3D11-compatible GPU” occurs for and select **Properties**.
4. Input **\-dx11** in the launch option text box on the **General** tab.  
![Steam Launch Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/steam-launch-options.jpg)

## 8\. Expand the Page File for More Virtual Memory

 Expanding the page file will increase the amount of virtual memory available for games. That’s a recommended troubleshooting method for the “D3D11-compatible GPU” error since your PC can better handle system demands for graphically intensive games with a larger page file. Check out our [guide to extending virtual memory in Windows](https://www.makeuseof.com/tag/virtual-memory-low-heres-fix/) to apply this potential fix.

![The Virtual Memory window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/virtual-memory-window.jpg)

## Enjoy Your Windows Games Again

 Many players have resolved the “D3D11-compatible GPU” error with the resolutions outlined in this guide. So, there’s a good likelihood that one of them will also get that issue sorted for your Windows 11/10 games. However, some players with PCs that have old GPUs might need to upgrade their graphics cards to fix the “D3D11-compatible GPU” issue.

 The “D3D11-compatible GPU” error is a common game-related error for both Windows 10 and 11\. You usually see this error message when you try to start certain affected games. It will present an error message that reads “a D3D11-compatible GPU (feature level 11, shader model-5) is required to run the engine," and affected games don’t start.

 This error has been more widely reported for Fortnite but also occurs for other Windows game titles. If you're struggling with this same issue, here is how you can fix the “D3D11-compatible GPU” error in Windows 10 and 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-captureconqueror-a-comprehensive-guide-to-screen-recording/"><u>[New] 2024 Approved  CaptureConqueror  A Comprehensive Guide to Screen Recording</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-high-dynamic-range-mastered-for-the-modern-user/"><u>Windows 11'S High Dynamic Range Mastered for the Modern User</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-in-2024-top-ringtones-for-game-of-thrones-enthusiasts-online-listings/"><u>[New] In 2024, Top Ringtones for Game of Thrones Enthusiasts - Online Listings</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-lost-data-from-lava-blaze-2-pro-by-fonelab-android-recover-data/"><u>Recover lost data from Lava Blaze 2 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-data-disaster-save-and-recover-snippets/"><u>Avoiding Data Disaster: Save & Recover Snippets</u></a></li>
<li><a href="https://windows11.techidaily.com/why-your-wallet-may-regret-inexpensive-windows-keys/"><u>Why Your Wallet May Regret Inexpensive Windows Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-taskmgr-with-command-line-interface-cli-feature/"><u>Enhance TaskMgr with Command Line Interface (CLI) Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/your-window-to-artistry-in-windows-1011/"><u>Your Window to Artistry in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-system-stability-automatic-windows-and-amd-driver-shift/"><u>Elevate System Stability: Automatic Windows & AMD Driver Shift</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-7-excellent-screen-capture-tools/"><u>[New] 2024 Approved  7 Excellent Screen Capture Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/bridging-the-gap-between-wi-fi-and-ethernet-in-windows/"><u>Bridging the Gap Between Wi-Fi and Ethernet in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-winvpn-error-remote-computer-not-reachable/"><u>Quick Guide: WinVPN Error Remote Computer Not Reachable</u></a></li>
<li><a href="https://windows11.techidaily.com/amp-up-your-vehicles-performance-with-these-top-windows-upgraders/"><u>Amp up Your Vehicle's Performance with These Top Windows Upgraders</u></a></li>
<li><a href="https://windows11.techidaily.com/from-standard-to-stylish-personalize-each-window-11-screen/"><u>From Standard to Stylish: Personalize Each Window 11 Screen</u></a></li>
<li><a href="https://games-able.techidaily.com/the-road-ahead-haptic-grip-or-digital-direct-control/"><u>The Road Ahead: Haptic Grip or Digital Direct Control</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-security-a-comprehensive-guide-to-lock-patterns-in-windows-11/"><u>Customizing Security: A Comprehensive Guide to Lock Patterns in Windows 11</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-how-to-make-a-3d-text-effect-in-photoshop/"><u>2024 Approved  How to Make a 3D Text Effect in Photoshop</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-access-the-archived-unique-methods-for-viewing-old-youtube-for-2024/"><u>[New] Access the Archived  Unique Methods for Viewing Old YouTube for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/1719329285690-resolve-programming-discrepancies-with-no-troubleshoot-tool/"><u>Resolve Programming Discrepancies with No Troubleshoot Tool.</u></a></li>
<li><a href="https://windows11.techidaily.com/flushing-dns-on-windows-best-practices/"><u>Flushing DNS on Windows: Best Practices</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-excessive-cpu-load-by-dropbox-app-on-windows-devices/"><u>Addressing Excessive CPU Load by Dropbox App on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/11-ways-to-open-the-credential-manager-on-windows-11/"><u>11 Ways to Open the Credential Manager on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-manage-windows-deletion-prompt-actions/"><u>Efficiently Manage Windows' Deletion Prompt Actions</u></a></li>
<li><a href="https://fake-location.techidaily.com/ultimate-guide-to-free-pptp-vpn-for-beginners-on-lava-blaze-2-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Free PPTP VPN For Beginners On Lava Blaze 2 | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/speedysnap-lingershot-videoclip/"><u>SpeedySnap LingerShot Videoclip</u></a></li>
<li><a href="https://windows11.techidaily.com/a-peek-at-your-gadgets-soul-6-methods-to-discover-its-make/"><u>A Peek at Your Gadget's Soul: 6 Methods to Discover Its Make</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-iphone-photographic-file-import-failures-on-windows-pcs/"><u>Handling iPhone Photographic File Import Failures on Windows PCs</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/ideal-ios-tools-2023s-leading-choices-for-psp-gameplay-for-2024/"><u>Ideal iOS Tools  2023'S Leading Choices for PSP Gameplay for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/the-ultimate-format-selection-elevating-your-youtube-content/"><u>The Ultimate Format Selection – Elevating Your YouTube Content</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-users-through-fixing-nvidias-unreachable-error/"><u>Guiding Users Through Fixing NVIDIA's 'Unreachable' Error</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reactivate-muted-system-sound-output-quickly/"><u>How to Reactivate Muted System Sound Output Quickly</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/why-does-the-pokemon-go-battle-league-not-available-on-oneplus-11r-drfone-by-drfone-virtual-android/"><u>Why does the pokemon go battle league not available On OnePlus 11R | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-looks-like-youre-stranded-xbox-app-error-in-windows-11-and-11/"><u>How to Fix the “Looks Like You’re Stranded” Xbox App Error in Windows 11 & 11</u></a></li>
<li><a href="https://extra-support.techidaily.com/navigating-windows-8-movie-maker-like-a-pro-for-2024/"><u>Navigating Windows 8 Movie Maker Like a Pro for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-capture-and-share-the-world-in-high-definition-with-mi-11s-screenshot-capabilities-for-2024/"><u>[New] Capture and Share the World in High Definition with Mi 11'S Screenshot Capabilities for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-your-messages-after-motorola-moto-g-stylus-5g-2023-has-been-deleted-by-fonelab-android-recover-messages/"><u>Recover your messages after Motorola Moto G Stylus 5G (2023) has been deleted</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/in-2024-how-to-make-animated-text-video-on-computeriphoneandroidonline/"><u>In 2024, How to Make Animated Text Video on Computer/iPhone/Android/Online</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-permission-restrictions-on-windows/"><u>Deciphering Permission Restrictions on Windows</u></a></li>
<li><a href="https://extra-tips.techidaily.com/soundtrack-synergy-inshot-edition/"><u>Soundtrack Synergy  InShot Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-onedrive-login-hiccup-zero-based-code-error-on-win11/"><u>Fixing OneDrive Login Hiccup: Zero-Based Code Error on Win11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-can-i-get-more-stardust-in-pokemon-go-on-samsung-galaxy-f04-drfone-by-drfone-virtual-android/"><u>How can I get more stardust in pokemon go On Samsung Galaxy F04? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-start-the-narrator-in-windows-11/"><u>How to Start the Narrator in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/disregard-met-not-fulfilled-emblem-on-win11/"><u>Disregard Met Not Fulfilled Emblem on Win11</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-best-pokemons-for-pvp-matches-in-pokemon-go-for-apple-iphone-15-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, Best Pokemons for PVP Matches in Pokemon Go For Apple iPhone 15 Plus | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-ultimate-insight-2024-video-showcase-guidebook/"><u>[New] Ultimate Insight  2024 Video Showcase Guidebook</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-overview-of-the-best-honor-100-pro-screen-mirroring-app-drfone-by-drfone-android/"><u>In 2024, Overview of the Best Honor 100 Pro Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/achieving-optimal-security-in-win-11-with-ms-defender-application-guard-for-edge/"><u>Achieving Optimal Security in Win 11 with MS Defender Application Guard for Edge</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-system-resource-usage-details-to-the-windows-system-tray/"><u>How to Add System Resource Usage Details to the Windows System Tray</u></a></li>
<li><a href="https://review-topics.techidaily.com/nokia-c12-pro-support-forgotten-screen-lock-by-drfone-android-unlock-android-unlock/"><u>Nokia C12 Pro support - Forgotten screen lock.</u></a></li>
<li><a href="https://extra-information.techidaily.com/comprehensive-evaluation-the-leading-gopro-cases-1-10/"><u>Comprehensive Evaluation  The Leading GoPro Cases #1-10</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-understanding-and-implementing-slug-line-rules/"><u>[New] Understanding and Implementing Slug Line Rules</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-uninstall-oneself-avoiding-admin-restrictions-in-windows/"><u>How To Uninstall Oneself: Avoiding Admin Restrictions in WINDOWS</u></a></li>
</ul></div>
