# INDIA SIMULATOR — AGENT RULES

## Roles
- Creative Director: owns narrative, world rules, characters, mission intent, and game design.
- Engineering agents: implement assigned technical systems.
- QA agent: validates builds, tests, regressions, and acceptance criteria.
- Integration agent: coordinates branches, interfaces, and merge readiness.

## Agent contract
Each agent must:
1. Read the relevant Bible before implementation.
2. Inspect existing code before changing it.
3. Modify only its assigned scope unless an interface change is required.
4. Reuse existing systems where possible.
5. Keep changes small and reviewable.
6. Test after implementation.
7. Report failures honestly.

## Token-efficiency rule
Use the computer for deterministic work: search, indexing, compiling, testing, formatting, dependency analysis, hashing, and Git operations. Use the LLM for decisions, ambiguity, architecture, and code generation.
