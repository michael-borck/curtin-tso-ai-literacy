## 📝 Internal Facilitator Notes: AI Literacy and Capability for Teaching Support Officers

**Seminar Title:** 🎓 AI Literacy and Capability for Teaching Support: Transforming Operations at Curtin **Duration:** 2 hours **Facilitator:** Michael Borck **Format:** Instructor-led, interactive, tool-based workshop (no slides)

### **Overall Seminar Goals for Facilitator:**

-   **Empowerment:** Help participants see AI as a powerful partner, not a threat or a magic box.
    
-   **Practicality:** Focus on immediate, actionable use cases relevant to teaching support operations.
    
-   **Mindset Shift:** Encourage a shift from "can AI replace me?" to "how can AI extend me?".
    
-   **Safety & Responsibility:** Ground the discussion in secure and ethical AI practices aligned with university policies.
    
-   **Engagement:** Maintain a highly interactive session with demos, discussions, and a hands-on challenge.
    

### **Pre-Seminar Checklist:**

-   Confirm all participants have a **Microsoft 365 (Office 365)** account with **Copilot access**.
    
-   Ensure access to a **laptop or suitable computing device** for each participant.
    
-   Have `tso_mock_unit_data.csv` readily available for demos.
    
-   Familiarize yourself with the latest version of **Microsoft Copilot** in Word and Excel.
    
-   **Important:** Only Copilot is approved for university data. Other AI tools (ChatGPT, Claude, etc.) are for personal exploration only.
    
-   Print/prepare handouts:
    
    -   `Seminar_Agenda_Detailed.md` (or share `Seminar_Agenda_Interactive.html`)
        
    -   `Prompt_Playbook_for_TSOs.md`
        
    -   `CRAFT_Prompting_Framework.md`
        
    -   `AI_Unlocking_Impossible_Tasks.md`
        
    -   `Secure_Sustainable_AI_Use.md`
        
    -   `Personal_AI_Challenge_Worksheet.md`
        
    -   `Seminar_Wrap_Up_and_Key_Takeaways.md`
        
    -   `TSO_Evaluation_Followup_Options.md` (for post-seminar distribution)
        
-   Prepare a whiteboard or digital equivalent to write the two guiding questions.
    

### **Agenda Breakdown & Facilitator Script:**

#### **🧭 0:00–0:10 — Welcome & Framing**

-   **Purpose:** Set the tone, position AI as a partner, and introduce the seminar's core questions.
    
-   **Key Message:** "AI isn't here to replace your judgment — it’s here to reduce your keyboard time."
    
-   **Talking Points:**
    
    -   **👋 Welcome & Context:**
        
        -   "Good morning/afternoon, everyone. I'm Michael Borck, and I'm excited to spend the next two hours exploring how AI can genuinely enhance your work as Teaching Support Officers."
            
        -   "You are the experts in teaching support and university operations. My role today is to show you what AI can do _with_ that expertise, not replace it."
            
        -   "We'll focus on practical applications and how AI integrates with tools you might already be using."
            
    -   **🤖 Why AI — and Why Now?:**
        
        -   "The landscape of work is changing rapidly. AI is no longer a futuristic concept; it's integrated into tools like Word, Excel, Outlook, and Teams."
            
        -   "The core idea is simple: AI is incredibly fast and increasingly reliable at handling **repetitive** tasks. This frees you up for more **valuable**, judgment-intensive work."
            
        -   "But, and this is crucial, AI isn’t perfect. It needs your **context**, your **expertise**, and your **guidance**."
            
    -   **🚀 What’s Now Possible That Wasn’t Before?:**
        
        -   "Let's think big for a moment. What tasks have you, or your faculty as a whole, avoided doing because they were too time-consuming, too expensive, or just seemed impossible for teaching support?"
            
        -   _Pause for a moment, let them reflect._
            
        -   "AI is making some of those 'too hard' jobs suddenly realistic: automated compliance checking at scale, intelligent impact analysis for course changes, proactive support planning, or even turning university policies into searchable Q&A systems."
            
    -   **❓ Two Guiding Questions for the Seminar:**
        
        -   _Write clearly on whiteboard/digital canvas:_
            
            1.  **"How can we automate what we already do?"**
                
            2.  **"What could we never do — until now?"**
                
        -   "These two questions will be our compass throughout this seminar. Keep them in mind as we explore the tools and techniques."
            
    -   **🧠 Tone to Set:**
        
        -   "This session is designed to be **interactive** and **imaginative**. It's a space for exploration, not perfection."
            
        -   "It's okay to be skeptical; in fact, healthy skepticism is vital. But I encourage you to also be curious. We're not aiming to master AI today, but to start _thinking differently_ about what it can do."
            

