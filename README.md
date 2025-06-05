# LeafyDoctor: AI-Powered Plant Disease Identifier

Final project for the Building AI course

## Summary

LeafyDoctor is an AI tool that identifies plant diseases from leaf images. It helps farmers and gardeners detect problems early and get treatment suggestions using deep learning models.

## Background

Plant diseases lead to huge losses in agriculture every year. Early detection is hard in rural areas where expert help is limited. LeafyDoctor helps bridge this gap using AI.

This project solves:
* Crop loss due to undetected diseases
* Lack of access to agricultural experts
* Misidentification of symptoms by non-experts

## How is it used?

Users take or upload a photo of a plant leaf. The AI model analyzes it and returns:
- the disease name
- confidence score
- basic treatment advice

It is mainly useful for:
- small-scale farmers
- agriculture students
- rural areas with limited expert access

## Data sources and AI methods

The AI uses a convolutional neural network (ResNet50) trained on the PlantVillage dataset, which contains labeled images of healthy and diseased leaves.

Data:
- PlantVillage Dataset
- Other public image datasets

AI method:
- Transfer learning with ResNet50
- Image preprocessing (resizing, normalization)
- Training with 80/20 validation split

## Challenges

Limitations:
- Model accuracy drops in poor lighting
- Limited to only 10 crops and diseases
- Doesn’t handle nutrient deficiencies

Ethical issues:
- Misdiagnosis risk
- Dependency on AI without expert validation

## What next?

Future goals:
- Add more crops and disease classes
- Develop a mobile offline version
- Partner with agriculture programs for field testing

## Acknowledgments

- PlantVillage dataset
- Building AI course by University of Helsinki and Reaktor
- Tomato leaf image from Wikimedia Commons / CC BY 2.0

- git add README.md
git commit -m "Fix summary format for Building AI course"
git push origin main
