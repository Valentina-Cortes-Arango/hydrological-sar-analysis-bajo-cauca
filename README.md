# Hydrological SAR Analysis — Bajo Cauca

This repository contains reproducible Python notebooks for the **multitemporal detection, despeckling, classification, and quantification of water bodies** in the Bajo Cauca Antioqueño region using **Sentinel-1 SAR imagery**.

---

## 🚀 How to Run

All notebooks are designed and tested to run **directly in [Google Colab](https://colab.research.google.com)** — no local setup required.

1️⃣ Click **Open in Colab** for any notebook below.  
2️⃣ Authenticate Google Earth Engine and Google Drive when prompted.  
3️⃣ Execute each cell in order to download, process, and analyze your data.

---

## 📂 Notebooks

| Notebook | Open in Colab | Description |
|---|---|---|
| `download_images_confluencia.ipynb` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Valentina-Cortes-Arango/hydrological-sar-analysis-bajo-cauca/blob/main/download_images_confluencia.ipynb) | Download monthly Sentinel-1 VV polarization SAR images. |
| `autoencoder_denoising_confluencia.ipynb` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Valentina-Cortes-Arango/hydrological-sar-analysis-bajo-cauca/blob/main/autoencoder_denoising_confluencia.ipynb) | Apply a pre-trained Autoencoder to despeckle SAR imagery. |
| `water_detection_confluencia.ipynb` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Valentina-Cortes-Arango/hydrological-sar-analysis-bajo-cauca/blob/main/water_detection_confluencia.ipynb) | Perform Otsu-based water classification and generate annual probability maps. |
| `permanent_water_and_cuantification_flood_area.ipynb` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Valentina-Cortes-Arango/hydrological-sar-analysis-bajo-cauca/blob/main/permanent_water_and_cuantification_flood_area.ipynb) | Compute permanent water bodies and quantify flood areas. |

---

## ✅ Requirements

All dependencies are installed automatically in each notebook:

- `earthengine-api`
- `geemap`
- `rasterio`
- `opencv-python`
- `geopandas`
- `scipy`
- `matplotlib`

---

## 🧑‍💻 Authors

**Valentina Cortés-Arango**,  
**Juan Andrés Jaramillo-Pineda**,  
**Camilo Echeverri-Idarraga**,  
**Carolina González-Morales**,  
**Silvana Bolaños-Chavarría**,  
**César Aníbal Olmos-Severiche**,  
**Jean Pierre Díaz-Paz**

---

## 📜 License

This project is licensed under the **GPL-3.0 License**.

---

## 🙌 Acknowledgements

This repository accompanies the article:  
**“A methodology for multitemporal analysis of hydraulic dynamic of water bodies using satellite radar imagery: A case study of the Bajo Cauca region in Antioquia-Colombia.”**

---

## ⭐️ If you find this useful, please **star** this repository!

