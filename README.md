# cf_ai_standup
An AI-powered daily standup assistant built on Cloudflare's developer platform. Type your standup updates into a chat interface and get clean AI-generated summaries. Request a weekly digest anytime to see everything you've logged.

## Features
- Chat-based standup input (what I did, what I'm doing, blockers)
- AI summarization via Llama 3.3 on Cloudflare Workers AI
- Persistent session history using Durable Objects
- Weekly digest on demand

## Tech Stack

| Component | Technology |
|---|---|
| LLM | Llama 3.3 (Cloudflare Workers AI) |
| Workflow | Cloudflare Durable Objects |
| UI | Cloudflare Pages |
| Memory | Durable Object state storage |

## Running Locally

### Prerequisites

- Node.js 18+
- A Cloudflare account (free tier works)
- Wrangler CLI installed: `npm install -g wrangler`

### Setup
1. Clone the repo
```bash
   git clone https://github.com/Jonimz/cf_ai_standup
```

2. Install dependencies
```bash
   npm install
```

3. Authenticate with Cloudflare
```bash
   wrangler login
```

4. Run locally
```bash
   wrangler dev
```

5. Open your browser at `http://localhost:8787`

## Deployed Link

Coming soon.

## License

MIT
