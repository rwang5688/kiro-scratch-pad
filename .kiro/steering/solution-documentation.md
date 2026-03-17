---
inclusion: auto
---

# Solution Documentation Steering

When a requester asks for a "best solution" or "feasible solutions" to a problem:

1. Document the question and proposed solutions under `.kiro/specs/yyyymmdd-<spec-name>/`, where:
   - `yyyymmdd` is the current date as a numerical value (e.g., `20260317`), ensuring directories sort chronologically by default
   - `<spec-name>` is a kebab-case best-guess title for the solution topic
2. Create a `solutions.md` file in that directory containing:
   - The original question or problem statement
   - Each proposed solution with a brief description, pros, and cons
   - A recommended solution (if applicable)
