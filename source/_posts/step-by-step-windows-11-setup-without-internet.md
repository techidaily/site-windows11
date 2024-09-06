---
title: "Step-by-Step: Windows 11 Setup Without Internet"
date: 2024-09-05T02:08:04.037Z
updated: 2024-09-06T02:08:04.037Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Step-by-Step: Windows 11 Setup Without Internet"
excerpt: "This Article Describes Step-by-Step: Windows 11 Setup Without Internet"
keywords: Win11SetupOffline,NoNetWindowsInstall,BootWin11NoInternet,InstallWin11NoLAN,WindowsSetupAirborne,SetupWin11OffWiFi,OnlineFreeWinSetup
thumbnail: https://thmb.techidaily.com/8efb02d1ad78746fe7e04d066e97a30754c0040bd1d393f4b6d528ffbc9df6b1.jpg
---

## Step-by-Step: Windows 11 Setup Without Internet

 Microsoft requires your system to have an active internet connection to complete the Windows 11 setup. It asks you to log into your Microsoft account to download critical updates and new features before you can start using your freshly installed Windows operating system.

 This becomes an issue if you want to use a local user account or don’t have an active internet connection during setup. Luckily, there are a few workarounds to skip the Windows 11 network setup. Here we show you how to bypass this restriction and complete the Windows 11 setup without an internet connection.

## Why Does Windows 11's Setup Require an Internet Connection?

