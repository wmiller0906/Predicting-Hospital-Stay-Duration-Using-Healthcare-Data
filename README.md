# Hospital Length of Stay Prediction

This project builds and evaluates linear regression models to predict hospital patient Length of Stay (LoS) using synthetic healthcare data provided by Microsoft. Starting with univariate and multivariate linear regression, it explores the effects of feature selection and interaction terms. Finally, it compares the performance of linear models with a Random Forest Regressor.

---

## Authors and Contributions

This repository contains code and analysis developed for the ECGR 4105 Final Project.

- **William Miller** — Sole contributor to all data preprocessing, model development, and implementation in this repository, including the Colab notebook, figures, and analysis.
- **C. Burton, W. Miller, and R. Thomas** — Co-authors of the written final project report submitted to the course instructor.

---

## Contents

| File                                                                    | Description                                                 |
|-------------------------------------------------------------------------|-------------------------------------------------------------|
| `Predicting_Hospital_Stay_Duration_Using_Healthcare_Data.ipynb`         | Main Colab notebook with all code, analysis, and plots      |
| `Predicting_Hospital_Stay_Duration_Using_Synthetic_Healthcare_Data.pdf` | Final report submitted for the ECGR 4105 course            |
| `LengthOfStay.csv`                                                      | Input dataset used in the notebook                          |
| `README.md`                                                             | Project summary and documentation                           |

---

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/wmiller0906/Predicting-Hospital-Stay-Duration-Using-Healthcare-Data.git
   ```

2. Open the `.ipynb` file in [Google Colab](https://colab.research.google.com/) or Jupyter Notebook.

3. Ensure `LengthOfStay.csv` is available and update the file path in the notebook if needed.

---

## Performance Metrics

| Model                               | MAE    | R²     |
|-------------------------------------|--------|--------|
| Univariate (Readmission Count)      | 1.2296 | 0.5622 |
| Multivariate Linear Regression      | 0.8999 | 0.7498 |
| Random Forest Regression            | 0.3808 | 0.9278 |

---

## Highlights

- **Readmission Count** was the strongest individual predictor (R² = 0.5622).
- A **multivariate linear regression** model achieved R² = 0.7498.
- **Feature selection and interaction terms** did not improve the linear model.
- **Random Forest Regression** significantly outperformed linear models with an R² of 0.9278.

---

## Disclaimer

- The dataset used in this project is synthetic and provided by Microsoft for educational purposes.  
Dataset source: [https://microsoft.github.io/r-server-hospital-length-of-stay](https://microsoft.github.io/r-server-hospital-length-of-stay)
- Portions of this project, including conceptual clarification,
methodology refinement, and debugging, were developed with assistance from ChatGPT, an AI language model by OpenAI. All final decisions, analyses, and interpretations were made by the author.

---

## Citation

If you use or refer to this project, please cite it as:

[1] W. Miller, *Predicting Hospital Length of Stay Using Healthcare Data*, GitHub repository, 2025. [Online]. Available: https://github.com/wmiller0906/Predicting-Hospital-Stay-Duration-Using-Healthcare-Data

[2] C. Burton, W. Miller, and R. Thomas, *Predicting Hospital Stay Duration Using Synthetic Healthcare Data*, ECGR 4105 Final Project Report, University of North Carolina - Charlotte, May 2025.
