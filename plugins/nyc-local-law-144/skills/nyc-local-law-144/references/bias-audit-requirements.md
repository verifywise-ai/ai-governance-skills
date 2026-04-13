# Bias audit requirements — NYC Local Law 144

## Independent auditor requirements

| Requirement | Detail |
|-------------|--------|
| Independence | Must not have a financial interest in the employer or AEDT vendor, other than compensation for the audit itself |
| Certification | No specific certification required by law, but auditor should have statistical analysis and data science expertise |
| Methodology | Auditor independently selects methodology and conducts analysis; employer cannot dictate analytical approach |
| Conflict of interest | Auditor cannot be an employee of, or have an ownership stake in, the employer or AEDT developer |

## Impact ratio calculation

### Selection-based AEDTs

| Metric | Formula |
|--------|---------|
| Selection rate | (Number selected in category) / (Total applicants in category) |
| Impact ratio | (Selection rate for category) / (Selection rate for most-selected category) |

### Scoring-based AEDTs

| Metric | Formula |
|--------|---------|
| Scoring rate | (Average score for category) / (Average score for highest-scoring category) |
| Impact ratio | Scoring rate for each category compared to highest-scoring category |

### Interpreting impact ratios

| Impact ratio | Interpretation |
|--------------|---------------|
| 1.0 | No disparity — category performs equal to most-selected/highest-scoring group |
| 0.8–1.0 | Generally acceptable — no adverse impact indicated |
| Below 0.8 | Potential adverse impact — reference to EEOC four-fifths rule |
| Significantly below 0.8 | Strong indicator of adverse impact — requires attention |

Note: The EEOC four-fifths (80%) rule is a reference point, not a bright-line legal standard under LL144. Impact ratios below 0.8 should trigger further analysis.

## Required statistical tables

### By race/ethnicity (10 EEOC categories)

| Category | # Applicants | # Selected | Selection Rate | Impact Ratio |
|----------|-------------|------------|----------------|--------------|
| Hispanic or Latino | | | | |
| White (not Hispanic or Latino) | | | | |
| Black or African American (not Hispanic or Latino) | | | | |
| Native Hawaiian or Other Pacific Islander (not Hispanic or Latino) | | | | |
| Asian (not Hispanic or Latino) | | | | |
| American Indian or Alaska Native (not Hispanic or Latino) | | | | |
| Two or More Races (not Hispanic or Latino) | | | | |

Note: Categories with fewer than 2% of total applicants may have unreliable impact ratios due to small sample size. Report all categories but flag statistical limitations.

### By sex

| Category | # Applicants | # Selected | Selection Rate | Impact Ratio |
|----------|-------------|------------|----------------|--------------|
| Male | | | | |
| Female | | | | |

### Intersectional analysis (race/ethnicity × sex)

Required if data is sufficient. "Sufficient data" is not defined by law — generally 30 or more applicants per category is considered adequate for statistical reliability.

| Category | Sex | # Applicants | # Selected | Selection Rate | Impact Ratio |
|----------|-----|-------------|------------|----------------|--------------|
| Hispanic or Latino | Male | | | | |
| Hispanic or Latino | Female | | | | |
| White | Male | | | | |
| White | Female | | | | |
| Black or African American | Male | | | | |
| Black or African American | Female | | | | |
| Asian | Male | | | | |
| Asian | Female | | | | |
| (other categories as data permits) | | | | | |

## Data source requirements

| Data source | When to use | Requirements |
|-------------|------------|--------------|
| Historical data | Preferred when available | Minimum one year of AEDT use data; must reflect actual candidate pool |
| Test data | When historical data is insufficient | Acceptable if less than one year of historical data; must be representative of expected candidate population |
| Combined approach | When historical data is partial | May supplement historical data with test data if historical data covers less than one year |

## Audit scope and timing

| Requirement | Detail |
|-------------|--------|
| Timing | Bias audit must be completed before AEDT is first used |
| Annual renewal | Audit must be conducted within one year prior to use; must be updated annually |
| Scope | Each AEDT must be independently audited; a single audit cannot cover multiple distinct AEDTs |
| Multiple positions | If same AEDT is used across different job categories, audit should cover all categories or representative sample |

## Published summary requirements

| Requirement | Detail |
|-------------|--------|
| Location | Must be posted on employer's employment section of website |
| Duration | Must remain posted for at least 6 months after last use of the AEDT |
| Required content — date | Date the bias audit was conducted |
| Required content — data | Source and type of data used (historical vs. test) |
| Required content — applicants | Number of applicants assessed |
| Required content — results | Impact ratios for each race/ethnicity category and sex category |
| Distribution type | Must indicate whether AEDT is selection-based (selects/rejects) or scoring-based (provides scores) |

## Example impact ratio calculation

For a selection-based AEDT:

| Category | # Applicants | # Selected | Selection Rate | Impact Ratio |
|----------|-------------|------------|----------------|--------------|
| White | 500 | 100 | 20.0% | 1.00 |
| Black or African American | 300 | 42 | 14.0% | 0.70 |
| Hispanic or Latino | 250 | 40 | 16.0% | 0.80 |
| Asian | 200 | 36 | 18.0% | 0.90 |

In this example:
- White has the highest selection rate (20.0%) and serves as the reference group (impact ratio = 1.00)
- Black or African American has an impact ratio of 0.70 (14.0% / 20.0%), which is below 0.8 — potential adverse impact
- Hispanic or Latino has an impact ratio of 0.80, at the threshold
- Asian has an impact ratio of 0.90, no adverse impact indicated
