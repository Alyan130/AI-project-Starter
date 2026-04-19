# AI Agent Coding Workspace Template

A production-ready, multi-agent development setup that works seamlessly with **Claude Code**, **OpenAI Codex**, and **Google Antigravity**. 

This template ensures consistent context, safe feature development on isolated branches, automated testing via **TestSprite MCP**, and zero context loss when switching between agents.

## ✨ Features

- **Universal context** across Claude Code, Codex, and Antigravity
- **Safe branching workflow**: Every feature lives on its own isolated branch
- **Explicit commands** for creating features and testing
- **TestSprite MCP** integration for intelligent, autonomous testing before pushing
- **Persistent memory** and handoff between agents
- **Agent Skills** compatible (`.agents/skills/` standard)
- Works with any tech stack (Next.js, FastAPI, LangGraph, Docker, etc.)

## 📁 Project Structure

```bash
your-project/
├── AGENTS.md                    # Universal rules + coding standards (read by ALL agents)
├── CLAUDE.md
├── .agents/
│   └── workflows/               # Explicit workflows (Antigravity + Codex)
│       ├── create-feature.md
│       └── test-feature.md
├── .claude/
│   └── commands/                # Explicit slash commands (Claude Code)
│       ├── create-feature.md
│       └── test-feature.md
├── tests/
│   ├── test-plans/              # Markdown test recommendations & strategies
│   ├── unit/
│   ├── integration/
│   └── e2e/
├── frontend/                    # (your frontend code)
├── backend/                     # (your backend code)
├── docker/
├── .gitignore
└── README.md
