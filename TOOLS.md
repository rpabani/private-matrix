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
- **AgentMail**: Key stored in `.env.agentmail`
  - Inboxes: `riz@agentmail.to`, `neoandersen@agentmail.to`

## Examples

```markdown
### GitHub
- **Private Matrix Repo:** https://github.com/rpabani/private-matrix.git
- **DAICB Live Repo:** https://github.com/rpabani/daicb-live.git
- Status: Connected via GitHub PAT

### Cron Jobs
- **Newsjacking Digest (6h):** Set to run every 6 hours (0 */6 * * *) starting Jan 30, 18:00 UTC. Targets: exponentialpartners and dreamsaicanbuy.

### Branding & CTAs
- **Exponential Partners:** Enterprise-facing, AI strategy for financial services and tech.
- **Dreams AI Can Buy:** Retail-facing, 1:1 AI coaching for individuals and small businesses.
```

## Why Separate?

Skills are shared. Your setup is yours. Keeping them apart means you can update skills without losing your notes, and share skills without leaking your infrastructure.

---

Add whatever helps you do your job. This is your cheat sheet.
