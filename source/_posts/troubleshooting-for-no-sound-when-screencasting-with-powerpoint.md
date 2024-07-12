---
title: Troubleshooting for No Sound when Screencasting with PowerPoint
date: 2024-07-11T21:58:50.999Z
updated: 2024-07-12T21:58:50.999Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting for No Sound when Screencasting with PowerPoint
excerpt: This Article Describes Troubleshooting for No Sound when Screencasting with PowerPoint
keywords: PowerPoint NoSound Fix,ScreenCast Silence Issue,Screencast Audio Loss,Clear PowerPoint Sound Problems,Resolve PPT Audio Glitches,Troubleshoot PPT Sound Mute,Eliminate ScreenCast Silence
thumbnail: https://thmb.techidaily.com/a333bfbef34affdca1048ed2699696db5230242a15d7fcb3455927615d5179aa.JPG
---

## Troubleshooting for No Sound when Screencasting with PowerPoint

 The screen recording feature in Microsoft PowerPoint can be useful for recording tutorials or training videos on your computer. But what if PowerPoint fails to capture the audio when you record the screen of your Windows computer?

 If you are annoyed by a similar issue, here are some troubleshooting tips that will help.

## 1\. Restart PowerPoint

 Temporary issues with PowerPoint can sometimes disrupt its ability to capture audio on your Windows computer. If it’s just a one-off glitch, simply closing and reopening PowerPoint should fix the problem.

 Press **Ctrl + Shift + Esc** to open the Task Manager. In the **Processes** tab, right-click on **Microsoft PowerPoint** and select the **End task** option.

![Close PowerPoint Using Task Manager on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/close-powerpoint-using-task-manager-on-windows.jpg)

 Right-click on the **PowerPoint** shortcut and select **Run as administrator**. After that, try to create a screen recording and see if PowerPoint records the audio this time.

## 2\. Allow Desktop Apps to Use Your Microphone

 Another reason why PowerPoint might fail to record audio is if you have denied desktop apps permission to access your microphone. Here's how you can change that.

1. Press **Win + I** to open the Settings app.
2. Head to **Privacy & security > App permissions > Microphone**.
3. Enable the toggle next to **Let desktop apps access your microphone**.  
![Allow Desktop Apps to Access Microphone on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/allow-desktop-apps-to-access-microphone-on-windows.jpg)

 Once you complete the above steps, all your desktop apps, including PowerPoint, should be able to use your microphone.

## 3\. Check Which Device Is Set as the Default Microphone on Windows

 Are there several audio devices connected to your Windows computer? If so, you need to ensure that you have selected the correct microphone on Windows.

 To view or change the default microphone on Windows, use these steps:

