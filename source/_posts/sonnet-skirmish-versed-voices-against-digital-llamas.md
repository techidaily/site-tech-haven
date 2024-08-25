---
title: Sonnet Skirmish - Versed Voices Against Digital Llamas
date: 2024-08-24T12:56:43.198Z
updated: 2024-08-25T12:56:43.198Z
tags:
  - chatgpt
  - open-ai
categories:
  - openAI
  - chatgpt
description: This Article Describes Sonnet Skirmish - Versed Voices Against Digital Llamas
excerpt: This Article Describes Sonnet Skirmish - Versed Voices Against Digital Llamas
thumbnail: https://thmb.techidaily.com/50da58587d7473ccea973193c5c4bacc32476fa35b560a9912e15b1167ea0299.jpeg
---

## Transform Personal Datasets Into an Intelligent, Customized ChatBot – Learn How

 Providing GPT technology in a powerful and easy-to-use chatbot, ChatGPT has become the world's most popular AI tool. Many people use ChatGPT to provide engaging conversations, answer queries, offer creative suggestions, and aid in coding and writing. However, ChatGPT is limited as you cannot store your data for long-term personal use, and its September 2021 knowledge data cutoff point.

 As a workaround, we can use OpenAI's API and LangChain to provide ChatGPT with custom data and updated info past 2021 to create a custom ChatGPT instance.

## Why Provide ChatGPT with Custom Data?

 Feeding ChatGPT with custom data and providing updated information beyond its knowledge cutoff date provides several benefits over just using ChatGPT as usual. Here are a few of them:

* **Personalized Interactions:** By providing ChatGPT with custom data, users can create a more customized experience. The model can be trained on specific datasets relevant to individual users or organizations, resulting in responses tailored to their unique needs and preferences.
* **Domain-Specific Expertise:** Custom data integration allows ChatGPT to specialize in particular domains or industries. It can be trained on industry-specific knowledge, terminology, and trends, enabling more accurate and insightful responses within those specific areas.
* **Current and Accurate Information:** Access to updated information ensures that ChatGPT stays current with the latest developments and knowledge. It can provide accurate responses based on recent events, news, or research, making it a more reliable source of information.

 Now that you understand the importance of providing custom data to ChatGPT, here's a step-by-step on how to do so on your local computer.

## Step 1: Install and Download Software and Pre-Made Script

 Please note the following instructions are for a Windows 10 or Windows 11 machine.

 To provide custom data to ChatGPT, you'll need to install and download the latest Python3, Git, Microsoft C++, and the ChatGPT-retrieval script from GitHub. If you already have some of the software installed on your PC, make sure they are updated with the latest version to avoid any hiccups during the process.

Start by installing:

