# Birth Certificate Verification System

This is a **Streamlit web application** that verifies birth certificate authenticity using **OCR, edge detection, and image analysis**.

## Fix for Deployment Issues:
If deploying on **Streamlit Cloud**, OpenCV may cause errors due to missing system dependencies (`libGL.so.1`).  
To fix this:
1. Use **`opencv-python-headless`** instead of `opencv-python` in `requirements.txt`.
2. Ensure **Tesseract OCR is available** in the environment.

## Features:
✅ Upload birth certificate images  
✅ Extract text using OCR  
✅ Detect document type  
✅ Identify serial numbers  
✅ Analyze seals/signatures  
✅ Detect tampering via pixelation analysis  
✅ Generate confidence score and validation report  

## Setup & Run Locally:
1. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
2. Run the app:
   ```sh
   streamlit run app.py
   ```

## Deployment:
To deploy on **Streamlit Cloud**:
1. Push this repository to **GitHub**.
2. Go to [Streamlit Cloud](https://share.streamlit.io/) and link the repository.
3. Deploy the app and share the link!

🚀 **Enjoy automated birth certificate verification!**
