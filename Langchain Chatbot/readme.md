# LaceTrace

## Description
LaceTrace is an AI-powered system designed to help detect fake shoes. This Streamlit application allows users to upload images of shoes and receive authenticity predictions, along with explanations for potentially fake shoes.

## Features
- Image upload functionality for shoe authentication
- AI-powered prediction of shoe authenticity
- Visual explanations for shoes classified as fake using LIME (Local Interpretable Model-agnostic Explanations)
- Chat interface for user queries and assistance

## Technologies Used
- Python
- Streamlit
- TensorFlow / Keras
- LangChain
- LIME (Local Interpretable Model-agnostic Explanations)
- Groq API for natural language processing

## Installation
1. Clone the repository:
git clone https://github.com/yourusername/lacetrace.git
cd lacetrace
Copy
2. Install the required packages:
pip install -r requirements.txt
Copy
3. Set up your Groq API key in the environment variables or directly in the code.

## Usage
1. Run the Streamlit app:
streamlit run app.py
Copy
2. Open your web browser and navigate to the local URL provided by Streamlit (usually http://localhost:8501).

3. Upload an image of a shoe using the file uploader.

4. View the prediction result and any explanations for fake classifications.

5. Use the chat interface in the sidebar for additional queries or assistance.

## Model
The shoe authentication model is a CNN model trained to classify shoes into four categories:
- Authentic Air Force 1
- Authentic Air Jordan
- Fake Air Jordans
- Fake Air Force 1

The model file (`my_model.hdf5`) should be placed in the appropriate directory as specified in the code.

## Contributors
- Ishan
- Shiya