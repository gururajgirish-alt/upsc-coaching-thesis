# Chapter 4: Data Analysis and Results

---

## 4.1 Introduction

This chapter presents the results of the quantitative analysis conducted on the 26-batch dataset collected from Insights IAS, IAS Baba, and La Excellence. The analysis follows the four-stage strategy outlined in Chapter 3: descriptive statistics, correlation analysis, multiple linear regression (main effects and interaction models), and category-wise comparative analysis.

---

## 4.2 Descriptive Statistics

### 4.2.1 Full Sample Overview

| Variable | N | Mean | Std Dev | Min | Max |
|---|---|---|---|---|---|
| Actual Batch Size (students) | 26 | 164.27 | 41.23 | 88 | 215 |
| Planned Batch Size (students) | 26 | 153.46 | 46.89 | 100 | 200 |
| Batch Pressure (ratio) | 26 | 1.083 | 0.142 | 0.880 | 1.375 |
| No. of Faculty | 26 | 11.54 | 2.89 | 8 | 16 |
| Avg Batches Simultaneously | 26 | 5.62 | 1.84 | 3 | 9 |
| Avg Weekly Teaching Hours | 26 | 28.46 | 5.23 | 18 | 38 |
| Faculty Load Score | 26 | 161.73 | 48.92 | 54 | 266 |
| Course Completion Delay (days) | 26 | 9.08 | 4.67 | 0 | 18 |

Key Observations:
- Average course completion delay across all 26 batches is 9.08 days
- Average Batch Pressure of 1.083 indicates 8.3% over-enrollment on average
- 88.5% of batches experienced some degree of delay

### 4.2.2 Institute-wise Descriptive Statistics

| Institute | Mean Delay | Mean Batch Pressure | Mean Faculty Load Score | Zero-Delay Batches |
|---|---|---|---|---|
| Insights IAS (n=10) | 10.90 days | 0.963 | 198.40 | 0 |
| IAS Baba (n=9) | 9.33 days | 1.177 | 148.44 | 1 |
| La Excellence (n=7) | 6.57 days | 1.137 | 122.86 | 2 |

### 4.2.3 Delay Distribution

| Delay Category | Range | Batches | Percentage |
|---|---|---|---|
| On Time | 0 days | 3 | 11.5% |
| Mild Delay | 1-7 days | 8 | 30.8% |
| Moderate Delay | 8-14 days | 11 | 42.3% |
| Severe Delay | 15+ days | 4 | 15.4% |

---

## 4.3 Correlation Analysis

| Variable | Delay | Batch Pressure | Faculty Load Score |
|---|---|---|---|
| Course Completion Delay | 1.000 | 0.612** | 0.847** |
| Batch Pressure | 0.612** | 1.000 | 0.389* |
| Faculty Load Score | 0.847** | 0.389* | 1.000 |

*p < 0.05; **p < 0.01

- Faculty Load Score and Delay: r = 0.847 (strong, positive, highly significant)
- Batch Pressure and Delay: r = 0.612 (moderate-to-strong, positive, highly significant)

---

## 4.4 Multiple Linear Regression Analysis

### Model 1: Main Effects

Delay = -14.823 + 8.941(Batch Pressure) + 0.0712(Faculty Load Score)

| Predictor | Beta | p-value |
|---|---|---|
| Intercept | -14.823 | 0.0019 |
| Batch Pressure | 8.941 | 0.0088 |
| Faculty Load Score | 0.0712 | < 0.0001 |

- R² = 0.7891, Adjusted R² = 0.7706, F = 42.67, p < 0.0001

### Model 2: Interaction Model

Delay = -38.412 + 31.247(BP) + 0.1834(FLS) - 0.1124(BP x FLS)

| Predictor | Beta | p-value |
|---|---|---|
| Intercept | -38.412 | 0.0008 |
| Batch Pressure | 31.247 | 0.0021 |
| Faculty Load Score | 0.1834 | 0.0020 |
| BP x FLS | -0.1124 | 0.0081 |

- R² = 0.9094, Adjusted R² = 0.8978, F = 78.34, p < 0.0001
- Delta R² = 0.1203 (p = 0.0081) — significant improvement over Model 1

---

## 4.5 Category-wise Analysis

### Batch Pressure Categories

| Category | Range | n | Mean Delay |
|---|---|---|---|
| Low Pressure | BP < 0.95 | 7 | 4.71 days |
| Normal Pressure | 0.95 to 1.05 | 6 | 8.17 days |
| High Pressure | BP > 1.05 | 13 | 12.31 days |

### Faculty Load Score Categories

| Category | Range | n | Mean Delay |
|---|---|---|---|
| Low Load | FLS < 120 | 6 | 3.83 days |
| Moderate Load | 120 to 180 | 11 | 8.64 days |
| High Load | FLS > 180 | 9 | 13.78 days |

### Combined 2x2 Matrix

| | Low/Moderate FLS (<=180) | High FLS (>180) |
|---|---|---|
| Low/Normal BP (<=1.05) | 4.92 days (n=9) | 9.50 days (n=4) |
| High BP (>1.05) | 9.25 days (n=8) | 15.40 days (n=5) |

---

## 4.6 Hypothesis Testing Summary

| Hypothesis | Result | Evidence |
|---|---|---|
| H1: FLS positively predicts delay | Supported | r = 0.847, p < 0.0001 |
| H2: Batch Pressure positively predicts delay | Supported | r = 0.612, p = 0.0088 |
| H3: Interaction FLS x BP predicts delay | Supported | beta = -0.1124, p = 0.0081 |
| H4: Significant inter-institute differences | Supported | ANOVA F = 4.23, p = 0.027 |
| H5: Interaction model > main effects only | Supported | Delta R2 = 0.1203, p = 0.0081 |

All five hypotheses are supported by the data.

---

## 4.7 Key Findings Summary

1. 88.5% of batches experienced delays — systemic, not isolated
2. Faculty Load Score is the strongest predictor (r = 0.847)
3. Batch Pressure is a significant secondary predictor (r = 0.612)
4. Interaction term adds 12% explanatory power (total R2 = 0.9094)
5. La Excellence has the best performance due to lowest Faculty Load Scores
6. Insights IAS has worst performance due to highest Faculty Load Scores despite lowest batch pressure