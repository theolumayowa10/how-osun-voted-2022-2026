# How Osun Voted: A Comparative Analysis of the 2022 and 2026 Governorship Elections

A Python-based analysis of the 2022 and 2026 Osun State governorship elections across all 30 Local Government Areas, examining election size, candidate performance, electoral geography, political control, competitiveness, third-party performance and participation.

---

## Project Overview

Election results tell us who won.

This project goes further by asking:

**How did Osun vote differently in 2026 compared with 2022?**

I compiled the election results across all 30 LGAs, structured and validated the data, then analysed the elections in Python to understand the political movements beneath the statewide result.

The analysis examines the election as a whole rather than treating it only as a comparison between the two leading contenders.

The project covers:

- Election size and valid-vote growth
- Candidate result structure
- LGA-level electoral geography
- Winning margins and competitiveness
- Changes in political control
- Third-party and non-major-party performance
- Participation and ballot quality
- Major-contender dynamics
- Final election findings

---

## Data Collection

This project did not begin with a ready-made dataset.

I compiled the election figures LGA by LGA from publicly available election records and credible published election reports.

The data preparation process included:

- Collecting election figures for all 30 Osun LGAs
- Cross-checking figures across multiple sources
- Reconciling inconsistencies
- Validating statewide totals
- Structuring the results into an analytical dataset
- Standardising candidate and party labels
- Calculating vote shares and margins
- Creating derived analytical variables for comparison

The objective was to build a dataset reliable enough to support both statistical analysis and public-facing election storytelling.

---

## Analytical Workflow

The project follows this workflow:

**Data Collection → Data Validation → Data Cleaning → Python Analysis → Editorial Data Story → Power BI → Portfolio Documentation**

Python serves as the analytical engine of the project.

The visual storytelling stage only begins after the analytical findings have been completed and validated.

---

## Tools Used

### Python

Python was used for:

- Data inspection
- Data cleaning
- Validation
- Transformation
- Vote-share calculations
- Winning-margin calculations
- LGA comparisons
- Electoral-control classification
- Competitiveness analysis
- Third-party analysis
- Participation analysis
- Final analytical tables

### Libraries

- pandas
- NumPy
- openpyxl

### Jupyter Notebook

The complete analytical process is documented in the project notebook.

### AI-Assisted Visual Storytelling

After completing the Python analysis, I used Nigerian newspaper front pages as visual references and prompted AI to translate the validated findings into an editorial-style election carousel.

The figures, conclusions and analytical framing came from the completed Python analysis.

---

# Key Findings

## 1. Osun recorded a larger valid-vote pool

Valid votes increased from:

**804,450 in 2022**

to:

**985,079 in 2026**

This represents an increase of:

**180,629 valid votes**

or:

**22.45%**

The 2026 election therefore operated within a substantially larger valid-vote pool than the 2022 contest.

---

## 2. The election remained concentrated around the two leading candidates

The two leading candidates accounted for:

**96.76% of valid votes in 2022**

and:

**97.04% in 2026**

The combined non-major-party share moved from:

**3.24% in 2022**

to:

**2.96% in 2026**

Despite the increase in valid votes, the statewide contest did not become more fragmented.

---

## 3. Candidate Result Structure

### 2022

| Candidate | Votes | Vote Share |
|---|---:|---:|
| Ademola Adeleke (PDP) | 403,371 | 50.14% |
| Gboyega Oyetola (APC) | 375,027 | 46.62% |
| Other candidates combined | 26,052 | 3.24% |

### 2026

| Candidate | Votes | Vote Share |
|---|---:|---:|
| Ademola Adeleke (Accord) | 511,067 | 51.88% |
| Bola Oyebamiji (APC) | 444,815 | 45.16% |
| Salaam (ADC) | 17,180 | 1.74% |
| Other candidates combined | 12,017 | 1.22% |

---

## 4. The statewide winning margin widened

The winning margin increased from:

**28,344 votes in 2022**

to:

**66,252 votes in 2026**

Adeleke's statewide vote share moved from:

**50.14% to 51.88%**

an increase of:

**1.74 percentage points**

APC's statewide vote share moved from:

**46.62% to 45.16%**

a decline of:

**1.46 percentage points**

---

## 5. Ten of Osun's 30 LGAs changed political control

Political control changed in one-third of the state's LGAs.

### APC-led to Adeleke-led

Six LGAs moved from the APC nominee to Adeleke:

- Aiyedaade
- Aiyedire
- Ife Central
- Ife East
- Ifedayo
- Iwo

### Adeleke-led to APC-led

Four LGAs moved in the opposite direction:

- Atakunmosa West
- Irepodun
- Obokun
- Olorunda

Political movement therefore occurred in both directions, although more LGAs moved into Adeleke's column than out of it.

---

## 6. The electoral map became less dominated by very close contests

| Competitiveness | 2022 | 2026 |
|---|---:|---:|
| Very close | 12 | 8 |
| Competitive | 6 | 6 |
| Comfortable | 9 | 11 |
| Dominant | 3 | 5 |

The number of very close LGA contests fell from:

**12 to 8**

while comfortable and dominant victories became more common.

This suggests that political control moved significantly across the state even as fewer LGAs were decided by extremely narrow margins.

---

## 7. Adeleke expanded his LGA advantage

LGAs won by Adeleke:

**17 in 2022 → 19 in 2026**

LGAs won by APC:

**13 in 2022 → 11 in 2026**

### Adeleke Strongholds

**Ede South**

2022 winning margin: **53.46%**

2026 winning margin: **60.13%**

**Ede North**

2022 winning margin: **42.00%**

2026 winning margin: **54.10%**

### APC Strongholds in 2026

**Irewole**

Winning margin: **45.79%**

