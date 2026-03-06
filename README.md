# Arabic Text Generation using AraGPT2

## Overview

This project demonstrates **Arabic text generation** using a transformer-based language model.
The model is trained on Arabic text from Wikipedia and is capable of generating coherent Arabic sentences based on a given prompt.

The project uses the **AraGPT2 model**, a GPT-2 based architecture designed for Arabic Natural Language Processing tasks.

---

## Project Goals

The goal of this project is to understand and implement **Text Generation in Natural Language Processing (NLP)** by:

* Loading an Arabic dataset
* Preprocessing and tokenizing the text
* Fine-tuning a pretrained language model
* Generating Arabic text from prompts

---

## Technologies Used

* Python
* PyTorch
* Hugging Face Transformers
* Hugging Face Datasets
* Google Colab

---

## Dataset

The dataset used for training is **Arabic Wikipedia**.

It is loaded directly from Hugging Face datasets:

wikimedia/wikipedia – Arabic version

Only a small percentage of the dataset is used for experimentation.

---

## Model

The model used in this project is:

AraGPT2 (aubmindlab/aragpt2-base)

AraGPT2 is a pretrained Arabic language model based on the GPT-2 architecture and designed for Arabic NLP tasks such as:

* Text generation
* Language modeling
* Content completion

---

## Project Structure

```
arabic-text-generation-gpt2
│
├── train_model.py
├── generate_text.py
├── requirements.txt
└── README.md
```

---

## Installation

Install the required libraries:

```
pip install transformers datasets torch
```

---

## Training the Model

Run the training script:

```
python train_model.py
```

The model will:

1. Load Arabic Wikipedia dataset
2. Tokenize the text
3. Train the AraGPT2 model

---

## Generate Text

After training, you can generate Arabic text using:

```
python generate_text.py
```

Example prompt:

```
الذكاء الاصطناعي
```

Example generated output:

```
الذكاء الاصطناعي يعد من أهم التقنيات الحديثة التي تستخدم في تحليل البيانات واتخاذ القرارات في العديد من المجالات.
```

---

## Example Workflow

1. Load Arabic dataset
2. Tokenize text using AraGPT2 tokenizer
3. Train model with causal language modeling
4. Generate Arabic sentences

---

## Applications

Arabic text generation can be used in:

* Chatbots
* Content generation
* Text completion
* Smart writing assistants
* NLP research

---

## Future Improvements

Possible improvements for the project include:

* Training on a larger Arabic dataset
* Increasing training epochs
* Implementing evaluation metrics
* Building an Arabic chatbot

---

## Author
Doaa Ali
NLP Project – Arabic Text Generation

Developed as a practical implementation of **Natural Language Processing** concepts.
