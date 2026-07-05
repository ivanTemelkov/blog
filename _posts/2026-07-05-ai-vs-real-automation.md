---
layout: post
title: "AI Automation vs. Real Automation"
tags: [ai, automation, determinism, ai-agents]
---

# AI Automation vs. Real Automation

Recently, I have seen many videos showing how amazing Claude Code, Codex, or any other AI coding agent can be.

The pattern is often very similar:

1. Feed the AI Agent a bunch of badly organized Excel spreadsheets.
2. Let it suggest a better structure.
3. Let it create a cool web-based dashboard.
4. Let it publish everything automatically to a website.

> "How cool is that?"
>
> "I didn’t write a single line of code."
>
> "And then it becomes even cooler: I can create an automated task every week and let the AI Agent do it again for me."

**Wait a little!**

So instead of trying to **normalize the data** and create a small frontend **once**, so it can display the information every time in the same way, we should **consume tokens** every week and hope that the AI Agent does a good job every time?

That sounds less like automation and more like **repeated improvisation**.

AI is powerful, but it is **not deterministic**. Even with well-designed constraints, it can still **deviate**. Maybe not every time. Maybe not in a dramatic way. But enough to make me uncomfortable when the task should produce the same result every time.

This does not mean we should not use AI.

Quite the opposite.

We can use AI to help **normalize the data once**.  
We can use AI to help **build the frontend once**.  
We can use AI to help **create an ETL pipeline once**.  
We can use AI to help design a flow that keeps the data in sync.

But after that, the process should become **deterministic**.

The goal should not be to ask the AI Agent to solve the same problem every week.

The goal should be to use the AI Agent to help us build a system that solves the problem reliably every week.

That, to me, is the difference between **AI automation** and **real automation**.