# prompts
 Data Analysis Prompt Library
 A flexible set of prompt templates for any data analysis context (not limited to payments or accounting).
 These prompts cover problem definition, data exploration, cleaning, modeling, visualization, and
 stakeholder communication. Replace placeholders like 
[DATA_SOURCE] , 
[DATE_RANGE] , 
[METRIC] , 
[TOOL] .
 1) Problem Definition & Planning
 1.1 Define the Problem
 Summarize the business question: [describe question]. Identify data sources: 
[DATA_SOURCE]. What is the expected outcome and how will success be measured?
 1.2 Success Metrics
 Suggest 3–5 KPIs to track success for [business objective]. Include formula, 
owner, refresh frequency, and potential pitfalls.
 1.3 Analysis Plan
 Create a step-by-step plan to analyze data from [DATA_SOURCE]. Include tasks, 
tools ([TOOL]), dependencies, and estimated time.
 2) Data Collection & Preparation
 2.1 Data Inventory
 List tables/files in [DATA_SOURCE]. Document schema, primary keys, foreign keys, 
data types, freshness, and quality notes.
 2.2 Cleaning Steps
 1
Provide a Python/Pandas or SQL script to clean the dataset: handle missing 
values, outliers, duplicates, and type mismatches.
 2.3 Data Transformation
 Generate transformation steps to prepare [DATA_SOURCE] for analysis: feature 
engineering, normalization, aggregation, or encoding.
 3) Exploratory Data Analysis (EDA)
 3.1 Overview
 Perform EDA on [DATA_SOURCE]. Show key statistics, distributions, correlations, 
and missing data summary.
 3.2 Anomaly Detection
 Identify anomalies in [DATA_SOURCE] using z-score and IQR methods. Visualize top 
10 anomalies.
 3.3 Segmentation Analysis
 Segment the dataset by [dimension] (e.g., region, product, customer type) and 
show key patterns or differences.
 4) Modeling & Prediction
 4.1 Statistical Model
 Build a regression model to predict [target variable] using [features]. Provide 
coefficients and interpret them.
 4.2 Classification
 2
Train a classification model to categorize [target]. Show confusion matrix, 
accuracy, precision, recall, F1-score.
 4.3 Forecasting
 Generate a time series forecast for [METRIC] for the next [n] periods using 
ARIMA/Prophet.
 5) Visualization & Reporting
 5.1 Dashboard Design
 Design a dashboard layout to track [KPIs]. Include filters, charts, and drill
down options.
 5.2 Visual Storytelling
 Summarize the analysis insights visually with 3–5 key charts and a brief 
narrative for stakeholders.
 6) Root Cause Analysis (RCA)
 Perform RCA for a sudden change in [METRIC]. Segment by relevant dimensions, run 
5 Whys, and suggest corrective actions.
 7) Automation & Pipelines
 Generate a pipeline outline to extract, transform, and load (ETL) data from 
[SOURCE] into [DESTINATION]. Include schedule, failure alerts, and data 
validation steps.
 3
8) Communication & Documentation
 8.1 Executive Summary
 Create a one-page summary of findings: problem, methods, key insights, and next 
steps.
 8.2 Stakeholder Update
 Draft an email/Slack message to share analysis results with [stakeholders]. 
Include main findings, impact, and proposed actions.
 9) Continuous Improvement
 Suggest how to improve the dataset: additional fields, better sampling, or 
higher frequency.
 9.1 Monitoring Metrics
 Create a monitoring plan to track [METRIC] over time with automated alerts.
 10) Request Anything Else
 If given a sample dataset or schema, generate: cleaning script, EDA notebook, 
visualization, or predictive model with explanations.
 
