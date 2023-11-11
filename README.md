# Steer My Heart
### A python generated storybook inspired by Japanese movie Drive My Car

## Introduction

This project, developed as part of 6105 data science class, focuses on implementing multiple python libraries for image processing to enhance and modify the images. 
All of the enhancment and modification were done in python. Additionally, we adopt Holistically-Nested Edge Detection (HED) network for edge and shape detection.

## Oscar Award

🏆 **In-Class Oscar Award Winner** 🏆

<details>
  <summary>Our team proudly received an in-class Oscar award for the outstanding work and creativity demonstrated in this project.</summary>
</details>


## Table of Contents

1. [Overview](#overview)
2. [Features](#features)
3. [Project Structure](#project-structure)
4. [Dependencies](#dependencies)
5. [Usage](#usage)
6. [Tech Stack](#tech-stack)
7. [Acknowledgments](#acknowledgments)
8. [Contributors](#contributors)
9. [License](#license)

## Overview

The project utilizes various image processing techniques such as brightness adjustment, blurring, and border addition have been implemented. Moreover, we applied the HED network for holistic edge detection in images. The code includes functionality to generate customized layouts, insert subtitles, and combine images, resulting in visually appealing outputs.

## Features

- Holistic Nested Edge Detection
- Image Brightening and Darkening
- Gaussian Blur Application
- Border Addition to Images
- Custom Layout Generation
- Subtitle Integration
- Image Combination

## Project Structure

```
|- code
  |- HED_network.py
  |- image_processing.py
  |- layout_generation.py
|- images
  |- scene1
  |- scene2
  |- scene3
  |- scene4
  |- scene5
|- modified_images
|- sub_images
|- subtitles
|- README.md
```

## Dependencies

- PyTorch
- NumPy
- OpenCV
- Pillow
- Matplotlib
- pandas

## Usage

1. Clone the repository:

```bash
git clone https://github.com/chethanmahindrakar/HED-and-Shape-detection.git
cd HED-and-Shape-detection
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

## Usage

1. Place images in the `images` directory, organized by scenes.
2. Update subtitle files in the `subtitles` directory.
3. Run the main script:

```bash
python main.py
```

4. Find the processed images in the `modified_images` directory.

## Tech Stack

- PyTorch
- OpenCV
- NumPy
- Pillow

## Acknowledgments

We would like to express our gratitude to [Instructor Name] for the guidance and support throughout the development of this project.

## Contributors

- [Your Name]
- [Teammate 1]
- [Teammate 2]

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
