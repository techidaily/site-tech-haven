---
title: "Mobile GPT: Rethink Your Downloading Decision"
date: 2024-09-02T12:18:56.420Z
updated: 2024-09-03T12:18:56.420Z
tags:
  - chatgpt
  - open-ai
categories:
  - openAI
  - chatgpt
description: "This Article Describes Mobile GPT: Rethink Your Downloading Decision"
excerpt: "This Article Describes Mobile GPT: Rethink Your Downloading Decision"
thumbnail: https://thmb.techidaily.com/9d8448293885018e42ea0c2c618da231bf75f85bd2fb228b8b71882f24dcc32a.jpg
---

## Easy Steps to Get Started with Auto-GPT: Downloading and Installing Made Simple

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
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->
 In this example, we have named our AI assistant "Recipe-Generator." Its role is to make a recipe based on the top five ingredients readily available in the US. We've set the first three goals as parameters on what we expect the recipe will be and set the last two to tell Auto-GPT to save the file as TXT, then shutdown.

![Running Recipe-Generator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/2-recipe-generator-thinking.jpg)

Once you give your last goal, you can hit enter for Auto-GPT to run.

 While running, you can see the AI's thoughts, reasoning, plan, and criticism. For every action of the AI assistant, you will be asked to authorize its plan to execute. You can do so by typing "y" as yes.

 If you want the AI to continue a number of times without asking you for authorization, you can type "y -(number actions authorized)." For example, if you want your AI assistant to continue executing the following five steps, you can type "y -5" and hit enter.

 One advantage of Auto-GPT over ChatGPT is that it is free to probe through the internet. As you can see here, our Recipe-Generator assistant downloads a file.

