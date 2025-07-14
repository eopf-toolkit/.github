# Earth Observation Processing Framework (EOPF) Toolkit

<p align="center">
  <img src="https://raw.githubusercontent.com/eopf-toolkit/eopf-101/main/img/EOPF_FINAL_LOGO.png" alt="EOPF Toolkit Logo" width="40%">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/eopf-toolkit/eopf-101/main/img/logos.png" alt="Consortium logos" width="80%">
</p>

## About EOPF Toolkit

The EOPF Toolkit is a community-driven initiative that facilitates the adoption of the Zarr data format for Copernicus Sentinel data, targeting users who are new to cloud computing. Our mission is to transform how you work with Earth Observation data in the cloud through cloud-native, efficient, and accessible tools and resources.

### Why Zarr Changes Everything

The traditional SAFE data format is being transformed through ESA's ambitious EOPF initiative, which is transitioning Copernicus Sentinel data to Zarr - an open-source, cloud-native protocol that revolutionizes how we store and access multi-dimensional arrays.

Zarr's chunked architecture divides data into small, independent pieces that enable retrieval and processing of specific areas without loading complete datasets. This approach supports parallel processing, allowing multiple chunks to be read and written simultaneously, dramatically improving processing efficiency compared to traditional formats.

## Our Resources

### EOPF 101 - Your Gateway to Cloud-Native Earth Observation

[EOPF 101](https://eopf-toolkit.github.io/eopf-101/) is a comprehensive online resource that takes you on a carefully structured journey through cloud-native Earth observation:

* **Chapter 1**: Introduction to EOPF, cloud-optimized geospatial formats, and overview of EOPF Zarr products
* **Chapter 2**: Deep dive into Zarr format structure with hands-on examples
* **Chapter 3**: SpatioTemporal Asset Catalog (STAC) integration with EOPF data
* **Chapter 4**: Tools and libraries for working with EOPF Zarr (Coming Soon)
* **Chapter 5**: Real-world application workflows and case studies (Coming Soon)

### EOPF Tooling Guide

The [EOPF Tooling Guide](https://github.com/eopf-toolkit/eopf-tooling-guide) provides documentation for all libraries and plugins developed to support the EOPF Zarr format:

| Tools                   | Description                                  | Status         |
| ----------------------- | -------------------------------------------- | -------------- |
| Python Integration      | Python access to EOPF Zarr using STAC        | In Development |
| GDAL Zarr Driver        | Enhanced GDAL driver for EOPF Zarr           | Planned        |
| QGIS Plugin             | QGIS integration for EOPF Zarr               | Planned        |
| R Integration           | R access to EOPF Zarr using STAC             | In Development |
| Julia Integration       | Julia access to EOPF Zarr using STAC         | Planned        |
| TiTiler Multidim        | Multidimensional data support for TiTiler    | In Development |
| Stackstac Optimizations | Enhanced Stackstac for EOPF                  | Planned        |

### EOPF Sentinel Zarr Sample Service

Explore sample datasets and experiment with our notebooks at the [EOPF Sentinel Zarr Sample Service](https://zarr.eopf.copernicus.eu/).

## Case Studies

We're developing both technical and thematic case studies that demonstrate the power of EOPF Zarr:

### Technical Case Studies
* Zarr with QGIS
* Zarr with R
* EOPF and STAC (xpystac)
* Multi-scale Zarr
* Dataset screening with rio-tiler and lonboard

### Thematic Case Studies
* Monitoring coastal dynamics in cloud-prone regions using Sentinel-1
* African rangeland monitoring using Sentinel-2 / Sentinel-3 fusion
* Wildfire assessment with Sentinel-3 and Sentinel-2 data

## The Team Behind EOPF Toolkit

The EOPF Toolkit is developed by a consortium of leading organizations in the Earth observation space:

* [Development Seed](https://developmentseed.org/)
* [thriveGEO](https://thrivegeo.com/)
* [Sparkgeo](https://sparkgeo.com/)

Together with a group of champion users, we're creating user-friendly resources that showcase the use of Zarr format Sentinel data for applications across multiple domains.

## Get Involved

We welcome you to join this community effort:

* 🌟 Follow us here on [GitHub](https://github.com/eopf-toolkit)
* 🔍 Explore [EOPF 101](https://eopf-toolkit.github.io/eopf-101/)
* 🚀 Participate in the EOPF Toolkit Notebook Competition (Oct 2025 - Jan 2026) - [Express your interest](https://thrivegeo.com/eopf-toolkit-competition/)
* 💡 Provide feedback and feature requests
* 🤝 Contribute to our open-source libraries and plugins

## Development Timeline

* ✅ **June 2025**: Launch of first version during Living Planet Symposium
* 🔄 **2nd half of 2025**: Development of thematic case studies with champion users
* 🏆 **Oct 2025 to Jan 2026**: EOPF Notebook competition
* 📢 **Throughout**: Communications and outreach through social media and conferences

---

The EOPF Toolkit is a project funded by the [European Space Agency](https://www.esa.int/).
