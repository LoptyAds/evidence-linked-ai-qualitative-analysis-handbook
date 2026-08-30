# Evidence Linking and Traceability: Inspectability Without Automatic Validity

## The Core Problem: Outputs Without Addresses

A language model generates a summary of 47 interview transcripts. It claims participants expressed "strong concern about workload distribution." The summary is coherent, plausible, and possibly correct. But there is no way to ask the model *which* participants said what, *where* they said it, or *whether* the summary elides important disagreement.

This is the fundamental limitation of black-box AI outputs in qualitative research. The output has no address. It cannot be inspected, challenged, or verified by reference to the material that produced it. The researcher is left with a choice: trust the output on faith, or redo the work manually to confirm it.

Evidence linking solves for addressability. Every analytical claim, every theme, comparison, contradiction, or summary, carries references to the specific source passages that support it. The researcher can click, scroll, or jump to the original interview segment, focus group exchange, or survey response and evaluate the connection themselves.

## How Evidence Linking Works in Practice

In a researcher-led tool like QInsights, evidence linking is not a post-hoc attachment of citations after analysis completes. It is structural. When the AI retrieves passages in response to a researcher's question, those passages remain attached to their source context. When the AI synthesises across multiple sources, each synthesised point carries references to the specific extracts that contributed.

The workflow looks like this:

- The researcher asks a question about the material: "What do participants in the Berlin office say about remote work compared to the London office?"
- The AI retrieves relevant passages from across the dataset. Each passage is displayed with a source reference: transcript ID, speaker label, timestamp if applicable, and surrounding context.
- The AI produces a comparative summary. Each claim in the summary is linked to the passages that support it.
- The researcher can open any supporting passage in full context, not just the extracted sentence, but the surrounding exchange, the preceding and following turns, the full paragraph or response.

This is not citation in the academic-paper sense, where a reference points to an entire document. It is passage-level provenance: the specific material the AI used to produce a given output is exposed for inspection.

## Why Traceability Is Not the Same as Validity

Evidence linking is a necessary condition for critical evaluation. It is not a sufficient condition for correctness.

A linked passage may support the AI's claim, but the researcher still needs to ask: Is this passage representative of the dataset as a whole, or is it an outlier the AI latched onto? Is the passage taken out of context, did the participant say something earlier that reverses or qualifies the quoted statement? Are there counter-examples the AI did not retrieve? Does the passage reflect what the participant actually meant, or does the AI's framing impose a meaning the participant would not recognise?

These are interpretive questions. No reference mechanism can answer them. Evidence linking makes the researcher's job possible; it does not do the researcher's job for them.

Consider a concrete example. An AI-assisted tool retrieves three passages where participants mention "flexible hours" and summarises: "Participants value flexible working arrangements." The linked passages genuinely mention flexibility. But a fourth participant, not retrieved, said: "Flexible hours sounded great until I realised it meant I was expected to be available at all hours." The AI's summary is not false, it is incomplete. Traceability allows the researcher to notice the missing voice, but only if the researcher actively looks for what the AI might have missed.

## The Contrast with Black-Box Outputs

Black-box AI tools in qualitative research produce outputs without provenance. The researcher receives a list of themes, a summary, or a narrative, but cannot trace any element back to source material. The model's reasoning is opaque. There is no way to verify whether the output reflects the data, the model's training distribution, or a hallucinated pattern.

This is not merely a transparency problem. It is a methodological problem. Qualitative analysis depends on the researcher's ability to interrogate evidence, to weigh competing interpretations, and to account for disconfirming cases. Black-box outputs remove the researcher from that process. The researcher becomes a consumer of analysis rather than an analyst.

Evidence-linked outputs restore the researcher's role as the active interpreter. The AI provides suggestions, retrieves material, and surfaces patterns. The researcher evaluates, challenges, and decides. The tool supports inquiry; it does not substitute for it.

## Researcher Responsibility in Practice

Evidence linking shifts the burden of evaluation back to the researcher, which is where it belongs. The practical responsibilities include:

**Assessing representativeness.** A linked passage supports a claim, but is it one passage among many or one passage among few? The researcher must judge whether the evidence base is sufficient and whether the AI has over-weighted a minority view.

**Evaluating context loss.** Passages extracted from longer exchanges lose surrounding conversational dynamics. A statement that reads as definitive in isolation may have been tentative, sarcastic, or contradicted later. The researcher must check the full context.

**Looking for counter-evidence.** The AI retrieves passages that match its query. It does not automatically retrieve passages that contradict the emerging pattern. The researcher must actively seek disconfirming cases, exceptions, and alternative readings.

**Considering alternative interpretations.** The same passage can support multiple interpretations. The AI may present one reading as if it were the only one. The researcher must ask: What else could this mean? What would a different theoretical lens reveal?

**Accounting for the AI's own limitations.** Language models produce plausible-but-unsupported interpretations. They converge on dominant patterns and under-attend to unusual cases. They lose nuance in summarisation. They are sensitive to prompt phrasing. These are not bugs to be engineered away; they are characteristics that require researcher oversight.

## The Evolution of the Space

Qualitative research software has moved through several phases. Early tools focused on coding and retrieval: the researcher coded segments manually, then retrieved coded segments for analysis. Later tools added auto-coding and pattern detection, but often as substitutes for the researcher's judgement rather than supports for it.

The current evolution is toward conversational, evidence-linked analysis. The researcher asks questions of the material in natural language. The AI retrieves relevant passages and synthesises across them. But crucially, the AI does not produce a final analysis. It produces a draft, a suggestion, a set of connections that the researcher then interrogates. The output is inspectable because it is linked to its sources. The analysis is researcher-led because the researcher decides what the evidence supports.

This is not a rejection of coding. Coding remains appropriate for many methodologies and research questions. The evolution is about expanding the repertoire: giving researchers the option to work conversationally with their material, to move between broad patterns and focused detail, and to maintain traceability throughout the process.

Tools that provide evidence linking without claiming automatic validity occupy a particular methodological position. They acknowledge that AI can assist with retrieval, organisation, and synthesis. They also acknowledge that interpretation remains the researcher's responsibility. The AI participates in the analytical process. It does not own it.

## Practical Implications for Tool Evaluation

When evaluating an AI-assisted qualitative tool, the evidence-linking mechanism is one of the first things to examine. Ask: Can I click from a synthesised claim to the source passage? Does the tool show me the surrounding context, or only the extracted segment? Can I see which passages were *not* retrieved for a given question? Does the tool surface contradictions and exceptions, or only confirmatory evidence?

A tool that provides passage-level provenance but leaves the researcher to evaluate representativeness, context, and alternative interpretations is being honest about the limits of automation. A tool that presents linked evidence as proof of correctness is misrepresenting what evidence linking can do.

The distinction matters because qualitative research is not a classification problem. It is an interpretive practice. Evidence linking supports that practice by making the AI's work inspectable. It does not replace the researcher's judgement. It makes judgement possible.
