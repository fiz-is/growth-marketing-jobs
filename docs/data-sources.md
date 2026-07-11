# Data Sources

Growth Marketing Jobs is built from public job-posting sources.

The project prioritizes company-owned job boards and applicant tracking system pages over copied listings or generic aggregator pages.

## Preferred source types

Preferred sources include:

- Company career pages
- Greenhouse job boards
- Lever job boards
- Ashby job boards
- Other public applicant tracking system pages

## Why source quality matters

Job data becomes stale quickly.

Public company job boards are usually more reliable than reposted listings because they are closer to the employer’s own source of truth.

The project aims to avoid treating every reposted job listing as equal.

## Data fields

Typical job fields include:

- Job title
- Company
- Job URL
- Location
- Remote or hybrid status when available
- Department or team
- Posting source
- Description text
- Publication or import status
- Expiration or inactive status when detectable

## Data limitations

Public job postings are inconsistent.

Common limitations include:

- Missing location details
- Ambiguous remote policies
- Inconsistent department labels
- Expired listings that remain publicly accessible
- Applicant tracking systems that format data differently
- Job descriptions that use broad or inconsistent role language

## Handling ambiguity

When a field is ambiguous, the project should avoid overstating certainty.

For example:

- A role should not be marked remote unless the source provides a reasonable remote signal.
- A role should not be classified as growth merely because the company is a startup.
- A location should not be over-normalized if the source is unclear.
- Expired jobs should not be presented as active roles.

## Future data improvements

Planned improvements include:

- Better location normalization
- Stronger remote eligibility detection
- More detailed role-family classification
- Tool-stack extraction from job descriptions
- Company-level aggregation
- Market-intelligence pages based on live inventory
