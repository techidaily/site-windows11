---
title: "Revitalize Your Clockwork: Restore Missing Windows Server Time"
date: 2024-10-14T17:34:24.128Z
updated: 2024-10-18T18:16:00.977Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Revitalize Your Clockwork: Restore Missing Windows Server Time"
excerpt: "This Article Describes Revitalize Your Clockwork: Restore Missing Windows Server Time"
keywords: Server Time Update,Windows Time Fix,Missing Window Time,Clockwork Reset,Time Sync Issue,Server Date Align,Restore Time Patch
thumbnail: https://thmb.techidaily.com/e2b01a1128735e3ec5310f2cbee0a0035159bd501806692c9cb150d9959d92bc.jpg
---

## Revitalize Your Clockwork: Restore Missing Windows Server Time

 Start your Windows computer and notice that the time is wrong. It might be a minor issue, or you accidentally changed the setting. But what if Windows Time Service is missing entirely?

 Fortunately, restoring the Windows Time Service is not complicated. This guide will discuss quickly restoring the missing Windows Time Service and setting the correct time on your computer.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Reboot Your PC

 Restart your computer before attempting any major troubleshooting. While it may sound simple, restarting the computer resolves minor errors and glitches that prevent the service from running. It flushes out temporary files and refreshes the operating system to ensure everything works correctly.

1. Press **Alt + F4** to bring up the Shutdown dialog
2. Select **Restart** from the drop-down menu and then hit **OK**.

 Once the computer restarts, check if Windows Time Service is available. If it's still missing, move on to the next step.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037474/7443" target="_top" id="2037474">
  <img src="//a.impactradius-go.com/display-ad/7443-2037474" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037474/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Change the Time Server

 If restarting the computer does not work, you must change the time server. Changing the time server synchronizes your system clock with an online one, displaying your computer's correct date and time.

 Follow the steps to change the time server:

1. Press the **Windows key** to open the Start Menu.
2. Type **control panel** in the search box and click the result. This opens the Control Panel window.
3. Select **View by: Large icons** and click **Date and Time**.
4. Switch to the **Internet Time** tab and click **Change settings**.
5. Check the **Synchronize with an Internet time server** box and select a time server from the drop-down menu.  
![Change the Time Server](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/change-the-time-server.jpg)
6. Click the **Update now** button to synchronize your computer with the time server.

