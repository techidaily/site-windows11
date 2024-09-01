---
title: "Propel Window's Video Workflow: Adopt Distributed Power by Tdarr Technology"
date: 2024-08-31T22:09:37.682Z
updated: 2024-09-01T22:09:37.682Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Propel Window's Video Workflow: Adopt Distributed Power by Tdarr Technology"
excerpt: "This Article Describes Propel Window's Video Workflow: Adopt Distributed Power by Tdarr Technology"
keywords: Propel Windows,Video Workflow,Distributed Power,Tdarr Tech,Media Streaming,Cloud Collaboration,Video Production
thumbnail: https://thmb.techidaily.com/4fec1082aae14c609dc25605c639b1fbe3c36aac7cabbe84615d93d1098bb494.jpg
---

## Propel Window's Video Workflow: Adopt Distributed Power by Tdarr Technology

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

### Tdarr's Hardware Requirements

 You can run the Tdarr server and the node software on any PC and access its interface through almost any browser. However, your hardware's performance and features can significantly affect encoding speeds.

 For example, a node running on a modern AMD Ryzen CPU will encode the same video in a blink compared to a ten-year-old Intel Celeron.

 Another node, using Nvidia's **NVEnc** hardware encoder for transcoding, will, in turn, be much faster than the AMD Ryzen CPU, but will also produce lower quality or larger files.

 So, if you find Tdarr's encoding too slow, you have two options:

* Try a less demanding codec or one that's "hardware accelerated" by your hardware.
* Upgrade to better hardware.

 Apart from that, you can run Tdarr even on a ten-year-old laptop if you can tolerate slow encoding speeds.

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
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
![Tdarr Define Library Source Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-define-library-source-crop.jpg)
7. Move to the **Transcode cache** tab and enter the full path to your "Temporary" folder in the **Cache** field.  
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
![Tdarr Set Transcode Cache to Temporary Folder Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-set-transcode-cache-to-temporary-folder-crop.jpg)
8. Finally, move to the **Output folder**, and as you might have guessed, enter the full path to your "Ready" folder in the **Output** field.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Tdarr Point Output Folder to Ready Folder Path Copy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-point-output-folder-to-ready-folder-path-copy.jpg)
9. Click the switch next to **Output Folder** on that tab to have Tdarr use the Incoming and Ready folders as Input and Output. If you don't do that, Tdarr will store everything in the Incoming folder. If you've got many media files, that can quickly get messy.

 If you wish, you can control the rate at which Tdarr scans the Incoming folder for new files. To do that, move to your library's **Source** tab, scroll down a bit, and change the number in the **Folder watch scan interval** field under **Folder watch settings**.

 Similarly, right below, you can tell it to run an hourly scan and define how many **File scanner threads** that will use. If you store your media on NVMe or SSD drives, increasing the number of File scanner threads can boost performance.

 Older mechanical HDDs, though, take a significant hit in performance when trying to access files in parallel, so it's best not to exceed the default value of "**2**" for those. You can also enable the option to **Hold files after scanning** and define how long (in seconds) those files will remain locked to ensure other apps won't interfere with them.

 Your library's **Filters** tab lets you define resolutions and codecs you'd prefer to skip. If, for example, you want Tdarr only to **downscale** videos, you can enter all the popular lower resolutions up to your monitor's native resolution (like "360p", "720p", and "1080p"), separated by commas in the **Resolutions to skip field**.

![Tdarr Library Filters Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-library-filters-crop.jpg)

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
 The **Codecs to skip** field works similarly. For example, if you type "**AV1, HEVC**" in that field, Tdarr won't try re-encoding video files already compressed with those codecs.

![Tdarr Library Filter Skip Code Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-library-filter-skip-code-crop.jpg)

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 To have Tdarr process your files, it will have to watch the incoming folder to detect changes (AKA: new files). For that, visit your library's **Source** tab and flick the switch next to **Folder watch** to the right.

![Tdarr Library Source Enable Folder Watch Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-library-source-enable-folder-watch-crop.jpg)

