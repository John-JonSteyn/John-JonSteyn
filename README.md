<p align="center">
  <a href="https://www.linkedin.com/in/john-jonsteyn/" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/%20-grey?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik01IDNhMiAyIDAgMSAxIDAgNCAyIDIgMCAwIDEgMC00TTMgOWg0djEySDN6TTEwIDloNHYyYzEtMyA3LTMgNyAzdjdoLTR2LTZjMC0zLTMtMy0zIDB2NmgtNHoiLz48L3N2Zz4%3D" alt="" /><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge" alt="LinkedIn" /></a>
  <a href="https://www.instagram.com/mrjohnjonsteyn/" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/%20-grey?style=for-the-badge&logo=instagram&logoColor=white" alt="" /><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge" alt="Instagram" /></a>
  <a href="https://www.threads.com/@mrjohnjonsteyn" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/%20-grey?style=for-the-badge&logo=threads&logoColor=white" alt="" /><img src="https://img.shields.io/badge/Threads-000000?style=for-the-badge" alt="Threads" /></a>
  <a href="https://x.com/JohnJon_Steyn" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/%20-grey?style=for-the-badge&logo=x&logoColor=white" alt="" /><img src="https://img.shields.io/badge/X%20%28Twitter%29-000000?style=for-the-badge" alt="X (Twitter)" /></a>
  <a href="https://www.youtube.com/@John-JonSteyn" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/%20-grey?style=for-the-badge&logo=youtube&logoColor=white" alt="" /><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge" alt="YouTube" /></a>  
</p>

---

## Profile

I’m a software engineer with a Bachelor of Science in Computing and currently pursuing a Master of Science in Artificial Intelligence.

My interests span the foundations of computing, cognitive science, neuroscience and artificial intelligence. I’m interested in how computation works, how brains process information and learn, and how insights from these fields build on one another to explain and develop intelligent systems.

I explore these subjects through software projects, independent research and explainer videos. My focus is on understanding the underlying principles and showing how they connect to the algorithms, models and systems built from them.

---

## Featured Research

### [Alzheimer's Brain-Age Representation Analysis](https://github.com/John-JonSteyn/AlzheimersBrainAgeRepresentationAnalysis)

A reproducible structural MRI study examining how brain-age representation shapes Alzheimer’s diagnostic and cognitive utility. The analysis compares scalar whole-brain gaps, anatomically resolved regional gaps, and raw FastSurfer morphometry within a CN-trained, subject-level out-of-fold framework, supported by demographic and structural baselines and sensitivity analyses for age-bias correction and reconstruction quality. The findings show that preserving regional structure recovers diagnostic and cognitive information lost through scalar compression.

<p align="center">
  <a href="https://github.com/John-JonSteyn/AlzheimersBrainAgeRepresentationAnalysis">
    <img
      src="https://raw.githubusercontent.com/John-JonSteyn/AlzheimersBrainAgeRepresentationAnalysis/main/Outputs/Figures/BrainAge/figure3_calibration_curves.png"
      width="520"
      alt="Calibration curves comparing scalar, regional, and raw brain-age representations"
    />
  </a>
</p>

### [Parkinson's Drawing Model Comparison](https://github.com/John-JonSteyn/ParkinsonsDrawingModelComparison)

A reproducible participant-level study comparing HOG-based support vector machines with ResNet18 trained from scratch and fine-tuned from ImageNet-pretrained weights on NewHandPD drawings. The analysis uses repeated nested cross-validation, duplicate-aware participant partitions, matched neural training settings, and learning curves to examine the contribution of pretraining. The classical pipeline achieves the highest observed mean balanced accuracy, while the pretraining comparison changes with model-selection procedure and training-set size.

<p align="center">
  <a href="https://github.com/John-JonSteyn/ParkinsonsDrawingModelComparison">
    <img
      src="https://raw.githubusercontent.com/John-JonSteyn/ParkinsonsDrawingModelComparison/main/figures/occlusion_parkinsons_correct.png"
      width="680"
      alt="Occlusion sensitivity analysis of a correctly classified drawing from a participant with Parkinson's disease"
    />
  </a>
</p>

### [Academic Literature Planning Agent](https://github.com/John-JonSteyn/AcademicLiteraturePlanningAgent)

