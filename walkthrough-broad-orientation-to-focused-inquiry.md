# Concrete Walkthrough: From Broad Orientation to Focused Inquiry Across a Dataset

## Starting Point: A Dataset and a Question

You have 47 interview transcripts, eight focus group discussions, and 412 open-ended survey responses. The research question, from the funding proposal: *How do healthcare professionals in rural clinics experience the adoption of a new electronic health record (EHR) system?* No pre-existing codebook. No methodology chosen yet. A directory of `.docx` files, `.txt` exports from the survey platform, and a deadline.

This follows one researcher's path through that dataset using an evidence-linked, AI-assisted approach. The goal is to show how movement from broad orientation to focused inquiry works when the tool supports conversational exploration rather than upfront coding.

## Initial Ingestion and Orientation

The researcher uploads everything into QInsights. The platform processes the text into a searchable corpus. No codes assigned. No themes extracted automatically. The summary view shows total word counts per source type, date ranges, speaker labels where available, and documents grouped by source category (interviews, focus groups, surveys).

First action: not asking for themes. Checking coverage. A query: *"Show me all passages where participants describe their first encounter with the EHR system."*

The AI retrieves 34 passages across 22 interview transcripts and 3 focus groups. Scanning them: some describe training sessions, some logging in for the first time alone, some mention a colleague walking them through it. The survey responses contain almost nothing about first encounters, the open-ended questions were asked later, about current usage. That is a useful early finding: the surveys will not contribute much to the adoption timeline narrative.

## Broad Pattern Detection Without Coding

Instead of coding the entire dataset, the researcher moves to a conversational prompt: *"Summarise the main concerns participants raise about the EHR system, grouping them by whether they appear more in interviews, focus groups, or surveys."*

The AI returns three groupings:

- **Interviews dominant**: workflow disruption, loss of clinical time, data entry burden, fear of making errors visible to administrators.
- **Focus groups dominant**: peer pressure to adopt quickly, comparisons between clinics, frustration that the system was chosen without clinician input.
- **Surveys dominant**: vague complaints about "slowness," mentions of workarounds, requests for more training.

Each grouping includes source references with clickable links back to the specific passages. The researcher opens three or four from each group to assess faithfulness. One interview passage is borderline: the participant described workflow disruption but then said it was temporary. Flagged for later.

## Narrowing: From Concerns to a Specific Pattern

"Data entry burden" appears across 18 interviews but in only 2 focus groups. That asymmetry is interesting. The researcher asks: *"Compare how participants in interviews versus focus groups talk about data entry. Are there differences in tone, detail, or attribution of responsibility?"*

The AI returns a comparison:

- In interviews, participants describe specific tasks (e.g., "I spend 20 extra minutes per patient on checkboxes") and often blame the system design or the vendor.
- In focus groups, participants mention data entry as a shared irritation but shift quickly to discussing how they cope, trading tips, developing shortcuts, covering for each other.
- One focus group excerpt: *"We all just do it. Nobody wants to be the one who can't keep up."*

The researcher opens the source passage. The full transcript shows the speaker was responding to someone who had just complained about data entry. The group laughter that follows suggests the comment was partly performative. Note: focus group dynamics may be suppressing individual complaints about burden. That is a methodological insight, not just a thematic one.

## Investigating Contradictions

Not all participants are negative. The researcher asks: *"Find passages where participants say something positive about the EHR system, and compare them to the passages where they are most critical. Are there participants who appear in both groups?"*

The AI identifies 11 positive passages (from 8 participants) and 42 critical passages. Three participants appear in both sets. The researcher pulls those three cases:

- Participant 17 (interview): positive about the reporting features, negative about data entry.
- Participant 33 (interview): positive about patient data access, negative about training quality.
- Participant 41 (survey only): wrote that the system "has potential" but is "not ready for our context."

Examining each full transcript: Participant 17 is a clinic manager who uses the reporting features for administrative purposes but does no direct patient data entry. Participant 33 is a nurse who works across two clinics and values remote access to patient histories. These are not contradictions within a single person's experience, they are role-based differences. The researcher refines: *"Group all participants by role (clinician, nurse, administrator, support staff) and compare their overall sentiment patterns."*

## Refining Interpretation Through Iterative Comparison

The role-based comparison shows administrators consistently more positive than clinicians. Support staff mostly neutral, focused on practical issues like login speed. The researcher now has a more specific hypothesis: the EHR adoption experience is stratified by role, not just by clinic or personality.

To test this: *"Within the clinician group only, are there differences between those who mention prior experience with other EHR systems and those who do not?"*

The AI retrieves 12 clinicians who mention prior EHR experience. Their passages are less negative overall. Several say things like *"This one is better than the last one"* or *"At least it's not [previous vendor]."* Following the links, reading full contexts: even the "better" comments are often followed by a caveat, *"But that's a low bar."*

The researcher creates a simple comparison table manually, using the source-linked passages as evidence. Three columns: role, prior EHR experience (yes/no), characteristic quote. No coding involved. The table is assembled by dragging passages from the AI results into a workspace.

## Checking for Missing Voices

The researcher pauses to ask a reflexive question: *"Which participants or groups are underrepresented in the passages retrieved so far?"*

The AI cannot answer directly, it can only report on what exists in the corpus. But the researcher uses the document list to check: of 47 interviews, 5 are with support staff, but only 1 of those 5 has been cited in any query. Opening that transcript manually: the support staff member describes a completely different set of problems, printer integration, password reset workflows, physical space for terminals. None appeared in the AI-generated summaries because the dominant patterns were clinical.

The researcher adds a deliberate query: *"Show me everything support staff say about the EHR system, regardless of whether it matches the main themes."*

## Closing the Loop: From Focused Findings Back to the Broad Question

After three sessions of iterative inquiry, the researcher has a set of linked findings:

1. The adoption experience is not uniform, stratified by professional role and by prior EHR experience.
2. Focus groups underrepresent individual burden due to group dynamics.
3. Support staff have distinct concerns that do not surface in clinician-dominated analyses.
4. The most negative accounts come from clinicians without prior EHR experience who do direct data entry.

Each finding is supported by source passages the researcher has inspected. Each also carries a caveat: sample size for some subgroups is small (e.g., only 5 support staff interviews). The researcher writes these caveats into the analysis notes.

The broad question, *How do healthcare professionals experience EHR adoption?*, now has a more precise answer: *It depends on role and prior experience, and the method of data collection (interview vs. focus group) shapes what gets reported.*

The researcher has not coded a single line of text. The analytical work was done through questioning, comparing, inspecting source passages, and exercising interpretive judgment. The AI retrieved and organized the material; the researcher decided what it meant and whether the evidence was adequate.