![AutoGPT downloading file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/3-recipe-generator.jpg)

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
 This makes this[AI potentially dangerous](https://www.makeuseof.com/what-is-ai-what-dangers-does-artificial-intelligence-pose/) ; that's why Auto-GPT always asks you for authorization before executing plans. Always read and understand your AI assistant's thoughts, reasoning, and plan before authorizing its actions.

 After every action of the AI, you can also provide your feedback to help the AI with its task.

![Providing human input](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/4-recipe-generator-human-interaction.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4708689&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Win： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
 In this screenshot, our AI assistant has looped through the same step three times. So, we tell the AI to skip browsing for recipes and start creating the output.

After making the recipe, our AI has now completed its task.

![Shutting down Auto-GPT](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/6-1.jpg)

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 To view the output, go to your Auto-GPT folder and**open auto-gpt-workspace** .

![Viewing-AutoGPT-Output](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/7-1.jpg)

 Success! Our AI assistant has given us a recipe for a chicken pot pie casserole.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-recording.techidaily.com/new-unraveling-the-mystery-of-online-video-sharing-for-2024/"><u>[New] Unraveling the Mystery of Online Video Sharing for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-get-ahead-in-call-capturing-20plus-techniques-for-windowsmac-users-for-2024/"><u>[Updated] Get Ahead in Call Capturing  20+ Techniques for Windows/Mac Users for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-ski-and-snow-gear-best-cams-compiled-in-7-lists/"><u>[Updated] In 2024, Ski and Snow Gear  Best Cams Compiled in 7 Lists</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-mastering-the-art-of-restoring-past-reddit-articles-for-2024/"><u>[Updated] Mastering the Art of Restoring Past Reddit Articles for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-picturesegment-appraisal/"><u>2024 Approved  PictureSegment Appraisal</u></a></li>
<li><a href="https://tech-haven.techidaily.com/chatgpt-plus-a-cost-benefit-analysis/"><u>ChatGPT Plus: A Cost-Benefit Analysis</u></a></li>
<li><a href="https://tech-haven.techidaily.com/customizing-ai-conversations-discover-the-latest-update-in-chatgpt-for-personalized-gpt-models/"><u>Customizing AI Conversations: Discover the Latest Update in ChatGPT for Personalized GPT Models</u></a></li>
<li><a href="https://tech-haven.techidaily.com/digital-dexterity-ai-comedy-and-laptop-legacy-unveiled/"><u>Digital Dexterity: AI Comedy & Laptop Legacy Unveiled</u></a></li>
<li><a href="https://tech-haven.techidaily.com/dissecting-hugging-faces-purpose-in-ai/"><u>Dissecting Hugging Face's Purpose in AI</u></a></li>
<li><a href="https://tech-haven.techidaily.com/dont-lose-it-again-how-to-restore-your-missing-chatgpt-history/"><u>Don't Lose It Again! How to Restore Your Missing ChatGPT History</u></a></li>
<li><a href="https://tech-haven.techidaily.com/embracing-ai-assisted-advice-with-top-7-reasons/"><u>Embracing AI-Assisted Advice with Top 7 Reasons</u></a></li>
<li><a href="https://tech-haven.techidaily.com/engaging-with-algorithms-mistrals-encounter-with-chatgpt/"><u>Engaging with Algorithms: Mistral's Encounter With ChatGPT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/generative-ai-and-its-seven-game-changing-effects-on-the-labor-market/"><u>Generative AI and Its Seven Game-Changing Effects on the Labor Market</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-samsung-galaxy-s23-ultra-frp-in-3-different-ways-by-drfone-android/"><u>How To Bypass Samsung Galaxy S23 Ultra FRP In 3 Different Ways</u></a></li>
<li><a href="https://tech-haven.techidaily.com/identifying-and-avoiding-bingchatgpts-fraudulent-cryptocurrency-tickets-a-comprehensive-guide/"><u>Identifying & Avoiding BingChatGPT's Fraudulent Cryptocurrency Tickets: A Comprehensive Guide</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-budding-filmmakers-best-gopro-upgrades/"><u>In 2024, Budding Filmmakers  Best GoPro Upgrades</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-top-5-samsung-galaxy-s23-ultra-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>In 2024, Top 5 Samsung Galaxy S23 Ultra Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://tech-haven.techidaily.com/maximize-your-productivity-with-these-ai-driven-chrome-addons-top-picks/"><u>Maximize Your Productivity with These AI-Driven Chrome Addons - Top Picks!</u></a></li>
<li><a href="https://extra-tips.techidaily.com/metaverse-laughs-crafting-funny-virtual-memes/"><u>Metaverse Laughs  Crafting Funny Virtual Memes</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-through-a-sea-of-ai-imagery-with-microsoft-copilot/"><u>Navigating Through a Sea of AI Imagery with Microsoft Copilot</u></a></li>
<li><a href="https://tech-haven.techidaily.com/potential-weaknesses-in-chatgpts-security/"><u>Potential Weaknesses in ChatGPT’s Security</u></a></li>
<li><a href="https://tech-haven.techidaily.com/revolutionizing-ai-how-gemini-15s-one-million-token-framework-transforms-the-industry/"><u>Revolutionizing AI: How Gemini-1.5's One Million Token Framework Transforms the Industry</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/sim-unlock-vivo-v27-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>Sim Unlock Vivo V27 Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://tech-haven.techidaily.com/simplifying-sticker-setup-challenges-resolving-top-6-problems-quickly/"><u>Simplifying Sticker Setup Challenges: Resolving Top 6 Problems Quickly</u></a></li>
<li><a href="https://tech-haven.techidaily.com/smarter-solutions-discover-your-8-ai-matches-now/"><u>Smarter Solutions: Discover Your 8 AI Matches Now</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-era-of-automated-writing-is-the-classic-student-essay-a-thing-of-the-past-due-to-innovations-like-chatgpt/"><u>The Era of Automated Writing: Is the Classic Student Essay a Thing of the Past Due to Innovations Like ChatGPT?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-pros-and-cons-of-prompt-engineering-as-a-job-understanding-its-legitimacy-with-key-indicators/"><u>The Pros and Cons of Prompt Engineering as a Job: Understanding Its Legitimacy with Key Indicators</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-6-tools-interacting-with-text-in-pdfs-and-docs-through-conversational-ai/"><u>Top 6 Tools: Interacting with Text in PDFs & Docs Through Conversational AI</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-ai-innovations-every-entrepreneur-must-learn-about-today/"><u>Top AI Innovations Every Entrepreneur Must Learn About Today</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unleash-your-creativity-with-5-outstanding-free-ai-photo-generators-available-now/"><u>Unleash Your Creativity with 5 Outstanding Free AI Photo Generators Available Now</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unveiling-the-truth-about-ai-hallucinations-detection-techniques-explored/"><u>Unveiling the Truth About AI Hallucinations: Detection Techniques Explored</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-2024-approved-procuring-growls-and-whispers-audio-packages/"><u>Updated 2024 Approved Procuring Growls and Whispers Audio Packages</u></a></li>
<li><a href="https://tech-haven.techidaily.com/vocal-command-unleashing-the-power-of-chatgpt-with-just-your-voice/"><u>Vocal Command: Unleashing the Power of ChatGPT with Just Your Voice</u></a></li>
<li><a href="https://tech-haven.techidaily.com/why-the-chatgpt-mobile-app-outshines-its-web-counterpart-a-comprehensive-guide/"><u>Why the ChatGPT Mobile App Outshines Its Web Counterpart: A Comprehensive Guide</u></a></li>
</ul></div>
