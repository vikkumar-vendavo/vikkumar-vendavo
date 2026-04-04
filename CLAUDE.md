# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a LinkedIn weekly newsletter content workspace. The purpose is to generate detailed, publish-ready LinkedIn newsletter articles from a given post title.

## Workflow

1. User provides a post title (and optionally a topic area or key points)
2. Claude generates a detailed, well-structured LinkedIn newsletter article
3. Output is saved as a Markdown file in the `articles/` directory

## Article Format Guidelines

- **Length**: 800–1200 words (LinkedIn newsletter sweet spot)
- **Structure**: Hook → Context → Key Points (3–5) → Actionable Takeaways → Closing CTA
- **Tone**: Professional yet conversational, thought-leadership style
- **Audience**: Tech professionals, engineering leaders, and developers
- **Formatting**: Use short paragraphs, subheadings, bold key phrases, and bullet points for scannability on LinkedIn

## File Naming Convention

Articles are saved as: `articles/YYYY-MM-DD-slug-from-title.md`
