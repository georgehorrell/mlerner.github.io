---
layout: post
title: 'Getting started in Bug Bounty Hunting'
date: '2019-12-18 00:00:00Z'
categories: post
tags: 
- Computer Security
---

Last week my first vulnerability was resolved and disclosed on HackerOne! The adrenaline I felt when I found my first vulnerability has been hard to replicate, and I have kept searching for new issues in my free time. Before I moved past that initial excitement, I wanted to stop and write a bit about my journey into bug hunting so far, what it is, and advice on diving deeper into it (if the reader was so inclined).

For context, over the past couple of weeks I have been participating in a few bug bounty programs for fun and profit. These programs are started by companies large and small on platforms like [HackerOne](https://www.hackerone.com) or [BugCrowd](https://www.bugcrowd.com) (these two are the big games in town). Companies like Google, Facebook, and others do this to incentivize "ethical hackers" (hackers who use their powers for good, not evil) to find vulnerabilities in their software. Many of these programs focus on a company's web presence, but a few also cover their API, mobile, and desktop apps.

I initially decided to start hunting after learning more about web vulnerabilities while playing and practicing for CTFs. I realized I was fairly good at solving this category of challenges given my background in building web applications and "cloud" infrastructure (an area where some of the more complex challenges head).

I am still far from the top of the bug bounty leaderboard, but a few resources along the way have been important in helping me grow my skills:

- If you are new to bug bounty hunting and learning about web vulnerabilities, I highly advise the [Hacker 101 content](https://www.hacker101.com/videos) and [accompanying CTF](https://ctf.hacker101.com/). You'll learn about a few of the more common vulnerabilities that you may have heard about in passing, like cross site scripting or SQL injection, but also a smattering of the more complex ones. Unlike a traditional CTF environment, you can take as much time as you want solving the accompanying Hacker101 challenges, which come in a variety of difficulties. A nice side effect of hacking on their CTF is that you will earn points towards an invite for a private program on HackerOne (this naming is somewhat straightforward - a "private" program is one where you need to be invited before you can submit bugs. Private programs generally have fewer hackers, so the odds of finding a vulnerability with high impact are tilted more in your favor).
- There are more than a few books about finding web vulnerabilities. I read two: [The Web Application Hacker's Handbook](https://www.amazon.com/Web-Application-Hackers-Handbook-Exploiting/dp/1118026470) and [Real-World Bug Hunting: A Field Guide to Web Hacking](https://nostarch.com/bughunting). The first is a classic that almost everyone recommends, but the content is somewhat dated - unsurprising given that the books was released in 2011. On the other hand, the second book, _Real-World Bug Hunting: A Field Guide to Web Hacking_, is a great introduction to many different classes of bugs, complete with summaries of real bug bounty reports from HackerOne, as well as tips for how to find bugs in each subsection.

Once you've trained your skills up to a certain level and are aware of the different classes of bugs, I would suggest jumping right into searching for your first issue, along with your trusty friend Burp Suite. I decided to start my search by looking for bugs in an unpaid "Vulnerability Disclosure Program". The private programs you should have been invited to as a result of playing the Hacker101 CTF could also be a good place to start. While some in the security community advise against bug hunting in programs without cash rewards (they argue it devalues security work), I found my first few bugs there. Often times the fruit is lower-hanging, given that more experienced bug bounty hunters are poking at applications with large cash rewards.

After finding my first bug on HackerOne, the snowball of invites seems to have kept rolling.

On that note, I have thought a bit more about how to continue to sharpen my skills. In particular, I have been watching the livestreams of a few successful bug bounty hunters, including [@NahamSec](https://twitter.com/NahamSec) and [Jason Haddix](https://twitter.com/Jhaddix). They stream their "recon" process for discovering web assets that a company owns as well as the tools they use to perform common tasks. Their interactions with viewers have also been quite useful to see, in particular when someone asks "why didn't you try it this other way?". Another way I've been enjoying my new hobby is by reading new reports on HackerOne. When a company fixes an issue that a bug hunter finds, they will often agree to disclose the report so that others in the community can learn from the findings. I'm actively looking for new ways to learn more about the space, and I think the importance of continued learning and the friendliness of the community have succeeded in pulling me in.

Until next time, happy hacking!
