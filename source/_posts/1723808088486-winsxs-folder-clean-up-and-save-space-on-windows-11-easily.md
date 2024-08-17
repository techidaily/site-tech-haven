---
title: "WinSxS Folder: Clean Up and Save Space on Windows 11 Easily"
date: 2024-08-16T10:10:51.785Z
updated: 2024-08-17T10:10:51.785Z
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

 2) If you haven’t changed the location where you placed your system file, choose**(C:)** and click**OK** . If you have changed the file location before, choose the correct file directory accordingly.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975b948ea778.png)

 3) Under**Files to delete** sector, tick the boxes before the files you don’t need anymore and then hit**OK** to delete them. Select to highlight the file name to see more detailed information if you want.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975bc59c244b.png)

 4) If you need to free more space, you can also choose**Clean up system files** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975bf02990e3.png)

 Then you will be prompted to choose which system drive you want to clean up. Choose accordingly and the clean process will start right away.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975bf68b4ff6.png)

<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->

 3) Check for possible typo. Then hit**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c4b394177.png)
<!-- affiliate ads begin -->
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 4) In the same DISM window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /StartComponentCleanup /ResetBase

 This command helps you remove all superseded versions of every component in the component store.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c546794f7.png)

 5) Make sure you have made no typo and hit**Enter** . Wait for it to finish.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c55d520c4.png)
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 6) Still in the same window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /SPSuperseded

 This command helps you reduce the amount of space used by a Service Pack.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c5c8b3c70.png)
