---
title: Harnessing Quora’s POE for LLM & Chatbot Access
date: 2024-08-16T12:31:28.246Z
updated: 2024-08-17T12:31:28.246Z
tags:
  - chatgpt
  - open-ai
categories:
  - openAI
  - chatgpt
description: This Article Describes Harnessing Quora’s POE for LLM & Chatbot Access
excerpt: This Article Describes Harnessing Quora’s POE for LLM & Chatbot Access
thumbnail: https://thmb.techidaily.com/b4646e6c7dd57e63be8305e5fc613622e6d7e19134ef2ba8ba5fe989f296bf0b.png
---

## Understanding Word and Character Quotas in AI-Powered Chatbots Like GPT-3

### Key Takeaways

* ChatGPT responses are not limitless in length, despite the initial claim. There are hidden limits determined by the token system, past conversations, and system demands.
* The token system used by ChatGPT considers both the length of queries and answers. The available token lengths vary depending on the GPT model used.
* To get longer responses from ChatGPT, you can ask it to continue, break your question into smaller sections, use the regenerate option, specify a word count limit, or start a new conversation. These techniques can help you work around the unofficial limits and receive more complete answers.

 ChatGPT is big news. But how big are the responses you get from this all-purpose chatbot?

 Establishing this is not as simple as you may think. For starters, ask ChatGPT this question, and you will be assured that there are no set limits to the length of its responses.

 However, as we uncover here, it isn't that straightforward. There are hidden limits to the length of a ChatGPT response, but there are also some nifty and simple workarounds to help you get longer answers.

## How Does ChatGPT Determine the Length of a Response?

