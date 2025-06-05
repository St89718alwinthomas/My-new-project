# LeafyDoctor: AI-Powered Plant Disease Identifier

Final project for the Building AI course

## Summary

LeafyDoctor is an AI tool that identifies plant diseases from leaf images. It uses deep learning to detect common crop diseases and offers treatment advice to help farmers make better decisions faster.

## Background

Plant diseases cause significant crop losses globally, and many farmers lack access to expert diagnosis. This project uses AI to make plant disease detection accessible to all, especially in remote areas.

Problems it solves:
* Crop loss due to late or missed disease detection
* Lack of agricultural experts in rural areas
* Difficulty identifying visual symptoms without training

## How is it used?

Users take or upload a photo of a leaf. The AI model then analyzes it and identifies any disease, giving a confidence score and recommended actions.

Ideal for:
* Farmers and home gardeners
* Agriculture students
* Areas with limited expert access

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b5/Tomato_blight_-_leaves.jpg/800px-Tomato_blight_-_leaves.jpg" width="300">

Example:
Disease: Early Blight
Confidence: 94%
Recommendation: Apply fungicide with chlorothalonil. Avoid overhead watering.

markdown
Copy
Edit

## Data sources and AI methods

The model is based on ResNet50 fine-tuned using the PlantVillage dataset.

Data:
* [PlantVillage Dataset](https://plantvillage.psu.edu/)
* Public agricultural image sets

| Model        | Accuracy |
|--------------|----------|
| ResNet50     | 94%      |
| MobileNetV2  | 91%      |

## Challenges

Limitations:
* May misidentify overlapping symptoms
* Doesn’t cover nutrient deficiencies
* Struggles with poor lighting or blurry images

Ethical Considerations:
* Meant to assist, not replace experts
* Incorrect diagnosis can lead to misuse of chemicals

## What next?

Future improvements:
* Offline mobile app
* Add more plant types and regional disease variations
* Collaborate with agricultural experts for validation

## Acknowledgments

* [PlantVillage Project](https://plantvillage.psu.edu/)
* [Tomato blight image by Scot Nelson](https://commons.wikimedia.org/wiki/File:Tomato_blight_-_leaves.jpg) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* University of Helsinki & Reaktor for the Building AI course
