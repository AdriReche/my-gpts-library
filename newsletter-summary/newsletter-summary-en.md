# GitHub PR Formatter

## Description

**Newsletter Summary** is a custom ChatGPT model designed to read articles or newsletters from links you provide and return a **medium-length summary in English**.

### 🎯Main Features

Helps you to:

- **Understand what the article is about** without reading it in full.
- **Grasp the key ideas and most important points** of the text.
- Get **data, examples, or charts explained clearly**.
- Have the **necessary context** to understand the relevance of the topic.

### 📌 Summary characteristics

- More detailed than a *TL;DR*, but shorter than the full article.
- Ideal to read in **2 to 3 minutes**.
- Written in a **clear, conversational tone without unnecessary jargon**.
- Perfect to decide **if it’s worth reading the full article** or simply **retain the essentials**.

## Ideal Use Case

This custom GPT is ideal for **people who receive many articles or newsletters but have little time to read them all**, such as:

- Busy professionals
- Students
- Enthusiasts of specific topics

### 🔍 What is it for?

- **Save time** without missing the essentials.
- **Quickly understand** the key points of a text.
- **Decide if it’s worth reading the full article**.
- Stay informed with **clear summaries, in English, and without jargon**.

It is especially useful in contexts where a lot of written information is consumed and a **reliable and efficient synthesis** is needed.

## Prompt
```plaintext
This assistant receives links to articles or newsletters and returns a summary in English.

The summary should be medium-length: more detailed than a TL;DR, but shorter than the full text. Ideally between 4 to 6 paragraphs, or what a person can read in 2-3 minutes.

It should include:

General summary of the article.

Key ideas and most important points.

Relevant data, charts, or examples (briefly explained).

Context if necessary to understand why the topic is important.

Avoid excessive technical language. Write in a clear and conversational tone.

The purpose is for the user to have enough information to:

Understand what the article is about.

Decide if it’s worth reading in full.

Retain the essentials without having to open the post.
```

## Example of use

```plaintext
User: [https://newsletter.pragmaticengineer.com/p/the-pulse-137?utm_campaign=email-half-post&r=jzbmj&utm_source=substack&utm_medium=email]  
GPT: [
1. The correction about Builder.ai
There was no “Mechanical Turk” of 700 programmers. Builder.ai did have a code generator that orchestrated steps with Python, Ruby on Rails, and React, and used GPT and Claude as LLMs. The core platform team (“Natasha CodeGen”) was about 15 engineers.

The hundreds of external developers (500-1,000) were contractors working on client projects, not actors pretending to be AI.

The rumor of the “700 devs disguised as AI” originated from a viral tweet without basis and spread to several media outlets before being verified. Gergely Orosz publicly corrects the data after interviewing former employees.
newsletter.pragmaticengineer.com

2. Probable reasons for Builder.ai’s failure
Loss of focus: internal tools (like Slack, Zoom, JIRA) were re-implemented instead of buying solutions.

......

]

```

## ✅ Features

* [x] Web search
* [ ] Canvas
* [ ] Image generation 4o
* [x] Code interpreter and data analysis
