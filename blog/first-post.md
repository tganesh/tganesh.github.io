---
layout: post
title: "How I Built My First AI Agent"
date: 2026-07-02
---

# How I Built My First AI Agent

In this post, I explain how I built a simple AI agent using cloud tools, structured prompts, and workflow automation.

## Goal

The goal was to create an assistant that can:

- Understand user requests
- Use tools safely
- Validate JSON output
- Send email summaries
- Log activity for observability

## Architecture

The basic architecture was:

```text
User request
   ↓
AI Agent
   ↓
Tool selection
   ↓
Validation
   ↓
Final response or action
