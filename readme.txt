This project demonstrates how to create a local AI chatbot that can read and answer questions from PDF files. Using Python, LangChain, a local LLM (GPT4All), and Flask for the web interface, you can upload any PDF and start chatting with it all offline, without using any third-party APIs.

Features

Upload and preview PDF files.
Ask questions about the PDF and get contextual answers.
All processing is done locally with no internet or API required.
Real-time typing effect for responses.
Clear chat functionality.


Tech Stack


Python 3.10+
Flask
LangChain
GPT4All (local model)
FAISS (for vector similarity search)
HuggingFace Sentence Transformers
HTML + CSS + JavaScript


Installation Steps

Clone or download the project folder.
Install dependencies:
pip install -r requirements.txt
Download the local LLM model (e.g. I used, ggml-gpt4all-j-v1.3-groovy.bin) and place it in the models folder.
Run the Flask app:
python app.py
Open your browser and visit http://127.0.0.1:5000