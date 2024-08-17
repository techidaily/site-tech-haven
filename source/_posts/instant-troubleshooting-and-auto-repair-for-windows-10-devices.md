---
title: Instant Troubleshooting and Auto-Repair for Windows 10 Devices
date: 2024-08-16T10:03:44.698Z
updated: 2024-08-17T10:03:44.698Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes Instant Troubleshooting and Auto-Repair for Windows 10 Devices
excerpt: This Article Describes Instant Troubleshooting and Auto-Repair for Windows 10 Devices
thumbnail: https://thmb.techidaily.com/a63a5a9ae6eb1efed5733d165b83ad90e6d4d9274b455dfd2cda566223079352.jpg
---

## Error Code 80240020: Comprehensive Troubleshooting Steps for Windows 10 Installation Issues Resolved

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/img_58140207aba43-600x394.jpg)

 Your**Windows Update** panel should come out in a couple of seconds. If it won’t open automatically, you can open this panel from Control Panel manually. Then, you should be able to download your Windows 10 from scratch.

The steps above also work if you are having a**80080080** or **8024600A**  error code. Usually the error is common with Windows 8.1 users, but for those who are using Windows 7, this solution applies as well. If the problem still persists, please be patient, Windows update takes time to download the upgrades in the background. If you still could not get this problem fixed, your Windows update tool might be corrupted so the security settings and background process is now malfunctioned. In this case, it is suggested that you burn the DVD or CD or USB flash drive with Windows 10 ISO files in to do the clean install from scratch. If you want to know how to do it, please refer to[this post here](https://tools.techidaily.com/drivereasy/download/) for more information.

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
<li><a href="https://extra-resources.techidaily.com/new-best-4k-tvs-top-ten-selection/"><u>[New] Best 4K TVs  Top Ten Selection</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-celebrity-fleeting-frame-study-for-2024/"><u>[New] Celebrity Fleeting Frame Study for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-backup-blueprint-from-your-phone-to-your-snap-story/"><u>[New] In 2024, Backup Blueprint  From Your Phone to Your Snap Story</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-top-10-drawing-apps-for-android-unleash-your-inner-artist/"><u>[New] Top 10 Drawing Apps for Android Unleash Your Inner Artist</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-unveiling-the-mechanics-behind-instagrams-content-curation-for-2024/"><u>[New] Unveiling the Mechanics Behind Instagram’s Content Curation for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-itops-expert-selection-best-windows-screencasters/"><u>[Updated] 2024 Approved  ITop's Expert Selection  Best Windows Screencasters</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-pros-insight-top-8-online-repositories-for-free-green-screen-scenery/"><u>[Updated] Pros' Insight  Top 8 Online Repositories for Free Green Screen Scenery</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-virtual-showdown-evaluating-obs-versus-twitchs-channel-space/"><u>[Updated] Virtual Showdown  Evaluating OBS Versus Twitch's Channel Space</u></a></li>
<li><a href="https://android-location.techidaily.com/10-fake-gps-location-apps-on-android-of-your-xiaomi-redmi-note-12-pro-5g-drfone-by-drfone-virtual/"><u>10 Fake GPS Location Apps on Android Of your Xiaomi Redmi Note 12 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-simplify-information-storage-via-mematic/"><u>2024 Approved  Simplify Information Storage via Mematic</u></a></li>
<li><a href="https://location-fake.techidaily.com/3utools-virtual-location-not-working-on-poco-m6-5g-fix-now-drfone-by-drfone-virtual-android/"><u>3uTools Virtual Location Not Working On Poco M6 5G? Fix Now | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/bert-and-gpt-explained-the-linguistic-frontier/"><u>BERT and GPT Explained: The Linguistic Frontier</u></a></li>
<li><a href="https://tech-haven.techidaily.com/beware-top-9-phony-chatgpt-related-threats-that-could-compromise-your-data/"><u>Beware: Top 9 Phony ChatGPT-Related Threats That Could Compromise Your Data</u></a></li>
<li><a href="https://tech-haven.techidaily.com/beyond-talking-points-next-gen-ai-horizons/"><u>Beyond Talking Points: Next-Gen AI Horizons</u></a></li>
<li><a href="https://tech-haven.techidaily.com/chatgpt-as-a-developers-ally-discover-4-innovative-uses-for-crafting-websites/"><u>ChatGPT as a Developer's Ally: Discover 4 Innovative Uses for Crafting Websites</u></a></li>
<li><a href="https://tech-haven.techidaily.com/chatgpt-techniques-for-writing-compelling-youtube-scripts-like-a-pro/"><u>ChatGPT Techniques for Writing Compelling YouTube Scripts Like a Pro</u></a></li>
<li><a href="https://tech-haven.techidaily.com/delete-your-past-chats-with-chatgpt-a-comprehensive-how-to/"><u>Delete Your Past Chats with ChatGPT: A Comprehensive How-To</u></a></li>
<li><a href="https://tech-haven.techidaily.com/elevate-chatgpt-today-with-these-top-9-tools/"><u>Elevate ChatGPT Today! With These Top 9 Tools</u></a></li>
<li><a href="https://tech-haven.techidaily.com/exploring-the-contrasts-between-gpt-4-and-gpt-c35-a-deep-dive-into-their-key-variances/"><u>Exploring the Contrasts Between GPT-4 and GPT-C3.5: A Deep Dive Into Their Key Variances</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-everyone-can-utilize-gpt-4-the-ultimate-walkthrough-for-microsofts-groundbreaking-language-model/"><u>How Everyone Can Utilize GPT-4: The Ultimate Walkthrough for Microsoft's Groundbreaking Language Model</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-install-updated-drivers-for-your-nvidia-gtx-1660-super-gpu-step-by-step-guide/"><u>How to Install Updated Drivers for Your Nvidia GTX 1660 Super GPU: Step-by-Step Guide</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-ios-of-apple-iphone-13-pro-max-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair iOS of Apple iPhone 13 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-6-methods-to-share-apple-iphone-13-screen-with-pc-drfone-by-drfone-ios/"><u>In 2024, 6 Methods to Share Apple iPhone 13 Screen with PC | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-best-3-software-to-transfer-files-tofrom-your-oppo-a58-4g-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Best 3 Software to Transfer Files to/from Your Oppo A58 4G via a USB Cable | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-capturing-clarity-a-guide-to-high-res-videos-on-the-web/"><u>In 2024, Capturing Clarity  A Guide to High-Res Videos on the Web</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-discovering-expert-seed-selection-for-valheimers/"><u>In 2024, Discovering Expert Seed Selection for Valheimers</u></a></li>
<li><a href="https://tech-haven.techidaily.com/inside-chatgpt-enterprise-what-it-provides-how-it-stands-out-and-why-companerates-need-it/"><u>Inside ChatGPT Enterprise: What It Provides, How It Stands Out, and Why Companerates Need It</u></a></li>
<li><a href="https://tech-haven.techidaily.com/leveraging-chatgpts-language-skills-tips-for-non-english-speakers/"><u>Leveraging ChatGPT's Language Skills: Tips for Non-English Speakers</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigate-the-digital-world-seamlessly-with-perplexity-ai/"><u>Navigate The Digital World Seamlessly With Perplexity AI</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-animation-drawing-made-easy-top-software-picks-and-beyond/"><u>New Animation Drawing Made Easy Top Software Picks and Beyond</u></a></li>
<li><a href="https://tech-haven.techidaily.com/quick-guide-to-change-dall-e-3s-webp-output-into-png-or-jpg-formats/"><u>Quick Guide to Change DALL-E 3'S WebP Output Into PNG or JPG Formats</u></a></li>
<li><a href="https://windows11.techidaily.com/reintroduce-forgotten-bluetooth-items-devices-mgr/"><u>Reintroduce Forgotten Bluetooth Items Devices Mgr</u></a></li>
<li><a href="https://tech-haven.techidaily.com/running-chatgpt-seamlessly-on-windows-a-comprehensive-how-to/"><u>Running ChatGPT Seamlessly on Windows - A Comprehensive How-To</u></a></li>
<li><a href="https://tech-haven.techidaily.com/streamline-your-spreadsheets-with-these-three-chatgpt-techniques-for-excel-mastery/"><u>Streamline Your Spreadsheets with These Three ChatGPT Techniques for Excel Mastery</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-best-6-ai-powered-chatbot-plugins-to-boost-productivity-in-visual-studio-code/"><u>The Best 6 AI-Powered Chatbot Plugins to Boost Productivity in Visual Studio Code</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-secrets-out-engage-in-dialogue-with-chatgpt-today/"><u>The Secret's Out: Engage in Dialogue with ChatGPT Today</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-trouble-with-trusting-automated-ai-for-intellectual-property-protection/"><u>The Trouble With Trusting Automated AI for Intellectual Property Protection</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-ultimate-tutorial-for-chatgpt-plugins-from-install-to-implementation/"><u>The Ultimate Tutorial for ChatGPT Plugins: From Install to Implementation</u></a></li>
<li><a href="https://tech-haven.techidaily.com/understanding-nvidias-ai-foundations-an-insight-into-customizable-generative-ai/"><u>Understanding NVIDIA's AI Foundations: An Insight Into Customizable Generative AI</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unraveling-complexity-how-transfer-learning-simplifies-ai/"><u>Unraveling Complexity: How Transfer Learning Simplifies AI</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unraveling-the-top-6-chatgpt-issues-and-how-to-fix-them/"><u>Unraveling the Top 6 ChatGPT Issues and How to Fix Them</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->