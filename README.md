# Image Stitching

This repository contains the code and resources for the project "Medical Image Stitching using SIFT and SURF". The objective of this project was to stitch together medical images using the SIFT and SURF methods.

## Overview

The project involves the following steps:

1. **Keypoint Detection and Description:** Using SIFT or SURF to find keypoints and descriptors in both the source and stitching images
2. **Keypoint Matching:** Using brute force matching to find matches between the keypoints of the two images
3. **Ratio Test:** Filtering out false matches using the ratio test
4. **Homography Matrix Calculation:** Calculating the homography matrix using the matched keypoints
5. **Image Warping and Overlay:** Warping the stitching image according to the homography matrix and overlaying it on the source image
6. **Multiple Image Stitching:** Repeating the process with the resultant image becoming the new source image for stitching the next image

## Repository Content

- **images** Contains sample images used for stitching.
- **ImageStitching.ipynb:** Contains the code for image stitching in a Jupyter Notebook.

## Code Usage

To use the code in this repository, follow these steps:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/tajallahshafqat/Image-Stitching.git
   cd Image-Stitching
   ```

2. **Install Dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook:**
   Open `ImageStitching.ipynb` in Jupyter Notebook or Jupyter Lab to explore and run the code for image stitching.

## Presentation Slides

For more detailed information on the project, including the objectives, methods, challenges, and optimizations, please refer to the [presentation slides](https://docs.google.com/presentation/d/13QPoz4qGSlMWvDnbRCx_InTLWAuDxrdRRCXTH0ww4ZM/edit?usp=sharing).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
