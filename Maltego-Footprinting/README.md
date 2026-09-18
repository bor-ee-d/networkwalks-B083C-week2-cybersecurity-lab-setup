# W2-PM3 — Maltego Based Footprinting

## Objective

Document the authorized Maltego footprinting exercise completed for the Networkwalks B083C Week 2 internship project.

## Methodology

The practical exercise used Maltego for OSINT-focused footprinting against the authorized target **networkwalks.com**.

### Steps Performed

1. Opened Maltego in the cybersecurity lab environment.
2. Used `networkwalks.com` as the starting domain.
3. Used the **Email Address** entity for the investigation.
4. Ran the **To Emails @domain [Search Engine]** transform.
5. The transform completed successfully and returned email-address entities in the Maltego graph.
6. Reviewed the returned entities as part of the footprinting exercise.

## Findings

The completed transform returned email-address entities associated with `networkwalks.com`.

The results demonstrate how Maltego can correlate publicly available information into related entities for OSINT and footprinting analysis.

## Evidence

Supporting screenshots should be placed in:

`screenshots/`

Recommended evidence:
- Maltego graph showing the `networkwalks.com` target.
- Email Address entities returned by the **To Emails @domain [Search Engine]** transform.

## Key Learning

This exercise provided practical experience with:
- Starting an OSINT investigation from a domain.
- Using Maltego entities and transforms.
- Discovering relationships between a target domain and publicly indexed email information.
- Interpreting graph-based results.
- Keeping footprinting activity within an authorized educational environment.

## Security & Ethical Considerations

This exercise was performed for authorized cybersecurity training.

Footprinting and OSINT techniques should only be used against domains, systems, or organizations where explicit authorization has been provided. Sensitive information, credentials, private data, or information from unauthorized targets should not be collected or published.
