# Torchstack

Torchstack is an AI consultancy founded by [Scott Campit, PhD](https://torchstack.ai). We work with early-stage and SMBs who know AI should be part of their systems, but want to have technical support. We work with business owners to implement their visions: scoping the work, building the first version, and handing back something the team can actually run.

## What we do

Most engagements start with one of these:
- **AI Assessment** — a paid 1–2 week diagnostic that maps where AI fits (and where it doesn't) in your product or workflow. The deliverable is a written plan you can hand to any engineer.
- **Proof of Concept** — a tightly-scoped prototype, usually 2–4 weeks, designed to de-risk the riskiest assumption first.
- **Workshops & training** — for teams that want to build internal AI literacy rather than outsource it.
- **Fractional technical leadership** — ongoing help on AI architecture, hiring, and roadmap.

If you're a founder considering working with us, the front door is **[torchstack.ai](https://torchstack.ai)**. We provide a free 15-minute intro call to identify how we can work together.

## What's in this org

This org hosts a mix of client work (public only with the client's permission), internal tooling we've open-sourced, and reference projects we share publicly.

## For developers exploring our code

If you're poking around the repos or thinking about contributing, here's what to expect:

- **Stack.** Python (FastAPI, LangChain/LlamaIndex), TypeScript/Next.js for front-ends, Postgres + pgvector or managed vector stores for retrieval, and whichever model providers fit the job (Anthropic, OpenAI, open-weights via Together/Modal/Bedrock).
- **House style.** Small, well-typed modules. Tests on the hot paths. Evals over vibes for anything model-driven. Deployable from day one — we don't ship "we'll productionize it later."
- **Repo conventions.** Each repo has its own `README.md` with setup steps, an `evals/` directory for any prompt or model work, and an `adr/` directory for decisions we don't want to relitigate later.
- **Issues and PRs.** Issues are welcome on public repos. For non-trivial PRs, please open an issue first so we can talk through the approach — much easier than rewriting after the fact.

## Working with Torchstack

- **Clients** → start at **[torchstack.ai](https://torchstack.ai)**. Book the free 15-minute intro and we'll figure out together whether the Assessment is the right next step.
- **Engineers** interested in contract work on client engagements or contributing to public projects → email **`<scott@torchstack.ai>`** with a couple of links to representative work.
- **Everyone else** → reach Scott directly on **[LinkedIn](https://www.linkedin.com/in/scottcampit/)**.
