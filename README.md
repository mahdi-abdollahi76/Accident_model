# Accident_model

# 🚦 Accident Risk Prediction with Feature-Aware Stacking

This project presents a high-accuracy accident risk prediction pipeline built with modular components, custom feature importance evaluation, and error-aware stacking using CatBoost. Designed for reliability, interpretability, and open-source reuse.

---

## 📊 Highlights

- 🔍 **Custom Feature Importance**
  - Feature-wise MAE evaluation using single-feature pipelines
  - Ranks predictors based on real-world impact, not just correlation

- 🧠 **Error-Aware Stacking**
  - Second-level model trained on residuals and base predictions
  - Captures error patterns and improves generalization

- 📈 **High Accuracy**
  - Achieved **R² = 0.93** and low MAE on hold-out validation
  - Outperforms standard ensemble methods

- 🧪 **Robust Validation**
  - Stratified split and random_state variation
  - Generalization gap analysis for trustworthy performance

- 🧱 **Modular Design**
  - All components (EDA, preprocessing, modeling, evaluation) are structured for reuse and packaging

---

📦 Coming Soon
✅ PyPI package for feature_importance module

📚 Documentation with examples and API reference

🧪 Unit tests with pytest

🌐 Kaggle notebook link for public demo

----
📜 License
This project is licensed under the MIT License. Feel free to use, modify, and share with attribution.

---
🙌 Author
Mahdi Abdollahi Self-taught ML practitioner focused on building reusable, auditable pipelines and open-source tools.

## 📁 Project Structure

