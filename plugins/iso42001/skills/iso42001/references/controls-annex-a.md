# Annex A controls — ISO/IEC 42001:2023

All 38 controls across 9 domains. Use this reference to assess applicability, identify gaps, and generate the Statement of Applicability (SoA).

---

## A.2 — Policies related to AI (2 controls)

| Control ID | Control Name | Applies to | Description | Common gaps | EU AI Act cross-ref | NIST AI RMF cross-ref |
|-----------|-------------|-----------|-------------|------------|--------------------|-----------------------|
| A.2.1 | AI policy | Both | Establish and maintain an AI policy approved by top management that sets out the organisation's commitment to responsible AI, defines the scope of AI activities, and provides a framework for setting AI objectives | Policy exists but is generic — lacks AI-specific commitments, measurable objectives, or explicit responsible AI principles | Art. 9 (risk management policy as part of high-risk compliance) | GV-1 (governance policies established) |
| A.2.2 | AI in organisational policies | Both | Review existing organisational policies (HR, procurement, security, privacy, ethics) and update them to address AI-specific considerations where AI systems affect those policy domains | Existing policies not updated to address AI — e.g., procurement policy lacks AI due diligence criteria, HR policy silent on AI-assisted decisions | Art. 26 (deployer obligations across policies) | GV-1.1 (legal and regulatory requirements integrated) |

---

## A.3 — Internal organisation (1 control)

| Control ID | Control Name | Applies to | Description | Common gaps | EU AI Act cross-ref | NIST AI RMF cross-ref |
|-----------|-------------|-----------|-------------|------------|--------------------|-----------------------|
| A.3.1 | Roles and responsibilities for AI | Both | Define, document, and communicate roles and responsibilities for AI governance, development, deployment, monitoring, and incident response. Assign accountability for AIMS at the management level | Roles assigned informally — no documented RACI matrix; AI governance responsibility not assigned to a named individual; data scientists lack defined accountability for model outcomes | Art. 16 (provider obligations), Art. 26 (deployer obligations) | GV-2 (roles and responsibilities established) |

---

## A.4 — Resources for AI systems (4 controls)

| Control ID | Control Name | Applies to | Description | Common gaps | EU AI Act cross-ref | NIST AI RMF cross-ref |
|-----------|-------------|-----------|-------------|------------|--------------------|-----------------------|
| A.4.1 | Resource policies for AI | Both | Establish policies governing the allocation and management of resources (computational, data, human, financial) required for AI systems throughout their lifecycle | No formal resource allocation — AI initiatives compete for ad hoc resources without policy-driven prioritisation | Art. 9(2) (resources for risk management) | GV-3 (resources allocated) |
| A.4.2 | Competence and awareness for AI | Both | Ensure personnel involved in AI activities have the necessary competence through education, training, or experience. Maintain competence records and deliver ongoing AI awareness programmes | Training is informal — no competence matrix, no evidence of AI-specific training, no assessment of training effectiveness | Art. 4 (AI literacy requirement) | GV-2.1 (competence requirements defined) |
| A.4.3 | AI system procurement | User | Establish criteria and processes for evaluating, selecting, and procuring AI systems or AI services from third parties. Include AI-specific requirements in procurement specifications | Procurement follows standard IT procurement — no AI-specific evaluation criteria, no assessment of provider's AI governance maturity, no bias or fairness requirements in RFPs | Art. 25 (deployer obligations for high-risk AI from providers) | GV-6.1 (third-party AI procurement policies) |
| A.4.4 | Third-party AI components | Provider | Evaluate and manage risks associated with third-party components (pre-trained models, datasets, libraries, APIs) incorporated into AI systems the organisation develops | Third-party model cards not reviewed; no assessment of training data provenance for incorporated models; dependency risks not tracked | Art. 28 (obligations along the AI value chain) | GV-6.2 (third-party risk assessment) |

---

## A.5 — AI system lifecycle (8 controls)

