---
title: The Ultimate Guide to Reactivating Explore in 11OS
date: 2024-08-27T16:05:25.336Z
updated: 2024-08-28T16:05:25.336Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Ultimate Guide to Reactivating Explore in 11OS
excerpt: This Article Describes The Ultimate Guide to Reactivating Explore in 11OS
keywords: Reactivate Explorer OS,Revive Windows 11,Resurrect Explore UI,Windows 11 Reinstalls,Restart Explorer Home,Redo Windows Search Bar,Fix Windows Navigation
thumbnail: https://thmb.techidaily.com/6283ff7f0ec530727c4f03db2aa9125ca35be5851e40e3896cfafa881709bc60.png
---

## The Ultimate Guide to Reactivating Explore in 11OS

### Quick Links

* [What Is File Explorer in Windows?](#what-is-file-explorer-in-windows)
* [Restart File Explorer Using Task Manager](#restart-file-explorer-using-task-manager)
* [Exit Explorer and Manually Restart It (Windows 10 Only)](#exit-explorer-and-manually-restart-it-windows-10-only)
* [Restart Windows Explorer Manually Using Command Prompt](#restart-windows-explorer-manually-using-command-prompt)
* [Use a Batch File to Restart File Explorer in Windows](#use-a-batch-file-to-restart-file-explorer-in-windows)

 When you're facing issues with the Windows user interface—for example, your taskbar isn't responding or file navigation seems slow—restarting the File Explorer process can often fix the issue. We'll show you how to do it.

## What Is File Explorer in Windows?

 File Explorer is the built-in file manager for Windows devices. You use it to navigate through various directories and browse for files within the operating system. It starts running in the background as soon as your computer boots up.

 If you're someone who switched from a Mac, think of File Explorer as Microsoft's equivalent of Finder in macOS. You can open a new File Explorer window by simply clicking the **folder** icon in the taskbar.

 Besides file management, the process behind this tool also allows you to interact with the Start menu, desktop, and taskbar items. Thus, when you restart File Explorer, you're hitting the reboot button for most of Windows' graphical user interface—without having to shut down or restart your PC.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->
## 1\. Restart File Explorer Using Task Manager

 Task Manager is a built-in system monitor that lets you start or end a process on your computer. These processes can be active programs, services, and other tasks that run in the background while you use your PC. Many people use Task Manager to [monitor RAM, GPU, and CPU usage on Windows](https://www.makeuseof.com/windows-11-check-ram-gpu-cpu-usage/).

 Since File Explorer is a process that always runs in the background, using Task Manager to restart it is a natural option. Here's what you need to do:

1. Right-click anywhere that's empty on the taskbar and select **Task Manager** from the context menu to get started. Alternatively, you can press **Ctrl + Shift + Esc** on your keyboard.
2. If you don't see the following window and get the simple view instead on Windows 10, click **More details**.
3. Next, scroll through the list of active processes and find **Windows Explorer**. Clicking the **Name** header to sort in ABC order can help here.
4. Select **Windows Explorer** and click **Restart** (or **Restart task** on Windows 11).

![Restarting Windows Explorer in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/restarting-windows-explorer-in-task-manager.png)

 Your desktop will go black, and the taskbar will disappear for a split second, confirming that the Windows Explorer process has rebooted on your system. After the restart, the interface will likely feel more responsive; any slowdowns should be fixed.

<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->
## 2\. Exit Explorer and Manually Restart It (Windows 10 Only)

 Do you like to have more control when you restart File Explorer? Maybe you don't want to immediately restart it because you're testing something on your computer and need it to use as few resources as possible.

 If so, Windows 10 lets you exit File Explorer, then you can manually restart it using Task Manager. Follow these steps:

![Exit Explorer option from the Windows Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/exit-explorer-option-from-the-windows-taskbar.png)

1. Press **Ctrl + Shift** on your keyboard and right-click anywhere on the taskbar.
2. Choose **Exit Explorer** from the context menu. Your screen will go black, and the taskbar will disappear indefinitely, but don't panic.
3. Now, press **Ctrl + Shift + Esc** on your keyboard to open the Task Manager.
4. Go to **File > Run new task** from the Task Manager's menu bar.
5. You'll be prompted to enter the name of the process you want to run. Type **explorer.exe** and click **OK**.

![running a new explorer task in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/running-a-new-explorer-task-in-task-manager.png)

 The taskbar and your desktop will reappear on the screen, confirming that File Explorer is once again actively running in the background of your system.

## 3\. Restart Windows Explorer Manually Using Command Prompt

 The [Command Prompt is a tool](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) that most Windows users are familiar with. This built-in command-line interpreter lets you perform various tasks on a Windows computer using specific commands.

 We'll use two separate commands to kill the **Explorer.exe** process and start it back up in this method. This manual method to restart File Explorer can be handy for Windows 11 users, since the above doesn't work on the newer OS.

1. Type **command prompt** in the Start menu search bar and open it. To stop **File Explorer** from running, type the following command and hit **Enter**:  
`taskkill /f /im explorer.exe`
2. When you're ready to re-run it, use this command and press **Enter**:  
`start explorer.exe`  
![Using CMD to restart Windows explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/06/how-to-restart-explorer-windows-10-7.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
 After entering the first command, your screen will go black. You'll be able to access your desktop again once you enter the second command.

## 4\. Use a Batch File to Restart File Explorer in Windows

 A batch file is simply a plain text file containing a series of commands you can execute with command-line interpreters like Command Prompt or PowerShell. These files use the **.bat** format; you can access them using File Explorer.

 All the [commands stored in a Windows batch file will execute automatically](https://www.makeuseof.com/tag/use-windows-batch-file-commands-automate-repetitive-tasks/) in sequential order once you open it. We'll use the same two commands we used in the Command Prompt method, except you'll store it as a batch file on your desktop for easy access:

1. Use the **Start** menu search bar to find and open **Notepad**. Now, copy/paste or type the following lines:  
`taskkill /f /im explorer.exe  
start explorer.exe  
exit`
2. Click **File > Save As** from Notepad's menu bar.
3. Set the **Save as type** to **All Files** and add **.bat** at the end of the file name. Select a location you can quickly access, like the **Desktop** folder, and click **Save**. This will save the Notepad document as a batch file.

![Saving code to restart explorer as a batch file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/06/how-to-restart-explorer-windows-10-10.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
<!-- affiliate ads end -->
 All you need to do now is double-click the file to run the commands automatically. When File Explorer restarts, your screen will go black for a moment. If you store the batch file on your desktop or [pin the file to your Windows taskbar](https://www.makeuseof.com/windows-11-taskbar-pin-almost-anything/), where it's easily accessible, this becomes the fastest way to restart **Explorer.exe** on your Windows PC.

 Now that you've learned not one, but four, different ways to restart File Explorer, it's time to figure out what works best for you. We have a clear winner if you're looking for the fastest method. But if you don't want to set up a batch file for the job, using Task Manager is generally your best bet.

 When you're facing issues with the Windows user interface—for example, your taskbar isn't responding or file navigation seems slow—restarting the File Explorer process can often fix the issue. We'll show you how to do it.

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
## What Is File Explorer in Windows?

 File Explorer is the built-in file manager for Windows devices. You use it to navigate through various directories and browse for files within the operating system. It starts running in the background as soon as your computer boots up.

 If you're someone who switched from a Mac, think of File Explorer as Microsoft's equivalent of Finder in macOS. You can open a new File Explorer window by simply clicking the **folder** icon in the taskbar.

 Besides file management, the process behind this tool also allows you to interact with the Start menu, desktop, and taskbar items. Thus, when you restart File Explorer, you're hitting the reboot button for most of Windows' graphical user interface—without having to shut down or restart your PC.

## 1\. Restart File Explorer Using Task Manager

 Task Manager is a built-in system monitor that lets you start or end a process on your computer. These processes can be active programs, services, and other tasks that run in the background while you use your PC. Many people use Task Manager to [monitor RAM, GPU, and CPU usage on Windows](https://www.makeuseof.com/windows-11-check-ram-gpu-cpu-usage/).

 Since File Explorer is a process that always runs in the background, using Task Manager to restart it is a natural option. Here's what you need to do:

1. Right-click anywhere that's empty on the taskbar and select **Task Manager** from the context menu to get started. Alternatively, you can press **Ctrl + Shift + Esc** on your keyboard.
2. If you don't see the following window and get the simple view instead on Windows 10, click **More details**.
3. Next, scroll through the list of active processes and find **Windows Explorer**. Clicking the **Name** header to sort in ABC order can help here.
4. Select **Windows Explorer** and click **Restart** (or **Restart task** on Windows 11).

![Restarting Windows Explorer in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/restarting-windows-explorer-in-task-manager.png)

 Your desktop will go black, and the taskbar will disappear for a split second, confirming that the Windows Explorer process has rebooted on your system. After the restart, the interface will likely feel more responsive; any slowdowns should be fixed.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Exit Explorer and Manually Restart It (Windows 10 Only)

 Do you like to have more control when you restart File Explorer? Maybe you don't want to immediately restart it because you're testing something on your computer and need it to use as few resources as possible.

 If so, Windows 10 lets you exit File Explorer, then you can manually restart it using Task Manager. Follow these steps:

![Exit Explorer option from the Windows Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/exit-explorer-option-from-the-windows-taskbar.png)

1. Press **Ctrl + Shift** on your keyboard and right-click anywhere on the taskbar.
2. Choose **Exit Explorer** from the context menu. Your screen will go black, and the taskbar will disappear indefinitely, but don't panic.
3. Now, press **Ctrl + Shift + Esc** on your keyboard to open the Task Manager.
4. Go to **File > Run new task** from the Task Manager's menu bar.
5. You'll be prompted to enter the name of the process you want to run. Type **explorer.exe** and click **OK**.

![running a new explorer task in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/running-a-new-explorer-task-in-task-manager.png)

 The taskbar and your desktop will reappear on the screen, confirming that File Explorer is once again actively running in the background of your system.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->
## 3\. Restart Windows Explorer Manually Using Command Prompt

 The [Command Prompt is a tool](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) that most Windows users are familiar with. This built-in command-line interpreter lets you perform various tasks on a Windows computer using specific commands.

 We'll use two separate commands to kill the **Explorer.exe** process and start it back up in this method. This manual method to restart File Explorer can be handy for Windows 11 users, since the above doesn't work on the newer OS.

1. Type **command prompt** in the Start menu search bar and open it. To stop **File Explorer** from running, type the following command and hit **Enter**:  
`taskkill /f /im explorer.exe`
2. When you're ready to re-run it, use this command and press **Enter**:  
`start explorer.exe`  
![Using CMD to restart Windows explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/06/how-to-restart-explorer-windows-10-7.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
 After entering the first command, your screen will go black. You'll be able to access your desktop again once you enter the second command.

## 4\. Use a Batch File to Restart File Explorer in Windows

 A batch file is simply a plain text file containing a series of commands you can execute with command-line interpreters like Command Prompt or PowerShell. These files use the **.bat** format; you can access them using File Explorer.

 All the [commands stored in a Windows batch file will execute automatically](https://www.makeuseof.com/tag/use-windows-batch-file-commands-automate-repetitive-tasks/) in sequential order once you open it. We'll use the same two commands we used in the Command Prompt method, except you'll store it as a batch file on your desktop for easy access:

1. Use the **Start** menu search bar to find and open **Notepad**. Now, copy/paste or type the following lines:  
`taskkill /f /im explorer.exe  
start explorer.exe  
exit`
2. Click **File > Save As** from Notepad's menu bar.
3. Set the **Save as type** to **All Files** and add **.bat** at the end of the file name. Select a location you can quickly access, like the **Desktop** folder, and click **Save**. This will save the Notepad document as a batch file.

![Saving code to restart explorer as a batch file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/06/how-to-restart-explorer-windows-10-10.jpg)

 All you need to do now is double-click the file to run the commands automatically. When File Explorer restarts, your screen will go black for a moment. If you store the batch file on your desktop or [pin the file to your Windows taskbar](https://www.makeuseof.com/windows-11-taskbar-pin-almost-anything/), where it's easily accessible, this becomes the fastest way to restart **Explorer.exe** on your Windows PC.

 Now that you've learned not one, but four, different ways to restart File Explorer, it's time to figure out what works best for you. We have a clear winner if you're looking for the fastest method. But if you don't want to set up a batch file for the job, using Task Manager is generally your best bet.

 When you're facing issues with the Windows user interface—for example, your taskbar isn't responding or file navigation seems slow—restarting the File Explorer process can often fix the issue. We'll show you how to do it.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What Is File Explorer in Windows?

 File Explorer is the built-in file manager for Windows devices. You use it to navigate through various directories and browse for files within the operating system. It starts running in the background as soon as your computer boots up.

 If you're someone who switched from a Mac, think of File Explorer as Microsoft's equivalent of Finder in macOS. You can open a new File Explorer window by simply clicking the **folder** icon in the taskbar.

 Besides file management, the process behind this tool also allows you to interact with the Start menu, desktop, and taskbar items. Thus, when you restart File Explorer, you're hitting the reboot button for most of Windows' graphical user interface—without having to shut down or restart your PC.

## 1\. Restart File Explorer Using Task Manager

 Task Manager is a built-in system monitor that lets you start or end a process on your computer. These processes can be active programs, services, and other tasks that run in the background while you use your PC. Many people use Task Manager to [monitor RAM, GPU, and CPU usage on Windows](https://www.makeuseof.com/windows-11-check-ram-gpu-cpu-usage/).

 Since File Explorer is a process that always runs in the background, using Task Manager to restart it is a natural option. Here's what you need to do:

1. Right-click anywhere that's empty on the taskbar and select **Task Manager** from the context menu to get started. Alternatively, you can press **Ctrl + Shift + Esc** on your keyboard.
2. If you don't see the following window and get the simple view instead on Windows 10, click **More details**.
3. Next, scroll through the list of active processes and find **Windows Explorer**. Clicking the **Name** header to sort in ABC order can help here.
4. Select **Windows Explorer** and click **Restart** (or **Restart task** on Windows 11).

![Restarting Windows Explorer in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/restarting-windows-explorer-in-task-manager.png)

 Your desktop will go black, and the taskbar will disappear for a split second, confirming that the Windows Explorer process has rebooted on your system. After the restart, the interface will likely feel more responsive; any slowdowns should be fixed.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
## 2\. Exit Explorer and Manually Restart It (Windows 10 Only)

 Do you like to have more control when you restart File Explorer? Maybe you don't want to immediately restart it because you're testing something on your computer and need it to use as few resources as possible.

 If so, Windows 10 lets you exit File Explorer, then you can manually restart it using Task Manager. Follow these steps:

![Exit Explorer option from the Windows Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/exit-explorer-option-from-the-windows-taskbar.png)

1. Press **Ctrl + Shift** on your keyboard and right-click anywhere on the taskbar.
2. Choose **Exit Explorer** from the context menu. Your screen will go black, and the taskbar will disappear indefinitely, but don't panic.
3. Now, press **Ctrl + Shift + Esc** on your keyboard to open the Task Manager.
4. Go to **File > Run new task** from the Task Manager's menu bar.
5. You'll be prompted to enter the name of the process you want to run. Type **explorer.exe** and click **OK**.

![running a new explorer task in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/running-a-new-explorer-task-in-task-manager.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
 The taskbar and your desktop will reappear on the screen, confirming that File Explorer is once again actively running in the background of your system.

## 3\. Restart Windows Explorer Manually Using Command Prompt

 The [Command Prompt is a tool](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) that most Windows users are familiar with. This built-in command-line interpreter lets you perform various tasks on a Windows computer using specific commands.

 We'll use two separate commands to kill the **Explorer.exe** process and start it back up in this method. This manual method to restart File Explorer can be handy for Windows 11 users, since the above doesn't work on the newer OS.

1. Type **command prompt** in the Start menu search bar and open it. To stop **File Explorer** from running, type the following command and hit **Enter**:  
`taskkill /f /im explorer.exe`
2. When you're ready to re-run it, use this command and press **Enter**:  
`start explorer.exe`  
![Using CMD to restart Windows explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/06/how-to-restart-explorer-windows-10-7.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
 After entering the first command, your screen will go black. You'll be able to access your desktop again once you enter the second command.

## 4\. Use a Batch File to Restart File Explorer in Windows

 A batch file is simply a plain text file containing a series of commands you can execute with command-line interpreters like Command Prompt or PowerShell. These files use the **.bat** format; you can access them using File Explorer.

 All the [commands stored in a Windows batch file will execute automatically](https://www.makeuseof.com/tag/use-windows-batch-file-commands-automate-repetitive-tasks/) in sequential order once you open it. We'll use the same two commands we used in the Command Prompt method, except you'll store it as a batch file on your desktop for easy access:

1. Use the **Start** menu search bar to find and open **Notepad**. Now, copy/paste or type the following lines:  
`taskkill /f /im explorer.exe  
start explorer.exe  
exit`
2. Click **File > Save As** from Notepad's menu bar.
3. Set the **Save as type** to **All Files** and add **.bat** at the end of the file name. Select a location you can quickly access, like the **Desktop** folder, and click **Save**. This will save the Notepad document as a batch file.

![Saving code to restart explorer as a batch file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/06/how-to-restart-explorer-windows-10-10.jpg)

 All you need to do now is double-click the file to run the commands automatically. When File Explorer restarts, your screen will go black for a moment. If you store the batch file on your desktop or [pin the file to your Windows taskbar](https://www.makeuseof.com/windows-11-taskbar-pin-almost-anything/), where it's easily accessible, this becomes the fastest way to restart **Explorer.exe** on your Windows PC.

 Now that you've learned not one, but four, different ways to restart File Explorer, it's time to figure out what works best for you. We have a clear winner if you're looking for the fastest method. But if you don't want to set up a batch file for the job, using Task Manager is generally your best bet.

 When you're facing issues with the Windows user interface—for example, your taskbar isn't responding or file navigation seems slow—restarting the File Explorer process can often fix the issue. We'll show you how to do it.

## What Is File Explorer in Windows?

 File Explorer is the built-in file manager for Windows devices. You use it to navigate through various directories and browse for files within the operating system. It starts running in the background as soon as your computer boots up.

 If you're someone who switched from a Mac, think of File Explorer as Microsoft's equivalent of Finder in macOS. You can open a new File Explorer window by simply clicking the **folder** icon in the taskbar.

 Besides file management, the process behind this tool also allows you to interact with the Start menu, desktop, and taskbar items. Thus, when you restart File Explorer, you're hitting the reboot button for most of Windows' graphical user interface—without having to shut down or restart your PC.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Restart File Explorer Using Task Manager

 Task Manager is a built-in system monitor that lets you start or end a process on your computer. These processes can be active programs, services, and other tasks that run in the background while you use your PC. Many people use Task Manager to [monitor RAM, GPU, and CPU usage on Windows](https://www.makeuseof.com/windows-11-check-ram-gpu-cpu-usage/).

 Since File Explorer is a process that always runs in the background, using Task Manager to restart it is a natural option. Here's what you need to do:

1. Right-click anywhere that's empty on the taskbar and select **Task Manager** from the context menu to get started. Alternatively, you can press **Ctrl + Shift + Esc** on your keyboard.
2. If you don't see the following window and get the simple view instead on Windows 10, click **More details**.
3. Next, scroll through the list of active processes and find **Windows Explorer**. Clicking the **Name** header to sort in ABC order can help here.
4. Select **Windows Explorer** and click **Restart** (or **Restart task** on Windows 11).

![Restarting Windows Explorer in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/restarting-windows-explorer-in-task-manager.png)

 Your desktop will go black, and the taskbar will disappear for a split second, confirming that the Windows Explorer process has rebooted on your system. After the restart, the interface will likely feel more responsive; any slowdowns should be fixed.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
## 2\. Exit Explorer and Manually Restart It (Windows 10 Only)

 Do you like to have more control when you restart File Explorer? Maybe you don't want to immediately restart it because you're testing something on your computer and need it to use as few resources as possible.

 If so, Windows 10 lets you exit File Explorer, then you can manually restart it using Task Manager. Follow these steps:

![Exit Explorer option from the Windows Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/exit-explorer-option-from-the-windows-taskbar.png)

1. Press **Ctrl + Shift** on your keyboard and right-click anywhere on the taskbar.
2. Choose **Exit Explorer** from the context menu. Your screen will go black, and the taskbar will disappear indefinitely, but don't panic.
3. Now, press **Ctrl + Shift + Esc** on your keyboard to open the Task Manager.
4. Go to **File > Run new task** from the Task Manager's menu bar.
5. You'll be prompted to enter the name of the process you want to run. Type **explorer.exe** and click **OK**.

![running a new explorer task in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/running-a-new-explorer-task-in-task-manager.png)

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The taskbar and your desktop will reappear on the screen, confirming that File Explorer is once again actively running in the background of your system.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4531356&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8fdd149fcaa7058caccc9c4ad5b0d89a/products/tss-box.JPG" border="0">The Tube Sites Submitter is a fast and efficient tool for anyone who needs to upload videos quickly, easily and automatically to hundreds of tube sites in mere minutes . </a>
<!-- affiliate ads end -->
## 3\. Restart Windows Explorer Manually Using Command Prompt

 The [Command Prompt is a tool](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) that most Windows users are familiar with. This built-in command-line interpreter lets you perform various tasks on a Windows computer using specific commands.

 We'll use two separate commands to kill the **Explorer.exe** process and start it back up in this method. This manual method to restart File Explorer can be handy for Windows 11 users, since the above doesn't work on the newer OS.

1. Type **command prompt** in the Start menu search bar and open it. To stop **File Explorer** from running, type the following command and hit **Enter**:  
`taskkill /f /im explorer.exe`
2. When you're ready to re-run it, use this command and press **Enter**:  
`start explorer.exe`  
![Using CMD to restart Windows explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/06/how-to-restart-explorer-windows-10-7.jpg)

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->
 After entering the first command, your screen will go black. You'll be able to access your desktop again once you enter the second command.

## 4\. Use a Batch File to Restart File Explorer in Windows

 A batch file is simply a plain text file containing a series of commands you can execute with command-line interpreters like Command Prompt or PowerShell. These files use the **.bat** format; you can access them using File Explorer.

 All the [commands stored in a Windows batch file will execute automatically](https://www.makeuseof.com/tag/use-windows-batch-file-commands-automate-repetitive-tasks/) in sequential order once you open it. We'll use the same two commands we used in the Command Prompt method, except you'll store it as a batch file on your desktop for easy access:

1. Use the **Start** menu search bar to find and open **Notepad**. Now, copy/paste or type the following lines:  
`taskkill /f /im explorer.exe  
start explorer.exe  
exit`
2. Click **File > Save As** from Notepad's menu bar.
3. Set the **Save as type** to **All Files** and add **.bat** at the end of the file name. Select a location you can quickly access, like the **Desktop** folder, and click **Save**. This will save the Notepad document as a batch file.

![Saving code to restart explorer as a batch file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/06/how-to-restart-explorer-windows-10-10.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633309&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/3_premium-icon.png" border="0"> Take advantage of PREMIUM features for 12 months. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Yearly Membership</a>
<!-- affiliate ads end -->
 All you need to do now is double-click the file to run the commands automatically. When File Explorer restarts, your screen will go black for a moment. If you store the batch file on your desktop or [pin the file to your Windows taskbar](https://www.makeuseof.com/windows-11-taskbar-pin-almost-anything/), where it's easily accessible, this becomes the fastest way to restart **Explorer.exe** on your Windows PC.

 Now that you've learned not one, but four, different ways to restart File Explorer, it's time to figure out what works best for you. We have a clear winner if you're looking for the fastest method. But if you don't want to set up a batch file for the job, using Task Manager is generally your best bet.


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
<li><a href="https://youtube-sure.techidaily.com/024-approved-cutting-edge-computers-notebook-recommendations-for-editors/"><u>[New] 2024 Approved  Cutting-Edge Computers  Notebook Recommendations for Editors</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-audience-centric-video-structure-chapter-addition-for-maximum-viewership-on-youtube-for-2024/"><u>[Updated] Audience-Centric Video Structure  Chapter Addition for Maximum Viewership on YouTube for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-intense-immersion-with-closest-viewing-techniques-in-roblox/"><u>[Updated] Intense Immersion with Closest Viewing Techniques in Roblox</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-pinterest-video-extraction-the-ultimate-guide-to-the-best-tools/"><u>[Updated] Pinterest Video Extraction  The Ultimate Guide to the Best Tools</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-ultimate-list-of-premium-internet-recorders-2023-for-2024/"><u>[Updated] Ultimate List of Premium Internet Recorders 2023 for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-tomorrows-digital-playground-a-comparative-study-of-metaverse-and-omniverse/"><u>2024 Approved  Tomorrow's Digital Playground  A Comparative Study of Metaverse & Omniverse</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-ultimate-guide-top-7-superior-wet-proof-camcorders/"><u>2024 Approved  Ultimate Guide  Top 7 Superior Wet-Proof Camcorders</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-unique-conversation-starters-for-streaming/"><u>2024 Approved  Unique Conversation Starters for Streaming</u></a></li>
<li><a href="https://techidaily.com/all-things-you-need-to-know-about-wipe-datafactory-reset-for-vivo-v29e-drfone-by-drfone-reset-android-reset-android/"><u>All Things You Need to Know about Wipe Data/Factory Reset For Vivo V29e | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/bring-back-the-magic-fix-unresponsive-bluetooth-in-win11-now-available-to-everyone-guide-inside/"><u>Bring Back the Magic: Fix Unresponsive Bluetooth in Win11 – Now Available to Everyone [Guide Inside!]</u></a></li>
<li><a href="https://extra-resources.techidaily.com/capture-clarity-editing-insights-for-professional-results-for-2024/"><u>Capture Clarity  Editing Insights for Professional Results for 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/chronological-tagging-adding-times-to-youtube-vids/"><u>Chronological Tagging  Adding Times to YouTube Vids</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/download-and-install-ibooks-app-your-ultimate-guide-to-reading-ebooks-on-mac-and-pc/"><u>Download and Install iBooks App: Your Ultimate Guide to Reading eBooks on Mac & PC</u></a></li>
<li><a href="https://windows11.techidaily.com/fixes-for-corrupted-files-in-windows-10-and-11/"><u>Fixes for Corrupted Files in Windows 10 and 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-absence-of-file-notifications-in-windows-11/"><u>Fixing Absence of File Notifications in Windows 11</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/free-avi-video-rotation-software-the-ultimate-cross-platform-guide-for-2024/"><u>Free AVI Video Rotation Software The Ultimate Cross-Platform Guide for 2024</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/futureproof-your-creations-elite-resin-3d-printers-to-watch/"><u>Futureproof Your Creations: Elite Resin 3D Printers to Watch</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/high-performance-vs-excess-analyzing-the-need-for-a-120mm-radiator-in-teamgroups-sub-12w-m2-ssd-setup/"><u>High Performance Vs. Excess? Analyzing the Need for a 120Mm Radiator in TeamGroup’s Sub-12W M.2 SSD Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-adobe-photoshop-2021-2023-not-opening-on-windows-10-and-11/"><u>How to Fix Adobe Photoshop 2021-2023 Not Opening on Windows 10 & 11</u></a></li>
<li><a href="https://driver-download.techidaily.com/how-to-get-the-latest-updates-for-your-hp-officejet-pro-8620-drivers-in-windows-pcs/"><u>How To Get the Latest Updates for Your HP OfficeJet Pro 8620 Drivers in Windows PCs</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/illuminate-your-graphics-instinct-for-adobe-motion-blur/"><u>Illuminate Your Graphics  Instinct for Adobe Motion Blur</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-charting-the-course-to-cash-how-much-does-pewdopeep-make/"><u>In 2024, Charting the Course to Cash  How Much Does PewDoPeep Make?</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-guide-on-how-to-remove-apple-id-from-iphone-15-pro-max-by-drfone-ios/"><u>In 2024, Guide on How To Remove Apple ID From iPhone 15 Pro Max</u></a></li>
<li><a href="https://windows11.techidaily.com/jump-over-compatibility-obstacles-with-these-simple-fixes/"><u>Jump Over Compatibility Obstacles with These Simple Fixes.</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-powershell-to-gauge-file-sizes-in-os/"><u>Leveraging PowerShell to Gauge File Sizes in OS</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-time-transferring-classic-titles-to-photos/"><u>Navigating Through Time: Transferring Classic Titles to Photos</u></a></li>
<li><a href="https://games-able.techidaily.com/perfecting-precision-initial-fps-adjustments/"><u>Perfecting Precision: Initial FPS Adjustments</u></a></li>
<li><a href="https://windows11.techidaily.com/procurement-primer-essential-considerations-for-laptop-shoppers/"><u>Procurement Primer: Essential Considerations for Laptop Shoppers</u></a></li>
<li><a href="https://windows11.techidaily.com/proven-methods-to-uncover-the-hidden-mac-addresses-on-windows-11/"><u>Proven Methods to Uncover the Hidden MAC Addresses on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-start-windows-os-on-your-playstation-steam-device/"><u>Quick Start: Windows OS on Your PlayStation Steam Device</u></a></li>
<li><a href="https://windows11.techidaily.com/reboot-and-reclaim-resetting-ms-store-in-windows-1011/"><u>Reboot and Reclaim: Resetting MS Store in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-any-conflicts-between-wsl-subsystem-and-win-11-upgrade/"><u>Resolving Any Conflicts Between WSL Subsystem and Win 11 Upgrade</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-administrative-functionality-in-microsoft-tools/"><u>Restoring Administrative Functionality in Microsoft Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-functionality-in-windows-services-explorer-with-these-7-steps/"><u>Restoring Functionality in Windows Services Explorer with These 7 Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/say-no-more-to-failed-uploads-in-google-chrome-for-your-pc-win/"><u>Say No More to Failed Uploads in Google Chrome for Your PC, WIN</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-play-eradicating-xbox-service-block/"><u>Seamless Play: Eradicating Xbox Service Block</u></a></li>
<li><a href="https://windows11.techidaily.com/stability-in-app-placement-for-task-manager-users/"><u>Stability in App Placement for Task Manager Users</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-correcting-windows-backup-defaults/"><u>Steps for Correcting Windows Backup Defaults</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-enable-user-sign-in-following-windows-setback/"><u>Steps to Enable User Sign-In Following Windows Setback</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-dealing-with-non-downloading-errors-on-windows/"><u>Strategies for Dealing with Non-Downloading Errors on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-rectifying-c0000005-on-windows-7vista/"><u>Strategies for Rectifying C0000005 on Windows 7/Vista</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-windows-security-hurdles-with-precision-and-care/"><u>Tackling Windows Security Hurdles with Precision & Care</u></a></li>
<li><a href="https://windows11.techidaily.com/top-ways-to-resolve-black-screens-in-win1111-pro/"><u>Top Ways to Resolve Black Screens in Win11/11 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-directx-installation-issues/"><u>Troubleshooting DirectX Installation Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-administrative-potential-with-advanced-task-management-in-win11/"><u>Unleash Administrative Potential with Advanced Task Management in Win11</u></a></li>
</ul></div>