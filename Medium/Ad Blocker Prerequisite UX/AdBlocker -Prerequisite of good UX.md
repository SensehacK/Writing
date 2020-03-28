 
Definitive Ad Block User Experience guide while reviewing how privacy, ads & security on the internet impacts our digital life. Kautilya 


Ad Blocker — Prerequisite of good UX

 
Open anything on the internet & you’ll find yourself bombarded with ads.
Sure ads let the writers, publishers or any entity to maintain their costs for the servers and get them paid for their work.
But occasionally these ad-driven websites/apps go out of bounds to create a horrible User Experience(UX) which leads to low engagement with the reader, the notoriety of the service or product increasing gradually.
So how can we enjoy a balanced experience on these ad-driven websites? Ad Blockers to the rescue!
Firefox + uBlock Origin + DuckDuckGo
I would list down the ways Ads could be blocked or temporarily disabled or specifically disabled for websites who abuse the user experience to drive more than normal ads which lead to an unpleasant experience as a whole.
This would be a prolonged article, as I’m touching on different ways of achieving a good privacy focused user experience on plethora of devices ranging from Smartphones, Personal Computer and smart devices like Smart TV’s, Consoles & IOT connected devices etc.
 
Browsers
 Image Credits: https://design.firefox.com/photon/visuals/product-identity-assets.html
Switch to Firefox!
I can’t stress this enough as if you’re using something made by Google whose whole purpose is to sell you ads on their platform. Releasing software products for free is because you’re the product. They would also have a conflict of interest when it comes to serving ads and only whitelisting their own domains with crippling support to the ad blockers.
Also Firefox has better memory management, good user data synchronization across various devices, and better tools for developers on top of being privacy-focused.
Download the fastest Firefox ever
Download Mozilla Firefox, a free Web browser. Firefox is created by a global non-profit dedicated to putting…www.mozilla.org
And did I mention it is free and available on every platform while being much faster, customizable and secure?
Switch to #Firefox, Don’t take my word for it.
Sources: MakeUseOf, Lifehacker, NYTimes, Mashable, Verge, HowToGeek
Also Microsoft Edge official beta has Chromium with privacy-focused browser, combine with Google Chrome v8 engine, whilst not stalking your presence in Incognito Mode. Switch to Firefox(FOOS), Safari, Microsoft Edge.
Also TOR Browser (based on Firefox fork + enhance privacy configuration) is also a good fit but we would dig deep in another article about Privacy.
Extensions
 Left to Right (Firefox Account, Dark Reader, uBlock Origin, HTTPS Everywhere)
Ad Block
 Image Credits: https://en.wikipedia.org/wiki/UBlock_Origin
Use uBlock Origin (Free and Open Source) ad blocker extension.
uBlock Origin goes the extra mile in blocking ads, you can follow the discussion on GitHub Issues or but you can read about how Firefox has better support for content blocking unlike Google Chrome.
Privacy
You could use HTTPS Everywhere for enforcing HTTPS connection wherever possible for default encryption over the web and thus avoiding insecure HTTP connections between Server and Client (Firefox browser).
Great article on benefits of using HTTPS as a default option for software developers (source).
  Location Access & Annoying Chat Bots
If you’re hesitant of installing one more extension which potentially could be resource hungry, fear not uBlock Origin will make sure that instead of unnecessary 100+ requests created by money-driven websites it would only request to specific things which are important to view the content and exclude the ads, trackers, fingerprinting, social components. It would be much faster and efficient to load 10 images vs (10 images + 4 ad images). Just an approximation on my part, every website architecture is different.
Also uBlock Origin doesn’t favor corporations which pay to show their Ads in browser under Allow Acceptable Ads functionality unlike some of its competitors. Becoming the very thing they solely tried to eradicate. 
5 things you should know about Adblock Plus -- starting with its alliance with the ad industry
You might be perturbed if somebody calls your business an " extortion racket" or your sales pitch a " ransom note." But…www.cnet.com
Also if you like efficiency comparison with other ad blockers here is the link.
Mobile Browser
 Safari content blocker — Firefox Focus
Android
Firefox has support for browser extensions, so again uBlock Origin could be used in conjunction with Firefox browser on android smartphones.
Firefox Google Play
iOS Firefox
If you need more privacy, you can install “Firefox Focus” which has an option to have content blocker in 
iOS -> Settings -> Safari -> Content Blocker 
Turn on Firefox or any Ad blocker you trust.
Firefox App Store
Firefox Focus App Store 
It has decent tracking protection and dark mode inbuilt for converting normal websites with the smart invert feature found in iOS accessibility (triple-click home/lock button) great at low light environments. If you like having Dark Mode everything, you could give the following article a read written by me.
Save your Eyes in Digital Life!
In 21st century we have been surrounded by screens everywhere & excessive dependency on digital lifestyle could lead to…medium.com
 
