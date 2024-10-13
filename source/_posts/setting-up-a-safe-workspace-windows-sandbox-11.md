---
title: "Setting Up a Safe Workspace: Windows Sandbox 11"
date: 2024-10-09T18:10:38.523Z
updated: 2024-10-12T19:04:10.830Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Setting Up a Safe Workspace: Windows Sandbox 11"
excerpt: "This Article Describes Setting Up a Safe Workspace: Windows Sandbox 11"
keywords: Workplace Safety Guide,Secure Computing Space,Virtualized Security,IT Security Basics,Safe Work Environment,Windows Sandbox Setup,OS Sandbox Protection
thumbnail: https://thmb.techidaily.com/c8cc0b50d6a862024b28911d2e2409173d05c3a9fcb60009ede2fce73e839885.jpg
---

## Setting Up a Safe Workspace: Windows Sandbox 11

 Microsoft Windows 11 features multiple virtualization solutions out of the box. While Hyper-V is an excellent tool, Windows Sandbox is an easy alternative to Windows virtual machines. It lets you run untrusted apps in an isolated environment without the hassle of setting up a complete virtualization tool.

 Unfortunately, Windows Sandbox is not available on the Home edition of the OS. If you are running the Pro, Enterprise, and Education edition, here is how to enable and set up Windows Sandbox in Windows 11.

