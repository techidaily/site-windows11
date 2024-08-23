---
title: Power Up Windows for Video-on-Demand via Dynamic Transcoding by Tdarr
date: 2024-08-22T21:42:17.744Z
updated: 2024-08-23T21:42:17.744Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Power Up Windows for Video-on-Demand via Dynamic Transcoding by Tdarr
excerpt: This Article Describes Power Up Windows for Video-on-Demand via Dynamic Transcoding by Tdarr
keywords: Power Up Windows VOD,Dynamic Windows Transcoding,Video-on-Demand Windows,Dynamic Transcoding Windows,Tdarr Windows Enhancement,Tdarr Dynamic Encoding,Tdarr VOD Boosting
thumbnail: https://thmb.techidaily.com/9bd169ce317850079833c4c232eaa6d389f824b0ea7ef26122a9f26ae8562eda.jpg
---

## Power Up Windows for Video-on-Demand via Dynamic Transcoding by Tdarr

 Transcoding is one of the most demanding tasks for your PC, translating to a time-consuming process for the end user. Encoding a single video can take days, depending on the PC's specifications, the codec used, and the source video's characteristics. That's where multiple PCs and an app like Tdarr can be a lifesaver.

 If you have more than one PC in your home network, why not let them lend a helping hand when transcoding media? Tdarr can turn all your PCs into nodes of the same networked transcoder, resulting in much faster audio and video encoding. Let's see how.

## What Is Tdarr?

 Sonarr, Radarr, and their "siblings" were created to assist with media piracy. However, unlike the other apps in the pirate-y "...arr" family, Tdarr differs in two crucial ways, justifying why we've decided to use it for this guide:

