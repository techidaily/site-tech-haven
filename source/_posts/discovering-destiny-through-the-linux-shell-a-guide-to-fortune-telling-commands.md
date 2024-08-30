---
title: "Discovering Destiny Through the Linux Shell: A Guide to Fortune Telling Commands"
date: 2024-08-29T02:12:02.431Z
updated: 2024-08-30T02:12:02.431Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/6fcd76fd6f172d48de92c06ef6acf9b4878b2af9216aa863bdd663f250b5d16d.jpg
---

## Discovering Destiny Through the Linux Shell: A Guide to Fortune Telling Commands

### Key Takeaways

* You can use the "fortune" command to view random quotes, jokes, or advice right in your terminal.
* Additionally, you can customize your fortune's database by creating your own fortune file.
* For additional fun, you could pipe a fortune with cowsay, or display a random fortune every time you launch your terminal.

 Ever thought your terminal could be a source of daily wisdom or humor? It's true! With the fortune command, you can receive a random quote, joke, or piece of advice every time you execute it. Whether you're working or enjoying a break, a short fortune can lift your mood and encourage new ideas.

##  What Is the fortune Command?

 The fortune command is a classic tool, with roots tracing back to the 1980s when it was bundled with [Unix](https://vimeo-videos.techidaily.com/2024-approved-elevate-your-visuals-music-integration-for-vimeo-films/). This command's primary purpose is to display a random quote, proverb, or humorous saying each time you run it. It is your digital fortune cookie that offers a slice of wisdom or a chuckle whenever you need it.

 Why add fortunes to your terminal? It’s just for fun! You can use them in your system's message of the day. Personally, I find the fortune command handy when I need some quick text to test [regular expressions](https://extra-lessons.techidaily.com/top-10-after-effects-text-presets/) in the terminal.

 To use fortune, you first need to make sure it's already present in your system. The [original version of fortune](https://en.wikipedia.org/wiki/Fortune%5F%28Unix%29) was created for a Unix-like operating system called NetBSD. However, if you're using Linux, you can't use that original version directly. Instead, you have to use a modified version called [fortune-mod](https://github.com/shlomif/fortune-mod).

 So, when you're installing fortune on a Linux system, you're actually installing the fortune-mod package. This version has been adapted specifically to work on Linux.

 On all major Linux systems, you can install fortune via default package manager. For example, on Ubuntu or Debian, run:

sudo apt install fortune-mod

 To get it on Fedora and other RPM-based systems, run:

sudo dnf install fortune-mod

 For Arch Linux, run this:

sudo pacman -S fortune-mod

 Once installed, all you need to do is type fortune into the terminal, hit enter, and wait for the magic to happen.

fortune

![Running fortune command in Linux terminal.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/fortune-command.png) 

<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
##  fortune Options

 When you run a fortune without any arguments, it randomly selects an epigram from the fortune's database. However, it also comes with several options that let you enhance your experience. Let's check out some of them:

| **Option**    | **Description**                                                                                                                                         |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- |
| \-a           | This option includes both offensive and inoffensive fortunes.                                                                                           |
| \-s           | This option tells fortune to only display short quotes. (less than 160 characters)                                                                      |
| \-I           | Serves up the long ones (more than 160 characters)                                                                                                      |
| \-c           | Display the cookie file from which the fortune was selected.                                                                                            |
| \-f           | Print a list of files that will be searched, without actually printing a fortune.                                                                       |
| \-e           | Using this option gives all files an equal shot. By default, longer files have a higher chance of being selected.                                       |
| \-i           | Ignore the case when matching patterns with -m.                                                                                                         |
| \-m <pattern> | Use this to search for fortunes that match a particular keyword. For example, if you want to see fortunes about love, you can type **fortune -m love**. |
| \-n <pattern> | Set the maximum length for a fortune to be considered short. The default is 160 characters. Anything longer fortune will classify as "long."            |

 Furthermore, fortune allows you to choose from different categories, such as, if you're a fan of literature or riddles, you can instruct fortune to only show quotes from those categories.

fortune literature

 You can also combine multiple options together, such as if you want a short, offensive quote from the literature category, run this:

fortune -s -o literature

##  Create Your Own fortune File

 What if I told you that you could create your own fortunes? That's right, it's a straightforward process. All you need is to create your custom fortune file and make it compatible with the fortune command's requirements. In this way, you're not bound to the predefined messages.

 To try it out, simply open your terminal and create a plain text document using your [favorite text editor](https://screen-video-capture.techidaily.com/free-software-showdown-the-leading-10-audio-capture-utilities-for-2024/).

nano funny

 Next, start adding your fortunes and make sure that each fortune is separated by a line with a percent sign % on it.

![Adding fortunes text to a plain text file using nano text editor in Linux terminal.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/adding-fortunes-saying.png) 

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
 Once your file is ready, you need to convert it to a format that fortune can use. You can do this with the strfile command, which generates the necessary "funny.dat" file for the fortune command:

strfile -c % funny funny.dat

![Converting plain text file to fortune supported file using strfile command.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/file-conversoin-strfile.png) 

 Now, [move both files to the directory](https://some-knowledge.techidaily.com/in-2024-immersive-innovations-the-distinct-worlds-of-mr-ar-and-vr/) where fortune looks for its data. This location can vary, but it often looks like "/usr/share/games/fortunes/" or "/usr/local/share/games/fortunes/".

sudo cp funny* /usr/share/games/fortunes/

 You can verify the movement by running this command:

fortune -f

![Listing all fortune source files using the -f option of fortune command.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/fortune-listing.png) 

 The percentage here gives you a rough idea of how much of the total database size is taken up by a particular file.

 Finally, you can use the fortune command to get fortunes from your customs file.

fortune funny

![Displaying random saying from your newly created fortune file.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/fotune-command-custom.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
<!-- affiliate ads end -->
 Every time you run the command, one of your hand-crafted fortunes will appear.

##  Combine fortune and cowsay for Extra Fun

 If you think the fortune command is cool, wait until you see it combined with cowsay. This fun command displays an [ASCII art](https://games-able.techidaily.com/exclusive-portable-power-stations-for-gaming/) cow in your terminal that says whatever you input. There's no need for arguments—just provide some text, and you're good to go.

 You can get cowsay from your default package manager such as on Ubuntu or Debian, use apt:

sudo apt install cowsay

 Now, let's [pipe](https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-11-pro-to-other-iphone-11-pro-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/) fortune output with cowasy to produce something very funny and interesting.

fortune | cowsay

![Piping fortune output to cowsay command to display random saying along with ASCII art.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/fortune-cowsay.png) 

 Check it out! You've got a cow dispensing wisdom right there in your terminal. Just what you always wanted!

 But wait—there's more! You can also change the character delivering your fortune. For example, use **\-f** followed by the character's name to pick any other ASCII creature:

fortune | cowsay -f tux

![Tux displays random statements using fortune and cowsay commands.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/fortune-cowsay-tux.png) 

 You can also make your tux [colorful by piping the lolcat command](https://youtube-tips.techidaily.com/n-2024-accelerate-yt-growth-strategies-for-1kplus-subscribers/).

fortune | cowsay -f tux | lolcat

![Making the ouptut of fortune and cowsay colorful using the lolcat command.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/cowsay-linux-lolcat-1.png) 

<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  View Fortune on Terminal Startup

 Want to see a friendly dose of wisdom every time you open a bash terminal? If yes, then you need to add a fortune command to the end of your [\~/.bashrc file](https://phone-solutions.techidaily.com/3-easy-solutions-to-hard-reset-nokia-xr21-drfone-by-drfone-reset-android-reset-android/).

 The first thing you need to do is to edit your shell configuration file. For [bash shell](https://blog-min.techidaily.com/how-to-repair-iphone-6-system-drfone-by-drfone-ios-system-repair-ios-system-repair/), the configuration file is likely \~/.bashrc, and for [zsh](https://on-screen-recording.techidaily.com/2023s-elite-web-based-recording-devices-for-2024/), it's \~/.zshrc. I'm using bash, so let's open it with:

nano ~/.bashrc

 Next, scroll to the bottom of the file and add the following line:

fortune | cowsay

![Adding fortune command along with cowsay to the end of bashrc file.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/fortune-cowsay-bashrc-file.png) 

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
 This will ensure that every time you open your terminal, you'll see a fortune delivered by a cow.

 After saving changes, press Ctrl+X to exit the editor. To see the changes happen, you can either [restart your terminal](https://data-wizards.techidaily.com/formatting-your-macs-storage-simplified-an-instructional-video/) or execute:

source ~/.bashrc

 Now, every time you launch your terminal, you'll be greeted with a delightful fortune.

![Random fortune appearing on a Linux terminal after being launched.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/terminal-fortune-begin.png) 

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->
 If you want to use different ASCII art creatures, such as tux, just replace the **cowsay** command in the \~/.bashrc file with the **cowsay -f tux** command.

![Adding new fortune command with tux ASCII art to the end of bashrc file.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/terminal-fortune-tux.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Use Fortune for Testing

 Beyond its entertainment or enlightening uses, the fortune command has a few hidden applications. For example, you can often use it to generate random text files that are very useful for testing scripts and various commands.

 Let's redirect fortune output to a file:

fortune > file1

 To view the content of the file, run:

cat file1

![Viewing the file using the cat command.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/viewing-file-with-cat.png) 

 If you want to append multiple fortunes to the same file, you can do so in a loop.

        `for i in {1..10};  
do fortune >> file1;  
done`
    
 Another clever use for fortune is [generating random numbers](https://tech-hub.techidaily.com/mastering-the-art-of-influence-crafting-convincing-requests-with-chatgpt/). By using the [wc command](https://iphone-unlock.techidaily.com/in-2024-unlock-iphone-se-2020-without-passcode-easily-drfone-by-drfone-ios/) with the **\-c** option, you can count the characters in each fortune:

fortune | wc -c

##  Create a Random Picker Game

 You can also use fortune to randomize data for other purposes. Say you have a list of friends, coworkers, or contest participants—just put their names into a file and let fortune pick a winner. To accomplish this, you'll need to make your own fortune file, as explained above.

---

 There are several [fun Linux commands](https://fox-friendly.techidaily.com/updated-2024-approved-podcastpathfinder-charting-new-courses/) that can brighten your day, much like the classic fortune command. Some that I find particularly amusing is the [fake Linux hacking commands](https://instagram-video-files.techidaily.com/updated-in-2024-perfecting-highlight-covers-an-in-depth-insta-photography-guide/).

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
<li><a href="https://facebook-clips.techidaily.com/new-the-complete-blueprint-for-extracting-fb-graphics-to-your-device/"><u>[New] The Complete Blueprint for Extracting FB Graphics to Your Device</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-step-by-step-guide-to-painless-iphone-screen-sharing/"><u>[Updated] 2024 Approved  Step-by-Step Guide to Painless iPhone Screen Sharing</u></a></li>
<li><a href="https://tech-haven.techidaily.com/best-ai-communicator-showdown-gpt-or-bing-leads/"><u>Best AI Communicator Showdown - GPT or Bing Leads?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/comparing-claude-and-chatgpt-the-top-choice-for-daily-conversations/"><u>Comparing Claude and ChatGPT: The Top Choice for Daily Conversations</u></a></li>
<li><a href="https://tech-haven.techidaily.com/crafting-stellar-resumes-tips-and-techniques-chatgpt/"><u>Crafting Stellar Resumes: Tips and Techniques (ChatGPT)</u></a></li>
<li><a href="https://tech-haven.techidaily.com/does-chatgpt-compromise-our-privacy/"><u>Does ChatGPT Compromise Our Privacy?</u></a></li>
<li><a href="https://sound-issues.techidaily.com/effortless-solutions-to-reactivate-your-astro-a2e-mic/"><u>Effortless Solutions to Reactivate Your Astro A2e Mic</u></a></li>
<li><a href="https://tech-haven.techidaily.com/elevate-your-twitter-game-using-chatgpt-a-step-by-step-guide-to-writing-effective-tweets/"><u>Elevate Your Twitter Game Using ChatGPT: A Step-by-Step Guide to Writing Effective Tweets</u></a></li>
<li><a href="https://extra-tips.techidaily.com/elite-5-screen-selections-ps5s-partner/"><u>Elite 5 Screen Selections  PS5's Partner</u></a></li>
<li><a href="https://tech-haven.techidaily.com/empowering-everyone-the-journey-into-gpt-4/"><u>Empowering Everyone: The Journey Into GPT-4</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/experts-take-on-using-luts-for-image-enhancement-in-pscc-for-2024/"><u>Expert's Take on Using LUTs for Image Enhancement in PSCC for 2024</u></a></li>
<li><a href="https://techidaily.com/factory-reset-apple-iphone-6-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>Factory Reset Apple iPhone 6 | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/get-started-on-ai-based-bing-simple-setup-procedure/"><u>Get Started on AI-Based Bing: Simple Setup Procedure</u></a></li>
<li><a href="https://extra-resources.techidaily.com/greatest-20-free-pubg-image-compilations/"><u>Greatest 20 Free PUBG Image Compilations</u></a></li>
<li><a href="https://tech-haven.techidaily.com/has-ais-rise-with-chatgpt-revolutionized-academic-writing-for-students/"><u>Has AI's Rise with ChatGPT Revolutionized Academic Writing for Students?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-effective-is-chatgpt-in-handling-numerical-and-algebraic-equations/"><u>How Effective Is ChatGPT in Handling Numerical and Algebraic Equations?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/implementing-advanced-ai-access-our-selection-of-8-ready-made-gpt-solutions/"><u>Implementing Advanced AI: Access Our Selection of 8 Ready-Made GPT Solutions</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/1715860334473-in-2024-leveraging-built-in-recorders-on-mate-1020-and-p2010-series-to-screen-capture/"><u>In 2024, Leveraging Built-In Recorders on Mate 10/20 & P20/10 Series to Screen Capture.</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-the-essential-snapshot-strategies-snapchat-boomerangs-unveiled/"><u>In 2024, The Essential Snapshot Strategies  Snapchat Boomerangs Unveiled</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-6-appsservices-to-trace-any-nokia-150-2023-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, Top 6 Apps/Services to Trace Any Nokia 150 (2023) Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/in-2024-unlocking-audio-enhancement-three-inexpensive-apple-techniques-for-films/"><u>In 2024, Unlocking Audio Enhancement  Three Inexpensive Apple Techniques for Films</u></a></li>
<li><a href="https://tech-haven.techidaily.com/love-algorithms-how-gpt-transforms-relationships/"><u>Love Algorithms: How GPT Transforms Relationships</u></a></li>
<li><a href="https://tech-haven.techidaily.com/maximizing-gpt-3-experience-on-your-device/"><u>Maximizing GPT-3 Experience on Your Device</u></a></li>
<li><a href="https://tech-haven.techidaily.com/messaging-and-ai-exploring-the-reasons-why-generative-technology-might-not-be-ideal/"><u>Messaging and AI: Exploring the Reasons Why Generative Technology Might Not Be Ideal</u></a></li>
<li><a href="https://tech-haven.techidaily.com/replacing-the-turing-benchmark-unveiling-5-cutting-edge-artificial-intelligence-tests/"><u>Replacing the Turing Benchmark: Unveiling 5 Cutting-Edge Artificial Intelligence Tests</u></a></li>
<li><a href="https://tech-haven.techidaily.com/safe-practices-for-implementing-chatgpt-in-mental-wellness-coaching/"><u>Safe Practices for Implementing ChatGPT in Mental Wellness Coaching</u></a></li>
<li><a href="https://tech-haven.techidaily.com/sam-altman-steps-down-as-openais-ceo-the-repercusscuions-on-chatgpt-services/"><u>Sam Altman Steps Down as OpenAI's CEO - The Repercusscuions on ChatGPT Services</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-role-of-shared-links-in-chatgpt-an-in-depth-analysis/"><u>The Role of Shared Links in ChatGPT: An In-Depth Analysis</u></a></li>
<li><a href="https://tech-haven.techidaily.com/travel-planning-made-easy-with-7-ai-powered-cost-free-tools/"><u>Travel Planning Made Easy with 7 AI-Powered, Cost-Free Tools</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/understanding-and-proficiently-implementing-cc-copyrights-for-2024/"><u>Understanding and Proficiently Implementing CC Copyrights for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/understanding-generative-ai-an-in-depth-exploration/"><u>Understanding Generative AI: An In-Depth Exploration</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unlock-new-levels-of-analysis-utilize-chatgpt-in-six-innovative-ways/"><u>Unlock New Levels of Analysis: Utilize ChatGPT in Six Innovative Ways</u></a></li>
</ul></div>
