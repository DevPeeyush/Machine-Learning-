Feature Engineering
│
├── 1. Feature Construction (Create NEW Features)
│   │
│   ├── A. Mathematical Features
│   │   ├── BMI = Weight / Height²
│   │   ├── Profit = Revenue - Cost
│   │   ├── Ratio Features
│   │   └── Percentage Features
│   │
│   ├── B. Aggregation Features
│   │   ├── Total Purchase
│   │   ├── Average Spending
│   │   └── Count Features
│   │
│   ├── C. Date-Time Features
│   │   ├── Year
│   │   ├── Month
│   │   ├── Day
│   │   ├── Weekday
│   │   ├── Hour
│   │   └── Season
│   │
│   ├── D. Interaction Features
│   │   ├── Age × Salary
│   │   ├── Polynomial Features
│   │   └── Cross Features
│   │
│   ├── E. Domain-Specific Features
│   │   ├── Medical Risk Score
│   │   ├── Credit Score
│   │   └── Customer Lifetime Value
│   │
│   └── Goal:
│       Create smarter and more informative features
│
├── 2. Feature Transformation (Modify Existing Features)
│   │
│   ├── A. Scaling
│   │   ├── Normalization
│   │   ├── Standardization
│   │   └── Robust Scaling
│   │
│   ├── B. Encoding Categorical Data
│   │   ├── Label Encoding
│   │   ├── One Hot Encoding
│   │   ├── Ordinal Encoding
│   │   ├── Frequency Encoding
│   │   └── Target Encoding
│   │
│   ├── C. Mathematical Transformations
│   │   ├── Log Transformation
│   │   ├── Square Root Transformation
│   │   ├── Reciprocal Transformation
│   │   └── Power Transformation
│   │
│   ├── D. Binning / Discretization
│   │   ├── Equal Width Binning
│   │   ├── Equal Frequency Binning
│   │   └── Custom Binning
│   │
│   └── Goal:
│       Make data more suitable for ML algorithms
│
├── 3. Feature Extraction (Compress Information)
│   │
│   ├── A. Dimensionality Reduction
│   │   ├── PCA
│   │   ├── LDA
│   │   ├── ICA
│   │   └── SVD
│   │
│   ├── B. Deep Learning Extraction
│   │   ├── Autoencoders
│   │   ├── CNN Features
│   │   └── Embeddings
│   │
│   ├── C. Text Feature Extraction
│   │   ├── Bag of Words
│   │   ├── TF-IDF
│   │   ├── Word2Vec
│   │   ├── GloVe
│   │   └── BERT Embeddings
│   │
│   ├── D. Image Feature Extraction
│   │   ├── Edge Detection
│   │   ├── Shape Features
│   │   ├── Texture Features
│   │   └── CNN Embeddings
│   │
│   └── Goal:
│       Reduce dimensions while preserving important information
│
├── 4. Feature Selection (Choose Best Features)
│   │
│   ├── A. Filter Methods
│   │   ├── Correlation
│   │   ├── Chi-Square Test
│   │   ├── ANOVA
│   │   └── Mutual Information
│   │
│   ├── B. Wrapper Methods
│   │   ├── Forward Selection
│   │   ├── Backward Elimination
│   │   ├── Stepwise Selection
│   │   └── Recursive Feature Elimination (RFE)
│   │
│   ├── C. Embedded Methods
│   │   ├── Lasso Regression
│   │   ├── Ridge Regression
│   │   ├── ElasticNet
│   │   └── Tree-Based Importance
│   │
│   └── Goal:
│       Keep only important and relevant features
│
├── 5. Handling Missing Values
│   │
│   ├── Remove Rows
│   ├── Remove Columns
│   ├── Mean Imputation
│   ├── Median Imputation
│   ├── Mode Imputation
│   ├── KNN Imputation
│   ├── Forward Fill
│   └── Backward Fill
│
├── 6. Handling Outliers
│   │
│   ├── Remove Outliers
│   ├── Capping
│   ├── Winsorization
│   ├── Log Transformation
│   └── Robust Scaling
│
├── 7. Text Feature Engineering
│   │
│   ├── Tokenization
│   ├── Stopword Removal
│   ├── Stemming
│   ├── Lemmatization
│   ├── N-Grams
│   └── Vectorization
│
├── 8. Time Series Feature Engineering
│   │
│   ├── Lag Features
│   ├── Rolling Mean
│   ├── Rolling Std
│   ├── Expanding Window
│   ├── Seasonality Features
│   └── Trend Features
│
└── 9. Image Feature Engineering
    │
    ├── Resizing
    ├── Normalization
    ├── Edge Detection
    ├── Histogram Features
    ├── Texture Extraction
    └── CNN Features