* It doesn't specialize in "granting access to illegal content" like (most of) its siblings, but in modifying the media files you already own.
* It trivializes the creation of mass-video-encoding networks. In the past, few, apart from professionals in the field, like Netflix, could pull this off successfully.

 After setting it up, Tdarr can help you "unify" your media collection, whose files are spread on various devices. You can always [compress videos to reduce their file size](https://www.makeuseof.com/compress-video-file/) yourself, but why not completely delegate the task to Tdarr?

1. You can configure Tdarr to "pull" your media files from all your devices.
2. It can then re-encode them to formats appropriate for each of them.
3. Finally, it can store the results in a shared folder or "push" them to each device on your local network.

 Best of all, after you set it up, it works automatically while taking advantage of the hardware capabilities of the "nodes" in your network: Windows desktop PCs, Linux servers, ARM-based Chromebooks, or your shiny new Mac.

 For this article, we'll see how you can set it up and use it on two Windows-based PCs on the same home network.

## How to Install Tdarr

 Despite being a relatively complicated collection of separate scripts and tools, Tdarr's installation is straightforward.

1. Start by downloading the appropriate version of the application for your platform from [Tdarr's official GitHub page](https://GitHub.com/HaveAGitGat/Tdarr).
2. Extract the downloaded zip archive and run the Tdarr **updater** app.
3. Windows protection might warn you that you are trying to run an unrecognized application. Click on **More info** to allow the app to run.
4. Click on **Run anyway** to acknowledge that you want to run an application created "by an unknown publisher".  
![Tdarr Install App Run Anyway](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-install-app-run-anyway.jpg)
5. Allow the Tdarr updater to download everything needed by the application. If you see any mention that a connection failed, grant the Tdarr updater access to the Internet through your firewall.  
![Tdarr Downloading Necessary Data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-downloading-necessary-data.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075475/7443" target="_top" id="2075475"><img src="//a.impactradius-go.com/display-ad/7443-2075475" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Tdarr's Hardware Requirements

 You can run the Tdarr server and the node software on any PC and access its interface through almost any browser. However, your hardware's performance and features can significantly affect encoding speeds.

 For example, a node running on a modern AMD Ryzen CPU will encode the same video in a blink compared to a ten-year-old Intel Celeron.

 Another node, using Nvidia's **NVEnc** hardware encoder for transcoding, will, in turn, be much faster than the AMD Ryzen CPU, but will also produce lower quality or larger files.

 So, if you find Tdarr's encoding too slow, you have two options:

* Try a less demanding codec or one that's "hardware accelerated" by your hardware.
* Upgrade to better hardware.

 Apart from that, you can run Tdarr even on a ten-year-old laptop if you can tolerate slow encoding speeds.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->
### What About Tdarr's Codecs?

 We won't go into detail about what codecs are and how they work. However, we must mention that the codecs and encoders you choose are the most important factor for Tdarr's encoding performance and quality of produced results.

* Newer Codecs come with better quality-to-bitrate ratios but also higher hardware requirements.
* Hardware encoders can dramatically boost performance but also produce lower quality/larger files than software encoders (when using similar settings).

 With the above in mind, here's a list of the codecs worth using with Tdarr for re-encoding your media files. The closer a codec is to the top, the better the output quality, the higher its requirements, and the slower the encoding time.

1. AV1
2. H.265/HEVC
3. VP9
4. H.264/AVC
5. AV1/H.265 GPU-assisted Encoding
6. H.264 GPU-Assisted Encoding
7. MPEG4, DivX, Xvid
8. MPEG2

## How to Configure Tdarr

 Tdarr's core is its server, which provides a browser-accessible interface for the app, manages media, and orchestrates encoding among various nodes. The server doesn't do any encoding on its own. For that, it needs at least one node.

 Each node can have its own configuration and run locally on your PC or another computer on the same network. Nodes are responsible for media analysis, health checks, re-encoding, etc.

 The server controls all nodes, how they act on media, and manages files.

 Tdarr's nodes come pre-configured for running on the "local" PC without requiring a network. Thus, if you only plan to use Tdarr on a single PC, you only have to configure its server (apart from minor node tweaks).

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Configuring Your Tdarr Server

 For this article, we'll see how you can configure Tdarr Server from scratch without importing an existing media collection. Have you got a media library set up? You can modify the paths we'll use to point to your existing folders to have Tdarr process and re-encode them.

1. To configure Tdarr for a single computer, enter the **Tdarr Server** folder created by Tdarr's updater and run the **Tdarr Server app**.
2. As with the updater, you will probably have to allow it access through your firewall.
3. Tdarr's page didn't open automatically in your default browser? Enter the following in your browser's address bar: "localhost:8265/", and press **Enter** to visit Tdarr's web-based GUI. We suggest you **bookmark** it for easier access in the future.  
![Tdarr Change Log](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-change-log.jpg)
4. If you don't like how Tdarr's page looks, you can change its theme from the **Options** page.
5. Scrolling down on the same page, you'll find a series of **Resolution boundaries** fields. Those allow you to set custom resolutions for your media.  
![Tdarr Options Define Resolution Boundary Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-options-define-resolution-boundary-crop.jpg)

1. For example, since I only have access to **Full HD** screens, I've set "**1920**" as the width in the **Width Max** field of all resolutions above 1080p and their height as "**1188**" in their respective **Height Max** fields. This way, Tdarr will never re-encode media at a higher resolution than the native Full HD (1920 x 1080) of my monitors, producing much smaller files more quickly than if it had to deal with higher resolutions.  
![Tdarr Options Custom Resolution Boundary Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-options-custom-resolution-boundary-crop.jpg)
2. You need at least one library for your media, so visit the **Libraries** page and click the **Library +** button to create one.
3. Type any name you wish in the field stating "**Library Name**".
4. Fire up your favorite file explorer. Choose where you want to keep your media and create a folder. For this article, we used a folder named "**Videos**" at the root of the system "C" drive.
5. Create three subfolders inside that folder. For ease of use, we've named them "**Incoming**", "**Ready**", and "**Temporary**". "Incoming" is where we will drop any unprocessed files for Tdarr to check out. "Temporary" is the folder Tdarr will use while processing files. "Ready" is where Tdarr will output processed files.  
![Tdarr Incoming Ready Temporary Folders](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-incoming-ready-temporary-folders.jpg)
6. Go back to Tdarr's interface, move to the **Libraries** page, select your library, and if not visible on your screen, scroll down to find the **Source** tab. Click on it and enter the full path to your Incoming folder in the **Source** field below.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Tdarr Define Library Source Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-define-library-source-crop.jpg)
7. Move to the **Transcode cache** tab and enter the full path to your "Temporary" folder in the **Cache** field.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![Tdarr Set Transcode Cache to Temporary Folder Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-set-transcode-cache-to-temporary-folder-crop.jpg)
8. Finally, move to the **Output folder**, and as you might have guessed, enter the full path to your "Ready" folder in the **Output** field.  
![Tdarr Point Output Folder to Ready Folder Path Copy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-point-output-folder-to-ready-folder-path-copy.jpg)
9. Click the switch next to **Output Folder** on that tab to have Tdarr use the Incoming and Ready folders as Input and Output. If you don't do that, Tdarr will store everything in the Incoming folder. If you've got many media files, that can quickly get messy.

 If you wish, you can control the rate at which Tdarr scans the Incoming folder for new files. To do that, move to your library's **Source** tab, scroll down a bit, and change the number in the **Folder watch scan interval** field under **Folder watch settings**.

 Similarly, right below, you can tell it to run an hourly scan and define how many **File scanner threads** that will use. If you store your media on NVMe or SSD drives, increasing the number of File scanner threads can boost performance.

 Older mechanical HDDs, though, take a significant hit in performance when trying to access files in parallel, so it's best not to exceed the default value of "**2**" for those. You can also enable the option to **Hold files after scanning** and define how long (in seconds) those files will remain locked to ensure other apps won't interfere with them.

 Your library's **Filters** tab lets you define resolutions and codecs you'd prefer to skip. If, for example, you want Tdarr only to **downscale** videos, you can enter all the popular lower resolutions up to your monitor's native resolution (like "360p", "720p", and "1080p"), separated by commas in the **Resolutions to skip field**.

![Tdarr Library Filters Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-library-filters-crop.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->
 The **Codecs to skip** field works similarly. For example, if you type "**AV1, HEVC**" in that field, Tdarr won't try re-encoding video files already compressed with those codecs.

![Tdarr Library Filter Skip Code Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-library-filter-skip-code-crop.jpg)

 To have Tdarr process your files, it will have to watch the incoming folder to detect changes (AKA: new files). For that, visit your library's **Source** tab and flick the switch next to **Folder watch** to the right.

![Tdarr Library Source Enable Folder Watch Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-library-source-enable-folder-watch-crop.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698827&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3REpage-newmainscreenshot.png" border="0">DEX 3 RE is Easy-To-Use DJ Mixing Software for MAC and Windows Designed for Today's Versatile DJ. 

 Mix from your own library of music, iTunes or use the Pulselocker subsciprtion service for in-app access to over 44 million songs. Use with over 85 supported DJ controllers or mix with a keyboard and mouse.  

 DEX 3 RE is everything you need without the clutter - the perfect 2-deck mixing software solution for mobile DJs or hard-core hobbiests.  
 PCDJ DEX 3 RE (DJ Software for Win & MAC - Product Activation For 3 Machines)</a>
<!-- affiliate ads end -->
## Customizing Tdarr's Nodes & Encoding

 Tdarr requires at least one active node to act on your media, so it's time to turn our attention to them.

1. With your Tdarr server still active, to add a node to it, enter the **Tdarr node** folder created by the Tdarr updater and run the **Tdarr node app** you'll find within it.
2. You will see a notification on Tdarr's interface web interface page that a node was **registered**.  
![Tdarr Node Connected to Server](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-node-connected-to-server.jpg)
3. To test things out, place a media file in your incoming folder.  
![Tdarr Place Video into Incoming Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-place-video-into-incoming-folder.jpg)
4. Move to Tdarr's main page (named "Tdarr") and scroll to the bottom, under **Status**, to find your library. Soon you will see the file you added to your Incoming folder appear there.  
![Tdarr Media Added to Library Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-media-added-to-library-crop.jpg)
5. Nothing will happen because your node needs to be configured to act on it. For that, scroll up to find the **Nodes** panel and click on your node name.  
![Tdarr Node Selection Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-node-selection-crop.jpg)

1. You will see more details about the selected node, and you can use the **plus** and **minus** buttons next to **Transcode** and **Health Check** to assign to the node CPU and GPU threads for each task. This way, you control which node does what, which is especially useful in a multi-computer environment.  
![Tdarr Node Transcode and Health Check Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-node-transcode-and-health-check-crop.jpg)
2. Click on your node's **Options** button to access its more advanced options.
<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
3. You can manually edit the node's configuration from here. Still, it's best to leave it as is and only manipulate it using external applications like Notepad.  
![Tdarr Node Config](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-node-config-1.jpg)
4. Scroll down and use the drop-down menu to select which type of GPU acceleration you want the node to use (if available on your hardware).  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->
![Tdarr Node Hardware Encoding Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-node-hardware-encoding-crop.jpg)
5. If you want to use the PC on which the node runs for other tasks while encoding, flick the switch under **Low FFMPEG/HandBrake Process Priority** to have the node consume fewer resources and avoid choking your PC. Alternatively, [use an app like Process Lasso to take control of your CPU threads](https://www.makeuseof.com/process-lasso-take-control-of-cpu-threads/) and ensure it won't start crawling while encoding.
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. For even more control, you can scroll down further and create a **Node schedule**, stating which hours of the day a node will be allowed to perform health-checking or transcoding tasks using the CPU or GPU.
7. When you return to the **Nodes** panel with at least one CPU or GPU assigned for transcoding and health checks, you will see that your node has started working on your incoming file.  
![Tdarr Node Scanning Media File Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-node-scanning-media-file-crop.jpg)
8. After an initial check and if the incoming file doesn't match your filter, Tdarr will start transcoding it.
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can see the result when it's done if you scroll to the **Staging** section where, in our case, the status of our file was "**Transcode Success**", and its size was down to around 49 MB. The **Handling** field on the right offers three buttons for controlling the entries of this list.

 Using those, you can requeue, skip, or accept an encode. You can find the re-encoded version of your file inside the "Ready" folder.

![Tdarr Re encoded File in Ready Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-re-encoded-file-in-ready-folder.jpg)

## Network & Hardware-Accelerated Encoding

 Tdarr is best when using all the CPU and GPU power of all PCs on your local network for re-encoding your files. However, that's a bit more complicated to set up.

 For this part of our guide, we take for granted that you have more than one PC, and they can "see" each other through your local network. You've got the PCs but haven't "networked them" yet? Choose a networking approach from our collection of [diagrams on which to base your home network for full connectivity](https://www.makeuseof.com/home-network-setup-diagrams/), and then follow our guide on [how to set up a secure home network](https://www.makeuseof.com/home-network-setup/).

1. Since all the PCs that will become nodes in Tdarr's network will require access to the same media files, you should keep them in a network-accessible shared folder. It's better to use a dedicated network drive for that. Still, we shared the same "Videos" folder we created earlier, but with "**shared**" as its network alias.  
![Tdarr Shared Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-shared-folder.jpg)
2. Update the **Source**, **Transcode cache**, and **Output folder** paths of your library to point to the respective subfolders within your "Shared" folder.
3. Install Tdarr on the other PCs in your local network. Use your file manager to enter the "**configs**" folder in Tdarr's installation directory.  
![Tdarr Config Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-config-folder.jpg)
4. Make a copy of the "**Tdarr\_Node\_Config.json**" file, then open the original with a text editor (like Notepad).  
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Tdarr Node Config in Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-node-config-in-explorer-1.jpg)
5. You can change the value next to "**nodeName**" to assign the node any name you wish, like "my\_laptop", to make it easier to recognize and manage what runs where. Next to "**serverIP**", enter the IP of the PC on which you run the Tdarr server. As the "**serverPort**", enter "**8266**".  
<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Tdarr Editing Node Config](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-editing-node-config.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
1. Next, you have to configure the "**pathTranslators**". This section is the most complicated to grasp since it needs you to define **pairs of paths**. Next to "**server**", you must enter the path from which the Tdarr server can access a particular folder.
2. Next to "**node**", you must enter the equivalent path from which a node can access the same folder through the network. So, the actual path to our incoming folder on the Tdarr server PC was **//vmware-host/Shared Folders/Shared/Incoming**, but the path to the same folder on our node PC was through the mapped network drive "D:" and the folders **/Shared/Incoming**.
3. You have to define a path translator for each of the folders you've specified in Tdarr's interface for your "Incoming", "Temporary", and "Output" folders. The goal is to have both the Tdarr server and its nodes able to find the same files through their respective paths.  
![Tdarr Node Config Path Translators](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-node-config-path-translators.jpg)
4. Run the node software on your second PC and ensure both its firewall and the one on your main Tdarr server PC allow connections between them. Our guide on [how to allow apps through Windows firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) can help with that. You should see the remote node popup in your Tdarr server interface if everything works correctly.  
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Tdarr Network Node Connected](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-network-node-connected.jpg)
5. Next to its address, you will see its IP address and be able to control its CPU and GPU threads and options as if it were a local node.
<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. If GPU encoding doesn't work for you, it's probably because the appropriate plugin is disabled. For that, move back to the **Libraries** page, scroll down to find its tabs, and click on **Transcode options**.
7. There, enable the "**Migz-Transcode Using Nvidia GPU & FFMPEG**" plugin. You must also prioritize it over CPU encoding by left-clicking, dragging, and dropping it above the "**Migz-Transcode Using CPU & FFMPEG**" plugin.  
![Tdarr Libraries Enable Hardware Transcoding Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-libraries-enable-hardware-transcoding-crop.jpg)
8. From the same spot, if you click on a plugin, you can configure some options about how it will work. However, we won't dive into those, for they're outside the scope of this article.  
![Tdarr Libraries Customize Hardware Transcoding Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-libraries-customize-hardware-transcoding-crop.jpg)
9. When you return to the **Nodes** panel, your nodes (for which you've enabled that) should be using their GPUs for transcoding.

## Set Up Your Auto-Multi-Hyper-Encoder With Tdarr

 Setting up complicated automation software like Tdarr can take a while and occasionally make you wonder why something doesn't work as intended. When you set it up, though, Tdarr feels like magic.

 Add its server and nodes to your computers' auto-startup sequences, and hey presto, your media will always be re-encoded to high-quality, smaller files, using the optimal resolutions and formats for every single "machine" in your network. All while taking advantage of all available CPUs and GPUs in your PCs without you having to lift a finger.

 If you have more than one PC in your home network, why not let them lend a helping hand when transcoding media? Tdarr can turn all your PCs into nodes of the same networked transcoder, resulting in much faster audio and video encoding. Let's see how.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-affordable-android-chat-top-free-app-alternatives/"><u>[New] 2024 Approved  Affordable Android Chat  Top Free App Alternatives</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-an-easy-to-follow-guide-to-applying-cc-license-types/"><u>[New] An Easy-to-Follow Guide to Applying CC License Types</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-iphone-slow-motion-camera-video/"><u>[New] In 2024, IPhone Slow-Motion Camera Video</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-in-2024-making-bank-with-youtube-an-analysis-of-pewdiepies-earnings/"><u>[New] In 2024, Making Bank with YouTube  An Analysis of PewDiePie’s Earnings</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-master-image-transformations-today/"><u>[New] Master Image Transformations Today</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-unveiling-the-process-of-recording-in-adobe-presenter/"><u>[New] Unveiling the Process of Recording in Adobe Presenter</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-windows-studio-options-beyond-moviemaker/"><u>[New] Windows Studio Options Beyond MovieMaker</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-the-craft-of-loom-seamless-screen-recording-guide/"><u>[Updated] 2024 Approved  The Craft of Loom  Seamless Screen Recording Guide</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-achieve-perfection-on-instagram-with-right-video-dimensions/"><u>[Updated] Achieve Perfection on Instagram with Right Video Dimensions</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-from-capture-to-air-expert-tips-for-streaming-upside-down-videos-on-youtube/"><u>[Updated] From Capture to Air  Expert Tips for Streaming Upside-Down Videos on Youtube</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-leading-nintendo-switch-combat-arcade-games-max-156/"><u>[Updated] Leading Nintendo Switch Combat Arcade Games (Max 156)</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-media-mosaic-maker/"><u>[Updated] Media Mosaic Maker</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-snatch-free-media-treasures-from-top-4-online-creators/"><u>[Updated] Snatch Free Media Treasures From Top 4 Online Creators</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-transforming-ordinary-sessions-into-visual-extravaganzas-in-zoom/"><u>[Updated] Transforming Ordinary Sessions Into Visual Extravaganzas in Zoom</u></a></li>
<li><a href="https://tech-revival.techidaily.com/1721938195314-chatgpt-clone-at-no-charge-set-it-up-locally-on-a-windows-machine-using-gpt-4-all-technology/"><u>ChatGPT Clone at No Charge: Set It Up Locally on a Windows Machine Using GPT-4 All Technology</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/discover-top-browser-screen-recording-software-audiences/"><u>Discover Top Browser Screen Recording Software Audiences</u></a></li>
<li><a href="https://windows11.techidaily.com/dynamic-tray-display-live-system-usage-statistics-on-desktop/"><u>Dynamic Tray Display: Live System Usage Statistics on Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-steps-to-disable-amdnvidia-graphics-extras/"><u>Easy Steps to Disable AMD/Nvidia Graphics Extras</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-file-handling-in-windows-powertoys/"><u>Efficient File Handling in Windows PowerToys</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-fixes-for-the-frozen-search-in-windows-11-settings-app/"><u>Efficient Fixes for the Frozen Search in Windows 11 Settings App</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-techniques-for-purging-steams-dns-cache/"><u>Efficient Techniques for Purging Steam's DNS Cache</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-accessing-windows-emergency-tools/"><u>Efficiently Accessing Windows Emergency Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-win-based-open-ai-discussions/"><u>Effortless WIN-Based Open AI Discussions</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-cortana-experience-use-of-vivetool/"><u>Elevate Cortana Experience: Use of ViveTool</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-sound-top-5-apps-for-windows-beyond-maxed-volume/"><u>Elevate Sound: Top 5 Apps for Windows Beyond Maxed Volume</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-vm-game-six-key-tips-for-windows-optimization/"><u>Elevate Your VM Game: Six Key Tips for Windows Optimization</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-mouse-interaction-with-clicklock-in-windows/"><u>Elevating Mouse Interaction with ClickLock in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-ui-customization-adding-shortcut-keys-for-wordpad-to-menu-bar/"><u>Elevating UI Customization: Adding Shortcut Keys for Wordpad to Menu Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-vintage-gameplay-experience-with-achievement-boost-via-retroarch/"><u>Elevating Vintage Gameplay Experience with Achievement Boost via Retroarch</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-blue-screen-due-to-unhandled-win-errors/"><u>Eliminating Blue Screen Due to Unhandled Win Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-error-code-0x80300024-from-pc/"><u>Eliminating Error Code: 0X80300024 From PC</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-non-appearing-screens-on-pc-startup/"><u>Eliminating Non-Appearing Screens on PC Startup</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-shutdown-restart-and-sign-out-errors-by-suspicious-apps/"><u>Eliminating Shutdown, Restart, and Sign Out Errors by Suspicious Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-the-windows-error-code-0x8007251d-for-activation/"><u>Eliminating the Windows Error Code 0X8007251D for Activation</u></a></li>
<li><a href="https://windows11.techidaily.com/embracing-evenings-learning-paints-dark-mode-features/"><u>Embracing Evenings: Learning Paint's Dark Mode Features</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-live-performance-on-task-monitor-win-11/"><u>Enhance Live Performance on Task Monitor Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-pc-finding-leverage-everywhereapp/"><u>Enhance PC Finding: Leverage EverywhereApp</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-the-real-time-update-speed-of-task-manager/"><u>Enhance the Real-Time Update Speed of Task Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-user-experience-add-portable-software-to-windows/"><u>Enhance User Experience: Add Portable Software to Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-your-typing-speed-via-typingaid-tactics/"><u>Enhance Your Typing Speed via TypingAid Tactics</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-your-workflow-top-5-windows-folder-techniques/"><u>Enhance Your Workflow: Top 5 Windows Folder Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-alt-code-function-on-windows-46-characters/"><u>Enhancing ALT Code Function on Windows (46 Characters)</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-buffer-free-browsing-chromium-and-youtube/"><u>Enhancing Buffer-Free Browsing: Chromium & YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-file-management-on-windows-11-with-new-actions/"><u>Enhancing File Management on Windows 11 with New Actions</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-performance-lowering-edges-resource-load/"><u>Enhancing Performance: Lowering Edge's Resource Load</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-power-indicators-set-up-fully-charged-notifications-on-windows-11/"><u>Enhancing Power Indicators: Set up Fully Charged Notifications on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-productivity-grouped-software-installs-on-windows-11-using-winstall/"><u>Enhancing Productivity: Grouped Software Installs on Windows 11 Using Winstall</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-storage-management-on-win-1011/"><u>Enhancing Storage Management on Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-clear-audio-a-quick-guide-for-windows-users/"><u>Ensuring Clear Audio: A Quick Guide for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-cortana-records-are-saved-windows-method/"><u>Ensuring Cortana Records Are Saved: Windows Method</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-proper-rights-in-fixing-insufficient-privilege-install-errors/"><u>Ensuring Proper Rights in Fixing Insufficient Privilege Install Errors</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/essential-steps-to-producing-a-youtube-hit-music-reaction-video-guide-for-2024/"><u>Essential Steps to Producing a YouTube Hit  Music Reaction Video Guide for 2024</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/evaluating-the-sony-xperia-5-unique-blend-of-portability-and-costliness/"><u>Evaluating the Sony Xperia 5: Unique Blend of Portability & Costliness</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-reset-apple-id-and-apple-password-from-iphone-13-by-drfone-ios/"><u>How to Reset Apple ID and Apple Password From iPhone 13</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-with-location-spoofer-on-htc-u23-pro-drfone-by-drfone-virtual-android/"><u>How To Simulate GPS Movement With Location Spoofer On HTC U23 Pro? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-imei-unlokers-for-your-motorola-edge-40-neo-phone-by-drfone-android/"><u>In 2024, Top IMEI Unlokers for Your Motorola Edge 40 Neo Phone</u></a></li>
<li><a href="https://article-files.techidaily.com/in-2024-why-cant-i-watch-video-on-sony-a6400-camera/"><u>In 2024, Why Can't I Watch Video on Sony A6400 Camera?</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-restoring-ccleaner-on-win11/"><u>Mastering the Art: Restoring CCleaner on Win11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/navigating-chatgpt-discussions-seamlessly-through-the-use-of-organizational-folders/"><u>Navigating ChatGPT Discussions Seamlessly Through the Use of Organizational Folders</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/ps5-purchase-is-it-justified-discover-the-five-compelling-reasons-to-level-up-your-gaming-experience/"><u>PS5 Purchase: Is It Justified? Discover the Five Compelling Reasons to Level Up Your Gaming Experience</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/sim-unlock-realme-c67-4g-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>Sim Unlock Realme C67 4G Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://extra-information.techidaily.com/ultimate-choice-10-excellent-camera-lenses/"><u>Ultimate Choice  10 Excellent Camera Lenses</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-the-power-of-open-source-with-sk1-a-comprehensive-two-trees-supercomputer-evaluation/"><u>Unveiling the Power of Open Source with SK1 - A Comprehensive Two Trees Supercomputer Evaluation</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>