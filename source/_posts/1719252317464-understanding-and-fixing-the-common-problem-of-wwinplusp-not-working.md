---
title: Understanding and Fixing the Common Problem of WWin+P Not Working
date: 2025-01-26T17:30:26.371Z
updated: 2025-01-30T05:44:32.529Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Understanding and Fixing the Common Problem of WWin+P Not Working
excerpt: This Article Describes Understanding and Fixing the Common Problem of WWin+P Not Working
keywords: WWinNoP Fix Guide,PauseWWinError Resolution,NonFunctionalWWin+P,TroubleshootWWinIssues,EnableWWinPlayback,CorrectWWinPlusP Errors,StopWWin+P Failures
thumbnail: https://thmb.techidaily.com/41df33583a82ea2d9923ca08fb1de828ddad2dc59980553349e15164e2adbb30.jpg
---

## Understanding and Fixing the Common Problem of WWin+P Not Working

 When you press **Win + P** on Windows, you should see a flyout appear that contains options to switch your display. But, sometimes, when you press this shortcut, nothing happens, leaving you unable to change displays easily and quickly. Luckily, we're going to show you some fixes you can try to get the **Win + P** shortcut to work again.

## 1\. Troubleshoot the Keyboard

 Before we get to the other fixes, we highly recommend you try [troubleshooting the keyboard](https://www.makeuseof.com/fix-keyboard-keys-not-working-windows/). This includes checking if the keys are damaged, running the Keyboard Troubleshooter, and updating and reinstalling the keyboard driver.

 For the **Win + P** shortcut in particular, if updating and reinstalling the keyboard driver doesn't work, we recommend doing the same to the display driver as well.

 Another generic fix you can try is [performing an SFC scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) to find and replace any corrupted or damaged system files on your PC that can cause **Win** \+ **P** to not work. Also, if you managed to [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) when the shortcut was working, you can revert your PC's settings to that restore point to potentially fix the issue.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fHWdQw1gRyI?si=ve9wZnPupiooLThG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Turn Off Game Mode

 Game Mode on Windows is a feature that turns off programs and tasks running in the background. That way, your PC has more resources to dedicate toward a smooth gaming experience. However, this feature is known to cause conflicts with the keyboard, and you can fix this by turning it off.

 To do that, press **Win** \+ **S** to bring up Windows Search, type **game mode settings** in the text box, and then click on **Game Mode settings** when it appears in the results.

![Game Mode settings in Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/game-mode-settings-windows-search.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Rxyki8-Y630?si=dHLkIxG59zdlZeN0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If the **Game Mode** toggle is **On**, click on it to set it to the **Off** position.

![Turn Off the Game Mode From Game Mode Settings in Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/1-turn-off-the-game-mode-from-game-mode-settings-in-windows-settings-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1dR4tF3VgyU?si=AJipgqZsNNxsRsBW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now, try the **Win + P** shortcut again to see if the display switch options will show up.

## 3\. Make Sure the Action Center Is Working

 If the Action Center (Quick Settings on Windows 11) isn't working, it can cause the **Win + P** shortcut to not work. Try clicking on the Action Center and see if it will come up. If it doesn't, you can learn [how to fix the Action Center](https://www.makeuseof.com/windows-11-action-center-not-opening/)[when it is not opening](http://www.makeuseof.com/windows-11-action-center-not-opening/).

 Usually, it could just be that you, someone else, or a virus has somehow disabled the Action Center. In that case, you just need to re-enable it to get the shortcut to work again. If the reason is a virus, fire up your antivirus and scan your PC.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MTb4xHzeQEk?si=9Sqq-gFWnHc8x3_P" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Try a Different User Account

 If your user account on Windows is corrupted, it can cause certain things to not work, including the **Win + P** shortcut. To verify whether your account is the problem or not, sign out and sign in to a different user account on your PC. Then, try the shortcut on the other user account, and if it works, you can use that one when you need to bring up the display switch options.

 Don't have another user account on your Windows computer? If that's the case, you can learn how to [create a local account on Windows 10](https://www.makeuseof.com/ways-to-create-local-user-account-windows/) or [create a local account on Windows 11](https://www.makeuseof.com/windows-11-create-local-user-account/). Afterward, you can test if the shortcut is working on the user account you just created.

## 5\. Create a Display Switch Shortcut

 If nothing you've done so far has worked, it might be time to use a workaround. One thing you can do is create a display switch shortcut that you can use to switch the display on your Windows PC.

 To do that, right-click an empty part of your Desktop and select **New > Shortcut**.

![The New and Shortcut options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/new-shortcut-options.jpg)

 The table below shows the locations of the various shortcuts for the display options:

| Display Option     | Shortcut Location                               |
| ------------------ | ----------------------------------------------- |
| PC screen only     | %windir%\\System32\\DisplaySwitch.exe /internal |
| Duplicate          | %windir%\\System32\\DisplaySwitch.exe /clone    |
| Extend             | %windir%\\System32\\DisplaySwitch.exe /extend   |
| Second screen only | %windir%\\System32\\DisplaySwitch.exe /external |

 Depending on the option you want to use, enter the appropriate shortcut location in the text box of the Create Shortcut wizard and click **Next**.

![entering the shortcut path for display switch in the Create Shortcut wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-shortcut-display-switch-shortcut.jpg)

 Give the display switch shortcut a name and click **Finish**.

![naming the display switch shortcut in the Create Shortcut wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/naming-display-switch-shortcut.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uV3vm805eX0?si=YSPcsFxBcJmoxLsU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You will find the display switch shortcut on the desktop, and when you double-click it, it will switch to the desired display option. You can create display switches for each option if you want.

## Get Win + P Working Again on Windows

 When you want to switch displays on Windows, the **Win + P** shortcut comes in handy. If it's not working, you can try the fixes above to get it to work. And if nothing helps, try creating a display switch shortcut as we've shown you.

 If you don't want to use the display switch shortcut, and you're sure there's nothing wrong with your keyboard, you can try the nuclear option: resetting your Windows PC.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-blue.techidaily.com/new-in-2024-harness-the-power-of-iphones-shutter-speed-for-motion-blurs/"><u>[New] In 2024, Harness the Power of iPhone’s Shutter Speed for Motion Blurs</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-scriptwriting-the-art-of-utilizing-slug-lines/"><u>[New] Scriptwriting The Art of Utilizing Slug Lines</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-clean-slates-mastering-the-eraser-tool-in-photoshop-for-2024/"><u>[Updated] Clean Slates Mastering the Eraser Tool in Photoshop for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/boost-your-creative-edge-on-instagram-with-more-free-filters/"><u>Boost Your Creative Edge on Instagram with More Free Filters</u></a></li>
<li><a href="https://vp-tips.techidaily.com/enhance-your-media-masterpiece-with-canvas-soundscape-edition-for-2024/"><u>Enhance Your Media Masterpiece with Canva's Soundscape Edition for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/expeditious-windows-11-app-accessibility/"><u>Expeditious Windows 11 App Accessibility</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/forgot-iphone-8-plus-password-here-are-the-best-solutions-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>Forgot iPhone 8 Plus Password? – Here are the Best Solutions | Stellar</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-enable-controlled-folder-access-in-windows-11-and-11/"><u>How to Enable Controlled Folder Access in Windows 11 & 11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-unlock-oneplus-nord-n30-se-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>In 2024, Unlock OnePlus Nord N30 SE Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaiming-your-controllers-functionality-in-windows/"><u>Reclaiming Your Controller’s Functionality in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/reimagining-your-windows-profile-a-new-username-approach/"><u>Reimagining Your Windows Profile: A New UserName Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/reversing-file-locks-on-windows-os/"><u>Reversing File Locks on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-global-mouse-navigation-made-simple-with-powertoys/"><u>Seamless Global Mouse Navigation Made Simple with PowerToys</u></a></li>
</ul></div>

