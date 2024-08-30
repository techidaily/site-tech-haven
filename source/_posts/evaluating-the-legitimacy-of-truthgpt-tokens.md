---
title: Evaluating the Legitimacy of TruthGPT Tokens
date: 2024-08-29T02:21:12.817Z
updated: 2024-08-30T02:21:12.817Z
tags:
  - chatgpt
  - open-ai
categories:
  - openAI
  - chatgpt
description: This Article Describes Evaluating the Legitimacy of TruthGPT Tokens
excerpt: This Article Describes Evaluating the Legitimacy of TruthGPT Tokens
thumbnail: https://thmb.techidaily.com/98a99e3eeb7551ca233212f1d8efc0e3f75521feec7e96aa9478cde7f5ee2f72.jpg
---

## Is CodeGPT The Future of Coding? Evaluating Its Capability to Compose Code

### Quick Links

* [What Is CodeGPT?](https://www.makeuseof.com/code-gpt-can-it-really-write-code/#what-is-codegpt)
* [How Much Does CodeGPT Cost?](https://www.makeuseof.com/code-gpt-can-it-really-write-code/#how-much-does-codegpt-cost)
* [Can CodeGPT Really Write Code?](https://www.makeuseof.com/code-gpt-can-it-really-write-code/#can-codegpt-really-write-code)

### Key Takeaways

* CodeGPT is an AI-powered coding assistant that helps programmers write and fix code, with features like auto-completion and code explanation.
* CodeGPT is available for free, but subscription plans for some features range from $9.99 to $49.99 per month.
* While CodeGPT can write code, its output may not always be error-free or follow best practices, so you should aim to understand and modify the generated code as necessary.

 If you're looking for an AI-powered assistant to help you write code, chances are you've encountered CodeGPT. It's one of many AI-powered tools you can use to assist you when programming. But can CodeGPT actually write code?

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
## What Is CodeGPT?

 CodeGPT is a dedicated extension that uses different artificial intelligence (AI) models to help programmers write and fix code. It includes various features geared towards faster and easier programming, including auto-completion, code explanation, refactoring, documentation, unit testing, error-checking, and bug-fixing. It also has a ChatGPT-like interface you can access from your code editor.

 The extension is particularly powerful because it lets you connect to various mainstream[large language models (LLMs)](https://www.makeuseof.com/what-are-large-langauge-models-how-do-they-work/) from different providers like OpenAI and Google. On top of that, CodeGPT lets you create your own AI agents that you can use in your projects or share with others.

 While there are several[code editors for Linux](https://www.makeuseof.com/best-ide-code-editors-for-linux/) , macOS, and Windows, CodeGPT is only available in two. Today, you can either[install and use CodeGPT in VS Code](https://www.makeuseof.com/install-use-codegpt-in-vs-code/) or in Cursor, which is a fork of VS Code.

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How Much Does CodeGPT Cost?

 You can download and install CodeGPT for free, but using the extension comes at a cost. CodeGPT offers various subscription packages that you can pay for if you need unlimited access.

 CodeGPT Plus has three subscription plans. The Basic plan goes for $9.99/month, followed by Standard ($19.99/month) and Gold ($49.99/month). There's a free trial period available, which you can use to evaluate the extension. Each package gives you access to specific AI agents with unlimited interactions.

 Bear in mind that you'll need to pay for unlimited usage of third-party AI models like OpenAI's GPT-4 model, for example. Although you can[access Open AI's GPT-4 model for free](https://www.makeuseof.com/ways-access-gpt-4-free/) , you cannot do so from within VS Code or Cursor.

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Can CodeGPT Really Write Code?

 To evaluate this, we'll use the extension to help us generate two different code samples in Python.

 First, we ask the model to generate a stack data structure in Python with all the relevant methods. We used this prompt:

> Create a stack in Python and include all the necessary methods

The model generated the following response:

        `class Stack:  
    def __init__(self):  
        self.stack = []  
​  
    def push(self, item):  
        self.stack.append(item)  
​  
    def pop(self):  
        if self.is_empty():  
            raise IndexError("Pop from empty stack")  
        return self.stack.pop()  
​  
    def peek(self):  
        if self.is_empty():  
            raise IndexError("Peek from empty stack")  
        return self.stack[-1]  
​  
    def is_empty(self):  
        return len(self.stack) == 0  
​  
    def size(self):  
        return len(self.stack)`

 This sample shows that CodeGPT is clever enough to create the stack using a**class** and include the necessary checks to handle specific errors that may arise. For instance, the code throws informative errors if you try to**peek** or**pop** an empty stack.

 In a second challenge, we asked CodeGPT to save a response formatted in JSON from the[JSONPlaceholder](https://jsonplaceholder.typicode.com/) API to a CSV file. For context, the response from the JSONPlaceholder API looks like this:

        `{  
 'userId': 1,  
 'id': 1,  
 'title': 'sunt aut facere repellat provident occaecati excepturi optio reprehenderit',  
 'body': 'quia et suscipit\nsuscipit recusandae consequuntur expedita et cum\nreprehenderit molestiae ut ut quas totam\nnostrum rerum est autem sunt rem eveniet architecto'  
}`

We asked CodeGPT the following:

> I've made a request to an external API at <https://jsonplaceholder.typicode.com/posts/1> and I'm getting a response back. I've formatted the response as json, how can I save it in a csv file?

The code that CodeGPT responded with was:

        `import csv  
import requests  
  
# Make a GET request to the API  

response = requests.get('<https://jsonplaceholder.typicode.com/posts/1>')  

# Convert the response to JSON format  

data = response.json()  
  
# Since we're receiving a dictionary, we need to turn it into a list of one dictionary  

data = [data]  
  
# Open (or create) a CSV file to write the data  

with open('output.csv', 'w', newline='') as output_file:  
   # Create a CSV writer object  
   writer = csv.DictWriter(output_file, fieldnames=data[0].keys())  
   # Write the CSV headers  
   writer.writeheader()  
   # Write the data to the CSV file  
   writer.writerows(data)  
`

 Generally, this response is good; it doesn't need any tweaking to work. CodeGPT also added comments explaining the purpose of the various lines of code, which is useful if you're doing something for the first time.

 The only issue here is the response doesn't specify an encoding type while calling**open()** . While a default will automatically be included, specifying an encoding type is recommended and considered best practice when[writing to files in Python](https://www.makeuseof.com/write-print-to-file-python/) . This might save you from incorrect interpretation, leading to jumbled text.

 So: CodeGPT can write code, but you should be careful because it won't always give you the best output. What you get might be error-prone and might not follow the best practices. Whenever you use CodeGPT or any other AI-powered tool to write code, strive to understand what the code does first. Don't just copy and paste.


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
<li><a href="https://youtube-webster.techidaily.com/024-approved-breakthrough-techniques-for-outstanding-youtube-openers-technique-1plus2/"><u>[New] 2024 Approved  Breakthrough Techniques for Outstanding YouTube Openers (Technique 1+2)</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/o-live-in-style-a-detailed-guide-to-youtubes-full-sphere-videos/"><u>[New] Go Live in Style  A Detailed Guide to YouTube's Full-Sphere Videos</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-financially-flourishing-online-media-personality/"><u>[Updated] Financially Flourishing Online Media Personality</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-quick-simple-steps-to-saving-twitters-emotive-graphics-gifs/"><u>[Updated] In 2024, Quick, Simple Steps to Saving Twitter’s Emotive Graphics (GIFs)</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-top-28-youtube-music-splitters-for-easy-audio-extraction/"><u>[Updated] In 2024, Top 28 YouTube Music Splitters for Easy Audio Extraction</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-combat-colossus-leading-10-royale-titles/"><u>2024 Approved  Combat Colossus  Leading 10 Royale Titles</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-fiscally-flourishing-through-film-reviewing-retail-relics/"><u>2024 Approved  Fiscally Flourishing Through Film  Reviewing Retail Relics</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-leading-techniques-for-youtube-mpeg-migration/"><u>2024 Approved  Leading Techniques for YouTube MPEG Migration</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-narrative-nooks-the-leading-10-rogues/"><u>2024 Approved  Narrative Nooks  The Leading 10 Rogues</u></a></li>
<li><a href="https://tech-haven.techidaily.com/beware-no-authentic-chatgpt-app-for-windows-avoid-the-fake-ones/"><u>Beware: No Authentic ChatGPT App for Windows - Avoid the Fake Ones!</u></a></li>
<li><a href="https://os-tips.techidaily.com/1723620242101-boost-your-iphones-speed-and-storage-with-these-4-best-free-cleanse-applications/"><u>Boost Your iPhone's Speed & Storage with These 4 Best Free Cleanse Applications!</u></a></li>
<li><a href="https://tech-haven.techidaily.com/can-artificnial-intelligence-outsmart-humans-predicting-which-jobs-are-endangered-by-generative-models/"><u>Can Artificnial Intelligence Outsmart Humans? Predicting Which Jobs Are Endangered by Generative Models</u></a></li>
<li><a href="https://tech-haven.techidaily.com/comparing-chatgpt-and-google-translate-determining-the-superior-language-tool/"><u>Comparing ChatGPT and Google Translate: Determining the Superior Language Tool</u></a></li>
<li><a href="https://tech-haven.techidaily.com/distinguishing-between-powerful-ai-and-basic-ai-technologies/"><u>Distinguishing Between Powerful AI and Basic AI Technologies</u></a></li>
<li><a href="https://tech-haven.techidaily.com/dive-into-the-world-of-ai-at-bing-how-to-signup/"><u>Dive Into the World of AI at Bing: How-To Signup</u></a></li>
<li><a href="https://games-able.techidaily.com/elevate-gameplay-and-engagement-best-7-bots-for-twitch-pros/"><u>Elevate Gameplay & Engagement: Best 7 Bots For Twitch Pros</u></a></li>
<li><a href="https://tech-haven.techidaily.com/embark-on-the-path-to-cash-rewards-via-bug-bounties-at-openai/"><u>Embark on the Path to Cash Rewards via Bug Bounties at OpenAI</u></a></li>
<li><a href="https://tech-haven.techidaily.com/exploring-the-creation-process-of-chatgpts-text-is-there-any-risk-of-plagiarism/"><u>Exploring the Creation Process of ChatGPT's Text: Is There Any Risk of Plagiarism?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/finding-your-way-with-gpt-in-remote-landscapes/"><u>Finding Your Way with GPT in Remote Landscapes</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/from-niche-to-notorious-the-journey-of-crafting-memetic-content-gifs-for-2024/"><u>From Niche to Notorious  The Journey of Crafting Memetic Content (GIFs) for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/future-horizons-in-artificial-intelligence-unveiling-the-potential-of-new-age-generative-bots-and-chat-technologies/"><u>Future Horizons in Artificial Intelligence: Unveiling the Potential of New-Age Generative Bots and Chat Technologies</u></a></li>
<li><a href="https://tech-haven.techidaily.com/global-vs-closed-ai-systems-dissecting-varieties/"><u>Global Vs. Closed AI Systems: Dissecting Varieties</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-google-frp-lock-from-tecno-spark-10c-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock from Tecno Spark 10C Devices</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-mastering-firefoxs-popup-window-magic/"><u>In 2024, Mastering Firefox's Popup Window Magic</u></a></li>
<li><a href="https://extra-tips.techidaily.com/insightful-evaluation-androids-photography-tool-lightroom/"><u>Insightful Evaluation  Android's Photography Tool, Lightroom</u></a></li>
<li><a href="https://tech-haven.techidaily.com/master-the-art-of-character-development-with-these-11-powerful-chatgpt-techniques/"><u>Master the Art of Character Development with These 11 Powerful ChatGPT Techniques</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-through-gpt-coding-utilizing-openais-platform-with-ease/"><u>Navigating Through GPT-Coding: Utilizing OpenAI's Platform with Ease</u></a></li>
<li><a href="https://audio-editing.techidaily.com/quiet-the-screenplay-removing-audible-aspects-from-mp4mkvavimov-and-wmv-videos-for-2024/"><u>Quiet the Screenplay Removing Audible Aspects From MP4/MKV/AVI/MOV and WMV Videos for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/redefining-home-management-ai-driven-by-gpts-touch/"><u>Redefining Home Management: AI-Driven by GPT's Touch</u></a></li>
<li><a href="https://tech-haven.techidaily.com/risks-avoid-mobile-gpt-app-downloads/"><u>Risks: Avoid Mobile GPT App Downloads</u></a></li>
<li><a href="https://techidaily.com/step-by-step-guide-pairing-your-logitech-wireless-keyboard/"><u>Step-by-Step Guide: Pairing Your Logitech Wireless Keyboard</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-installation-instructions-for-linksys-wusb6300-wireless-usb-adapter-free-download/"><u>Step-by-Step Installation Instructions for Linksys WUSB6300 Wireless USB Adapter - Free Download</u></a></li>
<li><a href="https://tech-haven.techidaily.com/step-by-step-strategies-utilizing-my-gpt-bots-to-excel-in-board-games-image-design-and-advanced-tasks/"><u>Step-by-Step Strategies: Utilizing My GPT Bots to Excel in Board Games, Image Design, and Advanced Tasks</u></a></li>
<li><a href="https://tech-haven.techidaily.com/step-by-step-tutorial-accessing-plugin-support-and-web-browsing-on-chatgpt-beta-version/"><u>Step-by-Step Tutorial: Accessing Plugin Support and Web Browsing on ChatGPT Beta Version</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-future-is-now-uncover-what-googles-ai-project-gemini-is-striving-for/"><u>The Future Is Now: Uncover What Google's AI Project Gemini Is Striving For</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-hidden-dangers-of-over-relying-on-ai-6-critical-points/"><u>The Hidden Dangers of Over-Relying on AI: 6 Critical Points</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-new-frontier-of-business-with-whisper-and-gptapis/"><u>The New Frontier of Business with Whisper & GPTAPIs</u></a></li>
<li><a href="https://tech-haven.techidaily.com/threatened-by-gpts-content-generation/"><u>Threatened by GPT's Content Generation?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-5-factors-that-make-ai-ill-suited-for-full-time-writing-roles/"><u>Top 5 Factors That Make AI Ill-Suited for Full-Time Writing Roles</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/ultimate-compilation-the-top-5-high-fidelity-cameras/"><u>Ultimate Compilation  The Top 5 High Fidelity Cameras</u></a></li>
<li><a href="https://tech-haven.techidaily.com/understanding-chatgpt-and-the-potential-of-using-advanced-generative-ai-tech/"><u>Understanding ChatGPT & The Potential of Using Advanced Generative AI Tech</u></a></li>
<li><a href="https://tech-haven.techidaily.com/understanding-turings-challenge-is-it-unbeatable/"><u>Understanding Turing's Challenge: Is It Unbeatable?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unlock-the-power-of-ai-integrating-codegpt-into-your-visual-studio-workflow/"><u>Unlock the Power of AI: Integrating CodeGPT Into Your Visual Studio Workflow</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unveiling-top-tier-gadgets-explore-toms-hardware-insights/"><u>Unveiling Top-Tier Gadgets: Explore Tom's Hardware Insights</u></a></li>
<li><a href="https://ai-video.techidaily.com/updated-breaking-language-barriers-elevate-your-content-with-the-best-free-video-translator-apps/"><u>Updated Breaking Language Barriers Elevate Your Content with the Best Free Video Translator Apps</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-reduced-clarity-of-audio-outputs-in-the-latest-adobe-rush-release/"><u>Updated In 2024, Reduced Clarity of Audio Outputs in the Latest Adobe Rush Release</u></a></li>
<li><a href="https://techidaily.com/useful-ways-that-can-help-to-effectively-recover-deleted-files-from-vivo-y100-5g-by-fonelab-android-recover-data/"><u>Useful ways that can help to effectively recover deleted files from Vivo Y100 5G</u></a></li>
<li><a href="https://tech-haven.techidaily.com/what-does-the-leadership-shake-up-at-openai-mean-for-chatgpt/"><u>What Does the Leadership Shake-Up at OpenAI Mean for ChatGPT?</u></a></li>
</ul></div>
