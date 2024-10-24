# Coral Type Detection using DETR

## Overview
This project implements a coral type detection system using Detection Transformer (DETR) to identify and classify two types of corals:
- Staghorn Coral
- Elkhorn Coral

## Project Description
This computer vision project utilizes the Detection Transformer (DETR) architecture to automatically detect and classify coral types from images. The system is specifically trained to distinguish between Staghorn and Elkhorn corals, which are important species in marine ecosystems. DETR treats an object detection problem as a direct set prediction problem with the help of an encoder-decoder architecture based on transformers. 

## Dataset
The dataset consists of labeled images of two coral types:
- Staghorn coral images
- Elkhorn coral images

The labels are stored in JSON files corresponding to each image, using a standardized format for object detection.

## Model
- **Architecture**: Detection Transformer (DETR)
- **Base Model**: Pre-trained DETR model fine-tuned on coral dataset
- **Output**: Binary classification (Staghorn vs Elkhorn)

## Results

### Detection Performance
- **Intersection over Union (IoU)**: > 0.7
- **Model Accuracy**: 99%
- **Object Detection**: Successfully identifies and distinguishes between Staghorn and Elkhorn corals

### Coral Growth Analysis
The system not only detects coral types but also analyzes their growth patterns by:
1. Measuring coral area in previous stage and current stage images
2. Calculating growth rate percentage based on the measurement

## Acknowledgments
- Facebook AI Research for the DETR architecture
- Coral Restoration Foundation for providing the Coral dataset

