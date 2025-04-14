# Rice Leaf Disease Classification 🌾🤖

This project uses **MobileNetV2** and **Transfer Learning** to classify rice leaf diseases using computer vision.

## 📁 Dataset

Images are categorized into 3 classes of rice leaf diseases. (Dataset stored on Google Drive — not uploaded here due to size constraints.)

## 📊 Technologies Used

- TensorFlow & Keras
- MobileNetV2
- Google Colab
- Matplotlib / Seaborn
- scikit-learn (for confusion matrix & classification report)

## 🧠 Model Highlights

- Used `ImageDataGenerator` for augmentation
- 80/20 train-validation split
- Fine-tuned classification head on MobileNetV2
- Visualized training curves, confusion matrix & sample predictions

## 📈 Training Plot

Plots for accuracy and loss during training and validation.

## ✅ Results

Model performs well across all 3 classes with high validation accuracy.

## 🚀 How to Run

1. Upload dataset to your Google Drive.
2. Update the dataset path in the notebook.
3. Run all cells in `rice_leaf_classification.ipynb`.

## 📄 Output

- Trained model saved as `.keras` file
- Evaluation using confusion matrix & classification report

## 📌 Sample Output

![confusion_matrix](path_to_image_if_uploaded)

---

Feel free to fork and use this project for your own leaf disease classification tasks!
