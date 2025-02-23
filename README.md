# NutriMind
AI powered food ingredient analysis and health assistant with OCR and personalized recommendations with the LLMs

# Overview

NutriMind is an AI-powered application that helps users make healthier food choices by analyzing food labels and providing personalized dietary recommendations. It uses Optical Character Recognition (OCR) to extract text from food images and Large Language Models (LLMs) to understand nutritional information and match it to individual health profiles.

# Features

Food Label Scanning: 
Upload images of food labels for text extraction.

Nutritional Analysis:
Understands ingredient lists and breaks down nutrient content.

Personalized Recommendations: 
Tailored advice based on the user’s health conditions and dietary needs.

Multi-Model Support:
Switch between multiple models to optimize performance.

Simple User Interface:
Clean and intuitive GUI for seamless usage.

# Installation
# 1. Clone the Repository :
              git clone https://github.com/santhiyagithub/NutriMind.git
              cd NutriMind
# 2. Create a Virtual Environment
             python -m venv venv
             source venv/bin/activate  # On Windows: venv\Scripts\activate
# 3. Install Dependencies
             pip install -r requirements.txt

# Usage 
# 1.Run the Application:
            python src/foodrecommendation.py

# 2.Upload food label image: 
            choose a image through the GUI

# 3. View results:
             extracted text , analyszed nutrients and recommendations will be displayed instantly.

# License

This project is licensed under the MIT License.
