---
title: Reshaping Administration Workflow in the Windows Ecosystem
date: 2025-02-25T04:55:25.091Z
updated: 2025-03-02T07:14:12.322Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reshaping Administration Workflow in the Windows Ecosystem
excerpt: This Article Describes Reshaping Administration Workflow in the Windows Ecosystem
keywords: Win Admin Workflow Update,Windows Admin Processing,System Admin Optimization,Windows Eco Admin Shift,Streamlined Windows Administration,Administrative Workflow Reform,Windows Workflow Management
thumbnail: https://thmb.techidaily.com/de2a2439a12942f0b9808810580359ed4223c732cf24aad5cc401c9c124e67ae.jpeg
---

## Reshaping Administration Workflow in the Windows Ecosystem

 If you’ve ever tried running a program on Windows as an administrator, you’ve probably come across a prompt asking you to either give or deny it permission to make high-level changes. That’s User Access Control (UAC) in action, and it adds an extra layer of security when a program or task is seeking elevated privileges. This gives you the chance to stop unwanted or malicious software from making changes on your PC.

 As an administrator, you can change how UAC behaves. In this guide, we’re going to show you how to do that using the Local Group Policy Editor and Registry Editor.

## What Behaviors Does UAC Have for Administrators?

 Before you go about changing the way UAC acts for administrators, it helps to know what behaviors you can choose and what they mean. We’re going to list them below, along with the definitions that are listed on [Microsoft Learn](https://learn.microsoft.com/en-us/windows/security/threat-protection/security-policy-settings/user-account-control-behavior-of-the-elevation-prompt-for-administrators-in-admin-approval-mode).

 Here’s what you can choose:

* **Elevate without prompting**: Assumes that the administrator will permit an operation that requires elevation, and more consent or credentials aren't required. This minimizes the protection that is provided by UAC.
* **Prompt for credentials on the secure desktop**: When an operation requires elevation of privilege, the user is prompted on the secure desktop to enter a privileged username and password. If the user enters valid credentials, the operation continues with the user's highest available privilege.
* **Prompt for consent on the secure desktop**: When an operation requires elevation of privilege, the user is prompted on the secure desktop to select **Permit** or **Deny**. If the user selects **Permit**, the operation continues with the user's highest available privilege.
* **Prompt for credentials**: An operation that requires elevation of privilege prompts the administrator to type the username and password. If the administrator enters valid credentials, the operation continues with the applicable privilege.
* **Prompt for consent**: An operation that requires elevation of privilege prompts the administrator to select **Permit** or **Deny**. If the administrator selects **Permit**, the operation continues with the administrator's highest available privilege.
* **Prompt for consent for non-Windows binaries**: This prompt for consent is the default. When an operation for a non-Microsoft application requires elevation of privilege, the user is prompted on the secure desktop to select **Permit** or **Deny**. If the user selects **Permit**, the operation continues with the user's highest available privilege.

 Now that you're familiar with the UAC behaviors for administrators, let’s see how to change them.

## Changing UAC Behavior for Administrators in the Local Group Policy Editor

 To change the UAC behavior for admins using the Local Group Policy Editor (LGPE), start by pressing **Win + R**, typing **gpedit.msc** in Windows Run, and hitting the **Enter** key to [open the LGPE on Windows](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

![Gpedit In Run Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Gpedit-In-Run-Menu.jpg)

 In the left panel, navigate to **Configuration > Windows Settings > Security Settings > Local Policies > Security Options**. In the right panel, double-click the **User Account Control: Behavior of the elevation prompt for administrators in Admin Approval Mode** policy to access its **Properties** window.

![the UAC behavior for admin policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/uac-behavior-admin-policy-local-group-policy-editor.jpg)

 Click on the dropdown and select the UAC behavior you want.

![Editing the UAC behavior for admin policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/editing-uac-behavior-admin-policy-local-group-policy-editor.jpg)

 To apply and save the changes, click on **OK**.

## Changing UAC Behavior for Administrators in the Registry Editor

 To change the UAC behavior for administrators using the Registry Editor, start by pressing **Win + R**, typing **regedit** in Windows Run, and hitting the **Enter** key.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

 In the UAC prompt, click **Yes** to [open the Registry Editor on Windows](https://www.makeuseof.com/windows-11-local-security-policy/).

 Changing settings in the Registry Editor can impact the performance of your computer negatively if you make a mistake. To make sure you always have a way to revert the changes, we recommend learning [how to back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/).

 In the navigation panel on the left, head to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Policies > System**. In the right panel, double-click the **ConsentPromptBehaviorAdmin** value to modify it.

![The ConsentPromptBehaviorAdmin value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/consentpromptbehavior-value-registry-editor.jpg)

 Enter one of the following variables in the text box for **Value date**:

| Variable | UAC Behavior                                 |
| -------- | -------------------------------------------- |
| 0        | Elevate without prompting                    |
| 1        | Prompt for credentials on the secure desktop |
| 2        | Prompt for consent on the secure desktop     |
| 3        | Prompt for credentials                       |
| 4        | Prompt for consent                           |
| 5        | Prompt for consent for non-Windows binaries  |

 So, if you were to, for example, change it to **Prompt for credentials**, you’d enter **3** in the **Value data** text box.

![Editing the ConsentPromptBehaviorAdmin value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/editing-consentpromptbehavior-value-registry-editor.jpg)

 Then, click **OK** to apply and save the changes.

## Control the UAC’s Behavior as an Administrator

 Now you can change the behavior of UAC for admins as you please, depending on your situation. Just be careful not to make your computer more vulnerable in the process, which can happen if you choose **Elevate without prompting**. Microsoft recommends using that option only when you’re in a highly secure environment where the administrator accounts are tightly controlled.

 In that case, you can even disable the UAC altogether if you'd like since you know there are other measures in place to protect your computer from unwanted or malicious programs.

 As an administrator, you can change how UAC behaves. In this guide, we’re going to show you how to do that using the Local Group Policy Editor and Registry Editor.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-activity-recording.techidaily.com/new-essential-guide-best-screencasting-apps-at-no-cost-for-2024/"><u>[New] Essential Guide Best Screencasting Apps at No Cost for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-immersive-play-samsung-vr-classics/"><u>[New] Immersive Play Samsung VR Classics</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-top-10-ps5-external-hard-drives-you-can-find-for-2024/"><u>[New] Top 10 Ps5 External Hard Drives You Can Find for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-navigating-through-your-new-laptops-m1-max-clips/"><u>[Updated] Navigating Through Your New Laptop's M1 Max Clips</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/essential-steps-to-correct-your-wireless-networks-access-point-errors/"><u>Essential Steps to Correct Your Wireless Network's Access Point Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/getting-to-know-you-your-pc-unveiling-the-brand-and-model/"><u>Getting to Know You (Your PC): Unveiling the Brand and Model</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1722894435041-gmail-sync-errors-demystified-a-comprehensive-troubleshooting-guide/"><u>Gmail Sync Errors Demystified: A Comprehensive Troubleshooting Guide.</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-iphone-13-mini-system-issues-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair iPhone 13 mini System Issues? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/old-world-new-interface-turning-windows-11-into-98/"><u>Old World, New Interface: Turning Windows 11 Into '98</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-obstacles-with-windows-safeguard-issues/"><u>Overcoming Obstacles with Windows Safeguard Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-zero-error-in-the-windows-store/"><u>Remedying Zero-Error in the Windows Store</u></a></li>
<li><a href="https://windows11.techidaily.com/revive-your-blank-camera-on-device-management-screen/"><u>Revive Your Blank Camera on Device Management Screen</u></a></li>
<li><a href="https://win-amazing.techidaily.com/1722978156985-step-by-step-tutorial-how-to-effortlessly-update-wacom-cintiq-software/"><u>Step-by-Step Tutorial: How to Effortlessly Update Wacom Cintiq Software!</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-secrets-behind-windows-system-updates/"><u>Unraveling the Secrets Behind Windows System Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-10-steps-to-rectify-defective-usb-hardware/"><u>Windows 10: Steps to Rectify Defective USB Hardware</u></a></li>
</ul></div>

