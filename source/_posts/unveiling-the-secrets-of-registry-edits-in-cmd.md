---
title: Unveiling the Secrets of Registry Edits in CMD
date: 2024-06-25T12:12:37.517Z
updated: 2024-06-26T12:12:37.518Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unveiling the Secrets of Registry Edits in CMD
excerpt: This Article Describes Unveiling the Secrets of Registry Edits in CMD
keywords: Edit Registry Command Guide,Mastering CMD for RegEdit,Unlock CMD Registry Tools,Explore CMD Registry Changes,Advanced CMD Registry Tips,Navigate CMD to Modify Registry,CMD Paths for Registry Edits
thumbnail: https://thmb.techidaily.com/7c8eb4a6751ebbb720d8baa15eb6264cc6e760acb0b1ed4fef37387dcca189b5.jpg
---

## Unveiling the Secrets of Registry Edits in CMD

 The Registry Editor is the first thing Windows users bring up when it comes to editing the Windows Registry. However, if you don't want to deal with a distracting GUI and too many clicks, there's a simpler-looking tool you can use: the Command Prompt.

 Although using it takes a little more know-how than the Registry Editor, our guide should be able to get you started.

## How to View the List of Registry Commands in Command Prompt

![the command to view all reg commands](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/the-command-to-view-all-reg-commands.jpg)

 There aren't a lot of commands when it comes to editing the registry using Command Line. To view them all, [open Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) and run the below command in Command Prompt:

`reg /?`

 Command Prompt will then list the commands, such as **reg add**, **reg delete**, **reg copy**, and **reg save**.

![the list reg commands in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/the-list-reg-commands-in-command-prompt.jpg)

 If you want to see more information about them, just add the **/?** switch at the end of the command. For, example, if you want to find out what the **reg add** command does, you'd enter the below command:

`reg add /?`

 After you run it, you'll get all the details on what it does and how to use it.

![details of the reg add command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/details-of-the-reg-add-command-in-command-prompt.jpg)

 If you're finding it hard the commands out on your own, don't worry. We will simplify it for you and show you how to get started using them.

