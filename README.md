# Muista — Finnish A1 lesson feed

This public repository holds the Finnish vocabulary and grammar cards for Muista 2.0. It does **not** contain personal learning progress.

## One-time setup

In Muista, open **Settings → Automatic lesson feed** and enter:

`https://raw.githubusercontent.com/Tourajj/muista-lessons/main/lessons.json`

Choose **Save feed** and **Sync now**. Muista checks the feed when opened, if external syncing is enabled in its settings.

## Updates

New lessons must be published to `lessons.json` in this repository. Muista then fetches them when opened. ChatGPT conversations do not publish to GitHub without an explicit action by the connected assistant, and GitHub does not receive private ChatGPT messages automatically.

Keep IDs stable and append new cards instead of replacing previous lessons. Review history stays locally on the student's phone.
