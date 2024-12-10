---
title: Streamline Menu Navigation by Omitting Windows 11 Extras
date: 2024-12-05T16:30:10.555Z
updated: 2024-12-10T16:07:55.249Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Streamline Menu Navigation by Omitting Windows 11 Extras
excerpt: This Article Describes Streamline Menu Navigation by Omitting Windows 11 Extras
keywords: Simplify Menu Streamlining,Reduce W11 Add-Ons,Optimize UI Layouts,Clean Menu Navigation,Minimize Windows Extras,Enhance Menu Clarity,Eliminate Unnecessary Features
thumbnail: https://thmb.techidaily.com/2f486f4dd87aa179d36ac9cfba84a9e655bb2170ba42ee253c3df8a8c92937c0.jpg
---

## Streamline Menu Navigation by Omitting Windows 11 Extras

 Windows 11 comes with a fresh new look and has mainly got a positive response for its new interface. However, there are a couple of features that are not being welcomed by the users. For instance, the addition of the "show more options" entry to the right-click context menu.

 Although it was introduced to simplify things, many users still prefer the old context menu from Windows 10\. Fortunately, you can remove Show more options from the context menu on Windows 11 by following the below methods.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0pSRlspzW-A?si=A82G3Yxwj_31cKDq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Remove "Show More Options" From the Context Menu With Folder Options

 The[Windows Folder Options](https://www.makeuseof.com/windows-folder-options-guide/) in File Explorer is the go-to place to view and manage File Explorer settings. You can use it to[enable compact view in File Explorer on Windows 11](https://www.makeuseof.com/how-to-enable-compact-view-windows-11-file-explorer/) , manage file thumbnails, remove the "show more options" entry, and much more.

 Here's how to use the folder option to remove the "show more options" entry from the context menu:

1. Press the**Win + E** hotkey to open the**File Explorer.**
2. Click the three horizontal dots at the top bar and choose**Options.**
3. In the**Folder Options,** switch to the**View** tab.
4. Check the**Launch folder** **windows in a separate process** box.  
![Launch folder windows in a separate process box in the Folder option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/launch-folder-windows-in-a-separate-process-box.jpg)
5. Click**Apply** \>**OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oP8grXxuy2o?si=uIRNhTYbecTcaC7J" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Next, restart your computer for the changes to take effect.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YwOwUI47FuU?si=NK7IEELjx7_SJSl2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Remove Show More Options From the Context Menu Using the Command Prompt

 If you're a power user, you can use Command Prompt to remove the "show more options" entry from the context menu. Here's how:

1. Open the**Start Menu** by pressing the**Win** key.
2. In the search bar, type**Command Prompt** and choose**Run as administrator** from the right pane.
3. Click**Yes** to the UAC that crops up.
4. In the elevated Command Prompt window, type the following command and press**Enter** :  
`reg add "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f /ve`

![Command to Remove Context menu in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/command-to-remove-context-menu.jpg)

 After executing the command, you'll see the "The operation completed successfully" message to confirm that it went through.

 Now, you will have to restart Windows Explorer to see the changes. To do that, open the**Task Manager** (see how to[launch the Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) ), right-click on**Windows Explorer,** and choose**Restart.**

 Check if you can see the changes. If not, then you will have to restart your computer for the changes to take effect.

 In the future, if you want to add the "show more options" entry to the context menu, then open Command Prompt with admin rights and run the following command:

`reg delete "HKEY_CURRENT_USER\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}" /f​`

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_SbYznUy_zY?si=ThBkP934r3mizi48" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Remove Show More Options From the Context Menu Using the Registry Editor

 Another quick way to remove the "show more options" entry is through the Registry Editor. Here's what you need to do:

 Before making any changes to the registry, ensure you've[created a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) or[back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . This will ensure your system settings and files are secure, and you can quickly access them if something goes wrong.

1. Open the Start Menu, type**Registry Editor** in the search bar, and press Enter.
2. In the Registry Editor, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID`
3. Right-click on the empty space on the right pane, click**New,** and then select**DWORD** **(32-bit) Value** from the context menu.
4. Name the value as**"UndockingDisabled"** and press**Enter** .  
![UndockingDisabled entry in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/undockingdisabled-entry.jpg)
5. Double-click on the UndockingDisabled key, type**1** in the**Value data,** and click**OK** to save the changes.  
![Editing UndockingDisabled in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/editing-undockingdisabled.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PKZUYice-ws?si=L8iMa9T3h7TMSWdQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Remove the "Show More Options" Entry From the Context Menu Using Winaero Tweaker

 There are plenty of third-party tools using which you can customize the look of your Windows 11 computer. For this guide, we will use Winaero Tweaker.

 Here's how to download Winaero Tweaker and use it to remove the "show more options" entry from the context menu:

1. Download the[Winaero Tweaker zip file](https://winaero.com/downloads/winaerotweaker.zip) on your computer.
2. Unzip the file, open the executable, and then follow the on-screen instructions to install it on your computer.
3. Launch Winaero Tweaker and choose the**Classic Full Context Menus** option from the left sidebar.  
![Classic Full Context Menus option of Winaero](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/classic-full-context-menus-option.jpg)
4. Check the**Enable classic full context menus** box.  
![Enable classic full context menus option in Winaero](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-classic-full-context-menus.jpg)
5. Click the**Restart Explorer** button that appears.

## Enjoy an Old School Context Menu on Windows 11

 The desktop context menu lets you quickly access areas like the personalization menu, display settings, and much more. In Windows 11, you get the new "Show more options" entry in the context menu. But if you prefer the old design, you can quickly disable the "Show more options" entry from the context using either of the above methods.

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
<li><a href="https://windows11.techidaily.com/how-to-overcome-repetitive-login-failures-in-teams/"><u>How to Overcome Repetitive Login Failures in Teams</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-show-or-hide-system-tray-icons-and-the-hidden-icons-menu-on-windows-11/"><u>How to Show or Hide System Tray Icons and the Hidden Icons Menu on Windows 11</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-time-saving-tricks-for-powerpoint-projections/"><u>In 2024, Time-Saving Tricks for PowerPoint Projections</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-oppo-reno-11f-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Why Your WhatsApp Location is Not Updating and How to Fix On Oppo Reno 11F 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/instant-internet-jump-after-installing-os/"><u>Instant Internet Jump After Installing OS</u></a></li>
<li><a href="https://facebook.techidaily.com/invisible-framework-social-norms-in-friend-requesting/"><u>Invisible Framework: Social Norms in Friend Requesting</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-windows-for-top-linux-functionality/"><u>Leveraging Windows for Top Linux Functionality</u></a></li>
<li><a href="https://tech-haven.techidaily.com/maximizing-ipad-output-discover-key-apps-to-enhance-productivity-and-workflow-as-recommended-experts/"><u>Maximizing iPad Output? Discover Key Apps to Enhance Productivity and Workflow as Recommended Experts</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-mac-video-editing-software-for-industry-experts-adobe-premiere-pro/"><u>New In 2024, Mac Video Editing Software for Industry Experts Adobe Premiere Pro</u></a></li>
<li><a href="https://data-wizards.techidaily.com/patched-reel-error-on-instagram/"><u>Patched: Reel Error on Instagram</u></a></li>
<li><a href="https://windows11.techidaily.com/personalizing-window-writable-wallpaper-with-confidence/"><u>Personalizing Window' Writable Wallpaper with Confidence</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-network-adapter-woes-clearing-up-win-error-31/"><u>Tackling Network Adapter Woes: Clearing Up WIN Error 31</u></a></li>
<li><a href="https://windows11.techidaily.com/the-best-way-to-play-ps1-games-on-windows-a-duckstation-guide/"><u>The Best Way to Play PS1 Games on Windows: A Duckstation Guide</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/unlock-your-phones-potential-with-ios-11-camera-tips-for-2024/"><u>Unlock Your Phone's Potential with iOS 11 Camera Tips for 2024</u></a></li>
<li><a href="https://win-excellent.techidaily.com/windows-serverqnap-nas/"><u>Windows Server到QNAP NAS的簡單兩步驟備份方法：全面解決方案</u></a></li>
<li><a href="https://program-issues.techidaily.com/zombie-army-4-dead-war-a-survival-guide-for-pc-gaming-troubleshooting/"><u>Zombie Army 4: Dead War - A Survival Guide for PC Gaming Troubleshooting</u></a></li>
</ul></div>

