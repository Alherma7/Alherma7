### Hi there! 👋 Welcome to my GitHub profile

Here you can find a selection of my most notable projects, organized by my core areas of expertise in Artificial Intelligence and Data Science.

---

### 🧠 Deep Learning
Projects focused on deep neural networks, natural language processing, and advanced architectures.
* [-contradictory-my-dear-watson](https://github.com/Alherma7/-contradictory-my-dear-watson) - Multilingual Natural Language Inference (NLI) for 100+ languages with Transformers (Kaggle): from a multilingual BERT baseline (~66% val accuracy) to a fine-tuned `xlm-roberta-large-xnli` (93.0% val, 0.926 public leaderboard accuracy).
* [R.O.A.D.-Barbados-Historic-Handwriting](https://github.com/Alherma7/R.O.A.D.-Barbados-Historic-Handwriting) - Handwritten text transcription of 17th-century Barbados legal documents for the Zindi "R.O.A.D." challenge; final pipeline is a 3-model deep-ensemble CRNN + CTC beam search + character n-gram language model (leaderboard score 0.845943, project closed).
* [RSNA_Knee_Abnormality_Detection](https://github.com/Alherma7/RSNA_Knee_Abnormality_Detection) - Multi-finding knee MRI classification (12 findings) for the RSNA Kaggle competition: a fine-tuned DINOv2-small with per-finding attention over 18 MRI series slices, trained on 58 expert-labeled studies plus ~4,350 studies soft-labeled from radiology reports by a public LLM label table (final private macro ROC-AUC 0.837, rank #4958/6,425). [Project write-up](https://alherma7.github.io/RSNA_Knee_Abnormality_Detection/) comparing it with the winning solutions: labels and input resolution were the gap.
* [DaT_Parkinson](https://github.com/Alherma7/DaT_Parkinson) - Dopamine-transporter SPECT scan classification (normal/abnormal) for DrivenData's DaT Parkinson's Challenge: a per-subject-centered 3D CNN blended with a ComBat-harmonized classical baseline, calibrated in logit space (final leaderboard log loss 0.3436, AUROC 0.9226, rank #160/1009). [Project write-up](https://alherma7.github.io/DaT_Parkinson/) with the full "what worked / what didn't" analysis.


### 👁️ Computer Vision
Models and applications oriented toward image and video processing, analysis, and understanding.
* [SpikeYOLO-jellyfish](https://github.com/Alherma7/SpikeYOLO-jellyfish) - Fork of BICLab's SpikeYOLO (spiking neural network object detector) adapted to jellyfish species detection on RGB video, using spike-rate/delta-modulation encoding via snntorch.
* [LOCS_Turtle_Face_Detection](https://github.com/Alherma7/LOCS_Turtle_Face_Detection) - Bounding-box detection of sea turtle facial scales for the Zindi "Local Ocean Conservation" challenge: a ConvNeXt-Tiny regressor trained with GIoU loss at 512 then 1024 px (public leaderboard IoU 0.894).

### 📊 Machine Learning & Data Analysis
Traditional machine learning algorithms, exploratory data analysis, and predictive models.
* [claude-usage-analytics](https://github.com/Alherma7/claude-usage-analytics) - Analytics platform for Claude Code telemetry: ingests raw JSONL event logs into a SQLite star schema and serves a multi-page Streamlit dashboard for executive and engineering-lead audiences (technical-interview take-home).
* [Financial_Stress_Prediction](https://github.com/Alherma7/Financial_Stress_Prediction) - LightGBM model predicting mobile money customer liquidity stress from 6-month transaction history, with trend feature engineering, stratified K-Fold CV, and probability calibration (Zindi challenge).
* [Climate_Risk_Health](https://github.com/Alherma7/Climate_Risk_Health) - Predicting whether a recorded death is climate-sensitive from mortality records and historical climate/environmental features (CHIRPS rainfall, ERA5 temperature, MODIS NDVI, SRTM elevation/slope), with spatially grouped cross-validation (Zindi challenge).
* [Tanzania_Tourism_Classification](https://github.com/Alherma7/Tanzania_Tourism_Classification) - Predicting a tourist's expenditure cost category (6 classes) from Tanzania NBS survey data with a tuned HistGradientBoosting model, Stratified 5-fold CV, and randomized hyperparameter search (Zindi/AI4D challenge, leaderboard Log Loss 1.0700).
* [Step_Ahead_Drought](https://github.com/Alherma7/Step_Ahead_Drought) - Forecasting next-month global Total Water Storage (GRACE-derived, 1° grid) from TWS/SPEI/soil-moisture history, with mask-aware validation, spatial-neighbourhood and temporal-anchor feature engineering, and a HistGradientBoosting model with native missing-value handling (Zindi/ITU challenge, leaderboard RMSE 0.7538, in progress).

### 🎨 Data Visualization
Projects turning real datasets into visual, art-inspired representations.
* [moma-data-art](https://github.com/Alherma7/moma-data-art) - MoMA collection data rendered as charts styled after the museum's own paintings (Mondrian, Picasso, Matisse), where each painting's own hand-digitized geometry becomes the container for the real data, revealed on hover.

### 🤖 Agents & Simulation
Autonomous agents/policies that act inside a simulated environment, evaluated through gameplay rather than a fixed dataset.
* [AI-agent-Kaggriculture](https://github.com/Alherma7/AI-agent-Kaggriculture) - Turn-based farming economy agent for Kaggle's "Kaggriculture" simulation competition: a hand-coded rule-based bot managing crops, livestock, hired hands and a shared market against an opponent agent (final rank #6448/10,148). [Project write-up](https://alherma7.github.io/AI-agent-Kaggriculture/) on why the winners used imitation learning and RL instead.

---

### 🛠️ Tech Stack & Tools

**Languages & Databases:**
<p>
  <img src="https://skillicons.dev/icons?i=python,postgres" alt="Languages & Databases" />
</p>

**AI, Machine Learning & Computer Vision:**
<p>
  <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,opencv,scikitlearn,huggingface,pandas,numpy" alt="AI & ML" />
</p>

**Tools & Environment:**
<p>
  <img src="https://skillicons.dev/icons?i=git,github,docker,vscode" alt="Tools" />
</p>
