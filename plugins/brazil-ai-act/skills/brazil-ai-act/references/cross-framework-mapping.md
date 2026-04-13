# Cross-framework mapping for the Brazil AI Act

## Requirement-level mapping

| Brazil AI Act Requirement | EU AI Act Article | ISO 42001 Control | NIST AI RMF Subcategory | South Korea AI Act | NYC LL144 |
|---------------------------|-------------------|-------------------|------------------------|-------------------|-----------|
| Risk classification (excessive / high / non-high) | Art. 6, Annex III (4-tier risk classification) | A.6 AISIA (AI system impact assessment) | MAP-2 (context and risk identification) | High-risk AI classification system | AEDT determination (is it an automated employment decision tool?) |
| Rights of affected persons (information, explanation, human review, contestation) | Art. 86 (right to explanation); Art. 68 (right to lodge complaint) | A.8 (Information for interested parties; transparency) | GV-1.2 (stakeholder engagement and awareness) | Right to explanation of AI decisions; right to refuse AI-only decisions | Notice to candidates/employees of AEDT use (10 business days prior) |
| Algorithmic impact assessment (pre-deployment, high-risk) | Art. 9 (risk management system); Art. 27 (FRIA for deployers) | Clause 6.1.2 (AI risk assessment); A.6.2 (assessment process) | MAP-4 (risks and benefits mapped for all components) | AI impact assessment for high-impact AI | — (bias audit is closest, but not a full impact assessment) |
| Transparency (disclosure of AI use, system information) | Art. 13 (transparency for deployers); Art. 50 (limited risk disclosure) | A.8.1 (Transparency for AI systems) | GV-1.2 (organizational AI transparency) | Transparency obligations for AI operators | Notice requirements (10 business days before use; alternative selection option) |
| Human oversight (human review, override capability) | Art. 14 (human oversight measures for high-risk) | A.5.8 (Human oversight of AI systems) | MG-2 (mechanisms for human oversight) | Human oversight provisions; right to refuse AI-only decisions | Alternative selection procedure or process (if candidate requests) |
| Non-discrimination (bias prevention, fairness) | Art. 10 (data governance, bias in training data) | A.5.5 (Bias management in AI lifecycle) | ME-3 (mechanisms for bias detection and mitigation) | Non-discrimination provisions for AI systems | Bias audit requirement (annual independent audit of AEDT) |
| Incident reporting (serious incidents to ANPD) | Art. 62 (reporting of serious incidents) | A.8.3 (Reporting of AI system incidents) | MG-4 (incident tracking and response) | Incident reporting obligations for high-impact AI | — (no incident reporting requirement) |
| Governance system (structure, policies, risk management) | Art. 9 (risk management system); Arts. 8-15 (high-risk requirements) | Clauses 4-10 (full AIMS — AI Management System) | GOVERN (organizational AI governance function) | Obligations by actor (developer, service provider, user) | — (no governance system requirement) |
| Data governance (training data quality, bias in data) | Art. 10 (data and data governance for high-risk) | A.7 (Data for AI systems — quality, provenance) | ME-1 (measurement of AI system performance and data) | Data quality and management requirements | — (data quality implied but not explicitly required) |

## Structural comparison

| Dimension | Brazil AI Act | EU AI Act | ISO 42001 | NIST AI RMF | South Korea AI Act | NYC LL144 |
|-----------|---------------|-----------|-----------|-------------|-------------------|-----------|
| Legal nature | National law (pending signature) | Binding EU regulation | Voluntary certifiable standard | Voluntary framework | National law | City ordinance |
| Scope | All AI systems affecting persons in Brazil | All AI systems in EU market | Any organization choosing to implement | Any organization choosing to apply | All AI systems in South Korea | Automated employment decision tools in NYC |
| Risk approach | 3-tier (excessive/high/non-high) | 4-tier (prohibited/high/limited/minimal) | Organization-defined risk assessment | Contextual risk throughout lifecycle | Risk-based classification | Binary (AEDT or not) |
| Regulator | ANPD | National authorities + EU AI Office | Certification bodies | None (voluntary) | Ministry of Science and ICT | NYC DCWP |
| Penalties | ANPD-enforced (details pending) | Up to 35M EUR or 7% global turnover | Loss of certification | None | Penalties defined in law | Up to $1,500 per violation per day |
| Rights focus | Strong (8 specific rights) | Moderate (FRIA, explanation) | Indirect (interested parties) | Indirect (stakeholders) | Moderate (explanation, refusal) | Limited (notice, alternative) |
| Data protection alignment | LGPD (same regulator) | GDPR (separate regulators) | References data management | References data governance | PIPA alignment | NYC data protection laws |