![lets connect you to a network](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/lets-connect-you-to-a-network.png)

 According to Microsoft, you need an active internet connection to perform updates and download and use some features. In addition, Windows 11 Home edition requires a Microsoft Account to complete device setup on first use.

 However, this may not be feasible due to many reasons. First, you may want to use a local user account, but connecting to the Internet will force you to log in with a Microsoft account. The second potential issue is the [missing WiFi drivers to connect to the network](https://www.makeuseof.com/windows-11-missing-wi-fi-option/). Finally, the unavailability of a working Internet connection is another reason you may want to bypass this restriction.

 In Windows 10, bypassing this restriction was easy. You could click on the "I don't have internet" option and proceed to create a local user account and complete the setup.

 Windows 11, however, stops at the "Let’s connect you to a network" screen with the "Next" button grayed out. Windows 11 Pro, Enterprise and Education users can click on "I don’t have internet" and proceed to complete the setup with a local user account; however, Home edition users don't have this option.

 Here are a few workarounds to install Windows 11 Home without an active Internet connection.

## 1\. Bypass Out-of-the-Box-Experience (OOBE) Internet Requirement

 You can bypass the Let’s connect you to a network screen using the OOBE \\BYPASSNRO command in Command Prompt.

 When executed, it runs an existing CMD script, bypassnro.cmd, stored in the System32 folder to modify the Windows registry. This modification allows you to complete the Windows 11 setup without an Internet connection.

 To complete the Windows 11 setup without internet:

1. Make sure your computer is not connected to the Internet.
2. Next, boot your computer with the Windows installation media. Skip to **Step 9** below if you are already on the **Let's connect you to a network** screen.
3. When the **Windows Setup** dialog appears, select your preferred language, time, and keyboard input layout and click **Next**.  
![Windows-11-setup-screen-install-now](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-11-setup-screen-install-now.jpg)
4. Click **Install Now.**  
![Windows 11 setup i dont have product key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-11-setup-i-dont-have-product-key.jpg)
5. Enter your product key. If you don't have a product key, click the **I don't have a product key** link in the bottom right corner. If you are upgrading from Windows 10 and had Windows 11 previously installed, the operating system will automatically recognize and validate the Windows product key linked to your computer hardware.

1. Next, if prompted, select the edition of Windows 11 you want to install.
2. Check the box to accept terms and click **Next**.
3. Select **Custom: Install Windows Only (Advanced).**  
![Windows 11 setup select installation drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-11-setup-select-installation-drive.jpg)
4. Select the installation drive and click **Next**. Wait for Windows to finish installation and restart your computer.
5. In the setup screen, select your region and keyboard layout.

1. Once in the **Let’s connect you to a network** screen, press **Shift + F10** to launch the **Command Prompt.**  
![oobe bypass nro command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/oobe-bypass-nro-command-prompt.jpg)
2. In the Command Prompt window, type the following command and press **Enter**:  
`OOBE\BYPASSNRO`
3. Upon successful execution, your system will restart and relaunch the OOBE dialog.  
![Windows-11-setup-select-installation-i-don't-have-internet-connection](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-11-setup-select-installation-i-don-t-have-internet-connection.jpg)
4. Follow the on-screen instructions to complete the setup. When you reach the **Let’s connect you to a network screen**, click on **I don’t have Internet** option.
5. Next, click on **Continue with limited setup.**  
![Windows 11 setup select installation continue with limited setup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-11-setup-select-installation-continue-with-limited-setup.jpg)
6. Accept the **License Agreement** and proceed to create your local user account.

 Make sure to add security questions. This will help you recover your local user account in case you forget your password. Once done, follow the on-screen instructions to complete the setup.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925549/19272" target="_top" id="1925549">
  <img src="//a.impactradius-go.com/display-ad/19272-1925549" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925549/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. End Network Connection Flow Process Using Task Manager

 You can bypass the "let’s connect you to a network" screen by killing the **oobenetworkconnectionflow.exe** process using the Windows Task Manager.

 Since you already have Windows 11 installed at this stage, you can [launch the Task Manager](https://www.makeuseof.com/how-to-access-task-manager-on-windows-11/) on top of your setup wizard using Command Prompt and kill the process.

 To skip the Windows 11 network setup using Task Manager:

1. Assuming you are in the **Let’s connect you to a network screen**, press **Shift + F10** to launch the Command Prompt.
2. In the Command Prompt window, type **taskmgr** and hit enter to launch **Task Manager.**  
![open task manager command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/open-task-manager-command-prompt.png)
3. Alternatively, use the **Ctrl + Shift + Esc** shortcut to launch Task Manager without Command Prompt.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115937/19272" target="_top" id="2115937">
  <img src="//a.impactradius-go.com/display-ad/19272-2115937" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115937/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Click **More Details** to open Task Manager in full view.
5. In the **Processes** tab, locate **Network Connection Flow.** Use the search bar in Task Manager to find the Network Connection Flow process.  
![Windows 11 setup select installation task manager kill network connection flow](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-11-setup-select-installation-task-manager-kill-network-connection-flow.jpg)
6. Select the **Network Connection Flow** process and then click the **End task** button. Wait for the process to end and then close the Task Manager.
7. Type **exit** in the Command Prompt and hit enter.

 Now you will be back in the setup wizard. It will show some loading animation and then proceed to the next step. Here enter your name and password to [create a local user account in Windows 11](http://www.makeuseof.com/ways-to-create-local-user-account-windows/) and complete the setup.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1884002/19272" target="_top" id="1884002">
  <img src="//a.impactradius-go.com/display-ad/19272-1884002" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1884002/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Directly Kill Network Connection Flow Using the Command Prompt

![end network connection flow command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/end-network-connection-flow-command-prompt.png)

<!-- affiliate ads begin -->
<span id="2135471">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2135471.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2135471">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2135471.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2135471%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2135471/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If you are unable to end the Network Connect Flow through Task Manager, you can directly kill it using the Command Prompt. Here’s how to do it.

1. At the Let’s connect you to a network screen, press **Shift + F10** to launch Command Prompt.
2. In the Command prompt window, type the following command and hit enter to execute:  
`taskkill /F /IM oobenetworkconnectionflow.exe`
3. Once executed, close the Command Prompt window to continue with the setup.

<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/352555/5172" target="_top" id="352555">
  <img src="//a.impactradius-go.com/display-ad/5172-352555" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/352555/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Skip Let’s Connect You to a Network Page with Alt + F4

 This workaround is more of a hit-or-miss but seems to have helped a few users. When at the **Let's connect you to a network screen**, pressthe **Alt + F4** keyboard shortcut to close the mandatory Internet connection required window. Incidentally, you can use this shortcut to close active windows/programs when working on your desktop as well.

 For more such handy shortcuts, explore our [ultimate guide to Windows 11 keyboard shortcuts](https://www.makeuseof.com/windows-11-keyboard-shortcuts/).

 If successful, Windows 11 will skip the current screen and move to the next step. Once you're past this step, you can create a local user account and then complete the setup.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925570/19272" target="_top" id="1925570">
  <img src="//a.impactradius-go.com/display-ad/19272-1925570" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925570/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Completing the Windows 11 Setup Without Internet Access

 You can follow one of the four methods listed above to skip the let’s connect you to a network window and complete the Windows 11 setup without the internet.

 That said, once you finish the setup and create a local user account, connect to the Internet to download critical security updates and features. You may also notice a few missing icons after the initial setup. Windows will download these icons when you connect to the Internet next time.

 This becomes an issue if you want to use a local user account or don’t have an active internet connection during setup. Luckily, there are a few workarounds to skip the Windows 11 network setup. Here we show you how to bypass this restriction and complete the Windows 11 setup without an internet connection.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-best-practices-for-documenting-lol-playthroughs/"><u>[New] In 2024, Best Practices for Documenting LOL Playthroughs</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-unleash-call-record-potential-essential-free-and-paid-tactics-for-skype-on-computers/"><u>[Updated] 2024 Approved  Unleash Call Record Potential - Essential Free & Paid Tactics for Skype on Computers</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-get-savvy-with-chromebook-snaps-explore-these-4-methods/"><u>[Updated] Get Savvy with Chromebook Snaps - Explore These 4 Methods</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/10-minute-bangla-blitz-start-your-language-adventure-today/"><u>10-Minute Bangla Blitz: Start Your Language Adventure Today</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-mastering-iphone-photo-blurring-4-techniques-explored/"><u>2024 Approved  Mastering iPhone Photo Blurring  4 Techniques Explored</u></a></li>
<li><a href="https://facebook.techidaily.com/budget-friendly-but-flawed-a-closer-look-at-the-mobvoi-ticwatch-e2-review/"><u>Budget-Friendly but Flawed: A Closer Look at the Mobvoi TicWatch E2 Review</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-media-player-server-crash/"><u>Fixing Media Player Server Crash</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-overcoming-lol-launch-lag/"><u>Guide to Overcoming LOL Launch Lag</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-postpone-windows-10-shutdown-during-active-processes/"><u>Guide to Postpone Windows 10 Shutdown During Active Processes</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-force-delete-or-uninstall-a-printer-in-windows-10-and-11/"><u>How to Force Delete or Uninstall a Printer in Windows 10 & 11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-any-infinix-smart-8-phone-password-using-emergency-call-by-drfone-android/"><u>How To Unlock Any Infinix Smart 8 Phone Password Using Emergency Call</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-card-on-nokia-150-2023-online-without-jailbreak-by-drfone-android/"><u>How to Unlock SIM Card on Nokia 150 (2023) online without jailbreak</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-vboxs-security-settings-secure-boot-and-tpm-management/"><u>Mastering VBox's Security Settings: Secure Boot & TPM Management</u></a></li>
<li><a href="https://windows11.techidaily.com/modify-default-task-manager-viewport-in-win11/"><u>Modify Default Task Manager Viewport in Win11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/nighttime-nirvana-with-asmr-select-artists/"><u>Nighttime Nirvana with ASMR  Select Artists</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-keyboard-interface-with-personalized-fn-keys-in-windows-11/"><u>Optimizing Keyboard Interface with Personalized FN Keys in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-usb-device-errors-on-windows-pcs/"><u>Overcoming USB Device Errors on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/personalized-overheat-avoidance-bios-tutorial-for-win-users/"><u>Personalized Overheat Avoidance: BIOS Tutorial for Win Users</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-common-winx-update-error-0x80246007/"><u>Quick Fixes for Common WinX Update Error: 0X80246007</u></a></li>
<li><a href="https://windows11.techidaily.com/regain-your-control-restoring-synapse-on-w10-and-w11/"><u>Regain Your Control: Restoring Synapse on W10 & W11</u></a></li>
<li><a href="https://windows11.techidaily.com/regaining-composure-post-high-living-days-for-windows-users/"><u>Regaining Composure Post-High Living Days, for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/reigniting-frozen-discord-overlay-a-stepwise-guide-for-windows-users/"><u>Reigniting Frozen Discord Overlay: A Stepwise Guide for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/security-refresh-windows-firewalls-five-commandments/"><u>Security Refresh: Windows Firewall's Five Commandments</u></a></li>
<li><a href="https://windows11.techidaily.com/smooth-operations-at-low-cost-leverage-w11-pro-key/"><u>Smooth Operations at Low Cost: Leverage W11 Pro Key</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-spontaneous-scrolls-a-winworlders-guide/"><u>Stop Spontaneous Scrolls: A Winworlder's Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/strategic-shopping-for-cost-efficient-windows-11-keys/"><u>Strategic Shopping for Cost-Efficient Windows 11 Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-decrease-high-cpu-consumption-by-dropbox-on-windows/"><u>Strategies to Decrease High CPU Consumption by Dropbox on Windows</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/streamline-your-vlogs-sound-with-effective-tips-for-2024/"><u>Streamline Your Vlog's Sound with Effective Tips for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/strengthen-your-safe-space-top-5-corrections-in-windows-features/"><u>Strengthen Your Safe Space: Top 5 Corrections in Windows Features</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-windows-update-failures-error-x712/"><u>Tackling Windows Update Failures: Error X712</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-picture-previews-in-windows-11-ui/"><u>Tailoring Picture Previews in Windows 11 UI</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-core-of-generative-ai-revealed/"><u>The Core of Generative AI Revealed</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-access-denial-in-windows-11-a-quick-guide-to-5-solutions/"><u>Troubleshooting Access Denial in Windows 11: A Quick Guide to 5 Solutions</u></a></li>
<li><a href="https://android-frp.techidaily.com/ultimate-guide-on-motorola-edge-40-frp-bypass-by-drfone-android/"><u>Ultimate Guide on Motorola Edge 40 FRP Bypass</u></a></li>
<li><a href="https://windows11.techidaily.com/ultimate-list-wins-premier-video-trimming-tools/"><u>Ultimate List: Win's Premier Video Trimming Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/unique-apps-for-a-stylish-windows-clock-display/"><u>Unique Apps for a Stylish Windows Clock Display</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11s-vanishing-icons-restoration-strategies/"><u>Win 11'S Vanishing Icons - Restoration Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-1110-hacks-swift-recovery-of-synapse-functions/"><u>Windows 11/10 Hacks: Swift Recovery of Synapse Functions</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-with-both-wi-fi-and-ethernet-connections-on-your-computer/"><u>Winning with Both Wi-Fi & Ethernet Connections on Your Computer</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>