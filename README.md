# LLM-implementation-from-scratch , GPT-Based Chatbot Assistant with OpenWebText

This repository contains a chatbot assistant powered by a Generative Pre-trained Transformer (GPT) language model trained on the OpenWebText dataset. The chatbot interacts with users in real-time through a command-line interface.

## Purpose
The purpose of this project is to understand and learn the core concepts and basics of working with GPT-based language models. It involves data extraction from the OpenWebText dataset, training a GPT model, and creating an interactive chatbot interface for users to engage in conversation.

## Development Process
1. **Data Extraction**: Text data is extracted from the OpenWebText dataset using Python scripts.
2. **Model Training**: The GPT language model is trained on the extracted data using PyTorch.
3. **Chatbot Interface**: An interactive command-line interface is implemented for users to interact with the trained chatbot.

## Prerequisites
- Python 3.9+
- PyTorch
- tqdm
- torchtext
- Hugging Face transformers

## Installation
1. Clone this repository:
####
git clone git_repo_link
####
3. Install the required Python packages:
####
pip install -r requirements.txt
####


## Usage
1. Navigate to the project directory.
2. Run the chatbot script:
####
python chatbot.py
####
3. Enter prompts in the command-line interface to interact with the chatbot.

## Docker
A Dockerfile is provided to containerize the chatbot application. To build the Docker image and run the container:

1. Build the Docker image:
####
docker build -t gpt-chatbot
####
2. Run the Docker container:
####
docker run -it gpt-chatbot
####

## Acknowledgments
- This project was inspired by the advancements in natural language processing and the work done by the open-source community. [OpenWebText](https://skylion007.github.io/OpenWebTextCorpus/)
- [FreeCodeCamp's video on building a Large Language Model from scratch](https://youtu.be/UU1WVnMk4E8?si=YgZEOVOAaMAu9l6U)
