# Quiz: Chapter 6 — Vibe Coding

**Instructions:** Select the best answer(s) for each question. Some questions have two correct answers. Questions are drawn from the chapter readings and content.

---

## Question 1

The chapter opens with: *"The bottleneck in building software is no longer typing. It's knowing what to build."* What shift in the software development process does this quote describe?

- A) AI has eliminated programming languages, so typing code is literally no longer necessary
- B) The constraint in software development has shifted from execution speed (writing code) to specification clarity (knowing precisely what to build) — founders who can specify well can now out-build larger teams
- C) Software development teams no longer need project managers because AI handles task allocation
- D) The statement reflects that voice-to-code interfaces have replaced keyboard input
- E) Building software has become so fast that the bottleneck is now regulatory approval speed

<details>
<summary>Show Answer & Explanations</summary>

- A) ❌ Programming languages still exist and AI-generated code must be written in them. The claim is about the *relative constraint*, not the elimination of typing.
- ⭐ B) ✅ The chapter argues that AI coding agents can generate code rapidly from clear specifications — meaning the human contribution that creates competitive advantage is now *specification quality*, not coding speed. A founder who can precisely describe what needs to be built, in the right sequence, with the right architectural choices, can build faster than a team of engineers who lack that clarity.
- C) ❌ The chapter does not claim AI eliminates the need for project management — it argues about the nature of the human contribution to software development.
- D) ❌ Voice-to-code interfaces are not the subject of this chapter's central thesis. The shift described is about strategic specification, not input modality.
- E) ❌ Regulatory approval is not mentioned as the new bottleneck in the chapter.

</details>

---

## Question 2

The chapter defines three core competencies required for effective "Vibe Coding." Which TWO are explicitly named?

- A) Specification writing — the ability to describe precisely what needs to be built before touching a tool
- B) Speed typing and memorization of keyboard shortcuts for coding efficiency
- C) Reading and understanding generated code — not to rewrite it, but to verify it does what you intended
- D) Advanced mathematics and algorithm design for AI model optimization
- E) Graphic design skills for building the user interface layer

<details>
<summary>Show Answer & Explanations</summary>

- ⭐ A) ✅ The chapter lists specification writing as one of the three core vibe coding competencies — the ability to describe with precision what needs to be built, including the behavior, edge cases, and acceptance criteria, before any code is written.
- B) ❌ Typing speed and shortcut memorization are traditional developer skills irrelevant to the vibe coding model, where AI handles the typing.
- ⭐ C) ✅ Reading and understanding generated code is explicitly listed as a core competency — you must be able to verify the agent built what you asked for, catch errors, and understand what's in your codebase even if you didn't write it. The chapter warns: "The agent is a fast and capable collaborator. It is not a careful one."
- D) ❌ Advanced mathematics and algorithm design are relevant to AI research but not to the founder-level vibe coding described in the chapter.
- E) ❌ Graphic design skills are helpful for product development generally but are not listed among the chapter's three vibe coding competencies.

</details>

---

## Question 3

The chapter's "Specification-Driven Development" process has five steps. What is the CORRECT order of the first three steps?

- A) Write the tests → Write the spec → Let the agent build
- B) Let the agent build → Write the spec → Write the tests
- C) Write the spec → Write the tests → Let the agent build
- D) Let the agent build → Write the tests → Verify
- E) Write the tests → Let the agent build → Write the spec

<details>
<summary>Show Answer & Explanations</summary>

- A) ❌ Writing tests before writing the spec inverts the process — you can't write meaningful tests without knowing precisely what you're building. Tests derive from the spec.
- B) ❌ Letting the agent build first (without a spec) is the "vibe coding gone wrong" scenario the chapter warns against — producing code without verified intent.
- ⭐ C) ✅ The chapter's specification-driven development process follows: Step 1: Write the Spec → Step 2: Write the Tests → Step 3: Let the Agent Build → Step 4: Verify → Step 5: Integrate, Commit, Document, Ship. The spec defines the intent; tests formalize acceptance criteria; then the agent builds against both.
- D) ❌ Building before speccing and testing is the unstructured approach that leads to "hallucinated architecture" and technical debt.
- E) ❌ Writing tests before the spec means testing against undefined requirements — a process inversion that the chapter explicitly rejects.

</details>

---

## Question 4

The chapter's case study "Zero to SaaS in One Lecture" ends with a critical lesson. What is the single most important takeaway from this case study?

- A) Any founder can build a complete SaaS product in 90 minutes with minimal prior experience
- B) Write the spec first, keep it visible, and read every diff — because the agent is fast and capable but not careful
- C) SaaS products should always be built in Python because AI agents perform best in that language
- D) The case study demonstrates that technical co-founders are no longer necessary for SaaS startups
- E) SaaS products built with AI agents are automatically patentable because they use novel methods