<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7) Make sure that you have made no typo and hit Enter.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c5eb65aaf.png)
<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-crafting-content-12-best-for-insta-edits/"><u>[New] 2024 Approved  Crafting Content  12 Best for Insta Edits</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-amplify-youtube-performance-rapid-video-rendering-guide-for-2024/"><u>[New] Amplify YouTube Performance - Rapid Video Rendering Guide for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/reating-impressive-3d-beginnings-on-youtube-for-2024/"><u>[New] Creating Impressive 3D Beginnings on YouTube for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-history-buffs-favorite-youtube-history-channels-for-2024/"><u>[New] History Buffs' Favorite YouTube History Channels for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-the-twittersphere-treasure-trove/"><u>[New] In 2024, The Twittersphere Treasure Trove</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-mobiles-best-explore-8-leading-free-mp3-download-applications/"><u>[New] Mobile's Best  Explore 8 Leading Free MP3 Download Applications</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-pcs-premier-ps3-clones-2023-edition-for-2024/"><u>[New] PC's Premier PS3 Clones - 2023 Edition for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-360-camera-buying-guide-how-to-choose-a-suitable-360-camera-2023-update/"><u>[Updated] 360 Camera Buying Guide  How to Choose a Suitable 360 Camera -2023 Update</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-average-income-for-popular-youtube-creators-for-2024/"><u>[Updated] Average Income for Popular YouTube Creators for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-achieve-professional-quality-on-yt-with-simple-blurring/"><u>[Updated] In 2024, Achieve Professional Quality on YT with Simple Blurring</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-instantaneously-enhance-your-facebook-page-with-songs/"><u>[Updated] Instantaneously Enhance Your Facebook Page with Songs</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-pinnacle-of-macro-photography-and-cinematography/"><u>[Updated] The Pinnacle of Macro Photography and Cinematography</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-time-tagging-in-picture-editing-software/"><u>[Updated] Time Tagging in Picture Editing Software</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-top-10-screen-capture-apps-your-mac-guide-to-choosing-wisely-for-2024/"><u>[Updated] Top 10 Screen Capture Apps  Your Mac Guide to Choosing Wisely for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/approved-mastering-youtube-video-edits-with-adobe-premiere/"><u>2024 Approved  Mastering YouTube Video Edits with Adobe Premiere</u></a></li>
<li><a href="https://location-social.techidaily.com/does-find-my-friends-work-on-zte-nubia-flip-5g-drfone-by-drfone-virtual-android/"><u>Does find my friends work on ZTE Nubia Flip 5G | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/elevating-articles-with-chatgpts-assistance/"><u>Elevating Articles with ChatGPT's Assistance</u></a></li>
<li><a href="https://tech-haven.techidaily.com/enhancing-your-python-workflow-with-gpt-3-essential-strategies-and-examples/"><u>Enhancing Your Python Workflow With GPT-3: Essential Strategies and Examples</u></a></li>
<li><a href="https://buynow-info.techidaily.com/1722668869789-expert-picks-top-performing-outside-media-drives-of-the-year-20236/"><u>Expert Picks: Top-Performing Outside Media Drives of the Year 202#36</u></a></li>
<li><a href="https://tech-haven.techidaily.com/explore-the-best-ai-based-notetaking-solutions-top-6-picks-for-quality-notes/"><u>Explore the Best AI Based Notetaking Solutions: Top 6 Picks for Quality Notes</u></a></li>
<li><a href="https://tech-haven.techidaily.com/exploring-vector-databases-for-ai-progress/"><u>Exploring Vector Databases for AI Progress</u></a></li>
<li><a href="https://tech-haven.techidaily.com/financial-wisdom-in-emojis-unveiling-trends-and-concerns/"><u>Financial Wisdom in Emojis: Unveiling Trends & Concerns</u></a></li>
<li><a href="https://howto.techidaily.com/fixing-persistent-pandora-crashes-on-honor-x50-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixing Persistent Pandora Crashes on Honor X50 | Dr.fone</u></a></li>
<li><a href="https://win-amazing.techidaily.com/free-and-easy-guide-to-installing-intel-82579v-drivers-start-today/"><u>Free & Easy Guide to Installing Intel 82579V Drivers – Start Today</u></a></li>
<li><a href="https://tech-haven.techidaily.com/generative-change-what-jobs-are-at-risk/"><u>Generative Change: What Jobs Are at Risk?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/guide-to-wiping-out-your-chatgpt-presence-from-sign-out-to-full-erasure/"><u>Guide to Wiping Out Your ChatGPT Presence – From Sign Out to Full Erasure</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-ai-censorship-shapes-your-interaction-with-chatbots/"><u>How AI Censorship Shapes Your Interaction with Chatbots</u></a></li>
<li><a href="https://program-issues.techidaily.com/how-to-fix-continuous-buffering-issues-during-discord-live-broadcasts/"><u>How to Fix Continuous Buffering Issues During Discord Live Broadcasts</u></a></li>
<li><a href="https://fox-helps.techidaily.com/iconic-photographs-the-true-story/"><u>Iconic Photographs  The True Story</u></a></li>
<li><a href="https://tech-haven.techidaily.com/imitating-individual-style-with-chatgpt-the-ultimate-training-strategy/"><u>Imitating Individual Style with ChatGPT: The Ultimate Training Strategy</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-complete-guide-on-unlocking-iphone-14-pro-with-a-broken-screen-by-drfone-ios/"><u>In 2024, Complete Guide on Unlocking iPhone 14 Pro with a Broken Screen?</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-honor-x8bwithwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Honor X8bwith/without a PC</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-bypass-icloud-by-checkra1n-even-on-iphone-7-if-youve-tried-everything-by-drfone-ios/"><u>In 2024, How To Bypass iCloud By Checkra1n Even On iPhone 7 If Youve Tried Everything</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-posting-a-youtube-video-via-insta-stories-a-step-by-step-guide/"><u>In 2024, Posting a YouTube Video via Insta Stories  A Step-by-Step Guide</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-ways-to-trade-pokemon-go-from-far-away-on-apple-iphone-7-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, Ways to trade pokemon go from far away On Apple iPhone 7 Plus? | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/introducing-chatgpt-on-your-android-device/"><u>Introducing ChatGPT on Your Android Device</u></a></li>
<li><a href="https://tech-haven.techidaily.com/is-there-a-decline-in-chatgpt-smarts-or-myth-busting-time-openai-weighs-in/"><u>Is There a Decline in ChatGPT Smarts or Myth Busting Time - OpenAI Weighs In</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-microsoft-bing-with-ai-the-ultimate-sign-up-guide/"><u>Mastering Microsoft Bing with AI - The Ultimate Sign-Up Guide</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-the-effects-of-censorship-in-ai-chatbot-interactions/"><u>Navigating the Effects of Censorship in AI Chatbot Interactions</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-the-shift-the-role-of-ai-in-changing-software-development/"><u>Navigating the Shift: The Role of AI in Changing Software Development</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/network-locked-sim-card-inserted-on-your-itel-p40-phone-unlock-it-now-by-drfone-android/"><u>Network Locked SIM Card Inserted On Your Itel P40 Phone? Unlock It Now</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-imovie-pro-tips-how-to-detach-audio-tracks-efficiently-on-a-mac/"><u>New 2024 Approved IMovie Pro Tips How to Detach Audio Tracks Efficiently on a Mac</u></a></li>
<li><a href="https://extra-skills.techidaily.com/revive-your-photos-two-methods-to-restore-photo-viewing-in-win10-for-2024/"><u>Revive Your Photos  Two Methods to Restore Photo Viewing in Win10 for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/sarah-silverman-joins-legal-battle-against-openai-and-meta-an-inside-look/"><u>Sarah Silverman Joins Legal Battle Against OpenAI & Meta: An Inside Look</u></a></li>
<li><a href="https://tech-haven.techidaily.com/setting-achievable-wellness-targets-using-chatgpt-a-comprehensive-guide/"><u>Setting Achievable Wellness Targets Using ChatGPT: A Comprehensive Guide</u></a></li>
<li><a href="https://tech-haven.techidaily.com/share-your-ai-journey-apps-that-save-and-spread-your-chatgpt-dialogues/"><u>Share Your AI Journey: Apps That Save & Spread Your ChatGPT Dialogues</u></a></li>
<li><a href="https://tech-haven.techidaily.com/step-by-step-guide-to-combining-chatgpt-with-whatsapp-for-improved-support-services/"><u>Step-by-Step Guide to Combining ChatGPT with WhatsApp for Improved Support Services</u></a></li>
<li><a href="https://common-error.techidaily.com/successful-fix-windows-found-the-right-printer-driver/"><u>Successful Fix: Windows Found the Right Printer Driver</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/swift-film-techniques-for-at-home-creators/"><u>Swift Film Techniques for At-Home Creators</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-best-6-chatgpt-integrated-plugins-to-supercharge-your-vs-code-workflow/"><u>The Best 6 ChatGPT Integrated Plugins to Supercharge Your VS Code Workflow</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-hidden-threat-of-artificamo-intelligence-to-security-5-uses-in-cybercrime/"><u>The Hidden Threat of Artificamo Intelligence to Security: 5 Uses in Cybercrime</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-4-errors-in-content-creation-avoid-at-all-costs-with-chatgpt/"><u>Top 4 Errors in Content Creation: Avoid at All Costs with ChatGPT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-4-innovative-ai-tale-crafting-tools/"><u>Top 4 Innovative AI Tale Crafting Tools</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-6-ai-powered-note-taking-tools-for-enhanced-note-management/"><u>Top 6 AI-Powered Note-Taking Tools for Enhanced Note Management</u></a></li>
<li><a href="https://tech-haven.techidaily.com/understanding-the-paperclip-maximizer-implications-of-ai/"><u>Understanding the Paperclip Maximizer: Implications of AI</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unleash-your-creativity-utilizing-chatgpt-in-building-fantasy-universes/"><u>Unleash Your Creativity: Utilizing ChatGPT in Building Fantasy Universes</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unleashing-intelligence-at-your-fingerttaps-top-8-ai-phone-apps-for-ios-and-android-devices/"><u>Unleashing Intelligence at Your Fingerttaps: Top 8 AI Phone Apps for iOS & Android Devices</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unlock-advanced-writing-capabilities-for-free-with-copilot-and-the-enhanced-gpt-4-engine/"><u>Unlock Advanced Writing Capabilities for Free with Copilot and the Enhanced GPT-4 Engine</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unlock-the-potential-of-ai-discover-7-proven-methods-to-improve-your-prompts/"><u>Unlock the Potential of AI: Discover 7 Proven Methods to Improve Your Prompts</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unraveling-the-paperclip-maximizer-issue-connections-with-artificial-intelligence/"><u>Unraveling the Paperclip Maximizer Issue: Connections with Artificial Intelligence</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unveiling-the-mysteries-a-deep-dive-into-whos-listening-when-you-speak-online/"><u>Unveiling the Mysteries: A Deep Dive Into Who's Listening When You Speak Online</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unveiling-the-phenomenon-of-ai-hallucinations-recognition-strategies/"><u>Unveiling the Phenomenon of AI Hallucinations - Recognition Strategies</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unveiling-the-power-of-chatgpts-preinstalled-addons-their-purpose-demystified/"><u>Unveiling the Power of ChatGPT's Preinstalled Addons – Their Purpose Demystified</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unveiling-vector-databases-their-role-in-advancing-ai-technologies/"><u>Unveiling Vector Databases: Their Role in Advancing AI Technologies</u></a></li>
<li><a href="https://tech-haven.techidaily.com/why-are-websites-turning-off-on-gptbot-decoding-digital-battles/"><u>Why Are Websites Turning Off on GPTBot? Decoding Digital Battles</u></a></li>
<li><a href="https://tech-haven.techidaily.com/workplace-changes-can-gpt-replace-humans/"><u>Workplace Changes: Can GPT Replace Humans?</u></a></li>
</ul></div>
