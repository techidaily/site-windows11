---
title: "Eliminating Clutter: Software Uninstallation Tricks for Windows 11 (106 Chars)"
date: 2024-07-11T21:25:30.568Z
updated: 2024-07-12T21:25:30.568Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Eliminating Clutter: Software Uninstallation Tricks for Windows 11 (106 Chars)"
excerpt: "This Article Describes Eliminating Clutter: Software Uninstallation Tricks for Windows 11 (106 Chars)"
keywords: WinUnclutterTips,W11SoftCleanup,Windows11DiskSpace,UninstallToolsWin11,StreamlineWindows,ClutterFreePC,FreeUpWindows
thumbnail: https://thmb.techidaily.com/9c499903b4fab811676ace6dccfa6523d6366f829a8f8e74e35020e8fb091823.jpg
---

## Eliminating Clutter: Software Uninstallation Tricks for Windows 11 (106 Chars)

 Most Windows users need to uninstall software now and again. The more software you install, the less free drive storage space you’ll have. Removing programs is the best way to retrieve drive storage space on your PC.

 There are various ways you can uninstall software in Windows 11\. Most users will probably be familiar with Windows’ built-in "Programs and Features" uninstaller. However, utilizing that uninstaller is not necessarily the best way to remove software; and sometimes you might have to try different methods. These are seven ways you can remove software packages in Windows 11\.

## 1\. Uninstall Software in the Control Panel

 The Control Panel is the uninstallation method most users will likely be familiar with. The Control Panel includes the Programs and Features applet. That’s an applet with which you can uninstall desktop apps that run on computers with x86 system architecture.

 Programs and Features is becoming a little outdated compared with some third-party uninstallers. It doesn’t always fully erase all files, folders, and registry entries for uninstalled software, which leaves behind some leftovers. Furthermore, Microsoft hasn’t updated Programs and Features to include UWP (Universal Windows Platform) apps for uninstalling. This is how to uninstall software with that applet.

1. Right-click **Start** on the taskbar and select the Power User’s menu **Run** shortcut.
2. Type **appwiz.cpl** into Run.
3. Click **OK** to bring up the Programs and Features window.
4. Select a software package to remove.
5. Click the **Uninstall** button.  
![programs-and-features-applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/programs-and-features-applet.png)
6. Then select **Yes** on any confirmation dialog boxes that might pop up.
7. An uninstaller wizard for the software might then open. Go through that wizard to select the required uninstall options.

## 2\. Uninstall Software in Settings

 As you can’t remove Microsoft Store apps with Programs and Features, you’ll probably need to uninstall some software via Settings. Settings includes an **Apps & features** tab from which you can select and uninstall UWP apps. You can uninstall software in Settings like this.

1. Press **Win + I** to launch Settings.
2. Click the **Apps** tab.
3. Select **Apps and features** to view a list of installed software.  
![The Apps & features tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/apps--features-in-settings.png)
4. Click a three-dot button on the right side of an app to select **Uninstall**.  
![uninstall-option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/uninstall-option.png)

## 3\. Uninstall Software via the Start Menu

 The Start menu lists most of the desktop and UWP apps installed on your desktop or laptop. That menu provides handy context menu shortcuts for uninstalling software. These are the steps for removing software via the Start menu.

1. Click the **Start** taskbar button for opening the menu.
2. Select the **All apps** menu option.
3. Right-click an app to remove and select **Uninstall**.  
![programs-and-features-applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/programs-and-features-applet.png)
4. If the software has a folder on the Start menu, click the folder to expand it. Then right-click the app in the folder to select its **Uninstall** option.

## 4\. Uninstall Software via File Explorer

 Many desktop software packages will have uninstall.exe files in their folders you can click to uninstall them with. To do so, you’ll need to find their uninstall.exe files within Explorer. This is how you remove software via File Explorer.

1. Press the **Win + E** key combination to open File Explorer.
2. Open the installation folder for the software you need to uninstall. If you stick with default installation directories, it will probably be in the "Program Files" folder.
3. Then have a look for an uninstall.exe file within the software folder.  
![The uninstall.exe file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/uninstallexe-file.png)
4. Double-click the uninstall.exe to open an uninstall window.
5. Select the required options in the uninstaller window to remove the software.

## 5\. Remove Software With the Command Prompt

 The Command Prompt is one of two command-line interpreters in Windows 11\. That has a Windows Management Instrumentation Command-line utility (WMIC) you can uninstall software with. If you prefer command-line methods, you can uninstall software with Command Prompt’s WMIC tool as follows.

1. Click the search button (magnifying glass icon) on Windows 11’s taskbar button.
2. Enter **Command Prompt** to find that app.
3. Select the **Run as administrator** option for the Command Prompt search result.
4. Input **wmic** in the Prompt and press Return.
5. Type in this command and press **Enter**:  
`product get name`
6. Note down the name of the software you want to uninstall from the list. You’ll need to include that name within the uninstall command.  
![The product get name command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/product-get-name-command.png)
7. Then input this command:  
`product where name="program name" call uninstall`
8. Press **Enter** to run the command.  
![The uninstall software Command Prompt command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/uninstall-software-command.png)
9. Then press the **Y** key and press **Return** to confirm.
10. You’ll need to replace the program name in the command specified above with the software title you noted down. For example, this is the command for uninstalling Epic Games Launcher:

`product where name="Epic Games Launcher" call uninstall`

## 6\. Remove Software With PowerShell

 You can’t uninstall some built-in Windows UWP apps, such as Camera and Photos, in Settings. If you want to remove some of those built-in apps, you can do so with this PowerShell command-line method. Follow the steps below to uninstall software with PowerShell.

