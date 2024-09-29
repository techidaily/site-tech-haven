---
title: "Step-by-Step Guide: Turning On/Off the Secure Sign-In Feature in Windows 11"
date: 2024-08-29T02:12:32.929Z
updated: 2024-08-30T02:12:32.929Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/6d8730f2a77f7bacc79151a55ebc1a6b3c6364485074d0b800543a32a08c9abf.jpg
---

## Step-by-Step Guide: Turning On/Off the Secure Sign-In Feature in Windows 11

### Quick Links

* [What is Secure Sign-in?](https://howto.techidaily.com/4-ways-to-fix-android-blue-screen-of-death-on-oneplus-open-drfone-by-drfone-fix-android-problems-fix-android-problems/)
* [Enable or Disable Secure Sign-In Using the Netplwiz Command](https://hardware-reviews.techidaily.com/unveiling-the-latest-in-computing-at-toms-electronics-hub/)
* [Enable or Disable Secure Sign-in Using the Registry](https://visual-screen-recording.techidaily.com/2024-approved-build-a-fortified-mc-base-plan-6-10/)
* [Enable or Disable Using the Local Security Policy](https://fox-friendly.techidaily.com/new-scripting-temporal-disruption-scenes/)

### Key Takeaways

* Secure Sign-In removes login fields until you type a string of keys, helping to thwart malware that may spoof the login screen.
* You can enable or disable Secure Sign-In through the User Accounts panel, Registry Editor, or Local Security Policy, but it's not a foolproof solution.
* Remember to keep Windows updated and use antivirus software.

 Windows is the most targeted operating system on the planet. That means you should fortify your PC's defenses to stay safe both online and offline. This guide shows you how to enable or disable Secure Sign-In for Windows 10 and Windows 11.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  What is Secure Sign-in?

 Secure Sign-In is an additional component on the Windows 10 login screen. It doesn’t prevent anyone from accessing your PC if they have your credentials. Instead, Windows 10 removes the login fields until you type a string of keys. After that, enter your password or PIN as usual.

 This feature aims to thwart malware. Malicious code could reside in the background and spoof the Windows 10 or Windows 11 login screen to capture your credentials. Because apps and programs typically don’t have access to the Ctrl+At+Del command, you can bypass the fake login screen by using Secure Sign-In that's activated by typing this three-key command.

##  Enable or Disable Secure Sign-In Using the Netplwiz Command

 To start, launch the Run command by pressing the "Windows" and "R" keys simultaneously (Windows+R). A small pop-up window will appear. Type **netplwiz** in the text field and then click the “OK” button (or press the Enter key) to continue.

![Enter "netplwiz" into a Run box or the Start Menu search.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/1-netplwiz-run.png) 

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35408920&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/FR-200-1.png" border="0">Glarysoft File Recovery Pro - Helps to recover your lost file/data, even permanently deleted data. </a>
<!-- affiliate ads end -->
 Alternatively, you can access the User Accounts panel by typing **netplwiz** into the taskbar’s search field and selecting the resulting Run command.

 The User Accounts panel will appear onscreen. Click the “Advanced” tab (if it’s not loaded by default). Locate the “Require Users to Press Ctrl+Alt+Delete” option listed under “Secure Sign-In.” Check to enable or uncheck to disable.

 Click the “Apply” button and then the “OK” button to finish.

![Click the box next to "Require Users to Press Ctrl+Alt+Delete" in the User Accounts window.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/2-enable-secure-sign-in.png) 

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
##  Enable or Disable Secure Sign-in Using the Registry

 If you want to take the hardcore route, why not [edit the registry](https://facebook-record-videos.techidaily.com/new-economical-mic-options-for-youtube-vloggers-for-2024/)? Remember, tread lightly: Any changes you make could cause system instability. This option is for experienced individuals who enjoy digging deep into Windows.

 Launch the Run command by pressing the "Windows" and "R" keys simultaneously (Windows+R). A small pop-up window will appear. Type **regedit** (without quotes) in the text field and then click the “OK” button (or press the Enter key) to continue.

![Launch regedit through a Run box or the Start Menu search.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/3-regedit.png) 

 You can also access the Registry Editor by typing **regedit** into the taskbar’s search field and selecting the resulting desktop app.

 Type or paste the following path into Registry Editor's address bar:

Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Winlogon
                    

![Paste the regedit path into the address bar.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/4-regedit-path.png) 

 Double-click the "DisableCad" entry to edit its values.

![Double-click "Disable CAD."](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/5-disable-cat.png) 

 In the "Edit DWORD (32-bit) Value" pop-up box, change the Value Data with one of these values:

* Enable = **0**
* Disable = **1**

 Click the “OK” button to finish. Restart your PC to save the settings.

![Change the value to 1 or 0, depending on your preference.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/6-change-value.png) 

 If you don’t see a "DisableCad" entry in the "Winlogon" settings, right-click on "Winlogon," select “New” in the pop-up menu, and then click “DWORD (32-bit) Value" in the next list. Name this new DWORD **DisableCAD** and change its value.

![Create a new DWORD for disableCAD.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/7-create-val.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
<!-- affiliate ads end -->
##  Enable or Disable Using the Local Security Policy

 Here’s another method that’s somewhat busier than following the User Accounts instructions. Use this method if you want to take the scenic route but avoid the Windows registry.

 This option is not available on Home Editions of Windows 10 or Windows 11, only Pro or higher.

 Launch the Run command by pressing the "Windows" and "R" keys simultaneously (Windows+R). A small pop-up window appears. Type **secpol.msc** in the text field and then click the “OK” button (or press the Enter key) to continue.

![Opening secpol.msc from a Run window.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/1-secpol-in-w11-run.png) 

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
 Like before, you can also access the Local Security Policy panel by typing **secpol.msc** into the taskbar’s search field and selecting the resulting desktop app.

 In the Local Policy Window, expand “Local Policies” listed on the left and select the “Security Options” subfolder underneath. Next, scroll down on the right and double-click the “Interactive Logon: Do Not Require CTRL+ALT+DEL” entry.

![Navigate to Local Policies, then to Security Options, then click 'Interactive logon: Do Not Require CTRL+ALT+DEL.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/2-6.png) 

 The entry’s Properties panel appears onscreen with the "Local Security Setting" tab displayed by default. Click a radio button to enable or disable this feature. Finish by clicking the “Apply” button and then the “OK” button.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 

![Set the toggle to Enabled or Disabled, then click 'Apply.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/3-5.png) 

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->
 Enabling Secure Sign-in won't make your computer invulnerable to attackers, but it is a small change you can make that could help in some circumstances. You should always keep security concerns in the back of your mind these days, since so much sensitive information is stored or accessed via our computers. Make sure your keep Windows up to date and that you're [using some kind of antivirus](https://video-capture.techidaily.com/2024-approved-nvidia-game-capturer-simple-gaming-sessions/).

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


