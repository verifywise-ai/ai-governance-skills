# South Korea AI Basic Act — Impact assessment

## When an impact assessment is required

| Trigger | Description |
|---------|-------------|
| New high-risk AI deployment | All high-risk AI systems require an impact assessment before initial deployment |
| Significant modification | When substantial changes are made to an existing high-risk AI system (new data sources, changed decision logic, expanded scope) |
| Periodic reassessment | As specified by MSIT guidelines; expected to require reassessment at regular intervals |
| MSIT request | MSIT may request an updated assessment at any time for high-risk AI systems |
| Change in risk profile | When the operational context changes in ways that may alter the risk profile |

## Required assessment content

### Section 1 — AI system description

| Element | Content required |
|---------|-----------------|
| System name and version | Official name, version number, date of assessment |
| Intended purpose | Clear description of what the AI system is designed to do |
| Technical specifications | Architecture type, model approach, key technical parameters |
| Operational context | Where and how the system is deployed, integration with other systems |
| Developer and deployer | Identifying information for responsible entities |
| Data inputs | What data the system processes and from what sources |
| Outputs and decisions | What the system produces, recommends, or decides |

### Section 2 — Risk identification

| Risk category | Assessment questions |
|--------------|---------------------|
| Life and physical safety | Could the system's outputs or failures directly endanger life or physical safety? |
| Fundamental rights | Could the system affect privacy, non-discrimination, due process, freedom of expression, or other fundamental rights? |
| Economic impact | Could the system affect individuals' economic opportunities, financial access, or livelihoods? |
| Psychological impact | Could the system cause psychological harm, manipulation, or undue stress? |
| Vulnerable populations | Does the system affect children, elderly, persons with disabilities, or other vulnerable groups? |
| Systemic risk | Could the system create cascading failures or systemic risks to critical infrastructure or public services? |
| Bias and discrimination | Could the system produce discriminatory outcomes against protected groups? |

### Section 3 — Impact analysis

| Element | Content required |
|---------|-----------------|
| Affected populations | Who is affected, demographics, estimated scale |
| Impact pathways | How the AI system's outputs reach and affect individuals |
| Severity assessment | How severe are potential negative impacts (minor, moderate, significant, critical) |
| Likelihood assessment | How likely are negative impacts to occur (rare, unlikely, possible, likely, almost certain) |
| Risk rating | Combined severity and likelihood rating for each identified risk |
| Cumulative effects | Assessment of combined effects when multiple risks interact |

### Section 4 — Mitigation measures

| Measure type | Content required |
|-------------|-----------------|
| Technical controls | Algorithm fairness measures, accuracy thresholds, fail-safe mechanisms |
| Organizational controls | Policies, procedures, training, oversight structures |
| Data controls | Data quality standards, bias detection, data protection measures |
| Access controls | Who can access, modify, or override the AI system |
| Monitoring controls | Real-time monitoring, anomaly detection, performance tracking |
| Residual risk | Assessment of remaining risk after mitigation measures are applied |

### Section 5 — Human oversight

| Element | Content required |
|---------|-----------------|
| Oversight model | How humans monitor and supervise the AI system (human-in-the-loop, human-on-the-loop, human-in-command) |
| Intervention capability | How and when humans can intervene in or override AI decisions |
| Override procedures | Documented procedures for human override of AI outputs |
| Competency requirements | Qualifications and training required for oversight personnel |
| Escalation paths | When and how issues are escalated beyond frontline oversight |

### Section 6 — Data governance

| Element | Content required |
|---------|-----------------|
| Training data description | Sources, size, characteristics, collection methods |
| Data quality measures | How data quality is assessed and maintained |
| Bias assessment | How training data is assessed for discriminatory bias |
| Data protection | How personal data is protected in compliance with PIPA (Personal Information Protection Act) |
| Data retention | How long data is retained and under what conditions |
| Data provenance | Documentation of data origin and processing chain |

### Section 7 — Monitoring plan

| Element | Content required |
|---------|-----------------|
| Performance metrics | Key metrics monitored (accuracy, fairness, error rates) |
| Monitoring frequency | How often metrics are reviewed (real-time, daily, weekly, monthly) |
| Drift detection | How model drift and performance degradation are detected |
| Incident thresholds | What performance levels trigger review or intervention |
| Review schedule | When the full impact assessment is reviewed and updated |
| Reporting | How monitoring results are reported to oversight personnel and MSIT if required |

## MSIT submission requirements

| Requirement | Detail |
|------------|--------|
| When to submit | High-risk AI systems may be required to submit assessments to MSIT (specific triggers to be defined by presidential decree) |
| Format | Expected to follow MSIT-specified template (to be issued) |
| Review process | MSIT may review the assessment and request modifications or additional safeguards |
| Outcome | MSIT may approve, request changes, or restrict deployment based on assessment findings |
| Ongoing obligations | Assessment results inform national AI safety monitoring; updates may be required |

## Impact assessment document template

```
SOUTH KOREA AI BASIC ACT — AI IMPACT ASSESSMENT

1. ASSESSMENT METADATA
   - Assessment date:
   - AI system name and version:
   - Developer:
   - Deployer:
   - Assessor(s):
   - Assessment type: [Initial / Update / Periodic / MSIT-requested]

2. AI SYSTEM DESCRIPTION
   - Intended purpose:
   - Technical approach:
   - Data inputs and sources:
   - Outputs and decisions:
   - Operational context:
   - Affected populations:

3. RISK IDENTIFICATION AND ANALYSIS
   [For each identified risk:]
   - Risk description:
   - Risk category: [Life/Safety | Rights | Economic | Psychological | Vulnerable populations | Systemic | Bias]
   - Severity: [Minor | Moderate | Significant | Critical]
   - Likelihood: [Rare | Unlikely | Possible | Likely | Almost certain]
   - Risk rating: [Low | Medium | High | Critical]

4. MITIGATION MEASURES
   [For each identified risk:]
   - Mitigation measure:
   - Measure type: [Technical | Organizational | Data | Access | Monitoring]
   - Residual risk after mitigation:

5. HUMAN OVERSIGHT
   - Oversight model:
   - Intervention capability:
   - Override procedures:
   - Personnel competency:
   - Escalation paths:

6. DATA GOVERNANCE
   - Training data description:
   - Data quality measures:
   - Bias assessment results:
   - Data protection measures:

7. MONITORING PLAN
   - Key metrics:
   - Monitoring frequency:
   - Drift detection approach:
   - Incident thresholds:
   - Review schedule:

8. CONCLUSIONS AND RECOMMENDATIONS
   - Overall risk assessment:
   - Deployment recommendation: [Proceed | Proceed with conditions | Do not proceed]
   - Conditions (if applicable):
   - Next review date:

9. APPROVAL
   - Approved by:
   - Date:
   - Signature:
```
