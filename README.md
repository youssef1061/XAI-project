# XAI Project — Explainable AI on Medical/Health Datasets

A comparative study of Explainable Artificial Intelligence (XAI) techniques applied across multiple machine learning models and datasets, reproducing and extending results from several published research papers. The project covers exploratory data analysis, preprocessing, model training, and explainability using **LIME** and **SHAP**.

---

## 📁 Repository Structure

| Notebook | Description |
|----------|-------------|
| `EDA_Preprocessing.ipynb` | Exploratory Data Analysis and data preprocessing pipeline shared across experiments |
| `01_Dawood_Xie2019_MLP.ipynb` | MLP model replicating Xie et al. (2019) with XAI explanations |
| `02_Dawood_Ullah2022_XGBoost_V3.ipynb` | XGBoost model replicating Ullah et al. (2022) with SHAP/LIME |
| `03_Dawood_Chowdhury2024_HistGB.ipynb` | Histogram Gradient Boosting replicating Chowdhury et al. (2024) |
| `Mohamed_Dawood_Xie2019.ipynb` | Alternative MLP implementation based on Xie et al. (2019) |
| `Mohamed_Ehab_Pang2025.ipynb` | Model replication based on Pang et al. (2025) |
| `YoussefHatem_Islam__et__al_(2025).ipynb` | Reproduction of Islam et al. (2025) with XAI analysis |
| `Youssef_Hatem_—_Zafar_et_al_(2025).ipynb` | Reproduction of Zafar et al. (2025) with SHAP explanations |
| `Youssef_hatem_Maimaitijiang2025.ipynb` | Reproduction of Maimaitijiang et al. (2025) with full XAI pipeline |
| `Team13_ResearchPaper.pdf` | Full research paper documenting the team's methodology and findings |

---

## ⚙️ Requirements

Install the required Python packages before running any notebook:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost shap lime jupyter
```

**Python version:** 3.8 or higher recommended.

---

## 🚀 How to Run

### Option 1: Google Colab (Recommended)

1. Open [Google Colab](https://colab.research.google.com/)
2. Click **File → Open notebook → GitHub**
3. Paste the repository URL: `https://github.com/youssef1061/XAI-project`
4. Select the notebook you want to run
5. Run all cells with **Runtime → Run all**

> **Note:** If the notebook loads a dataset from a local path, upload the dataset file via the Colab file panel or mount your Google Drive.

### Option 2: Run Locally with Jupyter

1. **Clone the repository:**
   ```bash
   git clone https://github.com/youssef1061/XAI-project.git
   cd XAI-project
   ```

2. **Install dependencies:**
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn xgboost shap lime jupyter
   ```

3. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

4. **Open any notebook** from the Jupyter interface in your browser and run cells sequentially with **Shift + Enter** or use **Kernel → Restart & Run All**.

### Option 3: Kaggle Notebooks

1. Go to [Kaggle](https://www.kaggle.com/) and create a new notebook
2. Under **File → Import Notebook**, upload the `.ipynb` file directly from the cloned repo
3. Attach the relevant dataset and run all cells

---

## 📋 Recommended Execution Order

For a full end-to-end understanding, run the notebooks in this order:

1. `EDA_Preprocessing.ipynb` — Start here for data understanding and preprocessing
2. Any model notebook (e.g., `01_Dawood_Xie2019_MLP.ipynb`) — Train the model
3. The XAI sections within each notebook will automatically generate SHAP/LIME explanations after training

---

## 🔬 XAI Techniques Used

- **SHAP (SHapley Additive exPlanations):** Global and local feature importance, summary plots, waterfall charts, and dependency plots
- **LIME (Local Interpretable Model-agnostic Explanations):** Per-instance explanation of individual predictions

---

## 👥 Team

**Team 13** — Computer Science, Data Science & AI Specialization

| Member | Notebooks |
|--------|-----------|
| Youssef Hatem | `YoussefHatem_Islam__et__al_(2025).ipynb`, `Youssef_Hatem_—_Zafar_et_al_(2025).ipynb`, `Youssef_hatem_Maimaitijiang2025.ipynb` |
| Mohamed Dawood | `01_Dawood_Xie2019_MLP.ipynb`, `02_Dawood_Ullah2022_XGBoost_V3.ipynb`, `03_Dawood_Chowdhury2024_HistGB.ipynb`, `Mohamed_Dawood_Xie2019.ipynb` |
| Mohamed Ehab | `Mohamed_Ehab_Pang2025.ipynb` |

---

## 📄 Research Paper

The full methodology, experiments, and results are documented in [`Team13_ResearchPaper.pdf`](./Team13_ResearchPaper.pdf).

---

## 📜 License

This project is for academic purposes only.
