---
title: Step by Step Instructions on How to Get and Set Up Auto-GPT Software
date: 2024-08-16T11:11:11.028Z
updated: 2024-08-17T11:11:11.028Z
tags:
  - chatgpt
  - open-ai
categories:
  - openAI
  - chatgpt
description: This Article Describes Step by Step Instructions on How to Get and Set Up Auto-GPT Software
excerpt: This Article Describes Step by Step Instructions on How to Get and Set Up Auto-GPT Software
thumbnail: https://thmb.techidaily.com/848032c0813eed1e619997cdd0bea2d2fe7603582b1ae72dd2c30508b513eea6.png
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

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
![A tab showing a tab to install Python ](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/2-install-python.jpg)

After Installing Python, you can download Auto-GPT from GitHub.

**Download** :[Auto-GPT](https://github.com/Significant-Gravitas/Auto-GPT/releases/tag/v0.4.7) (Free)

**Source code.zip** is for Windows, while**Source code.tar.gz** is for Linux and MacOS. First, download the file for your operating system, then copy the folder and paste it into your desired location.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Step 2: Configure Auto-GPT

 Since AutoGPT uses OpenAI's GPT model, you must generate an API key from OpenAI to act as your credential to use their product.

 Keep in mind that your account on ChatGPT is different from an OpenAI account. You must[register for an OpenAI account](https://openai.com/blog/openai-api) to access an OpenAI API. Now:

1. After registration and login, click on**Personal** in the top right corner of the website and select**View API keys** . This will send you to the[OpenAI API keys management](https://platform.openai.com/account/api-keys) , where you can manage your API keys.
2. To create a key, click**Create new secret key** , input a name, then click**Create secret key** . You can then copy the API key by using**CTRL + C** or clicking the copy icon on the right.  
![Create API key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/7-create-test-key.jpg)
3. Now you have your API key, go to your Auto-GPT folder and open the**.env** file using Notepad.  
<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Open env with Notepad](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/6-open-env.jpg)
4. Once opened, scroll down to the**LLM PROVIDER** section. There you will see OPENAI\_API\_KEY. Replace the placeholder with the API key you've just copied, then save the file.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
![Set API as environment variable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/wrwe.jpg)

 This file is where all your service credentials are placed, so if you want to use a[backend vector database to boost AI](https://www.makeuseof.com/what-is-a-vector-database/) , you can set your product API keys here. But if you only want to use AutoGPT, the OpenAI API key should be enough.

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![Running Recipe-Generator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/2-recipe-generator-thinking.jpg)

Once you give your last goal, you can hit enter for Auto-GPT to run.

 While running, you can see the AI's thoughts, reasoning, plan, and criticism. For every action of the AI assistant, you will be asked to authorize its plan to execute. You can do so by typing "y" as yes.

 If you want the AI to continue a number of times without asking you for authorization, you can type "y -(number actions authorized)." For example, if you want your AI assistant to continue executing the following five steps, you can type "y -5" and hit enter.

 One advantage of Auto-GPT over ChatGPT is that it is free to probe through the internet. As you can see here, our Recipe-Generator assistant downloads a file.

![AutoGPT downloading file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/3-recipe-generator.jpg)

 This makes this[AI potentially dangerous](https://www.makeuseof.com/what-is-ai-what-dangers-does-artificial-intelligence-pose/) ; that's why Auto-GPT always asks you for authorization before executing plans. Always read and understand your AI assistant's thoughts, reasoning, and plan before authorizing its actions.

 After every action of the AI, you can also provide your feedback to help the AI with its task.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->
![Providing human input](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/4-recipe-generator-human-interaction.jpg)

 In this screenshot, our AI assistant has looped through the same step three times. So, we tell the AI to skip browsing for recipes and start creating the output.

After making the recipe, our AI has now completed its task.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->
![Shutting down Auto-GPT](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/6-1.jpg)

 To view the output, go to your Auto-GPT folder and**open auto-gpt-workspace** .

<!-- affiliate ads begin -->
<a href="https://martinic.evyy.net/c/5597632/1422856/4482" target="_top" id="1422856"><img src="//a.impactradius-go.com/display-ad/4482-1422856" border="0" alt="" width="580" height="309"/></a>
<!-- affiliate ads end -->
![Viewing-AutoGPT-Output](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/7-1.jpg)

 Success! Our AI assistant has given us a recipe for a chicken pot pie casserole.

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
<li><a href="https://vimeo-videos.techidaily.com/new-conquered-by-creatives-from-wmm-to-a-stellar-vimeo-presence-for-2024/"><u>[New] Conquered By Creatives  From WMM to a Stellar Vimeo Presence for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-exploring-media-top-ranking-camera-apps-for-iphonesandroid-devices/"><u>[New] Exploring Media  Top-Ranking Camera Apps for iPhones/Android Devices</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-mastering-instagram-launch-your-live-session-for-2024/"><u>[New] Mastering Instagram  Launch Your Live Session for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-the-ultimate-checklist-for-achieving-high-quality-vocal-recordings/"><u>[New] The Ultimate Checklist for Achieving High-Quality Vocal Recordings</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-8-key-money-making-moves-for-youtube-rookies-for-2024/"><u>[Updated] 8 Key Money-Making Moves for YouTube Rookies for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-fix-zoo-membership-tackling-poor-sound-quality/"><u>[Updated] Fix Zoo Membership  Tackling Poor Sound Quality</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-precision-editing-perfecting-the-art-of-fades-in-pro/"><u>[Updated] Precision Editing  Perfecting the Art of Fades in Pro</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-unveiling-filmoras-most-attractive-edits/"><u>[Updated] Unveiling Filmora's Most Attractive Edits</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-visuallyvivid-adjust-your-content-for-instagram-success-for-2024/"><u>[Updated] VisuallyVivid  Adjust Your Content for Instagram Success for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/complete-understanding-of-srt-covering-everything-important/"><u>Complete Understanding of SRT, Covering Everything Important</u></a></li>
<li><a href="https://extra-resources.techidaily.com/crafting-a-harmonic-narrative-adding-youtube-music-to-vids/"><u>Crafting a Harmonic Narrative  Adding YouTube Music to Vids</u></a></li>
<li><a href="https://screen-recording.techidaily.com/guide-to-effective-nvidia-video-capture-for-2024/"><u>Guide to Effective NVIDIA Video Capture for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/has-chatgpt-simplified-or-compromised-academic-writings/"><u>Has ChatGPT Simplified or Compromised Academic Writings?</u></a></li>
<li><a href="https://extra-information.techidaily.com/herocam-pro-mastering-advanced-features/"><u>HeroCam Pro  Mastering Advanced Features</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-chatgpt-empowers-you-to-pen-down-beautiful-poetry-tips-and-tricks/"><u>How ChatGPT Empowers You to Pen Down Beautiful Poetry: Tips & Tricks</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-does-shapley-explanation-work-insights-into-openais-shape-technology/"><u>How Does Shapley Explanation Work? Insights Into OpenAI's SHAPE Technology</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-learning-chatgpt-can-transform-your-career-a-six-point-guide/"><u>How Learning ChatGPT Can Transform Your Career: A Six-Point Guide</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-the-introduction-of-chatgpt-and-whisper-api-endpoints-impacts-your-business-strategy/"><u>How the Introduction of ChatGPT and Whisper API Endpoints Impacts Your Business Strategy</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-to-access-and-utilize-the-smart-search-engine-bing/"><u>How to Access and Utilize the Smart Search Engine - Bing</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-frp-on-realme-v30-by-drfone-android/"><u>How to Bypass FRP on Realme V30?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/immersive-tabletop-journeys-gpt-insights-to-elevate-your-rpgs/"><u>Immersive Tabletop Journeys: GPT Insights to Elevate Your RPGs</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-realme-narzo-60x-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Realme Narzo 60x 5G | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-in-the-front-row-ranked-no-8-image-synthesis-app/"><u>In 2024, In the Front Row  Ranked No. 8 Image Synthesis App</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-two-ways-to-track-my-boyfriends-motorola-moto-g-stylus-2023-without-him-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, Two Ways to Track My Boyfriends Motorola Moto G Stylus (2023) without Him Knowing | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/innovative-extensions-for-exporting-and-sharing-conversations-from-chatgpt/"><u>Innovative Extensions for Exporting & Sharing Conversations From ChatGPT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/intelligent-engagement-siri-and-chatgpt-for-apple-users/"><u>Intelligent Engagement: Siri & ChatGPT for Apple Users</u></a></li>
<li><a href="https://tech-haven.techidaily.com/must-try-the-best-4-ai-powered-storytelling-apps-of-the-year/"><u>Must-Try: The Best 4 AI Powered Storytelling Apps of the Year</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-the-new-era-of-work-generative-ais-sevenfold-impact-on-employment-landscapes/"><u>Navigating the New Era of Work: Generative AI's Sevenfold Impact on Employment Landscapes</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-the-truth-how-to-authenticate-health-advice-sourced-from-ai-like-chatgpt/"><u>Navigating the Truth: How to Authenticate Health Advice Sourced From AI Like ChatGPT</u></a></li>
<li><a href="https://vp-tips.techidaily.com/precision-review-of-elite-parrots-ar-model-20/"><u>Precision Review of Elite Parrot's AR Model 2.0</u></a></li>
<li><a href="https://tech-haven.techidaily.com/scripting-success-how-chatgpt-transformed-my-podcast-creation-process/"><u>Scripting Success: How ChatGPT Transformed My Podcast Creation Process</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/social-media-best-practices-uploading-and-displaying-subtitles-for-2024/"><u>Social Media Best Practices  Uploading and Displaying Subtitles for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/step-by-step-guide-activating-your-account-on-bings-ai-enhanced-search-platform/"><u>Step-by-Step Guide: Activating Your Account on Bing's AI-Enhanced Search Platform</u></a></li>
<li><a href="https://tech-haven.techidaily.com/steps-for-identifying-fake-chatgpt-websites-and-action-plan-when-found/"><u>Steps for Identifying Fake ChatGPT Websites & Action Plan When Found</u></a></li>
<li><a href="https://tech-haven.techidaily.com/streamlining-your-interactions-leveraging-chatgpt-folders-for-efficient-conversation-control/"><u>Streamlining Your Interactions: Leveraging ChatGPT Folders for Efficient Conversation Control</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-art-of-custom-ai-crafting-chatgpt-from-scratch/"><u>The Art of Custom AI: Crafting ChatGPT From Scratch</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-evolution-of-academic-writing-are-ai-solutions-like-chatgpt-redefining-how-students-write-essays/"><u>The Evolution of Academic Writing: Are AI Solutions Like ChatGPT Redefining How Students Write Essays?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-impact-of-emoji-communication-on-personal-investment-strategies/"><u>The Impact of Emoji Communication on Personal Investment Strategies</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-pitfalls-of-relying-on-ai-for-identifying-copied-online-text-an-urgent-issue/"><u>The Pitfalls of Relying on AI for Identifying Copied Online Text - An Urgent Issue</u></a></li>
<li><a href="https://tech-haven.techidaily.com/thought-innovation-ai-mindmaps-for-ideas/"><u>Thought Innovation: AI, Mindmaps for Ideas</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-10-tech-thinkers-debate-the-ai-landscape/"><u>Top 10 Tech Thinkers Debate the AI Landscape</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-6-pitfalls-in-gpt-based-dialogues/"><u>Top 6 Pitfalls in GPT-Based Dialogues</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/unboxing-flight-comprehensive-guide-to-dji-phantom-4-for-2024/"><u>Unboxing Flight  Comprehensive Guide to DJI Phantom 4 for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/update-twitter-video-preview/"><u>Update Twitter Video Preview</u></a></li>
</ul></div>