| Control ID | Control Name | Applies to | Description | Common gaps | EU AI Act cross-ref | NIST AI RMF cross-ref |
|-----------|-------------|-----------|-------------|------------|--------------------|-----------------------|
| A.5.1 | AI system design specifications | Provider | Document design specifications for each AI system including intended purpose, functional requirements, performance requirements, fairness criteria, and constraints | Specifications exist for functionality but omit fairness criteria, explainability requirements, or human oversight specifications | Art. 8 (high-risk system requirements), Art. 11 (technical documentation) | MAP-1 (intended purpose documented) |
| A.5.2 | AI system design and development | Provider | Implement development practices that address AI-specific concerns including algorithm selection rationale, training methodology, hyperparameter selection, and bias mitigation measures during development | Development focuses on performance metrics — fairness and bias considerations addressed reactively, not by design | Art. 9 (risk management during development) | MAP-3 (benefits and costs mapped) |
| A.5.3 | Data management for AI | Provider | Establish processes for managing data used in AI systems including data collection, labelling, storage, quality assessment, and lifecycle management specific to AI training, validation, and test datasets | Data management follows general IT practices — no AI-specific quality criteria, no bias assessment of training data, no documentation of labelling methodology | Art. 10 (data and data governance) | ME-1.1 (measurement approaches for AI) |
| A.5.4 | AI system verification and validation | Provider | Define and execute verification and validation processes for AI systems including functional testing, performance testing, bias testing, robustness testing, and testing against intended purpose | Testing limited to functional accuracy — no bias testing, no adversarial robustness testing, no testing against edge cases or underrepresented populations | Art. 9(7) (testing for high-risk AI), Art. 15 (accuracy and robustness) | ME-2.1 (test and evaluation methods) |
| A.5.5 | AI system documentation | Provider | Maintain comprehensive documentation of AI system characteristics including architecture, training process, performance metrics, known limitations, and deployment requirements | Documentation exists for deployment but lacks training process details, limitation disclosures, or performance metric breakdowns by demographic group | Art. 11 (technical documentation per Annex IV) | MAP-5 (system characteristics documented) |
| A.5.6 | AI system deployment | Both | Establish controlled deployment processes including deployment approval gates, rollback procedures, monitoring setup, and stakeholder notification prior to operational deployment | Deployment follows standard CI/CD — no AI-specific approval gates, no pre-deployment bias check, no stakeholder notification process | Art. 9 (pre-market risk management) | MG-2.1 (deployment decisions) |
| A.5.7 | AI system operation and monitoring | Both | Implement ongoing monitoring of AI systems in production including performance monitoring, drift detection, bias monitoring, incident detection, and feedback collection mechanisms | Monitoring limited to uptime and response time — no model drift detection, no ongoing bias monitoring, no feedback loop from affected individuals | Art. 72 (post-market monitoring) | ME-2.2 (ongoing measurement and monitoring) |
| A.5.8 | Human oversight of AI systems | Both | Define and implement human oversight mechanisms appropriate to the AI system's impact level including intervention capabilities, override procedures, and escalation paths | Human oversight is informal — no documented escalation paths, no defined thresholds for human intervention, no evidence of override capability testing | Art. 14 (human oversight for high-risk AI) | MG-2.3 (human oversight mechanisms) |

---

## A.6 — AI system impact assessment (3 controls)

| Control ID | Control Name | Applies to | Description | Common gaps | EU AI Act cross-ref | NIST AI RMF cross-ref |
|-----------|-------------|-----------|-------------|------------|--------------------|-----------------------|
| A.6.1 | AISIA process | Both | Establish and maintain a documented process for conducting AI system impact assessments that evaluates potential impacts on individuals, groups, and society across defined dimensions | Process exists on paper but not executed consistently — no defined trigger criteria for when AISIA must be conducted, no review cycle established | Art. 27 (fundamental rights impact assessment) | MAP-2 (risks and benefits mapped), MAP-4 (risks prioritised) |
| A.6.2 | Assessment of impacts on individuals | Both | Assess impacts of AI systems on individuals including impacts on autonomy, dignity, privacy, safety, access to services, and decision-making rights. Consider both intended and unintended effects | Individual impact assessment limited to privacy — does not address autonomy, dignity, or access to services; unintended effects not systematically considered | Art. 27(1)(d) (specific risks to affected persons) | MAP-2.1 (potential harms identified) |
| A.6.3 | Assessment of societal concerns | Both | Assess broader societal impacts of AI systems including effects on communities, democratic processes, social equity, environmental sustainability, and public trust in AI | Societal impact not assessed — focus remains on direct business impact; no consideration of community-level effects, environmental cost of AI compute, or effects on public trust | Art. 27(1)(e) (risks to fundamental rights and democracy) | MAP-4.1 (societal implications mapped) |

---

## A.7 — Data for AI systems (4 controls)