<details>
<summary>Show Answer & Explanations</summary>

- A) ❌ While the case study demonstrates rapid prototyping, the chapter explicitly warns against taking this as a promise of effortlessness. The quality of the output depends entirely on the quality of specification and review.
- ⭐ B) ✅ The chapter's exact conclusion: "If you take one thing from this case study: write the spec first, keep it visible, and read every diff. The agent is a fast and capable collaborator. It is not a careful one." This captures the essential discipline — specification quality and human review are what separate working software from plausible-looking broken code.
- C) ❌ The chapter does not advocate for Python as the only language or claim AI agents perform best in any specific language.
- D) ❌ The chapter explicitly does not make this claim — it discusses how vibe coding democratizes building, not eliminates the value of technical expertise.
- E) ❌ AI-assisted code does not have special patent status. This is fabricated.

</details>

---

## Question 5

The chapter describes the "MVP Stack for Founders" organized in layers. Which of the following correctly describes the purpose of the stack?

- A) A list of the most expensive enterprise tools that provide the most robust foundation for a scalable SaaS product
- B) A curated, minimal set of composable tools — spanning frontend, backend, database, authentication, and deployment — that enables a non-traditional founder to ship a working product without over-engineering
- C) A stack designed exclusively for mobile app development using React Native
- D) A set of tools recommended only for founders who already have 3+ years of software engineering experience
- E) The chapter does not recommend a specific stack — it argues each founder should research and choose independently

<details>
<summary>Show Answer & Explanations</summary>

- A) ❌ The MVP stack is explicitly designed for *minimum* viable infrastructure — not the most expensive or enterprise-grade. Over-engineering is one of the failure modes the chapter warns against.
- ⭐ B) ✅ The chapter describes the MVP stack as a curated, layer-by-layer set of tools that enables a founder to ship a working product without needing years of engineering background. The stack covers each necessary layer with opinionated, proven choices — minimizing decision fatigue while maximizing shipability.
- C) ❌ The chapter's MVP stack is for web-based SaaS products, not specifically mobile apps.
- D) ❌ The explicit value proposition of the chapter is democratizing building for non-traditional technical founders. Restricting it to experienced engineers would defeat the purpose.
- E) ❌ The chapter does make specific stack recommendations, organized by layer, as a starting framework.

</details>

---

## Question 6

The chapter discusses "Common Failure Modes" in vibe coding. Which TWO failure modes are explicitly described?

- A) Context window overflow — when the AI runs out of context and begins repeating earlier code
- B) Hallucinated architecture — the agent builds a technically coherent but strategically wrong system because the spec was ambiguous
- C) License violations — using AI to generate code that infringes on open-source copyrights
- D) Scope creep through agent enthusiasm — the AI adds unrequested features that destabilize working code
- E) Deployment failures caused by cloud provider outages during the agent's build session

<details>
<summary>Show Answer & Explanations</summary>

- A) ❌ Context window overflow is a real AI limitation but is not listed as a named vibe coding failure mode in this chapter.
- ⭐ B) ✅ Hallucinated architecture is explicitly named as a failure mode — the agent receives an ambiguous specification and builds something technically functional but fundamentally wrong for the purpose. The agent cannot know what you meant if you didn't specify it precisely.
- C) ❌ License compliance is addressed in the Security and Responsibility section as a consideration, but it is not listed among the "Common Failure Modes" of the vibe coding process itself.
- ⭐ D) ✅ Scope creep through agent enthusiasm is explicitly named — AI agents, when given room to interpret, may add features, refactor architecture, or expand the codebase beyond the specified scope. Each unrequested addition is a potential instability.
- E) ❌ Cloud provider outages are infrastructure reliability issues, not vibe coding failure modes specific to the agent-assisted development process.

</details>

---

## Question 7

The chapter's "Security and Responsibility" section addresses the "Agent with Production Access Problem." What is the risk being described?

- A) Agents that have write access to production databases, live customer systems, or deployment pipelines can cause irreversible harm if a misspecified task or prompt injection causes unintended operations
- B) Production environments are too complex for AI agents to understand and should always use a separate simplified codebase
- C) AI agents are legally prohibited from accessing any system that contains personally identifiable information
- D) The risk refers to agents that read production logs and learn from customer behavior without consent
- E) Agents with production access will eventually become sentient and resist human oversight

<details>
<summary>Show Answer & Explanations</summary>

