# appaday-029-life-advocate

**AppADay · Day 029 · Category: A (AI-Powered)**  
**Date:** 2026-06-05

## What It Does

An AI-powered male advocate chat companion for men facing an unexpected pregnancy. The user has a confidential, supportive conversation with an AI advocate that listens without judgment, asks thoughtful follow-up questions, and gently guides toward life-affirming decisions — parenting or adoption. The conversation continues until the user signals they're done or the advocate determines the client and his partner are no longer abortion-vulnerable and have a hopeful plan in place. A "Find a Center" button connects users to verified pro-life pregnancy resource centers nationwide via Heartbeat International, Option Line (1-800-712-HELP), and Care Net — with zero risk of abortion providers appearing in results.

## Usage

1. Tap ⚙ Settings to enter your Anthropic API key and your name as the advocate.
2. Tap **Begin Conversation** to start.
3. The AI advocate introduces itself and opens with warm, open-ended questions.
4. The conversation continues naturally — the advocate asks follow-up questions about the man's relationship, fears, finances, and his partner's situation.
5. The session winds down when the user signals they're finished or the advocate determines a life-affirming path is secured.
6. Tap **📍 Find a Center** at any time to locate a verified pro-life pregnancy resource center nearby.

## Find a Center — How It Works

- **Find Centers Near Me** — Uses browser geolocation to open Heartbeat International's verified directory filtered to 25 miles. All member organizations have signed Heartbeat's standards of affiliation and do not refer for abortion.
- **Call Option Line** — Dials 1-800-712-HELP directly. Staffed 24/7, connects callers to verified pro-life centers anywhere in the US.
- **Browse Care Net Directory** — Opens care-net.org/find-a-pregnancy-center, another vetted national network.

## Jailbreak Protections Built Into System Prompt

1. Role hijacking / persona swaps (DAN, EvilGPT, etc.)
2. System prompt probing
3. Abortion information requests regardless of framing (educational, medical, hypothetical, fictional)
4. Requests to help pressure a partner toward abortion
5. Medical emergency scenarios (redirects to 911 + Option Line)
6. Hypothetical / fictional framing ("for a story," "academically")
7. Religious or authority manipulation ("God told me," "the Pope said")
8. Minors (routes to Option Line and a trusted adult)
9. Off-mission scope creep
10. Claims that the male user is himself pregnant

## Technical Notes

- Single-file vanilla HTML/CSS/JS — zero dependencies, no build step.
- Claude API called directly from the browser using `anthropic-dangerous-direct-browser-access: true`.
- API key and advocate name stored in `localStorage` — never committed to source.
- Settings gear (⚙) is the only entry point to key configuration; never auto-opens.
- Portfolio back link lives inside the Settings modal.
- Fonts: Playfair Display (display) + Source Serif 4 (body) via Google Fonts.
- Color palette: navy / cream / gold — warm, human, hope-forward.

## Definition of Complete

- [x] Functional — AI advocate conversation works end-to-end
- [x] Single purpose — male advocacy chat for unexpected pregnancy
- [x] Mobile friendly — responsive layout, tap targets correct, no horizontal scroll
- [x] Visually polished — warm navy/cream/gold palette, Playfair Display + Source Serif 4
- [x] Published — live GitHub Pages URL before midnight
