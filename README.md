# Handwritten Text Recognition Using OpenCV and Tesseract

## 📌 Overview
This project focuses on recognizing handwritten text using OpenCV and Tesseract OCR. It processes images of handwritten text and converts them into machine-readable text. The primary objective is to automate the extraction of handwritten content from scanned documents, notes, and images.

## 📊 Methodology
1. **Image Preprocessing**: Noise removal, thresholding, and contour detection using OpenCV.
2. **Character Segmentation**: Identifying and isolating individual characters or words.
3. **Optical Character Recognition (OCR)**: Using Tesseract OCR to extract text from processed images.
4. **Post-processing**: Cleaning and refining the extracted text for improved readability and accuracy.

## 📂 Project Structure
```
/HandwrittenTextRecognition
├── sample1.jpeg               # Sample handwritten image
├── sample2.jpg                # Sample handwritten image
├── sample3.jpeg               # Sample handwritten image
├── handwritten_text_recognition.ipynb  # Jupyter Notebook with code
├── requirements.txt           # Required dependencies
├── README.md                  # Project documentation
```

## ⚙️ Setup Instructions
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/Srinivasareddyseelam/HandwrittenTextRecognitionUsingOpencvandTesseract.git
cd HandwrittenTextRecognitionUsingOpencvandTesseract
```

### 2️⃣ Create a Virtual Environment (Optional but Recommended)
```sh
python -m venv venv  # For Windows
source venv/bin/activate  # For macOS/Linux
venv\Scripts\activate  # For Windows
```

### 3️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```

### 4️⃣ Run the Jupyter Notebook
```sh
jupyter notebook handwritten_text_recognition.ipynb
```

## 🎯 Features
✅ Preprocessing of handwritten images using OpenCV  
✅ Text extraction using Tesseract OCR  
✅ Handles various handwriting styles  
✅ Works on scanned documents, notes, and images  
✅ Easy-to-use and extend for different applications  

## 🚀 Future Improvements
- Improve OCR accuracy using deep learning models
- Support for multiple languages
- Deployment as a web application for online text recognition
- Integration with mobile applications for real-time text recognition

## 👨‍💻 Contributors
- **Srinivasareddy Seelam** - [GitHub Profile](https://github.com/Srinivasareddyseelam)
