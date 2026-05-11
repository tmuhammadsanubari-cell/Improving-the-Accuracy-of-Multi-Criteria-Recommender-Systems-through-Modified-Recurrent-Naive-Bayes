# Improving the Accuracy of Multi-Criteria Recommender Systems through Modified Recurrent Naive Bayes and Random Forest

## 📋 Project Overview

This repository contains a comprehensive final project focused on enhancing the accuracy of **Multi-Criteria Recommender Systems (MCRS)** by implementing and comparing advanced machine learning algorithms. The primary approach uses a **Modified Recurrent Naive Bayes (RNB)** model combined with **Random Forest** techniques to optimize rating predictions across multiple criteria.

### Key Objectives
- Develop an improved multi-criteria recommender system
- Implement Modified Recurrent Naive Bayes algorithm
- Compare performance with Random Forest classifier
- Optimize rating prediction accuracy
- Evaluate on real-world datasets (OpenTable and ITMRec)

---

## 🎯 Methodology

### Algorithms Implemented
1. **Modified Recurrent Naive Bayes (RNB)**: Enhanced version of traditional Naive Bayes that captures sequential dependencies in user preferences
2. **Random Forest**: Ensemble learning method for robust rating prediction

### Datasets
- **OpenTable Dataset** (`opentable_cleaned.csv`): Restaurant rating data with multiple criteria
- **ITMRec Dataset** (`ratings.csv`): Multi-criteria rating dataset for comprehensive evaluation

---

## 📁 Repository Structure

```
.
├── README.md                          # Project documentation
├── MCRS_RNB_RF_Final (1).ipynb       # Main Jupyter Notebook with full implementation
├── opentable_cleaned.csv              # Cleaned OpenTable dataset
├── ratings.csv                        # Multi-criteria ratings dataset
```

### File Descriptions

| File | Description |
|------|-------------|
| `MCRS_RNB_RF_Final (1).ipynb` | Complete implementation including data preprocessing, model development, training, and evaluation |
| `opentable_cleaned.csv` | Restaurant ratings with multiple criteria from OpenTable platform |
| `ratings.csv` | Multi-criteria recommendation dataset for model validation |

---

## 🚀 Getting Started

### Prerequisites
- Python 3.7+
- Jupyter Notebook
- Required libraries:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/tmuhammadsanubari-cell/Improving-the-Accuracy-of-Multi-Criteria-Recommender-Systems-through-Modified-Recurrent-Naive-Bayes.git
cd Improving-the-Accuracy-of-Multi-Criteria-Recommender-Systems-through-Modified-Recurrent-Naive-Bayes
```

2. Install required dependencies:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook
```

4. Open `MCRS_RNB_RF_Final (1).ipynb` and run all cells

---

## 📊 Model Evaluation

### Performance Metrics
The models are evaluated using standard machine learning metrics:
- **Mean Absolute Error (MAE)**
- **F1 Score** 

### Datasets Used
- **OpenTable**: Real-world restaurant recommendation data
- **ITMRec**: Multi-dimensional rating dataset for comprehensive benchmarking

---

## 🔍 Key Features

✅ **Multi-Criteria Analysis**: Considers multiple rating dimensions (e.g., food, service, ambiance)  
✅ **Advanced Algorithms**: Implements Modified RNB and Random Forest approaches  
✅ **Comprehensive Evaluation**: Detailed performance comparison across metrics  
✅ **Real-World Data**: Uses authentic datasets for practical validation  
✅ **Well-Documented Code**: Clear implementation with explanations  

---

## 📈 Results

The project demonstrates:
- Improved prediction accuracy through the Modified Recurrent Naive Bayes approach
- Effective ensemble learning with Random Forest
- Comparative analysis highlighting the strengths of each algorithm
- Practical insights for implementing multi-criteria recommender systems

*Note: Detailed results and visualizations can be found in the Jupyter notebook*

---

## 💡 Usage

To use this project:

1. **Data Preparation**: Load and preprocess your datasets
2. **Model Training**: Train the Modified RNB and Random Forest models
3. **Evaluation**: Compare performance metrics
4. **Prediction**: Generate recommendations using the trained models

Refer to the notebook for step-by-step implementation details.

---

## 🤝 Contributing

Contributions are welcome! If you have suggestions for improvements or find issues, please feel free to:
- Open an issue
- Submit a pull request
- Contact the repository owner

---

## 📝 License

This project is open source and available for academic and research purposes.

---

## 👤 Author

**tmuhammadsanubari-cell**  
Final Project: Improving Multi-Criteria Recommender Systems

---

## 📚 References

- Naive Bayes Classification and its variants
- Ensemble Methods: Random Forest
- Multi-Criteria Recommender Systems Literature
- OpenTable and ITMRec Dataset Documentation

---

## 📧 Contact & Support

For questions or inquiries about this project, please open an issue on the GitHub repository.

**Last Updated**: 2026-05-11
