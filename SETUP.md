# ExamGen Setup Guide

## Option A — Run the full Next.js app (recommended)

### Step 1: Install Node.js
Download and install from: https://nodejs.org (choose the LTS version)
Restart your computer after installing.

### Step 2: Add your Anthropic API key
Copy `.env.local.example` to `.env.local` and add your key:
```
ANTHROPIC_API_KEY=sk-ant-your-key-here
```
Get a key from: https://console.anthropic.com

### Step 3: Install & run
Open a terminal in this folder and run:
```
npm install
npm run dev
```
Then open: http://localhost:3000

---

## Option B — Open the standalone demo (no install needed)

Open `standalone.html` directly in any web browser.
You will be prompted for your Anthropic API key on first use.
The key is stored only in your browser's localStorage.

---

## What you get

- **Dashboard** — overview with stats and quick links
- **Generate** — paste textbook content → get exam questions
- **Question Bank** — search, filter, edit all saved questions  
- **Exam Builder** — assemble custom exam papers
- **Export** — copy or print student/teacher/answer key versions

## Supported question types
MCQ · Short Answer · Case-Study Short Answer · Data-Response ·
Calculation · Long Answer · Essay · Full Case Study · Mixed Paper

## Supported levels
IGCSE · AS Level · IAL / A Level
