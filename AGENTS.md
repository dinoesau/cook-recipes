# Agent Notes

- Repo is a personal Spanish-language recipe collection in Markdown. No build, test, lint, package manager, CI, or generated code.
- Recipe layout: `recipes/<category>/<dish>/README.md`. Each category has its own index at `recipes/<category>/README.md`.
- If asked about culinary science, technique, substitutions, or recipe generation, **invoke the repo-local `chef` skill** (`.agents/skills/chef/SKILL.md`). It overrides default culinary advice: it requires web searches from reputable sources, a physics-first framework, and a fixed response format.
