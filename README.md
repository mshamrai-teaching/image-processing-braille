# Computer Vision Course Assignment: Braille Image Processing

## Overview

Welcome to the Braille Image Processing assignment for the Computer Vision course! In this assignment, you will be working with Braille images to extract the dots and then implement an algorithm to translate the Braille patterns into English. The focus is on using classical computer vision methods with OpenCV; neural networks are not allowed for this assignment.

### Task

You will be provided with two Braille images: `braille1.png` and `braille2.png`. Your goal is to develop a solution that accurately extracts the dots from these images and translates them into English characters.

### Getting Started

1. **Clone this repository to your local machine:**

```bash
git clone https://github.com/mshamrai-teaching/image-processing-braille
```

2. **Navigate to the project directory:**
```bash
cd image-processing-braille
```

3. **Familiarize yourself with the provided Braille images:**
* braille1.jpg
* braille2.jpg

### Guidelines
* Tools: Use classical computer vision techniques with OpenCV.
* Files:
  * braille1.jpg: First Braille image for processing.
  * braille2.jpg: Second Braille image for processing.
* Restrictions: Neural networks are not allowed for this assignment.

### Hints

* Image Preprocessing:
  * Consider converting the images to grayscale.
  * Explore thresholding techniques to enhance dot visibility.

* Dot Extraction:
  * Investigate contour detection to identify dot locations.
  * Morphological operations might be useful in separating dots.

* Translation to English:
  * Create a mapping between Braille patterns and English characters.
  * Implement a mechanism to interpret the dots and form English characters.


### Submission
Ensure your final submission includes:

* Source code (braille_processing.py or similar).
* A brief report (report.md or similar) explaining your approach and any challenges faced.
