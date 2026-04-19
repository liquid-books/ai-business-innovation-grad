# Quiz: Chapter 7 — Synthetic Employees

**Instructions:** Select the best answer(s) for each question. Some questions have two correct answers. Questions are drawn from the chapter readings and content.

---

## Question 1

The chapter opens with the quote: *"The headcount line in your pro forma is about to become a subscription line."* What business model shift does this describe?

- A) Companies will begin paying employees via subscription billing software instead of payroll
- B) Human roles that previously appeared as fixed headcount costs in financial projections will increasingly be replaced by AI agent subscriptions — shifting the cost structure from labor to software
- C) Investors will require all startups to have subscription revenue before they will fund headcount
- D) The staffing industry will consolidate around a single subscription platform for hiring
- E) Pro forma financial models will no longer be required for AI-native startups

<details>
<summary>Show Answer & Explanations</summary>

- A) ❌ The quote is not about how employees are paid — it is about replacing human headcount with AI subscriptions in the cost structure of the business.
- ⭐ B) ✅ The chapter argues that roles previously projected as headcount (customer service agents, SDRs, researchers, operations staff) will be replaced by AI agent subscriptions. The economic implication: variable labor costs with benefits, PTO, and turnover become predictable, scalable SaaS subscriptions — fundamentally changing the operating leverage of a business.
- C) ❌ Investor requirements are not the subject of this quote. The transformation described is operational, not fundraising-related.
- D) ❌ Industry consolidation is not what the quote addresses. The shift is at the individual business level, not industry structure.
- E) ❌ Pro forma models remain essential — the point is that the *content* of those models is changing, not that they become unnecessary.

</details>

---

## Question 2

The chapter defines an AI agent using a "core loop." What are the THREE components of this core loop?

- A) Prompt → Generate → Publish
- B) Train → Deploy → Monitor
- C) Perceive → Reason → Act
- D) Input → Process → Output
- E) Sense → Decide → Execute

<details>
<summary>Show Answer & Explanations</summary>

- A) ❌ This describes a content generation workflow, not the agent core loop defined in the chapter.
- B) ❌ Train-Deploy-Monitor is a machine learning lifecycle, not the agent operational loop.
- ⭐ C) ✅ The chapter defines the agent core loop as Perceive (receive inputs from the environment — text, data, tool outputs), Reason (apply the model to determine what action to take), and Act (execute the action — call a tool, generate text, trigger a workflow). This loop repeats autonomously until the task is complete or an escalation condition is met.
- D) ❌ Input-Process-Output is a generic computing model, not the agent-specific loop defined in the chapter with its emphasis on environmental perception and tool-mediated action.
- E) ❌ Sense-Decide-Execute is similar but is not the exact three-term formulation used in the chapter.

</details>

---

## Question 3

The chapter introduces MCP (Model Context Protocol) and describes it as "the USB-C of agent tools." What does this analogy mean?

- A) MCP requires a physical USB-C connector to function, making it hardware-dependent
- B) MCP is a universal standard protocol that allows AI agents to connect to and use external tools and systems in a standardized way — just as USB-C provides a single universal connector for diverse peripherals
- C) MCP was developed by the same engineering team that designed the USB-C standard
- D) MCP limits agents to working with only one external tool at a time, like USB-C's single port design
- E) MCP is proprietary to Anthropic and cannot be used with non-Claude AI agents

<details>
<summary>Show Answer & Explanations</summary>

- A) ❌ MCP is a software protocol with no hardware dependency. The USB-C comparison is an analogy about standardization, not hardware compatibility.
- ⭐ B) ✅ The chapter uses the USB-C analogy to explain MCP as a universal standard: just as USB-C allows any compatible device to connect to any compatible peripheral, MCP allows any MCP-compatible AI agent to connect to any MCP-compatible tool or data source. Without MCP, each agent-tool integration requires custom code; MCP standardizes the connection layer.
- C) ❌ MCP is a software protocol designed for AI agent tooling — it has no historical connection to the USB-C hardware consortium.
- D) ❌ USB-C supports simultaneous connections and MCP supports multiple tool connections — the "single connector" aspect of the analogy refers to standardization, not limitation.
- E) ❌ MCP is an open protocol designed to be model-agnostic, not proprietary to Anthropic.

