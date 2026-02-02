# Generative AI Mastermind - Day 2 Workshop

## Overview
Day 2 of the comprehensive AI training program by Outskill, focusing on building products without code and AI automation workflows.

---

## Table of Contents
- [Day 1 Recap](#day-1-recap)
- [Session 1: Building Products with AI (No-Code)](#session-1-building-products-with-ai-no-code)
- [Session 2: AI Automations](#session-2-ai-automations)
- [Making Money with AI](#making-money-with-ai)
- [Key Takeaways](#key-takeaways)
- [Resources & Next Steps](#resources--next-steps)

---

## Day 1 Recap

### What We Learned Yesterday

**Foundation Concepts:**
- Understanding how AI is transforming work
- Shift from specialist to AI generalist mindset
- Companies reducing headcount, working with AI agents
- Future: fewer humans, more AI agents in organizations

**Key Learning Areas:**

1. **AI Models Overview**
   - 560+ AI models available on Open Router
   - Each model has different capabilities and pricing
   - Can install AI models locally (using Ollama)
   - Multi.AI for comparing multiple models side-by-side

2. **Prompt Engineering**
   - **Magic Prompt Formula**: Role + Task + Instructions + Data
   - **Markdown Prompting**: Advanced structure for AI agents
   - Context engineering importance

3. **AI Toolkit - Essential Tools**
   - Whisper Flow - Voice to text
   - Fireflies.AI - Meeting transcription
   - Emily.AI - Content summarization
   - Perplexity - Deep research
   - Gemini - Multi-purpose AI
   - Claude - Writing and coding
   - Suno - Music generation
   - Forth.AI - Product photography
   - Numerous.AI & Superjoin - Spreadsheet AI
   - Supergrow - LinkedIn content
   - Chronicle HQ - Presentations

4. **Custom GPTs & Gems**
   - Built viral tweet generator
   - Created LinkedIn post writer in personal style
   - Built AI Q&A mentor
   - Learned system prompts and knowledge bases

---

## Session 1: Building Products with AI (No-Code)

### Instructor: Dip
*PhD from IIT Madras, Head of Generative AI Education at Outskill*

### Part 1: Building Landing Pages

#### The 6-Step Landing Page Optimization Process

**Step 1: Take Screenshot**
- Use "Go Full Page" Chrome extension
- Capture entire existing landing page

**Step 2: Critique with ChatGPT Thinking**
- Upload screenshot to ChatGPT (use thinking model)
- Ask for CRO (Conversion Rate Optimization) analysis
- Identify areas for improvement

**Step 3: Add LP Best Practices**
- Find reference articles on landing page best practices
- Screenshot and upload to ChatGPT
- Request rewrite based on best practices

**Step 4: Generate Prompt**
- Ask ChatGPT to create prompt for rebuilding landing page
- Include all optimization insights

**Step 5: Improve Prompt with Another LLM**
- Copy prompt to different AI (Claude, Gemini)
- Ask for improvements and enhancements
- Get refined, better prompt

**Step 6: Build on V0/Lovable/Replit**
- Use improved prompt in builder platform
- Attach original screenshot for reference
- Generate optimized landing page

**Key CRO Concepts:**
- Conversion Rate = (Actions Taken / Total Visitors) × 100
- Goal: Improve from 5% to 10%+ conversion
- Focus on above-the-fold content
- Clear call-to-action (CTA)
- Social proof and testimonials
- Remove cognitive overload

### Part 2: Building Full Products

#### Understanding Product Architecture

**The Cinema Analogy:**

| Cinema Production | Product Development |
|-------------------|---------------------|
| What you see in theaters | **Front-end** (Web/Mobile UI) |
| Production controllers | **APIs** (Coordination layer) |
| 100-150 hours of footage | **Database** (Data storage) |
| Editor | **Server** (Processing) |
| VFX outsourcing | **Third-party integrations** |
| Ticket authentication | **User authentication** |

**Key Components:**
- **Front-end**: What users see and interact with
- **Back-end**: Database, server, processing
- **APIs**: Connect front-end and back-end
- **Third-party**: OpenAI SDK, payment gateways, etc.

#### The Product Design Process

**Phase 1: Conceptualization**

1. **Basic Feature List**
   ```
   Example: Calorie Counter App
   - Manual food entry
   - Barcode scanner
   - Water intake tracking
   - Analytics and insights
   ```

2. **Competitor Analysis**
   - Research top 3-4 competitors
   - Visit pricing/features pages
   - Screenshot feature comparisons
   - Analyze: MyFitnessPal, Lose It, Chronometer

3. **Enhanced Feature List**
   - Combine your ideas + competitor features
   - Use AI to analyze screenshots
   - Create comprehensive feature set

4. **MVP Definition**
   - **Minimum Viable Product** = Bare minimum to launch
   - Choose: 2 core features + 1 user delight feature
   - Like building a house: plumbing + electricity first, not garage

5. **Product Requirements Document (PRD)**
   - Act as product manager
   - Define functional requirements
   - Skip non-functional for first version
   - Use local storage (avoid database complexity initially)

6. **Refine to Prompt**
   - Convert PRD to building prompt
   - Give guidelines, not strict instructions
   - Let AI agent have breathing room
   - Simplify: No database, no authentication (for MVP)

**Phase 2: Building**

**Platforms to Use:**
- **Lovable** - Visual, generous free credits
- **Google AI Studio** - Free, uses Gemini
- **Replit** - Code-first but AI-powered
- **Bolt.new** - Quick prototypes
- **V0 by Vercel** - UI generation

**Building Example: Calorie Counter**

```markdown
Core Features:
1. AI photo-based food logging
2. Personalized macro goals
3. Smart meal suggestions

Implementation:
- Use OpenAI API for food recognition
- Local storage for data
- No authentication (MVP)
- Progressive enhancement
```

**The Iterative Process:**

1. **Start Small**
   - Build 2 core + 1 delight feature first
   - Don't try to build 10 features at once

2. **Test Every Step**
   - Add one feature at a time
   - Test after each addition
   - Watch for "breaking changes"

3. **Use Rollback**
   - If feature breaks app, revert to previous version
   - Platforms keep version history

4. **Enhance Gradually**
   - Add vegetarian/non-vegetarian filters
   - Add manual text entry
   - Add recipe generator
   - Improve UI/UX

**UI Enhancement Workflow:**

1. Find inspiration on Behance/Dribbble
2. Screenshot design you like
3. Give URL/screenshot to Lovable
4. AI fetches and applies design style
5. Yellow-themed, modern, professional look

**Publishing Your Product:**

- **Lovable**: Click "Publish" → Get hosted URL
- **Google AI Studio**: Deploy to Google Cloud
- **GitHub**: Save code for version control
- **Custom Domain**: Connect your own domain

### Key Principles

**For Landing Pages:**
- Follow CRO best practices
- Use thinking models for analysis
- Cross-validate with multiple LLMs
- Attach visual references

**For Products:**
- Guidelines over instructions
- One feature at a time
- Test continuously
- Start simple, enhance iteratively

---

## Session 2: AI Automations

### Instructor: Retesh
*AI Automation Expert, Agency Owner*

### Understanding Automation Basics

**Core Concepts:**
- **Trigger**: What starts the automation
- **Actions**: What happens after trigger

**Example:**
```
Amazon Order Flow:
Trigger: Payment confirmed
Actions:
- Send email to buyer
- Send SMS notification
- Notify seller to ship
- Update inventory
```

### The 7 Steps of Business Automation

#### Step 1: Capture Your Workflow

Document current manual process:

```
Lead Form Example:
1. User fills form
2. Download responses
3. Send intro email
4. Notify sales team
5. Add to CRM
```

#### Step 2: Map Flow of Information

```
Flow: Form → Sheets → Gmail → Sales Notification → CRM
```

#### Step 3: Identify Decision Points

```
If service = "Automation Consulting"
  → Send Email A
  → Assign to Sales Person A
  
If service = "Web Development"
  → Send Email B
  → Assign to Sales Person B
```

#### Step 4: Pinpoint Bottlenecks

What problems are you solving?
- Slow response time (manual emails)
- Sales team unaware of new leads
- CRM data entry errors
- Repetitive manual work

#### Step 5: Define Triggers & Actions

**Trigger:**
- New Google Form submission

**Actions:**
1. Send personalized email
2. Add to Google Sheets/CRM
3. Notify sales via Slack/WhatsApp
4. (Optional) Add to nurturing sequence

#### Step 6: Select Right Tools

**Automation Platforms:**

| Platform | Apps | Pros | Cons |
|----------|------|------|------|
| **Zapier** | 8,094 | Most integrations | Expensive |
| **Make.com** | 3,144 | Generous free tier (1000 ops) | Fewer apps |
| **N8N** | ~1,000 | Best for AI agents | Learning curve |
| **Pabbly Connect** | ~1,000 | Lifetime plan | Indian alternative |

**Selection Criteria:**
- Check if your apps are integrated
- Consider pricing model
- Free tier limits
- Use case complexity

#### Step 7: Implement, Test, Monitor, Optimize

**Implementation:**
- Build automation step-by-step
- Test each module

**Monitoring:**
- Weekly initially
- Bi-weekly after stabilization
- Monthly for mature automations

**Optimization:**
- Identify slow points
- Reduce credit usage
- Improve success rate

### Practical Example: Form to Email Automation

**Setup on Make.com:**

```markdown
Step 1: Create Google Form
- Add fields: Name, Email
- Link to Google Sheets

Step 2: Set Up Make.com Trigger
- Module: Google Sheets
- Event: Watch New Rows
- Connect account
- Select spreadsheet
- Choose sheet
- Headers: Yes (A1:C1)
- Limit: 2 (processes 2 rows per run)

Step 3: Add Email Action
- Module: Outlook/Gmail
- Action: Send Email
- Recipient: {{Email from Step 1}}
- Subject: "Registration Received"
- Body: HTML formatted welcome message

Step 4: Configure Scheduling
- At regular intervals: 15 minutes (free plan)
- Every day at specific time
- Days of week
- On demand
```

**Key Settings:**

- **Limit**: How many new rows to process per run
- **Schedule**: How often to check for new data
- **Starting Point**: Where to begin automation

### Advanced Example: Social Media Automation

**Workflow: AI-Generated Posts**

```markdown
Step 1: Generate Image
- Module: OpenAI
- Action: Generate Images (DALL-E 3)
- Prompt: "Generate motivational quote image"
- Requires: OpenAI API key + Credits

Step 2: Analyze Image
- Module: OpenAI
- Action: Analyze Image
- Model: GPT-4.1 Vision
- Task: "Generate caption for Instagram"

Step 3: Router (Split Flow)
Route A: Instagram
- Analyze for Instagram caption
- Post to Instagram Business

Route B: LinkedIn  
- Analyze for LinkedIn post (100 words)
- Post to LinkedIn

Scheduling: Daily at 6 PM
```

**Important Notes:**

**API Keys:**
- OpenAI API requires separate credits
- Not connected to ChatGPT subscription
- Get from: platform.openai.com/settings

**Credits:**
- Make.com: 1,000 free operations
- Each step consumes credits
- Router/internal steps: free
- External API calls: consume credits

**Image Models:**
- DALL-E 2: Older, some quality issues
- DALL-E 3: Better, spelling issues
- GPT Image-1: Best, requires org verification
- Alternative: Nano Banana, Minimax (Chinese models)

### Best Practices

**Do's:**
✅ Start with simple 2-3 step automations
✅ Test after every module addition
✅ Use Router for multiple paths
✅ Set appropriate scheduling
✅ Monitor credit usage
✅ Have rollback plan

**Don'ts:**
❌ Don't build complex flows immediately
❌ Don't skip testing
❌ Don't ignore error messages
❌ Don't forget to enable automation
❌ Don't run out of credits (automation stops)

### Common Use Cases

**Business:**
- Lead nurturing sequences
- Invoice generation
- Meeting scheduling
- Report generation
- Data synchronization

**Marketing:**
- Social media posting
- Email campaigns
- Content distribution
- Analytics reporting

**Personal:**
- Email organization
- Calendar management
- Expense tracking
- Health data logging

---

## Making Money with AI

### Opportunities Overview

The current moment is special - 95% of global population doesn't know what you've learned. Act with urgency.

### Option 1: Start an AI Agency

**What You Offer:**
- Custom AI solutions
- Automation workflows
- Product development

**Who to Target:**
- Small-medium enterprises (SMEs)
- Startups
- Department heads in larger companies

**Getting Started:**
1. Master 2 skills: Product building + Automations
2. Identify your niche (finance, healthcare, retail, etc.)
3. Find pain points in that niche
4. Build solutions
5. Start with 3-5 clients

**Example Solutions:**
- Invoice automation for SMEs
- Inventory management
- Customer support chatbots
- Marketing automation
- Lead scoring systems

**Pricing:**
- Per project: ₹50,000 - ₹5,00,000
- Monthly retainer: ₹25,000 - ₹1,00,000
- Depends on complexity and value delivered

### Option 2: Build & Sell AI Products

**Product Ideas:**

**Micro-SaaS:**
- Chrome extensions
- Figma plugins
- Notion templates with AI
- Industry-specific tools

**Where to Find Ideas:**
- Product Hunt (producthunt.com)
- Browse top launches daily
- Find gaps in existing products
- Rebuild better versions

**Example Products:**
- "Turn audio into personalized films"
- Digital planners
- Task management tools
- Industry-specific CRMs

**Distribution:**
- List on Product Hunt
- App Store / Play Store
- Gumroad / LemonSqueezy
- Direct sales via LinkedIn

**Monetization:**
- Subscription: ₹1,000/month × 100 users = ₹1,00,000/month
- One-time purchase: ₹5,000 × 50 users = ₹2,50,000
- Freemium model

### Option 3: AI Consulting

**What You Do:**
- 30-60 minute calls
- Identify AI opportunities in their business
- Provide implementation roadmap
- They execute or hire agency

**Rates:**
- ₹5,000 - ₹25,000 per consultation
- Package deals: 5 calls for ₹75,000
- Retainer: ₹50,000/month for ongoing advice

**How to Start:**
1. Build expertise in one industry
2. Create case studies
3. Offer free first consultation
4. Document insights
5. Scale through content

### Option 4: Content Creation & Distribution

**Faceless YouTube Channels:**

Example: AI Revolution
- 500K+ subscribers
- All AI-generated content
- Voice: AI
- Visuals: AI
- Editing: Minimal

**Monetization:**
- Brand sponsorships: ₹50,000 - ₹5,00,000 per video
- YouTube ads (if allowed)
- Affiliate marketing
- Course sales

**Instagram/LinkedIn:**
- Grow to 10K+ followers
- Brand deals: ₹25,000 - ₹2,00,000 per post
- Outskill Instagram: 200K → 1.2M in 6-8 months
- All AI-generated content

**Newsletters:**
- Build email list
- Provide weekly value
- Brand sponsorships
- Outskill example: ₹25,00,000/month from newsletter

**Process:**
1. Choose niche
2. Create AI avatar
3. Generate content daily
4. Focus on value, not views
5. Monetize at 10K+ followers

### Option 5: AI-Powered Ads for Brands

**Spec Ads Strategy:**
1. Choose 10 brands you love
2. Create AI ads for them (unpaid)
3. Post on social media
4. Brands will notice
5. Inbound requests start

**Why Brands Want AI Ads:**
- Lower cost per lead (CPL)
- Higher click-through rates (CTR)
- Unique creative positioning
- Thumb-stopping content

**Rates:**
- Single ad: ₹50,000 - ₹3,00,000
- Campaign: ₹5,00,000 - ₹25,00,000
- Monthly retainer: ₹2,00,000 - ₹10,00,000

### Getting Clients: 4-Step Framework

#### Step 1: Identify Target Audience

**Questions to ask:**
- Who has the budget?
- Who makes decisions?
- What industry am I targeting?

**Examples:**
- Founders (0-50 employee companies)
- VPs/Directors (51-500 employee companies)
- Creative directors (agencies)

#### Step 2: Optimize LinkedIn Profile

**Critical Sections:**

**Profile Picture:**
- Professional
- Clear face
- Good lighting
- Approachable

**Cover Picture:**
- What you offer
- Your niche
- Contact info
- Portfolio link

**Headline (220 characters):**
```
❌ "Software Developer"
✅ "AI Automation Specialist | Helping E-commerce Brands Save 20hrs/week | Built 50+ No-Code Solutions"
```

**About Section:**
- Who you help
- What you do
- How you do it
- Results you've delivered
- Call to action

**Featured Section:**
- Best posts
- Case studies
- Portfolio links
- Testimonials

**Experience:**
- Detailed descriptions
- Quantify results
- Use keywords

#### Step 3: Master Cold Emailing

**Finding Emails:**
- Hunter.io
- Snov.io
- Apollo.io
- RocketReach

**Email Structure:**
```markdown
Subject: Quick idea for [Company]

Hi [Name],

[Personalized observation about their business]

[One-liner about what you do]

[Specific value you can provide them]

[Soft CTA]

Best,
[Your name]
```

**Tools:**
- Lemlist
- Instantly.ai
- Woodpecker
- Smartlead

**Tips:**
- Personalize first line
- Keep under 100 words
- One clear CTA
- Follow up 3-4 times
- Track open rates

#### Step 4: Join Communities

**Where:**
- Cool (Slack communities)
- Indie Hackers
- Product Hunt
- Reddit (r/SaaS, r/Entrepreneur)
- Discord servers

**Strategy:**
- Provide value first
- Answer questions
- Share learnings
- Don't pitch immediately
- Build relationships

---

## Key Takeaways

### Technical Skills Learned

**Day 1:**
- Prompt engineering (Magic Formula + Markdown)
- Custom GPTs and Gemini Gems
- Multiple AI models and when to use each
- Voice agents and AI cloning

**Day 2:**
- Landing page optimization (6 steps)
- Product architecture understanding
- Building full products without code
- AI automation workflows (7 steps)
- Make.com platform mastery

### Mindset Shifts Required

1. **From Specialist to Generalist**
   - Deep in one area + Broad across many
   - AI amplifies this capability

2. **From Consumer to Builder**
   - Don't just use tools
   - Build solutions
   - Create value

3. **From Employee to Entrepreneur**
   - Micro-agencies possible
   - Side income opportunities
   - Location independent

4. **From Perfect to Iterative**
   - Ship MVP fast
   - Improve based on feedback
   - 80% solution today > 100% solution never

### Business Opportunities

**Immediate (0-3 months):**
- Freelance automation work
- Consulting calls
- Spec work for portfolio

**Short-term (3-6 months):**
- First agency clients
- Product launch
- Newsletter growth

**Long-term (6-12 months):**
- Recurring revenue
- Team building
- Product-market fit

### Critical Success Factors

**Must Do:**
✅ Practice immediately (next 7 days)
✅ Build public portfolio
✅ Optimize LinkedIn
✅ Start creating content
✅ Reach out to 10 potential clients
✅ Join relevant communities

**Avoid:**
❌ Waiting for perfection
❌ Learning without building
❌ Building without distribution
❌ Trying to monetize day 1
❌ Giving up after first rejection

---

## Resources & Next Steps

### Immediate Actions (Next 7 Days)

**Day 1-2: Practice**
- Build personal portfolio website
- Create one automation
- Optimize LinkedIn profile

**Day 3-4: Portfolio**
- Build 2-3 sample products
- Document case studies
- Create spec ads (if creative)

**Day 5-6: Outreach**
- List 50 potential clients
- Craft email templates
- Send 10 cold emails

**Day 7: Review**
- What worked?
- What didn't?
- Adjust strategy

### Workbooks Provided

1. **Level 1 Workbook** - Prompt Engineering
   - Create prompt library
   - Practice different techniques
   - Build custom GPTs

2. **Product Building Workbook**
   - Personal portfolio site
   - Bring your idea to life
   - Step-by-step guidance

3. **Automation Workbook**
   - 3 automation scenarios
   - Video tutorials included
   - Follow-along exercises

### Platforms & Tools

**No-Code Builders:**
- Lovable (generous free tier)
- Google AI Studio (free)
- Replit (freemium)
- Bolt.new
- V0 by Vercel
- Rocket AI

**Automation:**
- Make.com (1,000 free ops)
- Zapier (100 free tasks)
- N8N (open source)
- Pabbly Connect (lifetime plans)

**Finding Emails:**
- Hunter.io
- Snov.io
- Apollo.io

**Cold Email:**
- Lemlist
- Instantly.ai
- Smartlead

**Community:**
- Cool (Slack)
- Indie Hackers
- Product Hunt

### Bonus Sessions

**Day 3: Image & Video Generation**
- **When**: 7:30 PM - 10:00 PM IST
- **Instructor**: Shantanu (Creative Director)
- **Topics**:
  - Diffusion models deep dive
  - Creating cinematic videos
  - Building AI movies
  - Ad creation workflows
  - Brand storytelling with AI

### What You'll Receive

**Within 48 Hours:**
- All session recordings
- Access to LMS platform
- Organized by session

**Immediate Access:**
- Session workbooks
- Resource documents
- Road map to AI Generalist
- Certificate of completion

**Community Access:**
- AI updates newsletter
- Future workshop invitations
- Continued learning resources

### The 18-Month Roadmap

**Months 1-3: Level 1**
- Master prompting techniques
- Experiment with all major models
- Install local AI models
- Build prompt library

**Months 4-6: Level 2**
- Model Context Protocol (MCP)
- Connect apps to LLMs
- Build voice agents
- Complex integrations

**Months 7-9: Level 3**
- Image generation mastery
- Video creation workflows
- Audio manipulation
- Creative AI applications

**Months 10-12: Level 4**
- Advanced automations
- Agentic workflows
- Multi-step processes
- Business process optimization

**Months 13-18: Level 5**
- Full product development
- App Store deployment
- Monetization strategies
- Scaling your solutions

**Time Investment:**
- 10 hours/week = 18 months
- 20 hours/week = 9 months
- 40 hours/week = 4-5 months

### Support Channels

**For Questions:**
- Practice with workbooks first
- Review session recordings
- Check resource documents

**For Community:**
- Join Cool communities
- Connect on LinkedIn
- Engage with content

---

## Final Thoughts

### The Opportunity Window

**Why Now is Special:**
- 95% of people don't know this
- Technology is accessible
- Barriers to entry are low
- First-mover advantage still exists

**But Act Fast:**
- Technology getting easier (good & bad)
- More people learning daily
- Competition increasing
- Window won't stay open forever

### The Path Forward

**Don't Obsess Over Money Initially:**
- Treat AI as life skill
- Master the fundamentals
- Build real solutions
- Money follows mastery

**Focus On:**
- Deep practice
- Building portfolio
- Helping real people
- Creating value

**Remember:**
- Automation isn't "set and forget"
- Monitor and optimize regularly
- Technology evolves constantly
- Keep learning and adapting

### Success Formula

```
Skills (What you learned)
+
Practice (Next 7 days)
+
Portfolio (Show your work)
+
Distribution (LinkedIn + Cold email)
+
Community (Cool, Indie Hackers)
=
Opportunities & Income
```

---

## Instructor Credits

### Day 2 Instructors

**Dip (Session 1)**
- PhD, IIT Madras
- Head of GenAI Education, Outskill
- Electrical Engineer turned AI Expert
- "If I can do it, so can you"

**Retesh (Session 2)**
- Electrical Engineer
- AI Automation Agency Owner
- 15+ years software automation
- 5-6 years no-code expertise

**Host: PK (Punny Krishna)**
- Associate Director of Growth, Outskill
- Founding member
- Educator & Community Builder

---

## Certificate & Recognition

**You've Completed:**
- 16 hours of intensive training
- 2 full days of learning
- Multiple hands-on exercises
- Building real projects

**From 12,000 to 4,000:**
- Started with 12K+ participants
- Ended with 4K committed learners
- You're in the top 33% who finished
- That shows dedication

**What This Proves:**
- You can learn complex topics
- You have commitment
- You're future-ready
- You're part of the 5%

---

## Important Reminders

### About Recordings
- Arriving within 48 hours (by end of Tuesday)
- Will be sent via email
- Hosted on LMS platform
- Includes Day 3 bonus session

### About Certificate
- Generate immediately (15-minute window)
- Use registration email
- Download as PDF
- Share on LinkedIn

### About Practice
- Next 7 days are critical
- Use it or lose it
- Certificate without skills = worthless
- Skills without certificate = valuable

### Share the Knowledge
- Refer friends/colleagues
- Gift this experience
- Help reach 100M people globally
- Build the AI community

---

## Congratulations! 🎉

You've completed the Generative AI Mastermind!

**You Now Know:**
- How AI really works
- How to prompt effectively
- How to build products (no code)
- How to create automations
- How to make money with AI

**What's Next:**
- Day 3: Image & Video (Tomorrow 7:30 PM IST)
- Practice with workbooks
- Build your portfolio
- Start your AI journey

**Remember:**
> "Becoming an AI generalist isn't about being the best at everything—it's about being capable enough in many things to solve problems that specialists can't."

---

*Workshop completed: Day 2 of Generative AI Mastermind*
*Next Session: Day 3 - Image & Video Generation*
*Time: 7:30 PM - 10:00 PM IST*

**See you tomorrow! 🚀**

---