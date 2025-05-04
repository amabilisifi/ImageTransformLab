# ImageTransformLab

Welcome to **ImageTransformLab**, a repository for Assignment 2 of the Digital Image Processing course (Spring 2025, Department of Mathematical Sciences). This project explores advanced image processing techniques, including Discrete Fourier Transform (DFT), Discrete Cosine Transform (DCT), and image cartoonization using bilateral filtering.

## Project Overview

This repository contains a Jupyter notebook (`assignment2.ipynb`) implementing solutions for:
- **DFT Transformation**: Applying and inverting DFT and DCT transforms.
- **Image Cartoonization**: Using edge detection and bilateral filtering to create cartoon effects.

## Getting Started

### Prerequisites
- Python 3.8+
- Jupyter Notebook
- Required libraries:
  ```bash
  pip install numpy opencv-python matplotlib scikit-image scipy
  ```

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/amabilisifi/ImageTransformLab.git
   cd ImageTransformLab
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook src/assignment2.ipynb
   ```

### File Structure
- **images/**: Input images (e.g., `Q2-input.jpg`).
- **images/output/**: Output images (e.g., `Q2-output-edges.jpg`).
- **assignment2.ipynb**: Jupyter notebook with all implementations.
- **requirements.txt**: Lists Python dependencies.
- **LICENSE**: MIT License.

## Usage
1. Place input images in `images/input/`.
2. Open `src/assignment2.ipynb` and run the cells to generate outputs.
3. Outputs will be saved in `images/output/` (not tracked by Git).

## Results
The notebook generates the following outputs:
- **Q1**: DFT and DCT transformed images (to be visualized).
- **Q2**: Edge-detected image, bilateral-filtered image, and cartoonized images for α = 0, 0.25, 0.5, 1.

## Contributing
This is a student project, but feedback is welcome! Open an issue or submit a pull request for suggestions.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Course: Digital Image Processing, Spring 2025
- Instructor: [Instructor Name]
- Student: Nazanin Yousefi, 401110172
