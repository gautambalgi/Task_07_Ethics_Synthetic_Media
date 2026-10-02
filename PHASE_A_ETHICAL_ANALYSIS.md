# Phase A Ethical Analysis

## From a Synthetic Sports Narrative to Institutional Governance

### Starting from the Task 6 artifact

In Task 6, I converted a verified analytical narrative from Task 5 into synthetic speech. The source text summarized my analysis of the 2024 Syracuse University women's lacrosse season. It argued that the team's closest path to improvement was offensive development and that Emma Tyrrell was the player around whom that improvement could be organized. The purpose of Task 6 was not to invent a new claim. It was to see what happened when a genuine analytical argument was separated from my own voice and delivered by a realistic synthetic speaker.

I produced two audio versions. The first used the ElevenLabs preset voice "Roger." The second used the Fish Audio preset voice "Sarah." Both were generic voices supplied by the tools rather than clones of identifiable people. The ElevenLabs version used the complete script. Because of a free-tier character limit, the Fish Audio version used only part of the same script. Each version began with a spoken disclosure identifying the recording as AI-generated and created for a research assignment. The file names also included the word `SYNTHETIC`, and the Task 6 repository documented the tools, voices, script, and evaluation.

The comparison produced a result that now anchors my ethical analysis. The ElevenLabs version sounded substantially more human to me. Its pacing, warmth, and pauses made it feel like a person speaking rather than a system reading. The Fish Audio version was clear but more even and mechanical. When I tested the first 30 seconds of each file with the same AI-voice detector, the Fish Audio version was labeled "Likely AI-Generated" with a 1 percent real score. The ElevenLabs version received a 95 percent "Likely Authentic" headline score, but the written explanation beneath that score described the audio as strongly indicative of AI-generated speech. The same detector therefore presented incompatible conclusions about the same clip.

Task 6 was a benign use: the analysis was truthful, the voices were generic presets, and the disclosure was explicit. Even so, the exercise demonstrated a capability that can transfer authority from a human-sounding voice to words that no human speaker actually uttered. The ethical issue is not limited to whether a sentence is true. It also includes who appears to be speaking, whether the audience understands the method of production, what happens when the recording leaves its original context, and how cheaply the process can be repeated.

## What I notice after returning to the artifact

Listening again, the most striking feature is how little technical effort is required to create a plausible speaker. I did not train a model, collect a voice dataset, or edit individual phonemes. I supplied a script, selected a preset, and generated an MP3. The quality difference between the tools was real, but neither output required specialized audio engineering. A person with a laptop and a short script can create a voice that may pass a casual listen.

The process log identified cadence and pauses as the remaining seam between natural and synthetic speech. That remains true in the direct comparison, but the ElevenLabs output also shows why this seam is an unstable safeguard. A listener who is not actively searching for artifacts may hear an ordinary narrator. The detector result reinforces that point. A numerical score can look authoritative while its own explanation points in the opposite direction. If I had reported only the 95 percent headline, I would have misrepresented the tool's output. Detection therefore creates a second interpretation problem: users must evaluate the detector rather than merely read its score.

The Fish Audio character limit also mattered. I originally intended to hold the script constant across both systems, but the free tier prevented a fully controlled comparison. That limitation did not make the exercise invalid, but it narrowed what could be concluded. It is a reminder that process documentation is ethically relevant. Without documenting the shorter Fish Audio script, a reader could attribute every difference to voice quality even though the inputs were not perfectly identical.

Neither system refused the benign sports-analysis script. I did not test requests involving impersonation, deception, or harmful material, so Task 6 does not establish how either provider's safeguards would behave under misuse. The absence of a refusal in this exercise is therefore not evidence that the tools have no safeguards. It only shows that an ordinary truthful script moved through the systems with little friction.

There are uses I would not reproduce. I would not substitute a cloned real person's voice for either preset without specific permission. I would not remove the disclosure to test whether listeners could be fooled in an uncontrolled setting. I would not use the technique for an emergency announcement, disciplinary communication, endorsement, or message that depends on the personal authority of the apparent speaker. The line I draw is not simply between true and false content. It is between transparent assistance and borrowed identity.

## Ethical analysis across four axes

### Truth axis

Imagine that the same production method is used by someone who writes a false university athletics announcement. The recording states that a star player has been removed from the team for misconduct and that the university has confirmed the decision. A warm, measured synthetic narrator delivers the claim in the style of an official recap. The file is posted shortly before an important game and is shared in group chats before the university can respond.

