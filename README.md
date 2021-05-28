# Life Sciences Threat Simulation Index

Life Sciences Threat Simulation Index Release Candidate v1 (Q2 2021)

## Files

- merged.yml : all test cases in a single file
- navigator.json : MITRE Navigator layer for test cases
- summary.csv : test case names, MITRE technique IDs, MITRE tactics, and descriptions for all test cases in CSV format
- techniques : directory of all test cases broken down by MITRE tactic

## Methodology

Test cases are based on MITRE-tracked intelligence and the general process for determining test cases for inclusion is as follows:

1. Identify initial list of groups of interest
2. Map groups to MITRE-tracked groups and filter out non-MITRE groups
3. Extract intelligence for technique examples for each group and filter out anything older than 12 months 
    - this information is available in MITRE Enterprise CTI data
4. For each technique example, read source intelligence to determine if activity can be simulated
5. Develop list for simulatable activities
6. Filter out items from list that do not provide worthwhile simulation candidates
7. Develop full test cases for remaining items