</details>

---

## Question 4

In the Klarna "700" case study, what did Klarna publicly disclose about its AI customer service deployment?

- A) The AI system replaced 700 customer service agents, handled 2/3 of customer service chats, reduced average resolution time from 11 minutes to 2 minutes, and expected $40M in annual profit improvement
- B) The AI system handled only simple FAQ queries while human agents retained all complex case management
- C) Klarna's AI deployment resulted in 700 new engineering hires to maintain the system
- D) The AI achieved a 30% improvement in customer satisfaction scores compared to human agents
- E) Klarna's AI was built entirely in-house without any commercial AI model provider partnerships

<details>
<summary>Show Answer & Explanations</summary>

- ⭐ A) ✅ The chapter reports Klarna's specific public disclosures: equivalent to 700 FTEs replaced, two-thirds of customer service chats handled, resolution time dropping from 11 minutes to 2 minutes, and $40M in expected annual profit improvement. These are the exact figures Klarna disclosed in February 2024.
- B) ❌ The chapter does not describe Klarna's AI as limited to FAQ handling — the resolution time and CSAT comparisons suggest it handled substantive customer service cases.
- C) ❌ The AI deployment replaced human customer service agents, not created new engineering roles in a 1:1 ratio.
- D) ❌ The chapter reports that customer satisfaction scores remained "at parity with human agents" — not a 30% improvement.
- E) ❌ The chapter notes Klarna's AI was "built on OpenAI's models," not developed entirely in-house.

</details>

---

## Question 5

The chapter's "Synthetic Employee Playbook" defines six steps for deploying a synthetic employee. What is the purpose of Step 4: Escalation?

- A) To define which human manager receives the agent's performance review
- B) To define the conditions under which the agent stops autonomous action and requests human judgment — specifying which situations exceed its authorized decision scope
- C) To establish the agent's salary equivalent for financial planning purposes
- D) To determine when the agent should be upgraded to a more capable AI model
- E) To specify which competing AI vendors the agent is allowed to evaluate

<details>
<summary>Show Answer & Explanations</summary>

- A) ❌ Performance reviews for AI agents are not the function of the escalation step. The step is about real-time decision boundaries during task execution.
- ⭐ B) ✅ The chapter defines Step 4 (Escalation) as the critical safety and reliability layer: defining precisely when the agent should stop acting autonomously and pass control to a human. This includes situations involving financial decisions above a threshold, novel situations outside the runbook, and cases where confidence is low. Without well-defined escalation criteria, the agent either over-escalates (useless) or under-escalates (dangerous).
- C) ❌ Salary equivalents are part of the economic analysis of synthetic employees, not the escalation step of the deployment playbook.
- D) ❌ Model upgrade decisions are operational maintenance decisions, not the function of the escalation step in the playbook.
- E) ❌ Vendor evaluation is a procurement decision, not an escalation protocol function.

</details>

---

## Question 6

The chapter describes the "Synthetic SDR" as one of five high-value synthetic roles. What TWO capabilities make the Synthetic SDR economically valuable compared to a human SDR?

- A) The synthetic SDR can operate 24/7 without overtime pay, vacation, or benefit costs
- B) The synthetic SDR has a higher emotional intelligence score than human SDRs in controlled studies
- C) The synthetic SDR can personalize outreach at scale — researching each prospect and tailoring messaging — without the quality degradation that occurs when humans rush through high-volume outreach
- D) The synthetic SDR can legally make cold calls in all jurisdictions without telemarketing compliance requirements
- E) The synthetic SDR generates its own training data, reducing ongoing AI operational costs over time

