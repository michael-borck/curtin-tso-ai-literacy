# 🎓 TSO AI Literacy and Capability Program

**Transforming Teaching Support Operations at Curtin University**

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

This interactive hub provides all the materials for the "AI Literacy and Capability Program" for Teaching Support Officers at Curtin University. Navigate through the sections to explore how AI can transform teaching support operations, from automating compliance documentation to providing strategic insights.

### Program Details

- **Title:** 🎓 AI Literacy and Capability for Teaching Support: Transforming Operations at Curtin
- **Facilitator:** Michael Borck
- **Duration:** 2 hours
- **Format:** Instructor-led, interactive, tool-based workshop (no slides)

### 🧠 Learning Goals

- Automate and streamline internal teaching support operations like business case writing, impact analysis, and data collection
- Write effective prompts using the CRAFT framework to generate compliance-focused documentation and analyse student data
- Explore how AI tools can provide proactive insights for support planning and optimisation
- Understand AI limitations, privacy, and secure implementation within university policies

### 🔧 Participant Setup & Access Requirements

To get the most out of this session, please ensure you have:

- ✅ Microsoft 365 (Office 365) account with Copilot access
- ✅ A laptop or suitable computing device
- 📝 Note: Microsoft Copilot is our primary AI tool for university work
- 🧠 For personal exploration only: ChatGPT, Claude, or other AI tools (not for university data)

**Important:** Only Microsoft Copilot is approved for use with university data. Other AI tools mentioned in this workshop are for personal learning and experimentation with mock data only.

---

## ⚙️ Automate the Tedious

This section focuses on how AI can eliminate repetitive and time-consuming tasks in teaching support operations, particularly around compliance documentation, impact analysis, and data consolidation. We'll explore how to evolve from basic prompting to complex, strategic workflows.

### 🎯 Purpose

Show how AI can help eliminate repetitive and time-consuming tasks that Teaching Support Officers perform daily — particularly around business case writing, compliance checking, and data analysis. Demonstrate the evolution from basic prompting to automated workflows that save hours of manual work.

### 🧠 Framing

*"Let's be honest — a lot of time is spent on repetitive compliance checks, reformatting documentation, and manual data collection. These tasks consume hours that could be spent on strategic support planning. AI can automate these processes."*

Guiding Questions for this section:
1. How can we automate what we already do?
2. What could we never do — until now?

### 🧪 Live Demo Examples with Microsoft Copilot

We'll work with mock university data and policy excerpts using Microsoft Copilot in Excel and Word.

#### DEMO 1: Excel Formula Assistance with Copilot
- **Scenario:** You have a complex spreadsheet with broken formulas for calculating student load and resource allocation.
- **Initial Prompt:** Copy the broken formula and ask Copilot: "What's wrong with this formula and how can I fix it?"
- **Follow-Up Prompt:** "Generate a formula that calculates the weighted average of student satisfaction scores across multiple units, excluding any blank cells."
- 📌 **Highlight:** This saves hours of debugging and formula documentation searching - a real TSO pain point!

#### DEMO 2: Spreadsheet Analysis with Copilot
- **Scenario:** Analyze the `tso_mock_unit_data.csv` to identify trends without manual formula writing.
- **Prompt:** "Analyse this enrolment data and identify which units are at risk of low numbers. Create a summary table showing units with declining enrolment over 3 semesters."
- **Follow-Up:** "Generate a chart showing enrolment trends and highlight units that need intervention."
- 📌 **Highlight:** Transform raw data into actionable insights in minutes, not hours.

#### DEMO 3: Smart Business Case Generator in Word
- **Scenario:** Using Copilot in Word to draft compliance-ready documents.
- **Prompt:** "Draft a business case for a new engineering unit. Include sections for: market demand, resource requirements, TEQSA compliance, and risk assessment. Use formal academic language suitable for faculty board approval."
- **Follow-Up:** "Review this draft and ensure it addresses all requirements in Curtin's course approval policy. Flag any missing elements."
- 📌 **Highlight:** From rough notes to board-ready document in minutes.

#### DEMO 4: Future Possibility - Course Accreditation Analysis
- **Note:** This demonstrates what could be possible with Libre Chat (pending IT approval).
- **Conceptual Use Case:** "Upload course accreditation documents and ask: What are the key requirements for maintaining Engineers Australia accreditation for this program?"
- **Potential Value:** Query complex policy documents instantly instead of manual searching.
- 📌 **Highlight:** This is a future possibility pending security review by Brenton and Matt.

