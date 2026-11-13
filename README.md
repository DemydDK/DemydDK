# Demyd Sudarenko

I build AI-first products end to end: from the insurance core and provider integrations to the website, the analytics and the AI agents that run day-to-day work.

**Now:** founder and product engineer of **[TEHET](https://tehet.com.ua)** — online car insurance in Ukraine.

## What I built

- **An insurance platform with a provider-neutral core.** Quoting, checkout, payments and policy issue live in one core; brands are configuration on top of it.
- **Integrations with insurance providers.** Live quotes from many insurers, failover between providers, OTP signing, payment and policy documents by e-mail.
- **A public MCP server** — [tehet-mcp](https://github.com/DemydDK/tehet-mcp). AI assistants (Claude, ChatGPT and others) can get live indicative car insurance prices. It is listed in the official MCP Registry.
- **Pages built for AI assistants.** Each page answers one purchase question with a dated price, so an assistant can cite it.
- **An AI operations team.** Several AI agents work in parallel under written guardrails: no deploys without approval, no personal data in logs, a shared log of lessons learned.

## How I work

- Production first, measured by numbers. A change is done when it is deployed, verified and written down: why, what changed, how to roll back.
- Small, reversible steps, tests before every deploy, and clear error messages, so a customer always knows what to do next.
- Security by default: encrypted personal data, no secrets in code, staging separate from production.

## Featured

- [tehet-mcp](https://github.com/DemydDK/tehet-mcp) — public MCP server for live Ukrainian car insurance prices
- [multi-brand-insurance-platform](https://github.com/DemydDK/multi-brand-insurance-platform) — architecture case study and open examples

The core platform is commercial and closed source. I am happy to walk through the live product and the architecture in a call.
