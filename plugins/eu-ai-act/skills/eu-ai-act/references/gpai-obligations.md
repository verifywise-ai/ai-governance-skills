# General-purpose AI model obligations (Chapter V)

## All GPAI models — Article 53 obligations

| Obligation | Article | What to implement | Evidence needed | Common gaps |
|------------|---------|-------------------|-----------------|-------------|
| Technical documentation | Art. 53(1)(a), Annex XI | Maintain and keep up to date technical documentation of the model including training and testing process and results, containing at minimum the information set out in Annex XI | Annex XI compliant documentation: model architecture, training methodology, data sources, compute used, evaluation results, known limitations | Documentation focuses on capabilities without disclosing limitations; training data description insufficient; Annex XI sections incomplete |
| Information to downstream providers | Art. 53(1)(b) | Provide information and documentation to downstream AI system providers to enable their compliance with the AI Act | Downstream provider information package: model capabilities, limitations, integration guidelines, known risks, appropriate use cases, instructions for compliance | Information provided is marketing-oriented rather than compliance-enabling; limitations and risks not adequately communicated; no guidance for downstream risk management |
| Copyright policy | Art. 53(1)(c) | Establish a policy to comply with EU copyright law, in particular to identify and comply with reservations of rights expressed pursuant to Article 4(3) of Directive (EU) 2019/790 (text and data mining opt-out) | Documented copyright compliance policy; opt-out mechanism; records of rights reservations identified and respected | No systematic process to identify opt-out signals; policy exists but not operationalized; no audit trail of copyright compliance |
| Training content summary | Art. 53(1)(d) | Draw up and make publicly available a sufficiently detailed summary about the content used for training the GPAI model, according to the template provided by the AI Office | Published training content summary per AI Office template | Summary too vague to be meaningful; does not follow AI Office template; not publicly accessible |

## Systemic risk GPAI models — Article 55 additional obligations

| Obligation | Article | What to implement | Evidence needed | Common gaps |
|------------|---------|-------------------|-----------------|-------------|
| Model evaluation | Art. 55(1)(a) | Perform model evaluation in accordance with standardised protocols and tools, including conducting and documenting adversarial testing of the model | Model evaluation reports using standardised protocols; documented test methodologies; benchmark results | Evaluation limited to capability benchmarks without safety evaluations; no standardised protocol adherence; evaluation not updated post-deployment |
| Adversarial testing (red-teaming) | Art. 55(1)(a) | Conduct adversarial testing to identify and mitigate systemic risks, including potential misuse scenarios | Red-team reports; adversarial scenario documentation; mitigation measures for identified risks; retest results | Red-teaming is superficial or limited to common prompt injection; systemic risks (CBRN, cyber, societal) not tested; no external red-team involvement |
| Serious incident tracking and reporting | Art. 55(1)(b) | Track, document, and report serious incidents and possible corrective measures to the AI Office and relevant national competent authorities without undue delay | Incident tracking system; incident reports; corrective action documentation; reporting records | No formal incident tracking for model-level issues; reporting threshold unclear; incidents tracked at application level but not model level |
| Cybersecurity protections | Art. 55(1)(c) | Ensure an adequate level of cybersecurity protection for the GPAI model with systemic risk and the physical infrastructure of the model | Cybersecurity assessment; protection measures documentation; penetration testing results; model security measures (anti-extraction, anti-poisoning) | Cybersecurity focused on infrastructure only; model-specific threats (weights exfiltration, fine-tuning attacks) not addressed; no model-level security assessment |

## Systemic risk determination

| Criterion | Threshold | Detail |
|-----------|-----------|--------|
| Training compute | >10^25 FLOPs | GPAI models trained using total computing power of more than 10^25 floating point operations are presumed to have systemic risk |
| Commission designation | Case-by-case | The Commission may designate a GPAI model as having systemic risk based on criteria in Annex XIII (number of registered end users, degree of market integration, reach of AI system, capabilities) |
| Provider notification | Mandatory | Providers must notify the Commission without delay when their model meets the systemic risk threshold |

## Free and open-source GPAI models

| Aspect | Rule | Exception |
|--------|------|-----------|
| Art. 53(1)(a) — Technical documentation | Exempt: may instead provide sufficiently detailed summary of content used for training | Exemption does NOT apply if model has systemic risk |
| Art. 53(1)(b) — Downstream provider info | Exempt | Exemption does NOT apply if model has systemic risk |
| Art. 53(1)(c) — Copyright policy | NOT exempt — must comply | Applies to all GPAI regardless of license |
| Art. 53(1)(d) — Training content summary | NOT exempt — must publish | Applies to all GPAI regardless of license |
| Art. 55 — Systemic risk obligations | NOT exempt — full compliance required | All systemic risk obligations apply regardless of license |

**Definition:** A model is considered free and open-source when its parameters (weights) are made publicly available with a license permitting access, use, modification, and distribution.

## Codes of practice (Article 56)

| Aspect | Detail |
|--------|--------|
| Purpose | Enable GPAI model providers to demonstrate compliance with obligations |
| Development | AI Office coordinates development; providers and other stakeholders participate |
| Compliance presumption | Adherence to a code of practice creates a presumption of compliance with the corresponding obligations |
| Monitoring | AI Office and Board monitor and evaluate; codes must be updated based on new developments |
| Alternative | Providers may demonstrate compliance through alternative adequate means if they choose not to adhere to a code of practice |
