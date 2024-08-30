---
title: "Simplifying Windows CMD: A Step-by-Step Guide to Modifying the PATH Environment Variable"
date: 2024-08-29T02:13:53.774Z
updated: 2024-08-30T02:13:53.774Z
tags:
  - deals
categories:
  - tech
thumbnail: https://thmb.techidaily.com/2a75585c706bda1c98b7ca78005e810cc4fa04565ec0bfaa1522a3466ddc9fcb.jpg
---

## Simplifying Windows CMD: A Step-by-Step Guide to Modifying the PATH Environment Variable

### Quick Links

* [What Is the Windows System PATH?](https://facebook-record-videos.techidaily.com/updated-harmonizing-youtube-content-a-guide-to-blending-files/)
* [How to Add a Folder to Your PATH](https://fox-cloud.techidaily.com/new-quirky-creations-your-guide-to-no-cost-memes/)

### Key Takeaways

 The PATH tells Windows where it should look for executables, making them accessible via command-line interfaces or scripts. To add a new folder to PATH, navigate to Advanced System Settings > Environment Variables, select PATH, click "Edit" and then "New."

 Have you ever wondered why you can just type ipconfig into a command prompt and it works, but when you want to use a command line program you downloaded you have to navigate to its directory first? Here's how to fix that using the Windows System PATH on Windows 10 and Windows 11.

##  What Is the Windows System PATH?

 The Windows System PATH tells your PC where it can find specific directories that contain executable files. Ipconfig.exe, for example, is found in the C:\\Windows\\System32 directory, which is a part of the system PATH by default. When you type ipconfig into a Command Prompt, Windows doesn't need to know where that EXE is—it'll check all the folders in its PATH until it finds the right one.

 If you've downloaded a program that uses a command-line interface—like ADB, the [Android Debug Bridge](https://techtrends.techidaily.com/how-to-successfully-obtain-a-refund-for-your-purchased-games-on-steam/)—you can't just type adb in the Command Prompt or PowerShell to run it, like you can with Windows' built-in commands (e.g.ipconfig). Instead, you have to tell Command Prompt where to find that file, by typing in the full path of the EXE:

C:\Android\platform-tools\adb.exe

 If you don't, you'll get an error message like this.

![ADB is not recognized since it is not on the system PATH.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/adb-error.png) 

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->
 That's a lot of typing, especially for something you have to run often.

 If you want the same convenience with a program you downloaded (like ADB), you need to add its folder to Windows' system PATH. That way, when you need to run adb, you can just run:

adb

 No extra typing necessary.

<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  How to Add a Folder to Your PATH

 These steps are basically the same on Windows 10 and Windows 11\. There are just some minor differences in the user interface.

 Start by pressing the Windows key to open up the Start Menu, then search for "advanced system settings." You can alternatively browse through Control Panel to System and Security > System and click on the "Advanced system settings" hyperlink in the left-hand pane.

![Search for and open "Advanced System Settings."](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/advanced-system.png) 

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Once the System Properties window opens, click on the "Environment Variables" button.

![Click &quot;Environment Variables.&quot;](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/environmental-variables.png) 

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
 In the "System Variables" box, look for a variable called _Path._ Select that and click on the "Edit" button.

 You can modify the PATH for only the current user by changing the PATH variable under "User Variables." It won't affect other users, however. In many cases, it is better and more convenient to add something to the system PATH, so it is universally accessible on your PC.

![Select &quot;PATH&quot; under &quot;System Variables,&quot; then click &quot;Edit.&quot;](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/system-variables.png) 

 This process is both easier and less confusing in Windows 10 and Windows 11 than it was in earlier versions of Windows. Once you've clicked the edit button, a new dialog box will appear with each location in the PATH on a separate line. This is a dramatic improvement over the way previous versions of Windows handled PATH locations and makes easy work of adding a new one.

![The current PATH.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/PATH-Stuff.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->
 First, click the 'new' button, which will add a line at the end of the list. Add your location—"C:\\AndroidSDK" in our example—and hit Enter. Click the "OK" button and you're finished.

 Older versions of Windows required each line end with a semi-colon, but Windows 10 and 11 do not if you use the user interface like we are here. If you use a command-line interface to edit the PATH, you'll still find them there.

![Click &quot;New,&quot; enter the path to ADB, then click &quot;OK.&quot;](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/android-SD.png) 

 The Android Debugging Bridge should now be accessible from any Command Prompt, PowerShell, or Windows Terminal, with no need to specify its directory.

![ADB now works in PowerShell without specifying the path manually.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/adb-on-path.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
<!-- affiliate ads end -->
 You can add as many locations as you like to PATH. However, convention and best practice dictate that you try to avoid cluttering up your PATH with unnecessary executables.

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
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-perfecting-obs-broadcasts-for-facebook-audience/"><u>[New] 2024 Approved  Perfecting OBS Broadcasts for Facebook Audience</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-mobile-editing-hacks-writing-on-photos/"><u>[New] Mobile Editing Hacks  Writing on Photos</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-privacy-preserving-recordings-methods-to-shield-sensitive-data-for-2024/"><u>[New] Privacy-Preserving Recordings  Methods to Shield Sensitive Data for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-pro-chromebook-record-unmatched-screen-capture-for-2024/"><u>[New] Pro Chromebook Record  Unmatched Screen Capture for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-streamline-your-virtual-sessions-with-these-top-10-tools/"><u>[Updated] 2024 Approved  Streamline Your Virtual Sessions with These Top 10 Tools</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-gratuitous-screen-snap-for-macos-for-2024/"><u>[Updated] Gratuitous Screen Snap for MacOS for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-streamline-and-shine-the-top-5-video-quality-tools/"><u>2024 Approved  Streamline & Shine  The Top 5 Video Quality Tools</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/2024s-ultimate-list-of-advanced-fitness-tracking-gadgets/"><u>2024'S Ultimate List of Advanced Fitness Tracking Gadgets</u></a></li>
<li><a href="https://tech-haven.techidaily.com/avoiding-unintended-exposures-with-chatgpts-adaptive-gpt-systems-tips-for-better-protection/"><u>Avoiding Unintended Exposures with ChatGPT's Adaptive GPT Systems: Tips for Better Protection</u></a></li>
<li><a href="https://tech-haven.techidaily.com/behind-the-screen-the-dead-internet-theory-revealed-for-online-communication-insights/"><u>Behind the Screen: The Dead Internet Theory Revealed for Online Communication Insights</u></a></li>
<li><a href="https://tech-haven.techidaily.com/beyond-impressive-the-4-distinct-advantages-of-using-claude-ai-instead-of-chatgpt/"><u>Beyond Impressive: The 4 Distinct Advantages of Using Claude AI Instead of ChatGPT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/can-machines-pass-the-turing-test-exploring-possibilities-and-challenges/"><u>Can Machines Pass the Turing Test? Exploring Possibilities and Challenges</u></a></li>
<li><a href="https://tech-haven.techidaily.com/chatgpt-a-tool-for-banks-vulnerabilities/"><u>ChatGPT: A Tool for Banks' Vulnerabilities?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/comparing-giants-in-ai-chatbots-google-bard-versus-bing-chat/"><u>Comparing Giants in AI Chatbots: Google Bard Versus Bing Chat</u></a></li>
<li><a href="https://tech-haven.techidaily.com/crafting-engaging-presentations-using-chatgpts-powerful-tools/"><u>Crafting Engaging Presentations Using ChatGPT's Powerful Tools</u></a></li>
<li><a href="https://tech-haven.techidaily.com/delving-into-prompt-engineering-job-opportunities-9-crucial-elements-for-your-decision/"><u>Delving Into Prompt Engineering Job Opportunities - 9 Crucial Elements for Your Decision</u></a></li>
<li><a href="https://tech-haven.techidaily.com/distinguishing-between-powerful-ai-and-basic-ai-technologies/"><u>Distinguishing Between Powerful AI and Basic AI Technologies</u></a></li>
<li><a href="https://tech-haven.techidaily.com/enhance-your-document-workflow-with-these-10-must-have-chatgpt-pdf-tools/"><u>Enhance Your Document Workflow with These 10 Must-Have ChatGPT PDF Tools</u></a></li>
<li><a href="https://tech-haven.techidaily.com/enhancing-excel-experience-3-powerful-chatgpt-applications/"><u>Enhancing Excel Experience: 3 Powerful ChatGPT Applications</u></a></li>
<li><a href="https://tech-haven.techidaily.com/evaluating-the-dangers-of-seeking-medical-insights-from-chatgpt/"><u>Evaluating the Dangers of Seeking Medical Insights From ChatGPT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/exploring-the-creation-process-of-chatgpts-text-is-there-any-risk-of-plagiarism/"><u>Exploring the Creation Process of ChatGPT's Text: Is There Any Risk of Plagiarism?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/gptbot-overview-and-the-rationale-for-its-restriction-on-websites/"><u>GPTBot Overview & The Rationale for Its Restriction on Websites</u></a></li>
<li><a href="https://win-answers.techidaily.com/house-flipper-sstem-how-to-prevent-the-game-from-crashing-while-playing-on-a-desktop/"><u>House Flipper ˈsɪstem: How to Prevent the Game From Crashing While Playing on a Desktop</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-fix-oem-unlock-missing-on-vivo-x-fold-2-by-drfone-android/"><u>How To Fix OEM Unlock Missing on Vivo X Fold 2?</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721103580978-i-am-also-known-as-a/"><u>I Am Also Known as A:</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-5-easy-ways-to-change-location-on-youtube-tv-on-vivo-y27s-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Easy Ways to Change Location on YouTube TV On Vivo Y27s | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-best-8-mirrorless-cameras-to-elevate-your-vlogging-game/"><u>In 2024, Best 8 Mirrorless Cameras to Elevate Your Vlogging Game</u></a></li>
<li><a href="https://tech-haven.techidaily.com/introduce-a-cost-free-localized-chatbot-ai-on-pc/"><u>Introduce a Cost-Free Localized Chatbot AI on PC</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-the-art-of-integrating-gpt-references-enhancing-conversations-with-personalized-ai/"><u>Mastering the Art of Integrating GPT References: Enhancing Conversations with Personalized AI</u></a></li>
<li><a href="https://extra-resources.techidaily.com/mirrorless-4k-cameras-top-10-list-unveiled/"><u>Mirrorless 4K Cameras  Top 10 List Unveiled</u></a></li>
<li><a href="https://fox-that.techidaily.com/1721470583289-no-audio-on-your-apple-device-heres-what-you-can-do/"><u>No Audio on Your Apple Device? Here’s What You Can Do!</u></a></li>
<li><a href="https://tech-haven.techidaily.com/protect-yourself-from-ai-phishing-attempts-tips-on-recognizing-suspicious-chatgpt-websites-and-action-plans/"><u>Protect Yourself From AI Phishing Attempts: Tips on Recognizing Suspicious ChatGPT Websites and Action Plans</u></a></li>
<li><a href="https://fix-guide.techidaily.com/proven-ways-in-how-to-hide-location-on-life360-for-tecno-spark-10-5g-drfone-by-drfone-virtual-android/"><u>Proven Ways in How To Hide Location on Life360 For Tecno Spark 10 5G | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/recognizing-artificial-intelligence-illusions-identifying-and-understanding-ai-hallucinations/"><u>Recognizing Artificial Intelligence Illusions: Identifying & Understanding AI 'Hallucinations'</u></a></li>
<li><a href="https://tech-haven.techidaily.com/step-by-step-tutorial-accessing-plugin-support-and-web-browsing-on-chatgpt-beta-version/"><u>Step-by-Step Tutorial: Accessing Plugin Support and Web Browsing on ChatGPT Beta Version</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-art-of-balancing-human-creativity-and-ai-assistance-in-writing/"><u>The Art of Balancing Human Creativity and AI Assistance in Writing</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-enigmatic-eye-slick-camera-tech/"><u>The Enigmatic Eye  Slick Camera Tech</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-latest-on-chatgpt-is-it-running/"><u>The Latest on ChatGPT: Is It Running?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-ultimate-collection-of-7-key-online-utilities-to-refine-your-prompt-construction-techniques/"><u>The Ultimate Collection of 7 Key Online Utilities to Refine Your Prompt Construction Techniques</u></a></li>
<li><a href="https://tech-haven.techidaily.com/threatened-by-gpts-content-generation/"><u>Threatened by GPT's Content Generation?</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/top-10-inspirational-hr-journeys-unveiled-for-2024/"><u>Top 10 Inspirational HR Journeys Unveiled for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/top-4-android-system-repair-software-for-realme-11x-5g-bricked-devices-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 4 Android System Repair Software for Realme 11X 5G Bricked Devices | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/total-gigabytes-for-an-entirety-of-daily-films/"><u>Total Gigabytes for an Entirety of Daily Films</u></a></li>
<li><a href="https://tech-haven.techidaily.com/transforming-employment-7-predictions-on-how-generative-ai-shapes-our-future-work/"><u>Transforming Employment: 7 Predictions on How Generative AI Shapes Our Future Work</u></a></li>
<li><a href="https://tech-haven.techidaily.com/transforming-the-internet-the-impact-of-ai-on-future-search-engine-results/"><u>Transforming the Internet: The Impact of AI on Future Search Engine Results</u></a></li>
<li><a href="https://tech-haven.techidaily.com/understanding-artificei-intelligence-a-beginners-guide/"><u>Understanding ArtificeI Intelligence: A Beginner's Guide</u></a></li>
<li><a href="https://tech-haven.techidaily.com/understanding-turings-challenge-is-it-unbeatable/"><u>Understanding Turing's Challenge: Is It Unbeatable?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unraveling-the-distinctions-between-gpt-and-bert-in-natural-language-processing/"><u>Unraveling the Distinctions Between GPT and BERT in Natural Language Processing</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-is-geo-blocking-and-how-to-bypass-it-on-samsung-galaxy-xcover-7-drfone-by-drfone-virtual-android/"><u>What is Geo-Blocking and How to Bypass it On Samsung Galaxy XCover 7? | Dr.fone</u></a></li>
<li><a href="https://youtube-data.techidaily.com/bes-evergreen-most-watched-video-catalog-for-2024/"><u>YouTube's Evergreen Most-Watched Video Catalog for 2024</u></a></li>
</ul></div>