| Control ID | Control Name | Applies to | Description | Common gaps | EU AI Act cross-ref | NIST AI RMF cross-ref |
|-----------|-------------|-----------|-------------|------------|--------------------|-----------------------|
| A.7.1 | Data management policy for AI | Both | Establish a data management policy that addresses AI-specific requirements including data sourcing ethics, consent for AI training use, data quality standards, bias assessment criteria, and data lifecycle management | General data policy exists but does not address AI-specific concerns — no consent framework for AI training use, no bias assessment criteria for datasets | Art. 10(1)–(2) (data governance practices) | ME-1.1 (data measurement approaches) |
| A.7.2 | Data acquisition and collection for AI | Provider | Define criteria and processes for acquiring and collecting data used in AI systems including provenance tracking, representativeness assessment, legal basis for collection, and documentation of collection methodology | Data collected opportunistically — no provenance tracking, no representativeness assessment, no documentation of collection methodology or legal basis | Art. 10(2)(a)–(d) (training data design choices) | MAP-2.3 (data requirements mapped) |
| A.7.3 | Data quality for AI | Both | Establish data quality criteria specific to AI use cases including accuracy, completeness, timeliness, consistency, and absence of prohibited bias. Implement quality assessment and remediation processes | Data quality addressed informally — no defined quality criteria for AI use cases, no systematic quality assessment, no remediation process when quality thresholds are not met | Art. 10(2)(f)–(g) (bias examination and correction) | ME-1.2 (data quality metrics) |
| A.7.4 | Data preparation for AI | Provider | Document and control data preparation processes including feature engineering, data transformation, augmentation, splitting, and annotation to ensure reproducibility and quality preservation | Data preparation ad hoc — no documented pipelines, no version control for datasets, no reproducibility of preparation steps, annotation guidelines informal | Art. 10(5) (data preparation safeguards) | MAP-5.1 (data characteristics documented) |

---

## A.8 — Information for interested parties (3 controls)

| Control ID | Control Name | Applies to | Description | Common gaps | EU AI Act cross-ref | NIST AI RMF cross-ref |
|-----------|-------------|-----------|-------------|------------|--------------------|-----------------------|
| A.8.1 | Transparency of AI systems | Both | Provide clear, accessible information about AI system capabilities, limitations, and decision-making processes appropriate to the impact level and audience (technical users, affected individuals, regulators) | Transparency limited to technical documentation — no accessible information for affected individuals, no clear disclosure of AI use in customer-facing processes | Art. 13 (transparency for deployers), Art. 50 (transparency for limited risk) | GV-1.2 (transparency and documentation) |
| A.8.2 | Communication with stakeholders | Both | Establish communication channels and processes for engaging with stakeholders (regulators, affected individuals, civil society, customers) regarding AI system governance, impacts, and changes | No formal stakeholder communication — regulators contacted only reactively, no proactive engagement with affected communities, no feedback mechanisms for individuals subject to AI decisions | Art. 13(3)(b) (instructions for deployers), Art. 86 (right to explanation) | GV-4 (stakeholder engagement) |
| A.8.3 | AI incident and disruption reporting | Both | Define and implement processes for reporting AI-specific incidents (bias detection, unexpected outputs, safety events, model failures) to relevant internal and external parties within defined timeframes | Incident reporting uses general IT processes — no AI-specific incident classification, no defined reporting thresholds for bias incidents or model failures, no external reporting procedure | Art. 73 (serious incident reporting) | MG-4 (incident response and recovery) |

---

## A.9 — Use of AI by third parties (7 controls)

| Control ID | Control Name | Applies to | Description | Common gaps | EU AI Act cross-ref | NIST AI RMF cross-ref |
|-----------|-------------|-----------|-------------|------------|--------------------|-----------------------|
| A.9.1 | Third-party AI use policy | User | Establish a policy governing the organisation's use of AI systems provided by third parties including evaluation criteria, risk acceptance thresholds, and ongoing monitoring requirements | No specific third-party AI policy — AI tools adopted without formal evaluation, risk assessment, or governance oversight | Art. 25 (deployer due diligence) | GV-6 (third-party AI governance) |
| A.9.2 | AI supply chain management | Both | Assess and manage risks throughout the AI supply chain including upstream data providers, model providers, cloud infrastructure, and downstream integrators | Supply chain visibility limited — no mapping of AI supply chain dependencies, no assessment of upstream provider practices, no contingency for provider disruption | Art. 28 (value chain obligations) | GV-6.1 (supply chain risk management) |
| A.9.3 | Data sharing with AI providers | Both | Establish controls for sharing organisational data with AI providers including purpose limitation, data minimisation, security requirements, and contractual protections | Data shared with AI providers without formal data sharing agreements — no purpose limitation, no contractual restrictions on provider's use of shared data for model training | Art. 10 (data governance), Art. 28 (contractual arrangements) | GV-6.2 (data sharing governance) |
| A.9.4 | Disclosure of AI interactions | Both | Ensure individuals interacting with AI systems are informed that they are interacting with AI, understand the nature of the interaction, and know how to access human alternatives where appropriate | No disclosure that customers or employees are interacting with AI systems — chatbots and automated decision tools not identified as AI | Art. 50 (transparency obligations for certain AI systems) | GV-1.2 (transparency obligations) |
| A.9.5 | External AI system use | User | Monitor and control the use of external AI systems by the organisation's personnel including shadow AI governance, approved AI tool registers, and acceptable use guidelines | Shadow AI uncontrolled — employees using unapproved AI tools (ChatGPT, Copilot, image generators) without oversight, no approved tool register, no acceptable use guidance | Art. 4 (AI literacy), Art. 26 (deployer obligations) | GV-1.1 (AI system inventory) |
| A.9.6 | AI procurement requirements | User | Include AI-specific requirements in procurement contracts including performance guarantees, bias audit rights, data handling restrictions, incident notification obligations, and exit provisions | Standard IT procurement contracts used — no AI-specific contractual clauses, no bias audit rights, no incident notification requirements, no model change notification | Art. 25 (deployer obligations), Art. 28 (contractual arrangements) | GV-6.1 (procurement governance) |
| A.9.7 | Public AI tool governance | Both | Establish governance for the organisation's use of publicly available AI tools and services including risk assessment, data loss prevention, and acceptable use restrictions | No governance of public AI tool use — sensitive data entered into public AI services, no risk assessment of public AI tools, no data loss prevention controls | No direct equivalent — falls under general deployer obligations | GV-1.1 (AI system governance) |

