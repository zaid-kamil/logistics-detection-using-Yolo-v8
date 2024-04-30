# Logistics > 2023-10-23 4:01pm
https://universe.roboflow.com/large-benchmark-datasets/logistics-sz9jr

Provided by a Roboflow user
License: CC BY 4.0

## Logistics Pre-trained Object Detection Model

Pre-trained models are trained on large datasets until they achieve good generalization, meaning they can recognize patterns effectively. "pre-trained" indicates that the model has already undergone training on a substantial dataset, often a generic one, and is ready for fine-tuning on a specific task with a smaller dataset. The Logistics Object Detection Base Model is a pre-trained model hosted on Roboflow Universe, created to be a strong starting point for custom training on logistics-specific object detection tasks. This model is built on a dataset of 99,238 images across **20 logistics-focused classes**, collected from various projects on Roboflow Universe. Part of this dataset was auto-labeled using the [Autodistill DETIC](https://github.com/autodistill/autodistill-detic) tool from Roboflow, helping to achieve a mean Average Precision (mAP) of 76%.

**Classes:**

*  Barcode, QR Code 
*  Car, Truck, Van
*  Cardboard Box, Wood Pallet, Freight Container
*  Fire, Smoke
*  Forklift
*  Gloves, Helmet, Safety Vest
*  Ladder
*  License Plate
*  Person
*  Road Sign, Traffic Cone, Traffic Light

**Current Status:**
The model has achieved a mAP of 76%, marking its readiness as a checkpoint for further custom training. It aims to shorten the development cycle, facilitating better model performance in specific logistics scenarios.
 