---
title: Effortless History Handling - Top 4 Extensions for GPT-3
date: 2024-09-02T12:18:01.609Z
updated: 2024-09-03T12:18:01.609Z
tags:
  - chatgpt
  - open-ai
categories:
  - openAI
  - chatgpt
description: This Article Describes Effortless History Handling - Top 4 Extensions for GPT-3
excerpt: This Article Describes Effortless History Handling - Top 4 Extensions for GPT-3
thumbnail: https://thmb.techidaily.com/c8166e8b96eec7a32e2c5447a156a34a01b3ade6d8a5a024a318a811ffe0e892.jpg
---

## Effortless Auto-GPT Installation - Follow These Steps

 With the explosion of ChatGPT, many people were impressed by the power and utility of OpenAI's GPT technology. This sparked the idea of making an automatic ChatGPT that answers and generates its prompts to achieve a specific goal, an idea that evolved into Auto-GPT.

 Since Auto-GPT is still under development, you'll only be able to access Auto-GPT just how a developer would—which may require a bit of technical know-how.

 To make things easier for you, here is a step-by-step guide on how to download and install Auto-GPT.

## Step 1: Download Python and AutoGPT

 Despite what you may have read elsewhere, installing Auto-GPT is pretty straightforward.

 Let's begin by manually downloading the latest version of Python 3 and the Auto-GPT executable from GitHub. You'll first want to download and install Python 3 since your PC will need it to read and execute files within Auto-GPT.

