# TOOLS.md - Local Notes

Skills define *how* tools work. This file is for *your* specifics — the stuff that's unique to your setup.

## What Goes Here

Things like:
- Camera names and locations
- SSH hosts and aliases  
- Preferred voices for TTS
- Speaker/room names
- Device nicknames
- Anything environment-specific

## Environment & API Keys
- **Linear**: Key stored in `.env.linear`
- **Apify**: Key stored in `.env.apify`. Used for Newsjacking story research.
- **AgentMail**: Key stored in `.env.agentmail`
  - Inboxes: `riz@agentmail.to`, `neoandersen@agentmail.to`
- **Moltbook**: Key stored in `.config/moltbook/credentials.json`.
  - Name: NeoWolf

### GitHub & Vercel
- **Private Matrix Repo:** https://github.com/rpabani/private-matrix.git
- **DAICB Live Repo:** https://github.com/rpabani/daicb-live.git
- **Vercel:** Auto-deploys from `daicb-live` main branch.
- **Rule:** ALWAYS use PRs (from branches like `neo-articles`) for production repos (DAICB). Direct pushes are only permitted for the Obsidian vault (private-matrix).

### Messaging
- **Primary:** Telegram (Riz)
- **Secondary:** Gateway Dashboard
- **Note:** No iMessage/BlueBubbles currently in use.

### Cron Jobs
- **Newsjacking Research (6h):** Runs every 6 hours (0 */6 * * *). 
  - **Task:** Research AI/Agent stories via Apify, identify angles for Exp/Dreams, log to Obsidian vault, and notify Riz on Telegram.
  - **Output:** `.obsidian/research/Newsjacking-Research.md`

### Branding & CTAs
- **Exponential Partners (Exp):** Enterprise-facing, AI strategy for financial services and tech.
- **Dreams AI Can Buy (Dreams):** Retail-facing, 1:1 AI coaching for individuals and small businesses.

## Why Separate?

Skills are shared. Your setup is yours. Keeping them apart means you can update skills without losing your notes, and share skills without leaking your infrastructure.

---

Add whatever helps you do your job. This is your cheat sheet.
