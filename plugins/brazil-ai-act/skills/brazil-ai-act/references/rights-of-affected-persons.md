# Rights of affected persons under the Brazil AI Act

## Rights table

| Right | Description | When it Applies | How to Implement | LGPD Parallel |
|-------|-------------|-----------------|------------------|---------------|
| Right to be informed | Know when interacting with an AI system or when AI is used in decisions | All AI systems | Clear disclosure before or during interaction; signage, notices, or in-app disclosure | Art. 18 LGPD (right to information about processing) |
| Right to explanation | Understand how the AI system reached a specific decision or recommendation | Automated decisions affecting rights or interests of individuals | Provide meaningful explanation of logic, main criteria, and factors that influenced the decision; avoid purely technical jargon | Art. 20 LGPD (right to review of automated decisions) |
| Right to human review | Request that a human being review an automated decision | Significant automated decisions that affect legal rights or similarly significant interests | Designate human reviewer with authority and competence to understand and override the AI decision; document review process | Art. 20 LGPD (right to request review by natural person) |
| Right to non-discrimination | Not be subject to discriminatory outcomes produced by AI systems | All AI systems | Bias testing before deployment, ongoing fairness monitoring, remediation procedures when discrimination is detected | Constitution Art. 5 (equality before the law); Art. 6(IX) LGPD (non-discrimination) |
| Right to correction | Correct inaccurate data used by the AI system in making decisions | When AI uses personal data for decisions | Data correction request process, consideration of whether model retraining is needed, confirmation of correction | Art. 18(III) LGPD (right to correction of incomplete, inaccurate, or outdated data) |
| Right to data portability | Port personal data used in AI processing to another provider | When technically feasible and data is used in AI processing | Machine-readable format export, API access where applicable, reasonable timeframe for fulfillment | Art. 18(V) LGPD (right to portability of data) |
| Right to contest | Challenge AI decisions through a formal process | Significant automated decisions that affect legal rights or interests | Formal appeals process, ombudsman or review board, access to judicial recourse, documented decision rationale | Constitutional right (Art. 5, XXXV — access to justice) |
| Right to prior notice | Be notified before AI is used for decisions affecting the individual | Before deployment of AI system on an individual for decision-making purposes | Advance notice with purpose, scope, type of AI system, and rights available to the individual; reasonable notice period | Not explicitly stated in LGPD (new obligation under AI Act) |

## Implementation checklist for each right

### Right to be informed
- [ ] AI system interaction points identified
- [ ] Disclosure language drafted (plain Portuguese)
- [ ] Disclosure mechanism implemented (banner, notice, verbal)
- [ ] Disclosure timing verified (before or at point of interaction)
- [ ] Records of disclosure maintained

### Right to explanation
- [ ] Explanation templates created for each decision type
- [ ] Technical logic translated to plain language
- [ ] Explanation delivery mechanism implemented
- [ ] Staff trained to provide explanations on request
- [ ] Explanation records maintained

### Right to human review
- [ ] Human reviewers designated with appropriate authority
- [ ] Review request process documented and accessible
- [ ] Reviewers trained on AI system logic and limitations
- [ ] Override mechanism functional and tested
- [ ] Review decisions documented and archived

### Right to non-discrimination
- [ ] Protected characteristics identified for Brazilian context
- [ ] Bias testing conducted before deployment
- [ ] Ongoing fairness metrics monitored in production
- [ ] Remediation process defined for detected bias
- [ ] Discrimination complaints process established

### Right to correction
- [ ] Data correction request channel established
- [ ] Process for verifying and implementing corrections defined
- [ ] Impact assessment for correction on model outputs documented
- [ ] Confirmation of correction sent to requester
- [ ] Correction records maintained

### Right to data portability
- [ ] Data export format defined (machine-readable)
- [ ] Export mechanism implemented and tested
- [ ] Timeframe for fulfillment established
- [ ] Data scope for portability documented
- [ ] Portability request records maintained

### Right to contest
- [ ] Appeals process documented and published
- [ ] Review body or ombudsman designated
- [ ] Timeline for appeal resolution defined
- [ ] Judicial recourse information provided
- [ ] Contest and resolution records maintained

### Right to prior notice
- [ ] Notice content defined (purpose, scope, rights)
- [ ] Notice delivery mechanism established
- [ ] Reasonable notice period determined
- [ ] Notice records maintained
- [ ] Process for updating notice when system changes

## LGPD and AI Act rights alignment

| LGPD Right (Art. 18) | AI Act Right | Alignment Notes |
|-----------------------|--------------|----------------|
| Right to confirmation of processing | Right to be informed | AI Act extends to disclosure of AI involvement specifically |
| Right to access data | Right to explanation | AI Act goes further — requires explanation of AI decision logic, not just data access |
| Right to correction | Right to correction | Substantially aligned; AI Act adds consideration of model impact |
| Right to anonymization, blocking, deletion | — | LGPD-specific; not directly replicated in AI Act but still applies |
| Right to portability | Right to data portability | Substantially aligned |
| Right to information about sharing | Right to be informed | AI Act extends to AI-specific disclosures |
| Right to review of automated decisions | Right to human review, Right to explanation | AI Act provides more detailed requirements for human review process |
| Right to object to processing | Right to contest | AI Act provides formal contestation mechanism beyond LGPD objection |

## Key implementation considerations

1. **Language requirement** — All disclosures, explanations, and notices must be provided in Portuguese, in clear and accessible language appropriate for the target audience.

2. **Vulnerable populations** — Enhanced protections apply when AI systems affect children, elderly persons, or persons with disabilities. Explanations and notices must be adapted accordingly.

3. **Timing** — Rights are not merely reactive. The right to prior notice and right to be informed require proactive disclosure before or during AI interaction, not only upon request.

4. **ANPD enforcement** — ANPD will issue specific guidance on implementing these rights. Organizations should monitor ANPD publications and adapt their processes accordingly.

5. **Documentation** — All rights exercises must be documented. ANPD may request evidence of rights implementation during audits or investigations.
