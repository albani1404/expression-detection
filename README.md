# 🧠 Emotion Detection 
This project is an implementation of deep learning models to detect human expressions or emotions from facial images using Convolutional Neural Networks (CNN) with TensorFlow and Keras.

## 📁 Project Structure

- `detect.ipynb` - The main notebook that contains the entire emotion detection pipeline.
- The dataset consists of facial images categorized by emotion labels.

## 🔧 Technologies Used

- Python 3.x
- TensorFlow & Keras
- OpenCV
- Scikit-learn
- Matplotlib & Seaborn (visualization)
- tqdm (progress bar)

## ⚙️ Processing Flow

1. **Import Library** 
 Import all libraries required for image processing, modeling, and evaluation.

2. **Preprocessing Data**  
   - Read the image dataset
   - Resize and normalize the image
   - Split data into training and validation sets

3. **Image Augmentation** 
 Using `ImageDataGenerator` to improve model performance through data augmentation.

4. **CNN Model Architecture** 
 Using multiple layers of `Conv2D`, `MaxPooling2D`, `Flatten`, and `Dense` for image classification.

5. **Model Training** 
 The model is trained using `fit()` and saved to file if required.

6. **Model Evaluation**  
   - Display accuracy and loss graphs
   - Display confusion matrix and classification report

## 🚀 How to Run

1. Clone this repository (if it exists):
   ```bash
   git clone https://github.com/username/deteksi-emosi.git
 cd emotion-detection
 ```

2. Install the dependencies:
   ```bash
 pip install -r requirements.txt
 ```

3. Run the notebook:
   ```bash
 jupyter notebook detection.ipynb
 ```

## 📝 Note

- Image datasets are not provided in this repository. Make sure you prepare the dataset with the appropriate directory structure.
- The model can be customized to match the number of emotion classes or a more complex CNN architecture.