The delivery mechanism is almost unchanged from Task 6. A script is entered, a voice is selected, and an MP3 is produced. The ethical character changes because the content is fabricated and presented with cues of institutional confidence. The harm is not only that listeners receive an incorrect fact. The voice lowers the psychological distance between assertion and evidence. A fluent speaker seems to stand behind the statement even though no accountable person does.

The likely consequences extend beyond the athlete. Teammates and staff may face questions, the subject may suffer reputational damage, and the university may have to disprove a claim that never deserved initial credibility. Even after a correction, copies of the recording may continue to circulate. A disclosure that the voice is synthetic would help, but it would not make the false allegation responsible. Transparent fabrication remains fabrication.

The truth axis therefore requires controls that are independent of production method. A truthful synthetic message should be verified against an approved source before publication. High-impact factual claims should have a named human owner. Disclosure cannot replace fact-checking, and provenance cannot prove that the words inside an authentic file are accurate.

### Consent axis

Imagine that a student organization wants a recognizable introduction for an event. Instead of requesting a recording from the dean, a member collects short clips from public speeches and clones the dean's voice. The resulting audio says, "I am proud to endorse this event and encourage every student to attend." The event itself is legitimate and the statement is not offensive. The dean, however, never said it and never authorized the use of the voice.

The change from Task 6 is the use of another person's identity. Roger and Sarah were generic presets. A cloned dean would carry a relationship, reputation, and institutional role into the recording. Listeners would not hear an interchangeable narrator. They would hear a specific person whose authority could affect attendance, fundraising, or trust.

Consent must be specific rather than implied from public availability. A speech posted online is permission to listen to that speech, not permission to construct new speech in the person's voice. Consent must also identify purpose, channels, duration, editing rights, and revocation. A general approval to make one orientation video should not become authorization to create future endorsements.

At this boundary, the technology changes from a communication tool into a mechanism for appropriating agency. The represented person loses control over what appears to be their own expression. Written permission, review of the final output, and a clear withdrawal process are therefore minimum requirements. Some contexts should remain prohibited even with consent, particularly emergency instructions and communications where the audience must know that a specific official personally spoke.

### Context axis

Imagine that a university communications office publishes a synthetic orientation narration. The recording begins with the same kind of disclosure used in Task 6: "This is an AI-generated voice." The description repeats the disclosure, and the full recording is accurate. A third party later downloads the file, removes the first sentence, and posts a 20-second excerpt under the caption "University official admits housing is unavailable."

The original artifact may have been responsibly produced, but the audience for the excerpt does not receive the original context. The disclosure was attached to the beginning rather than to the excerpted segment. The new caption also changes the implied meaning. The speaker now appears to be an identifiable institutional source even if the original used a generic voice.

This scenario shows that disclosure is fragile when it exists only at one location. Files are cropped, transcribed, compressed, remixed, and re-uploaded. Descriptions become separated from media. Metadata may be stripped. A label can be clear at publication and absent at consumption.

Responsible design must anticipate this movement. For video, the disclosure should remain visible throughout or recur at reasonable intervals. For audio, it should appear at the beginning and end, with an audible identifier that survives common excerpts when feasible. Captions and descriptions should repeat the disclosure. The organization should preserve the original, maintain a public verification page, and use tamper-evident provenance when supported. None of those controls can prevent every deceptive edit, but together they make the official version easier to identify and the altered version easier to challenge.

### Scale axis

Imagine that a bad actor obtains public directory information and automatically generates 20,000 synthetic messages. Each message uses the recipient's name, academic program, and an invented financial-aid deadline. The voice sounds calm and administrative. Recipients are instructed to visit a fraudulent payment site to preserve their aid.

Task 6 produced two clips through a manual process. At scale, generation becomes a system rather than a single artifact. Personalization can make each message feel relevant, while automation reduces the cost of experimentation. The actor can vary voices, wording, urgency, and delivery channels until one combination succeeds. Even a low response rate can harm many people.

Scale also changes the defender's problem. A communications office can correct one false clip, but it may not be able to identify thousands of customized versions. Detectors must process large volumes, and platform enforcement may occur after recipients have acted. The audience cannot reasonably conduct a forensic analysis of every message.

