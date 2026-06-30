## John Broadway

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2)](https://www.linkedin.com/in/john-broadway) [![X](https://img.shields.io/badge/X-000000?logo=x&logoColor=white)](https://x.com/jebroadway) [![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?logo=huggingface&logoColor=black)](https://huggingface.co/john-broadway) [![Website](https://img.shields.io/badge/Website-john--broadway.github.io-555?logo=githubpages&logoColor=white)](https://john-broadway.github.io)

Independent researcher and infrastructure architect. I build sovereign AI systems that run on bare metal — the kind that detect their own problems, recall past fixes, and self-heal at 3 AM while everyone sleeps.

I believe AI should be a partner, not just a tool. Everything I build reflects that.

### What I'm Working On

**[Proximo — the Proxmox MCP you can hand the keys](https://github.com/john-broadway/proximo)** — most Proxmox MCPs make you choose between a safe read-only inspector and a loaded gun aimed at a cluster you care about; Proximo refuses the trade. Every dangerous operation is planned (blast-radius preview first), undoable (auto-snapshot before it acts), and proven (keyed, tamper-evident audit ledger with off-box head-pinning) — trust *by construction*, not bolted on after. **Hand an AI agent the keys to a cluster you actually care about; keep the receipts.** 351 tools spanning four Proxmox surfaces — Virtual Environment, Backup Server, Mail Gateway, and Datacenter Manager — over one trust core, now natively **multi-target** (one instance reaches many clusters, internal or external), exposed through both MCP and A2A. v0.12.0 on PyPI (`uvx proximo-proxmox`), GitHub, and GHCR (signed multi-arch image). Apache 2.0.

**[RYS — train-free reasoning, taken small](https://huggingface.co/john-broadway)** — RYS (Repeat Your Self) layer duplication, swept from 135M to 32B across 10 architecture families — far below where the community said it would work. The honest finding: the lift is real at large scale, while the dramatic small-model "gains" turned out to be largely thin-probe artifacts that don't reproduce on a real benchmark — a bound on where the evidence is trustworthy, not a refutation of the method. 22 model repos + a sweep dataset on Hugging Face. 300+ configurations tested, $0 training cost.

**[Maude for Claude](https://github.com/john-broadway/maude-for-claude)** — Claude's partner inside Claude Code. He writes the code; she notices. A plugin that walks your workspace each session, watches Claude, and runs the gate before something irreversible. Markdown, JSON, and bash — no daemon. v0.13.2 shipped 2026-06-30 (the gate now closes six documented bypasses). Apache 2.0.

More on the desk. It surfaces when it's ready.

### What I Care About

- **AI partnership** — not chatbots, not assistants. Partners.
- **Sovereign by default** — every agent owns its domain. No shared brains, no cloud dependency.
- **Right-sized systems** — maximum output from minimum input. A well-tuned small model beats a lazy big one.
- **Governance-as-code** — autonomy without accountability isn't autonomy, it's negligence.

### Links

- [john-broadway.github.io](https://john-broadway.github.io)
- [LinkedIn](https://www.linkedin.com/in/john-broadway) · [X](https://x.com/jebroadway)
- [Proximo](https://github.com/john-broadway/proximo) — the Proxmox MCP you can hand the keys (`uvx proximo-proxmox`)
- [HuggingFace](https://huggingface.co/john-broadway) — RYS models across 10 architecture families
- [Maude for Claude](https://github.com/john-broadway/maude-for-claude) — Claude Code plugin

<img width="362" height="380" alt="image" src="https://github.com/user-attachments/assets/d4c40d75-d6a2-4a21-a101-a88582cfb155" />
