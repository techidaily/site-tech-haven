---
title: "Step-by-Step Guide: Accessing Disk Management on Your Windows 11 PC"
date: 2024-08-16T10:06:21.694Z
updated: 2024-08-17T10:06:21.694Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Step-by-Step Guide: Accessing Disk Management on Your Windows 11 PC"
excerpt: "This Article Describes Step-by-Step Guide: Accessing Disk Management on Your Windows 11 PC"
thumbnail: https://thmb.techidaily.com/77d2b3ef679b5fcf16ae0f3446de13ba438b3d48f4673334fb3a900060d9f0bc.jpg
---

## Effective Winsxs Directory Management: Free Up Disk Space on Windows 11 in a Flash

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

## **2\. Use DISM Tool**

**DISM**  stands for Deployment Image & Servicing Management. It is a tool that allows you to make changes to Windows features, packages, drivers, and international settings. In this case, we will use it to help us clean up our WinSxS folder.

 The process may take a long time. It some cases, it could take up to 30 minutes. Please don’t worry when it’s not finished after a long time. Please be patient until the process finishes.

 1) On your keyboard, press **Windows logo key**   and **X**   at the same time, then choose **Command Prompt (Admin)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c1bb42138.png)
<!-- affiliate ads begin -->
<span id="1793213">
					<video width="1080" height="1620" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19135-1793213">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:1080px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftinyland.pxf.io%2Fc%2F5597632%2F1793213%2F19135'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793213/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 When prompted with the UAC, hit **Yes** to continue.

 2) In DISM window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /StartComponentCleanup

 This command helps you clean up files when your system is not in use.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c1fc428ac.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4693127&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.videosoftdev.com/images/video_editor/screenshots/1.jpg" border="0">
VSDC Pro Video Editor is a light professional non-linear video editing suite for creating a movie of any complexity. It supports the most popular video/audio formats and codecs, including 4K, HD and GoPro videos. Preconfigured profiles make the creation of videos for various multimedia and mobile devices absolutely hassle-free.

Key features:

•	Import from any devices and cams, including GoPro and drones. All formats supported. Сurrently the only free video editor that allows users to export in a new H265/HEVC codec, something essential for those working with 4K and HD.
•	Everything for hassle-free basic editing: cut, crop and merge files, add titles and favorite music
•	Visual effects, advanced color correction and trendy Instagram-like filters   
•	All multimedia processing done from one app: video editing capabilities reinforced by  a video converter, a screen capture, a video capture, a disc burner and a YouTube uploader
•	Non-linear editing: edit several files with simultaneously 
•	Easy export to social networks: special profiles for YouTube, Facebook, Vimeo, Twitter and Instagram
•	High quality export – no conversion quality loss, double export speed even of HD files due to hardware acceleration
•	Stabilization tool will turn shaky or jittery footage into a more stable video automatically. 
•	Essential toolset for professional video editing: blending modes, Mask tool, advanced multiple-color Chroma Key  
</a>
<!-- affiliate ads end -->

 3) Check for possible typo. Then hit**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c4b394177.png)
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->

 4) In the same DISM window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /StartComponentCleanup /ResetBase

 This command helps you remove all superseded versions of every component in the component store.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c546794f7.png)
