# LakesWQ_evaluation
 
# Water Quality Prediction from Satellite Data

## Project Overview

This notebook demonstrates the prediction of water quality parameters using satellite imagery from Sentinel-2 and Landsat missions combined with in-situ measurements.

### Objectives
- Extract satellite-derived features at in-situ measurement locations
- Build predictive models for water quality parameters
- Compare different machine learning algorithms
- Analyze feature importance and model interpretability

### Target Variables
- **IRB_EC**: Electrical Conductivity (μS/cm)
- **IRB_TUR**: Turbidity (NTU)
- **IRB_WT**: Water Temperature (°C)
- **IRB_DO**: Dissolved Oxygen (mg/L)

### Data Sources
- **In-situ measurements**: Point measurements of water quality parameters
- **Sentinel-2**: 12 spectral bands at 10-60m resolution, one mulitlayer tiff 
- **Landsat**: 9 spectral bands at 30m resolution

---