# Decontextualized Emotion Recognition

## Overview

This project explores whether emotion can be computationally recognized under decontextualized conditions.

I fine-tune a ResNet18 model on a curated facial dataset and compare predictions across original, cropped, and grayscale images to examine contextual influence.

## Dataset
	•	144 facial images
	•	6 classes: Neutral, Sad, Shocked
	•	Emotion and contextual metadata included

## Method
	1.	Fine-tune ResNet18 for 3-class emotion classification
	2.	Evaluate with validation accuracy and confusion matrix
	3.	Compare predictions under:
	•	Original image
	•	Cropped face
	•	Grayscale image

## Key Insight

Emotion predictions shift when contextual information is removed, indicating sensitivity to visual and environmental cues.
