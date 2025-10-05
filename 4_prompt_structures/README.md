# 🔧 Prompt Structures – High-Converting, Reusable Patterns

> Proven prompt blueprints for agents, content, and portfolio growth. Copy, adapt, ship.

## 📋 Overview
This folder collects modular prompt structures optimized for:
- 🧠 Agent system prompts (roles, tools, memory)
- 📝 Social posts (LinkedIn/Twitter) that drive engagement
- 🧩 Project showcases and portfolio blurbs
- 🎯 Calls-to-action that convert viewers to users/contributors

Each prompt includes variables, usage notes, and examples.

---

## 🧱 Prompt Anatomy (Use This Checklist)

A good prompt generally includes:
- Role and objective
- Inputs and constraints
- Tools and functions available
- Output format with examples
- Quality criteria and refusal policy
- Memory/reference context

Use this consistently to reduce ambiguity and improve outcomes.

---

## 📚 Contents

- linkedin_post_prompt.md – Technical/viral post scaffold  
- portfolio_pitch_prompt.md – Short, high-signal repo blurb  
- project_showcase_prompt.md – Demo narrative + CTA  
- More coming soon (PRs welcome!)

---

## ⚙️ Usage Tips

- Parameterize with {{variables}} and keep defaults documented
- Provide 1–2 high-quality examples (few-shot beats zero-shot)
- Add explicit output schemas (JSON, Markdown sections)
- For agents, list tools and function signatures clearly
- Set guardrails: what to avoid, how to refuse, quality bar

---

## 🔌 Integration Patterns (Agents)

Example system prompt snippet:

```
You are {{agent_name}}, a {{role}}.
Objective: {{objective}}

Tools available:
- search(query: string) -> list[Result]
- fetch(url: string) -> str

Memory:
- vector_store: semantic recall for prior topics

Rules:
- Cite sources with links
- Think step-by-step, but output only final answer
- If missing data, ask one clarifying question

Output format (Markdown):
- Summary
- Steps taken
- Sources
```

---

## 🧪 Testing & Evaluation

- Create a small eval set (5–10 representative tasks)
- Track win rate against a baseline prompt
- Log token usage and latency; optimize for cost/performance
- Keep a changelog of prompt tweaks with outcomes

---

## 🔗 Related
- Tutorials: ../1_tutorials/
- Templates: ../2_templates/
- Examples: ../5_examples/

---

Last updated: October 2025 • Have a great prompt? Open a PR.
