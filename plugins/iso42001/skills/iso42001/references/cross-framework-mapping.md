# Cross-framework mapping — ISO/IEC 42001:2023 to other AI governance frameworks

Map ISO 42001 clauses and Annex A controls to EU AI Act, NIST AI RMF, South Korea AI Act, Brazil AI Act, and NYC Local Law 144.

---

## Clause-level mapping

| ISO 42001 clause | EU AI Act article | NIST AI RMF subcategory | South Korea AI Act | Brazil AI Act | NYC LL144 |
|-----------------|------------------|------------------------|-------------------|---------------|-----------|
| Clause 4.3 — AIMS scope | Art. 6 (risk classification determines scope) | GV-1 (governance scope established) | Scope of high-risk designation | Scope of regulated AI activities | AEDT determination (whether tool is in scope) |
| Clause 5.2 — AI policy | Art. 9 (risk management policy), Art. 26 (deployer obligations) | GV-1 (organisational AI policies), GV-1.1 (legal requirements integrated) | AI ethics principles and guidelines | AI governance principles | No direct equivalent |
| Clause 5.3 — Roles and responsibilities | Art. 16 (provider obligations), Art. 26 (deployer obligations) | GV-2 (roles and responsibilities), GV-2.1 (competence requirements) | Designated responsible officer for AI | Responsible party designation | Employer responsibility for AEDT compliance |
| Clause 6.1.2 — AI risk assessment | Art. 9 (risk management system for high-risk AI) | MAP-1 (context established), MAP-2 (risks and benefits mapped), MEASURE (risk measurement) | AI impact assessment for high-risk systems | Algorithmic impact assessment | No direct equivalent — risk addressed through bias audit only |
| Clause 6.1.2 — AISIA | Art. 27 (fundamental rights impact assessment by deployers) | MAP-2 (AI risks and benefits mapped), MAP-4 (risks prioritised and managed) | Impact assessment on individuals and society | Impact assessment provisions | Disparate impact analysis (limited to employment bias) |
| Clause 6.2 — AI objectives | Art. 9(2)(a) (risk management objectives) | GV-3 (AI objectives aligned to organisational goals) | National AI strategy objectives | AI development objectives | No direct equivalent |
| Clause 7.2 — Competence | Art. 4 (AI literacy obligation) | GV-2.1 (competence and training) | AI literacy and education provisions | AI competence requirements | No direct equivalent |
| Clause 8 — Operation | Art. 8–15 (high-risk operational requirements) | MAP, MEASURE, MANAGE (operational functions) | Operational requirements for high-risk AI | Operational compliance requirements | Bias audit execution (annual) |
| Clause 9 — Performance evaluation | Art. 72 (post-market monitoring) | MEASURE (ongoing measurement), MG-1 (monitoring outcomes) | Monitoring and evaluation provisions | Ongoing monitoring requirements | Annual bias audit constitutes periodic evaluation |
| Clause 10 — Improvement | Art. 72 (corrective actions from monitoring) | MANAGE MG-4 (incident response and learning) | Improvement and remediation requirements | Corrective action provisions | Updated bias audit reflects improvements |

---

## Annex A control mapping