A Python planning-agent system for auditable academic literature discovery, evidence organisation, and research synthesis. The system receives a research goal, creates a traceable plan, retrieves scholarly metadata, scores credibility, extracts claims and evidence links, detects contradictions and subtopics, and exports Markdown, JSON, SQLite, and execution-log evidence through a supervisor-led blackboard architecture.

<p align="center">
  <img src="https://raw.githubusercontent.com/John-JonSteyn/AcademicLiteraturePlanningAgent/main/Output/ReadmeFigures/BlackboardComposition.svg" width="520" alt="Academic literature planning agent blackboard composition">
</p>

### [Rule-Based Chatbot Comparison](https://github.com/John-JonSteyn/RuleBasedChatbotComparison)

A comparative study of Python and Rust implementations of a retrieval-based chatbot, focused on performance, maintainability, and implementation trade-offs under matched conditions.

<p align="center">
  <img src="https://raw.githubusercontent.com/John-JonSteyn/RuleBasedChatbotComparison/main/Results/Bench/Plots/scalability_wall_vs_decksize_topic.png" width="420" alt="Chatbot scalability plot">
</p>

### [Financial Distress Trend Modelling](https://github.com/John-JonSteyn/FinancialDistressTrendModelling)

A longitudinal machine-learning pipeline over SEC filings designed to model how financial distress emerges over time, producing temporal risk trajectories and company-level explanatory signals for early warning and monitoring.

<p align="center">
  <img src="https://raw.githubusercontent.com/John-JonSteyn/FinancialDistressTrendModelling/main/docs/examples/company_report_elevated_risk.png" width="420" alt="Financial distress report example">
</p>

---

## Selected Projects

### [Brain Tumour MRI Classification](https://github.com/John-JonSteyn/BrainTumorMRIScikitLearnClassification)

A classical machine-learning baseline for classifying brain MRI images into tumour categories using HOG features and SVMs. Includes preprocessing, training, evaluation, error analysis, and ethical discussion, with a focus on reproducible modelling in a clinically relevant imaging setting.

<p align="center">
  <img src="https://raw.githubusercontent.com/John-JonSteyn/BrainTumorMRIScikitLearnClassification/main/reports/figures/misclassified_grid.png" width="520" alt="Misclassified brain MRI examples">
</p>

### [Airbnb Spatial Price Modelling](https://github.com/John-JonSteyn/AirBNBSpatialPriceModelling)

A collaborative analysis of New York City Airbnb asking prices using listing, host, review and spatial features. The project compares three regression models, identifies market segments through K-means clustering, and maps neighbourhood prediction error. Random Forest achieved a held-out MAE of USD 42.79. My contributions included team formation, report visualisations, results writing and analytical review.

<p align="center">
  <a href="https://github.com/John-JonSteyn/AirBNBSpatialPriceModelling">
    <img
      src="https://raw.githubusercontent.com/John-JonSteyn/AirBNBSpatialPriceModelling/main/figures/figure_03_market_segments.png"
      width="520"
      alt="Geographic distribution of three Airbnb market segments across New York City"
    />
  </a>
</p>

### [Diabetes Risk Factor Analysis](https://github.com/John-JonSteyn/DiabetesRiskFactorAnalysis)

A reproducible R-based analysis of a diabetes dataset, examining how glucose, BMI, age, pregnancies, and hereditary factors relate to diabetes outcome. The repository covers data auditing, cleaning, descriptive analysis, hypothesis testing, regression modelling, and automated generation of statistical outputs and figures.

<p align="center">
  <img src="https://raw.githubusercontent.com/John-JonSteyn/DiabetesRiskFactorAnalysis/main/plots/correlation_matrix_heatmap.png" width="420" alt="Diabetes correlation matrix heatmap">
</p>

### [Lifestyle & Sleep Pattern Analysis](https://github.com/John-JonSteyn/LifestyleAndSleepPatternAnalysis)

An exploratory analysis of sleep, stress, physiology, and lifestyle variables as an interacting system. The notebook focuses on baselines, correlations, anchored visualisations, and hypothesis generation, with an emphasis on reproducible analysis and cautious interpretation.

<p align="center">
  <img src="https://raw.githubusercontent.com/John-JonSteyn/LifestyleAndSleepPatternAnalysis/main/outputs/plots/pearson_correlation_matrix.png" width="420" alt="Lifestyle and sleep correlation matrix">
</p>
