---
title: Executing Policies for a Single-User Target in Modern Windows Systems
date: 2024-08-15T16:09:17.466Z
updated: 2024-08-16T16:09:17.466Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Executing Policies for a Single-User Target in Modern Windows Systems
excerpt: This Article Describes Executing Policies for a Single-User Target in Modern Windows Systems
keywords: Win System Policy Execution,Single-User Policy Guide,User Targeted Policies,Modern Windows Management,Policy Framework for Users,Single-User Security Setting,Windows Systems Policy Implementation
thumbnail: https://thmb.techidaily.com/60a050976608e9140d90809a0ac2529ef41e9995b243e26e295a790742b88b8b.jpg
---

## Executing Policies for a Single-User Target in Modern Windows Systems

 When applying a local group policy to your PC, you may not want it to paint over all users. The answer is to apply local group policy to a specific user or set of users. This way you can control which features are accessible to specific user accounts.

 It also makes it easy to apply and modify controls and appearances for individual users, and you’ll get a quick glance at which policies apply to which users. Here’s how to apply local group policy to specific user accounts on Windows 10 and 11\.

## What Is the Local Group Policy?

 Group Policy is a Windows feature that gives you more control over the things user accounts are able to do and have access to. Changing Group Policy changes how the system works for different sets of users. We’ve covered [what Group Policy is and how you can use it](https://www.makeuseof.com/tag/windows-group-policy/), with examples, in much more detail separately.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Apply a Local Group Policy to a Specific User Account

 First off, you must have Windows 10 Pro, Enterprise, or Education editions to access the Local Group Policy Editor. Here’s how to set up what’s called a [Microsoft Saved Console](https://www.makeuseof.com/microsoft-management-console-how-to-use-it/) (MSC) for a specific user.

1. Press **Win + R**, type “mmc” into the box, and hit **OK**. This will open the Microsoft Management Console.
2. You will be presented with a UAC prompt. Click on **Yes**.
3. In the Microsoft Management Console window that opens up, go to **File > Add/Remove Snap-in**.  
![Adding a snap-in to the Microsoft Saved Console](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/01-add-remove-snap-in-microsoft-saved-console.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->
4. Look for and select **Group Policy Object Editor**; click on the **Add** button to add it to the **Selected snap-ins** pane; and click **OK**.  
![Adding Group Policy Object Editor for a specific user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/02-add-group-policy-object-editor-microsoft-saved-console.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->
5. Next you will be asked to select a Group Policy Object. Click on **Browse**.  
![Select the Group Policy Object for a specific user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/03-select-group-policy-object.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->

1. Switch to the **Users** tab in the window that pops up.  
![Select user-specific Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/04-msc-select-user-group-policy.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->
2. Select the user account for which you want to create a custom Local Group Policy, then click **OK**.
3. Click on the **Finish** button, and then on the **Add or Remove Snap-ins** window, click **OK** on the bottom right.
4. The Group Policy for the specific user should appear in the console window.
5. Go to **File > Save As** and select a location you want to save the MSC. You can rename it here.
6. Once you’re done, click on the **Save** button.

 You’ve now created a user-specific Local Group Policy MSC. Whenever you need to configure policy settings that apply just to this specific user, double-click the file you just created and make the policy changes you need. Don’t forget to save the console settings when finished.

<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Easily Control What Windows Users Have Access To

 By utilizing Local Group Policy, you have greater control over what functionality you accord to a specific user or set of users. A simple change at this level can make your job much easier when applying restrictions and granting freedoms to Windows users.

 It also makes it easy to apply and modify controls and appearances for individual users, and you’ll get a quick glance at which policies apply to which users. Here’s how to apply local group policy to specific user accounts on Windows 10 and 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>



