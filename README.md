# Task 07 Ethics of Synthetic Media

## Project overview

This repository contains my ethical analysis and governance proposal for Research Task 7. The work begins with the synthetic-audio artifact I created in Task 6 and reasons outward from that experience. It asks what changes when synthetic communication moves across four axes: truth, consent, context, and scale. It then converts that analysis into a policy that a university communications office could use in practice.

The central conclusion is that no single safeguard is sufficient. A disclosure can be removed, provenance cannot prove that a statement is true, and a detector can return a confident but contradictory result. Responsible use therefore requires layered controls: verified content, valid consent, durable disclosure, provenance and records, defined approval, prohibited uses, incident response, and a willingness to refuse production.

## Task 6 foundation

Task 6 used a truthful analytical narrative from my Task 5 review of the 2024 Syracuse University women's lacrosse season. I generated synthetic narration through two generic preset voices:

- ElevenLabs using the preset voice Roger.
- Fish Audio using the preset voice Sarah.

The audio opened with a spoken synthetic-media disclosure. The ElevenLabs version used the full script, while the Fish Audio version was shortened because of a free-tier character limit. ElevenLabs sounded more natural in pacing and pauses. Fish Audio sounded slightly more mechanical.

The detector test became the most important bridge into Task 7. Fish Audio received a 1 percent real result. ElevenLabs received a 95 percent authentic headline score, but the detector's explanation described characteristics associated with AI-generated speech. That disagreement shows why a detector result should be treated as evidence rather than proof.

Task 6 repository: [Task_06_Deep_Fake](https://github.com/gautambalgi/Task_06_Deep_Fake)

This repository links to Task 6 rather than re-uploading its synthetic audio.

## Organizational context

The Phase B policy is written for the central communications office of a hypothetical mid-sized university. This setting was selected because such an office has useful reasons to consider synthetic media, including accessibility narration, translation, orientation content, and production prototypes. It also speaks with institutional authority to students, employees, families, alumni, media, and the public.

That combination makes governance necessary. A realistic synthetic voice can make a routine script easier to distribute, but the same capability can fabricate an endorsement, imitate a university leader, or make a false emergency message appear official. The proposed policy draws concrete boundaries between acceptable assistance and unacceptable impersonation.

This is a research proposal and is not an official policy of Syracuse University or any other institution.

## Repository map

| File | Purpose |
| --- | --- |
| [`PHASE_A_ETHICAL_ANALYSIS.md`](PHASE_A_ETHICAL_ANALYSIS.md) | Reflection on Task 6, four original ethical scenarios, and a survey of disclosure, provenance, detection, law, platform policy, and professional norms |
| [`PHASE_B_SYNTHETIC_MEDIA_POLICY.md`](PHASE_B_SYNTHETIC_MEDIA_POLICY.md) | An operational policy covering permitted and prohibited uses, consent, disclosure, provenance, review, refusal, vendors, and incident response |
| [`POLICY_LIMITATIONS.md`](POLICY_LIMITATIONS.md) | An honest stress test of where the proposed policy can fail and what residual risk remains |
| [`REFERENCES.md`](REFERENCES.md) | Primary and authoritative sources used to understand the mitigation landscape |

## What surprised me

The most surprising finding was not that one generated voice sounded more natural than another. It was that the detector could call the ElevenLabs audio 95 percent authentic while describing it as AI-generated in the same result. That made the weakness of a detector-only solution concrete. A single number can appear decisive even when the evidence underneath it is internally inconsistent.

I was also struck by how much the ethics changed without changing the tool. The same text-to-speech workflow could narrate a transparent accessibility resource, fabricate a statement in a stolen voice, or generate thousands of personalized scams. The capability itself does not determine the outcome. Truth, consent, context, scale, and accountable governance do.

## Scope and safety

- No new synthetic artifact was created for Task 7.
- No synthetic voice or likeness of an identifiable person is included here.
- The ethical scenarios are original hypotheticals rather than summaries of real victims or incidents.
- The policy treats legal compliance as a minimum and does not present itself as legal advice.

## Author

Gautam K. Balgi  
Syracuse University  
October 2026

