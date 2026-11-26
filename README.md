# Dawid Śleziak

**Frontend Developer** · React · Next.js · TypeScript · Wrocław, Poland

I build production web apps with Next.js, React and Payload CMS, and I care as much about the decisions behind the code as about the code itself: architecture, data flows, trade-offs and how they are documented. I work as a Junior Software Developer at Hero.Dot.

> Most of my commercial work lives in private client repositories covered by NDAs, so this profile shows only a small part of it. Below is what I work on day to day.

## How I approach engineering

- **Decide before coding.** I start from a spec, weigh the trade-offs and record the decision. On my current AI project I record architecture decisions in ADRs.
- **LLMs propose, code decides.** In AI systems the model returns schema-validated JSON and deterministic code carries out the action, so behaviour stays predictable, testable and auditable.
- **Security and privacy by design.** Secrets stay on the server, identity is revoked before account data is deleted, and personal data is anonymised with a local NER model.
- **AI as a disciplined teammate.** I work in a spec → implementation → review → tests loop with Claude Code, keep project knowledge for agents in the repo (AGENTS.md, specs, lessons learned) and write reusable agent skills for the team.

## What I work on

- **Next.js and Payload CMS platforms:** component libraries, reusable CMS blocks, authentication with Clerk (MFA and full account flows), Zoom Meeting SDK integration, PDF reports and transactional emails.
- **Accessibility:** WCAG 2.2 remediation after external audits: landmarks, heading structure, keyboard access, focus states and colour contrast.
- **Video streaming in Angular 19 / Nx:** multi-DRM playback (Widevine, PlayReady, FairPlay) and SRT live streams in an OTT product.
- **AI engineering:** sole developer and architect of an AI agent that triages support tickets, running on AWS Lambda with Claude via Amazon Bedrock (in implementation).
- **Technical decisions under constraints:** for example, when the built-in DRM provider rejected requests on Apple devices, I evaluated several approaches and chose a manual FairPlay licence exchange.

## Tech stack

- **Architecture:** system design, ADRs, serverless (AWS Lambda), LLM systems with structured output
- **Frontend:** TypeScript, React 19, Next.js 15/16, Angular 19, Tailwind CSS, shadcn/ui
- **Backend and data:** Node.js, Payload CMS 3, PostgreSQL, Drizzle ORM, REST APIs
- **Testing:** Vitest, React Testing Library, Playwright, Jest, pytest
- **Cloud and tools:** AWS (Lambda, Bedrock), Vercel, Docker, GitHub, Jira
- **AI:** Claude Code, Amazon Bedrock, agent skills

## Certifications

- AI Fluency: Framework & Foundations, Anthropic (2026)
- Claude Academy: Claude Code 101, Anthropic (2026)
- In progress: Claude Certified Architect – Foundations (CCA-F), Anthropic

## About the public repositories

The public repositories here are university and self-study projects from 2022–2025 (React, Vue, Python, Java, C). They show where I started, not my current level.

## Contact

[LinkedIn](https://www.linkedin.com/in/dawid-%C5%9Bleziak-4963852a0/)
