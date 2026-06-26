# Boomie (TechBees) 👋🏾

I'm Boomie Odumade, an engineering leader with 20+ years building and scaling engineering orgs, and founder of [TechBees](https://techbees.me), where I provide:
- Fractional CTO/VPE services [techbees.me/engineering-leadership](https://techbees.me/engineering-leadership)
- Career coaching for individuals [techbees.me/coaching](https://techbees.me/coaching)
- Courses on tech & AI for all skill levels [techbees.me/learn](https://techbees.me/learn)

This GitHub org holds a mix of projects: hands-on AI work I'm building in public, tools built for real use, and of course, private repos for my own work.

Like a lot of people, I'm building with AI. 
- All apps are at [techbees.me/apps](https://techbees.me/apps)
- I'm also blogging about some of it at [techbees.me/blog/building-out-loud-ai](https://techbees.me/blog/building-out-loud-ai)
- Apps are not only shipped but also built with intentional comprehension practices.

## Released Apps

Apps from this portfolio that are released, all repos private unless otherwise stated:

- **Salone Vibes** - An AI-powered app to explore Salone (Sierra Leonean) music: look up Krio words and phrases with cultural context, discover artists, browse events, save favorites, admin tools for bulk adding, and more. (live app at [salone-vibes.techbees.me](https://salone-vibes.techbees.me) | [blog](https://techbees.me/blog/i-built-salone-vibes-app))
  - Built with: Cursor, Claude API, Tavily, Whisper. Hosted on Railway (API + Postgres).
  - The most technically complex app in the portfolio so far including multiple AI agents.
- **WinCraft** - A wins tracker that helps you log professional and personal wins as they happen, then turns them into AI-powered summaries and resume bullets.  ([live app at wincraft.techbees.me](https://wincraft.techbees.me) | blogs for demo versions at [techbees.me/blog/building-out-loud-ai](https://techbees.me/blog/building-out-loud-ai))
  - Built with: Claude Code, Next.js, Supabase, Vercel, Anthropic API
- **PlainDocs** - An AI-powered document explainer that breaks down legal documents, terms of service, contracts, and policies into plain language, with multiple output language choices. (live app at [plaindocs.techbees.me](https://plaindocs.techbees.me))
  - Built with: Amazon Bedrock (Nova Lite), Bedrock Guardrails, Amazon Comprehend, AWS Lambda, Amazon API Gateway, Amazon DynamoDB, Amazon Cognito, Lovable for frontend and hosting.
  - Repos:
    - [github.com/boomie-techbees/plaindocs-explained](https://github.com/boomie-techbees/plaindocs-explained) for frontend
    - [github.com/boomie-techbees/plaindocs-backend](https://github.com/boomie-techbees/plaindocs-backend) for backend (e.g. Lambda code).
- **African Song Translations** - View existing African song translations or request one and get an answer in under a minute. Translations include cultural context. Play the song and read along for extra fun. (live app at [african-song-translations.techbees.me](https://african-song-translations.techbees.me))
  - Built with: Lovable (including Lovable Cloud, AI gateway, hosting), Supabase, Anthropic API
- **Study Buddy** - Turn your notes into flashcards and quizzes. Built for anyone who's constantly onboarding into new terminology, systems, or clients, including consultants, fractional leaders, new hires, and fast learners. (live app at [study-buddy.techbees.me](https://study-buddy.techbees.me))
  - Built with: Lovable (including Lovable Cloud, AI gateway, hosting), Supabase

## AI Prototypes or Demos

These are projects I built to evaluate tools, explore emerging patterns, and demonstrate what's possible with today's AI coding ecosystem.

| Project | What it does | Tools Picked | Live Demo |
|---|---|---|---|
| ghana-prototype-vibes | Throwaway prototype comparing a few music APIs on coverage for Ghanaian artists. Includes AI-generated bios via Claude and origin signal enrichment. Built to validate data quality before committing to a full Ghana Vibes fork. | Lovable, Last.fm, Deezer, YouTube API, Anthropic API | [ghana-prototype-vibes.techbees.me](https://ghana-prototype-vibes.techbees.me) |
| slack-aggregator | Unified dashboard showing Slack unreads and bookmarks across multiple workspaces. Built and deployed; removed after hitting Slack workspace admin install policy wall. | Kiro, Node/Express, React, PostgreSQL, Railway | — |
| [agent-job-fit-analyzer](https://github.com/boomie-techbees/agent-job-fit-analyzer) | Autonomous agent that proactively scrapes job boards, scores listings against a candidate profile, and surfaces results in a web UI | Claude Code, Python, Flask | |
| [security-questionnaire-assistant](https://github.com/boomie-techbees/security-questionnaire-assistant) | RAG-powered tool that answers security questionnaire questions from your own uploaded policy documents, with citations and Word export | Cursor, FastAPI, React, Claude API | |
| [wincraft-claude-code](https://github.com/boomie-techbees/wincraft-claude-code) | WinCraft archived from tool comparison | Claude Code, hosted on Netlify | [Try it](https://gleeful-puffpuff-8beac5.netlify.app/) (uses local storage, no signup required) |
| [wincraft-bolt](https://github.com/boomie-techbees/wincraft-bolt) | WinCraft archived from tool comparison | Bolt.new | [Try it](https://win-journal-app-d2ig.bolt.host/) (signup required, dummy data OK) |
| [wincraft-lovable](https://github.com/boomie-techbees/wincraft-lovable) | WinCraft archived from tool comparison | Lovable | [Try it](https://my-win-muse.lovable.app) (no signup, add your own data) |
| [wincraft-replit](https://github.com/boomie-techbees/wincraft-replit) | WinCraft archived from tool comparison | Replit | [Try it](https://daily-wins-log--boomieo.replit.app) (includes test data) |

## Why the same app across four tools?

Building WinCraft in Bolt, Lovable, Replit, and Claude Code was intentional. Evaluating AI coding tools, not just using them, is part of my value as a technical leader. Each tool has different strengths, tradeoffs, and ideal use cases. 

The comparison was the point. And those comparisons are in the comparison blogs at [Building Out Loud with AI: Beginner's Edition](https://techbees.me/blog/building-out-loud-ai/beginners-edition) and [Building Out Loud with AI: Engineering Edition](https://techbees.me/blog/building-out-loud-ai/engineering-edition).

## About TechBees

TechBees provides fractional CTO and VP Engineering services to companies that need senior engineering leadership without a full-time hire. I also coach engineers and engineering leaders navigating career transitions.

[Website](https://techbees.me) | [LinkedIn](https://linkedin.com/in/odumade)