### 📊 Mock Unit Data Sample

| Semester | Unit Code | Enrollment | Capacity | Completion Rate | Resources |
|----------|-----------|------------|----------|-----------------|-----------|
| 2024 S1 | ENGR1001 | 285 | 300 | 92% | Full |
| 2024 S1 | PHYS2002 | 156 | 200 | 88% | Adequate |
| 2024 S1 | MATH101 | 420 | 400 | 85% | Over capacity |
| 2024 S1 | COMP3001 | 98 | 150 | 94% | Under-utilised |

### 🛠 Copilot Prompt Enhancers

- "Fix this Excel formula and explain what was wrong."
- "Create a pivot table summarising enrolment by faculty."
- "Generate a VLOOKUP formula to match student IDs with completion rates."
- "Draft this in formal academic language suitable for board review."
- "Check this document against university policy requirements."

### 💬 Discussion Prompt

"Which parts of your TSO workflow could benefit most from AI automation?"
"Where might AI help you move from reactive to proactive support planning?"

---

## 🔨 Prompt Crafting with CRAFT

Learn how to write better prompts that yield more relevant, high-quality AI responses using the structured CRAFT framework.

### 💡 Why It Matters

- Most disappointing AI results are due to vague or context-free prompts
- Structured prompts produce better outputs with less rework
- Good prompting principles work across all AI tools, but we'll focus on Microsoft Copilot for university work

*"Think of prompting like a briefing: the better you brief the AI, the better its draft. But also — the first prompt is rarely the final answer. Good prompts invite a conversation, not just a command."*

### 🧠 C.R.A.F.T Framework

| Letter | Meaning | Example |
|--------|---------|---------|
| C | **Context** | "This data is from Curtin engineering units over 3 semesters." |
| R | **Role** | "You are a senior Teaching Support Officer." |
| A | **Action** | "Analyse enrolment trends and resource utilisation." |
| F | **Format** | "Write in bullet points." |
| T | **Tone/Target** | "Use clear language for a faculty board presentation." |

*"You don't have to use every element every time — but this gives you the scaffolding."*

### 🛠 DEMO: Improving a Prompt with CRAFT

**Original Prompt:**
> "What's happening with student numbers?"

**Improved Prompt (with CRAFT):**
> "This is enrolment data from engineering units at Curtin over three semesters. You are an experienced Teaching Support Officer. Analyse the enrolment trends and identify any units at risk of low numbers. Output in three bullet points using clear language for the faculty board."

### 🗣️ Prompting as a Conversation with Copilot

"CRAFT is a great starting point — but don't stop there. One-shot prompting can feel transactional. The real power is in using Copilot as a collaborator."

*"Think of CRAFT as your first message to Copilot. The next steps are to discuss, clarify, iterate."*

**Example Chain in Copilot:**
1. Craft a CRAFT-style analysis prompt in Excel
2. Follow up: "Add any units at risk of cancellation."
3. Follow up: "Now create a chart to visualize this data."

---

## 📚 Prompting Guides & Examples

Explore a collection of prompt patterns, techniques, and examples to enhance your AI interactions for various teaching support tasks.

### 🔧 AI Prompt Playbook for Teaching Support Officers

#### ✨ One-Shot Prompt Starters for Copilot

**🔹 Summarise a table (Excel with Copilot)**
> "Analyze this student enrolment data and highlight which units have capacity issues and any concerning trends in student progression. Create a summary table."

**🔹 Rewrite for faculty (Word with Copilot)**
> "Rewrite this unit performance summary for a faculty board meeting. Keep it under 150 words and focus on actionable insights. Use formal academic language."

**🔹 Create an executive summary (Word with Copilot)**
> "Draft an executive summary of this semester's teaching support achievements. Include sections for efficiency gains, compliance improvements, and student satisfaction metrics. Format with clear headings."

**🔹 Strategy from data (Excel with Copilot)**
> "Based on this enrolment and resource data, identify three strategic options for next semester's unit offerings. Create a table showing each option with pros, cons, and resource impact."

### 📊 From Data to Decisions: Value-Adding Copilot Prompts

