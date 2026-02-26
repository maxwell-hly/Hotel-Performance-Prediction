# Hotel-Performance-Prediction
Beyond the Noise: Uncovering the Value of Inconsistent Signals in User-Generated Content for Hotel Performance Forecasting

This repository serves as a **methodological demonstration** for the empirical study on hotel performance forecasting using UGC inconsistency signals. 

Due to the constraints of ongoing funded research and platform data policies, we are unable to publicly release the complete proprietary feature engineering pipeline (e.g., custom NLP scripts, BERTopic dynamic drift modeling) and the fully processed numerical feature dataset. 

Instead, this repository provides:
1. **`ReviewData10000.csv`**: A sub-sample of the raw online reviews used in the study, providing context on the raw data structure.
2. **`Prediction_Framework_Demo.ipynb`**: The core machine learning architectural script. It illustrates the methodological logic detailed in **Appendix A** of the manuscript, including the chronological data splitting, the Bayesian Optimization search spaces, and the evaluation protocol.

### How to Interpret the Code
The script abstracts the complex text-to-feature engineering steps into a placeholder function (`extract_features_from_raw_text`). It explicitly lists the 19 core features utilized in the study to demonstrate how the structured data is fed into the ensemble models (XGBoost, Random Forest) for robust time-series forecasting.

This framework is provided to enhance methodological transparency and to guide interested researchers in constructing similar predictive pipelines.
