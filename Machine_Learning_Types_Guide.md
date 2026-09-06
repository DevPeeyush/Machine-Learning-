# Machine Learning Types – Tree Diagram and Explanation

# Machine Learning
```text
Machine Learning
│
├── 1. Supervised Learning
│   ├── Regression
│   └── Classification
│
├── 2. Unsupervised Learning
│   ├── Clustering
│   ├── Association
│   └── Dimensionality Reduction
│
├── 3. Semi-Supervised Learning
│   ├── Small Labeled Data
│   └── Large Unlabeled Data
│
└── 4. Reinforcement Learning
    ├── Agent
    ├── Environment
    ├── Rewards
    └── Policy Learning
```

## 1. Supervised Learning
**Definition:** The model learns from labeled data (input + correct output).

### Types
- **Regression** → Predicts continuous values.
  - Example: House price prediction.
- **Classification** → Predicts categories/classes.
  - Example: Spam email detection.

### Common Algorithms
- Linear Regression
- Logistic Regression
- Decision Trees
- Random Forest
- Support Vector Machine (SVM)
- Neural Networks

---

## 2. Unsupervised Learning
**Definition:** The model learns from data without labels.

### Types
- **Clustering**
  - Groups similar data points together.
  - Example: Customer segmentation.
- **Association**
  - Finds relationships between items.
  - Example: Market basket analysis.
- **Dimensionality Reduction**
  - Reduces the number of features.
  - Example: Data visualization and compression.

### Common Algorithms
- K-Means
- Hierarchical Clustering
- DBSCAN
- Apriori
- PCA (Principal Component Analysis)

---

## 3. Semi-Supervised Learning
**Definition:** Uses a small amount of labeled data and a large amount of unlabeled data.

### Why Use It?
- Labeling data is expensive.
- Unlabeled data is easy to collect.

### Example
- Image recognition with only a few labeled images and many unlabeled images.

### Common Methods
- Self-Training
- Label Propagation
- Pseudo-Labeling

---

## 4. Reinforcement Learning
**Definition:** An agent learns by interacting with an environment and receiving rewards or penalties.

### Components
- Agent
- Environment
- Action
- State
- Reward

### Examples
- Game-playing AI
- Self-driving cars
- Robotics

### Common Algorithms
- Q-Learning
- Deep Q Networks (DQN)
- SARSA
- Policy Gradient Methods

---

# Quick Comparison Table

| Type | Uses Labels? | Goal | Example |
|--------|-------------|--------|---------|
| Supervised Learning | Yes | Predict output | House price prediction |
| Unsupervised Learning | No | Discover patterns | Customer grouping |
| Semi-Supervised Learning | Partially | Improve learning with few labels | Image classification |
| Reinforcement Learning | Reward-based | Learn actions | Game AI |

---

# Easy Memory Trick

- **Supervised** = Teacher gives answers.
- **Unsupervised** = Find patterns yourself.
- **Semi-Supervised** = Few answers, many unknowns.
- **Reinforcement** = Learn by rewards and penalties.
