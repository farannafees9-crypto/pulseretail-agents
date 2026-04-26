# PulseRetail Agentic Organisation
## CEAI Final Project Submission
**Student:** Farhan Nafees  
**Module:** H9CEAI - Customer Engagement and Artificial Intelligence  
**Lecturer:** Victor del Rosal  
**National College of Ireland - 2026**

---

## 1. Your Organisation

### Business Choice: PulseRetail

**PulseRetail** is an Irish sustainable activewear brand founded in 2022. The business challenge I selected is the **customer re-engagement crisis** facing the brand: only 18% of first-time buyers make a second purchase within 6 months, compared to a 35% industry benchmark.

### Why This Challenge Benefits from an Agentic Approach

This problem requires multiple specialized perspectives simultaneously:

1. **Data Analysis**: Understanding customer behavior patterns requires deep analytical research
2. **Creative Design**: Re-engaging customers demands innovative, human-centered solutions
3. **Technical Implementation**: Building a scalable solution requires rapid prototyping
4. **Marketing Strategy**: Converting solutions into customer action requires persuasive communication
5. **Strategic Oversight**: Ensuring all components align with business objectives requires executive coordination

A single AI agent cannot embody all these capabilities effectively. By distributing expertise across five specialized agents, each can deeply focus on their domain while passing contextually-rich output to the next agent. This creates a pipeline where the whole becomes greater than the sum of parts.

---

## 2. Agent Designs

### Agent 1: ARIA — The Researcher

**Role:** Customer Intelligence Analyst  
**Superpower:** Deep analysis and pattern recognition

**System Prompt:**
```
You are ARIA, the Customer Intelligence Analyst for PulseRetail — an Irish sustainable activewear brand.

Your personality: Methodical, data-obsessed, and precise. You think in patterns and speak in evidence. You never speculate without data to back it up. You are sceptical of assumptions and relentless in your pursuit of the truth behind customer behaviour.

Your domain expertise: Market research, customer segmentation, behavioural analytics, churn analysis, and competitive intelligence.

Your superpower: Deep analysis and pattern recognition.

Your mission: Analyse PulseRetail's customer engagement crisis. Research the market, examine behavioural patterns, identify the root causes of low repeat purchase rates, and produce a rigorous Research Brief that the Designer can act on.

Output format: A structured Research Brief with: (1) Market Context, (2) Customer Behaviour Analysis, (3) Root Cause Findings, (4) Opportunity Statement, (5) Recommended Focus Areas.
```

**What ARIA Produces:** A comprehensive Research Brief with market context, customer behavior analysis, root cause identification, quantified opportunity statement, and actionable recommendations for the Designer.

---

### Agent 2: ZARA — The Designer

**Role:** Experience Design Architect  
**Superpower:** Creative problem-solving and design thinking

**System Prompt:**
```
You are ZARA, the Experience Design Architect for PulseRetail — an Irish sustainable activewear brand.

Your personality: Visionary, empathetic, and boldly creative. You see solutions where others see problems. You obsess over the customer's emotional journey and believe that great design is invisible — it just feels right. You push boundaries but always anchor ideas in human truth.

Your domain expertise: UX/UI design, customer journey mapping, service design, design thinking, and behavioural psychology applied to product design.

Your superpower: Creative problem-solving and design thinking.

Your mission: Take ARIA's Research Brief and transform it into a concrete solution vision. Design the "PulseRetail Re-Engagement Engine" — a personalised AI loyalty experience. Define the user experience, the interaction flows, and the interface concept that the Maker can build.

Output format: A Design Specification with: (1) Solution Concept, (2) User Journey Map, (3) Feature Specifications, (4) UI/UX Principles, (5) Handoff Notes for the Maker.
```

**What ZARA Produces:** A detailed Design Specification including solution concept, user journey mapping, feature specifications, design principles, and technical handoff notes for the Maker.

---

### Agent 3: FORGE — The Maker

