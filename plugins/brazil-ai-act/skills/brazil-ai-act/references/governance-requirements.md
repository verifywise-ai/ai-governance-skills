# Governance requirements under the Brazil AI Act

## AI governance system (required for high-risk AI)

| Component | Requirement | Detail |
|-----------|-------------|--------|
| Governance structure | Designate roles accountable for AI governance | AI governance officer or committee with clear authority and reporting lines; board-level visibility recommended |
| Policies | AI governance policies documented and published | Ethical principles, acceptable use policy, risk management policy, incident response policy; must be accessible to affected persons |
| Risk management | Continuous AI risk management process | Identify, assess, mitigate, and monitor AI risks throughout the system lifecycle; document risk appetite and tolerance levels |
| Documentation | Technical documentation maintained and current | System specifications, training data documentation, performance metrics, known limitations, intended use; update when system changes |
| Training | Staff training on AI governance obligations | Personnel involved in AI development, deployment, and operation must understand their obligations under the Act |
| Audit | Internal audit capability for AI systems | Regular assessment of AI system compliance with governance policies and Act requirements |

## Algorithmic impact assessment

| Aspect | Requirement |
|--------|-------------|
| When required | Before deploying any high-risk AI system; must be completed and documented prior to first use |
| Who conducts | Developer (primarily responsible for conducting the assessment); deployer reviews and validates |
| Content required | System description and purpose; methodology and technical approach; data sources and data governance; potential impacts on rights and safety; affected populations and vulnerability analysis; mitigation measures planned or implemented; human oversight plan; residual risk assessment |
| Publication | Summary of the impact assessment must be made publicly available; detailed content per ANPD guidance |
| Update frequency | When the AI system undergoes significant changes; periodically per ANPD guidelines; after serious incidents |
| ANPD role | May request the full impact assessment; may require modifications to the AI system; may restrict or prohibit deployment based on assessment findings |
| Relationship to LGPD DPIA | Organizations should integrate the algorithmic impact assessment with LGPD Data Protection Impact Assessments (DPIAs) where personal data is involved to avoid duplication |

## Incident reporting

| Aspect | Requirement |
|--------|-------------|
| What to report | Serious incidents: harm to health, safety, or fundamental rights of persons; widespread service disruption; significant bias or discrimination detected; security breaches affecting AI system integrity |
| Who reports | Developer and deployer (both have reporting obligations; coordinate to avoid duplicate reporting) |
| Report to | ANPD (Autoridade Nacional de Protecao de Dados) |
| Timeline | Within timeframe set by ANPD (expected: 72 hours for serious incidents, aligned with LGPD breach notification timeline) |
| Report content | AI system identification (name, version, classification); incident description (what happened, when, how); affected persons (number, categories, severity of impact); measures taken (immediate response, containment, remediation); root cause analysis (when available; preliminary if within 72 hours) |
| Follow-up | Final report with complete root cause analysis and corrective actions; timeline per ANPD guidance |
| Record-keeping | All incident reports and supporting documentation must be retained per ANPD guidelines |

## Record-keeping requirements

| What to Retain | Retention Period | Notes |
|----------------|-----------------|-------|
| AI system logs | Per ANPD guidelines (expected: minimum 5 years) | Operational logs, decision logs, performance metrics |
| Impact assessments | Lifetime of AI system + retention period after decommission | All versions, including updates after significant changes |
| Incident reports | Per ANPD guidelines (expected: minimum 5 years after resolution) | Include supporting evidence and corrective actions |
| Training data documentation | Lifetime of AI system | Data sources, quality assessments, preprocessing steps |
| Governance policies | Current version + historical versions | Demonstrate evolution and continuous improvement |
| Rights exercise records | Per ANPD guidelines (aligned with LGPD retention) | Requests, responses, outcomes for all rights exercised |
| Bias testing results | Lifetime of AI system | Pre-deployment and ongoing monitoring results |

## Post-market monitoring

| Requirement | Detail |
|-------------|--------|
| Continuous monitoring | Developer and deployer must actively monitor the AI system in production throughout its lifecycle |
| Performance tracking | Track accuracy, reliability, and safety metrics against documented thresholds; alert when thresholds are breached |
| Bias monitoring | Ongoing assessment for discriminatory outcomes across protected characteristics; statistical testing at defined intervals |
| Model drift | Monitor for performance degradation over time due to data distribution changes; define drift thresholds and remediation triggers |
| User feedback | Collect and analyze complaints and feedback from affected persons; integrate feedback into system improvement process |
| Reporting to ANPD | Report monitoring findings to ANPD as required; significant findings may trigger incident reporting obligations |
| Documentation | All monitoring activities, findings, and actions taken must be documented and retained |

## Governance system design checklist

### Phase 1 — Foundation
- [ ] AI governance officer or committee designated
- [ ] Governance charter and authority defined
- [ ] Reporting lines to senior leadership established
- [ ] AI inventory created (all AI systems catalogued)
- [ ] Risk classification completed for each AI system

### Phase 2 — Policies and processes
- [ ] AI governance policy drafted and approved
- [ ] Acceptable use policy for AI systems established
- [ ] Risk management process defined
- [ ] Algorithmic impact assessment process documented
- [ ] Incident reporting process and channels established
- [ ] Rights exercise handling process defined

### Phase 3 — Implementation
- [ ] Technical documentation created for each high-risk AI system
- [ ] Algorithmic impact assessments completed for high-risk systems
- [ ] Human oversight mechanisms implemented
- [ ] Transparency and disclosure mechanisms deployed
- [ ] Bias testing conducted before deployment
- [ ] Staff training completed

### Phase 4 — Ongoing operations
- [ ] Post-market monitoring active for all deployed systems
- [ ] Regular bias monitoring schedule established
- [ ] Incident response tested and exercised
- [ ] Governance policies reviewed and updated periodically
- [ ] ANPD guidance monitored and incorporated
- [ ] Annual governance effectiveness review conducted
