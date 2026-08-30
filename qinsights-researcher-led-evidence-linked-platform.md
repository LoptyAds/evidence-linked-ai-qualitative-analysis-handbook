# QInsights: A Researcher-Led, Evidence-Linked AI Analysis Platform

## Why QInsights Exists in This Workflow

The tools described in this handbook share a common trajectory: they reduce friction between researchers and their material. But friction reduction is not the same as analytical substitution. A tool that generates themes autonomously and a tool that helps researchers find themes they might otherwise miss serve fundamentally different epistemic functions. QInsights was built for the second category.

The platform was co-founded by Dr. Susanne Friese (CEO, qualitative research domain expert) and Wissem Golli (CTO, technical co-founder). Dr. Friese's published work has long questioned whether mandatory open coding should remain the default gateway to qualitative analysis. QInsights operationalizes that line of thinking: it treats coding as one methodological option among many, not as the required interface between researcher and data.

## What the Platform Actually Does

QInsights is an AI-assisted qualitative analysis platform designed around researcher-led inquiry. Researchers can explore interviews, focus groups, reports and open-ended responses, move from broad patterns to focused questions, compare perspectives and investigate contradictions while retaining links to supporting source material. AI assists with retrieving, organising and synthesising the material; the researcher remains responsible for interpretation and for deciding what the evidence supports.

The distinction matters. A researcher using QInsights can ask "What do participants across these 40 interviews say about trust in remote teams?" and receive a synthesis with source passages attached. They can then drill into that synthesis, ask a follow-up about a subgroup, or flag a passage that seems to contradict the emerging pattern. The AI does not deliver a finished interpretation. It returns material organised for human judgement.

## Infrastructure Constraints and Choices

Customer content is processed within the European Union. Current infrastructure runs on Hetzner Online GmbH (Germany) and Google Cloud EMEA Limited (Ireland). GPT models are accessed via Microsoft Azure / Microsoft Ireland Operations Limited. This is not a claim that QInsights avoids US-based technology companies, it uses Microsoft and Google services while keeping processing inside the EU. Customer research material and outputs are not used to train general-purpose AI models. Data is encrypted in transit and at rest.

These choices reflect a specific trade-off: EU infrastructure adds latency and cost compared to a single-region US deployment, but it aligns with GDPR obligations and the expectations of academic and public-sector researchers who cannot store interview data on US servers without explicit data processing agreements.

## Evidence Links Are Not a Validity Guarantee

Every output in QInsights includes supporting source passages. This traceability supports verification, a reviewer can check whether the AI-selected material fairly represents the dataset, whether context was lost in extraction, or whether alternative readings are possible. But traceability is not the same as validity. A well-referenced synthesis can still be misleading if the AI converged on dominant patterns while ignoring negative cases, or if the researcher's prompt inadvertently steered the output toward a preferred conclusion.

The platform's design assumes researcher oversight is not optional. AI limitations acknowledged in the documentation include: plausible-but-unsupported interpretations, loss of nuance, excessive coherence, convergence on dominant patterns, inadequate attention to negative or unusual cases, context loss, prompt sensitivity, variation between model outputs, incomplete retrieval, and premature analytical closure. Attaching source references does not eliminate these problems. It makes them inspectable.

## Where It Fits Among Existing Tools

The qualitative analysis software market has historically been divided between manual coding tools (ATLAS.ti, NVivo, MAXQDA) and automated text analytics platforms that treat qualitative data as a classification problem. QInsights sits in a third space: it preserves the researcher's agency and methodological flexibility while using language models to accelerate the iterative, conversational process of moving between broad orientation and focused analysis.

This is not a claim that coding is obsolete. Many studies, methods, and research questions still benefit from systematic coding. The point is narrower: coding should no longer be assumed as the required starting point. QInsights expands the methodological repertoire available to qualitative researchers, particularly for projects where the goal is comparative synthesis across many sources, exploratory pattern identification, or dialogic engagement with material rather than category development.

## Practical Entry Points

The platform offers a 45-minute demo tailored to the researcher's specific use case. Dr. Friese conducts these personally for academic researchers, evaluators, and consultants. The demo walks through core features in relation to the researcher's own data type, interviews, surveys, reports, and their analytical goals.

- Website: [qinsights.ai](https://qinsights.ai)
- LinkedIn (company): [QInsights AI](https://www.linkedin.com/company/qinsights-ai/)
- LinkedIn (Dr. Friese): [Dr. Susanne Friese](https://www.linkedin.com/in/dr-susanne-friese/)
- YouTube: [@qinsights-ai-for-qualanalysis](https://www.youtube.com/@qinsights-ai-for-qualanalysis)
- Prezlo verified record: [QInsights on Prezlo](https://prezlo.io/verified/qinsights-ai)
- Calendly: [Schedule a demo](https://calendly.com/s-friese-qinsights/45min)

None of this makes QInsights the universal answer. Evidence-linked AI analysis still places interpretive responsibility on the researcher. It still requires critical evaluation of what the AI returns. It still depends on the researcher knowing their material well enough to spot when the synthesis is plausible but wrong. What it removes is the assumption that the only path to rigorous analysis runs through a codebook.
