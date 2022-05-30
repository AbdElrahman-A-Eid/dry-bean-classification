# Dry Beans Classification V2 | Kaggle Competition

Unranked Competition on [Kaggle](https://www.kaggle.com/competitions/dry-beans-classification-iti-ai-pro-intake02) held by ITI AI-Pro.

## Introduction
You are given a set of features extracted from the shape of the beans in images and it's required to predict the type of each bean. There are 7 bean types in this dataset.

## Data Fields
The dataset consists of features describing the shape of the bean and you're required to predict it's type.
- ID - an ID for this instance
- Area - (A), The area of a bean zone and the number of pixels within its boundaries.
- Perimeter - (P), Bean circumference is defined as the length of its border.
- MajorAxisLength - (L), The distance between the ends of the longest line that can be drawn from a bean.
- MinorAxisLength - (l), The longest line that can be drawn from the bean while standing perpendicular to the main axis.
- AspectRatio - (K), Defines the relationship between L and l.
- Eccentricity - (Ec), Eccentricity of the ellipse having the same moments as the region.
- ConvexArea - (C), Number of pixels in the smallest convex polygon that can contain the area of a bean seed.
- EquivDiameter - (Ed), The diameter of a circle having the same area as a bean seed area.
- Extent - (Ex), The ratio of the pixels in the bounding box to the bean area.
- Solidity - (S), Also known as convexity. The ratio of the pixels in the convex shell to those found in beans.
- Roundness - (R), Calculated with the following formula: (4piA)/(P^2)
- Compactness - (CO), Measures the roundness of an object: Ed/L
- ShapeFactor1 - (SF1)
- ShapeFactor2 - (SF2)
- ShapeFactor3 - (SF3)
- ShapeFactor4 - (SF4)
- y - the class of the bean. It can be any of BARBUNYA, SIRA, HOROZ, DERMASON, CALI, BOMBAY, and SEKER.

## Libraries Used
- SciKitLearn:
  - Models: `SVC`, `TSNE`
  - Metrics: `classification_report`, `accuracy_score`, `average_precision_score`, `f1_score`
  - Preprocessing: `LabelEncoder`, `RobustScaler`
  - Model Selection: `train_test_split`
- NumPy
- Pandas
- SciPy
- Visualization:
   - `matplotlib.pyplot`
   - `seaborn`
   - `plotly`

## Dataset
- Observations:
  - Training: 10834 
  - Test: 2709
- Features: 16

## Exploratory Data Analysis (EDA)
- Numeric Analysis (Duplicates, Null Values, Skewness, etc.)
- Visual Analysis (Boxplots, Histograms, Heatmaps, TSNE, etc.)

## Data Preprocessing
- Training \ Validation Split
- Normalization

## Model Training
Model Chosen: Support Vector Classifier

## Model Evaluation
Metrics Used:
- F1 Score
- Recall
- Precision

## Team Members
- [AbdElrahman Eid](https://github.com/AbdElrahman-A-Eid)
- [Ahmed Azzam](https://github.com/AhmedAzzam99)
- [Ahmed Zakaria](https://github.com/Ahmed-Zakaria96)
- [Mohamed Nasser](https://github.com/Mohamed-AN)
- [Mostafa Nafie](https://github.com/Mostafa-Nafie)