Search Engine
If you value your privacy, just stray away from big brother corporations like Google, Amazon, Facebook as their best interest is to collect as much information as possible like creating a profile or fingerprinting the user as much as possible. So they could serve you better-targeted ads on their platform like Gmail, Facebook, Amazon Google product ads, Youtube, Instagram, Google Search and Google Ad platform like DoubleClick, Google Ads, etc.
DuckDuckGo — Privacy, simplified.
The Internet privacy company that empowers you to seamlessly take control of your personal information online, without…duckduckgo.com
Switch to DuckDuckGo, they offer a transparent business model of how the search querying works and what information they collect, you can’t have an account with personally identifiable data. Though you can have an Anonymous Cloud Save user ID generated for your settings to be synchronized across various devices.
 
Hosts file
Overview:
A hosts file is used by Operating Systems to store a list of domain records with designated IP addresses to instantly make a connection request between client and server.
 Windows 10 Host file
This could be used to redirect or override a specific domain name with the specified IP address.
So even if your browser requested “reddit.com” and you have altered this domain in your host file to point towards a different IP address, the O.S would not consult with external DNS provided by your Internet Service Provider(ISP). It would just refer its local Host-based DNS table(host file) for navigating network requests. Every tool could be used for something different which it wasn’t designed to do, network administrators or tech geeks like yourself would utilize this architecture for specifying the ad domains to loop-back IP addresses like ’127.0.0.1’ or ‘0.0.0.0’. This IPv4 address is reserved for network testing and we could just loop through the ad domains at our network layer.
Below is the list of community sourced hosts file, which is always updating for incorporating new security flaws, privacy rules, blacklisting ad domains etc.
O.S File Path
Fairly easy to configure and block hosts of ad networks directly.
- Mac: /private/etc/hosts file path
- Windows: C:\Windows\system32\drivers\etc\hosts file path
- Linux: etc/hosts file path
- iOS: etc/hosts file path (iOS Jailbreak required)
- Android: etc/hosts file path and tutorial. (Android Root required )
For more information on Windows OS Host file path, read this article, also on Linux OS please visit this website.
Modifying Network HOSTS file on O.S
Modifying hosts file on our system to effectively block network connections.medium.com
Hosts file
•	Windows, macOS, Linux distros : uBlock Assets Link, Personal Host file
•	Android Rooted: AdAway App Link
•	iOS Jailbreak: UHB Adblock list Reddit link. Which blocks about 3000+ blacklisted hosts.
Good subreddit for all things Jailbreak
P.S: If you want the whole list of my blacklisted domains, I’ll add my repository directory /sense-setup/ads/hosts if anyone wants to have all of those settings.
SensehacK/sense-setup
My workstation overall setup. With the current version of VSCode as of this writing (1.22.1), you can find your…github.com
 
DNS
DNS is the mediator between your Operating System and ISP controlling how the network requests get routed within the web. You could use it as your advantage to blacklist specific domains thus eliminating ads, hardening security and preserving privacy all with just a few steps.
Online DNS (Easy)
You could opt for an Alternate DNS server that blocks the ad networks while querying the domain names and doesn’t return the blacklisted networks.
This article better explains how to achieve this if you want to go for this route.
Blocks Ads with Your Router Using an Ad-blocking DNS Server
Ads can be annoying we all know that, granted it’s still good to support sites you visit some of the latest ads have…smarthomeflow.com
Pi-hole (Intermediate)
Pi-hole is based on Raspberry Pi which runs the Raspbian O.S and Pi-hole filters, blocks, intercepts all of the network traffic when your router is configured to Pi-hole DNS Server.
A black hole for Internet advertisements.
Home
Network-wide protection Instead of browser plugins or other software on each computer, install Pi-hole in one place and…pi-hole.net
AdGuard Server (Expert)
If you want granular control over every aspect of the network, look no further as AdGuard would provide advance features that Pi-hole doesn’t include them in default release and needs more dependency management with learning more about the tool. In an enterprise, AdGuard would serve far superior tools in terms of saving time for network and system administrators for enforcing new domain level network rules. GitHub
AdGuard Home
AdGuard Home is a network-wide software for blocking ads & tracking. After you set it up, it'll cover ALL your home…adguard.com
 
YouTube
  Left: Youtube Right: Youtube + (uBlock Origin) | O.S, Browser: Windows 10,Firefox Nightly
Web
Browsers like Firefox, Safari, Microsoft Edge with normal adblockers like uBlock Origin will block 99% ads and also would prevent analytics collected by big brother. As you can see in the screenshot above, about 15% of the network requests are blocked on YouTube alone.
  Left: Youtube, Right: Youtube + (Vanced)
Android
Vanced YouTube App: Complete package with most of the YouTube premium features built-in like Picture in Picture (PIP), background music, enhanced privacy and no ads. You would need to install a small helper service to actually log in with your Google account.
  Left: Youtube, Right: Youtube + (Cercube)
