# Refugee_study
Coping Strategies and Resilience Among Displaced Youth in Bidibidi Settlement

****Data provided upon reasonable request***

🧩 Problem Statement / Background

Displaced youth in refugee settlements face immense psychological stressors. This study investigates how different coping mechanisms—problem-focused, emotion-focused, social support, and spiritual practices—predict resilience among adolescents and young adults in Bidibidi, Uganda. The goal is to identify actionable psychosocial levers for improving mental health in protracted displacement contexts.

⸻

🛠️ Methods Used
	•	Tool: R (v4.4.1)
	•	Packages: MASS, brant, car, ordinal, ggplot2, sjPlot, among others
	•	Statistical Models:
	•	Proportional-odds ordinal logistic regression
	•	Brant test for proportionality assumption
	•	QR decomposition for rank diagnostics
	•	Variance Inflation Factor (VIF) for multicollinearity
	•	Data Management:
	•	Row-wise total scoring of five validated scales
	•	Categorical recoding for demographics
	•	Sample restricted to 108 participants with complete cases

⸻

📈 Key Findings
	•	Strongest predictors of resilience:
	•	Social Support Coping (OR = 1.44; p < 0.001)
	•	Spiritual Practices (OR = 1.15; p = 0.005)
	•	Non-significant predictors:
	•	Emotion-Focused Coping
	•	Problem-Focused Coping (positive trend)
	•	Vulnerability flag:
	•	Youth aged 25+ had significantly lower resilience (OR = 0.15; p = 0.003)

Visuals:
	•	📊 Figure 1: Forest plot of ORs and 95% CIs

	•	📈 Figure 2: Calibration plot showing excellent model reliability across all risk deciles


▶️ How to Run the Code (R)
	1.	Software Requirement:
	•	R version 4.4.1 or higher
	•	RStudio (recommended for IDE)
	2.	Install Required Packages (once): install.packages(c("MASS", "car", "brant", "ordinal", "ggplot2", "sjPlot"))

 	3.	Open & Run
	•	Open PCMR.Rmd in RStudio
	•	Click “Knit” to produce a full HTML report, or run chunks manually
	•	Ensure the dataset (likely named df2 or similar) is loaded correctly
	4.	Expected Outputs:
	•	Regression tables for ordinal logistic model
	•	Diagnostic results (Brant test, VIF)
	•	Descriptive summaries of all scales
	•	Forest and calibration plots for model interpretability
	5.	Data Notes:
	•	Data was cleaned and preprocessed in R
	•	All participants had complete scores on 5 coping/resilience scales
	•	Demographics recoded for analytic clarity (e.g., Age: 18–24 vs. 25+)



 
