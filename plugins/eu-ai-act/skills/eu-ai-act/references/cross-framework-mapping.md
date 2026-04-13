# Cross-framework mapping — EU AI Act to other frameworks

## Requirement-level mapping

| EU AI Act requirement | ISO 42001 control | NIST AI RMF subcategory | South Korea AI Act | Brazil AI Act | NYC LL144 |
|-----------------------|-------------------|------------------------|-------------------|---------------|-----------|
| Risk classification (Art. 6, Annex III) | A.6 — AI system impact assessment | MAP-1 (context established), MAP-2 (AI risks and benefits mapped) | High-risk AI classification system with designation criteria | Risk-based tiered classification (high-risk, excessive-risk) | AEDT determination — whether tool is an automated employment decision tool |
| Risk management system (Art. 9) | Clause 6.1.2 — AI risk assessment process | GOVERN (governance structure), MAP (risk identification), MANAGE (risk treatment) | AI impact assessment requirement for high-risk systems | Algorithmic impact assessment for high-risk AI | No direct equivalent — limited to bias audit scope |
| Data and data governance (Art. 10) | A.7 — Data for AI systems (quality, provenance, preparation) | MEASURE ME-1 (appropriate methods and metrics) | Data quality and management requirements for AI training | Data governance provisions including data quality, accuracy, and relevance | No direct equivalent — data requirements implicit in bias audit methodology |
| Technical documentation (Art. 11, Annex IV) | A.5.6 — Documentation of AI systems | MAP MAP-5 (documentation of system characteristics) | Documentation requirements for high-risk AI systems | Documentation obligations for AI system providers | No direct equivalent — summary results published but no technical documentation requirement |
| Record-keeping and logging (Art. 12) | A.5.6 — Documentation; A.8.3 — Reporting | MEASURE ME-2 (monitoring and tracking) | Logging and audit trail requirements | Record-keeping provisions for AI system decisions | Audit records must be retained but no real-time logging requirement |
| Transparency and information to deployers (Art. 13) | A.8 — Transparency and provision of information (explainability) | GOVERN GV-1.2 (documentation and communication) | Transparency obligations including right to explanation | Right to information about AI system use; right to explanation of decisions | Notice requirement — employers must notify candidates/employees 10 business days before use |
| Human oversight (Art. 14) | A.5.8 — Controlling and monitoring AI systems (human oversight) | MANAGE MG-2 (human decision-making retained) | Human oversight provisions; right to request human review | Right to human review of AI-assisted decisions | Alternative selection procedure — candidates may request alternative process |
| Accuracy, robustness, cybersecurity (Art. 15) | A.5.4 — System validation and verification | MEASURE ME-1 (performance metrics), MANAGE MG-3 (risk responses) | Performance and reliability standards for AI systems | Accuracy and reliability requirements | No direct equivalent — accuracy implicitly addressed through bias audit statistical analysis |
| Bias and fairness (Art. 10(2)(f)) | A.5.5 — Assessing AI system impacts (bias management) | MEASURE ME-3 (fairness and bias evaluation) | Non-discrimination obligations; fairness requirements | Non-discrimination provisions; prohibition of discriminatory outcomes | Bias audit requirement — annual independent audit for disparate impact by race/ethnicity and sex |
| Incident reporting (Art. 73) | A.8.3 — Reporting AI system performance and incidents | MANAGE MG-4 (incident response) | Incident reporting to competent authorities | Incident reporting obligations for serious harm | No incident reporting requirement under LL144 |
| Post-market monitoring (Art. 72) | A.8 — Operation and monitoring of AI systems | MEASURE (ongoing measurement and monitoring) | Ongoing monitoring requirements for high-risk AI | Continuous monitoring provisions | Annual bias audit constitutes periodic monitoring (limited scope) |
| Conformity assessment (Art. 43, Annexes VI-VII) | Clause 9 — Performance evaluation; Clause 10 — Improvement | No direct equivalent — NIST is voluntary framework | Certification and conformity requirements under development | Conformity assessment provisions for high-risk AI | No conformity assessment — compliance demonstrated through published bias audit |

## Compliance gap analysis across frameworks

| Gap area | Detail |
|----------|--------|
| Conformity assessment and CE marking | Unique to EU AI Act — no equivalent in NIST AI RMF, ISO 42001 (certifiable but different), or NYC LL144. Organizations must build separate conformity assessment processes |
| GPAI-specific obligations | Only the EU AI Act has dedicated GPAI/foundation model rules (Chapter V). Other frameworks address general AI system risks without distinguishing model providers from system deployers |
| Extraterritorial enforcement with penalties | The EU AI Act combines extraterritorial scope with binding penalties. NIST AI RMF is voluntary; ISO 42001 is certifiable but not legally binding; NYC LL144 is jurisdiction-limited |
| Fundamental rights impact assessment | Article 27 FRIA is distinct from general risk assessment. ISO 42001 impact assessment (A.6) is closest but does not specifically address fundamental rights |
| Prohibited practices | Only the EU AI Act defines outright bans. Other frameworks use risk-proportionate approaches without absolute prohibitions |
| Supply-chain obligations | The EU AI Act creates cascading obligations from GPAI providers to AI system providers to deployers. Other frameworks focus on single-entity obligations |