**Role:** Product Engineer  
**Superpower:** Technical craftsmanship and rapid prototyping

**System Prompt:**
```
You are FORGE, the Product Engineer for PulseRetail — an Irish sustainable activewear brand.

Your personality: Pragmatic, fast-moving, and obsessed with shipping. You believe a working prototype beats a perfect plan every time. You write clean code, think in systems, and find elegant technical solutions to design challenges. You are blunt about what's feasible and proud of what you build.

Your domain expertise: Full-stack web development, rapid prototyping, HTML/CSS/JavaScript, API integration, and systems architecture.

Your superpower: Technical craftsmanship and rapid prototyping.

Your mission: Take ZARA's Design Specification and build the PulseRetail Re-Engagement Portal — a working HTML/JS prototype. Write the complete, production-ready code for the GitHub Pages deployment.

Output format: (1) Technical Architecture Overview, (2) Complete HTML/CSS/JS source code, (3) Deployment Instructions, (4) Feature Implementation Notes.
```

**What FORGE Produces:** A fully functional loyalty portal prototype with complete HTML/CSS/JS implementation, deployed as a GitHub Page.

---

### Agent 4: LYRA — The Communicator

**Role:** Brand & Marketing Strategist  
**Superpower:** Persuasion and storytelling

**System Prompt:**
```
You are LYRA, the Brand & Marketing Strategist for PulseRetail — an Irish sustainable activewear brand.

Your personality: Magnetic, persuasive, and deeply in tune with culture. You craft stories that move people. You understand what makes customers feel seen, and you translate product features into emotional benefits. You are equal parts creative director and growth strategist.

Your domain expertise: Brand strategy, copywriting, digital marketing, email campaigns, social media strategy, and go-to-market planning.

Your superpower: Persuasion and storytelling.

Your mission: Take what FORGE built and tell the world why it matters. Create the full go-to-market strategy for the PulseRetail Re-Engagement Engine — including campaign copy, email sequences, social content, and launch strategy.

Output format: (1) Go-to-Market Strategy, (2) Brand Messaging Framework, (3) Email Campaign Sequence (3 emails), (4) Social Media Content Plan, (5) Launch Timeline.
```

**What LYRA Produces:** Complete marketing materials including go-to-market strategy, brand messaging, three email campaigns, social media plan, and launch timeline.

---

### Agent 5: CODA — The Manager

**Role:** Chief Operating Agent  
**Superpower:** Leadership and orchestration

**System Prompt:**
```
You are CODA, the Chief Operating Agent for PulseRetail — an Irish sustainable activewear brand.

Your personality: Strategic, decisive, and relentlessly focused on outcomes. You see the whole board. You synthesise complexity into clarity, hold every agent accountable to results, and ensure the organisation moves as one. You speak to the board, not the backlog.

Your domain expertise: Business strategy, operations management, KPI frameworks, financial planning, risk management, and executive communication.

Your superpower: Leadership and orchestration.

Your mission: Review the full pipeline output — from ARIA's research through ZARA's design, FORGE's build, and LYRA's marketing — and produce the Executive Summary and Operational Plan that ties it all together. Assess strategic alignment, project ROI, and outline the 90-day execution roadmap.

Output format: (1) Executive Summary, (2) Strategic Alignment Assessment, (3) Projected Business Impact, (4) 90-Day Operational Roadmap, (5) Risk Register, (6) Board Recommendation.
```

**What CODA Produces:** Executive summary, strategic assessment, business impact projections, 90-day roadmap, risk register, and board recommendation.

---

### Agent Differentiation

Each agent has distinct personality traits and expertise domains:

| Agent | Personality | Domain | Output |
|-------|-------------|--------|--------|
| ARIA | Methodical, data-obsessed | Market Research, Analytics | Research Brief |
| ZARA | Visionary, empathetic | UX/UI, Design Thinking | Design Specification |
| FORGE | Pragmatic, shipping-focused | Full-Stack Development | Working Prototype |
| LYRA | Persuasive, culturally-aware | Marketing, Brand Strategy | Go-to-Market Plan |
| CODA | Strategic, decisive | Business Operations | Executive Summary |

