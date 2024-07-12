---
title: "Delving Into Windows Tools: CHKDSK, SFC & DISM's Functions"
date: 2024-07-11T22:30:10.659Z
updated: 2024-07-12T22:30:10.659Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Delving Into Windows Tools: CHKDSK, SFC & DISM's Functions"
excerpt: "This Article Describes Delving Into Windows Tools: CHKDSK, SFC & DISM's Functions"
keywords: Windows CHKDSK,System SFC Fix,DISM Diagnostic Tool,CHKDSK Utility,SFC Error Repair,System File Checker,Disable Integrity Failures
thumbnail: https://thmb.techidaily.com/7190f701d24b2bca2702a5bcd803eaeb74415822adafed338c6c5049f6c7aefb.jpg
---

## Delving Into Windows Tools: CHKDSK, SFC & DISM's Functions

### Quick Links

* [What Is CHKDSK and When Should You Use It?](#what-is-chkdsk-and-when-should-you-use-it)
* [What Is SFC Scannow and When Should You Use It?](#what-is-sfc-scannow-and-when-should-you-use-it)
* [What Is DISM and When Should You Use It?](#what-is-dism-and-when-should-you-use-it)
* [What Order Should You Run CHKDSK, SFC, and DISM In?](#what-order-should-you-run-chkdsk-sfc-and-dism-in)

### Key Takeaways

* CHKDSK scans your hard drive for errors and bad sectors, and you should run it if your computer isn't booting properly.
* SFC scans and repairs Windows system files, so run it when you experience program crashes or missing DLL errors.
* DISM is the most powerful tool and fixes corrupt files in the Windows system image, use it when SFC can't repair files.

 When your PC starts reporting errors, slowing down, or misbehaving, you can use Windows's built-in diagnostic tools to try and fix the problem. CHKDSK, SFC, and DISM check the health of your hard drive and repair corrupt files, but the three tools work in different ways and target different areas of your system.

 CHKDSK, SFC, and DISM are system tools, and you can run all three. However, this can be time-consuming and unnecessary for your specific problem, so it's best to know when and how to use this trio of troubleshooting tools.

## What Is CHKDSK and When Should You Use It?

 CHKDSK (Check Disk) is the first Windows diagnostic tool you should try if your PC starts acting strangely. For example, if it hangs while shutting down or becomes frustratingly slow.

 CHKDSK scans your entire hard drive to find and fix errors in files and the file system itself. It also checks your drive for bad sectors (clusters of data that cannot be read), and either tries to repair them or tells your system not to use them.

 Windows may run CHKDSK on startup if it detects a problem with your hard drive, sometimes for innocuous reasons such as improper shutdown, but also more serious ones, including malware infection and impending drive failure. However, it won't actually fix any issues until instructed to do so.

 To prevent future errors and potential data loss, it's worth running CHKDSK manually as part of your PC maintenance routine. You can use one of the following methods:

### 1\. Run CHKDSK Through File Explorer

 You can run CHKDSK from the command prompt. If you're uncomfortable using the Command Prompt, open **File Explorer**, click **This PC**, right-click the drive you want to check and select **Properties**.

 Select the **Tools** tab and then select **Check** in the **Error-checking** section.

![Launch the Check Disk tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-error-checking.jpg)

 If Windows determines that everything is running smoothly, it will suggest that you don't need to scan the drive. To run CHKDSK anyway, select **Scan drive**.

 The scan may take anywhere from a few minutes to half an hour, depending on the size and state of your drive. Once complete, CHKDSK will either tell you that no errors were found, or if it does find any, it will suggest you fix them.

### 2\. Run CHKDSK From the Command Prompt

 For greater control over the disk-checking process, you should run CHKDSK from an elevated Command Prompt. Follow these steps to continue:

1. Press the **Win** \+ **R** keys to open the Run dialog.
2. Type "cmd" in Run and press the **Ctrl** \+ **Shift** \+ **Enter** keys together to open Command Prompt as an administrator.
3. Click **Yes** in the User Account Control prompt.
4. In the Command Prompt window, type **chkdsk,** then space, followed by the drive letter you want to check. For example, **chkdsk c:** to scan your C: drive.  
![CHKDSK scan in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/chkdsk-scan.jpg)
5. Press **Enter** to scan for errors in read-only mode, which means no changes will be made.

 To make changes, you can use parameters with the CHKDSK command. Here are two you can use to fix problems:

* To make CHKDSK fix the problems it finds, type **chkdsk /f c:** (for your C: drive).
* To scan for bad sectors and errors, type **chkdsk /r c:**

 If you cannot run these commands because "the volume is in use by another process," Command Prompt will offer to schedule the scan for when your PC restarts. This should, however, only happen once. If the tool pops up whenever you boot your PC, you can [stop CHKDSK from running at every startup](https://www.makeuseof.com/tag/stuck-chkdsk-use-fix-right-way/) manually.

## What Is SFC Scannow and When Should You Use It?

 Whereas CHKDSK finds and fixes errors in the file system of your hard drive, **SFC (System File Checker)** specifically scans and repairs Windows system files. If it detects a file has been corrupted or modified, SFC automatically replaces that file with the correct version.

 Knowing when to use SFC is usually more obvious than with CHKDSK, which depends on the hunch that your hard drive isn't behaving correctly. If Windows programs are crashing, you're getting error messages about missing DLL files, or you're experiencing the dreaded Blue Screen of Death, then it's definitely time to run SFC.

[Open an elevated Command Prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), then type the following command and press **Enter** to execute:

`sfc /scannow`

 SFC will perform a full scan of your system and repair and replace any files that are damaged or missing using versions from the Windows component store (read the next section on DISM for more information on this and how SFC and DISM work can work together). The scan can take some time, but make sure you leave the Command Prompt window open until it's complete.

 If you only want to scan but not repair corrupted system files, type:

`sfc /verifyonly command`

 Once SFC has finished scanning, you'll see one of three messages:

* **Windows Resource Protection did not find any integrity violations.** This means that whatever's causing your PC problems isn't related to a system file.
* **Windows Resource Protection found corrupt files and successfully repaired them.** This should hopefully mean that your problems have been solved.
* **Windows Resource Protection found corrupt files but was unable to fix some of them.** This means that system files are to blame, but SFC can't replace them. Try running the tool again in Safe Mode. If you still get the same result, don't despair: it's time to use DISM.

![Screenshot of complete sfc scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/screenshot-of-complete-sfc-scan.jpg)

## What Is DISM and When Should You Use It?

**DISM (Deployment Image Servicing and Management)** is the most powerful of the three Windows diagnostic tools. Although you shouldn't usually need to use the tools, it's the one to turn to when you're experiencing frequent crashes, freezes, and errors, but SFC either can't repair your system files or is unable to run at all.

 While CHKDSK scans your hard drive and SFC your system files, DISM detects and fixes corrupt files in the component store of the Windows system image so that SFC can work properly. It can also help with Windows updates, driver integration, and boot issues you might be facing.

[Create a backup of your data](https://www.makeuseof.com/tag/ultimate-windows-10-data-backup-guide/) before running DISM, just in case something goes wrong.

 As with CHKDSK and SFC, you'll need to open an elevated Command Prompt (or Administrator Terminal Window on Windows 11) to run DISM. To save you the time and risk of performing repairs unnecessarily, you can first check if the image is corrupted without making any changes. Type the following command and press Enter:

`Dism /Online /Cleanup-Image /CheckHealth`

![windows dism check in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/windows-dism-check-in-command-prompt.jpg)

 The scan should only take a few seconds. If no corruption is detected, you can run a more advanced scan to determine if the component store is healthy and repairable, again without making any changes, by typing:

`Dism /Online /Cleanup-Image /ScanHealth`

 If DISM reports that there are problems with the system image, run another advanced scan to repair these issues automatically. DISM will connect to Windows Update to download and replace damaged files as required. Note that the process may take up to 10 minutes and hang for a while at 20 seconds, but this is normal. Type this command:

`Dism /Online /Cleanup-Image /RestoreHealth  
`

![dism scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dism-scan.jpg)

 Once the scan and repairs are complete, restart your PC and run SFC again to replace your corrupt or missing system files.

## What Order Should You Run CHKDSK, SFC, and DISM In?

 Now that you understand what CHKDSK, SFC, and DISM do, running one or more of these Windows troubleshooting tools will hopefully help you fix your PC.

 However, a common question concerns the order in which you should run these system tests. Should you always run CHKDSK first? Or how about always running DISM before SFC?

 There is no specific order to CHKDSK, SFC, and DISM, as why you run each tool depends on the issue you're experiencing. However, if you run SFC and it finds corrupt files and other issues, you should then run DISM to fix the Component Store and then run SFC again to fix any broken files.

 If you're still having trouble, perform a System Restore. This will restore your system files, settings, and programs to a time when they worked properly. If your system wasn't damaged when the restore point was created, it may solve your corruption problems.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://mondly-stories.techidaily.com/catalan-in-flash-daily-10-minute-lessons/"><u>Catalan in Flash: Daily 10-Minute Lessons</u></a></li>
<li><a href="https://windows11.techidaily.com/countering-compromised-windows-defender-on-win-11/"><u>Countering Compromised Windows Defender on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-sound-malfunction-fixing-error-code-xc00d36b4/"><u>Combatting Sound Malfunction: Fixing Error Code Xc00d36b4</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-investing-wisdom-in-webcams-finest-stocks-channels/"><u>[New] 2024 Approved  Investing Wisdom in Webcams  Finest Stocks Channels</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-resource-unavailable-situations-on-windows-149-chars/"><u>Correcting 'Resource Unavailable' Situations on Windows (149 Chars)</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-listenguide-breakdown/"><u>[New] In 2024, ListenGuide Breakdown</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/the-strategists-handbook-for-youtube-ad-profitability-for-2024/"><u>The Strategist's Handbook for YouTube Ad Profitability for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-a-compre-point-strategies-for-effortless-story-posting-for-2024/"><u>[Updated] A Compre Point  Strategies For Effortless Story Posting for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/-success-the-ultimate-list-of-channels/"><u>Stock Success  The Ultimate List of Channels</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-account-lockout-reset-in-successive-login-attempts-windows-1011/"><u>Configuring Account Lockout Reset in Successive Login Attempts Windows 10/11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-premium-components-for-next-gen-streaming/"><u>[Updated] Premium Components for Next-Gen Streaming</u></a></li>
<li><a href="https://windows11.techidaily.com/counteracting-the-impact-of-vac-denial-in-steam-gaming/"><u>Counteracting the Impact of VAC Denial in Steam Gaming</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-quick-access-to-start-from-onedrive/"><u>Customizing Quick Access to Start From OneDrive</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-to-fixing-device-path-errors/"><u>Comprehensive Guide to Fixing Device Path Errors</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-next-gen-display-top-5-hdmi-21-infinity-refresh-monitors-ps5/"><u>[Updated] Next-Gen Display  Top 5 HDMI 2.1 Infinity Refresh Monitors [PS5]</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-pioneering-adventures-the-ultimate-gaming-list-top-10/"><u>[Updated] 2024 Approved  Pioneering Adventures  The Ultimate Gaming List (Top 10)</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-x80070091-error-in-windows-steps-for-empty-directory-problem-solving/"><u>Deciphering X80070091 Error in Windows - Steps for 'Empty Directory' Problem Solving</u></a></li>
<li><a href="https://windows11.techidaily.com/cut-down-complications-opt-for-simplicity-in-win11/"><u>Cut Down Complications: Opt for Simplicity in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/compilation-of-best-windows-11-art-software/"><u>Compilation of Best Windows 11 Art Software</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-srt-fundamentals-explored-in-detail-and-clarity/"><u>[New] SRT Fundamentals Explored in Detail and Clarity</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-bsod-0x0000003b-and-resolution-steps-in-windows-os/"><u>Decoding BSOD -0X0000003B & Resolution Steps in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-non-deletable-keys-a-windows-guide/"><u>Correcting Non-Deletable Keys: A Windows Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-absence-of-drive-letters-problems-and-cures-for-win-users/"><u>Decoding the Absence of Drive Letters: Problems & Cures for Win Users</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-crafting-viral-videos-on-youtube-a-strategic-plan/"><u>[Updated] Crafting Viral Videos on YouTube  A Strategic Plan</u></a></li>
<li><a href="https://windows11.techidaily.com/controlling-elements-post-sleep-for-optimal-use/"><u>Controlling Elements Post-Sleep for Optimal Use</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-3-things-you-must-know-about-fake-snapchat-location-on-realme-c55-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Things You Must Know about Fake Snapchat Location On Realme C55 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/dive-into-deeper-game-experience-incorporating-achievements-in-vintage-titles-through-retroarch/"><u>Dive Into Deeper Game Experience: Incorporating Achievements in Vintage Titles Through Retroarch</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-access-issues-enabling-windows-logins-post-fail/"><u>Clearing Access Issues: Enabling Windows Logins Post-Fail</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/2024-approved-top-trending-android-apps-on-google-play-this-month/"><u>2024 Approved Top-Trending Android Apps on Google Play This Month</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-2024-approved-avoiding-tiktoks-ghost-mode-strategies-to-stay-visible/"><u>[New] 2024 Approved  Avoiding TikTok's Ghost Mode  Strategies to Stay Visible</u></a></li>
<li><a href="https://windows11.techidaily.com/curtailing-windows-updates-and-restarts/"><u>Curtailing Windows Updates and Restarts</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-facts-you-need-to-know-about-screen-mirroring-nokia-c22-drfone-by-drfone-android/"><u>In 2024, 3 Facts You Need to Know about Screen Mirroring Nokia C22 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-windows-11s-application-could-not-be-started-error-xc000003e/"><u>Combatting Windows 11'S Application Could Not Be Started Error Xc000003e</u></a></li>
<li><a href="https://windows11.techidaily.com/determining-public-ip-with-system-commands-windows/"><u>Determining Public IP with System Commands, Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-procedure-call-failures-in-malwarebytes-for-windows-os/"><u>Combatting Procedure Call Failures in Malwarebytes for Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-windows-layout-fancywm-power-up/"><u>Customize Windows Layout: FancyWM Power Up</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/in-2024-budget-friendly-filmmaking-essentials-software-you-need/"><u>In 2024, Budget-Friendly Filmmaking Essentials Software You Need</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/2024-approved-prankster-peak-standout-comedians-of-the-week/"><u>2024 Approved  Prankster Peak  Standout Comedians of the Week</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-home-screen-preferences-on-w11-os/"><u>Customizing Home Screen Preferences on W11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/counteracting-dxgierrordeviceremoved-in-win-1011/"><u>Counteracting DXGI_ERROR_DEVICE_REMOVED in Win 10/11</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>