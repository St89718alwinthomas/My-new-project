# 🌿 LeafyDoctor: AI-Powered Plant Disease Identifier

> Final project for the Building AI course (by Reaktor & University of Helsinki)

---

## Summary

**LeafyDoctor** is a smart assistant that helps farmers and gardeners identify plant diseases by analyzing leaf images using AI. It quickly detects common plant diseases and offers actionable treatment suggestions — all within seconds.

---

## 🌱 Background

Plant diseases cause massive agricultural losses every year. Unfortunately, early diagnosis is often hard in rural areas due to a lack of access to expert plant pathologists. LeafyDoctor aims to bridge that gap.

### Problem it solves:
- 🧪 20–40% of crops are lost annually due to diseases.
- 👨‍🌾 Small-scale farmers may not have access to agricultural experts.
- ⚠️ Visual symptoms can be misleading or hard to recognize without help.

I was inspired to build this project from my curiosity about AI for good — and its power to assist communities in need.

---

## 🚀 How It’s Used

1. User takes or uploads a photo of an infected leaf.
2. The image is processed using a convolutional neural network.
3. The model classifies the disease and returns treatment tips.

### Typical Users:
- 🌾 Smallholder farmers
- 📸 Agriculture students & researchers
- 🌍 Areas with limited internet access (offline version in development)

### Example:
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b5/Tomato_blight_-_leaves.jpg/800px-Tomato_blight_-_leaves.jpg" width="300" alt="Leaf Disease Example">

Disease: Early Blight
Confidence: 94%
Recommendation: Remove infected leaves. Apply a fungicide with chlorothalonil. Avoid overhead watering.

---

## 🧠 Data Sources & AI Methods

LeafyDoctor is powered by transfer learning on top of a ResNet50 model, trained using thousands of labeled leaf images.

### Data:
- [PlantVillage Dataset](https://plantvillage.psu.edu/)
- Additional open-source agricultural image datasets

| Model        | Accuracy |
|--------------|----------|
| ResNet50     | 94%      |
| MobileNetV2  | 91%      |

---

## ⚠️ Challenges

### Current Limitations:
- ❌ Cannot yet detect nutrient deficiencies (only diseases)
- 🌫️ Accuracy may drop with poor lighting or blurry images
- 🌍 Currently supports only 10 plant species

### Ethical Considerations:
- AI results should not replace expert diagnosis entirely
- Misdiagnosis could lead to unnecessary pesticide use

---

## 🔭 What's Next?

Here’s how LeafyDoctor can grow:
- 📱 Mobile app with offline support
- 🌾 Add more regional crop diseases
- 📊 Build explainable AI layer for transparency
- 🤝 Collaborate with agri-extension programs

### Needs:
- Diverse datasets from different regions
- UI/UX and mobile developers
- Field testing with farmers

---

## 🙌 Acknowledgments

- Inspired by the [PlantVillage Project](https://plantvillage.psu.edu/)
- Image credit: [Tomato blight by Scot Nelson](https://commons.wikimedia.org/wiki/File:Tomato_blight_-_leaves.jpg) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
- Huge thanks to the [Building AI](https://buildingai.elementsofai.com/) course creators

---
