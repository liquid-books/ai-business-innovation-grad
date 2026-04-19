---
title: "Introduction to AI Disruption"
subtitle: "The Business Model Canvas as a Disruption Map"
short_title: "Ch 1: AI Disruption"
description: "Why the current AI era represents a structural inflection, not a cyclical one. Nine BMC blocks, nine surfaces where AI is rewriting the rules."
label: ch-01-ai-disruption
tags: [AI disruption, Business Model Canvas, inflection, tool stack, LLMs]
---

# Introduction to AI Disruption

> *"AI doesn't disrupt one block of the Business Model Canvas. It disrupts all nine, simultaneously."*

:::{figure} ../images/ch01-overview-infographic.png
:label: fig-ch01-overview-infographic
:alt: Chapter 1 overview infographic showing AI disruption across the Business Model Canvas
:width: 90%
:align: center

A comprehensive overview of Chapter 1 concepts: the three-era inflection, the Business Model Canvas as a disruption map, and the AI tool stack that powers modern business innovation.
:::

---

## Learning Objectives

By the end of this chapter, you will be able to:

1. Distinguish the AI era from prior technological waves and explain why LLMs represent a structural inflection, not a cyclical trend.
2. Apply the Business Model Canvas (BMC) as a disruption diagnostic tool, identifying where AI creates value or existential risk in each of the nine blocks.
3. Evaluate the strategic trade-offs of early adoption versus late adoption using the winner's curse framework.
4. Configure a professional AI tool stack and navigate six core platforms fluently.
5. Analyze a real company (Shopify) through the lens of AI-native business model transformation.

---

## 1.1 The Inflection

:::{figure} ../images/ch01-three-eras-timeline.png
:label: fig-ch01-three-eras-timeline
:alt: Timeline of three technological eras: pre-internet, internet, and AI
:width: 85%
:align: center

The three great technological eras in modern business history. Each era compressed adoption timelines and raised the baseline capability required to compete. The AI era is compressing faster than any prior wave.
:::

### Three Eras of Business Technology

Every few decades, a technology arrives that does not merely improve how businesses operate — it rewrites what a business *is*. We have lived through two such moments in recent memory, and we are living through the third right now.

**Era 1: Pre-Internet (1960–1994)**
The foundational era of business computing was defined by automation of known processes. ERP systems (SAP, Oracle) automated accounting. Relational databases (IBM DB2, Oracle) structured inventory. EDI (Electronic Data Interchange) linked suppliers to retailers. The logic was simple: take a human task, replicate it in silicon, do it faster and cheaper. The adoption timeline stretched over 20–30 years. A Fortune 500 company that bought an IBM mainframe in 1970 faced minimal urgency — competitors were on the same adoption curve. The technology was expensive, required deep IT expertise, and served as a barrier to entry rather than a leveler.

**Era 2: The Internet Era (1995–2021)**
The internet collapsed geography and search costs. A startup in a garage could reach the same customer as a Fortune 500 company — if it could be found. Google made finding things cheap. Amazon made logistics cheap. Stripe made payments cheap. The defining dynamic was *disintermediation*: every layer of business that existed to mediate information (travel agents, stock brokers, classified ad publishers, encyclopedia salespeople) was compressed or eliminated. Adoption timelines shortened: a technology that took 20 years to penetrate in the pre-internet era now took 5–8 years. The winners were those who understood that software ate the world (Andreessen, 2011) before their industries did.

**Era 3: The AI Era (2022–present)**
Something different is happening now. The release of ChatGPT in November 2022 marked not just the launch of a product, but the public legibility of a capability that had been maturing in research labs for a decade. What changed was not compute power alone — it was *interpretability*. For the first time, a machine could receive an ambiguous, natural-language instruction and return a useful, contextually appropriate response. This is not retrieval. It is not pattern-matching in the narrow sense. It is *interpretation*.

:::{important}
**The key distinction of the AI era:** Prior AI systems (recommendation engines, fraud detection, image classifiers) operated on structured inputs and produced structured outputs within predefined problem spaces. Large Language Models operate on *unstructured human intent* and produce *novel outputs* across domains. The economic implications are categorically different.
:::

### Why LLMs Are Different: Interpretation, Not Retrieval

To understand why LLMs represent a structural break from prior AI systems, consider the following comparison:

::::{tab-set}
:::{tab-item} Prior AI Systems (1980–2021)
**Examples:** Spam filters, recommendation engines, fraud detection, image classifiers, search ranking

**How they work:**
- Trained on labeled datasets with clear right/wrong answers
- Operate within a closed problem space defined at training time
- Retrieve or classify based on statistical similarity
- Fail gracefully: uncertain = no action or escalate to human
- Require domain-specific retraining for each new task

**Business implication:** Automate repetitive decisions within known problem spaces. Replace or augment specific workers doing specific tasks. High cost per deployment, high specificity.
:::

:::{tab-item} LLMs and Foundation Models (2022–present)
**Examples:** GPT-4o, Claude, Gemini Pro, and Llama (latest versions)

**How they work:**
- Trained on the totality of human-written text (effectively)
- Operate across open problem spaces via natural language
- *Interpret* intent, context, and nuance — not just match patterns
- Generate novel outputs: text, code, plans, arguments, images
- Transfer across domains with minimal prompt engineering

**Business implication:** Automate *reasoning itself* across problem spaces. Replace or augment knowledge workers doing *complex, varied tasks*. Low marginal cost per deployment, extreme generality.
:::
::::

This distinction matters enormously for business strategy. When AI could only automate known, structured tasks, a company's competitive moat was still built on proprietary knowledge, relationships, and brand. When AI can *reason* — when it can synthesize a market analysis, draft a contract, write production code, plan a supply chain restructuring, and explain all of it in plain language — the moat shifts. Proprietary *data* becomes the moat, not the *knowledge workers* who interpret it.

:::{figure} ../images/ch01-llm-vs-prior-ai.png
:label: fig-ch01-llm-vs-prior-ai
:alt: Comparison diagram of LLM interpretation versus prior AI retrieval paradigms
:width: 85%
:align: center

LLMs operate in open problem spaces via natural language interpretation. Prior AI systems operated in closed, structured problem spaces. This is not a quantitative improvement — it is a qualitative shift in the type of work that can be automated.
:::

### The Compression of Adoption Timelines

