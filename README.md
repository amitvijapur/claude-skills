# Claude Skills

A collection of custom [Claude Code](https://docs.claude.com) skills for agentic workflows, research automation and development.

Each skill is its own repository — clone this repo with `--recursive` to get everything, or grab individual skills.

## Skills

| Skill | Description | Status |
|-------|-------------|--------|
| [omc-agency](https://github.com/amitvijaput/omc-agency) | Orchestrate 150+ specialist agents with OMC patterns (ralplan, autopilot, team) | Active |

## Quick start

### Clone everything

```bash
git clone --recursive https://github.com/amitvijaput/claude-skills.git
```

### Clone a single skill

```bash
git clone https://github.com/amitvijaput/omc-agency.git
```

### Install a skill

Copy the skill's `SKILL.md` (and any supporting files) to your Claude Code skills directory:

```bash
mkdir -p ~/.claude/skills/omc-agency
cp omc-agency/SKILL.md ~/.claude/skills/omc-agency/
```

## Upcoming skills

- **Dexter** — autonomous financial research agent (Dexter-inspired methodology)
- **STORM Researcher** — multi-source long-form writing with citations
- **SWE Debugger** — autonomous bug reproduction and fixing
- **Security Auditor** — OWASP-mapped codebase security review
- More coming...

## About

Built by [Amit](https://github.com/amitvijaput) — CS student at Durham University, building agentic AI tooling and financial research systems.

## Licence

Each skill has its own licence. See the individual repositories.
