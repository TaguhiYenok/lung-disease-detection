# 🫁 Lung Disease Detection from Chest X-rays

This project applies deep learning (EfficientNetB7 and EfficientNetV2L) to classify lung conditions — including COVID-19, Pneumonia, and Lung Opacity — from chest radiographs. It compares performance across models using a two-phase transfer learning strategy with data augmentation.

---

## 📂 Project Structure

```
Lung-Disease-Detection/
├── Notebooks/
│   ├── EfficientNetB7.ipynb
│   ├── EfficientNetV2L.ipynb
│   └── EfficientNetB7_Augmentation.ipynb
├── Datasets/
│   ├── Anomaly/
│   └── Normal/
├── requirements.txt
├── .gitignore
└── README.md
```

> ⚠️ **Note:** The `Datasets/` folder is excluded from this repository due to size. Please download the dataset manually from [Kaggle](https://www.kaggle.com/datasets/fatemehmehrparvar/lung-disease) or contact the author.

---

## 🚀 How to Run

1. **Clone this repo**
   ```bash
   git clone https://github.com/YOUR_USERNAME/lung-disease-detection.git
   cd lung-disease-detection
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Open and run notebooks**

Use Jupyter Notebook or VS Code to open files inside the `Notebooks/` folder:

- `EfficientNetB7.ipynb` – baseline model  
- `EfficientNetV2L.ipynb` – advanced model  
- `EfficientNetB7_Augmentation.ipynb` – with data augmentation  

---

## 🧪 Models Used

| Model                | Purpose                              |
|----------------------|--------------------------------------|
| EfficientNetB7       | Strong baseline, pretrained on ImageNet |
| EfficientNetB7 + Aug | Improved generalization              |
| EfficientNetV2L      | High-capacity model with fine-grained features |

---

## 📈 Results (from published research)

| Metric              | EfficientNetB7 | EfficientNetV2L |
|---------------------|----------------|-----------------|
| Validation Accuracy | 93.36%         | 92.12%          |
| Macro F1 Score      | 0.94           | 0.92            |
| COVID-19 Precision  | 0.92           | 0.98            |

See detailed results and visualizations inside each notebook.

---

## 👩‍💻 Author

**Taguhi Yenokyan**  
Master’s in Computer Science – UC San Diego  
[LinkedIn Profile](https://www.linkedin.com/in/taguhiyenokyan)

---

## 📜 Citation

If you use this project or find it helpful, please cite:

> Taguhi Yenokyan and Abhishek Verma, “Lung Disease Detection Using Deep Learning,” Department of Computer Science, California State University, Northridge.

---
