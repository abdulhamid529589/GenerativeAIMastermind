# Generative AI / Claude AI Mastermind — Complete Session Notes (Day 1 & Day 2)

> **Source:** 2-Day Generative AI Mastermind (Outskill) — Full Transcript (Day 1 + Day 2)

> **Compiled for:** Cyber Security Department — AI Engineering Coursework
> **Purpose:** Structured, readable reference notes covering every major concept, tool, and workflow demonstrated across both days of the mastermind.

---

## Table of Contents

1. [Session Overview & Context](#1-session-overview--context)
2. [Part A — Foundations of Generative AI (by Deep)](#part-a--foundations-of-generative-ai-by-deep)

- 2.1 [What Is Generative AI? (The Layered Definition)](#21-what-is-generative-ai-the-layered-definition)
- 2.2 [How LLMs Actually Work — The 5-Step Process](#22-how-llms-actually-work--the-5-step-process)
- 2.3 [Prompt Engineering vs. Context Engineering](#23-prompt-engineering-vs-context-engineering)
- 2.4 [The 5 Layers of Context Engineering (ICTEB Framework)](#24-the-5-layers-of-context-engineering-ictbe-framework)
- 2.5 [Worked Example: Context-Engineered Prompt](#25-worked-example-context-engineered-prompt)
- 2.6 [Meta-Prompting: Getting AI to Build Its Own Prompt](#26-meta-prompting-getting-ai-to-build-its-own-prompt)
- 2.7 [Which AI Model to Use, and When](#27-which-ai-model-to-use-and-when)
- 2.8 [Discovering & Comparing Models](#28-discovering--comparing-models)
- 2.9 [Reasoning Models & "Effort" Settings](#29-reasoning-models--effort-settings)
- 2.10 [Claude Skills](#210-claude-skills)

3. [Part B — Building an AI Toolkit (by Deep)](#part-b--building-an-ai-toolkit-by-deep)

- 3.1 [Productivity Tools](#31-productivity-tools)
- 3.2 [Learning Tools](#32-learning-tools)
- 3.3 [Research Tools](#33-research-tools)
- 3.4 [Interview Preparation](#34-interview-preparation)
- 3.5 [Data & Dashboard Interpretation](#35-data--dashboard-interpretation)
- 3.6 [Creative / Marketing Tools](#36-creative--marketing-tools)
- 3.7 [Distribution & Networking Tools](#37-distribution--networking-tools)
- 3.8 [Data Analysis with AI](#38-data-analysis-with-ai)
- 3.9 [Tool Discovery Platforms](#39-tool-discovery-platforms)
- 3.10 [Claude Artifacts](#310-claude-artifacts)
- 3.11 [Capstone Demo: End-to-End Job Application Workflow](#311-capstone-demo-end-to-end-job-application-workflow)

4. [Part C — The Future of Work with AI (by Deep)](#part-c--the-future-of-work-with-ai-by-deep)

- 4.1 [AI Agents vs. AI Chat: Delegation vs. Micromanagement](#41-ai-agents-vs-ai-chat-delegation-vs-micromanagement)
- 4.2 [The AI Generalist Mindset](#42-the-ai-generalist-mindset)
- 4.3 [Career Guidance by Experience Level](#43-career-guidance-by-experience-level)
- 4.4 [Organizational Architecture in the AI Era](#44-organizational-architecture-in-the-ai-era)
- 4.5 [Opportunities for Entrepreneurs](#45-opportunities-for-entrepreneurs)

5. [Part D — Building AI Bots & Agents (by Webhu Sicinti)](#part-d--building-ai-bots--agents-by-webhu-sicinti)

- 5.1 [Level 1: Custom GPTs (No-Code Micro-Apps)](#51-level-1-custom-gpts-no-code-micro-apps)
- 5.2 [Reverse-Engineering a Personal Writing Style](#52-reverse-engineering-a-personal-writing-style)
- 5.3 [Markdown Prompting Structure (Role / Objective / Context / Instructions / Notes)](#53-markdown-prompting-structure-role--objective--context--instructions--notes)
- 5.4 [Building It for Free: Claude Projects](#54-building-it-for-free-claude-projects)
- 5.5 [Level 3: Building an Autonomous "AI Employee" with Kimi](#55-level-3-building-an-autonomous-ai-employee-with-kimi)
- 5.6 [Building a Custom Q&A Agent (Outskill AI Mentor)](#56-building-a-custom-qa-agent-outskill-ai-mentor)
- 5.7 [Turning an Agent into a Voice Assistant (Vapi)](#57-turning-an-agent-into-a-voice-assistant-vapi)
- 5.8 [Claude Design (AI Slide/Design Generation)](#58-claude-design-aislidedesign-generation)

6. [Part E — The 5 Levels of an AI Generalist](#part-e--the-5-levels-of-an-ai-generalist)

- 6.1 [Level 1 — Advanced Model Usage](#61-level-1--advanced-model-usage)
- 6.2 [Level 2 — MCP (Model Context Protocol) & Automation](#62-level-2--mcp-model-context-protocol--automation)
- 6.3 [Level 3 — AI-Generated Audio, Image & Video (Digital Cloning)](#63-level-3--ai-generated-audio-image--video-digital-cloning)
- 6.4 [Level 4 — Building Autonomous Agents ("Jerry")](#64-level-4--building-autonomous-agents-jerry)
- 6.5 [Level 5 — Vibe Coding](#65-level-5--vibe-coding)

7. [Day 2 — Recap & Kickoff](#7-day-2--recap--kickoff)
8. [Part F — Vibe Coding (by Dilip)](#part-f--vibe-coding-by-dilip)

- 8.1 [The Core Philosophy: Blueprint Before You Build](#81-the-core-philosophy-blueprint-before-you-build)
- 8.2 [Two Build Paths: Website vs. Web Application](#82-two-build-paths-website-vs-web-application)
- 8.3 [Use Case 1: Improving an Existing Website — The C2R2 Framework](#83-use-case-1-improving-an-existing-website--the-c2r2-framework)
- 8.4 [Use Case 2: Building a New Website From Scratch](#84-use-case-2-building-a-new-website-from-scratch)
- 8.5 [Understanding Front End vs. Back End (The Movie Analogy)](#85-understanding-front-end-vs-back-end-the-movie-analogy)
- 8.6 [Use Case 3: Building a Full Web Application From Scratch](#86-use-case-3-building-a-full-web-application-from-scratch)
- 8.7 [Iterative Feature Building & Error Handling](#87-iterative-feature-building--error-handling)
- 8.8 [Publishing, Security, and Scaling](#88-publishing-security-and-scaling)
- 8.9 [Vibe Coding Platform Comparison](#89-vibe-coding-platform-comparison)
- 8.10 [Dilip's Closing Advice: "Be the Surfer"](#810-dilips-closing-advice-be-the-surfer)

9. [Part G — AI-Powered Automation with n8n (by Divij)](#part-g--ai-powered-automation-with-n8n-by-divij)

- 9.1 [What Are Automations? Traditional vs. AI-Powered](#91-what-are-automations-traditional-vs-ai-powered)
- 9.2 [The Three Pillars of Any Automation: Trigger → Logic → Action](#92-the-three-pillars-of-any-automation-trigger--logic--action)
- 9.3 [Where Automation Excels vs. Where It Struggles](#93-where-automation-excels-vs-where-it-struggles)
- 9.4 [No-Code Automation Platform Landscape](#94-no-code-automation-platform-landscape)
- 9.5 [Understanding APIs (The Waiter Analogy)](#95-understanding-apis-the-waiter-analogy)
- 9.6 [Planning Before Building: The Whiteboard Method](#96-planning-before-building-the-whiteboard-method)
- 9.7 [Full Build Walkthrough: Automated Gmail Customer Support Triage](#97-full-build-walkthrough-automated-gmail-customer-support-triage)
- 9.8 [Extending the Workflow Further](#98-extending-the-workflow-further)
- 9.9 [Learning for Free: Templates & Local Hosting](#99-learning-for-free-templates--local-hosting)

10. [Part H — Program Options, Bonuses & Closing](#part-h--program-options-bonuses--closing)

- 10.1 [Outskill Program Tiers](#101-outskill-program-tiers)
- 10.2 [Bonuses, Certificates & Referral Program](#102-bonuses-certificates--referral-program)

11. [Glossary of Tools Mentioned](#11-glossary-of-tools-mentioned)
12. [Key Takeaways & Action Items](#12-key-takeaways--action-items)

---

## 1. Session Overview & Context

- **Format:** A free, large-scale, live 2-day online "mastermind" hosted by **Outskill**, described as the world's largest generative AI education platform (11M+ learners, 100M+ learning hours, 4.8/5 average rating).
- **Audience:** Extremely diverse — 87% first-time attendees, participants from 20+ countries, experience ranging from 0 to 40+ years, across engineering, finance, HR, legal, sales, government, and more.
- **Structure of Day 1:**

1. **Session 1 (Deep):** Foundations of generative AI, prompting, model selection, and a broad AI tool stack.
2. **Session 2 (Webhu Sicinti):** Advanced prompt engineering, building custom AI bots/agents, automation (MCP), and the "5 levels of an AI generalist."

- **No recordings provided** for the mastermind sessions (only for the paid Accelerator Program); note-taking was strongly encouraged.
- **Certificate** provided on completion of the full mastermind.

---

## Part A — Foundations of Generative AI (by Deep)

### 2.1 What Is Generative AI? (The Layered Definition)

**Simple definition:** Generative AI is artificial intelligence that **creates content** — text, images, or videos.

The broader hierarchy of AI, from general to specific:

| Layer                                      | Description                                                                                                                                                             | Example                                             |
| ------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------- |
| **Artificial Intelligence (AI)**           | Systems designed to mimic human intelligence. The benchmark for "intelligence" keeps shifting (chess in the 1990s → Jeopardy in the 2000s → AlphaGo → the Turing Test). | Any rule-based or learning system                   |
| **Pattern Recognition / Machine Learning** | Systems that learn from data and predict future behavior based on past behavior.                                                                                        | Amazon "you may also like," Netflix recommendations |
| **Neural Networks / Deep Learning**        | Deeper pattern recognition mimicking how the human brain processes complex data, used for image recognition and tracking.                                               | Facial recognition tagging, surveillance tracking   |
| **Large Language Models (LLMs)**           | A subset of deep learning focused specifically on generating text, images, and video from language.                                                                     | ChatGPT, Claude, Gemini                             |

**Key idea:** The mastermind focuses specifically on the LLM layer — the tools people interact with daily (ChatGPT, Claude, Gemini, etc.).

---

### 2.2 How LLMs Actually Work — The 5-Step Process

Demonstrated using the prompt: _"Explain large language models to me like I am 5 years old."_

| Step                                          | What Happens                                                                                                                                                          | Analogy Used                                                                                                                                                       |
| --------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **1. Tokenization**                           | The input sentence is broken into smaller pieces (tokens).                                                                                                            | A chef chopping a pumpkin into small pieces; a Lego structure made of small bricks                                                                                 |
| **2. Embeddings**                             | Each token/word is converted into a numerical/mathematical representation (coordinates). Words with similar meaning end up as "neighbors" in this mathematical space. | GPS coordinates — places like the Eiffel Tower or Red Fort are represented as lat/long. Words like "founders," "startups," "VC" cluster in the same "neighborhood" |
| **3. Self-Attention (Transformer Mechanism)** | The model identifies which words in the input are most important for generating a correct/relevant response.                                                          | Shining a flashlight on seat "F12" in a dark movie theater — you don't scan every letter, you focus on what matters                                                |
| **4. Prediction**                             | The model predicts the most probable next word, one token at a time, based on patterns learned from massive training data.                                            | Autocomplete predicting "store" after "I'm going to the \_\_\_"                                                                                                    |
| **5. Response Generation**                    | The predicted tokens are assembled and converted back into full, human-readable sentences/paragraphs.                                                                 | Converting coordinates back into readable text                                                                                                                     |

> **Core intuition:** LLMs don't "think" like humans — they predict the statistically most likely next word based on patterns seen in massive amounts of training text (a "super-smart parrot" that has read the entire internet).

---

### 2.3 Prompt Engineering vs. Context Engineering

This is one of the most important distinctions taught in the session.

| Concept                 | Definition                                                                                                         | Analogy                                                                                                 |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------- |
| **Prompt Engineering**  | Giving _better instructions_ — the actual task/command.                                                            | "Turn on the bike using the battery."                                                                   |
| **Context Engineering** | Giving AI _everything a smart human would need_ to succeed at the task — background, audience, goals, constraints. | Telling a new employee about the company, its culture, and its processes — not just "prepare a report." |

**New-employee analogy:** Even the smartest new hire will fail on Day 1 without context about the company. If AI gives a poor output, **it is the user's fault (lack of context), not the AI's fault** — just as it would be an employer's fault if a great new hire failed due to lack of onboarding.

---

### 2.4 The 5 Layers of Context Engineering (ICTEB Framework)

| Layer                                       | Question It Answers                                                        | Example                                                                                                        |
| ------------------------------------------- | -------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- |
| **1. Identity**                             | Who should the AI act as?                                                  | "Act as an experienced email copywriter who has written for brands like Ogilvy."                               |
| **2. World/Context**                        | What does the AI need to know about the situation, business, and audience? | "The audience is professionals aged 25+ working in marketing/tech/product who want to stay relevant using AI." |
| **3. Task**                                 | What exactly needs to happen? (This is the actual "prompt" instruction.)   | "Write a launch email inviting signed-up users to the workshop."                                               |
| **4. Examples**                             | What does great output look like vs. bad output?                           | "Keep it short, concise, and action-oriented. No fluff."                                                       |
| **5. Boundaries / Rules / Non-negotiables** | What must NOT happen? Constraints.                                         | "Keep it under 500 words. Use bullets. End with a decision table. Avoid jargon."                               |

**Worked example prompt structure (Weekly Leadership Update):**

- **Identity:** "You are a sharp chief of staff and executive communication partner."
- **World:** "Preparing a weekly update for founders, senior leaders, functional heads — busy, design-oriented, no vague motivational language."
- **Task:** "Turn the raw notes below into a crisp weekly leadership update."
- **Examples:** "Good updates are direct, specific, and separate facts / risks / decisions / next actions."
- **Constraints:** "Under 500 words. Use bullets. End with a table: Decision Needed | Owner | Deadline. Avoid jargon."

---

### 2.5 Worked Example: Context-Engineered Prompt

Tool used: **Superprompts** (a prompt-storage/organization tool) → prompt copied into **Claude (Sonnet)**.

**Process demonstrated:**

1. Store reusable, well-structured prompts.
2. Paste a fully context-engineered prompt into Claude.
3. Claude converts messy meeting notes into a polished weekly leadership update with sections: Performance, Product, Hiring, Customer Success, Risks to Watch, Decisions Needed.

**Simple "meta-prompt" trick for beginners:**

> "You are my executive briefing partner. When I give you a rough task, first convert it into a strong Identity / World / Task / Examples / Constraints structure, then ask clarifying questions if needed."

This lets you give AI a _rough, even typo-filled_ task, and it builds the structured prompt internally, asks clarifying questions, and produces a polished output — plus you can say **"double-check your output"** or **"rebuild it"** to iteratively refine.

> **Underrated tip:** Always ask AI "Are you sure this is the best possible output? Can you double-check?" — this alone significantly improves quality.

---

### 2.6 Meta-Prompting: Getting AI to Build Its Own Prompt

Instead of writing prompts manually, give AI a **structure/template** and let it fill in the "identity, world, task, examples, constraints" fields itself when you give it a rough task in natural (even messy) language.

---

### 2.7 Which AI Model to Use, and When

**Think of models like modes of difficulty (Easy / Medium / Hard) — not "good" vs. "bad."**

| Provider    | Lightweight (Everyday)                | Medium (Thinking)       | Heavy (Deep Reasoning)                             |
| ----------- | ------------------------------------- | ----------------------- | -------------------------------------------------- |
| **ChatGPT** | 5.5 Instant (free)                    | 5.5 Thinking (Plus/Pro) | 5.5 Pro                                            |
| **Gemini**  | 3.5 Flash (80% of tasks)              | —                       | 3.5 / 4 Pro (for ~20% harder tasks)                |
| **Claude**  | Haiku (batch tasks — emails, tickets) | Sonnet (daily tasks)    | Opus (strategic decisions requiring deep thinking) |

> **Note (as of the session):** A new generation of models called **"Fable"** was mentioned as temporarily out of public domain at the time of recording — described as the highest-thinking tier.

**Decision heuristic:**

- Decisions you make instantly → **Haiku / Instant / Flash**
- Decisions requiring ~5 minutes of thought → **Sonnet / Thinking / Pro (light)**
- Decisions requiring 20–30 minutes of deep strategizing → **Opus / Pro (heavy)**

**Why this matters:** Using an overly powerful model for a trivial task wastes tokens/usage quota — described as "using a nuclear missile to kill a mosquito." Matching the model to the task extends your usable quota significantly.

---

### 2.8 Discovering & Comparing Models

**OpenRouter.ai**

- Aggregates 400+ active AI models from across the industry (not just the "big 3").
- Has a **Rankings** section showing which models are most-used **by category** (Programming, Marketing, Legal, Health, Academics, Technology, etc.) — useful as a proxy for "which model works well for my use case."
- Example rankings cited: MIMO v2.5 (programming/marketing), Gemini 3 Flash Preview (legal), DeepSeek v4 Flash (health/academics), Claude Sonnet 4.6 (technology).

**GetMulti.com**

- Lets you run the _same prompt_ across multiple models (e.g., Claude Opus, GPT-5.5, Grok 4.3, DeepSeek V4 Pro) simultaneously and compare outputs side-by-side.
- Analogy: "Tasting a slice from each pizza place before deciding which pizza is best _for you_" — there is no universal "best" model, only best-for-your-use-case.

---

### 2.9 Reasoning Models & "Effort" Settings

- Reasoning models "think out loud" before answering (e.g., Claude Opus, Gemini Pro, GPT-5.5 Thinking).
- Claude Opus offers **Effort levels**: Low / Medium / High / Extra / Max, plus an **Extended Thinking** toggle for deeper reasoning on complex tasks.
- **Underrated tip:** Open up and read the model's visible "thinking" process — it reveals _how_ the AI is interpreting your prompt, which helps you write better prompts in future.
- **Worked example:** Comparing "Hire a junior analyst" vs. "Build an AI reporting workflow" — Opus produced a full side-by-side comparison (cost, speed, quality, reliability, hidden risks) and recommended a **14-day test experiment** before committing to either option.

---

### 2.10 Claude Skills

- **Analogy:** A chef's recipe / SOP ensures a dish tastes identical every time it's made, regardless of who cooks it. A **Skill** is the AI equivalent — a repeatable, standardized instruction set for a recurring task.
- Claude ships with built-in skills such as `docx` (Word documents) and `pptx` (PowerPoint presentations).
- When you ask Claude to "make a document," it intelligently recognizes it should invoke the relevant skill (similar to how a sous-chef instantly knows what "paneer butter masala" recipe to follow without needing the recipe re-explained every time).
- **Note:** At the time of the session, Skills were available on Claude's paid plans only.

---

## Part B — Building an AI Toolkit (by Deep)

> **Philosophy:** Build a personal "AI toolkit" — a curated set of tools mapped to recurring daily tasks — the same way a chef is protective of and selective about their knives and equipment.

### 3.1 Productivity Tools

**Whisperflow (Voice-to-Text)**

- Converts rough, filler-word-heavy spoken thoughts ("um," "uh," rambling) into clean, well-structured, grammatically correct text — automatically formats into bullet points/structured content where appropriate.
- Described as a **4–5x productivity multiplier** over manual typing.
- Available on Windows and Mac.

**Fireflies.ai (Meeting Notes / Transcription)**

- Joins meetings on your behalf, transcribes them, and has an in-built AI assistant (**"Fred"**) that can answer questions like _"What are the key action items from this meeting?"_ — broken down by owner.

---

### 3.2 Learning Tools

**NotebookLM (Google)**

- Since both NotebookLM and YouTube are Google products, NotebookLM can ingest a YouTube video transcript directly (a limitation many other tools have due to YouTube blocking bot access).
- Use case: Paste a YouTube link → ask NotebookLM to summarize the video in bullet points → generates a **quiz** (adjustable difficulty) from the video content for self-testing.
- **Key advantage:** Answers are grounded only in the actual video content — it does **not hallucinate**.

---

### 3.3 Research Tools

**Claude Research (Deep Research Mode)**

- Accessed via the "+" button inside Claude → "Research."
- Use case demonstrated: Comprehensive company research before a job application — evaluating a target company (1) as a workplace, (2) as an AI-transformation-focused organization, and (3) for AI-implementation-specific roles.
- Runs autonomously in the background for 10–15+ minutes while you continue other work.

---

### 3.4 Interview Preparation

- Use **Voice Mode** in ChatGPT, Claude, or Gemini to simulate a live interviewer.
- Process: Give the AI your target role/context → it asks interview questions → you answer aloud → ask it to **"give me feedback on the answer"** → it critiques for specificity, clarity, and role-alignment, and suggests improved phrasing.

---

### 3.5 Data & Dashboard Interpretation

- Take a **screenshot of any dashboard** you don't understand and upload it to Claude/ChatGPT.
- Prompt technique: Ask for three tiers of explanation — (1) explain it like I'm 5, (2) explain it for a new manager, (3) explain it for a senior leader — each with **3 key observations**: what looks healthy, what looks risky, and what question to ask next.

---

### 3.6 Creative / Marketing Tools

**Fort.ai (AI Product Photography / Ad Generation)**

- Paste an e-commerce product URL (e.g., an Amazon listing) → the tool auto-extracts product details, features, and images.
- Generates product photography, banners, and ad creatives; supports background replacement, object erasing, and scene regeneration (e.g., placing a coffee product in a "cozy kitchen" scene).

---

### 3.7 Distribution & Networking Tools

**Supergrow (LinkedIn Growth)**

- A "post idea generator" for LinkedIn — turns a rough concept (favorite tool, book learnings, a YouTube video) into a ready-to-edit LinkedIn post.

**Happenstance (Referral / Networking Finder)**

- An AI tool built on top of your professional network.
- Use case: _"I want to apply for a role at [Company X]. Find people from my network who can help me."_ — surfaces former/current employees, ranked by relevance (e.g., people who worked there recently, VPs, talent partners) for warm referrals.

---

### 3.8 Data Analysis with AI

- Demonstrated using a Walmart sales dataset from **Kaggle** (store, date, weekly sales, holiday flag, temperature, fuel cost, CPI, unemployment rate).
- Process: Upload the CSV to Claude → prompt it to act as a **senior data analyst reporting to the Head of Sales** → ask for a full dashboard covering sales trends, contributing factors, and decision recommendations.
- **Key insight explained:** Claude writes and executes actual code behind the scenes to perform this analysis (visible if you expand the "thinking"/code panel) — this is why Claude excels at these tasks: **Anthropic optimized Claude heavily for coding first**, which generalized into strong performance on structured analytical tasks (since most complex tasks can be mapped to a coding problem).

---

### 3.9 Tool Discovery Platforms

**"There's An AI For That" (theresanaiforthat.com)**

- A directory/search engine for AI tools, filterable by category (Personal, Work, Relationships, Random) and sub-category (Education, Fashion, Life Coaching, etc.).
- Shows saves, reviews, thumbs up/down, and yearly rankings (2024/2025/2026) to help identify trending/popular tools for any use case.

---

### 3.10 Claude Artifacts

- A Claude feature for generating **interactive mini-applications** directly inside a chat (e.g., a personal India tax-planning calculator built by describing income assumptions in natural language).
- Works on the **free Claude plan**.

---

### 3.11 Capstone Demo: End-to-End Job Application Workflow

This demonstrated **tool orchestration** — chaining multiple AI tools to solve one complex real-world problem (applying for a job at "RazorPay" was used as the example):

| Step                        | Tool Used                                 | Purpose                                                                   |
| --------------------------- | ----------------------------------------- | ------------------------------------------------------------------------- |
| 1. Extract personal profile | **Claude for Chrome** (browser extension) | Pull key resume points from your LinkedIn profile                         |
| 2. Extract job requirements | **Claude for Chrome**                     | Pull key points from the job posting page                                 |
| 3. Company research         | **Claude Research**                       | Deep research on the company as employer / AI maturity / role fit         |
| 4. Build resume             | **Claude (chat)**                         | Combine profile + job description + research → generate a tailored resume |
| 5. Build cover letter       | **Claude (chat)**                         | Use the resume + company research to draft a cover letter                 |
| 6. Find a referral          | **Happenstance**                          | Identify a warm contact to forward the application to                     |
| 7. Mock interview prep      | **Claude / ChatGPT Voice Mode**           | Practice interview questions based on the exact resume and JD             |

> **Core lesson:** "Claude in Chrome" runs on your own Claude subscription tier and can read/extract information from any webpage you're viewing, feeding it directly into your broader AI workflow.

---

## Part C — The Future of Work with AI (by Deep)

### 4.1 AI Agents vs. AI Chat: Delegation vs. Micromanagement

| Mode                          | Description                                                                                                      |
| ----------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| **AI Chat (Micromanagement)** | You explain _how_ to do each step — "do this, then do this, then do this."                                       |
| **AI Agent (Delegation)**     | You specify the _goal_ and let the AI determine and execute the steps ("get this done" — the _how_ is up to it). |

**Benchmark cited:** _GDP-Val_ — a benchmark comparing top-10%-value human work output against AI output in blind human evaluation. As of the session, AI-generated work had, for the first time, begun to **surpass** human-generated work in blind evaluations for certain high-value tasks — suggesting workforce-disruption timelines (e.g., "80% of work handled by AI agents by 2030") may be **underestimates**.

**Historical framing (reassurance):** Every technological shift (electricity, calculators, computers) triggered fear of job loss among incumbents (mill workers, math teachers, accountants) — but ultimately caused _transformation_, not elimination, of work.

---

### 4.2 The AI Generalist Mindset

- **Old model:** Core specialists (e.g., software engineer = high tech skill, low breadth) reporting to a few "ultra-generalists" at the top.
- **New model:** Everyone becomes **"T-shaped"** — deep in one domain, but broad competence across data, product, design, marketing, and business, _powered by AI_. E.g., a "T-shaped tech-powered AI generalist" or "T-shaped product-powered AI generalist."
- **Definition of an AI Generalist:** _A person who solves problems using AI._ Their first question is always: _"Can AI solve this?"_ If yes, they figure out how. If no, that's a valid answer too — not everything should be AI-automated.

---

### 4.3 Career Guidance by Experience Level

| Experience Level                 | Role in the AI Era                                                                                                                                                       |
| -------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **10–20+ years**                 | Manage AI strategy _and_ remain hands-on ("player-coaches") — experience without AI fluency becomes a liability ("a tax"), not an asset.                                 |
| **3–9 years (early/mid-career)** | Build AI-powered solutions and manage AI agent workflows — described as the best window to become "the AI champion" and gain outsized visibility within an organization. |
| **1–3 years / freshers**         | No legacy "baggage" — AI is described as an "unfair advantage" for this group since they can build fluency from scratch without unlearning old habits.                   |

> **Cited insight:** AI doesn't flatten talent distribution — it _amplifies_ it. Those with taste, judgment, and the ability to build stand out even more; mediocrity becomes far more exposed ("AI raises the floor, but the ceiling for excellent people goes even higher").

---

### 4.4 Organizational Architecture in the AI Era

A described future organizational model ("Agent-Human Architecture"):

- **Action Agents** — do the granular execution work.
- **System Architects** — technical or non-technical people who design/build the systems (including AI-agent workflows).
- **Validators** — domain experts who can judge whether AI output is correct/high-quality.
- **Relationship Experts** — ensure humans and agents stay in sync.
- **Chief Accountability Officer** — the founder/leader at the top, accountable for outcomes.

Roles are increasingly described generically as **"member of technical staff"** (used at companies like Meta/Anthropic) rather than by narrow job titles.

---

### 4.5 Opportunities for Entrepreneurs

- **Consulting/AI implementation** is highlighted as a major near-term opportunity — becoming the affordable AI implementation partner for small/medium businesses that cannot afford large consultancies (McKinsey, Infosys, TCS).
- **Single-person or tiny-team "unicorns"** are cited as real, current phenomena (e.g., companies reaching $250M+ run-rate or $400M acquisitions with 1–3 employees), enabled by AI compressing the time between milestones (idea → launch → first million → scale).
- **Advice:** "There has never been a better time to be an entrepreneur" due to drastically reduced time-to-milestone with AI tooling.

---

## Part D — Building AI Bots & Agents (by Webhu Sicinti)

> **Central teaching philosophy:** _"Think WITH AI, not just outsource thinking TO AI."_ Break every problem into smaller steps and orchestrate AI through each one, rather than issuing one vague command and hoping for a good result.

### 5.1 Level 1: Custom GPTs (No-Code Micro-Apps)

- Found under **ChatGPT → "More" → GPTs** (or `chatgpt.com/gpts`).
- These are micro-applications built on top of ChatGPT by other users/companies for specific tasks (e.g., an "Email & Mail Writer" GPT).
- **Building your own (requires a paid ChatGPT account):**

1. Click **Create** → a conversational wizard opens (left panel = chat with the builder; right panel = live preview).
2. Describe the bot in plain language (e.g., _"Build a LinkedIn post generator — I give a topic, you write a viral post"_).
3. The wizard auto-generates a name, profile picture, and instructions, and lets you test immediately in the preview pane.

- **Limitation identified:** A GPT built this way produces generic content — it does **not** replicate the user's personal writing style, and still requires the user to manually think of topics. This limitation motivates Level 2.

---

### 5.2 Reverse-Engineering a Personal Writing Style

**Two-step AI-assisted process to capture someone's authentic writing voice:**

**Step 1 — Build a "Content DNA Playbook":**

- Export/download your own historical content (e.g., a CSV of all past LinkedIn posts with likes/comments/shares).
- Upload this data to Claude with a prompt instructing it to act as an **"expert content analyzer"** and:
- Filter to only pre-AI-era posts (to capture _authentic_, non-AI-assisted writing).
- Analyze hooks, body structure, call-to-action patterns, sentence framing, vocabulary/lexicon, tone, emotional palette, and topic territories.
- Output an extensive **"Content DNA Playbook"** — detailed enough that any competent writer could replicate the style at ~99% fidelity using it.

**Step 2 — Convert the Playbook into a Reusable Prompt:**

- Paste the full Content DNA Playbook back into Claude/an AI in a new conversation.
- Ask it to act as an **"expert prompt engineer"** and convert the playbook into a system prompt that, given any topic, produces a LinkedIn post replicating that exact writing style.

> **Key insight:** Rather than trying to manually describe your own writing style (which is nearly impossible to do precisely — "I write in simple English" is too vague to be useful), get AI to _reverse-engineer_ your style from real samples, then convert that analysis into an actionable prompt.

---

### 5.3 Markdown Prompting Structure (Role / Objective / Context / Instructions / Notes)

A structured prompting format for building robust, production-grade prompts for bots/agents:

| Section          | Purpose                                                                                                                                                                                       |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Role**         | How should the AI behave/who is it? (e.g., "You are an experienced LinkedIn copywriter.")                                                                                                     |
| **Objective**    | What is its core job, every time?                                                                                                                                                             |
| **Context**      | _Why_ the task matters — the stakes. (e.g., "If the writing doesn't match my authentic voice, my audience will notice it's AI-written, engagement will drop, and it will hurt the business.") |
| **Instructions** | The step-by-step "how" — this is where the full Content DNA Playbook detail is embedded.                                                                                                      |
| **Notes**        | Miscellaneous hard constraints that didn't fit elsewhere (e.g., "Never use an em dash character.")                                                                                            |

**Markdown formatting as an "AI signaling language":**

- `#` Single hashtag = Heading 1 (largest, most important)
- `##` Double hashtag = Heading 2 (secondary importance)
- `###` Triple hashtag = Heading 3 (tertiary)
- `**bold text**` = emphasis/critical instruction

> Since AI can't visually "bold" or resize text the way humans intuitively signal importance, markdown symbols are the coded language used to tell the model what matters most.

**Practical workflow:** Rather than hand-writing prompts in this format, simply **paste the format template to Claude/ChatGPT** and ask it to restructure an existing rough prompt into this Role/Objective/Context/Instructions/Notes format.

---

### 5.4 Building It for Free: Claude Projects

- Custom GPTs require a paid ChatGPT plan. The **free-tier equivalent is Claude Projects** (sidebar → Projects → New Project).
- Setup:

1. Create a new project (e.g., "Viral LinkedIn Post Generator").
2. Paste the finalized markdown-structured prompt into **Instructions**.
3. Upload supporting reference files (e.g., the Content DNA Playbook PDF) so Claude can consult them if the prompt alone is ambiguous.

- Once configured, you can simply give it a topic and receive a fully on-brand LinkedIn post — or even ask it to **research trending AI/business news from the last 24 hours and propose 5 topic ideas** before writing the post.

---

### 5.5 Level 3: Building an Autonomous "AI Employee" with Kimi

**Problem with Level 2:** The user still has to manually open the app and prompt it daily. Level 3 removes the human from the loop entirely.

**Tool used: Kimi (kimi.com)** — a free Chinese AI platform with a "Work"/co-work feature comparable to Claude's Cowork, run via a **desktop app** (does not work fully via browser for this use case).

**Step-by-step setup:**

1. Create a **new local folder** on your computer (e.g., "Viral LinkedIn Post AI Employee").
2. Inside Kimi, create a new project and point it at that folder — this grants Kimi read/write access to only that folder (not the whole computer).
3. Copy three files into the folder:

- The Content DNA Playbook
- The finalized markdown prompt
- The historical LinkedIn post analytics CSV (likes/comments/views data)

4. Give Kimi a comprehensive natural-language instruction, e.g.:
   > _"Every day, research the internet for trending topics in AI. Come up with 10 candidate topics. Cross-reference them against my historical post-performance data (the CSV) to identify which 3 topics are most likely to perform well for my specific audience — with a 5-point justification for each. Then, using the prompt and playbook, write all 3 as fully-styled LinkedIn posts. Save the research and the 3 posts as separate files inside a new folder structure (numbered 1, 2, 3…) so I can review them each morning."_
5. Kimi autonomously performs **web research, data analysis (writing its own Python scripts), and content generation** — the entire process took roughly 40–60 minutes for the first run (subsequent runs are faster).
6. **Automation/scheduling:** Once verified working, instruct Kimi:
   > _"Run this exact process automatically every day at 7:00 AM IST and save the output to the folder."_
   > This is confirmed via a **scheduled task/cron job** visible in Kimi's "Scheduled Tasks" panel.

> **Critical caveat:** The scheduled automation **only runs while the host computer remains powered on** (since it runs locally, not on Kimi's cloud servers). Free-tier automations of this kind require an always-on machine.

> **Cost-optimization tip:** Cheaper/open models (e.g., Kimi K2, GLM) can run these agentic workflows for a fraction of the cost of premium models like Opus (~$5/month vs. ~$100/month cited), at the cost of somewhat slower execution.

---

### 5.6 Building a Custom Q&A Agent (Outskill AI Mentor)

**Goal:** Let thousands of learners get instant, accurate answers to session-content questions without a human host having to personally read every chat message.

**Method:**

1. Convert every session recording into a **transcript** using a free tool (e.g., **Happy Scribe**).
2. Write a prompt instructing an AI to act as a teaching assistant that **only answers based on what's actually in the transcript** (preventing hallucination) and to present the answer in an engaging, well-explained way.
3. Test inside **Claude Projects** first (prompt + transcript file uploaded) — validated successfully with real audience questions (e.g., recalling the 5-step tokenization process, and correctly identifying "Happenstance" from an indirect description).
4. **To make it shareable** (since Claude Projects can't easily be shared/deployed publicly to a free-tier audience), the same prompt + knowledge base is rebuilt on a dedicated **agent-building platform**.

**Deploying via Lyzr AI (agent-builder platform):**

1. Go to **Agent Studio → Create Agent**.
2. Fill in three fields (all filled by copy-pasting from the same markdown prompt): **Role**, **Goal**, **Instructions**.
3. Select an underlying AI model (e.g., Anthropic Opus 4.8).
4. Upload the **Knowledge Base** (the transcript file(s)).
5. Test in the built-in **Playground**.
6. Under **Deploy**, copy the **Agent API integration code** — this is the "backend" connector.

**Building the front-end UI with Google AI Studio (free, no-code/vibe-coding):**

1. Describe the desired app in plain language: a ChatGPT-style Q&A interface, styled to match brand colors (e.g., black + neon green), supporting threaded conversation history.
2. Paste in the **Lyzr agent's integration code** so the visual front-end connects to the working backend agent.
3. Google AI Studio auto-generates a functioning, styled web app within minutes.

> **Architecture summary:** Lyzr AI = backend/brain (agent logic + knowledge base) ↔ Google AI Studio = frontend/face (the UI). This "two-tool orchestration" pattern is reusable for almost any custom AI application.

---

### 5.7 Turning an Agent into a Voice Assistant (Vapi)

- **Tool: Vapi.ai** (paid) — turns any prompt + knowledge base into a **voice-based conversational agent**.
- Setup: Create Assistant → set First Message → paste the same system prompt → upload knowledge file(s) → select a voice (built-in voices, or a **custom cloned voice via ElevenLabs** integration for a fully personalized "sounds like me" assistant).
- Demonstrated live: A working voice agent answering spoken questions about session content, in a cloned voice.

---

### 5.8 Claude Design (AI Slide/Design Generation)

_(Demonstrated by Funny Krishna as a bonus segment)_

- Found under **Claude → Design** (beta feature, paid plans).
- **Core concept — Design Systems:** Before generating any content, first create a **Design System** by uploading brand assets (logos, fonts, colors, existing presentations) or connecting Figma — this ensures all future generated output (slides, documents, wireframes, prototypes) stays visually consistent with brand identity.
- **Workflow demonstrated:**

1. Use a deep-research model (e.g., ChatGPT Deep Research) to generate raw research content and slide-by-slide talking points.
2. Paste the full slide content into Claude Design with the correct Design System selected.
3. Claude Design auto-generates a fully branded, consistently styled multi-slide presentation (infographics, timelines, layouts) in ~10–15 minutes.

- **Capabilities:** Prototypes, slide/presentation decks, documents, wireframes, and animations — all governed by the same reusable design system.

---

## Part E — The 5 Levels of an AI Generalist

Webhu Sicinti's proposed roadmap/skill progression (full details provided in an accompanying — not included here — resource document):

### 6.1 Level 1 — Advanced Model Usage

_(Est. 3.5–4 months at 10 hrs/week)_

- **Multi-model access via OpenRouter:** 300+ models available in one place, rather than being limited to ChatGPT/Claude/Gemini alone.
- **Bolt AI:** A unified chat-style interface that connects to OpenRouter, giving access to hundreds of models through one clean UI.
- **Advanced model parameters ("driving in manual, not auto"):** Every model has tunable settings most users never touch:
- `Temperature` — controls randomness/creativity of output
- `Max Tokens` — output length limit
- `Top P` / `Top K` — controls diversity of token selection
- `Frequency Penalty` / `Presence Penalty` — reduces repetition
- `Reasoning Effort` — how much the model "thinks" before answering
- **Ollama:** Run open-source LLMs (Qwen, GPT-OSS, Gemma, LLaMA, DeepSeek-R, etc.) **locally on your own computer** — free forever, works offline, and crucially **fully private** (nothing sent to any company's servers). Can also be connected to Bolt AI for a nicer chat interface than the default terminal-style output.

### 6.2 Level 2 — MCP (Model Context Protocol) & Automation

_(Est. building toward 7 months cumulative)_

**What MCP is:** A protocol that lets an AI model directly **use real-world apps/software** (the ones you already use daily) to complete tasks end-to-end — not just generate text about them.

**Demonstrated MCP integrations:**
| Connected App | Example Automated Task |
|---|---|
| **Zomato** | Research new biryani restaurants matching dietary/calorie goals (cross-referenced with a fitness-tracking app), present 3–4 options, and place the order via COD/UPI |
| **Zerodha Kite** (stock trading) | Pull entire portfolio, research underperforming stocks online, and produce buy/hold/sell recommendations — converted into a live "Bloomberg-style" dashboard |
| **Goose** (open-source computer-use agent by Jack Dorsey's team) | Autonomously reorganize a messy desktop into logical folders; also used to scrape a target Instagram profile via **Apify**, identify top-performing Reels, download them, transcribe them, and rewrite them as LinkedIn posts in the user's own style |
| **Vapi (phone calling)** | Autonomously place a real phone call on the user's behalf to a colleague, deliver a message, and report back a summary of what was discussed |

> **Key theme:** MCP-connected agents can operate your actual software stack (food delivery, brokerage accounts, file systems, phone/calling systems) exactly as a human assistant would — no coding required to set this up.

### 6.3 Level 3 — AI-Generated Audio, Image & Video (Digital Cloning)

_(Est. ~4 months)_

- Demonstrated fully AI-generated marketing/ad videos and social media Reels (script, visuals, voice, and editing largely AI-produced).
- **Personal AI cloning:** Training an AI model on a set of your own photos ("a soul"/likeness model) to generate entirely new, realistic images of yourself in situations you never actually photographed.
- **Business impact cited:** Brand-sponsored content (e.g., paid partnerships) created entirely using an AI-cloned likeness — reported as generating **over ₹2 crore (~$240K+) in revenue over 6 months** from brand deals for AI-generated content featuring a digital clone.

### 6.4 Level 4 — Building Autonomous Agents ("Jerry")

_(Force-multiplier level)_

- **"Jerry"** — a persistent, always-on personal AI executive assistant built on the **Hermes agent framework** (open-source), operating via **Slack**.
- Demonstrated capabilities:
- Drafting and sending emails on command, with minimal instruction (no need to specify email addresses — it infers from context/history).
- Booking calendar events across multiple people automatically.
- **Autonomously initiating and conducting real phone calls** (via Vapi) to follow up on tasks, including self-correcting when it dials a wrong/outdated number by searching email for updated contact info, and **remembering the correction for future use** (persistent memory).
- Attending meetings on the user's behalf and summarizing them on request.
- Retrieving files/documents from local storage and cross-referencing them on request.
- Monitoring cross-platform social media growth/analytics (LinkedIn, YouTube, Instagram, Twitter) and providing daily briefs.
- Analyzing 90 days of business email to diagnose sales-pipeline bottlenecks and draft internal recommendations.
- Using a **browser (via "Comet" browser)** to independently navigate websites (e.g., Y Combinator's company directory), research listings, and generate personalized recommendations based on known user context.

> **Core lesson:** Building an agent like "Jerry" is not primarily a coding exercise — it requires learning **agentic frameworks** (e.g., Hermes, open-source agent orchestration tools) and how to correct/coach an agent conversationally when it makes mistakes, much like managing a real (if occasionally clumsy) employee.

### 6.5 Level 5 — Vibe Coding

_(Est. total Level 1–5 roadmap: ~18 months at 10 hrs/week)_

**"Vibe coding"** = building functional software applications through natural-language prompting, without writing code manually.

Examples cited:

- A custom **CRM** built via **Replit** as a free alternative to a $100,000/year HubSpot enterprise plan.
- A **"Viral Carousel Hunter"** — an app monitoring 119 curated Instagram accounts multiple times daily, ranking trending content to source content inspiration.
- An internal **AI graphic designer tool** for a marketing team to generate creative assets on demand.

---

## 7. Day 2 — Recap & Kickoff

> **Host note:** Day 2 was hosted by **Karthik** (Senior Manager, Growth), filling in for Funny Krishna. Karthik opened with an audience-driven recap of Day 1 before introducing the two Day 2 speakers.

**Quick recap of Day 1 concepts (as summarized live by Karthik):**

- **AI Generalist mindset:** The shift from narrow specialists to broad, AI-powered generalists — someone building a product can also market, design, and ship it themselves using AI instead of hiring separate specialists.
- **"Someone who understands AI better might take your job — not AI itself."** This reframing was repeated as a core message from Day 1.
- **Orchestration:** Being an AI generalist means becoming an orchestrator — managing and coordinating multiple AI agents simultaneously.
- **Model landscape:** 600+ AI models exist (OpenRouter was cited as showing 500+); tools like **GetMulti** let you query several models with one prompt.
- **The 5-step LLM process:** Tokenization → Embedding → Transformer/self-attention → Prediction → Response generation. Tokens were emphasized as **"the currency of AI"** — every message is converted to numeric tokens, and usage/cost is measured in tokens.
- **The "Magic Prompt" (markdown prompting):** Setting Role, Task/Objective, Context, Instructions, and Data/Notes so the LLM has full clarity — contrasted against other named techniques (zero-shot, few-shot, chain-of-thought, tabular, self-refine, diverse prompting).
- **AI Toolkit recap:** Whisperflow (voice-to-text, usable across any app — Slack, Discord, WhatsApp, not just AI chat tools), Gemini (productivity + image generation), Claude, Fireflies (+ its "Fred" assistant), Fort.ai (AI photo shoots), Supergrow (writes _like_ you, not just _for_ you), Perplexity / Gemini / ChatGPT Deep Research, Happenstance (network-of-networks for job searching), Numerous AI (spreadsheet formulas/tables), Suno (AI music).
- **Building Custom GPTs / Gemini Gems:** Setting up name, description, instructions, and a knowledge base (with fallback instructions for out-of-scope questions) — all underpinned by markdown prompting (Role / Objective / Context / Instructions / Notes).
- **The 5 Levels of an AI Generalist** (recapped from Day 1's Webhu Sicinti session) — Day 2 was flagged as going deeper into **Level 4 (agents) and Level 5 (vibe coding)**, plus **automation** using **n8n**.

**Day 2 ground rules reiterated:** take notes/screenshots, use the Zoom AI Companion to catch up on anything missed, don't spam the chat or share external links, be patient with different teaching styles, and — most importantly — **practice** what's taught, since tools are only internalized through hands-on use.

---

## Part F — Vibe Coding (by Dilip)

### 8.1 The Core Philosophy: Blueprint Before You Build

**Correcting a common misconception:** Vibe coding is _not_ "building applications without writing a single line of code." The accurate definition is **"building applications without _you_ writing a single line of code"** — the AI writes the code on your behalf. Someone (or something) always writes code; here, that "someone" is the AI, positioned as **a highly capable developer who just joined your team** and needs proper direction.

**Why people get frustrated with vibe coding — the "Swiggy/Zomato scrolling" analogy:**
People endlessly scroll food-delivery apps without deciding what to eat — not because there aren't enough options, but because they lack **clarity on what they want**. The same happens in vibe coding: people don't have clarity on _what to build_, so the AI cannot deliver a good result no matter how capable it is.

**The specificity principle — the "fussy coffee order" analogy:**
Don't say "make me something interesting" (too vague — like asking a chef to surprise you, when their idea of "interesting" differs completely from yours). Instead, be as specific as the customer who orders: _"a latte with coconut milk, honey instead of sugar."_ Vibe coding requires that same level of precision in your prompts.

**The "half-built house" analogy — why blueprints matter:**

- **At the design/blueprint stage** of building a house, you can make unlimited changes cheaply and easily.
- **Once construction has started** (pillars up, ceiling set), major structural changes (e.g., "swap the bedroom and living room") become extremely costly and disruptive.
- **Lesson:** Invest heavily in the **blueprint stage** before any actual building/generation happens. A rock-solid blueprint makes the build phase fast and clean; a weak blueprint leads to constant, costly rework.

### 8.2 Two Build Paths: Website vs. Web Application

| Path                | Description                                                                                                                                                                                     |
| ------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Website**         | Primarily front-end — informational/marketing pages, no complex backend logic. Covered via two sub-cases: (1) improving an existing site, (2) building a new site from scratch.                 |
| **Web Application** | Has both a front end _and_ a back end (database, server logic, APIs) — e.g., an app with user data, AI processing, and persistent state. Covered via a full build of an AI calorie-counter app. |

### 8.3 Use Case 1: Improving an Existing Website — The C2R2 Framework

**First, define what "improving a website" actually means (beyond cosmetics).**
Surface-level answers (better UI/UX, SEO, images) are **cosmetic**. The deeper question is: _what is a website actually for?_ Answer: **capturing user details** (email/phone) and/or **getting the user to buy/sign up for something** — both of which are **measurable**. The core mantra: **"What gets measured, gets improved."**

**Key metric — Conversion Rate:**

> If out of 100 visitors, 5 people sign up for something, that's a **5% conversion rate**. The process of increasing this (e.g., from 5% to 10%) is called **Conversion Rate Optimization (CRO)**.

**The C2R2 Framework** (Dilip's blueprint process for improving any existing website):

| Step            | Action                                                                                                                                                                                                                  | Tool(s) Used                                                                                              |
| --------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------- |
| **1. Capture**  | Take a full-page screenshot of the current website                                                                                                                                                                      | **GoFullPage** (free Chrome extension)                                                                    |
| **2. Critique** | Feed the screenshot to an LLM and ask it to act as a **Conversion Rate Optimization expert**, critiquing design, copy, UI/UX, and elements against your specific conversion goal (e.g., "take sign-ups from 5% to 10%") | **Claude Opus** (recommended for depth — Sonnet is faster but shallower for high-stakes design decisions) |
| **3. Redesign** | Ask the same AI to incorporate its own critique and output a **complete redesign in markdown** — including new copy and brand elements                                                                                  | Claude Opus                                                                                               |
| **4. Rebuild**  | Convert the markdown redesign into a **concise, copy-paste-ready prompt**, then feed it into a no-code builder to generate the actual working site                                                                      | **Google AI Studio** (free) or **Lovable** (paid, credit-based)                                           |

**Underrated tip repeated throughout the session:** Always read the AI's **visible "thinking" process** — it reveals how the model is interpreting your prompt, letting you course-correct in your _next_ prompt if it's drifting off-track.

**Practical execution notes:**

- **Lovable pricing model:** Credit-based. Roughly **1 credit ≈ $0.25 (~₹25)**. The demo used a $25/100-credit plan. A full website rebuild + refinements used roughly 6–7 credits (~$1.50/₹150).
- **Google AI Studio** is free but requires connecting to Google Cloud (GCP) for hosting/publishing — a more technical, multi-step process compared to Lovable's one-click publish, which is optimized for non-coders.
- **Vibe coding tip:** Build the **first version expansively** (no restrictions) — only add constraints and refinements in follow-up prompts.
- If you have an existing site with elements you want preserved, **explicitly state what NOT to change** — otherwise the AI may treat the task as a from-scratch rebuild.
- After generation, placeholder content (e.g., "Placeholder placeholder") can be filled in by prompting: _"Scrape [website] and fill the placeholders."_
- Direct on-canvas editing is supported — click an element and describe the change (e.g., replacing "co-founder" with "founding/early team member") without needing a new full prompt.
- **Custom domains:** Both platforms support connecting your own domain once ready to go live.

### 8.4 Use Case 2: Building a New Website From Scratch

**Step-by-step blueprint process (demonstrated using a fictional premium gym brand, "Constant"):**

1. **Gather reference websites:** Use **Perplexity** to research and surface 2–3 existing websites (ideally competitors/analogous brands) that match your desired positioning and aesthetic (e.g., "aesthetic, premium, invite-only gyms in India and abroad").
   > **Rule of thumb:** Limit references to a **maximum of 2** — more references create conflicting design signals ("too many cooks spoil the broth").
2. **Capture references:** Screenshot the 1–2 chosen reference sites with **GoFullPage**.
3. **Brief the AI like a designer:** Upload the screenshots to **Claude** and describe the brand positioning, target customer, anti-customer, tone, and constraints in free-flowing natural language (dictation-style is fine — no need for a polished prompt). Explicitly invite Claude to **ask clarifying questions** — this simulates a real client-designer conversation (e.g., Claude asked about brand feel, target city, membership screening criteria, and suggested brand names like "Constant," "Bedrock," "Nucleus").
4. **Build a Design System:** Use **claude.ai/design** to generate a full visual design system (colors, typography, layout principles) from the brand brief — independent of, but informed by, the reference sites.
5. **Generate the full website copy in markdown**, based on the design direction.
6. **Rebuild in a no-code tool:** Download the Claude-generated prototype/markdown file and upload it into **Lovable**, asking it to build a polished, working version following the established design palette.
7. **Refine iteratively:** Continue prompting for section-by-section changes, generating a **Product/Design system view** you can browse (Home Page, Design Systems tab, etc.) before finalizing.

> **Consistent theme:** ~80% of effort goes into the blueprint (research, positioning, design direction); the actual "build" step becomes fast and low-friction once the blueprint is solid.

### 8.5 Understanding Front End vs. Back End (The Movie Analogy)

To prepare for building a full web _application_ (not just a website), Dilip explained the front-end/back-end split using a **movie production analogy**:

| Movie Production Concept                                                   | Software Equivalent                                                             |
| -------------------------------------------------------------------------- | ------------------------------------------------------------------------------- |
| The final 2–3 hour movie you watch in the theater                          | **Front end** — the user-facing part of the product (what you see/touch/click)  |
| Assistant directors & production controllers coordinating actors/schedules | **APIs** — maintain sync between front end and back end                         |
| The 150–200 hours of raw shot footage stored in a vault                    | **Database** — where raw information/data is stored                             |
| The editing team turning raw footage into the final cut                    | **Server** — processes/operates on the database and sends data to the front end |
| Outsourced VFX studios (e.g., Industrial Light & Magic)                    | **Third-party services** — e.g., plugging in an AI model/API into your product  |

> **Key takeaway:** A website blueprint only needs front-end thinking. A web _application_ blueprint needs both front-end AND back-end thinking — making it inherently more complex to plan.

### 8.6 Use Case 3: Building a Full Web Application From Scratch

**Product built live:** An **AI-powered calorie counter application** ("Nourish AI").

**Step-by-step build process:**

1. **Brainstorm features:** Ask the AI (e.g., Claude) to propose a broad list of possible features for the app concept — core features and "delight" features.
2. **Define the MVP (Minimum Viable Product):**
   > **House-occupancy analogy:** To occupy a house, you don't need finished furniture or a fully stocked kitchen — you need bare-minimum functioning electricity, plumbing, and basic furniture. Everything else can be added _after_ move-in. Similarly, an MVP = the **bare minimum feature set** that lets a user get real value and start using the product; more features are added iteratively afterward.

- Ask the AI to prioritize features into a **table, ranked by priority**, and to always **request multiple options** (e.g., "give me at least 4–5 options") rather than accepting a single narrow suggestion.
- **Features chosen for the calorie counter MVP:**
- **Photo Meal Logger** — snap/upload a food photo → AI estimates the meal and calorie count.
- **Daily Calorie Estimate/Summary** — running total of calories consumed.
- **"Is This Worth It?" Advisor** — a conversational feature where the user describes a planned food choice (e.g., "I'm planning pizza tonight") and the AI advises whether it fits their remaining calorie budget, with healthier alternative suggestions.

3. **Pick a visual design system:** Use **superdesign.dev** — a gallery of pre-built design styles/aesthetics (e.g., "Super Green," an organic style well-suited to a food/health app). Each style has a **"copy the full prompt"** button that outputs the exact prompt needed to replicate that visual style in a no-code builder.
4. **Generate a PRD (Product Requirements Document):**
   > A PRD is the formal document a product manager gives to engineers, specifying exactly what must be built. In this workflow, **Claude plays the product manager** and **Lovable plays the engineer** — Claude is prompted (with the chosen features + design prompt) to output a comprehensive PRD in markdown, covering target users, feature specs, design system, and technical architecture.
5. **Review and simplify the PRD:** Since the user may be non-technical, explicitly state that upfront (_"I am non-technical, keep the architecture simple"_) and request simplifications — e.g., **removing login/authentication for the initial build** (with a note to add it back later) to speed up early testing.
6. **Convert the PRD into a build prompt:** Ask the AI to _"convert the PRD to a single copy-and-paste prompt I can use in Lovable"_ — the PRD is for **thinking**, the distilled prompt is for **building** (all rationale/"why" content is stripped out, leaving pure instructions).
7. **Enable managed backend infrastructure:** Specify use of **"Lovable Cloud"** so Lovable handles the database and AI/LLM integration internally — removing the need to manually source and manage your own API keys.
8. **Build in Lovable:** Paste the final prompt in and let it generate the full working application (front end + database + AI integration).

### 8.7 Iterative Feature Building & Error Handling

**Golden rule:** Add features **incrementally — a maximum of ~2 at a time.** Attempting to implement a long laundry list of features simultaneously risks breaking previously working functionality and creates a debugging nightmare.

**Demonstrated iteration cycle:**

1. Add a "quantity adjustment" feature (e.g., "0.5x" a meal portion) and a "type instead of photograph" logging option.
2. Add a "remove items from log" / "reset" capability.
3. Encountered a real **404 error** when testing — used as a teaching moment: simply describe the error (or **take/attach a screenshot directly inside the builder**, e.g., _"take a screenshot… something is off"_) and let the AI diagnose and fix it (in this case, restarting the server resolved it).
4. Enhanced the "Is This Worth It?" advisor to proactively suggest **healthier alternative meals** instead of just approving/rejecting a choice.

**Version control / rollback:** No-code platforms like Lovable maintain a full history of prior application versions. If a new feature breaks something, you can **instantly revert to any previous version** — a critical safety net for iterative, prompt-driven development.

### 8.8 Publishing, Security, and Scaling

- **Connectors/integrations:** Lovable offers a growing ecosystem of plug-in connectors — e.g., **Stripe** (payments), **Zoho Books** (accounting), **Google Sheets** (lead capture), **Resend** (transactional emails), **Perplexity** (AI-powered search) — extending app functionality without custom code.
- **Exporting code:** For technical users who want to self-host, Lovable allows **downloading the full generated codebase**.
- **⚠️ Critical security warning:** Non-technical builders will not inherently know about security vulnerabilities in AI-generated code. **Always run the built-in security scan before publishing an app publicly**, and ask the AI to _"fix all"_ flagged issues. Explicitly-designed gaps (e.g., intentionally omitted authentication for early testing) can be resolved later by simply prompting _"add authentication."_
- **Auto-scaling:** Lovable automatically scales infrastructure up/down based on real user traffic — but higher usage consumes more credits accordingly.

### 8.9 Vibe Coding Platform Comparison

| Platform                         | Cost Model                         | Best For                                                                                                                                                             |
| -------------------------------- | ---------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Lovable**                      | Paid, credit-based (~$0.25/credit) | Non-technical users; easiest end-to-end publishing experience                                                                                                        |
| **Google AI Studio**             | Free                               | Budget-conscious builders; hosting requires a separate Google Cloud setup (more technical)                                                                           |
| **Replit**                       | —                                  | Technical/developer-leaning users who want to go deeper into the underlying code                                                                                     |
| **Emergent, Base44, and others** | —                                  | Comparable alternatives — Dilip stresses that choosing between them is "like choosing your favorite food" — largely personal preference; **most do a "decent job."** |

> **Reframing "which tool is best":** Just as no single restaurant/cuisine is objectively "the best" for everyone, no single vibe-coding platform is universally best — the UI differs, but the underlying workflow (build a strong prompt → paste it in → iterate) is consistent across all of them.

### 8.10 Dilip's Closing Advice: "Be the Surfer"

- **Start small, start slow.** Don't attempt to build a full enterprise CRM (e.g., "a Salesforce competitor") as a first project — build a small, **personal tool that solves one specific problem you have.**
- **On the "future of coding":** Citing Anthropic's own Claude Code team, Dilip noted that **90–95% of their own code is now written by AI agents**, not typed manually — reinforcing that the future skill is **directing/guiding AI**, not manual coding.
- **The "surfer on the beach" analogy (from an IIT professor):** Most people stand on the shore, too hesitant to enter the water, waiting for the wave to simply wash over their feet. A few people paddle out and **learn to ride the wave before it crashes** — and by the time it reaches shore, everyone else looks to _them_ for guidance on how to ride it. **The AI wave is happening right now — very few people are riding it yet.** Whether you learn with Outskill, alone, or elsewhere doesn't matter — the point is to **start now**, because the "first-mover" advantage in AI fluency is currently wide open but will not stay that way.

---

## Part G — AI-Powered Automation with n8n (by Divij)

### 9.1 What Are Automations? Traditional vs. AI-Powered

**Automations are not new** — technologies like **RPA (Robotic Process Automation)** have existed for years, historically requiring hand-written logical code (e.g., `if X, do Y` conditions in a programming language like Python). What has changed since ~2022 is:

1. **Accessibility:** No-code/low-code drag-and-drop tools have made building automations dramatically simpler — no programming required.
2. **Intelligence:** AI can now be embedded _inside_ automations, replacing rigid, purely rule-based logic with adaptive, judgment-based decision-making.

| Automation Type                       | How Decisions Are Made                                                                                                                                                                                                          |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Traditional/Rule-based Automation** | Fixed logic: `if X, do Y` — every path is explicitly pre-programmed by the builder.                                                                                                                                             |
| **AI-Powered Automation**             | The builder provides tools/access (e.g., an inbox, an LLM API, a social platform) and a **goal**; the **AI agent decides the best sequence of steps** to achieve it — judgment is now AI-driven rather than fully pre-scripted. |

**Illustrative example given:** A daily task of reading a Medium blog, summarizing it, and posting to LinkedIn at 9 AM — fully rule-based and automatable with fixed steps (schedule trigger → fetch article → summarize → post).

**Rule of thumb for identifying automatable tasks:**

> _"If you think you can do that task yourself, and it's possible without you changing a lot of logic each time, it can very likely be automated."_

**Everyday automation examples cited:**

- **Instagram "comment X to get a DM"** bots (triggered by a specific comment on a post).
- **WhatsApp Business auto-replies** (instant acknowledgment messages, catalogs, or full conversational bots).

### 9.2 The Three Pillars of Any Automation: Trigger → Logic → Action

Every automation, on any platform (n8n, Zapier, Make.com, or any future tool), is built from exactly **three types of building blocks**:

| Component      | Definition                                                                                                            | Examples (from n8n)                                                                                                                                                                                                                                                                                                                            |
| -------------- | --------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **1. Trigger** | The "starting gun" — a state change/event that kicks off the workflow.                                                | **On App Event** (e.g., new Gmail message received, new Slack message, new Google Sheets row) — _most widely used_; **On Schedule** (e.g., every day at 9 AM); **On Form Submission** (a form is filled/submitted); **On Webhook Call** (an external API call hits your workflow); **Manual Trigger** (click-to-test only, not for production) |
| **2. Logic**   | Data transformation, filtering, conditional branching, or looping — determines _how_ data flows through the workflow. | **If/Else conditions** (branching true/false paths); **Loops** (iterating over rows/items, e.g., processing every row of a spreadsheet); **AI logic nodes** (AI Agent, Text Classifier, Sentiment Analysis, Summarization, Q&A Chain, Information Extraction)                                                                                  |
| **3. Action**  | "What happens next" — the actual task performed in a connected app.                                                   | Gmail: add a label, delete a message, reply, send, create draft; Slack: send a message, archive a channel; Notion: create/append a page; Google Drive: copy/delete a file                                                                                                                                                                      |

> **Practical framing:** Dissect _any_ automation you encounter and you will always be able to map it onto exactly these three buckets — Trigger, (optional) Logic, Action.

### 9.3 Where Automation Excels vs. Where It Struggles

**Automations excel at:**

- Repetitive, high-volume tasks
- Moving data between apps
- Summarizing/classifying content (now AI-enabled — this "intelligence layer" simply wasn't possible in pre-AI automation tools)
- Scheduled, time-based jobs, notifications, and alerts

**Automations struggle with:**

- **High-judgment decisions** that require nuanced human discretion
- **Human-in-the-loop requirements** (tasks that genuinely need a person to review/approve)
- **Constantly changing / open-ended edge cases** — e.g., if you try to let an AI freely create _new_ categories on the fly rather than choosing from a fixed, well-defined set, it introduces unpredictable risk. **Safer design:** define a small number of well-understood categories (based on known historical patterns) plus a catch-all **"Other"** bucket, rather than letting the AI invent categories dynamically.

### 9.4 No-Code Automation Platform Landscape

| Platform           | Cost                                              | Open Source? | Notes                                                                                                                                                                    |
| ------------------ | ------------------------------------------------- | ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **n8n**            | Free (self-hosted) / Cloud with 14-day free trial | ✅ Yes       | Most flexible and powerful; large open-source community with 7,000+ shareable templates; can be self-hosted on your own or company servers for full data control/privacy |
| **Zapier**         | Paid                                              | ❌ No        | Easiest to start with, but limited nodes/options                                                                                                                         |
| **Make.com**       | Paid (browser-only)                               | ❌ No        | Broader than Zapier but still limited vs. n8n; no self-hosting                                                                                                           |
| **Power Automate** | Paid (Microsoft ecosystem)                        | ❌ No        | Native to Microsoft 365 environments                                                                                                                                     |
| **Copilot Studio** | Paid (Microsoft ecosystem)                        | ❌ No        | Microsoft's equivalent to n8n-style workflows, relevant when a company restricts external tools like n8n for data-security reasons                                       |

**Why n8n was chosen for teaching:** It is **free, open-source, self-hostable** (giving full data-privacy control by keeping automations on a company's own servers), and has by far the **richest community template library** (7,000+ ready-made workflows) to learn from and build on.

**Local installation (free, unlimited use):**

```
npm install n8n
npm run build
npm link
n8n start
```

Requires Node.js installed (n8n will prompt for it if missing). Runs at `localhost:8000` (or similar port) instead of the cloud URL — identical interface, but self-hosted and completely free with unlimited workflows.

### 9.5 Understanding APIs (The Waiter Analogy)

**API = Application Programming Interface** — the "bridge" that lets two separate software systems communicate with each other.

> **Analogy:** An API is like a **restaurant waiter**. You don't walk into the kitchen and talk directly to the chef — you tell the waiter your order, the waiter relays it to the kitchen, and brings your food back once it's ready. In software, your application sends a **request** via an API, the API relays it to the target server, and returns the **response**.

**Real-world example:** Booking a movie ticket via Paytm, District, or BookMyShow — if you book seat 10 on one app, it becomes unavailable on all the others, because every platform is connected to the same underlying cinema-chain API (e.g., PVR's booking system).

**Why this matters for automation:** To connect an automation to any LLM (OpenAI, Anthropic, Gemini) or third-party app (WhatsApp, Twitter, etc.), you need an **API key** for that service.

**OpenRouter (recap from Day 1):** Described here again as a **"unified interface for LLMs"** — a single API key that lets you access many different providers' models (Anthropic, OpenAI, Google, DeepSeek, etc.) without managing separate keys for each.

> **Cost note:** With the exception of some free-tier allowances (e.g., **Google Gemini API**, which offers meaningful free usage), **most LLM API keys are paid** and require a minimum account balance (e.g., ~$5) to function.

### 9.6 Planning Before Building: The Whiteboard Method

Before touching n8n, **sketch the workflow on paper/whiteboard first**:

1. Identify your **trigger block** (e.g., "New email arrives in Gmail inbox").
2. Identify what information you'd naturally check to make a decision manually (e.g., sender email, subject line, email body).
3. Identify the **intelligence layer** needed (an AI model to classify/understand the content).
4. Define your **classification categories** based on real historical patterns (e.g., Customer Inquiry/Support, Mentoring Request, Newsletter, Promotional).
5. Map each category to a specific **action** (e.g., reply, delete, label, notify).

### 9.7 Full Build Walkthrough: Automated Gmail Customer Support Triage

**Business case (inspired by a real brand, referenced as "Nykaa"):** A company receiving 5,000+ support emails/day wants them automatically triaged (e.g., ~35% are counterfeit-product complaints, others are billing/invoice issues, etc.).

**Step-by-step build in n8n:**

1. **Trigger:** Add **On App Event → Gmail → "On Message Received."** Connect your Gmail account (OAuth sign-in), and configure the **poll time** (how frequently n8n checks for new mail — e.g., every minute) and max emails fetched per check.
2. **AI Classification Node:** Add an **AI → Text Classifier** node (or an AI Agent). Feed it the email's **From**, **Subject**, and **Body** fields (dragged and dropped from the trigger's output — no manual typing required, since n8n exposes all upstream data dynamically).

- Requires an underlying **LLM connection** (e.g., via **OpenRouter**, using a model such as GPT-4.1 Mini for cost efficiency) — set up once via an API key credential.
- Define **categories** with clear, detailed natural-language descriptions for each (e.g., _"Customer Inquiry/Support"_, _"Mentoring Request"_, _"Newsletters"_, _"Promotions/Subscriptions"_) — the richer and more specific the description, the more accurately the AI classifies.

3. **Branching Logic (If/Else):** For newsletters, add a condition checking the sender's domain against a trusted allow-list (e.g., keep emails from `deeplearning.ai` or a specific "Alpha Signal" domain; delete anything else in that category) — combined with **OR** logic across multiple conditions.
4. **Actions per branch:**

- **Promotional emails →** Gmail: **Delete Message** action.
- **Customer Inquiry emails →** Gmail: **Create Label** (one-time setup; instructed to gracefully "continue" if the label already exists rather than erroring out) → **Add Label to Message** → then a second **AI Agent** node drafts a **personalized reply**, using a detailed **system prompt** describing the company, its services, operating hours, and tone — with the **user prompt** populated dynamically from the incoming email's subject/body.
- **Reply action:** Gmail → **Reply to Message** (or **Create Draft**, for a human-review-first workflow) — inserting the AI-generated reply text.

5. **Prompt refinement / debugging demonstrated live:** Iteratively tightened the AI reply-drafting prompt to fix issues such as: pulling the customer's name correctly, omitting an unwanted auto-generated subject line, avoiding markdown symbols (asterisks/hashtags) in plain-text email replies, and enforcing a consistent sign-off ("Thanks and regards — [Company] Support Team" instead of a generic "Best regards").
6. **Testing before publishing:** Workflows can be run manually (via the **Execute** button) at every node during the build phase; **Executions** tab logs every run's timestamp and outcome for monitoring/debugging.
7. **Publish:** Clicking **Publish** activates the workflow to run **24/7 autonomously** on the configured schedule/trigger, with no further manual intervention needed. **Unpublishing** stops it just as easily.

### 9.8 Extending the Workflow Further

The base workflow can be extended indefinitely by adding more branches, actions, or tools, e.g.:

- **Slack/WhatsApp notifications:** Alert a human team member whenever a high-priority customer inquiry is triaged and answered.
- **Web search tools attached to the AI Agent:** e.g., **Tavily API**, **Serper API**, or **Brave Search API** — letting the agent look up additional real-time context (such as researching the sender's company) before drafting a reply. (Discovery tip: simply ask ChatGPT _"what free or paid web-search tools can I connect to my AI agent?"_ to find current options.)

### 9.9 Learning for Free: Templates & Local Hosting

- **n8n Template Library:** A vast public community repository (7,000+ workflows) accessible via **n8n.io/workflows** — filterable by category (e.g., "sales," "marketing"). Templates can be **copy-pasted directly into your own n8n canvas** (Ctrl+C on the template page → Ctrl+V into a new n8n workflow), then simply re-authenticate your own credentials for each connected app.
- Example templates cited: an automation that reviews your calendar each morning, researches upcoming meeting attendees'/companies' latest news, and emails you a personalized briefing; a "summarize YouTube video from transcript" workflow.
- **Free LLM access for practice:** Use **Google AI Studio** to generate a **free Gemini API key** (in place of a paid OpenAI/OpenRouter key) for connecting the AI nodes in your n8n workflows at no cost.
- **Free local hosting:** Installing n8n locally (see §9.4) removes the 14-day cloud trial limit entirely and allows **unlimited free workflow building** for practice.

---

## Part H — Program Options, Bonuses & Closing

### 10.1 Outskill Program Tiers

| Program                     | Duration / Format                                        | Notes                                                                                                                                                                                                                                                                                                                                                                                                             |
| --------------------------- | -------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Mastermind** (this event) | 2 days, live only                                        | Free; no recordings originally promised (later provided as a bonus — see below); certificate provided on completion                                                                                                                                                                                                                                                                                               |
| **Accelerator Program**     | 14-day intensive "mega sprint" + ongoing weekly sessions | Covers the full AI-generalist curriculum hands-on, including breakout rooms with mentors, daily CSAT tracking, and micro-projects each day. A parallel **Engineering-focused Accelerator track** exists for more technical learners (includes a short Python "base camp" refresher for those without prior Python experience — noted as generally easier to pick up if coming from another language like Java).   |
| **Fellowship Program**      | 6 months, weekly weekend live sessions                   | Deeper, longer-form version of the Accelerator; NSDC-linked certification; live (not recorded) because curriculum is continuously updated as AI evolves; standard price ~₹3.5 lakh (India) / ~$10,000 (international, due to purchasing-power-parity pricing), with potential scholarship discounts (e.g., ~₹1,95,000 cited) for selected applicants and flexible no-extra-cost EMI options for a limited period. |

**Guidance repeated for students:** Students were explicitly advised **not** to enroll in the paid programs — they have the time and bandwidth to self-learn using the free roadmap and public resources instead. The paid programs are positioned primarily for working professionals/entrepreneurs who lack the time to self-research.

**On live-only delivery:** Both the Fellowship and (originally) the Mastermind avoided static recordings deliberately, reasoning that **known availability of a recording increases procrastination and reduces live engagement/retention** — though see §10.2 for the reversal on Mastermind recordings specifically.

### 10.2 Bonuses, Certificates & Referral Program

- **Recordings (a deliberate "white lie" revealed at the end):** Despite repeated claims throughout both days that no recordings would be provided, the hosts revealed this was an intentional white lie to maximize live attendance and engagement — recordings **were** provided after all, released within **72 hours** (processing time required by Zoom) via the shared Google Drive resource link.
- **Resource Drive:** A single shared Google Drive link consolidated: session notes, hands-on workbooks, the full "AI Generalist Roadmap" (mapped across the 5 levels discussed on Day 1, with curated links such as Anthropic's prompt engineering guide and model release notes), and (later) session recordings.
- **Certificate Generator:** A dedicated tool was shared for generating a personal completion certificate — explicitly restricted to personal use only (not for redistribution).
- **Referral / Challenge Program:** A gamified referral system where learners earn points by referring friends and completing tasks (e.g., posting an AI "pledge" on LinkedIn, writing a graduation post, creating an AI-generated YouTube video summary, building a simple web app with Claude/Replit). Points accumulate toward potential prizes (laptop, iPad, phone) and course-access rewards.
- **Bonus live session announced:** In response to strong audience demand (via chat polling), an **additional live session on AI image and video generation** was announced for the following evening (7:00 PM IST) — presented as an unplanned, on-the-spot bonus beyond the original 2-day scope.

---

## 11. Glossary of Tools Mentioned

| Tool                                   | Category                     | Purpose                                                                                                                                                              |
| -------------------------------------- | ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ChatGPT / GPTs**                     | LLM / No-code bots           | General chat + custom micro-app builder                                                                                                                              |
| **Claude (Sonnet, Opus, Haiku)**       | LLM                          | General chat, coding, reasoning, projects, artifacts, design                                                                                                         |
| **Gemini**                             | LLM                          | General chat (Flash/Pro tiers)                                                                                                                                       |
| **Whisperflow**                        | Productivity                 | Voice-to-text with auto-cleanup/structuring                                                                                                                          |
| **Fireflies.ai**                       | Productivity                 | Meeting transcription + AI Q&A assistant ("Fred")                                                                                                                    |
| **NotebookLM**                         | Learning                     | YouTube/document summarization, quiz generation                                                                                                                      |
| **Superprompts**                       | Prompt management            | Storing/organizing reusable prompts                                                                                                                                  |
| **OpenRouter.ai**                      | Model discovery              | Access to 400+ AI models + usage rankings by category                                                                                                                |
| **GetMulti.com**                       | Model comparison             | Run one prompt across multiple models simultaneously                                                                                                                 |
| **Fort.ai**                            | Marketing/Creative           | AI product photography and ad generation                                                                                                                             |
| **Supergrow**                          | Distribution                 | LinkedIn content idea generator                                                                                                                                      |
| **Happenstance**                       | Networking                   | AI-powered referral/network search                                                                                                                                   |
| **"There's An AI For That"**           | Discovery                    | Directory/search engine for AI tools                                                                                                                                 |
| **Kimi (kimi.com)**                    | Agent platform               | Free autonomous "AI employee" with local file/computer access and scheduling                                                                                         |
| **Lyzr AI**                            | Agent builder                | No-code backend agent creation with knowledge base + deployable API                                                                                                  |
| **Google AI Studio**                   | Vibe coding                  | Free no-code front-end/app builder                                                                                                                                   |
| **Vapi.ai**                            | Voice AI                     | Voice agent creation, phone calling automation                                                                                                                       |
| **ElevenLabs**                         | Voice cloning                | Custom/cloned voice generation                                                                                                                                       |
| **Ollama**                             | Local LLM                    | Run open-source models locally, free & private                                                                                                                       |
| **Bolt AI**                            | Unified interface            | Chat UI connecting to OpenRouter + Ollama with advanced parameter control                                                                                            |
| **Goose**                              | Computer-use agent           | Open-source agent for autonomous computer/file/browser tasks                                                                                                         |
| **Apify**                              | Web scraping                 | Scraping tool connected via MCP for social media data collection                                                                                                     |
| **Zomato / Zerodha Kite**              | MCP integrations             | Real-world app automation examples (food ordering, stock trading)                                                                                                    |
| **Happy Scribe**                       | Transcription                | Converts video/audio into text transcripts                                                                                                                           |
| **Y Combinator Companies Directory**   | Research                     | Startup idea research source                                                                                                                                         |
| **GoFullPage**                         | Web capture                  | Free Chrome extension for full-page website screenshots                                                                                                              |
| **Claude Opus/Sonnet**                 | LLM (design/critique)        | Used for website critique, redesign, and copywriting in vibe coding workflows                                                                                        |
| **claude.ai/design**                   | Design system builder        | Generates full brand/design systems (colors, typography, layout) from a brief                                                                                        |
| **Google AI Studio**                   | Vibe coding (also see Day 1) | Free no-code app/website builder; also source of free Gemini API keys                                                                                                |
| **Lovable**                            | Vibe coding                  | Paid, credit-based no-code app builder with managed backend ("Lovable Cloud"), connectors (Stripe, Zoho Books, Resend, etc.), version history, and security scanning |
| **Replit**                             | Vibe coding                  | Developer-leaning no-code/low-code app builder                                                                                                                       |
| **Emergent / Base44**                  | Vibe coding                  | Alternative no-code app-building platforms                                                                                                                           |
| **superdesign.dev**                    | Design reference             | Gallery of pre-built UI design styles with copyable prompts                                                                                                          |
| **n8n**                                | Automation platform          | Free, open-source, self-hostable workflow/automation builder (cloud version has 14-day trial)                                                                        |
| **Zapier**                             | Automation platform          | Paid, beginner-friendly automation platform with limited nodes                                                                                                       |
| **Make.com**                           | Automation platform          | Paid, browser-based automation platform, broader than Zapier                                                                                                         |
| **Power Automate / Copilot Studio**    | Automation platform          | Microsoft-native automation/agent-building tools                                                                                                                     |
| **OpenRouter**                         | Unified LLM API              | Single API key providing access to many LLM providers (also see Day 1)                                                                                               |
| **Tavily / Serper / Brave Search API** | Web search tools             | Connectable search tools for giving AI agents real-time internet access                                                                                              |
| **Fireflies "Fred"**                   | Meeting AI assistant         | In-meeting Q&A assistant (recap from Day 1)                                                                                                                          |

---

## 12. Key Takeaways & Action Items

1. **Understand the mechanics, not just the interface.** Knowing tokenization → embeddings → self-attention → prediction → generation makes you a "Version 2 driver" — someone who can diagnose and improve AI output, not just consume it blindly.
2. **Context engineering beats prompt engineering.** Always supply Identity, World/Context, Task, Examples, and Boundaries — treat AI like a brilliant new hire who knows nothing about your specific situation until you tell it.
3. **Match the model to the task's difficulty**, not the other way around — this conserves usage limits and produces better-fit results.
4. **Think WITH AI, not just delegate blindly to it.** Break big problems into smaller, sequential sub-tasks and orchestrate multiple tools/models together (this is called _orchestration_).
5. **Reverse-engineer before you generate.** To replicate a personal style (writing, brand, etc.), first get AI to analyze real historical examples into a detailed "playbook," then convert that playbook into a reusable system prompt.
6. **Use markdown structure (Role / Objective / Context / Instructions / Notes)** for any serious, reusable AI prompt or agent build.
7. **MCP (Model Context Protocol) is the bridge from "AI that talks" to "AI that acts"** — connecting AI to real apps (food delivery, brokerage, calendars, email, phone systems) is what enables true automation.
8. **Building agents is a skill, not a coding requirement.** No-code platforms (Kimi, Lyzr, Google AI Studio, Vapi) let non-developers build fully functional autonomous employees and voice assistants.
9. **Privacy matters.** For sensitive data, use locally-run models (via Ollama) instead of cloud services — private, free, and works offline.
10. **The AI Generalist career path** (Level 1 → 5: Advanced Models → MCP/Automation → Media Generation → Autonomous Agents → Vibe Coding) is estimated at ~18 months of consistent (10 hrs/week) effort to progress through fully — but even partial progress compounds quickly into real career/business advantage.
11. **Practical career move:** Document 2–3 concrete AI-driven problems you can solve within your own organization/domain and present them to leadership — this is cited repeatedly as a fast path to visibility, promotion, or new-role opportunities.
12. **Vibe coding = disciplined prompting, not "no thinking required."** The highest-leverage activity is not the generation step — it's building a rock-solid blueprint (via critique → redesign → PRD) _before_ any code is generated. Under-specifying the "blueprint" stage guarantees expensive, frustrating rework later ("the half-built house" problem).
13. **Always define an MVP before building anything complex.** Pick the smallest set of features (ideally 2–3, prioritized in a table) that deliver real value, ship that, then iterate — adding no more than ~1–2 new features at a time to avoid breaking existing functionality.
14. **Every automation, on every platform, reduces to three building blocks: Trigger → Logic → Action.** Learning to mentally decompose any repetitive task into this structure is the core transferable skill of automation-building — independent of which specific tool (n8n, Zapier, Make.com) you use.
15. **AI has added a new "intelligence layer" to traditional rule-based automation** — enabling judgment-based classification, summarization, and content generation inside workflows that previously required entirely rigid, pre-programmed logic. But automation still struggles with genuinely dynamic edge cases and tasks that require real human judgment or approval.
16. **APIs are the universal connective tissue of the software world** — understanding them (even at a conceptual "waiter" level) is essential to understanding how AI models and automations plug into real apps like Gmail, Slack, and WhatsApp.
17. **Cost-consciousness matters.** Both vibe-coding platforms (credit-based pricing) and automation platforms (paid LLM API keys) have real, trackable costs — budget-conscious learners should start with free options (Google AI Studio, Gemini's free API tier, locally-hosted n8n) before scaling to paid infrastructure.
18. **Security is not automatic.** AI-generated applications can contain real vulnerabilities that non-technical builders won't spot on their own — always run available security scans and address flagged issues before publishing anything publicly.

---

_End of combined Day 1 + Day 2 notes for the Generative AI / Claude AI Mastermind. These notes consolidate: LLM fundamentals, prompt/context engineering, the AI toolkit, custom GPTs/agents, MCP-based automation, the 5 Levels of an AI Generalist, vibe coding (websites and full web applications), and no-code automation with n8n._
