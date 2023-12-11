# Protein Coordinate Analysis

## Overview
This Python script is designed to automate the analysis of protein coordinates extracted from a photodetector. It involves several steps of data processing, image analysis, and statistical evaluation.

## Features
- **Data Import**: Reads coordinate data from CSV files.
- **Visualization**: Generates scatter plots for visual analysis.
- **Image Processing**: Includes thresholding and connected components analysis for identifying regions of interest.
- **Region Analysis**: Filters regions based on size, labels components, and extracts properties.
- **Ellipse Fitting**: Fits ellipses to identified regions and performs image transformations.
- **Cell Expansion**: Expands the identified regions to boundaries or adjacent cells.
- **Spatial Analysis**: Utilizes spatial data structures for proximity analysis.

## Dependencies
- NumPy
- Matplotlib
- OpenCV
- scikit-image
- scipy

## Usage
1. **Data Reading**: Modify `filename` to point to your CSV file.
2. **Visualization**: Use `plotar()` to generate initial scatter plots.
3. **Image Processing**: Follow the script to perform histogram analysis, thresholding, and connected component analysis.
