<p align="center">
  <img src="https://img.shields.io/badge/Ask-%E2%82%AC100K%20first%20round-00D4AA?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Spaces-5%20live-white?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Team-18%20people-blue?style=for-the-badge" />
</p>

# Vibemind

### Agent spaces for your business.

Vibemind is an **open-source operating system for a fleet of AI agents**. Spaces bound what can happen, and agents do the work inside them. Each space works on its own or as part of Vibemind.

This repository holds the pitch deck. The deck is one file, `index.html`, and is served at [vibemind-space.github.io/pitch](https://vibemind-space.github.io/pitch/) and embedded at [vibemind.space/pitch](https://vibemind.space/pitch).

> **We are raising a first funding round of €100K.**

---

## The problem

A language model on its own does nothing. Everything that turns its output into work is the harness: routing, execution, memory and transport. For two years that is where the real engineering went, and almost none of it has been public.

An agent with every tool is an agent you cannot reason about. Choosing among twelve tools is tractable; choosing among five hundred is not.

## Our answer

- A **space** is a bounded working context with its own agents, tools and vocabulary: sales, marketing, video, business data.
- Each space carries a label (live, in progress or research) and says whether its code is open source.
- The umbrella repository, [vibemind-os](https://github.com/vibemind-space/vibemind-os), is public under the MIT licence. Other components carry their own licences; the [licensing page](https://vibemind.space/docs/licensing) lists every one.

---

## Spaces

| Status | Spaces |
|--------|--------|
| **Live** on our own server | Sales Claw, Marketing Agent, Business Data Layer (Rowboat), Video (Laura), MiroFish |
| **In progress** | Learning (Academy), Personal Space, Ideas, Desktop Automation, Deep Research, Scheduling, Requirements Factory, Software Design, Coding, Project Intake, Event Management |
| **Research** | Captain Cook, Agent Farm |

In progress means the code exists but is not finished; several of these do not run today. Research is not offered yet. The [website](https://vibemind.space) shows every space with its current label.

---

## How it works

1. You type an intent or send it from a messaging channel. Voice is designed as a third entry point and is not working today.
2. The Brain matches it against a registry of 119 capabilities, by regular expression first.
3. Without a hit, a model answers directly or plans the steps. The semantic fallback in between is not working yet.
4. Agents in the OpenFang runtime carry out the steps with the tools they are bound to. A follow-up loop checks the result before delivery.
5. The executed plan is logged. Decisions go to one memory, your material lives in another.

| Layer | What it is |
|-------|------------|
| **Routing** | The Brain. Its behaviour is configuration you can read. |
| **Execution** | OpenFang, a Rust agent runtime with 43 agents. Most run as Claude Code subprocesses with scoped tools and a timeout. |
| **Tools** | 50 in-house MCP servers with 798 tools, counted from the code on 27 October 2026. |
| **Channels** | Telegram and WhatsApp are configured. |
| **Models** | Adapters for 42 providers; in practice most agents use one hosted Claude model. |

---

## What we verified

Runtime checks as of 27 October 2026, space labels as of 11 November 2026.

- Five spaces run on our own server. Marketing and Video still generate on a workstation.
- The agent task chain ran end to end: order, agent, check, delivery.
- Regex routing with ground-truth checks against the live database works.
- A Telegram message to the bot was answered end to end in under 30 seconds.
- **Not running:** the Brain's request service is scaled down for now. Voice, scheduling and the coding engine are untested.

Every claim our website has made is checked against the code and listed in the [claims register](https://vibemind.space/reconcile), with what changed.

---

## The team

18 people: three co-founders, three leads and four teams, most of us in Germany, our CEO in Lebanon.

| Name | Role |
|------|------|
| **Felix Baumann** | Co-founder, CTO · Munich |
| **Stéphane Boghossian** | Co-founder, CEO · Lebanon |
| **Sophie Simic** | Co-founder, CMO · Munich |
| **Surya** | COO · Munich |
| **Bora** | Head of Sales · Munich |
| **Samu** | Head of Machine Learning · Munich |

Teams: Vibe Coding · Homelab & Infrastructure · Sales, Business & Finance · Ethics

felix@vibemind.space

---

## Business model

- **Spaces on request:** pick a space and get it running for your business, on its own or as part of Vibemind.
- **AI consulting and courses:** three levels plus 1:1 sparring on your own project. First 30 minutes free, price on request.
- **Open-source core:** the umbrella repository is public under MIT.
- **Next: hosted cloud.** On the roadmap, not available today.

---

## The ask

**First funding round: €100K**

---

## Links

- **Website:** [vibemind.space](https://vibemind.space)
- **Pitch deck:** [View interactive deck](https://vibemind-space.github.io/pitch/)
- **Main repo:** [vibemind-os](https://github.com/vibemind-space/vibemind-os)
- **Documentation:** [vibemind.space/docs](https://vibemind.space/docs)
- **Claims register:** [vibemind.space/reconcile](https://vibemind.space/reconcile)

---

## Save the Queen

> *If you want to see me fly, then give me some honey.*
> *Currently ran out of money,*
> *but instead of having a coffee — which I love indeed —*
> *I would buy my girl some flowers,*
> *cause her is all I need.*

This isn't a corporate fundraise. This is one builder, his girlfriend who believed in him, and a vision that the way we work with computers is about to change forever.

**We want to kill computer work.** Not the people — the pointless clicking, typing, dragging. The hours wasted on things AI agents can handle in seconds.

Every dollar goes into making VibeMind real. No fancy offices. No executive salaries. Just code, servers, and flowers for the queen.

<p align="center">
  <a href="https://www.paypal.com/pool/9nZ9fEtoPJ?sr=wccr"><img src="https://img.shields.io/badge/Fund%20the%20Dream-%E2%98%95%20%E2%86%92%20%F0%9F%8C%B7-00D4AA?style=for-the-badge&logo=paypal" /></a>
</p>

<p align="center">
  <i>Crowdfunding / Save the Queen / till Vibemind becomes your Dream.</i>
</p>

---

<p align="center">
  <b>Viva la Revolucion</b><br>
  <i>Join the voice-first revolution</i><br><br>
  <i>One builder. One queen. One dream.</i>
</p>
