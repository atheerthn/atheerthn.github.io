---
title: "How criminals attack the games industry"
layout: post
date: 2016-02-24 22:44
image: /assets/images/markdown.jpg
headerImage: false
tag:
- gaming
- bot manager
star: true
category: blog
author: Jonathan
description: cybersecurity in online gaming
---
If you work in the video games industry, it's already obvious that security is a challenge, and criminals are a threat. But how much do you know about how the criminal economy works? What actually motivates them? What specific methods do they use? And how do they interact with one another?

If you already know the answers, we should talk -- no, seriously. But you'll also be interested in reading the new State of the Internet / Security report coming out this September, because there's a ton of useful information in it for the companies that already understand the threat but want to learn more about current patterns.

If you don't know much about the criminal economy, then you'll still enjoy the State of the Internet / Security report, but you can also keep reading this blog post for a primer on criminal economics.

## Criminal Economics 101

The first thing to understand about the criminals who attack the games industry is that they participate in a working, fluid, day-to-day economy that they manage completely themselves. In this economy, there is no regulation, there is only reputation. And it works -- in terms of financial incentives and operational structure. It takes place not only in shady private forums and marketplaces on the darknet, but anywhere criminals can communicate: Facebook, Discord, public messaging forums, and, prior to COVID-19, out in the open at conventions and gatherings.

![Markdowm Image1][1]
<figcaption class="caption">PA sample of the types of games where accounts can be purchased</figcaption>

The next thing to understand is how they operate. If you've worked in a modern enterprise, then you would easily recognize how things work. Cybercriminals have built informal structures that mirror the efficiencies of standard enterprise operations. They have developers, QA folks, middle managers, project managers, salespeople, and even marketing and PR people, who hype vendors and products.

### Let's look at bots as an example.

Bots are powered by servers, domain controllers, and a central ops hub that gives infected systems their commands. So criminals need infrastructure. And they get it -- from one another, and often from the public cloud providers. In fact, bots don't even have to be infected systems at all -- oftentimes, criminals will just purchase space on cloud computing platforms to perform their attacks. From there, the operational aspects closely mirror app deployment and enterprise product launches. Bots are coded and QA'ed. They are marketed and sold. Then buyers come back with feature or service requests, and the coders update, and put it back out there. From a marketing perspective, individual criminals build their reputations on data breaches and successful products. They put out info dumps for free to boost their own reputation and steal from and one-up one another to further build that reputation. And, believe it or not, they rely on customer service to maintain their base.

The image of a lone hacker in a basement seems quaint next to the facts.

And did we mention PR? Earlier this year, a major game launched with some pretty deep anti-cheat protection. The publisher in question is minority owned by a Chinese industry player. In response to this difficult-to-hack protection, the criminal industry put out its own version of PR, saying that the company had installed a "Chinese rootkit" on players' PCs. It was a ridiculous claim, but it caused this particular publisher a good deal of trouble with its community. All to pressure them into easing off on their built-in security.

Now, if the criminal operation seems oddly professional, the next question to address is: What are the criminals' goals? To clarify up front, this section will focus specifically on the goals of criminals, not necessarily other types of malicious actors such as angry players, cheaters, glory hackers (for the lulz!), and hacktivists.

The primary goal of most criminals is account takeover via credential stuffing. DDoS, either for ransom or to use as air-cover for other attack types, is another problem. But the low-hanging fruit for criminals are the accounts and the value therein. In the 2019 State of the Internet / Security report on web attacks and gaming abuse, Akamai published that we recorded 55 billion credential stuffing attacks over a 17-month period, and 12 billion of those targeted the games industry.

![Markdowm Image2][2]
<figcaption class="caption">Credential stuffing attacks by day during the reporting period</figcaption>

---

Criminals generally attack gaming accounts through leaked password lists. They'll speed through and hit the easiest-to-crack accounts first. This opening salvo typically targets accounts owned by players who reuse passwords and have not enabled multi-factor authentication. A quick YouTube search will turn up an absurd number of video tutorials on how to do this effectively against specific popular games. 

Once criminals access an account, they are looking for a few different things, but it's important to note that even fragments of accounts have value to a criminal once compromised. Criminals are looking for personally identifiable information (PII), which could help them move laterally into other valuable accounts. They're also looking for in-game items or currencies that can be dumped into another account, traded, or sold on secondary markets. There are also cases where the criminal will just "flip" and sell the whole account to someone who doesn't feel like grinding and wants to play the game.

![Markdowm Image3][3]
<figcaption class="caption">Verified Fortnite accounts with viable payment methods are sold on a darknet marketplace</figcaption>

Once a criminal has drained an account of value, they quickly move on to the next. And they continue to make significant profits doing so.
---
## What can you do about it?
---
There are a number of ways to protect against cybercriminals. Game developers and publishers employ a multilayered approach to combating them. Akamai doesn't pretend to solve every possible risk, but we're proud to be involved in the effort. We're particularly proud of the Bot Manager product line.

Bot Manager is not a silver bullet, but it is an excellent set of night-vision binoculars. It allows you better visibility into your environment, so you can see what's happening in your logs in real time. By tying Bot Manager into your security information and event management (SIEM) platform, you can churn out actionable intelligence that will empower your security teams to make critical business decisions on changes and processes in the moment. From there, your security teams can focus on the most effective ways to allocate their limited resources to combat security threats now, and in the future.

Thanks for reading! For more detailed information:
* [Read last year's State of the Internet / Security report on the games industry](https://www.akamai.com/us/en/multimedia/documents/state-of-the-internet/soti-security-web-attacks-and-gaming-abuse-report-2019.pdf)
* [Sign up to get the upcoming State of the Internet / Security report, available September 23, 2020](https://www.akamai.com/us/en/resources/our-thinking/state-of-the-internet-report)

---
[1]: https://blogs.akamai.com/GamingAttacksBlog1_8.19.png
[2]: https://blogs.akamai.com/GamingAttacksBlog2_8.19.png
[3]: https://blogs.akamai.com/GamingAttacksBlog3_8.19.png
