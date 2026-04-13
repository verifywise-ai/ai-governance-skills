# South Korea AI Basic Act — Risk classification

## High-risk AI criteria

The AI Basic Act establishes a binary classification: **high-risk** or **not high-risk**. High-risk AI systems are designated by presidential decree based on the potential to significantly affect life, physical safety, or fundamental rights.

### General criteria for high-risk designation

| Criterion | Description |
|-----------|-------------|
| Impact on life or safety | AI system may directly affect life or physical safety of individuals |
| Impact on fundamental rights | AI system may significantly affect fundamental rights (privacy, non-discrimination, freedom) |
| Sector designation | AI system operates in a sector designated as high-risk by presidential decree |
| Use case designation | AI system performs a specific function designated as high-risk by presidential decree |

**Note:** Specific sectors and use cases will be defined by presidential decree before the Act takes effect in January 2026. The criteria below reflect expected designations based on legislative intent and MSIT guidance.

### Expected high-risk sectors (subject to presidential decree)

| Sector | Expected high-risk use cases | Rationale |
|--------|------------------------------|-----------|
| Healthcare | Diagnostic AI, treatment recommendation, patient risk scoring | Direct impact on life and physical safety |
| Transportation | Autonomous driving, traffic management, safety-critical systems | Direct impact on physical safety |
| Critical infrastructure | Energy grid management, water treatment, telecommunications | Impact on public safety and essential services |
| Education | Student assessment, admission decisions, learning evaluation | Impact on fundamental rights and opportunities |
| Employment | Hiring decisions, performance evaluation, termination recommendations | Impact on fundamental rights and livelihoods |
| Financial services | Credit scoring, insurance risk assessment, fraud detection | Impact on economic rights and access to services |
| Law enforcement | Predictive policing, surveillance, criminal risk assessment | Impact on fundamental rights and liberty |
| Public safety | Emergency response, disaster management, public health monitoring | Direct impact on life and safety |

## Classification decision tree

| Factor | High-risk indicator | Not high-risk indicator |
|--------|-------------------|----------------------|
| Impact on fundamental rights | Directly affects individual rights (privacy, non-discrimination, due process) | No rights impact or minimal indirect effect |
| Decision autonomy | Autonomous or semi-autonomous decisions affecting individuals | Advisory only with human as final decision-maker |
| Affected population | Vulnerable groups (children, elderly, persons with disabilities) | General population with limited individual scope |
| Reversibility | Decisions difficult or impossible to reverse (denial of benefits, criminal risk scores) | Easily reversible outcomes (content recommendations, non-binding suggestions) |
| Sector | Designated high-risk sector by presidential decree | Non-designated sector |
| Scale of impact | Affects large populations or critical services | Limited individual or organizational scope |

## Classification process

| Step | Action | Outcome |
|------|--------|---------|
| 1 | Check if AI system's sector is designated high-risk by presidential decree | If yes → provisionally high-risk |
| 2 | Check if specific use case is designated high-risk by presidential decree | If yes → provisionally high-risk |
| 3 | Assess whether system significantly affects life, physical safety, or fundamental rights | If yes → high-risk |
| 4 | Consider classification factors (autonomy, reversibility, vulnerable populations, scale) | Supports or refutes high-risk determination |
| 5 | Document classification rationale with article citations | Required for compliance record |

## Comparison with EU AI Act risk tiers

| Feature | South Korea AI Basic Act | EU AI Act |
|---------|------------------------|-----------|
| Number of risk tiers | 2 (high-risk vs not high-risk) | 4 (prohibited, high-risk, limited risk, minimal risk) |
| Prohibited AI category | Not explicitly defined; ethics principles serve as guardrails | Explicit Article 5 prohibitions (social scoring, subliminal manipulation, etc.) |
| Classification mechanism | Presidential decree designation of sectors and use cases | Annex III categories with Article 6(2) exceptions |
| Exception criteria | Not yet defined (subject to presidential decree) | Five specific exceptions in Article 6(2) |
| Classification timing | Upon designation by presidential decree | Upon placement on market or putting into service |
| Reclassification | MSIT and National AI Committee may update designations | Commission may amend Annex III via delegated acts |
| Self-assessment | Developer must assess based on designation criteria | Provider must assess and document classification |

## High-risk classification examples

| AI system | Likely classification | Reasoning |
|-----------|----------------------|-----------|
| Medical diagnostic AI | 🔴 High-risk | Directly affects life and health; healthcare sector expected to be designated |
| Autonomous vehicle system | 🔴 High-risk | Directly affects physical safety; transportation sector expected to be designated |
| Credit scoring algorithm | 🔴 High-risk | Affects fundamental economic rights; financial services sector expected to be designated |
| AI-powered hiring tool | 🔴 High-risk | Affects employment rights; employment sector expected to be designated |
| Content recommendation engine | 🟢 Not high-risk | Advisory function, easily reversible, no designated sector |
| AI spell checker | 🟢 Not high-risk | No impact on rights, purely assistive, easily overridden |
| Customer service chatbot | 🟢 Not high-risk | Informational, no autonomous decisions affecting rights |
| AI-based fraud detection (financial) | 🔴 High-risk | May result in account restrictions affecting financial access |
