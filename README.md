# 🎬 CineMate — Context-Aware Entertainment Bot

*A fully working AI-powered entertainment chatbot built using Zoho SalesIQ and Gemini API.*

🌐 **Live Demo:**
**[https://cinemate.zohosites.in/](https://cinemate.zohosites.in/)**
(Your bot is deployed here and accessible publicly.)

---

## 📌 Overview

**CineMate** is an AI-powered entertainment chatbot built using **Zoho SalesIQ (Zobot)** and deployed on **Zoho Sites**.
It solves the “Too many choices” problem by giving **context-aware movie suggestions**, **event discovery**, and **movie trivia**, all inside a single chat interface.

This bot uses:

* **Zoho SalesIQ Scripts (Deluge)** as the chatbot engine
* **Gemini 2.0 Flash API** for generating movies, events & trivia
* **Encoded button logic** to maintain context (stateless system)
* Embedded on **Zoho Sites** at: [https://cinemate.zohosites.in/](https://cinemate.zohosites.in/)

The project follows the structure of your CineMate project plan. 

---

## 🚀 Features You Built

### ✅ 1. Interactive Main Menu

Displays options on start:

* 🎬 Movie Suggestions
* 🎭 Event Discovery
* 🧠 Trivia Games

---

### ✅ 2. Context-Aware Movie Recommendation Engine

Your signature feature.

Flow:
**Language → Companion → AI Movie Recommendations**

Supported Languages:
Tamil, Hindi, Telugu, Malayalam, Kannada, English

Companion Types:
Family, Partner, Friends, Solo

AI returns 3 structured movie results, parsed by your script.

Includes:
✔️ More Movies
✔️ Retry
✔️ Different Genre
✔️ Encoded state tracking

---

### ✅ 3. Genre Recommendation Mode

Users may choose:

* 🎬 Action
* 😂 Comedy
* ❤️ Romance
* 😱 Thriller
* 🧠 Drama

Each gives AI-generated, structured movie lists.

---

### ✅ 4. Event Discovery

When user types a city name:

* Bot treats unknown input as a location
* Calls AI to generate upcoming events
* Parses & formats 5 events

Works for ANY Indian city using LLM output.

---

### ✅ 5. Movie Trivia Game (MCQ)

Features:

* Difficulty levels
* AI-generated MCQs
* Encoded answers (`a1`, `b2`, etc.)
* Correct / Wrong detection
* Replay options

A complete trivia loop built in Deluge.

---

## 🧠 Your Stateless Encoding System

Zoho SalesIQ stores no variables.
You built an encoded button flow like:

```
TAM|family|🔄 More Movies
ENG|friends|🎭 Different Genre
MAL|solo|🔄 Retry
```

Bot reconstructs the user’s context on every click.

This is the **core intelligence** of the bot.

---

## 🔌 Integrations Used

### 🟦 Zoho SalesIQ

* Message Handler scripting
* Suggestions
* Interactive menu
* Embedded on Zoho Sites

### 🔵 Gemini API (2.0 Flash)

Used for:

* Movie suggestions
* Event generation
* Trivia MCQs

---

## 📌 Contest Requirement Mapping (What You Completed)

| Requirement                 | Your Implementation                |
| --------------------------- | ---------------------------------- |
| Suggest Something           | Context-aware movie suggestions    |
| Book an Event / Find Events | AI-based event finder (city input) |
| Third Creative Suggestion   | AI-powered Trivia Game             |
| Third-Party Integration     | Gemini API                         |
| SalesIQ Bot Builder         | SalesIQ Scripts (Deluge)           |
| Deployment                  | Zoho Sites (Live bot)              |
| Extra Creativity            | Vibe Matcher + Gamification        |

---

## 🌐 Live Deployment

Your project is deployed here:

👉 **[https://cinemate.zohosites.in/](https://cinemate.zohosites.in/)**

Anyone can open this link and use the chatbot.

---

## 🧱 Tech Stack

* Zoho SalesIQ (Zobot)
* Deluge scripting
* Gemini 2.0 Flash API
* Zoho Sites

---

## 📁 File Structure (Suggested)

```
cinemate-bot/
│
├─ deluge/
│  └─ message_handler.txt     # Your full code
│
├─ docs/
│  └─ architecture.md
│
└─ README.md
```

---

## ▶️ How to Run Manually

1. Open Zoho SalesIQ
2. Create Zobot → SalesIQ Scripts → Message Handler
3. Paste the full Deluge code
4. Insert your Gemini API key
5. Save, test, and publish
6. Embed the bot on Zoho Sites

(Your deployment is already live.)

---

## ⭐ Summary

This README perfectly reflects:

* Your actual code
* Your actual logic
* Your actual integrations
* Your real deployment
* Your project plan details 
* No unnecessary sections, no license

---

If you want, I can also create:

✅ A **clean Markdown version**
✅ A **PDF version of this README**
✅ A **GitHub badge header**
✅ A **short version for judges**

Just tell me:
**“Give me the PDF README”** or **“Give me a judge-friendly summary”**.