**🧠 Summary Use Case: Teaching Support Analysis (Excel with Copilot)**
> "Analyze the unit performance data in this spreadsheet. Create a summary focusing on enrolment trends, student outcomes, and resource utilisation. Add a chart showing key metrics."

**📰 Communication Use Case: Faculty Update (Word with Copilot)**
> "Using this unit analysis data, draft a faculty newsletter update. Include sections on teaching innovations, student satisfaction improvements, and resource efficiency. Use professional language with a positive tone."

**💼 Executive Summary: Board Presentation (Word with Copilot)**
> "Create an executive summary document for the board based on this semester's data. Structure it with: 1) Key achievements, 2) Compliance status, 3) Efficiency metrics, 2) Student success indicators. Use formal academic language."

**🎯 Strategy Use Case: Best Practices (Excel with Copilot)**
> "Analyze this unit performance data and identify the top 3 performing units. Create a table showing what makes them successful and how these practices could benefit other faculties."

### ⚙️ Multi-Turn Prompt Chains with Copilot

**🔹 Document Analysis Workflow (Word with Copilot)**
> First prompt: "Analyze this course proposal and identify key compliance requirements based on TEQSA standards."
> Follow-up: "Now highlight 3 potential compliance risks and suggest improvements for each."
> Final: "Create an executive summary of the analysis with clear recommendations."

**🔹 Format Shifting (Word/Outlook with Copilot)**
> First prompt: "Summarize this impact analysis report into 5 key points for the board."
> Follow-up: "Now draft an email to faculty staff with the same information but in a more conversational tone."
> Final: "Create a brief 2-paragraph update for the student portal focusing on positive outcomes."

### 🧠 CRAFT Prompt Patterns for TSOs with Copilot

**📊 Summarise a Table (Excel with Copilot)**
> "Context: This spreadsheet contains unit performance metrics for the science faculty from semester 1.  
> Role: Analyze as a senior Teaching Support Officer would.  
> Action: Identify key trends and anomalies in the data.  
> Format: Create a summary table with bullet points for each finding.  
> Target: Focus on enrolment patterns, completion rates, and resource utilisation."

**📝 Turn Data into Narrative (Word with Copilot)**
> "Context: These are business school unit metrics for TEQSA compliance review.  
> Role: Write as a Teaching Support Officer preparing documentation.  
> Action: Analyze performance against key quality indicators and identify areas for improvement.  
> Format: Draft a formal paragraph suitable for compliance documentation.  
> Target: Emphasize student success outcomes and teaching quality metrics."

**🎯 Strategy Options (Excel/Word with Copilot)**
> "Context: Our faculty faces a 15% budget reduction for next academic year.  
> Role: Provide analysis as an experienced Teaching Support Officer.  
> Action: Develop 3 strategic scenarios for maintaining teaching quality despite budget cuts.  
> Format: Create a comparison table showing each option with advantages, risks, and resource implications.  
> Target: Consider unit consolidation, online delivery expansion, and staffing optimisation."

---

## 🌟 Unlocking the Impossible

This section helps us see beyond automation to how AI can expand our capabilities, enabling tasks previously too complex, time-consuming, or costly.

### 💡 Framing Statement

*"So far, we've looked at how to automate what you already do with Copilot. Now let's explore what becomes possible when we think bigger - both with tools available today and secure solutions on the horizon."*

### 🧠 Examples of "Impossible" Tasks AI Can Now Tackle

| Task Type | Previously Hard/Impossible | Now Possible With AI |
|-----------|---------------------------|---------------------|
| Policy synthesis | Reading & comparing multiple TEQSA documents | Summarise and extract requirements instantly |
| Report repurposing | Turning 1 analysis into multiple formats | Reformat for board, faculty, or students |
| Internal Q&A | Answering policy questions on demand | Query university docs via secure tools |
| Impact modeling | Manual analysis of course changes | AI-driven scenario exploration |
| Compliance checking | Line-by-line policy verification | Automated compliance gap analysis |

### 🤖 Future Possibility: Secure Document Q&A with Libre Chat

While we currently use Copilot for our AI needs, we're exploring the potential of Libre Chat - a secure platform that could allow us to upload and query internal documents like policies, procedures, and TEQSA guidelines.