7. Once completed, click **OK** to save the changes and exit.

 After these steps, you should see the Windows Time Service running on your system. Check the time to ensure it is correct and make further adjustments.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2129741/7443" target="_top" id="2129741">
  <img src="//a.impactradius-go.com/display-ad/7443-2129741" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2129741/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Add More Time Servers

 If the Windows Time Service is still missing, you can try adding more time servers to the list. Multiple time servers increase the chance of finding an active server and keeping your system in sync. If one server goes down, your computer can automatically switch to another.

 The solution requires editing the Windows registry. Even a small mistake can damage your system, so proceed with caution. To avoid data loss, [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing.

 To add time servers, do the following:

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **regedit** in the dialog box and click **OK**.
3. If the UAC window pops up on the screen, click **Yes** to grant permission.
4. In the Registry Editor window, navigate to the following directory.  
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\DateTime\Servers  
 Copy and paste the path into the Registry Editor address bar and press Enter. This will take you to the Location key.
5. From the left navigation panel, right-click the Servers folder and select **New** \> **String Value**.  
![Add More Time Servers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/add-more-time-servers.jpg)
6. Name the new value **Server N**, and replace **N** with a number starting from 1.  

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136627/26400" target="_top" id="2136627">
  <img src="//a.impactradius-go.com/display-ad/26400-2136627" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136627/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can't have the same number twice. That means if there are already 3 values named _Server 1_, _Server 2_, and _Server 3_, you must call the new one as **Server 4**.
7. Double-click the newly created value and add a time server address in the Value data field.
8. Here are some time server addresses:  
`time.windows.com  

time.nist.gov  

time-a-wwv.nist.gov  

time-c-wwv.nist.gov  

ntp-wwv.nist.gov`

 After adding the time server, click **OK** and close the Registry Editor window. Now restart your computer to apply the changes and check if Windows Time Service is available.

## 4\. Re-register the Windows Time Service

 If the above steps fail, you can try re-registering the Windows Time Service. Re-registering a service refreshes its configuration and forces it to start again. Doing this may fix the missing Windows Time Service and recover clock synchronization.

 To re-register the Windows Time Service, follow these steps:

1. Press the **Win + S** keys to open the Windows Search.
2. Type **cmd** in the search box and simultaneously press **Ctrl + Shift + Enter**. This opens the Command Prompt with administrative privileges.
3. If the UAC window pops up, click **Yes** to grant permission.
4. Type the following command in the Command Prompt and press Enter:  
net stop w32time
5. This command will stop the Windows Time Service. Now type the following command to unregister the service and press **Enter**:  
w32tm /unregister
6. After that, run the following command to register the service:  
w32tm /register
7. Next, type the following command and hit **Enter**. This starts the Windows Time Service.  
net start w32time

 After performing these steps, close the Command Prompt window and restart your system. You should see that the Windows Time Service is running, and your clock syncs with the time server.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006914/19272" target="_top" id="2006914">
  <img src="//a.impactradius-go.com/display-ad/19272-2006914" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006914/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Repair Corrupted System Files

![SFC Command Preview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/sfc-command-preview.jpg)

 Corrupt system files can also cause Windows services to fail. So, if the Windows Time Service is still missing, try repairing corrupt system files. You can do this using the System File Checker tool. This tool scans your system for missing files and repairs the errors it finds.

 Wait for the scan to complete, and restart your computer. After that, check if the Windows Time Service is still missing. If it is, try running the Deployment Image Servicing and Management tool. This tool repairs corrupted system files and restores your Windows installation's health.

 If you're not sure how to run either of these tools, check out how to repair corrupt Windows files with its built-in tools for instructions.

## 6\. Scan for Malware

 Sometimes, malware is to blame for Windows services acting a little odd. As such, it's worth [running a full system scan](https://www.makeuseof.com/scan-for-viruses-without-buying-antivirus-software/) and removing all detected threats.

![Full Scan Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/full-scan-windows-security.jpg)

 If you feel your PC isn't as secure as it could be, you could try downloading one of the [best antivirus apps for Windows](http://www.makeuseof.com/windows-11-antivirus-apps/). These will both actively block malicious program from installing themselves on your PC, and remove any that are currently infesting your computer.

 For those who prefer a command-line approach, you can [use Windows PowerShell to scan Windows for malware](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/).

## Restore the Missing Windows Time Service

 Hopefully, one or more of these tips worked for you. Missing Windows services can be a huge pain, but hopefully, one of these methods has brought back the Windows Time Service back to working order.

 Fortunately, restoring the Windows Time Service is not complicated. This guide will discuss quickly restoring the missing Windows Time Service and setting the correct time on your computer.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-the-ultimate-pathway-for-storytellers-mastery-over-facebook-live-feature/"><u>[Updated] 2024 Approved The Ultimate Pathway for Storytellers Mastery Over Facebook Live Feature</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-synthesize-and-add-videos-to-your-listing/"><u>2024 Approved Synthesize and Add Videos to Your Listing</u></a></li>
<li><a href="https://common-error.techidaily.com/boost-your-league-of-legends-gameplay-with-improved-faster-download-speeds/"><u>Boost Your League of Legends Gameplay with Improved Faster Download Speeds</u></a></li>
<li><a href="https://driver-download.techidaily.com/guide-to-repairing-startech-peripheral-driver-conflicts-on-various-windows-os-versions/"><u>Guide to Repairing StarTech Peripheral Driver Conflicts on Various Windows OS Versions</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/juxtaposing-flight-with-flair-a-bebop-parrot-analysis-for-2024/"><u>Juxtaposing Flight with Flair – A Bebop Parrot Analysis for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/master-microsoft-excel-a-comprehensive-guide-with-12-tricks-for-correcting-faulty-formulas/"><u>Master Microsoft Excel: A Comprehensive Guide with 12 Tricks for Correcting Faulty Formulas</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-excel-a-step-by-step-guide-to-searching-and-substituting-text-and-numbers/"><u>Mastering Excel: A Step-by-Step Guide to Searching and Substituting Text & Numbers</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-unit-conversions-a-step-by-step-guide-using-microsoft-excel/"><u>Mastering Unit Conversions: A Step-by-Step Guide Using Microsoft Excel</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-adding-images-to-your-microsoft-excel-spreadsheet/"><u>Step-by-Step Guide: Adding Images to Your Microsoft Excel Spreadsheet</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-properly-formatting-telephone-digits-in-excel-spreadsheets/"><u>Step-by-Step Guide: Properly Formatting Telephone Digits in Excel Spreadsheets</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-removing-a-pivottable-from-your-microsoft-excel-spreadsheet/"><u>Step-by-Step Guide: Removing a PivotTable From Your Microsoft Excel Spreadsheet</u></a></li>
<li><a href="https://unlock-android.techidaily.com/still-using-pattern-locks-with-zte-axon-40-lite-tips-tricks-and-helpful-advice-by-drfone-android/"><u>Still Using Pattern Locks with ZTE Axon 40 Lite? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/the-quest-for-the-best-framerate-balancing-speed-and-clarity/"><u>The Quest for the Best Framerate - Balancing Speed & Clarity</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723016477759-trouble-with-discord-voice-here-are-the-fixes-you-need/"><u>Trouble with Discord Voice? Here Are the Fixes You Need</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secrets-of-locating-data-positions-with-excel-match-function-a-comprehensive-guide/"><u>Unveiling the Secrets of Locating Data Positions with Excel MATCH Function: A Comprehensive Guide</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/unveiling-the-top-10-photographic-rescue-experts-a-thorough-evaluation-of-pros-and-cons/"><u>Unveiling the Top 10 Photographic Rescue Experts : A Thorough Evaluation of Pros & Cons</u></a></li>
</ul></div>

