# Q1K_VS_EEG
# Visual Search EEG & Eye-Tracking Analysis

## Project Overview
This project analyzes EEG, and eye-tracking data from a Visual Search task, aiming to explore patterns in cognitive performance, attention, and potential familial effects. It compare data from ASD, ADHD, and control groups.   
The analyses cover a comparison of EEG patterns between conditions, and detail, and investigate how eye-tracking measures align with EEG results.

A key focus is on **reaction times, P1 and P3b amplitude, alpha, gamma waves, and family patterns** in both typical and clinical populations.

---

## Data Summary Visualization
A visual summary of all graphs and analyses from this project can be found within the notebooks.  
These include:
- Behavioral performance trends (reaction times, accuracy)
- EEG condition-based power analyses
- Eye-tracking heatmaps and fixation distributions
- Distance and pattern similarity metrics
- Familial pattern exploration in visual search performance

---

## Project Structure
| File | Description |
|------|-------------|
| `Eye_tracking_data_VS.ipynb` | Processes and analyzes raw eye-tracking data from the visual search task. |
| `EEG_data.ipynb` | Extracts, preprocesses, and cleans EEG datasets for further analysis. |
| `VS_results_EEG_cond.ipynb` | Analyzes EEG power across conditions of the visual search task based on population. |
| `VS_results_EEG_det.ipynb` |Analyzes EEG power across details of the visual search task based on population. |
| `EEG+ET.ipynb` | Integrates EEG and eye-tracking datasets for combined analysis. |
| `familial_pattern_VS.ipynb` | Explores familial patterns in visual search performance across participants. |
| `VS_distance_data.ipynb` | Analyses links between distance and reaction time. |
| `VS_EEG_EXTRACTION.ipynb` | Additional EEG extraction and figure generation for visualization. |

---

## Roadmap & Recommended Execution Order
To reproduce the full analysis, follow this order:

1. **Behavioral Data Processing** → `VS_distance_data.ipynb`  
2. **EEG Data Preparation** → `EEG_data.ipynb`  
3. **EEG Condition Analysis** → `VS_results_EEG_cond.ipynb`  
4. **EEG Detail Analysis** → `VS_results_EEG_det.ipynb`  
5. **EEG + Eye-Tracking Integration** → `EEG+ET.ipynb`  
6. **Familial Pattern Analysis** → `familial_pattern_VS.ipynb`  

---

**Author:** Audrey-Anne Beaudry  
