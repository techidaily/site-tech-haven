---
title: How to Use ChatGPT on a Mac
date: 2024-08-16T11:24:56.134Z
updated: 2024-08-17T11:24:56.134Z
tags:
  - chatgpt
  - open-ai
categories:
  - openAI
  - chatgpt
description: This Article Describes How to Use ChatGPT on a Mac
excerpt: This Article Describes How to Use ChatGPT on a Mac
thumbnail: https://thmb.techidaily.com/9e992eeefd8e84a59a07a57a0f98ead45d9f4acef9a3d89961494ce528757e4e.jpg
---

## Llama ˈLocal-Ization' Guide: How to Install and Use It Yourself

 Meta released Llama 2 in the summer of 2023\. The new version of Llama is fine-tuned with 40% more tokens than the original Llama model, doubling its context length and significantly outperforming other open-sourced models available. The fastest and easiest way to access Llama 2 is via an API through an online platform. However, if you want the best experience, installing and loading Llama 2 directly on your computer is best.

 With that in mind, we've created a step-by-step guide on how to use Text-Generation-WebUI to load a quantized Llama 2 LLM locally on your computer.

## Why Install Llama 2 Locally

 There are many reasons why people choose to run Llama 2 directly. Some do it for privacy concerns, some for customization, and others for offline capabilities. If you're researching, fine-tuning, or integrating Llama 2 for your projects, then accessing Llama 2 via API might not be for you. The point of running an LLM locally on your PC is to reduce reliance on[third-party AI tools](https://www.makeuseof.com/best-ai-web-apps/) and use AI anytime, anywhere, without worrying about leaking potentially sensitive data to companies and other organizations.

 With that said, let's begin with the step-by-step guide to installing Llama 2 locally.

## Step 1: Install Visual Studio 2019 Build Tool

 To simplify things, we will use a one-click installer for Text-Generation-WebUI (the program used to load Llama 2 with GUI). However, for this installer to work, you need to download the Visual Studio 2019 Build Tool and install the necessary resources.

**Download:** [Visual Studio 2019](https://learn.microsoft.com/en-us/visualstudio/releases/2019/release-notes) (Free)

1. Go ahead and download the community edition of the software.
2. Now install Visual Studio 2019, then open the software. Once opened, tick the box on**Desktop development with C++** and hit install.  
<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Install-Desktop-Development-With-C++](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/2-install-desktop-development-with-c.jpg)

 Now that you have Desktop development with C++ installed, it's time to download the Text-Generation-WebUI one-click installer.

## Step 2: Install Text-Generation-WebUI

 The Text-Generation-WebUI one-click installer is a script that automatically creates the required folders and sets up the Conda environment and all necessary requirements to run an AI model.

 To install the script, download the one-click installer by clicking on**Code** \>**Download ZIP.**

