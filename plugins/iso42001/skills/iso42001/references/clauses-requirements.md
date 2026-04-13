# Mandatory clauses 4–10 — ISO/IEC 42001:2023

Detailed requirements for each mandatory clause. Use for gap assessment, audit preparation, and implementation guidance.

---

## Clause 4 — Context of the organisation

### 4.1 Understanding the organisation and its context

| Aspect | Detail |
|--------|--------|
| Requirement | Determine external and internal issues relevant to the organisation's purpose that affect its ability to achieve the intended outcomes of the AIMS |
| AI-specific considerations | Identify the AI landscape the organisation operates in — regulatory requirements (EU AI Act, national AI laws), industry-specific AI expectations, competitive AI adoption, stakeholder AI concerns, technological maturity of AI capabilities |
| Required outputs | Documented context analysis covering: external factors (regulatory, market, technology, societal attitudes to AI), internal factors (AI maturity, competence, culture, infrastructure, existing AI systems) |
| Audit evidence | Context analysis document, evidence of periodic review (at least annual), management discussion records |
| Common nonconformities | Context analysis is generic — does not specifically address AI-related external or internal issues; not updated when AI regulatory landscape changes; no consideration of societal attitudes toward AI |

### 4.2 Understanding the needs and expectations of interested parties

| Aspect | Detail |
|--------|--------|
| Requirement | Identify interested parties relevant to the AIMS and their requirements including regulatory, contractual, and ethical expectations |
| AI-specific considerations | AI-specific stakeholders include: regulators with AI oversight, individuals subject to AI decisions, data subjects whose data trains AI, AI supply chain partners, civil society groups, employees affected by AI automation, customers relying on AI outputs |
| Required outputs | Stakeholder register with: party name, requirements, relevance to AIMS, how requirements are monitored and addressed |
| Audit evidence | Stakeholder register, evidence of stakeholder requirements captured and tracked, evidence of periodic review |
| Common nonconformities | Stakeholder register omits individuals affected by AI decisions; regulatory requirements not mapped to specific clauses/controls; stakeholder requirements not reviewed when new AI systems are deployed |

### 4.3 Determining the scope of the AIMS

| Aspect | Detail |
|--------|--------|
| Requirement | Define the scope of the AIMS including boundaries, applicability of requirements, and AI systems covered |
| AI-specific considerations | The scope must identify: which AI systems are included (by name, type, purpose), organisational boundaries (departments, locations, legal entities), interfaces with external parties (providers, users, data subjects), and any exclusions with justification |
| Required outputs | AIMS scope document, AI system register (listing all in-scope AI systems with intended purpose, deployment status, and responsible owner) |
| Audit evidence | Scope document approved by management, AI system register maintained and current, evidence that scope was reviewed when new AI systems were introduced |
| Common nonconformities | Scope too narrow — excludes embedded AI in SaaS platforms, pilot projects, or internal automation tools; AI system register incomplete; scope not reviewed when new AI systems are deployed |

### 4.4 AI management system

| Aspect | Detail |
|--------|--------|
| Requirement | Establish, implement, maintain, and continually improve the AIMS in accordance with the standard's requirements |
| AI-specific considerations | The AIMS must address the full lifecycle of AI systems from planning through decommission, integrate with existing management systems (ISO 27001, ISO 9001), and maintain documented processes for all required activities |
| Required outputs | AIMS manual or process documentation, process interaction map, integration points with other management systems |
| Audit evidence | Documented AIMS processes, evidence of implementation, evidence of continual improvement activities |
| Common nonconformities | AIMS exists as documentation only — processes not implemented in practice; no integration with existing management systems; AIMS processes not communicated to relevant personnel |

---

## Clause 5 — Leadership

### 5.1 Leadership and commitment

| Aspect | Detail |
|--------|--------|
| Requirement | Top management must demonstrate leadership and commitment to the AIMS by ensuring AI policy is established, objectives are set, resources are available, and the importance of AI governance is communicated |
| AI-specific considerations | Top management must understand AI-specific risks and opportunities, actively participate in AI governance decisions (not delegate entirely), and ensure AI governance is integrated into business strategy |
| Required outputs | Evidence of management engagement — meeting minutes, resource allocation decisions, AI governance agenda items in management meetings |
| Audit evidence | Management review minutes showing AI governance as a standing agenda item, resource allocation records, communication records demonstrating management's AI governance messaging |
| Common nonconformities | Management commitment is nominal — AI governance delegated entirely without oversight; no evidence of management engagement in AI risk decisions; AI not on management meeting agendas |