The scale axis supports strict limits on personalization, bulk generation, and high-stakes topics. Synthetic media should not communicate individualized financial, disciplinary, admissions, medical, or safety decisions. Approved public messages should point to an authenticated institutional page rather than request sensitive action inside the recording. Rate limits, access controls, audit logs, and human approval are organizational protections, but the most reliable control for some uses is refusal.

## Mitigation landscape

No single mitigation resolves the problem. The most defensible approach is layered: truthful content, consent, visible disclosure, provenance, limited use, human approval, records, monitoring, and a response plan.

### Disclosure norms

Disclosure promises to tell an audience that a voice, face, image, or scene was generated or materially altered. It can be spoken, displayed on screen, placed in a caption, added to a file name, or attached through a platform's upload workflow. Task 6 used several forms: a spoken opening sentence, synthetic file names, and repository documentation. Those signals made the intent clear to a person encountering the files in their original setting.

Disclosure works best when it is immediate, understandable, difficult to miss, and repeated across the places where the content will appear. It performs less well when audiences do not understand the label, when a label is placed only in a description, or when the content is excerpted. A label also says nothing about whether the underlying statement is true, authorized, or fair.

Platform practice illustrates both the value and the dependency. YouTube requires disclosure for realistic content that is generated or meaningfully altered and may apply labels through creator disclosure, internal detection, or Content Credentials. Meta also requires disclosure for certain photorealistic video and realistic-sounding audio. These mechanisms reach large audiences, but the creator and platform still control whether and how the label appears.

For an organization, disclosure should be mandatory but never treated as permission. A prohibited impersonation does not become acceptable because it is labeled. The policy in Phase B therefore combines disclosure with consent, factual verification, use restrictions, and approval.

### Provenance and Content Credentials

Provenance records where a digital asset came from and how it changed. The C2PA Content Credentials standard can associate an asset with a signed manifest containing origin and editing assertions. Cryptographic hashes and signatures make the credential tamper-evident. Durable credentials can also use watermarking or fingerprint lookup to reconnect an asset to its manifest.

The promise is stronger chain-of-custody information. A communications office could sign an approved file so that compatible tools can verify that it came from the office and has not been altered since signing. That would be useful when distinguishing an official orientation recording from a modified copy.

The limits are equally important. C2PA states that provenance can be incomplete, metadata can be removed, and provenance alone cannot establish that an asset's message is factually true. Its effectiveness also depends on adoption by creation tools, publishing systems, platforms, and viewers. An unsigned file is not automatically false, and a properly signed false statement remains false.

Task 6 did not complete a cryptographic provenance test. Its provenance was documentary: the repository, file names, source script, spoken disclosure, and process log. That record is useful, but it should not be described as C2PA verification. For future institutional work, the policy requires use of Content Credentials when the workflow supports them while retaining a separate internal record even when credentials are unavailable or stripped.

### Detection

Detection promises to classify an artifact as synthetic by finding model traces, acoustic regularities, inconsistencies, watermarks, or other signals. In Task 6, it correctly treated the more mechanical Fish Audio clip as synthetic. It failed to produce a coherent result for the more natural ElevenLabs clip: a 95 percent authentic headline appeared above an explanation describing AI characteristics.

That contradiction demonstrates why a detector score is evidence rather than proof. Performance can change with generator, voice, language, duration, compression, background noise, and post-processing. New generators can also produce artifacts outside a detector's training distribution. A false negative may create confidence in a synthetic file, while a false positive may wrongly discredit a real speaker.

Detection remains useful for triage. It can identify content that deserves human review and can be combined with provenance, source verification, and comparison with known originals. It should not be the sole basis for accusing a person of fabrication or approving a high-impact communication. The Phase B policy prohibits treating one automated detector as a final verdict.

### Legal and regulatory approaches

Law addresses pieces of the synthetic-media problem rather than providing one universal rule. The legal terrain includes fraud and impersonation, privacy and publicity rights, intellectual property, election communications, robocalls, consumer protection, and non-consensual imagery. Requirements differ by jurisdiction and context.

Two federal examples show why the medium and use matter. The Federal Trade Commission's Government and Business Impersonation Rule gives the agency tools against material false impersonation of governments and businesses in commerce. The Federal Communications Commission has confirmed that AI-generated voices fall within the Telephone Consumer Protection Act's restrictions on artificial or prerecorded voices. These rules do not function as a complete university synthetic-media code, but they show that using an AI voice does not place conduct outside existing regulation.

