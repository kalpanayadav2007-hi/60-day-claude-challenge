# Day 3 - Role Based Prompting

## Objective

Learn how assigning different roles changes Claude's responses.
# Prompt Without Role

How should I learn AI in 2026?

### Output
Good pick — ML/infra is one of the areas where "learn by doing" actually outpaces courses right now. Here's how the path breaks down for 2026:
1. Foundations (don't skip, but don't linger)
Solid Python (clean, modular code, not just scripts), enough linear algebra and probability to understand embeddings and sampling, and SQL since most real-world ML data comes from databases, warehouses, logs, or event pipelines. If you already code comfortably, this is a few weeks, not months. Scaler
2. Classical ML → Deep Learning
Learn the ML workflow (not memorize algorithms) with scikit-learn: supervised/unsupervised learning, feature engineering, evaluation. Then move into neural nets — PyTorch is recommended for most learners in 2026 because it's Pythonic, widely used in research, and strongly supported by the Hugging Face ecosystem. Scaler
3. The 2026-specific layer: LLM engineering
This is now its own track, and it's where the demand is. One well-structured path covers five skill areas in order: foundations, prompting and tool calling, retrieval, fine-tuning and alignment, and serving and operations. A few notes worth flagging: KDnuggets
Tool calling is now a first-class capability in every major model API, not an advanced trick — worth learning early since it's the bridge from "chatbot" to "agent." KDnuggets
On fine-tuning, Direct Preference Optimization has largely replaced PPO-based approaches for tone and style alignment, and realistically dataset curation is where most engineering time actually goes, not the training run itself. KDnuggetsKDnuggets
Evaluation is a first-class engineering task now — building eval sets and catching failure modes before users do. KDnuggets

