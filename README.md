![marketing-os: stop re-explaining your company. The context layer of a marketing operating system.](cover.png)


# Context layer

A marketing operating system covers a lot of ground: positioning, campaigns, content, budgets, numbers, playbooks, the way a team works.

This repo is one layer of it. The one everything else depends on: **context**. What a company knows about itself, written down so every piece of work starts from the same place instead of from scratch.

## Where this fits

A marketing OS has four layers:

- **Context**: what the company knows about itself. ICP, positioning, brand and voice, competitors, goals.
- **Execution**: campaigns, content, assets, customer stories, the work itself.
- **Measurement**: what you track, and what it's telling you.
- **Operations**: playbooks, process, how the team actually works.


![The four layers of a marketing OS, with context first. This repo is the context layer.](layers.png)


Context comes first, because every other layer reads from it. Get the positioning wrong and every campaign after it is wrong too.

This repo holds that layer, and only that layer, because it's the part that's useful to someone else empty. A blank ICP framework still helps you think. A blank playbook is a table with headers.

Some of the other layers will follow. Others won't: process, team frameworks and playbooks are only worth anything when they come from actually having done the work.

It is not software. Nothing to install. Six markdown files and the discipline to keep them current.

## The problem this solves

**Marketing context is scattered by default.** Forty files across five tools, half of them out of date, and one person who knows where everything is. Everyone works from a slightly different version, so everything you produce moves a little further away from the last thing.

**AI copies whatever you give it.** If what you give it is thin or out of date, you get more of that, faster. It doesn't improve on the way in.

**If it isn't written down, you become the bottleneck.** Start building a real marketing function and you add people: a first hire, a freelancer, an agency, a few agents. Every one of them needs the same background, and you are the only place to get it. Sales, product and support too, all describing the same company to the same buyers, usually from different versions of it.

Writing it down is what lets you add people without everything falling apart.

## Who it's for

- **Startups getting ready to grow.** One or two marketers today, but preparing for the next phase. This is where undocumented context stops being fine and starts being the thing slowing you down.
- **Marketing leads walking into that.** There's no discovery phase and then a doing phase. Filling this in is the discovery, and work comes out of it while you're still filling it in.
- **Small teams** re-answering the same questions every quarter because nobody wrote the answer down.
- **Anyone using AI for marketing** who is tired of re-explaining the company at the start of every session.
- **Freelancers and consultants** who need to hand over a working system, not a folder of deliverables.

If you already have a rigorous, current, single source of truth for positioning and voice, you don't need this. Most people don't.

## Status

Context layer: live. More will follow, selectively.

## What's in here

```
CLAUDE.md              → the short version of everything below. Read this first.
context/
  business-context.md  → who we are, what we do, who we sell to, the rules
  competitors.md       → the landscape, per-competitor profiles, white space
  brand-guidelines.md  → brand core, visual identity, voice and writing rules
  expert-pov.md        → founder beliefs, contrarian takes, the one big idea
  goals.md             → targets and KPIs, as context work can point at
example/               → all of the above filled in, plus what came out of it
```

Six files. Everything else is built on top of them.

## See what it looks like filled in

The `example` folder has all six files filled in for a made-up company. A small Belgian business that sells booking software to padel clubs.

It also has three things that were written using those files: a campaign plan, a LinkedIn post, and a positioning statement.

Each of those three is shown twice. Once written by an AI that knew nothing about the company. Once written by an AI that had read the six files first. Underneath each pair, a table shows which file caused which difference.

**Open [`example/output/campaign-brief.md`](example/output/campaign-brief.md) first.** Both versions came from the same one-line request: "draft a Q3 campaign plan".

The first one could be about any company. The second one knows which channels this company already tried and dropped, who it deliberately doesn't sell to, and how much its founder can realistically take on. Nobody put any of that in the request. It was already written down in the files.

## How to use it

Four steps.

**1. Get your own copy.**
Click "Use this template" at the top of this page and GitHub makes you your own version. Or if that feels like a lot, click into any file, copy the text, and paste it into a Google Doc or Notion page. Both work fine.

**2. Fill in the six files.**
Everything in [square brackets] or *italics* is a prompt for you to replace with your own answer. Start with `business-context.md`, because the others refer back to it.

This takes about an afternoon. You'll want a long conversation with whoever knows the business best, the website open in another tab, a few sales calls if you have them, and an hour looking at competitors.

**3. Let your AI read the files, don't paste them in.**
The point is that it reads the current version every time. Paste text into a chat and you're working from a copy you chose by hand, which is out of date the moment you change something.

Two ways that work properly:

*Keep them as files.* Use a tool that reads the folder directly, like Claude Code. You tell it to read `CLAUDE.md` and it finds the rest on its own. It runs in a terminal, but you type in plain English.

*Keep them in Notion.* Rebuild the six files as Notion pages and connect Notion to Claude. It reads the live pages, so when you update one, the next thing you ask is already using it. If your team lives in Notion, this is the better option.

Either way, update the file or the page and everything after it uses the new version. That's the whole trick.

If you just want to try it once, paste the files into a chat. Fine for a test, not a way to work.

**4. Keep them current.**
Every file has a change log at the bottom. When your positioning shifts or a competitor does something, update the file and date it. A file nobody updates is worse than no file, because people still trust it.

Your first version won't be right. Write it anyway and fix it later.

## Credit

The four-layer architecture (context, skills, orchestration, integrations) and the idea of a context spine come from [Matteo Tittarelli's AI GTM system](https://www.growthunhinged.com/p/how-to-build-your-ai-gtm-system). He published it to be copied. This is his structure, with the parts a marketing lead deals with day to day added, and written so people who don't use code can still use it.

## Using this

No licence yet. Shared as-is. Take what's useful, change what doesn't fit, and credit is appreciated but not required.

If you fill it in for your own company and something in the structure turns out to be wrong, tell me. That's the useful feedback.

## Who's behind this

Katrien Zoë Depoorter. B2B tech marketer. Builder by nature. Brand, demand and operational set-up.

[LinkedIn](https://www.linkedin.com/in/katrienzoedepoorter/) · [Substack](https://katrienzoe.substack.com) · [portor-co.be](https://www.portor-co.be/)

## Related

Part of [marketing-os](https://github.com/katrien-zoe/marketing-os), a set of marketing systems kept as public templates. A companion module, [get-recommended-by-ai](https://github.com/katrien-zoe/get-recommended-by-ai), covers getting your company named when a buyer asks an AI which software to use.
