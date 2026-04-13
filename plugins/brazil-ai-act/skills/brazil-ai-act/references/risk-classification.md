# Brazil AI Act risk classification

## Excessive risk — Prohibited AI practices

| Category | Description | Exceptions |
|----------|-------------|------------|
| Social scoring by government | Government-run systems that evaluate individuals based on social behavior for access to public services or benefits | None |
| Subliminal manipulation | AI systems that use subliminal techniques beyond a person's consciousness to cause harm or materially distort behavior | None |
| Exploitation of vulnerabilities | AI systems that exploit vulnerabilities due to age, disability, or social or economic condition to cause harm or materially distort behavior | None |
| Real-time remote biometric identification in public spaces | Real-time facial recognition systems used by law enforcement in publicly accessible spaces | Limited law enforcement exceptions: imminent threat to life, search for missing persons, investigation of specific serious crimes |
| Discriminatory profiling | AI systems used to profile individuals based on race, ethnicity, gender, sexual orientation, political opinion, religion, or other protected characteristics to restrict rights or access to services | Research purposes with appropriate safeguards |

## High-risk AI systems

| Sector / Use Case | Why High-Risk | Examples |
|--------------------|---------------|----------|
| Biometric identification (non-real-time) | Affects fundamental rights, identity verification, potential for mass surveillance | Post-event facial recognition, fingerprint matching systems |
| Critical infrastructure management | Safety impact on essential services and physical well-being | AI managing energy grids, water treatment, transport systems |
| Education and vocational training | Affects access to education, grading fairness, and future opportunities | Automated grading, admission screening, student performance prediction |
| Employment and worker management | Affects livelihoods, hiring decisions, working conditions, termination | Resume screening, performance monitoring, promotion decisions |
| Essential private and public services | Affects access to credit, insurance, healthcare, and government benefits | Credit scoring, insurance risk assessment, healthcare triage |
| Law enforcement | Liberty and fundamental rights implications | Criminal risk assessment, evidence evaluation, suspect identification |
| Migration and border control | Affects vulnerable populations, asylum seekers, and migrants | Visa application screening, border risk assessment |
| Justice and democratic processes | Rule of law implications, democratic integrity | Judicial decision support, legal research AI, election-related systems |
| Healthcare and medical devices | Patient safety, diagnostic accuracy, treatment decisions | AI-assisted diagnosis, treatment recommendation systems |
| Autonomous vehicles | Physical safety of passengers, pedestrians, and other road users | Self-driving cars, autonomous drones, delivery robots |

## Non-high risk AI systems

| Aspect | Detail |
|--------|--------|
| Mandatory obligations | None specific; general principles of the Act apply |
| Voluntary transparency | Encouraged to disclose AI use and provide explanations |
| Codes of conduct | Encouraged to follow industry codes of conduct and best practices |
| Recommended practices | Risk assessment, documentation, bias testing as good practice |
| ANPD guidance | May issue sector-specific recommendations for non-high risk systems |

## Comparison with EU AI Act risk classification

| Feature | Brazil AI Act (PL 2338/2023) | EU AI Act (Reg. 2024/1689) |
|---------|------------------------------|---------------------------|
| Risk tiers | 3 tiers: excessive / high / non-high | 4 tiers: prohibited / high / limited / minimal |
| Prohibited practices list | Similar to EU but fewer specific items | More extensive list (8 categories in Article 5) |
| Limited risk category | No separate limited risk category | Explicit limited risk tier for chatbots, deepfakes, emotion recognition (Article 50) |
| High-risk exceptions | No explicit exception mechanism like Article 6(2) | Five-criteria exception test under Article 6(2) |
| Regulator for classification | ANPD (same as data protection) | National competent authorities + EU AI Office |
| LGPD/GDPR alignment | Strong alignment with LGPD data protection principles | Strong alignment with GDPR data protection principles |
| Sandbox provisions | Regulatory sandbox for testing before classification is finalized | Regulatory sandboxes under Article 57 |
| Classification updates | ANPD may update high-risk list | Commission may update Annex III via delegated acts |

## Risk classification decision tree

```
START: Describe the AI system, sector, use case, and affected population
  │
  ├─ Does it perform social scoring, subliminal manipulation,
  │  exploitation of vulnerabilities, discriminatory profiling,
  │  or real-time biometric identification in public spaces?
  │  │
  │  ├─ YES → EXCESSIVE RISK (PROHIBITED)
  │  │        Check if any specific exception applies.
  │  │        If exception applies → may proceed with safeguards.
  │  │        If no exception → must not be deployed.
  │  │
  │  └─ NO → Continue
  │
  ├─ Does it operate in a high-risk sector/use case?
  │  (biometrics, critical infrastructure, education, employment,
  │   essential services, law enforcement, migration, justice,
  │   healthcare, autonomous vehicles)
  │  │
  │  ├─ YES → HIGH-RISK
  │  │        Full compliance required: algorithmic impact assessment,
  │  │        governance system, transparency, human oversight,
  │  │        incident reporting, documentation.
  │  │
  │  └─ NO → Continue
  │
  └─ NON-HIGH RISK
     Voluntary transparency obligations.
     Encouraged to follow codes of conduct.
     General principles of the Act still apply.
```
