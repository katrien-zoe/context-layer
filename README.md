# marketing-os

A marketing operating system that works in two places at once: Notion for people, markdown for agents.

Same structure, same content, two formats. Fill it in once, and both your team and your AI read from the same foundation.

## The problem this solves

AI makes marketing output fast. It does not make it consistent.

Ask an agent for ten LinkedIn posts and you get ten posts. Whether they sound like your company, reflect your current positioning, or contradict what you published last quarter is a coin flip. Every new piece starts from scratch, so nothing compounds.

The fix isn't a better prompt. It's a foundation the work reads from. That's what this is.

## What's in here

```
CLAUDE.md              → the spine. Top-line context, always loaded first.
context/
  business-context.md  → who we are, what we do, who we sell to, the rules
  competitors.md       → the landscape, per-competitor profiles, white space
  brand-guidelines.md  → brand core, visual identity, voice and writing rules
  expert-pov.md        → founder beliefs, contrarian takes, the one big idea
  goals.md             → targets and KPIs, as context work can point at
```

Six files. Fill them in, and everything downstream gets sharper.

## How to use it

**If you work in markdown / Claude Code:** clone the repo, fill in the templates, keep them next to your work. Claude reads `CLAUDE.md` first and follows it to whatever else it needs.

**If you work in Notion:** the same structure exists as a Notion template. Fill in whichever you prefer and mirror it across. The content is what matters, not the format.

**If you're not technical:** every file here is plain text. Open it in your browser, read it, copy it. No installation, nothing to run.

Start with `context/business-context.md`. It's the one everything else references.

## Why two formats

Most teams have humans who live in Notion and agents that live in files. Pick one and you either lose the people or lose the machine. Keeping both in sync costs a little discipline and solves a lot of drift.

## Credit

The four-layer architecture (context, skills, orchestration, integrations) and the idea of a context spine come from [Matteo Tittarelli's AI GTM system](https://www.growthunhinged.com/p/how-to-build-your-ai-gtm-system). He published it to be copied. This is that structure, extended with the operational layer a marketing lead actually runs and mirrored into a format non-technical teams can use.

## Who's behind this

Katrien Zoë Depoorter. B2B tech marketer. Builder by nature. Brand, demand and operational set-up.

[LinkedIn](https://www.linkedin.com/in/katrienzoedepoorter/) · [Substack](https://katrienzoe.substack.com) · [portor-co.be](https://www.portor-co.be/)
