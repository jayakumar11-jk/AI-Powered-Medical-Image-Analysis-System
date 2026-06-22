# AI-Powered-Medical-Image-Analysis-System
An AI-based web application that analyzes medical images such as X-rays, MRI scans, CT scans, and Ultrasound images using advanced AI models. The system provides diagnostic insights, key findings, and patient-friendly explanations through an interactive web interface.

🚀 Features
Upload medical images securely
AI-powered diagnostic analysis
Detect abnormalities and severity levels
Patient-friendly explanations
Structured medical report generation
Supports PNG, JPG, JPEG, and DICOM images
Simple and responsive Flask web interface
🛠️ Technologies Used
Python
Flask
Groq API
Llama 4 Scout Model
HTML/CSS
Markdown
📂 Project Structure
project/
│── app.py
│── templates/
│   └── index.html
│── uploads/
│── static/
│── requirements.txt
⚙️ Installation
1️⃣ Clone the Repository
git clone https://github.com/your-username/medical-image-analysis.git
cd medical-image-analysis
2️⃣ Install Dependencies
pip install -r requirements.txt
3️⃣ Run the Application
python app.py
🔑 API Configuration

This project uses the Groq API for AI image analysis.

Get your API key from:
console.groq.

Enter the API key in the application before uploading images.

📸 Supported Image Formats
PNG
JPG
JPEG
DICOM
🧠 How It Works
User uploads a medical image
Image is converted into Base64 format
AI model analyzes the image
Detailed medical insights are generated
Results are displayed in a structured report format
🎯 Objective

To provide an AI-powered assistant for preliminary medical image analysis and improve accessibility to diagnostic support for healthcare professionals and patients.

📌 Future Enhancements
User authentication system
PDF report download
Multi-language support
Cloud image storage
Real-time AI analysis improvements
