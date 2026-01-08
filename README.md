# Framing Lens

A mobile-first Perspective / Framing exercise app that converts ambiguous prompts into descriptive response patterns. Mobile-first is the default—not a limit—and the system is designed to be adapted: prompts, interpretation rules, outputs, and workflows can be remixed for different environments, contexts, and objectives. With default setting set in beginning stages so altering, changing completely, or misusage understood to be possible but that’s perspective and environmental based objectives. (Will Work As Is, this is ready to be used today by anyone, only changes require more time but this is a seed for those who want more but a final product for those that this satisfies) 

## License

Public domain (CC0). Use it however you want.

## Default settings: Labels with (default settings) fall under this category (Settings as default are made for system to run based this current perspective and environment can be used in many different ways based on Perspective and/Or Environment)

## How this could be read

This repository documents a default implementation. Defaults are not limits.
Different perspective and or environments can run different prompt sets, output modules, and sharing policies—without needing a single "correct" use case.

## Default stance (implementation default, not universal truth)

This default implementation presents patterns as observations (tendencies, tradeoffs, and what the pattern prioritizes). Other environments may choose different output modules, different language, or different workflows.

-Meaning if any option in this stops you from changing it in anyway so you can continue any project you are working on I don’t want to constraint you, prevent you, and or control what you do. I did as much as I could think about to fix this issue based off of many different perspectives and environments and that’s why it’s stressed to be changed because those things change as you go around the world or even continue in time. I understand I have missed many things and I’m saying it’s up for you to have that if you want. Please give feedback if anything is missed that my current system prevents! 

## What it does (in plain terms)- (default settings) Unless you want, wish, need something different based on perspective and or environment 

Framing Lens captures how people respond to ambiguity, then summarizes patterns in how they interpret, prioritize, and act. Those summaries can be used in many ways depending on environment and intent.

## Contexts this can support (examples, not a boundary)- Others missed are up to you to add (Default settings) 

- Self-reflection (how your framing changes across time and situations)
- 1-on-1 coaching or facilitation (two perspectives side-by-side)
- Education (teaching perspective-taking and interpretation)
- Team collaboration (reducing friction, pairing styles, communication bridging)
- Research (pattern collection and analysis)
- Creative work (prompt remixing, narrative contrast, worldbuilding)

## MVP scope (core)- (Default settings) 

- Session-first flow: Landing → Session setup → Prompt answering → Results
- Versioned prompt sets (starting with v3)
- Configurable sharing and identity via policy
- Modular results (choose modules based on context)
- Rules-based pattern engine (interpretable, not black-box)

## Tech (initial)-(default settings) 

- Next.js (App Router)
- Postgres later (Supabase/Neon or equivalent)
- Deploy on Vercel (GitHub-connected)

## Documentation

- docs/PROMPT_SET_v3.md — canonical prompt set text (v3)
- docs/OUTPUT_MODULES.md — results are modular; environments choose modules
- docs/WIREFLOW.md — screens and user flow (session-first)
- docs/ROUTES_API.md — routes + API endpoints
- docs/DATA_MODEL.md — database tables (planned)
- docs/POLICY_MODEL.md — sharing/identity/retention as policy options
- docs/SCORING_ENGINE.md — scoring rules and signal mapping approach
- docs/ROADMAP.md — evolution of optional capabilities

## Quick Start (later, after MVP)

- How to run locally (npm install, npm run dev ).
- Where to find the main app code (e.g., /app once it exists). nextjs
