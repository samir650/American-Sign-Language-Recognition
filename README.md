# American Sign Language (ASL) Alphabet and Common Words Recognition

This project utilizes **MediaPipe** and **Machine Learning** to recognize American Sign Language (ASL) alphabets and some common words in real-time.

## 📌 Features
- 🖼 **Image Collection**: Capture images of ASL gestures.
- 📊 **Dataset Creation**: Process images into a dataset using MediaPipe.
- 🤖 **Model Training**: Train a **RandomForest** classifier on hand landmark data.
- 🎥 **Real-time Inference**: Detect and classify ASL signs using a webcam.

## 📂 Repository Structure
```
ASL-Sign-Recognition/
│── data/                    # Collected image dataset (excluded from Git)
│── models/                  # Trained model files
│── scripts/                 # Python scripts for different tasks
│   ├── collect_imgs.py        # Script to collect sign images
│   ├── create_dataset.py      # Process images into dataset
│   ├── train_classifier.py    # Train a RandomForest model
│   ├── inference_classifier.py # Real-time sign detection
│── requirements.txt          # Dependencies list
│── README.md                 # Project documentation
│── .gitignore                # Ignore unnecessary files
```

## 🔧 Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/ASL-Sign-Recognition.git
   cd ASL-Sign-Recognition
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
   
## 🚀 Usage
### 1️⃣ Collect Images
Run the script to capture images for each ASL sign:
```sh
python scripts/collect_imgs.py
```
Press `Q` to start capturing images.

### 2️⃣ Create Dataset
Convert images into structured dataset:
```sh
python scripts/create_dataset.py
```

### 3️⃣ Train Classifier
Train the RandomForest model:
```sh
python scripts/train_classifier.py
```

### 4️⃣ Run Real-time Inference
Detect ASL signs in real-time using a webcam:
```sh
python scripts/inference_classifier.py
```
Press `Q` to exit.

## 🛠 Dependencies
- Python 3.x
- OpenCV
- MediaPipe
- NumPy
- Scikit-Learn

## 🚀 Future Improvements
- Expand dataset with more ASL words.
- Improve model accuracy using deep learning.
- Add a GUI interface for accessibility.

## 📜 License
This project is open-source under the **MIT License**.

---
### **🙌 Contributing**
Contributions are welcome! Feel free to fork this repository and submit a pull request with improvements.

