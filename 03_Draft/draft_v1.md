# AI Governance Across Jurisdictions
## EU, United States and India — A Regulatory Comparison Brief

**Prepared by: Nisarg Kamble  |  AI Governance Portfolio, Project 5 of 5  |  September 2026**

> **Status: pre-verification draft.** This is the original draft as first written, before
> the systematic fact-check in `../01_Research/research_log.md`. Kept here unmodified as an
> audit trail -- see `draft_v2.md` for the corrected version. Section 5 (India) names
> "Do No Harm" as the anchoring principle among the seven sutras -- this does not appear in
> the real MeitY framework and is corrected in v2. Every other section (EU, US) was checked
> and found already accurate -- an unusually clean result given the density of specific dates
> and regulation numbers this brief contains.

1. Executive Summary

As of September 2026, the European Union, the United States, and India represent three fundamentally different regulatory philosophies for AI: the EU applies a binding, horizontal, risk-tiered statute now partway through a staggered — and recently deferred — implementation timeline; the United States has no federal AI statute and instead a fragmented, actively shifting patchwork of state laws, several of which have changed materially within 2026 alone; and India has deliberately chosen a non-binding, principle-based guidance framework over a standalone AI law, relying on existing statutes to reach AI-related harms. This brief compares all three as they currently stand, not as they were originally designed, since each has moved substantially from its original 2023-2024 blueprint.

2. Comparative Scope

This brief focuses on general-purpose and high-risk AI regulation as it would apply to an AI-based credit-scoring tool — a use case directly relevant to Northstar FinTech Services (the fictional organization used throughout this portfolio) and one that would likely be classified as high-risk or its jurisdictional equivalent in most frameworks discussed below.

3. European Union

The EU AI Act (Regulation (EU) 2024/1689) entered into force on 1 August 2024 and applies in stages. Prohibited practices and AI literacy obligations became enforceable on 2 February 2025. General-purpose AI (GPAI) provider obligations followed on 2 August 2025. The Act's general application, including Article 50 transparency duties (chatbot disclosure, AI-generated content labeling), was scheduled for 2 August 2026 and — critically — this date was not deferred.

What did change: the Digital Omnibus on AI (Regulation (EU) 2026/1744) was signed 8 July 2026, published in the Official Journal 24 July 2026, and entered into force 27 July 2026 — six days before the original high-risk deadline. It deferred compliance for standalone high-risk AI systems (Annex III, which would include a credit-scoring tool) from 2 August 2026 to 2 December 2027, and for AI embedded in already-regulated products (Annex I) from 2 August 2027 to 2 August 2028. Separately, the Article 50(2) watermarking obligation specifically was pushed to 2 December 2026, a shorter deferral than the rest of Article 50. This is enacted, binding law, not a proposal — an important distinction given how much AI-Act commentary from 2024-2025 still assumes the original August 2026 high-risk deadline.

For a credit-scoring tool specifically: it would fall under Annex III as a high-risk system used in creditworthiness assessment, meaning its substantive high-risk obligations (risk management system, data governance, human oversight, conformity assessment) do not bite until December 2027 — but the Article 50 transparency obligations already apply from August 2026, and GDPR's existing automated-decision-making protections (Article 22) apply regardless of the AI Act's timeline.

4. United States

The United States has no comprehensive federal AI statute; regulation is fragmented across states, and — unusually for a two-year-old regulatory landscape — several state laws changed substantially within 2026 itself.

Texas

The Texas Responsible AI Governance Act (TRAIGA, HB 149) was signed 22 June 2025 and took effect 1 January 2026 — it is currently the most broadly enforceable state AI law, applying to any developer or deployer serving Texas residents with no size threshold. It is conduct-based (prohibiting specific uses like intentional discrimination and unlawful manipulation) rather than a broad high-risk impact-assessment regime; enforcement runs through the Texas Attorney General with a 60-day cure period and no private right of action.

California