<details>
<summary>Show Answer & Explanations</summary>

- ⭐ A) ✅ The chapter identifies the 24/7 operational capability and elimination of human employment overhead (benefits, PTO, turnover costs) as a primary economic advantage of the synthetic SDR. A human SDR works 40 hours per week; a synthetic SDR operates continuously.
- B) ❌ Emotional intelligence claims for AI agents are not made in the chapter — the value proposition is about scale, availability, and consistency, not emotional sophistication.
- ⭐ C) ✅ The chapter identifies personalization at scale as a key synthetic SDR advantage: AI can research each prospect (LinkedIn, company news, recent activities) and craft tailored outreach for every contact without the quality degradation that happens when a human SDR sends hundreds of templated emails. The quality-volume trade-off that limits human SDRs is removed.
- D) ❌ Telemarketing compliance requirements (TCPA, Do Not Call lists) apply to AI-powered calling systems — in some jurisdictions, AI calling has additional restrictions, not fewer. The chapter's chapter does not claim legal exemptions.
- E) ❌ Self-generating training data that reduces ongoing AI costs is not described as a synthetic SDR feature in the chapter.

</details>

---

## Question 7

The chapter discusses the ethical considerations of synthetic employee deployment. Which of the following does the chapter identify as a specific ethical concern?

- A) The synthetic employee may develop emotional attachment to users, creating liability for the company
- B) AI agents configured to represent humans in customer-facing roles without disclosure raises questions about consent and transparency — customers may not know they are interacting with an AI
- C) Synthetic employees paid as software subscriptions may violate minimum wage laws in some jurisdictions
- D) The use of synthetic employees is prohibited by the Geneva Convention's protections on labor rights
- E) Synthetic employees automatically join the company's pension plan under ERISA regulations

<details>
<summary>Show Answer & Explanations</summary>

- A) ❌ While AI attachment is a real phenomenon studied in consumer psychology, the chapter's ethical considerations focus on displacement, consent, and accountability — not AI emotional attachment.
- ⭐ B) ✅ The chapter explicitly identifies disclosure and consent as an ethical concern: when an AI agent presents as a human (or ambiguously), customers interacting with it have not consented to an AI relationship. This creates questions about deception, informed consent, and appropriate disclosure — particularly in high-stakes contexts like financial advice or healthcare.
- C) ❌ Software subscriptions are not employment contracts and do not trigger minimum wage law applicability. This conflates software licensing with employment law.
- D) ❌ The Geneva Convention governs armed conflict and humanitarian law — it has no jurisdiction over labor or AI deployment practices. This is fabricated.
- E) ❌ ERISA (Employee Retirement Income Security Act) governs employee benefit plans — software subscriptions are not employees and do not trigger ERISA obligations.

</details>

---

## Question 8

The chapter discusses "Agent Architectures" and describes conditions for when each architecture earns its complexity. What is the chapter's guidance on when to use a MULTI-AGENT architecture?

- A) Multi-agent architectures should always be used because they are more robust than single-agent systems
- B) Multi-agent architectures are appropriate when the task scope exceeds what a single agent can hold in context, when tasks require parallel specialization, or when independent verification of outputs is required
- C) Multi-agent architectures are only appropriate for companies with more than 100 employees
- D) Multi-agent architectures should only be used when all involved agents are from the same AI provider to ensure compatibility
- E) Multi-agent architectures are prohibited in regulated industries due to accountability chain complexity

<details>
<summary>Show Answer & Explanations</summary>

