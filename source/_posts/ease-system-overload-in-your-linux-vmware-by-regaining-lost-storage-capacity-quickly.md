---
title: Ease System Overload in Your Linux Vmware by Regaining Lost Storage Capacity Quickly
date: 2024-10-18T21:34:44.696Z
updated: 2024-10-24T18:25:38.750Z
tags:
  - windows
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/52651182169_f06ff010f1_o.jpg
---

## Ease System Overload in Your Linux Vmware by Regaining Lost Storage Capacity Quickly

### Key Takeaways

* VirtualBox doesn't automatically shrink Linux guest disks, but you can manually reclaim disk space by zeroing out data and compacting the volume.
* You should enable dynamic allocation in VirtualBox and back up your data before proceeding with the disk compacting process.
* Use the "dd" command to zero-out empty space in the Linux guest and then use VBoxManage to compact the virtual disk image.

 VirtualBox lets you run Linux in a virtual machine, and you'll often find your virtual disks continually growing in size, even though you've been clearing them of files. I'll show you how to shrink these volumes back down to size, compacting them and saving your disk space.

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2141676/17091" target="_top" id="2141676">
  <img src="//a.impactradius-go.com/display-ad/17091-2141676" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettieu.pxf.io/i/5597632/2141676/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Why Your VirtualBox Linux Guest Isn’t Automatically Shrinking

 If you've used [VirtualBox](https://remote-screen-capture.techidaily.com/updated-2024-approved-little-gamers-treasure-trove-of-joy/) with Windows guests (in virtual machine terminology the "guest" is the operating system running within the virtual machine), you're probably used to your VirtualBox disk volumes shrinking as you delete files from them, so that they only use up as much space on your physical disk as they need to contain the files in them.

 This is the intended purpose of VirtualBox's dynamic allocation feature, but it doesn't work with [Linux guests](https://extra-guidance.techidaily.com/updated-snapshot-sophistication-editing-to-dazzle/). When using a Linux guests, many users find the disks grow to their full size, and then never shrink back down as files are deleted from them.

 This is due to how Linux manages its filesystems and how it interacts with its VirtualBox host. Linux doesn't "zero out" (overwrite with empty data) files when they are deleted for performance reasons, so VirtualBox has no way to tell what data on a virtual disk is active data and which is deleted.

 You can solve this issue by zeroing that data yourself, and telling VirtualBox to compact the volume, bringing it back down to its actual size. Here's how it's done.

##  How to Reclaim Disk Space From a Linux Virtual Machine in VirtualBox

 The first thing you need to do to reclaim disk space from your Linux guests' virtual disks is ensure that dynamic allocation is enabled. If it is not, you will need to [convert your disk to a dynamically allocated disk](https://fox-info.techidaily.com/new-visualize-verve-vocalize-laughter-kapwings-toolkit/).

![How to find out whether 'Dynamically allocated storage' is enabled for your virtual disk.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/vbox-dynamic-disk-1.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902319/19272" target="_top" id="1902319">
  <img src="//a.impactradius-go.com/display-ad/19272-1902319" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902319/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Next, [back up your virtual disk](https://extra-information.techidaily.com/mac-and-pcs-top-10-supercharged-srt-systems-unveiled/). If something goes wrong (like a mistyped command, or your power going out part way through the process), you risk losing all the data in your Linux guest.

 Next, on your Linux guest [run the following command in the terminal](https://vimeo-videos.techidaily.com/updated-boost-your-income-with-effective-vimeo-monetization-techniques-for-2024/):

sudo dd if=/dev/zero of=/var/deleteme

 This command will write zero'd out (empty) data to the file /var/deleteme until the disk is completely full. This overwrites all of your previously deleted files, solving the problem that Linux doesn't overwrite deleted data automatically.

 Be careful using the dd command as it will overwrite data without warning! Check your commands and paths carefully before running them.

 This process could take some time depending on the size of the volume, so be patient and do not interrupt it. Once it has finished, the process will exit (possibly with an error saying that it is out of space). Once this has happened, you can delete the zeroed-out file and shut down your Linux guest:

sudo rm -rf /var/deleteme

    
                    sudo shutdown now -h

 Now the unused space on your virtual disk is zeroed out and VirtualBox will be able to reclaim the space on your host by shrinking it. The final step is to use the vboxmanage command to compact the virtual disk image. Do this by running:

        `vboxmanage modifymedium disk /path/to/image.vdi -compact`
    
 You must change /path/to/image.vdi to the path of the virtual disk you want to compact. If you are on Windows, you will need to use VBoxManage.exe like so:

VBoxManage.exe modifymedium disk /path/to/image.vdi -compact

 If VBoxManage.exe is not available from the command line on your Windows system, read on for instructions on how to enable it.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135363/19272" target="_top" id="2135363">
  <img src="//a.impactradius-go.com/display-ad/19272-2135363" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135363/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  What Did the dd Linux Command Do?

 This method for compacting a VirtualBox Linux guest utilizes the dd command to write an empty file to disk so that empty space can be identified by VirtualBox.

 The [dd](https://ss64.com/bash/dd.html) (data duplicator) command converts and copies files, and can also be used to write data. The "if" option passed to it supplies the input file (in this case /dev/zero supplies a constant stream of zero-value data or null data). The "of" option specifies the output file, and this stream of zero data is written to it. This will continue until the disk is full as /dev/zero never stops providing null data.

##  Using VboxManage.exe in Windows

 By default, VBoxManage.exe isn't available on the Windows command line. You can add it by [updating your Windows system path](https://screen-mirroring-recording.techidaily.com/updated-ideal-systems-for-recording-and-streaming-athletic-competitions-for-2024/) to include the VirtualBox installation directory, or calling the full path to the executable when using it:

& "C:/Path/To/VBoxManage.exe" modifymedium disk /path/to/image.vdi -compact

 The "&" symbol, called the call operator, that executes the quoted command. This lets you use spaces in path to the executable.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082521/7443" target="_top" id="2082521">
  <img src="//a.impactradius-go.com/display-ad/7443-2082521" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082521/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  More About Managing VirtualBox Guests

 As your guests grow, you can [increase the size](https://tech-recovery.techidaily.com/the-ultimate-guide-16-best-free-sources-for-learning-american-sign-language/) of their virtual disks as well as [reduce them](https://screen-video-capture.techidaily.com/new-vocalvoyage-listening-and-recording-expedition-for-2024/). [Snapshotting](https://facebook-video-recording.techidaily.com/updated-fb-video-downloader-extraordinaire-mp4-transformation-for-2024/) lets you take the state of your virtual machine at a certain point in time and save it; if you later want to go back to how things were at that exact moment (for example after testing a configuration change), you can simply roll back and everything will be as it was.

 VirtualBox is a powerful virtualization tool that is used both professionally by developers to build and test software, and home users to run older software and games on modern computers, or run other operating systems without having to purchase a second machine. You can run [Windows](https://some-skills.techidaily.com/the-secrets-of-selecting-a-powerful-streaming-device-for-2024/), [Linux](https://extra-guidance.techidaily.com/updated-snapshot-sophistication-editing-to-dazzle/), [ChromeOS](https://ios-unlock.techidaily.com/in-2024-unlocking-iphone-xs-max-passcode-without-a-computer-by-drfone-ios/), Android, and other operating systems on MacOS, Windows, and Linux Hosts.

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
<li><a href="https://eaxpv-info.techidaily.com/new-how-to-execute-flawless-wirecast-broadcasts-on-youtube-for-2024/"><u>[New] How to Execute Flawless WireCast Broadcasts on YouTube for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-navigating-instagrams-video-limit-regulations-for-2024/"><u>[New] Navigating Instagram's Video Limit Regulations for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-time-travel-through-free-visual-storerooms-for-2024/"><u>[New] Time Travel Through Free Visual Storerooms for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/approved-pivotal-information-in-the-realm-of-asmr/"><u>2024 Approved Pivotal Information in the Realm of ASMR</u></a></li>
<li><a href="https://windows11.techidaily.com/ending-dual-access-to-your-camera-error-0xa00f4243/"><u>Ending Dual Access to Your Camera (Error 0xA00F4243)</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-privacy-with-best-windows-crypto-apps-152-chars/"><u>Ensuring Privacy with Best Windows Crypto Apps (152 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-preparations-for-revitalizing-your-pc-with-windows/"><u>Essential Preparations for Revitalizing Your PC with Windows</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-google-frp-lock-from-infinix-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock from Infinix Devices</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/instagram-videography-guide-size-matters-for-2024/"><u>Instagram Videography Guide - Size Matters for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-xp-error-code-0x80300024/"><u>Navigating Windows XP Error Code: 0X80300024</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-invalid-verification-error-by-steams-vac/"><u>Overcoming Invalid Verification Error by Steam's VAC</u></a></li>
<li><a href="https://windows11.techidaily.com/personalize-your-digital-notepad-a-guide-to-windows-11-customization/"><u>Personalize Your Digital Notepad: A Guide to Windows 11 Customization</u></a></li>
<li><a href="https://audio-editing.techidaily.com/premier-voice-recorders-for-android-comprehensive-and-cost-free-for-2024/"><u>Premier Voice Recorders for Android - Comprehensive and Cost-Free for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-picking-a-software-dependency-provider/"><u>The Ultimate Guide to Picking a Software Dependency Provider</u></a></li>
<li><a href="https://fake-location.techidaily.com/thinking-about-changing-your-netflix-region-without-a-vpn-on-motorola-moto-g14-drfone-by-drfone-virtual-android/"><u>Thinking About Changing Your Netflix Region Without a VPN On Motorola Moto G14? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/top-7-skype-hacker-to-hack-any-skype-account-on-your-zte-axon-40-lite-drfone-by-drfone-virtual-android/"><u>Top 7 Skype Hacker to Hack Any Skype Account On your ZTE Axon 40 Lite | Dr.fone</u></a></li>
<li><a href="https://discover-data.techidaily.com/toplogiciels-de-migration-securises-pour-les-ssds-kingston-guide-complet/"><u>Toplogiciels De Migration Sécurisés Pour Les SSDs Kingston - Guide Complet</u></a></li>
<li><a href="https://windows11.techidaily.com/tracking-windows-logins-identifying-successes-and-failures/"><u>Tracking Windows Logins: Identifying Successes & Failures</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-registry-shortcomings-solutions/"><u>Unveiling Windows Registry Shortcomings: Solutions</u></a></li>
</ul></div>

