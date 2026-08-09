# Models/

This folder holds the trained model artifacts produced by `src/ShadowIT_Cloud.ipynb`.

After running the notebook end-to-end (Section 22, "Save Final Models"), copy these three files here from your `base_path`:

- `random_forest_model.joblib` — trained Random Forest classifier
- `isolation_forest_model.joblib` — trained Isolation Forest (final recommended model)
- `feature_scaler.joblib` — the fitted `StandardScaler` used to preprocess features before scoring new data

*(This folder is currently empty — models will be added once the notebook has been run and the `.joblib` files exported.)*
