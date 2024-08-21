---
title: "Strategic Health Planning: Leveraging ChatGPT for Personalized Wellbeing Targets"
date: 2024-08-20T12:07:15.913Z
updated: 2024-08-21T12:07:15.913Z
tags:
  - chatgpt
  - open-ai
categories:
  - openAI
  - chatgpt
description: "This Article Describes Strategic Health Planning: Leveraging ChatGPT for Personalized Wellbeing Targets"
excerpt: "This Article Describes Strategic Health Planning: Leveraging ChatGPT for Personalized Wellbeing Targets"
thumbnail: https://thmb.techidaily.com/769d83492280fd0660acd0112190d1d990d0e4305860168c39e79719f29b2ea7.jpg
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
 When Installing Microsoft C++, you'll want to install**Microsoft Visual Studio Build Tools** first. Once installed, you can tick the**Desktop development with C++** option and click**Install** with all the optional tools automatically ticked on the right sidebar.

![Installing Microsoft C++ through Build Tools](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/2-install-c.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
 Now that you have installed the latest versions of Python3, Git, and Microsoft C++, you can download the Python script to easily query custom local data.

**Download:** [ChatGPT-retrieval script](https://github.com/techleadhd/chatgpt-retrieval) (Free)

 To download the script, click on**Code,** then select**Download ZIP** . This should download the Python script into your default or selected directory.

![Downloading Python script on GitHub](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/3-download-script.jpg)

Once downloaded, we can now set up a local environment.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You will be provided with a string of characters. This is your OpenAI API key. Copy it by clicking on the copy icon on the side of the API key. Keep note that this API key should be kept secret. Do not share it with others unless you really intend for them to use it with you.

 Once copied, return to the chatgpt-retrieval-main folder and open constants with**Notepad** . Now replace the placeholder with your API key. Remember to save the file!

![Adding API key as environment variable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/add-api-key.jpg)

 Now that you have successfully set up your virtual environment and added your OpenAI API key as an environment variable. You can now provide your custom data to ChatGPT.

## Step 3: Adding Custom Data

 To add custom data, place all your custom text data in the**data** folder within chatgpt-retrieval-main. The format of the text data may be in the form of a PDF, TXT, or DOC.

![Adding custom data for ChatGPT](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/adding-data.jpg)

<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
 As you can see, it correctly described the AMD Instinct MI250x, which was released after ChatGPT -3's knowledge cutoff date.

<!-- affiliate ads begin -->
<a href="https://uperfect.sjv.io/c/5597632/1246754/15155" target="_top" id="1246754"><img src="//a.impactradius-go.com/display-ad/15155-1246754" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1246754/15155" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-video-files.techidaily.com/new-elevate-your-igtv-presence-with-edited-titles-and-descriptions-for-2024/"><u>[New] Elevate Your IGTV Presence with Edited Titles and Descriptions for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-in-2024-how-luts-revolutionize-your-photo-editing-experience/"><u>[New] In 2024, How LUTs Revolutionize Your Photo Editing Experience</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-preserve-tweets-as-visual-delights-with-iosandroid-steps/"><u>[New] In 2024, Preserve Tweets as Visual Delights with iOS/Android Steps</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-innovative-approaches-to-integrating-your-fb-story/"><u>[New] Innovative Approaches to Integrating Your FB Story</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-mastering-video-metrics-the-role-of-thumbnail-size/"><u>[New] Mastering Video Metrics  The Role of Thumbnail Size</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-2024-approved-the-zen-of-broadcasting-perfecting-zooms-techniques-for-youtube/"><u>[Updated] 2024 Approved  The Zen of Broadcasting  Perfecting Zoom's Techniques for YouTube</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-can-i-peruse-friends-shared-videos-and-pics-via-messenger/"><u>[Updated] Can I Peruse Friends' Shared Videos & Pics via Messenger?</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-free-photo-editing-tricks-unveiling-iphones-hidden-features-for-2024/"><u>[Updated] Free Photo Editing Tricks  Unveiling iPhone's Hidden Features for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-ultimate-training-harnessing-the-power-of-adobe-captivates-screen-record-feature/"><u>[Updated] Ultimate Training  Harnessing the Power of Adobe Captivate's Screen Record Feature</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-understanding-and-adhering-to-soundtracks-legal-requirements-on-instagram/"><u>[Updated] Understanding and Adhering to Soundtracks' Legal Requirements on Instagram</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-androids-secret-weapon-for-stunning-time-lagged-footage/"><u>2024 Approved  Android's Secret Weapon for Stunning Time-Lagged Footage</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/approved-crafting-the-perfect-binge-worthy-mukbang-experience/"><u>2024 Approved  Crafting the Perfect Binge-Worthy Mukbang Experience</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-how-to-add-videos-in-instagram-story/"><u>2024 Approved  How to Add Videos in Instagram Story</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-premium-audio-narrative-compositions/"><u>2024 Approved  Premium Audio Narrative Compositions</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-snapchats-highlight-an-in-depth-look/"><u>2024 Approved  Snapchat's Highlight  An In-Depth Look</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-the-essential-guide-to-blurring-video-borders-in-teams/"><u>2024 Approved  The Essential Guide to Blurring Video Borders in Teams</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/2024-approved-youtubers-unite-with-these-17-top-tier-lights/"><u>2024 Approved  Youtubers Unite with These 17 Top-Tier Lights</u></a></li>
<li><a href="https://android-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-lava-yuva-2-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Lava Yuva 2</u></a></li>
<li><a href="https://tech-haven.techidaily.com/beating-stress-effective-techniques-using-chatgpt/"><u>Beating Stress: Effective Techniques Using ChatGPT</u></a></li>
<li><a href="https://tech-hub.techidaily.com/boost-your-companys-efficiency-discover-8-ways-to-utilize-chatgpt/"><u>Boost Your Company's Efficiency: Discover 8 Ways to Utilize ChatGPT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/breaking-down-auto-gpt-its-unique-characteristics-over-chatgpt/"><u>Breaking Down Auto-GPT: Its Unique Characteristics Over ChatGPT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/dall-e-3-now-has-integrated-editing-tools-but-they-need-work/"><u>DALL-E 3 Now Has Integrated Editing Tools, But They Need Work</u></a></li>
<li><a href="https://tech-haven.techidaily.com/demystifying-langchain-llm-your-first-steps-as-a-starters-handbook/"><u>Demystifying LangChain LLM: Your First Steps as a Starter's Handbook</u></a></li>
<li><a href="https://tech-haven.techidaily.com/discovering-huggingchat-an-in-depth-look-at-the-open-source-competitor-of-chatgpt/"><u>Discovering HuggingChat: An In-Depth Look at the Open Source Competitor of ChatGPT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/effective-chatgpt-strategies-steering-clear-of-4-major-missteps-for-quality-output/"><u>Effective ChatGPT Strategies: Steering Clear of 4 Major Missteps for Quality Output</u></a></li>
<li><a href="https://tech-haven.techidaily.com/elevating-language-models-the-top-4-improvements-were-eager-for-gpt-n/"><u>Elevating Language Models: The Top 4 Improvements We're Eager For GPT-N</u></a></li>
<li><a href="https://tech-haven.techidaily.com/elevating-team-efficiency-by-integrating-chatgpt-into-your-workflow-strategy-plan/"><u>Elevating Team Efficiency by Integrating ChatGPT Into Your Workflow Strategy Plan</u></a></li>
<li><a href="https://tech-haven.techidaily.com/guard-against-data-thieves-with-ai-literacy-and-caution/"><u>Guard Against Data Thieves with AI Literacy and Caution</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-does-codegpt-work-and-is-it-truly-efficient-at-programming/"><u>How Does CodeGPT Work, And Is It Truly Efficient At Programming?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/human-creativity-in-writing-unmatched-by-algorithms/"><u>Human Creativity in Writing Unmatched by Algorithms</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-can-i-bypass-a-forgotten-phone-password-of-infinix-note-30-vip-racing-edition-by-drfone-android/"><u>In 2024, Can I Bypass a Forgotten Phone Password Of Infinix Note 30 VIP Racing Edition?</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-expert-tips-for-seamless-photo-and-video-import-in-windows-10/"><u>In 2024, Expert Tips for Seamless Photo and Video Import in Windows 10</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-delete-icloud-account-from-iphone-6-plus-without-password-by-drfone-ios/"><u>In 2024, How to Delete iCloud Account From iPhone 6 Plus without Password?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-the-art-of-resilient-chatgpt-sign-in/"><u>Mastering the Art of Resilient ChatGPT Sign-In</u></a></li>
<li><a href="https://tech-haven.techidaily.com/microsofts-ai-revolution-discover-8-compelling-ways-to-implement-vision-driven-conversational-agents/"><u>Microsoft's AI Revolution: Discover 8 Compelling Ways to Implement Vision-Driven Conversational Agents</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-ai-conversations-your-guide-to-the-finest-non-chatgpt-options/"><u>Navigating AI Conversations: Your Guide to the Finest Non-ChatGPT Options</u></a></li>
<li><a href="https://screen-capture.techidaily.com/nine-superior-tools-to-freeze-dynamic-windows-gifs-flawlessly-for-2024/"><u>Nine Superior Tools to Freeze Dynamic Windows GIFs Flawlessly for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/python-programming-with-gpt-3-tips-and-tricks-for-seamless-implementation/"><u>Python Programming with GPT-3: Tips and Tricks for Seamless Implementation</u></a></li>
<li><a href="https://techtrends.techidaily.com/quick-and-easy-guide-how-to-update-your-windows-10-drivers/"><u>Quick & Easy Guide: How to Update Your Windows 10 Drivers</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-10-best-alternatives-to-chatgpt/"><u>The 10 Best Alternatives to ChatGPT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-ultimate-crypto-warning-signs-for-bingchat-token-schemes/"><u>The Ultimate Crypto Warning Signs for BingChat Token Schemes</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-ultimate-walkthrough-for-activating-and-using-chatgpt-on-android-phones/"><u>The Ultimate Walkthrough for Activating and Using ChatGPT on Android Phones</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-5-causes-behind-corporations-prohibiting-chatgpt-use/"><u>Top 5 Causes Behind Corporations Prohibiting ChatGPT Use</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-7-tools-beyond-chatgpt-for-auto-coding-solutions/"><u>Top 7 Tools Beyond ChatGPT for Auto-Coding Solutions</u></a></li>
<li><a href="https://tech-haven.techidaily.com/understanding-grok-ai-inside-look-at-elon-musks-new-creation-its-functionality-and-associated-costs/"><u>Understanding Grok AI: Inside Look at Elon Musk's New Creation, Its Functionality & Associated Costs</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unleash-the-power-of-conversation-your-guide-to-operating-nvidias-rtx-ai-on-a-personal-computer/"><u>Unleash the Power of Conversation: Your Guide to Operating Nvidia's RTX AI on a Personal Computer</u></a></li>
<li><a href="https://tech-haven.techidaily.com/voice-command-mastery-controlling-chatgpt-the-easy-way/"><u>Voice Command Mastery: Controlling ChatGPT the Easy Way</u></a></li>
<li><a href="https://tech-haven.techidaily.com/what-is-huggingchat-your-affordable-and-transparent-alternative-to-chatgpt-unveiled/"><u>What Is HuggingChat? Your Affordable and Transparent Alternative to ChatGPT Unveiled</u></a></li>
</ul></div>