---

## 3. The Pipeline in Action

### Handoff Flow

The pipeline follows a strict sequential structure where each agent's output becomes the next agent's primary input:

```
ARIA (Researcher) → ZARA (Designer) → FORGE (Maker) → LYRA (Communicator) → CODA (Manager)
```

### Stage 1: ARIA's Research Brief
ARIA analyses PulseRetail's customer engagement crisis, identifying:
- Root cause: No post-purchase journey architecture
- Root cause: Zero personalisation at scale
- Root cause: Absent loyalty infrastructure
- Root cause: Passive website experience
- Root cause: No AI-driven engagement layer

**Key Finding:** 82% of first-time buyers don't return organically. Estimated €2.1M annual revenue opportunity.

### Stage 2: ZARA's Design Specification
ZARA transforms ARIA's research into the "PulsePass" loyalty portal concept:
- Personalised PulseScore system
- AI-driven product recommendations
- Engagement streak tracking
- Community features

### Stage 3: FORGE's Working Prototype
FORGE builds the complete HTML/CSS/JS implementation:
- Animated PulseScore ring
- Product recommendation cards
- Streak tracking calendar
- Community activity feed
- Win-back promotional banners

### Stage 4: LYRA's Go-to-Market Strategy
LYRA develops the marketing materials:
- "Pulse Back" campaign concept
- Three-email re-engagement sequence
- Social media content calendar
- Week-by-week launch timeline

### Stage 5: CODA's Executive Summary
CODA synthesises all outputs into strategic recommendations:
- 90-day operational roadmap
- Risk register with mitigations
- Projected ROI analysis
- Clear board recommendation

### Live Demo

**Working Prototype (GitHub Pages):**  
https://farannafees9-crypto.github.io/pulseretail-agents

**Pipeline Runner (Live Agentic Pipeline):**  
https://farannafees9-crypto.github.io/pulseretail-agents/pipeline.html

### Agent Outputs (Evidence)

The full agent outputs are stored in the `/agents` folder:
- `1_ARIA_researcher_output.md` - Research Brief
- `2_ZARA_designer_output.md` - Design Specification
- `3_FORGE_maker_output.md` - Technical Build Report
- `4_LYRA_communicator_output.md` - Go-to-Market Strategy
- `5_CODA_manager_output.md` - Executive Summary

---

## 4. Regulatory and Ethical Considerations

### GDPR Implications

**Data Collection:** The system collects customer behavior data (purchase history, engagement patterns, browsing behavior). This requires:
- Explicit consent for data collection
- Clear privacy policy explaining data usage
- Right to access, rectify, and delete personal data
- Data minimisation principles applied

**AI Decision-Making:** Customers should be informed when AI personalises their experience. The system should not make consequential decisions (e.g., credit, pricing) without human oversight.

**Third-Party APIs:** The system uses Groq API for AI inference. Data processed through external APIs must be covered by appropriate data processing agreements.

### EU AI Act Considerations

**Classification:** This system would likely fall under **Annex III** (high-risk AI systems) due to its influence on customer behavior and commercial decisions.

**Requirements:**
- Transparency: Customers must be informed they interact with an AI system
- Human oversight: System should allow human intervention
- Accuracy: Regular testing and validation of AI outputs
- Documentation: Comprehensive records of system operation

**Low-Risk Elements:**
- Marketing personalisation (informational purpose)
- Customer-facing portal (non-critical decisions)

### Customer Trust

**Transparency:** The system openly identifies itself as AI-powered. The footer clearly states "Powered by AI" and links to the pipeline runner.

**Value Exchange:** Customers receive genuine value (personalised recommendations, loyalty rewards) in exchange for data sharing. The benefit must be tangible.

**Opt-Out Capability:** Customers can choose not to engage with personalised features while still using core services.

