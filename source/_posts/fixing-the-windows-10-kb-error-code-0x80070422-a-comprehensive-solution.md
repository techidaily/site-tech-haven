---
title: "Fixing the Windows 10 KB Error Code 0X80070422: A Comprehensive Solution"
date: 2025-01-09T17:51:13.817Z
updated: 2025-01-13T16:02:54.393Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Fixing the Windows 10 KB Error Code 0X80070422: A Comprehensive Solution"
excerpt: "This Article Describes Fixing the Windows 10 KB Error Code 0X80070422: A Comprehensive Solution"
thumbnail: https://thmb.techidaily.com/7fab9a6185158d097b206408c1b02e98fd2b514b00431bdf0c9ec5881d711d0e.jpg
---

## Resolving Windows 10 Installation Issue - Fix Error Code 80 #

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
<li><a href="https://instagram-videos.techidaily.com/new-from-followers-to-fans-5-essential-instagram-tactics-for-influencers-for-2024/"><u>[New] From Followers to Fans 5 Essential Instagram Tactics for Influencers for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-in-2024-unveiling-10plus-proven-techniques-for-selecting-the-finest-cricket-broadcasts/"><u>[New] In 2024, Unveiling 10+ Proven Techniques for Selecting the Finest Cricket Broadcasts</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-from-dungeon-crawlers-to-complex-gameplay/"><u>[Updated] In 2024, From Dungeon Crawlers to Complex Gameplay</u></a></li>
<li><a href="https://howto.techidaily.com/calls-on-samsung-galaxy-a05-go-straight-to-voicemail-12-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Calls on Samsung Galaxy A05 Go Straight to Voicemail? 12 Fixes | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/chatgpts-intellect-shows-strength-openai-asserts/"><u>ChatGPT's Intellect Shows Strength, OpenAI Asserts</u></a></li>
<li><a href="https://tech-haven.techidaily.com/creative-ways-to-use-chatgpt-and-transform-your-dandd-campaigns/"><u>Creative Ways to Use ChatGPT and Transform Your D&D Campaigns</u></a></li>
<li><a href="https://tech-haven.techidaily.com/demystifying-the-issue-of-synchronizing-artificial-intelligence-with-human-values/"><u>Demystifying the Issue of Synchronizing Artificial Intelligence with Human Values</u></a></li>
<li><a href="https://tech-haven.techidaily.com/easy-instructions-running-chatgpt-seamlessly-on-windows-devices/"><u>Easy Instructions: Running ChatGPT Seamlessly on Windows Devices</u></a></li>
<li><a href="https://tech-haven.techidaily.com/efficient-chat-management-using-chatgpt-folder-techniques/"><u>Efficient Chat Management Using ChatGPT Folder Techniques</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-infinix-hot-30-5g-drfone-by-drfone-virtual-android/"><u>How to Get and Use Pokemon Go Promo Codes On Infinix Hot 30 5G | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/live-streaming-pro-master-the-art-with-manycams-ultimate-virtual-camera-solution/"><u>Live Streaming Pro: Master the Art with ManyCam's Ultimate Virtual Camera Solution</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlVkEwpjKKo?si=hXi-mchMaJvbnIzM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

