## Hi, I'm Elvin (Ale). 👋

I build public, versioned work on **governed, auditable agentic-AI systems**.

The core idea is simple: agents are not just prompts you tune. They are systems made of artifacts you can design, version, inspect, test, and govern. Things like manifests, prompts, skills, tool specs, memory and state strategies, schemas, evals, policies, and runtime configs.

My background is in clinical data and regulated environments, where "it works in the demo" was never good enough. That shaped how I think about AI. The interesting question isn't how you talk to a model. It's what you build around it.

Can you version it?  
Can you inspect it?  
Can you govern it?

### What I'm building

**[agentic-ai-artifact-taxonomy](https://github.com/ElvinMorales/agentic-ai-artifact-taxonomy)**  
A framework-neutral taxonomy for the artifacts agentic systems are actually made of, organized by lifecycle (design-time, runtime, iteration) and mapped to protocols like MCP and A2A. Shared vocabulary over another clever demo. This is the source of truth the rest of my work points back to.

**[agentic-artifact-builder](https://github.com/ElvinMorales/agentic-artifact-builder)** ([try it live](https://elvinmorales.github.io/agentic-artifact-builder/))  
A small browser app for learning and working with the taxonomy: browse artifact types by lifecycle stage, fill in guided fields, and generate clean, public-safe starter files. No install.

**[agent-librarian](https://github.com/ElvinMorales/agent-librarian)**  
A deterministic CLI that scans an agent repo, catalogs the artifacts it finds, validates them, and flags likely overlap for human review rather than auto-deduplicating. The point is making a pile of files reviewable.

**[journal-agent](https://github.com/ElvinMorales/journal-agent)**  
A private-first journaling companion built on the taxonomy, with a local MCP server for reviewing memory and state proposals. Control-plane artifacts stay public; journal entries stay local.

**[strategic-mirror-agent](https://github.com/ElvinMorales/strategic-mirror-agent)**  
A public-safe, file-first scaffold for a personal career and workplace communication coach. It demonstrates how to separate identity, prompts, memory, state, guardrails, connector policy, schemas, evals, and private runtime boundaries.

### How I think about this

- **Governed > clever.** An AI you can't audit isn't a system. It's a liability with good manners.
- **Artifacts, not vibes.** If it matters, it should be addressable, versionable, inspectable, and governable.
- **Boundaries by design.** Decide what's public and what's private before you build, not after.

### Elsewhere

- LinkedIn: [https://www.linkedin.com/in/elvinamorales](https://www.linkedin.com/in/elvinamorales/)
