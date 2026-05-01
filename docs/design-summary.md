Zion - Design Summary

- Purpose: A personal AI engineering toolkit. Central collection of reusable skills, prompts, agents, and other AI workflow resources. Named after The Matrix.
- Primary consumer: VS Code Copilot, but designed to be portable.
- Structure:
  - skills/<descriptive-name>/SKILL.md — flat list, descriptive folder names
  - Each skill folder has a required SKILL.md (with name + description frontmatter) and optional supporting files
  - New top-level folders (prompts, agents, etc.) added organically as content arrives
- `.github/skills` — active skills for Zion itself (eats its own cooking, copies from skills)
- No install tooling — manual copy from skills into target repo's skills
- README — brief description of Zion's purpose + a table cataloging all available skills