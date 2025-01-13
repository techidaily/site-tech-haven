---
title: The Ultimate Guide to Accessing Windows 10 Recovery Options Menu Successfully
date: 2025-01-11T16:30:09.929Z
updated: 2025-01-13T16:02:35.995Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes The Ultimate Guide to Accessing Windows 10 Recovery Options Menu Successfully
excerpt: This Article Describes The Ultimate Guide to Accessing Windows 10 Recovery Options Menu Successfully
thumbnail: https://thmb.techidaily.com/f8511b1b508552460f630419c51d2d616ebcbf19dbd124bdf2e50582d197ea31.jpg
---

## Error Code 80240020 Deciphered: Easy Steps to Successfully Install Windows 10 without a Glitch

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
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-the-zen-of-zoom-talk-top-strategies-for-smooth-virtual-dialogue/"><u>[New] 2024 Approved The Zen of Zoom Talk Top Strategies for Smooth Virtual Dialogue</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-insta-self-portraits-are-they-truly-accurate/"><u>[Updated] In 2024, Insta Self-Portraits Are They Truly Accurate?</u></a></li>
<li><a href="https://sound-issues.techidaily.com/achieving-perfect-sound-recording-in-discord-while-playing-games-now-solved/"><u>Achieving Perfect Sound Recording in Discord While Playing Games - Now Solved!</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/acquire-high-quality-sounds-for-media-creators-in-2024/"><u>Acquire High-Quality Sounds for Media Creators, In 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/chatgpt-mastery-building-dynamic-web-apps-from-scratch/"><u>ChatGPT Mastery: Building Dynamic Web Apps From Scratch</u></a></li>
<li><a href="https://tech-haven.techidaily.com/confidentiality-concerns-evaluating-the-safety-of-sharing-sensitive-data-with-ai-like-chatgpt/"><u>Confidentiality Concerns: Evaluating the Safety of Sharing Sensitive Data with AI Like ChatGPT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/creating-distinctive-ai-art-with-microsoft-copilot-a-step-by-step-guide/"><u>Creating Distinctive AI Art with Microsoft Copilot: A Step-by-Step Guide</u></a></li>
<li><a href="https://tech-haven.techidaily.com/decoding-claude-pro-and-its-place-among-gpt-enhancements/"><u>Decoding Claude Pro and Its Place Among GPT Enhancements</u></a></li>
<li><a href="https://tech-haven.techidaily.com/decreasing-phantom-data-from-ai-through-precision-prompts/"><u>Decreasing Phantom Data From AI Through Precision Prompts</u></a></li>
<li><a href="https://tech-haven.techidaily.com/demystifying-gpt4alls-complex-processes/"><u>Demystifying GPT4All's Complex Processes</u></a></li>
<li><a href="https://tech-haven.techidaily.com/directive-design-mastery-top-7-online-learning-resources/"><u>Directive Design Mastery: Top 7 Online Learning Resources</u></a></li>
<li><a href="https://tech-haven.techidaily.com/easy-ways-to-distribute-access-to-your-chatgpt-sessions/"><u>Easy Ways to Distribute Access to Your ChatGPT Sessions</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-check-if-your-vivo-y78t-is-unlocked-by-drfone-android/"><u>How To Check if Your Vivo Y78t Is Unlocked</u></a></li>
<li><a href="https://fox-direct.techidaily.com/in-2024-champion-steadicams-for-uav-filmmaking-excellence/"><u>In 2024, Champion Steadicams for UAV Filmmaking Excellence</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-use-pokemon-go-joystick-on-motorola-g54-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Pokemon Go Joystick on Motorola G54 5G? | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/microphone-data-review-tips/"><u>Microphone Data Review Tips</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ultimate-guide-to-get-the-meltan-box-pokemon-go-for-motorola-edge-2023-drfone-by-drfone-virtual-android/"><u>Ultimate guide to get the meltan box pokemon go For Motorola Edge 2023 | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1CdWd06fCwc?si=wzg-68q0jAksPRXp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

