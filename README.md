# Human in the Loop with LangGraph

Demonstrates how to add human intervention points in a LangGraph workflow using interrupts and checkpointing.

## What You'll Learn

- **Interrupt** — Pause agent execution to get human input
- **MemorySaver** — Checkpoint state so the agent can resume after interruption
- **Human Assistance Tool** — A custom tool that requests help from a human

## Key Concepts

- Using `interrupt()` to pause agent execution
- Compiling graphs with a `checkpointer` for state persistence
- Resuming graph execution after human input via `Command`

## Setup

```bash
pip install -r requirements.txt
cp .env.example .env   # Add your API keys
python humanintheloop.py
```
