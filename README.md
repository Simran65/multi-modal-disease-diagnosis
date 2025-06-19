# 🧠 Multi-modal Disease Diagnosis using AI
This project explores the use of **AI techniques** (Machine Learning and Deep Learning) to diagnose diseases by combining **tabular patient health records** and **chest X-ray images**.

## 🩺 Diagnosed Diseases
- Heart Disease
- Diabetes
- Stroke
- Pneumonia

## 📊 Datasets Used

### 1. Tabular Data (Heart Disease, Diabetes, Stroke)
Features:
- HighBP, HighChol, BMI, Smoking, Physical Activity, Age, etc.

### 2. X-ray Image Data (Pneumonia Detection)
- 5,856 Pediatric Chest X-ray Images  
- Image Size: 28x28 (grayscale)


## 🛠️ Methodology

### Tabular Data
- **Preprocessing:** Missing values handling, normalization, feature selection
- **Models:** Logistic Regression, Decision Trees, Random Forests
- **Evaluation:** Accuracy, Precision, Recall, F1 Score

### Image Data
- **Model:** CNN for pneumonia detection
- **Preprocessing:** Resizing, normalization
- **Generative Models:** VAE / GAN for noise removal and enhancement
- **Evaluation:** Accuracy, SSIM, RMSE


## 📈 Results

- High accuracy achieved across both modalities
- CNN with generative preprocessing improved pneumonia classification
- Demonstrated the power of hybrid AI systems in healthcare diagnostics


## 🔐 Ethical Considerations

- Ensuring patient data privacy and model transparency
- Models assist clinicians — **not replace** them


## 🚀 Future Work

- Expand dataset (more X-rays, genetic data)
- Real-time deployment possibilities
- Advanced generative AI for noisy image correction


🧬 *"AI will not replace doctors, but doctors using AI will replace those who don't."*

