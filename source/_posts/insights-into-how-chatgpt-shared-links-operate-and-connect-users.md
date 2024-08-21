---
title: Insights Into How ChatGPT Shared Links Operate and Connect Users
date: 2024-08-20T12:09:35.284Z
updated: 2024-08-21T12:09:35.284Z
tags:
  - chatgpt
  - open-ai
categories:
  - openAI
  - chatgpt
description: This Article Describes Insights Into How ChatGPT Shared Links Operate and Connect Users
excerpt: This Article Describes Insights Into How ChatGPT Shared Links Operate and Connect Users
thumbnail: https://thmb.techidaily.com/c526ac87f9f87d0fc29a8b589fea98a72d504302296a8e604ba200e55b8a3fda.jpg
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

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->
### Python3 and Microsoft C++ Installation Notes

 When installing Python3, make sure that you tick the**Add python.exe to PATH** option before clicking**Install Now** . This is important as it allows you to access Python in any directory on your computer.

![Adding Python to PATH](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/1-download-python.jpg)

<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 When Installing Microsoft C++, you'll want to install**Microsoft Visual Studio Build Tools** first. Once installed, you can tick the**Desktop development with C++** option and click**Install** with all the optional tools automatically ticked on the right sidebar.

![Installing Microsoft C++ through Build Tools](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/2-install-c.jpg)

 Now that you have installed the latest versions of Python3, Git, and Microsoft C++, you can download the Python script to easily query custom local data.