California has enacted a stack of AI-adjacent laws rather than one comprehensive statute: SB 53 (Transparency in Frontier Artificial Intelligence Act), signed 29 September 2025 and effective 1 January 2026, imposes safety-framework and catastrophic-risk disclosure duties on large frontier-model developers specifically — it would not directly govern a fintech's credit-scoring model unless that model itself qualified as a frontier foundation model, which is unlikely. AB 2013 (training-data transparency) is also in force since January 2026. Separately, California's Civil Rights Council automated-decision-making-technology (ADMT) regulations are in force, with significant-decision compliance obligations phasing in through January 2027 — this is the piece most directly relevant to an AI credit-scoring use case operating in California.

Colorado

This is the clearest illustration of how unstable the US state landscape currently is. Colorado's original AI Act (SB 24-205, signed May 2024) was the first comprehensive US state AI law and was structurally similar to the EU's risk-tiered model, including duty-of-care and algorithmic-discrimination obligations. Its effective date was delayed twice, then in April 2026 a federal magistrate judge stayed its enforcement following a lawsuit by xAI in which the U.S. Department of Justice intervened — the first instance of federal intervention against a state AI law. On 14 May 2026, Colorado repealed the original Act entirely and replaced it with the narrower Automated Decision-Making Technology Act (SB 26-189), which drops the discrimination/duty-of-care framework in favor of a disclosure-and-consumer-notice model, effective 1 January 2027. As of September 2026, Colorado's AG has stated neither the original nor replacement law will be enforced until rulemaking concludes.

Federal backdrop

A March 2026 federal “National Policy Framework for Artificial Intelligence” called on Congress to pass federal AI legislation, and a June 2026 executive order established a DOJ AI Litigation Task Force specifically to challenge state AI laws on preemption grounds. As of September 2026, no federal preemption has actually succeeded — Texas TRAIGA, California's law stack, and Colorado's new ADMT Act all remain enacted, enforceable state law on their own timelines. This is an active, unresolved conflict, not a settled question, and should be tracked rather than treated as decided.

5. India

India has explicitly chosen not to enact a standalone AI statute. On 5 November 2025, MeitY published the India AI Governance Guidelines under the IndiaAI Mission — a voluntary, principle-based framework built around seven foundational principles (“sutras”), including “Do No Harm” as the anchoring principle. The Guidelines propose three new institutions (an AI Governance Group, a Technology & Policy Expert Committee, and an AI Safety Institute) and recommend an action plan across short/medium/long-term timelines, but they are explicitly government guidance, not binding law — the stated policy conclusion was that India's existing IT Act, DPDP Act, and Consumer Protection Act already reach most AI-related harms, and that a dedicated AI statute is not needed at this stage.

In practice, this means an AI credit-scoring tool deployed in India today is governed by: (a) the DPDP Act, 2023, insofar as it processes personal data — noting, as established in Project 2 of this portfolio, that the DPDP Act's substantive consent and breach-notification obligations are not yet in force and become effective 13 May 2027; (b) RBI's existing guidance on digital lending and algorithmic decision-making in financial services, which predates and operates independently of the AI-specific guidelines; and (c) the voluntary AI Governance Guidelines themselves, which encourage but do not mandate self-certification, risk mitigation, and transparency. There is also a proposed amendment to the IT Rules requiring labeling of AI-generated and deepfake content, currently under consultation rather than in force.

6. Comparison Table

7. Business Implications

For a multinational or India-headquartered fintech operating an AI credit-scoring tool across some combination of these jurisdictions, three practical implications follow directly from the analysis above:

Design to the strictest applicable standard now, even where it is not yet legally required. The EU's high-risk obligations (risk management, human oversight, conformity assessment) do not bite until December 2027, but building toward them now avoids a compressed compliance sprint later, and substantially overlaps with what RBI and DPDP-aligned practice already expect in India.

Treat US state compliance as a moving target, not a fixed map. Colorado's law changed twice within 2026 alone; a compliance program built rigidly around any single state's current statute risks being built on law that no longer exists within months. A control framework should map to underlying risk categories (discrimination, transparency, human oversight) that persist across state-law rewrites, rather than to the specific text of any one state law.

