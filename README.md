# Local AI Transcriber

A local-first AI transcription and note-generation pipeline built with Whisper, Ollama, and Obsidian.

This project converts voice recordings into structured markdown notes completely offline — without subscriptions, cloud lock-in, or external AI APIs.

## Features

- Local audio transcription with faster-whisper
- AI-powered summaries using Ollama
- Markdown note generation for Obsidian
- Action item and key point extraction
- Automatic note formatting and tagging
- Works with recordings from PLAUD, phones, meetings, lectures, and voice memos
- Fully offline and privacy-focused

## Stack

- faster-whisper — speech-to-text
- Ollama — local LLM orchestration
- Obsidian — knowledge management
- Python — pipeline automation

## Planned Pipeline

```txt
Audio Recording
      ↓
faster-whisper
      ↓
Raw Transcript
      ↓
Ollama
      ↓
Structured Markdown Note
      ↓
Obsidian Vault
```
