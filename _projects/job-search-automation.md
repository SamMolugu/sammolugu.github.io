---
name: Job Search Automation Tool
tools: [Python, Typer, Pydantic, Playwright, SQLite]
description: A CLI pipeline that parses a resume PDF, scores job matches via ATS APIs, and automates application form pre-fill.
---

Built a Python CLI pipeline (Typer, Pydantic, httpx) that ingests a resume PDF via pdfplumber, constructs a structured candidate profile, and queries Greenhouse and Lever ATS APIs to discover and score job matches across company boards.

Automated form pre-fill and application workflow using Playwright with per-ATS playbooks and human-in-the-loop CAPTCHA handling. Audit trail persisted in SQLite; generates markdown reports; scheduled to run during US Eastern market hours.