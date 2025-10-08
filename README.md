# Create a README file for the 5th experiment
readme_text = """# Practical Experiment: Cross-Validation and Bias–Variance Analysis

A practical notebook demonstrating the impact of cross-validation strategies 
on model performance and the bias–variance trade-off, 
using executable examples in Google Colab.

## 📄 Notebook File
classic_ml_lab_05_cross_validation_bias_variance.ipynb
"""

# Save the README file
with open("README.md", "w", encoding="utf-8") as f:
    f.write(readme_text)

print("README.md created successfully!")
