# AI-Generated vs. Human-Captured Image Classification Using CNN

---

## Project Introduction

### 1. Aim of Project
Develop a Convolutional Neural Network (CNN) model to classify images into AI-generated and human-captured categories, aiming for accurate and efficient differentiation.

### 2. Business Value
- **Content Moderation**: Identify AI-generated images for online platform quality control.
- **Copyright Protection**: Detect potential copyright violations in AI-generated images.
- **Fake News Detection**: Identify misleading AI-generated visuals in news and social media.
- **Enhanced Content Recommendation**: Improve personalization in content recommendations.
- **User Experience Improvement**: Enhance platform reliability and safety.

### 3. Key Metrics
- **Classification Accuracy**: Measure of correctly classified images.
- **Model Loss (Cost Function)**: Indicator for model improvement.

### 4. Data Collection
- **AI-Generated Images**: Sourced from [GenCraft](https://gencraft.com/explore), [Pixabay](https://pixabay.com/images/search/ai%20generated/), and web scraping [code](https://colab.research.google.com/drive/1gxtUKNgD7FdH99r0nI1W8lpf25cgmfS5?usp=share_link).
- **Validation Set for AI Images**: From [DeviantArt](https://www.deviantart.com/sono2000/gallery).
- **Human-Generated Images**: From [COCO Dataset](https://cocodataset.org/#download).

### Training Details
- Utilized Google Colab for its computational capabilities.
- Gathered 10,000 images (5,000 each of AI-generated and human-captured).
- Data split: 80:20 for training and testing, with 500 images per category for validation.

### Model Architecture
- Multiple convolutional layers with max-pooling.
- Three fully connected layers, culminating in a binary classification output.

### Training and Evaluation
- Functions for model training and evaluation defined.
- Hyperparameter tuning for learning rate and batch size.

### Project Outcomes
- Initial model achieved around 80.15% accuracy on validation dataset.
- Testing on unseen data showed approximately 77.80% accuracy.
- Live inference with DALL·E-generated images demonstrated real-time classification capabilities.
- Hyperparameter tuning explored to optimize model performance.
