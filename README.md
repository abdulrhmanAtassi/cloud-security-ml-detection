# Cloud Security Threat Detection using Machine Learning

A practical ML framework for detecting security threats in cloud environments with focus on realistic performance evaluation.

## Overview
This research addresses the gap between academic ML studies (claiming 99%+ accuracy) and real-world deployment by implementing rigorous data leakage detection.

## Key Results
- **Conservative Random Forest**: 93.74% accuracy (realistic performance)
- **Detected and removed 52 leaky features** from original 79 features
- **Processed 1.2M+ network flow records** from CSE-CIC-IDS2018 dataset

## Technologies Used
- Python, scikit-learn, pandas, numpy
- SMOTE for class balancing
- Multiple ML algorithms (Random Forest, SVM, Logistic Regression)

## Files
- `cloud_security_analysis.ipynb` - Complete analysis and model training
- `research_paper.pdf` - Full academic paper
- `requirements.txt` - Required Python packages

## Usage
```python
# Install requirements
pip install -r requirements.txt

# Run the Jupyter notebook
jupyter notebook cloud_security_analysis.ipynb
```

## Methodology
1. Data preprocessing and quality audit
2. 5-stage data leakage detection
3. Conservative model training
4. Realistic performance evaluation

## Citation
Research conducted at Princess Sumaya University for Technology, Amman, Jordan

## Contact
Abdulrhman Atassi - a.atassi2@icloud.com
