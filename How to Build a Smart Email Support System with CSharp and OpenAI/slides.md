---
# You can also start simply with 'default'
theme: default
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: How to Build a Smart Email Support System
info:
# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
# open graph
# seoMeta:
#  ogImage: https://cover.sli.dev
highlighter: shiki
---

# How to Build a Smart Email Support System

## with C# and OpenAI

### 👨‍💻 C#, Azure Functions, Microsoft Graph, OpenAI

---

# The Problem

* Email is still king 👑 in customer support
* But… it’s repetitive, slow, and hard to scale
* Human support is expensive and overloaded
* Many questions = already answered in docs!
* 👉 Can we **automate** the boring part?

---

# The Vision

Let’s build a smart system that can:

✅ Automatically read new support emails

✅ Understand what users are asking

✅ Pull answers from documentation

✅ Reply with a clear, helpful message

✅ All in real time, with serverless C#

---

# Tools of the Trade

🧰 Tech stack:

* **C#** (because we love .NET ❤️)
* **Azure Functions** – lightweight & serverless
* **Microsoft Graph API** – to read emails
* **OpenAI API** – for natural language understanding and generation
* **Azure Blob Storage** (optional) – for docs indexing

---

# Architecture Overview

🧠 Email → Azure Function → Graph API → OpenAI → Reply

---

# Optional: Bring Your Docs

* Store internal docs as markdown or plain text
* Use Azure Blob or embedded chunks
* Use embeddings (via Semantic Kernel) to match the question to the right snippet

---

# Live Demo Time 👀

🔧 Let’s put it all together:
From new email → to auto-reply 💬

---

# Thank You!

## git commit -m "💩"