## Add and Delete Keys in the Windows Registry

 To add a key to the registry using Command Prompt, you need to use the **reg add** command while specifying the path to the new key and whether you want to force the operation with the **/f** switch(this will bypass the need for the confirmation prompt).

 As always, when it comes to editing the Windows Registry, we recommend that the first thing you do is [create a system restore point on Windows](https://www.makeuseof.com/use-system-restore-windows/).

 Here's an example:

`REG Add HKLM\SOFTWARE\MyNewKey /f`

 In the above command, we're adding the **MyNewKey** subkey to the **KHLM/Software** key. If you go to the Registry Editor and expand that key, you'll be able to see the **MyNewKey** subkey within it.

 Deleting the key is simple as well, as you just need to replace **add** with **delete** in the above example. Here's how:

`reg delete HKLM\SOFTWARE\MyNewKey /f`

 Now the **MySubKey** key will disappear in the Registry Editor.

## How to Add, Modify, and Delete Values in the Windows Registry

![adding a value to Windows registry in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/adding-a-value-to-windows-registry-in-command-prompt.jpg)

 To add or modify a value key in the registry using Command Prompt, you'll still use the **reg add** command like above. However, this time, you'll also have to specify the following parameters: value (**/v**), value type (**/t**), and value data (**/d**). Here's an example of what the command would like:

`reg add HKLM\SOFTWARE\MyNewKey /v MyValue /t REG_DWORD /d "1" /f`

 Once you run the command, you will be able to find the value in the Registry Editor. And if the key doesn't exist, Command Prompt will create it.

 The Windows Registry uses several value types, and here's a table of the common ones:

| Value Type      | Description           |
| --------------- | --------------------- |
| REG\_NONE       | No value type         |
| REG\_SZ         | String value          |
| REG\_MULTI\_SZ  | Multi-string value    |
| REG\_EXPAND\_SZ | Expanded string value |
| REG\_DWORD      | 32-bit DWORD value    |
| REG\_QWORD      | 64-bit QWORD value    |
| REG\_BINARY     | Binary value          |

 To delete the value, you just need to use the **reg delete** command while specifying the path to the key, and the name of the value. Here's an example of deleting the value we created earlier:

`reg delete HKLM\SOFTWARE\MyNewKey /v MyValue /f`

 After running the above command successfully, the value should disappear from the Registry Editor.

## How to Copy Registry Entries From One Key to Another

![transfering entries from one registry key to another in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/transfering-entries-from-one-registry-key-to-another-in-command-prompt.jpg)

 Sometimes, you might want to copy the values from one key to another in the registry. This is as easy as using the **reg copy** command while specifying the key you're copying them from and the one you're copying them to (keep in mind that both keys have to already exist before you run the command). Here's an example:

`reg copy HKLM\SOFTWARE\MyNewKey1 HKLM\SOFTWARE\MyNewKey2 /s`

 The **/s** switch at the end tells Command Prompt that it should copy every subkey and value in the first key (**MyNewKey1**) into the second one (**MyNewKey2**).

 Unfortunately, there's no way to copy specific values from one key to another. You'll have to use the Registry Editor for that.

## How to Import Registry Entries

![importing a registry file in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/importing-a-registry-file-in-command-prompt.jpg)

 If you have [created a Windows Registry file](https://www.makeuseof.com/windows-registry-file-guide/) or downloaded it elsewhere, you can import it into the registry using the **reg import** command. All you need to do is specify the path to the registry file and Command Prompt will do the rest. Here's an example:

`reg import C:\Users\CHIFUNDO\Desktop\MyRegFile.reg`

 Once you run that command, the contents of the reg file will be merged with the registry.

## How to Export Registry Entries

![exproting a registry key in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/exproting-a-registry-key-in-command-prompt.jpg)

 You can export a key in the registry using the **reg export** command while specifying the path of the key you want to export and the file you want to create. This comes in handy when you need to back up certain keys and values to restore them elsewhere. Here's an example:

`reg export "HKLM\SOFTWARE\MyNewKey" D:\Reg_Backup\CHIFUNDO\Desktop\MyRegFile.reg`

 After you run the command successfully, check the location you entered, and you'll find the key and its associated subkeys and values have been exported successfully. In our case, it will create a file called **MyRegFile.reg** and save it on the desktop.

 You can also export a specific value using the **reg query** command and include the key, value, and path to the registry file you want to export the value to. Here's an example.

`reg query HKLM\SOFTWARE\MyNewKey /v MyValue > C:\Users\CHIFUNDO\Desktop\MyRegFile.reg`

 The resulting registry file will only contain the key and the specific value you exported.

## How to Save Registry Entries

![saving-a-key-to-a-registry-file-in-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/saving-a-key-to-a-registry-file-in-windows.jpg)

 If you already have a registry file or any other text file, you can add keys to it using Command Prompt and the **reg save** command, which will overwrite the file with the new information. You just need to specify the name of the key and the registry file you want to save it to. Here's an example:

`reg save HKLM\SOFTWARE\MyNewKey2 C:\Users\CHIFUNDO\Desktop\MyRegFile.hiv /y`

 The **/y** switch at the end of the command above overwrites the file you're saving the key to without bringing up a prompt. When you open the file, you won't be able to read the contents since it will be saved as a binary file.

## How to Restore Registry Entries

![restoring-a-registry-key-in-command-prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/restoring-a-registry-key-in-command-prompt.jpg)

 So, let's say something has happened to the keys and values within the **MyNewKey2** we saved in the previous section, you can use the backup file you created to restore it. You'll need to use the **reg restore** command. Here's how to run it:

`reg restore HKLM\SOFTWARE\MyNewKey2 C:\Users\CHIFUNDO\Desktop\MyRegFile.hiv`

 Now the **MyNewKey2** key should return to the state it was in when you made the backup.

## Tweak the Registry Without the Registry Editor

 While Command Prompt can't do everything the Registry Editor does, it does offer a quick way to edit the registry without opening the aforementioned tool. While using Command Prompt to tweak the registry is quite advanced, even if you're the average user, you should be able to get by if you follow along closely.

 Just don't forget to do what we mentioned earlier to avoid permanently ruining your Windows computer and create a system restore point first

 Although using it takes a little more know-how than the Registry Editor, our guide should be able to get you started.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/integrating-your-android-into-windows-11-webstreaming/"><u>Integrating Your Android Into Windows 11 Webstreaming</u></a></li>
<li><a href="https://windows11.techidaily.com/rejoining-lost-astra-pilot-on-windows-11-machines/"><u>Rejoining Lost Astra Pilot on Windows 11 Machines</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-stable-windows-printer-connections/"><u>Ensuring Stable Windows-Printer Connections</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-pinpointing-device-serial-numbers-on-windows/"><u>The Ultimate Guide to Pinpointing Device Serial Numbers on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/enhanced-windows-file-navigation-a-guide-excluding-ls/"><u>Enhanced Windows File Navigation: A Guide Excluding LS</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-vibrance-to-dull-desktop-windows-effects/"><u>Restoring Vibrance to Dull Desktop Windows Effects</u></a></li>
<li><a href="https://windows11.techidaily.com/fast-track-to-windows-11-arm-with-easy-iso-setup-instructions/"><u>Fast Track to Windows 11 ARM with Easy ISO Setup Instructions</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-to-vanquish-your-pcs-win11-blue-screen/"><u>Expert Tips to Vanquish Your PC's Win11 Blue Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/choosing-the-right-nearby-share-software-for-secure-collaboration/"><u>Choosing the Right Nearby Share Software for Secure Collaboration</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-public-melodies-for-calmness/"><u>[Updated] Public Melodies for Calmness</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-in-2024-top-7-tiktok-emojis-and-unveiling-hidden-tiktok-charms/"><u>[Updated] In 2024, Top 7 TikTok Emojis & Unveiling Hidden TikTok Charms</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-create-stunning-videos-online-with-ease-wevideo/"><u>New Create Stunning Videos Online with Ease - WeVideo</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-auditory-sculpture-in-motion-constructing-vibrant-audio-visual-compositions-with-premiere-pro/"><u>New 2024 Approved Auditory Sculpture in Motion Constructing Vibrant Audio-Visual Compositions with Premiere Pro</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/1716465703098-from-buffer-to-broadcast-learn-how-to-convert-your-youtube-viewing-into-a-screenshot-for-free/"><u>From Buffer to Broadcast  Learn How to Convert Your YouTube Viewing Into a Screenshot for Free.</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/condense-time-amplify-impact-time-lapse-video-creation-in-final-cut-pro/"><u>Condense Time, Amplify Impact Time Lapse Video Creation in Final Cut Pro</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-majestic-monsters-thunderous-voices-an-exclusive-soundtrack/"><u>Updated In 2024, Majestic Monsters, Thunderous Voices An Exclusive Soundtrack</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-first-steps-into-filmmaking-the-ultimate-guide-for-making-your-first-10-youtube-videos/"><u>[Updated] First Steps Into Filmmaking  The Ultimate Guide for Making Your First 10 YouTube Videos</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-vivo-y200-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Vivo Y200 | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-ways-to-track-vivo-x-fold-2-without-them-knowing-drfone-by-drfone-virtual-android/"><u>3 Ways to Track Vivo X Fold 2 without Them Knowing | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>