| ISO 42001 control | EU AI Act article | NIST AI RMF subcategory | South Korea AI Act | Brazil AI Act | NYC LL144 |
|------------------|------------------|------------------------|-------------------|---------------|-----------|
| A.2.1 — AI policy | Art. 9 (risk management framework), Art. 26 (deployer policies) | GV-1 (governance policies) | AI ethics charter requirement | AI governance policy requirement | No direct equivalent |
| A.2.2 — AI in organisational policies | Art. 26(5) (workplace AI policies) | GV-1.1 (policy integration) | Integration of AI considerations across policies | Cross-policy AI integration | No direct equivalent |
| A.3.1 — Roles and responsibilities | Art. 16 (provider responsibilities), Art. 26 (deployer responsibilities) | GV-2 (accountability structures) | Designated AI officer requirement | Responsible party requirement | Employer is responsible party |
| A.4.1 — Resource policies | Art. 9(2) (resource allocation for risk management) | GV-3 (resource governance) | Resource allocation for AI governance | Resource requirements | No direct equivalent |
| A.4.2 — Competence and awareness | Art. 4 (AI literacy for all staff) | GV-2.1 (workforce competence) | AI education and training mandate | AI literacy provisions | No direct equivalent |
| A.4.3 — AI procurement | Art. 25 (deployer due diligence for high-risk AI) | GV-6.1 (procurement governance) | Procurement standards for AI | AI procurement provisions | No direct equivalent |
| A.4.4 — Third-party components | Art. 28 (value chain obligations) | GV-6.2 (component risk assessment) | Third-party AI assessment | Component assessment provisions | No direct equivalent |
| A.5.1 — Design specifications | Art. 8 (compliance by design), Art. 11 (technical documentation, Annex IV) | MAP-1 (intended purpose), MAP-5 (documentation) | Design requirements for high-risk AI | Design documentation requirements | No direct equivalent |
| A.5.2 — Design and development | Art. 9 (risk management during development) | MAP-3 (cost-benefit analysis), ME-2 (test and evaluation) | Development standards | Development requirements | No direct equivalent |
| A.5.3 — Data management | Art. 10 (data and data governance requirements) | ME-1.1 (data measurement) | Data management requirements | Data governance provisions | Bias audit data requirements (implicit) |
| A.5.4 — Verification and validation | Art. 9(7) (testing requirements), Art. 15 (accuracy, robustness) | ME-2.1 (test methods), ME-2.2 (ongoing evaluation) | Testing and validation requirements | V&V provisions | Bias audit methodology (statistical testing) |
| A.5.5 — Documentation | Art. 11 (technical documentation per Annex IV) | MAP-5 (system documentation) | Documentation requirements | Documentation obligations | Summary results publication |
| A.5.6 — Deployment | Art. 9 (pre-market risk assessment) | MG-2.1 (deployment decisions) | Deployment approval requirements | Deployment provisions | No direct equivalent |
| A.5.7 — Operation and monitoring | Art. 72 (post-market monitoring system) | ME-2.2 (ongoing monitoring), MG-1 (monitoring results) | Ongoing monitoring requirements | Continuous monitoring provisions | Annual bias audit (periodic monitoring) |
| A.5.8 — Human oversight | Art. 14 (human oversight for high-risk AI) | MG-2.3 (human decision-making), MG-2 (human oversight) | Human oversight and intervention rights | Right to human review | Alternative selection procedure (candidate right) |
| A.6.1 — AISIA process | Art. 27 (FRIA process for deployers) | MAP-2 (risk mapping process), MAP-4 (risk prioritisation) | Impact assessment process | Algorithmic impact assessment process | Disparate impact assessment process |
| A.6.2 — Individual impacts | Art. 27(1)(d) (risks to specific persons) | MAP-2.1 (individual harms identified) | Individual rights impact | Individual impact assessment | Candidate impact (race, sex categories) |
| A.6.3 — Societal concerns | Art. 27(1)(e) (risks to fundamental rights and democracy) | MAP-4.1 (societal implications) | Societal impact assessment | Societal impact provisions | No direct equivalent — limited to employment |
| A.7.1 — Data management policy | Art. 10(1)–(2) (data governance practices) | ME-1.1 (data approaches) | Data management standards | Data governance framework | No direct equivalent |
| A.7.2 — Data acquisition | Art. 10(2)(a)–(d) (training data design) | MAP-2.3 (data requirements) | Data sourcing requirements | Data acquisition provisions | No direct equivalent |
| A.7.3 — Data quality | Art. 10(2)(f)–(g) (bias examination and correction in data) | ME-1.2 (data quality metrics) | Data quality standards | Data quality requirements | Bias audit relies on data quality (implicit) |
| A.7.4 — Data preparation | Art. 10(5) (data preparation safeguards) | MAP-5.1 (data documentation) | Data preparation standards | Data preparation provisions | No direct equivalent |
| A.8.1 — Transparency | Art. 13 (transparency for deployers), Art. 50 (limited-risk transparency) | GV-1.2 (transparency and documentation) | Transparency and right to explanation | Right to information about AI use | Notice requirement — 10 business days before use |
| A.8.2 — Stakeholder communication | Art. 13(3)(b) (instructions for deployers), Art. 86 (right to explanation) | GV-4 (stakeholder engagement) | Stakeholder notification requirements | Stakeholder communication provisions | Public posting of bias audit summary |
| A.8.3 — Incident reporting | Art. 73 (serious incident reporting to authorities) | MG-4 (incident response) | Incident reporting to competent authority | Incident reporting obligations | No incident reporting requirement |
| A.9.1 — Third-party AI policy | Art. 25 (deployer obligations) | GV-6 (third-party governance) | Third-party AI governance | Third-party provisions | No direct equivalent |
| A.9.2 — Supply chain management | Art. 28 (value chain obligations) | GV-6.1 (supply chain risk) | Supply chain requirements | Supply chain governance | No direct equivalent |
| A.9.3 — Data sharing | Art. 10 (data governance), Art. 28 (contractual arrangements) | GV-6.2 (data governance in supply chain) | Data sharing requirements | Data sharing provisions | No direct equivalent |
| A.9.4 — AI interaction disclosure | Art. 50(1) (chatbot disclosure), Art. 50(4) (deepfake disclosure) | GV-1.2 (interaction transparency) | AI interaction disclosure obligation | Right to know about AI interaction | Notice of AEDT use to candidates |
| A.9.5 — External AI use | Art. 4 (AI literacy), Art. 26 (deployer obligations) | GV-1.1 (AI system inventory) | Shadow AI governance | External AI governance | No direct equivalent |
| A.9.6 — Procurement requirements | Art. 25 (deployer due diligence), Art. 28 (contractual arrangements) | GV-6.1 (procurement standards) | AI procurement standards | Procurement provisions | No direct equivalent |
| A.9.7 — Public AI tools | No direct equivalent — general deployer obligations apply | GV-1.1 (AI inventory and governance) | Public AI tool governance | Public AI tool provisions | No direct equivalent |
| A.10.1 — Decommission policy | No direct equivalent | MG-3.1 (retirement planning) | No direct equivalent | No direct equivalent | No direct equivalent |
| A.10.2 — Data retention | Art. 12(3) (log retention for high-risk AI) | MG-3.2 (data disposition) | Data retention requirements | Data retention provisions | Record retention (4 years) |
| A.10.3 — Model deprecation | Art. 28 (provider notification obligations) | MG-3.1 (lifecycle management) | No direct equivalent | No direct equivalent | No direct equivalent |
| A.10.4 — Component reuse | No direct equivalent | MAP-1.1 (context reassessment) | No direct equivalent | No direct equivalent | No direct equivalent |
| A.10.5 — Archiving | Art. 12(3) (record retention), Art. 72 (post-market records) | MG-3.2 (archiving) | Record archiving requirements | Archiving provisions | No direct equivalent |
| A.10.6 — Responsible disposal | No direct equivalent | MG-3.2 (responsible disposal) | No direct equivalent | No direct equivalent | No direct equivalent |

