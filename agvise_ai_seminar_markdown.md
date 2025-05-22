# 🌾 Agvise AI Seminar Hub

**AI-Powered Productivity for Consultants: From Automating the Tedious to Unlocking the Impossible**

---

## Table of Contents

1. [Welcome & Overview](#welcome--overview)
2. [Automate the Tedious](#automate-the-tedious)
3. [Prompt Crafting (CRAFT)](#prompt-crafting-craft)
4. [Prompting Guides](#prompting-guides)
5. [Unlocking the Impossible](#unlocking-the-impossible)
6. [Secure & Sustainable AI](#secure--sustainable-ai)
7. [Personal AI Challenge](#personal-ai-challenge)
8. [Core Tensions in AI](#core-tensions-in-ai)
9. [Wrap-Up & Next Steps](#wrap-up--next-steps)

---

## Welcome & Overview

This interactive hub provides all the materials for the "AI-Powered Productivity for Consultants" seminar. Navigate through the sections to explore how AI can enhance your work, from automating routine tasks to unlocking new strategic possibilities.

### Seminar Details

- **Title:** 🌾 AI-Powered Productivity for Consultants: From Automating the Tedious to Unlocking the Impossible
- **Facilitator:** Michael Borck
- **Duration:** 2 hours
- **Format:** Instructor-led, interactive, tool-based seminar (no slides)

### 🧠 Learning Goals

- Automate common consulting tasks using AI in Word/Excel
- Write better prompts using the CRAFT framework
- Explore emerging tools like NotebookLM for internal knowledge work
- Understand AI limitations, privacy, and sustainable use

### 🔧 Participant Setup & Access Requirements

To get the most out of this session, please ensure you have:

- ✅ Microsoft 365 (Office 365) account
- ✅ Google Account (personal or work)
- ✅ A laptop or suitable computing device
- 🧠 Optional: Access to other LLM tools (e.g., ChatGPT, Claude, Gemini)

---

## ⚙️ Automate the Tedious

This section focuses on how AI can eliminate repetitive and time-consuming tasks in consulting, particularly around reporting, summarising, and rewording. We'll explore how to evolve from basic prompting to more complex, value-added interactions.

### 🎯 Purpose

Show how AI can help eliminate repetitive and time-consuming tasks that consultants perform every week — particularly around reporting, summarising, and rewording. Demonstrate the evolution from basic prompting to prompt chaining, multi-role reasoning, and value-added insight.

### 🧠 Framing

*"Let's be honest — a lot of time is spent copying, pasting, rewording, and formatting. These are things that don't require judgment — but they do require time. AI can help us take these off the plate."*

Guiding Questions for this section:
1. How can we automate what we already do?
2. What could we never do — until now?

### 🧪 Live Demo Examples (Conceptual)

We'll work with mock datasets and public article excerpts. Tools: Copilot Chat, ChatGPT, Claude, or Gemini.

#### DEMO 1: Summarise Mock Crop Data
- **Initial Prompt:** "You are a junior analyst. Summarise this farm production and financial table. Highlight which crop performed best each year and any concerning trends."
- **Follow-Up Prompt:** "Now rewrite that summary for a broadacre WA farm client in plain English."
- 📌 **Highlight:** Basic prompting → tone/format shift → value-added rewrite.

#### DEMO 2: Turn Insights into Content
- **Prompt:** "Using the summary above, create a LinkedIn post highlighting farm performance and grain yield outcomes in 2023."
- **Variation Prompt:** "Write this as a newsletter article with subheadings and 3 key takeaways."
- 📌 **Highlight:** Reusing same insight → multiple content formats.

#### DEMO 3: Reason Like a Consultant
**Prompt Chain:**
1. "Act as a junior analyst: summarise."
2. "Act as a senior consultant: critique the summary."
3. "Merge both into a final report section."
- 📌 **Highlight:** Role simulation, layered prompting, critical refinement.

#### DEMO 4: Prompt as Workflow (Agent Logic)
- **Single Orchestration Prompt:** "Read this data and a short market summary. Then: 1) summarise trends, 2) highlight 3 risks, 3) write strategy suggestions, and 4) draft a report paragraph. Label each step."
- 📌 **Highlight:** Single prompt → full workflow (agent-like behavior).

### 📊 Mock Crop Data Sample

| Year | Crop   | Yield (t/ha) | Price ($/t) | Revenue ($/ha) | Cost ($/ha) | Profit ($/ha) |
|------|--------|--------------|-------------|----------------|-------------|---------------|
| 2023 | Wheat  | 2.61         | 331.71      | 865.76         | 420         | 445.76        |
| 2023 | Barley | 2.59         | 286.99      | 743.30         | 380         | 363.30        |
| 2023 | Canola | 1.10         | 592.80      | 652.08         | 500         | 152.08        |
| 2023 | Lupins | 1.59         | 460.57      | 732.31         | 360         | 372.31        |

### 🛠 Optional Prompt Enhancers

- "Use plain English suitable for farm clients."
- "Structure as a summary with headings."
- "Limit to 100 words per section."
- "Write like a trusted Agvise consultant."

### 💬 Discussion Prompt

"Which parts of your reporting process could this help with?"
"Where might AI reduce your time-to-insight without sacrificing accuracy?"

---

## 🔨 Prompt Crafting with CRAFT

Learn how to write better prompts that yield more relevant, high-quality AI responses using the structured CRAFT framework.

### 💡 Why It Matters

- Most disappointing AI results are due to vague or context-free prompts
- Structured prompts produce better outputs with less rework
- Good prompting is platform-agnostic: it works in ChatGPT, Copilot, Gemini, Claude, etc.

*"Think of prompting like a briefing: the better you brief the AI, the better its draft. But also — the first prompt is rarely the final answer. Good prompts invite a conversation, not just a command."*

### 🧠 C.R.A.F.T Framework

| Letter | Meaning | Example |
|--------|---------|---------|
| C | **Context** | "This data is from a WA mixed farm over 5 years." |
| R | **Role** | "You are a senior ag consultant." |
| A | **Action** | "Summarise the financial trends." |
| F | **Format** | "Write in bullet points." |
| T | **Tone/Target** | "Use plain English for the farm owner." |

*"You don't have to use every element every time — but this gives you the scaffolding."*

### 🗣️ Prompting as a Conversation

"CRAFT is a great starting point — but don't stop there. One-shot prompting can feel transactional. The real power is in using AI as a collaborator."

*"Think of CRAFT as your first message to a new colleague. The next steps are to discuss, clarify, iterate."*

**Example Chain:**
1. Craft a CRAFT-style summary prompt
2. Follow up: "Add any year-on-year risks you see."
3. Follow up: "Now restructure that for a client newsletter."

---

## 📚 Prompting Guides & Examples

Explore a collection of prompt patterns, techniques, and examples to enhance your AI interactions for various consulting tasks.

### Value-Adding Prompts

- **Summary Use Case:** "Summarise the key insights from this annual farm business review. Use plain English. Focus on production, financials, and risk outcomes."
- **Marketing Use Case:** "Turn this report into a newsletter article for farm business owners. Highlight strong grain yields, cashflow recovery, and return on capital. Use a professional and optimistic tone."
- **Thought Leadership (LinkedIn):** "Write a short LinkedIn post summarising this 2023 farm report. Focus on ROI, yield, and forward planning. Make it professional and client-facing."
- **Strategy Use Case (Lessons Learned):** "From this report, extract 3 lessons other farms could learn from this client's performance and decision-making in 2023."

### Prompt Chaining Techniques

- **Guided Workflow (Full Chain):** "You are an AI assistant... Follow these steps: 1. Summarise data. 2. Analyse market outlook. 3. Generate strategic recommendations. 4. Combine into a report..."
- **Modular Prompt Chain (Explicit Steps):** "You are a multi-step reasoning assistant... Step 1: Summarise table. Step 2: Analyse market excerpt..."
- **Interactive Chain (Pause Between Steps):** "You are an AI assistant performing a four-step workflow. Complete step 1, then wait for me to type CONTINUE..."

### Advanced AI Prompting Tips

- **AI Debate Technique:** Have two AIs critique each other's solutions
- **Different AIs for Different Roles:** Assign specialized roles (Farm Architect AI, Crop Implementation AI)
- **Chain-of-Thought Programming:** Guide AI step-by-step through complex problems
- **Reverse Engineering:** Ask AI to explain existing practices/technologies
- **Progressive Disclosure:** Start minimal, gradually add context
- **Persona-Based Prompting:** "As an agronomist...", "As an economist..."

### Prompt Playbook Highlights

- **One-Shot Starters:** "Summarise this table.", "Rewrite for a client."
- **Multi-Turn Chains:** "1. Summarise. 2. Risks? 3. Report section."
- **CRAFT-Based:** "This data is from... You are a... Summarise trends... Output in bullets..."
- **Reflection Prompts:** "What's one part of your job AI could help with?"

---

## 🌟 Unlocking the Impossible

This section helps us see beyond automation to how AI can expand our capabilities, enabling tasks previously too complex, time-consuming, or costly.

### 💡 Framing Statement

*"So far, we've looked at how to automate what you already do. Now let's ask a better question: — What have you never been able to do because it felt too hard, too slow, or too expensive? AI may now make those things possible."*

### 🧠 Examples of "Impossible" Tasks AI Can Now Tackle

| Task Type | Previously Hard/Impossible | Now Possible With AI |
|-----------|---------------------------|---------------------|
| Market synthesis | Reading & comparing 5+ articles fast | Summarise and extract insights instantly |
| Report repurposing | Turning 1 report into 3 formats | Reformat for client, email, or blog post |
| Internal Q&A | Answering SOP/policy questions on demand | Summarise docs into NotebookLM |

### 🤖 NotebookLM: AI That Knows Your Documents

NotebookLM is Google's AI notebook that reads and cites *your* content. Upload SOPs, reports, policies, and query them. It's great for internal insights, onboarding, and strategy documents.

**Use Cases for Agvise:**
- Ask: "How do we usually advise on lease arrangements?"
- Summarise changes in advice over 3 years
- New staff can ask questions without bugging seniors

**Limitations:** Not suitable for client-sensitive content (yet). Still in beta — best used for internal knowledge reuse.

---

## 🔒 Secure & Sustainable AI Use

Grounding our AI exploration in responsible use is crucial. This section covers how to use AI confidently without risking sensitive data, and how to think long-term about secure, governed AI integration.

### 📄 Framing Statement

*"Even if the AI gets the right answer, if you use the wrong data or tool, it can create serious risk. Let's talk about what's safe, what's smart, and what's sustainable in your setting."*

### 🔍 Key Principles

1. Use mock or public data in all experiments (especially with public tools)
2. Assume anything entered into a public AI chat is public
3. Use your secure platforms (like M365 Copilot) for sensitive work
4. Prototype in chat tools, deploy in secure environments
5. Governance is a team sport: involve IT/security

### 🤖 AI Tools: What's Under the Hood?

- **Copilot / ChatGPT:** LLMs trained to predict useful text. Copilot is integrated into M365; ChatGPT is public-facing unless restricted.
- **Prompt Engineering:** Structuring your input (Context, Role, Action, Format, Task - CRAFT) to guide AI output.
- **Agents:** Tools that reason and act in steps (e.g., AutoGPT). Conceptually similar to complex prompt chains.
- **Key Concepts:** Context Window (AI's short-term memory), Temperature (creativity/randomness), AI predicts, not "thinks".
- **Security & Risk:** Copilot data stays in your M365 tenant. Avoid client-sensitive data in public ChatGPT. Always verify AI output.
- **MCPs (Most Capable Prompt):** Prompts that instruct AI to simulate an expert role (e.g., "You are a senior farm consultant...").

---

## 🧩 Personal AI Challenge

Apply what you've learned to a personal, meaningful task. This is a space for experimentation, reflection, and building confidence in your AI prompting skills.

### 📝 Worksheet Prompts

1. What's the task or challenge you're exploring? (e.g., Summarising farm reports into client-ready text)
2. What do you currently do?
3. Draft your CRAFT prompt for this task.
4. Which tool would you try? (☐ Copilot ☐ ChatGPT ☐ Claude ☐ NotebookLM ☐ Not sure)
5. What would success look like for this task?
6. **Reflection:** Surprised by the output? Would you use it again? Where might it fit in your workflow?

---

## ⚖️ Core Tensions in AI-Assisted Work

AI is powerful, but it introduces trade-offs. This section highlights key tensions to consider for balancing ambition with caution.

### 🧠 Thinking vs. Replacing

**Tension:** "AI thinks for me" vs. "AI replaces my work"
**What to Remember:** Use AI to support reasoning, not bypass it. It's a partner, not a substitute.

### 🎯 Prompting vs. Collaborating

**Tension:** One-shot prompting vs. Over-engineering prompts
**What to Remember:** Most good outcomes need back-and-forth. CRAFT is a start, not the finish.

### 🏁 Wrap-Up Thought

*"AI doesn't eliminate trade-offs — it just reshapes them. The best practitioners navigate these tensions with clarity, not certainty. You don't need to solve everything — you just need to notice where the friction lives."*

---

## 🎁 Wrap-Up & Next Steps

Concluding the seminar with clarity, confidence, and practical next steps to integrate AI into your workflows.

### 🚀 Next Steps

*"You don't need permission to start — you just need a use case. Start small, stay safe, and build from there."*

- Prototype one idea next week (AI summary, blog, table analysis)
- Share one working prompt with a colleague
- Bring ideas to your next team or strategy session

### 🚀 Follow-Up Options

If the team would benefit from continued support, consider:

- **Prompt to Process Workshop:** Turn prompt chains into automated workflows (n8n, Power Automate, Zapier)
- **Copilot Integration Working Session:** Map current Word/Excel workflows to Copilot
- **AI Adoption Brief or Playbook:** Custom internal resource with prompts, Copilot guidance, and security best practices

### 🏁 Final Takeaway

*"You don't have to master AI today. But if you can start thinking with it — shaping questions, exploring answers, refining together — you've already unlocked the most powerful part of the tool."*

---

**Facilitator:** Michael Borck  
**Duration:** 2 hours  
**Format:** Interactive, tool-based seminar