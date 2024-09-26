---
title: "Windows 11: Stop Intelligent Assistant"
date: 2024-08-22T21:37:07.046Z
updated: 2024-08-23T21:37:07.046Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows 11: Stop Intelligent Assistant"
excerpt: "This Article Describes Windows 11: Stop Intelligent Assistant"
keywords: Win 11 Smart Assist Cut Off,Windows 11 End IntelliSense,Disable Windows 11 Cortana,Stop W11 AI Features,Turn Off Microsoft's AI in Win11,Cease Windows 11 Voice Assistant,Block Intelligent Assist in Win11
thumbnail: https://thmb.techidaily.com/3c096ca7006d9a28f3f7e555f29e64435eb73c0052911cf681dfac2286fbe4f4.jpg
---

## Windows 11: Stop Intelligent Assistant

 Windows Copilot, Microsoft's new AI assistant, can assist you with a variety of tasks, such as answering questions, changing system settings, and creating AI images. However, if you're not a fan of Copilot or simply don't need it, you can remove its taskbar icon or disable it entirely on your Windows 11 PC. Here, we'll show you how.

## How to Remove the Copilot Icon From the Windows 11 Taskbar

 By default, the Copilot icon appears in the Windows 11 taskbar. However, if you prefer not to have it there but still want to use it occasionally, it's easy to hide the Copilot icon. Simply right-click anywhere on an empty spot on your taskbar and select **Taskbar settings**. In the Settings window that appears, turn off the toggle next to **Copilot**.

![Remove Copilot Icon From Windows 11 Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/remove-copilot-icon-from-windows-11-taskbar.jpg)

 This should remove the Copilot icon from the taskbar. You can still access Copilot by pressing the **Win + C** keyboard shortcut in Windows 11\.

## How to Completely Disable Copilot via Group Policy Settings

 Although hiding the Copilot is quite easy, it does not turn it off completely, and you might inadvertently access it. Fortunately, you can turn off Copilot completely via the Local Group Policy Editor on PCs running the Professional, Education, or Enterprise edition of Windows 11\.

 If you are using Windows 11 Home, skip to the Registry Editor method below or use a [workaround to enable the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Press **Win + S** to access the search menu.
2. Type **gpedit.msc** in the search box and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **User Configuration > Administrative Templates > Windows Components > Windows Copilot**.
5. Double-click the **Turn off Windows Copilot** policy on your right.
6. Select the **Enabled** option.
7. Hit **Apply** followed by **OK**.  
![Turn Off Windows Copilot Using the Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-windows-copilot-using-the-group-policy-editor.jpg)

 Once you complete the above steps, Copilot will be disabled on your Windows 11 PC and you won't be able to access it even with the keyboard shortcut. If you want to re-enable Copilot later, repeat the above steps and set the **Turn off Windows Copilot** policy to **Not configured** or **Disabled**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Completely Disable Copilot by Modifying Registry Files

 Another way to disable Copilot on Windows 11 involves modifying registry files. However, since editing the registry can be risky, you should follow the steps carefully. Also, be sure to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/). This will allow you to restore the registry files in case something goes wrong.

 Once you’ve done that, here’s what you need to do to disable Copilot via the Registry Editor:

1. Press **Win + R** to open the Run dialog.
2. Type **regedit** in the text box and press **Enter** to open the Registry Editor.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_CURRENT\_USER > Software > Policies > Microsoft > Windows**.
5. Right-click the **Windows** key and select **New > Key**. Name it **WindowsCopilot**.
6. Right-click on the **WindowsCopilot** DWORD, go to **New**, and select **DWORD (32-bit) Value** from the submenu. Name the DWORD **TurnOffWindowsCopilot**.
7. Double-click the **TurnOffWindowsCopilot** DWORD, type **1** in the text field, and click **OK**.
8. Restart your PC for the changes to take effect.  
![Turn Off Windows Copilot Using the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-windows-copilot-using-the-registry-editor.jpg)

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 And that’s about it. Windows Copilot will be disabled on your PC. To re-enable it in the future, repeat the above steps and set the **TurnOffWindowsCopilot** DWORD value to 0\. You can also delete the **TurnOffWindowsCopilot** DWORD instead.

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->
## Get Rid of Copilot on Windows 11

 While Windows Copilot is a powerful tool, not everyone may want to use it. Fortunately, it’s possible to get rid of it. The above steps will help you achieve your goal, whether you want to keep Copilot out of sight or turn it off entirely.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>