### 5.2 AI policy

| Aspect | Detail |
|--------|--------|
| Requirement | Establish an AI policy that is appropriate to the organisation's purpose, provides a framework for setting AI objectives, includes commitment to responsible AI and continual improvement, and is communicated to all relevant parties |
| AI-specific considerations | The policy must address: responsible AI principles (fairness, transparency, accountability, safety), the organisation's AI risk appetite, commitment to human oversight, data ethics, and alignment with applicable regulations |
| Required outputs | AI policy document, signed by top management, communicated to all personnel and relevant external parties |
| Audit evidence | Signed AI policy, evidence of communication (intranet posting, email distribution, training records), evidence of periodic review (at least annual) |
| Common nonconformities | Policy is generic CSR statement — lacks AI-specific commitments; not signed by top management; not communicated to all relevant personnel; no review schedule established |

### 5.3 Organisational roles, responsibilities, and authorities

| Aspect | Detail |
|--------|--------|
| Requirement | Assign and communicate roles, responsibilities, and authorities relevant to the AIMS |
| AI-specific considerations | AI governance requires specific roles beyond traditional IT or risk management |
| Required outputs | RACI matrix or role description documents for all AIMS-relevant roles |
| Audit evidence | Role descriptions, organisational charts showing AI governance structure, appointment letters or records, evidence roles are communicated |
| Common nonconformities | Roles assigned informally — no documented RACI; AI governance responsibility fragmented across departments with no single point of accountability; AI-specific roles not defined |

**Minimum roles for AIMS:**

| Role | Responsibility | Clause reference |
|------|---------------|-----------------|
| AIMS owner / AI governance lead | Overall accountability for the AIMS | 5.3 |
| AI risk manager | Ownership of AI risk assessment and AISIA processes | 6.1.2 |
| AI system owner (per system) | Accountable for each AI system's lifecycle and compliance | 8.1 |
| Data governance lead for AI | Ownership of data quality, provenance, and bias management | A.7 |
| AI ethics / responsible AI lead | Advisory role on fairness, transparency, and societal impact | A.6, A.8 |
| Internal auditor (AI competent) | Conducts AIMS internal audits with AI domain knowledge | 9.2 |
| AI incident manager | Leads AI-specific incident response and reporting | A.8.3 |

---

## Clause 6 — Planning

### 6.1 Actions to address risks and opportunities

| Aspect | Detail |
|--------|--------|
| Requirement | Plan actions to address risks and opportunities identified through context analysis and stakeholder requirements |
| AI-specific considerations | Planning must address both organisational risks to the AIMS and AI system-specific risks. Two mandatory processes: AI risk assessment and AISIA |

#### 6.1.2 AI risk assessment and AISIA

| Aspect | Detail |
|--------|--------|
| Requirement | Establish and execute an AI risk assessment process that evaluates risks specific to AI systems, and an AI system impact assessment (AISIA) that evaluates impacts on individuals and society |
| AI-specific considerations | AI risk assessment uses likelihood x severity for AI-specific risks (model, data, operational, supply chain, regulatory). AISIA uses impact dimensions (nature, severity, breadth, reversibility, consent, oversight, recourse). These are separate but complementary processes |
| Required outputs | AI risk assessment methodology document, risk register for each in-scope AI system, AISIA methodology document, AISIA record for each in-scope AI system |
| Audit evidence | Completed risk registers with treatment decisions, completed AISIA records with impact classifications, evidence of periodic reassessment, evidence that results informed control selection |
| Common nonconformities | Risk assessment and AISIA conflated into a single process; not performed for all in-scope AI systems; results not linked to control selection in SoA; no defined reassessment triggers or frequency |

#### 6.1.3 AI risk treatment and Statement of Applicability

