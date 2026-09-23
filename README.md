# Jeremy Capps

> I build the layer where domain knowledge becomes an environment an agent can actually work in.

Between the expert who *knows* a workflow and the agent that has to *perform* it, there's a missing layer: the faithful world the agent reaches into — the documents, the notes, the state a real accountant or lawyer would pull from to solve a problem. I build that layer, and the harnesses that prove it's faithful.

I don't drop the business to be an engineer, or drop the engineering to manage data. The real work is the seam between them — and I've been building its tooling since before it had a title.

Operator and engineer — nine years across operations, product, design, and engineering.

## What I build

- **The environment** — mounts a domain's operational context as structured state an agent navigates and acts inside. ([domain-environment ↗](https://github.com/jeremycapps/domain-environment))
- **The judge** — declares what a correct execution looks like and grades the actual against it, by decision not keystroke. ([domain-verifier ↗](https://github.com/jeremycapps/domain-verifier))

The through-line: record what happened, declare what should be true, and treat the diff between them as the work.

## How I work

Observe the real trajectories, separate the deterministic sub-decision from the judgment one, promote only the safe part to tooling, and leave the check running. Same loop at every scale.

Most recent, smallest scale: I mined 140 of my own agent sessions, found one wasteful pattern — unscoped recursive search — and routed it. ~250× faster, ~10× less context, zero model change, gated behind a 19-case test suite. The interesting part wasn't the speed; it was that 99.6% of the win was scope and consolidation, not a faster tool. Demonstrated in a narrow routing experiment: grep → git grep.

## Currently

Strategic Projects Lead at Aroko. Writing and case studies at [jeremycapps.com](https://jeremycapps.com).