## Mapping by compliance activity

### If you are already compliant with the EU AI Act

| Brazil AI Act Requirement | EU AI Act Equivalent | Gap to Address |
|---------------------------|---------------------|----------------|
| Risk classification | Art. 6 risk classification | Brazil uses 3 tiers (no limited risk category); review Brazil-specific prohibited list |
| Algorithmic impact assessment | Art. 9 risk management + Art. 27 FRIA | Brazil requires publication of summary; verify FRIA content meets Brazil requirements |
| Rights of affected persons | Art. 86 + national rights | Brazil has 8 specific rights (more detailed than EU); implement right to prior notice (not in EU Act) |
| Human oversight | Art. 14 human oversight | Substantially aligned; verify human review process meets Brazil standards |
| Transparency | Art. 13 + Art. 50 | Substantially aligned; ensure Portuguese language disclosures |
| Incident reporting | Art. 62 serious incidents | Report to ANPD (not EU authorities); align with LGPD 72-hour timeline |
| Governance | Arts. 8-15 requirements | Substantially aligned; ensure ANPD-specific requirements are met |

### If you are already compliant with ISO 42001

| Brazil AI Act Requirement | ISO 42001 Equivalent | Gap to Address |
|---------------------------|---------------------|----------------|
| Risk classification | A.6 AISIA | ISO uses org-defined risk; Brazil mandates 3-tier classification — map ISO assessment to Brazil tiers |
| Algorithmic impact assessment | Clause 6.1.2 + A.6.2 | ISO assessment may not cover all Brazil-required content; supplement with Brazil-specific elements |
| Rights of affected persons | A.8 Transparency | ISO addresses interested parties generally; Brazil requires 8 specific enforceable rights — implement each |
| Incident reporting | A.8.3 Reporting | ISO reporting is org-defined; Brazil requires ANPD reporting within expected 72 hours |
| Governance | Clauses 4-10 AIMS | Strong foundation; ensure ANPD-specific requirements and Brazil-specific policies are included |

### If you are already compliant with NIST AI RMF

| Brazil AI Act Requirement | NIST AI RMF Equivalent | Gap to Address |
|---------------------------|----------------------|----------------|
| Risk classification | MAP-2 context/risk | NIST uses contextual risk (no tiers); must map to Brazil's mandatory 3-tier system |
| Algorithmic impact assessment | MAP-4 risk/benefit mapping | NIST mapping is broader; must create Brazil-specific impact assessment document |
| Rights of affected persons | GV-1.2 stakeholder engagement | NIST is voluntary/advisory; Brazil requires legally enforceable rights — implement formal processes |
| Incident reporting | MG-4 incident response | NIST is voluntary; Brazil requires mandatory ANPD reporting — establish formal reporting channel |
| Governance | GOVERN function | Good foundation; must formalize into Brazil-compliant governance system with ANPD alignment |

## Key differences to watch

1. **Brazil's rights emphasis is stronger than most frameworks** — Eight specific enforceable rights for affected persons, influenced by LGPD tradition. Organizations compliant with other frameworks likely need to implement additional rights mechanisms.

2. **ANPD as sole regulator for both data protection and AI** — Unique regulatory structure means AI compliance and LGPD compliance will be assessed together. Integrate governance rather than maintaining separate streams.

3. **No limited risk category** — Unlike the EU AI Act, Brazil does not have a separate limited risk tier. Systems that would be limited risk under the EU Act fall into non-high risk in Brazil, but transparency obligations from the rights framework still apply.

4. **Extraterritorial scope applies broadly** — Any AI system affecting persons in Brazil is in scope, regardless of where the developer, deployer, or operator is located. Foreign organizations must assess their exposure.

5. **Pending final promulgation** — As of early 2025, the Act awaits presidential signature. Specific articles and numbering may change. Monitor ANPD publications for final text and implementing regulations.
