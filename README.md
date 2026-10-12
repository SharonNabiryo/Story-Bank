# Story Bank

Story Bank helps job seekers walk into interviews with their best stories ready. You write each career story once in STAR form (Situation, Task, Action, Result), see which skills your stories prove, prepare for each interview, and practice answering out loud.

**Live demo:** https://sharonnabiryo.github.io/Story-Bank/

## The problem

Behavioral interviews ask "Tell me about a time when..." questions, and most candidates rebuild the same stories from scratch for every interview. They forget the details, ramble past two minutes, or can't put a number on the result.

## Features

- **Guided story writer:** one STAR part at a time, with prompting questions, tips, and examples.
- **Live strength checks:** spoken length, balance of parts, a number in the result, and "I" instead of "we."
- **Resume import:** turns resume bullets into draft stories, with [bracketed questions] for the details the resume doesn't say.
- **Skill coverage:** shows which of 12 commonly tested skills your stories prove and which are missing.
- **Interview tracker:** countdown, prep checklist, likely questions matched to your stories, questions to ask, and a post-interview debrief.
- **Practice mode:** a timed answer to a real interview question, with a confidence rating and practice log. Questions you were asked in real interviews join the bank.
- **Cue cards:** full-screen, swipeable story summaries to review on interview day.
- **Readiness score:** combines skill coverage, story strength, and practice.

## How it works

Story Bank is a single HTML file with no build step and no dependencies beyond Google Fonts.

- **Storage:** stories and interviews are saved in your browser's local storage. Nothing leaves your device.
- **Matching and import:** this standalone version matches job postings and drafts stories using keyword rules. The original prototype also ran AI coaching, AI matching, and AI resume import inside Claude's artifact runtime. Adding AI here would need a small backend so an API key is never exposed in the browser.

## Run it locally

Open `index.html` in any modern browser.

## Built with

HTML, CSS, and vanilla JavaScript. Prototyped with AI-assisted development (Claude), then reviewed and tested by me.

## What I'd build next

- A backend for AI coaching and accounts, so stories sync across devices
- Usage analytics to measure first-story completion
- Voice practice with transcription
