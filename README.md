## Methods and data for MPR News story about community efforts to address the opioid crisis 

Story: Across north Minneapolis, neighbors help neighbors survive the opioid crisis [link TK](link here)


### Data sources
**Minnesota emergency department record.:** Encounter-level emergency department visit records were obtained through the Healthcare Cost and Utilization Project [(HCUP)](https://hcup-us.ahrq.gov/db/state/sedddbdocumentation.jsp). Each record includes the patient's residential ZIP code, year of visit, demographic fields, and up to several dozen ICD-10-CM diagnosis codes. These records underlie the ZIP-code-level analysis of opioid-related ER visits. Per data use agreements, this data must be aggregated before sharing. Thus we cannot publish the raw emergency department data used. 

**HCUP Fast Stats — Opioid special emphasis tables.** Aggregated, published rates of opioid-related hospital and emergency department use, including breakdowns by state and by community-level income quartile, were drawn from [HCUP Fast Stats "special emphasis" data](https://datatools.ahrq.gov/hcup-fast-stats/).

**CDC provisional overdose death counts.** State and national counts of opioid-involved overdose deaths were drawn from the [CDC National Center for Health Statistics VSRR Provisional Drug Overdose Death Counts](https://data.cdc.gov/National-Center-for-Health-Statistics/VSRR-Provisional-Drug-Overdose-Death-Counts/xkb8-kh2a/about_data) dataset. These figures are provisional and subject to revision as additional death records are processed.

**U.S. Census Bureau, American Community Survey (ACS).** ZIP-code-level population denominators (total and by race/ethnicity) and median household income were drawn from the ACS 5-year estimates via the Census API.

### Definitions
**Opioid-related visits.** An ER visit was classified as opioid-related if any of its diagnosis fields contained an ICD-10-CM code in the opioid poisoning/adverse-effect range (T40.0–T40.4, T40.6) or the opioid use, abuse, and dependence range (F11), following standard HCUP and CDC opioid-surveillance code sets. Some specific codes were then excluded: those tagged as in remission and those whose opioid use was a problem due to underdosing or side effects when taken as directed.

**Rates.** ER visit rates are expressed per 100,000 residents, using ACS population as the denominator. This is a typical way to report public health figures to allow for comparison. Where rates cover multiple years, they are annualized (total cases over the period divided by the number of years, then divided by population).

**Minimum-count threshold.** To meet data use requirements, and to avoid unstable rates built on very small numbers, ZIP codes (or ZIP-code race groups) were required to have at least 11 cases in each relevant year; ZIP-years or groups below that threshold were excluded from the corresponding analysis.

### Methods behind specific statements
**Consistent decline in the 55411 ZIP code.** Using HCUP encounter-level records, opioid-related ER visits were counted by ZIP code and year. For each ZIP code, the year-over-year change was calculated across the three consecutive transitions spanning 2021 to 2024 (2021–2022, 2022–2023, and 2023–2024). A ZIP code was considered to have "consistently declined" if each of these three transitions showed a decrease of at least five percent. ZIP codes were required to have at least 11 opioid-related visits in each of the four years (2021–2024) to be included, per data sharing requirements. 

**Statewide opioid mortality trends.** Opioid-involved overdose deaths for Minnesota and the United States were drawn from the CDC NCHS VSRR Provisional Drug Overdose Death Counts dataset. Year-over-year comparisons use the counts as reported in that dataset. Rates are calculated over the total number of deaths, also provided in the dataset. Because these counts are provisional, recent periods (particularly 2025) are subject to upward revision as additional records are finalized.

**Income and opioid ER rates, Minnesota vs. national.** Published opioid ER rates by community-level income quartile were drawn from the HCUP Fast Stats opioid special-emphasis tables. HCUP assigns each patient to an income quartile based on the median household income of their residential ZIP code, measured against that year's national distribution; quartile cutoffs therefore shift from year to year.

### Notes and limitations
**Race and ethnicity.** In the encounter-level HCUP data, race and Hispanic ethnicity are recorded as mutually exclusive categories, and the ACS non-Hispanic race denominators were chosen to align with that coding.

**Small numbers.** Despite the minimum-count threshold, ZIP-code-level rates — particularly for smaller population groups — can rest on modest case counts and should be interpreted with appropriate caution.
