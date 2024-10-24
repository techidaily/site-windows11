---
title: Uncovering the Invisible Workers in Win11
date: 2024-10-23T16:31:46.524Z
updated: 2024-10-24T18:07:56.903Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Uncovering the Invisible Workers in Win11
excerpt: This Article Describes Uncovering the Invisible Workers in Win11
keywords: Win11 Hidden Labor,Beneath Win11 Workforce,Windows Core Staff,Win11 Unseen Contributors,Understated Win11 Users,Inside Win11 Team,Secret Win11 Helpers
thumbnail: https://thmb.techidaily.com/7ac9924553405319fc34adce73b50933080c4e0b7ab947e877cf6636c606146d.jpg
---

## Uncovering the Invisible Workers in Win11

 Background apps in Windows continue to perform actions such as updates and fetch up-to-date data even when you are not using them. While Windows can intelligently manage and power-optimize background apps, it can still drain your battery and increase data usage.

 Fortunately, Windows lets you change the background permission for individual Microsoft Store apps. Here we show you how to disable individual or all background apps in Windows 11\.

## 1\. How to Disable Background Apps via the Settings App

 If you want to disable individual Microsoft Store apps from running in the background, you can disable it from the Settings page. Follow the below steps to disable background apps from Settings.

1. Press **Win + I** to open the **Settings** app.
2. Open the **Apps** tab in the left pane.
3. Click on **Installed apps** in the right pane and search to locate the app for which you want to change the background permission.
4. Click the **three-dots menu** icon next to the app name and select **Advanced options.** If the option is not available, then the app does not support the background app permission management feature.  
![advanced options windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/advanced-options-windows-11-settings.jpg)
5. Scroll down to the **Background apps permissions** section.  
![background app permission never](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/background-app-permission-never.png)
6. Click the drop-down for **Let this app run in background** and select **Never**. This should disable the app from running in the background.

 By default, the background permission for the app is set to **Power optimized(recommended)**. This means Windows will decide when the app can run in the background to save more power. If you set it to **Always**, the app will continuously run in the background irrespective of your power status.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037474/7443" target="_top" id="2037474">
  <img src="//a.impactradius-go.com/display-ad/7443-2037474" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037474/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. How to Disable Background Apps via Power & Battery Settings

 The Power & battery page in Windows 11 Settings provides data on the battery usage of installed apps. This is really useful If you want to disable background apps based on battery usage to save some juice.

 Here's how to do it.

