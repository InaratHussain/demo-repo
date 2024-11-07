# 🧠 Autism Detection in Toddlers using Bayesian Network


## 📖 Overview

Early detection of **Autism Spectrum Disorder (ASD)** is crucial for providing children with the resources and support they need to thrive. This project leverages a **Bayesian Network** to predict autism likelihood in toddlers using a probabilistic model based on behavioral and developmental data. By capturing the dependencies between specific attributes, this classifier can provide a **highly interpretable** and **accurate** autism screening tool.

## ✨ Features

- 🔍 **Bayesian Network Classifier**: Uses a probabilistic approach to assess autism likelihood based on key attributes.
- 🔧 **Data Preprocessing**: Cleans and prepares data for optimal model performance.
- 📊 **Predictive Analysis**: Outputs a probability-based classification for each toddler.
- 🔎 **Explainable Results**: Highlights key factors impacting autism prediction for transparency and insights.

## 📁 Dataset

The model is trained on a dataset specifically designed for **autism screening in toddlers**, containing a range of behavioral indicators associated with ASD.

## 🛠️ Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/autism-detection-bayesian-network.git
   cd autism-detection-bayesian-network
   ```

2. **Install required packages**:
   ```bash
   pip install -r requirements.txt
   ```

## 🚀 Usage

1. **Run the model**:
   ```bash
   python autism_detection.py
   ```
   This script will load the dataset, train the Bayesian classifier, and output the classification results along with associated probabilities.

2. **Evaluate the model**:
   Model performance is assessed using metrics like **accuracy, precision, and recall**.

## 📂 Project Structure

```
├── autism_detection.py       # Main script for model training and prediction
├── data/                     # Directory containing the autism dataset
├── README.md                 # Project description and usage guide
└── requirements.txt          # Dependencies for the project
```

## 🧬 Methodology

### Step 1: Data Collection
- Import and explore the dataset to understand feature distributions and correlations.

### Step 2: Data Preprocessing
- Clean, handle missing values, and normalize data as needed.

### Step 3: Modeling with Bayesian Network
- Build and train the Bayesian classifier based on conditional probabilities.

### Step 4: Evaluation
- Use metrics like **accuracy, precision, and recall** to assess model performance.

### Step 5: Interpretation
- Provide insights on key attributes impacting the likelihood of autism.

## 📈 Results

This Bayesian model provides **probabilistic predictions** that emphasize **interpretability**, allowing users to understand the impact of different attributes on autism detection.

## 🤝 Contributions

Contributions are welcome! If you have suggestions for improving the model or adding features, feel free to open a pull request. Feedback and issue reports are also appreciated.

## 📜 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.


