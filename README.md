# Hi, I'm jali89-dot

I help open-source projects and small dev teams improve README, setup, and contributor onboarding documentation.

My current focus is practical setup testing: checking whether a new contributor can clone, configure, and run a project using the documented instructions.

## What I Can Help With

- README and setup documentation review
- Fresh contributor setup testing
- Missing or unclear environment variable documentation
- `.env.example` improvements
- CONTRIBUTING.md improvements
- Small documentation pull requests
- Clear issue and PR hygiene

## How I Work

I keep changes small, focused, and easy to review.

Before suggesting changes, I usually check:
- whether the README setup flow is complete
- whether required environment variables are documented
- whether `.env.example` exists and is safe
- whether install/dev/build commands are clear
- whether contributors might get stuck during setup

I do not include real secrets, tokens, credentials, or private environment values.

## Example Work

### OpenLife backend environment documentation

Problem:  
The project needed clearer documentation for backend production environment variables.

Action:  
I documented backend environment variables in the README, including `PORT`, `DATABASE_URL`, `DATABASE_NAME`, `JWT_SECRET`, `JWT_ACCESS_EXPIRATION_TTL`, and `NODE_ENV`, with safe production notes.

Result:  
Merged a focused documentation-only PR with no runtime code changes and no secrets included.

Merged PR:  
https://github.com/BhupinderSehjal/OpenLife/pull/121

### LuvLyricsApp contributor troubleshooting docs

Problem:  
The project needed contributor troubleshooting notes for setup, lint, typecheck, and test issues.

Action:  
I added a concise troubleshooting section to `CONTRIBUTING.md`, including Node version checks, dependency refresh steps, `.env.example` copy commands, CI check commands, and notes about Firebase/Google credentials.

Result:  
Merged a focused documentation-only PR. The maintainer approved it and specifically liked the PowerShell env copy note, credentials clarification, and focused placement.

Merged PR:  
https://github.com/LuvLyricsApp/LuvLyricsApp/pull/58
## Services

**Quick README Review**  
I read your README/setup docs and identify unclear or missing setup steps.

**Setup Test Report**  
I follow the setup instructions, run the documented commands, and report what worked and what failed.

**Setup + Docs Improvement Report**  
I test the setup flow, document blockers, and suggest exact README/CONTRIBUTING improvements.

## Current Focus

- JavaScript / TypeScript projects
- React / Next.js / Node.js projects
- Open-source setup documentation
- Contributor onboarding
- Small docs PRs
