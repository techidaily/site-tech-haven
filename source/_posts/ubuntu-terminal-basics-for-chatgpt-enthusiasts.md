---
title: Ubuntu Terminal Basics for ChatGPT Enthusiasts
date: 2024-08-24T12:47:37.758Z
updated: 2024-08-25T12:47:37.758Z
tags:
  - chatgpt
  - open-ai
categories:
  - openAI
  - chatgpt
description: This Article Describes Ubuntu Terminal Basics for ChatGPT Enthusiasts
excerpt: This Article Describes Ubuntu Terminal Basics for ChatGPT Enthusiasts
thumbnail: https://thmb.techidaily.com/e95b10a90432b136a95f53788d2f6a34587f22e1538a737ba31a5504b6070516.jpg
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
 Now that you have installed the latest versions of Python3, Git, and Microsoft C++, you can download the Python script to easily query custom local data.

**Download:** [ChatGPT-retrieval script](https://github.com/techleadhd/chatgpt-retrieval) (Free)

 To download the script, click on**Code,** then select**Download ZIP** . This should download the Python script into your default or selected directory.

![Downloading Python script on GitHub](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/3-download-script.jpg)

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
Once downloaded, we can now set up a local environment.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
## Step 2: Set Up the Local Environment

 To set up the environment, you'll need to open a terminal in the chatgpt-retrieval-main folder you downloaded. To do that, open**chatgpt-retrieval-main** folder, right-click, and select**Open in Terminal** .

![Opening terminal on directory folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/4-open-terminal.jpg)

<!-- affiliate ads begin -->
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
Once the terminal is open, copy and paste this command:

pip install langchain openai chromadb tiktoken unstructured

 This command uses Python's package manager to[create and manage the Python virtual environment](https://www.makeuseof.com/create-manage-python-virtual-environments/) needed.

 After creating the virtual environment, we need to supply an OpenAI API key to access their services. We'll first need to generate an API key from the[OpenAI API keys site](https://platform.openai.com/account/api-keys) by clicking on**Create new secret key** , adding a name for the key, then hitting the**Create secret key button** .

![Creating secret API key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/generate-api-key.jpg)

 You will be provided with a string of characters. This is your OpenAI API key. Copy it by clicking on the copy icon on the side of the API key. Keep note that this API key should be kept secret. Do not share it with others unless you really intend for them to use it with you.

 Once copied, return to the chatgpt-retrieval-main folder and open constants with**Notepad** . Now replace the placeholder with your API key. Remember to save the file!

![Adding API key as environment variable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/add-api-key.jpg)

 Now that you have successfully set up your virtual environment and added your OpenAI API key as an environment variable. You can now provide your custom data to ChatGPT.

## Step 3: Adding Custom Data

 To add custom data, place all your custom text data in the**data** folder within chatgpt-retrieval-main. The format of the text data may be in the form of a PDF, TXT, or DOC.

![Adding custom data for ChatGPT](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/adding-data.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
 As you can see, it correctly described the AMD Instinct MI250x, which was released after ChatGPT -3's knowledge cutoff date.

## Limitations of Custom ChatGPT

 Although feeding GPT-3.5 with custom data opens more ways to apply and use the LLM, there are a few drawbacks and limitations.

 Firstly, you need to provide all the data yourself. You can still access all the knowledge of GPT-3.5 until its knowledge cutoff date; however, you must provide all the extra data. This means if you want your local model to be knowledgeable of a certain subject on the internet that GPT-3.5 don't already know, you'll have to go to the internet and scrape the data yourself and save it as a text on the data folder of chatgpt-retrieval-main.

 Another issue is that querying ChatGPT like this takes more time to load when compared to asking ChatGPT directly.

 Lastly, the only model currently available is GPT-3.5 Turbo. So even if you have access to GPT-4, you won't be able to use it to power your custom ChatGPT instance.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://youtube-web.techidaily.com/n-2024-skyrocket-your-streams-earnings-universal-strategies-for-success/"><u>[New] In 2024, Skyrocket Your Stream's Earnings  Universal Strategies for Success</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-sideways-instagram-videos-an-enigma-or-bug-for-2024/"><u>[New] Sideways Instagram Videos  An Enigma or Bug for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-the-art-of-vrecorder-integration-simple-download-and-use-tutorials-for-2024/"><u>[New] The Art of VRecorder Integration  Simple Download & Use Tutorials for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-integrating-automatic-speech-conversion-into-powerpoint-presentations/"><u>[Updated] 2024 Approved  Integrating Automatic Speech Conversion Into PowerPoint Presentations</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-in-2024-gain-more-loyal-viewers-unlock-top-strategies-for-enhancing-viewer-retention-on-youtube/"><u>[Updated] In 2024, Gain More Loyal Viewers  Unlock Top Strategies for Enhancing Viewer Retention on YouTube</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-the-best-8-value-video-communication-programs-for-pc-and-mac/"><u>[Updated] In 2024, The Best 8 Value Video Communication Programs for PC and MAC</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-unraveling-successs-secrets-how-to-amass-more-subscribers-on-youtube/"><u>[Updated] Unraveling Success's Secrets  How to Amass More Subscribers on YouTube</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-instagrams-best-practices-for-sensational-video-loops/"><u>2024 Approved  Instagram's Best Practices for Sensational Video Loops</u></a></li>
<li><a href="https://tech-haven.techidaily.com/awaken-your-smartphone-with-chatgpt/"><u>Awaken Your Smartphone with ChatGPT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/beware-of-downloading-google-bard-it-may-be-a-security-threat/"><u>Beware of Downloading Google Bard - It May Be a Security Threat</u></a></li>
<li><a href="https://tech-haven.techidaily.com/bring-back-the-past-a-guide-to-recovering-deleted-chat-history-from-microsofts-chatbot/"><u>Bring Back the Past: A Guide to Recovering Deleted Chat History From Microsoft's Chatbot</u></a></li>
<li><a href="https://tech-haven.techidaily.com/browser-integration-or-enhanced-functionality-selecting-your-preferred-chatgpt-type/"><u>Browser Integration or Enhanced Functionality: Selecting Your Preferred ChatGPT Type</u></a></li>
<li><a href="https://tech-haven.techidaily.com/budget-friendly-lg-um7300-49-inch-4k-television-evaluation/"><u>Budget-Friendly LG UM7300 49-Inch 4K Television Evaluation</u></a></li>
<li><a href="https://tech-haven.techidaily.com/comparative-insights-how-is-natural-language-processing-different-from-machine-learning/"><u>Comparative Insights: How Is Natural Language Processing Different From Machine Learning?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/crafting-the-future-of-sound-integrating-gpt-into-daws/"><u>Crafting the Future of Sound: Integrating GPT Into DAWs</u></a></li>
<li><a href="https://tech-haven.techidaily.com/discovering-the-secrets-of-gpt-4-all-how-this-advanced-ai-engine-works/"><u>Discovering the Secrets of GPT- 4 All: How This Advanced AI Engine Works</u></a></li>
<li><a href="https://tech-haven.techidaily.com/embarking-on-langchain-an-insiders-quick-tale/"><u>Embarking on LangChain: An Insider's Quick Tale</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/essential-leisure-ideal-screen-time-solutions-for-2024/"><u>Essential Leisure  Ideal Screen-Time Solutions for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/explore-the-best-tools-to-enhance-your-pdf-analysis/"><u>Explore the Best Tools to Enhance Your PDF Analysis</u></a></li>
<li><a href="https://tech-haven.techidaily.com/explore-the-top-9-chatgpt-add-ons-for-immediate-website-upgrade/"><u>Explore the Top 9 ChatGPT Add-Ons for Immediate Website Upgrade</u></a></li>
<li><a href="https://tech-haven.techidaily.com/guarding-against-tech-giants-keep-openai-bots-off-your-content/"><u>Guarding Against Tech Giants: Keep OpenAI Bots Off Your Content</u></a></li>
<li><a href="https://change-location.techidaily.com/home-button-not-working-on-tecno-phantom-v-fold-here-are-real-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Home Button Not Working on Tecno Phantom V Fold? Here Are Real Fixes | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-does-googles-revolutionary-palm-2-transform-natural-language-processing/"><u>How Does Google's Revolutionary PaLM 2 Transform Natural Language Processing?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-to-craft-perfect-presentations-with-these-7-best-ai-apps/"><u>How to Craft Perfect Presentations with These 7 Best AI Apps</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-turn-off-the-screen-lock-on-my-c300-by-drfone-android-unlock-android-unlock/"><u>How to turn off the screen lock on my C300</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-here-are-some-of-the-best-pokemon-discord-servers-to-join-on-realme-12-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some of the Best Pokemon Discord Servers to Join On Realme 12 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-streamlining-youtube-audio-pace-via-devices/"><u>In 2024, Streamlining YouTube Audio Pace via Devices</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-top-10-rapidly-expanding-youtube-hubs-for-motivation/"><u>In 2024, Top 10 Rapidly Expanding YouTube Hubs for Motivation</u></a></li>
<li><a href="https://tech-haven.techidaily.com/in-the-realm-of-ramblings-mistral-versus-gpt-3/"><u>In the Realm of Ramblings: Mistral Versus GPT-3</u></a></li>
<li><a href="https://tech-haven.techidaily.com/innovative-techniques-leveraging-chatgpt-for-audio-production-within-a-daw-environment/"><u>Innovative Techniques: Leveraging ChatGPT for Audio Production Within a DAW Environment</u></a></li>
<li><a href="https://tech-haven.techidaily.com/integrating-intelligence-four-methods-for-chatgpt-to-read-your-pdfs/"><u>Integrating Intelligence: Four Methods for ChatGPT to Read Your PDFs</u></a></li>
<li><a href="https://tech-haven.techidaily.com/level-up-gaming-skills-with-these-top-chatgpt-games/"><u>Level Up Gaming Skills with These Top ChatGPT Games</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-tough-emails-leveraging-chatgpt-at-your-desk/"><u>Mastering Tough Emails: Leveraging ChatGPT at Your Desk</u></a></li>
<li><a href="https://tech-haven.techidaily.com/pc-troubleshooting-made-simple-using-conversational-ai-technology/"><u>PC Troubleshooting Made Simple Using Conversational AI Technology</u></a></li>
<li><a href="https://tech-haven.techidaily.com/police-strike-down-vpns-upholding-cyber-law/"><u>Police Strike Down VPNs, Upholding Cyber Law</u></a></li>
<li><a href="https://tech-haven.techidaily.com/progressive-breakdown-understanding-and-comparing-every-version-from-gpt-1-to-gpt-4/"><u>Progressive Breakdown: Understanding and Comparing Every Version From GPT-1 to GPT-4</u></a></li>
<li><a href="https://tech-haven.techidaily.com/revolutionize-your-document-creation-process-with-chatgpt-and-microsoft-word-collaboration/"><u>Revolutionize Your Document Creation Process with ChatGPT and Microsoft Word Collaboration</u></a></li>
<li><a href="https://hardware-help.techidaily.com/step-by-step-tutorial-to-downloading-the-latest-broadcom-gigabit-driver-on-windows-10-fixed/"><u>Step-by-Step Tutorial to Downloading the Latest Broadcom Gigabit Driver on Windows 10 [FIXED]</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-future-is-now-how-generative-artificial-intelligence-reshapes-careers-in-7-pivotal-ways/"><u>The Future Is Now: How Generative Artificial Intelligence Reshapes Careers in 7 Pivotal Ways</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-path-to-proficiency-in-chatgpts-api-utilization/"><u>The Path to Proficiency in ChatGPT's API Utilization</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-sixfold-impact-of-ai-on-next-gen-smartwatch-features-with-chatgpt-integration/"><u>The Sixfold Impact of AI on Next-Gen Smartwatch Features with ChatGPT Integration</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-ultimate-guide-crafting-artificnals-through-dall-e-and-chatgpt-4-integration/"><u>The Ultimate Guide: Crafting Artificnals Through DALL-E & ChatGPT-4 Integration</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-ultimate-pathway-to-creating-metaverse-identities-for-2024/"><u>The Ultimate Pathway to Creating Metaverse Identities for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/transformative-tools-the-best-7-ai-presentation-devices/"><u>Transformative Tools: The Best 7 AI Presentation Devices</u></a></li>
<li><a href="https://tech-haven.techidaily.com/transforming-therapy-sessions-with-chatgpt-for-effective-cbt-interventions/"><u>Transforming Therapy Sessions with ChatGPT for Effective CBT Interventions</u></a></li>
<li><a href="https://tech-haven.techidaily.com/which-ai-reigns-supreme-comparing-chatgpt-and-google-bard/"><u>Which AI Reigns Supreme? Comparing ChatGPT and Google Bard</u></a></li>
<li><a href="https://buynow-help.techidaily.com/wi-fi-mesh-is-its-value-clear/"><u>Wi-Fi Mesh: Is Its Value Clear?</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-layers-impact-on-linux-dominance/"><u>Windows Layer's Impact on Linux Dominance</u></a></li>
</ul></div>
