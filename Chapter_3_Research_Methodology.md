# Chapter 3: Research Methodology

---

## 3.1 Introduction

This chapter presents the research design, data collection approach, variable operationalization, and analytical strategy employed in this study. The methodology is designed to systematically test the four research questions and five research objectives established in Chapter 1, using batch-level operational data collected from three prominent UPSC coaching institutes. The chapter is organized to move from the philosophical foundations of the research design through to the specific statistical techniques applied in the analysis.

---

## 3.2 Research Philosophy and Approach

This study adopts a **positivist research philosophy**, grounded in the assumption that operational phenomena in coaching institutes are objectively measurable and that systematic relationships between these variables can be identified through rigorous quantitative analysis. The research approach is **deductive** — the study begins with a theoretical framework derived from the literature, derives specific testable hypotheses, and tests these hypotheses against empirical data.

---

## 3.3 Research Design

The study employs a **quantitative, cross-sectional, comparative research design**. The **batch** is established as the unit of analysis — a deliberate and theoretically grounded choice because the key independent variables (faculty load score, batch pressure) are batch-level phenomena.

---

## 3.4 Population and Sample

**Sample:** 26 batches from three institutes:
- **Insights IAS** — 10 batches (GS1 through GS10)
- **IAS Baba** — 9 batches (GFP1 through GFP9)
- **La Excellence** — 7 batches (GSF1 through GSF7)

**Sampling Rationale:** Purposive sampling based on established multi-batch operations, data availability, geographic diversity, and variation in operational models.

---

## 3.5 Data Collection

Batch-level operational data was collected through institute operational records, faculty teaching logs, and a standardized data extraction template across all three institutes. Data collection was conducted between March 2025 and May 2025.

**Variables Collected:**

| Variable | Definition | Source |
|---|---|---|
| Institute | Name of coaching institute | Records |
| Batch Code | Unique batch identifier | Records |
| Planned Start Date | Officially announced course start date | Timetable |
| Actual End Date | Date final scheduled topic was completed | Teaching log |
| Planned Batch Size | Target enrollment as per institute plan | Enrollment register |
| Actual Batch Size | Actual enrolled students at course start | Enrollment register |
| Avg Batches Simultaneously | Average concurrent batches per faculty | Assignment schedule |
| Avg Weekly Teaching Hours | Average teaching hours per faculty per week | Teaching log |

---

## 3.6 Operationalization of Variables

### 3.6.1 Dependent Variable: Course Completion Delay

**Formula:** Course Completion Delay = Actual End Date - Planned End Date (in calendar days)

### 3.6.2 Independent Variable 1: Faculty Load Score (FLS)

**Formula:** Faculty Load Score = Average Batches Handled Simultaneously x Average Weekly Teaching Hours

### 3.6.3 Independent Variable 2: Batch Pressure (BP)

**Formula:** Batch Pressure = Actual Batch Size / Planned Batch Size

### 3.6.4 Interaction Term

**Formula:** Interaction Term = Faculty Load Score x Batch Pressure

---

## 3.7 Hypotheses

- **H1:** Significant positive relationship between Faculty Load Score and course delay
- **H2:** Significant positive relationship between Batch Pressure and course delay
- **H3:** Interaction between FLS and BP significantly predicts delay beyond individual effects
- **H4:** Significant differences in delays across the three institutes
- **H5:** Interaction model explains significantly greater variance than main-effects-only model

---

## 3.8 Analytical Strategy

Four sequential analytical stages:
1. **Descriptive Statistics** — means, standard deviations, frequency distributions
2. **Correlation Analysis** — Pearson correlations between key variables
3. **Multiple Linear Regression** — two hierarchical models (main effects and interaction)
4. **Category-wise Comparative Analysis** — batch groupings by pressure and load levels

**Model 1:** Delay = β0 + β1(Batch Pressure) + β2(Faculty Load Score) + ε

**Model 2:** Delay = β0 + β1(Batch Pressure) + β2(Faculty Load Score) + β3(BP x FLS) + ε

---

## 3.9 Statistical Tools

All analyses conducted using **Microsoft Excel** (Data Analysis ToolPak for regression, LINEST and CORREL functions).

---

## 3.10 Ethical Considerations

- Formal data access agreements obtained from all three institutes
- No individual student data collected or reported
- All data aggregated at the batch level
- Cross-verification of data against multiple sources

---

## 3.11 Limitations

1. Sample size (26 batches) below recommended minimum for regression
2. Weekly teaching hours sourced from self-reported faculty logs
3. Cross-sectional design limits causal inference
4. Limited generalizability to smaller or newer institutes

---

## 3.12 Summary

The methodology employs a positivist, deductive, quantitative approach with batch as the unit of analysis. Data from 26 batches across three institutes is analyzed through descriptive statistics, correlation analysis, hierarchical regression, and category-wise comparison to test five hypotheses about the relationships between faculty load, batch pressure, and course completion delay.