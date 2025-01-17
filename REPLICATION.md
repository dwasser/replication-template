# Validation and Replication results
> INSTRUCTIONS: Once you've read these instructions, DELETE THESE AND SIMILAR LINES.
> Go through the steps to download and attempt a replication. Document your steps here, the errors generated, and the steps you took to alleviate those errors.

You may want to consult [Unofficial Verification Guidance](https://social-science-data-editors.github.io/guidance/Verification_guidance.html) for additional tips and criteria.

> INSTRUCTION: ALWAYS do "Data description", "Code description". If data is present, ALWAYS do "Data checks". If time is sufficient (initial assessment!), do "Replication steps", if not, explain why not.

Data description
================

> INSTRUCTIONS: Identify all data sources. Create a list (and commit the list together with this report) (not needed if filling out the "Data Citation and Information report"). For each data source, list in this document presence or absence of source, codebook/information on the data, and summary statistics. Summary statistics and codebook may not be necessary if they are available for public use data. In all cases, if the author of the article points to an online location for such information, that is OK. Check for data citation. IN THIS DOCUMENT, point out only a summary of shortcomings.

Code description
================
> INSTRUCTIONS: Identify all **Figure, Table, and any in-text numbers**. Create a list, mapping each of them to a particular program and line number within the program. Commit that list (excel file OK). IN THIS DOCUMENT, point out only a summary of shortcomings. E.g.

- Table 5: could not identify code that produces Table 5

Data checks
===========
> INSTRUCTIONS: When data are present, run checks:
> - can data be read (using software indicated by author)?
> - Is data in archive-ready formats (CSV, TXT) or in custom formats (DTA, SAS7BDAT, Rdata)?
> - Run check for PII ([PII_stata_scan.do](PII_stata_scan.do), sourced from [here](https://github.com/J-PAL/stata_PII_scan) if using Stata) and report results.

Replication steps
=================
> INSTRUCTIONS: provide details about your process of accessing the code and data.
> Do NOT detail things like "I save them on my Desktop".
> DO describe actions   that you did  as per instructions ("I added a config.do")
> DO describe any other actions you needed to do ("I had to make changes in multiple programs"), without going into detail (the commit log can provide that information)

Example:
1. Downloaded code from URL provided.
2. Downloaded data from URL indicated in the README. A sign-up was required (not indicated in README)
3. Added the config.do generating system information, but commented out log creation, as author already creates log files.
4. Ran code as per README, but the third step did not work.
5. Made changes to the way the third step is run to get it to work.

Findings
========
> Describe your findings both positive and negative in some detail, for each **Figure, Table, and any in-text numbers**.

## Tables
- Table 1: Looks the same
- Table 2: (contains no data)
- Table 3: Minor differences in row 5, column 3, 0.003 instead of 0.3

## Figures
- Figure 1: Looks the same
- Figure 2: no program provided

## In-Text Numbers
> INSTRUCTIONS: list page and line number of in-text numbers. If ambiguous, cite the surrounding text, i.e., "the rate fell to 52% of all jobs: verified".

[ ] There are no in-text numbers
[ ] There are in-text numbers, but they are not identified in the code
- Page 21, line 5: Same


Classification
==============
> INSTRUCTIONS: Make an assessment here.
>
> Full replication can include a small number of apparently insignificant changes in the numbers in the table. Full replication also applies when changes to the programs needed to be made, but were successfully implemented.
>
> Partial replication means that a significant number (>25%) of programs and/or numbers are different.
>
> Note that if any data is confidential and not available, then a partial replication applies. This should be noted on the "Replication assessment questionnaire"/ JIRA.
>
> Note that when all data is confidential, it is unlikely that this exercise should have been attempted.
>
> Failure to replicate: only a small number of programs ran successfully, or only a small number of numbers were successfully generated (<25%)

- [ ] full replication
- [ ] partial replication (see above)
- [ ] not able to replicate (reasons see above)
