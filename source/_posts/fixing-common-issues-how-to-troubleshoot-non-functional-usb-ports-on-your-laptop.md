---
title: "Fixing Common Issues: How To Troubleshoot Non-Functional USB Ports On Your Laptop"
date: 2025-01-09T16:37:28.003Z
updated: 2025-01-13T17:02:27.372Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Fixing Common Issues: How To Troubleshoot Non-Functional USB Ports On Your Laptop"
excerpt: "This Article Describes Fixing Common Issues: How To Troubleshoot Non-Functional USB Ports On Your Laptop"
thumbnail: https://thmb.techidaily.com/91e7f02bd957e18d2516616e2ae6cdb5e18d026273686f4e3b0840225091d98b.jpg
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
<li><a href="https://youtube-sure.techidaily.com/-vloggers-dream-exploring-the-best-12-video-capture-devices/"><u>[New] A Vlogger's Dream Exploring the Best 12 Video Capture Devices</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-free-tailor-made-templates-for-concluding-audio/"><u>[New] Free, Tailor-Made Templates for Concluding Audio</u></a></li>
<li><a href="https://youtube-data.techidaily.com/remium-watchlists-highest-youtube-movie-selections-for-2024/"><u>[New] Premium Watchlists Highest YouTube Movie Selections for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-google-docs-speech-to-text-a-complete-guidebook/"><u>[Updated] Google Docs Speech-to-Text A Complete Guidebook</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-the-ultimate-guide-to-linking-fb-stories/"><u>[Updated] In 2024, The Ultimate Guide to Linking FB Stories</u></a></li>
<li><a href="https://tech-haven.techidaily.com/50-mobile-discounts-and-expert-insights-on-cracking-ransomware-codes-podcast-with-chatgpt/"><u>$50 Mobile Discounts & Expert Insights on Cracking Ransomware Codes - Podcast with ChatGPT!</u></a></li>
<li><a href="https://tech-haven.techidaily.com/6-economically-sound-artificial-intelligence-options/"><u>6 Economically Sound Artificial Intelligence Options</u></a></li>
<li><a href="https://tech-haven.techidaily.com/ahead-in-the-race-of-language-chatgpt-vs-google-translate-accuracy-showdown/"><u>Ahead in the Race of Language: ChatGPT Vs. Google Translate Accuracy Showdown</u></a></li>
<li><a href="https://tech-haven.techidaily.com/ai-assisted-healthy-habits-structured-goals-with-chatgpt/"><u>AI-Assisted Healthy Habits: Structured Goals with ChatGPT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/apples-cutting-edge-ai-innovations-exposed-at-worldwide-developers-conference-wwdc-2024/"><u>Apple's Cutting-Edge AI Innovations Exposed at Worldwide Developers Conference (WWDC) 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/artificinas-intelligentes-5-momentos-en-el-lado-del-ciberdelincuencia/"><u>Artificinas Intelligentes: 5 Momentos en El Lado Del Ciberdelincuencia</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/ensure-seamless-performance-download-intel-usb-30-support-software-for-windows-10/"><u>Ensure Seamless Performance: Download Intel USB 3.0 Support Software for Windows 10</u></a></li>
<li><a href="https://tech-haven.techidaily.com/1721990789186-explore-discreet-ai-chatting-with-duckduckgo-connect-securely-using-gpt-and-advanced-tools/"><u>Explore Discreet AI Chatting with DuckDuckGo - Connect Securely Using GPT and Advanced Tools</u></a></li>
<li><a href="https://fake-location.techidaily.com/fake-the-location-to-get-around-the-mlb-blackouts-on-itel-p55-drfone-by-drfone-virtual-android/"><u>Fake the Location to Get Around the MLB Blackouts on Itel P55 | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-unlocking-the-potential-of-aiseesoft-for-video-documentation/"><u>In 2024, Unlocking the Potential of Aiseesoft for Video Documentation</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/seamless-syntax-system/"><u>Seamless Syntax System</u></a></li>
<li><a href="https://fix-guide.techidaily.com/simple-solutions-to-fix-android-systemui-has-stopped-error-for-motorola-edgeplus-2023-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Simple Solutions to Fix Android SystemUI Has Stopped Error For Motorola Edge+ (2023) | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/why-are-sites-stifling-access-to-gptbot-insights-revealed/"><u>Why Are Sites Stifling Access to GPTBot? Insights Revealed</u></a></li>
<li><a href="https://tech-haven.techidaily.com/write-less-achieve-more-with-ai-assistants/"><u>Write Less, Achieve More with AI Assistants</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YpnYKIrpgZQ?si=94zicAHp1CH-0oso" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

