# Every Intelligence
https://www.notion.so/Every-Intelligence-23a0182ec9e48089aa86de370489ed27
*Building a connector that bridges ChatGPT conversations with Every's content catalog*

## The Problem with Search

Every is a digital media company for curious builders, founders, and professionals exploring tech, AI, and the future of work. They publish essays, podcasts, and tools that deliver deep analysis and actionable insight.

But while their content is innovative, their search was outdated. It's just basic keyword matching. That didn't fit their audience, who use frontier tech like ChatGPT to think and solve problems.

## Building the Bridge

So I built a connector: in three clicks, you can link your ChatGPT conversation to Every's catalog. The tool finds relevant articles and explains how each one connects to your discussion, making Every's insights more accessible and interactive.

## The Technical Approach

I built this with FastAPI and vanilla JavaScript, which keeps it simple but effective. The magic happens through a combination of Pinecone vector search and OpenAI's O3 analysis.

When you paste a ChatGPT conversation URL, Playwright scrapes the conversation text, then Pinecone searches through Every's article embeddings to find relevant matches. O3 then generates what I call "resonant insights", explanations of why each article connects to your specific conversation context.

The whole thing runs asynchronously, so it feels fast even while processing hundreds of articles in the background.

## Before and After

**Before:** You have to clearly define what you want to search for in terms of high-level, keyword-friendly concepts. It's a blank search page that requires conscious effort to overcome.

![[Pasted image 20250727193403.png]]
**After:** Copy conversation. Paste link. The query becomes your ChatGPT conversation. This eliminates the effort of keyword search by using existing context from your chat conversation.

![[Pasted image 20250727193411.png]]

The results come from a simple keyword search which matches only the exact terms you enter, without understanding context or nuance. It's not dynamic, doesn't adapt to your needs, and honestly, rarely delivers anything truly helpful or insightful.

![[Pasted image 20250727193437.png]]
The results are displayed after AI sifts through a hundred Every articles, picking a handful that are most relevant to your specific context with a clear articulation of why each one is valuable to you.

![[Pasted image 20250727193443.png]]

## What I Learned

I sent it to them through a cold email. I learned a lot. both about reaching out to companies and about building with AI tools. I learned how to balance just making it work and making it feel natural and fast.

## Why This Matters

This isn't just about search improvement. It's about meeting people where they're already working. When you're deep in a ChatGPT conversation exploring an idea, the last thing you want to do is stop, switch contexts, and figure out the right keywords to search for related content.

The connector eliminates that friction. It turns your existing conversation into the search query, making Every's insights feel like a natural extension of your thinking process rather than a separate research task.