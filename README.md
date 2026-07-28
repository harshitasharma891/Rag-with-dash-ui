# RAG with Dash UI

## Overview

This project is a Retrieval-Augmented Generation (RAG) application with a Dash-based user interface. It enables users to submit queries and receive AI-generated responses using a retrieval pipeline.

## Features

- Interactive Dash UI
- Retrieval-Augmented Generation (RAG)
- Hugging Face model integration
- Tokenizer configuration
- Modular project structure

## Project Structure

```
Rag-with-dash-ui/
│
├── app.py
├── dash_app.py
├── spam_model/
├── templates/
├── static/
└── requirements.txt
```

## Installation

Clone the repository:

```bash
git clone https://github.com/harshitasharma891/Rag-with-dash-ui.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
python app.py
```

## Model File

The pretrained model (`model.safetensors`) is not included because GitHub limits individual files to 100 MB.

Download the model separately and place it inside the `spam_model` folder before running the application.

## Technologies Used

- Python
- Dash
- Hugging Face Transformers
- PyTorch
- NLP

## Author

Harshita Sharma
