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

## Also shipping

### [humane-gate](https://github.com/buildinghumanetech/humane-gate)

HumaneBench rubric v4, running as an advisory check on every pull request. It scores what a diff changes about what software says or does to a person. It blocks nothing. It posts one verdict (clear, review, discuss, or needs context) and asks a question when the diff alone can't answer it. Teams can see what it would have caught on their real PRs for thirty days before deciding whether it should ever have teeth.

### [ai-bill-of-rights](https://github.com/buildinghumanetech/ai-bill-of-rights)

A versioned, signable, open-source AI Bill of Rights, live at [ai-for-people.org](https://ai-for-people.org). Each version lives as markdown in this repo. Verified humans can sign it, and signers are listed publicly.

### [defining-humane-ai](https://github.com/buildinghumanetech/defining-humane-ai)

An open-source, versioned definition of "humane AI." Researchers, policy people, and practitioners draft v1.0 in a working session co-located with AIES 2026 in Malmö on Thursday, October 15th, 2026. The repo holds the definition, an open letter anyone can sign, a companion white paper, and an adoption map. CC BY 4.0. Call for participation: [buildinghumanetech.github.io/defining-humane-ai](https://buildinghumanetech.github.io/defining-humane-ai/).

## Other repositories

| Repo | What it is |
|---|---|
| [humane-tech-framework](https://github.com/buildinghumanetech/humane-tech-framework) | Practical framework and documentation for integrating humane design principles into real products |
| [humanebench-website](https://github.com/buildinghumanetech/humanebench-website) | Source for humanebench.ai |
| [wonder-lab](https://github.com/buildinghumanetech/wonder-lab) | Source for the Wonder Lab site, our research initiative measuring whether AI interaction changes awe and self-transcendent experience |
| [certifiedhumane-website](https://github.com/buildinghumanetech/certifiedhumane-website) | Source for certifiedhumane.ai, a prototype certification for AI products that prioritize wellbeing, privacy, and dignity |

*(This list reflects what's public on GitHub as of this writing — update it here as repos are added, archived, or renamed.)*

## Get involved

We welcome contributors — engineers, designers, researchers, and anyone who wants technology to treat people better. Most active collaboration happens around HumaneBench evaluations and our Humane Tech Hackathons.

- Start with the [humanebench](https://github.com/buildinghumanetech/humanebench) issues tagged "help wanted"
- Read the [Humane Technology Framework](https://github.com/buildinghumanetech/humane-tech-framework) and its `CONTRIBUTING.md`
- Say hello: info@buildinghumanetech.com

  [![building-humane-technology on Cossmology](https://vpxherzezesqifjloaxx.supabase.co/functions/v1/generate-badge?shortname=building-humane-technology&siteUrl=https%3A%2F%2Fcossmology.com&v=2)](https://cossmology.com/organizations/building-humane-technology)