In India, voluntary today does not mean irrelevant. The Guidelines' own action plan explicitly anticipates legislative amendments where gaps are identified; early voluntary alignment (self-certification, incident reporting practices) positions an organization ahead of any future mandatory regime, consistent with how the Guidelines describe their own medium-term trajectory.

8. Governance Strategy

A practical baseline governance model for an organization operating across these three jurisdictions should be built around risk categories rather than any single jurisdiction's specific legal text, using a structure similar to the NIST AI RMF applied in Project 2 of this portfolio (Govern / Map / Measure / Manage) as the jurisdiction-agnostic backbone, with jurisdiction-specific overlays applied at the Manage stage:

A single internal high-risk classification (as established in Northstar's Responsible AI Policy, Project 3) that is deliberately built to be at least as strict as the strictest applicable external regime, so that jurisdictional differences become a question of which additional disclosures apply, not whether the underlying system is safe.

A jurisdiction-tracking function (owned by Legal/Compliance, feeding the AI Governance Committee) specifically because, as shown above, the applicable law in a given jurisdiction can change within months rather than years.

Documentation practices (model cards, impact assessments, human-oversight logs) built once to the most demanding standard (currently the EU's Annex III documentation requirements, even though not yet enforceable) and reused across jurisdictions, rather than maintained separately per jurisdiction.

9. Key Risks for Enterprises

Regulatory whiplash: building compliance infrastructure around a specific law's current text (as Colorado demonstrated) risks that infrastructure becoming obsolete before it is ever tested by enforcement.

False sense of safety from voluntary compliance: in India, self-certification under the voluntary Guidelines does not create the same legal defensibility as compliance with a binding statute, and should not be represented internally or externally as equivalent to legal compliance.

Premature reliance on deferred deadlines: treating the EU's December 2027/August 2028 dates as fixed and distant risks a repeat of the same last-minute compression that led to the Digital Omnibus deferral in the first place — the deferral itself is evidence that implementation timelines in this space are not reliably fixed.

10. Conclusion

The three jurisdictions examined here are not converging toward a single global AI governance model; if anything, September 2026 shows them diverging further — the EU deepening a binding risk-tiered statute (while proving willing to defer its own deadlines under pressure), the United States fragmenting further at the state level while a federal preemption fight remains unresolved, and India deliberately choosing voluntary guidance over binding law. For an organization deploying AI across these jurisdictions, the defensible governance posture is not to chase the letter of any single regime, but to build toward the most demanding substantive requirements across all three, track each jurisdiction's legal status on an ongoing basis rather than a point-in-time basis, and treat this comparison brief itself as a snapshot requiring regular refresh, not a static reference document.

References

Regulation (EU) 2024/1689 (EU AI Act) and Regulation (EU) 2026/1744 (Digital Omnibus on AI), Official Journal of the European Union.

Texas HB 149 (Texas Responsible Artificial Intelligence Governance Act), signed 22 June 2025, effective 1 January 2026.

California SB 53 (Transparency in Frontier Artificial Intelligence Act) and AB 2013, effective 1 January 2026; California Civil Rights Council ADMT regulations.

Colorado SB 24-205 (repealed) and SB 26-189 (Automated Decision-Making Technology Act), signed 14 May 2026, effective 1 January 2027.

Ministry of Electronics and Information Technology, Government of India. India AI Governance Guidelines, published 5 November 2025, under the IndiaAI Mission.

Ministry of Electronics and Information Technology, Government of India. Digital Personal Data Protection Act, 2023, and DPDP Rules, 2025 (staged commencement).

Note: This brief reflects publicly reported regulatory status as of September 2026. Several elements discussed (the Digital Omnibus deferral, Colorado's repeal-and-replace, India's Guidelines) are recent developments; readers should verify current status before relying on specific dates for compliance decisions.
