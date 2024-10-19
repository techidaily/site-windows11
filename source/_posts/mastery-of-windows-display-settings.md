---
title: Mastery of Windows Display Settings
date: 2024-10-17T23:57:39.645Z
updated: 2024-10-18T17:57:24.133Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastery of Windows Display Settings
excerpt: This Article Describes Mastery of Windows Display Settings
keywords: WinDisplayTips,SetWindowsResolution,AdjustScreenRefreshRate,CustomizeWinColors,ManageDPIWindows,ControlDesktopSize,OptimizeDisplaySettings
thumbnail: https://thmb.techidaily.com/214585cc6f04e9f51b09b50240658d386b443c6b610883b05f292e6c6a7a4335.jpg
---

## Mastery of Windows Display Settings

 The Windows lock screen usually displays images when you power on your device or wake it from sleep mode. By default, the lock screen will only appear for about a minute, and then your screen will go blank.

 Meanwhile, the screen saver is an image or animation that appears when your PC has been inactive for a while. Just like the lock screen, the screen saver will also appear for about one minute.

 Wondering how you can display the lock screen or screen saver for longer?

 This article will show you the various ways to change the Windows lock screen and screen saver timeout settings.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Change the Lock Screen Timeout Settings

 Let’s first take a look at how you can configure the Windows 10 lock screen timeout settings.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528685/16446" target="_top" id="1528685">
  <img src="//a.impactradius-go.com/display-ad/16446-1528685" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528685/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Use the Windows System Settings

 The Windows system settings always come in handy in various situations. Let’s check out how you can use them to change the Windows 10 screen lock timeout settings:

1. Press **Win + I** to open the system settings.
2. Select the **Personalization** option from the menu items.
3. Click the **Lock screen** option on the left-hand side pane.
4. Scroll down on the right-hand side and select the **Screen timeout settings** option.
5. Click the **On battery power** drop-down menu on the right-hand side pane and select your preferred option.

