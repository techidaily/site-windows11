---
title: How to Enable or Disable In-Hand Typing Windows 10
date: 2024-12-06T20:35:32.576Z
updated: 2024-12-10T16:36:28.227Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Enable or Disable In-Hand Typing Windows 10
excerpt: This Article Describes How to Enable or Disable In-Hand Typing Windows 10
keywords: Windows 10 Hint Typing,Type In Windows 10,In-Hand Keyboard Windows,Enable Windows Typing,Disable Windows Input,In-Hand Typing Settings,Windows 10 Typing Control
thumbnail: https://thmb.techidaily.com/6f98ed833e99780ec633017bfd02ba19a6f592b2168edc5e24a71f77a22d913e.jpg
---

## How to Enable or Disable In-Hand Typing Windows 10

 The fingertip writing feature in Windows allows users to write on a touch-enabled device using their fingertips, without a stylus or a pen. You can use it to input text directly into documents or applications easily.

 Below, we talk about the different ways to enable or disable the fingertip writing feature in the Handwriting Panel in Windows.

## 1\. Use the Settings App to Enable/Disable Fingertip Writing

 The easiest, most straightforward way to enable or disable the fingertip writing feature is by using the Settings app. You can make these changes in the Bluetooth & devices section and do not need to have administrative access to the system as well.

Here is how you can proceed:

1. Press the**Win** +**I** keys to open the Settings app.
2. Choose**Bluetooth & devices** from the left pane.
3. Move to the right side of the window and click on**Pen & Windows Ink** .  
![Access the Pen & Windows Ink section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/pen-and-windows-ink.jpg)
4. Expand the**Use your handwriting to enter text** section under Handwriting.
5. Checkmark the box associated with**Write with your fingertip** .  
![Write with your fingertip option in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/write-with-you-fingertip-1.jpg)

 You can now close the Settings app if you want. To disable the feature in the future, simply follow these steps again and uncheck the Write with your fingertip option.