- A) ❌ The chapter explicitly warns against defaulting to architectural complexity. "When each architecture earns its complexity" means simpler architectures should be used unless the task genuinely requires the overhead of multi-agent coordination.
- ⭐ B) ✅ The chapter identifies multi-agent architectures as appropriate in three scenarios: (1) tasks too large for single-agent context windows; (2) tasks requiring parallel specialization where different agents handle distinct domains simultaneously; (3) tasks requiring independent verification where one agent's output is reviewed by a second. Outside these conditions, single-agent or chained architectures are preferred.
- C) ❌ Architectural choice is driven by task requirements, not company size.
- D) ❌ Multi-agent architectures can and do use agents from multiple providers — cross-provider orchestration is a common pattern the chapter discusses.
- E) ❌ Regulated industries do face accountability challenges with AI, but the chapter does not state a categorical prohibition on multi-agent architectures in those industries.

</details>

---

## Question 9

The chapter's discussion of "What the Klarna Didn't Disclose" is notable for raising what concern about the published Klarna AI results?

- A) Klarna did not disclose the names of the 700 employees who were displaced, violating privacy laws
- B) Klarna did not disclose the error rate — resolution time of 2 minutes is only a meaningful improvement if the resolutions are correct, particularly for high-stakes BNPL disputes
- C) Klarna did not disclose how much it paid OpenAI for the API access, preventing competitors from benchmarking costs
- D) Klarna did not disclose the customer demographic breakdown of AI vs. human service interactions
- E) Klarna did not disclose the names of the engineers who built the system, preventing independent technical verification

<details>
<summary>Show Answer & Explanations</summary>

- A) ❌ Employee privacy regarding displacement is a legitimate concern, but the chapter specifically identifies the error rate gap, not employee disclosure, as the critical omission.
- ⭐ B) ✅ The chapter explicitly states: "Klarna did not disclose the error rate. A resolution time of 2 minutes is only a meaningful improvement if the resolutions are correct. Customer service in the BNPL space involves disputed charges, fraud flags, account access issues, and repayment plans — categories where errors have real financial consequences for customers."
- C) ❌ API cost disclosure is not identified as the notable omission in the chapter's "What Klarna Didn't Disclose" section.
- D) ❌ Demographic breakdown of AI vs. human interactions is not the specific omission the chapter calls out.
- E) ❌ Engineer attribution is not the concern raised — the chapter focuses on outcome quality, not technical team identity.

</details>

---

## Question 10

The chapter discusses the gross margin implications of synthetic employee deployment for services businesses. What is the core economic argument?

- A) Services businesses with synthetic employees must report lower gross margins because AI costs are classified as COGS
- B) Replacing high-variable-cost human labor with AI subscriptions (lower marginal cost, no benefits, no overtime) structurally improves gross margins for services businesses — potentially enabling them to achieve software-like margins
- C) Synthetic employee costs must be capitalized on the balance sheet rather than expensed, improving gross margin optics
- D) Services businesses cannot deploy synthetic employees because their GAAP revenue recognition requires human delivery of services
- E) Synthetic employees reduce gross margins by increasing reliance on expensive AI API providers who extract value from the cost structure

<details>
<summary>Show Answer & Explanations</summary>

- A) ❌ The accounting classification of AI costs varies by type (COGS vs. operating expense), but the chapter's core argument is about the *economic improvement* in gross margins, not their accounting classification.
- ⭐ B) ✅ The chapter argues that services businesses — traditionally constrained to low gross margins (20–40%) by high labor costs — can structurally improve their economics by replacing variable human labor with AI subscriptions. A services firm that runs synthetic researchers, synthetic SDRs, and synthetic customer success agents approaches the cost structure of a software business, with its superior gross margin profile.
- C) ❌ Capitalization vs. expensing of AI costs is an accounting policy question not discussed as the gross margin improvement mechanism in the chapter.
- D) ❌ GAAP revenue recognition does not require human delivery for services — AI-delivered services can be recognized using the same frameworks. This constraint is fabricated.
- E) ❌ The chapter acknowledges AI API cost risk (the gross margin squeeze from Chapter 4) but argues the net economic effect of synthetic employee replacement is positive for services businesses, not negative.

</details>

---

*Quiz for Chapter 7 — Business Applications of Artificial Intelligence © Dr. Ernesto Lee, 2026.*
