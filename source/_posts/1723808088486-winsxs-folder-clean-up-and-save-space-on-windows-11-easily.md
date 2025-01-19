---
title: "WinSxS Folder: Clean Up and Save Space on Windows 11 Easily"
date: 2025-01-15T19:22:44.286Z
updated: 2025-01-19T16:53:27.481Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes WinSxS Folder: Clean Up and Save Space on Windows 11 Easily"
excerpt: "This Article Describes WinSxS Folder: Clean Up and Save Space on Windows 11 Easily"
thumbnail: https://thmb.techidaily.com/cceaece01aa4bcb3e2bd94d9a7dafd046bccc2616fb9998b912dd3cd3c939c21.jpg
---

## WinSxS Folder: Clean Up and Save Space on Windows 11 Easily

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_59759c33baabd.png)

 This is among the usually asked questions: can I delete WinSxS folder to free up some disk space?

The answer is, no.

 Nor can you delete everything in the WinSxS folder, because some of the files are important for Windows to run and update. Basically, WinSxS folder is where the files needed for your Windows are, as well as backups and/or updates of those files.

 But there are many ways you can use to reduce the size for your WinSxS folder on Windows 10\. In this post, we will be introducing two of them. So you will at least have one option that works.

[**1. Use Disk Cleanup**](https://tools.techidaily.com/drivereasy/download/)

[**2. Use DISM Tool**](https://tools.techidaily.com/drivereasy/download/)

**WARNING** : It is never suggested that you use a third-party tool to cleanup your WinSxS file, since faulty deleting the whole folder or some files in the folder might end up breaking your computer, making it impossible to boot or update.

## **1\. Use Disk Cleanup**

 Disk cleanup is a built-in tool that helps you delete temporary files. To run it, just follow:

 1) On your keyboard, press**Windows logo** button, then type in**disk cleanup** . Then choose**Disk Cleanup** from the list.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975b754c83e3.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sXLLPY11of0?si=-3YNnpnO0wbc0K_-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 2) If you haven’t changed the location where you placed your system file, choose**(C:)** and click**OK** . If you have changed the file location before, choose the correct file directory accordingly.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975b948ea778.png)

 3) Under**Files to delete** sector, tick the boxes before the files you don’t need anymore and then hit**OK** to delete them. Select to highlight the file name to see more detailed information if you want.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975bc59c244b.png)

 4) If you need to free more space, you can also choose**Clean up system files** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975bf02990e3.png)

 Then you will be prompted to choose which system drive you want to clean up. Choose accordingly and the clean process will start right away.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975bf68b4ff6.png)

## **2\. Use DISM Tool**

**DISM**  stands for Deployment Image & Servicing Management. It is a tool that allows you to make changes to Windows features, packages, drivers, and international settings. In this case, we will use it to help us clean up our WinSxS folder.

 The process may take a long time. It some cases, it could take up to 30 minutes. Please don’t worry when it’s not finished after a long time. Please be patient until the process finishes.

 1) On your keyboard, press **Windows logo key**   and **X**   at the same time, then choose **Command Prompt (Admin)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c1bb42138.png)

 When prompted with the UAC, hit **Yes** to continue.

 2) In DISM window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /StartComponentCleanup

 This command helps you clean up files when your system is not in use.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c1fc428ac.png)

 3) Check for possible typo. Then hit**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c4b394177.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eu4vwlZcMvM?si=4vEczfVU4BUUFP-t" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 4) In the same DISM window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /StartComponentCleanup /ResetBase

 This command helps you remove all superseded versions of every component in the component store.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c546794f7.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6KXVWj6Ar1M?si=Cd_jktmoN3e9OzH3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 5) Make sure you have made no typo and hit**Enter** . Wait for it to finish.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c55d520c4.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3AGmFrtBLHw?si=VhvpUaXHPBHl6OT6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 6) Still in the same window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /SPSuperseded

 This command helps you reduce the amount of space used by a Service Pack.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c5c8b3c70.png)

7) Make sure that you have made no typo and hit Enter.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c5eb65aaf.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1dR4tF3VgyU?si=AJipgqZsNNxsRsBW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you need more assistance, feel free to leave us comment and we will see what else we can do to help.

Hope your problem solved!

* [system](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://some-guidance.techidaily.com/new-top-7-hydro-resistant-camcorders-explored/"><u>[New] Top 7 Hydro-Resistant Camcorders Explored</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-facebook-live-mastery-a-recording-journey/"><u>[Updated] In 2024, Facebook Live Mastery A Recording Journey</u></a></li>
<li><a href="https://fox-helps.techidaily.com/acclaimed-websites-for-google-pixel-tonal-sounds/"><u>Acclaimed Websites for Google Pixel Tonal Sounds</u></a></li>
<li><a href="https://tech-haven.techidaily.com/excel-evolution-unlocked-by-integrating-ai-ingenuity-of-chatgpt/"><u>Excel Evolution Unlocked by Integrating AI Ingenuity of ChatGPT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/expert-advice-how-to-enroll-in-chatgpts-innovative-plug-in-platform/"><u>Expert Advice: How to Enroll in ChatGPT's Innovative Plug-In Platform</u></a></li>
<li><a href="https://tech-haven.techidaily.com/exploring-chatgpts-text-limit-techniques-to-surpass-the-character-threshold/"><u>Exploring ChatGPT's Text Limit: Techniques to Surpass the Character Threshold</u></a></li>
<li><a href="https://tech-haven.techidaily.com/exploring-gemini-15s-game-changing-feature-of-handling-over-a-million-tokens-in-context/"><u>Exploring Gemini 1.5'S Game-Changing Feature of Handling Over a Million Tokens in Context</u></a></li>
<li><a href="https://tech-haven.techidaily.com/exploring-the-myth-is-chatgpt-losing-its-smart-edge-insights-from-openai/"><u>Exploring the Myth: Is ChatGPT Losing Its Smart Edge? Insights From OpenAI</u></a></li>
<li><a href="https://tech-haven.techidaily.com/from-concepts-to-canvas-ai-driven-painting-via-chatgpt/"><u>From Concepts to Canvas: AI-Driven Painting via ChatGPT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/from-data-to-decisions-the-journey-of-ai-through-transfer-learning/"><u>From Data to Decisions: The Journey of AI Through Transfer Learning</u></a></li>
<li><a href="https://tech-haven.techidaily.com/from-gpt-35-writes-journey-to-gpt-4s-innovations/"><u>From GPT-3.5' Writes: Journey to GPT-4's Innovations</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/full-guide-to-unlock-your-oppo-find-x6-by-drfone-android/"><u>Full Guide to Unlock Your Oppo Find X6</u></a></li>
<li><a href="https://article-tips.techidaily.com/high-performance-drones-sold-here-for-2024/"><u>High-Performance Drones Sold Here for 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-unbrick-a-dead-nokia-c210-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Unbrick a Dead Nokia C210 | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/mobile-scanning-solutions-for-iphone-transform-pdfsjpegs-into-searchable-files/"><u>Mobile Scanning Solutions for iPhone: Transform PDFs/JPEGs Into Searchable Files</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/-video-and-photography-mobile-apps-for-iphoneandroid-users/"><u>Top 5 Video & Photography Mobile Apps for iPhone/Android Users</u></a></li>
<li><a href="https://tech-revival.techidaily.com/troubleshooting-guide-reinstating-the-picture-showcase-tool-in-windows-11/"><u>Troubleshooting Guide: Reinstating the Picture Showcase Tool in Windows 11</u></a></li>
</ul></div>