<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Tdarr Node Selection Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-node-selection-crop.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
1. You will see more details about the selected node, and you can use the **plus** and **minus** buttons next to **Transcode** and **Health Check** to assign to the node CPU and GPU threads for each task. This way, you control which node does what, which is especially useful in a multi-computer environment.  
![Tdarr Node Transcode and Health Check Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-node-transcode-and-health-check-crop.jpg)
2. Click on your node's **Options** button to access its more advanced options.
3. You can manually edit the node's configuration from here. Still, it's best to leave it as is and only manipulate it using external applications like Notepad.  
![Tdarr Node Config](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-node-config-1.jpg)
4. Scroll down and use the drop-down menu to select which type of GPU acceleration you want the node to use (if available on your hardware).  
![Tdarr Node Hardware Encoding Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-node-hardware-encoding-crop.jpg)
5. If you want to use the PC on which the node runs for other tasks while encoding, flick the switch under **Low FFMPEG/HandBrake Process Priority** to have the node consume fewer resources and avoid choking your PC. Alternatively, [use an app like Process Lasso to take control of your CPU threads](https://www.makeuseof.com/process-lasso-take-control-of-cpu-threads/) and ensure it won't start crawling while encoding.
6. For even more control, you can scroll down further and create a **Node schedule**, stating which hours of the day a node will be allowed to perform health-checking or transcoding tasks using the CPU or GPU.
7. When you return to the **Nodes** panel with at least one CPU or GPU assigned for transcoding and health checks, you will see that your node has started working on your incoming file.  
![Tdarr Node Scanning Media File Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-node-scanning-media-file-crop.jpg)
8. After an initial check and if the incoming file doesn't match your filter, Tdarr will start transcoding it.
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->

 You can see the result when it's done if you scroll to the **Staging** section where, in our case, the status of our file was "**Transcode Success**", and its size was down to around 49 MB. The **Handling** field on the right offers three buttons for controlling the entries of this list.

 Using those, you can requeue, skip, or accept an encode. You can find the re-encoded version of your file inside the "Ready" folder.

![Tdarr Re encoded File in Ready Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-re-encoded-file-in-ready-folder.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=14095146&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8b6cc3ee5ec407721ce3bf5ff4c0f56b/PRO_BUY_728x90-EN.jpg" border="0"></a>
<!-- affiliate ads end -->
## Network & Hardware-Accelerated Encoding

 Tdarr is best when using all the CPU and GPU power of all PCs on your local network for re-encoding your files. However, that's a bit more complicated to set up.

 For this part of our guide, we take for granted that you have more than one PC, and they can "see" each other through your local network. You've got the PCs but haven't "networked them" yet? Choose a networking approach from our collection of [diagrams on which to base your home network for full connectivity](https://www.makeuseof.com/home-network-setup-diagrams/), and then follow our guide on [how to set up a secure home network](https://www.makeuseof.com/home-network-setup/).

1. Since all the PCs that will become nodes in Tdarr's network will require access to the same media files, you should keep them in a network-accessible shared folder. It's better to use a dedicated network drive for that. Still, we shared the same "Videos" folder we created earlier, but with "**shared**" as its network alias.  
![Tdarr Shared Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-shared-folder.jpg)
2. Update the **Source**, **Transcode cache**, and **Output folder** paths of your library to point to the respective subfolders within your "Shared" folder.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
3. Install Tdarr on the other PCs in your local network. Use your file manager to enter the "**configs**" folder in Tdarr's installation directory.  
![Tdarr Config Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-config-folder.jpg)
4. Make a copy of the "**Tdarr\_Node\_Config.json**" file, then open the original with a text editor (like Notepad).  
![Tdarr Node Config in Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-node-config-in-explorer-1.jpg)
5. You can change the value next to "**nodeName**" to assign the node any name you wish, like "my\_laptop", to make it easier to recognize and manage what runs where. Next to "**serverIP**", enter the IP of the PC on which you run the Tdarr server. As the "**serverPort**", enter "**8266**".  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
![Tdarr Editing Node Config](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-editing-node-config.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
1. Next, you have to configure the "**pathTranslators**". This section is the most complicated to grasp since it needs you to define **pairs of paths**. Next to "**server**", you must enter the path from which the Tdarr server can access a particular folder.
2. Next to "**node**", you must enter the equivalent path from which a node can access the same folder through the network. So, the actual path to our incoming folder on the Tdarr server PC was **//vmware-host/Shared Folders/Shared/Incoming**, but the path to the same folder on our node PC was through the mapped network drive "D:" and the folders **/Shared/Incoming**.
3. You have to define a path translator for each of the folders you've specified in Tdarr's interface for your "Incoming", "Temporary", and "Output" folders. The goal is to have both the Tdarr server and its nodes able to find the same files through their respective paths.  
![Tdarr Node Config Path Translators](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-node-config-path-translators.jpg)
4. Run the node software on your second PC and ensure both its firewall and the one on your main Tdarr server PC allow connections between them. Our guide on [how to allow apps through Windows firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) can help with that. You should see the remote node popup in your Tdarr server interface if everything works correctly.  
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
![Tdarr Network Node Connected](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-network-node-connected.jpg)
5. Next to its address, you will see its IP address and be able to control its CPU and GPU threads and options as if it were a local node.
6. If GPU encoding doesn't work for you, it's probably because the appropriate plugin is disabled. For that, move back to the **Libraries** page, scroll down to find its tabs, and click on **Transcode options**.
7. There, enable the "**Migz-Transcode Using Nvidia GPU & FFMPEG**" plugin. You must also prioritize it over CPU encoding by left-clicking, dragging, and dropping it above the "**Migz-Transcode Using CPU & FFMPEG**" plugin.  
![Tdarr Libraries Enable Hardware Transcoding Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-libraries-enable-hardware-transcoding-crop.jpg)
8. From the same spot, if you click on a plugin, you can configure some options about how it will work. However, we won't dive into those, for they're outside the scope of this article.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
![Tdarr Libraries Customize Hardware Transcoding Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-libraries-customize-hardware-transcoding-crop.jpg)
9. When you return to the **Nodes** panel, your nodes (for which you've enabled that) should be using their GPUs for transcoding.

## Set Up Your Auto-Multi-Hyper-Encoder With Tdarr

 Setting up complicated automation software like Tdarr can take a while and occasionally make you wonder why something doesn't work as intended. When you set it up, though, Tdarr feels like magic.

 Add its server and nodes to your computers' auto-startup sequences, and hey presto, your media will always be re-encoded to high-quality, smaller files, using the optimal resolutions and formats for every single "machine" in your network. All while taking advantage of all available CPUs and GPUs in your PCs without you having to lift a finger.

 If you have more than one PC in your home network, why not let them lend a helping hand when transcoding media? Tdarr can turn all your PCs into nodes of the same networked transcoder, resulting in much faster audio and video encoding. Let's see how.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-lab.techidaily.com/024-approved-essential-guide-top-10-free-youtube-to-mp3-tools/"><u>[New] 2024 Approved  Essential Guide  Top 10 Free YouTube-to-MP3 Tools</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ring-your-spotify-mixes-online-5-top-playlist-conversion-apps-for-youtube/"><u>[New] Bring Your Spotify Mixes Online  5 Top Playlist Conversion Apps for YouTube</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-maximize-impact-with-professional-grade-fb-cover-videos/"><u>[New] Maximize Impact with Professional-Grade FB Cover Videos</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-youtubes-next-gen-streaming-made-easy-with-obs-tutorial/"><u>[New] Youtube's Next Gen Streaming Made Easy with OBS Tutorial</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-how-to-record-google-meet-for-2024/"><u>[Updated] How to Record Google Meet for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-unlocking-content-discovery-with-instagram-hashtags-for-2024/"><u>[Updated] Unlocking Content Discovery with Instagram Hashtags for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/3-ways-to-erase-apple-iphone-8-when-its-locked-within-seconds-by-drfone-ios/"><u>3 Ways to Erase Apple iPhone 8 When Its Locked Within Seconds</u></a></li>
<li><a href="https://hardware-help.techidaily.com/easy-setup-free-hp-photosmart-7520-printer-software/"><u>Easy Setup: Free HP Photosmart 7520 Printer Software</u></a></li>
<li><a href="https://fox-http.techidaily.com/elevate-your-yi-4k-experience-with-key-add-ons-for-2024/"><u>Elevate Your YI 4K Experience with Key Add-Ons for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/explore-extreme-device-integration-the-power-of-galaxys-dex-app/"><u>Explore Extreme Device Integration: The Power of Galaxy's DeX App</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-power-settings-on-windows-desktops/"><u>Exploring Power Settings on Windows Desktops</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-oneplus-ace-2-to-samsung-galaxy-s21-ultra-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos From OnePlus Ace 2 to Samsung Galaxy S21 Ultra | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-use-phone-clone-to-migrate-your-xiaomi-14-ultra-data-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Use Phone Clone to Migrate Your Xiaomi 14 Ultra Data? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/learn-to-unbind-your-onedrive-and-microsoft-profile-on-windows/"><u>Learn to Unbind Your OneDrive & Microsoft Profile on Windows</u></a></li>
<li><a href="https://hardware-help.techidaily.com/master-your-tech-world-expert-advice-from-toms-hardware-insights/"><u>Master Your Tech World: Expert Advice From Tom's Hardware Insights</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-app-migration-to-your-new-windows-11-laptop/"><u>Mastering App Migration to Your New Windows 11 Laptop</u></a></li>
<li><a href="https://technical-tips.techidaily.com/mastering-hardware-choices-wisdom-from-toms-technological-review/"><u>Mastering Hardware Choices - Wisdom From Tom's Technological Review</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-canary-vulnerability-alerts/"><u>Mastering Windows’ Canary Vulnerability Alerts</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-unlock-your-creative-potential-10-top-music-video-editing-software-for-2024/"><u>New Unlock Your Creative Potential 10 Top Music Video Editing Software for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/organizing-ideas-visual-note-taking-using-obsidian/"><u>Organizing Ideas: Visual Note-Taking Using Obsidian</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-blocked-app-warning-on-windows-os/"><u>Overcoming Blocked App Warning on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-pink-screens-with-ease-and-speed/"><u>Overcoming Windows Pink Screens with Ease and Speed</u></a></li>
<li><a href="https://windows11.techidaily.com/proactive-pc-management-keeping-windows-11s-amd-drivers-current/"><u>Proactive PC Management: Keeping Windows 11'S AMD Drivers Current</u></a></li>
<li><a href="https://windows11.techidaily.com/quickly-restart-print-spool-in-windows/"><u>Quickly Restart Print Spool in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/reconfiguring-system-settings-managed-by-your-organization-on-windows-11/"><u>Reconfiguring System Settings Managed by Your Organization on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/regain-control-over-windows-11s-dropped-items/"><u>Regain Control Over Windows 11'S Dropped Items</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-non-responsive-windows-netflix-application/"><u>Resolving Non-Responsive Windows Netflix Application</u></a></li>
<li><a href="https://windows11.techidaily.com/revive-stalled-access-on-credential-store/"><u>Revive Stalled Access on Credential Store</u></a></li>
<li><a href="https://windows11.techidaily.com/secrets-resolving-uncontrolled-mouse-jitter-in-win11/"><u>Secrets: Resolving Uncontrolled Mouse Jitter in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/simplify-tasks-with-your-default-windows-terminal/"><u>Simplify Tasks With Your Default Windows Terminal</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-zerodxgierordevicelatencyerror-for-win11-users/"><u>Solving ZeroDXGIErorDeviceLatencyError for Win11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-windows-update-failures-with-these-fixes/"><u>Stop Windows Update Failures with These Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-coding-process-essential-wsl-2-tips-and-tricks-for-dev/"><u>Streamline Coding Process: Essential WSL 2 Tips and Tricks for Dev</u></a></li>
<li><a href="https://windows11.techidaily.com/swiftly-tap-into-disk-access-4-ways-to-engage-with-disk-editor-settings-on-win11/"><u>Swiftly Tap Into Disk Access: 4 Ways to Engage with Disk Editor Settings on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-system-wake-up-shortening-boot-menu-hesitation-period/"><u>Tailoring System Wake-Up: Shortening Boot Menu Hesitation Period</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-reactivating-explore-in-11os/"><u>The Ultimate Guide to Reactivating Explore in 11OS</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-for-functional-thx-audio/"><u>Troubleshooting Windows for Functional THX Audio</u></a></li>
<li><a href="https://windows11.techidaily.com/unwrapping-the-mystery-microsoft-store-error-code-0x80073cf3/"><u>Unwrapping the Mystery: Microsoft Store Error Code 0X80073CF3</u></a></li>
<li><a href="https://windows11.techidaily.com/zip-file-chameleon-techniques-for-windows-images/"><u>ZIP File Chameleon Techniques for Windows Images</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>