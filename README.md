# Mindmaxxing

A personal playbook of persuasion, sales, negotiation, social and dating tactics, plus a small game for practicing them.

## What's here

| Folder | What it is |
|---|---|
| [`playbook/`](playbook/) | The notes. One Markdown file per category, each tactic written up with what it is, why it works, an example, how I'd use it, and when it backfires. Start with [`playbook/README.md`](playbook/README.md). |
| [`app/`](app/) | **Playbook Sparring**, a single-page practice app built from the playbook. |

## Playbook Sparring

Open [`app/index.html`](app/index.html) in a browser. There's no build step and nothing to install.

- **Spar:** roleplay scenes where Claude plays the other person and a coach scores your round 0–100.
- **Drills:** quick "pick the better line" cards with spaced repetition.
- **Deck:** every tactic and how far you've trained it.

Progress (XP, rank, streak) is saved in your browser's local storage.

Sparring calls Claude through the `window.claude` runtime, which is only available when the page runs as a Claude artifact. Opened directly from this repo, Drills and Deck work fully and Spar shows a notice instead.

The tactics, scenes and drills are copied into the page, so new playbook entries need a matching update in `app/index.html`.
