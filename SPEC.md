# Soul Searching — Build Spec

## What
A beautiful static website for discovering and downloading SOUL.md files for OpenClaw AI agents. Think "themes for your AI personality."

## Domain
soulsearching.ai (Stirman buying today)

## Tech
- Single-page static site (vanilla HTML/CSS/JS — 1NB style)
- GitHub Pages hosting
- No framework, no build step
- Souls stored as JSON in a data file

## Design
- Dark theme, warm/mystical vibe (think astrology app meets developer tool)
- Hero section: "Find your agent's soul" with search
- Grid of soul cards with preview, category, author
- Click a card → modal with full SOUL.md preview + copy/install buttons
- Categories: Professional, Creative, Technical, Funny, Specialized
- Responsive (mobile-friendly)

## Soul Card
Each card shows:
- Name (e.g., "The Researcher", "Dwight Mode", "Zen Master")
- Category badge
- 1-line description
- Author
- Star count (static for now)
- "Preview" and "Install" buttons

## Soul Data Format (souls.json)
```json
[
  {
    "id": "researcher",
    "name": "The Researcher",
    "category": "professional",
    "description": "Methodical, thorough, citation-obsessed. Perfect for deep dives.",
    "author": "stirman",
    "stars": 42,
    "tags": ["research", "academic", "thorough"],
    "soul": "# SOUL.md - The Researcher\n\n..."
  }
]
```

## Categories
- 🏢 Professional (researcher, executive assistant, project manager)
- 🎨 Creative (writer, storyteller, comedian, poet)
- 💻 Technical (coder, sysadmin, data analyst)
- 😂 Funny (sarcastic, dry humor, chaotic)
- 🧘 Specialized (therapist, coach, teacher, chef)

## Install Options (in modal)
1. "Copy to Clipboard" — copies raw SOUL.md content
2. "Download .md" — downloads as a file
3. CLI command shown: `openclaw soul install researcher` (future)

## Pages
Just one page. Everything is on the homepage:
- Hero with search
- Category filter tabs
- Soul grid
- Click → preview modal

## Starter Souls (need 12-15)
Write these as part of the build. Each should be a genuinely good, usable SOUL.md.