History shows a consistent pattern: each technological wave compresses adoption timelines relative to the prior wave. The printing press took roughly 50 years to achieve widespread European adoption. Electricity took 40 years to penetrate American manufacturing. The telephone took 35 years to reach 50% of US households. The internet took approximately 7 years to reach 50% of the US population after the commercialization of the web browser. Smartphones reached 50% penetration in about 5 years.

ChatGPT reached 100 million users in *two months* — the fastest consumer technology adoption in history. By 2025, Andreessen Horowitz's State of AI report found that AI tool usage had penetrated 40% of knowledge workers globally, with enterprise AI budgets growing at 120% year-over-year.

:::{figure} ../images/ch01-adoption-compression.png
:label: fig-ch01-adoption-compression
:alt: Chart showing compression of adoption timelines across technological eras
:width: 85%
:align: center

Adoption timelines have compressed with each technological wave. The AI era is the fastest on record, with ChatGPT reaching 100 million users in two months. Business strategy windows are narrowing proportionally.
:::

What does this compression mean for business strategy? Simply: **the window for strategic positioning is shorter than it has ever been.** In the internet era, a company that recognized the threat in 2000 had until approximately 2005–2007 to build a response before incumbents were structurally disadvantaged. In the AI era, the equivalent window may be 12–24 months.

This is not hyperbole. Consider:

- **[Klarna](https://www.klarna.com)** deployed AI to replace 700 customer service agents in 2024. Within 12 months, it reported that its AI system handled 2/3 of customer service chats with satisfaction scores matching human agents — at 1/10th the cost.
- **Goldman Sachs** reported in 2025 that AI coding assistants had reduced software development time by 40% for its engineering teams, effectively expanding its engineering output without headcount growth.
- **[McKinsey's 2025 State of AI report](https://www.mckinsey.com/capabilities/quantumblack/our-insights/the-state-of-ai)** found that companies in the top quartile of AI adoption were achieving revenue growth 1.4x higher than their bottom-quartile peers — and that gap was *widening*.

### The Winner's Curse

The compression of adoption timelines creates a strategic paradox known in this context as the **winner's curse of AI adoption**. The term borrows from auction theory, where the winner of an auction tends to have overpaid because they have the highest estimate of value — often because they are also the most optimistic.

In the AI context, the winner's curse operates differently: **the companies that move first face the highest implementation costs and the lowest model quality, while the companies that move last face the highest competitive disadvantage.** Both extremes destroy value.

:::{figure} ../images/ch01-winners-curse.png
:label: fig-ch01-winners-curse
:alt: Risk matrix showing the winner's curse of AI adoption - moving too slow vs too fast
:width: 80%
:align: center

The winner's curse of AI adoption. Moving too early incurs high implementation costs and low model quality. Moving too late incurs structural competitive disadvantage. The optimal window is narrowing as adoption compresses.
:::

The optimal adoption strategy is neither first-mover nor fast-follower in the classical sense. It is **informed early majority**: move after the technology has achieved sufficient reliability for production use, but before the late majority normalizes it. In 2026, we are at or approaching this inflection for most enterprise AI applications.

:::{note}
**A note on model quality:** Each successive wave of frontier models has represented step-change improvements in benchmark performance over predecessors. The practical implication: tasks that were not reliably automatable two years ago are routinely automated today. Strategic plans built on two-year-old AI capabilities are already outdated.
:::

:::{dropdown} Deep Dive: The Diffusion of Innovations Framework Applied to AI

Everett Rogers' Diffusion of Innovations (1962) remains the most durable framework for understanding technology adoption. His five adopter categories — Innovators (2.5%), Early Adopters (13.5%), Early Majority (34%), Late Majority (34%), and Laggards (16%) — describe adoption curves that are S-shaped across all technologies.

In the AI era, Rogers' framework requires one critical update: **the chasm between Early Adopters and Early Majority has compressed dramatically.** In Geoffrey Moore's famous extension of Rogers (Crossing the Chasm, 1991), this chasm was characterized by a product maturity gap — early adopters tolerate rough edges that early majority buyers reject.

For AI tools, the rough edges are disappearing faster than any prior technology. Claude, ChatGPT, and Gemini are already "good enough" for the Early Majority across most knowledge-work use cases. This means the strategic window for crossing the chasm is shorter, and the penalty for remaining in the laggard category is more severe.

**What this means for your company:** If your organization has not yet integrated AI into at least three core business processes, you are statistically in the Late Majority. The gap between your productivity trajectory and that of your Early Majority competitors is compounding monthly.

**Recommended reading:** Rogers, E.M. (2003). *Diffusion of Innovations* (5th ed.). Free Press. Moore, G.A. (2014). *Crossing the Chasm* (3rd ed.). HarperBusiness.
:::

---

## 1.2 The Business Model Canvas as a Disruption Map

:::{figure} ../images/ch01-bmc-disruption-map.png
:label: fig-ch01-bmc-disruption-map
:alt: Full Business Model Canvas with AI disruption overlay showing which blocks are most affected
:width: 90%
:align: center

The Business Model Canvas with AI disruption intensity overlaid. All nine blocks are affected, but the intensity and mechanism vary. The most acute disruptions are occurring in Value Propositions, Key Resources, Cost Structure, and Customer Relationships.
:::

Osterwalder and Pigneur's Business Model Canvas (2010) is the dominant framework for visualizing and analyzing business models. Originally designed as a tool for design and iteration, it has become, in the AI era, an indispensable diagnostic for disruption. Each of the nine blocks represents a surface where AI is simultaneously creating new value and destroying old competitive positions.

:::{tip}
**BMC Template:** Download the Business Model Canvas Word template for this course here: [Business-Model-Canvas-Word-Template.docx](https://github.com/liquid-books/ai-business-innovation-grad/blob/main/docs/ch1/Business-Model-Canvas-Word-Template-v3-hwiqaj.docx). You will use this template for Lab assignments throughout the semester.
:::

:::{important}
The Business Model Canvas is not a static snapshot. In the AI era, treat it as a **dynamic map** that requires quarterly review. A block that was stable in Q1 2025 may be fundamentally different by Q4 2025 as new AI capabilities emerge.
:::

The canvas framework is deceptively simple. Behind each block lies a complex set of assumptions about how value is created, delivered, and captured. AI disrupts these assumptions — sometimes subtly, sometimes catastrophically.

```{mermaid}
graph TD
    A[Business Model Canvas] --> B[Customer Segments]
    A --> C[Value Propositions]
    A --> D[Channels]
    A --> E[Customer Relationships]
    A --> F[Revenue Streams]
    A --> G[Key Resources]
    A --> H[Key Activities]
    A --> I[Key Partnerships]
    A --> J[Cost Structure]

    B --> B1["AI Impact: Segment-of-one\nhyper-personalization"]
    C --> C1["AI Impact: Dynamic value props\nco-created with AI"]
    D --> D1["AI Impact: Conversational\nchannels replace browse-first"]
    E --> E1["AI Impact: Always-on\npersonalized agents"]
    F --> F1["AI Impact: Usage-based\noutcome-based pricing"]
    G --> G1["AI Impact: Data and models\nbecome primary resources"]
    H --> H1["AI Impact: AI-augmented\nknowledge work at scale"]
    I --> I1["AI Impact: AI vendors\nbecome critical partners"]
    J --> J1["AI Impact: Marginal cost\nof knowledge work → 0"]
```

### Block 1: Customer Segments

**Traditional definition:** The groups of people or organizations a business aims to reach and serve. Segments are defined by shared characteristics: demographics, psychographics, geography, behavior, or need.

**How AI disrupts it:** AI is collapsing the granularity of segmentation toward its theoretical limit: **the segment of one**. Traditional segmentation grouped customers because personalization was expensive — it required human labor to customize offers, content, and communication for each individual. AI makes this labor negligible.

:::{figure} ../images/ch01-customer-segments-ai.png
:label: fig-ch01-customer-segments-ai
:alt: Diagram showing AI-powered hyper-personalization from broad segments to segment-of-one
:width: 80%
:align: center

AI-powered hyper-personalization collapses the traditional segmentation hierarchy. Where mass marketing served millions with one message and traditional segmentation served segments with tailored messages, AI can serve each individual with a dynamically generated, contextually optimal experience.
:::

**Current examples (2025–2026):**

- **Netflix's AI personalization engine** now generates individualized thumbnail artwork, trailer cuts, and content recommendations that vary by user, device, time of day, and emotional state inferred from viewing patterns. The result: a measurable reduction in churn and a 35% increase in content discovery per session.
- **Spotify's DJ feature** uses AI to generate personalized audio commentary between songs, creating the experience of a radio DJ who knows the listener intimately. This feature drove a 12% increase in premium subscriptions among users who engaged with it in 2024.
- **Stitch Fix** has used AI-driven segment-of-one styling since 2019, but its 2025 "StyleAI" system goes further: synthesizing purchase history, social media preferences inferred from browsing data, and seasonal context to produce style recommendations that beat human stylists on customer satisfaction scores.

**Strategic implication:** Companies that continue to operate with coarse segmentation (e.g., "millennial women, income $50K–$80K") are leaving conversion and retention on the table. The segmentation advantage now belongs to those with the richest first-party data and the AI infrastructure to activate it.

### Block 2: Value Propositions

**Traditional definition:** The bundle of products and services that create value for a specific Customer Segment. The value proposition answers the question: why should a customer choose us?

**How AI disrupts it:** AI creates value propositions that were previously impossible: propositions that are **dynamic** (changing in real-time based on context), **co-created** (built in dialogue with the customer), and **compound** (aggregating capabilities that previously required multiple vendors).

**Current examples:**

- **[Harvey AI](https://www.harvey.ai)** (legal) offers a value proposition impossible before LLMs: a junior associate-level legal research and drafting capability available 24/7 at $0.01 per task. This is not faster legal research — it is a *new value proposition* for legal work that displaces the hourly billing model.
- **[GitHub Copilot](https://github.com/features/copilot)** offers "pair programming with an AI that knows every public codebase." In 2025, GitHub reported that Copilot users completed tasks 55% faster and wrote code with 40% fewer bugs. This is not an incremental improvement — it is a step-change in what developer productivity means.
- **Glean** (enterprise search) promises that every employee can find any internal information in seconds. This proposition was technically achievable before LLMs but economically unviable. With AI, Glean's indexing and retrieval intelligence makes the proposition both achievable and affordable.

**Strategic implication:** Audit your current value proposition against this question: *Is this proposition becoming more or less differentiated as AI capabilities improve?* If a competitor can now deliver your core value proposition with AI at 1/10th the cost, your moat is eroding.

### Block 3: Channels

**Traditional definition:** The touchpoints through which a company communicates with and reaches its Customer Segments to deliver a Value Proposition.

**How AI disrupts it:** AI is fundamentally changing the *nature* of channels, not just their efficiency. The shift is from **browse-first** channels (websites, stores, app catalogs) to **conversational-first** channels (AI agents, voice interfaces, chat-native experiences).

**Current examples:**

- **[Perplexity AI](https://www.perplexity.ai)** has grown to 20 million daily active users by 2025 as an AI-native search channel. Brands that optimized for Google SEO now face a new channel: AI answer engines that synthesize information rather than list links. Winning in this channel requires being cited *by AI*, not just ranked *by algorithms*.
- **[Shopify](https://www.shopify.com)'s AI storefront assistant** allows customers to describe what they want in natural language ("I need a birthday gift for my sister who loves hiking, budget $50–$80") and receive curated recommendations. This collapses the browse-and-filter UX into a conversational experience.
- **Duolingo's AI tutor** (Max) replaced much of the app-based lesson structure with conversational practice. Engagement time per session increased 30% as users found the conversational format more natural and effective.

**Strategic implication:** Your channel strategy must now include AI-mediated channels. This means optimizing for AI discoverability (structured data, authoritative content), building conversational interfaces, and understanding how AI agents make recommendations on behalf of users.

### Block 4: Customer Relationships

**Traditional definition:** The types of relationships a company establishes with specific Customer Segments — from self-service to dedicated personal assistance, from transactional to community-based.

**How AI disrupts it:** AI enables a new category of customer relationship: **the always-on, personalized AI companion** that combines the warmth of a dedicated personal advisor with the scale of self-service. This collapses the traditional trade-off between relationship depth and operational cost.

**Current examples:**

- **[Klarna](https://www.klarna.com)'s AI assistant** serves as a shopping advisor, financial manager, and customer service agent simultaneously. In 2024, it handled 2.3 million customer conversations in a single day — equivalent to the workload of 5,000 human agents. Customer satisfaction scores were within 2 points of human agent performance.
- **Salesforce Einstein AI** provides sales representatives with real-time relationship intelligence: flagging at-risk accounts, recommending next best actions, and drafting personalized outreach. The result is not just efficiency — it is a *qualitatively different relationship* between the sales rep, the AI, and the customer.
- **Woebot** (mental health) has demonstrated that AI companions can maintain therapeutic-quality relationships with users experiencing mild anxiety and depression, with clinical outcomes comparable to CBT for select conditions (Fitzpatrick et al., 2017). By 2025, Woebot served over 4 million users — a scale no human therapist workforce could match.

### Block 5: Revenue Streams

**Traditional definition:** The cash a company generates from each Customer Segment. Revenue models include asset sales, usage fees, subscription fees, licensing, brokerage fees, and advertising.

**How AI disrupts it:** AI is enabling entirely new revenue architectures built around **outcomes** rather than inputs, and **usage** rather than access. The shift is from "pay for the software" to "pay for the result."

:::{figure} ../images/ch01-revenue-streams-ai.png
:label: fig-ch01-revenue-streams-ai
:alt: Comparison of traditional vs AI-era revenue models showing usage-based and outcome-based pricing
:width: 80%
:align: center

The AI era is accelerating a shift from access-based (subscription) revenue models to usage-based and outcome-based models. This shift fundamentally changes customer acquisition economics, pricing strategy, and retention dynamics.
:::

**Current examples:**

- **EvenUp** (legal AI) charges law firms a percentage of settlements secured using its AI-generated demand letters. This outcome-based model was only possible because EvenUp's AI is measurably predictive of settlement outcomes. They price on value, not inputs.
- **Otter.ai** shifted from a flat subscription to a usage-based model in 2024, charging per meeting transcribed. As transcription became a commodity, the differentiation moved to analysis and action item extraction — each billed as a premium add-on.
- **Palantir's AI Platform (AIP)** uses a hybrid model: a base subscription for platform access plus outcome-linked bonuses for measurable operational improvements. For a defense contractor client in 2025, this translated to $40M in outcome fees on a $10M platform subscription.

**Strategic implication:** Evaluate whether your current pricing model is aligned with the value AI is actually creating for your customers. If your customers are capturing AI-generated value that you are not pricing, you are leaving money on the table.

### Block 6: Key Resources

**Traditional definition:** The most important assets required to make a business model work — physical, intellectual, human, or financial.

**How AI disrupts it:** **Data and AI models** are emerging as the dominant Key Resources in the AI era, displacing human expertise and physical assets in many business models. The competitive moat is shifting from "we have the best people" to "we have the best data and the best models trained on it."

**Current examples:**

- **Bloomberg GPT** (2023) demonstrated that a domain-specific LLM trained on proprietary financial data outperformed general-purpose LLMs on financial tasks. Bloomberg's decades of structured financial data became a competitive resource for AI development.
- **Veeva Systems** (life sciences SaaS) built a competitive moat around clinical trial data and regulatory documentation. Its AI layer, trained on this proprietary corpus, now provides predictive analytics on drug approval probability — a capability no competitor can replicate without the data.
- **DeepMind's AlphaFold** demonstrated that AI models, once trained, become intellectual property of extraordinary value. AstraZeneca licensed AlphaFold access to accelerate drug discovery — paying for the *model*, not the *people* who built it.

**Strategic implication:** Audit your Key Resources with fresh eyes: what data do you generate that is proprietary, high-quality, and large-scale? That data is likely your most important AI resource. If you are not capturing, labeling, and securing it, you are not building an AI-era competitive moat.

### Block 7: Key Activities

**Traditional definition:** The most important things a company must do to make its business model work — production, problem solving, platform/network management.

**How AI disrupts it:** AI is restructuring what "doing" means. Activities that once required large teams of skilled workers are now AI-augmented or AI-executed. **The key activity is increasingly the design and management of AI systems**, rather than the execution of the underlying tasks those systems perform.

**Current examples:**

- **Jasper AI** (content marketing) shifted its key activity from content creation to **content strategy and AI orchestration**. Its platform allows marketing teams to define brand voice, generate content at scale, and optimize for performance — with minimal human writing involved in execution.
- **Legalzoom's AI document generation** shifted the key activity of legal document creation from licensed attorneys to AI systems, with attorneys focusing on edge cases and quality assurance. This restructured both cost structure and human capital requirements.
- **Waymo** (autonomous vehicles) illustrates the extreme end: the entire key activity of driving has been delegated to AI systems, with human Key Activities reduced to fleet management, safety monitoring, and regulatory compliance.

### Block 8: Key Partnerships

**Traditional definition:** The network of suppliers and partners that make the business model work. Partnerships range from strategic alliances to supplier relationships to joint ventures.

**How AI disrupts it:** A new category of critical partner has emerged: **AI foundation model providers**. OpenAI, Anthropic, Google, and Meta have become infrastructure-layer partners for thousands of businesses — with all the strategic risks that infrastructure dependency implies.

**Current examples:**

- **[Cursor](https://www.cursor.com)** (AI code editor) built its entire product on top of Anthropic's Claude API. When Anthropic changed its API pricing in 2024, Cursor's unit economics were directly impacted — illustrating the platform risk of a single AI partner dependency.
- **Intercom** integrated multiple AI providers (OpenAI, Anthropic) into its customer service platform, explicitly to reduce single-provider risk. By 2025, this multi-model architecture had become a standard recommendation for enterprise AI procurement.
- **Microsoft's OpenAI partnership** ($13B investment) is the defining example of AI partnerships reshaping competitive positions. Microsoft's integration of GPT-4 across Office 365, GitHub, Azure, and Bing created a compounding competitive advantage that Google, Amazon, and Salesforce scrambled to replicate with their own AI partner ecosystems.

:::{warning}
**Key Partnership Risk in the AI Era:** Building your business model on top of a single AI provider's API creates a dependency risk analogous to building on a single cloud provider in 2010. Best practices in 2025 include: multi-model architectures, model-agnostic abstraction layers, fine-tuned open-source alternatives, and contractual SLA protections with AI providers.
:::

### Block 9: Cost Structure

**Traditional definition:** The costs incurred to operate a business model — fixed costs, variable costs, economies of scale, economies of scope.

**How AI disrupts it:** AI is driving the marginal cost of knowledge work toward zero. This is the most structurally disruptive force in the entire canvas, because it collapses the cost advantage of scale that large incumbents have historically enjoyed.

**Current examples:**

- **Duolingo** reduced its contractor translator workforce by 10% in 2024, explicitly citing AI as the replacement. The cost of content localization — a historically expensive, human-intensive activity — collapsed. The savings were reinvested in AI product development.
- **IBM** announced a pause on hiring for 7,800 positions expected to be replaced by AI in 2023. By 2025, IBM reported that AI had replaced 40% of its HR functions with a 25% improvement in processing speed and a 30% reduction in error rates.
- **Chegg** reported a 48% revenue decline in 2023–2024, directly attributing the loss to students using ChatGPT instead of its tutoring subscription. The cost structure of human tutoring could not compete with the near-zero marginal cost of AI tutoring.

**Strategic implication:** The zero-marginal-cost economics of AI knowledge work mean that cost leadership strategies based on labor arbitrage are increasingly fragile. If your cost advantage is built on cheap knowledge workers (offshore outsourcing, large analyst teams), model the scenario where AI reduces that cost to near zero for your competitors.

---

## 1.3 The Tool Stack / Lab Setup

:::{figure} ../images/ch01-tool-stack-overview.png
:label: fig-ch01-tool-stack-overview
:alt: Diagram of the six core AI tools ecosystem for business education and innovation
:width: 85%
:align: center

The six-tool AI stack for this course. Each tool occupies a distinct role in the AI-native workflow: conversational reasoning, knowledge synthesis, experimentation, advanced reasoning, code development, and collaborative creation. Together, they form an end-to-end innovation stack.
:::

This course is built around a philosophy: **you cannot teach AI business strategy from the outside.** You must use the tools, internalize their capabilities and limitations, and develop intuitions that can only come from hands-on practice.

The following six tools constitute your primary workbench. All are free or have generous free tiers. All are used by professional AI practitioners in 2025–2026.

:::{tip}
**Before your first lab session:** Create accounts on all six platforms. Use the same email address for professional continuity. Keep a private doc with your login credentials and initial impressions after your first 30 minutes on each platform.
:::

```{mermaid}
flowchart LR
    subgraph Core_Reasoning ["Core Reasoning"]
        A["gemini.google.com\nConversational AI\nMultimodal reasoning"]
        B["claude.ai\nAdvanced reasoning\nLong-context analysis"]
    end
    subgraph Knowledge ["Knowledge & Research"]
        C["notebooklm.google.com\nDocument synthesis\nSource-grounded answers"]
    end
    subgraph Development ["Development & Experimentation"]
        D["aistudio.google.com\nAPI access & prompting\nModel comparison"]
        E["Claude Code\nAI-native coding\nFull codebase awareness"]
    end
    subgraph Collaboration ["Creative & Collaboration"]
        F["Google Antigravity\nTeam AI workspace\nShared context"]
    end

    A --> C
    B --> E
    D --> E
    C --> F
```

### Tool 1: [gemini.google.com](https://gemini.google.com)

Gemini is Google's flagship conversational AI, powered by the latest Gemini Pro model. For business applications, Gemini's distinguishing features are:

- **Multimodal reasoning:** Gemini can analyze images, PDFs, spreadsheets, and video alongside text. Upload a competitor's annual report and ask Gemini to identify their AI investment signals.
- **Deep Research mode:** Gemini's Deep Research feature conducts multi-step web research and synthesizes findings into structured reports — replacing 4–6 hours of analyst work in 20–30 minutes.
- **Google Workspace integration:** Gemini is embedded in Docs, Sheets, Gmail, and Slides, allowing AI assistance within your existing workflow.

**Best use cases in this course:** Market research, competitive analysis, document summarization, brainstorming, drafting.

### Tool 2: [notebooklm.google.com](https://notebooklm.google.com)

NotebookLM is Google's document-grounded AI workspace. Unlike general-purpose chatbots, NotebookLM is explicitly anchored to documents *you* upload. It will not hallucinate facts outside your source material — and it will cite the page and paragraph for every claim.

**Best use cases in this course:** Analyzing academic papers, synthesizing primary research, preparing for case study discussions, building literature reviews.

:::{note}
**NotebookLM is the most underrated tool in this stack.** For academic work, its source-citation discipline makes it substantially more reliable than general-purpose AI for research tasks. Upload your course readings and your external research sources, then query across all of them simultaneously.
:::

:::{seealso}
**Chapter 1 NotebookLM Resource:** A shared NotebookLM notebook for this chapter — loaded with course readings, case studies, and supplementary materials — is available at: [notebooklm.google.com/notebook/0c144708-1215-4c1d-81e0-c2c9ee33fa85](https://notebooklm.google.com/notebook/0c144708-1215-4c1d-81e0-c2c9ee33fa85). Ask it any questions about the chapter content, and it will respond with citations from the source materials.
:::

### Tool 3: [aistudio.google.com](https://aistudio.google.com)

Google AI Studio is the developer-facing interface for Google's Gemini family of models. It provides:

- **Prompt engineering workspace:** Test prompts, compare outputs, and refine systematically.
- **Model selection:** Compare Gemini Pro, Flash, and specialized variants.
- **API key management:** Generate API keys for programmatic access.
- **Grounding with Google Search:** Enable real-time web search augmentation for time-sensitive queries.

**Best use cases in this course:** Prompt engineering, API experimentation, building custom AI workflows, testing model performance on business tasks.

### Tool 4: [claude.ai](https://claude.ai)

Anthropic's Claude is, as of 2025–2026, the most capable AI system for complex reasoning, nuanced writing, and long-context analysis. Claude's distinguishing features:

- **Extended thinking:** Claude's extended thinking mode shows its reasoning process, enabling you to audit and guide its logic.
- **200K token context window:** Claude can hold an entire book, legal contract, or financial model in context simultaneously.
- **Constitutional AI:** Anthropic's safety training makes Claude notably more careful about uncertainty, more likely to express doubt when appropriate, and less prone to confident confabulation.

**Best use cases in this course:** Complex analysis, long-document work, nuanced strategic reasoning, writing with high accuracy requirements.

### Tool 5: Claude Code

Claude Code is Anthropic's AI-native coding agent — distinct from claude.ai in that it operates as a terminal-based agent with full access to your codebase, file system, and development environment.

**What this means in practice:**
- Claude Code can read, write, and execute code across your entire project
- It can install dependencies, run tests, debug errors, and refactor architecture
- It operates autonomously on multi-step tasks: "build a web scraper for competitor pricing" → runs for 10 minutes → returns working code

**Best use cases in this course:** Lab assignments with coding components, building MVPs, data analysis automation.

:::{tip}
You do not need to be a professional developer to use Claude Code productively. If you can describe what you want in plain English, Claude Code can typically produce working code. The skill is in precise problem specification — which is itself a valuable business skill.
:::

### Tool 6: Google Antigravity

Google Antigravity (formerly known as Google Labs' Workspace AI collaboration tools) represents Google's vision for AI-native collaborative work. It enables:

- **Shared AI context:** Multiple team members working with a shared AI that has context on the team's collective knowledge
- **Workflow automation:** Connecting AI reasoning to document creation, email, calendar, and project management
- **Enterprise-grade privacy:** All data processed within Google's enterprise security boundary

**Best use cases in this course:** Team projects, capstone work, building shared knowledge bases.

### Supporting Tools

| Tool | Purpose | Free Tier |
|------|---------|-----------|
| **[GitHub](https://github.com)** | Code repository, version control, deployment | Free for public repos |
| **[Cursor](https://www.cursor.com)** | AI-native code editor (VS Code with AI) | 2-week trial, then $20/mo |
| **[Obsidian](https://obsidian.md)** | Personal knowledge management, linked notes | Free for personal use |

:::{tip}
**Obsidian as a learning accelerator:** Many of the most effective AI practitioners maintain a "second brain" in Obsidian — a personal knowledge base of prompts, frameworks, case study notes, and mental models. Consider building your Obsidian vault as a parallel project throughout this course.
:::

---

## Case Study: Shopify's Transformation from Commerce Platform to AI-Native Merchant OS

:::{figure} ../images/ch01-shopify-transformation.png
:label: fig-ch01-shopify-transformation
:alt: Shopify's Business Model Canvas before and after AI transformation
:width: 90%
:align: center

Shopify's Business Model Canvas evolution: from a commerce platform (2015–2021) to an AI-native merchant operating system (2023–2026). The transformation affects all nine BMC blocks, illustrating how AI can drive comprehensive rather than incremental business model change.
:::

### Background

Shopify was founded in 2006 by Tobias Lütke, who built the platform out of frustration with existing e-commerce software while trying to sell snowboards online. By 2021, Shopify powered 1.7 million merchants globally and had a market capitalization of $185 billion — briefly making Lütke one of the wealthiest people in Canada.

Then came 2022. Post-pandemic normalization of e-commerce growth, rising interest rates, and competition from Amazon, TikTok Shop, and Wix compressed Shopify's market cap to $35 billion by late 2022. The company was forced to lay off 10% of its workforce and confront an existential question: *What is Shopify's value proposition in a world where AI can do much of what Shopify's human services do?*

Lütke's answer was not defensive. In a 2023 letter to employees, he wrote: "Shopify Sidekick is the most important product we've ever built." Sidekick was not a feature — it was a strategic repositioning.

### The BMC Analysis: Before and After

**Before (2015–2021): The Commerce Platform**

| Block | Description |
|-------|-------------|
| Customer Segments | Small-to-medium merchants; direct-to-consumer brands |
| Value Proposition | "Commerce made easy" — turnkey online store with payments, inventory, shipping |
| Channels | SEO/content marketing, partner app marketplace, word of mouth |
| Customer Relationships | Self-service SaaS; Shopify Plus for enterprise (dedicated support) |
| Revenue Streams | Monthly subscription tiers; Shopify Payments transaction fees |
| Key Resources | Platform infrastructure; payment network; app ecosystem (7,000+ apps) |
| Key Activities | Platform development; merchant acquisition; payment processing |
| Key Partnerships | Payment processors; shipping carriers; app developers |
| Cost Structure | Infrastructure; R&D; S&M at 30–40% of revenue |

**After (2023–2026): The AI-Native Merchant OS**

| Block | Description |
|-------|-------------|
| Customer Segments | Same base + new segments: enterprise merchants requiring AI capabilities |
| Value Proposition | "AI that runs your store" — Sidekick handles marketing copy, inventory forecasting, customer segmentation, and support |
| Channels | Conversational AI onboarding; AI-generated storefront personalization |
| Customer Relationships | Sidekick as always-on AI business advisor for every merchant |
| Revenue Streams | New: AI add-on subscriptions; outcome-based pricing pilots for AI-driven revenue uplift |
| Key Resources | Merchant transaction data (billions of data points on purchasing behavior); AI models trained on this corpus |
| Key Activities | AI model training on proprietary merchant data; Sidekick capability expansion |
| Key Partnerships | OpenAI (Sidekick engine); Google (search and shopping integrations); logistics AI partners |
| Cost Structure | Shift: infrastructure costs rising (AI inference); headcount costs falling (AI replaces support and content roles) |

### The Strategic Insight

Shopify's most defensible asset was never its software — it was the **behavioral data generated by 2+ million merchants and their customers.** This data, accumulated over 17 years, represents purchasing patterns, conversion rates, inventory dynamics, and marketing effectiveness across virtually every product category.

By training AI models on this proprietary corpus, Shopify created a moat that a startup with equivalent AI talent cannot replicate without equivalent data. The AI capability *is* the data — and the data *is* the competitive advantage.

**Key lessons from Shopify's transformation:**

1. **Incumbents with data moats can win the AI transition** — if they move before their data advantage erodes.
2. **AI repositions existing resources as competitive advantages** — Shopify's transaction data was valuable before AI; it is now *the* primary competitive resource.
3. **The value proposition shifts from tool to advisor** — Shopify went from "here's a platform" to "here's an AI that helps your business grow."
4. **Revenue model evolution follows capability evolution** — as Sidekick demonstrably drives merchant revenue, outcome-based pricing becomes viable.

:::{note}
**2025 Update:** Shopify's market cap recovered to $100B+ by Q3 2025, driven significantly by Sidekick adoption (30% of Plus merchants actively using AI features) and the launch of Shopify Magic (generative AI for product descriptions, marketing campaigns, and customer segmentation). The AI pivot has been validated by the market.
:::

---

## Lab 1: The Tool Gauntlet

**Objective:** Achieve baseline proficiency across all six core AI tools by completing a structured series of tasks that mirror real business use cases.

**Estimated time:** 3–4 hours (can be spread across multiple sessions)

**Deliverable:** A 500-word reflection document submitted to the course LMS describing your experience, surprises, and initial mental model of each tool's strengths and limitations.

### Lab Tasks

:::{important}
**A Note on Prompting: Meta-Prompting Is Required**

The prompts provided in each task below are **starter prompts only**. They are intentionally minimal — designed to get you oriented to the tool, not to produce the best possible output. A weak, one-sentence prompt will produce a weak output. That is by design.

The expectation for every lab in this course is that you will **meta-prompt**: use AI to improve your prompt before submitting it to the task. Meta-prompting means asking an AI (Claude or Gemini work well for this) to help you turn a basic prompt into a high-quality, professional prompt.

**How to meta-prompt:**
1. Start with the starter prompt provided.
2. Open Claude or Gemini and say: *"I need to write a high-quality prompt for an AI assistant to accomplish the following task: [paste your starter prompt]. Help me expand it into a thorough, 2–3 paragraph prompt that specifies the role, context, output format, quality criteria, and any constraints. Make it significantly better than the starter."*
3. Review the improved prompt, refine it to match your specific needs, and use *that* as your actual prompt for the task.

Your submitted lab work should reflect a prompt of 2–3 substantial paragraphs — not a one-liner. Instructors will assess prompt quality as part of the lab evaluation. Over the course of the semester, your prompting skills are expected to compound. By Chapter 9, your prompts should be dramatically more sophisticated than your Chapter 1 prompts.
:::

**Task 1: Gemini — Market Landscape Analysis (45 min)**
1. Open [gemini.google.com](https://gemini.google.com) and enable Deep Research mode.
2. Prompt: *"Conduct a comprehensive analysis of the AI-powered customer service market in 2025–2026. Identify the top 5 players, their business models, pricing, and key differentiators. Format as a structured report."*
3. Review the output. Identify 2 claims you want to verify independently.
4. Verify those claims using NotebookLM (see Task 2) or direct web search.

**Task 2: NotebookLM — Source Synthesis (30 min)**
1. Upload 3 documents to [notebooklm.google.com](https://notebooklm.google.com): (a) any academic paper on AI in business from [Google Scholar](https://scholar.google.com), (b) a competitor's annual report or 10-K filing from [SEC.gov](https://www.sec.gov/cgi-bin/browse-edgar), (c) any news article about an AI business application from the past 6 months.
2. Ask NotebookLM: *"What are the three most important claims these sources make about AI's impact on business? Where do they agree and disagree?"*
3. Note how NotebookLM cites sources. Compare to how Gemini responded in Task 1.

**Task 3: AI Studio — Prompt Engineering (30 min)**
1. Open [aistudio.google.com](https://aistudio.google.com) and select the latest Gemini Pro model.
2. Write a prompt to analyze a business problem of your choice. Test three variations:
   - A brief, conversational prompt (1–2 sentences)
   - A structured prompt with role, context, task, and format instructions
   - A chain-of-thought prompt that asks the model to reason step by step
3. Document how output quality changes across prompt types. This is your first prompt engineering experiment.

**Task 4: Claude — Long-Context Analysis (30 min)**
1. Open [claude.ai](https://claude.ai) and select the latest Claude model.
2. Upload this chapter (or a document of 10,000+ words of your choice).
3. Ask Claude: *"Identify the three most contestable claims in this document. For each, provide the strongest counterargument, evidence that might support the claim, and your overall assessment of the claim's defensibility."*
4. Enable extended thinking if available. Observe how the reasoning process differs from standard responses.

**Task 5: Claude Code — First AI Coding Experience (45 min)**
1. Install Claude Code following the setup guide at docs.anthropic.com/claude-code.
2. Create a new folder: `lab01-data-analysis/`
3. Prompt Claude Code: *"Create a Python script that downloads stock price data for three companies of my choice using the yfinance library, calculates their 30-day and 90-day moving averages, and generates a comparison chart. Include comments explaining each step."*
4. Run the generated code. Note any errors and how Claude Code responds to them.

**Task 6: Tool Integration — Connecting the Stack (30 min)**
1. Take the market analysis from Task 1 (Gemini) and the source synthesis from Task 2 (NotebookLM).
2. Open Claude and paste both outputs.
3. Prompt: *"I have an AI market analysis and a synthesis of academic sources on AI in business. Identify the three biggest gaps between what industry analysts are saying and what academic research suggests. What should a business strategist pay attention to that both sources might be missing?"*
4. Reflect: what happened when you connected multiple AI tools in sequence? What was the output quality compared to any single tool?

---

### AI Studio Build — Weekly Application

**This is not optional.** Every chapter in this course includes an AI Studio Build assignment. This is how you learn to build, not just analyze.

**The BMC Disruption Analyzer**

In [aistudio.google.com](https://aistudio.google.com), you will build a shareable AI application — your first of nine.

**What you are building:** A system-prompted Gemini application that functions as an industry-disruption analyst. When a user enters any industry name, the app returns a structured analysis of how AI disrupts each of the nine BMC blocks for that industry, with a specific real-world example per block.

**Step-by-step:**

1. Open [aistudio.google.com](https://aistudio.google.com) and navigate to **"Build"** (not "Stream Realtime" or "Prompt").
2. In the **System Instructions** field, write your system prompt. This is where you define what your application does, how it behaves, and what format it outputs. (Apply meta-prompting here — use Claude to help you write a thorough system prompt before pasting it into AI Studio.)
3. A strong system instruction for this application will specify:
   - The AI's role (industry disruption analyst with deep business strategy expertise)
   - The exact output structure (one section per BMC block, with a concrete example for each)
   - The tone (analytical, evidence-based, specific — not vague or generic)
   - The quality bar (examples must name specific companies, technologies, or business models — no abstract generalities)
4. Test your application by entering at least **three industries** of your choosing. Review the outputs critically: Are the examples specific? Are the disruption mechanisms accurate? Refine your system prompt iteratively until you are satisfied.
5. Use the **Share** function in AI Studio to generate a public share link.

**Deliverable:** Submit (a) your AI Studio share link, (b) the full text of your system instruction, and (c) sample outputs for three industries of your choosing. Your system instruction alone should be 2–3 substantial paragraphs.

**What you are learning:** System instructions, structured prompting, output format control, and iterative prompt refinement. These are the foundational skills for every AI Studio build in subsequent chapters.

:::{tip}
**Build on AI Studio, not just in it.** The shift from "using AI Studio to run prompts" to "building with AI Studio to create shareable tools" is the shift from AI consumer to AI builder. This course trains the latter. Every AI Studio Build assignment compounds on the last — by Chapter 9, you will have built nine interconnected tools that together form your AI innovation toolkit.
:::

---

## Discussion Prompts

:::{important}
**Discussion Guidelines:** Your initial post should be 300–400 words and include at least **two scholarly citations** in APA format. After posting, respond substantively to **two peers' posts** — your responses should advance the conversation with new evidence, alternative frameworks, or respectful challenge to your peer's claims.
:::

### Discussion 1: The Winner's Curse in Your Industry

Select an industry you are familiar with (your current industry, a prior employer, or an industry you find strategically interesting). Apply the winner's curse framework from Section 1.1 to analyze the current AI adoption landscape in that industry.

In your post:
- Identify where your chosen industry currently sits on the AI adoption curve (innovator, early adopter, early majority, late majority, or laggard)
- Cite at least one specific company that has moved early and describe the outcomes (positive or negative)
- Cite at least one specific company that has moved late and describe the competitive consequences
- Argue for the adoption strategy you believe is optimal for a new entrant in this industry in 2026

Support your argument with scholarly sources on technology adoption and at least one recent news source (no more than two years old) documenting AI adoption patterns in your chosen industry.

### Discussion 2: The BMC Disruption Audit

Select a company you admire or find strategically interesting. Conduct a focused BMC disruption audit.

In your post:
- Identify the **single most disrupted block** in your chosen company's BMC and explain, with evidence, why you assess it as the most disrupted
- Identify the **block most likely to become a competitive advantage** if the company executes its AI strategy well
- Argue whether this company is more likely to be an AI winner or loser over the next three years, using specific evidence from public sources

Your post should demonstrate familiarity with at least one of these frameworks from your readings: Disruption theory (Christensen), Platform dynamics (Parker, Van Alstyne & Choudary), or Dynamic capabilities (Teece).

---

## Readings

**Required:**

- Osterwalder, A., & Pigneur, Y. (2010). [*Business model generation: A handbook for visionaries, game changers, and challengers*](https://www.strategyzer.com/library/the-business-model-canvas). Wiley. (Chapters 1–2: The Canvas)
- Christensen, C.M., McDonald, R., Altman, E.J., & Palmer, J.E. (2018). Disruptive innovation: An intellectual history and directions for future research. *Journal of Management Studies, 55*(7), 1043–1078.
- McKinsey Global Institute. (2025). [*The state of AI: How organizations are rewiring to capture value*](https://www.mckinsey.com/capabilities/quantumblack/our-insights/the-state-of-ai). McKinsey & Company.
- Eloundou, T., Manning, S., Mishkin, P., & Rock, D. (2023). GPTs are GPTs: An early look at the labor market impact potential of large language models. [*arXiv:2303.10130*](https://arxiv.org/abs/2303.10130).

**Recommended:**

- Andreessen, M. (2011, August 20). Why software is eating the world. *The Wall Street Journal*.
- Brynjolfsson, E., & McAfee, A. (2014). *The second machine age: Work, progress, and prosperity in a time of brilliant technologies*. W.W. Norton & Company.
- Parker, G.G., Van Alstyne, M.W., & Choudary, S.P. (2016). *Platform revolution: How networked markets are transforming the economy and how to make them work for you*. W.W. Norton & Company.
- Teece, D.J. (2010). Business models, business strategy and innovation. *Long Range Planning, 43*(2–3), 172–194.

---

## Glossary

| Term | Definition |
|------|------------|
| **Artificial Intelligence (AI)** | The simulation of human intelligence processes by machines, particularly computer systems; in contemporary usage, refers primarily to machine learning systems capable of performing tasks that historically required human cognition |
| **Large Language Model (LLM)** | A type of AI model trained on massive text corpora using transformer architecture, capable of generating, interpreting, and reasoning about natural language across open-ended tasks |
| **Business Model Canvas (BMC)** | A strategic management template developed by Alexander Osterwalder for developing and documenting business models, organized around nine building blocks that cover the four main areas of a business: customers, offer, infrastructure, and financial viability |
| **Inflection Point** | A moment when a technology, industry, or trend undergoes a fundamental, structural change in trajectory — distinct from incremental improvement |
| **Disruptive Innovation** | Clayton Christensen's theory describing how new entrants with simpler, more affordable products can displace established competitors by targeting overlooked segments before eventually moving upmarket |
| **Segment of One** | The theoretical limit of customer segmentation, in which each individual customer receives a fully personalized experience; increasingly achievable through AI-powered personalization |
| **Adoption Curve** | Everett Rogers' model describing how innovations spread through populations over time, with adopter categories from Innovators to Laggards |
| **Winner's Curse** | In AI adoption, the paradox where early movers face highest implementation costs and lowest model quality, while late movers face highest competitive disadvantage |
| **Foundation Model** | A large AI model trained on broad data that can be adapted to a wide range of downstream tasks; examples include GPT-4, Claude, and Gemini |
| **Fine-Tuning** | The process of further training a pre-trained foundation model on a domain-specific dataset to improve performance on targeted tasks |
| **Retrieval-Augmented Generation (RAG)** | A technique combining AI generation with retrieval from external knowledge bases, enabling AI systems to access and cite specific sources rather than relying solely on training data |
| **Value Proposition** | The bundle of benefits a company promises to deliver to customers; the answer to "why should a customer choose us?" |
| **Key Resource** | In the BMC framework, the most important assets required to make a business model work — physical, intellectual, human, or financial |
| **Cost Structure** | The most important costs incurred while operating under a particular business model |
| **API (Application Programming Interface)** | A set of protocols and tools that allows different software applications to communicate; in AI, the mechanism through which businesses access AI model capabilities programmatically |
| **Prompt Engineering** | The practice of designing and optimizing input prompts to elicit desired outputs from AI models; a key skill for AI-era knowledge workers |
| **Marginal Cost** | The cost of producing one additional unit of a good or service; AI is driving the marginal cost of knowledge work toward zero, with profound business model implications |
| **Moat (Competitive)** | A company's sustainable competitive advantage that protects it from competitors; in the AI era, data assets and proprietary AI models are emerging as primary moat sources |
| **AI-Native** | Describes a product, company, or workflow designed from the ground up with AI as a core component, rather than AI added as a feature to a pre-existing design |
| **Outcome-Based Pricing** | A revenue model in which customers pay based on results achieved rather than access to a tool or platform; increasingly viable as AI makes outcomes more measurable and predictable |

---

*Chapter 1 of 9 — Business Applications of Artificial Intelligence © Dr. Ernesto Lee, 2026. Published under Creative Commons CC-BY-4.0.*