1. Click the **magnifying icon** on the taskbar to access the search menu.
2. Type **sound settings** in the box and press **Enter**.
3. Under the **Input** tab, select your preferred audio device.  
![Select Default Microphone in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/select-default-microphone-in-windows.jpg)

 Is your microphone not showing up in the Settings app? Apply the necessary [fixes to get Windows to detect your microphone](https://www.makeuseof.com/windows-not-detecting-microphone/).

## 4\. Disable Hardware Graphics Acceleration in PowerPoint

 While enabling the hardware graphics acceleration feature in PowerPoint can improve its performance, the feature may not work seamlessly all the time. When this happens, you are likely to run into all kinds of issues, including issues with the screen recorder.

 According to a post on [Microsoft Community](https://answers.microsoft.com/en-us/msoffice/forum/all/audio-not-working-on-my-ppt-recording/79c77eae-2f86-4c09-a3d6-5fc4b3d89c58), several users managed to fix this particular issue by disabling the hardware graphics acceleration in PowerPoint. You can also give it a try with these steps:

1. Open PowerPoint on your PC.
2. Click the **File** menu in the top left corner.
3. Select **Options** from the left pane.
4. In the PowerPoint Options window, use the left pane to switch to the **Advanced** tab.
5. Scroll down to the **Display** section.
6. Clear the checkboxes that read **Disable hardware graphics acceleration** and **Disable Slide Show hardware graphics acceleration**.
7. Click **OK** to apply the changes.  
![Disable Hardware Acceleration in PowerPoint](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-hardware-acceleration-in-powerpoint.jpg)

 Restart PowerPoint after this for changes to take effect.

## 5\. Run the Windows Recording Audio Troubleshooter

 Windows offers several useful troubleshooters for fixing common issues on your computer. In this case, running the Recording Audio troubleshooter can help. It can automatically detect any issues with PowerPoint's audio recording functionality and fix them.

 To run the Recording Audio troubleshooter:

1. Right-click on the **Start** icon and select **Settings** from the list.
2. Navigate to **System > Troubleshoot > Other troubleshooters**.
3. Click the **Run** button next to **Recording Audio**.  
![Recording Audio Troubleshooter on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/recording-audio-troubleshooter-on-windows.jpg)

 Allow the troubleshooter to find and fix any issues, and then check if PowerPoint can record the audio.

## 6\. Restart the Windows Audio Services

 Windows relies on certain audio services to capture and record your audio. Typically, these services start automatically every time you boot your computer.

 However, if one of these services encounters any problems, your apps and programs may fail to record the audio. In most cases, you can fix such issues by simply restarting the audio services on your PC.

 To do so, use these steps:

1. Press **Win + S** to open the search menu.
2. Type **services** in the search box and select the first result that appears.
3. In the Services window, locate the **Windows Audio** service. Right-click on it and select **Restart**.
4. Similarly, restart the **Windows Audio Endpoint Builder** service as well.  
![Restart Windows Audio Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/restart-windows-audio-service.jpg)

 Using the Services app isn't the only way to manage services on Windows. You can also use Task Manager, Command Prompt and PowerShell to [start, stop or restart services on Windows](https://www.makeuseof.com/how-to-start-stop-service-windows/).

## 7\. Start PowerPoint in Safe Mode

 One of your add-ins may be acting up and causing PowerPoint to malfunction. To check for this possibility, you need to open PowerPoint in safe mode. For that, press **Win + R** to open the Run dialog box. Type **PowerPnt /safe** in the text field and press **Enter**.

 After opening PowerPoint in safe mode, try creating a screen recording and see if it records audio as expected. If it does, it means one of your add-ins is causing the problem. To identify the one causing the issue, you will need to disable all of your add-ins and then re-enable them one at a time. Here’s how to do that.

1. In PowerPoint, click the **File** menu in the top left corner.
2. Select **Options** in the left pane.
3. In the PowerPoint Options window, switch to the **Add-ins** tab.
4. Click the drop-down menu next to **Manage** and select **COM Add-ins**.
5. Click the **Go** button.
6. Clear the checkboxes to disable add-ins and then click **OK**.  
![Disable Add-ins in PowerPoint](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-add-ins-in-powerpoint.jpg)

 Restart PowerPoint after this, and then enable your add-ins one at a time until the issue occurs again. Once you find the faulty add-in, consider removing it.

## 8\. Update Microsoft PowerPoint

 Such issues can also occur if you are using an outdated version of PowerPoint. To update PowerPoint, navigate to **File > Account**. Click on **Update Options** and select **Update Now**.

![Update PowerPoint on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-powerpoint-on-windows.jpg)

 Wait for Microsoft Office to update PowerPoint, and the issue should not occur after that.

## 9\. Run the Office Repair Tool

 If PowerPoint still won’t record audio while recording the screen on Windows, you can run the Office repair tool as a last resort. Here are the steps for the same.

1. Press **Win + S** to open the search menu.
2. Type **control panel** in the text box and press **Enter**.
3. Click on **Programs and Features**.
4. Locate the **Microsoft Office suite** on the list. Right-click on it and select **Change**.
5. Select the **Quick Repair** option and hit the **Repair** button.  
![Repair Microsoft Office](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/repair-microsoft-office.jpg)

 If the problem persists even after this, you can run the Office repair tool again to perform an **Online Repair**. Note that this process may take a little longer to complete, as the tool will attempt a more thorough repair.

## Get PowerPoint to Record Your Audio Again on Windows

 It can be frustrating when PowerPoint stops recording audio on your Windows computer. In any case, one of the above tips should help fix the underlying issue for good.

 If you are annoyed by a similar issue, here are some troubleshooting tips that will help.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/solve-icloud-download-issues-with-these-helpful-steps/"><u>Solve iCloud Download Issues with These Helpful Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/lost-in-explore-reintroducing-your-sd-card/"><u>Lost in Explore: Reintroducing Your SD Card</u></a></li>
<li><a href="https://windows11.techidaily.com/outdated-pcs-upgraded-to-modern-windows-11-standards/"><u>Outdated PCs Upgraded to Modern Windows 11 Standards</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-error-messages-related-to-virtual-disks/"><u>Overcoming Error Messages Related to Virtual Disks</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-pros-guide-to-fb-advertising-success/"><u>[Updated] Pros' Guide to FB Advertising Success</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-guide-to-the-best-free-video-conferencing-software-for-corporate-and-educational-sectors/"><u>[New] In 2024, Guide to the Best Free Video Conferencing Software for Corporate and Educational Sectors</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-aural-clean-up-purifying-recordings-on-audacity-for-2024/"><u>[New] Aural Clean-Up  Purifying Recordings on Audacity for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-the-problem-of-unrecognized-drivers-during-windows-startup/"><u>Fixing the Problem of Unrecognized Drivers During Windows Startup</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tuning-video-speed-in-vlc-to-minimize-delay/"><u>Fine-Tuning Video Speed in VLC to Minimize Delay</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-disconnected-windows-printer-linkup/"><u>Restoring Disconnected Windows Printer Linkup</u></a></li>
<li><a href="https://windows11.techidaily.com/recovering-from-remote-access-denied-issue/"><u>Recovering From Remote Access Denied Issue</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-ways-to-trade-pokemon-go-from-far-away-on-tecno-spark-20-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to trade pokemon go from far away On Tecno Spark 20? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-net-error-0x800704b3-on-windows-devices/"><u>Navigating Through Net Error 0X800704B3 on Windows Devices</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-in-2024-a-step-by-step-guide-on-how-to-promote-youtube-channel/"><u>New In 2024, A Step-by-Step Guide on How to Promote YouTube Channel</u></a></li>
<li><a href="https://windows11.techidaily.com/three-easy-steps-to-unlock-your-network-with-telnet-on-wins/"><u>Three Easy Steps to Unlock Your Network with Telnet on Wins</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-freeze-fixes-in-win-photoshop-setup/"><u>Navigating Freeze Fixes in Win-Photoshop Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-fixing-photography-packaging-issues-on-windows-11/"><u>Quick Guide: Fixing Photography Packaging Issues on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/methodologies-for-clearing-windows-11s-f429f-app-crashes/"><u>Methodologies for Clearing Windows 11’S F429F APP Crashes</u></a></li>
<li><a href="https://windows11.techidaily.com/prioritizing-page-notes-on-pc-windows/"><u>Prioritizing Page Notes on PC Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/tech-integration-connect-ps3-dualshock-wirelessly/"><u>Tech Integration: Connect PS3 DualShock Wirelessly</u></a></li>
<li><a href="https://windows11.techidaily.com/show-your-connection-status-update-windows-icon-bar/"><u>Show Your Connection Status: Update Windows Icon Bar</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-faceless-watchers-of-fb-flashbacks-for-2024/"><u>[New] Faceless Watchers of Fb Flashbacks for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-to-dark-modes-on-win-11-notepad/"><u>Navigate to Dark Modes on Win 11 Notepad</u></a></li>
<li><a href="https://windows11.techidaily.com/top-8-common-slip-ups-for-first-time-windows-11-enthusiasts/"><u>Top 8 Common Slip-Ups for First-Time Windows 11 Enthusiasts</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/optimize-workflow-effective-methods-of-capturing-macs-screen-via-shortcut-keys/"><u>Optimize Workflow  Effective Methods of Capturing Mac’s Screen via Shortcut Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-security-implementing-custom-pattern-locks-in-windows/"><u>Tailored Security: Implementing Custom Pattern Locks in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/removing-obstacles-in-windows-update-code-0xc004f050/"><u>Removing Obstacles in Windows Update (Code 0XC004F050)</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-continuous-credential-entry-alerts-in-os/"><u>Overcoming Continuous Credential Entry Alerts in OS</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-open-the-volume-mixer-in-windows-11/"><u>How to Open the Volume Mixer in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-self-shutdowns-steps-for-windows-11-users/"><u>Fix Self-Shutdowns: Steps for Windows 11 Users</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-investing-in-the-future-learning-to-proficiently-record-skype-calls/"><u>[New] 2024 Approved  Investing in the Future  Learning to Proficiently Record Skype Calls</u></a></li>
<li><a href="https://extra-tips.techidaily.com/making-your-mark-in-the-podcast-world-with-xml-mastery/"><u>Making Your Mark in the Podcast World with XML Mastery</u></a></li>
<li><a href="https://windows11.techidaily.com/say-farewell-to-windows-subsys-embracing-alternatives-for-android/"><u>Say Farewell to Windows Subsys: Embracing Alternatives for Android</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-launching-works-on-windows-10plus/"><u>Step-by-Step: Launching Works on WIndows 10+</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-the-process-of-disabling-windows-apps/"><u>Navigating Through the Process of Disabling Windows Apps</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/dawn-chorus-saying-good-morning-in-10-different-vernaculars/"><u>Dawn Chorus: Saying Good Morning in 10 Different Vernaculars</u></a></li>
<li><a href="https://windows11.techidaily.com/reversing-the-tide-fixing-xbox-11-stranded-app-issue/"><u>Reversing the Tide: Fixing Xbox 11 Stranded App Issue</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-can-i-get-more-stardust-in-pokemon-go-on-oppo-a1-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How can I get more stardust in pokemon go On Oppo A1 5G? | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-10-best-podcasts-microphones-for-2024/"><u>[Updated] 10 Best Podcasts Microphones for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-2024-approved-prime-techniques-converting-visual-content-on-pinterest-to-mp3s/"><u>[New] 2024 Approved  Prime Techniques  Converting Visual Content on Pinterest To MP3s</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-task-manager-not-working-in-windows/"><u>How to Fix the Task Manager Not Working in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-manage-restricted-access-and-hidden-directories-in-outlook/"><u>How to Manage Restricted Access and Hidden Directories in Outlook</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-channel-cash-flow-harnessing-youtube-ad-revenue-anywhere/"><u>[Updated] In 2024, Channel Cash Flow  Harnessing YouTube Ad Revenue Anywhere</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-obsudios-ultimate-guide-to-video-recording-with-obs/"><u>In 2024, Obsudio's Ultimate Guide to Video Recording with OBS</u></a></li>
<li><a href="https://windows11.techidaily.com/overcome-sluggishness-valorant-on-windows/"><u>Overcome Sluggishness: Valorant on Windows</u></a></li>
</ul></div>