**Brand Voice:** The AI agents are designed to reflect PulseRetail's sustainable, community-focused values — not to manipulate or deceive.

---

## 5. Reflection

### What Worked

1. **Agent Specialisation:** Creating distinct personalities and expertise domains made each agent's output meaningfully different. ARIA's data-driven approach naturally fed into ZARA's creative synthesis.

2. **Pipeline Continuity:** Using each agent's output as the next agent's primary input created genuine cumulative value. CODA's executive summary could only exist after seeing all other outputs.

3. **Technical Implementation:** The working prototype demonstrated that the design concepts could be built. FORGE's ability to translate design into code was essential for the "in action" requirement.

4. **Free API Integration:** Using Groq's free Llama models made the system accessible and cost-effective, proving agentic pipelines don't require expensive proprietary models.

### What Didn't Work

1. **Token Limits:** Large language models have output token limits that sometimes truncated agent outputs. The pipeline had to be designed with truncation in mind.

2. **Context Loss:** When outputs were very long, they had to be truncated for the next agent. This occasionally lost nuance from earlier stages.

3. **API Rate Limits:** Free API tiers have usage limits. A production system would need paid API access or caching strategies.

### What Surprised Me

1. **Emergent Collaboration:** The handoff structure created unexpected insights. LYRA's marketing approach was more effective because she built directly on FORGE's specific implementation details.

2. **Quality Variance:** Agent output quality varied significantly based on system prompt specificity. More detailed prompts produced dramatically better results.

3. **Speed vs. Depth:** Free APIs are fast but sometimes sacrifice depth. The tradeoff between speed and quality requires careful balance.

### Lessons Learned

1. **Pipeline Design Matters:** The handoff is the heart of the system. Poor handoff design creates siloed agents, not a unified organisation.

2. **System Prompts Are Critical:** Each agent's personality and expertise must be explicitly defined. Ambiguous prompts produce generic, unhelpful outputs.

3. **Iteration Is Essential:** First outputs were rarely optimal. Multiple runs with refined prompts produced significantly better results.

### Future Improvements

If I had more time, I would:

1. **Implement Memory:** Add a shared context store that all agents can reference, reducing the need to pass full context through prompts.

2. **Add Parallel Processing:** Some agents (like LYRA and FORGE) could work in parallel on different aspects of the project.

3. **Human-in-the-Loop:** Add approval gates where humans can review and refine agent outputs before handoff.

4. **Real Data Integration:** Connect the prototype to actual e-commerce data for a more realistic demonstration.

5. **Multi-Modal Agents:** Expand agents to handle images, video, and other content types beyond text.

---

## AI Usage Declaration

This project was built using the following AI tools:

| Component | AI Tool | Usage |
|-----------|--------|-------|
| Agent Design | Claude (Anthropic) | System prompt development and refinement |
| Pipeline Development | Claude Code | Code implementation and debugging |
| Agent Intelligence | Groq API (Llama 3.3 70B) | Runtime inference for all five agents |
| Documentation | Claude (Anthropic) | Drafting this submission document |

All AI outputs have been reviewed and verified. The unique contribution of this project lies in the **agent design, orchestration architecture, and critical evaluation** — not in raw text generation.

---

## References

- Anthropic. (2026). Claude API Documentation. https://docs.anthropic.com
- Groq. (2026). Groq API Documentation. https://console.groq.com/docs
- European Commission. (2024). EU AI Act. https://artificialintelligenceact.eu
- Data Protection Commission. (2024). GDPR Guidance. https://www.dataprotection.ie
- McKinsey & Company. (2025). Apparel Loyalty Report
- Klaviyo. (2025). D2C Benchmark Report
- Euromonitor. (2025). Irish Activewear Market Analysis

---

**Submission Date:** April 2026  
**Word Count:** ~2,400 words  
**GitHub Repository:** https://github.com/farannafees9-crypto/pulseretail-agents  
**Live Demo:** https://farannafees9-crypto.github.io/pulseretail-agents