1. Press **Win + X** to open the **WinX** men and select **Settings**.
2. In the **System** tab, scroll down and click on **Power & battery.**
3. Scroll down to the Battery section and click on **Battery usage.**  
![power and battery usage](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/power-and-batter-usage.png)
4. Click the drop-down for **Battery levels** and select **Last 7 days.** Windows will load all the apps using the battery power in the last seven days.  
![manage background activity](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/manage-background-activity.png)
5. To change the background app permission, click the **three-dots menu** beside the app name, and click on **Manage background productivity**. This option is only available for Microsoft Store apps.
6. Click the **drop-down** (**Power optimized**) under the **Background apps permissions** section and select **Never**. This will disable the app from running in the background.
7. Repeat the steps for all the apps that can drain your battery or affect system performance.

 In addition to disabling background apps, try to create and use [custom Windows power plans to extend your laptop battery life](https://www.makeuseof.com/tag/save-energy-extend-battery-life-custom-windows-power-plans/). With custom power plans, you can tweak your processor and other components to configure low-power modes to achieve an improved battery life.

## 3\. How to Disable Background Apps for the Current User

 If you want, you can disable background apps for the individual user. Useful if you share your PC with multiple users at work or home. Also useful if you need to disable a non-Microsoft third-party app from running in the background.

 For this, you will need to create a registry file and run it with administrative privilege. Before you proceed, [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/). You can use the restore point to revert your PC to its previous state if something goes wrong when editing the registry entries.

 To disable background apps for the current user:

1. Press **Win + R** to open the **Run** dialog.
2. Type **notepad** and click **OK** to open the text editor app.  
![disable background apps windows 11 registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/disable-background-apps-windows-11-registry-editor.jpg)
3. In the Notepad file, copy and paste the following content:  
`Windows Registry Editor Version 5.00  

[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\BackgroundAccessApplications]  
"GlobalUserDisabled"=dword:00000001  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Search]  
"BackgroundAppGlobalToggle"=dword:00000000`
4. Next, press **Win + S** to open the **Save** dialog.
5. Here, name the file as **Disable\_Background\_Apps\_for\_current\_user.reg**. Then, click the **Save as type** drop-down and select **All Files.**  
![disable background apps windows 11 registry editor save](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/disable-background-apps-windows-11-registry-editor-save.jpg)
6. Click the **Save** button to save the file.
7. Right-click on the newly created reg file and select **Open.** Click **Yes** to confirm and modify the registry entries to disable background apps.
8. If the script runs without error, restart your PC to apply the changes.

 The above script modifies the two DWORD values, **GlobalUserDisabled** and **BackgroundAppGlobalToggle,** setting them to **1** and **0**, respectively. Modifying the GlobalUserDisabled value prevents background access to applications.

 Similarly, changes to the BackgroundAppGlobalToggle turn off the toggle for background apps in Windows search, thus limiting its background access.

 If you need to turn on background apps for the current user, then save the following script as **enable\_background\_apps.reg** and run it as administrator.

![reg file content background app disable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/reg-file-content-background-app-disable.png)

`Windows Registry Editor Version 5.00  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\BackgroundAccessApplications]  
"GlobalUserDisabled"=-  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Search]  
"BackgroundAppGlobalToggle"=-`

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484939/16446" target="_top" id="1484939">
  <img src="//a.impactradius-go.com/display-ad/16446-1484939" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484939/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. How to Disable Background Apps for All Users Using Registry Editor

 If you want to disable background apps for all the user accounts, you can manually create and modify the registry values in the Registry Editor.

 To disable background apps for all the user accounts:

1. Press **Win + R** to open **Run**.
2. Type **regedit**, and click **OK**. Click **Yes** to grant administrative access.
3. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows`
4. Under the **Windows** key, locate the **AppPrivacy** key**.** If not available, you will need to create a new key.  
![registry editor create new key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/registry-editor-create-new-key.png)
5. Right-click on the **Windows** key and select **New > Key.** Rename the key as **AppPrivacy.**
6. Right-click on the **AppPrivacy** key and select **New > DWORD (32-bit) Value**. Rename the value as **LetAppsRunInBackground.**  
![registry editor create new value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/registry-editor-create-new-value.png)
7. Right-click on the **LetAppsRunInBackground** value and select **Modify**.  
![registry editor data 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/registry-editor-data-2.png)
8. Type **2** in the **Value data** field and click **OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896532/19272" target="_top" id="1896532">
  <img src="//a.impactradius-go.com/display-ad/19272-1896532" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896532/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

9. Close the Registry Editor and restart your PC to apply the changes.

 This should disable Microsoft Store apps from running in the background. To enable the background apps, modify the **LetAppsRunInBackground** value and set it to **0**.

## 5\. How to Disable Background Apps Using the Group Policy Editor

 Alternatively, you can also use the Group Policy Editor to configure background apps settings on your computer network. This is useful for system administrators having to configure multiple systems.

 Note that Group Policy Editor is officially only available in the Pro, Education, and Enterprise editions of the Windows OS. If you are on Home, read our guide on [how to enable Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). This involves a registry hack to enable the missing functionality in the Home edition of the OS.

 Once you have the policy editor up and running, continue with the steps below. To disable background apps using Group Policy Editor:

1. Press the **Win key**, type **group policy**, and click on **Edit group policy** from the search results.
2. In the Group Policy Editor, navigate to the following location:  
`Computer Configuration\Administrative Templates\Windows Components\App Privacy​`
3. In the right pane, locate and double-click on **Let Windows apps run in the background** policy.  
![disable background app group policy editor policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/disable-background-app-group-policy-editor-policy.png)
4. In the new window that appears, select **Enabled**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2132162/7443" target="_top" id="2132162">
  <img src="//a.impactradius-go.com/display-ad/7443-2132162" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2132162/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Next, under the **Options** section, click the drop-down for **Default for all apps** and select **Force Deny**.  
![disable background app group policy editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/disable-background-app-group-policy-editor.png)
6. Click **OK** and **Apply** to save the changes.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938721/19272" target="_top" id="1938721">
  <img src="//a.impactradius-go.com/display-ad/19272-1938721" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938721/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Alternatively, you can set the Let Windows apps run in the background policy to **Disabled** and apply the changes. However, when set to **Disabled** or **Not Configured**, individual employees in your organization can configure the apps to run in the background.

 On the contrary, setting this policy to **Force Deny** will prevent the app from running in the background, with no option for the employees to change the policy.

## Disabling Background Apps in Windows 11

 Windows allows you to configure background app permission for the Microsoft Store apps. You can disable these apps to conserve battery and avoid unnecessary data usage on a metered connection.

 That said, if you are struggling with slow system performance issues, disabling background apps may not be the solution. What you can do instead is reconfigure your OS, analyze your storage devices and look for hardware upgrades to boost system performance.

 Fortunately, Windows lets you change the background permission for individual Microsoft Store apps. Here we show you how to disable individual or all background apps in Windows 11\.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-blue.techidaily.com/new-master-the-art-of-attraction-secrets-to-viral-tiktok-unboxing-content/"><u>[New] Master the Art of Attraction Secrets to Viral TikTok Unboxing Content</u></a></li>
<li><a href="https://windows11.techidaily.com/9-ways-to-fix-the-0x8004def5-onedrive-error-code-on-windows-11/"><u>9 Ways to Fix the 0X8004def5 OneDrive Error Code on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-windows-11-stumbling-blocks-the-most-crucial-tips/"><u>Avoiding Windows 11 Stumbling Blocks: The Most Crucial Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-clutter-software-uninstallation-tricks-for-windows-11-106-chars/"><u>Eliminating Clutter: Software Uninstallation Tricks for Windows 11 (106 Chars)</u></a></li>
<li><a href="https://win-blog.techidaily.com/expert-advice-on-how-to-stop-chivalry-ii-from-freezing-or-crashing/"><u>Expert Advice on How to Stop Chivalry II From Freezing or Crashing</u></a></li>
<li><a href="https://hardware-help.techidaily.com/exploring-hardware-with-tom-in-depth-analysis-of-pc-specs-and-setup/"><u>Exploring Hardware with Tom: In-Depth Analysis of PC Specs and Setup</u></a></li>
<li><a href="https://win-answers.techidaily.com/four-effective-ways-to-bypass-blocked-torrent-sites-and-regain-access/"><u>Four Effective Ways to Bypass Blocked Torrent Sites & Regain Access</u></a></li>
<li><a href="https://windows11.techidaily.com/get-ahead-in-passwords-7-best-free-generation-tools-for-windows/"><u>Get Ahead in Passwords: 7 Best Free Generation Tools for Windows</u></a></li>
<li><a href="https://fox-useful.techidaily.com/guide-simple-methods-to-enjoy-and-excel-at-army-commander-on-pc/"><u>Guide: Simple Methods to Enjoy and Excel at Army Commander on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/simplified-guide-to-shift-your-qbittorrent-installation/"><u>Simplified Guide to Shift Your qBittorrent Installation</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-your-unresponsive-dns-quick-and-effective-solutions/"><u>Troubleshoot Your Unresponsive DNS: Quick & Effective Solutions!</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unlock-the-secrets-of-high-quality-gopro-vlogging-for-2024/"><u>Unlock the Secrets of High-Quality GoPro Vlogging for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-power-of-dism-in-win11-image-management/"><u>Unveiling the Power of Dism in Win11 Image Management</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/unveiling-the-power-of-the-fujitsu-scansnap-ix1600-a-review-for-efficient-office-document-handling/"><u>Unveiling the Power of the Fujitsu ScanSnap iX1600: A Review for Efficient Office Document Handling</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-video-editing-on-a-shoestring-16-free-and-intuitive-movie-makers/"><u>Updated Video Editing on a Shoestring 16 Free and Intuitive Movie Makers</u></a></li>
<li><a href="https://windows11.techidaily.com/why-task-managers-feature-extras-under-edge/"><u>Why Task Managers Feature Extras Under Edge?</u></a></li>
<li><a href="https://windows11.techidaily.com/zeroing-out-bloatware-windows-11-edition/"><u>Zeroing Out Bloatware: Windows 11 Edition</u></a></li>
</ul></div>

