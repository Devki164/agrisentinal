# Hyperspectral Crop Diagnostics Tool 🛰️🌱

An AI-powered remote sensing application designed to process hyperspectral data cubes, execute automated vegetation masking, and perform sub-pixel crop health analysis.

## Features
*   **Hyperspectral Data Handling:** Dynamic reading and parsing of `.hdr` header files and image metadata (Lines, Samples, and Spectral Bands).
*   **Automated Background Masking:** Built-in NDVI thresholding to filter out non-vegetation artifacts like soil and background noise.
*   **Unified AI Analytics:** Processes over 100,000+ individual leaf pixels simultaneously to predict localized crop stress, disease, or nutrient deficiencies.
*   **Diagnostic Visualization:** Generates and renders high-resolution 2D spectral health heatmaps for precise target mapping.

## Tech Stack
*   **Python 3**
*   **Spectral Python (SPY):** For processing hyperspectral image data.
*   **NumPy:** For high-performance multi-dimensional array manipulations.
*   **Matplotlib:** For rendering final geospatial diagnostic heatmaps.

## Getting Started

### Installation
Install the primary dependency using pip:
```bash
pip install spectral
