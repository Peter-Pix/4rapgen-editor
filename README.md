# 4RAP.GEN Editor

Czech rap media article editor — generuj, hodnoť a publikuj MDX články přímo na GitHub.

## Features
- ✏️ Markdown editor s live preview
- 🤖 AI hodnocení článků (GPT-4o, Gemini, Claude) — skóre 0–25
- 🚀 Přímý commit na GitHub (Peter-Pix/czech-rap-media)
- 📥 Import/export .mdx souborů
- ⚖️ Porovnání dvou článků side-by-side
- 📊 Logování kreditů na článek
- 🔑 Vlastní API klíče — žádné vendor lock-in

## Supported LLMs
- Google Gemini (zdarma tier — 1M tokenů/den)
- OpenAI GPT-4o
- Anthropic Claude
- Ollama (lokální modely)

## Deploy
Automaticky přes Vercel — každý push na `main` = nový deploy.

## Stack
Vanilla HTML/CSS/JS — žádné závislosti, žádný build step.
