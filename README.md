# CodeGuard

**Private, offline AI code security review — your source code never leaves your machine.**

CodeGuard is a desktop app that reviews your code for common security vulnerabilities using a local AI model. No cloud, no uploads, no telemetry. Everything runs on your own computer.

Built for developers who can't — or won't — send their code to a third-party server: proprietary codebases, client work, anything under NDA.

## What it does

- Flags common vulnerabilities — injection flaws, hardcoded secrets, unsafe input handling, insecure deserialization, and more
- Plain-English explanations with CWE references
- Suggested fix for each finding
- Exports a Markdown report (full version)
- Runs entirely offline via your own local AI model

## Honest about what it is

CodeGuard is a **first-pass assistant, not a replacement for human security review**. It catches common, pattern-based issues well, but it can miss things and can occasionally suggest an imperfect fix. **Always verify findings before acting on them.** Think of it as a fast, private second pair of eyes — not an authority.

## Requirements

- Windows
- [Ollama](https://ollama.com/download) installed (free) — CodeGuard uses it to run the AI model locally

## Quick start

1. Install [Ollama](https://ollama.com/download).
2. Download the latest release and unzip it.
3. Run `CodeGuard Demo.exe`.
4. If the button says **Install Model (4.7GB)**, click it — this downloads the AI model once (~4.7GB).
5. Paste your code, click **Run Technical Audit**.

> Windows may warn about an unknown publisher — click **More info → Run anyway**. The app is unsigned (expected for a demo).

## Demo limitations

This is a demo build: 5 audits, fastest model only, export disabled.

**Want the full version?** [Join the waitlist →](https://tally.so/r/Z99yOe)

## Feedback

Found a bug, want a feature, or just have thoughts? [Open an issue](https://github.com/QuantumDragon-tech/codeguard-demo/issues) — all feedback welcome.
