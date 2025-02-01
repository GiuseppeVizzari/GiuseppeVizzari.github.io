---
title: 'What goes around comes around, or unsolved issues sooner or later exact their toll'
description: "."
date: 2025-2-1
permalink: /posts/2025/2/What-goes-around-comes-around
tags:
  - web
  - LLMs
  - distillation
  - poisoning
  - robots.txt
---

In my last post I wrote that I was noticing a **growing resentment about AI in general**, although specifically the target is generally represented by commercial initiatives based on LLMs. Their ways of operating would make proud Mark Zuckerberg and his motto "move fast and break things"... and of course, Meta is clearly part of this game as well.

This week has been particularly lively and eventful, with a _new kid on the block_ of commercial LLM based chatbot services: **Deepseek launched an "open weights Reasoning model"** (I feel the urge to **talk about the term reasoning for LLMs**, but that will need to wait) and made it available through web and mobile phone applications. What made this launch particularly intriguing were:
* **The astonishing cost efficiency**: [Deepseek disclosed that its operational costs](https://www.msn.com/en-us/money/other/deepseek-ai-cost-less-than-6-million-to-develop-heres-why-meta-and-microsoft-are-justifying-spending-billions/ar-AA1y8Ud7) are orders of magnitude lower than OpenAI's estimates for running its larger ChatGPT models;
* **The use of non-cutting-edge hardware**: Deepseek reportedly did not rely on the latest and most expensive Nvidia GPUs.
* **Accusations of service misuse**: [OpenAI swiftly accused Deepseek of improperly using its services](https://www.nytimes.com/2025/01/29/technology/openai-deepseek-data-harvest.html) to extract and distill information, violating OpenAI’s terms of service;
* the fact that **the company is Chinese**.

The first two points caused an understandable shock in the stock market. A company's stock value is basically a concrete representation of the current collective expectations about the revenues that company will provide to shareholders in a relatively limited time frame. It's therefore really clear why the stock value of many companies dropped as a result of this news. After all, the value of many of those stocks had grown incredibly in the last few years, to the point of being considered by several analysts the next bubble. Ironically, there is no independent verification of Deepseek’s cost estimates or its claim of using less expensive hardware. But that's the market, and no, the market is not always right.

The third point - the accusation of having distilled information from OpenAI's models - is the most fascinating to me. It highlights at least two types of ideological stances.

<figure>
  <img src="https://pixabay.com/get/gd21d9151991dc62623edaf0aa8ac372096c7ad5fb3afdae0ee6dbfc84c9b4da03670193429c9fe5920794c09d4ff044e_640.jpg" alt="A car crashed"/>
  <figcaption><a href="https://pixabay.com/photos/crash-car-car-crash-accident-1308575/" target="blank">A Pixabay photo</a> suggesting that it's not always a good idea to move fast and break things.</a>.</figcaption>
</figure>

For one, OpenAI and other major LLM developers have trained their models using massive amounts of data scraped from the internet, often disregarding terms of service and possibly even breaching **copyright laws**, not just terms of service in a contract among a client and a provider. There are ongoing and very relevant lawsuits questioning the legality of such practices, particularly regarding _fair use_ (by the way, do yourself a favor and read what the sadly deceased [Suchir Balaji thought about GenAI and fair use](https://suchir.net/fair_use.html)). I suspect that the comparably larger outrage in this case is due to the fact that the Deepseek is a Chinese company (the fourth point in my list), whereas OpenAI is an American one. With reference to the "moving fast and breaking things" tendency, these companies don't seem to be acting in a fundamentally different way, though. [Someone also commented that "karma is a bitch"](https://garymarcus.substack.com/p/openai-cries-foul), or (using a quote of Chinese roots) "Don't do unto others what you don't want done unto you".

<figure>
  <img src="https://upload.wikimedia.org/wikipedia/commons/8/83/Mother-of-the-Lake.jpg" alt="A (real) tar pit"/>
  <figcaption>It is always nice to lear things, like <a href="https://en.wikipedia.org/wiki/Tarpit_(networking)" target="blank">metaphors used in networking</a>. Picture by <a href="//commons.wikimedia.org/w/index.php?title=User:Jw2c&amp;action=edit&amp;redlink=1" class="new" title="User:Jw2c (page does not exist)">Jw2c</a> - <span class="int-own-work" lang="en">Own work</span>, Public Domain, <a href="https://commons.wikimedia.org/w/index.php?curid=7557054">Link</a></figcaption>
</figure>

Now, you probably read about these events already, and with more interesting/detailed/intelligent comments than mine... but I want to connect and an additional bit, that you probably missed in all this commotion. Just few hours before the Deepseek news, ArsTechnica [posted about a sort of server-side malware targeting crawlers that ignore robots.txt](https://arstechnica.com/tech-policy/2025/01/ai-haters-build-tarpits-to-trap-and-trick-ai-scrapers-that-ignore-robots-txt/), a tool (and approach) to trap and trick AI scrapers that don't respect the request not to index areas of a website, ignoring the <code>robot.txt</code> file in the server. The post is very interesting, and reports parts of an interview with the person that developed the so called "tarpit" trick. The approach does not just cause inconveniences to the crawler but it also injects information that could poison the training process. Of course, OpenAI said that they have already developed countermeasures to these poisoning attempts, but it is clear that response to their MO (due to the grey area in which they are operating the acronym seems particularly appropriate) has moved beyond courts of law, some people are taking the matter in their hands directly. So, the general sentiment has changes, and besides hopes, enthusiasm, and fear, AI (or, more precisely, AI companies) has also started to generate genuine hostility, even hatred. This is a bitter consideration for me, and for the portion of the academic world that is working in AI, that will need to carry part of this burden.

<figure>
  <img src="https://images-na.ssl-images-amazon.com/images/S/compressed.photo.goodreads.com/books/1353400616i/13587160.jpg" alt="The cover of Morozov's 'To Save Everything, Click Here: The Folly of Technological Solutionism'"/>
  <figcaption>It is worth suggesting that, to some extent, these events are very much related to <a href="https://www.goodreads.com/author/show/4113527.Evgeny_Morozov" target="blank">Morozov's books</a>.</figcaption>
</figure>

More broadly, these conflicts reflect unresolved tensions in the digital economy and in the development of the complex socio-technical phenomenon that is the Internet. Once again, these events are somewhat reminiscent of the controversies that had arisen between content producers and social media companies (something that had a role in the rise of the "click bait" phenomenon). The Internet is a very complex ecosystem, and due to its size, spread, and penetration in human activities it has reached a huge relevance, although - paraphrasing Morozov - it did not __save everything__. It did change it deeply. Within this process, sometime curious, bizarre, sometimes grotesque statements have been uttered very seriously, but often instrumentally, like ["ad-blockers will kill the Internet"](https://www.newsweek.com/2016/02/12/ad-blockers-will-kill-internet-421333.html).

We are still grappling with unresolved issues, and time continues to bring them back to our doorstep. The real question remains: will we finally address them, or just wait for the storm to pass—again?
