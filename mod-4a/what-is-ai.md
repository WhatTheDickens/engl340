---
title: What is Artificial Intelligence?
layout: default
parent: Artificial Intelligence
nav_order: 2
---

# What is Artificial Intelligence?

To suppose that we can talk meaningfully about something called "artificial intelligence" is to assume that we can take, as our starting point, something we already understand, called "intelligence," and ask whether it's possible, or what it would look like, to replicate it "artificially."

But far from understanding intelligence, we don't even have an agreed-upon definition of it&mdash;any more than we have agreed-upon definitions of such related words as "thinking," "mind," and "consciousness."

What we do have, accompanied by both extravagant claims for their efficacy and vehement calls to resist or severely regulate them&mdash;sometimes issuing from the same source&mdash;are computer systems and interfaces *presented to us* as exhibiting or employing artificial intelligence (AI for short). Sometimes these systems and interfaces are said to exhibit or employ a specific variety of artificial intelligence known as "generative artificial intelligence"&mdash;GenAI, for short.

AI and GenAI are thus brute, increasingly inescapable facts of current social reality at the same time that "AI" and "GenAI" are terms without clear, or perhaps any, conceptual content. This may be part of what authors Emily M. Bender and Alex Hanna have in mind when they write, in their book *The AI Con: How to Fight Big Tech's Hype and Create the Future We Want*,

> To put it bluntly, "AI" is a marketing term. It doesn't refer to a coherent set of technologies. Instead, the phrase "artificial intelligence" is deployed when the people building or selling a particular set of technologies will profit from getting others to believe that their technology is similar to humans, able to do things that, in fact, intrinsically require human judgment, perception, or creativity. <!-- p. 38 -->

This isn't to say that the technologies lumped together and marketed as AI aren't, individually, powerful and potentially valuable. The varieties of what Bender and Hanna prefer to call "automation"&mdash;such as automated decision-making, classification, recommendation, transcription/translation, and text/image generation systems&mdash;all have their uses, though their usefulness must be balanced against their proven and potential harms, discussed in more detail later in this module. Moreover, the research that makes these systems possible, in areas such as machine learning, natural language processing, and statistical inference, is rigorous and well defined.

What's undeniable, however, is that a critical understanding of these systems, and the research behind them, requires that we consider the impact of treating them as though they're approaching, or have already crossed, the line between machine and human. And it requires that we consider, as well, whose interests are served by presenting them in that light.

<!-- But in fact AI has a long history. The article "[Artificial Intelligence](https://plato.stanford.edu/entries/artificial-intelligence/#HistAI)" in the *Stanford Encyclopedia of Philsophy* traces its roots to Aristotle (who can be "credited with devising the first knowledge-bases and ontologies") and shows us the seventeenth-century French philosopher Descartes considering what distinguishes machines from humans.

In the context of modern computing, 

Is it possible to create machines that think? In the mid-twentieth century, the mathematician Alan Turing raised this question only to dismiss it as meaningless and propose, instead, that we consider an "imitation game" in which a human would try to determine whether they were conversing with another human or with a machine. 

A machine that can make itself sufficiently indistinguishable from a human to its human interlocutor is said to have passed the "Turing test."

how we might know that a machine was 

leave a human interlocutor unable to distinguish between itself and another

proposed a thought experiment skirted this question while proposing a test&mdash;since known as the "Turing Test"&mdash;for whether a machine could successfully imitate thought, leaving a human interlocutor uncertain whether they were conversing with a machine or another human.

-->

<!-- The recent showering of media attention on artificial intelligence&mdash;AI for short&mdash;and especially on generative artificial intelligence&mdash;GenAI&mdash;might make these -->


<!-- Eliza -->

Although there's no universally accepted definition of "artificial intelligence" in computing, the term is commonly used to describe one or more of the following:

- an area of research within computer science
- a property that some researchers claim (controversially) belongs or could belong to certain computer systems
- a set of technologies for generating new content (text, images, sound, etc.) from existing content

The last item on that list has given rise to the term "generative artificial intelligence" or, for short, "GenAI." While GenAI isn't new, it suddenly seems to be everywhere: not only in free-standing tools with names such as ChatGPT, Claude, Gemini, Copilot, DALL-E, and Midjourney, but also, increasingly, as an affordance built into other tools, such as search engines, word-processors, image editors, email and messaging interfaces, mobile apps, coding environments, websites, cars, and home appliances.

In this module, we'll make some use of GenAI and consider some of the ethical concerns currently being raised around its impact on society and the environment. 

But first, it will be helpful to put GenAI and artificial intelligence (AI) as a whole in some historical perspective. Data scientist William J.B. Mattingly's series of videos on AI and machine learning is a good place to start. Watch the first video in the series, below, to get a brief introduction to how artificial intelligence fits into the larger history of computing.

<iframe width="560" height="315" src="https://www.youtube.com/embed/G6cW5JybUPU?si=Ky9-pDmMc_9zqtmv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## A few key terms

The definitions below have been adapted from José Antonio Bowen and C. Edward Watson, *Teaching with AI: A Practical Guide to a New Era of Human Learning* (John Hopkins University Press, 2024) and *Intro to AI*, a newsletter distributed by [*MIT Technology Review*](https://www.technologyreview.com/).

- **Artificial Intelligence (AI):** Depending on context, this term usually refers to an area of research within computer science, a property that some researchers claim (controversially) belongs or could belong to certain computer systems, or a set of technologies for generating new content (text, images, sound, etc.) This isn't an exhaustive list.
- **Expert Systems:** rules and logic programmed into a computer to anticipate a wide range of possible scenarios.
- **Machine Learning:** The use of probability and statistics to find patterns in huge quantities of data and generalize from these. Recommendation algorithms such as those used by Netflix, YouTube, and Spotify rely on machine learning, as do search engines, social media feeds, and voice assistants like Siri and Alexa.
- **Deep Learning:** Super-powered machine learning that uses massive datasets and large neural networks, and that requires a great deal of computing power (sometimes called "compute.")
- **Neural Networks:** Computing systems designed to emulate the neural connections in the human brain. The "neurons" in the network are connected by complex mathematical equations. When a new piece of data (a new image, for example) is passed through a neural network, it moves through the layers of the network and outputs a result. A **trained** neural network, aka a **model**, has learned through trial and error to reproduce patterns in its training data and produce (hopefully) correct answers.
- **Foundational Models:** Neural networks trained with a large data set using machine learning techniques that mimic human trial and error.
- **Large Language Models (LLMs):** Foundational models focused on language. Built on deep-learning algorithms that are trained on enormous quantities of text, they're able to predict which words are most likely to appear together in a sentence or paragraph and generate textual content that sounds or reads like what a person might say or write.
- **GPT:** Generative Pre-trained Transformers. Foundational models and LLMs all use GPT architecture.
- **Parameter:** an internal variable in a neural network that can be tuned or adjusted to change the output.
- **Diffusion Model** A type of foundational model used to create images and video.
- **Alignment:** The work that humans do to ensure that an AI system does only what users want it to do.