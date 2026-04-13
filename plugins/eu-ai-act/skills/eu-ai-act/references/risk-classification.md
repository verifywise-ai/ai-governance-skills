# EU AI Act risk classification

## Prohibited AI practices (Article 5)

| Category | Description | Exceptions |
|----------|-------------|------------|
| Social scoring | AI systems that evaluate or classify persons based on social behaviour or personal characteristics, leading to detrimental or unfavourable treatment unrelated to the context in which data was generated or that is unjustified or disproportionate | None |
| Subliminal manipulation | AI systems that deploy subliminal techniques beyond a person's consciousness to materially distort behaviour, causing or likely to cause significant harm | None |
| Exploitation of vulnerabilities | AI systems that exploit vulnerabilities of persons due to age, disability, or specific social or economic situation to materially distort behaviour, causing or likely to cause significant harm | None |
| Predictive policing (individual) | AI systems that make risk assessments of natural persons to predict the risk of committing a criminal offence, based solely on profiling or personality traits | Permitted when used to augment human assessment based on objective, verifiable facts directly linked to criminal activity |
| Untargeted facial recognition scraping | AI systems that create or expand facial recognition databases through untargeted scraping of facial images from the internet or CCTV footage | None |
| Emotion recognition in workplace/education | AI systems that infer emotions of persons in workplace or educational settings | Permitted where intended for medical or safety reasons |
| Biometric categorization (sensitive attributes) | AI systems that categorize persons based on biometric data to deduce or infer race, political opinions, trade union membership, religious or philosophical beliefs, sex life, or sexual orientation | Permitted for law enforcement when strictly necessary, subject to safeguards |
| Real-time remote biometric identification in public spaces (law enforcement) | AI systems for real-time remote biometric identification of persons in publicly accessible spaces for law enforcement | Permitted only for: (a) targeted search for specific victims of abduction, trafficking, or sexual exploitation; (b) prevention of specific, substantial, imminent threat to life or terrorist attack; (c) identification of suspects of serious criminal offences. Requires prior judicial authorization except in duly justified urgency |

## High-risk AI systems (Annex III)

| Area | Category | Specific use cases |
|------|----------|-------------------|
| 1 | Biometrics | Remote biometric identification (non-real-time); biometric categorization by sensitive or protected attributes; emotion recognition systems |
| 2 | Critical infrastructure | AI used as safety components in management and operation of critical digital infrastructure, road traffic, water/gas/heating/electricity supply |
| 3 | Education and vocational training | AI determining access to or admission to educational institutions; evaluating learning outcomes; assessing appropriate level of education; monitoring and detecting prohibited behaviour during tests |
| 4 | Employment and worker management | AI for recruitment (screening, filtering, evaluating candidates); decisions on promotion, termination, task allocation; monitoring and evaluating performance and behaviour of workers |
| 5 | Essential services access | AI for evaluating eligibility for public assistance benefits and services; credit scoring and creditworthiness assessment; risk assessment and pricing in life and health insurance; evaluation and classification of emergency calls; dispatching emergency first response services |
| 6 | Law enforcement | AI for individual risk assessment (risk of offending, re-offending); polygraph and similar tools; evaluation of reliability of evidence; assessment of risk of irregular immigration; security risk of natural persons; detecting, recognizing, or identifying persons |
| 7 | Migration, asylum, and border control | AI for polygraph and similar tools in asylum/visa/residence permit applications; security risk assessment of irregular migration; assisting examination of asylum/visa/residence permit applications and complaints regarding eligibility |
| 8 | Justice and democratic processes | AI assisting judicial authorities in researching and interpreting facts and law and applying the law; AI used to influence outcome of election or referendum, or voting behaviour (excluding organizing, optimizing campaigns not directly targeting voters) |

## Article 6(2) — High-risk exceptions

An AI system listed in Annex III is **not** considered high-risk if it meets any of these conditions:

| Exception | Description |
|-----------|-------------|
| No significant risk of harm | The AI system does not pose a significant risk of harm to the health, safety, or fundamental rights of natural persons |
| Not sole/primary decision basis | The AI system is not the sole or primary basis for decisions that significantly affect persons |
| Narrow procedural task | The AI system performs a narrow procedural task, such as converting unstructured data into structured data |
| Improves prior human activity | The AI system is intended to improve the result of a previously completed human activity |
| Preparatory task | The AI system performs a preparatory task to an assessment relevant for the purposes of the use cases listed in Annex III |

**Important:** The provider must document the exception assessment and make it available to competent authorities upon request. The exception does not apply to AI systems that profile natural persons (Article 6(3)).

## Limited risk (Article 50) — Transparency obligations

| System type | Obligation | Detail |
|-------------|-----------|--------|
| AI systems interacting with persons (chatbots) | Disclose AI interaction | Inform persons that they are interacting with an AI system, unless obvious from the circumstances |
| AI-generated or manipulated content (deepfakes) | Label as AI-generated | Mark content in a machine-readable format and disclose that it has been artificially generated or manipulated |
| Emotion recognition systems | Inform subjects | Inform persons exposed to the system of its operation and process personal data in accordance with applicable law |

## Minimal risk

| Aspect | Detail |
|--------|--------|
| Obligations | No mandatory requirements under the EU AI Act |
| Encouraged measures | Voluntary codes of conduct (Article 95) covering transparency, human oversight, sustainability, accessibility, stakeholder participation, diversity of development teams |
| Examples | AI-enabled video games, spam filters, inventory management systems, AI-assisted writing tools (where no limited risk transparency triggers apply) |
