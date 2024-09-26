---
title: Reworking Default View of Task Manager in Win11
date: 2024-08-15T15:44:53.041Z
updated: 2024-08-16T15:44:53.041Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reworking Default View of Task Manager in Win11
excerpt: This Article Describes Reworking Default View of Task Manager in Win11
keywords: Win11 Task Manager Update,Enhanced Task View Win11,Modern Task Manager Win11,UI Revamp Task Manager Win11,Default View Improvement Win11,Win11 Task Interface Redesign,New TaskManager Win11 Experience
thumbnail: https://thmb.techidaily.com/15a61f0827860e342a65d573fdf8ef935cbe188b573d2796a1411e612ad84808.jpg
---

## Reworking Default View of Task Manager in Win11

 The Task Manager provides a quick overview of your system's current status and shows essential information. Its Start page displays useful details such as currently running background processes, applications, CPU, and memory utilization. If you'd like to customize its appearance, change the Start page. In this article, we’ll look at how to change the Task Manager Start page in Windows 11\.

## 1\. Use Task Manager Settings

 If you want to quickly change the Task Manager Start page, you can use its Settings tab. This option requires no modification to the registry editor or additional scripts to run.

 To change the Task Manager Start page using Task Manager settings, do the following.

1. Press **Win + R** to open the Run dialog box.
2. Type **taskmgr** and press **Enter** to launch Task Manager.
3. Once in Task Manager, click on **Settings** (the gear icon).
4. You'll see a **Default Start Page** drop-down menu at the top. This is where you can select the page to display when Task Manager opens.  
![Use Settings to Change Task Manager Start Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/use-settings-to-change-task-manager-start-page.jpg)

 The options available are the following:

1. Processes
2. Performance
3. App history
4. Startup apps
5. Users
6. Details
7. Services ​​​​

 Once you make a selection, Task Manager will remember the setting and open the page you chose from now on.

<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Tweak the Registry Editor

 The Registry Editor is another way to change the default Start page for Task Manager. The procedure is slightly more complex than using Task Manager Settings, but it offers more customization options. Be careful when modifying entries in the Registry Editor, as incorrect changes can cause errors or system instability. To avoid losing data, [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it.

 To change the Task Manager Start page using the Registry Editor, follow these steps.

1. [Open the Registry Editor window](https://www.makeuseof.com/windows-11-open-registry-editor/).
2. If the UAC prompt pops up, click **Yes** to grant administrative rights.
3. In the left pane, navigate to the following key.  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\TaskManager`
4. Double-click **StartUpTab** in the right pane. If there is no such entry, then right-click on the Task Manager key.
5. From the context menu, select **New > DWORD (32-bit) Value**.
6. Now name the value **StartUpTab** and double-click on it.  
![Modify Registry to Change Task Manager Start Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modify-registry-to-change-task-manager-start-page.jpg)
<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Set its **Value data** to one of the following numbers to change the default start page:  
`0 = Processes  

1 = Performance  

2 = App history  

3 = Startup apps  

4 = Users  

5 = Details  

6 = Services`
8. Click **OK** to save the changes and close the Registry Editor window.

 Next time you open Task Manager, it will display a page according to your preferences.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Use a REG File

 If the registry editor isn't your thing, you can use a REG file to modify the Task Manager start page. The process does not require registry tweaking and is straightforward.

 To create a .reg file, [open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) and type the following:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\TaskManager]  
  
"StartUpTab"=dword:00000000`

 Here, the last digit reflects the type of Start page.

 For example, if you want to set **Processes** as your default start page, use **0** (**00000000**). Similarly, if you want the **Details** page to display as default, set it to **5** (**00000005**).

 The other options are:

`00000001 - Performance  
  
00000002 - App history  
  
00000003 - Startup apps  
  
00000004 - Users  
  
00000006 - Services`

 Now, click **File** and select **Save as**. In the Save as dialog box, click the Save as type drop-down menu and select **All files**. Name the file with the **.reg** extension. For example, **TaskManagerStartPage.reg**.

![Use a REG File to Change Task Manager Start Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/use-a-reg-file-to-change-task-manager-start-page.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->

 Next, select **Desktop** from the left pane and click **Save**. Once saved, double-click on this newly created REG file. This adds the required details to the Registry Editor and changes the Task Manager start page.

 If you ever want to revert the changes, delete the REG file and restart your computer.

<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Changing the Task Manager Start Page on Windows

 It’s easy to customize Task Manager and change its Start page according to your preference. You can use Task Manager Settings, the Registry Editor, or a REG file to set the desired page. Once you have set the Start page, Task Manager will remember it and open that page when you launch it.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>



