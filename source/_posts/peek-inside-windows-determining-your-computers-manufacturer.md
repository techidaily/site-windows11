---
title: "Peek Inside Windows: Determining Your Computer's Manufacturer"
date: 2024-06-25T12:20:34.167Z
updated: 2024-06-26T12:20:34.167Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Peek Inside Windows: Determining Your Computer's Manufacturer"
excerpt: "This Article Describes Peek Inside Windows: Determining Your Computer's Manufacturer"
keywords: PC Brand Identification,Compute Make Discovery,System Vendor Check,Uncover PC Origin,Detect Device Maker,OS Manufacturer ID,Decrypt Machine Name
thumbnail: https://thmb.techidaily.com/57a65c2b181c750fb6364283d0997e4f78e21ce130fdd9928a29e2fa7b69ddd1.jpg
---

## Peek Inside Windows: Determining Your Computer's Manufacturer

 Whether you want to find the correct hardware upgrade for your computer or want to fix an issue, knowing about your computer model name can come in handy in various situations. Here are 6 quick ways to check your computer model name on Windows.

## 1\. Using the Settings App

![Checking System Name in the Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-name.jpg)

 The quickest way to check your computer model name and number is through the Settings app. Simply, launch the**Settings app** (see[how to open the Settings app on Windows](https://www.makeuseof.com/windows-ways-to-open-system-settings/) ) and choose**System** from the left sidebar. You'll see your computer model name at the top of the System window.

## 2\. Using the System Information App

 The System Information is the go-to place to[check your system information on Windows 11](https://www.makeuseof.com/windows-11-check-system-information/) . You can use it to know about your computer's hardware resources, components, and software environment.

 To see your computer model name using the System Information app, follow the below instructions:

1. Press the**Win + S** hotkeys to open**Windows Search.**
2. In the search bar, type**System Information** and choose**Open** from the right pane.  
![Typing System Information in Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-information.jpg)
3. Choose**System Summary** from the left sidebar.
4. Check the**System Model** row in the right pane to know about your computer model name.  
![Checking System Model in System Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-model.jpg)

## 3\. Using the DirectX Diagnostic Tool

 The DirectX Diagnostic Tool contains information about the DirectX components and drivers installed on your computer. You can also use this tool to get information like System model, BIOS, Processor, Memory, Page file, and more.

 Here's how to use the DirectX Diagnostic Tool to know about your system model name:

1. Use one of the[many ways to open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. In the text field, type**dxdiag** and click**OK.**
3. Click the**System** tab in the DirectX Diagnostic Tool.
4. Under the System Information section, you can check your computer model name next to the**System Model** option.  
![System Model option in the DirectX Diagnostic Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-model-option.jpg)

## 4\. Using the Command-Line Tools

 If you're an advanced Windows user, you can use the command-line tools, Windows PowerShell and Command Prompt, to know everything about your computer. Here's how to use the Command Prompt to check your computer model name:

1. Open the Windows Search, type**Command Prompt** in the search bar, and press Enter.
2. In the Command Prompt window, type**wmic csproduct get name** , and press Enter.  
![System model checking command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-model-checking-command.jpg)

You'll see the model name on the console screen.

 Now, to view the model name using Windows PowerShell, launch Windows PowerShell, type the following command, and press Enter.

`Get-CimInstance -ClassName Win32_ComputerSystem`

![Command to Check System name in Windows PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/command-to-check-system-name.jpg)

 In case you want to check your computer serial number, execute the following command in the PowerShell window.

`Get-CimInstance -ClassName Win32_bios`

![Command to Check System Serial number in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/command-to-check-system-serial-number.jpg)

## 5\. Using the Manufacturer's Assistant App

![Checking System name using HP Support Assistant](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/hp-support-assistant.jpg)

 Most manufacturers nowadays offer an assistant app using which you can check your computer model name and number. For instance, if you're using an HP laptop, you can download the[HP Support Assistant app](https://support.hp.com/us-en/help/hp-support-assistant) to know everything about your computer.

 Similarly, you can download the assistant app of your manufacturer to check your computer's name.

## 6\. By Entering the BIOS

 The Basic Input / Output System, aka BIOS, lets you configure basic computer settings like boot order, hardware components, and more. You can also use the BIOS menu to know every tiny detail about your computer.

 Here's how to[enter the BIOS menu on Windows](https://www.makeuseof.com/tag/enter-bios-computer/) and check your computer model name:

1. Open the Settings app, and choose**Windows Update** from the left sidebar.
2. Choose the**Advanced options.**
3. Under**Additional options,** select the**Recovery** option.
4. Click the**Restart now** button next to**Advanced startup.** Your computer will not boot into Recovery mode.  
![Restart now button next to Advanced startup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/restart-now-button.jpg)
5. Navigate to**Troubleshoot** \>**Advanced options** \>**UEFI Firmware Settings** \>**Restart.**
6. Usually, your computer will now boot straight into UEFI BIOS. But in some manufacturers like HP, you'll be welcomed with a**Startup** **Menu.** Choose**System Information** from the menu.  
![Choosing System Information from the Startup menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/choosing-system-information.JPG)
7. You can check your computer name in the System Information section.  
![Checking Product name in System Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/checking-product-name.JPG)

## Get to Know Your Computer's Model on Windows

 These were all the working ways using which you can know your computer model name. However there are many other methods to check the name, but the ones mentioned above are among the quickest and easiest.

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
<li><a href="https://windows11.techidaily.com/techniques-to-rectify-unresponsive-windows-key/"><u>Techniques to Rectify Unresponsive Windows Key</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-flush-for-your-win11-dns-cache/"><u>The Ultimate Flush for Your Win11 DNS Cache</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-quieting-geforces-visual-flourishes/"><u>Step-By-Step: Quieting GeForce's Visual Flourishes</u></a></li>
<li><a href="https://windows11.techidaily.com/win11s-unnecessary-filler-heres-how-to-tackle-it/"><u>Win11's Unnecessary Filler? Here’s How To Tackle It</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-recovery-overcoming-black-screen-issues-in-wins/"><u>Swift Recovery: Overcoming Black-Screen Issues in Wins</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-hd-strategy-for-classics-gaming-on-windows-via-scummvm/"><u>The Ultimate HD Strategy for Classics Gaming on Windows via ScummVM</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-performance-gauges-for-pcs/"><u>Efficient Performance Gauges for PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/facing-down-rounded-corners-in-windows-11/"><u>Facing Down Rounded Corners in Windows 11</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-avoiding-youtubes-controversial-scrutiny/"><u>In 2024, Avoiding YouTube's Controversial Scrutiny</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-the-ultimate-gag-reel-collection-comical-cells-and-cell-blocks-on-facebook/"><u>[New] The Ultimate Gag Reel Collection  Comical Cells and Cell Blocks on Facebook</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-enhancing-video-performance-on-the-social-platform-for-2024/"><u>[Updated] Enhancing Video Performance on the Social Platform for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-dose-life360-notify-me-when-someone-checks-my-location-on-realme-c55-drfone-by-drfone-virtual-android/"><u>In 2024, Dose Life360 Notify Me When Someone Checks My Location On Realme C55? | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/youtube-revenue-the-unfavorable-guidelines-for-2024/"><u>YouTube Revenue  The Unfavorable Guidelines for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-motorola-s-lock-screen-pattern-pin-or-password-by-drfone-android-unlock-android-unlock/"><u>How to bypass Motorola ’s lock screen pattern, PIN or password</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/free-video-invitation-templates-and-makers-events-for-2024/"><u>Free Video Invitation Templates and Makers Events for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-fix-iphone-6s-unavailable-issue-with-ease-by-drfone-ios/"><u>How To Fix iPhone 6s Unavailable Issue With Ease</u></a></li>
<li><a href="https://extra-information.techidaily.com/quick-launch-lines-a-practical-roadmap-for-product-review-channel-founders/"><u>Quick Launch Lines  A Practical Roadmap for Product Review Channel Founders</u></a></li>
</ul></div>
