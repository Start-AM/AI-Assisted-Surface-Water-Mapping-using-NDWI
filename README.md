# AI-Assisted-Surface-Water-Mapping-using-NDWI
This project focuses on extracting and analyzing surface water bodies from satellite imagery using the Normalized Difference Water Index (NDWI) integrated with Machine Learning techniques. The approach enhances traditional threshold-based methods by improving classification accuracy and enabling intelligent water body detection.

---

## 🌊 AI-Assisted Surface Water Mapping using NDWI

This project focuses on extracting and analyzing surface water bodies from satellite imagery using the **Normalized Difference Water Index (NDWI)** integrated with **Machine Learning techniques**. The approach enhances traditional threshold-based methods by improving classification accuracy and enabling intelligent water body detection.

---

## 🚀 Project Overview

The workflow leverages remote sensing data (Sentinel-2 / Landsat) and applies NDWI to highlight water features, followed by AI-based classification to refine results. The final output includes vectorized water bodies and area-based analysis for decision-making.

---

## 🧠 Key Features

* NDWI-based water detection using spectral bands
* AI/ML integration (Random Forest / SVM) for improved accuracy
* Raster-to-vector conversion of water bodies
* Automated area calculation (sq. km)
* Scalable workflow for large geographic regions

---

## 🛠️ Tech Stack

* QGIS (Geospatial Analysis)
* Python (Optional – ML integration)
* Google Earth Engine (optional)
* Satellite Data: Sentinel-2 / Landsat

---

## 📊 Workflow

1. Data acquisition (satellite imagery)
2. Preprocessing (clipping, cloud masking)
3. NDWI calculation
4. Threshold-based water extraction
5. AI-based classification
6. Vectorization & area calculation

---

🔷 1. What is NDWI?

NDWI is a spectral index used to highlight water features in satellite images.

𝑁𝐷𝑊𝐼 = (𝐺𝑟𝑒𝑒𝑛−𝑁𝐼𝑅)/(𝐺𝑟𝑒𝑒𝑛+𝑁𝐼𝑅)
​
Green band → reflects water strongly
NIR (Near Infrared) → water absorbs it
Result:
Values > 0 → Water
Values < 0 → Land/Vegetation
🔷 2. End-to-End Workflow (Industry-Grade Approach)
📌 Step 1: Data Acquisition
Satellite sources:
Sentinel-2 (ESA)
Landsat 8/9 (USGS)
Required bands:
Green (B3)
NIR (B8)
📌 Step 2: Preprocessing
Atmospheric correction
Cloud masking
Clipping to Area of Interest (AOI)
(e.g., Yamuna Basin, Delhi)
📌 Step 3: NDWI Calculation
Use:
QGIS Raster Calculator
Python (Google Earth Engine / Rasterio)

Formula applied pixel-wise → NDWI raster generated

📌 Step 4: Thresholding (Traditional Method)
Apply threshold (e.g., NDWI > 0)
Output:
Binary water mask

⚠️ Limitation:

Misclassification (shadows, built-up areas)

---

## 📌 Output

* NDWI Raster Map
* Classified Water Body Map
* Vector Shapefiles
* Area Statistics

---

## 🎯 Applications

* Flood monitoring & management
* Urban water resource planning
* Environmental analysis
* Climate impact assessment

---

## ⚠️ Limitations

* Sensitive to cloud cover
* Seasonal variation in water bodies
* Requires labeled data for ML models

---

## 🔮 Future Scope

* Deep Learning (CNN-based segmentation)
* Real-time monitoring using GEE
* Integration with IoT-based water systems

---

## 🧾 Author

**Mohit Singh**
Engineering Student | GIS & Remote Sensing Enthusiast

---
