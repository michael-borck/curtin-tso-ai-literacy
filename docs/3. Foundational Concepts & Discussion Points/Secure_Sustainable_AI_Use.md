## 🔒 1:15–1:30 — Secure & Sustainable AI Use

### 🌟 Purpose

Ground the seminar in responsible use. Provide participants with confidence about what they *can* do now without risking sensitive data, and how to think long-term about integrating AI in secure, governed ways.

---

### 📄 Framing Statement

> “Even if the AI gets the right answer, if you use the wrong data or tool, it can create serious risk. Let’s talk about what’s safe, what’s smart, and what’s sustainable in your setting.”

---

## 🔍 Key Principles

1. **Use mock or public data in all experiments**
   Especially in exploratory or non-integrated tools (e.g., ChatGPT, Claude).

2. **Assume anything entered into a public AI chat is public**
   Unless you *know* the tool offers enterprise privacy, don’t paste sensitive or client-identifiable info.

3. **Use your secure platforms for sensitive work**
   Copilot inside Microsoft 365 is enterprise-grade: your data stays in your tenant and isn’t used to train models.

4. **Prototype in chat tools, deploy in secure environments**
   Prompt in ChatGPT, migrate your workflow to Copilot, Zapier, or n8n later.

5. **Governance is a team sport**
   Involve your IT/security leads when formalising AI use. Keep logs, version prompts, and review how tools access data.

---

# 🤖 AI Tools: What’s Under the Hood?

## 1. What is Copilot / ChatGPT?
- LLMs trained to predict useful text.
- Copilot runs inside M365 tools.
- ChatGPT is public-facing unless restricted.

## 2. What is Prompt Engineering?
- Structure your input to guide output.
- CRAFT = Context, Role, Action, Format, Task.

## 3. What Are Agents?
- Tools that reason + act using steps (e.g. AutoGPT).
- Not used directly in Copilot, but conceptually similar.

## 4. Key Concepts
- Context Window: How much AI can consider at once.
- Temperature: Randomness/creativity setting.
- Not “thinking” — just predicting.

## 5. Security & Risk
- Copilot: Internal to your M365 tenant.
- ChatGPT: Avoid client-sensitive data unless secured.
- Always verify AI output.

## 6. What are MCPs?
- “Model Context Protocol”
- An open protocol that lets AI assistants securely connect to external data sources and tools.




---

## 🚧 Platform Governance Comparison

| Tool             | Use Case                     | Governance Notes                                                    |
| ---------------- | ---------------------------- | ------------------------------------------------------------------- |
| **ChatGPT**      | Rapid prototyping, summaries | ❌ No client data. Treat like a public whiteboard.                   |
| **Copilot Chat** | Secure drafting in M365      | ✅ Safe for internal docs. Respects your permissions.                |
| **Gemini**       | Research, document analysis  | ⚠️ Check what is shared via APIs. Not built for confidential input. |
| **Claude**       | Long context reasoning       | ❌ Same privacy limits as ChatGPT. Use mock data only.               |

---

## 🚀 Strategy Summary: Prompt, Process, Protect

> 1. **Prompt It** — Use AI chat to test your thinking, summarise ideas, and shape workflows.
> 2. **Process It** — Move successful chains into tools like Copilot, n8n, or Zapier.
> 3. **Protect It** — When it’s sensitive or client-facing, work within secure systems.

---

## 🚶 What to Say if Asked: “Can we use this for real clients?”

> “Yes, but only in tools governed by your enterprise environment — like Copilot in Microsoft 365. You can prototype freely in public AI, but don’t use client data outside secure systems.”

---

## 🏛 Key Takeaway

> “AI is only as smart as your context — and only as safe as your systems. Work with it like a colleague: trust it, but verify, and never put it in a position to break the rules.”

