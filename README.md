# Chatbot with Fine-Tuned Flan T5 and LoRA
## Overview
This project demonstrates the creation and deployment of a chatbot using a fine-tuned Flan T5 model and LoRA (Learned Optimizer for Retrieval Augmentation) to enhance its responses. The chatbot is deployed as a Streamlit web application.

## Key Components
1. Machine Learning Model:

a. The machine learning model is built using the Hugging Face Transformers library.

b. It uses the "google/flan-t5-large" model for seq2seq tasks and fine-tunes it on a custom dataset for chatbot interactions.

2. LoRA Integration:

a. LoRA (Learned Optimizer for Retrieval Augmentation) is integrated into the model using the peft library.

b. It enhances the chatbot's responses by optimizing retrieval and generation.

3. Data Preprocessing:

a. The chatbot training data is preprocessed to prepare it for fine-tuning. The dataset consists of human and assistant interactions.

4. Training and Deployment:

a. The model is trained using Seq2SeqTrainer with custom training arguments.

b. It is then saved and pushed to the Hugging Face Model Hub for easy access.

5. Streamlit Web Application:

a. The chatbot is deployed as a Streamlit web application.

b. Users can input text, and the chatbot generates responses using the fine-tuned model with LoRA augmentation.

## Instructions

## Setup
1. Clone this repository to your local machine.

2. Ensure you have Python 3.6 or higher installed.

3. Install the required Python packages:

   ### pip install -r requirements.txt
   
## Training
Follow the provided code in the Jupyter notebook to fine-tune the Flan T5 model using your custom dataset. Save the model and tokenizer to the Hugging Face Model Hub.

## Deployment
Deploy the chatbot using Streamlit: streamlit run app.py

Access the chatbot via your web browser.

## Usage

Enter text in the input field and click "Generate" to interact with the chatbot.
The chatbot will respond with informative and context-aware answers thanks to LoRA integration.

## Demo
Demo Video : https://drive.google.com/file/d/1AfW9egrjFATf13Kd_KAFc96E3qRYqSJc/view?usp=sharing






