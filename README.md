<h1 align="center">Himansh Raj</h1>

<p align="center">
  <b>Applied AI engineer.</b> I build the layer underneath the models:<br/>
  gateways, agent runtimes, and inference that runs on your own machine.
</p>

<p align="center">
  <a href="https://himansh.in">himansh.in</a> ·
  <a href="https://maya.himansh.in">maya.himansh.in</a> ·
  <a href="https://huggingface.co/iamthehimansh">Hugging Face</a> ·
  <a href="https://linkedin.com/in/iamthehimansh">LinkedIn</a> ·
  <a href="https://x.com/iamthehimansh_">X</a>
</p>

---

## Maya OS: a local-first AI operating system

```bash
npm i -g maya-os && maya
```

One command boots an **OpenAI- and Anthropic-compatible gateway** that routes a
single request surface across cloud providers *and* local GGUF models
(llama.cpp / Metal), with RAM guardrails that degrade instead of killing your Mac.

On top of it: **agent teams running on real PTYs**. Claude Code, Codex and
`maya code` driven as genuine terminal processes, coordinated by an orchestrator
with a persistent loop agent, a message bus, and SQLite-backed shared contracts.
Eight packages, MIT, shipped.

| | |
|---|---|
| **Maya OS**, the platform | [`maya-os`](https://www.npmjs.com/package/maya-os) · [repo](https://github.com/iamthehimansh/Maya-os) |
| **maya code**, the coding agent | [`@maya-os/code`](https://www.npmjs.com/package/@maya-os/code) · [repo](https://github.com/iamthehimansh/Mayac) |

`maya code` is a provider-agnostic agent loop over the Anthropic + OpenAI SDKs
with a full-screen Ink TUI, skills, **MCP**, sub-agents, workflows and mid-turn
steering of a running agent.

---

## What else I build

**Models from scratch.** [F75](https://github.com/iamthehimansh/F75), a ~100k-parameter
LM trained end-to-end on one RTX 5060 Ti to study next-token behaviour under
extreme capacity limits. [LlamaVision](https://huggingface.co/iamthehimansh/LlamaVision-llama-3.3-1b),
a 6.3M-parameter projector aligning vision features into a frozen Llama-3.3-1B
embedding space.

**Systems, low enough to hurt.** [H++](https://github.com/iamthehimansh/Hpp), a
statically-typed language whose only primitive is the *bit* (compiler + runtime
in C and Assembly). An [8085 emulator](https://github.com/iamthehimansh/8085-sumulation)
with full 64KB addressing and step debugging. [NetGuard](https://github.com/iamthehimansh/NetGuard),
a no-root Android firewall that intercepts DNS through a local VpnService tunnel.

**Infra for my own work.** [boxctl-deck](https://github.com/iamthehimansh/boxctl-deck),
GPU workstation fleet control over SSH with live telemetry.

---

## Now

**Applied AI Engineer @ Colate.** Built the multi-provider LLM gateway behind Cana: one
shared request/event representation translating **OpenAI, Anthropic and Gemini**
formats, with streaming, tool calls and multimodal inputs. Added prompt caching
and token accounting: **6.05B cached input tokens, 53% input-token reuse,
35% lower inference latency**. Also built its multi-agent orchestration (worker,
reviewer and lead roles, dependency-aware delegation, inter-agent messaging) and
persistent AWS/Kubernetes runtimes.

**Research Intern @ MISN Lab, IIT Delhi.** Agentic systems for recommendation
under Dr. Sandeep Kumar: retrieval, planning and tool use, plus the evaluation
methodology to tell whether any of it actually works.

---

## Won

**HIVE** @ IIT Delhi 2024 · **FinAThon** @ IIT Delhi 2023 ·
**Top 10 worldwide** @ IIT Bombay TechFest 2023 · **3rd** @ DEXTERIX 4.0

---

<p align="center"><i>B.Tech CSE (AI &amp; ML), IILM University · 2023-2027 · Noida, India</i></p>
