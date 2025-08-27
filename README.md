# Q1K_VS_EEG
# Visual Search EEG & Eye-Tracking Analysis

## Project Overview
This project analyzes EEG, and eye-tracking data from a Visual Search task, aiming to explore patterns in cognitive performance, attention, and potential familial effects. It compare data from ASD, ADHD, and control groups.   
The analyses cover a comparison of EEG patterns between conditions, and detail, and investigate how eye-tracking measures align with EEG results.

The focus is on **reaction times, P1 and P3b amplitude, alpha, gamma waves, and family patterns** in both neurotypical vs neurodevelopmental (ASD, ADHD) indiviudals.

---

## Data Summary Visualization
A visual summary of all graphs and analyses from this project can be found within the notebooks.  
These include:
- Behavioral performance trends (reaction times, accuracy)
- EEG condition-based power analyses
- Eye-tracking + EEG visualization
- Distance and pattern similarity metrics
- Familial pattern exploration in visual search performance

---

## Project Structure
| File | Description |
|------|-------------|
| `Eye_tracking_data_VS.ipynb` | Processes and analyzes raw eye-tracking data from the visual search task. |
| `EEG_data.ipynb` | Extracts, preprocesses, and cleans EEG datasets for further analysis. |
| `VS_results_EEG_cond.ipynb` | Analyzes EEG erps across conditions (5, 9 13 distractors) of the visual search task based on population. |
| `VS_results_EEG_det.ipynb` |Analyzes EEG erps across details (single vs conjunction) of the visual search task based on population. |
| `EEG+ET.ipynb` | Integrates EEG and eye-tracking datasets for combined analysis. |
| `familial_pattern_VS.ipynb` | Explores familial patterns in visual search performance across participants. |
| `VS_distance_data.ipynb` | Analyses links between distance from the center as a potential confound and reaction time. |
| `VS_EEG_EXTRACTION.ipynb` | Additional EEG extraction and figure generation for visualization (similar to the EEG_data but modified to accommodate compute clusters). |

---

## Roadmap & Recommended Execution Order
To reproduce the full analysis, follow this order:

1. **Eye Tracking Data Preprocessing + Analysis** → `Eye_tracking_data_VS.ipynb`  
2. **EEG Data Preparation** → `EEG_data.ipynb`  
3. **EEG Condition Analysis** → `VS_results_EEG_cond.ipynb`  
4. **EEG Detail Analysis** → `VS_results_EEG_det.ipynb`  
5. **EEG + Eye-Tracking Integration** → `EEG+ET.ipynb`  
6. **Familial Pattern Analysis** → `familial_pattern_VS.ipynb`  
7. **Distance Confound Analysis** → `VS_distance_data.ipynb`
---

## Reusability
This codebase was developed as part of the Quebec 1,000 Families (Q1K) project to analyze EEG, eye-tracking, and behavioral data collected during a nonverbal visual search task. The task was designed to be inclusive of a wide range of cognitive and verbal abilities, addressing a common limitation in autism spectrum disorder (ASD) research, which often overrepresents higher-functioning individuals and under-models familial effects. By sharing this code, we aim to enable further research that tackles this critical gap in the literature.

The pipeline is modular and well-documented, making it adaptable for researchers working with multimodal neurodevelopmental data. Components can be reused independently. 
By publishing the pipeline before data publication, this project promotes transparency and reproducibility. Researchers are encouraged to adapt it for new datasets, integrate additional modalities, or extend its statistical modeling framework.

---

## Acknowledgements
The authors would like to thank all families who took part in this study. Special thanks to the my supervisor Mayada Elsabbagh.

---
## Badges

![MIT License](https://img.shields.io/badge/License-MIT-green.svg)
---
## Requirements

- Python 3.8+
- Packages:
  - Python: pathlib, pandas, numpy, os, statsmodels, seaborn, matplotlib.pyplot, glob, spicy, pingouin, mne, tqdm, collections

---
## Support
For support, email: [audrey-anne.beaudry@mail.mcgill.ca](mailto:audrey-anne.beaudry@mail.mcgill.ca)

---
## License
This project is licensed under the MIT License.

**Author:** Audrey-Anne Beaudry and Gabriel Blanco Gomez
