# Multispectral Image Analysis using Principal Component Analysis (PCA)

## Overview
This project performs Principal Component Analysis (PCA) on multispectral images to analyze and visualize the variance across different spectral bands. The process includes:
- Loading RGB and grayscale multispectral images
- Splitting images into individual color channels
- Constructing a multi-band image array
- Computing covariance and eigenvalues for PCA
- Transforming the data into principal components
- Visualizing the original spectral bands and the resulting principal components

## Features
- Reads and processes multispectral images (RGB and additional bands)
- Splits RGB images into individual Red, Green, and Blue channels
- Constructs a 7-band image array for analysis
- Applies PCA to extract principal components
- Generates visualizations for both original spectral bands and transformed components
- Computes variance retention for each principal component
- Compares RGB image with the transformed PCA representation

## Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/multispectral-pca.git
cd multispectral-pca

# Install dependencies
pip install numpy pandas matplotlib seaborn opencv-python
```

## Usage
```bash
# Run the script
python pca_multispectral.py
```

Ensure that your image files are placed in the `images/` directory and named as follows:
- `image.png`
- `image1.png`, `image2.png`, ..., `image7.png`

## Results & Visualizations
- **RGB Image and its Individual Channels**
- **Spectral Bands Representations**
- **Principal Component Images**
- **Variance Retention Graph**
- **Comparison Between RGB and PCA Transformed Image**

## Example Output
```python
# Example snippet for visualization
import matplotlib.pyplot as plt
plt.imshow(img, vmin=0, vmax=255)
plt.axis('off')
plt.show()
```

## License
This project is open-source and available under the MIT License.

## Acknowledgments
- OpenCV for image processing
- NumPy and Pandas for numerical computations
- Matplotlib and Seaborn for data visualization

---
Feel free to contribute or suggest improvements!
