# Jonathan Simone

Independent AI Systems Research. Founder, Simone Systems Research.

> I study how autonomous AI systems coordinate, verify results, preserve human authority, and convert compute into independently verified progress.

| Project | Research question | Status |
|---|---|---|
| [PTCG Lab](https://github.com/thisisntjon/poketcg-research) | Can a fleet of AI agents make a policy measurably stronger, and can its own evidence be trusted while it tries? | PUBLIC · AUTHOR-RUN · NEGATIVE RESULT on strength |
| [SEED](https://github.com/thisisntjon/seed-protocol) | How do we distinguish agent activity from verified progress? | HYPOTHESIS (C-004) · INSTRUMENT VALIDATED · AUTHOR-RUN case study |
| [The Council](https://github.com/thisisntjon/thecouncil) | Can heterogeneous models independently verify one another's claims better than peer review alone? | PUBLIC working system |
| [BigBoss](https://github.com/thisisntjon/bigboss-approval-plane) | How should humans retain authority over autonomous coding agents? | WORKING MVP |
| [The Bus](https://github.com/thisisntjon/thebus) | What happens when the original architecture fails prior-art review? | NEGATIVE RESULT · RETIRED |
| [Godot AI Methodology](https://github.com/thisisntjon/godot-ai-methodology) | What software architecture makes AI-assisted development safer and more verifiable? | PUBLIC methodology |

**Measured so far.** Seven weeks of multi-vendor agent research on the Kaggle Pokémon TCG AI Battle benchmark produced one scoped positive: a combined card-and-rule intervention gained **+7.82 points [+6.08, +9.56]** on a development panel. An **8,400-game** panel across seven fresh opponent implementations then located that gain in **two of the seven** cells (+20.42 and +18.75). The other five average **−0.47 points [−2.64, +1.71]**. The scope is the finding. [Report](https://github.com/thisisntjon/poketcg-research/blob/main/docs/STRATEGY-WRITEUP.md)

Separately, an author-run census of **1,979** PR-linked commits in a single-operator agent fleet found **43.2%** docs-only and **2 of 80** sampled PRs changing the playing agent. Composition and identity, not a causal claim. [Research note](https://simoneresearch.com/blog/throughput-is-not-progress/) · [dataset](https://github.com/thisisntjon/seed-protocol/tree/main/workflow/research/2026-08-24-pr-case-study/artifacts)

**Not claimed.** The fielded competition agent is a public Apache-2.0 community kernel used with no modifications. I did not write it and I do not claim it; it is credited in [NOTICE](https://github.com/thisisntjon/poketcg-research/blob/main/NOTICE). A policy trained on my own data improved held-out imitation loss and then won **23 of 1,200** decided games against that kernel. It was never fielded.

**Retained failures.** The Bus was retired after a prior-art sweep invalidated 17 of its assumptions; the retraction ledger is public. Both [seed-protocol](https://github.com/thisisntjon/seed-protocol/blob/main/workflow/canon/RETRACTIONS.md) and [poketcg-research](https://github.com/thisisntjon/poketcg-research/blob/main/workflow/canon/RETRACTIONS.md) keep retraction registers of numbers that were published and are now known false, with the value to use instead.

**Verify some of it yourself.** No engine, no network, no credentials:

```bash
git clone https://github.com/thisisntjon/poketcg-research
cd poketcg-research
python -X utf8 scripts/prior_art.py "Xerosic" --limit 2
```

The expected output, its exit code, and what it does *not* establish are written down in [REPRODUCING.md](https://github.com/thisisntjon/poketcg-research/blob/main/docs/REPRODUCING.md).

Site: [simoneresearch.com](https://simoneresearch.com) · Contact: jon@simoneresearch.com
