# ML4SCI DeepLense Evaluation Tasks

This repository contains the solutions for the **DeepLense Evaluation Tests** organized by **CERN's ML4SCI group**. The tasks include:

- ✅ **Common Test I**: Multi-Class Classification
- ✅ **Specific Test II**: Lens Finding

---

## 🔧 Requirements

Before running the notebooks, make sure to install the required Python packages using:
pip install -r requirements.txt

Python 3.7+ and PyTorch are required for both tasks.

## 📘 How to Run

1. **Clone the Repository**
   - git clone https://github.com/CRS5226/ml4_sci.git
   - cd ml4_sci

## Update Dataset Paths

Download the respective datasets provided in the test description. Update the paths in the notebooks accordingly:

- **For Task I**: Update image and CSV file paths.
- **For Task II**: Update the path to `train_lenses/`, `train_nonlenses/`, `test_lenses/`, and `test_nonlenses/` in the notebook.

## Run Each Cell in the Notebook

Open the notebooks in Jupyter or VSCode and execute each cell sequentially after updating the paths. Both notebooks are organized with clear sections for:

- Dataset loading
- Model architecture (e.g., ResNet18)
- Training loop
- Evaluation (accuracy, confusion matrix, ROC curves, etc.)
- Final prediction and visualization
