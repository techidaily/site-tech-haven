---
title: Harnessing Quora’s POE for LLM & Chatbot Access
date: 2025-01-09T18:08:18.749Z
updated: 2025-01-13T18:02:05.460Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E3yY7lZ-FKA?si=g8VEuExP8GH59B69" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Of course, asking ChatGPT about itself isn't a good idea since it isn't typically objective about its abilities or has limited information. So, we ran some tests to determine the length limits of ChatGPT responses. We asked the chatbot to write a 5000-word article on the history of the FIFA World Cup. ChatGPT's assessment of itself differed from the results we found.

![Asking ChatGPT to write 5000 words article](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/asking-chatgpt-to-write-5000-words-article.jpg)

 ChatGPT is a powerful tool. But maybe 5,000 words was asking a bit too much, so I asked for 2,500 words instead.

![Asking ChatGPT to write 2500 words article](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/asking-chatgpt-to-write-2500-words-article.jpg)

 ChatGPT still said it wasn't able to fulfill the request. We worked down to 1,000 words before the chatbot produced the article. But there was another problem: no matter how many times we tried, ChatGPT couldn't produce 1,000 words on the subject. But why? What's limiting the chatbot's ability to produce longer replies?

 Part of the answer as to why this happens lies in something called the token system.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KKFdFHaVIJg?si=x2vLw7ty3FtHX-9T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### What Is the Token System ChatGPT Uses?

 When you ask ChatGPT a question, the length of the replies it can provide depends on a token system. Rather than a simple word count to determine the length of both queries and answers, ChatGPT uses this system. Notice something? The length of both "queries and answers" is taken into consideration. The token system breaks down each input and output into a series of tokens to classify the request and response size.

 While word count does play a part in this, it isn't the whole story. For instance, the example below was entered into[OpenAI's Tokenizer tool](https://platform.openai.com/tokenizer) .

![Screenshot of ChatGPT Tokenizer tool test](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/screenshot-of-chatgpt-tokenizer-tool-test.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qbuund2HKOQ?si=NaGHqIrx8hSL7gWV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The sentence "How many words have I typed" and answer "6" were "tokenized" to a value of nine tokens. This is consistent with OpenAI's "rule of thumb" that one token is equivalent to around three-quarters of a word.

 Here's where things get a little bit tricky. OpenAI's GPT models come in varying token lengths. The standard GPT-4 model that comes with your ChatGPT Plus subscription offers anywhere between 4k and 8k token context length. OpenAI also provides an extended 32k token context length GPT-4 model. The GPT-3.5 series offers even more token variety. There are 4k, 8k, and 16k GPT-3.5 models. However, not all these models are publicly available.

 We used the base GPT-3.5 and supposed GPT-4 8k models for this test. We say "supposed" because the 8k tag didn't check out when we ran a context window test. And then there's the fact that there's no confirmation from official sources that the GPT-4 model at chat.openai.com is an 8k model.

 The base GPT 3.5 4k model is supposed to restrict user questions and replies to 4,097 tokens. Similarly, the GPT-4 8k model is supposed to deliver 8,192 tokens. By OpenAI's reckoning, this equates to about 3,000 words for the GPT-3.5 and around 5,000 to 6,000 words for the GPT-4 8k tokens. But wait a minute. With an approximate 3,000 to 6,000 words capacity on either model, why wasn't ChatGPT able to deliver a 2,500-word or even 1,500-word article when we requested? Why are ChatGPT responses much less than their advertised token count or context length?

## Why Are ChatGPT's Responses Limited?

 While token length looks straightforward and good in theory, there's more to how AI models consider these limits. There are two notable considerations.

1. **Past Conversations** : Because ChatGPT is a conversational chatbot, whenever you ask a question, the chatbot considers older conversations to stay consistent and ensure natural-sounding interactions. This means in longer conversations, older prompts and responses are invariably considered as part of the context window and end up eating your token length. So, it is not just the immediate question and replies that is considered in the context window calculation.
2. **System Demand** :[ChatGPT has quickly become one of the fastest-growing apps of all time](https://www.makeuseof.com/how-chatgpt-became-fastest-growing-app/) . This has generated a huge demand for ChatGPT. To ensure everyone gets a piece of the action, 8k tokens might not always be 8k. Remember, the more tokens to process, the more demand on the system. To lessen the average demand from each user, responses are curtailed to far below the stated limits.

 To stress, this is not a fixed rule—we generated outputs that exceeded this by almost two hundred words. However, this can be considered a safe upper limit to achieve complete answers.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S3Th6oa_isA?si=TTQ013BB9beUM4x6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Get Longer Responses From ChatGPT

 Once you understand that there is a "hidden limit" to ChatGPT's responses, there are some simple ways to help you get more complete responses.

1. **Ask ChatGPT to Continue:** If ChatGPT stops partway through an answer, then one option is to simply ask it to continue. In the example below, we typed "Go on," and it added another two hundred words to the response.  
![Screenshot of ChatGPT being prompted to continue](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/screenshot-of-chatgpt-being-prompted-to-continue.jpg)
2. **Break your question into smaller sections:** For instance, we asked it several times to write an essay on the impact of AI on society. One option here is to ask it to bullet-point some topics for an essay on AI, then use the supplied bullet points as individual prompts.  
![Screenshot of ChatGPT response to AI Bullet points](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/screenshot-of-chatgpt-response-to-ai-bullet-points.jpg)
3. **Use the Regenerate option:** While this might throw up the same error, with nothing to lose, it is always worth a shot.
4. **Specify an upper limit to your word count in your prompt:** The image below illustrates how this can be used to manipulate the maximum word count in an answer.  
![Screenshot of using a word limit for ChatGPT response](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/screenshot-of-using-a-word-limit-for-chatgpt-response.jpg)
5. **Start a new conversation** : starting a new conversation gives you a clean slate to work with. Remember, ChatGPT considers past prompts and responses in a conversation. Starting a new chat gives you unused context to work with.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aG3NRuHrIJg?si=HwzwD0RXmrzIXX1V" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://youtube-blog.techidaily.com/ed-download-youtube-icons-quickly-web-os-specific-options-explained/"><u>[Updated] Download YouTube Icons Quickly Web, OS-Specific Options Explained</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-capture-and-preserve-a-detailed-look-at-7-ways-to-log-webcasts/"><u>2024 Approved Capture and Preserve A Detailed Look at 7 Ways to Log Webcasts</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-dji-phantom-3-pro-an-in-depth-analysis/"><u>2024 Approved DJI Phantom 3 Pro An In-Depth Analysis</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/amds-next-leap-with-fire-range-the-continued-use-of-fl1-packaging-in-zen-5-cpus-and-potential-for-rtx-series-integration-in-new-laptop-releases/"><u>AMD's Next Leap with 'Fire Range': The Continued Use of FL1 Packaging in Zen 5 CPUs and Potential for RTX Series Integration in New Laptop Releases</u></a></li>
<li><a href="https://tech-haven.techidaily.com/in-search-of-clarity-tracing-back-to-what-sparked-the-significant-2024-upheaval-between-crowdstrike-and-windows/"><u>In Search of Clarity: Tracing Back to What Sparked the Significant 2024 Upheaval Between CrowdStrike and Windows</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722964102652-logitech-headset-drivers-download-and-update-easily/"><u>Logitech Headset Drivers Download & Update Easily</u></a></li>
<li><a href="https://win-answers.techidaily.com/mastering-phasmophobia-performance-reducing-high-cpu-consumption-tips/"><u>Mastering Phasmophobia Performance: Reducing High CPU Consumption Tips</u></a></li>
<li><a href="https://tech-haven.techidaily.com/relax-in-comfort-make-zoom-meetings-from-your-sofa-using-the-latest-apple-tv-application/"><u>Relax in Comfort: Make Zoom Meetings From Your Sofa Using the Latest Apple TV Application</u></a></li>
<li><a href="https://tech-haven.techidaily.com/student-friendly-guide-to-score-big-savings-on-apple-music-with-authorized-discounts/"><u>Student-Friendly Guide to Score Big Savings on Apple Music with Authorized Discounts</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-artists-ascent-a-guide-to-professional-growth-in-graphic-design-for-2024/"><u>The Artist's Ascent A Guide to Professional Growth in Graphic Design for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-enhanced-lg-bp550-review-2023-update/"><u>The Enhanced LG BP550 Review - 2023 Update</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-ultimate-benefits-of-apple-pay-for-shoppers-expert-tips-on-how-and-why-to-use-it-both-offline-and-online/"><u>The Ultimate Benefits of Apple Pay for Shoppers: Expert Tips on How and Why to Use It Both Offline and Online</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-july-2024-laptop-bargains-you-cant-miss-zdnet-reviews/"><u>Top July 2024 Laptop Bargains You Can't Miss - ZDNet Reviews</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-rated-smartwatches-comprehensive-reviews-by-tech-specialists-zdnet/"><u>Top-Rated Smartwatches : Comprehensive Reviews by Tech Specialists | ZDNet</u></a></li>
<li><a href="https://apple-account.techidaily.com/unlock-apple-id-without-phone-number-from-iphone-13-pro-max-by-drfone-ios/"><u>Unlock Apple ID without Phone Number From iPhone 13 Pro Max</u></a></li>
<li><a href="https://tech-haven.techidaily.com/why-cant-you-access-apples-newest-artificial-intelligence-innovations-on-previous-iphones-discover-the-pricey-secrets-techinsights/"><u>Why Can't You Access Apple's Newest Artificial Intelligence Innovations on Previous iPhones? Discover the Pricey Secrets! - TechInsights</u></a></li>
</ul></div>

