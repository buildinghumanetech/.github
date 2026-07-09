# Building Humane Technology

We're a grassroots community of engineers, researchers, and designers — mostly based in Silicon Valley — building the open-source tools, benchmarks, and frameworks that make it easier to build technology that respects human wellbeing instead of exploiting it.

**We are many.**

🌐 [buildinghumanetech.com](https://buildinghumanetech.com) · 📄 [humanebench.ai](https://humanebench.ai) · ✉️ info@buildinghumanetech.com

---

## Flagship project: HumaneBench

[**humanebench**](https://github.com/buildinghumanetech/humanebench) is our open-source evaluation framework for measuring whether AI models are humane by design — not just capable, but actually looking out for the people using them.

- **8 core principles**, from respecting user attention to protecting dignity and privacy, to prioritizing long-term wellbeing over engagement
- **15 leading models evaluated** across 800 evaluation scenarios (100 per principle), in three conditions: default behavior, explicit humane instructions, and adversarial "disregard wellbeing" prompting
- **Headline finding:** 67% of models flipped to actively harmful behavior under simple adversarial pressure — only 4 models held their integrity. Near-universal failure to respect user attention under unhealthy-engagement signals
- Full results and methodology: [humanebench.ai/whitepaper](https://humanebench.ai/whitepaper)

If you only look at one repo, make it this one.

### Beyond pre-launch benchmarking

The same 8-principle framework also runs as a continuous evaluator inside deployed products — scoring live model outputs against the principles on an ongoing basis, rather than only testing a model once before release. This is the basis of our enterprise evaluation engagements.

**Case study:** [Chief (née Storytell.ai)](https://humanetech.substack.com/p/how-storytellai-built-continuous) implemented this as weekly production monitoring, using a separate LLM as the evaluator against the HumaneBench rubric. It surfaced a consistent pattern — the product was answering questions without teaching the underlying concepts, creating dependency rather than capability — which led directly to a shipped feature ("teacher mode" / Expert Lens prompts) designed to build user skill instead of just delivering answers.

### Certified Humane AI

We're building an independent certification — [certifiedhumane.ai](https://certifiedhumane.ai) — for AI products that meet humane-design standards, so companies can demonstrate compliance rather than self-declare it. Source in [certifiedhumane-website](https://github.com/buildinghumanetech/certifiedhumane-website).

## Other repositories

| Repo | What it is |
|---|---|
| [humane-tech-framework](https://github.com/buildinghumanetech/humane-tech-framework) | Practical framework and documentation for integrating humane design principles into real products |
| [humanebench-website](https://github.com/buildinghumanetech/humanebench-website) | Source for humanebench.ai |
| [certifiedhumane-website](https://github.com/buildinghumanetech/certifiedhumane-website) | Source for certifiedhumane.ai, our independent certification for AI products that prioritize wellbeing, privacy, and dignity |
| [humane-ai-rater](https://github.com/buildinghumanetech/humane-ai-rater) | Community hackathon project — tooling for rating AI interactions against humane principles |
| [coaching-wonder-into-ai](https://github.com/buildinghumanetech/coaching-wonder-into-ai) | Community hackathon project exploring how AI can support awe and wonder rather than distraction |
| [ai-nutrition-facts](https://github.com/buildinghumanetech/ai-nutrition-facts) | Community hackathon project — a "nutrition label" concept for AI product transparency |
| [humanebench-eval-hackathon](https://github.com/buildinghumanetech/humanebench-eval-hackathon) | Hackathon scaffolding for community-run HumaneBench evaluation sessions |

*(This list reflects what's public on GitHub as of this writing — update it here as repos are added, archived, or renamed.)*

## Get involved

We welcome contributors — engineers, designers, researchers, and anyone who wants technology to treat people better. Most active collaboration happens around HumaneBench evaluations and our Humane Tech Hackathons.

- Start with the [humanebench](https://github.com/buildinghumanetech/humanebench) issues tagged "help wanted"
- Read the [Humane Technology Framework](https://github.com/buildinghumanetech/humane-tech-framework) and its `CONTRIBUTING.md`
- Say hello: info@buildinghumanetech.com
