# Multimodal-approach-for-extreme-weahter-condtions
# Multimodal Model for Extreme Weather Prediction and Socioeconomic Impact Assessment in Kenya

## Overview
This project focuses on predicting extreme weather events (droughts, floods, and heatwaves) in Kenya and assessing their socioeconomic impact using a **multimodal machine learning model**. By integrating time-series climate data, socioeconomic vulnerability indices, and climate teleconnections, the model enhances disaster preparedness, early warning systems, and policy interventions.

## Features
- **Extreme Weather Prediction**: Uses climate time-series data for forecasting.
- **Socioeconomic Impact Assessment**: Estimates economic loss and displacement risk.
- **Risk Mapping System**: Provides geospatial visualizations of high-risk areas.
- **Machine Learning-Based Approach**: Implements LSTMs and MLPs for feature extraction and fusion.
- **API Integration**: Enables real-time updates for early warning systems.

## Data Sources
- **Climate Data**: ERA5 Reanalysis (temperature, precipitation, wind speed)
- **Socioeconomic Data**: WorldPop (population density), EM-DAT (disaster history), KNBS reports
- **Climate Teleconnections**: ENSO, NAO, and Indian Ocean Dipole (IOD) indices (optional)

## Model Architecture
1. **Feature Extraction**
   - LSTM for time-series climate data.
   - MLP for socioeconomic vulnerability indices.
   - MLP for climate teleconnection indices (optional).
2. **Fusion Mechanism**
   - Concatenates embeddings from all branches.
   - Joint dense layers for classification and regression.
3. **Training & Evaluation**
   - Classification: Binary cross-entropy, AUC-ROC, F1-Score.
   - Regression: Mean squared error (MSE), R², MAE.
   - Baseline Comparison: XGBoost trained on static features.

## Deployment
- Generates daily risk scores.
- Estimates economic impact by region.
- Provides interactive risk maps.
- Offers API for real-time updates.

## Expected Outcomes
- **Improved accuracy** over traditional forecasting models.
- **Better disaster preparedness** through impact estimation.
- **Scalable and open-source** solution for climate resilience.

## License
This project is licensed under the **MIT License**, allowing for free use, modification, and distribution with attribution. See [LICENSE](LICENSE) for details.

## Contributing
We welcome contributions! To contribute:
1. Fork the repository.
2. Create a new branch (`feature-branch-name`).
3. Commit changes and submit a pull request.

## Contact
For questions, reach out via email or open an issue in the repository.

---
**Note:** This project aligns with Kenya’s disaster risk reduction policies and aims to enhance predictive capabilities for climate resilience.

