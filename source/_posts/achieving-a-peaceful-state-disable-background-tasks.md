---
title: "Achieving a Peaceful State: Disable Background Tasks"
date: 2024-08-15T15:12:47.752Z
updated: 2024-08-16T15:12:47.752Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Achieving a Peaceful State: Disable Background Tasks"
excerpt: "This Article Describes Achieving a Peaceful State: Disable Background Tasks"
keywords: Peaceful Mind Mode,Stop Background Noise,Quiet PC Workflow,Silent System Update,Hush Task Management,Calm Process Control,Serene Background Sync
thumbnail: https://thmb.techidaily.com/3e8a6c48903de348edfc32de01dc40c1bc954d345539201fb129df4e83ad3d30.jpg
---

## Achieving a Peaceful State: Disable Background Tasks

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
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
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
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
6. Click the **Save** button to save the file.
7. Right-click on the newly created reg file and select **Open.** Click **Yes** to confirm and modify the registry entries to disable background apps.
8. If the script runs without error, restart your PC to apply the changes.

 The above script modifies the two DWORD values, **GlobalUserDisabled** and **BackgroundAppGlobalToggle,** setting them to **1** and **0**, respectively. Modifying the GlobalUserDisabled value prevents background access to applications.

 Similarly, changes to the BackgroundAppGlobalToggle turn off the toggle for background apps in Windows search, thus limiting its background access.

 If you need to turn on background apps for the current user, then save the following script as **enable\_background\_apps.reg** and run it as administrator.

![reg file content background app disable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/reg-file-content-background-app-disable.png)
<!-- affiliate ads begin -->

<!-- affiliate ads end -->

`Windows Registry Editor Version 5.00  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\BackgroundAccessApplications]  
"GlobalUserDisabled"=-  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Search]  
"BackgroundAppGlobalToggle"=-`

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
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
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->
5. Right-click on the **Windows** key and select **New > Key.** Rename the key as **AppPrivacy.**
6. Right-click on the **AppPrivacy** key and select **New > DWORD (32-bit) Value**. Rename the value as **LetAppsRunInBackground.**  
![registry editor create new value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/registry-editor-create-new-value.png)
7. Right-click on the **LetAppsRunInBackground** value and select **Modify**.  
![registry editor data 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/registry-editor-data-2.png)
8. Type **2** in the **Value data** field and click **OK** to save the changes.
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
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
4. In the new window that appears, select **Enabled**.
5. Next, under the **Options** section, click the drop-down for **Default for all apps** and select **Force Deny**.  
![disable background app group policy editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/disable-background-app-group-policy-editor.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
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