[How ChatGPT works is complex](https://www.makeuseof.com/how-does-chatgpt-work/) , and the response length varies depending on what is being asked and the level of detail requested. As the next screenshot shows, ChatGPT claims there are no strict limits.

![Screenshot of ChatGPT Declaring No Limits](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/screenshot-of-chatgpt-declaring-no-limits.jpg)

 Of course, asking ChatGPT about itself isn't a good idea since it isn't typically objective about its abilities or has limited information. So, we ran some tests to determine the length limits of ChatGPT responses. We asked the chatbot to write a 5000-word article on the history of the FIFA World Cup. ChatGPT's assessment of itself differed from the results we found.

![Asking ChatGPT to write 5000 words article](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/asking-chatgpt-to-write-5000-words-article.jpg)

 ChatGPT is a powerful tool. But maybe 5,000 words was asking a bit too much, so I asked for 2,500 words instead.

![Asking ChatGPT to write 2500 words article](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/asking-chatgpt-to-write-2500-words-article.jpg)

 ChatGPT still said it wasn't able to fulfill the request. We worked down to 1,000 words before the chatbot produced the article. But there was another problem: no matter how many times we tried, ChatGPT couldn't produce 1,000 words on the subject. But why? What's limiting the chatbot's ability to produce longer replies?

 Part of the answer as to why this happens lies in something called the token system.

### What Is the Token System ChatGPT Uses?

 When you ask ChatGPT a question, the length of the replies it can provide depends on a token system. Rather than a simple word count to determine the length of both queries and answers, ChatGPT uses this system. Notice something? The length of both "queries and answers" is taken into consideration. The token system breaks down each input and output into a series of tokens to classify the request and response size.

 While word count does play a part in this, it isn't the whole story. For instance, the example below was entered into[OpenAI's Tokenizer tool](https://platform.openai.com/tokenizer) .

![Screenshot of ChatGPT Tokenizer tool test](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/screenshot-of-chatgpt-tokenizer-tool-test.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
<!-- affiliate ads end -->

 The sentence "How many words have I typed" and answer "6" were "tokenized" to a value of nine tokens. This is consistent with OpenAI's "rule of thumb" that one token is equivalent to around three-quarters of a word.

 Here's where things get a little bit tricky. OpenAI's GPT models come in varying token lengths. The standard GPT-4 model that comes with your ChatGPT Plus subscription offers anywhere between 4k and 8k token context length. OpenAI also provides an extended 32k token context length GPT-4 model. The GPT-3.5 series offers even more token variety. There are 4k, 8k, and 16k GPT-3.5 models. However, not all these models are publicly available.

 We used the base GPT-3.5 and supposed GPT-4 8k models for this test. We say "supposed" because the 8k tag didn't check out when we ran a context window test. And then there's the fact that there's no confirmation from official sources that the GPT-4 model at chat.openai.com is an 8k model.

 The base GPT 3.5 4k model is supposed to restrict user questions and replies to 4,097 tokens. Similarly, the GPT-4 8k model is supposed to deliver 8,192 tokens. By OpenAI's reckoning, this equates to about 3,000 words for the GPT-3.5 and around 5,000 to 6,000 words for the GPT-4 8k tokens. But wait a minute. With an approximate 3,000 to 6,000 words capacity on either model, why wasn't ChatGPT able to deliver a 2,500-word or even 1,500-word article when we requested? Why are ChatGPT responses much less than their advertised token count or context length?

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Why Are ChatGPT's Responses Limited?

 While token length looks straightforward and good in theory, there's more to how AI models consider these limits. There are two notable considerations.

1. **Past Conversations** : Because ChatGPT is a conversational chatbot, whenever you ask a question, the chatbot considers older conversations to stay consistent and ensure natural-sounding interactions. This means in longer conversations, older prompts and responses are invariably considered as part of the context window and end up eating your token length. So, it is not just the immediate question and replies that is considered in the context window calculation.
2. **System Demand** :[ChatGPT has quickly become one of the fastest-growing apps of all time](https://www.makeuseof.com/how-chatgpt-became-fastest-growing-app/) . This has generated a huge demand for ChatGPT. To ensure everyone gets a piece of the action, 8k tokens might not always be 8k. Remember, the more tokens to process, the more demand on the system. To lessen the average demand from each user, responses are curtailed to far below the stated limits.

 To stress, this is not a fixed rule—we generated outputs that exceeded this by almost two hundred words. However, this can be considered a safe upper limit to achieve complete answers.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## How to Get Longer Responses From ChatGPT

 Once you understand that there is a "hidden limit" to ChatGPT's responses, there are some simple ways to help you get more complete responses.

1. **Ask ChatGPT to Continue:** If ChatGPT stops partway through an answer, then one option is to simply ask it to continue. In the example below, we typed "Go on," and it added another two hundred words to the response.  
![Screenshot of ChatGPT being prompted to continue](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/screenshot-of-chatgpt-being-prompted-to-continue.jpg)
<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
2. **Break your question into smaller sections:** For instance, we asked it several times to write an essay on the impact of AI on society. One option here is to ask it to bullet-point some topics for an essay on AI, then use the supplied bullet points as individual prompts.  
![Screenshot of ChatGPT response to AI Bullet points](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/screenshot-of-chatgpt-response-to-ai-bullet-points.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
3. **Use the Regenerate option:** While this might throw up the same error, with nothing to lose, it is always worth a shot.
4. **Specify an upper limit to your word count in your prompt:** The image below illustrates how this can be used to manipulate the maximum word count in an answer.  
![Screenshot of using a word limit for ChatGPT response](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/screenshot-of-using-a-word-limit-for-chatgpt-response.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
<!-- affiliate ads end -->
5. **Start a new conversation** : starting a new conversation gives you a clean slate to work with. Remember, ChatGPT considers past prompts and responses in a conversation. Starting a new chat gives you unused context to work with.

 These tips will help you to get more complete answers from ChatGPT and work around the unofficial limit in the length of its responses.

## ChatGPT: Quality Over Quantity

 While there is no official information on the maximum length of ChatGPT responses, in practice, there are hidden constraints. The token system, influenced by past conversations and system demand, all impact how long ChatGPT's answers can be. However, by asking ChatGPT to continue, breaking questions into parts, regenerating responses, specifying word counts, and starting new chats, you can often get more complete, longer replies. Though not perfect, being aware of these unofficial limits and using the right techniques can help you get the most out of this powerful AI chatbot.


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
<li><a href="https://youtube-zero.techidaily.com/024-approved-tutorial-unmask-your-youtube-audience/"><u>[New] 2024 Approved  Tutorial  Unmask Your YouTube Audience</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-unveiling-todays-instagram-trends-and-tags-for-2024/"><u>[New] Unveiling Today's #Instagram Trends and Tags for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-navigating-the-backup-of-phones-camera-roll-for-snapchat-users/"><u>2024 Approved  Navigating the Backup of Phone's Camera Roll for Snapchat Users</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-ultimate-guide-for-effortless-youtube-shorts-design/"><u>2024 Approved  The Ultimate Guide for Effortless YouTube Shorts Design</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/amd-radeon-hd-driver-installation-package-for-microsoft-windows-7-users/"><u>AMD Radeon HD Driver Installation Package for Microsoft Windows 7 Users</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-strategies-to-correctly-address-error-code-31-on-a-windows-machine/"><u>Comprehensive Strategies to Correctly Address Error Code 31 on a Windows Machine</u></a></li>
<li><a href="https://tech-haven.techidaily.com/embracing-gpt-3-the-path-to-excellence-at-openai/"><u>Embracing GPT-3: The Path to Excellence at OpenAI</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-epic-launcher-performance-a-how-to/"><u>Enhancing Epic Launcher Performance: A How-To</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-the-newest-logitech-headset-software-instantly-for-optimal-performance/"><u>Get the Newest Logitech Headset Software Instantly for Optimal Performance</u></a></li>
<li><a href="https://tech-haven.techidaily.com/gpt-and-bing-battle-for-top-generative-bot-acclaim/"><u>GPT and Bing Battle for Top Generative Bot Acclaim</u></a></li>
<li><a href="https://tech-haven.techidaily.com/gpt4all-demystified-operation-insights/"><u>GPT4All Demystified: Operation Insights</u></a></li>
<li><a href="https://tech-haven.techidaily.com/guiding-kids-in-the-age-of-ai-5-essential-practices-for-responsible-chatgpt-use/"><u>Guiding Kids in the Age of AI: 5 Essential Practices for Responsible ChatGPT Use</u></a></li>
<li><a href="https://tech-haven.techidaily.com/heres-what-10-global-tech-leaders-think-about-ai/"><u>Here's What 10 Global Tech Leaders Think About AI</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-ai-facilitates-cybercrime-understanding-the-top-5-methods/"><u>How AI Facilitates Cybercrime: Understanding the Top 5 Methods</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-artificial-intelligence-chatbots-transform-the-landscape-of-creating-digital-content/"><u>How Artificial Intelligence Chatbots Transform the Landscape of Creating Digital Content</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-a-lost-poco-x5-for-free-drfone-by-drfone-virtual-android/"><u>How to Track a Lost Poco X5 for Free? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-realme-12plus-5g-to-samsung-galaxy-s21-ultra-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos From Realme 12+ 5G to Samsung Galaxy S21 Ultra | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-to-troubleshoot-these-6-typical-chatgpt-mistakes-easily/"><u>How to Troubleshoot These 6 Typical ChatGPT Mistakes Easily</u></a></li>
<li><a href="https://tech-haven.techidaily.com/idea-genesis-leveraging-ais-insights-to-boost-project-quality/"><u>Idea Genesis: Leveraging AI's Insights to Boost Project Quality</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-a-comprehensive-guide-for-enhancing-tiktok-voices/"><u>In 2024, A Comprehensive Guide for Enhancing TikTok Voices</u></a></li>
<li><a href="https://tech-haven.techidaily.com/incorporating-personalized-gpt-insights-into-chatbot-interactions-for-a-bespooken-experience/"><u>Incorporating Personalized GPT Insights Into Chatbot Interactions for a Bespooken Experience</u></a></li>
<li><a href="https://tech-haven.techidaily.com/innovative-strategies-to-improve-your-dandd-experience-using-chatgpt/"><u>Innovative Strategies to Improve Your D&D Experience Using ChatGPT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/integrating-chatgpt-with-ubuntu-mastering-conversational-ai-via-shell-interface/"><u>Integrating ChatGPT with Ubuntu: Mastering Conversational AI via Shell Interface</u></a></li>
<li><a href="https://tech-haven.techidaily.com/is-gpt-5-on-the-horizon-exploring-the-release-timeline/"><u>Is GPT-5 on the Horizon? Exploring the Release Timeline</u></a></li>
<li><a href="https://fake-location.techidaily.com/ispoofer-is-not-working-on-realme-gt-5-pro-fixed-drfone-by-drfone-virtual-android/"><u>iSpoofer is not working On Realme GT 5 Pro? Fixed | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/learning-from-human-input-is-chatgpt-able-to-evolve/"><u>Learning From Human Input: Is ChatGPT Able to Evolve?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/leveraging-ai-chatgpts-strengths-in-7-health-factors/"><u>Leveraging AI: ChatGPT's Strengths in 7 Health Factors</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-chatgpt-for-total-life-enhancement/"><u>Mastering ChatGPT for Total Life Enhancement</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-generative-ai-the-7-critical-mistakes-you-should-not-make/"><u>Mastering Generative AI: The 7 Critical Mistakes You Should Not Make</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-prompt-engineering-for-ai-5-essential-techniques-to-get-optimal-chatgpt-responses/"><u>Mastering Prompt Engineering for AI: 5 Essential Techniques to Get Optimal ChatGPT Responses</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-task-automation-leveraging-chatgpt-for-enhanced-productivity-at-work/"><u>Mastering Task Automation: Leveraging ChatGPT for Enhanced Productivity at Work</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-the-basics-of-openai-an-ultimate-information-source/"><u>Mastering the Basics of OpenAI: An Ultimate Information Source</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-the-basics-of-langchain-llm-an-essential-starter-resource/"><u>Navigating the Basics of LangChain LLM: An Essential Starter Resource</u></a></li>
<li><a href="https://tech-haven.techidaily.com/nostalgia-in-play-handhelds-and-hardware-help/"><u>Nostalgia in Play: Handhelds & Hardware Help</u></a></li>
<li><a href="https://fox-that.techidaily.com/overcome-the-on-hold-battery-charge-dilemma-with-these-8-methods/"><u>Overcome the On-Hold Battery Charge Dilemma with These 8 Methods</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/perfecting-profiles-how-to-embed-linktree-on-tiktok-seamlessly/"><u>Perfecting Profiles  How to Embed Linktree on TikTok Seamlessly</u></a></li>
<li><a href="https://fake-location.techidaily.com/the-best-8-vpn-hardware-devices-reviewed-on-poco-f5-pro-5g-drfone-by-drfone-virtual-android/"><u>The Best 8 VPN Hardware Devices Reviewed On Poco F5 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/track-it-like-that-essential-tiktok-raps-you-cant-ignore-for-2024/"><u>Track It Like That  Essential TikTok Raps You Can't Ignore for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/transformative-techniques-podcast-covers-reimagined/"><u>Transformative Techniques  Podcast Covers Reimagined</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unlocking-gpt-4s-potential-accessible-ai-for-all-discover-the-workflow/"><u>Unlocking GPT-4's Potential: Accessible AI for All - Discover The Workflow</u></a></li>
</ul></div>
