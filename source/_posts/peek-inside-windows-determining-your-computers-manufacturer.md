---
title: "Peek Inside Windows: Determining Your Computer's Manufacturer"
date: 2024-08-15T15:52:03.291Z
updated: 2024-08-16T15:52:03.291Z
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

 The quickest way to check your computer model name and number is through the Settings app. Simply, launch the**Settings app** (see [how to open the Settings app on Windows](https://www.makeuseof.com/windows-ways-to-open-system-settings/) ) and choose**System** from the left sidebar. You'll see your computer model name at the top of the System window.

## 2\. Using the System Information App

 The System Information is the go-to place to [check your system information on Windows 11](https://www.makeuseof.com/windows-11-check-system-information/) . You can use it to know about your computer's hardware resources, components, and software environment.

 To see your computer model name using the System Information app, follow the below instructions:

1. Press the**Win + S** hotkeys to open**Windows Search.**
2. In the search bar, type**System Information** and choose**Open** from the right pane.  
![Typing System Information in Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-information.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->
3. Choose**System Summary** from the left sidebar.
4. Check the**System Model** row in the right pane to know about your computer model name.  
![Checking System Model in System Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-model.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
## 3\. Using the DirectX Diagnostic Tool

 The DirectX Diagnostic Tool contains information about the DirectX components and drivers installed on your computer. You can also use this tool to get information like System model, BIOS, Processor, Memory, Page file, and more.

 Here's how to use the DirectX Diagnostic Tool to know about your system model name:

1. Use one of the [many ways to open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. In the text field, type**dxdiag** and click**OK.**
3. Click the**System** tab in the DirectX Diagnostic Tool.
4. Under the System Information section, you can check your computer model name next to the**System Model** option.  
![System Model option in the DirectX Diagnostic Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-model-option.jpg)

## 4\. Using the Command-Line Tools

 If you're an advanced Windows user, you can use the command-line tools, Windows PowerShell and Command Prompt, to know everything about your computer. Here's how to use the Command Prompt to check your computer model name:

1. Open the Windows Search, type**Command Prompt** in the search bar, and press Enter.
2. In the Command Prompt window, type**wmic csproduct get name** , and press Enter.  
![System model checking command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-model-checking-command.jpg)
<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

You'll see the model name on the console screen.

 Now, to view the model name using Windows PowerShell, launch Windows PowerShell, type the following command, and press Enter.

`Get-CimInstance -ClassName Win32_ComputerSystem`

![Command to Check System name in Windows PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/command-to-check-system-name.jpg)

 In case you want to check your computer serial number, execute the following command in the PowerShell window.

`Get-CimInstance -ClassName Win32_bios`

![Command to Check System Serial number in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/command-to-check-system-serial-number.jpg)
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Using the Manufacturer's Assistant App

![Checking System name using HP Support Assistant](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/hp-support-assistant.jpg)

 Most manufacturers nowadays offer an assistant app using which you can check your computer model name and number. For instance, if you're using an HP laptop, you can download the [HP Support Assistant app](https://support.hp.com/us-en/help/hp-support-assistant) to know everything about your computer.

 Similarly, you can download the assistant app of your manufacturer to check your computer's name.

## 6\. By Entering the BIOS

 The Basic Input / Output System, aka BIOS, lets you configure basic computer settings like boot order, hardware components, and more. You can also use the BIOS menu to know every tiny detail about your computer.

 Here's how to [enter the BIOS menu on Windows](https://www.makeuseof.com/tag/enter-bios-computer/) and check your computer model name:

1. Open the Settings app, and choose**Windows Update** from the left sidebar.
2. Choose the**Advanced options.**
3. Under**Additional options,** select the**Recovery** option.
4. Click the**Restart now** button next to**Advanced startup.** Your computer will not boot into Recovery mode.  
![Restart now button next to Advanced startup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/restart-now-button.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->
5. Navigate to**Troubleshoot** \>**Advanced options** \>**UEFI Firmware Settings** \>**Restart.**
6. Usually, your computer will now boot straight into UEFI BIOS. But in some manufacturers like HP, you'll be welcomed with a**Startup** **Menu.** Choose**System Information** from the menu.  
![Choosing System Information from the Startup menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/choosing-system-information.JPG)
<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. You can check your computer name in the System Information section.  
![Checking Product name in System Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/checking-product-name.JPG)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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