| Aspect | Detail |
|--------|--------|
| Requirement | Select risk treatment options and determine which Annex A controls are applicable. Document the Statement of Applicability (SoA) with justification for inclusion or exclusion of each control |
| AI-specific considerations | All 38 Annex A controls must be considered. Applicability depends on role (provider/user/both), AI system characteristics, impact level from AISIA, and risk level from risk assessment |
| Required outputs | Risk treatment plan, Statement of Applicability (SoA) covering all 38 controls with applicability determination and justification |
| Audit evidence | SoA document with justification for each control, risk treatment plan linked to risk register, evidence that SoA is reviewed when scope or risk profile changes |
| Common nonconformities | SoA exclusions not justified — controls marked "not applicable" without rationale; SoA not updated when new AI systems are added to scope; treatment plan not linked to specific risks |

### 6.2 AI objectives and planning to achieve them

| Aspect | Detail |
|--------|--------|
| Requirement | Establish measurable AI objectives consistent with the AI policy. Plan actions to achieve them including what will be done, resources required, responsible parties, timelines, and evaluation methods |
| AI-specific considerations | AI objectives must go beyond general management objectives — include specific targets for fairness, transparency, accountability, safety, and human oversight. Objectives should be measurable with defined metrics and baselines |
| Required outputs | AI objectives register with: objective, metric, baseline, target, responsible party, timeline, evaluation method |
| Audit evidence | Objectives register, evidence of progress tracking, evidence of periodic review, evidence that objectives are communicated to relevant personnel |
| Common nonconformities | Objectives are aspirational statements — not measurable, no metrics defined, no baselines established; objectives not linked to AI policy commitments; no progress tracking mechanism |

---

## Clause 7 — Support

### 7.1 Resources

| Aspect | Detail |
|--------|--------|
| Requirement | Determine and provide the resources needed for the establishment, implementation, maintenance, and continual improvement of the AIMS |
| AI-specific considerations | AI governance requires specialised resources including: AI technical expertise, computational infrastructure, data management tools, AI monitoring platforms, external expertise (legal, ethical, domain), and training budgets for AI competence development |
| Required outputs | Resource allocation records, budget documentation for AIMS activities |
| Audit evidence | Budget records, procurement records, resource allocation decisions documented in management reviews |
| Common nonconformities | Resources allocated for initial implementation but not for ongoing operation; no budget for external expertise; computational resources for AI monitoring not provisioned |

### 7.2 Competence

| Aspect | Detail |
|--------|--------|
| Requirement | Determine necessary competence for persons doing work that affects AI governance performance, ensure they are competent on the basis of education, training, or experience, and take actions to acquire necessary competence |
| AI-specific considerations | Competence requirements must be role-specific and address both technical AI skills and governance understanding |
| Required outputs | Competence matrix by role, training records, competence assessment records |
| Audit evidence | Competence matrix, training attendance records, competence assessments (tests, certifications, reviews), gap analysis and development plans |
| Common nonconformities | Competence matrix does not cover all AIMS roles; training is one-off rather than ongoing; no assessment of training effectiveness; competence gaps not tracked or addressed |

**Role-based competence matrix:**

| Role | Technical AI competence | AI governance competence | Domain competence |
|------|------------------------|-------------------------|-------------------|
| AIMS owner | Awareness | Expert | Expert |
| AI system developer | Expert | Working knowledge | Working knowledge |
| AI system owner | Working knowledge | Expert | Expert |
| Data engineer / scientist | Expert | Working knowledge | Working knowledge |
| AI risk manager | Working knowledge | Expert | Working knowledge |
| Internal auditor | Working knowledge | Expert | Working knowledge |
| End users of AI systems | Awareness | Awareness | Expert |
| Top management | Awareness | Awareness | Expert |

### 7.3 Awareness

| Aspect | Detail |
|--------|--------|
| Requirement | Ensure persons doing work under the organisation's control are aware of the AI policy, their contribution to AIMS effectiveness, and the implications of not conforming to AIMS requirements |
| AI-specific considerations | Awareness must cover: what AI systems the organisation uses and develops, responsible AI principles, how to report AI incidents, acceptable use of AI tools, and implications of misuse |
| Required outputs | Awareness programme documentation, awareness delivery records |
| Audit evidence | Awareness programme content, delivery records (attendance, completion), evidence of awareness testing, evidence of periodic refresh |
| Common nonconformities | Awareness programme limited to initial onboarding — no periodic refresh; content does not cover AI-specific topics; no evidence that awareness was effective (no testing or feedback) |