**Potential Use Cases (Pending IT Approval):**
- Ask: "What are the requirements for course accreditation at Curtin?"
- Query complex policy documents without manual searching
- Support new TSO staff with instant access to institutional knowledge

**Current Status:** Under security review by IT team (Brenton and Matt). This represents the future of secure, internal AI tools that respect data governance while enhancing productivity.

### 🧠 Discussion Prompt

> "What's something you've *wanted* to do for faculty support, but never had the time or tools for?"
> "What would a junior TSO assistant, working 24/7 and able to read any policy instantly, let you do more of?"

---

## 🔒 Secure & Sustainable AI Use

Grounding our AI exploration in responsible use is crucial. This section covers how to use AI confidently without risking sensitive data, and how to think long-term about secure, governed AI integration.

### 📄 Framing Statement

*"Even if the AI gets the right answer, if you use the wrong data or tool, it can create serious risk. Let's talk about what's safe, what's smart, and what's sustainable in your setting."*

### 🔍 Key Principles

#### Core AI Implementation Principles

1. **People-first Design**
   AI should enhance human capabilities, not replace human judgment. TSOs remain central to teaching support delivery.

2. **Responsible and Ethical Use of AI**
   Consider the impact on students, staff, and academic integrity. Ensure transparency in AI-assisted processes.

3. **Secure and Responsible Design**
   Align with Curtin's IT security policies and TEQSA compliance requirements. Protect student data and privacy.

#### Practical Safety Guidelines

1. **Use mock or public data in all experiments**
   Especially in exploratory or non-integrated tools (e.g., ChatGPT, Claude). Never use real student data outside secure systems.

2. **Assume anything entered into a public AI chat is public**
   Unless you *know* the tool offers enterprise privacy, don't paste student-identifiable or sensitive university information.

3. **Use your secure platforms for sensitive work**
   Copilot inside Microsoft 365 is enterprise-grade: your data stays in your tenant and isn't used to train models.

4. **Prototype in chat tools, deploy in secure environments**
   Test prompts with mock data in ChatGPT, then migrate your workflow to secure Copilot or approved university systems.

5. **Governance is a team sport**
   Involve your IT/security leads and Teaching & Learning committee when formalising AI use. Keep logs, version prompts, and review how tools access data.

### 🤖 AI Tools: What's Under the Hood?

