# AgentAI

A dark-themed AI portal for research, vibe coding, and chat.

## Features
- Terminal-themed UI with monospace typography
- Three modes: Chat, Research, Code
- Email OTP authentication via Brevo
- Claude 3.5 Sonnet powered by Anthropic SDK
- Per-user usage tracking in real-time
- Persistent conversation history
- Self-hosted Convex backend support

## Tech Stack
- React + Vite + TypeScript
- Tailwind CSS v4
- Convex (backend & database)
- Convex Auth (email OTP)
- Anthropic SDK (Claude 3.5 Sonnet)
- Brevo (transactional email)
- Framer Motion

## Setup
```bash
bun install
bun run dev
```

## Environment Variables
- `VITE_CONVEX_URL` - Convex deployment URL
- `ANTHROPIC_API_KEY` - Anthropic API key
- `BREVO_EMAIL_SENDER` - Brevo API key
- `SITE_URL` - Site URL for auth redirects
