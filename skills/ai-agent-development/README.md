# AI Agent Development

Build autonomous agents, multi-agent systems, and orchestrated agent workflows with practical implementation phases.

## What this skill does

The `ai-agent-development` skill helps you:
- Design agent architecture
- Implement single-agent workflows
- Build multi-agent systems
- Add orchestration, tools, and memory
- Evaluate agent quality before release

It is ideal when you need structured, end-to-end execution for AI agent projects.

## When to use

Use this skill when you are:
- Creating a new AI agent
- Moving from single-agent to multi-agent design
- Adding tool calling and memory to agents
- Improving reliability and evaluation for existing agents

## How to invoke

Use one of the following prompts:
- `Use @ai-agent-development to design and implement this AI agent`
- `Use @ai-agent-development to build a multi-agent version`
- `Use @ai-agent-development to add tool integration and memory`

## Skill workflow (high level)

1. Agent design
2. Single-agent implementation
3. Multi-agent coordination
4. Orchestration and state management
5. Tool integration
6. Memory architecture
7. Evaluation and iteration

See [`SKILL.md`](./SKILL.md) for the full phase-by-phase workflow.

## Setup skills in AI agents

### 1) Copy or symlink the skill folder

From your local clone of this repository:

```bash
cd <path-to-skills-repo>
```

For Claude-style agents:

```bash
mkdir -p ~/.claude/skills
ln -sfn "$(pwd)/ai-agent-development" ~/.claude/skills/ai-agent-development
```

For Copilot-style local skills:

```bash
mkdir -p ~/.copilot/skills
ln -sfn "$(pwd)/ai-agent-development" ~/.copilot/skills/ai-agent-development
```

### 2) Verify files

Ensure the skill directory contains at least:
- `SKILL.md`
- `README.md`

### 3) Use in your agent session

Invoke with:

```text
Use @ai-agent-development for this task
```

### Optional: project-scoped setup

If your agent runtime supports project-level skill discovery, keep this folder in your project and point your skill search path to it.

## Related skills

- `ai-agents-architect`
- `multi-agent-patterns`
- `agent-memory-systems`
- `agent-evaluation`
