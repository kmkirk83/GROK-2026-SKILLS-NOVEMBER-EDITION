# GROK 2026 SKILLS NOVEMBER EDITION

Complete collection of Grok skills (bundled system skills + user custom skills) as of November 2026.

This repository provides a clean, categorized archive of every available skill. Each skill lives in its own directory containing a `SKILL.md` file (and supporting scripts/references where applicable).

## Repository Structure

```
├── bundled/                  # Core system / platform skills
│   ├── color/
│   ├── docx/
│   ├── ffmpeg/
│   ├── finance/
│   ├── image-gen-edit/
│   ├── imagemagick/
│   ├── mcp/
│   ├── memory-edit/
│   ├── pdf/
│   ├── pptx/
│   ├── skill-creator/
│   ├── skill-installer/
│   ├── tasks/
│   └── xlsx/
├── custom/                   # Specialized autonomous, business, and product skills
│   ├── agent-eval-improver/
│   ├── autonomous-ai-build-playbook/
│   ├── autonomous-income-engine/
│   ├── autonomous-research-synthesizer/
│   ├── autonomous-ship-deploy/
│   ├── background-completion-swarm/
│   ├── continuous-improvement-loop/
│   ├── demo-walkthrough-recorder/
│   ├── design-quality-gate/
│   ├── ecommerce-maximizer-package/
│   ├── full-autonomous-product-machine/
│   ├── high-reliability-coding-mode/
│   ├── hyperframes-demo-enhancer/
│   ├── income-focused-ecommerce-stack/
│   ├── knowledge-work-plugins/
│   ├── meta-orchestration-system/
│   ├── ponytail/
│   ├── premortem-prompts/
│   ├── product-delivery-swarm/
│   ├── project-autonomy-bootstrap/
│   ├── realtime-agent-orchestra/
│   ├── research-to-product-pipeline/
│   ├── revenue-first-prompt-system/
│   ├── secret-sauce/
│   ├── security-audit-gate/
│   ├── shopify-instagram-business-ai/
│   ├── skill-gap-analyzer/
│   ├── task-decomposition-verifier/
│   └── vibe-coding-maximizer/
├── LICENSE
├── README.md
└── RELEASE_NOTES.md
```

## Categories & Skill Descriptions

### Bundled (System Skills)
These provide foundational capabilities for document generation, media processing, data, and skill management.

| Skill | Purpose |
|-------|---------|
| color | Color extraction, palette generation, contrast checking, CVD simulation |
| docx | Create, read, edit Word documents |
| ffmpeg | Video/audio processing, conversion, GIFs, subtitles |
| finance | Personal finance data access (accounts, transactions) |
| image-gen-edit | Image generation and editing (Grok Imagine) |
| imagemagick | Image manipulation utilities |
| mcp | MCP-related tooling |
| memory-edit | Persistent user memory management |
| pdf | PDF creation, reading, OCR, form filling, merging |
| pptx | PowerPoint presentation creation and editing |
| skill-creator | Create and validate new skills |
| skill-installer | Install / manage skills |
| tasks | Task management utilities |
| xlsx | Spreadsheet creation, reading, and manipulation |

### Custom (Specialized Skills)
High-effort autonomy, product delivery, ecommerce, research, and orchestration skills.

#### Autonomy & Orchestration
- **project-autonomy-bootstrap** — Single entry-point that activates the full autonomy suite at the start of any chat or project.
- **task-decomposition-verifier** — Hierarchical task breakdown + multi-stage verification and adversarial critique.
- **skill-gap-analyzer** — Detect capability gaps and recommend/create missing skills.
- **agent-eval-improver** — Evaluate agent outputs for thoroughness, autonomy, and effectiveness; recommend improvements.
- **realtime-agent-orchestra** — Set up multi-agent realtime orchestration systems from plain English.
- **meta-orchestration-system** — Higher-order management of agent crews and fleets.
- **background-completion-swarm** — Daily autonomous completion of unfinished work across repositories.
- **continuous-improvement-loop** — Closed-loop quality measurement and improvement.

#### Product Delivery & Shipping
- **autonomous-ship-deploy** — End-to-end build + deploy to Vercel (primary) or Netlify with live public URL.
- **product-delivery-swarm** — Full product completion (frontend, backend, tests, docs, GitHub Releases).
- **full-autonomous-product-machine** — Idea → live demoable product with design and security gates.
- **autonomous-ai-build-playbook** — Governed AI-assisted software build from intent to release.
- **high-reliability-coding-mode** — Quality-first coding prioritizing specification, verification, and maintainability.
- **vibe-coding-maximizer** — Elite practices for rapid yet reliable AI-assisted development and distribution.
- **demo-walkthrough-recorder** — Capture live product demos into captioned MP4 walkthroughs.
- **hyperframes-demo-enhancer** — Higher-quality HTML-to-video demos via HyperFrames.

#### Research & Decision Support
- **autonomous-research-synthesizer** — Long-horizon multi-source research with quality scoring and contradiction detection.
- **research-to-product-pipeline** — Evidence-first path from research through premortem into governed product build.
- **premortem-prompts** — Structured five-step premortem to stress-test any plan before execution.

#### Ecommerce & Income
- **shopify-instagram-business-ai** — Automated Shopify + Instagram operations, content, and growth.
- **ecommerce-maximizer-package** — Maximum-effort ecommerce system combining store ops, Instagram, and autonomy.
- **income-focused-ecommerce-stack** — Zero-capital to revenue ecommerce and digital product system.
- **autonomous-income-engine** — Zero-capital income generation via digital products and self-replicating agents.
- **revenue-first-prompt-system** — Structure every output for measurable revenue paths and monetization.
- **secret-sauce** — Proven monetization playbook used by high-earning indie developers and solo founders.

#### Quality & Design Gates
- **design-quality-gate** — Design critique, anti-AI-slop detection, and professional design vocabulary.
- **security-audit-gate** — Multi-phase security audit with independent verification before production.

#### Other
- **knowledge-work-plugins** — Role specialization and structured professional workflows (engineering, sales, product, etc.).
- **ponytail** — Minimalist “laziest dev” style that writes one line and completes the project.

## Usage

Each `SKILL.md` contains:
- YAML frontmatter with `name` and `description` (triggers)
- Detailed instructions, protocols, constraints, and examples

Load a skill by referencing its name or description in conversation. The system matches triggers automatically.

## Full Binary Package

A complete zip of every skill (all SKILL.md files + scripts + references) is available in the originating conversation artifacts and referenced in the v1.0.0 release.

**Release**: https://github.com/kmkirk83/GROK-2026-SKILLS-NOVEMBER-EDITION/releases/tag/v1.0.0

---
*Populated via Composio · November 2026*
