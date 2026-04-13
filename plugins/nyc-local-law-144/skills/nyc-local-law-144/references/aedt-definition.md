# AEDT definition — NYC Local Law 144

## Statutory definition (DCWP Rule § 5-300)

| Term | Definition |
|------|-----------|
| Automated employment decision tool (AEDT) | Any computational process derived from machine learning, statistical modeling, data analytics, or artificial intelligence that issues a simplified output (score, classification, recommendation) used to substantially assist or replace discretionary decision-making for employment decisions |
| Substantially assists | (1) Relies solely on simplified output with no other inputs, OR (2) uses simplified output as one of weighted criteria, OR (3) uses simplified output to overrule or modify conclusions derived from other factors |
| Employment decision | Screening candidates for employment or employees for promotion within New York City |
| Simplified output | A score, classification, ranking, or recommendation produced by the computational process |

## What qualifies as an AEDT

| System type | AEDT? | Reasoning |
|-------------|-------|-----------|
| Resume screening AI that ranks candidates | Yes | Scores and ranks candidates, reduces candidate pool |
| Video interview AI assessing personality traits | Yes | Classifies candidates based on assessed traits |
| Chatbot that asks screening questions and scores answers | Yes | Scores candidate responses, substantially assists decision |
| Skills assessment platform with ML scoring | Yes | ML-based scoring of candidate performance |
| Predictive analytics tool scoring employee promotion readiness | Yes | ML-based scoring for promotion decisions |
| Job board algorithm that matches candidates to postings | Gray area | Depends on whether it reduces the candidate pool or merely suggests matches |
| AI tool that summarizes resumes but does not score or rank | Gray area | Depends on whether summary substantially assists or is purely informational |
| Calendar scheduling tool for interviews | No | Administrative function, not discretionary decision-making |
| ATS keyword filter using Boolean logic (no ML) | No | Not derived from ML, statistical modeling, data analytics, or AI |
| Background check service (no ML scoring) | No | Factual verification, not ML-based scoring or classification |
| Human recruiter using AI-generated notes as one input among many with full discretion | Gray area | May not qualify if human makes 100% of the decision and AI is purely informational |

## Gray areas and exclusions

| Scenario | Analysis |
|----------|----------|
| Tool used only for internal promotions (no external candidates) | **Still covered** — LL144 applies to both hiring and promotion decisions |
| Tool where human makes 100% of the decision; AI is purely informational | **May not qualify** — if AI does not substantially assist or replace discretionary decision-making, it may fall outside the definition |
| Tool used on candidates located outside NYC | **Not covered** — LL144 only applies to employment decisions in New York City, regardless of where the employer is based |
| Company headquartered in NYC using AEDT on candidates in other cities | **Not covered** — geographic scope is based on candidate/employee location, not employer location |
| Multiple AEDTs used in sequence in the same hiring process | **Each must be separately audited** — each tool that qualifies as an AEDT requires its own independent bias audit |
| AEDT used by staffing agency on behalf of employer | **Both may be liable** — employment agencies are covered entities under LL144 |
| Vendor-provided AEDT where employer has no access to underlying model | **Employer still responsible** — the obligation to obtain a bias audit falls on the employer/employment agency using the AEDT |

## AEDT determination decision tree

```
1. Does the tool use ML, statistical modeling, data analytics, or AI?
   ├── No → NOT AN AEDT. Stop.
   └── Yes → Continue to step 2.

2. Does the tool produce a simplified output (score, classification, ranking, recommendation)?
   ├── No → NOT AN AEDT. Stop.
   └── Yes → Continue to step 3.

3. Is the output used for an employment decision (hiring or promotion)?
   ├── No → NOT AN AEDT. Stop.
   └── Yes → Continue to step 4.

4. Does the output substantially assist or replace discretionary decision-making?
   ├── Solely relied upon → AEDT
   ├── One of weighted criteria → AEDT
   ├── Overrules/modifies other factors → AEDT
   ├── Purely informational, human retains full discretion → GRAY AREA
   └── Not used in decision → NOT AN AEDT

5. Is the employment decision for candidates/employees in NYC?
   ├── No → NOT COVERED (even if tool qualifies as AEDT)
   └── Yes → LL144 APPLIES — bias audit, notice, and publication required
```
