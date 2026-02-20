<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=10D5qKSJfCnR6aaFYMebMDg3uTJpxnNxA" alt="Nexviatech" width="320"/>
</p>

<h1 align="center">🎯 AI Lead Scraper — Telegram to Google Sheets</h1>

<p align="center">
  <strong>Built by <a href="https://nexviatech.online">Nexviatech</a></strong> · A client wanted to pull targeted leads from Apollo.io just by sending a Telegram message. We built it.
</p>

<p align="center">
  <a href="https://nexviatech.online"><strong>→ Want this built for your business? nexviatech.online</strong></a>
</p>

---

## The Problem We Solved

A client's sales team was manually searching Apollo.io, filtering by industry, role, and location — then copying data into spreadsheets. Every lead list took 30–45 minutes to build.

> *"I just want to say 'find me 50 SaaS CEOs in the US' and get a clean list. That's it."*

So we built it. Send a voice note or text to a Telegram bot. The AI understands what you want, builds the Apollo search, scrapes the leads, and drops everything into Google Sheets — automatically.

**Result:** A lead list that took 45 minutes now takes under 2 minutes, triggered from anywhere, even on mobile.

---

## What It Does

- You send a message to a Telegram bot — text or voice note
- The AI reads your request and builds the Apollo.io search URL
- Apify scrapes the leads matching your criteria
- Everything lands in a Google Sheet, clean and ready to use

**Fields captured:** Name · Title · Email · LinkedIn · Company · Website · Country · Founded Year

---

## How It Works

```
Telegram Message (text or voice)
         │
         ▼
  Voice? → Transcribe via Whisper
  Text?  → Use directly
         │
         ▼
  AI Agent (GPT-4o-mini)
  Understands request → Builds Apollo URL
         │
         ▼
  Apify Apollo.io Scraper
  Runs search → Pulls leads
         │
         ▼
  Google Sheets
  Leads stored, formatted, ready
```

**Tools used:** n8n · Telegram · OpenAI Whisper + GPT-4o-mini · Apify · Apollo.io · Google Sheets

---

## Example Requests

Just message the bot — text or voice, both work:

- *"Find me 50 CTOs at fintech startups in the UK"*
- *"100 marketing managers at SaaS companies, US only"*
- *"Get me decision makers in e-commerce, around 30 leads"*
- 🎤 Voice note saying the same thing — works exactly the same way

---

## Setup (6 Steps)

**1.** Import the `.json` workflow into your n8n instance

**2.** Create a Telegram bot via [@BotFather](https://telegram.me/BotFather) and copy the token

**3.** Connect credentials in n8n:
- Telegram bot token
- OpenAI API key (Whisper + GPT-4o-mini)
- Google Sheets OAuth2
- Apify API token

**4.** Create two Google Sheets:
- **Industry ID sheet** — maps industry names to Apollo.io IDs (used by the AI)
- **Leads output sheet** — where scraped leads are written

**5.** Add your Apify token to the HTTP request nodes

**6.** Send a message to your bot and watch it run

---

## This Is One of Many

This workflow is one example of what Nexviatech delivers. We've also built:

- **AI research agents** that answer complex business questions in seconds
- **Tech stack identifiers** that enrich lead lists with competitor intelligence
- **Email inbox assistants** that triage and respond automatically
- **Website traffic scrapers** that feed live data into dashboards

Every project starts with a client problem. We build the solution.

---

## Work With Us

If your team is doing manually what a bot could do automatically, let's talk.

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=10D5qKSJfCnR6aaFYMebMDg3uTJpxnNxA" alt="Nexviatech" width="200"/>
</p>

<p align="center">
  <strong><a href="https://nexviatech.online">nexviatech.online</a> · info@nexviatech.online</strong>
</p>

---

*Built by Nexviatech · We turn client problems into working AI systems.*