## How to Set Up Windows Sandbox in Windows 11

 Windows Sandbox is an optional feature, which means you'll have to install it from the Optional features section. You can[add and remove optional features from the Windows Features dialog](http://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) . Alternatively, you can use PowerShell or Command Prompt for a swift installation of Windows Sandbox.

 While the setup process is easier, your computer must meet some system requirements. Windows 11 Pro, Education, or Enterprise running computers with virtualization support are Windows Sandbox compatible. In most cases,[if your system can run Windows Hyper-V](https://www.makeuseof.com/windows-11-enable-hyper-v/) , it should also run Windows Sandbox.

<!-- affiliate ads begin -->
<span id="1982485">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982485.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982485">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982485.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982485%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982485/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. Enable Windows Sandbox Using the Windows Features Dialog

 You can install Windows Sandbox using the Windows Features dialog. This dialog houses most of the optional Windows features that are ready to be installed on your PC.

 Follow these steps to install Windows Sandbox using the Windows Features dialog:

1. Press**Win + R** to open**Run** .
2. Type**appwiz.cpl** and click**OK** to open**Control Panel.**
3. In the left panel, click on**Turn Windows features on or off.**  
![control panel turn windows features on or off](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/control-panel-turn-windows-features-on-or-off.jpg)
4. In the**Turn Windows features on or off dialog** , scroll down and locate**Windows Sandbox.**
5. Check the**Windows Sandbox** option and click**OK** .  
![enable Windows sandbox turn windows features on or off](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-Windows-sandbox-turn-windows-features-on-or-off.jpg)
6. Windows will search for the files and install the required dependencies to run Windows Sandbox scenarios. Once the changes are applied, close the Windows features dialog and restart your PC.
7. After the restart, press**Win + S** to open**Windows search.**
8. Type**sandbox** and click on**Windows Sandbox** from the search result to launch the virtualization tool.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2027190/19272" target="_top" id="2027190">
  <img src="//a.impactradius-go.com/display-ad/19272-2027190" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2027190/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Install Windows Sandbox Using PowerShell

![enable windows sandbox powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-windows-sandbox-powershell.jpg)

 You can use the Enable WindowsOptionalFeature command in PowerShell to install Windows Sandbox in Windows. This method is useful if you find the sandbox option greyed out or unable to install it from the Windows Feature dialog.

To install Windows Sandbox using PowerShell:

1. Press**Win + X** to open the**WinX** menu.
2. Click on**Windows Terminal (Admin)** to open the Windows Terminal with administrative privilege. Since PowerShell is assigned as the default profile upon launch, you can execute your PowerShell cmdlets straight away in Windows Terminal.
3. In the Windows Terminal window, copy and paste the following command and press Enter:  
Enable-WindowsOptionalFeature -Online -FeatureName "Containers-DisposableClientVM" -All
4. If no error occurs, Windows will install the required files to enable Windows Sandbox.
5. Once done, press**Y** and hit**Enter** to restart your PC.
6. After the restart, you can launch Windows Sandbox from Windows Search.

## 3\. Install Windows SandBox Using Command Prompt

![enable windows sandbox command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-windows-sandbox-command-prompt.jpg)

 Deployment Image Servicing and Management (DISM) is a command-line utility that facilitates the installation of optional features using the Command Prompt. To install Windows Sandbox, you will need to use the Enable-Feature command in Command Prompt. Here's how to do it.

1. Press**Win + R** to open**Run** .
2. Type**cmd** in the**Run** dialog. Press and hold**Ctrl + Shift** and click**OK** to open Command Prompt as administrator.
3. In the Command Prompt, type the following command and press**Enter** :  
`dism /online /Enable-Feature /FeatureName: "Containers-DisposableClientVM" -All`
4. Wait for the process to complete. Once done, press**Y** and**Enter** to restart your PC.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144273/7443" target="_top" id="2144273">
  <img src="//a.impactradius-go.com/display-ad/7443-2144273" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144273/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Use Windows Sandbox

![Windows Sandbox Open](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Windows-Sandbox-Open.jpg)

 Now that you have Windows Sandbox installed, you can start using it to test untrusted apps in isolation. To launch the app, press**Win + S** to open**Windows Search** and type**Windows Sandbox.** Click on the app from the search result to open it.

 Upon its launch, Windows Sandbox looks like a lightweight version of your Windows machine. You can copy files from your host system or download them from the Internet using the built-in web browser. Any actions you perform in the sandbox will not affect your host system.

 Once the testing is complete, close the Sandbox and click**OK** to confirm the action. Unlike a VM, Sandbox will delete all the data (including apps and files) upon exit. So, you'll get a clean, isolated environment running the same Windows OS build as your host machine each time.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134249/18498" target="_top" id="2134249">
  <img src="//a.impactradius-go.com/display-ad/18498-2134249" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134249/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Set Up and Use Windows Sandbox in Windows 11

 Windows Sandbox provides an excellent way to test apps and files in an isolated environment without the hassle of setting up a virtual machine. While the virtual machines have distinct advantages, Sandbox is lighter, faster, and loads a fresh copy of Windows OS each time it's run.

 Windows 11 Home users, however, have missed out on this excellent feature. But if you must use a sandbox, consider using third-party alternatives such as Sandboxie Plus and SHADE Sandbox. These alternatives offer a similar set of functionalities with no complicated setup involved.

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
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-your-guide-to-stellar-igtv-talent/"><u>2024 Approved Your Guide to Stellar IGTV Talent</u></a></li>
<li><a href="https://location-social.techidaily.com/4-feasible-ways-to-fake-location-on-facebook-for-your-zte-axon-40-lite-drfone-by-drfone-virtual-android/"><u>4 Feasible Ways to Fake Location on Facebook For your ZTE Axon 40 Lite | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/building-better-montages-a-creative-guide/"><u>Building Better Montages A Creative Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-smart-color-settings-in-windows-11-apps/"><u>Enabling Smart Color Settings in Windows 11 Apps</u></a></li>
<li><a href="https://win-able.techidaily.com/expert-solutions-to-address-freezing-problems-while-playing-valheim-on-desktop/"><u>Expert Solutions to Address Freezing Problems While Playing Valheim on Desktop</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/in-2024-airborne-vigils-the-most-durable-drone-fleet/"><u>In 2024, Airborne Vigils The Most Durable Drone Fleet</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-toolwiz-photosapp-overview-a-complete-analysis-and-future-prospects/"><u>In 2024, Toolwiz PhotosApp Overview - A Complete Analysis and Future Prospects</u></a></li>
<li><a href="https://windows11.techidaily.com/keep-your-windows-control-panel-running-smoothly/"><u>Keep Your Windows Control Panel Running Smoothly</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-based-in-game-voice-sync-with-valorant/"><u>Mastering Windows-Based In-Game Voice Sync with Valorant</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-auto-lock-settings-in-windows/"><u>Navigate Auto-Lock Settings in Windows</u></a></li>
<li><a href="https://tech-hub.techidaily.com/navigating-safely-in-the-digital-playground-5-methods-for-child-friendly-chatgpt-use/"><u>Navigating Safely in the Digital Playground: 5 Methods for Child-Friendly ChatGPT Use</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-windows-1111-shop-glitch-x800704cf/"><u>Preventing Windows 11/11 Shop Glitch X800704CF</u></a></li>
<li><a href="https://windows11.techidaily.com/removing-the-rust-of-access-denied-in-windows/"><u>Removing the Rust of 'Access Denied' In Windows</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/seamless-gameplay-instant-cure-for-amd-and-tarkov-hiccup/"><u>Seamless Gameplay: Instant Cure for AMD & Tarkov Hiccup</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-non-attached-usb-device-dilemma-in-virtualbox-environment/"><u>Tackling Non-Attached USB Device Dilemma in VirtualBox Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/take-control-of-your-workflow-learn-these-essential-cmd-commands/"><u>Take Control of Your Workflow: Learn These Essential CMD Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-tab-navigation-windows-11-enhanced-guide/"><u>The Art of Tab Navigation: Windows 11 Enhanced Guide</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/top-5-honor-x50iplus-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 Honor X50i+ Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://change-location.techidaily.com/what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-vivo-y36i-drfone-by-drfone-virtual-android/"><u>What is the best Pokemon for pokemon pvp ranking On Vivo Y36i? | Dr.fone</u></a></li>
</ul></div>