- **Copilot / ChatGPT:** LLMs trained to predict useful text. Copilot is integrated into M365; ChatGPT is public-facing unless restricted.
- **Prompt Engineering:** Structuring your input (Context, Role, Action, Format, Task - CRAFT) to guide AI output.
- **Agents:** Tools that reason and act in steps. Conceptually similar to complex prompt chains.
- **Key Concepts:** Context Window (AI's short-term memory), Temperature (creativity/randomness), AI predicts, not "thinks".
- **Security & Risk:** Copilot data stays in your M365 tenant. Avoid student-sensitive data in public ChatGPT. Always verify AI output.

### 🚧 Platform Governance Comparison

| Tool | Use Case | Governance Notes |
|------|----------|------------------|
| **Copilot (M365)** | Primary tool for university work | ✅ APPROVED for internal docs and student data. Educational license. |
| **ChatGPT** | Personal exploration only | ❌ NOT for university data. Personal learning with mock data only. |
| **Claude** | Personal exploration only | ❌ NOT for university data. Personal learning with mock data only. |
| **Gemini** | Personal exploration only | ❌ NOT for university data. Personal learning with mock data only. |
| **Libre Chat** | Future possibility | 🔄 Under review by IT (Brenton/Matt). Not yet approved. |

### 🚶 What to Say if Asked: "Can we use this for real student data?"

> "Yes, but only in tools governed by Curtin's enterprise environment — like Copilot in Microsoft 365. You can prototype freely in public AI with mock data, but never use real student data outside secure university systems."

---

## 🧩 Personal AI Challenge

Apply what you've learned to a personal, meaningful task. This is a space for experimentation, reflection, and building confidence in your AI prompting skills.

### 📝 Worksheet Prompts

1. What's the task or challenge you're exploring? (e.g., Automating business case templates in Word, analysing unit performance data in Excel)
2. What do you currently do?
3. Draft your CRAFT prompt for this task.
4. Which tool would you try? (☐ Copilot (recommended for university work) ☐ ChatGPT (personal exploration only) ☐ Other)
5. What would success look like for this task?
6. **Reflection:** Surprised by the output? Would you use it again? Where might it fit in your workflow?

### Your Workflow Challenge

This worksheet feeds directly into our project milestone: "Brainstorm and identify initial high-impact use cases" (June 2025). Your input here will help shape our TSO AI toolkit.

---

## ⚖️ Core Tensions in AI-Assisted Work

AI is powerful, but it introduces trade-offs. This section highlights key tensions to consider for balancing ambition with caution.

### 🧠 Thinking vs. Replacing

**Tension:** "AI thinks for me" vs. "AI replaces my work"
**What to Remember:** Use AI to support reasoning, not bypass it. It's a partner, not a substitute. TSOs provide the context, judgment, and human connection that AI cannot.

### 🎯 Prompting vs. Collaborating

**Tension:** One-shot prompting vs. Over-engineering prompts
**What to Remember:** Most good outcomes need back-and-forth. CRAFT is a start, not the finish. Think conversation, not command.

### 🔒 Efficiency vs. Security

**Tension:** Quick results vs. Data protection
**What to Remember:** Always prioritize student data security. Better to be slow and secure than fast and exposed.

### 🏁 Wrap-Up Thought

*"AI doesn't eliminate trade-offs — it just reshapes them. The best practitioners navigate these tensions with clarity, not certainty. You don't need to solve everything — you just need to notice where the friction lives."*

---

## 🎁 Wrap-Up & Next Steps

Concluding the program with clarity, confidence, and practical next steps to integrate AI into your teaching support workflows.

### 🗂 Key Concepts to Revisit

* **CRAFT** for clear, structured prompts
* **Prompting as a conversation**, not a one-shot answer
* **AI as collaborator**, not replacement
* **Mock → Workflow → Secure Deployment**
* **People-first → Responsible → Secure Design**

### 🚀 Next Steps & Project Timeline

*"You don't need permission to start — you just need a use case. Start small, stay safe, and build from there."*

**Immediate Actions (aligned with June 2025 milestone):**
- Use the Personal AI Challenge worksheet to identify your high-impact use case
- This feeds directly into our "Brainstorm and identify initial high-impact use cases" milestone

**Coming Next (July-September 2025):**
- Quick Win: Smart Business Case Generator pilot
- Strategic Win: Intelligent Impact Analysis tools
- Operational Win: Automated data workflows

**Your Role:**
- Prototype one idea next week using the techniques from today
- Share successful prompts with your TSO colleagues
- Bring your use cases to the next Teaching Support meeting
- Contribute to building our TSO AI toolkit

### 🚀 Follow-Up Options

#### 🔁 1. *Copilot Quick Win* Workshop (July 2025)

> Master **Microsoft Copilot for TSO Excellence**

* Advanced Excel formula assistance and data analysis with Copilot
* Automate business case generation in Word with Copilot
* Build TSO-specific prompt templates for common tasks
* Hands-on practice with real TSO scenarios (using secure data)

#### 🛠 2. Scoping an Intelligent Accreditation Hub (August 2025)

> Explore **Libre Chat for Policy & Accreditation Management**

* Work with Brenton and Matt to assess Libre Chat security
* Design secure document upload and query workflows
* Pilot accreditation document Q&A system
* Develop governance protocols for AI-assisted compliance

#### 📚 3. TSO Copilot Excellence Toolkit (September 2025)

> Create comprehensive Microsoft Copilot resources for TSOs:

* Validated Copilot prompts for Excel, Word, and Teams
* TSO-specific templates and workflows
* Integration guides for Curtin's M365 environment
* Copilot best practices aligned with university policies
* Success metrics and TSO case studies

### 💬 Feedback & Next Steps

> We'd love your thoughts:

* What resonated?
* What needs more depth next time?
* Which use cases are you most excited to explore?

Please reach out to Michael Borck or the Teaching Support leadership team with any ideas or requests.

### 🏁 Final Takeaway

*"You don't need to transform everything today. But every prompt you refine, every workflow you automate — that's a step toward the future of teaching support at Curtin."*

---

**Facilitator:** Michael Borck  
**Duration:** 2 hours  
**Format:** Interactive, tool-based workshop

**Site developed for Curtin University Teaching Support Officers**