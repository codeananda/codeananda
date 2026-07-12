# Adam Murphy | AI Engineer | LLM Systems for Regulated Industries

I build production LLM systems for industries where wrong answers cost money — insurance, finance, law, property. Recent systems have:

- ⚡ Cut insurance underwriting review from **days to 3–5 minutes** at **99.55% precision**
- 📄 Processed **12M+ documents in 48 hours** on Kubernetes spot instances
- 📊 Screened private-equity deals end-to-end against the firm's own scorecard, **backtested against realised returns**
- 🛡️ Built a consumer-fintech assistant designed to keep responses on the information side of the FCA advice boundary — **zero hallucinated financial figures by construction**

## 📁 Case studies

Client names are under NDA; the systems, numbers and engineering are real. Each repo has the full designed write-up:

- [AI underwriting platform](https://github.com/codeananda/ai_underwriting_platform) — the carrier's actual manual applied at 99.55% precision; review in minutes, not days
- [A financial assistant that never makes up a number](https://github.com/codeananda/fintech_ai_assistant) — every figure computed by deterministic code; 43 tools, zero hallucinated numbers
- [Testing AI that never answers the same way twice](https://github.com/codeananda/testing_nondeterministic_llm_systems) — golden-sample regression, LLM-as-judge, test suites 48× faster
- [When the document is the attacker](https://github.com/codeananda/llm_prompt_injection_defence) — the five-layer prompt-injection defence adopted as a production platform's security spec
- [Enterprise payslip data extraction](https://github.com/codeananda/enterprise_payslip_data_extractor) — dual-LLM verification for mortgage approvals: 52% fewer errors, 80% less manual review
- [National-scale document pipeline](https://github.com/codeananda/planning_doc_text_extract_embed) — 12M docs / 120M pages embedded in 48 hours, zero-cost self-hosted embeddings
- [UK Local Plan policy summariser](https://github.com/codeananda/local_plan_policy_summariser) — 700+ plans weekly, 75% LLM cost reduction via context caching
- [Client testimonials](https://github.com/codeananda/testimonials) — six years of reviews, 100% Job Success

Further case studies (multi-carrier platform architecture, agentic engineering enablement, PE deal screening) available on request.

## 🎯 What I'm known for

- **Accuracy you can audit** — golden-sample regression suites, LLM-as-judge testing, human-edit-count evaluation. 99% figures that are maintained properties, not launch statistics.
- **LLM security that ships** — designed the five-layer prompt-injection defence a production platform adopted as its security spec, including a ~20-line pre-filter that closes a published 100% detection-evasion attack.
- **Cost-conscious architecture** — 65–75% LLM cost reductions through model routing, context caching, batch APIs and self-hosted embeddings.
- **Agentic engineering** — led team-wide AI-tooling adoption; a ten-gate pre-push pipeline runs five adversarial AI reviewers on every change for ~$25, so PRs arrive clean before a human looks.

## 🛠️ Tech

- **Orchestration:** LangChain (v1), LangGraph, Langfuse, LangSmith, Claude Code / agent skills, MCP
- **Models:** Claude (Bedrock + Anthropic API), GPT, Gemini (Vertex), Llama
- **Infra:** AWS (Bedrock, Lambda, ECS, SQS, S3, RDS), Docker, Kubernetes, PostgreSQL + pgvector, FastAPI
- **ML:** PyTorch, scikit-learn, pandas · AWS ML Specialty certified

## 🤝 Work with me

Expert-Vetted on Upwork (top 1%) · 100% Job Success · $400K+ earned · [Upwork profile](https://www.upwork.com/freelancers/~01153ca9fd0099730e)
