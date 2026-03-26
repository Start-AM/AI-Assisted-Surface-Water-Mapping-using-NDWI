# AI-Assisted-Surface-Water-Mapping-using-NDWI
This project focuses on extracting and analyzing surface water bodies from satellite imagery using the Normalized Difference Water Index (NDWI) integrated with Machine Learning techniques. The approach enhances traditional threshold-based methods by improving classification accuracy and enabling intelligent water body detection.
## 🌊 AI-Assisted Surface Water Mapping using NDWI

This project demonstrates an intelligent approach to detecting and mapping surface water bodies using the **Normalized Difference Water Index (NDWI)** combined with **Machine Learning techniques**. It leverages satellite imagery (Sentinel-2 / Landsat) to identify water features with improved accuracy over traditional threshold-based methods.

The workflow begins with preprocessing satellite data, including clipping to the area of interest and removing noise such as clouds. NDWI is then calculated to highlight water pixels. Instead of relying solely on fixed thresholds, machine learning models such as Random Forest or SVM are applied to enhance classification and reduce misclassification errors.

The processed raster output is further converted into vector format (polygons), enabling spatial analysis and area calculation of water bodies. This ensures the results are not only visually interpretable but also analytically useful.

### 🚀 Key Highlights

* NDWI-based water detection
* AI-enhanced classification
* Raster-to-vector conversion
* Area estimation in sq. km
* Scalable and efficient workflow

### 🛠️ Tech Stack

QGIS, Python (optional), Google Earth Engine, Sentinel/Landsat data

### 🎯 Applications

Flood monitoring, urban planning, water resource management, and environmental analysis

### ⚠️ Limitations

Affected by cloud cover, seasonal variations, and requires training data for ML models

### 🔮 Future Scope

Integration with deep learning, real-time monitoring, and automated geospatial pipelines

---

**Author:** Mohit Singh
Engineering Student | GIS & Remote Sensing Enthusiast
