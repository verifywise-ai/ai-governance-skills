# Cross-framework mapping — NYC Local Law 144 to other frameworks

## Requirement-level mapping

| NYC LL144 requirement | EU AI Act article | ISO 42001 control | NIST AI RMF subcategory | South Korea AI Act | Brazil AI Act |
|-----------------------|-------------------|-------------------|------------------------|-------------------|---------------|
| AEDT determination — whether tool qualifies as automated employment decision tool | Risk classification (Annex III — employment is a high-risk area) | A.6 — AI system impact assessment (AISIA) | MAP-1 (context established), MAP-2 (AI risks and benefits mapped) | High-risk AI classification system with designation criteria for employment AI | High-risk classification for employment AI systems |
| Bias audit — annual independent audit for disparate impact by race/ethnicity and sex | Art. 10 — data governance and bias examination; Art. 10(2)(f) — bias detection and correction | A.5.5 — assessing AI system impacts (verification and validation, bias management) | MEASURE ME-2 (monitoring and tracking), MEASURE ME-3 (fairness and bias evaluation) | AI impact assessment requirement for high-risk systems; non-discrimination obligations | Algorithmic impact assessment; non-discrimination provisions |
| Impact ratios — statistical measurement of selection/scoring disparities across demographic categories | Art. 10(2)(f) — examination of datasets for possible biases and appropriate bias detection measures | A.5.3 — data for AI systems (data management and quality) | MEASURE ME-3 (fairness and bias evaluation metrics) | Non-discrimination obligations; fairness requirements for AI systems | Non-discrimination rights; prohibition of discriminatory outcomes |
| Candidate notice — employers must notify candidates at least 10 business days before AEDT use | Art. 13 (transparency and provision of information to deployers), Art. 50 (transparency for certain AI systems) | A.8.1 — transparency of AI systems | GOVERN GV-1.2 (documentation and communication of AI system information) | Transparency obligations including right to know about AI use in decisions | Right to information about AI system use; right to explanation of AI-assisted decisions |
| Alternative procedure — candidates may request alternative selection process not relying on AEDT | Art. 14 — human oversight measures for high-risk AI systems | A.5.8 — controlling and monitoring AI systems (human oversight) | MANAGE MG-2 (human decision-making retained where appropriate) | Human oversight provisions; right to request human review of AI decisions | Right to human review of AI-assisted decisions |
| Published summary — audit results posted on employer website for at least 6 months | Art. 13 — information to deployers including system capabilities and limitations | A.8.2 — provision of information about AI systems to interested parties | GOVERN GV-1.2 (documentation and communication) | Transparency obligations for AI system operators | Governance and transparency provisions for AI system operators |
| Annual renewal — bias audit must be conducted within one year prior to use and renewed annually | Art. 72 — post-market monitoring system for high-risk AI | A.5.8 — monitoring and review of AI systems over time | MANAGE MG-3 (risk responses including ongoing monitoring) | Periodic assessment requirements for high-risk AI systems | Post-market monitoring provisions for high-risk AI |

## Key differences from other frameworks

| Dimension | NYC LL144 | Other frameworks |
|-----------|-----------|-----------------|
| Scope | Single city, single use case (employment AEDTs) | National or international scope; multiple use cases |
| Specificity | Highly specific — defined statistical methodology, exact notice periods, per-candidate penalties | Generally principles-based with implementation flexibility |
| Enforcement | DCWP enforcement with per-candidate financial penalties ($500–$1,500 per violation) | EU AI Act: up to 35M EUR/7% turnover. NIST: voluntary. ISO: certification-based |
| Technical requirements | Prescriptive — impact ratio calculations, 10 EEOC categories, annual cadence | Generally performance-based without prescribed statistical methods |
| Audit independence | Specific independence requirements for auditor | EU AI Act: notified body for biometric systems. ISO: third-party certification body |
| Transparency | 10 business day notice, website publication, data request rights | Varies from general transparency principles to specific disclosure requirements |

## Compliance gap analysis across frameworks

| Gap area | Detail |
|----------|--------|
| Narrow scope creates false comfort | Organizations compliant with LL144 may assume broader AI hiring compliance, but LL144 only covers AEDTs in NYC. Other frameworks address wider AI risks in employment |
| Statistical methodology not portable | LL144's impact ratio approach is specific to US employment discrimination law (EEOC four-fifths rule). EU AI Act and other frameworks may require different bias measurement approaches |
| No risk management system required | LL144 requires bias audits but not a comprehensive AI risk management system. Organizations need ISO 42001 or NIST AI RMF for systematic risk management |
| No technical documentation requirement | LL144 requires published audit summaries but not the detailed technical documentation required by EU AI Act (Annex IV) or ISO 42001 |
| No incident reporting | LL144 has no incident reporting requirement. Organizations using AEDTs should still establish incident response per EU AI Act Art. 73 or NIST MANAGE MG-4 |
| Per-candidate penalty model unique | LL144's per-use penalty structure is unique among AI frameworks and creates multiplicative risk for high-volume hiring that other frameworks' flat penalties do not |