**Download:** [Text-Generation-WebUI Installer](https://github.com/oobabooga/text-generation-webui/tree/main) (Free)

1. Once downloaded, extract the ZIP file to your preferred location, then open the extracted folder.
2. Within the folder, scroll down and look for the appropriate start program for your operating system. Run the programs by double-clicking the appropriate script.  
   * If you are on Windows, select**start\_windows** batch file  
   * for MacOS, select**start\_macos** shell scrip  
   * for Linux,**start\_linux** shell script.  
   ![Select operating system](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/4-select-operating-system.jpg)
3. Your anti-virus might create an alert; this is fine. The prompt is just an[antivirus false positive](https://www.makeuseof.com/what-is-antivirus-false-result/) for running a batch file or script. Click on**Run anyway** .
4. A terminal will open and start the setup. Early on, the setup will pause and ask you what GPU you are using. Select the appropriate type of GPU installed on your computer and hit enter. For those without a dedicated graphics card, select**None (I want to run models in CPU mode)** . Keep in mind that running on CPU mode is much slower when compared to running the model with a dedicated GPU.  
![Selecting GPU hardware installed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/5-select-gpu-settings.jpg)
5. Once the setup is complete, you can now launch Text-Generation-WebUI locally. You can do so by opening your preferred web browser and entering the provided IP address on the URL.  
<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
![How to launch-Text-Generation-WebUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/6-launch-text-generation-webui.jpg)
6. The WebUI is now ready for use.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
![Text-Generation-WebUI ](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/7-text-generation-webui-view.jpg)

 However, the program is only a model loader. Let's download Llama 2 for the model loader to launch.

## Step 3: Download the Llama 2 Model

 There are quite a few things to consider when deciding which iteration of Llama 2 you need. These include parameters, quantization, hardware optimization, size, and usage. All of this information will be found denoted in the model's name.

* **Parameters:** The number of parameters used to train the model. Bigger parameters make more capable models but at the cost of performance.
* **Usage:** Can either be standard or chat. A chat model is optimized to be used as a chatbot like ChatGPT, while the standard is the default model.
* **Hardware Optimization:** Refers to what hardware best runs the model. GPTQ means the model is optimized to run on a dedicated GPU, while GGML is optimized to run on a CPU.
* **Quantization:** Denotes the precision of weights and activations in a model. For inferencing, a precision of q4 is optimal.
* **Size:** Refers to the size of the specific model.

 Note that some models may be arranged differently and may not even have the same types of information displayed. However, this type of naming convention is fairly common in the[HuggingFace](https://www.makeuseof.com/what-is-hugging-face-and-what-is-it-used-for/) Model library, so it's still worth understanding.

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![HuggingFace model naming convention](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/huggingface-model-naming-convention-1.jpg)

 In this example, the model can be identified as a medium-sized Llama 2 model trained on 13 billion parameters optimized for chat inferencing using a dedicated CPU.

 For those running on a dedicated GPU, choose a**GPTQ** model, while for those using a CPU, choose**GGML** . If you want to chat with the model like you would with ChatGPT, choose**chat** , but if you want to experiment with the model with its full capabilities, use the**standard** model. As for parameters, know that using bigger models will provide better results at the expense of performance. I would personally recommend you start with a 7B model. As for quantization, use q4, as it's only for inferencing.

**Download:** [GGML](https://huggingface.co/localmodels/Llama-2-7B-ggml/tree/main) (Free)

**Download:** [GPTQ](https://huggingface.co/localmodels/Llama-2-7B-Chat-GPTQ/tree/main) (Free)

 Now that you know what iteration of Llama 2 you need, go ahead and download the model you want.

 In my case, since I'm running this on an ultrabook, I'll be using a GGML model fine-tuned for chat,**llama-2-7b-chat-ggmlv3.q4\_K\_S.bin.**

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Downloading Llama 2 model of your preference](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/8-download-llama-2-model.jpg)

 After the download is finished, place the model in**text-generation-webui-main** \>**models** .

![Placing Llama 2 model to model folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/9-place-model-to-model-folder.jpg)

 Now that you have your model downloaded and placed in the model folder, it's time to configure the model loader.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
## Step 4: Configure Text-Generation-WebUI

Now, let's begin the configuration phase.

1. Once again, open Text-Generation-WebUI by running the**start\_(your OS)** file (see the previous steps above).
2. On the tabs located above the GUI, click**Model.** Click the refresh button at the model dropdown menu and select your model.
3. Now click on the dropdown menu of the**Model loader** and select**AutoGPTQ** for those using a GTPQ model and**ctransformers** for those using a GGML model. Finally, click on**Load** to load your model.  
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
![Setting model loader](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/10-select-model-loader.jpg)
4. To use the model, open the Chat tab and start testing the model.  
![Testing Llama 2 locally](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/12-testing-llama-2-locally.jpg)

 Congratulations, you've successfully loaded Llama2 on your local computer!

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
## Try Out Other LLMs

 Now that you know how to run Llama 2 directly on your computer using Text-Generation-WebUI, you should also be able to run other LLMs besides Llama. Just remember the naming conventions of models and that only quantized versions of models (usually q4 precision) can be loaded on regular PCs. Many quantized LLMs are available on HuggingFace. If you want to explore other models, search for TheBloke in HuggingFace's model library, and you should find many models available.


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
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-the-complete-guide-to-facebooks-live-feature-how-to-and-best-practices/"><u>[New] 2024 Approved  The Complete Guide to Facebook's Live Feature  How-To & Best Practices</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/-easy-ways-to-multiply-your-youtube-follower-base/"><u>[New] 5 Easy Ways to Multiply Your YouTube Follower Base</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-apowersoft-free-screen-recorder-review-for-2024/"><u>[New] Apowersoft Free Screen Recorder Review for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-convert-srt-with-ease-the-finest-free-converters-ranked/"><u>[New] In 2024, Convert SRT with Ease - The Finest FREE Converters Ranked</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-minimalist-obs-adjustments-for-under-500-pcs-for-2024/"><u>[New] Minimalist OBS Adjustments for Under-$500 PCs for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-reel-it-in-8-online-utilities-for-creating-and-sharing-instagram-videos/"><u>[New] Reel It In  8 Online Utilities For Creating & Sharing Instagram Videos</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ltimate-streaming-hits-for-movie-lovers/"><u>[New] Ultimate Streaming Hits for Movie Lovers</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-best-5-video-recording-software-timelapse-edition/"><u>[Updated] 2024 Approved  Best 5 Video Recording Software Timelapse Edition</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-video-editing-virtuosity-mastering-the-fade-inout/"><u>[Updated] Video Editing Virtuosity  Mastering the Fade-In/Out</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-add-fun-to-youtube-comments-a-quick-guide-to-emojis/"><u>2024 Approved  Add Fun to YouTube Comments  A Quick Guide to Emojis</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-glowing-with-hd-does-it-serve-the-scope-of-hdr-well/"><u>2024 Approved  Glowing with HD  Does It Serve the Scope of HDR Well?</u></a></li>
<li><a href="https://facebook.techidaily.com/a-second-act-for-instagram-why-some-want-it-back/"><u>A Second Act for Instagram: Why Some Want It Back?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/exploring-the-premier-choices-beyond-chatgpt/"><u>Exploring the Premier Choices Beyond ChatGPT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/gpt-4-is-now-free-for-everyone-but-there-are-still-6-reasons-to-keep-using-chatgpt-plus/"><u>GPT-4 Is Now Free for Everyone, but There Are Still 6 Reasons to Keep Using ChatGPT Plus</u></a></li>
<li><a href="https://tech-haven.techidaily.com/gpt-powered-text-interaction-for-paper-files/"><u>GPT-Powered Text Interaction for Paper Files</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-chatgpt-pales-when-it-comes-to-nuanced-writing-tasks/"><u>How ChatGPT Pales When It Comes to Nuanced Writing Tasks</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-android-unlock-code-sim-unlock-your-infinix-note-30-pro-phone-and-remove-locked-screen-by-drfone-android/"><u>In 2024, Android Unlock Code Sim Unlock Your Infinix Note 30 Pro Phone and Remove Locked Screen</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-maximizing-efficiency-in-rl-video-recordings/"><u>In 2024, Maximizing Efficiency in RL Video Recordings</u></a></li>
<li><a href="https://tech-haven.techidaily.com/join-openais-quest-track-and-report-software-glitches/"><u>Join OpenAI's Quest: Track and Report Software Glitches!</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mapping-ais-emergence-in-modern-times/"><u>Mapping AI's Emergence in Modern Times</u></a></li>
<li><a href="https://tech-haven.techidaily.com/master-the-marketplace-10-ways-chatgpt-enhances-your-linkedin-job-search-strategy/"><u>Master the Marketplace: 10 Ways ChatGPT Enhances Your LinkedIn Job Search Strategy</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-image-generation-using-chatgpt-step-by-step-tips-and-tricks/"><u>Mastering Image Generation Using ChatGPT: Step-by-Step Tips and Tricks</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-the-fix-a-comprehensive-guide-to-chatgpt-login-difficulties/"><u>Mastering the Fix: A Comprehensive Guide to ChatGPT Login Difficulties</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-web-development-via-gpts-fourfold-assistance/"><u>Navigating Web Development via GPT’s Fourfold Assistance</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-wild-terrain-with-technology-can-chatgpt-be-your-guide/"><u>Navigating Wild Terrain with Technology: Can ChatGPT Be Your Guide?</u></a></li>
<li><a href="https://activate-lock.techidaily.com/new-multiple-ways-how-to-remove-icloud-activation-lock-from-your-apple-iphone-15-pro-by-drfone-ios/"><u>New Multiple Ways How To Remove iCloud Activation Lock From your Apple iPhone 15 Pro</u></a></li>
<li><a href="https://tech-haven.techidaily.com/outsmarting-love-scammers-discover-7-ai-tricks-used-by-online-con-artists-to-target-the-vulnerable/"><u>Outsmarting Love Scammers: Discover 7 AI Tricks Used by Online Con Artists to Target the Vulnerable</u></a></li>
<li><a href="https://tech-haven.techidaily.com/phone-free-signup-a-comprehensive-guide-to-joining-chatgpt-telegram-and-whatsapp/"><u>Phone-Free Signup: A Comprehensive Guide to Joining ChatGPT, Telegram & WhatsApp</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/preparation-to-beat-giovani-in-pokemon-go-for-realme-v30-drfone-by-drfone-virtual-android/"><u>Preparation to Beat Giovani in Pokemon Go For Realme V30 | Dr.fone</u></a></li>
<li><a href="https://driver-install.techidaily.com/quick-lenovo-z50-70-firmware-patches-here/"><u>Quick Lenovo Z50-70 Firmware Patches Here</u></a></li>
<li><a href="https://techidaily.com/samsung-galaxy-m34-5g-won-t-play-mkv-movies-by-aiseesoft-video-converter-play-mkv-on-android/"><u>Samsung Galaxy M34 5G won’t play MKV movies</u></a></li>
<li><a href="https://tech-haven.techidaily.com/sculpting-digital-prose-to-mirror-your-voice/"><u>Sculpting Digital Prose to Mirror Your Voice</u></a></li>
<li><a href="https://tech-haven.techidaily.com/siri-or-chatgpt-discover-what-sets-them-apart-in-voice-assistant-technology/"><u>Siri or ChatGPT? Discover What Sets Them Apart in Voice Assistant Technology</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-dichotomy-of-reality-and-fantasy-through-ai/"><u>The Dichotomy of Reality & Fantasy Through AI</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/the-great-livestream-showdown-streamlabs-vs-obs-head-to-head-for-2024/"><u>The Great Livestream Showdown  Streamlabs Vs. OBS Head-to-Head for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-impact-of-generative-algorithms-on-interactive-entertainment/"><u>The Impact of Generative Algorithms on Interactive Entertainment</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/the-pano-way-to-online-visibility-posting-360-photos-through-mobile-apps-for-2024/"><u>The Pano-Way to Online Visibility  Posting 360 Photos Through Mobile Apps for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-rise-of-gpt-bot-insights-into-its-impact-on-web-accessibility/"><u>The Rise of GPT Bot: Insights Into Its Impact on Web Accessibility</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-science-behind-predictive-artificial-intelligence-and-its-operational-processes/"><u>The Science Behind Predictive Artificial Intelligence and Its Operational Processes</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-truth-about-chatgpt-on-windows-malware-alert-not-a-legitimate-client/"><u>The Truth About ChatGPT on Windows: Malware Alert, Not a Legitimate Client</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-4-desired-enhancements-for-the-next-generation-of-gpt-technology/"><u>Top 4 Desired Enhancements for the Next Generation of GPT Technology</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-5-unused-ai-conversation-capabilities-for-enhanced-interaction/"><u>Top 5 Unused AI Conversation Capabilities for Enhanced Interaction</u></a></li>
<li><a href="https://tech-haven.techidaily.com/translation-showdown-assessing-the-performance-of-chatgpt-vs-google-translate/"><u>Translation Showdown: Assessing the Performance of ChatGPT Vs. Google Translate</u></a></li>
<li><a href="https://tech-haven.techidaily.com/uncover-hidden-gems-discover-the-six-coolest-chatgpt-compatible-games/"><u>Uncover Hidden Gems: Discover The Six Coolest ChatGPT-Compatible Games!</u></a></li>
<li><a href="https://tech-haven.techidaily.com/understanding-ai-risks-in-financial-institutions-can-chatgpt-become-a-tool-for-hackers/"><u>Understanding AI Risks in Financial Institutions: Can ChatGPT Become a Tool for Hackers?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/understanding-artificial-intelligence-chatbot-filtering-impact-on-users/"><u>Understanding Artificial Intelligence Chatbot Filtering: Impact on Users</u></a></li>
<li><a href="https://tech-haven.techidaily.com/understanding-chatgpts-security-measures-identify-4-reasons-for-a-lockout-and-reset-techniques/"><u>Understanding ChatGPT's Security Measures: Identify 4 Reasons for a Lockout and Reset Techniques</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unearthed-secret-chat-with-chatgpt-easily/"><u>Unearthed Secret: Chat With ChatGPT Easily</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/unpacking-overcooked-2-review-gastronomic-havoc-at-its-finest/"><u>Unpacking Overcooked 2 Review: Gastronomic Havoc at Its Finest</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/visual-output-stopped-no-gpu/"><u>Visual Output Stopped, No GPU</u></a></li>
</ul></div>
