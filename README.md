# Claude Skills

A collection of custom [Claude Code](https://docs.claude.com) skills for agentic workflows, research automation and development.

Each skill is its own repository — clone this repo with `--recursive` to get everything, or grab individual skills.

## Skills

| Skill | Description | Built on | Status |
|-------|-------------|----------|--------|
| [omc-agency](https://github.com/amitvijapur/omc-agency) | Orchestrate 150+ specialist agents with OMC patterns (ralplan, autopilot, team) | [Oh My Claude Code](https://github.com/Yeachan-Heo/oh-my-claudecode) + [Agency Agents](https://github.com/msitarzewski/agency-agents) | Active |
| [skill-auditor](https://github.com/amitvijapur/skill-auditor) | Audit candidate skills for redundancy, routing conflicts and trigger collisions before installing | — | Active |

## Quick start

### Clone everything

```bash
git clone --recursive https://github.com/amitvijapur/claude-skills.git
```

### Clone a single skill

```bash
git clone https://github.com/amitvijapur/omc-agency.git
git clone https://github.com/amitvijapur/skill-auditor.git
```

### Install a skill

Copy the skill's `SKILL.md` (and any supporting files) to your Claude Code skills directory:

```bash
# Example: install skill-auditor
mkdir -p ~/.claude/skills/skill-auditor
cp -r skill-auditor/SKILL.md skill-auditor/scripts/ ~/.claude/skills/skill-auditor/
```

## Upcoming skills

- **Dexter** — autonomous financial research agent (Dexter-inspired methodology)
- **STORM Researcher** — multi-source long-form writing with citations
- **SWE Debugger** — autonomous bug reproduction and fixing
- **Security Auditor** — OWASP-mapped codebase security review
- More coming...

## About

Built by [Amit](https://github.com/amitvijapur) — CS student at Durham University, building agentic AI tooling and financial research systems.

## Licence

Each skill has its own licence. See the individual repositories.
