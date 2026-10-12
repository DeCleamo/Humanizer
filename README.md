# PGTurn — Text & DOCX Humanizer Portal

A clean, practical, fast, and 100% private in-browser portal for humanizing AI text and Word documents (`.docx`).

## Features

- **Direct DOCX Processing**: Upload any `.docx` file, humanize all paragraphs in-memory while preserving XML styling, formatting, fonts, tables, and images, and download the humanized `.docx`.
- **Direct Text Input**: Paste or type text directly with live word/character counters.
- **Rule-Based Engine (Zero AI)**: Pure deterministic n-gram disruption, LLM cliche replacement, discourse marker rotation, and burstiness cadence enhancement.
- **Zero-Width Character Purge**: Strips invisible tracking Unicode (`\u200B`, `\u200C`, `\u200D`, `\uFEFF`, `\u2060`, C2PA/SynthID artifacts).
- **LaTeX & Code Safe**: Protects mathematical formulas (`$...$`, `$$...$$`, `\begin{equation}`) and executable code logic.
- **100% Client-Side Privacy**: Runs completely in your local browser session. No servers, no tracking, no logins.

## Running Locally

Run a local HTTP server:

```bash
python3 -m http.server 8000 --directory docs
```

Open [http://localhost:8000](http://localhost:8000) in your browser.
