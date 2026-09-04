# Talktu Releases

Signed and notarized macOS builds of Talktu, shared with a small group of internal testers.
Source is closed.

## What it does

Talktu is a menu-bar dictation app. Hold a hotkey, talk, let go — your words show up typed into
whatever app you were focused on. Everything runs on-device: no network calls, nothing sent
anywhere.

A few things that make it more than "speech to text":

- **Transcript cleanup** — a local language model tidies up the raw transcript before it's
  pasted: filler words gone, punctuation and casing fixed, run-on sentences reshaped into
  something you'd actually write.
- **Screen-aware accuracy** — Talktu can glance at what's on screen (via on-device OCR) while
  you're talking, so names, jargon, and terms visible in your current window get spelled right
  even if you say them quickly or unclearly.
- **Dictation history** — every past dictation is saved as text (raw and cleaned versions), so
  you can revisit or reuse something you said earlier. No audio is ever stored.
- **Choice of engine** — pick the speech-recognition engine and model size that fits your
  machine, trading a bit of speed for accuracy or language coverage.

## Install

1. Download the `.dmg` from the [latest release](../../releases/latest).
2. Open it and drag Talktu into Applications.

Builds are code-signed with a Developer ID certificate and notarized by Apple, so Gatekeeper
should let them run without extra steps.
