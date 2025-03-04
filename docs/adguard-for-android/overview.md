---
title: Features overview
sidebar_position: 1
---

:::note

This article covers AdGuard for Android, a multifunctional ad blocker that protects your device at the system level. To see how it works, [download the AdGuard app](https://adguard.com/download.html?auto=true)

:::

> Disclaimer: AdGuard for Android is not to be confused with AdGuard Content Blocker. AdGuard Content Blocker is an app available in Google Play that has truncated functionality to meet restrictions imposed by the store. AdGuard for Android, on the contrary, is a powerful application to block ads, manage applications, and perform other roles that will be described in this article. The only place it can be downloaded from is [the AdGuard website](https://adguard.com/adguard-android/overview.html).

## Ad blocking

Any ad blocker's main purpose is to block ads, and for the majority of AdGuard software ad-blocking algorithms are mostly the same. The mechanism of filtering ads is described [here](/general/ad-filtering/how-ad-blocking-works).

![Ad blocking](https://cdn.adtidy.org/public/Adguard/Blog/manifestv3/adblockingworks.png)

The ad-blocking feature is pretty obvious in its concept, but there are some points worthy of a separate mention. Most importantly, AdGuard works as a universal filter sifting through your apps traffic and deciding what to do with this or that web request. The whole process is managed by filters — lists of special rules. The program has a default and constantly updated set of filters but you can also add your own filtering rules and filters to this set.

Most mobile ad blockers for Android use this principle, but what is pretty much the whole app in their case is only one of the many features for AdGuard. Read [this comparative article](https://adguard.com/en/blog/adguard-vs-adaway-dns66.html) to learn the differences between AdGuard and other ad blockers.

## Filters

The program uses a lot of different filters, our own and third-party ones, sorted by language and their purpose. For example, filters in the Annoyances category are very different from the language-specific ones.

![Filters *mobile](https://cdn.adtidy.org/content/kb/ad_blocker/android/features/filters1.png)

Find out more about all the filters available for AdGuard products by reading their descriptions in the app or [this comprehensive article](/general/ad-filtering/adguard-filters).

## Custom filters

![Custom filters *mobile](https://cdn.adtidy.org/content/kb/ad_blocker/android/features/custom-filters.png)

AdGuard allows you to create your own custom filters, using the same type of rules that we have in our filters. If you want to try your hand at this, we would recommend studying [the article on creating your own ad filters](/general/ad-filtering/create-own-filters) which describes the AdGuard rules syntax in detail and provides plenty of examples.

> Tip: use the Import feature to transfer your rules to a different device.

## HTTPS filtering {#https-filtering}

Nowadays almost all websites work via HTTPS, the web protocol where the last S letter stands for "secure". It happened so that most advertisers use this protocol as well, this is why [HTTPS filtering](/general/https-filtering/what-is-https-filtering) is really crucial for a modern ad blocker.

![What is https](https://cdn.adtidy.org/public/Adguard/Blog/https/what_is_https.png)

To be able to filter HTTPS traffic, AdGuard needs to install a certificate into your device's user storage. On older versions of Android OS this was done automatically during the onboarding process or later via AdGuard settings, and it only required a couple of taps. On Android 11 and later automatic certificate installation is no longer available. Now you need to install the certificate manually.

Here is the installation instruction:

1. Go to the app's main screen and tap *Turn on* next to the *HTTPS filtering is off* message (it will be highlighted in orange if the AdGuard certificate is not installed yet).

2. A new screen will appear, tap *Next*, *Next* and *Save it now* when prompted to download the AdGuard certificate.

3. After the certificate is downloaded, you will see a new screen. Tap *Open security settings*.

4. This will bring up system settings. Scroll down to *Advanced*, open it and then tap *Encryption & credentials* (these settings may be called variously on different devices — the main thing is to choose advanced security settings).

5. Tap *Install certificate* and then *CA certificate*.

6. A warning message will appear. Read through it and tap *Install anyway* to proceed.

7. Select the recently downloaded AdGuard certificate. A *CA certificate installed* toast message should show up.

8. The AdGuard certificate is successfully installed and HTTPS filtering is working now!

> If you update from Android 10 to Android 11, there's a chance that the already installed certificate will still be accepted. Otherwise, the *HTTPS filtering is off* warning will appear on the main screen, highlighted in orange. So you'll need to go through the same process of reinstalling the certificate manually.

In case you have problems with the certificate installation, read [this article](../solving-problems/manual-certificate) or contact our support team at support@adguard.com.

> **We want to emphasize that AdGuard Ad Blocker will function without HTTPS filtering. However, it won't be able to properly filter ads on sites that use the HTTPS protocol (most of sites do that). So if you want to use the full functionality of the app and get the best ad filtering quality and processing speed, we strongly recommend you to activate HTTPS-filtering.**

## Stealth Mode

Many websites gather information about their visitors, such as their IP addresses, information about the browser and operating system installed, screen resolution, and even what page the user came or was redirected from. Some web pages use cookies to mark the browser and save your personal settings, user preferences, or "recognize" you upon your next visit. Stealth Mode safeguards your personal information from such data and statistics gathering systems.

You can flexibly adjust the work of Stealth Mode: for instance, you can prohibit the website to receive the search request you used to find it on the Internet, automatically delete both third-party and website’s own cookies, and disable location sharing in your browser that can be used to track your whereabouts.

To learn all the main features and options you can manage in the Stealth mode settings, [read this article](/general/stealth-mode).

![Stealth mode *mobile](https://cdn.adtidy.org/content/kb/ad_blocker/android/features/stealth-mode.png)

## Browsing Security

Phishing is a fraudulent online practice aimed at obtaining sensitive information like usernames, passwords, credit card details and such from internet users. This form of fraud, effected through spoof emailing and fake websites posing as trusted mediums like banks, social services etc., is causing more financial damage every year. As for malware (malicious software), it is as the name suggests — any type of software designed with the intent to damage the personal computer or other device it gets into. What once began as a prank now is a tool to steal confidential information from users and businesses.

![Browsing security *mobile](https://cdn.adtidy.org/content/kb/ad_blocker/android/features/browsing-security.png)

Fortunately, AdGuard's Browsing Security module protects you from visiting phishing and malicious websites. It also warns you about malware being downloaded onto your device. In case you want to learn more about Browsing Security, read [this article](/general/browsing-security).

> But note that AdGuard for Android is not an antivirus. It will neither stop the actual download of a virus nor delete the already existing ones. For the complete protection of your device, we recommend using AdGuard in tandem with a dedicated AV tool.

![Browsing security warning *mobile](https://cdn.adtidy.org/content/kb/ad_blocker/android/features/browsing_security_warning.png)

At the same time, we'd like to emphasize that your personal data is *not* transferred anywhere, and AdGuard does *not* know which websites you are visiting. The security check is not performed against an open web address (URL) but through hash prefixes (hash is a certain data structure that renders unambiguous each address added to the base). However, you can send us information on the websites you visit to improve the database, if you opt to. Learn more about AdGuard's phishing and malware protection.

# Control your apps

One of the main stated purposes of AdGuard for Android is to give users back the full control over their devices. With AdGuard, you can see comprehensive information about all web requests coming through your device. No app will be able to go online without you knowing.

## Apps management

In the Apps Management module you can choose which apps should have Wi-Fi or mobile data access, which will be filtered by AdGuard and which not. You can also change the background Internet access rules for your apps when the screen is locked. These settings can be applied to all installed apps at once or on the individual basis.

![Apps management *mobile](https://cdn.adtidy.org/content/kb/ad_blocker/android/features/apps-management.png)

You can find extra settings in the upper right corner of the Apps Management screen. They will help you fine-tune AdGuard for Android to your preference. For example, you can make the common settings applicable to each and every app, or select the apps which need a more detailed approach.

![Chrome *mobile](https://cdn.adtidy.org/content/kb/ad_blocker/android/features/chrome.png)

By tapping the icons, you will see a screen showing app-specific traffic to help you make more informed decisions. AdGuard is of help not only with ad filtering and privacy protection, it can aid your device function better, saving battery life and traffic as well.

## Filtering log

In the Filtering Log, you can directly observe all web requests made by browsers and apps. Thanks to this feature, you have full control over all processes on your device.

![Filtering log *mobile](https://cdn.adtidy.org/content/kb/ad_blocker/android/features/filtering-log.png)

You can block each request right there in one tap (or unblock it, if the request is already blocked). There's also detailed information about each request, although it is mostly aimed at the advanced users, particularly those who create their own filtering rules. We will be elaborating on it just a bit further below.

## User rules

As mentioned above, AdGuard for Android uses a set of filters to block ads. And then there is the User rules section that allows you to create and adjust your own filtering rules. It is located in the Settings tab of the AdGuard menu.

![User rules *mobile](https://cdn.adtidy.org/content/kb/ad_blocker/android/features/user-rules.png)

When you first install AdGuard, the User rules section is empty. To fill it with rules, you will need to understand the basics of the rules syntax. Don't worry if you are not familiar with it, here's a good place to start should you feel an urge to delve deeper into custom rules creation.

By the way, whenever you use Filtering Log to block anything, a corresponding rule will appear in User rules, so use it if you ever want to undo the blocking. And generally speaking, Filtering Log and User rules go together particularly well: you can use the former to monitor requests in order to build a correct rule for the User rules.

## DNS filtering

The DNS Filtering module allows to configure DNS settings on the user's device, including the chosen DNS server, DNS protocol, and DNS filters that block ads and trackers.

![AdGuard DNS](https://cdn.adtidy.org/public/Adguard/kb/DNS_filtering/adguard_dns_en.jpg)

A bit of a theory refresher: DNS stands for "Domain name system", and its purpose is to translate domain names into something browsers can understand, i.e. IP addresses. So, each time you go to a website, your browser sends a DNS request to a server, usually determined by your ISP. That server either redirects the request to another (upstream) server or replies with an IP address. If you use a special DNS server instead of a default one, it can send unsafe and potentially dangerous requests to the "void". Thus, the responses with the IP addresses won't be received and "bad requests" will be nipped in the bud.

DNS filtering has its own separate tab within the AdGuard for Android app home screen. Here you can choose which type of DNS you wish to use (it can be either regular DNS or high-security DNS — we will get to that later on) as well as enable DNS-level blocking.

## DNS blocking

DNS blocking is a standalone feature that complements AdGuard protection suite.

![DNS mechanism](https://cdn.adtidy.org/public/Adguard/Blog/android-features/DNS-mechanism.jpg)

There are two methods of DNS blocking:

1. Some DNS servers can block DNS requests to potentially harmful domains.
2. There is built-in DNS filtering that works right on your device and can block DNS requests, in addition to what's blocked by the selected DNS server.

How exactly does DNS filtering work? It has a special DNS filter which contains a large list of ad and tracker domains, which it uses in conjunction with User rules to recognize 'bad' requests. Every request is checked against this filter, and if there's a hit, instead of forwarding it to the DNS server, it is being rerouted to a 'blackhole'.

The simplicity of this approach is both a benefit and a disadvantage. The main advantage of this approach is that it's both battery life friendly and traffic-saving. Once a domain is blocked, it won't be requested again within an hour. The disadvantage would be the "roughness" of this method: specific URLs can't be blocked, only whole domains. Sometimes the only way to block ads by DNS is to add a rule that will break something at the same time. In this case, we just don't add this rule and the ad remains unblocked — because the alternative where the website does not work at all is even worse.

## DNS servers

But AdGuard for Android "DNS package" does not end just there. One of the useful perks is an option to select *absolutely any* DNS server to use. At your service is a list consisting of dozens of servers to choose from, from our own AdGuard DNS servers to other popular providers like Google DNS, Cloudflare and others. On top of that, if your favorite server is not in the default list, you still can enter its address manually and use it anyway. See the comprehensive list of popular DNS providers — you can find many DNS servers there and any to AdGuard with a tap of a finger.

There are several reasons to use a custom DNS server instead of one offered by your ISP by default. Some servers are faster, some provide ad blocking or parental control solutions, some enhance your privacy etc.

But DNS servers not only vary by function. Besides, they can also differ by supported protocol types. There are three main types of protocols that DNS servers work over: HTTPS, TLS, and QUIC. Correspondingly, there are DNS-over-HTTPS (DoH), DNS-over-TLS (DoT) and DNS-over-QUIC (DoQ). While the first two are standard protocols, the third (DoQ) is experimental, yet the most outstanding one. We'll describe it later. Choosing a DNS server from a trusted provider is essential to protect DNS traffic. When user's DNS traffic is safe, their privacy and security are increased, and it's easier to prevent eavesdropping and manipulation of DNS data via man-in-the-middle attacks (MITMs).

### DNS-over-QUIC

DNS-over-QUIC (DoQ) is a rather new encryption protocol and AdGuard DNS is the first public resolver that supports it. Unlike DoH and DoT, it uses QUIC as a transport protocol and finally brings DNS back to its roots — working over UDP. It brings all the good things that QUIC has to offer — out-of-the-box encryption, reduced connection times, better performance when data packets are lost. Also, QUIC is supposed to be a transport-level protocol and there are no risks of metadata leaks that could happen with DoH.

To learn more about DNS-over-QUIC, check out [this article](https://adguard.com/en/blog/dns-over-quic.html) dedicated entirely to it.

To enable DoQ in AdGuard for Android, perform the following steps:

* Open the app, then open the side menu
* Go to *Settings → DNS Filtering* and enable it
* Select any of AdGuard DNS servers from the list of available servers
* Under *Server type* choose *DNS-over-QUIC*

## DNS user filter

It is very much like the regular User filter, but for DNS requests.

![DNS user filter *mobile](https://cdn.adtidy.org/content/kb/ad_blocker/android/features/dns-user-filter.png)

You'll find DNS user filter at *Settings → DNS Filtering → DNS Requests blocking*. DNS User filter supports two types of syntax: a limited portion of AdGuard syntax and "hosts" syntax. You can read more about it in our Knowledge Base.

## Custom DNS filters

You can add any [custom DNS filters](https://filterlists.com/) or custom hosts lists. A useful feature considering how popular hosts lists are among Internet users.

![DNS filters *mobile](https://cdn.adtidy.org/content/kb/ad_blocker/android/features/dns-filters.png)

This option is available on the *Settings → DNS Filtering → DNS Requests blocking* screen.

## Proxy and TOR

A proxy server is basically another computer serving as a hub that processes your internet requests. You can set up AdGuard to route all your device's traffic through any proxy — and you'll be able to configure the whole thing right inside the app. And here is [an instruction on how to set up a proxy](../solving-problems/outbound-proxy).

> Some popular VPN providers offer an alternative way to use their service as a proxy. This can be used to run them alongside AdGuard in local VPN mode.

![Proxy settings *mobile](https://cdn.adtidy.org/content/kb/ad_blocker/android/features/proxy-settings.png)

Contrary to a popular opinion, using a proxy server is not just about bypassing access restriction to geoblocked resources. It is about security! If you are using a proxy server, intruders won't know what websites you visit. You can also use AdGuard along with the anonymity network TOR (we have already integrated AdGuard with Tor for your convenience!). Here is a [Wiki article](https://en.wikipedia.org/wiki/Tor_(anonymity_network)) where the whole concept of TOR network is nicely explained in case you wish to find out more.

## Extensions support

Userscripts (we also call them extensions) are basically mini-programs written in JavaScript that extend the functionality of one or more websites. Usually, you'd need some special userscript manager to add them, and it's traditionally more of a desktop thing. But with AdGuard everything is possible! Now you can add any userscripts by URL or load them from a file, and AdGuard will serve as a userscript manager and take care of the rest. Go to *Settings → Extensions* to enable some of the pre-installed extensions or to add custom userscripts.

![Extensions *mobile](https://cdn.adtidy.org/content/kb/ad_blocker/android/features/extensions.png)

By the way, you can tap any added userscript to see more details, and to reinstall or delete it.

## Compatibility with AdGuard VPN

The best kind of compatibility is when you install two apps and they just start working together. Presuming you already have AdGuard Ad Blocker installed, just download AdGuard VPN from Play Store (you can get there right from the ad blocker app, there's an item in General settings).

![Compatibility *mobile](https://cdn.adtidy.org/content/kb/ad_blocker/android/features/compatibility.png)

Both apps will detect each other and do everything that's needed for smooth joint work. All that will be left for you is to enjoy both ad-free Internet and the benefits of a VPN. It also works the other way around just as well: install AdGuard Ad Blocker on top of an already-running AdGuard VPN and you're good.

If you'd like to disable Compatibility Mode for any reason, it's very simple to do so from AdGuard Ad Blocker settings, just toggle the switch. Additionally, you can add AdGuard Ad Blocker and AdGuard VPN tiles to your device's notification bar and toggle them in one tap at your own will — thanks to Compatibility Mode the configuration will change immediately and silently.

## License

While some ot the features in AdGuard for Android are free, others require [purchasing a license](https://adguard.com/en/license.html). There are Personal (up to three devices) and Family (up to 9 devices), Yearly and Lifetime license keys. The premium version offers the following features to its users:
* Stealth Mode
* Browsing security
* Extensions
* Ad blocking in all apps (not only browsers)
* Custom filters

Read [this article](/general/license/activation) to learn how to activate the license key.

## Other features

There are too many features to describe them all in detail, so let us simply list them here:

* When you visit certain screens for the first time, there will appear tooltips that describe the purpose of that screen and its main features
* You can export or import AdGuard settings (for a faster switch between the settings profiles or to transfer your profile between different devices)
* Select an update channel, i.e. the mode in which the application receives its updates (stable release channel, less stable beta channel and raw ["nightly" channel](https://adguard.com/en/blog/nightly-builds/)
* By tapping a little battery icon on the main screen of the app you will get to the "Battery Usage" screen. System battery stats [are often wrong](../solving-problems/battery), so we decided to have our own, one that would reflect the real state of things
* You can change the app's language in the General Settings tab
