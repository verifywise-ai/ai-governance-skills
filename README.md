# Claude Skills for AI Governance

A Claude Code plugin marketplace containing 6 AI governance skills covering major AI regulations and frameworks. Each skill transforms Claude into a specialized compliance advisor capable of gap assessments, document generation, risk classification, and structured guidance — all grounded in the actual regulatory text.

## Available skills

| Skill | Description |
|---|---|
| `eu-ai-act` | EU AI Act (Regulation 2024/1689) compliance: risk classification, conformity assessment, FRIA, GPAI obligations, and technical documentation |
| `nist-ai-rmf` | NIST AI Risk Management Framework: organizational profile, risk identification, playbook guidance, and trustworthy AI mapping |
| `iso42001` | ISO/IEC 42001:2023 AI Management System: gap assessment, AISIA, SoA for 38 Annex A controls, and certification readiness |
| `nyc-local-law-144` | NYC Local Law 144: AEDT determination, bias audit planning, report generation, and candidate notice compliance |
| `south-korea-ai-act` | South Korea AI Basic Act: high-risk classification, obligations by role, impact assessment, and transparency compliance |
| `brazil-ai-act` | Brazil AI Act (Marco Legal da IA): risk classification, rights of affected persons, governance system design, and obligations by role |

## Installation

Add the marketplace to your Claude Code installation:

```
/plugin marketplace add verifywise-ai/ai-governance-skills
```

Then install individual skills:

```
/plugin install <name>@ai-governance-skills
```

### Available skill names

- `eu-ai-act`
- `nist-ai-rmf`
- `iso42001`
- `nyc-local-law-144`
- `south-korea-ai-act`
- `brazil-ai-act`

## Author

Gorkem Cetin

## License

MIT
