# Reimagining-Inside-Out-2-Storybook-Creation-with-AI

## Project Overview

This project leverages Python, OpenCV, PIL (Pillow), TensorFlow, and Keras to transform scenes from Inside Out 2 into a visually enriched storybook that adopts a new cinematic genre. By combining computer vision techniques with machine learning, this project aims to deliver compelling visuals with narrative consistency.

## Key Features

1. Cinematic Visual Enhancement

Applied OpenCV's cv2.LUT() for color grading to match the new genre's aesthetic.

Utilized cv2.stylization() for artistic effects that enhance visual storytelling.

Integrated cv2.detailEnhance() for texture refinement, ensuring crisp and detailed visuals.

2. Artistic Image Transformation

Employed Pillow's Image.blend() for smooth multi-layer merging, creating seamless transitions between elements.

Used Image.transform() for precise perspective alignment to maintain visual coherence.

Enhanced contrast with ImageEnhance and implemented filtering techniques such as sharpening and edge detection.

3. Emotional Scene Classification with Deep Learning

Integrated OpenCV’s cv2.dnn.blobFromImage() for efficient feature extraction.

Developed a custom TensorFlow CNN model, fine-tuned with data augmentation and transfer learning.

Achieved high-accuracy classification of emotional scenes to maintain the story’s narrative depth and consistency.

## Tech Stack

Programming Language: Python

Computer Vision Libraries: OpenCV, PIL (Pillow)

Deep Learning Frameworks: TensorFlow, Keras
