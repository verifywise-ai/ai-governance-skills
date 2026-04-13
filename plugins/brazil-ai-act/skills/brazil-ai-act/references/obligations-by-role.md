# Obligations by role under the Brazil AI Act

## Obligations matrix

| Obligation | Developer | Deployer | Operator | Article Reference |
|-----------|-----------|----------|----------|-------------------|
| Risk classification | Must classify the AI system into the appropriate risk tier before making it available | Must verify the developer's risk classification is appropriate for the intended deployment context | — | PL 2338/2023, risk classification provisions |
| Algorithmic impact assessment | Must conduct the algorithmic impact assessment before the system is made available for deployment | Must review and validate the impact assessment; supplement with deployment-specific analysis | — | PL 2338/2023, impact assessment provisions |
| Technical documentation | Must create and maintain comprehensive technical documentation (system specs, training data, performance metrics, limitations) | Must maintain deployment-specific documentation and keep developer documentation accessible | — | PL 2338/2023, documentation provisions |
| Transparency and disclosure | Must design the AI system to enable transparency (explainability features, disclosure capabilities) | Must implement transparency measures in the deployment context (user-facing disclosures, notices) | Must provide information to affected persons at point of interaction when operating the AI system | PL 2338/2023, transparency provisions |
| Human oversight | Must design human oversight capabilities into the AI system (override mechanisms, interpretability features) | Must implement human oversight in operational context (designate reviewers, establish review processes) | Must facilitate human review requests from affected persons | PL 2338/2023, human oversight provisions |
| Right to explanation | Must provide technical information enabling explanations of AI decisions | Must provide meaningful explanations to affected persons upon request; primary obligation | Must direct explanation requests to deployer; assist where possible | PL 2338/2023, rights provisions |
| Incident reporting | Must report serious incidents to ANPD; must cooperate with deployer on incident investigation | Must report serious incidents to ANPD; must notify developer of incidents detected in deployment | Must escalate incidents to deployer; cooperate with investigation | PL 2338/2023, incident reporting provisions |
| Data governance | Must ensure training data quality, representativeness, and bias mitigation; document data sources and governance measures | Must ensure data used in deployment context meets quality standards; monitor data quality in production | — | PL 2338/2023, data governance provisions |
| Bias testing | Must test for bias before making the AI system available; document testing methodology and results | Must monitor for bias in the deployed system on an ongoing basis; report findings to developer | — | PL 2338/2023, non-discrimination provisions |
| Record-keeping | Must maintain development records, training data documentation, testing results, and impact assessments | Must maintain deployment records, monitoring logs, incident reports, and rights exercise records | Must maintain operational records of AI system use and decisions | PL 2338/2023, record-keeping provisions |
| Post-market monitoring | Must monitor AI system performance across deployments; issue updates and corrections as needed | Must monitor AI system performance in their specific deployment; report issues to developer | — | PL 2338/2023, monitoring provisions |
| Governance system | Must establish AI governance system for high-risk AI (governance structure, policies, risk management) | Must establish AI governance system for high-risk AI (deployment governance, monitoring, rights management) | — | PL 2338/2023, governance provisions |
| Sandbox participation | May apply to participate in ANPD regulatory sandbox for AI innovation | May participate in sandbox alongside developer | — | PL 2338/2023, sandbox provisions |

## Role definitions

### Developer
The entity that designs, develops, or trains an AI system. The developer bears primary responsibility for the safety and compliance of the AI system before it is made available. Key responsibilities include risk classification, impact assessment, technical documentation, and ensuring the system is designed to enable compliance by downstream deployers and operators.

### Deployer
The entity that integrates an AI system and makes it available for use in a specific context. The deployer bridges the developer and operator, ensuring the AI system is properly configured, monitored, and compliant in the specific deployment context. Key responsibilities include validating the developer's assessments, implementing transparency and human oversight, and ongoing monitoring.

### Operator
The entity that uses an AI system to make or support decisions in its operations. The operator interacts directly with affected persons and bears responsibility for front-line transparency, facilitating rights exercise, and escalating issues. The operator's obligations are generally lighter than the developer and deployer but are critical for rights protection.

## Shared obligations

| Shared Obligation | Who Shares | Coordination Required |
|-------------------|-----------|----------------------|
| Incident reporting to ANPD | Developer + Deployer | Coordinate to avoid duplicate reporting; share investigation findings |
| Post-market monitoring | Developer + Deployer | Developer monitors across deployments; deployer monitors their specific deployment; share findings |
| Record-keeping | Developer + Deployer + Operator | Each maintains records appropriate to their role; make available to ANPD on request |
| Governance system (high-risk) | Developer + Deployer | Each establishes governance appropriate to their role; align on policies and processes |
| Transparency | Developer + Deployer + Operator | Developer designs capability; deployer implements; operator delivers to affected persons |
| Bias management | Developer + Deployer | Developer tests pre-deployment; deployer monitors in production; share findings and remediation |

## Role determination guidance

| Scenario | Developer | Deployer | Operator |
|----------|-----------|----------|----------|
| Company builds and uses its own AI system | Yes | Yes | Yes |
| Company builds AI system sold to others | Yes | No | No |
| Company integrates third-party AI into its product | No (third party) | Yes | Possibly |
| Company uses a SaaS AI product for HR decisions | No | No (SaaS provider) | Yes |
| Company fine-tunes a foundation model for deployment | Yes (for fine-tuned version) | Yes | Possibly |

**Important:** An entity may hold multiple roles simultaneously. When this occurs, the entity must satisfy all obligations applicable to each role it holds.
