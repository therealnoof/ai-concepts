# ⚡ AI Concepts

Interactive, animated diagrams that explain AI and machine learning concepts visually.

## Pages

- **[Neural Networks](/)** — How artificial neural networks process data through layers of neurons
- **[RAG Pipeline](/rag/how-rag-works)** — Retrieval-Augmented Generation pipeline diagram
- **[Transformers](/transformers/how-transformers-work)** — The architecture powering modern LLMs
- **[Agentic AI](/agentic-ai/how-agents-work)** — How AI agents reason, plan, use tools, and collaborate
- **[Training Pipeline](/training/how-training-works)** — How LLMs are trained from raw data to deployed model
- **[AI Security](/ai-security/securing-ai)** — End-to-end security for the AI data factory

## Tech Stack

- Pure HTML / CSS / JavaScript (no build step, no framework)
- Google Fonts (Outfit, JetBrains Mono, Sora, IBM Plex Mono, DM Sans, Fira Code)
- Hosted on Cloudflare Pages

## Local Development

Just open any `index.html` in a browser, or run a local server:

```bash
# Python
python3 -m http.server 8080

# Node.js
npx serve .
```

Then visit `http://localhost:8080`

## Deployment

This site deploys automatically to Cloudflare Pages on push to the `main` branch.

### Cloudflare Pages Settings

- **Build command:** (leave empty — no build step needed)
- **Build output directory:** `/` (serve from root)
- **Root directory:** `/` (default)