4. Deployment/MLOps — non-negotiable
The high-value MLE in 2026 is an MLOps expert who can deploy and monitor models at scale, not just an algorithm tuner. Docker is your entry point; from there, pick one cloud (AWS is dominant, but GCP's Vertex AI is often cited as more intuitive for ML tooling specifically). Medium
5. Portfolio over certificates
Every source agrees on this one: projects become the evidence that you are able to implement what you have learned, and documentation matters as much as code — describing the problem, data pre-processing, models tested, and why you made those choices can show engineering skill better than a repo full of notebooks. Given your "output-generation vs. feedback-loop" pattern with AI tools — this is a great place to flip it: use Claude to critique your project write-ups and poke holes in your eval methodology, not just to generate the code. ScalerScaler
Realistic timeline: if you already code, three to six months of focused work builds confidence across the LLM-specific areas, with the first project shipped well before that. KDnuggets
Given where you are — exploring product-engineering vs. AI-founding vs. translator roles — I'd suggest picking one end-to-end project (e.g., a small RAG app or a fine-tuned model with a documented eval) and shipping it fully rather than sampling five courses. That's the "depth in one area" lever you flagged as your growth constraint, and it directly feeds the founding/product-engineering paths you're weighing.
Want me to help you scope a first project, or build out a structured 8-12 week study plan?You are the founder of a successful AI startup that raised millions of dollars.
I am a college student.
How should I learn AI in 2026 if my goal is to build my own AI company?
Think strategically.
Focus on business opportunities, product building, customer validation, and AI skills.Architected founder-perspective guidance on vertical AI opportunities and lean startup methodologyArchitected founder-perspective guidance on vertical AI opportunities and lean startup methodologyAlright — thinking about this the way I'd think about it if I were sitting across from a student founder right now, in mid-2026.
Start with the opportunity, not the technology.
The founders who are struggling right now are the ones who fell in love with a model capability and went looking for a use case. That's backwards, and it's gotten worse: more than 70% of founders are building in markets already past saturation — AI writing tools, generic chatbots, meeting summarizers. Skip those entirely. Preuve AI
What's actually working in 2026: vertical AI tools that solve specific, expensive problems for specific industries, where the moat is not the AI itself but the regulated domain, the proprietary data, or the specific buyer a general-purpose tool can't reach. The three-part filter I'd apply to any idea: a specific industry with an expensive manual process, a clearly calculable ROI for the buyer, and an AI function that genuinely replaces or improves a workflow rather than adding complexity for its own sake. EnactOn + 2
Concretely, the categories with room right now: AI compliance tooling tied to the EU AI Act's August 2026 enforcement, vertical SaaS for unglamorous industries like HVAC or pest control, AI agent infrastructure, senior care tech, and fintech infrastructure — precisely because the catalysts are forcing functions like regulation deadlines and demographic shifts, not hype. As a student, don't dismiss "boring" — vertical SaaS for a niche like HVAC can reach real recurring revenue on trade-association distribution with no sales team. Preuve AI + 2
Customer validation comes before code, not after.
This is the part students skip because building feels more productive than talking to strangers. It isn't. Talk to at least 10 potential customers before writing a line of code or paying a developer. You're not asking "would you use this" — you're trying to find someone who's already spending money or hours badly solving this problem. If you can't find 10 people with the pain, the idea isn't ready. Appscrip
Product building: speed is the actual skill.
The bar for "technical enough" has dropped. You don't need to be an AI expert or hire a technical co-founder to get a working prototype in front of users now — tools that generate app foundations from a description have made building accessible to domain experts, not just engineers. That said, given you're leaning ML/infra: use that edge to build the thing that's hard to fake — the eval loop, the retrieval quality, the fine-tuned behavior — while leaning on AI tools for everything around it (UI, boilerplate, ops). Your job as a technical founder isn't to write every line, it's to own the part of the product that's actually defensible. Bubble
The window is short — move like it.
The window for any given AI startup idea narrows fast as competitors build quickly, and early movers earn distribution advantages that compound. That's a real argument for starting now, as a student, even imperfectly — capital and funding are unusually available (AI startup funding hit $242B in Q1 2026 alone), and being early to a narrow niche matters more than being polished. AppscripAppscrip
What I'd actually do in your seat this year:

Pick one industry you already have a way into — a part-time job, a relative's business, a campus org — not the sexiest one, the one where you can talk to 10 people this month.
Ship a rough version fast, even manually ("Wizard of Oz" it — do the AI part by hand before you automate it) to prove the workflow saves real time or money.
Use the ML/infra learning from your engineering track to build the one component that's hard to replicate — not the whole app.
Treat every conversation with a potential customer as more valuable than another week of building alone.

One honest caveat: I can't verify company-specific funding or revenue figures beyond what's publicly reported, and "best ideas" lists like these are directional, not guaranteed — the actual signal only comes from your own customer conversations. Want help scoping customer interview questions, or picking between two or three specific niches you're already close to?You are a Senior AI Software Engineer working at a top tech company.
I am a beginner.
How should I learn AI in 2026 if my goal is to become an AI Developer?
Give me a detailed technical roadmap.
Include:
- Programming languages
- Frameworks
- Projects
- Deployment
- GitHub portfolio
- Interview preparationArchitected comprehensive AI developer roadmap with structured sectionsArchitected comprehensive AI developer roadmap with structured sectionsLet's build this out properly — the kind of roadmap I wish someone had handed me instead of the "watch every course" approach.
Programming Languages
Python — non-negotiable, go deep. Python is the dominant language for AI agent development, supported by virtually every major framework, including LangChain, AutoGen, CrewAI, and OpenAI's SDK — its ecosystem is why. Get past "I know Python" to actually writing clean, typed, modular code — that's the bar in production teams now, not scripting. Monday.com
SQL — you'll pull training data, log agent traces, and query vector stores constantly.
TypeScript/JavaScript (secondary) — worth knowing if you want to ship anything user-facing; several frameworks now ship JS/TS SDKs alongside Python for web-based implementations.
Frameworks — learn in this order

PyTorch — for understanding what's happening under the hood (training loops, tensors, backprop). Don't skip this even if you go straight into LLM app work — it's the difference between "I called an API" and "I understand why it responded that way."
Hugging Face Transformers — the standard interface to open models, tokenizers, and fine-tuning.
An orchestration/agent framework. This is the 2026-specific addition to any roadmap. LangChain is the most widely adopted open-source framework for building AI agents and LLM applications, and pairs with LangGraph for stateful, cyclic multi-agent orchestration. LangGraph has emerged as the leading standard for production-grade agent systems specifically because it replaces implicit behavior with explicit, debuggable graphs — worth learning right after basic LangChain. Alternatives worth knowing exist: CrewAI (role-based, faster to prototype with), Microsoft's Agent Framework/Semantic Kernel (if you're eyeing enterprise/Azure-heavy companies), and the OpenAI Agents SDK. LangChain + 2
LlamaIndex — for retrieval-heavy work; it specializes in connecting LLMs to your data, making it essential for applications that need to reason over private documents, databases, and knowledge bases. Medium
A vector store (Chroma or FAISS to start) and an observability tool — LangSmith provides tracing, evaluation, and debugging for production AI applications regardless of the underlying framework. Companies increasingly care whether you can debug an agent, not just build one. LangChain

Projects — build in increasing difficulty, each teaching the next skill

Fine-tune a small open model on a narrow task (e.g., matching a tone or format) and measure it against a baseline — teaches dataset curation and evaluation, which is where the real engineering work is.
A RAG pipeline over a real document set (not a toy dataset) — teaches chunking, embeddings, retrieval quality tradeoffs.
A tool-calling agent that does something real (query an API, update a spreadsheet, search the web) — teaches the model→tool→result loop that's now standard in every major API.
A multi-agent system with LangGraph or CrewAI for a workflow with real branching logic — teaches orchestration and state management.
One capstone: pick a narrow, real problem (not "chatbot for X") and take it fully end-to-end — data in, model/pipeline, eval suite, deployed, monitored. This is the one you talk about in every interview.

Deployment

