# 🌍 Remote Sensing Project using Sentinel-2 & Python

This mini-project explores how satellite images from **Sentinel-2** can be processed using Python to calculate and visualize environmental indices like NDVI, NDWI, BSI, and IOI.

---

## 📌 Objective

To extract insights about vegetation, water, soil, and built-up land from `.tiff` band images using Remote Sensing techniques and Python data analysis libraries.

---

## 🛰️ Data Source

- **Google Earth**: For selecting the area and timeline  
- **Sentinel-2** (Copernicus / ESA): Satellite imagery (.tiff format)

Bands Used:
- `B2` – Blue
- `B4` – Red
- `B8` – Near Infrared (NIR)
- `B11` – Short Wave Infrared (SWIR)

---

## 🧮 Calculated Indices

| Index | Full Form                          | Purpose                      |
|-------|------------------------------------|------------------------------|
| NDVI  | Normalized Difference Vegetation Index | Vegetation health detection |
| NDWI  | Normalized Difference Water Index     | Water body detection        |
| BSI   | Bare Soil Index                      | Soil / barren land detection|
| IOI   | Index of Openness (or Built-up)      | Urban/built-up detection    |

---

## 🛠️ Tech Stack

- Python 🐍
- NumPy
- Rasterio
- Matplotlib
- Seaborn
- SciPy
- Google Earth
- Sentinel-2 `.tiff` image files

---

## 📊 Output Visuals

Each index was visualized using a **heatmap** to understand its spatial variation across the selected region:

- ✅ NDVI Heatmap  
- ✅ NDWI Heatmap  
- ✅ BSI Heatmap  
- ✅ IOI Heatmap  

---

## 📁 Folder Structure (Suggestion)

DS_ML_Workshop/
│
├── data/ # .tiff files
├── ndvi_ndwi_bsi_ioi.ipynb # Main notebook
├── plots/ # Saved heatmaps
├── README.md # Project documentation
└── requirements.txt # Python packages


---

## 📚 Learning Outcome

- Learned how to process `.tiff` images using `rasterio`
- Applied Remote Sensing index formulas to real satellite data
- Understood the role of each band in environmental monitoring
- Gained hands-on practice in data normalization, visualization, and geospatial insight generation

---

## 🔗 Author & Credits

Made with ❤️ by **Krushna Sonawane**  
[LinkedIn](linkedin.com/in/krushna-sonawane-16442b2b8) | [GitHub](https://github.com/KrushnaSonawane24)