**Download:** [ChatGPT-retrieval script](https://github.com/techleadhd/chatgpt-retrieval) (Free)

 To download the script, click on**Code,** then select**Download ZIP** . This should download the Python script into your default or selected directory.

![Downloading Python script on GitHub](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/3-download-script.jpg)

Once downloaded, we can now set up a local environment.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## Step 2: Set Up the Local Environment

 To set up the environment, you'll need to open a terminal in the chatgpt-retrieval-main folder you downloaded. To do that, open**chatgpt-retrieval-main** folder, right-click, and select**Open in Terminal** .

![Opening terminal on directory folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/4-open-terminal.jpg)

Once the terminal is open, copy and paste this command:

pip install langchain openai chromadb tiktoken unstructured

 This command uses Python's package manager to[create and manage the Python virtual environment](https://www.makeuseof.com/create-manage-python-virtual-environments/) needed.

 After creating the virtual environment, we need to supply an OpenAI API key to access their services. We'll first need to generate an API key from the[OpenAI API keys site](https://platform.openai.com/account/api-keys) by clicking on**Create new secret key** , adding a name for the key, then hitting the**Create secret key button** .

![Creating secret API key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/generate-api-key.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
 You will be provided with a string of characters. This is your OpenAI API key. Copy it by clicking on the copy icon on the side of the API key. Keep note that this API key should be kept secret. Do not share it with others unless you really intend for them to use it with you.

 Once copied, return to the chatgpt-retrieval-main folder and open constants with**Notepad** . Now replace the placeholder with your API key. Remember to save the file!

![Adding API key as environment variable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/add-api-key.jpg)

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Now that you have successfully set up your virtual environment and added your OpenAI API key as an environment variable. You can now provide your custom data to ChatGPT.

## Step 3: Adding Custom Data

 To add custom data, place all your custom text data in the**data** folder within chatgpt-retrieval-main. The format of the text data may be in the form of a PDF, TXT, or DOC.

![Adding custom data for ChatGPT](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/adding-data.jpg)

 As you can see from the screenshot above, I've added a text file containing a made-up personal schedule, an article I wrote on[AMD's Instinct Accelerators](https://www.makeuseof.com/what-are-amd-instinct-ai-accelerators/) , and a PDF document.

## Step 4: Querying ChatGPT Through Terminal

 The Python script allows us to query data from the custom data we've added to the data folder and the internet. In other words, you will have access to the usual ChatGPT backend and all the data stored locally in the data folder.

 To use the script, run the python[chatgpt.py](http://chatgpt.py) script and then add your question or query as the argument.

python [chatgpt.py](http://chatgpt.py) "YOUR QUESTION"

Make sure to put your questions in quotation marks.

 To test if we have successfully fed ChatGPT our data, I'll ask a personal question regarding the**Personal Sched.txt** file.

![Testing ChatGPT with custom data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/visit.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
 It worked! This means ChatGPT was able to read the Personal Sched.txt provided earlier. Now let's see if we have successfully fed ChatGPT with information it does not know due to its knowledge cutoff date.

![Asking custom ChatGPT about topic outside knowledge cut off data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/m250x.jpg)

 As you can see, it correctly described the AMD Instinct MI250x, which was released after ChatGPT -3's knowledge cutoff date.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->
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
<li><a href="https://digital-screen-recording.techidaily.com/new-from-recordings-to-live-streaming-on-youtube-and-twitch-with-obs/"><u>[New] From Recordings to Live  Streaming on YouTube & Twitch with OBS</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-game-magic-discover-4-ways-to-preserve-your-gaming-sessions-for-2024/"><u>[New] In-Game Magic  Discover 4 Ways to Preserve Your Gaming Sessions for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-obtaining-high-quality-photos-without-restrictions/"><u>[New] Obtaining High-Quality Photos Without Restrictions</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-social-splendor-leading-story-filter-hits/"><u>2024 Approved  Social Splendor  Leading Story Filter Hits</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/a-journey-through-dutch-languages-past/"><u>A Journey Through Dutch Language's Past</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/breakdown-of-profit-earning-potential-from-each-youtube-sponsored-post-in-2024/"><u>Breakdown of Profit  Earning Potential From Each YouTube Sponsored Post, In 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/chatgpt-as-your-personal-resume-guru-strategies-for-crafting-an-impressive-cv-using-ai-technology/"><u>ChatGPT as Your Personal Resume Guru: Strategies for Crafting an Impressive CV Using AI Technology</u></a></li>
<li><a href="https://techidaily.com/complete-guide-to-hard-reset-your-oppo-a56s-5g-drfone-by-drfone-reset-android-reset-android/"><u>Complete Guide to Hard Reset Your Oppo A56s 5G | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/crafting-a-unique-chatbot-experience-utilizing-personal-data-for-your-custom-gpt-creation/"><u>Crafting a Unique Chatbot Experience: Utilizing Personal Data for Your Custom GPT Creation</u></a></li>
<li><a href="https://tech-haven.techidaily.com/cutting-edge-collaboration-how-bz-joins-forces-with-ms-to-revolutionize-game-design-and-ai-language-tech-talk/"><u>Cutting-Edge Collaboration: How BZ Joins Forces with MS to Revolutionize Game Design and AI Language [Tech Talk]</u></a></li>
<li><a href="https://tech-haven.techidaily.com/experience-improvements-with-chatgpt-on-ios-a-comparative-analysis-of-app-vs-web/"><u>Experience Improvements with ChatGPT on iOS: A Comparative Analysis of App Vs. Web</u></a></li>
<li><a href="https://extra-resources.techidaily.com/expert-guide-to-enhance-your-iphone-x-animoji-skills/"><u>Expert Guide to Enhance Your iPhone X Animoji Skills</u></a></li>
<li><a href="https://tech-haven.techidaily.com/exploring-workplace-consequences-is-it-safe-to-use-chatgpt-on-company-time/"><u>Exploring Workplace Consequences: Is It Safe to Use ChatGPT on Company Time?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/gptzero-decoded-pinpointing-non-human-text-creators/"><u>GPTZero Decoded: Pinpointing Non-Human Text Creators</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-leave-a-life360-group-on-apple-iphone-6-without-anyone-knowing-drfone-by-drfone-virtual-ios/"><u>How To Leave a Life360 Group On Apple iPhone 6 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-move-contacts-from-honor-70-lite-5g-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Move Contacts From Honor 70 Lite 5G to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-oppo-reno-8t-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Oppo Reno 8T</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-10-best-spy-watches-for-your-realme-c67-4g-drfone-by-drfone-virtual-android/"><u>In 2024, Top 10 Best Spy Watches For your Realme C67 4G | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/inside-chatgpt-jailbreaking-is-it-worth-the-risks/"><u>Inside ChatGPT Jailbreaking: Is It Worth The Risks?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/is-chatgpt-the-key-to-wilderness-safety-and-rescue-techniques/"><u>Is ChatGPT The Key To Wilderness Safety And Rescue Techniques?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/is-it-possible-for-chatgpt-to-tackle-mathematical-queries-effectively/"><u>Is It Possible for ChatGPT to Tackle Mathematical Queries Effectively?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/is-your-needs-met-by-going-local-with-llms/"><u>Is Your Needs Met by Going Local with LLMs?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/le-chat-vs-chatgpt-an-in-depth-review-by-our-team-at-mistral-ai/"><u>Le Chat Vs. ChatGPT: An In-Depth Review by Our Team at Mistral AI</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-the-new-era-of-internet-browsing-understanding-the-role-of-intelligent-algorithms-in-enhancing-site-ranking/"><u>Navigating the New Era of Internet Browsing: Understanding the Role of Intelligent Algorithms in Enhancing Site Ranking</u></a></li>
<li><a href="https://tech-haven.techidaily.com/pseudo-ai-plugin-purloins-facebook-details/"><u>Pseudo-AI Plugin: Purloins FACEBOOK Details</u></a></li>
<li><a href="https://tech-haven.techidaily.com/pursue-profits-and-purpose-through-software-error-discovery-at-openai/"><u>Pursue Profits and Purpose Through Software Error Discovery at OpenAI</u></a></li>
<li><a href="https://tech-haven.techidaily.com/stay-ahead-with-chatgpt-learn-about-their-freshly-introduced-innovative-tools-and-capabilities/"><u>Stay Ahead with ChatGPT – Learn About Their Freshly Introduced Innovative Tools and Capabilities</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-enigma-of-ai-jargon-deciphering-29-crucial-phrases/"><u>The Enigma of AI Jargon: Deciphering 29 Crucial Phrases</u></a></li>
<li><a href="https://buynow-help.techidaily.com/the-hidden-costs-of-buying-a-tv-recorder-without-research/"><u>The Hidden Costs of Buying a TV Recorder Without Research</u></a></li>
<li><a href="https://tech-haven.techidaily.com/1722845817114-the-user-friendly-way-to-hide-subtitles-during-an-amazon-video-binge-session/"><u>The User-Friendly Way to Hide Subtitles During an Amazon Video Binge Session</u></a></li>
<li><a href="https://tech-haven.techidaily.com/timing-talk-how-chatgpt-4-measures-up-to-35/"><u>Timing Talk: How ChatGPT-4 Measures Up to 3.5</u></a></li>
<li><a href="https://tech-haven.techidaily.com/transform-your-android-into-an-intelligent-companion-the-ultimate-guide-to-enabling-voice-operated-chatgpt-via-voicegpt-app/"><u>Transform Your Android Into an Intelligent Companion: The Ultimate Guide to Enabling Voice-Operated ChatGPT via VoiceGPT App</u></a></li>
<li><a href="https://tech-haven.techidaily.com/transform-your-kitchen-habits-cooking-tips-from-chatgpt-for-wholesome-foods/"><u>Transform Your Kitchen Habits: Cooking Tips From ChatGPT for Wholesome Foods</u></a></li>
<li><a href="https://tech-haven.techidaily.com/troubleshooting-chatgpt-top-9-solutions-when-it-fails-on-iphone/"><u>Troubleshooting ChatGPT: Top 9 Solutions When It Fails On iPhone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/understanding-the-bert-nlp-model-key-features-and-distinctions-from-gpt/"><u>Understanding the BERT NLP Model: Key Features and Distinctions From GPT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/understanding-the-impact-of-generative-ai-on-modern-misinformation-tactics/"><u>Understanding the Impact of Generative AI on Modern Misinformation Tactics</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unleashing-the-potential-of-ai-for-better-workflow-chatgpt-meets-onlyoffice-docspace/"><u>Unleashing the Potential of AI for Better Workflow: ChatGPT Meets ONLYOFFICE DocSpace</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unveiling-the-limits-of-ai-detection-technology-with-four-illustrative-examples/"><u>Unveiling the Limits of AI Detection Technology with Four Illustrative Examples</u></a></li>
<li><a href="https://tech-haven.techidaily.com/warning-signals-alert-no-official-chatgpt-windows-version-avoid-malware-disguised-as-a-client/"><u>Warning Signals Alert! No Official ChatGPT Windows Version, Avoid Malware Disguised as a Client</u></a></li>
<li><a href="https://tech-haven.techidaily.com/windows-users-guide-to-running-free-chatgpt-clones-without-limitations-using-freedomgpt/"><u>Windows Users Guide to Running FREE ChatGPT Clones Without Limitations Using FreedomGPT</u></a></li>
</ul></div>