**Boripe**

Winning margin: **22.69%**

---

## 8. Ejigbo emerged as the clearest third-party hotspot

ADC recorded:

**17,180 votes statewide**

representing:

**1.74% of valid votes**

Its strongest performance came in Ejigbo.

### Ejigbo

ADC votes:

**5,053**

ADC vote share:

**12.53%**

Share of all ADC votes statewide:

**29.41%**

Combined non-major-party vote share:

**14.04%**

Other notable non-major-party vote shares in 2026 included:

| LGA | Non-Major Vote Share |
|---|---:|
| Ejigbo | 14.04% |
| Ilesa West | 4.27% |
| Ife East | 3.62% |
| Atakunmosa East | 3.44% |
| Osogbo | 3.40% |

Smaller parties remained limited statewide, but Ejigbo stood out as their clearest pocket of strength.

---

## 9. Valid-vote growth varied significantly across LGAs

The fastest percentage increases in valid votes included:

| LGA | Valid-Vote Growth |
|---|---:|
| Ifedayo | 45.77% |
| Ede North | 36.24% |
| Egbedore | 35.03% |
| Iwo | 34.78% |

Osogbo contributed the largest individual share of the statewide increase in valid votes at:

**7.92%**

followed by:

**Iwo: 6.86%**

and:

**Ede North: 6.84%**

---

## 10. Ballot quality varied geographically

For the 2026 election:

**Accredited voters:** 1,010,684

**Votes cast:** 1,005,800

**Valid votes:** 985,079

**Rejected ballots:** 20,721

**Accredited-to-cast rate:** 99.52%

**Valid-ballot rate:** 97.94%

**Rejected-ballot rate:** 2.06%

Ilesa West recorded the highest rejected-ballot rate at:

**3.17%**

Orolu recorded the lowest accredited-to-cast rate at:

**93.97%**

---

## 11. Major-Contender Dynamics

Adeleke's vote share increased in:

**18 LGAs**

and decreased in:

**12 LGAs**

His largest vote-share gain occurred in:

**Ife Central: +13.58 percentage points**

His largest decline occurred in:

**Irewole: -16.37 percentage points**

APC's vote share increased in:

**11 LGAs**

and declined in:

**19 LGAs**

Its largest gain occurred in:

**Irewole: +17.47 percentage points**

Its largest decline occurred in:

**Ife Central: -13.48 percentage points**

---

# Final Interpretation

The 2026 Osun governorship election was not simply a repeat of 2022.

The state recorded a substantially larger valid-vote pool, ten LGAs changed political control, fewer contests were decided by extremely narrow margins, and the statewide winning margin expanded considerably.

At the same time, political movement was not entirely one-directional.

APC gained control of four LGAs previously won by Adeleke, while six LGAs moved in the opposite direction.

Third-party influence remained limited across the state, but Ejigbo emerged as a significant local exception.

Taken together, the findings show an election where the statewide result became more decisive while meaningful political movement continued underneath it at LGA level.

---

# Editorial Data Story

After completing the analysis, the findings were translated into an eight-slide Nigerian newspaper-inspired visual story.

The carousel covers:

1. Election overview
2. Election size and valid-vote growth
3. Candidate result structure
4. Electoral geography
5. LGAs that changed political control
6. Third-party and non-major-party performance
7. Participation and ballot quality
8. Final findings

The objective was to present election analysis in a format that combines data journalism, political reporting and visual storytelling.

---

# Repository Structure

    how-osun-voted-2022-2026/
    │
    ├── README.md
    │
    ├── notebooks/
    │   └── How_Osun_Voted_2022_2026_Analysis.ipynb
    │
    ├── data/
    │   └── How_Osun_Voted_2022_2026_Final_Analysis.xlsx
    │
    ├── visuals/
    │   ├── carousel_slide_01.jpg
    │   ├── carousel_slide_02.jpg
    │   ├── carousel_slide_03.jpg
    │   ├── carousel_slide_04.jpg
    │   ├── carousel_slide_05.jpg
    │   ├── carousel_slide_06.jpg
    │   ├── carousel_slide_07.jpg
    │   └── carousel_slide_08.jpg
    │
    └── sources/
        └── data_sources.md

---

# Project Outputs

## Python Analysis

A complete Jupyter Notebook containing the data preparation, validation, calculations and analytical workflow.

## Final Analysis Workbook

An Excel workbook containing the cleaned LGA-level analytical dataset and the final supporting tables used throughout the project.

## Editorial Carousel

An eight-slide Nigerian newspaper-inspired visual data story presenting the strongest findings from the analysis.

## Power BI Dashboard

The next stage of the project will translate the validated analytical tables into an interactive Power BI dashboard.

---

# Important Analytical Note

The 2022 dataset contains the valid-vote and candidate-result information required for the comparative analysis.

Comparable 2022 accreditation, votes-cast and rejected-ballot figures were not available within the analytical dataset used for this project.

For that reason, the **22.45% increase in valid votes is not described as a 22.45% increase in voter turnout**.

Participation and ballot-quality metrics based on accreditation, votes cast and rejected ballots are reported specifically for the 2026 election.

This distinction is important because valid-vote growth and voter turnout are not the same measure.

---

# Project Status

**Data collection:** Complete

**Data cleaning and validation:** Complete

**Python analysis:** Complete

**Editorial data story:** Complete

**GitHub documentation:** Complete

**Power BI dashboard:** Next stage

**Portfolio documentation:** Upcoming

---

## Author

**Mayowa Oluyole**

Data Analyst | Data Storyteller

I build analytical projects that combine data collection, Python, data visualisation and storytelling to communicate complex information more clearly.

This project forms part of my growing body of work in public-sector analytics, political data, data journalism and visual storytelling.
