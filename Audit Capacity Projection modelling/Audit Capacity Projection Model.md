# 📊 Quality Assurance Team Performance Projection Modelling

## 🎯 Overview

This project developed a comprehensive audit capacity projection model for the Regional Hub to forecast audit performance throughout 2025. Using Excel-based modeling, I created both optimistic and realistic scenarios that account for team growth, training requirements, qualification processes, and vacation time. The model provides strategic workforce planning insights for a dynamically evolving audit team scaling from existing members to 24 auditors by mid-year.

### ⚠️ Disclaimer
Due to the confidential nature of company audit operations, specific auditor names and certain operational details have been included only to demonstrate the analytical methodology. This README showcases the projection modeling approach and business intelligence capabilities.


<img width="2238" height="758" alt="image" src="https://github.com/user-attachments/assets/c6b3bffe-99e9-4eed-b6ba-aa1cdac868ec" />



## 🏢 Business Problem

### Context
Management needed to understand audit capacity for 2025 to support strategic planning and resource allocation. With aggressive hiring plans and a growing team, no clear projection existed for realistic audit throughput considering training requirements, qualification processes, and operational constraints.

### Specific Challenges

- **Unknown Capacity Baseline**: No established projection for audit output from a rapidly scaling team
- **Training Time Impact**: Unclear how onboarding and qualification periods would affect productivity
- **Experience Level Variations**: Different training timelines for Senior vs. Auditor roles needed consideration
- **Realistic vs. Ideal Scenarios**: Gap between theoretical maximum capacity and practical achievable output
- **Vacation Time Considerations**: Need to account for mandatory time-off and public holidays
- **Rolling Hire Schedule**: Staggered new joiner start dates from February through June requiring dynamic modeling
- **Resource Planning Risk**: Potential over-commitment without accurate capacity forecasting

## 💡 Solution Overview

### High-Level Approach
Built a month-by-month projection model in Excel which calculates audit capacity based on expected and known future hires (experience level, number of people, time of hire). Created two scenarios: an ideal maximum capacity model and a realistic model incorporating vacation time.

### Key Solution Components

- **Training Timeline Modeling**: Differentiated qualification periods for Senior experience (2 months) vs. Junior experience Auditors (3 months)
- **Training:** Training included onboarding, mandatory trainings, and number of qualification audits to be performed.
- **Dynamic Team Growth**: Incorporated staggered hiring schedule across 5 months
- **Dual Scenario Analysis**: Ideal capacity vs. vacation-adjusted realistic projections
- **Standardized Audit Duration**: Based on reference, 2-week allocation per audit case was used for consistent calculations
- **Extended Timeline Projection**: 2 projections, one with end of the year timeline, the other with end of Q1 (March) timeline

## 🔧 Project Details

### Methodology & Assumptions

#### Training Assumptions

| | Senior Auditor | Junior Auditor |
|--|--|--|
| Universal Training period| `1 month` (mandatory for all auditors)| `1 month` (mandatory for all auditors)|
| Qualification period | `1 month` (due to experience, requires less audits and time for qualification) | `2 months` |
| **Total training time** | `2 months` | `3 months` |


*Rationale: Auditors receive extended qualification time to account for less experience and ensure quality standards.*


#### Capacity Calculations

**Standard Audit Duration**: 2 weeks per audit case
- Based on advised scheduling guidelines
- Used as baseline unit for all projections

**Monthly Capacity by Role**:

| Role | Number of audits/month |
| -- | -- |
| Team Lead | `1 audit/month` (reduced capacity due to management responsibilities) |
| Senior Auditor | `2 audits/month` |
| Junior Auditor | `2 audits/month` |


#### **Annual Time-Off Assumptions**:

- **Model 1:** 20 days: Legal minimum vacation entitlement = > covers 4 weeks = `- 2 audits`
- **Model 2:** 20 days Legal minimum + ~10 days: Public holidays (Christmas, Easter, national holidays) = > covers 6 weeks `- 3 audits`


*Note: Individual vacation day allocations may vary; standardized assumption used for consistency across projections.*

### Team Composition & Growth

**Final Team Size**: 24 auditors
- 1 Team Lead
- 6 Seniors
- 17 Auditors

**Hiring Schedule & Team qualification **:

