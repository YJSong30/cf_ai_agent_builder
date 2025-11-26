# Cloudflare Agent Builder

This project is an AI-Powered agent built on cloudflare workers.
It utilizes AI inference (workers AI), demonstrates workflow using Cloudflare agents, persistant memory through durable obejcts, and user interaction via a chatbot.

This chatbot features a friendly AI chatbot that's main task is to schedule tasks for you. It's ran directly on Cloudflare Workers.

LLM used: Llama 3.0 (Workers AI)

This project was created through Cloudflare's recommended `agents-starter` template

# Run Locally

1. `npm install`
2. `npm run dev`
3. Open the URL printed in your terminal (usually http://localhost:5173)

# Deploy to Cloudflare

1. Log into Cloudflare:
   `npx wrangler login`
2. Deploy:
   `npm run deploy`

# AI Prompts

All prompts used to build this project are included in [PROMPTS.md](PROMPTS.md)