### 7.4 Communication

| Aspect | Detail |
|--------|--------|
| Requirement | Determine internal and external communications relevant to the AIMS including what to communicate, when, to whom, and how |
| AI-specific considerations | AI governance communication must address: internal communication of AI policy and changes, external communication with regulators and affected parties, incident communication, and transparency disclosures |
| Required outputs | Communication plan or matrix |
| Audit evidence | Communication plan, evidence of communications executed per plan, feedback records |
| Common nonconformities | No formal communication plan — communications ad hoc; external communication not addressed; no process for communicating AI incidents to affected parties |

### 7.5 Documented information

| Aspect | Detail |
|--------|--------|
| Requirement | The AIMS must include documented information required by the standard and determined by the organisation as necessary for AIMS effectiveness. Control creation, update, and management of documented information |
| AI-specific considerations | AI-specific documentation includes: AI system register, risk registers, AISIA records, SoA, model documentation, data governance records, incident logs, audit trails of AI decisions |
| Required outputs | Document control procedure, document register, version control system |
| Audit evidence | Document control procedure, evidence of version control, evidence of document review and approval, evidence of controlled distribution |
| Common nonconformities | AI-specific documents not under version control; model documentation not maintained when models are updated; AISIA records not linked to AI system register; document retention periods not defined for AI-specific records |

---

## Clause 8 — Operation

### 8.1 Operational planning and control

| Aspect | Detail |
|--------|--------|
| Requirement | Plan, implement, and control the processes needed to meet AIMS requirements and implement the actions determined in planning (Clause 6) |
| AI-specific considerations | Operational planning must cover: AI system development and deployment processes, data management operations, supplier management processes, monitoring and incident response operations, change management for AI systems |
| Required outputs | Operational procedures for all AIMS processes, process performance criteria |
| Audit evidence | Documented operational procedures, evidence of process execution, process performance records, change management records |
| Common nonconformities | Operational procedures exist for development but not for monitoring, incident response, or decommission; change management does not cover AI model updates; no process performance criteria defined |

### 8.2 AI risk assessment execution

| Aspect | Detail |
|--------|--------|
| Requirement | Execute the AI risk assessment process (defined in 6.1.2) at planned intervals and when significant changes occur |
| AI-specific considerations | Triggers for reassessment include: new AI system deployment, significant model update, change in deployment context, regulatory changes, incident occurrence, stakeholder feedback, and scheduled periodic review |
| Required outputs | Completed risk assessments for all in-scope AI systems, completed AISIA records, updated risk register |
| Audit evidence | Dated risk assessment records, evidence that assessments were triggered by defined events, evidence that results were communicated to relevant parties |
| Common nonconformities | Initial assessment completed but no reassessment scheduled; reassessment not triggered by model updates or context changes; results not communicated to AI system owners |

### 8.3 AI risk treatment execution

| Aspect | Detail |
|--------|--------|
| Requirement | Implement the risk treatment plan determined in 6.1.3 |
| AI-specific considerations | Treatment implementation includes: deploying technical controls (guardrails, monitoring, bias mitigation), establishing operational controls (human oversight, escalation procedures), and implementing contractual controls (supplier agreements, SLAs) |
| Required outputs | Evidence of treatment implementation, residual risk assessment |
| Audit evidence | Implementation records for each treatment action, residual risk ratings, evidence that treatments are effective |
| Common nonconformities | Treatment plan documented but not fully implemented; residual risk not reassessed after treatment; treatment effectiveness not measured |

---

## Clause 9 — Performance evaluation

### 9.1 Monitoring, measurement, analysis, and evaluation

| Aspect | Detail |
|--------|--------|
| Requirement | Determine what needs to be monitored and measured, the methods, when monitoring and measurement shall be performed, and when results shall be analysed and evaluated |
| AI-specific considerations | AI governance metrics must cover both AIMS process performance and AI system performance |
| Required outputs | Metrics and monitoring plan, performance dashboards or reports |
| Audit evidence | Defined metrics with targets, evidence of measurement, analysis reports, trend data |
| Common nonconformities | Metrics limited to AIMS process compliance (audit completion, training completion) — no AI system performance metrics; no trend analysis; no defined targets or thresholds |

**Recommended metrics:**