* **Download:** [Python3](https://www.python.org/downloads/) (Free)
* **Download:** [Git](https://git-scm.com/downloads) (Free)
* **Download:** [Microsoft Visual Build Tools](https://visualstudio.microsoft.com/visual-cpp-build-tools/) (Free)

### Python3 and Microsoft C++ Installation Notes

 When installing Python3, make sure that you tick the**Add python.exe to PATH** option before clicking**Install Now** . This is important as it allows you to access Python in any directory on your computer.

![Adding Python to PATH](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/1-download-python.jpg)

 When Installing Microsoft C++, you'll want to install**Microsoft Visual Studio Build Tools** first. Once installed, you can tick the**Desktop development with C++** option and click**Install** with all the optional tools automatically ticked on the right sidebar.

![Installing Microsoft C++ through Build Tools](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/2-install-c.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
 Now that you have installed the latest versions of Python3, Git, and Microsoft C++, you can download the Python script to easily query custom local data.

**Download:** [ChatGPT-retrieval script](https://github.com/techleadhd/chatgpt-retrieval) (Free)

 To download the script, click on**Code,** then select**Download ZIP** . This should download the Python script into your default or selected directory.

![Downloading Python script on GitHub](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/3-download-script.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
Once downloaded, we can now set up a local environment.

## Step 2: Set Up the Local Environment

 To set up the environment, you'll need to open a terminal in the chatgpt-retrieval-main folder you downloaded. To do that, open**chatgpt-retrieval-main** folder, right-click, and select**Open in Terminal** .

![Opening terminal on directory folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/4-open-terminal.jpg)

Once the terminal is open, copy and paste this command:

pip install langchain openai chromadb tiktoken unstructured

 This command uses Python's package manager to[create and manage the Python virtual environment](https://www.makeuseof.com/create-manage-python-virtual-environments/) needed.

 After creating the virtual environment, we need to supply an OpenAI API key to access their services. We'll first need to generate an API key from the[OpenAI API keys site](https://platform.openai.com/account/api-keys) by clicking on**Create new secret key** , adding a name for the key, then hitting the**Create secret key button** .

![Creating secret API key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/generate-api-key.jpg)

<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
 You will be provided with a string of characters. This is your OpenAI API key. Copy it by clicking on the copy icon on the side of the API key. Keep note that this API key should be kept secret. Do not share it with others unless you really intend for them to use it with you.

 Once copied, return to the chatgpt-retrieval-main folder and open constants with**Notepad** . Now replace the placeholder with your API key. Remember to save the file!

![Adding API key as environment variable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/add-api-key.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->
 Now that you have successfully set up your virtual environment and added your OpenAI API key as an environment variable. You can now provide your custom data to ChatGPT.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
## Step 3: Adding Custom Data

 To add custom data, place all your custom text data in the**data** folder within chatgpt-retrieval-main. The format of the text data may be in the form of a PDF, TXT, or DOC.

![Adding custom data for ChatGPT](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/adding-data.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
 As you can see from the screenshot above, I've added a text file containing a made-up personal schedule, an article I wrote on[AMD's Instinct Accelerators](https://www.makeuseof.com/what-are-amd-instinct-ai-accelerators/) , and a PDF document.

## Step 4: Querying ChatGPT Through Terminal

 The Python script allows us to query data from the custom data we've added to the data folder and the internet. In other words, you will have access to the usual ChatGPT backend and all the data stored locally in the data folder.

 To use the script, run the python[chatgpt.py](http://chatgpt.py) script and then add your question or query as the argument.

python [chatgpt.py](http://chatgpt.py) "YOUR QUESTION"

Make sure to put your questions in quotation marks.

 To test if we have successfully fed ChatGPT our data, I'll ask a personal question regarding the**Personal Sched.txt** file.

![Testing ChatGPT with custom data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/visit.jpg)

 It worked! This means ChatGPT was able to read the Personal Sched.txt provided earlier. Now let's see if we have successfully fed ChatGPT with information it does not know due to its knowledge cutoff date.

![Asking custom ChatGPT about topic outside knowledge cut off data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/m250x.jpg)

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
 As you can see, it correctly described the AMD Instinct MI250x, which was released after ChatGPT -3's knowledge cutoff date.

## Limitations of Custom ChatGPT

 Although feeding GPT-3.5 with custom data opens more ways to apply and use the LLM, there are a few drawbacks and limitations.

 Firstly, you need to provide all the data yourself. You can still access all the knowledge of GPT-3.5 until its knowledge cutoff date; however, you must provide all the extra data. This means if you want your local model to be knowledgeable of a certain subject on the internet that GPT-3.5 don't already know, you'll have to go to the internet and scrape the data yourself and save it as a text on the data folder of chatgpt-retrieval-main.

 Another issue is that querying ChatGPT like this takes more time to load when compared to asking ChatGPT directly.

 Lastly, the only model currently available is GPT-3.5 Turbo. So even if you have access to GPT-4, you won't be able to use it to power your custom ChatGPT instance.

## Custom ChatGPT Is Awesome But Limited

 Providing custom data to ChatGPT is a powerful way to get more out of the model. Through this method, you can feed the model with any text data you want and prompt it just like regular ChatGPT, albeit with some limitations. However, this will change in the future as it becomes easier to integrate our data with the LLM, along with access to the latest GPT-4 model.


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
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-from-beginner-to-expert-with-a-complete-fcp-guidebook/"><u>[New] 2024 Approved  From Beginner to Expert with a Complete FCP Guidebook</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-instagrams-most-motivational-shots-a-top-20-list/"><u>[New] 2024 Approved  Instagram's Most Motivational Shots  A Top 20 List</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-honing-the-craft-of-question-design-in-interviews/"><u>[New] Honing the Craft of Question Design in Interviews</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-in-2024-innovative-acoustic-link-for-speakers/"><u>[New] In 2024, Innovative Acoustic Link for Speakers</u></a></li>
<li><a href="https://youtube-data.techidaily.com/uick-guide-youtube-soundtracks-to-mp3-for-macos-2shift/"><u>[New] Quick Guide  YouTube Soundtracks to MP3 for MacOS 2Shift</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-when-should-you-share-your-insta-story/"><u>[New] When Should You Share Your Insta Story?</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-2024-approved-color-coding-in-the-digital-world-srgb-vs-rgb/"><u>[Updated] 2024 Approved  Color Coding in the Digital World  Srgb vs Rgb</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-beginners-guide-to-screen-recording-for-dell-computers-for-2024/"><u>[Updated] Beginner's Guide to Screen Recording for Dell Computers for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-prime-action-recorder-with-in-face-view/"><u>[Updated] Prime Action Recorder with In-Face View</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-understanding-picture-in-picture-how-to-use-it-for-youtube/"><u>2024 Approved  Understanding Picture In Picture  How to Use It for YouTube</u></a></li>
<li><a href="https://tech-haven.techidaily.com/best-in-class-bots-chatgpt-or-gemini-for-top-notch-programming-assistance/"><u>Best in Class Bots: ChatGPT or Gemini for Top-Notch Programming Assistance</u></a></li>
<li><a href="https://tech-haven.techidaily.com/bypass-the-limits-deploying-a-free-gpt-companion-chatbot-on-windows-using-freedomgpt/"><u>Bypass the Limits: Deploying a Free GPT Companion Chatbot on Windows Using FreedomGPT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/can-chatgpt-and-bard-safely-steer-your-money-moves/"><u>Can ChatGPT and Bard Safely Steer Your Money Moves?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/case-studies-on-the-reliability-issues-of-ai-detection-systems-including-zerogpt/"><u>Case Studies on the Reliability Issues of AI Detection Systems Including ZeroGPT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/comparing-giants-gemini-and-chatgpt-unite/"><u>Comparing Giants: Gemini and ChatGPT Unite</u></a></li>
<li><a href="https://tech-haven.techidaily.com/corporate-clashes-reimagined-microsoft-blizzard-alliance-and-ai-innovations-audio-show/"><u>Corporate Clashes Reimagined: Microsoft-Blizzard Alliance and AI Innovations [Audio Show]</u></a></li>
<li><a href="https://tech-haven.techidaily.com/documenting-effortlessly-a-guide-to-using-gpt-for-word/"><u>Documenting Effortlessly: A Guide to Using GPT for Word</u></a></li>
<li><a href="https://tech-haven.techidaily.com/efficiently-design-large-scale-content-using-canva-and-gpt-3-integration-techniques/"><u>Efficiently Design Large Scale Content Using Canva & GPT-3 Integration Techniques</u></a></li>
<li><a href="https://tech-haven.techidaily.com/elevate-your-writing-game-go-paperless-with-hix-and-gpt-narratives/"><u>Elevate Your Writing Game - Go Paperless with HIX and GPT-Narratives</u></a></li>
<li><a href="https://tech-haven.techidaily.com/exploiting-chatgpts-link-to-wolframalpha-in-3-ways/"><u>Exploiting ChatGPT's Link to WolframAlpha in 3 Ways</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/fbm-transcripts-how-to-get-and-use-complete-records/"><u>FBM Transcripts  How to Get and Use Complete Records</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/finding-the-perfect-recorders-outside-microsofts-ecosystem-for-2024/"><u>Finding the Perfect Recorders Outside Microsoft's Ecosystem for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/from-novice-to-nimble-harnessing-openais-text-creation-tools/"><u>From Novice to Nimble: Harnessing OpenAI's Text Creation Tools</u></a></li>
<li><a href="https://driver-download.techidaily.com/get-the-most-recent-bluetooth-driver-enhancements-from-microsoft-compatible-with-win-111087/"><u>Get the Most Recent Bluetooth Driver Enhancements From Microsoft - Compatible with Win 11/10/8/7</u></a></li>
<li><a href="https://tech-haven.techidaily.com/gpt-out-securing-your-online-privacy/"><u>GPT Out: Securing Your Online Privacy</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-does-the-stardust-trade-cost-in-pokemon-go-on-poco-x5-drfone-by-drfone-virtual-android/"><u>How does the stardust trade cost In pokemon go On Poco X5? | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-the-chatgpt-ios-application-surpasses-the-website-in-usability-and-features/"><u>How the ChatGPT iOS Application Surpasses the Website in Usability and Features</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-to-embed-codegpt-within-your-visual-studio-code-setup/"><u>How to Embed CodeGPT Within Your Visual Studio Code Setup</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/how-to-safely-dissolve-an-inactive-linkedin-account-for-2024/"><u>How to Safely Dissolve an Inactive LinkedIn Account for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/immediate-entry-into-openais-exclusive-gpt-shop-your-ultimate-guide/"><u>Immediate Entry Into OpenAI's Exclusive GPT Shop: Your Ultimate Guide</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-explore-the-spectrum-of-light-with-windows-hdr-video-capabilities/"><u>In 2024, Explore the Spectrum of Light with Windows' HDR Video Capabilities</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-how-to-enhance-your-page-posts-amidst-facebooks-shift/"><u>In 2024, How to Enhance Your Page Posts Amidst Facebook's Shift</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-after-switching-from-tecno-camon-30-pro-5g-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data After Switching From Tecno Camon 30 Pro 5G to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-3d-print-designs-a-step-by-step-guide-using-chatgpt/"><u>Mastering 3D Print Designs: A Step-by-Step Guide Using ChatGPT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-microsoft-copilot-a-comprehensive-mac-installation-tutorial/"><u>Mastering Microsoft Copilot: A Comprehensive Mac Installation Tutorial</u></a></li>
<li><a href="https://tech-haven.techidaily.com/maximizing-communication-effectiveness-with-chatgpt-by-designing-targeted-user-profiles/"><u>Maximizing Communication Effectiveness with ChatGPT by Designing Targeted User Profiles</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-chatgpt-pitfalls-a-guide-to-correcting-prevalent-issues/"><u>Navigating ChatGPT Pitfalls: A Guide to Correcting Prevalent Issues</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/no-more-glitches-nvidia-and-intel-graphics-on-win10-syncing-flawlessly/"><u>No More Glitches! NVIDIA & Intel Graphics on Win10 Syncing Flawlessly</u></a></li>
<li><a href="https://tech-haven.techidaily.com/quick-tutorial-guide-download-and-install-llama-2-locally/"><u>Quick Tutorial Guide: Download & Install Llama 2 Locally</u></a></li>
<li><a href="https://tech-haven.techidaily.com/revolutionize-your-business-with-these-essential-five-ai-tools/"><u>Revolutionize Your Business With These Essential Five AI Tools</u></a></li>
<li><a href="https://tech-haven.techidaily.com/step-by-step-instructions-downloading-and-setting-up-auto-gpt/"><u>Step by Step Instructions: Downloading and Setting up Auto-GPT</u></a></li>
<li><a href="https://extra-information.techidaily.com/superior-visual-treatment-applying-filters-to-videos/"><u>Superior Visual Treatment  Applying Filters to Videos</u></a></li>
<li><a href="https://tech-haven.techidaily.com/tech-icons-predicting-ais-impact-worldwide/"><u>Tech Icons Predicting AI’s Impact Worldwide</u></a></li>
<li><a href="https://tech-haven.techidaily.com/tired-of-awaiting-chatgpt-desktop-embrace-this-robust-open-source-substitute-now/"><u>Tired of Awaiting ChatGPT Desktop? Embrace This Robust Open-Source Substitute Now!</u></a></li>
<li><a href="https://tech-haven.techidaily.com/transforming-independent-workflow-discover-6-productive-uses-for-chatgpt/"><u>Transforming Independent Workflow: Discover 6 Productive Uses for ChatGPT</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/ultimate-guide-on-xiaomi-redmi-note-12-proplus-5g-frp-bypass-by-drfone-android/"><u>Ultimate Guide on Xiaomi Redmi Note 12 Pro+ 5G FRP Bypass</u></a></li>
<li><a href="https://activate-lock.techidaily.com/unlocking-an-icloud-locked-ipad-and-iphone-xs-by-drfone-ios/"><u>Unlocking an iCloud Locked iPad and iPhone XS</u></a></li>
<li><a href="https://tech-haven.techidaily.com/visual-visionaries-top-30-conceptual-spark-plugs-from-ai-art/"><u>Visual Visionaries: Top 30 Conceptual Spark Plugs From AI Art</u></a></li>
<li><a href="https://tech-haven.techidaily.com/who-reigns-supreme-googles-bard-or-microsofts-bing-chat/"><u>Who Reigns Supreme? Google’s Bard or Microsoft’s Bing Chat</u></a></li>
</ul></div>
