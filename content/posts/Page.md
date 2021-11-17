---
title: Closing the tabs
date: 2020-09-15T11:30:03.000Z
tags:
    - blog
    - AI tools
author: Me
draft: false
description: The initial post
outputs:
    - html
    - json
hideSummary: false
searchHidden: true
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
cover:
    image: <image path/url>
    alt: <alt text>
    caption: <text>
    relative: false
    hidden: true
slug: closing-tabs-
---
## A beginning
There is a lot of stuff on the Internet. When I find something interesting I tend to leave a tab open, as an unsolved task, as something to get back to. Way too often I never get back but the tabs remain open. Silent, judging, unread. And even when do read them often I need to experiment, to save results in order to fully process the info. Thus this blog. 
For some time now the majority of my unclosed tabs are about AI tools, promises of actually helpful neural networks, articles scientific and readable. 
Here are the topics I plan to close the tabs about...

## AI writing assistants
[G2 grid (a square with Leader, contenders)](https://www.g2.com/categories/ai-writing-assistant) is awfully crowded. But all these tools are probably good for something and useless for others. I generally let Grammarly check my writing so we can assume that this whole blog is a practical demo of Grammarly as a corrector. But what if
1. I want my text to be rewritten as if it was written by a native speaker.
1. I want to generate a short text (fictional description) and edit it later.
1. I want text summarized “abstractively” (see extractive vs abstractive summarization).
1. I want the whole writing process to be as automated as possible (I have no idea what the process is really like).
1. I am looking for things I didn’t even think to solve with a tool.

I am going to leave most copywriter stuff outside the scope for now (write a press release, generate a daily Telegram post, etc). Maybe I’ll get back to it later.

I am going to try to test the tools, produce results and document the results here. 


## Content management and search using deep neural networks

Neural networks nowadays can understand the content. Or at least fake this understanding pretty well (see [Chinese room](https://en.wikipedia.org/wiki/Chinese_room)). This open possibility for a number of practical applications. Just for example, we can actually organize all our clutter in the Downloads folder or better yet or the content we sift through on a day-to-day basis.

And all the building blocks are actually there:
1. We can get a webpage from the chrome extension. 
2. Parse webpage and extract text, images (multimedia), metadata with trafilatura. 
3. Create a multimodal representation of the data using SBERT and other NN. 
4. Use weaviate or milvus to help us create a production-ready search application.

If I ever come up with a prototype with a system like this it will not only make my life a lot easier it will also close like 20 unread tabs in my browser (or let me close all the tabs and have the data well organized in the shiny new system)

## Content creation using neural networks

NN can restyle images. NN can generate images. NN can write music. But the music sucks, the images are limited and styling looks cool only for the first time you see it. Meta and Nvidia are talking a lot about digital avatars. About a way to create a digital twin for a person. What if our twins could do better than State-of-the-art "creative" NN, or at the very least what if NN could use our twins to create content that we want or like. Or maybe at least helpful for us specifically. As such, I plan to close some tabs about creating systems like https://tavus.io/ or using StyleGan3 for something practical or at least cool  https://www.youtube.com/watch?v=9QuDh3W3lOY

## Game system optimization

RL is fun. Multiagent game theory is math. Solving some games is a matter of throwing enough computing power at them. But what if we do not want to just solve a game. What if we want to design a game that is 
1. Interesting
2. Balanced
3. Has a sophisticated and tunable AI available

The framework for automating game system design is actually the same as for designing the agent who can play the game. It's just a matter of reinterpreting the parameters and throwing the computer power at it. At least in theory. What I want to know is what it is like in practice.


## Github repo analysis

A surprising number of people have in recent years asked me about the possibility of utilizing Jira, Confluence, Github data to optimize processes in teams. Honestly, I was only able to give general advice regarding text embedding and data representation. Then it occurred to me how much time I could have saved if I knew which repos have bugs, which project is about to close and which library is going to be mainstream in half a year. And for most open source projects is data is readily available. You just have to use well-known methods to analyze it. 