| Category | Metric | Frequency |
|----------|--------|-----------|
| AIMS process | Percentage of AI systems with current risk assessment | Quarterly |
| AIMS process | Percentage of Annex A controls implemented per SoA | Quarterly |
| AIMS process | Number of open nonconformities and corrective actions | Monthly |
| AI system | Model performance against defined thresholds | Continuous |
| AI system | Bias metrics by protected characteristic | Monthly |
| AI system | Number of AI incidents by severity | Monthly |
| AI system | Drift detection alerts and response time | Continuous |
| Stakeholder | Number of AI-related complaints or concerns | Quarterly |
| Stakeholder | Time to resolve AI-related complaints | Quarterly |

### 9.2 Internal audit

| Aspect | Detail |
|--------|--------|
| Requirement | Conduct internal audits at planned intervals to determine whether the AIMS conforms to the organisation's requirements and the standard, and is effectively implemented and maintained |
| AI-specific considerations | Internal auditors must have AI domain competence (not just management system audit skills). Audit scope must cover both AIMS processes and AI system-level controls. Sampling should include technical evidence (model documentation, data quality records) not just management documentation |
| Required outputs | Internal audit programme, audit plans, audit reports, nonconformity records |
| Audit evidence | Audit programme with schedule, individual audit plans, audit reports with findings and evidence, corrective action tracking for audit findings |
| Common nonconformities | Auditors lack AI competence — audit limited to document review without technical assessment; audit programme does not cover all clauses and controls within the certification cycle; findings not tracked to closure |

### 9.3 Management review

| Aspect | Detail |
|--------|--------|
| Requirement | Top management must review the AIMS at planned intervals to ensure its continuing suitability, adequacy, and effectiveness |
| AI-specific considerations | Management review inputs must include: AI risk landscape changes, AISIA results, AI incident summary, AI system performance data, regulatory developments, stakeholder feedback on AI, and internal audit findings. Review outputs must include: decisions on AIMS changes, resource allocation, and improvement priorities |
| Required outputs | Management review agenda, management review minutes with inputs reviewed and decisions made |
| Audit evidence | Management review minutes, attendance records (showing top management participation), evidence that review inputs were presented, evidence that decisions were implemented |
| Common nonconformities | Management review is a formality — inputs not comprehensive, decisions not recorded, actions not tracked to completion; top management does not attend; AI-specific inputs (incident data, performance metrics) not included |

---

## Clause 10 — Improvement

### 10.1 Continual improvement

| Aspect | Detail |
|--------|--------|
| Requirement | Continually improve the suitability, adequacy, and effectiveness of the AIMS |
| AI-specific considerations | Continual improvement for AI governance includes: incorporating lessons from AI incidents, updating controls as AI technology evolves, improving AI risk assessment methodology based on experience, and adapting to emerging regulations and standards |
| Required outputs | Improvement register or log documenting improvement initiatives, their rationale, implementation, and outcomes |
| Audit evidence | Improvement register, evidence of improvement initiatives executed, evidence that improvements resulted from analysis of performance data, incidents, or audit findings |
| Common nonconformities | No formal improvement process — improvements ad hoc and undocumented; no link between performance data / incidents and improvement actions; improvement register does not exist |

### 10.2 Nonconformity and corrective action

| Aspect | Detail |
|--------|--------|
| Requirement | When a nonconformity occurs, react to control and correct it, evaluate the need for corrective action to eliminate the root cause, implement corrective action, review effectiveness, and update risks and opportunities if necessary |
| AI-specific considerations | AI-specific nonconformities include: AI system producing biased outputs, AISIA not conducted for new AI system, data quality thresholds breached, human oversight not functioning as designed, AI incident response procedure not followed. Root cause analysis must consider AI-specific factors (training data, model architecture, deployment context) |
| Required outputs | Nonconformity log, root cause analysis records, corrective action records, effectiveness review records |
| Audit evidence | Nonconformity records with descriptions, root cause analysis documentation, corrective action plans with responsible parties and timelines, evidence of effectiveness reviews, evidence that corrective actions were implemented |
| Common nonconformities | Root cause analysis superficial — does not address AI-specific technical factors; corrective actions address symptoms not causes; effectiveness reviews not conducted; nonconformities from AI incidents not captured in the management system |