---

## A.10 — AI system decommission (6 controls)

| Control ID | Control Name | Applies to | Description | Common gaps | EU AI Act cross-ref | NIST AI RMF cross-ref |
|-----------|-------------|-----------|-------------|------------|--------------------|-----------------------|
| A.10.1 | AI decommission policy | Both | Establish a policy and process for decommissioning AI systems including trigger criteria, transition planning, stakeholder notification, and timeline requirements | No decommission policy — AI systems retired ad hoc without formal process, stakeholders not notified, no transition planning | No direct equivalent | MG-3.1 (system retirement planning) |
| A.10.2 | Data retention after AI decommission | Both | Define data retention and disposal requirements for data associated with decommissioned AI systems including training data, operational data, model artefacts, and decision logs | Data retained indefinitely or deleted without assessment — no retention schedule for AI-specific data, no consideration of regulatory retention requirements for AI decision records | Art. 12(3) (logging retention for high-risk AI) | MG-3.2 (data disposition) |
| A.10.3 | Model deprecation | Provider | Establish a controlled process for deprecating AI models including version control, downstream notification, migration support, and sunset timelines | Models deprecated without downstream notification — users discover model changes through failures, no migration path provided, no sunset timeline communicated | Art. 28 (provider obligations to downstream parties) | MG-3.1 (model lifecycle management) |
| A.10.4 | AI system component reuse | Provider | Assess risks of reusing AI system components (models, datasets, features) in new contexts including fitness-for-purpose evaluation, bias reassessment, and documentation updates | Components reused without reassessment — model trained for one context deployed in another without evaluating fitness, bias profile, or performance in the new context | No direct equivalent | MAP-1.1 (context reassessment) |
| A.10.5 | AI system archiving | Both | Maintain archives of decommissioned AI systems sufficient to support audit, investigation, and dispute resolution including model versions, configuration, training data references, and decision records | No AI-specific archiving — systems deleted entirely upon decommission, no ability to reconstruct decisions or reproduce outputs for audit or dispute resolution | Art. 12(3) (record retention for high-risk AI) | MG-3.2 (archiving for accountability) |
| A.10.6 | Responsible AI disposal | Both | Ensure AI system disposal addresses potential harms including preventing unauthorised model use, securing proprietary data, and managing environmental impact of compute resources | Disposal limited to infrastructure decommission — no consideration of model leakage risk, no secure deletion of proprietary training data, no environmental impact assessment | No direct equivalent | MG-3.2 (responsible disposal) |

---

## Provider vs user applicability summary

| Domain | Total controls | Provider only | User only | Both |
|--------|---------------|--------------|----------|------|
| A.2 — Policies | 2 | 0 | 0 | 2 |
| A.3 — Internal organisation | 1 | 0 | 0 | 1 |
| A.4 — Resources | 4 | 1 | 1 | 2 |
| A.5 — Lifecycle | 8 | 5 | 0 | 3 |
| A.6 — Impact assessment | 3 | 0 | 0 | 3 |
| A.7 — Data | 4 | 2 | 0 | 2 |
| A.8 — Transparency | 3 | 0 | 0 | 3 |
| A.9 — Third parties | 7 | 0 | 3 | 4 |
| A.10 — Decommission | 6 | 2 | 0 | 4 |
| **Total** | **38** | **10** | **4** | **24** |