## 2\. Enable/Disable Fingertip Writing via the Registry Editor

 If the "Write with your fingertip" option is disabled in the Settings app, you can also make these changes using the Registry Editor.

 Windows Registry is a powerful tool that is typically used to manage important system settings and configurations. This is an administrative-level utility, so you will need to log into your administrator account if you are using a standard user account to use it. You can also[convert your standard user account into an administrator account](https://www.makeuseof.com/windows-standard-adminstrator-account-differences/) .

 Once you have logged into Windows as an administrator,[create a Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) , just to be safe.

Then, proceed with these steps:

1. Press the**Win** +**R** keys together to open Run.
2. Type "regedit" in the text field of Run and click**Enter** .
3. Click**Yes** in the User Account Control prompt.
4. Once you have launced the Registry Editor, navigate to the location below:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\TabletTip`
5. Right-click on**TableTip** and choose**New** \>**Key** .  
![Create a new key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/create-new-key.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hZsnjxeSh1U?si=hZIfzQPDNX5KtOCg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Name this key as EmbeddedInkControl.
2. Now, move to the right pane and right-click anywhere on an empty space.
3. Choose**New** \>**DWORD (32-bit) Value** .
4. Rename this key as EnableInkingWithTouch.
5. Double-click on**EnableInkingWithTouch** and under Value data, type 1\. This will enable the fingertip writing feature.  
![Enter 1 under Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enableinking-with-touch.jpg)
6. Click**OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/it8VkxDUdAc?si=ef6VZWR7kW4P9ikh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Close the Registry Editor and restart your computer.

 Upon reboot, you should be able to use the fingertip writing feature. To disable this feature, follow the aforementioned steps again and change the value data of the EnableInkingWithTouch key to 0.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0pSRlspzW-A?si=A82G3Yxwj_31cKDq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Enable/Disable Fingertip Writing Via the Group Policy Editor

 The third way of enabling/disabling the fingertip writing feature is via the Group Policy Editor. Like the Windows Registry, this utility also allows the administrators to manage the advanced-level system settings in Windows.

 To use the Group Policy Editor for managing the fingertip writing feature, follow these steps:

1. Press the**Win** +**R** keys simultaneously to open Run.
2. Type "gpedit.msc" in Run and click**Enter** .
3. Click**Yes** in the User Account Control prompt.
4. Once you are in the Group Policy Editor, navigate to the location below:  
`Computer Configuration > Administrative Templates > Windows Components > Handwriting`
5. Locate the**Handwriting Panel Default Mode Docked** policy in the right pane and double-click on it.  
![Access the Handwriting panel default mode docked policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/handwriting-policy.jpg)
6. To enable the feature, choose**Not configured** . If you want to disable it, choose**Disable** .  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yDuvbv0QOYI?si=byottcEM_Rrvi4EL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Enable the handwriting panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-handwriting-panel-1.jpg)
7. Click**Apply** \>**OK** to save the changes.

 You can now close the Group Policy Editor and begin using the fingertip writing feature with ease.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_SbYznUy_zY?si=ThBkP934r3mizi48" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Use Your Fingertips to Write Away on Windows

 The fingertip writing feature can be a great tool for those who do not prefer using a stylus or a writing pen. You can use it to take handwritten notes and have them automatically converted into digital text which you then further organize and share.

 The three methods we have listed above should help you manage this feature easily. However, it is important to exercise caution and create a backup before you make any changes to the system settings and configurations.

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
<li><a href="https://solve-news.techidaily.com/2024-iphone-iosipados/"><u>2024新築版: IPhoneユーザにお勧め!カット、結合、変換機能が完成された最新音声編集アプリ - iOSとiPadOSで使用</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-infinix-hot-40i-drfone-by-drfone-virtual-android/"><u>9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Infinix Hot 40i | Dr.fone</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/210642558-9781736365120-discovering-your-excellence-within/"><u>Discovering Your Excellence Within | Free Book</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-to-resolve-powerpoint-print-issues-on-windows-os/"><u>Essential Tips to Resolve PowerPoint Print Issues on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-eliminate-call-not-successful-problems-in-windows-malwarebytes/"><u>How to Eliminate Call Not Successful Problems in Windows Malwarebytes</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-4-feasible-ways-to-fake-location-on-facebook-for-your-samsung-galaxy-m14-4g-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Feasible Ways to Fake Location on Facebook For your Samsung Galaxy M14 4G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-resuscitate-flaky-slack-notifications/"><u>Methods to Resuscitate Flaky Slack Notifications</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/1721268197582-photo-perfect-stellar-repair-app/"><u>Photo Perfect Stellar Repair App: すぐ届ける購入オプション</u></a></li>
<li><a href="https://review-topics.techidaily.com/proven-ways-in-how-to-hide-location-on-life360-for-honor-90-lite-drfone-by-drfone-virtual-android/"><u>Proven Ways in How To Hide Location on Life360 For Honor 90 Lite | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/resize-images-in-win11-a-step-by-step/"><u>Resize Images in Win11: A Step-by-Step</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-reversing-fatal-application-crashes/"><u>Techniques for Reversing Fatal Application Crashes</u></a></li>
<li><a href="https://some-guidance.techidaily.com/transforming-social-interactions-on-xbox-mastering-zoom-for-2024/"><u>Transforming Social Interactions on Xbox Mastering Zoom for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/tutorial-initiating-clipboard-operations-within-microsoft-edges-protected-environment-windows-11/"><u>Tutorial: Initiating Clipboard Operations Within Microsoft Edge's Protected Environment, Windows 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/unpacking-the-3dr-experience-from-a-single-individual/"><u>Unpacking the '3DR' Experience From a Single Individual</u></a></li>
<li><a href="https://technical-tips.techidaily.com/unraveling-the-mystery-behind-oleaut32dll-absence-and-how-to-rectify-it/"><u>Unraveling the Mystery Behind OleAut32.dll Absence & How to Rectify It</u></a></li>
</ul></div>

