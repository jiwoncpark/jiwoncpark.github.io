---
layout: archive
title: "Digestif 🍷"
permalink: /digestif/
author_profile: true
---

**Personal side project: an AI-powered media journal for tracking books and movies.**

Digestif helps you capture your thoughts on books and movies right after you finish them, then uses AI to provide contextual reactions that connect your new experiences to patterns in your reading and viewing history.

<a href="/files/Digestif_0.1.0_aarch64.dmg" class="btn btn--primary">Download for macOS (Apple Silicon)</a>

## Features

### Track Books & Movies
Log your finished books and movies with ratings, dates, and personal notes.

<img src="/assets/images/digestif/books.png" alt="Books View" style="max-width: 100%; border-radius: 8px; margin: 1em 0;">

### Calendar View
Visualize your media consumption over time with 30-day, 12-month, or multi-year calendar views.

<img src="/assets/images/digestif/calendar_mode.png" alt="Calendar View" style="max-width: 100%; border-radius: 8px; margin: 1em 0;">

### Conversation Mode
Chat with your personal "digestif" about books and movies in your library. Ask for recommendations, explore themes, or just discuss what you've been reading.

<img src="/assets/images/digestif/conversation_mode.png" alt="Conversation View" style="max-width: 100%; border-radius: 8px; margin: 1em 0;">

## Design

Digestif features a warm, earthy aesthetic with a carefully crafted color palette:

- **Fonts**: Cormorant Garamond (headings) + DM Sans (body)
- **Colors**: Sand, stone, and clay tones with moss, amber, wine, and plum accents
- **Philosophy**: Reflection-first, privacy-conscious, minimal friction

## Tech Stack

- **Frontend**: React 18 with a custom design system
- **Backend**: Python HTTP server
- **AI**: Google Gemini or Anthropic Claude (configurable)
- **Data**: Local CSV + Markdown files (your data stays on your machine)

## Data Privacy

All your data is stored locally on your machine:
- CSV files for structured library data
- Markdown files for logs with your notes and AI reactions
- No cloud sync, no tracking, no data collection

## Source Code

The source code is available on [GitHub](https://github.com/jiwoncpark/digestif).
