---
title: How to Display More Pinned Items on the Windows 11 Start Menu
date: 2024-06-25 10:43:17
updated: 2024-06-26 11:19:51
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Display More Pinned Items on the Windows 11 Start Menu
excerpt: This Article Describes How to Display More Pinned Items on the Windows 11 Start Menu
keywords: Pin Management,Windows 11 Start View,Maximize Pinned Items,Enhance Start Menu,Window 11 Pinning,Increase Start Visibility,Pinned Items Maximization
thumbnail: https://thmb.techidaily.com/cf7a08bd282de8a6ab97b6e5d5d8ca10a7266e7f855e68e8c2f62606a22410cc.jpeg
---

## How to Display More Pinned Items on the Windows 11 Start Menu

 Pinning items to the Start Menu on Windows 11 is a great way to keep your apps and programs within reach if you don’t want them cluttering the Taskbar or desktop. But if you find yourself running out of space to pin them, you can make it so that the Start Menu shows more pinned items.

 Here’s how to display more pinned items on the Windows 11 Start Menu.

## How Do I Display More Pinned Items on the Start Menu on Windows 11?

 Before you proceed, make sure you’ve updated Windows 11 to the latest version. Then, you can use the Settings apps or the Registry Editor to show more apps and programs in the Windows 11 Start Menu

### Using the Settings App

 Displaying more items on the Start Menu in the settings is the easiest way of doing it. To do that, follow the steps below:

1. Press**Win + I** to open the Settings app.
2. Click**Personalization** on the left side menu, and then click**Start** on the right.  
![part of the windows 11 personalization settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/part-windows-11-personalization-settings.jpg)
3. At the top, you’ll see the**Layout** heading, and you should tick the**More pins** radio button.  
![the layout section of the windows 11 personalization settings with the more pins option highlighted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/layout-section-start-settings-windows-11.jpg)

 If you want to return the number of pinned items on the Start Menu to the default setting, follow steps**1** and**2** and tick the**Default** radio button instead.

### Using the Registry Editor

 Before you start using the Registry Editor, we highly recommend that you read our guides on[backing up the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or[creating a system restore on Windows 11](https://www.makeuseof.com/windows-11-create-restore-point/) . It’s always a good idea to have a way to restore the registry in case something goes wrong.

 Afterward, you can add more apps and programs to the Windows Start Menu by following the steps below.

1. Press**Win + R** , enter**regedit** in Windows Run’s dialog box, and hit the**Enter** key. When you see the UAC prompt, click**Yes** to open the Registry Editor.
2. Copy and paste the below path into the Registry Editor’s address bar and hit the**Enter** key:  
HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced
3. In the right panel, double-click the**Start\_Layout** value to edit it.  
![windows registry with the start layout value selected](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-reg-editor-start-layout-value-selected.jpg)
4. Change**Value data** to**1** to add more pins to the Start Menu.  
![editing the start value in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/start-layout-value-regedit.jpg)
5. Restart your Windows 11 PC.

 If you ever want to return the default layout for the pinned items on the Start Menu, just change**Value data** of the**Start\_Layout** value back to**0** in the Registry Editor.

## Expand Your Taskbar by Displaying More Items

 If you find that the Start Menu isn't showing enough pinned items, you can simply reveal more of them using the Settings app or Registry Editor. That way, you will have more of your favorite apps and programs within reach when you click**Start** .

 If you decide to use Registry Editor to tweak the registry, however, be sure to create some sort of backup beforehand.


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
