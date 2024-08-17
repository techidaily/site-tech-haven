---
title: "Fixing Common Issues: How To Troubleshoot Non-Functional USB Ports On Your Laptop"
date: 2024-08-16T10:07:30.467Z
updated: 2024-08-17T10:07:30.467Z
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
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-driveease-expert-review/"><u>[New] 2024 Approved  DriveEase Expert Review</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-inside-polarrs-magic-box-the-ultimate-digital-image-enhancer/"><u>[New] Inside Polarr's Magic Box  The Ultimate Digital Image Enhancer</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-golden-text-in-3d-selecting-quality-online-sites/"><u>[Updated] Golden Text in 3D  Selecting Quality Online Sites</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-mastering-social-media-tags-leading-tools-reviewed-fbtwitterinsta/"><u>[Updated] Mastering Social Media Tags  Leading Tools Reviewed (FB/Twitter/Insta)</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-optimal-data-buffering-for-sony-a7s-ii/"><u>2024 Approved  Optimal Data Buffering for Sony A7S II</u></a></li>
<li><a href="https://tech-haven.techidaily.com/a-clash-of-bots-is-gpt-plus-superior-to-perplexity/"><u>A Clash of Bots: Is GPT Plus Superior to Perplexity?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/a-deep-dive-into-the-transformative-shifts-from-gpt-35-to-gpt-4/"><u>A Deep Dive Into the Transformative Shifts From GPT-3.5 to GPT-4</u></a></li>
<li><a href="https://tech-haven.techidaily.com/academic-integrity-beyond-auto-generated-texts/"><u>Academic Integrity Beyond Auto-Generated Texts</u></a></li>
<li><a href="https://tech-haven.techidaily.com/adapting-to-success-top-six-tactics-for-the-automation-era-jobscape/"><u>Adapting to Success: Top Six Tactics for the Automation Era Jobscape</u></a></li>
<li><a href="https://tech-haven.techidaily.com/ais-next-phase-brings-heightened-security-threats/"><u>AI's Next Phase Brings Heightened Security Threats</u></a></li>
<li><a href="https://tech-haven.techidaily.com/artificial-intelligence-perfection-our-curated-list-of-best-tools-for-prompts/"><u>Artificial Intelligence Perfection: Our Curated List of Best Tools for Prompts</u></a></li>
<li><a href="https://tech-haven.techidaily.com/beating-isolation-harnessing-chatgpts-power/"><u>Beating Isolation: Harnessing ChatGPT's Power</u></a></li>
<li><a href="https://tech-haven.techidaily.com/boosting-daily-output-top-7-methods-chatgpt-improves-job-efficiency/"><u>Boosting Daily Output: Top 7 Methods ChatGPT Improves Job Efficiency</u></a></li>
<li><a href="https://tech-haven.techidaily.com/chatgpt-and-user-confidentiality-understanding-potential-risks/"><u>ChatGPT and User Confidentiality: Understanding Potential Risks</u></a></li>
<li><a href="https://vp-tips.techidaily.com/digital-pixels-at-your-command-curve-artfully-for-2024/"><u>Digital Pixels at Your Command  Curve Artfully for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/easing-into-cinematic-scene/"><u>Easing Into Cinematic Scene</u></a></li>
<li><a href="https://youtube-help.techidaily.com/game-up-your-content-with-these-effective-freefire-video-hashtags-for-2024/"><u>Game Up Your Content with These Effective FreeFire Video Hashtags for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-find-and-install-proper-dell-bluetooth-drivers-on-windows-platforms/"><u>How to Find and Install Proper Dell Bluetooth Drivers on Windows Platforms</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-boundaries-of-chatgpts-character-input-effective-methods-to-overcome-limitations/"><u>The Boundaries of ChatGPT's Character Input: Effective Methods to Overcome Limitations</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-ultimate-strategy-to-craft-targeted-user-personas-in-chatgpt-and-boost-engagement/"><u>The Ultimate Strategy to Craft Targeted User Personas in ChatGPT and Boost Engagement</u></a></li>
<li><a href="https://fake-location.techidaily.com/thinking-about-changing-your-netflix-region-without-a-vpn-on-realme-narzo-60x-5g-drfone-by-drfone-virtual-android/"><u>Thinking About Changing Your Netflix Region Without a VPN On Realme Narzo 60x 5G? | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/to-use-or-not-to-use-weighing-pros-and-cons-of-chatgpt-in-literary-compositions/"><u>To Use or Not to Use? Weighing Pros and Cons of ChatGPT in Literary Compositions</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-5-voice-commands-for-mastering-chatgpt/"><u>Top 5 Voice Commands for Mastering ChatGPT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/transform-your-food-habits-the-ultimate-strategy-for-personalized-meal-planning-with-chatgpt/"><u>Transform Your Food Habits: The Ultimate Strategy for Personalized Meal Planning with ChatGPT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/transforming-interactions-through-ai-learn-about-the-power-of-chatgpt-vision-with-these-8-tips/"><u>Transforming Interactions Through AI: Learn About the Power of ChatGPT Vision with These 8 Tips</u></a></li>
<li><a href="https://tech-haven.techidaily.com/troubleshooting-steps-to-fix-communication-error-between-chatgpt-and-plugins/"><u>Troubleshooting Steps to Fix Communication Error Between ChatGPT and Plugins</u></a></li>
<li><a href="https://tech-haven.techidaily.com/understanding-the-evolution-of-large-language-models-inside-googles-new-palm-2/"><u>Understanding the Evolution of Large Language Models - Inside Google's New PaLM 2</u></a></li>
<li><a href="https://tech-haven.techidaily.com/understanding-the-safety-profile-of-openais-chatbot-a-look-at-6-key-risks/"><u>Understanding the Safety Profile of OpenAI's Chatbot: A Look at 6 Key Risks</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unleash-your-imagination-best-5-ai-powered-text-creation-platforms/"><u>Unleash Your Imagination: Best 5 AI-Powered Text Creation Platforms</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unreliable-health-advice-from-digital-diagnosticians/"><u>Unreliable Health Advice From Digital Diagnosticians</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unveiling-9-key-platforms-where-aspiring-users-learn-about-artificial-intelligence-tools/"><u>Unveiling 9 Key Platforms Where Aspiring Users Learn About Artificial Intelligence Tools</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->