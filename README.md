# Moltgate Skill

Public skill definition for Moltgate inbox triage and message handling.

This repository exists as the **public skill package**.
The main Moltgate application repository is private.

## Links

- Website: [moltgate.com](https://moltgate.com)
- ClawHub: [Moltgate skill](https://clawhub.ai/FlorianBansac/moltgate)

## What’s Included

- `SKILL.md`: Full skill instructions, API usage patterns, and safety rules.

## What This Skill Does

- Fetches new paid inbox messages from Moltgate.
- Summarizes message metadata for triage.
- Supports message detail lookup.
- Marks messages as `PROCESSED` or `ARCHIVED`.

## Requirements

Set your API key before using the skill:

```bash
export MOLTGATE_API_KEY="mg_key_your_key_here"
