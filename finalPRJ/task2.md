
🏗️ Task 2: Feature Engineering & Preprocessing

[ ] 2.1 Train/Test Split

Split the data into Train and Test sets using a specific ratio (e.g., 80/20) *before* any preprocessing to prevent data leakage.

Use `stratify=y` to maintain the proportions of the imbalanced target classes.

[ ] 2.2 Cleaning and Scaling

Handle missing data (if any) by fitting the imputer/transformer *only* on the Train set.

Encode categorical variables (e.g., One-Hot Encoding for nominal variables and Ordinal Encoding for ordinal variables).

Scale numerical features using `StandardScaler` (apply `.fit_transform()` on the Train set and `.transform()` on the Test set).

[ ] 2.3 Creation of Meaningful Financial Features

Construct relevant credit ratios based on domain knowledge (e.g., installment amounts or loan amounts relative to duration, or composite indicators of financial behavioral stability).

[ ] 🎯 Expected Deliverables for Task 2:

A report detailing the handling of missing data and the rationale behind the chosen encoding methods for variables.

Introduction of at least 1–2 newly engineered features, including their mathematical formulas and a justification for their impact on risk.

Analysis and identification of 3 key features that offer the greatest power in distinguishing between "good" (reliable) and "bad" (defaulting) borrowers. 