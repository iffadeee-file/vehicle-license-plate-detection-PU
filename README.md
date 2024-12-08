# Vehicle License Plate Detection Project

This project uses Google Vision API to detect vehicle license plates from images. By utilizing Optical Character Recognition (OCR), this application extracts text from an image and provides vehicle-related information such as type and color.

## Key Features
- Utilizes Google Vision API for text detection (OCR) in images.
- Detects vehicle license plates from uploaded images.
- Provides vehicle-related information, including type and color.
- Outputs the result in a JSON format for easy integration.

## Prerequisites
Before running this project, make sure you set up Google Cloud Vision API credentials. Follow these steps:

1. **Create a Project in Google Cloud Console**:
   - Go to [Google Cloud Console](https://console.cloud.google.com/).
   - Create a new project and enable the Vision API.

2. **Create API Key**:
   - In Google Cloud Console, go to **API & Services > Credentials**.
   - Create a **Service Account Key** with the JSON format.

3. **Install Dependencies**:
   - This project requires Python and some libraries. Install them using:
     ```bash
     pip install google-cloud-vision
     pip install google-generative-ai
     ```

4. **API Credentials**:
   - After getting the API credentials JSON file (e.g., `YOUR_JSON.json`), save it in the project directory.

## Installation and Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/username/license-plate-detection.git
   cd license-plate-detection
