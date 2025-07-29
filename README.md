
# 🚗 Vehicle Damage Detection Web App

An interactive web application that allows users to **drag and drop a car image** and instantly identifies the **type of visible damage**. Designed with ease-of-use and real-world applicability in mind, the app leverages deep learning to provide fast, reliable classification.

> ⚠️ Note: The model is trained specifically on **third-quarter front and rear views** of vehicles. For accurate predictions, input images should capture these angles.

![App Screenshot](app_screenshot.jpg)

---

### 🧠 Model Architecture

- Utilized **ResNet50** for transfer learning.
- Trained on a dataset of approximately **1,700 images** across **6 distinct classes**:
  1. Front – Normal  
  2. Front – Crushed  
  3. Front – Breakage  
  4. Rear – Normal  
  5. Rear – Crushed  
  6. Rear – Breakage  
- Achieved **~80% validation accuracy**.

---

### ⚙️ Setup Instructions

1. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

2. **Launch the Streamlit App**
   ```bash
   streamlit run app.py
   ```
