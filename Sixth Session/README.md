
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

# 🌍 Introduction to Remote Sensing with Python

Welcome to the **Introduction to Remote Sensing with Python** repository! This project is designed to provide a hands-on introduction to remote sensing data analysis and visualization using cutting-edge tools like **Cubo**, **STAC (SpatioTemporal Asset Catalogs)**, and **Google Earth Engine (GEE)**.

## 🌟 Objectives

By the end of this course, you will:
- Understand the fundamentals of remote sensing and geospatial analysis.
- Learn to explore and query remote sensing data using **Cubo** and **STAC** APIs.
- Process and visualize geospatial data using **Google Earth Engine**.
- Calculate vegetation indices like NDVI, EVI, SAVI, and more using Python.

## 📚 Features

- **Cubo:** Harness the power of AI-driven geospatial tools for data discovery and analysis.
- **STAC:** Simplify access to remote sensing datasets with standardized catalogs.
- **GEE:** Leverage Google's cloud-based platform for large-scale geospatial processing.
- Python integration with key geospatial libraries: **GeoPandas**, **Rasterio**, **Xarray**, and **Matplotlib**.

## 📅 Table of Contents

1. [Getting Started](#getting-started)
2. [Vegetation Indices](#vegetation-indices)
3. [Using Cubo for Remote Sensing](#using-cubo-for-remote-sensing)
4. [Querying with STAC](#querying-with-stac)
5. [Google Earth Engine Basics](#google-earth-engine-basics)
6. [Resources](#resources)

## 🚀 Getting Started

### Installation Instructions

Clone this repository and install the required dependencies:

\`\`\`bash
git clone https://github.com/your-repo-name/remote-sensing.git
cd remote-sensing
pip install -r requirements.txt
\`\`\`

Install additional packages as needed for **Cubo** or **GEE**:
\`\`\`bash
pip install cubo-stac-api earthengine-api
\`\`\`

### Using the Notebook

Open the provided Jupyter Notebook to start exploring remote sensing datasets. Run each cell sequentially for step-by-step guidance on:
1. Querying data from **STAC**.
2. Performing geospatial analysis with **Cubo**.
3. Visualizing data and calculating vegetation indices.

### Vegetation Indices Example

Learn how to calculate popular vegetation indices:
- **NDVI**: Assess vegetation health using NIR and Red bands.
- **SAVI**: Soil-adjusted vegetation health index.
- **EVI**: Enhanced vegetation index for reducing atmospheric effects.

## 🌐 Tools in Action

### Using Cubo for Remote Sensing
Cubo provides an AI-powered geospatial analytics platform to discover, preprocess, and analyze satellite data efficiently.

### Querying with STAC
STAC enables you to search, filter, and retrieve remote sensing imagery from multiple sources (e.g., Sentinel-2, Landsat).

### Google Earth Engine Basics
GEE offers a cloud-based geospatial computation platform to analyze and visualize massive remote sensing datasets.

## 💻 Resources

- [Cubo Documentation](https://docs.cubo.com)
- [STAC Specification](https://stacspec.org/)
- [Google Earth Engine API](https://developers.google.com/earth-engine/)
- [GeoPandas](https://geopandas.org/)
- [Rasterio](https://rasterio.readthedocs.io/)
- [Xarray](https://xarray.pydata.org/)
- [Matplotlib](https://matplotlib.org/)

## 🤝 Contributing

Contributions are welcome! If you have suggestions for new features, corrections, or additional examples, feel free to open an issue or submit a pull request.

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

