# 🌾 Crop Recommendation System (LightGBM)

This machine learning project recommends the most suitable crop to plant based on soil and climatic factors (N, P, K, temperature, humidity, pH, rainfall). It uses a LightGBM classifier for accurate multi-class prediction.

## 📁 Project Structure

- `data/` — Contains the dataset (`Crop_recommendation.csv`)
- `notebooks/` — Jupyter notebook for model development (`MP-LGBM-1.ipynb`)
- `images/` — Plots and charts (confusion matrix, feature distributions, etc.)
- `saved_models/` — Trained LightGBM model (`lightgbm_model.pkl`)
- `requirements.txt` — Python dependencies
- `README.md` — Project overview and instructions

## 🚀 Usage

1. Clone the repository
2. Install dependencies:
    ```
    pip install -r requirements.txt
    ```
3. Run the notebook in `notebooks/` to retrain or test the model.
4. Use the saved model from `saved_models/` for making predictions.

## 📊 Features

- Comprehensive EDA with visualizations
- LightGBM classifier achieving high accuracy
- Clear evaluation using confusion matrix and classification report
- Sample prediction code snippet

## 📜 License

MIT License