<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->

 5) Make sure you have made no typo and hit**Enter** . Wait for it to finish.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c55d520c4.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->

 6) Still in the same window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /SPSuperseded

 This command helps you reduce the amount of space used by a Service Pack.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c5c8b3c70.png)
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7) Make sure that you have made no typo and hit Enter.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c5eb65aaf.png)

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
<li><a href="https://tech-haven.techidaily.com/bard-how-google-is-stepping-up-to-compete-in-the-ai-conversationalist-space-against-chatgpt/"><u>'BARD': How Google Is Stepping Up to Compete in the AI Conversationalist Space Against ChatGPT</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-top-film-previews-unveiled/"><u>[New] Top Film Previews Unveiled</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-mastering-instagram-fcpxs-guide-to-vertical-video-editing/"><u>[Updated] 2024 Approved  Mastering Instagram  FCPX's Guide to Vertical Video Editing</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-how-to-handle-previewed-activities-on-facebook/"><u>[Updated] How to Handle Previewed Activities on Facebook</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-audireview-listening-and-recording-evaluation/"><u>[Updated] In 2024, Audireview  Listening & Recording Evaluation</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-perfect-your-visual-storytelling-inserting-titles-into-photo-videos-on-windows/"><u>[Updated] Perfect Your Visual Storytelling  Inserting Titles Into Photo Videos on Windows</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-from-good-to-great-elevate-your-tiktok-edits/"><u>2024 Approved  From Good to Great  Elevate Your TikTok Edits</u></a></li>
<li><a href="https://tech-haven.techidaily.com/artificial-intelligence-oversight-four-potential-regulatory-avenues/"><u>Artificial Intelligence Oversight: Four Potential Regulatory Avenues</u></a></li>
<li><a href="https://tech-haven.techidaily.com/breakdown-of-artificial-intelligence-lexicon-grasping-29-keywords-you-need/"><u>Breakdown of Artificial Intelligence Lexicon: Grasping 29 Keywords You Need</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/budget-wireless-router-faceoff-tp-link-archer-c9-review-and-comparison/"><u>Budget Wireless Router Faceoff: TP-Link Archer C9 Review & Comparison</u></a></li>
<li><a href="https://tech-haven.techidaily.com/can-interactions-with-users-help-improve-chatgpts-learning-process/"><u>Can Interactions With Users Help Improve ChatGPT's Learning Process?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/comprehensive-tutorial-on-extracting-and-exporting-chatgpt-dialogues/"><u>Comprehensive Tutorial on Extracting & Exporting ChatGPT Dialogues</u></a></li>
<li><a href="https://tech-haven.techidaily.com/deciding-on-an-assistant-in-depth-look-at-claude-and-chatgpt-for-daily-functionality/"><u>Deciding on an Assistant: In-Depth Look at Claude and ChatGPT for Daily Functionality</u></a></li>
<li><a href="https://tech-haven.techidaily.com/digital-dialogue-dynamics-gpt-and-googles-bard-face-off/"><u>Digital Dialogue Dynamics: GPT & Google’s Bard Face-Off</u></a></li>
<li><a href="https://tech-haven.techidaily.com/digital-dialogues-duo-chatgpt-vs-google-bard-showdown/"><u>Digital Dialogues Duo: ChatGPT Vs. Google Bard Showdown</u></a></li>
<li><a href="https://tech-haven.techidaily.com/discover-5-free-ai-tools-to-compose-elite-professional-emails-and-summarize-your-messages-with-chatgpt-effortlessly/"><u>Discover 5 Free AI Tools to Compose Elite Professional Emails & Summarize Your Messages with ChatGPT Effortlessly</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/discover-the-best-7-alarm-clock-apps-you-shouldnt-miss/"><u>Discover the Best 7 Alarm Clock Apps You Shouldn't Miss</u></a></li>
<li><a href="https://tech-haven.techidaily.com/discover-the-best-ai-storyteller-applications-four-options-to-explore/"><u>Discover the Best AI Storyteller Applications: Four Options to Explore</u></a></li>
<li><a href="https://tech-haven.techidaily.com/experts-choice-6-premier-chatgpt-extensions-compatible-with-vs-code/"><u>Experts' Choice: 6 Premier ChatGPT Extensions Compatible with VS Code</u></a></li>
<li><a href="https://tech-haven.techidaily.com/explore-the-fun-side-of-ai-top-6-games-to-try-on-chatgpt/"><u>Explore the Fun Side of AI: Top 6 Games to Try on ChatGPT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/exploring-the-hype-understanding-recent-twitter-fraud-alerts-metas-official-verified-badge-rollout-and-demystifying-chatgpt-4-functionality/"><u>Exploring the Hype: Understanding Recent Twitter Fraud Alerts, Meta's Official Verified Badge Rollout and Demystifying ChatGPT-4 Functionality</u></a></li>
<li><a href="https://tech-haven.techidaily.com/exploring-the-impact-of-chatgpt-and-whisper-api-integration-on-business-opportunities/"><u>Exploring the Impact of ChatGPT and Whisper API Integration on Business Opportunities</u></a></li>
<li><a href="https://tech-haven.techidaily.com/greenhouse-gases-vs-carbon-dioxayer-unveiling-the-truth/"><u>Greenhouse Gases Vs. Carbon Dioxayer, Unveiling the Truth</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-a-quick-dive-into-video-ratios-the-aspect-ratio-essentials-for-youtubers/"><u>In 2024, A Quick Dive Into Video Ratios  The Aspect Ratio Essentials for YouTubers</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-exclusive-insights-3-secrets-to-capture-every-moment-on-discord/"><u>In 2024, Exclusive Insights  3 Secrets to Capture Every Moment on Discord</u></a></li>
<li><a href="https://tech-haven.techidaily.com/incorporating-ai-how-to-maintain-a-daily-meditation-routine-with-chatgpt-assistance/"><u>Incorporating AI: How to Maintain a Daily Meditation Routine with ChatGPT Assistance</u></a></li>
<li><a href="https://tech-haven.techidaily.com/leveraging-chatgpts-capabilities-for-effective-scholarly-inquiry-and-writing/"><u>Leveraging ChatGPT's Capabilities for Effective Scholarly Inquiry and Writing</u></a></li>
<li><a href="https://tech-haven.techidaily.com/local-instance-of-chatgpt-for-windows-using-open-source-gpt-4-alternative/"><u>Local Instance of ChatGPT for Windows Using Open Source GPT-4 Alternative</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-the-interface-your-key-to-conversing-with-top-tier-ai-via-quoras-platform-features-for-chatbots-and-llms/"><u>Mastering the Interface: Your Key to Conversing with Top-Tier AI via Quora's Platform Features for Chatbots & LLMs</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-the-top-6-gpt-car-configuration-challenges-and-solutions/"><u>Mastering the Top 6 GPT Car Configuration Challenges and Solutions</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mitigating-data-disappearance-in-ai-talks/"><u>Mitigating Data Disappearance in AI Talks</u></a></li>
<li><a href="https://tech-haven.techidaily.com/rethink-how-you-research-choose-perplexity-ai/"><u>Rethink How You Research - Choose Perplexity AI</u></a></li>
<li><a href="https://tech-haven.techidaily.com/reviving-lost-conversations-how-to-keep-your-chat-with-gpt-intact/"><u>Reviving Lost Conversations: How to Keep Your Chat with GPT Intact</u></a></li>
<li><a href="https://tech-haven.techidaily.com/revolutionize-your-writing-process-with-these-8-powerful-ai-tools-for-writers/"><u>Revolutionize Your Writing Process with These 8 Powerful AI Tools for Writers</u></a></li>
<li><a href="https://tech-haven.techidaily.com/sam-altman-resigns-as-head-of-openai-a-turning-point-or-a-pivot-for-chatgpt-evolution/"><u>Sam Altman Resigns as Head of OpenAI - A Turning Point or a Pivot for ChatGPT Evolution?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/silence-the-snoops-opt-out-of-gpts-data-harvesting/"><u>Silence the Snoops: Opt-Out of GPT's Data Harvesting</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solve-your-league-of-legends-woes-fixing-the-sluggish-downloads-once-and-for-all/"><u>Solve Your League of Legends Woes: Fixing the Sluggish Downloads Once and For All!</u></a></li>
<li><a href="https://tech-haven.techidaily.com/subscribersilence-yearning-for-chatgpt-reopening/"><u>SubscriberSilence: Yearning for ChatGPT Reopening</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/the-elite-club-of-youtubes-favorite-shorter-videos-for-2024/"><u>The Elite Club of YouTube's Favorite Shorter Videos for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-future-of-business-mastering-these-5-key-ai-technologies/"><u>The Future of Business: Mastering These 5 Key AI Technologies</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-hidden-depth-of-snapchats-myai-learn-about-its-six-unexpected-utilities-beyond-cool-tech/"><u>The Hidden Depth of Snapchat's MyAI - Learn About Its Six Unexpected Utilities Beyond Cool Tech!</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-role-of-chatgpt-in-simplifying-web-design-for-developers/"><u>The Role of ChatGPT in Simplifying Web Design for Developers</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-ultimate-showdown-can-chatgpt-outperform-google-translate-in-high-quality-linguistic-conversions/"><u>The Ultimate Showdown: Can ChatGPT Outperform Google Translate in High-Quality Linguistic Conversions?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-ultimate-walkthrough-for-deploying-the-nvidia-rtx-artificial-intelligence-chat-interface-on-your-computer-system/"><u>The Ultimate Walkthrough for Deploying the Nvidia RTX Artificial Intelligence Chat Interface on Your Computer System</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-8-intelligent-chrome-plugins-that-supercharge-productivity/"><u>Top 8 Intelligent Chrome Plugins That Supercharge Productivity</u></a></li>
<li><a href="https://tech-haven.techidaily.com/ultimate-techniques-for-merging-gpt-with-google-sheets-and-documents/"><u>Ultimate Techniques for Merging GPT with Google Sheets and Documents</u></a></li>
<li><a href="https://tech-haven.techidaily.com/understanding-chatgpt-unlocking-the-potential-of-generative-ai/"><u>Understanding ChatGPT: Unlocking the Potential of Generative AI</u></a></li>
<li><a href="https://tech-haven.techidaily.com/understanding-manners-is-it-necessary-to-address-ai-entities-such-as-chatgpt-alexa-and-siri-politely/"><u>Understanding Manners: Is It Necessary to Address AI Entities Such as ChatGPT, Alexa & Siri Politely?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unlocking-chatgpt-a-step-by-step-guide-to-activating-the-new-beta-features/"><u>Unlocking ChatGPT: A Step-by-Step Guide to Activating the New Beta Features</u></a></li>
</ul></div>
