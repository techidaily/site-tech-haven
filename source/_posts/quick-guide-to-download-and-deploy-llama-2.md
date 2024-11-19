---
title: Quick Guide to Download & Deploy Llama 2
date: 2024-11-13T22:08:57.249Z
updated: 2024-11-19T00:08:42.313Z
tags:
  - chatgpt
  - open-ai
categories:
  - openAI
  - chatgpt
description: This Article Describes Quick Guide to Download & Deploy Llama 2
excerpt: This Article Describes Quick Guide to Download & Deploy Llama 2
thumbnail: https://thmb.techidaily.com/3d656cbcb6ed3f0737e87c15dfee4b95bfd8fca2d1ffd5bcbe3ae82b87b12f89.jpg
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
![Install-Desktop-Development-With-C++](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/2-install-desktop-development-with-c.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135354/19272" target="_top" id="2135354">
  <img src="//a.impactradius-go.com/display-ad/19272-2135354" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135354/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now that you have Desktop development with C++ installed, it's time to download the Text-Generation-WebUI one-click installer.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135393/19272" target="_top" id="2135393">
  <img src="//a.impactradius-go.com/display-ad/19272-2135393" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135393/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
![How to launch-Text-Generation-WebUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/6-launch-text-generation-webui.jpg)
6. The WebUI is now ready for use.  
![Text-Generation-WebUI ](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/7-text-generation-webui-view.jpg)

 However, the program is only a model loader. Let's download Llama 2 for the model loader to launch.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137413/7443" target="_top" id="2137413">
  <img src="//a.impactradius-go.com/display-ad/7443-2137413" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137413/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Step 3: Download the Llama 2 Model

 There are quite a few things to consider when deciding which iteration of Llama 2 you need. These include parameters, quantization, hardware optimization, size, and usage. All of this information will be found denoted in the model's name.

* **Parameters:** The number of parameters used to train the model. Bigger parameters make more capable models but at the cost of performance.
* **Usage:** Can either be standard or chat. A chat model is optimized to be used as a chatbot like ChatGPT, while the standard is the default model.
* **Hardware Optimization:** Refers to what hardware best runs the model. GPTQ means the model is optimized to run on a dedicated GPU, while GGML is optimized to run on a CPU.
* **Quantization:** Denotes the precision of weights and activations in a model. For inferencing, a precision of q4 is optimal.
* **Size:** Refers to the size of the specific model.

 Note that some models may be arranged differently and may not even have the same types of information displayed. However, this type of naming convention is fairly common in the[HuggingFace](https://www.makeuseof.com/what-is-hugging-face-and-what-is-it-used-for/) Model library, so it's still worth understanding.

![HuggingFace model naming convention](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/huggingface-model-naming-convention-1.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2016148/19272" target="_top" id="2016148">
  <img src="//a.impactradius-go.com/display-ad/19272-2016148" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016148/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In this example, the model can be identified as a medium-sized Llama 2 model trained on 13 billion parameters optimized for chat inferencing using a dedicated CPU.

 For those running on a dedicated GPU, choose a**GPTQ** model, while for those using a CPU, choose**GGML** . If you want to chat with the model like you would with ChatGPT, choose**chat** , but if you want to experiment with the model with its full capabilities, use the**standard** model. As for parameters, know that using bigger models will provide better results at the expense of performance. I would personally recommend you start with a 7B model. As for quantization, use q4, as it's only for inferencing.

**Download:** [GGML](https://huggingface.co/localmodels/Llama-2-7B-ggml/tree/main) (Free)

**Download:** [GPTQ](https://huggingface.co/localmodels/Llama-2-7B-Chat-GPTQ/tree/main) (Free)

 Now that you know what iteration of Llama 2 you need, go ahead and download the model you want.

 In my case, since I'm running this on an ultrabook, I'll be using a GGML model fine-tuned for chat,**llama-2-7b-chat-ggmlv3.q4\_K\_S.bin.**

![Downloading Llama 2 model of your preference](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/8-download-llama-2-model.jpg)

 After the download is finished, place the model in**text-generation-webui-main** \>**models** .

![Placing Llama 2 model to model folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/9-place-model-to-model-folder.jpg)

 Now that you have your model downloaded and placed in the model folder, it's time to configure the model loader.

## Step 4: Configure Text-Generation-WebUI

Now, let's begin the configuration phase.

1. Once again, open Text-Generation-WebUI by running the**start\_(your OS)** file (see the previous steps above).
2. On the tabs located above the GUI, click**Model.** Click the refresh button at the model dropdown menu and select your model.
3. Now click on the dropdown menu of the**Model loader** and select**AutoGPTQ** for those using a GTPQ model and**ctransformers** for those using a GGML model. Finally, click on**Load** to load your model.  
![Setting model loader](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/10-select-model-loader.jpg)
4. To use the model, open the Chat tab and start testing the model.  
![Testing Llama 2 locally](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/12-testing-llama-2-locally.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144275/7443" target="_top" id="2144275">
  <img src="//a.impactradius-go.com/display-ad/7443-2144275" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144275/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Congratulations, you've successfully loaded Llama2 on your local computer!

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
<li><a href="https://youtube-docs.techidaily.com/024-approved-fortnite-thumbnail-blitz-a-30-second-guide/"><u>[New] 2024 Approved Fortnite Thumbnail Blitz A 30-Second Guide</u></a></li>
<li><a href="https://fox-where.techidaily.com/boost-your-computers-precision-essential-windows-11-mouse-drivers-upgrade-guide/"><u>Boost Your Computer's Precision: Essential Windows 11 Mouse Drivers Upgrade Guide</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/complete-tutorial-on-downloading-and-installing-the-epson-es-400-scanner-for-windows-computers/"><u>Complete Tutorial on Downloading & Installing the Epson ES-400 Scanner for Windows Computers</u></a></li>
<li><a href="https://fox-metric.techidaily.com/gerez-vos-erreurs-rapides-avec-ces-9-techniques-au-volant-du-boulevard-peripherique-est-en-activite/"><u>Gérez Vos Erreurs Rapides Avec Ces 9 Techniques Au Volant Du Boulevard Périphérique Est en Activité</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-to-successfully-watch-movies-from-a-usb-drive-on-your-vizio-television/"><u>How To Successfully Watch Movies From A USB Drive On Your Vizio Television</u></a></li>
<li><a href="https://tech-haven.techidaily.com/htmlmp4/"><u>HTMLコード内動画からMP4ファイルへの変換技術</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-turn-off-google-location-to-stop-tracking-you-on-oppo-a59-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Turn Off Google Location to Stop Tracking You on Oppo A59 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-the-ultimate-hash-list-boosting-youtube-views-to-6000plus/"><u>In 2024, The Ultimate Hash List Boosting Youtube Views to $6,000+</u></a></li>
<li><a href="https://techtrends.techidaily.com/is-snappydriver-v113-worth-your-time-detailed-review-inside/"><u>Is SnappyDriver v1.13 Worth Your Time? Detailed Review Inside!</u></a></li>
<li><a href="https://win-dash.techidaily.com/latest-sapphire-driver-updates-available-now-for-windows-systems/"><u>Latest Sapphire Driver Updates Available Now for Windows Systems</u></a></li>
<li><a href="https://tech-haven.techidaily.com/m2ts3/"><u>M2TSファイルを効果的に変換するためのベストフリーソフト:お薦めランキングトップ3</u></a></li>
<li><a href="https://article-tips.techidaily.com/mastering-image-quality-a-guide-without-watermarks/"><u>Mastering Image Quality A Guide Without Watermarks</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mmf-to-mp3/"><u>MMF to MP3変換：一つの流れで理解する手引き</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mp4-video-compression-techniques-a-step-by-step-guide/"><u>MP4 Video Compression Techniques: A Step-by-Step Guide</u></a></li>
<li><a href="https://tech-haven.techidaily.com/resolving-issues-when-your-gopro-footage-refuses-to-show-up-on-windows-machine/"><u>Resolving Issues: When Your GoPro Footage Refuses to Show Up on Windows Machine</u></a></li>
<li><a href="https://tech-haven.techidaily.com/rotating-videos-with-windows-movie-maker-a-comprehensive-guide-and-alternatives-explored/"><u>Rotating Videos with Windows Movie Maker: A Comprehensive Guide and Alternatives Explored</u></a></li>
<li><a href="https://tech-haven.techidaily.com/samsung-tv-now-supports-avi-file-type-after-fix/"><u>Samsung TV Now Supports Avi File Type After Fix</u></a></li>
<li><a href="https://win-excellent.techidaily.com/schnelles-diy-befolge-diese-beiden-einfachen-methoden-um-eine-dism-offline-wiederherstellung-auf-ihrem-windows-server-2016-durchzufuhren/"><u>Schnelles DIY: Befolge Diese Beiden Einfachen Methoden, Um Eine DISM-Offline-Wiederherstellung Auf Ihrem Windows Server 2016 Durchzuführen</u></a></li>
<li><a href="https://tech-haven.techidaily.com/simple-steps-mastering-video-cropping-techniques-in-openshot-editor/"><u>Simple Steps: Mastering Video Cropping Techniques in OpenShot Editor</u></a></li>
</ul></div>

