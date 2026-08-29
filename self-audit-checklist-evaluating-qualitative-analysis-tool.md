# Self-Audit Checklist for Evaluating a Qualitative Analysis Tool

## Self-Audit Checklist for Evaluating a Qualitative Analysis Tool

Use this checklist as a structured scoring instrument, not a passive reading list. Each criterion maps to a specific failure mode that surfaces when a tool claims AI capability but cannot deliver defensible qualitative work. Score each item 0 (absent), 1 (partial), or 2 (fully met). A total below 16 out of 24 means the tool should not be trusted for funded or published research.

### Data Security and Compliance

- [ ] The tool offers a published data processing agreement (DPA) that covers GDPR, HIPAA, or your jurisdiction's equivalent. Without this, you cannot legally transfer raw interview recordings or transcripts.
- [ ] Data is encrypted at rest (AES-256 minimum) and in transit (TLS 1.2+). Ask for the specific cipher suites, not marketing copy.
- [ ] The vendor provides a clear data retention and deletion policy. After project completion, can you force deletion of all copies including backups? Most tools hold data indefinitely unless you request removal in writing.
- [ ] Server location matches your institutional requirements. A tool hosted on US East Coast servers may violate EU or Canadian public sector data residency rules regardless of what the privacy policy says.

### Evidence Linking and Traceability

- [ ] Every coded segment, theme, or summary includes a direct link back to the source text (and ideally the audio/video timestamp). If you click a code and cannot see the exact quote that generated it, the tool fails this criterion.
- [ ] The tool preserves the original transcript formatting and speaker labels. Some NLP pipelines strip punctuation, merge speakers, or flatten dialogue. This destroys conversational context.
- [ ] You can export a full audit trail showing which researcher or AI action created each code, at what time, from which source file. Without this, a reviewer cannot verify your analysis process.

### Researcher Control Over Analysis

- [ ] The AI suggestions are non-destructive. You must be able to accept, reject, or modify every AI-generated code or theme without the tool overwriting your manual work.
- [ ] The tool allows you to create your own codebook from scratch, import an existing one, or start from AI suggestions and then edit freely. A tool that forces you to accept its predefined categories is not researcher-led.
- [ ] You can reorder, merge, split, or delete codes at any point. Some tools lock the codebook after the "auto-coding" phase. That is not analysis, that is a report generator.

### Codebook Management

- [ ] The codebook supports hierarchical structures (parent-child relationships) and definitions for each code. Flat lists of tags cannot represent thematic relationships.
- [ ] You can assign memos, annotations, or definitions to individual codes and to specific coded segments. Memos are where your interpretive reasoning lives.
- [ ] The tool tracks codebook version history. If you rename or restructure codes, can you see what changed and when? Without versioning, collaborative teams lose weeks to confusion.

### NLP Accuracy for Unstructured Data

- [ ] The tool handles domain-specific vocabulary, slang, and non-standard grammar. Test it on a sample of your actual data, not their demo dataset. Academic interview transcripts contain false starts, hesitations, and regional idioms that generic NLP models misclassify.
- [ ] Sentiment or thematic classification does not rely solely on keyword matching. Ask how the model handles negation ("I did not find the training useful") and sarcasm. Most commercial NLP tools fail both.
- [ ] The vendor discloses which underlying model or models they use (e.g., GPT-4, a fine-tuned BERT variant, a proprietary transformer). If they say "our proprietary AI" without naming the architecture, you cannot evaluate its known limitations.

### Output Auditability

- [ ] You can export the complete project in a standard format (CSV, JSON, XML, or a qualitative analysis interchange format). Proprietary export formats that lose code definitions or memo content are a lock-in trap.
- [ ] The tool generates a methods report or log that documents every automated step: preprocessing, tokenization, model inference, post-processing. This is required for reproducibility in peer review.
- [ ] The output includes confidence scores or uncertainty indicators for AI-generated codes. A tool that assigns every code with equal confidence is hiding model limitations.

### Scoring and Next Steps

A score of 20-24 means the tool is likely production-ready for rigorous qualitative work. 12-19 means it may work for internal discovery but not for published findings. Below 12, the tool is a prototype dressed as a product.

No tool scores perfectly across all six criteria today. The trade-off is usually between researcher control and NLP accuracy. Tools that give you full manual override often have weaker automated coding. Tools with strong NLP are often black boxes that resist audit. The point of this checklist is not to find a perfect score but to know exactly where your chosen tool falls short so you can compensate with methodology.

For a real-world example of a tool designed around evidence linking and researcher control, see the [QInsights profile](./qinsights-evidence-linked-ai-analysis-option.md). Their approach prioritizes traceability over automation speed, which is a defensible trade-off for academic and government work.
