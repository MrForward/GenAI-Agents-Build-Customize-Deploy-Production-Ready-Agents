# 🧪 Examples – Real-World Agent Samples

> Runnable, minimal examples that demonstrate core agent capabilities end-to-end.

## 📋 Overview
This folder contains small, focused examples you can run locally in minutes. Each example shows a complete loop: prompt → planning/tools → memory → output, with logging and guardrails.

✅ Minimal dependencies  
✅ Clear config via .env  
✅ Copy/paste friendly  
✅ Comments explaining key lines

---

## 🚀 Quick Start

```bash
# From repository root
pip install -r requirements.txt
cp .env.example .env
# Fill in API keys in .env

# Run an example
python 5_examples/openai_agent_demo.py
```

---

## 📂 Included Examples

1) openai_agent_demo.py  
- Shows: basic LLM agent with tool-calling + short-term memory  
- Highlights: function schema, error handling, simple planner  
- Extend: add a search tool, add vector memory

2) crewai_agent_demo.py  
- Shows: multi-role CrewAI orchestration with shared context  
- Highlights: roles, tasks, tools, handoffs  
- Extend: add evaluator/critic loop

---

## 🧠 What to Look For

- How prompts are structured (system + few-shot + task)  
- How tools are registered and invoked  
- How failures are retried or gracefully handled  
- How outputs are validated (schemas)  
- How logs help you debug

---

## 🔧 Customize

- Swap LLM provider in a single config place  
- Add a tool by implementing a function and registering it  
- Add memory by enabling Redis/Vector DB and storing summaries  
- Wrap examples behind a tiny CLI for reproducibility

---

## 🧭 Next Steps

- Move to Templates: ../2_templates/ for production-ready setups  
- Learn Concepts: ../1_tutorials/ to deepen fundamentals  
- Explore Ideas: ../3_agent_ideas/ for validated product directions

---

Last updated: October 2025 • Have a great example? PRs welcome.
