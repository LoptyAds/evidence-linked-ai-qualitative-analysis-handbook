# Real Limitations of LLM-Assisted Qualitative Work and Why Oversight Stays Necessary

## What LLMs Actually Do (and Don't Do) With Qualitative Material

Large language models process text through statistical pattern completion. Given a sequence of tokens, they predict what comes next. This works well for summarization, paraphrase, and surface-level pattern recognition across large volumes of text. But the underlying mechanism has nothing to do with understanding, interpretation, or the kind of situated judgment that qualitative analysis requires.

The practical consequence: LLMs produce outputs that *look* like analysis but are not, in themselves, analytically warranted. The distinction matters because the output format, coherent paragraphs, thematic groupings, quoted evidence, creates an illusion of completeness. Researchers who treat LLM output as a first draft rather than a finished finding are working appropriately. Those who treat it as an answer are not.

## Plausible But Unsupported Interpretations

An LLM can generate a thematic summary that sounds reasonable, cites real passages from your material, and still be wrong. The model selects evidence that fits the pattern it has constructed, not necessarily evidence that represents the dataset. If three participants express ambivalence about a program and twelve express clear support, the model may still produce a balanced "mixed reactions" theme if that pattern appears frequently in its training data. The output is plausible. It is not necessarily accurate.

This is not a bug that better prompting fixes. It is a feature of how statistical language models work. They optimize for coherence and likelihood, not for representativeness or fidelity to the specific dataset.

## Loss of Nuance and Excessive Coherence

Qualitative material is messy. Participants contradict themselves. They trail off. They use irony, indirection, and context-dependent meaning. LLMs tend to flatten this messiness into clean thematic categories. A participant who says "the training was useful, I guess, though I'm not sure it changed anything" gets coded as positive sentiment, or neutral, or mixed, but the model rarely preserves the precise ambivalence carried by the phrasing and the pause.

Worse, LLMs impose coherence. They will connect statements that participants themselves did not connect, because the model's objective function rewards making things fit. A researcher reading the output sees a tidy thematic structure and may stop looking for contradictions, tensions, or unresolved questions. The model has, in effect, closed the analysis prematurely.

## Convergence on Dominant Patterns, Inattention to Negative Cases

Qualitative rigor often depends on actively looking for cases that do not fit the emerging interpretation. LLMs do the opposite. They converge on whatever pattern is statistically strongest in the text, then reproduce that pattern across outputs. Negative cases, the one participant who had a completely different experience, the outlier response that complicates the narrative, are either omitted or folded into a broader category where their specificity is lost.

This is not a minor limitation. For many qualitative methodologies, the negative case is where the analytical insight lives. An LLM that systematically underrepresents outliers is not just inaccurate; it is methodologically counterproductive.

## Context Loss Across Long Documents

LLMs have finite context windows. Even with extended context, the model's attention decays unevenly across long inputs. A comment made early in a focus group that gets reinterpreted later, or a participant's biographical detail that reframes everything they say, may fall outside the effective range the model considers when generating a response.

The result: outputs that are locally coherent but globally inconsistent. A theme identified from the first 2000 tokens may contradict a theme from the last 2000 tokens, and the model will not flag the contradiction. The researcher only catches it if they read the full transcript themselves.

## Prompt Sensitivity and Output Variation

Run the same query twice against the same dataset. You will get different results. Temperature settings, random seeds, and model updates all introduce variation. A researcher who asks "what themes emerge around trust?" on Monday and again on Wednesday may get two different sets of themes, both plausible, neither reproducible.

This is fine for brainstorming. It is not fine for analytical claims that need to be stable enough to defend. The variation means that any single LLM output is a sample from a distribution, not a determinate result. Researchers who treat it as the latter are building analysis on shifting ground.

## Incomplete Retrieval and the Reference Fallacy

Some tools attach source references to LLM outputs, a quotation, a paragraph number, a link back to the original transcript. This is better than no references. But it does not solve the underlying problem. The model may have selected a supporting passage that is not representative, or omitted five contradictory passages that would complicate the interpretation. The reference proves the passage exists. It does not prove the passage is the right evidence for the claim.

The reference fallacy is the assumption that traceability equals validity. It does not. Traceability supports verification, it lets the researcher check the source. But the check itself is a human act of judgment. The researcher must still ask: is this passage typical? Is there counter-evidence the model did not surface? Does the context around the passage change its meaning?

## Premature Analytical Closure

Perhaps the most insidious limitation is how LLM outputs affect researcher cognition. A clean, well-structured summary feels like an answer. It satisfies the desire for closure. Researchers who receive an LLM-generated thematic map may stop asking questions, not because the map is complete, but because the format signals completeness.

The best defense is iterative questioning. Treat LLM output as a provisional map that needs to be tested, challenged, and revised against the material. Ask the model to find counter-examples. Ask it to compare two subgroups. Ask it to show you the passages it excluded. The conversational loop, query, inspect, challenge, re-query, is the mechanism that keeps the researcher in control and the analysis open.

## Why Oversight Stays Necessary

None of these limitations are disqualifying. LLMs are useful tools for processing large volumes of text, surfacing patterns, and supporting exploration. But they are tools, not analysts. The researcher remains responsible for evaluating evidence, deciding what the material means, and defending that interpretation against alternatives.

This is not a compromise. It is the correct division of labor. The model handles retrieval, organization, and synthesis at scale. The researcher handles judgment, context, and interpretive responsibility. The two functions are not interchangeable. And attaching source references to model output does not change that fact.