iOS
Cercube for YouTube: Modded iOS YouTube for disabling ads on YouTube.
Reasons for iOS Jailbreak are plenty and just a recent post of disabling in App pop-ups regarding YouTube Premium Trial garnered so much attention.
NoYTNo Reddit Link
 
Spotify
  Left: Spotify, Right: Spotify Premium + (uBlock)
Web
Disabling Spotify ads on the web is very easy, if you’re using uBlock Origin it disables it automatically. Even though I have subscribed with Spotify Premium, I still keep uBlock Origin turned on as it makes sure Spotify isn’t tracking me with sending network requests to Google, Microsoft & Amazon servers for analytics.
Paying for the subscription doesn’t stop them tracking their end users with different types of analytics like device type, usage, network statistics, geolocation, other third party cookies from Google, Amazon, social media websites to deliver personalized, predictable ads to drive your subconscious mind with targeted opinions towards organizations based on your history of searches, websites, social media interactions to deliver you content pertaining towards your categorized profile. 
Eg. Internet Users who are fanboys of U.S.A’s president could be targeted with “Earth is Flat” theory content in their internet feed. This is just the gist of possible applications with analytics and tracking users. 
Privacy shouldn’t be just a Myth.
COVID-19 is real, So is Climate Change! 
Unlike Earth being FLAT.
Desktop
 
There are even comprehensive guides to disabling Spotify ads on Desktop.
Mac OS: 
MuteSpotifyAds
Windows OS: 
Spotify-Ad-Blocker
Smartphones
iOS and Android also have few modded Spotify apps to avoid ads & utilize premium features like option to play any song rather than just shuffle play. Use at your own discretion though as Spotify bans user accounts which tries to circumvent ads served by the application.
If you like hip-hop, you can head over to my personal Spotify playlists. I still try to discover new music everyday and broden my personal music genre via last.fm .
sensehack
We and our partners use cookies to personalize your experience, to show you ads based on your interests, and for…open.spotify.com
 
Router Ad Blocking
Add 10–15 blacklisted ad domains to the block list of the router’s admin page which will permanently block network requests from leaving your local LAN leading to lesser ads and better privacy depending on your security model.
Disabling few giant ad domain hosts & certain analytics hosts leads to significantly better User Experience overall while saving bandwidth and processing time on your mobile phones. The free game you downloaded won’t bombard you with video ads, fullscreen ads or let you watch a video to just give you bogus points to grind your way to unlock certain things in the game. I truly disdain freemium model, below video by Vox shares some great insights about it.
Every router’s configuration would be different so you would have to navigate in the admin panel of your home router and work accordingly. I would suggest making a backup of your router settings just in case if anything goes awry you could always restore to your previous settings.
Link of blacklisted domains: Reddit Thread
It works great for every device connected to the Wifi Router, as network requests filtered using blacklisted hosts won’t actually send or receive IP packets . Although I haven’t tried testing it extensively on the Xbox Dashboard which displays ads on my Xbox homescreen even though I’m a long term subscriber of Gamepass Ultimate. If you like games, Xbox Gamepass is like Netflix of games.
Also I would update my article if I get to block the ads on my Xbox but frankly I don’t mind them ads as long as Xbox Live dedicated servers are up and running even during this COVID-19 pandemic. Maybe they can donate the extra ad revenue towards betterment of humanity. 
We all know Gates foundation are actively helping humanity for several decades now. If companies which display ads could dedicate certain % of their ad revenue towards helping the world be a better place, surely be whitelisted for displaying ads under my home network configurations.
 
In conclusion, ad blocking is great practice for clutter free experience but it harms the publisher to deliver quality product whilst disabled ads lead to less revenue culminating in deteriorating quality of the ultimate products. 
So I would wholeheartedly recommend whitelisting certain websites or products which you like & has a decent UX even with ads. Also support them via subscriptions or contributing to their Patreon which in turn makes up for their ad revenue.
For content writers or makers, please follow a good ad guidelines on your website or content experience which won’t blast users with signup newsletters, auto-playing videos or displaying popups/alerts of sales, banners, and chatbots.
https://www.reddit.com/r/funny/comments/9q22c2/every_website_in_2018/
If the User Experience of your website would be riddled with ads and popups all over the screen then end users would probably turn to installing Ad Blockers and switching “ON” their Ad Blockers to disable these nuisances.
 https://www.reddit.com/r/dankmemes/comments/8efod5/theres_no_other_way/

Disclaimer: 
All views are of my own, nobody is sponsoring any of the aforementioned companies. Please follow my article at your own discretion. I haven’t turned on analytics or ads on this article, you can support me by giving me constructive criticism. The article is written solely based on my experience, which may change in foreseeable future as technology and opinions change everyday, although I tried to approach the subject matter as openly as possible.
Credits:
All logos are of their respective companies, I do not own any company assets like name and trademark.
Icons provided by FlatIcon
Cover images & screenshots by Sensehack
~ Kautilya Save


