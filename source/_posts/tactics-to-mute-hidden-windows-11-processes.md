---
title: Tactics to Mute Hidden Windows 11 Processes
date: 2024-10-16T17:27:33.203Z
updated: 2024-10-18T22:29:17.894Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tactics to Mute Hidden Windows 11 Processes
excerpt: This Article Describes Tactics to Mute Hidden Windows 11 Processes
keywords: Muting Hidden Win11 Procs,Win11 Window Silence Tactics,Suppress Hidden OS Processes,Windows 11 Stealth Mode,Quieting Hidden Apps Win11,Noise-Free Win11 Tasks,Banish Background Win11 Proc
thumbnail: https://thmb.techidaily.com/89f58c00fabb0b3ac26622205cb1b82f67ddb2d733ca5558e5f2d4e68026f7eb.jpg
---

## Tactics to Mute Hidden Windows 11 Processes

 Background apps in Windows continue to perform actions such as updates and fetch up-to-date data even when you are not using them. While Windows can intelligently manage and power-optimize background apps, it can still drain your battery and increase data usage.

 Fortunately, Windows lets you change the background permission for individual Microsoft Store apps. Here we show you how to disable individual or all background apps in Windows 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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
<a href="https://appsumo.8odi.net/c/5597632/2144283/7443" target="_top" id="2144283">
  <img src="//a.impactradius-go.com/display-ad/7443-2144283" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144283/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. How to Disable Background Apps via Power & Battery Settings

 The Power & battery page in Windows 11 Settings provides data on the battery usage of installed apps. This is really useful If you want to disable background apps based on battery usage to save some juice.

 Here's how to do it.

1. Press **Win + X** to open the **WinX** men and select **Settings**.
2. In the **System** tab, scroll down and click on **Power & battery.**
3. Scroll down to the Battery section and click on **Battery usage.**  
![power and battery usage](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/power-and-batter-usage.png)
4. Click the drop-down for **Battery levels** and select **Last 7 days.** Windows will load all the apps using the battery power in the last seven days.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938716/19272" target="_top" id="1938716">
  <img src="//a.impactradius-go.com/display-ad/19272-1938716" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938716/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136613/26400" target="_top" id="2136613">
  <img src="//a.impactradius-go.com/display-ad/26400-2136613" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136613/26400" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2027181/19272" target="_top" id="2027181">
  <img src="//a.impactradius-go.com/display-ad/19272-2027181" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2027181/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Right-click on the **AppPrivacy** key and select **New > DWORD (32-bit) Value**. Rename the value as **LetAppsRunInBackground.**  
![registry editor create new value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/registry-editor-create-new-value.png)
7. Right-click on the **LetAppsRunInBackground** value and select **Modify**.  

![registry editor data 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/registry-editor-data-2.png)
8. Type **2** in the **Value data** field and click **OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484">
  <img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
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

5. Next, under the **Options** section, click the drop-down for **Default for all apps** and select **Force Deny**.  
![disable background app group policy editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/disable-background-app-group-policy-editor.png)
6. Click **OK** and **Apply** to save the changes.

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
<li><a href="https://extra-resources.techidaily.com/new-contrast-in-colors-crafting-cinematic-moods/"><u>[New] Contrast in Colors Crafting Cinematic Moods</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-solutions-for-enabling-audio-in-obs-broadcasts-for-2024/"><u>[New] Solutions for Enabling Audio in OBS Broadcasts for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-deciding-the-top-iphone-video-editor-cameo-or-filmorago/"><u>[Updated] 2024 Approved Deciding the Top iPhone Video Editor Cameo or FilmoraGo?</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-key-methods-to-customize-song-speed-on-spotify-for-2024/"><u>[Updated] Key Methods to Customize Song Speed on Spotify for 2024</u></a></li>
<li><a href="https://buynow-help.techidaily.com/in-depth-analysis-and-features-breakdown-why-the-garmin-forerunner-e-is-a-top-pick-for-fitness-enthusiasts/"><u>In-Depth Analysis and Features Breakdown: Why the Garmin Forerunner E Is a Top Pick for Fitness Enthusiasts</u></a></li>
<li><a href="https://screen-capture.techidaily.com/recording-your-display-essential-tips-for-effective-screen-capture/"><u>Recording Your Display Essential Tips for Effective Screen Capture</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-and-protect-win-11-edge-instalment-of-microsofts-aguard-feature/"><u>Secure and Protect Win 11 Edge: Instalment of Microsoft's Aguard Feature</u></a></li>
<li><a href="https://fox-glue.techidaily.com/spotify-how-to-halt-default-podcast-additions-for-2024/"><u>Spotify How to Halt Default Podcast Additions for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-tackling-windows-disk-errors/"><u>The Ultimate Guide to Tackling Windows Disk Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/title-perfecting-space-between-windows-widgets/"><u>Title: Perfecting Space Between Windows Widgets</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-gif-size-limits-a-guide-to-fixed-errors-in-discord-win11/"><u>Unraveling GIF Size Limits: A Guide to Fixed Errors in Discord (Win11)</u></a></li>
</ul></div>

