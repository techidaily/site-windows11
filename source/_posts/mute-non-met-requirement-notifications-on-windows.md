---
title: Mute Non-Met Requirement Notifications on Windows
date: 2024-09-05T02:08:02.502Z
updated: 2024-09-06T02:08:02.502Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mute Non-Met Requirement Notifications on Windows
excerpt: This Article Describes Mute Non-Met Requirement Notifications on Windows
keywords: Mute Windows Alerts,Stop Met Req Notifications,Turn Off Windows Messages,Silence Met Status Warnings,Halt Non-Met System Notify,Disable Met Notification Windows,Quiet Non-Met Windows Alerts
thumbnail: https://thmb.techidaily.com/f5b8e36c4ebd6a9ca109693d88c7c440e68928a27daf3516cb90c9a543d54e11.jpeg
---

## Mute Non-Met Requirement Notifications on Windows

### Key Takeaways

* Windows 11 has stricter hardware requirements, resulting in a "System requirements not met" watermark for unsupported hardware.
* You can remove the watermark by modifying the Registry Editor or using the Group Policy Editor.
* New updates may cause the watermark to reappear, requiring you to repeat the removal steps.

 If you are running Windows 11 on unsupported hardware, the newer operating system version will show a "System requirement not met" watermark in the bottom left corner of your screen.

 This may not be a concern if you use the OS in a virtual machine. But a watermark can stick out like a sore thumb for most people. Fortunately, you can remove the system requirements not met watermark with a registry hack and the Group Policy Editor.

