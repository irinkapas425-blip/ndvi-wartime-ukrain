# ndvi-wartime-ukrain
Analysis of NDVI dynamics and crop yields in  Zhytomyr and Kherson regions during wartime (2019-2023)
# NDVI Dynamics Under Wartime Conditions in Ukraine (2019–2023)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](ВАШ_ПОСИЛАННЯ_НА_COLAB)

# About
Comparative analysis of NDVI vegetation index and grain crop yields 
in Zhytomyr and Kherson regions of Ukraine during full-scale 
wartime (2019–2023).

Zhytomyr region showed agricultural resilience 
(NDVI grew from 0.54 to 0.62), while Kherson region suffered 
critical decline due to occupation (data absent in 2023).

# Data Sources
- Sentinel-2 via Google Earth Engine — NDVI calculation
- State Statistics Service of Ukraine — official yield data
- **FAO GAUL** — administrative boundaries

# Results
| Year | Zhytomyr NDVI | Kherson NDVI | Zhytomyr Yield | Kherson Yield |
|------|--------------|--------------|----------------|---------------|
| 2019 | 0.542 | 0.397 | 58.9 ц/га | 36.2 ц/га |
| 2020 | 0.458 | 0.393 | 48.2 ц/га | 35.0 ц/га |
| 2021 | 0.532 | 0.414 | 60.8 ц/га | 43.4 ц/га |
| 2022 | 0.561 | 0.390 | 43.3 ц/га | 31.9 ц/га |
| 2023 | 0.581 | 0.434 | 54.8 ц/га | NA (окупація) |

#Key Figures
![NDVI Comparison](figures/ndvi_comparison.png)
![Main Figure](figures/main_figure.png)

#Tech Stack
- Python (earthengine-api, geemap, pandas, matplotlib)
- Google Earth Engine (Sentinel-2)
- Google Colab

# Citation
Якщо використовуєте дані — будь ласка цитуйте:
[Ірина Пасічник] (2026). NDVI Dynamics Under Wartime Conditions 
in Ukraine. GitHub Repository.

# Contact
rikoonlin@i.ua | https://www.linkedin.com/in/iryna-p-557323410/?locale=uk