| Joiners | Number and types of joiners |
| -- | -- |
| Existing members* | `13 people` (1 Team Lead, 3 Seniors, 9 Juniors) |
| March Joiners | `2 people` (2 Juniors) |
| April Joiners | `4 people` (1 Senior, 3 Juniors |
| May Joiners | `3 people` (1 Senior, 2 Juniors) |
| June Joiners | `2 people` (2 Juniors) |
| **Total** | `24 people` (1 Team Lead, 6 Seniors, 17 Juniors) | 

***Assumptions**
- Already part of the team but still requiring training & qualification
- No auditor could do audit from February 2025. 
- 1 Team Lead, 2 Senior, 1 Junior auditor could perform audits from March from *Existing members*


### Analysis Features

**Scenario Modeling**:
1. **Ideal Capacity Model**: Maximum theoretical audit output without time-off considerations
2. **Realistic Capacity Model**: Vacation-adjusted projections for practical planning

**Temporal Analysis**:
- Month-by-month capacity tracking
- Training period visibility per auditor
- Productivity ramp-up visualization
- Extended 15-month projection window

**Capacity Metrics**:
- Individual auditor contribution tracking
- Role-based capacity aggregation
- Cumulative team output projections

## 📊 Key Findings

### Projection Results

**2025 Calendar Year (Feb-Dec)**:

<img width="752" height="452" alt="image" src="https://github.com/user-attachments/assets/4c66a8d4-f276-4de2-b844-5e8707f39a55" />





**Extended Timeline (Feb 2025 - Mar 2026)**:

<img width="752" height="452" alt="image" src="https://github.com/user-attachments/assets/1dc87e57-ed2b-4f28-931a-9c824f8c2c61" />






**Percentage loss due to vacations**
- **~10-15% less audits** can be expected from the potential total number of audits which can be performed within both timeframes



### Strategic Insights

**Training Investment**: Significant upfront capacity loss during Q1-Q2 due to qualification requirements for 14 new joiners

**Capacity Ramp-Up**: Team reaches full productivity by May 2025 when all existing staff complete training and early joiners qualify

**Realistic Planning Gap**: ~10-15% difference between ideal and realistic scenarios highlights importance of vacation-adjusted planning

## 🎯 Key Skills Demonstrated

- **Workforce Capacity Planning**: Multi-variable projection modeling for dynamic team growth
- **Scenario Analysis**: Comparative modeling of ideal vs. realistic operational conditions
- **Excel Financial Modeling**: Time-series projections with complex dependencies
- **Business Requirements Translation**: Converting operational constraints into quantitative models
- **Strategic Workforce Analytics**: Long-term resource planning and capacity forecasting
- **Assumption Documentation**: Clear articulation of modeling logic and constraints
- **Stakeholder Communication**: Translating complex projections into actionable insights

## 🛠️ Tools & Technologies

### Primary Tools
- **Microsoft Excel** - Projection modeling and scenario analysis
- **Excel Formulas** - Dynamic capacity calculations and time-series modeling
- **Spreadsheet Design** - Multi-scenario comparison framework



## 🚧 Challenges & Solutions

- **Modeling Staggered Hiring:** 14 new joiners across 5 months required individual auditor rows with dynamic start dates and role-based qualification timelines.

- **Dual Scenario Maintenance:** Maintained consistency between ideal and realistic models through parallel spreadsheet structure with vacation adjustment as the single variable difference.

- **Vacation Time Standardization:** Applied legal minimum + public holidays as conservative baseline for 24 team members with unknown individual entitlements.

- **Long-Term Projection Accuracy:** Extended model to 15 months to demonstrate capacity stabilization while acknowledging increasing uncertainty in assumptions.

- **Management Capacity Differentiation:** Reduced Team Lead capacity to 1 audit/month to reflect management responsibilities versus operational auditor workload.

## 💼 Business Impact

- **Strategic Planning**: Provided management with data-driven capacity projections for 2025 commitments

- **Resource Allocation**: Enabled informed decisions about hiring timeline and team composition

- **Realistic Expectations**: Vacation-adjusted model prevents over-commitment and supports sustainable workload planning

- **Training Investment Visibility**: Quantified productivity impact of qualification requirements for budget justification

- **Backlog Management**: Contextualized current 650-case workload against projected capacity for prioritization decisions

---

## 📈 Questions or Feedback?

I'm always interested in discussing workforce analytics, capacity planning, and Excel modeling techniques. Feel free to reach out if you have questions about this projection methodology or would like to collaborate on similar workforce planning challenges!

**This project demonstrates practical application of quantitative modeling and scenario analysis to transform operational constraints into strategic workforce capacity projections for quality assurance operations.**