## Why Does Windows 11 Show the "System Requirements Not Met" Watermark?

 Microsoft Windows 11 has a much [stricter hardware requirement](https://www.makeuseof.com/can-your-pc-run-windows-11/) than its predecessors. If your system does not meet the minimum system requirement, including TPM 2.0, the installation will stop abruptly.

 However, with the problem came many workarounds that allowed you to [bypass the restriction and install Windows 11](https://www.makeuseof.com/bypass-windows-11-minimum-installation-requirements/) on unsupported hardware.

 While Microsoft initially allowed installation on unsupported hardware with a warning about security issues and lack of future updates, it has now [decided to put a permanent watermark](https://www.makeuseof.com/microsoft-windows-11-unsupported-watermark/) to remind the users that their system is not supported. A similar message may also appear in the Settings app.

<!-- affiliate ads begin -->
<span id="1495277">
					<video width="1536" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1495277.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/17189-1495277">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1495277.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:960px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ffunwhole.sjv.io%2Fc%2F5597632%2F1495277%2F17189'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1495277/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Remove the "System Requirement Not Met" Watermark Using the Registry Editor

 If you see the "system requirements not met" watermark on your PC, you can remove it by modifying a DWORD value in Registry Editor.

 As modifying the Windows Registry involves risk, [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before making any changes using the Registry Editor.

 Follow these steps to remove the "System requirement not met" watermark in Windows 11:

1. Press **Win + R** to open the **Run** dialog.
2. Type **regedit** and click **OK** to open the Registry Editor.
3. In the Registry Editor, navigate to the following path. You can also copy and paste the path in the Registry Editor address bar for quick navigation.  
HKEY_CURRENT_USER\Control Panel\UnsupportedHardwareNotificationCache
4. In the right pane, right-click on the **SV2 DWORD** value and select **Modify**.
5. Enter **0** into the value data field.  
![Edit sv2 value to remove the system requirement not met watermark.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/edit-sv2-value-remove-system-requirement-not-met-watermark.jpg)
6. Click **OK** to save the changes.
7. Close the Registry Editor and restart your PC to apply the changes. After restarting, Windows 11 will no longer show the unsupported hardware watermark.

 If you don’t have the UnsupportedHardwareNotificationCache key, you must create a new one and set its value. To do this:

1. In Registry Editor, right-click the **Control** key (**HKEY\_CURRENT\_USER\\Control Panel**) and select **New > Key.**
2. Next, rename the key as **UnsupportedHardwareNotificationCache.**  
![Create new key for unsupported hardware notification cache.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/create-new-key-unsupported-hardware-notification-cache.jpeg)
3. Next, right-click on the new key and select **New > DWORD (64-bit)** value.
<!-- affiliate ads begin -->
<span id="1983551">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983551.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983551">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983551.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983551%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983551/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Rename the value as **SV2**.
5. Next, modify the **SV2 DWORD** value and set its **Value data** to **2**.
6. Click **OK** to save the changes.

 The watermark may reappear with new updates. So, you must repeat the steps after installing the update to keep your desktop clean.

## 2\. Remove the System Requirement Not Met Message Using the Group Policy Editor

 You can use the Group Policy Editor to turn off the System requirements not met message in Windows 11\. To achieve this, we’ll need to modify the **Hide messages when Windows system requirements are not met** Group Policy and set it to enabled.

 Only the Windows 11 Pro, Enterprise, and Education edition comes with the Local Group Policy Editor installed by default. If running the Home edition, follow these steps to [enable the Group Policy Editor in Windows Home](http://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To turn off the System requirement not message using GPedit:

1. Press **Win + R** to open the **Run** dialog.
2. Type **gpedit.msc** and click **OK** to open **Group Policy Editor**. Click **Yes** if prompted by **User Account Control**.
3. In Group Policy Editor, navigate to the following location:  
`Local Computer Policy > Computer Configuration > Administrative Templates > System`
4. In the right pane, scroll down and locate the **Hide messages when Windows system requirements are not met** policy.  
![Group policy editor Hide messages when Windows system requirements are not met](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/group-policy-editor-hide-messages-when-windows-system-requirements-are-not-met.jpg)
5. Next, select and double-click on the policy to open its properties.
6. Select **Enabled** to enable the policy setting.  
![Group policy editor Hide messages when Windows system requirements are not met enable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/group-policy-editor-hide-messages-when-windows-system-requirements-are-not-met-enable.jpg)
7. Click **Apply** and **OK** to save the changes.

 Now, you need to restart your computer to apply the changes. After the restart, the "minimum system requirements are not met message" will not be displayed on the desktop.;

 If you need to revert the changes, open the **Hide messages when Windows system requirements are not met** policy again and set it to **Not Configured**.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997695/19272" target="_top" id="1997695">
  <img src="//a.impactradius-go.com/display-ad/19272-1997695" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997695/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Removing the "System Requirement Not Met" Watermark in Windows 11

 If you have bypassed the TPM secure boot requirement to install Windows 11, you will likely see the System requirement not met watermark on your PC. Fortunately, you can remove the watermark by modifying a Windows registry entry or configuring a group policy using GPedit.

 If you are running Windows 11 on unsupported hardware, the newer operating system version will show a "System requirement not met" watermark in the bottom left corner of your screen.

 This may not be a concern if you use the OS in a virtual machine. But a watermark can stick out like a sore thumb for most people. Fortunately, you can remove the system requirements not met watermark with a registry hack and the Group Policy Editor.

## Why Does Windows 11 Show the "System Requirements Not Met" Watermark?

 Microsoft Windows 11 has a much [stricter hardware requirement](https://www.makeuseof.com/can-your-pc-run-windows-11/) than its predecessors. If your system does not meet the minimum system requirement, including TPM 2.0, the installation will stop abruptly.

 However, with the problem came many workarounds that allowed you to [bypass the restriction and install Windows 11](https://www.makeuseof.com/bypass-windows-11-minimum-installation-requirements/) on unsupported hardware.

 While Microsoft initially allowed installation on unsupported hardware with a warning about security issues and lack of future updates, it has now [decided to put a permanent watermark](https://www.makeuseof.com/microsoft-windows-11-unsupported-watermark/) to remind the users that their system is not supported. A similar message may also appear in the Settings app.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2030381/7443" target="_top" id="2030381">
  <img src="//a.impactradius-go.com/display-ad/7443-2030381" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2030381/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Remove the "System Requirement Not Met" Watermark Using the Registry Editor

 If you see the "system requirements not met" watermark on your PC, you can remove it by modifying a DWORD value in Registry Editor.

 As modifying the Windows Registry involves risk, [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before making any changes using the Registry Editor.

 Follow these steps to remove the "System requirement not met" watermark in Windows 11:

1. Press **Win + R** to open the **Run** dialog.
2. Type **regedit** and click **OK** to open the Registry Editor.
3. In the Registry Editor, navigate to the following path. You can also copy and paste the path in the Registry Editor address bar for quick navigation.  
HKEY_CURRENT_USER\Control Panel\UnsupportedHardwareNotificationCache
4. In the right pane, right-click on the **SV2 DWORD** value and select **Modify**.
5. Enter **0** into the value data field.  
![Edit sv2 value to remove the system requirement not met watermark.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/edit-sv2-value-remove-system-requirement-not-met-watermark.jpg)
6. Click **OK** to save the changes.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934142/19272" target="_top" id="1934142">
  <img src="//a.impactradius-go.com/display-ad/19272-1934142" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934142/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Close the Registry Editor and restart your PC to apply the changes. After restarting, Windows 11 will no longer show the unsupported hardware watermark.

 If you don’t have the UnsupportedHardwareNotificationCache key, you must create a new one and set its value. To do this:

1. In Registry Editor, right-click the **Control** key (**HKEY\_CURRENT\_USER\\Control Panel**) and select **New > Key.**
2. Next, rename the key as **UnsupportedHardwareNotificationCache.**  
![Create new key for unsupported hardware notification cache.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/create-new-key-unsupported-hardware-notification-cache.jpeg)
3. Next, right-click on the new key and select **New > DWORD (64-bit)** value.
4. Rename the value as **SV2**.
5. Next, modify the **SV2 DWORD** value and set its **Value data** to **2**.
6. Click **OK** to save the changes.

 The watermark may reappear with new updates. So, you must repeat the steps after installing the update to keep your desktop clean.

## 2\. Remove the System Requirement Not Met Message Using the Group Policy Editor

 You can use the Group Policy Editor to turn off the System requirements not met message in Windows 11\. To achieve this, we’ll need to modify the **Hide messages when Windows system requirements are not met** Group Policy and set it to enabled.

 Only the Windows 11 Pro, Enterprise, and Education edition comes with the Local Group Policy Editor installed by default. If running the Home edition, follow these steps to [enable the Group Policy Editor in Windows Home](http://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To turn off the System requirement not message using GPedit:

1. Press **Win + R** to open the **Run** dialog.
2. Type **gpedit.msc** and click **OK** to open **Group Policy Editor**. Click **Yes** if prompted by **User Account Control**.
3. In Group Policy Editor, navigate to the following location:  
`Local Computer Policy > Computer Configuration > Administrative Templates > System`
4. In the right pane, scroll down and locate the **Hide messages when Windows system requirements are not met** policy.  
![Group policy editor Hide messages when Windows system requirements are not met](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/group-policy-editor-hide-messages-when-windows-system-requirements-are-not-met.jpg)
5. Next, select and double-click on the policy to open its properties.
<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484950/16446" target="_top" id="1484950">
  <img src="//a.impactradius-go.com/display-ad/16446-1484950" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484950/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Select **Enabled** to enable the policy setting.  
![Group policy editor Hide messages when Windows system requirements are not met enable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/group-policy-editor-hide-messages-when-windows-system-requirements-are-not-met-enable.jpg)
7. Click **Apply** and **OK** to save the changes.
<!-- affiliate ads begin -->
<span id="1304647">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1304647.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1304647">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1304647.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1304647%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1304647/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now, you need to restart your computer to apply the changes. After the restart, the "minimum system requirements are not met message" will not be displayed on the desktop.;

 If you need to revert the changes, open the **Hide messages when Windows system requirements are not met** policy again and set it to **Not Configured**.

<!-- affiliate ads begin -->
<span id="1975562">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975562.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975562">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975562.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975562%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975562/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Removing the "System Requirement Not Met" Watermark in Windows 11

 If you have bypassed the TPM secure boot requirement to install Windows 11, you will likely see the System requirement not met watermark on your PC. Fortunately, you can remove the watermark by modifying a Windows registry entry or configuring a group policy using GPedit.

 If you are running Windows 11 on unsupported hardware, the newer operating system version will show a "System requirement not met" watermark in the bottom left corner of your screen.

 This may not be a concern if you use the OS in a virtual machine. But a watermark can stick out like a sore thumb for most people. Fortunately, you can remove the system requirements not met watermark with a registry hack and the Group Policy Editor.

## Why Does Windows 11 Show the "System Requirements Not Met" Watermark?

 Microsoft Windows 11 has a much [stricter hardware requirement](https://www.makeuseof.com/can-your-pc-run-windows-11/) than its predecessors. If your system does not meet the minimum system requirement, including TPM 2.0, the installation will stop abruptly.

 However, with the problem came many workarounds that allowed you to [bypass the restriction and install Windows 11](https://www.makeuseof.com/bypass-windows-11-minimum-installation-requirements/) on unsupported hardware.

 While Microsoft initially allowed installation on unsupported hardware with a warning about security issues and lack of future updates, it has now [decided to put a permanent watermark](https://www.makeuseof.com/microsoft-windows-11-unsupported-watermark/) to remind the users that their system is not supported. A similar message may also appear in the Settings app.

## 1\. Remove the "System Requirement Not Met" Watermark Using the Registry Editor

 If you see the "system requirements not met" watermark on your PC, you can remove it by modifying a DWORD value in Registry Editor.

 As modifying the Windows Registry involves risk, [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before making any changes using the Registry Editor.

 Follow these steps to remove the "System requirement not met" watermark in Windows 11:

1. Press **Win + R** to open the **Run** dialog.
2. Type **regedit** and click **OK** to open the Registry Editor.
3. In the Registry Editor, navigate to the following path. You can also copy and paste the path in the Registry Editor address bar for quick navigation.  
HKEY_CURRENT_USER\Control Panel\UnsupportedHardwareNotificationCache
4. In the right pane, right-click on the **SV2 DWORD** value and select **Modify**.
5. Enter **0** into the value data field.  
![Edit sv2 value to remove the system requirement not met watermark.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/edit-sv2-value-remove-system-requirement-not-met-watermark.jpg)
6. Click **OK** to save the changes.
7. Close the Registry Editor and restart your PC to apply the changes. After restarting, Windows 11 will no longer show the unsupported hardware watermark.

 If you don’t have the UnsupportedHardwareNotificationCache key, you must create a new one and set its value. To do this:

1. In Registry Editor, right-click the **Control** key (**HKEY\_CURRENT\_USER\\Control Panel**) and select **New > Key.**
2. Next, rename the key as **UnsupportedHardwareNotificationCache.**  
![Create new key for unsupported hardware notification cache.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/create-new-key-unsupported-hardware-notification-cache.jpeg)
3. Next, right-click on the new key and select **New > DWORD (64-bit)** value.
4. Rename the value as **SV2**.
5. Next, modify the **SV2 DWORD** value and set its **Value data** to **2**.
6. Click **OK** to save the changes.

 The watermark may reappear with new updates. So, you must repeat the steps after installing the update to keep your desktop clean.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896560/19272" target="_top" id="1896560">
  <img src="//a.impactradius-go.com/display-ad/19272-1896560" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896560/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Remove the System Requirement Not Met Message Using the Group Policy Editor

 You can use the Group Policy Editor to turn off the System requirements not met message in Windows 11\. To achieve this, we’ll need to modify the **Hide messages when Windows system requirements are not met** Group Policy and set it to enabled.

 Only the Windows 11 Pro, Enterprise, and Education edition comes with the Local Group Policy Editor installed by default. If running the Home edition, follow these steps to [enable the Group Policy Editor in Windows Home](http://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To turn off the System requirement not message using GPedit:

1. Press **Win + R** to open the **Run** dialog.
2. Type **gpedit.msc** and click **OK** to open **Group Policy Editor**. Click **Yes** if prompted by **User Account Control**.
3. In Group Policy Editor, navigate to the following location:  
`Local Computer Policy > Computer Configuration > Administrative Templates > System`
4. In the right pane, scroll down and locate the **Hide messages when Windows system requirements are not met** policy.  
![Group policy editor Hide messages when Windows system requirements are not met](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/group-policy-editor-hide-messages-when-windows-system-requirements-are-not-met.jpg)
5. Next, select and double-click on the policy to open its properties.
6. Select **Enabled** to enable the policy setting.  
![Group policy editor Hide messages when Windows system requirements are not met enable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/group-policy-editor-hide-messages-when-windows-system-requirements-are-not-met-enable.jpg)
7. Click **Apply** and **OK** to save the changes.
<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1167086/14483" target="_top" id="1167086">
  <img src="//a.impactradius-go.com/display-ad/14483-1167086" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://electronicx.pxf.io/i/5597632/1167086/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now, you need to restart your computer to apply the changes. After the restart, the "minimum system requirements are not met message" will not be displayed on the desktop.;

 If you need to revert the changes, open the **Hide messages when Windows system requirements are not met** policy again and set it to **Not Configured**.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915870/19272" target="_top" id="1915870">
  <img src="//a.impactradius-go.com/display-ad/19272-1915870" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915870/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Removing the "System Requirement Not Met" Watermark in Windows 11

 If you have bypassed the TPM secure boot requirement to install Windows 11, you will likely see the System requirement not met watermark on your PC. Fortunately, you can remove the watermark by modifying a Windows registry entry or configuring a group policy using GPedit.

 If you are running Windows 11 on unsupported hardware, the newer operating system version will show a "System requirement not met" watermark in the bottom left corner of your screen.

 This may not be a concern if you use the OS in a virtual machine. But a watermark can stick out like a sore thumb for most people. Fortunately, you can remove the system requirements not met watermark with a registry hack and the Group Policy Editor.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1061528/11832" target="_top" id="1061528">
  <img src="//a.impactradius-go.com/display-ad/11832-1061528" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1061528/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Why Does Windows 11 Show the "System Requirements Not Met" Watermark?

 Microsoft Windows 11 has a much [stricter hardware requirement](https://www.makeuseof.com/can-your-pc-run-windows-11/) than its predecessors. If your system does not meet the minimum system requirement, including TPM 2.0, the installation will stop abruptly.

 However, with the problem came many workarounds that allowed you to [bypass the restriction and install Windows 11](https://www.makeuseof.com/bypass-windows-11-minimum-installation-requirements/) on unsupported hardware.

 While Microsoft initially allowed installation on unsupported hardware with a warning about security issues and lack of future updates, it has now [decided to put a permanent watermark](https://www.makeuseof.com/microsoft-windows-11-unsupported-watermark/) to remind the users that their system is not supported. A similar message may also appear in the Settings app.

## 1\. Remove the "System Requirement Not Met" Watermark Using the Registry Editor

 If you see the "system requirements not met" watermark on your PC, you can remove it by modifying a DWORD value in Registry Editor.

 As modifying the Windows Registry involves risk, [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before making any changes using the Registry Editor.

 Follow these steps to remove the "System requirement not met" watermark in Windows 11:

1. Press **Win + R** to open the **Run** dialog.
2. Type **regedit** and click **OK** to open the Registry Editor.
3. In the Registry Editor, navigate to the following path. You can also copy and paste the path in the Registry Editor address bar for quick navigation.  
HKEY_CURRENT_USER\Control Panel\UnsupportedHardwareNotificationCache
4. In the right pane, right-click on the **SV2 DWORD** value and select **Modify**.
5. Enter **0** into the value data field.  
![Edit sv2 value to remove the system requirement not met watermark.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/edit-sv2-value-remove-system-requirement-not-met-watermark.jpg)
6. Click **OK** to save the changes.
7. Close the Registry Editor and restart your PC to apply the changes. After restarting, Windows 11 will no longer show the unsupported hardware watermark.

 If you don’t have the UnsupportedHardwareNotificationCache key, you must create a new one and set its value. To do this:

1. In Registry Editor, right-click the **Control** key (**HKEY\_CURRENT\_USER\\Control Panel**) and select **New > Key.**
2. Next, rename the key as **UnsupportedHardwareNotificationCache.**  
![Create new key for unsupported hardware notification cache.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/create-new-key-unsupported-hardware-notification-cache.jpeg)
3. Next, right-click on the new key and select **New > DWORD (64-bit)** value.
4. Rename the value as **SV2**.
5. Next, modify the **SV2 DWORD** value and set its **Value data** to **2**.
6. Click **OK** to save the changes.

 The watermark may reappear with new updates. So, you must repeat the steps after installing the update to keep your desktop clean.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100542/7443" target="_top" id="2100542">
  <img src="//a.impactradius-go.com/display-ad/7443-2100542" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100542/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Remove the System Requirement Not Met Message Using the Group Policy Editor

 You can use the Group Policy Editor to turn off the System requirements not met message in Windows 11\. To achieve this, we’ll need to modify the **Hide messages when Windows system requirements are not met** Group Policy and set it to enabled.

 Only the Windows 11 Pro, Enterprise, and Education edition comes with the Local Group Policy Editor installed by default. If running the Home edition, follow these steps to [enable the Group Policy Editor in Windows Home](http://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To turn off the System requirement not message using GPedit:

1. Press **Win + R** to open the **Run** dialog.
2. Type **gpedit.msc** and click **OK** to open **Group Policy Editor**. Click **Yes** if prompted by **User Account Control**.
3. In Group Policy Editor, navigate to the following location:  
`Local Computer Policy > Computer Configuration > Administrative Templates > System`
4. In the right pane, scroll down and locate the **Hide messages when Windows system requirements are not met** policy.  
![Group policy editor Hide messages when Windows system requirements are not met](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/group-policy-editor-hide-messages-when-windows-system-requirements-are-not-met.jpg)
5. Next, select and double-click on the policy to open its properties.
6. Select **Enabled** to enable the policy setting.  
![Group policy editor Hide messages when Windows system requirements are not met enable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/group-policy-editor-hide-messages-when-windows-system-requirements-are-not-met-enable.jpg)
7. Click **Apply** and **OK** to save the changes.

 Now, you need to restart your computer to apply the changes. After the restart, the "minimum system requirements are not met message" will not be displayed on the desktop.;

 If you need to revert the changes, open the **Hide messages when Windows system requirements are not met** policy again and set it to **Not Configured**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118320/7443" target="_top" id="2118320">
  <img src="//a.impactradius-go.com/display-ad/7443-2118320" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118320/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Removing the "System Requirement Not Met" Watermark in Windows 11

 If you have bypassed the TPM secure boot requirement to install Windows 11, you will likely see the System requirement not met watermark on your PC. Fortunately, you can remove the watermark by modifying a Windows registry entry or configuring a group policy using GPedit.


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
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-the-art-of-audio-mastery-with-iphones-voice-recording/"><u>[New] 2024 Approved  The Art of Audio Mastery with iPhone's Voice Recording</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/rom-hidden-to-highlighted-your-2-ways-to-see-yts-past-videos/"><u>[New] From Hidden to Highlighted  Your 2 Ways to See YT's Past Videos</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-from-zero-to-hero-crafting-an-authoritative-online-self/"><u>[New] In 2024, From Zero to Hero  Crafting an Authoritative Online Self</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-top-8-best-fbx-game-recorder-alternatives/"><u>[New] In 2024, Top 8 Best FBX Game Recorder Alternatives</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-prime-episodes-your-guide-to-gpodc-mastery/"><u>[New] Prime Episodes  Your Guide to GPodC Mastery</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/nleash-creativity-best-free-video-editor-apps-android-edition/"><u>[New] Unleash Creativity  Best Free Video Editor Apps, Android Edition</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-master-fades-with-ease-4-methods-unveiled/"><u>[Updated] 2024 Approved  Master Fades with Ease  4 Methods Unveiled</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-2024-approved-transform-your-browsing-with-ms-edges-pip/"><u>[Updated] 2024 Approved  Transform Your Browsing with MS Edge's PIP</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-cross-platform-zoom-meeting-setup-guide-for-2024/"><u>[Updated] Cross-Platform Zoom Meeting Setup Guide for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-harness-the-power-of-engagement-boosting-youtube-traffic/"><u>[Updated] Harness the Power of Engagement  Boosting YouTube Traffic</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-in-2024-virtual-wit-wizardry/"><u>[Updated] In 2024, Virtual Wit Wizardry</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-top-5-chrome-plug-ins-for-snatching-fb-videos/"><u>[Updated] Top 5 Chrome Plug-Ins for Snatching FB Videos</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-vlc-analysis-and-substitutes-revisited/"><u>2024 Approved  VLC Analysis & Substitutes Revisited</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/assessment-of-the-motorola-moto-g-power-impressive-durability-and-excellent-battery-efficiency/"><u>Assessment of the Motorola Moto G Power: Impressive Durability and Excellent Battery Efficiency</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/elevate-your-skyrim-adventure-revolutionary-frame-rate-boosting-update-launched/"><u>Elevate Your Skyrim Adventure: Revolutionary Frame Rate Boosting Update Launched</u></a></li>
<li><a href="https://windows11.techidaily.com/explore-and-set-up-your-windows-11-home/"><u>Explore and Set Up Your Windows 11 Home</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-users-through-windows-error-0x0000004e-woes/"><u>Guiding Users Through Windows' Error 0X0000004E Woes</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-remedy-missing-router-control-center/"><u>How to Remedy Missing Router Control Center</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-deleted-y02t-contacts-an-easy-method-explained-by-fonelab-android-recover-contacts/"><u>How to Restore Deleted Y02T Contacts  An Easy Method Explained.</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-update-your-xbox-360-controller-with-the-latest-software-drivers/"><u>How to Update Your Xbox 360 Controller with the Latest Software Drivers</u></a></li>
<li><a href="https://windows11.techidaily.com/ignore-non-essential-feedback-alerts-suggestions-on-windows/"><u>Ignore Non-Essential Feedback Alerts, Suggestions on Windows</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-discovering-8-ultimate-mirrorless-vlogging-cameras/"><u>In 2024, Discovering 8 Ultimate Mirrorless Vlogging Cameras</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-first-time-furnishings-minimalist-house-plans-in-mc/"><u>In 2024, First-Time Furnishings  Minimalist House Plans in MC</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/in-2024-the-best-of-the-best-movie-trailer-creation-software-for-mac-and-pc/"><u>In 2024, The Best of the Best Movie Trailer Creation Software for Mac and PC</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-multiview-tech-with-windows/"><u>Mastering Multiview Tech with Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11-sign-in-shift-move-from-pin-to-password-effortlessly/"><u>Mastering Windows 11 Sign-In Shift: Move From PIN to Password Effortlessly</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11-webcam-fixes-error-a00f4289/"><u>Mastering Windows 11 Webcam Fixes - Error A00F4289</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-the-could-not-call-runtime-problem-in-malwarebytes-windows/"><u>Mending the Could Not Call Runtime Problem in Malwarebytes Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-no-script-zone-essential-4-steps-for-ps-execution-restoration/"><u>Navigating the No-Script Zone: Essential 4 Steps for PS Execution Restoration</u></a></li>
<li><a href="https://windows11.techidaily.com/nine-steps-to-overcome-0x8004def5-onedrive-error-in-win11/"><u>Nine Steps to Overcome 0X8004Def5 Onedrive Error in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-crash-zeroing-in-on-error-0x800f0831/"><u>Overcoming Windows Crash: Zeroing In on Error 0X800F0831</u></a></li>
<li><a href="https://windows11.techidaily.com/perfect-your-snip-tool-text-expertly-on-windows-11/"><u>Perfect Your Snip Tool Text Expertly on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/quickfire-processes-identifying-graphic-card-model-windows-11/"><u>Quickfire Processes: Identifying Graphic Card Model, Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/reduce-cpu-peaks-with-the-help-of-windows-rm-insights/"><u>Reduce CPU Peaks with the Help of Windows RM Insights</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-internet-connectivity-issues-in-windows-11/"><u>Resolving Internet Connectivity Issues in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-nvidia-control-panel-save-issue/"><u>Resolving Nvidia Control Panel Save Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/reverting-lost-presets-for-win-11-sleep-mode/"><u>Reverting Lost Presets for Win 11 Sleep Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/running-the-troubleshooter-in-windows-settings/"><u>Running the Troubleshooter in Windows Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/scripting-changes-to-fn-key-settings-in-win-1011/"><u>Scripting Changes to FN Key Settings in Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/shielding-windows-key-tactics-for-uac-protection/"><u>Shielding Windows: Key Tactics for UAC Protection</u></a></li>
<li><a href="https://windows11.techidaily.com/simplified-integration-how-to-set-up-linux-in-your-win10-box/"><u>Simplified Integration: How to Set Up Linux in Your Win10 Box</u></a></li>
<li><a href="https://buynow-help.techidaily.com/six-port-petfeast-dispenser-a-dependable-routine-for-your-furry-friends-nutrition/"><u>Six-Port PetFeast Dispenser: A Dependable Routine for Your Furry Friends’ Nutrition</u></a></li>
<li><a href="https://windows11.techidaily.com/steering-clear-of-xboxs-dead-end-road-error-on-modern-os/"><u>Steering Clear of Xbox's Dead-End Road Error on Modern OS</u></a></li>
<li><a href="https://screen-capture.techidaily.com/straightforward-screen-grabber-w10-edition/"><u>Straightforward Screen Grabber, W10 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-correctly-handle-windows-update-failure-error-0x80070003/"><u>Strategies to Correctly Handle Windows Update Failure (Error 0X80070003)</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-the-memory-monster-edge-webview2-troubleshooting/"><u>Taming the Memory Monster: Edge WebView2 Troubleshooting</u></a></li>
<li><a href="https://windows11.techidaily.com/the-secret-behind-timeless-game-aesthetics-retroarcs-shaders/"><u>The Secret Behind Timeless Game Aesthetics - RetroArc's Shaders</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-choosing-between-snipping-tool-and-printscreen/"><u>The Ultimate Guide to Choosing Between Snipping Tool and PrintScreen</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/top-5-car-locator-apps-for-apple-iphone-7-drfone-by-drfone-virtual-ios/"><u>Top 5 Car Locator Apps for Apple iPhone 7 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/uncover-the-file-location-for-your-desktop-images/"><u>Uncover the File Location for Your Desktop Images</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-fixing-winscomrssvdll-errors-in-windows-78/"><u>Understanding and Fixing WinscomrssvDll Errors in Windows 7/8</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-edges-ongoing-role-in-win11-systems/"><u>Understanding Edge's Ongoing Role in Win11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-full-potential-of-windows-11-search-here/"><u>Unlock the Full Potential of Windows 11 Search Here</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/unveiling-what-patch-tuesday-means-for-software-protection/"><u>Unveiling What Patch Tuesday Means for Software Protection</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11s-error-740-a-strategic-plan-for-correction-and-compensation/"><u>Win 11’S Error 740: A Strategic Plan for Correction and Compensation</u></a></li>
</ul></div>
