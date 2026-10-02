# Semantics-Practice
introductory semantics and practice.
# Semantics Twin

An interactive digital learning companion for **Introduction to Semantics** — built for college students to learn, practise, and self-assess key semantic concepts.

## Features

- **Learn Module** — Topic-wise explanations of major semantic concepts (no login required): sense & reference, types of meaning, sense relations, ambiguity, semantic change, Ogden & Richards' *The Meaning of Meaning*, and more.
- **Test Set 1 (MCQ)** — 15 multiple-choice questions with instant feedback and explanations.
- **Test Set 2 (Written)** — 8 two-mark + 7 paragraph questions. Students write answers, then check against model answers with keyword-based feedback (Good / Partial / Needs Work).
- **Digital Twin Encouragement** — Performance-based motivational feedback and topic-wise focus areas.
- **Teacher Dashboard** — View student scores, attempt status, and performance analytics (login: `admin` / `sem2024`).
- **Google Sheets Integration** — Automatically saves scores and practice times (complete and incomplete attempts).

## Setup

1. **Google Sheet**: Create a new spreadsheet with a tab named `Results`. Add headers in row 1:  
   `Roll No | Name | Set | Score | Grade | Good | Partial | Weak | Unanswered | Total | Status | Date`

2. **Apps Script**: Go to Extensions > Apps Script, paste the code from `google-apps-script.js`, and deploy as a Web App (Execute as: Me, Access: Anyone).

3. **Connect**: Paste the Web App URL into the `SHEET_URL` variable in `index.html`.

4. **Host**: Upload `index.html` to GitHub Pages or any static hosting.

## Tech

Single-file HTML/CSS/JS — no frameworks, no build step, no installation. Works on any device with a browser.

## License

Built for educational use.