#### **⚙️ 0:10–0:30 — Automating Our Core Work: From Hours to Minutes**

-   **Purpose:** Demonstrate AI's ability to handle repetitive teaching support tasks, particularly around compliance documentation and impact analysis.
    
-   **Key Message:** "AI isn't just for answering questions — it can draft business cases, check compliance, analyse impacts, and consolidate data. We're not just automating what we do — we're enhancing our strategic value."
    
-   **Live Demo Setup:**
    
    -   Ensure you have `tso_mock_unit_data.csv` ready.
        
    -   Have Microsoft Copilot ready in both Excel and Word.
        
    -   Prepare a broken Excel formula example for Demo 1.
        
    -   _Remind participants that these are mock data examples to demonstrate functionality, not real student data._
        
-   **Framing:**
    
    -   "Let's be honest — a lot of time is spent on repetitive compliance checks, reformatting documentation, and manual data collection. These tasks consume hours that could be spent on strategic support planning. AI can automate these processes."
        
    -   _Reiterate the two guiding questions from the previous segment._
        
-   **Demo Walkthrough (follow prompts from `tso_automate_the_tedious_full.md`):**
    
    -   **✅ DEMO 1: Excel Formula Assistance with Copilot**
        
        -   _This demonstrates how Copilot can save hours debugging formulas._
            
        -   **Setup:** Open Excel with a broken formula for calculating student load (prepare example: =SUMIF(A:A,">100",B:B)/COUNTIF(C:C,""))
            
        -   **Initial Prompt:** Copy the broken formula and ask Copilot: "What's wrong with this formula and how can I fix it?"
            
        -   _Show how Copilot identifies the error (COUNTIF with empty criteria) and provides the corrected formula._
            
        -   **Follow-Up Prompt:** "Generate a formula that calculates the weighted average of student satisfaction scores across multiple units, excluding any blank cells."
            
        -   **📌 Highlight:** This saves hours of debugging and formula documentation searching - a real TSO pain point!
            
    -   **✅ DEMO 2: Spreadsheet Analysis with Copilot**
        
        -   _Use the `tso_mock_unit_data.csv` for analysis._
            
        -   **Setup:** Open the CSV in Excel with Copilot.
            
        -   **Prompt:** "Analyse this enrolment data and identify which units are at risk of low numbers. Create a summary table showing units with declining enrolment over 3 semesters."
            
        -   _Show how Copilot analyses the data and creates insights._
            
        -   **Follow-Up:** "Generate a chart showing enrolment trends and highlight units that need intervention."
            
        -   **📌 Highlight:** Transform raw data into actionable insights in minutes, not hours.
            
    -   **✅ DEMO 3: Smart Business Case Generator in Word**
        
        -   _Using Copilot in Word to draft compliance-ready documents._
            
        -   **Setup:** Open Word with Copilot and some rough notes about a new engineering unit proposal.
            
        -   **Prompt:** "Draft a business case for a new engineering unit. Include sections for: market demand, resource requirements, TEQSA compliance, and risk assessment. Use formal academic language suitable for faculty board approval."
            
        -   _Show how Copilot creates a structured document._
            
        -   **Follow-Up:** "Review this draft and ensure it addresses all requirements in Curtin's course approval policy. Flag any missing elements."
                
        -   **📌 Highlight:** From rough notes to board-ready document in minutes.
            
    -   **✅ DEMO 4: Future Possibility - Course Accreditation Analysis**
        
        -   _This demonstrates what could be possible with Libre Chat (pending IT approval)._
            
        -   **Conceptual Discussion:** "Imagine uploading course accreditation documents and asking: 'What are the key requirements for maintaining Engineers Australia accreditation for this program?'"
            
        -   **Potential Value:** Query complex policy documents instantly instead of manual searching.
            
        -   **📌 Important Note:** "This is a future possibility. Libre Chat is currently under security review by Brenton and Matt. For now, we work within Copilot's capabilities."
            
    -   **🛠 Optional Prompt Enhancers (Discuss, don't necessarily demo all):**
        
        -   "Use clear language suitable for faculty board presentations."
            
        -   "Structure as an executive summary with actionable recommendations."
            
        -   "Include compliance references to TEQSA standards."
            
        -   "Write like an experienced Teaching Support Officer."
            
-   **Discussion Prompt (`tso_review_first_two_agenda_items.md` suggests a tailored prompt):**
    
    -   "Which parts of your **TSO workflow** could benefit most from AI automation?"
        
    -   "Where might AI help you move from **reactive to proactive** support planning?"
        
    -   _Encourage participants to share specific examples from their work._
        
-   **Key Takeaway:**
    
    -   "AI isn't just for answering questions — it can draft business cases, check compliance, analyse impacts, and consolidate data. We're not just automating what we do — we're enhancing our strategic value."
        

#### **🔨 0:30–0:45 — Prompt Crafting with CRAFT**

-   **Purpose:** Teach participants a structured framework (CRAFT) for writing effective prompts.
    
-   **Key Message:** "CRAFT isn’t just for writing better prompts — it’s a way to start better conversations with AI. Think of it like briefing a capable colleague, not commanding a tool. It works best when you build on it turn by turn."
    
-   **Handout:** `CRAFT_Prompting_Framework.md`
    
-   **Talking Points:**
    
    -   **💡 Why It Matters:**
        
        -   "Most disappointing AI results aren't because the AI is bad, but because the prompt was vague or lacked context."
            
        -   "Structured prompts lead to better, more relevant outputs with less rework."
            
        -   "The beauty of CRAFT is that it's platform-agnostic – it works whether you're using ChatGPT, Copilot, Gemini, or Claude."
            
        -   "Think of prompting like a briefing: the better you brief the AI, the better its draft. And remember, the first prompt is rarely the final answer. Good prompts invite a **conversation**, not just a command."
            
    -   **🧠 C.R.A.F.T Framework:**
        
        -   _Walk through each element of CRAFT, using the examples from `CRAFT_Prompting_Framework.md`._
            
        -   **C** = **Context**: "What background info does the AI need? (e.g., 'This data is from Curtin engineering units over 3 semesters.')"
            
        -   **R** = **Role**: "Who should the AI pretend to be? (e.g., 'You are a senior Teaching Support Officer.')"
            
        -   **A** = **Action**: "What do you want the AI to _do_? (e.g., 'Analyse enrolment trends and resource utilisation.')"
            
        -   **F** = **Format**: "How should the output be structured? (e.g., 'Write in bullet points.')"
            
        -   **T** = **Tone/Target**: "What's the desired tone or audience? (e.g., 'Use clear language for a faculty board presentation.')"
            
        -   "You don’t have to use every element every time — but this gives you the scaffolding."
            
    -   **🛠 DEMO: Improving a Prompt with CRAFT:**
        
        -   _Use the "Original Prompt" and "Improved Prompt" example from the handout._
            
        -   **Original Prompt:** "What's happening with student numbers?"
            
        -   **Improved Prompt:** "This is enrolment data from engineering units at Curtin over three semesters. You are an experienced Teaching Support Officer. Analyse the enrolment trends and identify any units at risk of low numbers. Output in three bullet points using clear language for the faculty board."
            
        -   _Show the difference in output quality (if possible, by running both in your LLM)._
            
    -   **🗣 Prompting as a Conversation:**
        
        -   "CRAFT is a great **starting point** — but don't stop there. One-shot prompting can feel transactional. The real power is in **using AI as a collaborator**."
            
        -   "Think of CRAFT as your first message to a new colleague. The next steps are to discuss, clarify, iterate."
            
        -   **Example Chain (reiterate from previous section, or quickly demo one):**
            
            1.  "Craft a CRAFT-style summary prompt."
                
            2.  "Follow up: 'Add any year-on-year risks you see.'"
                
            3.  "Follow up: 'Now restructure that for a faculty update.'"
                
        -   "You’re not just prompting. You’re **working together.**"
            
    -   **🔁 Practice Exercise (Interactive):**
        
        -   "Now it's your turn. Take a short paragraph or summary (either from your own work or a generic example you have ready)."
            
        -   "Your task is to rewrite a basic prompt for it using the CRAFT structure."
            
        -   "Then, think of a follow-up prompt to adapt the result for another audience."
            
        -   _Give them 3-5 minutes to work individually or in pairs._
            
        -   _Invite 1-2 participants to share their original task, their CRAFT prompt, and their follow-up idea._
            
        -   **Facilitator Highlight:** Emphasize how **prompting evolves across turns** and how adding context and specificity improves results.
            
-   **Key Takeaway:**
    
    -   "CRAFT isn’t just for writing better prompts — it’s a way to start better conversations with AI. Think of it like briefing a capable colleague, not commanding a tool. It works best when you build on it turn by turn."
        

#### **☕ 0:45–0:55 — Break**

-   **Purpose:** Provide a short break for participants.
    
-   **Talking Points:**
    
    -   "Time for a quick break! Grab some tea or coffee, stretch your legs."
        
    -   _Optional: Write on whiteboard/digital canvas:_ "What _hasn’t_ AI helped you with — yet?" _This can serve as a thought-starter for the next segment._
        

#### **🌟 0:55–1:15 — Unlocking the Impossible**

-   **Purpose:** Shift mindset from automation to capability expansion, showcasing tasks previously difficult or impossible.
    
-   **Key Message:** "Automation is good. But transformation is better. The real power of AI is doing things you couldn’t do before. This is where competitive advantage lives."
    
-   **Handout:** `AI_Unlocking_Impossible_Tasks.md`
    
-   **Talking Points:**
    
    -   **💡 Framing Statement:**
        
        -   "So far, we’ve looked at how to automate what you already do. Now let’s ask a better question: What have you never been able to do because it felt too hard, too slow, or too expensive? AI may now make those things possible."
            
    -   **🧠 Examples of "Impossible" Tasks AI Can Now Tackle:**
        
        -   _Go through the table in the handout, providing brief, real-world examples for each._
            
        -   **Market synthesis:** "Imagine quickly digesting 5+ market reports to extract key insights, not just summaries."
            
        -   **Report repurposing:** "Turning a detailed annual report into a concise faculty email, a website update, and a board presentation, all in minutes."
            
        -   **Internal Q&A:** "New staff asking complex policy questions and getting instant, cited answers from your internal SOPs."
            
        -   **Competing viewpoints:** "Having AI simulate a debate between different approaches to unit consolidation or delivery modes, showing pros and cons for each."
            
        -   **Strategic what-ifs:** "Exploring multiple 'what-if' scenarios for course changes and student impact without spending days building complex spreadsheets."
            
    -   **🤖 Future Possibilities: Libre Chat Discussion**
        
        -   "While we currently work within Copilot's capabilities, there's an exciting possibility on the horizon: Libre Chat."
            
        -   "Imagine being able to upload course accreditation documents, TEQSA guidelines, or university policies and _ask_ them questions directly."
            
        -   _Conceptual walkthrough:_
            
            -   "You could upload accreditation requirements and ask: 'What are the key requirements for maintaining Engineers Australia accreditation?'"
                
            -   "Or query: 'What documentation is needed for a major course revision according to Curtin policy?'"
                
            -   "This could transform how we handle complex compliance and policy questions."
                
        -   **📌 Important caveat:**
            
            -   "Libre Chat is currently under security review by our IT team (Brenton and Matt)."
                
            -   "This represents the future of secure, internal AI tools that respect data governance while enhancing productivity."
                
    -   **🧠 Discussion Prompt:**
        
        -   "What's something you've _wanted_ to do for faculty support, but never had the time or tools for?"
            
        -   "What would a junior TSO assistant, working 24/7 and able to read any policy instantly, let you do more of?"
            
        -   _Encourage sharing and brainstorming._
            
    -   **✅ Optional Micro-Exercise: Reverse Prompt (if time allows, or assign as homework)**
        
        -   "Think of a task you've never had time for. Now, try to write a prompt that _tries_ to do that thing. What happens?"
            
        -   _Example: "Write a benchmarking summary comparing this semester's unit performance to 3 previous semesters. Highlight enrolment trends, completion rates, and resource utilisation patterns."_
            
-   **Key Takeaway:**
    
    -   "Automation is good. But transformation is better. The real power of AI is doing things you couldn’t do before. This is where competitive advantage lives."
        

#### **🔒 1:15–1:30 — Secure & Sustainable AI Use**

-   **Purpose:** Ground the seminar in responsible AI use, building confidence in secure practices.
    
-   **Key Message:** "AI is only as smart as your context — and only as safe as your systems. Work with it like a colleague: trust it, but verify, and never put it in a position to break the rules.”
    
-   **Handout:** `Secure_Sustainable_AI_Use.md`
    
-   **Handout:** `AI_Core_Tensions_Handout.md` (for deeper reflection)
    
-   **Talking Points:**
    
    -   **📄 Framing Statement:**
        
        -   "Even if the AI gets the right answer, if you use the wrong data or tool, it can create serious risk. Let’s talk about what’s safe, what’s smart, and what’s sustainable in your setting."
            
    -   **🔍 Key Principles (go through each point in the handout):**
        
        1.  **Use mock or public data in all experiments:** "Especially with public tools like ChatGPT. Never use real student data here."
            
        2.  **Assume anything entered into a public AI chat is public:** "Unless you have explicit enterprise agreements, treat it as a public forum."
            
        3.  **Use your secure platforms for sensitive work:** "Copilot within Microsoft 365 is enterprise-grade. Your data stays within your tenant and is _not_ used to train public models. This is critical for Curtin and student data protection."
            
        4.  **Prototype in chat tools, deploy in secure environments:** "Think of public AI as your sandbox for prompt engineering. Once you have a working workflow, move it to a secure environment like Copilot, or even automation tools like Zapier or n8n if appropriate."
            
        5.  **Governance is a team sport:** "Involve your IT and security teams. Keep logs of how AI is used, version your prompts, and understand data access."
            
    -   **🚧 Platform Governance Comparison:**
        
        -   _Briefly discuss the table in the handout, emphasizing the distinction between public and enterprise-grade tools._
            
        -   "**ChatGPT/Claude:** Great for rapid prototyping with mock data. **Never** for student-sensitive information."
            
        -   "**Copilot Chat (in M365):** Your go-to for internal and faculty-facing work. It respects your existing permissions and data security."
            
        -   "**Gemini:** Use with caution, verify its data handling policies for your specific use case."
            
    -   **🚀 Strategy Summary: Prompt, Process, Protect:**
        
        -   "To summarise our approach to responsible AI use:"
            
            1.  **Prompt It:** "Use AI chat to test your thinking, summarise ideas, and shape workflows."
                
            2.  **Process It:** "Move successful chains into tools like Copilot, n8n, or Zapier."
                
            3.  **Protect It:** "When it's sensitive or student-facing, work within secure systems."
                
    -   **🚶 What to Say if Asked: "Can we use this for real student data?"**
        
        -   "Yes, but only in tools governed by Curtin's enterprise environment — like Copilot in Microsoft 365. You can prototype freely in public AI with mock data, but never use real student data outside secure university systems."
            
    -   **🤔 Discussion (refer to `AI_Core_Tensions_Handout.md`):**
        
        -   "AI introduces some core tensions. Let's look at the 'Thinking vs. Replacing' or 'Speed vs. Safety' sections in your handout. What challenges do you foresee in balancing these in your daily work?"
            
        -   _Encourage a brief discussion on practical implications._
            
-   **Key Takeaway:**
    
    -   "AI is only as smart as your context — and only as safe as your systems. Work with it like a colleague: trust it, but verify, and never put it in a position to break the rules.”
        

#### **🧩 1:30–1:45 — Personal AI Challenge**

-   **Purpose:** Provide a hands-on, personalized activity to apply learned concepts and build confidence.
    
-   **Key Message:** "This is where the real shift happens: not just using AI for the tasks I already do, but discovering how it can help me think, improve, and explore new possibilities. One prompt at a time."
    
-   **Handout:** `Personal_AI_Challenge_Worksheet.md`
    
-   **Talking Points:**
    
    -   **🧠 Challenge Setup:**
        
        -   "You’ve seen one-shot prompts. You’ve seen collaborative chains. You’ve seen CRAFT. Now let’s flip it around: what’s a task you do often — or wish you could do — that we haven’t covered?"
            
        -   "Your task is to fill out the 'Personal AI Challenge Worksheet'."
            
        -   **Participants choose one:**
            
            -   A **real task** they perform in Excel, Word, Teams, or Outlook.
                
            -   A **reporting or writing challenge** (summaries, strategy, risk, benchmarking).
                
            -   A **faculty question** they regularly field.
                
        -   **Then, on the worksheet:**
            
            -   "Identify the task/challenge."
                
            -   "Write your **first CRAFT-style prompt** for it."
                
            -   "Choose which tool you'd try (Copilot, ChatGPT, Claude, NotebookLM)."
                
            -   "Define what success would look like for this task."
                
            -   "If you have time, try running your prompt in your chosen tool and note the results."
                
        -   _Give participants 10-12 minutes to work on this individually._
            
        -   _Circulate around the room to offer one-on-one support and answer questions._
            
    -   **🗣 Share & Reflect:**
        
        -   "Let's bring it back together. Would 1-2 volunteers be willing to share their challenge and what they experienced?"
            
        -   _If someone shares, guide the discussion:_
            
            -   "What was the original task?"
                
            -   "What was the AI's output like (briefly summarise)?"
                
            -   "What was your revised or improved prompt (if applicable)?"
                
        -   **Facilitator Highlight:**
            
            -   "Notice how prompt refinement is a form of thinking, not just correcting."
                
            -   "This is about collaboration, not just automation."
                
            -   "Consider how the choice of tool fits the task."
                
-   **Key Takeaway:**
    
    -   "This is where the real shift happens: not just using AI for the tasks I already do, but discovering how it can help me think, improve, and explore new possibilities. One prompt at a time."
        

#### **🎁 1:45–2:00 — Wrap-Up & Takeaways**

-   **Purpose:** Provide a clear summary, reinforce key concepts, and encourage practical next steps.
    
-   **Key Message:** "You don’t have to master AI today. But if you can start thinking with it — shaping questions, exploring answers, refining together — you’ve already unlocked the most powerful part of the tool.”
    
-   **Handout:** `Seminar_Wrap_Up_and_Key_Takeaways.md`
    
-   **Handout (for post-seminar distribution):** `TSO_Evaluation_Followup_Options.md`
    
-   **Talking Points:**
    
    -   **🧠 Recap the Journey:**
        
        -   "We've covered a lot today. We started with _why_ AI matters and _what's now possible_."
            
        -   "We moved into practical applications: automating the tedious, crafting better prompts with CRAFT, and exploring how AI can unlock entirely new capabilities."
            
        -   "Crucially, we discussed governance, safety, and how to approach AI sustainably within Curtin's context."
            
    -   **🗂 Key Concepts to Revisit (refer to `Seminar_Wrap_Up_and_Key_Takeaways.md`):**
        
        -   "Remember CRAFT for clear, structured prompts."
            
        -   "Think of prompting as a **conversation**, not a one-shot command."
            
        -   "AI is your **collaborator**, not a replacement."
            
        -   "Our workflow mantra: **Mock → Workflow → Secure Deployment**."
            
        -   "And the core principle: **Prompt → Process → Protect**."
            
    -   **📦 What They Leave With:**
        
        -   "You're walking away with tangible resources:"
            
            -   "Your **Prompt Playbook** (cheat sheets for CRAFT, Prompt Chaining, Value-Adding Prompts, Advanced Tips)."
                
            -   "Your **Personal Prompt Challenge** worksheet – a roadmap for your next experiment."
                
            -   "The **'AI Under the Hood'** handout (if distributed) and **NotebookLM Use Case Overview** (if applicable)."
                
            -   "Most importantly, a clearer **framing for safe & responsible AI use** within your work."
                
    -   **🚀 Next Steps:**
        
        -   "You don’t need permission to start — you just need a use case. Start small, stay safe, and build from there."
            
        -   **Recommend:**
            
            -   "This week, prototype just **one idea** using AI: maybe an AI summary, a draft blog post, or a quick table analysis."
                
            -   "Share one working prompt with a colleague – learning together accelerates adoption."
                
            -   "Bring your ideas and challenges to your next team or strategy session. This is an ongoing conversation."
                
    -   **💬 Closing Prompt (Optional, but powerful):**
        
        -   "To leave you with one final thought: If you had a smart assistant who could read, write, and think with you — what would you ask it to do first next week?"
            
        -   _Encourage them to write this down on their worksheet or a sticky note and keep it visible._
            
    -   **🏁 Final Takeaway:**
        
        -   "You don’t have to master AI today. But if you can start thinking with it — shaping questions, exploring answers, refining together — you’ve already unlocked the most powerful part of the tool."
            
    -   **Post-Seminar Logistics:**
        
        -   "Thank you all for your engagement and curiosity. We'll be sending out a follow-up email with a link to all these resources, plus some optional next steps for continued learning and support."
            
        -   _Mention the `TSO_Evaluation_Followup_Options.md` document here, which will be sent out._