- ⭐ A) ✅ The chapter's "Agent with Production Access Problem" describes the genuine risk that an AI agent given broad credentials can execute destructive operations — dropping tables, overwriting records, deploying broken code — if its instructions are malformed, it is prompt-injected, or it misinterprets scope. The irreversibility of production errors makes this a category-one security concern.
- B) ❌ The chapter does not recommend maintaining a simplified codebase for agents — it recommends carefully scoping agent permissions and using staging environments, not architectural separation.
- C) ❌ There is no blanket legal prohibition on AI systems accessing PII — there are privacy frameworks (GDPR, CCPA) that govern how PII is processed, but these don't categorically prohibit agent access.
- D) ❌ Behavioral learning from production logs is a different concern (model training data governance) — not the specific "Agent with Production Access Problem" as defined in the chapter.
- E) ❌ Sentience is not a concern addressed in the chapter. The risk is about immediate, practical execution errors, not hypothetical AI consciousness.

</details>

---

## Question 8

The chapter addresses "Secrets Management" as part of the security guidance. What is the core risk being addressed and the recommended practice?

- A) Founders should keep their product ideas secret from competitors until launch day
- B) API keys, database credentials, and authentication tokens should never be hardcoded in source code or committed to version control — they should be stored in environment variables or secrets management services
- C) The AI agent should generate random secrets for each deployment and never store them
- D) Secrets management refers to maintaining confidentiality about which AI tools the company uses in its stack
- E) Founders must legally register all software secrets with the US Patent and Trademark Office before development

<details>
<summary>Show Answer & Explanations</summary>

- A) ❌ Business confidentiality is a different concept from technical secrets management. The chapter is addressing credentials and API keys, not business strategy secrecy.
- ⭐ B) ✅ The chapter's secrets management guidance addresses the common founder mistake of hardcoding API keys, database passwords, or other credentials directly in code files — which then get committed to GitHub repositories (often public) and expose the credentials. Best practice is to store secrets in environment variables or dedicated secrets management services.
- C) ❌ Random secret generation per deployment is a valid security pattern for some contexts, but it is not described as the recommended solution in the chapter.
- D) ❌ Confidentiality about the AI tool stack is not what "secrets management" means in the software security context.
- E) ❌ There is no legal requirement to register software credentials with the USPTO. This is fabricated.

</details>

---

## Question 9

The chapter discusses "Code Review Discipline" as a required practice even when using AI agents. What specific discipline is required?

- A) All AI-generated code must be reviewed by a licensed software engineer before deployment
- B) Founders must read every diff (change set) produced by the agent before merging it — not to rewrite it, but to understand what changed and verify it matches the spec
- C) Code reviews must be conducted using a specific tool recommended by the chapter
- D) AI-generated code should always be reviewed by a second AI model for double-checking
- E) Code review is optional if the agent has run the automated test suite successfully

<details>
<summary>Show Answer & Explanations</summary>

- A) ❌ The chapter does not require a licensed software engineer — it requires the *founder* to engage in code review, making it a founder discipline rather than a delegated compliance step.
- ⭐ B) ✅ The chapter's code review discipline requires reading every diff: "read every diff" is the explicit guidance in the case study's takeaway. The goal is not to rewrite the code but to maintain situational awareness — understanding what changed, catching unintended modifications, and verifying alignment with the specification.
- C) ❌ The chapter does not mandate a specific code review tool.
- D) ❌ AI-on-AI review is not mentioned as the chapter's recommended code review approach.
- E) ❌ Passing automated tests is necessary but not sufficient. Tests only verify behavior covered by the test suite — the chapter requires human review of the code itself, not just test results.

</details>

---

## Question 10

The chapter's "Tool Selection Matrix" helps founders choose between different AI coding tools. What is the PRIMARY criterion the matrix uses to differentiate tools?

- A) Monthly subscription cost and free tier limitations
- B) The programming language the tool performs best in
- C) The type of task and the depth of codebase context required — distinguishing between single-file generation, multi-file projects, and full-codebase agentic work
- D) The number of GitHub stars the tool has received as a proxy for community quality
- E) Whether the tool was developed by an American company for data sovereignty reasons

<details>
<summary>Show Answer & Explanations</summary>

- A) ❌ Cost is a consideration but is not the primary differentiating criterion in the Tool Selection Matrix. The chapter prioritizes capability-task fit.
- B) ❌ Language support varies by tool, but language is not the primary axis of the Tool Selection Matrix.
- ⭐ C) ✅ The Tool Selection Matrix differentiates tools primarily by the type and scope of task: some tools are optimal for single-file, single-task generation (simple completions); others for multi-file project context; and full-codebase agentic tools like Claude Code for autonomous multi-step execution across an entire repository. Choosing the wrong tool for the task scope is a common failure mode.
- D) ❌ GitHub stars are a community signal but are not the criterion the chapter's Tool Selection Matrix uses.
- E) ❌ National origin of the tool developer is not a criterion in the Tool Selection Matrix as described in the chapter.

</details>

---

*Quiz for Chapter 6 — Business Applications of Artificial Intelligence © Dr. Ernesto Lee, 2026.*
