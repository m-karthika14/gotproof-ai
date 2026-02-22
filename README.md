# gotProof

Because *“I swear I took the screenshot”* isn’t evidence.



## Overview

gotProof is a local-first automation system that transforms screenshots from passive storage into actionable intelligence.

Screenshots often contain critical information such as payment confirmations, deadlines, system errors, and learning material — yet they remain buried in folders when needed the most.

gotProof bridges this gap by automatically understanding screenshots and triggering meaningful actions using Accomplish as an execution layer.



## The Problem

Screenshots are used to capture:

* Payment confirmations
* Deadlines
* Errors
* Study material
* Receipts and proofs

However, they:

* Lack structure
* Are hard to retrieve
* Require manual tracking
* Often lead to missed deadlines or lost information

Managing screenshots becomes a repetitive and inefficient task.



## The Solution

gotProof converts screenshots into usable outcomes.

Instead of storing screenshots, it:

* Understands their intent
* Organizes them intelligently
* Generates actionable outputs

This eliminates the need for manual sorting, tagging, or searching.



## How It Works

1. A screenshot is captured normally by the user
2. OCR extracts textual content locally
3. Local AI classifies the intent
4. Accomplish routes the task through custom skills
5. The appropriate action is executed

Examples:

| Screenshot Type      | Outcome            |
| -------------------- | ------------------ |
| Payment confirmation | Stored as proof    |
| Deadline notice      | Reminder created   |
| Error message        | Fix note generated |
| Study content        | Summary created    |



## Role of Accomplish

Accomplish acts as the execution engine of the system.

Once intent is detected, Accomplish performs real-world actions such as:

* Document creation
* Reminder generation
* Knowledge summarization
* File organization

Custom skills used:

* Intent Organizer
* Summary Creator
* Fix Note Generator
* Deadline Reminder Creator
* Learning Note Builder
* Action Router

These enable decision-based automation from screenshot content.



## System Workflow

Screenshot → OCR → Intent Detection → Action Routing → Accomplish Skill Execution



## Tech Stack

Frontend
React + Tailwind CSS

Backend
Node.js + Express

Database
MongoDB

OCR
Tesseract.js

Local AI
Ollama (Mistral)

Automation Layer
Accomplish (Custom Skills)



## Privacy

gotProof operates locally.

* Screenshots are processed on-device
* No mandatory cloud storage
* User data remains private

---

## Use Cases

* Tracking payment proofs
* Managing deadlines
* Resolving technical errors
* Summarizing learning material
* Organizing visual records



## Demo

https://youtu.be/kpgqO3Tt4Ko





👉 Investor-style README