---

## Key integration observations

| Observation | Detail |
|-------------|--------|
| Strongest alignment: EU AI Act | ISO 42001 maps most directly to the EU AI Act. Organisations pursuing 42001 certification will have covered significant ground toward EU AI Act compliance, particularly for high-risk AI requirements (Articles 8–15). The main gap is conformity assessment and CE marking, which are regulatory-specific. |
| Strongest alignment: NIST AI RMF | NIST AI RMF's four functions (Govern, Map, Measure, Manage) align well with ISO 42001's clause structure. GV maps to Clauses 5–6, MAP to Clause 6 and A.6, MEASURE to A.5 and A.7, MANAGE to Clause 8 and A.8–A.10. The key difference is that NIST is voluntary while ISO 42001 is certifiable. |
| Partial alignment: South Korea AI Act | South Korea's framework shares concepts (impact assessment, transparency, human oversight) but implementation specifics differ. ISO 42001 provides the management system structure that the Korean framework does not prescribe. |
| Partial alignment: Brazil AI Act | Brazil's risk-tiered approach aligns conceptually with AISIA impact levels. ISO 42001 certification may support demonstrating compliance with Brazilian requirements once the act is finalised. |
| Limited alignment: NYC LL144 | NYC LL144 is narrowly scoped to automated employment decision tools and bias audits. ISO 42001's broader governance framework far exceeds LL144 requirements, but LL144's specific bias audit methodology and notice requirements are not directly addressed by any ISO 42001 control. |
| Decommission gap | A.10 (AI system decommission) has limited cross-framework equivalents. Most AI regulations focus on deployment and operation, not retirement. This is a differentiator for ISO 42001 — organisations can demonstrate mature lifecycle governance. |
| Data governance depth | A.7 (data for AI systems) provides more structured data governance for AI than most regulatory frameworks, which tend to reference data quality in general terms. Organisations implementing A.7 well will exceed most regulatory data requirements. |
