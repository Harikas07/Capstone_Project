# Capstone_Project
🧠 AI-Driven Multi modal data fusion for Early Cancer Diagnosis

📘 Overview

This research project aims to develop an AI-driven model that integrates clinical and genomic data from the MMIST-ccRCC dataset to predict early-stage clear cell renal cell carcinoma (ccRCC) characteristics and survival outcomes.

The focus is on multi-modal data fusion, specifically comparing:

Early fusion: combining clinical and genomic features before model training.

Late fusion: combining predictions from separate models trained on each modality.

The project demonstrates how integrating complementary data modalities improves prediction accuracy and interpretability compared to unimodal models.

🎯 Objectives

Train and evaluate machine learning models using clinical + genomic data.

Implement and compare early fusion and late fusion strategies.

Assess model performance with metrics such as Accuracy, Precision, Recall, F1-score, and AUC.

Visualize feature importance and modality contributions.

🧩 Dataset

Dataset Name: MMIST-ccRCC (Multi-Modal Imaging and Clinical Dataset for clear cell Renal Cell Carcinoma)

Data Used:

clinical.csv – patient demographics, lab results, and clinical features.

genomic_split.csv – gene expression and mutation data.

Note: Imaging data is excluded from this study per project scope adjustment.

Data Source:

Mota, Tiago et al. “MMIST-ccRCC: A Real-World Medical Dataset for the Development of Multi-Modal Systems.”

⚙️ Methodology
1. Data Preprocessing

Handle missing values and normalize features.

Encode categorical clinical variables.

Merge datasets on patient identifiers.

Split into training (70%), validation (15%), and test (15%) sets.

2. Modeling Approaches

Baseline Models: Logistic Regression, Random Forest.

Deep Learning Models: MLP architectures for each modality.

Fusion Strategies:

Early Fusion: Concatenate feature spaces from both modalities.

Late Fusion: Combine predictions from modality-specific models using ensemble averaging or meta-learning.

3. Evaluation Metrics

Accuracy

Precision / Recall / F1-Score

AUC (Area Under the ROC Curve)

Confusion Matrix and ROC Curve Visualization

📊 Expected Outcomes

Cleaned and preprocessed multi-modal dataset.

Trained early and late fusion models.

Comparison charts showing performance improvements.

Visualizations of feature importance and fusion contributions.

Insights on model interpretability and clinical applicability.