Docker first — containerize every project, no exceptions, even personal ones.
Pick one cloud and go deep rather than sampling three (AWS is the market default; GCP's Vertex AI is often considered the more intuitive ML-specific tooling).
Learn to serve a model behind an API (FastAPI is the common pairing with PyTorch/Transformers), plus basic monitoring — latency, error rates, and for LLM apps specifically, output quality drift.
Get comfortable with at least one inference optimization concept (quantization, batching, or a serving tool) — even surface-level understanding differentiates you from "notebook only" candidates.

GitHub Portfolio
Documentation is doing more work than people think. For each project: state the problem, show your data/approach decisions and why you made them, and — critically — show eval results, not just "it works." A repo with a clear README, a demo (video or hosted link), and honest limitations reads as far more senior than five unexplained notebooks. Pin 3-4 repos max, each one representing a different skill (fine-tuning, RAG, agents, deployment) rather than five variations on the same idea.
Interview Preparation

Coding: LeetCode at a medium level — this hasn't gone away, most AI dev interviews still open with a DSA round.
ML fundamentals: be able to explain model choice, evaluation metrics, overfitting/underfitting, and tradeoffs — not derive attention from scratch, but reason clearly about behavior.
LLM/agent-specific rounds are now common and distinct from classic ML interviews — expect questions on system vs. user prompts, RAG architecture and indexing strategies, agent design patterns (ReAct, planning, multi-agent hierarchies), and tool-calling mechanics. Interviewers will likely ask follow-ups probing your precise skillset, so know one framework (LangChain/LangGraph or LlamaIndex) well enough to discuss real tradeoffs, not just definitions. DataCamp
System design for AI: be ready to whiteboard a RAG pipeline or agent architecture end-to-end — this has become a standard round at AI-forward companies.
Practice explaining your capstone project out loud, focusing on decisions and failure modes, not just the happy path — that's what separates "I followed a tutorial" from "I engineered this."

Rough timeline: 2-3 months on languages + PyTorch/Transformers foundations, 2-3 months on frameworks + first two projects, 1-2 months on agents/multi-agent + deployment, ongoing portfolio polish and interview prep in parallel with your last projects rather than after. If you're consistent, 6-9 months gets you genuinely interview-ready.
Want me to turn this into a week-by-week study plan, or help you scope that capstone project first?compare these all responses which are asked aboveArchitected comparative analysis across three distinct professional perspectivesArchitected comparative analysis across three distinct professional perspectivesHere's how the three stack up — same underlying question ("how do I learn AI in 2026"), three very different lenses:
ML/Infra Engineer angleFounder angleAI Developer angleCore questionHow do I build the models/systems?What do I build and for whom?How do I get hired building AI products?End goalTechnical mastery, MLOps competenceA company with paying customersA job as an AI DeveloperStarting pointPython, math, PyTorchCustomer pain, not technologyPython, PyTorch, frameworksCore skill emphasizedModel training, deployment, evaluationTalking to customers, speed of shippingFramework fluency (LangChain/LangGraph), system design"Depth" leverDataset curation, fine-tuning, MLOpsOne narrow vertical, one real workflowOne capstone project, deeply documentedPortfolio artifactDeployed model + eval resultsValidated MVP + customer conversationsGitHub repos with README + eval, demo linksBiggest risk flaggedStaying in "notebook prototype" mode foreverBuilding a ChatGPT wrapper nobody needsShallow tutorial-following without real projectsTimeline given3–6 months to competenceMove fast, weeks to first customer conversations6–9 months to interview-readyWhat's not coveredBusiness viability, customer demandDeep technical depth (fine-tuning internals, infra)Building a company, market validation
Where they agree:

All three independently converge on ship real, end-to-end things over consuming more courses — a project/product with documented reasoning beats a certificate every time.
All three flag evaluation as underrated — whether that's model eval, customer validation, or eval suites in interviews.
All three point at the same technical core (Python, PyTorch, LLM/agent frameworks) as table stakes, just weighted differently.

Where they genuinely diverge:

The founder path treats technical depth as necessary but not sufficient — it's explicitly secondary to finding a real problem.
The ML engineer and AI Developer paths overlap heavily (roughly 70%), but the AI Developer path adds interview mechanics and portfolio presentation, while the ML engineer path goes deeper into fine-tuning and MLOps internals.
Only the founder path talks about market saturation and timing — the other two assume the job/skill exists and stays stable, which isn't really true for AI right now.

One thing worth naming: you've now gotten three coherent but different "correct" answers to the same underlying question. That's the real tension in the generalist-explorer stage — each path is a legitimate 6+ month bet, and trying to hold all three at once is usually what stalls progress rather than accelerates it. If it'd help, I can build a decision framework for choosing between them based on what you actually have leverage on right now (time, network, existing skills) — or if you already have a lean, we could go deep on just that one.


Comparison

Without Role:
- General learning advice
- Suitable for beginners

Founder Persona:
- Focused on solving customer problems
- Suggested validating ideas before coding
- Recommended building AI products

Developer Persona:
- Focused on programming
- Suggested Python, Git, APIs, Docker
- Recommended building portfolio projects

Learning:
Adding a role significantly changes the quality, structure, and perspective of AI responses.

