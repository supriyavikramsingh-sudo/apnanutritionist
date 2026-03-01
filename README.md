# ApnaNutritionist 🥗

> A conversational AI nutritionist that lives 
> in your Telegram. Log meals, track macros, 
> and hit your daily targets — without ever 
> leaving your chat.

---

## The Problem

Most people who want to eat better don't fail 
because of lack of motivation — they fail because 
tracking is too much work. Existing apps require 
you to search databases, weigh food, and log 
everything manually. Nobody sustains that.

Nutrition tracking has a compliance problem. 
Despite growing awareness around health and 
fitness, most people abandon dedicated tracking 
apps within weeks due to the manual effort 
required. This is particularly acute in India 
where meal diversity and homemade food make 
database-driven apps unreliable.

---

## The Solution

ApnaNutritionist meets users where they already 
are — on Telegram — and uses AI vision and 
language models to eliminate manual logging 
entirely. Just describe your meal or send a 
photo. The bot handles the rest.

---

## How It Works

1. **Onboarding** — Tell the bot your age, 
   weight, height, and activity level. It 
   calculates your personalised daily calorie 
   and macro targets using the Mifflin-St Jeor 
   formula.

2. **Meal Logging** — Log meals via text 
   ("2 rotis + dal tadka") or photo. The bot 
   identifies the meal, estimates calories and 
   macros, and shows your running daily total.

3. **Tracking** — Approve a meal and it's 
   automatically logged to your personal Google 
   Sheet with date, timestamp, macros, and 
   calories.

4. **Insights** — At end of day, get a summary 
   of what you hit and what you missed, with 
   optional meal suggestions for the next day.

5. **Smart Updates** — Tell the bot you lost 
   weight or changed your routine. It 
   recalculates your targets automatically.

---

## Features

- 📸 Photo and text meal logging
- 🔥 Instant calorie + macro estimation
- 💪 Personalised TDEE + macro targets
- 📊 Auto-created personal Google Sheet
- 📈 Running daily totals via /today
- 🔗 Sheet link via /sheet
- 💡 End of day insights + meal suggestions
- 🔄 Semantic profile update detection
- 🛡️ Per-user data isolation
- 🇮🇳 Optimised for Indian meals and portions

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Channel | Telegram Bot API |
| Orchestration | OpenClaw |
| Vision + NLP | OpenAI gpt-5 |
| Text Estimation | OpenAI gpt-5-mini |
| Storage | Google Sheets + Drive API |
| CLI | gogcli v0.9.0 |
| Hosting | Hostinger VPS |

---

## The Bigger Vision

ApnaNutritionist is the first module in a 
larger conversational wellness ecosystem.

Modern wellness is fragmented. People use one 
app to count steps, another to log meals, 
another to track sleep. None of these talk to 
each other and all require significant manual 
effort. We are building a modular, 
interconnected wellness stack — nutrition, 
fitness, sleep, hydration, mental wellness — 
all powered by the same conversational AI 
layer, all sharing the same user profile, 
all informing each other.

This is not another health app. 
This is the operating system for your body.

---

## Status

🟢 Live on Telegram — @apnanutritionist_bot

---

*Built with OpenClaw. Hosted on Hostinger.*