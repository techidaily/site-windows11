---
title: Discreetly Putting an End to Invisible Window Tasks
date: 2024-08-15T16:05:00.433Z
updated: 2024-08-16T16:05:00.433Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Discreetly Putting an End to Invisible Window Tasks
excerpt: This Article Describes Discreetly Putting an End to Invisible Window Tasks
keywords: Ending Hidden Tasks,Discrete Task Resolution,Eliminate Stealth Chores,Concealed Work Fixation,Silent Task Eradication,Invisible Task Cessation,Quietly Ceasing Ops
thumbnail: https://thmb.techidaily.com/8710795f69b6885ee183c5bcebd20dd5644a88070a4884d479fae689522aa348.jpg
---

## Discreetly Putting an End to Invisible Window Tasks

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
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. How to Disable Background Apps via Power & Battery Settings

 The Power & battery page in Windows 11 Settings provides data on the battery usage of installed apps. This is really useful If you want to disable background apps based on battery usage to save some juice.

 Here's how to do it.

1. Press **Win + X** to open the **WinX** men and select **Settings**.
2. In the **System** tab, scroll down and click on **Power & battery.**
3. Scroll down to the Battery section and click on **Battery usage.**  
![power and battery usage](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/power-and-batter-usage.png)
<!-- affiliate ads begin -->
<a href="https://uperfect.sjv.io/c/5597632/1246754/15155" target="_top" id="1246754"><img src="//a.impactradius-go.com/display-ad/15155-1246754" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1246754/15155" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Click the drop-down for **Battery levels** and select **Last 7 days.** Windows will load all the apps using the battery power in the last seven days.  
![manage background activity](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/manage-background-activity.png)
5. To change the background app permission, click the **three-dots menu** beside the app name, and click on **Manage background productivity**. This option is only available for Microsoft Store apps.
6. Click the **drop-down** (**Power optimized**) under the **Background apps permissions** section and select **Never**. This will disable the app from running in the background.
7. Repeat the steps for all the apps that can drain your battery or affect system performance.

 In addition to disabling background apps, try to create and use [custom Windows power plans to extend your laptop battery life](https://www.makeuseof.com/tag/save-energy-extend-battery-life-custom-windows-power-plans/). With custom power plans, you can tweak your processor and other components to configure low-power modes to achieve an improved battery life.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Click the **Save** button to save the file.
7. Right-click on the newly created reg file and select **Open.** Click **Yes** to confirm and modify the registry entries to disable background apps.
8. If the script runs without error, restart your PC to apply the changes.

 The above script modifies the two DWORD values, **GlobalUserDisabled** and **BackgroundAppGlobalToggle,** setting them to **1** and **0**, respectively. Modifying the GlobalUserDisabled value prevents background access to applications.

 Similarly, changes to the BackgroundAppGlobalToggle turn off the toggle for background apps in Windows search, thus limiting its background access.

 If you need to turn on background apps for the current user, then save the following script as **enable\_background\_apps.reg** and run it as administrator.

![reg file content background app disable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/reg-file-content-background-app-disable.png)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

`Windows Registry Editor Version 5.00  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\BackgroundAccessApplications]  
"GlobalUserDisabled"=-  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Search]  
"BackgroundAppGlobalToggle"=-`

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
9. Close the Registry Editor and restart your PC to apply the changes.

 This should disable Microsoft Store apps from running in the background. To enable the background apps, modify the **LetAppsRunInBackground** value and set it to **0**.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://fox-helps.techidaily.com/new-in-2024-discovering-vr-a-concise-explanation-for-all/"><u>[New] In 2024, Discovering VR  A Concise Explanation for All</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-capture-every-detail-advanced-skype-calls-recording-methods/"><u>2024 Approved  Capture Every Detail  Advanced Skype Calls Recording Methods</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-premium-extensions-catalog-ae-edition/"><u>2024 Approved  Premium Extensions Catalog  AE Edition</u></a></li>
<li><a href="https://android-unlock.techidaily.com/a-complete-guide-to-oem-unlocking-on-lava-storm-5g-by-drfone-android/"><u>A Complete Guide To OEM Unlocking on Lava Storm 5G</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/affordable-chill-expert-analysis-of-uphere-c5c-and-d6sec-portable-ac-units/"><u>Affordable Chill: Expert Analysis of UpHere C5C and D6Sec Portable A/C Units</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-fixes-for-windows-updates-failure-at-errors-0xc1900101/"><u>Essential Fixes for Windows Updates Failure at Errors 0xC1900101</u></a></li>
<li><a href="https://techtrends.techidaily.com/essential-tips-to-address-helperdll-cant-be-found-mistake/"><u>Essential Tips to Address Helper.dll Can't Be Found Mistake</u></a></li>
<li><a href="https://tech-revival.techidaily.com/experience-a-paradigm-shift-openai-debuts-transformative-gpt-4-ai-model/"><u>Experience a Paradigm Shift: OpenAI Debuts Transformative GPT-4 AI Model</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-create-a-linux-virtual-machine-inside-a-windows-virtual-machine-using-hyper-v/"><u>How to Create a Linux Virtual Machine Inside a Windows Virtual Machine Using Hyper-V</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/how-to-downloadsave-instagram-reels-video-in-2-ways-for-2024/"><u>How to Download/Save Instagram Reels Video in 2 Ways for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-overcome-new-cell-placement-hurdles-in-excel-widows/"><u>How to Overcome New Cell Placement Hurdles in Excel Widows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reestablish-windows-steam-connections/"><u>How to Reestablish Windows-Steam Connections</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-stop-windows-from-automatically-locking-itself/"><u>How to Stop Windows From Automatically Locking Itself</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-realme-c53-to-mac-drfone-by-drfone-android/"><u>In 2024, How to Mirror Realme C53 to Mac? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/innovative-password-solutions-7-best-wins-for-windows-users/"><u>Innovative Password Solutions: 7 Best Wins for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/leading-the-pack-best-windows-11-for-fps-tracking/"><u>Leading the Pack: Best Windows 11 for FPS Tracking</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-directdraw-repair-techniques-on-the-latest-version-of-windows/"><u>Mastering DirectDraw Repair Techniques on the Latest Version of Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11s-security-with-rufus-expertise/"><u>Navigating Windows 11'S Security with Rufus Expertise</u></a></li>
<li><a href="https://windows11.techidaily.com/optimized-development-space-unveiling-the-potential-of-devs-on-win11/"><u>Optimized Development Space: Unveiling the Potential of Devs on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-microsoft-store-glitch-0x80073d26-in-win11/"><u>Overcoming Microsoft Store Glitch 0X80073D26 in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/picking-between-google-and-windows-file-sharing-technologies/"><u>Picking Between Google and Windows File Sharing Technologies</u></a></li>
<li><a href="https://driver-install.techidaily.com/premium-audio-device-from-amd/"><u>Premium Audio Device From AMD</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-cure-for-flickering-screens-on-windows-11-pcs/"><u>Quick Cure for Flickering Screens on Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-to-stop-steam-from-halting-games-on-windows-11/"><u>Quick Fixes to Stop Steam From Halting Games on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-resetting-and-restoring-search-on-windows-11-settings-ui/"><u>Quick Fixes: Resetting and Restoring Search on Windows 11 Settings UI</u></a></li>
<li><a href="https://windows11.techidaily.com/reimagine-windows-look-using-chosen-pics/"><u>Reimagine Window's Look Using Chosen Pics</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-classics-playing-oldschool-games-with-dosbox-x/"><u>Reviving Classics: Playing Oldschool Games with DOSBox-X</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-your-desktops-background-stability/"><u>Securing Your Desktop's Background Stability</u></a></li>
<li><a href="https://windows11.techidaily.com/silence-automatic-spotify-launch-in-windows/"><u>Silence Automatic Spotify Launch in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-adjust-standard-user-permissions-in-windows/"><u>Steps to Adjust Standard User Permissions in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-screen-space-challenges-in-games/"><u>Tackling Screen Space Challenges in Games</u></a></li>
<li><a href="https://windows11.techidaily.com/tactical-plan-to-vanquish-wows-deadly-error-132-in-osxwin/"><u>Tactical Plan to Vanquish WoW's Deadly Error #132 in OSX/Win</u></a></li>
<li><a href="https://windows11.techidaily.com/tailor-your-media-select-from-top-8-video-editing-titles-for-windows/"><u>Tailor Your Media - Select From Top 8 Video Editing Titles for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-beginners-guide-to-the-windows-11-calendar/"><u>The Beginner's Guide to the Windows 11 Calendar</u></a></li>
<li><a href="https://windows11.techidaily.com/the-complete-guide-to-windows-11-personalization/"><u>The Complete Guide to Windows 11 Personalization</u></a></li>
<li><a href="https://windows11.techidaily.com/the-compreenas-guide-for-streamlining-windows-esd-transformation-to-an-iso/"><u>The Compreenas Guide for Streamlining Windows' ESD Transformation to an ISO</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-easy-paths-to-windows-help-and-hands-on-center/"><u>The Easy Paths To Windows Help and Hands-On Center</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/the-essential-guide-to-efficient-youtube-follow-link-design/"><u>The Essential Guide to Efficient YouTube Follow Link Design</u></a></li>
<li><a href="https://windows11.techidaily.com/the-path-to-successful-python-server-implementation-on-windows/"><u>The Path to Successful Python Server Implementation on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/top-4-password-protectors-for-a-secure-windows-11-journey/"><u>Top 4 Password Protectors for a Secure Windows 11 Journey</u></a></li>
<li><a href="https://win-answers.techidaily.com/total-war-warhammer-3-update-eliminating-pc-game-interrupts-and-ensuring-stability/"><u>Total War: WARHAMMER 3 Update: Eliminating PC Game Interrupts & Ensuring Stability</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-inaccurate-power-estimator-on-windows-11-desktops/"><u>Troubleshooting Inaccurate Power Estimator on Windows 11 Desktops</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-steam-cloud-glitch-on-windows/"><u>Troubleshooting Steam Cloud Glitch on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/turbocharge-storage-space-with-win11-defrag-guide/"><u>Turbocharge Storage Space with Win11 Defrag Guide</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/unlock-the-full-potential-of-skype-written-in-spanish-but-not-widely-known-among-english-speakers-it-was-used-as-a-basis-for-creating-new-models-like-bert-a/"><u>Unlock the Full Potential of Skype’ Written in Spanish, but Not Widely Known Among English Speakers. It Was Used as a Basis for Creating New Models Like BERT and GPT-3. How Can I Access This Model? Is It Free to Use?</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-power-of-testing-enable-sandbox-in-win-11/"><u>Unlocking the Power of Testing: Enable Sandbox in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-leaderboard-game-lol/"><u>Unlocking Windows Leaderboard Game (LOL)</u></a></li>
<li><a href="https://windows11.techidaily.com/update-user-folder-names-with-ease-on-win11/"><u>Update User Folder Names with Ease on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/upgrade-windows-11-notebook-using-ai-expert/"><u>Upgrade Windows 11 Notebook Using AI Expert</u></a></li>
<li><a href="https://windows11.techidaily.com/win10win11-eliminating-audacity-paudio-faults/"><u>Win10/Win11: Eliminating Audacity PAudio Faults</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-bluescreen-blitz-implement-these-11-essential-steps/"><u>Win11 Bluescreen Blitz: Implement These 11 Essential Steps</u></a></li>
</ul></div>
