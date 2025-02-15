---
title: 'Enigma of reason reloaded: on the evolution of reasoning in computer science'
description: "On the evolution of the semantics of the term reasoning in computer science."
date: 2025-2-15
permalink: /posts/2025/2/Enigma-of-reason-reloaded
tags:
  - reasoning
  - LLMs
  - Computer Science
  - AI
---

If you read this blog you have already encountered a reference to a book titled [The Enigma of Reason, by Hugo Mercier and Dan Sperber](https://www.hup.harvard.edu/books/9780674237827). It took me some time to read it, probably due to the complexity of the matter, the depth of the discussion, that is based on scientific researches by the authors, and the distance between my background (Computer Science) and the discipline in which this work is set (Cognitive Science).

It's hard to summarize the book, that is very rich and thought provoking, but I would say that it is an investigation on rationality, not unlike the probably more famous [Thinking, Fast and Slow, by Daniel Kahneman](https://www.goodreads.com/book/show/11468377-thinking-fast-and-slow). Where Kahneman postulates the existence of two systems in our mind (System 1 being the fast, intuitive, and emotional, System 2 being the slower, more deliberative, and more logical), Mercier and Sperber propose a highly modular cognitive system, in which different specialized modules, typically of bayesian nature, have developed throughout our evolution. Reason is one of such modules, that developed late in our evolution, not so much to enable us solving abstract, logical problems, but rather to solve problems, and leverage possibilities, posed by living in groups. As a consequence, we also developed the possibility to make abstractions, develop formal mathematical and logical frameworks, even discuss rationality describing it in a quantitative way. But that is probably an abstraction, that does not really fit well the working of our cognitive system.

I don't know if I was able to provide a reasonable summary of the book, but anyway, consider reading it. It's really worth the effort and time.

<figure>
  <img src="https://www.hup.harvard.edu/img/feeds/jackets/9780674237827.png?fm=jpg&q=80&fit=max&w=800" alt="The Enigma of Reason, by Hugo Mercier and Dan Sperber"/>
  <figcaption><a href="https://www.hup.harvard.edu/books/9780674237827" target="blank">The Enigma of Reason, by Hugo Mercier and Dan Sperber</a>: I actually read an ebook edition, but I'm pretty sure the cover was different...</figcaption>
</figure>

In Computer Science and in Artificial Intelligence, the term **reasoning** (and probably I should talk about **automated reasoning**) also has a long history, with roots that definitely predate both the disciplines. Automated reasoning was probably an inevitable development of formal logic, and a significant portion of AI researches and results, those we refer to when we talk about symbolic AI or GOFAI, are essentially based in this line of work. Although probably no one would go as far as claiming that we reason similarly as a logic programming system, there surely are situations in which logic programming systems work very well, although they are not currently very trendy. It is no surprise that Knowledge Representation and Reasoning is a typical topic of interest for AI conferences, as well as a topic for sessions in their programmes.

LLMs and LLM based chatbots are now a much more popular topic of research, experimental application development, attempts to develop new systems, applications, services. We still need to understand the economical and energetic sustainability of LLM based products and services, and this will require some time. The simple, but extremely powerful, mechanism of operation of an LLM is sometimes summarized as "autoregressive token generation": essentially, given the textual prompt, the LLM iteratively (i.e. word by word, or token by token) predicts the next word, based on the information internalized during the training (I am honestly upset by the proliferation of new terms such as pre-training and... what, post-training?). Early experiments with LLM based systems revealed, although LLMs are mostly great at producing plausible continuations of phrases, and responses to straight questions (also called zero-shot prompts), they were not an oracle. They often made (and sometimes still make, despite the advancements from the earlier generations) factual mistakes, despite the linguistic plausibility of the overall result. It was also found out that, in particular in cases in which some mathematical calculation or simple logical (or commonsense) reasoning was necessary, **it was often effective to add an expression such as "Let's think step by step" to the prompt**. This sentence asks the model to "reason out loud" and to go through all the required steps to carry out the task. This discovery was instrumental in the definition of the so-called "prompt engineering", which is from my point of view a practice of defining and refining prompts to acquire the desired results from an LLM (engineering is probably excessive). The "chain-of-thought" prompt technique also led to a plethora of works trying to improve the LLM reasoning process, in a lot of different ways (some of which of "agentic" nature, something relating to [a recent post in my blog](https://giuseppevizzari.github.io/posts/2025/1/Agents-have-come-a-long-way)).

I'll tell you a secret: **I felt upset in using the term "reasoning" to describe the LLM elaboration of a response** to a prompt. At the same time, I eventually used the term anyway.

<figure>
  <img src="https://media.wired.com/photos/5cdefc28b2569892c06b2ae4/master/w_2560%2Cc_limit/Culture-Grumpy-Cat-487386121-2.jpg" alt="A rare picture of me judging myself after using the term reasoning for describing LLM response elaboration."/>
  <figcaption>A rare picture of me judging myself after using the term reasoning for describing LLM response elaboration.</figcaption>
</figure>

I usually pay attention and try not to anthropomorphize AI techniques or results.

However, it's probably part of the human nature to do that. I can surely remember [pareidolia](https://en.wikipedia.org/wiki/Pareidolia), our tendency (as humans) to give a meaningful interpretation on a possibly random stimulus, usually visual, so that one detects an object, pattern, or even meaning where there is none. And I often see faces in a lot of stuff.

Moreover, LLMs are terribly good at having you forget that you're interacting with a computer program. [Ethan Mollick's book](https://www.barnesandnoble.com/w/co-intelligence-ethan-mollick/1144159618) is full of examples in which this happens, and the author even suggests actively forgetting that behind the chatbot there's an LLM and think of being interacting with an intelligent, sentient entity.

Still, I'm upset with myself.

I've been doing research in AI, although not specifically in Knowledge Representation and Reasoning, for a long time. I am serving in the organization of scientific conferences on AI. It's not that I consider the term reasoning to be copyrighted, and that one needs to pay a royalty to the Knowledge Representation and Reasoning community. Certainly, we are going to have a problem in organizing the programme of conferences in which different papers might attribute extremely different semantics to the term reasoning... we should get ready to discuss as a community long standing traditions, implicit definitions, habits, and maybe tear them down. We should also somehow think back at the schema in Russell and Norvig's AIMA book: I used to think I was working in a quadrant where people were mostly trying to make agents acting rationally, but it seems that investigating how to build agents that think as humans might be the next frontier of AI.

I internalized that the term reasoning is stronger than a simple processing, that reasoning was generally a process preserving truth along its unfolding, assuring some property. It seems ironic that we get back to something that, at the same time, looks closer to human reasoning, being potentially prone to error, but also (from my point of view, and based on what I remember of Mercier and Sperber's book) only good at representing human post-hoc analysis of how a decision has been taken, for sake of justification or communication.