1. Open Windows 11’s search tool by pressing **Win** or using the search bar on the taskbar.
2. Type **PowerShell** in the search box to find that command-line interpreter.
3. Right-click Windows Powershell’s search result to select a **Run as administrator** option.
4. To view an app list, type in this command and press **Return**:  
`Get-AppxPackage`
5. Find the app you want to uninstall in the list, and note down the PackageFullName specified for it. You can copy the PackageFullName by selecting its text and pressing the **Ctrl + C** hotkey.  
![The Get-AppxPackage command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/get-appxpackage-command.png)
6. Then input this uninstall app command and press **Return**:  
`Remove-AppxPackage [App Name]`

![The Remove-AppxPackage command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/remove-apppackage.png)

 Make sure you replace **\[App Name\]** in that command with the PackageFullName for the app you want to uninstall. A command to uninstall Edge would look like this:

`Remove-AppxPackage Microsoft.MicrosoftEdge_44.19041.1266.0_neutral__8wekyb3d8bbwe`

## 7\. Remove Software With Third-Party Uninstallers

 There are numerous third-party uninstaller tools for Windows 11/10 with which you can uninstall both desktop software and UWP apps. Many of them include options for erasing the leftover residual files and registry keys from uninstalled software. Thus, the best third-party uninstaller utilities uninstall software more thoroughly than Programs and Features, which makes them preferable alternatives.

 Some third-party uninstallers even enable users to batch uninstall software packages, which is a handy feature. IObit Uninstaller is a freeware uninstaller tool that incorporates such a feature. This guide to [batch uninstalling software with IObit Uninstaller](https://www.makeuseof.com/windows-10-iobit-uninstaller-batch-uninstall/) provides details about how you can utilize that feature.

## 8\. Uninstall Software via the Search Tool

 Aside from finding software with Windows 11’s search tool, you can also select to uninstall software from there. This is how you can uninstall software with the search tool:

1. To access the file finder utility, click **Search** on the taskbar or simultaneously press the **Windows** logo and **S** keys.
2. Enter the name of the software you want to uninstall in the search tool.
3. Click the **Uninstall** option for the matching software search result.  
![The Uninstall option in Windows 11's search tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-uninstall-option-in-the-search-tool.jpg)
4. If the software you want to install isn’t the best match, right-click its search result and select **Uninstall**.

## 9\. Uninstall Software With Gaming Clients

 Many users install games with gaming clients, such as Steam and Epic Games Launcher. If you’ve installed a game with a gaming client, you can also uninstall it with the same software. You can do so by selecting the uninstall option for a game within the client software. This [how-to-uninstall Steam games article](https://www.makeuseof.com/how-to-uninstall-steam-games-reinstall/) tells you how to remove games within Steam.

![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/uninstall-option-in-epic-games.jpg)

## 10\. How to Uninstall Software With Registry Editor and Run

 Utilizing the Registry Editor for removing software packages is not something many users will consider. However, you can remove software by entering the UninstallString values for them shown in the registry into Run. It might be necessary to sometimes utilize this method to remove software packages for which uninstall errors occur. This is how you can uninstall software with the Registry Editor and Run apps:

1. Start the Registry Editor, which you can access with the methods outlined in this [guide to opening the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
2. Next, go to this **Uninstall** key location:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Uninstall`
3. Select a key with a name that matches the software you want to install.
4. Double-click **UninstallString** to bring up a window for editing the string.
5. Select the text in the **Value data** box and press **Ctrl** \+ **C** to copy.  
![The value data for an UninstallString](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-uninstallstring-string.jpg)
6. Click **OK** on the **Edit String** window and close the Registry Editor.
7. Next, you’ll need to start the Run dialog, which has a convenient **Windows** logo + **R** hotkey.
8. Click in Run’s **Open** box and press **Ctrl** \+ **V** to paste in the copied value for the **UninstallString**.  
![The Run dialog that includes an UninstallString value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-run-dialog.jpg)
9. Press **OK** to bring up an uninstall window for the software.
10. Select to uninstall the software from there.

 Some programs will have keys with alphanumeric codes that don’t match their titles in any way. So, you may need to identify program keys differently. To do so, select a key with an alphanumeric code and look at the value for its **DisplayName** string. The **DisplayName** strings show you the names of the keys’ software packages.

![The value data for a DisplayName string](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/a-displayname-string-value.jpg)

## 11\. Uninstall Software via the Context Menu

 Uninstalling software via the right-click context menu is a convenient way to remove programs. The only thing is File Explorer doesn’t include a context menu option for uninstalling software. However, you can add a context menu option for uninstalling programs with software like Windows Uninstaller and IObit Uninstaller. Check out this [guide to adding uninstall shortcuts to the context menu](https://www.makeuseof.com/how-to-add-uninstall-shortcut-context-menu-windows-11-10/) for further details.

 When you’ve added an uninstall shortcut to the context menu, you can remove software by right-clicking its desktop shortcut and selecting the uninstall option. Note that the shortcut will be on the classic context menu, meaning you'll need to click **Show more options** to access it. Alternatively, right-click the program’s EXE (application) file within its installation folder and select the uninstall context menu option.

![The Uninstall desktop context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-uninstall-context-menu-option-1.jpg)

## Uninstall Software You Don’t Need

 Don’t let unneeded software waste drive storage space on your PC. You can free up many gigabytes of drive space by removing desktop software and UWP apps with any of the methods above. How you uninstall programs is entirely up to you. Choose whatever method for uninstalling software you prefer.

 There are various ways you can uninstall software in Windows 11\. Most users will probably be familiar with Windows’ built-in "Programs and Features" uninstaller. However, utilizing that uninstaller is not necessarily the best way to remove software; and sometimes you might have to try different methods. These are seven ways you can remove software packages in Windows 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