Legal compliance is a floor. An institution may face serious ethical and reputational harm even when no specific synthetic-media statute applies. The proposed policy therefore requires legal or privacy review for identifiable likenesses, high-impact subjects, paid distribution, regulated communications, and uncertain jurisdiction. It does not ask ordinary staff members to make legal determinations themselves.

### Platform policy

Platforms can require creator disclosure, add labels, preserve or interpret Content Credentials, accept impersonation complaints, reduce distribution, or remove harmful content. Their scale makes these controls important. YouTube, for example, requires disclosure for realistic altered or generated content and may apply an AI label automatically when valid C2PA metadata is present or its systems detect alteration.

Platform controls break at their boundaries. Policies differ across services, enforcement may be delayed, and content can move to private messages or platforms with weaker rules. A platform label may also disappear when a file is downloaded and reposted elsewhere. An organization cannot outsource its ethical obligations to the distribution service.

The practical implication is to satisfy both the institution's stricter internal disclosure standard and each platform's current upload requirements. The organization must keep an official copy and verification record outside the platform so that its evidence does not depend on one company's interface.

### Professional and organizational norms

Professional norms translate broad principles into role-specific expectations. Journalism provides a useful example because credibility is central to its work. The Associated Press has required careful verification of AI-produced material and has restricted publication of synthetic photo, video, and audio except in narrow editorial circumstances. A university communications office is not a newsroom, but it also speaks with institutional authority and should protect the reliability of its public record.

Organizational norms can require a named human owner, prepublication review, consent records, documented tools, restricted accounts, incident reporting, and periodic audits. They can also say no to a use that a tool technically allows. Their weakness is dependence on implementation. A policy that employees cannot understand, that managers do not enforce, or that vendors can bypass becomes symbolic rather than protective.

For this reason, the Phase B policy uses concrete categories, assigned reviewers, required records, and explicit prohibited uses. It also includes a refusal rule. Responsible governance is not the promise that every synthetic artifact will be detected. It is the creation of a process in which the organization can explain who authorized a use, why it was allowed, how the audience was informed, and what happens if the content escapes its intended context.

## Conclusion

Task 6 showed that synthetic speech can be convincing even when it is produced through a simple free-tier workflow. The ethical lesson is not that every synthetic voice is deceptive. My own artifact was truthful, disclosed, and built from generic presets. The lesson is that realism transfers communicative authority without automatically transferring accountability.

The contradictory detector result makes a detector-only response inadequate. The ease of stripping context makes disclosure-only governance inadequate. The difference between a generic preset and an identifiable person's voice makes consent central. The ability to automate production makes scale a separate ethical dimension rather than merely more of the same artifact.

The policy that follows is therefore built around layered accountability: narrow permitted uses, categorical refusals, documented consent, resilient disclosure, provenance and records, human approval, source verification, and an incident process. These measures cannot eliminate misuse, but they can prevent the organization from treating technical capability as sufficient justification for deployment.

## Sources cited in this analysis

- [Task 6 repository](https://github.com/gautambalgi/Task_06_Deep_Fake)
- [NIST AI 100-4: Reducing Risks Posed by Synthetic Content](https://doi.org/10.6028/NIST.AI.100-4)
- [NIST AI 600-1: Generative Artificial Intelligence Profile](https://doi.org/10.6028/NIST.AI.600-1)
- [C2PA Content Credentials Explainer, version 2.4](https://spec.c2pa.org/specifications/specifications/2.4/explainer/Explainer.html)
- [YouTube: Disclosing use of generative AI content](https://support.google.com/youtube/answer/14328491)
- [Meta: Misinformation and AI disclosure policy](https://transparency.meta.com/policies/community-standards/misinformation/)
- [FTC: Government and Business Impersonation Rule](https://www.ftc.gov/news-events/news/press-releases/2024/04/ftc-announces-impersonation-rule-goes-effect-today)
- [FCC: AI-generated voices and the TCPA](https://www.fcc.gov/document/fcc-makes-ai-generated-voices-robocalls-illegal)
- [Associated Press guidance on generative AI in newsrooms](https://www.ap.org/media-center/ap-in-the-news/2023/ap-other-news-organizations-develop-standards-for-use-of-artificial-intelligence-in-newsrooms/)

