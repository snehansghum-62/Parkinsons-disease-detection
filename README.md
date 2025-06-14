
---

## 📊 Dataset

- **File:** `parkinsons1.xlsx`
- Contains biomedical voice measurements from people with and without Parkinson’s.
- Includes features like:
  - MDVP:Fo(Hz), MDVP:Fhi(Hz), MDVP:Flo(Hz)
  - NHR, HNR
  - RPDE, DFA
  - Class (0: healthy, 1: Parkinson’s)

---

## ⚙️ Models Used

### 🔹 AutoEncoder
- Reduces dimensionality by encoding and reconstructing features.
- Helps extract meaningful latent features from raw input.

### 🔹 TabNet
- Deep learning model optimized for tabular data.
- Leverages attention mechanisms for interpretable results.

---

## 🚀 How to Run

1. **Clone the Repository**
```bash
git clone https://github.com/yourusername/Parkinsons-disease-detection.git
cd Parkinsons-disease-detection

## Dependencies

- Python 3.x
- numpy
- pandas
- scikit-learn
- tensorflow
- pytorch-tabnet
- openpyxl (for Excel file support)
