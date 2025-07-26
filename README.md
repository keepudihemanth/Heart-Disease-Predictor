# Heart-Disease-Predictor

# 🫀 Heart Disease Prediction using MLP (Multi-Layer Perceptron)

This project builds a heart disease prediction model using a neural network (MLP) with TensorFlow/Keras. The model is trained on patient medical attributes and predicts the likelihood of heart disease.

## 📂 Files

| File                  | Description                                       |
|-----------------------|---------------------------------------------------|
| `heart_train.csv`     | Training dataset                                  |
| `heart_test.csv`      | Test dataset                                      |
| `submission.csv`      | Submission format                                 |
| `heart_model.h5`      | Trained Keras model file                          |


---

## 🧠 Dataset Columns

This dataSet is taken from kaggle DataQuest

| Column         | Description |
|----------------|-------------|
| **Age**            | Age of the patient [years] |
| **Sex**            | Sex of the patient [M: Male, F: Female] |
| **ChestPainType**  | Chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic] |
| **RestingBP**      | Resting blood pressure [mm Hg] |
| **Cholesterol**    | Serum cholesterol [mm/dl] |
| **FastingBS**      | Fasting blood sugar [1 if > 120 mg/dl, else 0] |
| **RestingECG**     | Resting ECG results [Normal, ST, LVH] |
| **MaxHR**          | Maximum heart rate achieved |
| **ExerciseAngina** | Exercise-induced angina [Y: Yes, N: No] |
| **Oldpeak**        | ST depression (numeric) |
| **ST_Slope**       | Slope of ST segment [Up, Flat, Down] |
| **HeartDisease**   | Output class [1: heart disease, 0: normal] |

---


