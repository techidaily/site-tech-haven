---
title: "Troubleshooting Guide: Resolving Issues with Arch Bluetooth Mouse on Windows 11 Creators Version"
date: 2025-01-14T20:03:21.547Z
updated: 2025-01-19T21:05:05.147Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Troubleshooting Guide: Resolving Issues with Arch Bluetooth Mouse on Windows 11 Creators Version"
excerpt: "This Article Describes Troubleshooting Guide: Resolving Issues with Arch Bluetooth Mouse on Windows 11 Creators Version"
thumbnail: https://thmb.techidaily.com/9304676ddebde0491fac069817e2e83439806cdb3bbe061f637b22cd4655ca5f.jpg
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
<li><a href="https://extra-tips.techidaily.com/new-boost-creativity-and-production-in-movies-xp-software/"><u>[New] Boost Creativity and Production in Movies XP Software</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-nightly-serenity-with-asmr-top-choices-to-listen-to/"><u>[New] Nightly Serenity with ASMR Top Choices to Listen To</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-choosing-between-obs-and-streamlabs-for-broadcast-excellence/"><u>[Updated] 2024 Approved Choosing Between OBS and Streamlabs for Broadcast Excellence</u></a></li>
<li><a href="https://network-issues.techidaily.com/elevate-your-display-experience-by-updating-to-the-latest-intel-hd-graphics-3000-in-w10/"><u>Elevate Your Display Experience by Updating to the Latest Intel HD Graphics 3000 in W10</u></a></li>
<li><a href="https://win-latest.techidaily.com/losung-fur-den-fehlenden-gespeicherten-excel-dokumentenabruf-wiederherstellungsstrategie/"><u>Lösung Für Den Fehlenden Gespeicherten Excel-Dokumentenabruf: Wiederherstellungsstrategie</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unlocking-the-power-of-distributing-your-ai-interactions/"><u>Unlocking the Power of Distributing Your AI Interactions</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unveiling-the-next-era-of-web-browsing-microsoft-brings-powerful-ai-to-revolutionize-bings-search-capabilities/"><u>Unveiling the Next Era of Web Browsing: Microsoft Brings Powerful AI to Revolutionize Bing's Search Capabilities</u></a></li>
<li><a href="https://tech-haven.techidaily.com/using-a-vpn-how-to-connect-with-chatgpt-securely/"><u>Using a VPN: How to Connect with ChatGPT Securely</u></a></li>
<li><a href="https://tech-haven.techidaily.com/utilizing-chatgpt-plus-for-efficient-and-effective-language-learning-strategies/"><u>Utilizing ChatGPT Plus for Efficient and Effective Language Learning Strategies</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uV3vm805eX0?si=YSPcsFxBcJmoxLsU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