![Using Windows System Settings to Change the Lock Screen Timeout Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Using-Windows-System-Settings-to-Change-the-Lock-Screen-Timeout-Settings.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880944/19272" target="_top" id="1880944">
  <img src="//a.impactradius-go.com/display-ad/19272-1880944" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880944/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Apply the same settings for the **When plugged** in option on the right-hand side pane. From there, close the **system settings** and restart your device to save these changes.

### Use the Edit Plan Settings (via the Control Panel)

 The Control Panel is a reliable Windows tool that helps you configure various system settings. We’ll show you how you can use it to configure the screen saver timeout settings.

 In this case, we’ll use the Control Panel to navigate to the Edit Plan settings.

 Here are the steps you need to follow:

1. Type **Control Panel** in the Start menu search bar and select the **Best match**.
2. Click the **View by** drop-down menu and select **Small icons**.
3. Select **Power Options** from the menu items.
4. Click the **Change plan settings** option on the right-hand side.
5. Locate the **Turn off the display** option. From there, select your preferred options on the **On battery** and **When plugged in** drop-down menus.
6. Finally, click the **Save changes** button.

![Using the Edit Plan Settings to Change the Lock Screen Timeout Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Using-the-Edit-Plan-Settings-to-Change-the-Lock-Screen-Timeout-Settings.jpg)

### Use the Advanced Power Options (via the Control Panel)

 You can also use the Control Panel's advanced power settings to configure the lock screen timeout settings.

 Simply follow these steps:

1. Press **Win + R** to open the Run command dialog box.
2. Type **Control Panel** and then press **OK**.
3. Select **Power Options** from the menu items.
4. Click **Change plan settings**. From there, select the **Change advanced power settings** option on the next screen.
5. Scroll down and click the **Display** option. Next, click the **Turn off display after** option.
6. Select the **On battery** option, and then configure the lock screen timeout settings using the **arrow buttons**. From there, apply the same settings for the **Plugged in** option.

![Using the Advanced Power Options to Change the Lock Screen Timeout Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Using-the-Advanced-Power-Options-to-Change-the-Lock-Screen-Timeout-Settings.jpg)

 When you're done, click **Apply** and then click **OK**. Finally, close the **Control Panel** and then restart your device to save these changes.

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014853/22899" target="_top" id="2014853">
  <img src="//a.impactradius-go.com/display-ad/22899-2014853" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014853/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Use the Command Prompt

 The Command Prompt is a reliable tool that can help you [troubleshoot various Windows system issues](https://www.makeuseof.com/how-to-troubleshoot-faulty-windows-pc/). Interestingly, this tool can also help you configure the settings on your device.

 Here’s how to configure the Windows lock screen timeout settings [using the Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/):

1. Press **Win + R** to open the Run command dialog box.
2. Type **CMD** and press **Ctrl + Shift + Enter** to open an elevated Command Prompt.
3. Next, type the following commands—one at a time—and press **Enter** in each case:

powercfg.exe /setacvalueindex SCHEME_CURRENT SUB_VIDEO VIDEOIDLE 60

powercfg.exe /setacvalueindex SCHEME_CURRENT SUB_VIDEO VIDEOCONLOCK 60

 The "**60**" in the command indicates the duration (seconds) in which the lock screen will be displayed. If you want to increase the lock screen duration, apply the previous steps and change "**60**" to a different value of your choice.

 When you finish, type the following command and press **Enter**:

powercfg.exe /SETACTIVE SCHEME_CURRENT

 Finally, restart your PC to save these changes.

## How to Change the Screen Saver Timeout Settings

 Now, let's explore how you can change the screen saver timeout settings.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148636/16836" target="_top" id="2148636">
  <img src="//a.impactradius-go.com/display-ad/16836-2148636" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148636/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Use the System Settings

![An illustration of someone configuring settings on a PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/An-illustration-of-someone-configuring-settings-on-a-PC.jpg)

 Here's how to change the duration of the screen saver using the system settings:

1. Press **Win + I** to open the system settings.
2. Type **screen saver** in the Settings search bar and select the **Change screen saver** option.

 Bear in mind that you can change the screen saver timeout settings only if the screen saver is enabled. If the screen saver is currently disabled, click the **Screen saver** drop-down menu and select your preferred image.

![Enabling the screensaver option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Enabling-the-screensaver-option.jpg)

 From there, follow these steps to configure the screen saver timeout settings:

1. Navigate to the **Wait** option on the Screen Saver Settings window.
2. Click the **arrow buttons** to select the screen saver duration (in minutes).

![Using the System Settings to Change the Screen Saver Timeout Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Using-the-System-Settings-to-Change-the-Screen-Saver-Timeout-Settings.jpg)

 Finally, press **Apply** and then press **OK** to save these changes.

### Use the Local Group Policy Editor

 The Local Group Policy Editor (LGPE) is an incredible tool that makes it easy for you to configure various system settings. Now, here's how you can use this tool to configure the screen saver timeout settings:

1. Press **Win + R** to open the Run command dialog box.
2. Type **gpedit.msc** and press **Enter** to open the LGPE.
3. Navigate to **User Configuration > Administrative Templates> Control Panel > Personalization**.
4. Double-click the **Screen saver timeout** option on the right-hand side.

![Using the LGPE to Change the Screen Saver Timeout Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Using-the-LGPE-to-Change-the-Screen-Saver-Timeout-Settings.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2145009/26400" target="_top" id="2145009">
  <img src="//a.impactradius-go.com/display-ad/26400-2145009" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2145009/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In the next window, select the **Enabled** option. From there, use the **arrow buttons** next to the **Seconds** box to select the duration of the screen saver.

 Press **Apply**, press **OK**, and then close the **LGPE**. Finally, restart your device to save these changes.

 If you want to disable the screen saver settings, here are the steps you need to follow:

1. Navigate to the **Personalization** option on the LGPE as per the previous steps.
2. Double-click the **Screen saver timeout** option and select either the **Disabled** or the **Not Configured** option.
3. Finally, press **Apply**, press **OK**, and then close the **LGPE**.

 Still looking for more tips on how to increase screen time on your laptop? We've got one more solution for you!

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938716/19272" target="_top" id="1938716">
  <img src="//a.impactradius-go.com/display-ad/19272-1938716" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938716/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Use the Registry Editor

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

 The Registry Editor can help you tweak the screen-saver timeout settings with ease. But it's quite a sensitive tool, so you should consider [backing up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first before you proceed.

 Now, here's how to configure the screen-saver timeout settings with the Registry Editor:

1. Press **Win + R** to open the Run command dialog box.
2. Type **Regedit** and press **OK** to open the Registry Editor.
3. Copy-paste the following command into the address bar:

HKEY_USERS\.DEFAULT\Control Panel\Desktop

 Locate the **ScreenSaveTimeOut** option on the right-hand side.

 If the key is missing, right-click on a blank space on the right and select **New > DWORD (32-bit) Value**. From there, rename the value as **ScreenSaveTimeOut** and press **Enter**.

 Next, double-click the **ScreenSaveTimeOut** value.

![Clicking the "ScreenSaveTimeOut" value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/clicking-the-screensavetimeout-value.jpg)

 Now, type the screen saver timeout duration (in seconds) in the **Value data** box. The default option is usually **900** seconds (15 minutes), but you can enter your desired value. Finally, click **OK** and then restart your device to save these changes.

## Tweak Your Lock Screen Timeout Settings Without a Hassle

 Wondering how to increase laptop screen time? Or do you want to lock your PC and ensure that it doesn’t fully go into sleep mode?

 Try increasing the lock screen and screen saver timeout settings using the solutions we’ve covered. From there, you can explore other cool things, such as how to automatically lock your Windows 11 PC when you’re away.

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
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-screenshots-of-success-decoding-post-viewer-demographics/"><u>[New] In 2024, Screenshots of Success Decoding Post Viewer Demographics</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-violating-copyrights-in-video-posting-what-are-the-consequences-in-2024/"><u>[New] Violating Copyrights in Video Posting What Are the Consequences, In 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/cold-climates-hot-wins-beijing-highlights/"><u>Cold Climates, Hot Wins Beijing Highlights</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/how-samsung-galaxy-fit-enhances-your-workout-routine-an-in-depth-review/"><u>How Samsung Galaxy Fit Enhances Your Workout Routine: An In-Depth Review</u></a></li>
<li><a href="https://android-location.techidaily.com/how-to-fake-gps-on-android-without-mock-location-for-your-tecno-camon-20-pro-5g-drfone-by-drfone-virtual/"><u>How to Fake GPS on Android without Mock Location For your Tecno Camon 20 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-properly-utilize-system-restore-on-microsoft-windows/"><u>How to Properly Utilize System Restore on Microsoft Windows</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-vivo-y27-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How PGSharp Save You from Ban While Spoofing Pokemon Go On Vivo Y27 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-vmware-start-issues-on-windows-11plusoses/"><u>Mastering VMware Start Issues on Windows 11+OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-steams-missing-files-hurdle-on-win11-os/"><u>Overcoming Steam's Missing Files Hurdle on Win11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/recovering-from-disrupted-asana-use-a-focused-approach-for-pc-users/"><u>Recovering From Disrupted Asana Use: A Focused Approach for PC Users</u></a></li>
<li><a href="https://app-tips.techidaily.com/recovering-lost-apple-id-credentials-for-itunes-backups-on-ios-devices/"><u>Recovering Lost Apple ID Credentials for iTunes Backups on iOS Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-for-save-failed-error-on-windows-systems/"><u>Remedy for Save Failed Error on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/skirting-microsofts-app-verification-system-on-pc/"><u>Skirting Microsoft's App Verification System on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-fix-xbox-game-download-failures-on-pc/"><u>Steps to Fix Xbox Game Download Failures on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/swiftly-undoing-changes-to-windows-app-configurations/"><u>Swiftly Undoing Changes to Windows App Configurations</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ltimate-guide-to-the-best-7-android-adblock-tools/"><u>The Ultimate Guide to the Best 7 Android AdBlock Tools</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/the-ultimate-tutorial-for-fb-360-streaming/"><u>The Ultimate Tutorial for FB 360 Streaming</u></a></li>
<li><a href="https://windows11.techidaily.com/top-windows-improvements-what-to-expect-from-feb23/"><u>Top Windows Improvements: What to Expect From Feb23</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-zte-nubia-flip-5g-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset ZTE Nubia Flip 5G | Dr.fone</u></a></li>
</ul></div>

