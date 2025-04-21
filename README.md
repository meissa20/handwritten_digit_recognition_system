# Handwritten Digit Recognition 

## 📌 Objective

The goal of this assignment is to build a neural network from scratch using PyTorch to recognize handwritten digits from the MNIST dataset. It involves custom model architecture, data handling, training, and performance analysis.

---

## 📁 Project Structure

```
handwritten_digit_recognition_system/
├── handwritten_digit_recognition_system.ipynb      # Jupyter notebook containing full code and analysis
├── results/               # Folder for saved plots and confusion matrices
├── data/                  # Downloaded and preprocessed MNIST dataset
└── README.md              # Project readme file
```

---

## ⚙️ Requirements

- Python ≥ 3.8  
- PyTorch  
- scikit-learn  
- matplotlib  
- numpy  
- pandas

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 🚀 How to Run

1. **Download and preprocess the data**  
   The dataset will be downloaded automatically in the notebook using torchvision or can be placed manually inside the `data/` directory.

2. **Open the Jupyter Notebook**  
   ```bash
   jupyter notebook handwritten_digit_recognition_system.ipynb
   ```

3. **Execute all cells**  
   Follow the notebook sections to train the model, plot results, and analyze performance.

---

## 📊 Analysis Highlights

- Comparison of 4 different **learning rates**
- Impact of varying **batch sizes**
- Exploration of **model architecture variations**
- Final model tested on the test set with **confusion matrix** and **accuracy report**
- Bonus: CNN with **dropout** and **layer normalization**

---

