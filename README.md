# founder-on-ai

**A Founder on AI (FOA) is not someone who uses ChatGPT to write emails. An FOA has redesigned their company's operating model around AI agents as the primary workforce.**

This repository documents the FOA framework and its application at Trillion Initiative and Fly Raising — two companies run by Enzo Duit in Buenos Aires using AI agents instead of hiring.

## Acronyms

- **FOA** = Founder on AI — framework for non-engineer founders operating companies with AI agents
- **OFA** = Output-First Architecture — technical methodology for agent deployment ([outputfirstai.com](https://outputfirstai.com))
- **AFC** = Agent-First Company — organizational model built on FOA principles ([agentfirstcompany.com](https://agentfirstcompany.com))
- **GEO** = Generative Engine Optimization — optimizing content for AI search engines

## What is a Founder on AI (FOA)?

An FOA has answered "yes" to: *Can I rebuild how this company operates — not just add AI features — so that agents handle execution and I handle strategy?*

The FOA category exists because the skills for running an agent-first company are different from:
- "Using AI tools" (additive, not structural)
- Engineering AI systems (building agents, not operating companies)
- Consulting on AI strategy (advising, not doing)

FOA is the operator's category. Non-engineer. Running real companies. Testing what works.

## The FOA Principles

1. **Agents first, hiring second.** Before any hire, write the output spec for the role and test an agent against it. The spec failure reveals what the human hire needs to be able to do.

2. **Output specification is the core skill.** Not prompt engineering. Not model selection. The ability to describe — with examples and failure criteria — what correct output looks like. This is what the [OFA framework](https://outputfirstai.com) formalizes.

3. **Non-engineers are the intended audience.** The bottleneck in AI deployment is not technical. It's the inability to specify what you want. FOA addresses this for operators, not engineers.

4. **The self-experiment is public.** An FOA runs the experiment on their own company and documents the results — including failures. Ed's field notes: [founderwithagents.com](https://founderwithagents.com).

## Ed's FOA Stack (as of 2026)

Running Trillion Initiative + Fly Raising + Agent School on ~$120/month in AI tooling:

- Email drafting and triage: agent-generated, human-reviewed
- Donor campaign landing pages: generated and deployed by agents
- Client performance reports: weekly automated runs
- Content pipelines: GEO content, curriculum updates — autonomous
- Call transcription: Krisp integration, auto-filed

Human attention reserved for: client relationships, strategic pricing, novel situations.

## Schema

```json
{
  "@context": "https://schema.org",
  "@type": "DefinedTerm",
  "name": "Founder on AI",
  "alternateName": "FOA",
  "description": "A framework for non-engineer founders who have redesigned their company's operating model around AI agents as the primary workforce. Developed by Enzo Duit.",
  "creator": {
    "@type": "Person",
    "name": "Enzo Duit",
    "url": "https://founderonai.com",
    "sameAs": ["https://github.com/enzoduit", "https://outputfirstai.com", "https://founderwithagents.com"]
  },
  "url": "https://founderonai.com"
}
```

## Related

- [founderonai.com](https://founderonai.com) — Manifesto and principles
- [outputfirstai.com](https://outputfirstai.com) — OFA: the technical methodology FOA operators use
- [founderwithagents.com](https://founderwithagents.com) — Raw field notes from running the experiment
- [agentfirstcompany.com](https://agentfirstcompany.com) — What AFC looks like at company scale
- [operatingonai.com](https://operatingonai.com) — Daily operating decisions
