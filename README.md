# 🎈 Automatic Number Plate Recognition (ANPR) 🚘

An interactive and simple Streamlit-based app for automatic number plate detection and recognition. This app leverages **YOLOv5** for number plate detection and **Tesseract OCR** for text recognition, providing real-time detection from images or live video feeds.

---

## 🚀 Features

- **Number Plate Detection**: Uses YOLOv5 for efficient and accurate detection of vehicle number plates.
- **Text Recognition**: Extracts text from detected number plates using Tesseract OCR.
- **Image Upload Support**: Analyze uploaded images in popular formats (PNG, JPG, BMP, etc.).
- **Live Video Feed**: Detect and recognize number plates from webcam streams in real time.
- **User-Friendly Interface**: Powered by Streamlit for an intuitive and interactive user experience.

---

## 💻 How to Run Locally

### Prerequisites

Ensure you have the following installed:

- Python 3.7 or later
- pip (Python package installer)

### Step 1: Clone the Repository

```bash
git clone https://github.com/Abhijrathod/blank-app.git
cd blank-app

Here’s the content formatted into a proper Markdown (.md) file:

# 🎈 Automatic Number Plate Recognition (ANPR) 🚘

An interactive and simple Streamlit-based app for automatic number plate detection and recognition. This app leverages **YOLOv5** for number plate detection and **Tesseract OCR** for text recognition, providing real-time detection from images or live video feeds.

---

## 🚀 Features

- **Number Plate Detection**: Uses YOLOv5 for efficient and accurate detection of vehicle number plates.
- **Text Recognition**: Extracts text from detected number plates using Tesseract OCR.
- **Image Upload Support**: Analyze uploaded images in popular formats (PNG, JPG, BMP, etc.).
- **Live Video Feed**: Detect and recognize number plates from webcam streams in real time.
- **User-Friendly Interface**: Powered by Streamlit for an intuitive and interactive user experience.

---

## 💻 How to Run Locally

### Prerequisites

Ensure you have the following installed:

- Python 3.7 or later
- pip (Python package installer)

### Step 1: Clone the Repository

```bash
git clone https://github.com/Abhijrathod/blank-app.git
cd blank-app

Step 2: Install Requirements

Install the required Python libraries:

pip install -r requirements.txt

Step 3: Run the App

Start the Streamlit app:

streamlit run streamlit_app.py

The app will launch in your default web browser. If not, navigate to the URL displayed in the terminal (usually http://localhost:8501).
📂 Project Structure

📦 blank-app
├── 📂 .devcontainer/       # Devcontainer configuration for VS Code
├── 📂 .github/             # GitHub workflows and CI/CD pipelines
├── 📄 .gitignore           # Git ignore file
├── 📄 LICENSE              # License file
├── 📄 README.md            # Project documentation
├── 📄 requirements.txt     # Python dependencies
├── 📄 streamlit_app.py     # Main Streamlit application

📋 How to Use

    Select Input Type: Choose between "Upload Image" or "Live Video Feed."
    Upload an Image:
        Drag and drop an image or browse to upload it.
        The app will process the image, detect the number plate, and display extracted text.
    Live Video Feed:
        Enable the webcam feed.
        The app will detect and recognize number plates in real-time.
    Download Results:
        Save the processed image with detected number plates and extracted text.

🛠 Technologies Used

    Frontend: Streamlit
    Detection Model: YOLOv5 (via PyTorch Hub)
    OCR: Tesseract OCR
    Image Processing: OpenCV, PIL
    Language: Python

📜 License

This project is licensed under the Apache 2.0 License.
🏗 Future Enhancements

    Add support for batch processing of images.
    Enhance OCR accuracy for low-resolution images.
    Integrate cloud-based processing for scalability.
    Support detection in videos (uploaded files).

🙌 Contributing

Contributions are welcome! Please follow these steps to contribute:

    Fork the repository.
    Create a new branch (feature/your-feature-name).
    Commit your changes and push them to your branch.
    Open a pull request describing your changes.

📧 Contact

If you have any questions or issues with the app, feel free to reach out:

    Author: Abhijrathod
    Email: ralhanprateek@gmail.com

