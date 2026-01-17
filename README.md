# BCG Data Science & Advanced Analytics Virtual Experience Program

## Executive Summary

This project represents a comprehensive data science initiative undertaken as part of the BCG X Virtual Experience Program. The analysis focuses on customer churn prediction for PowerCo, a leading European energy utility provider facing significant customer attrition in the SME segment following market deregulation.

---

## Business Context

### Client Overview
**PowerCo** is a major gas and electricity utility provider serving three primary customer segments:
- Corporate clients
- Small and Medium Enterprises (SMEs)
- Residential consumers

### Challenge
The liberalization of Europe's energy market has triggered unprecedented customer churn, particularly within the SME segment. PowerCo has engaged BCG to identify the root causes of churn and develop data-driven retention strategies.

### Core Hypothesis
Customer churn is primarily driven by price sensitivity. By identifying at-risk customers and their price elasticity, PowerCo can implement targeted retention strategies before customers defect to competitors.

### Proposed Intervention
The SME division leadership has proposed offering a 20% discount to high-risk customers as a retention mechanism, hypothesizing that this incentive will be sufficient to retain price-sensitive customers.

---

## Project Objectives

### Task 1: Business Understanding & Hypothesis Formulation

**Goal:** Transform the business problem into a structured data science framework and establish a rigorous testing methodology.

**Critical Questions Addressed:**
- What factors influence a customer's decision to remain with or leave their current provider?
- Which data elements most effectively predict churn behavior?
- How should we structure our analytical dataset for optimal model performance?
- What exploratory techniques will yield the deepest insights into customer behavior?

**Deliverable:** Comprehensive analytical framework including data requirements, feature specifications, and modeling approach.

---

### Task 2: Exploratory Data Analysis (EDA)

**Available Data Assets:**
- **Customer Profile Data:** Usage patterns, registration dates, consumption forecasts
- **Pricing Intelligence:** Fixed and variable rate structures, historical pricing
- **Outcome Variable:** Binary churn indicator for each customer

**Analytical Objectives:**
1. Conduct comprehensive data profiling
   - Assess data quality, types, and distributions
   - Identify missing values and outliers
   - Examine statistical properties of key variables
2. Test the price sensitivity hypothesis through statistical analysis
3. Synthesize findings into actionable insights
4. Recommend additional data sources to enhance model performance

**Deliverable:** Executive summary (half-page) with key insights and data enhancement recommendations.

---

### Task 3: Feature Engineering & Predictive Modeling

**Goal:** Develop robust predictive features and build a high-performance churn prediction model to validate the price sensitivity hypothesis.

#### Phase 1: Feature Engineering

**Primary Feature:**
- Leverage existing engineered feature: "Off-peak price differential between December and January (year-over-year)"

**Feature Development Strategy:**
- Engineer complementary features to capture diverse churn signals
- Optimize feature granularity for maximum predictive power
- Eliminate redundant or low-signal features
- Create interaction terms and derived metrics

**Guiding Principles:**
- Establish clear feature-to-target relationships
- Ensure features complement rather than duplicate existing signals
- Balance feature complexity with interpretability
- Maintain temporal validity to prevent data leakage

#### Phase 2: Model Development & Validation

**Modeling Approach:**
- Algorithm: Random Forest Classifier (ensemble learning method)
- Evaluation: Multi-metric performance assessment
- Validation: Rigorous cross-validation strategy

**Critical Considerations:**
- Problem framing: Classification vs. regression trade-offs
- Performance benchmarks: Establishing acceptable thresholds
- Evaluation framework: Selecting metrics aligned with business objectives
- Business impact quantification: Translating model performance into financial terms

**Required Deliverables:**
1. **Performance Analysis:** Detailed examination of model strengths and weaknesses
2. **Metric Justification:** Rationale for selected evaluation criteria
3. **Algorithm Assessment:** Comprehensive advantages/disadvantages analysis of Random Forest for this use case
4. **Performance Verdict:** Clear determination of model adequacy with supporting evidence
5. **Financial Impact Analysis (Bonus):** 
   - Quantification of potential cost savings from discount strategy
   - ROI calculations for model deployment
   - Documentation of underlying assumptions and sensitivities

---

### Task 4: Executive Presentation & Strategic Recommendations

**Objective:** Synthesize project findings into a compelling executive summary suitable for C-suite presentation.

**Strategic Framework:**
- **Key Metric Identification:** Determine the single most impactful finding
- **Technical Depth Calibration:** Balance detail with executive accessibility
- **Business Impact Articulation:** Quantify bottom-line financial implications
- **Recommendation Validation:** Apply "so what?" test to ensure actionable insights

**Deliverable:** Executive slide deck summarizing insights, model performance, and strategic recommendations.

---

---

## Key Findings

*[This section will be populated upon completion of analysis with:]*
- *Primary drivers of customer churn*
- *Validation/refutation of price sensitivity hypothesis*
- *Model performance metrics and business impact*
- *Strategic recommendations for retention strategy*

---

---

## Project Methodology

### 1. Data Understanding & Preparation
- Comprehensive data profiling and quality assessment
- Missing value imputation strategies
- Outlier detection and treatment
- Feature encoding and transformation

### 2. Exploratory Analysis
- Univariate and multivariate analysis
- Correlation analysis and feature relationships
- Churn rate analysis across customer segments
- Price sensitivity evaluation

### 3. Feature Engineering
- Domain-driven feature creation
- Temporal feature extraction
- Interaction term development
- Feature selection and dimensionality reduction

### 4. Model Development
- Baseline model establishment
- Random Forest implementation
- Hyperparameter optimization
- Cross-validation strategy

### 5. Model Evaluation
- Performance metric calculation (Accuracy, Precision, Recall, F1, AUC-ROC)
- Confusion matrix analysis
- Feature importance ranking
- Business impact quantification

---

## Results & Business Impact

*[To be completed - will include:]*
- Model performance metrics
- Feature importance rankings
- Financial impact projections
- Actionable retention strategies
- Discount strategy effectiveness analysis

---

## Future Enhancements

- Incorporate additional data sources (competitor pricing, market trends)
- Experiment with advanced algorithms (XGBoost, Neural Networks)
- Develop customer lifetime value (CLV) predictions
- Build real-time churn prediction API
- Create interactive dashboard for stakeholder monitoring

---

## Contributing

This is an individual project completed as part of the BCG Virtual Experience Program. However, suggestions and feedback are welcome.

---

## License

This project is for educational purposes as part of the BCG X Virtual Experience Program.

---

## Author

**[Karan Kumar]**  
Data Science Enthusiast

---

## Acknowledgments

- **BCG X** for providing the Virtual Experience Program framework
- **PowerCo** (fictional client) for the business case scenario
- **Forage** for hosting the virtual program platform


