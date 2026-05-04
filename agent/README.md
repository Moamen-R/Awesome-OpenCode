# OpenCode Agents

This directory contains OpenCode markdown-based agents converted from Claude's subagent specifications.

## Overview

All 20 specialized agents have been successfully converted from Claude format to OpenCode format. These agents provide targeted expertise for specific development tasks.

## Agent Directory

### Analysis & Review
- **accessibility-tester** - Comprehensive accessibility testing and WCAG compliance verification
- **architect-reviewer** - System design evaluation and architectural pattern assessment
- **code-reviewer** - Code review focused on best practices and potential issues
- **security-auditor** - Security audits, compliance assessments, and risk evaluations

### Development Specialists
- **api-designer** - API design, specifications, and architecture
- **backend-developer** - Server-side APIs, microservices, and backend systems
- **cli-developer** - Command-line tools and terminal applications
- **frontend-developer** - Frontend applications across React, Vue, and Angular
- **fullstack-developer** - Complete feature development across all layers
- **mcp-developer** - Model Context Protocol servers and clients

### DevOps & Infrastructure
- **build-engineer** - Build performance optimization and compilation
- **microservices-architect** - Distributed systems and microservices architecture
- **performance-engineer** - Performance bottleneck identification and optimization

### Security & Testing
- **ad-security-reviewer** - Active Directory security auditing
- **penetration-tester** - Authorized security testing and vulnerability validation
- **powershell-security-hardening** - PowerShell security and compliance
- **qa-expert** - Quality assurance strategy and testing planning
- **ui-ux-tester** - UI/UX functionality testing and defect reporting

### Creative & Design
- **debugger** - Bug diagnosis and root cause analysis
- **ui-designer** - Visual interfaces and design systems
- **websocket-engineer** - Real-time bidirectional communication

## Format

Each agent is defined in markdown format with the following structure:

```yaml
---
description: Description of what the agent does and when to use it
mode: subagent
---

Agent instructions and capabilities...
```

## Configuration

Agents in this directory are automatically available in OpenCode. To use them:

1. **Manual invocation**: Use `@agent-name` in your message
2. **Automatic invocation**: Primary agents can invoke these subagents for specialized tasks
3. **Cycling**: Tab through agents to select different primary agents

## Source

These agents were converted from GitHub Copilot CLI subagent specifications to OpenCode markdown format on 2026-05-04.

## Documentation

For more information about OpenCode agents, visit:
https://opencode.ai/docs/agents/

## Location

- **Global agents**: `~/.config/opencode/agents/`
- **Project-specific agents**: `.opencode/agents/` (at project root)

These agents are placed in the global location and will be available across all OpenCode projects on this system.
