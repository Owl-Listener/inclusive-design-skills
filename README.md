# Inclusive Design Skills

> **Part of the [Designer Skills suite](https://github.com/Owl-Listener/designer-skills).**
> Install this collection and four more with one command in Claude Code:
>
> `/plugin marketplace add Owl-Listener/designer-skills`
>
> This repo still works on its own. The suite just gives everyone one front door.


Agentic skills for designing accessible, inclusive products — from cognitive accessibility to adaptive interfaces, inclusive research, and accessibility decision-making.
**40 skills** and **18 commands** across **6 plugins**.

Works with any AI coding agent that supports the SKILL.md format: [Claude Code](https://docs.anthropic.com/en/docs/claude-code), [OpenAI Codex](https://openai.com/index/codex/), [Gemini CLI](https://github.com/google-gemini/gemini-cli), [Cursor](https://www.cursor.com), and others.

## Why This Exists

Every accessibility skill set that exists today is engineer-facing. They audit code, check WCAG compliance, validate ARIA attributes, and flag contrast ratios. They treat accessibility as a technical implementation problem that gets caught at the end.

This collection operates **before code**. It shapes decisions about information architecture, language, interaction patterns, cognitive demands, and inclusion — the design layer that determines whether something is genuinely usable, not just technically compliant.

Accessibility isn't a code review. It's a design commitment.

## Plugins

| Plugin | Skills | Commands | Description |
| --- | --- | --- | --- |
| [cognitive-accessibility](cognitive-accessibility) | 8 | 3 | Design for how people actually think: cognitive load, plain language, wayfinding, focus, memory, and error recovery. |
| [inclusive-interaction](inclusive-interaction) | 7 | 3 | Design multi-modal interactions that adapt to how people move, perceive, and communicate. |
| [accessible-content](accessible-content) | 7 | 3 | Structure content that works for screen readers, cognitive differences, and diverse literacy levels. |
| [inclusive-personas](inclusive-personas) | 6 | 3 | Build user stories, personas, and scenarios that include disability from the start. |
| [adaptive-interfaces](adaptive-interfaces) | 6 | 3 | Design systems that respect user preferences and adapt to individual needs. |
| [accessibility-decisions](accessibility-decisions) | 6 | 3 | Document, communicate, and maintain accessibility decisions across teams and time. |

## Quick Start

### Claude Code

Add the marketplace:

```
/plugin marketplace add Owl-Listener/inclusive-design-skills
```

Then run `/plugin`, open the **Discover** tab, and install the plugins you want.

Or get this collection plus four more in one go, through the full suite:

```
/plugin marketplace add Owl-Listener/designer-skills
```

### Other Tools

Skills use the universal SKILL.md format. Copy the skill folders into your tool's skills directory, or reference them directly from this repo. Each SKILL.md file works as a standalone instruction set.

For manual use without a coding agent: open any SKILL.md file, copy the contents, and paste it as context at the start of a conversation with any AI assistant. The frameworks and decision criteria work regardless of the tool.

## What Are Skills and Commands?

- **Skills** are domain knowledge units (nouns). They teach your AI agent about a specific aspect of inclusive design — like assessing cognitive load, writing plain language content, or designing forgiving error flows.
- **Commands** are workflows (verbs). They chain multiple skills together to accomplish a task — like running a full cognitive accessibility review or generating an inclusive persona set.

## All Commands

| Command | Plugin | Description |
| --- | --- | --- |
| `/cognitive-accessibility:review` | cognitive-accessibility | Run a full cognitive accessibility review of a flow or interface. |
| `/cognitive-accessibility:simplify` | cognitive-accessibility | Simplify content and interactions to reduce cognitive load. |
| `/cognitive-accessibility:assess-load` | cognitive-accessibility | Assess cognitive load across a multi-step process. |
| `/inclusive-interaction:audit` | inclusive-interaction | Audit an interface for multi-modal interaction support. |
| `/inclusive-interaction:design-flow` | inclusive-interaction | Design an interaction flow with inclusive input and output options. |
| `/inclusive-interaction:keyboard-review` | inclusive-interaction | Review keyboard navigation and focus management. |
| `/accessible-content:review` | accessible-content | Review content for accessibility across cognitive and literacy levels. |
| `/accessible-content:rewrite` | accessible-content | Rewrite content in plain language while preserving meaning. |
| `/accessible-content:structure` | accessible-content | Structure content for screen reader and assistive technology use. |
| `/inclusive-personas:generate` | inclusive-personas | Generate a diverse, inclusive persona set for a product. |
| `/inclusive-personas:audit-stories` | inclusive-personas | Audit user stories for disability inclusion. |
| `/inclusive-personas:scenario-map` | inclusive-personas | Map inclusive usage scenarios across ability spectrums. |
| `/adaptive-interfaces:specify` | adaptive-interfaces | Specify adaptive behaviour for an interface. |
| `/adaptive-interfaces:preference-audit` | adaptive-interfaces | Audit respect for user preferences (motion, contrast, colour scheme). |
| `/adaptive-interfaces:responsive-review` | adaptive-interfaces | Review responsive and flexible layout for accessibility. |
| `/accessibility-decisions:document` | accessibility-decisions | Document accessibility decisions and tradeoffs for a feature. |
| `/accessibility-decisions:review` | accessibility-decisions | Review and surface undocumented accessibility assumptions. |
| `/accessibility-decisions:handoff` | accessibility-decisions | Generate an accessibility decision handoff for engineering. |

## Who This Is For

- **Designers** who want to build accessibility into their process, not bolt it on after.
- **Product managers** who need to make informed accessibility tradeoffs.
- **Content strategists** who write for diverse cognitive and literacy levels.
- **Researchers** who want to include disability in their work from the start.
- **Engineers** who want design-informed accessibility guidance, not just code linting.
- **Anyone** building products used by humans in the full range of human experience.

## Grounding and Sources

Every skill in this collection is grounded in established frameworks, standards, and research. Nothing here is invented — it's existing accessibility knowledge structured into a format AI agents can use.

### Standards and Guidelines

| Source | Used in | What I drew from |
| --- | --- | --- |
| [WCAG 2.2](https://www.w3.org/TR/WCAG22/) (W3C) | All plugins | Success criteria for visual, interaction, and content accessibility |
| [COGA: Making Content Usable](https://www.w3.org/TR/coga-usable/) (W3C) | cognitive-accessibility | The 8 objectives for cognitive accessibility design |
| [COGA Issue Papers](https://w3c.github.io/coga/issue-papers/) (W3C) | cognitive-accessibility | Research modules on cognitive disabilities and web access |
| [WAI-ARIA Authoring Practices](https://www.w3.org/WAI/ARIA/apg/) (W3C) | inclusive-interaction, accessible-content | Keyboard patterns, roles, and states for interactive components |
| [CSS Media Queries Level 5](https://www.w3.org/TR/mediaqueries-5/) (W3C) | adaptive-interfaces | prefers-reduced-motion, prefers-contrast, prefers-color-scheme |

### Frameworks and Methodologies

| Source | Used in | What I drew from |
| --- | --- | --- |
| [Microsoft Inclusive Design Toolkit](https://inclusive.microsoft.design/) | inclusive-personas | Permanent, temporary, and situational impairment spectrum |
| [Cognitive Load Theory](https://en.wikipedia.org/wiki/Cognitive_load_theory) (John Sweller) | cognitive-accessibility | Intrinsic, extraneous, and germane load framework |
| [Plain Language Guidelines](https://www.plainlanguage.gov/) (US Government) | cognitive-accessibility, accessible-content | Readability principles and content simplification |
| [Architecture Decision Records](https://adr.github.io/) | accessibility-decisions | Structure for documenting design decisions with context and rationale |
| [W3C Alt Text Decision Tree](https://www.w3.org/WAI/tutorials/images/decision-tree/) | accessible-content | Framework for choosing appropriate alt text strategy |

### Research and Advocacy

| Source | Used in | What I drew from |
| --- | --- | --- |
| [Nothing About Us Without Us](https://en.wikipedia.org/wiki/Nothing_About_Us_Without_Us) (Disability rights movement) | inclusive-personas, CONTRIBUTING.md | Principle of centring lived experience in design |
| [WebAIM Screen Reader Survey](https://webaim.org/projects/screenreadersurvey10/) | inclusive-interaction | Real-world assistive technology usage patterns |
| [WHO World Report on Disability](https://www.who.int/publications/i/item/9789241564182) | inclusive-personas | Global disability prevalence and population data |

### What I synthesised

The **accessibility-decisions** plugin applies established software engineering practices (ADRs, technical debt tracking, stakeholder communication) to accessibility — a combination that doesn't have a single authoritative source but draws on how experienced accessibility practitioners actually work. The **inclusive-personas** plugin structures Microsoft's impairment spectrum into actionable persona and scenario templates. These are the synthesis of existing thinking, not novel frameworks.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on adding new skills, commands, and plugins.

We particularly welcome contributions from people with lived experience of disability. Nothing about us without us.

## Related

Part of the [Designer Skills suite](https://github.com/Owl-Listener/designer-skills), alongside design practice, AI product design, UX program management, and design leadership. Install everything with one command, or pick just the collections you need.

## License

MIT — see [LICENSE](LICENSE).
