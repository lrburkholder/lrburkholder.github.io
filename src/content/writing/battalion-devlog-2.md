---
title: "Battalion Devlog #2 — WTF is Battalion, anyway?"
description: "The hypothesis behind a human-directed loop controller for AI-assisted software development."
date: 2026-11-23
---

*Originally shared on [LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:7498459037093642241/). Date here reflects the site migration, not the original post.*

Previously, I mentioned creating Battalion as a loop controller for AI-assisted software development. Let's talk about that in more detail.

What's a loop controller? A loop controller is an application that sits between you and an LLM, providing the loop of information from you and your environment (code, video of your cat, whatever) to the LLM and sending the LLM's answers back to you. VS Code Copilot is a loop controller stapled onto a text editor/IDE. Claude.ai, the web interface you use to talk to Claude, is a loop controller.

Every loop controller I'm familiar with looks and behaves very similarly, and they all seem to be designed to put power into the 'hands' of the LLM, not you the user. More automation, more subagents. But is that what makes good software? I'm not so sure, and so I'm building Battalion to test my hypothesis:

> If the human users are able to learn and stand behind the code that an LLM produces, the stakes that the users have in the produced product will make for better products.

Where did Battalion come from? At my day job over the past ~9 months, I've been building out "the Squad", a set of two dozen or so prompts designed to encapsulate the SDLC. Building code with the Squad has taught me quite a lot about where AI work ... works. But also about where it doesn't. Battalion is where I'm trying to put those lessons into action for others.

More next week on the differences between Battalion and tools like Claude Code or Cursor.

**Humans decide. AIs execute. Both learn.**
