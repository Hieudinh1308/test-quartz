---
title: AI Agents
tags:
  - ai
  - agents
---

# AI Agents

An AI Agent is a software system that can:

1. Observe its environment
2. Reason about a task
3. Take actions
4. Learn from results

## Architecture

```text
User
  ↓
Planner
  ↓
Executor
  ↓
Tools
  ↓
Result
```

## Agent Components

### LLM

Responsible for reasoning and decision making.

### Memory

Stores:

- Conversation history
- User preferences
- Long-term knowledge

### Tools

Examples:

- Search Engine
- Database
- Python Runtime
- GitHub API

## Related Notes

- [[rag]]
- [[../linux/docker]]

## Example

A GitHub Research Agent can:

- Clone repositories
- Read files
- Summarize code
- Generate documentation