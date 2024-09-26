---
title: Steps to Enforce Local Policies to a Specific User in Windows 11
date: 2024-08-15T16:23:11.161Z
updated: 2024-08-16T16:23:11.161Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Enforce Local Policies to a Specific User in Windows 11
excerpt: This Article Describes Steps to Enforce Local Policies to a Specific User in Windows 11
keywords: Windows Policy Enforcement,Win11 User Restrictions,Local Policy Application,Policy Limits Setup,User Access Controls,Security Settings Windows 11,Policy Implementation Steps
thumbnail: https://thmb.techidaily.com/8e847bcd25e1bb956f9c0d5ed5c3e1ee40f922a7b0a9cd027835fb97af58ec95.jpg
---

## Steps to Enforce Local Policies to a Specific User in Windows 11

 When applying a local group policy to your PC, you may not want it to paint over all users. The answer is to apply local group policy to a specific user or set of users. This way you can control which features are accessible to specific user accounts.

 It also makes it easy to apply and modify controls and appearances for individual users, and you’ll get a quick glance at which policies apply to which users. Here’s how to apply local group policy to specific user accounts on Windows 10 and 11\.

## What Is the Local Group Policy?

 Group Policy is a Windows feature that gives you more control over the things user accounts are able to do and have access to. Changing Group Policy changes how the system works for different sets of users. We’ve covered [what Group Policy is and how you can use it](https://www.makeuseof.com/tag/windows-group-policy/), with examples, in much more detail separately.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
## How to Apply a Local Group Policy to a Specific User Account

 First off, you must have Windows 10 Pro, Enterprise, or Education editions to access the Local Group Policy Editor. Here’s how to set up what’s called a [Microsoft Saved Console](https://www.makeuseof.com/microsoft-management-console-how-to-use-it/) (MSC) for a specific user.

1. Press **Win + R**, type “mmc” into the box, and hit **OK**. This will open the Microsoft Management Console.
2. You will be presented with a UAC prompt. Click on **Yes**.
3. In the Microsoft Management Console window that opens up, go to **File > Add/Remove Snap-in**.  
![Adding a snap-in to the Microsoft Saved Console](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/01-add-remove-snap-in-microsoft-saved-console.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
4. Look for and select **Group Policy Object Editor**; click on the **Add** button to add it to the **Selected snap-ins** pane; and click **OK**.  
![Adding Group Policy Object Editor for a specific user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/02-add-group-policy-object-editor-microsoft-saved-console.jpg)
<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Next you will be asked to select a Group Policy Object. Click on **Browse**.  
![Select the Group Policy Object for a specific user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/03-select-group-policy-object.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->

1. Switch to the **Users** tab in the window that pops up.  
![Select user-specific Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/04-msc-select-user-group-policy.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2. Select the user account for which you want to create a custom Local Group Policy, then click **OK**.
3. Click on the **Finish** button, and then on the **Add or Remove Snap-ins** window, click **OK** on the bottom right.
4. The Group Policy for the specific user should appear in the console window.
5. Go to **File > Save As** and select a location you want to save the MSC. You can rename it here.
6. Once you’re done, click on the **Save** button.

 You’ve now created a user-specific Local Group Policy MSC. Whenever you need to configure policy settings that apply just to this specific user, double-click the file you just created and make the policy changes you need. Don’t forget to save the console settings when finished.

<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
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