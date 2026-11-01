# reVista

An experimental, public and collaborative hobby restoration project targeting **Windows Vista itself**, not a modern Windows system with a Vista-style skin.

## Project charter

Explore how selected Vista-era capabilities can be understood, restored and extended through behavior research, reverse engineering and independently implemented compatible components. The approach is analogous to rebuilding parts for a historic machine: preserve the character and target behavior while fabricating replacement components where feasible.

This repository begins as a research and planning workspace. It does not yet contain an implementation or establish technical feasibility.

## Join the research

Contributors are welcome to share public technical references, reproducible observations, compatibility test ideas and narrowly scoped proposals through issues. Read [CONTRIBUTING.md](CONTRIBUTING.md) first. Repository visibility is public; project licensing remains undecided, so public availability must not be treated as an open-source license grant.

## Working approach

1. **Research before rebuilding.** Search extensively for existing public documentation, projects, compatibility work, tools and technical findings. Record source URLs, versions, licenses, provenance and limitations; assess reuse rather than assuming everything must be rebuilt.
2. **Understand behavior.** Where authorized and legally appropriate, use observation, disassembly/decompilation and controlled experiments to develop explicit behavioral specifications. Do not treat reconstructed output as automatically reusable or distributable source.
3. **Implement independently.** Develop narrowly scoped compatible replacement components against documented interfaces and reproducible tests. Do not import leaked Microsoft source, proprietary binaries or credentials into this repository.
4. **Verify incrementally.** Select one bounded component, establish a Vista baseline and compatibility tests, then measure correctness, regressions and integration limitations before expanding scope.
5. **Use a supervisor/worker model.** A high-capability cloud model leads architecture, decomposition and milestone reviews; local models perform most bounded research processing, implementation and test iterations. Keep supervisor involvement concentrated at explicit checkpoints, with traceable evidence and escalation rules.

## Initial research gates

- Define the target Vista edition, architecture and service-pack baseline, plus the first component and acceptance criteria.
- Build an annotated resource inventory, including licensing and provenance review for each proposed reuse.
- Decide the permitted analysis inputs, isolation strategy and test environment.
- Resolve applicable reverse-engineering, compatibility and distribution questions before distributing derived material or replacement components.
- Define model roles, task budgets, review checkpoints and evidence requirements before starting worker execution.

## Boundaries and unresolved decisions

- No Microsoft source code is available to this project; access to or permission to modify Microsoft's proprietary implementation must not be assumed.
- This charter is not a claim of clean-room provenance, legal compliance, security suitability or compatibility achieved.
- Project licensing is **not yet selected**. Third-party material retains its own terms; inclusion is not authorization to reuse it.
- No production deployment, operating-system replacement, worker installation or autonomous execution is initiated by creating this repository.
- Windows and Windows Vista are Microsoft trademarks. This is an independent project, not an official Microsoft effort.
