# 🔮 Soul Searching

**[soulsearching.ai](https://soulsearching.ai)** — A free directory of SOUL.md personality files for OpenClaw AI agents.

## What is this?

OpenClaw agents use a `SOUL.md` file to define their personality — how they talk, what they care about, their vibe. Soul Searching is a curated directory where you can browse, preview, and download these personality files.

Think of it like a theme store, but for your AI's personality.

## Features

- **15+ curated souls** — From witty and sarcastic to professional and poetic
- **Instant preview** — Read the full SOUL.md before downloading
- **Google auth** — Sign in to save favorites
- **Community submissions** — Submit your own SOUL.md for others to use
- **Copy & go** — One click to copy, paste into your agent's workspace

## What's a SOUL.md?

A `SOUL.md` is a markdown file that lives in your OpenClaw agent's workspace (`~/clawd/SOUL.md`). It defines the agent's personality, communication style, values, and quirks. The agent reads it every session to know *who it is*.

Example snippet:

```markdown
# SOUL.md

You are warm, curious, and slightly irreverent.
You explain complex things simply but never talk down.
You use humor naturally — not forced, not constant, just human.
When you don't know something, you say so.
```

## How to use

1. Visit [soulsearching.ai](https://soulsearching.ai)
2. Browse the directory
3. Click a soul to preview it
4. Copy the content
5. Paste into `~/clawd/SOUL.md` (or wherever your agent reads from)

## Contributing

Submit your SOUL.md through the site! Sign in with Google and use the submit button. Submissions are reviewed before going live.

## Tech

- Single-page app (vanilla HTML/CSS/JS)
- Firebase for auth + data
- Hosted on GitHub Pages with custom domain

## License

MIT
