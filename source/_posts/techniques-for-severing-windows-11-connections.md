---
title: Techniques for Severing Windows 11 Connections
date: 2024-09-05T02:09:34.204Z
updated: 2024-09-06T02:09:34.204Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Techniques for Severing Windows 11 Connections
excerpt: This Article Describes Techniques for Severing Windows 11 Connections
keywords: Win11 Disconnect Methods,Sever W11 Links Efficiently,Cutting W11 Connections,Separate W11 Network Ties,Techniques to Break W11 Links,Dissolve Windows 11 Connexion,Disengage W11 Connectivity
thumbnail: https://thmb.techidaily.com/0838ac8f5f2d8f067138531cc9f4dfd905cfa9adb1733f1b9948bd185f0bb490.jpg
---

## Techniques for Severing Windows 11 Connections

### Quick Links

* [Sign Out Other Users Using the Task Manager](#sign-out-other-users-using-the-task-manager)
* [Sign Out Other Users Using the Command Prompt](#sign-out-other-users-using-the-command-prompt)
* [Log Off Other Users Using Process Explorer](#log-off-other-users-using-process-explorer)
* [Ask Other Users Before You Sign Them Out](#ask-other-users-before-you-sign-them-out)

### Key Takeaways

* To sign out other users on Windows 11, you can use Task Manager, Command Prompt, or Process Explorer.
* The Task Manager method works on any version of Windows, while the Command Prompt option only works for Pro and above versions of Windows. Process Explorer requires a separate download.
* Be sure to consider any unsaved work before logging off a user.

 Each active user session on your PC means your computer's resources are shared with others, which can impact system performance. If someone is not actively using their session, you can log off the idle user from your account to reclaim those system resources.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528696/16446" target="_top" id="1528696">
  <img src="//a.impactradius-go.com/display-ad/16446-1528696" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528696/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Sign Out Other Users Using the Task Manager

 The Task Manager's **Users** tab keeps track of all the user sessions active on your computer. You can use it to manage user accounts on Windows, switch between different user accounts, and sign off other user accounts. If you only need to [sign out of your current session on Windows 11](https://www.makeuseof.com/windows-11-how-to-sign-out/), the process is much simpler, though.

 You must be logged in as an administrator to sign off other user accounts; [check if your user account has administrator rights](https://www.makeuseof.com/check-windows-account-admin-rights/) if you're not sure. Importantly, when you sign out a user, the user's unsaved data might be lost. So tread carefully.

 To sign out other users using Task Manager:

1. Right-click on **Start** and select **Task Manager**. Alternatively, use the keyboard shortcut **Ctrl + Shift + Esc**.
2. In Task Manager, open the **Users** tab in the left pane which displays the number of users currently logged in. If not visible, click the **Open Navigation** button (three horizontal bars) in the top left corner.  
![Winx Menu Task Manager Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/winx-menu-task-manager-windows-11.png)
3. In the **Users** tab, locate the account you want to sign off.
4. Right-click on the user account and select **Sign off**.  
![Users Tab in Task Manager with Logoff Option in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/users-tab-in-task-manager-with-logoff-option-in-windows-11.jpg)
5. Click **Sign out user**. Windows will close all the open apps and running processes and then log out the user.

<!-- affiliate ads begin -->
<span id="1982499">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982499.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982499">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982499.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982499%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982499/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Sign Out Other Users Using the Command Prompt

 On Windows 11 Pro, Edu, and Enterprise editions, you can use Command Prompt's "query sessions" command to check and log off active user accounts. This command is unlikely to work on a Windows 11 Home, limiting your options.

 To sign out other users using Command Prompt:

1. Press the **Win** key and type **cmd**.
2. Right-click on **Command Prompt** and select **Run as administrator**.
3. In the Command Prompt window, type the following command to view all the active user sessions with a query:  
`query session`
4. The output will show all the active user sessions on your computer. Make a note of the user account **ID** you want to sign out. In this instance, we have **Tashreef** as **1** and **Guest21** as **3** under the **ID** column.  
![Command Prompt With Query Session Command Running on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/command-prompt-with-query-session-command-running-on-windows-11.jpeg)
5. Type the following command to sign out the specified user. Replace **2** below with the user account ID you want to sign out:  
`Logoff 3`
6. Upon successful execution, Windows will sign out the specified user account.  
![Command Prompt With Logoff Command Running on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/command-prompt-with-logoff-command-running-on-windows-11.jpg)
7. Once done, type **exit** and press Enter to close the Command Prompt.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006933/19272" target="_top" id="2006933">
  <img src="//a.impactradius-go.com/display-ad/19272-2006933" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006933/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<span id="1983552">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983552.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983552">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983552.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983552%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983552/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Log Off Other Users Using Process Explorer

 Process Explorer is part of [Windows Sysinternal Tools, a suite of system administration utilities](http://www.makeuseof.com/windows-sysinternals-guide/) from Microsoft. Though the freeware is popular among developers and system admins, anyone can use Process Explorer to use some of its advanced features.

 Process Explorer is a powerful tool that maps all currently active processes and DLL files to the accounts running them. Our purpose is to show you how to use its user management feature to kick out other user sessions.

1. Go to Microsoft's official [Process Explorer page](https://learn.microsoft.com/en-us/sysinternals/downloads/process-explorer) and download Process Exploreras a zip file to a location on your desktop.  
![Download Process Explorer Web Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/download-process-explorer-web-page.jpg)
2. Right-click on the **ProcessExplorer.zip** archive, and select **Extract All**. Select a location and extract the folder.  
![Process Explorer Exe File Run as Administrator Option in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-exe-file-run-as-administrator-option-in-windows-11.jpg)
3. Open the **ProcessExplorer** folder, right-click on **procexp64.exe**, and select **Run as administrator**.  
![Process Explorer App User Option Selected in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-app-user-option-selected-in-windows-11.jpg)
4. In the **Process Explorer** window, click **Users** to view all the active user sessions.  
![Process Explorer App User Account Logoff Option Selected in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/process-explorer-app-user-account-logoff-option-selected-in-windows-11.jpg)
5. Hover your cursor over the user account name and select **Logoff**.
<!-- affiliate ads begin -->
<span id="1975636">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975636.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975636">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975636.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975636%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975636/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Process Explorer will sign out the selected user account from your computer. If you get an [access denied error](https://www.makeuseof.com/windows-11-fix-access-denied-error/), run the procexp64.exe executable with administrator privileges and try again.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948909/19272" target="_top" id="1948909">
  <img src="//a.impactradius-go.com/display-ad/19272-1948909" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948909/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Ask Other Users Before You Sign Them Out

 When you log off other users, any unsaved work in their accounts is lost. So do consider that before you apply the above methods. Logging off from a Windows account in a multi-user PC is a good habit because it reduces the chance of data loss and frees up the computer's resources for others. Always request others to sign off when their work is finished.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://desktop-recording.techidaily.com/new-making-an-informed-decision-on-itops-utility/"><u>[New] Making an Informed Decision on ITop's Utility?</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-the-ultimate-guide-to-selecting-screen-recorder-software/"><u>[New] The Ultimate Guide to Selecting Screen Recorder Software</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/approved-flashglimpse-crafter/"><u>2024 Approved  FlashGlimpse Crafter</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/360-camera-buying-guide-how-to-choose-a-suitable-360-camera-2023-update/"><u>360 Camera Buying Guide  How to Choose a Suitable 360 Camera -2023 Update</u></a></li>
<li><a href="https://tech-revival.techidaily.com/discover-the-leading-6-ai-applications-revolutionizing-your-note-taking-experience/"><u>Discover the Leading 6 AI Applications Revolutionizing Your Note-Taking Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-guide-ripping-audio-cds-successfully-with-your-windows-pc/"><u>Easy Guide: Ripping Audio CDs Successfully with Your Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/end-of-windows-10-maintenance-in-year-exploring-alternative-os-choices/"><u>End of Windows 10 Maintenance in [Year]: Exploring Alternative OS Choices</u></a></li>
<li><a href="https://windows11.techidaily.com/enhanced-sound-mastery-with-microsofts-updated-clipchamp-software/"><u>Enhanced Sound Mastery with Microsoft's Updated Clipchamp Software</u></a></li>
<li><a href="https://windows11.techidaily.com/evaluating-the-portable-razer-usb-c-hub-essential-insights-for-mobile-gaming-enthusiasts/"><u>Evaluating the Portable Razer USB-C Hub: Essential Insights for Mobile Gaming Enthusiasts</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-exceptional-no-cost-creativity-suites-as-the-optimal-substitutes-for-adobe-in-future-artistic-ventures/"><u>Exploring Exceptional No-Cost Creativity Suites as the Optimal Substitutes for Adobe in Future Artistic Ventures</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-contacts-from-xiaomi-redmi-k70-pro-by-fonelab-android-recover-contacts/"><u>How to Rescue Lost Contacts from Xiaomi Redmi K70 Pro?</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-circle-everything-you-need-to-know-on-vivo-y55s-5g-2023-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Circle Everything You Need to Know On Vivo Y55s 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/key-indicators-that-show-your-laptop-needs-replacement-now/"><u>Key Indicators That Show Your Laptop Needs Replacement Now</u></a></li>
<li><a href="https://windows11.techidaily.com/left-side-arrangement-organizing-windows-11-taskbar-icons/"><u>Left-Side Arrangement: Organizing Windows 11 Taskbar Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/lenovo-legion/"><u>Lenovo Legion</u></a></li>
<li><a href="https://extra-skills.techidaily.com/mastering-the-art-of-vector-imagery-best-10-sources-for-2024/"><u>Mastering the Art of Vector Imagery  Best 10 Sources for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-performance-8-must-do-tasks-following-the-acquisition-of-a-new-windows-computer/"><u>Maximizing Performance: 8 Must-Do Tasks Following the Acquisition of a New Windows Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/revamping-the-boring-windows-terminal-into-a-stylish-command-hub/"><u>Revamping the Boring Windows Terminal Into a Stylish Command Hub</u></a></li>
<li><a href="https://windows11.techidaily.com/say-goodbye-to-netflix-download-functionality-for-desktop-upcoming-changes-explained/"><u>Say Goodbye to Netflix Download Functionality for Desktop: Upcoming Changes Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-12-improvements-for-a-future-release-what-users-hope-for-from-windows-12/"><u>The Essential 12 Improvements for a Future Release: What Users Hope For From Windows 12</u></a></li>
<li><a href="https://windows11.techidaily.com/the-nearly-complete-windows-11-update-for-2amz-may-2024-innovations-and-features-ahead/"><u>The Nearly Complete Windows 11 Update for 2Amz, May 2024: Innovations and Features Ahead!</u></a></li>
<li><a href="https://fox-blue.techidaily.com/top-10-best-action-cameras-for-diving-or-snorkelling-2023-update-for-2024/"><u>Top 10 Best Action Cameras For Diving Or Snorkelling -2023 Update for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-techniques-for-resolving-memory-corruption-issues-in-windows-11/"><u>Top 5 Techniques for Resolving Memory Corruption Issues in Windows 11</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/unveil-the-potential-of-instagram-footage-comprehensive-guide-to-mp4-conversion-software-windowsosx/"><u>Unveil the Potential of Instagram Footage  Comprehensive Guide to MP4 Conversion Software [Windows/OSX]</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-microsofts-new-surface-laptop-6-exclusive-release-with-no-retail-availability/"><u>Unveiling Microsoft's New Surface Laptop 6: Exclusive Release with No Retail Availability</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-solutions-resolving-the-visibility-issue-of-your-freshly-installed-hard-drive-on-windows/"><u>Unveiling Solutions: Resolving the Visibility Issue of Your Freshly Installed Hard Drive on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/weekly-tech-highlights-anticipating-the-upcoming-innovations-from-google-and-samsungs-new-handsets/"><u>Weekly Tech Highlights: Anticipating the Upcoming Innovations From Google & Samsung's New Handsets</u></a></li>
<li><a href="https://windows11.techidaily.com/why-does-my-windows-desktoplaptop-turn-off-unexpectedly-discover-the-top-8-causes/"><u>Why Does My Windows Desktop/Laptop Turn Off Unexpectedly? Discover the Top 8 Causes</u></a></li>
<li><a href="https://windows11.techidaily.com/why-microsofts-copilotplus-and-its-advanced-upscaling-technology-make-it-essential-gear-for-serious-gamers/"><u>Why Microsoft's CoPilot+ and Its Advanced Upscaling Technology Make It Essential Gear for Serious Gamers</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-upgrades-simplified-step-by-step-instructions-for-keeping-your-software-current/"><u>Windows 11 Upgrades Simplified: Step-by-Step Instructions for Keeping Your Software Current</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>