**Download:** [Python 3](https://www.python.org/downloads/) (Free)

 Once downloaded, double-click on the file to install Python. Make sure to tick the box for**Add python.exe to PATH** . This will enable your PC to use Python anywhere in your PC. After that, go ahead and click**Install Now** .

![A tab showing a tab to install Python ](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/2-install-python.jpg)

After Installing Python, you can download Auto-GPT from GitHub.

**Download** :[Auto-GPT](https://github.com/Significant-Gravitas/Auto-GPT/releases/tag/v0.4.7) (Free)

**Source code.zip** is for Windows, while**Source code.tar.gz** is for Linux and MacOS. First, download the file for your operating system, then copy the folder and paste it into your desired location.

## Step 2: Configure Auto-GPT

 Since AutoGPT uses OpenAI's GPT model, you must generate an API key from OpenAI to act as your credential to use their product.

 Keep in mind that your account on ChatGPT is different from an OpenAI account. You must[register for an OpenAI account](https://openai.com/blog/openai-api) to access an OpenAI API. Now:

1. After registration and login, click on**Personal** in the top right corner of the website and select**View API keys** . This will send you to the[OpenAI API keys management](https://platform.openai.com/account/api-keys) , where you can manage your API keys.
2. To create a key, click**Create new secret key** , input a name, then click**Create secret key** . You can then copy the API key by using**CTRL + C** or clicking the copy icon on the right.  
![Create API key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/7-create-test-key.jpg)
3. Now you have your API key, go to your Auto-GPT folder and open the**.env** file using Notepad.  
![Open env with Notepad](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/6-open-env.jpg)
4. Once opened, scroll down to the**LLM PROVIDER** section. There you will see OPENAI\_API\_KEY. Replace the placeholder with the API key you've just copied, then save the file.  
![Set API as environment variable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/wrwe.jpg)

 This file is where all your service credentials are placed, so if you want to use a[backend vector database to boost AI](https://www.makeuseof.com/what-is-a-vector-database/) , you can set your product API keys here. But if you only want to use AutoGPT, the OpenAI API key should be enough.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
## Step 3: Install Auto-GPT Dependencies

 Now that you have configured Auto-GPT, it's time to install its dependencies through a terminal.

1. To open a terminal in the Auto-GPT environment, right-click on the Auto-GPT folder, then select**Open in Terminal** .
2. To install all the requirements needed for Auto-GPT to work, use the command:  
pip install -r requirements.txt
3. Once you press enter, your terminal will download and install all the required dependencies.  
![Pip install requirements](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/3-4.jpg)
4. After installation, try opening Auto-GPT using:  
python -m autogpt  
![AutoGPT installation success](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/4-4.jpg)

Congratulations! You have successfully Installed Auto-GPT.

## How to Use Auto-GPT

 Now that you have successfully installed Auto-GPT on your computer let's discuss how to use Auto-GPT.

 When you first open Auto-GPT, you'll be given two options: Manual or Automatic mode. Automatic mode is the default mode where you'll only need to input what you want to be achieved. In this mode, AutoGPT will automatically assign the name of your AI assistant, its role, and its goals. Use this mode if you're not particularly knowledgeable about the process of achieving your goal.

 But if you are knowledgeable, we suggest you use the Manual mode. This ensures that your goals are properly detailed, which makes the output more likely to mirror your expectations. To activate this mode, use the command:

--manual

 After setting AutoGPT on Manual mode, it will ask you to name your AI assistant, then assign its role and five goals the AI should follow.

 You can input any name you want. It doesn't affect Auto-GPT performance (as far as we know). After giving a name, try providing a clear and concise role, as this will set the AI's role.

 Although you don't need to fill all five goals, it is still recommended that you do, as this will likely affect the efficiency of your AI.

![Creating Recipe-Generator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/recipe-generator.jpg)

 In this example, we have named our AI assistant "Recipe-Generator." Its role is to make a recipe based on the top five ingredients readily available in the US. We've set the first three goals as parameters on what we expect the recipe will be and set the last two to tell Auto-GPT to save the file as TXT, then shutdown.

![Running Recipe-Generator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/2-recipe-generator-thinking.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
Once you give your last goal, you can hit enter for Auto-GPT to run.

 While running, you can see the AI's thoughts, reasoning, plan, and criticism. For every action of the AI assistant, you will be asked to authorize its plan to execute. You can do so by typing "y" as yes.

 If you want the AI to continue a number of times without asking you for authorization, you can type "y -(number actions authorized)." For example, if you want your AI assistant to continue executing the following five steps, you can type "y -5" and hit enter.

 One advantage of Auto-GPT over ChatGPT is that it is free to probe through the internet. As you can see here, our Recipe-Generator assistant downloads a file.

![AutoGPT downloading file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/3-recipe-generator.jpg)

 This makes this[AI potentially dangerous](https://www.makeuseof.com/what-is-ai-what-dangers-does-artificial-intelligence-pose/) ; that's why Auto-GPT always asks you for authorization before executing plans. Always read and understand your AI assistant's thoughts, reasoning, and plan before authorizing its actions.

 After every action of the AI, you can also provide your feedback to help the AI with its task.

![Providing human input](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/4-recipe-generator-human-interaction.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
 In this screenshot, our AI assistant has looped through the same step three times. So, we tell the AI to skip browsing for recipes and start creating the output.

After making the recipe, our AI has now completed its task.

![Shutting down Auto-GPT](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/6-1.jpg)

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
 To view the output, go to your Auto-GPT folder and**open auto-gpt-workspace** .

![Viewing-AutoGPT-Output](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/7-1.jpg)

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Success! Our AI assistant has given us a recipe for a chicken pot pie casserole.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
## Auto-GPT Limitations

 Although Auto-GPT's automation works, it's still quite limited. Through a series of testing, we discovered that Auto-GPT couldn't handle anything complex. Most of the time, it continued looping around the same thought and reasoning. Although you can keep providing helpful prompts, it feels more like ChatGPT stuck in a loop instead of the autonomous assistant it is meant to be.

 Many of these loopings are caused by an endless cycle of generating prompts for a problem, querying the internet about the problem, identifying what is true from false, then trying to solve the problem with the information gathered.

 The problem with Generative Pre-trained Models is that they are expected to hallucinate occasionally ([AI hallucination refers to an AI tool outputting false information](https://www.makeuseof.com/what-is-ai-hallucination-and-how-do-you-spot-it/) but presenting it as fact). If the GPT model hallucinates, Auto-GPT will likely continue looping as it looks to solve problems generated from false info. The more complex the problem is, the more likely that Auto-GPT and similar programs will get stuck in this loop.

 Other problems that contribute to Auto-GPT getting stuck are the model struggling to handle or navigate website advertising and cookies, login pages, and all kinds of pop-ups (the stuff humans hate, too!).

 Using GPT-4 will noticeably reduce hallucinations and improve overall performance. However, its context size is still limited to 8,000 tokens. After reaching the 8k-token mark, GPT-4 will start losing context starting from the beginning of the task, affecting results. Furthermore, using GPT-4 is several times pricier than GPT-3.5 ([each GPT token has a cost](https://www.makeuseof.com/what-is-chatgpt-token-limit-can-you-exceed-it/) ). You'll want to set limits through your API account.

## The Future of Auto-GPT

 Ever since the start of August 2023, the Auto-GPT GitHub project has continuously gained support gaining over 140,000 GitHub Starts. Developments and updates don't seem to be slowing down. Future developments are expected to provide more functionalities, bug fixes, and improved stability in conjunction with the release of GPT-4 and its 32K model.

 With that said, Auto-GPT is still in its early development stage, and GPT-4 is still on its 8k model. As for now, Auto-GPT should not be used as a tool for any professional or business applications. Anyone using it should only be for the purpose of learning and experimentation.


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
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-uncovering-true-reflection-in-distorted-facebook-video/"><u>[New] 2024 Approved  Uncovering True Reflection in Distorted Facebook Video</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-beat-coffee-stain-effects-with-ioss-complimentary-red-eye-fix-app/"><u>[New] Beat Coffee Stain Effects with iOS's Complimentary Red-Eye Fix App</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-instagram-slideshow-feature/"><u>[New] In 2024, Instagram Slideshow Feature</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-scrutinizing-hdr-performance-in-luminance-tech/"><u>[New] Scrutinizing HDR Performance in Luminance Tech</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-frolicsome-user-enrollment-process/"><u>[Updated] Frolicsome User Enrollment Process</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-seamless-guest-entry-into-your-peers-tiktok-lives/"><u>[Updated] Seamless Guest Entry Into Your Peers' TikTok Lives</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-power-of-symbolism-in-crafting-effective-podcast-logos/"><u>[Updated] The Power of Symbolism in Crafting Effective Podcast Logos</u></a></li>
<li><a href="https://tech-haven.techidaily.com/avoiding-content-creation-missteps-use-of-chatgpt/"><u>Avoiding Content Creation Missteps: Use of ChatGPT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/best-ai-bots-face-off-which-one-takes-the-crown-in-handling-same-creative-prompt/"><u>Best AI Bots Face Off! Which One Takes the Crown in Handling Same Creative Prompt?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/boosting-content-extraction-from-pdfs-via-chatgpt-techniques/"><u>Boosting Content Extraction From PDFs via ChatGPT Techniques</u></a></li>
<li><a href="https://tech-haven.techidaily.com/chatgpt-plus-unveiled-weighing-its-advantages-and-disadvantages/"><u>ChatGPT Plus Unveiled: Weighing Its Advantages and Disadvantages</u></a></li>
<li><a href="https://tech-haven.techidaily.com/choosing-between-copybot-basic-and-pro-key-features-compared/"><u>Choosing Between Copybot Basic & Pro: Key Features Compared</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/complete-guide-updating-and-downloading-insignia-bluetooth-adapter-drivers-on-windows-systems/"><u>Complete Guide: Updating and Downloading Insignia Bluetooth Adapter Drivers on Windows Systems</u></a></li>
<li><a href="https://tech-haven.techidaily.com/decoding-chatgpts-business-centric-features/"><u>Decoding ChatGPT's Business-Centric Features</u></a></li>
<li><a href="https://tech-haven.techidaily.com/discover-how-copilot-revolutionizes-free-access-with-ultimate-gpt-4-turbo/"><u>Discover How Copilot Revolutionizes Free Access with Ultimate GPT-4 Turbo</u></a></li>
<li><a href="https://tech-haven.techidaily.com/discover-the-best-7-no-cost-ai-journey-planners-with-chatgpt-for-quick-travel-schemes/"><u>Discover the Best 7 No-Cost AI Journey Planners with ChatGPT for Quick Travel Schemes</u></a></li>
<li><a href="https://tech-haven.techidaily.com/eager-for-a-chatgpt-like-experience-on-your-pc-discover-this-top-rated-open-source-option/"><u>Eager For a ChatGPT-Like Experience on Your PC? Discover This Top-Rated Open Source Option!</u></a></li>
<li><a href="https://tech-haven.techidaily.com/elevate-your-company-with-these-8-innovative-applications-of-chatgpt/"><u>Elevate Your Company with These 8 Innovative Applications of ChatGPT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/enhancing-virtual-meetings-with-ai-the-role-of-chatgpt-in-team-engagement/"><u>Enhancing Virtual Meetings with AI: The Role of ChatGPT in Team Engagement</u></a></li>
<li><a href="https://tech-haven.techidaily.com/evaluating-cgps-precision-and-reliability-in-health-info/"><u>Evaluating CGP's Precision and Reliability in Health Info</u></a></li>
<li><a href="https://tech-haven.techidaily.com/exploring-the-capabilities-of-ai-assistant-claude-3/"><u>Exploring the Capabilities of AI-Assistant, Claude 3</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/exploring-the-eye-catching-aesthetics-of-the-new-galaxy-tab-s9-series-are-they-worth-their-cost/"><u>Exploring the Eye-Catching Aesthetics of the New Galaxy Tab S9 Series - Are They Worth Their Cost?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/financial-wisdom-in-emojis-cybersecurity-scare-with-activision-and-the-rise-of-gpt-job-displacement/"><u>Financial Wisdom in Emojis? Cybersecurity Scare with Activision & the Rise of GPT Job Displacement</u></a></li>
<li><a href="https://win-amazing.techidaily.com/free-download-focusrite-scarlett-2i2-windows-audio-interface-and-plug-ins/"><u>Free Download: Focusrite Scarlett 2I2 Windows Audio Interface & Plug-Ins</u></a></li>
<li><a href="https://tech-haven.techidaily.com/freelancers-guide-to-selecting-a-bot-is-bing-or-gpt-3-better/"><u>Freelancer's Guide to Selecting a Bot: Is Bing or GPT-3 Better?</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-teleport-your-gps-location-on-vivo-y17s-drfone-by-drfone-virtual-android/"><u>How To Teleport Your GPS Location On Vivo Y17s? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-best-ways-on-how-to-unlockbypassswiperemove-vivo-y02t-fingerprint-lock-by-drfone-android/"><u>In 2024, Best Ways on How to Unlock/Bypass/Swipe/Remove Vivo Y02T Fingerprint Lock</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-beyond-the-surface-10-under-the-radar-facts-about-reels/"><u>In 2024, Beyond the Surface  10 Under-the-Radar Facts About Reels</u></a></li>
<li><a href="https://tech-haven.techidaily.com/inside-look-the-revolutionary-ai-features-introduced-by-apple-during-the-wwdc-event-of-2024/"><u>Inside Look: The Revolutionary AI Features Introduced by Apple During the WWDC Event of 2024</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/install-the-most-recent-drivers-for-your-hp-network-adapter-supports-win11win7win8/"><u>Install the Most Recent Drivers for Your HP Network Adapter: Supports Win11/Win7/Win8</u></a></li>
<li><a href="https://tech-haven.techidaily.com/master-the-art-of-business-communication-using-these-5-free-ai-platforms-generate-sophisticated-emails-and-summarize-inboxes-with-chatgpt/"><u>Master the Art of Business Communication: Using These 5 FREE AI Platforms, Generate Sophisticated Emails & Summarize Inboxes With ChatGPT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-ai-defense-nightshade-for-authentic-art-preservation/"><u>Mastering AI Defense: Nightshade for Authentic Art Preservation</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-ai-safely-the-top-six-warnings-to-heed/"><u>Navigating AI Safely: The Top Six Warnings to Heed</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-the-landscape-of-generative-ai-uncovering-its-functionality-and-prominent-business-users/"><u>Navigating the Landscape of Generative AI – Uncovering Its Functionality & Prominent Business Users</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-the-pros-and-cons-of-auto-gpt-without-gpt-4-integration/"><u>Navigating the Pros and Cons of Auto-GPT Without GPT-4 Integration</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-the-use-of-gpt-3-at-openai-playground/"><u>Navigating the Use of GPT-3 at OpenAI Playground</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-the-world-of-artificial-intelligence-an-ultimate-guide-to-29-essential-jargon-and-abbreviations/"><u>Navigating the World of Artific#ial Intelligence: An Ultimate Guide to 29 Essential Jargon and Abbreviations</u></a></li>
<li><a href="https://tech-haven.techidaily.com/next-level-viewing-deciding-your-tv-lineup-with-chatgpt/"><u>Next-Level Viewing: Deciding Your TV Lineup with ChatGPT</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/pioneering-ig-video-influence-crafting-an-excellent-marketing-plan/"><u>Pioneering IG Video Influence  Crafting an Excellent Marketing Plan</u></a></li>
<li><a href="https://tech-haven.techidaily.com/safety-of-external-chatgpt-modules-and-browser-extensions-what-do-experts-say/"><u>Safety of External ChatGPT Modules and Browser Extensions: What Do Experts Say?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-ultimate-guide-to-free-open-source-ai-picture-makers/"><u>The Ultimate Guide to Free, Open Source AI Picture Makers</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/things-you-should-know-when-unlocking-total-wireless-of-apple-iphone-12-by-drfone-ios/"><u>Things You Should Know When Unlocking Total Wireless Of Apple iPhone 12</u></a></li>
<li><a href="https://tech-haven.techidaily.com/tips-and-tricks-to-seamlessly-insert-your-own-gpt-mentions-into-chatgpt-exchanges-for-optimal-engagement/"><u>Tips and Tricks to Seamlessly Insert Your Own GPT Mentions Into ChatGPT Exchanges for Optimal Engagement</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-4-artificial-intelligence-strategies-to-boost-academic-study/"><u>Top 4 Artificial Intelligence Strategies to Boost Academic Study</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-5-methods-how-you-can-use-gpt-4-at-no-cost/"><u>Top 5 Methods: How You Can Use GPT-4 at No Cost</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-5-strategies-for-crafting-successful-gpt-3-prompts-achieve-optimal-ai-responses/"><u>Top 5 Strategies for Crafting Successful GPT-3 Prompts: Achieve Optimal AI Responses</u></a></li>
<li><a href="https://tech-haven.techidaily.com/trustworthy-health-insights-ensuring-accuracy-when-interacting-with-chatgpt-and-similar-tools/"><u>Trustworthy Health Insights: Ensuring Accuracy when Interacting with ChatGPT & Similar Tools</u></a></li>
<li><a href="https://tech-haven.techidaily.com/understanding-chatgpt-exploring-the-safety-and-addressing-potential-cybersecurity-threats/"><u>Understanding ChatGPT: Exploring the Safety and Addressing Potential Cybersecurity Threats</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unlocking-efficiency-with-claude-3-why-it-beats-chatgpt-on-all-fronts-revealed/"><u>Unlocking Efficiency with Claude 3 - Why It Beats ChatGPT on All Fronts (Revealed)</u></a></li>
</ul></div>
