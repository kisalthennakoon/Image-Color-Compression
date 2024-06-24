# Image Color Compression with Custom K-Means Clustering

This project compresses images by reducing the number of colors using a custom K-means clustering algorithm. The algorithm identifies the most frequent colors in an image and compresses it to a specified number of colors, such as 16 colors for JPG images.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Usage](#usage)
- [License](#License)

## Introduction

This project implements an image color compression technique using a custom K-means clustering algorithm which I has been developed myown to clustering. The algorithm creates centroids of clusters and assigns samples to the nearest centroid to identify the most frequent colors in an image. The compressed image is then created using these identified colors.

## Features

- **Custom K-Means Clustering Algorithm:** Implements a custom K-means algorithm to create centroids and assign samples.
- **Image Color Compression:** Compresses images by reducing the number of colors.

## Requirements

To run this project, you need the following libraries:

- numpy
- matplotlib
- scikit-learn

## Usage
1. Open the Jupyter Notebook in Weather Prediction file.
2. Install all the requirements mentioned in under the requarements title
3. Run all cells to and comare the images.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

