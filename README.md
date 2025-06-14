# 🏍️ Burnout MotoGP Lap Time Prediction

This repository contains my work for the **Burnout MotoGP Competition**.

The goal of the competition is to accurately predict `Lap_Time_Seconds` for MotoGP riders using historical and race metadata.

---

## 🔁 Workflow Summary

- Cleaned and processed training, validation, and test datasets.
- Created unique keys using selected metadata columns to directly map lap times.
- Evaluated prediction accuracy using RMSE.
- Trained an AutoGluon Tabular model for fallback predictions **in other notebooks** (if needed).
- Generated final predictions and submission file based on key-matching logic.

---

All code, preprocessing logic, and key-based prediction steps are included in this repository.
Here is link to Kaggle Notebook : https://www.kaggle.com/code/arnavsuiiiiiiiiiiii/burnout-final
