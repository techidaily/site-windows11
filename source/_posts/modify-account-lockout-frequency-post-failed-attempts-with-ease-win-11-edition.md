---
title: Modify Account Lockout Frequency Post Failed Attempts with Ease, Win 11 Edition
date: 2024-09-30T02:58:44.435Z
updated: 2024-10-07T07:24:15.870Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Modify Account Lockout Frequency Post Failed Attempts with Ease, Win 11 Edition
excerpt: This Article Describes Modify Account Lockout Frequency Post Failed Attempts with Ease, Win 11 Edition
keywords: Account Lockout Control,Easy Unlock Limit Adjustment,Reset Lock Frequency Settings,Windows 11 Security Tweaks,Increase Failed Attempt Tolerance,Modify Unlock Threshold,Easy Account Lockout Adjustment
thumbnail: https://thmb.techidaily.com/200bad50912773155a76642b85b00bc52b52d7ab3430de1df3acbec7a4ce0fd7.jpg
---

## Modify Account Lockout Frequency Post Failed Attempts with Ease, Win 11 Edition

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  
![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  
![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2129738/7443" target="_top" id="2129738">
  <img src="//a.impactradius-go.com/display-ad/7443-2129738" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2129738/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037345/7443" target="_top" id="2037345">
  <img src="//a.impactradius-go.com/display-ad/7443-2037345" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037345/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136626/26400" target="_top" id="2136626">
  <img src="//a.impactradius-go.com/display-ad/26400-2136626" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136626/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484910/16446" target="_top" id="1484910">
  <img src="//a.impactradius-go.com/display-ad/16446-1484910" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484910/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-links.techidaily.com/2024-approved-elevate-your-gaming-experience-with-unique-sound-alteration-techniques-for-a-competitive-edge-no-cost/"><u>2024 Approved Elevate Your Gaming Experience with Unique Sound Alteration Techniques for a Competitive Edge (No Cost!)</u></a></li>
<li><a href="https://techtrends.techidaily.com/easy-setup-enjoy-hulu-entertainment-on-your-lg-smart-television/"><u>Easy Setup: Enjoy Hulu Entertainment on Your LG Smart Television</u></a></li>
<li><a href="https://windows11.techidaily.com/guides-to-mend-failing-defragmentation-software-in-os/"><u>Guides to Mend Failing Defragmentation Software in OS</u></a></li>
<li><a href="https://windows11.techidaily.com/halt-automatic-wallpapers-on-modern-windows-systems/"><u>Halt Automatic Wallpapers on Modern Windows Systems</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-get-and-use-pokemon-go-promo-codes-on-infinix-hot-30-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Get and Use Pokemon Go Promo Codes On Infinix Hot 30 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/integrating-android-titles-on-pc-seamless-gameplay-through-windows-and-google/"><u>Integrating Android Titles on PC: Seamless Gameplay Through Windows & Google</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/logitech-keyboard-shortcuts-capturing-your-screen-effortlessly/"><u>Logitech Keyboard Shortcuts: Capturing Your Screen Effortlessly</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-route-to-enabling-the-dark-mode-in-notepad-on-win-11/"><u>Quick Route to Enabling the Dark Mode in Notepad on Win 11</u></a></li>
<li><a href="https://win-info.techidaily.com/revive-your-aging-pc-with-these-cost-free-tricks-before-upgrading-to-windows-10-zdnet/"><u>Revive Your Aging PC with These Cost-Free Tricks Before Upgrading to Windows 10 - ZDNet</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-access-with-shortcuts-microsoft-store-uwp-apps/"><u>Seamless Access with Shortcuts: Microsoft Store (UWP) Apps</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ful-conversion-of-youtube-videos-to-interactive-gif-artistry/"><u>Skillful Conversion of YouTube Videos to Interactive GIF Artistry</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-steps-what-to-do-when-your-laptops-touchpad-fails-to-respond/"><u>Solution Steps: What to Do When Your Laptop's Touchpad Fails to Respond</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-freezing-or-slow-downloads-in-windows/"><u>Steps to Resolve Freezing or Slow Downloads in Windows</u></a></li>
<li><a href="https://tech-haven.techidaily.com/understanding-the-chatgpt-tokens-cap-how-much-can-you-send-at-once/"><u>Understanding the ChatGPT Tokens Cap: How Much Can You Send at Once?</u></a></li>
<li><a href="https://windows11.techidaily.com/unfreezing-deadlocks-fixing-windows-semaphore-expired-error/"><u>Unfreezing Deadlocks: Fixing Windows' 'Semaphore Expired' Error</u></a></li>
</ul></div>

