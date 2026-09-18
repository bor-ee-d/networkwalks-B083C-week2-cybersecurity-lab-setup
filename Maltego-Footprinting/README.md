# W2-PM3 — Maltego Based Footprinting

## Objective

Perform and document an authorized OSINT/footprinting exercise using Maltego as part of the Networkwalks B083C Week 2 cybersecurity internship.

## Target

- **Authorized target:** `networkwalks.com`
- **Starting entity:** Domain
- **Focus:** Email-address footprinting

## Methodology

1. Opened Maltego in the cybersecurity lab environment.
2. Created a new graph and added the `networkwalks.com` domain.
3. Selected the **Email Address** entity/transform path.
4. Ran **To Emails @domain [Search Engine]**.
5. The transform completed successfully.
6. The returned email-address entities were displayed in the Maltego graph and reviewed as footprinting results.

> **Note:** The `@` in the Transform name is part of the Transform label; it is not a separate symbol that Maltego is required to add to the graph.

## Findings

The Email Address Transform returned email-related entities associated with the authorized `networkwalks.com` domain.

This demonstrates how Maltego can use graph-based relationships to connect a domain with publicly indexed email information.

## Evidence

Store practical screenshots in:

`screenshots/`

Recommended evidence:
- Starting graph containing `networkwalks.com`.
- Transform selection/run.
- Final graph showing the returned Email Address entities.
- Transform Output showing successful completion.

## Key Learning Outcomes

- Started an OSINT investigation from a domain entity.
- Used Maltego entities and Transforms.
- Performed email-address footprinting.
- Interpreted graph-based relationships and returned entities.
- Practised documenting OSINT activity in an authorized training environment.

## Security & Ethical Considerations

This exercise was performed for authorized cybersecurity training. Footprinting and OSINT techniques should only be used against systems, domains, or organizations where appropriate authorization has been provided. Sensitive information, credentials, private data, or information from unauthorized targets should not be collected or published.
