# chatgpt  

# GPT Language Model 🚀

A simple, PyTorch-based implementation of a **GPT-style language model** trained on character-level data. This project explores the basics of the Transformer architecture and generates text based on input context. 

## Features ✨
- Transformer architecture with multi-head self-attention.
- Trainable on any character-level dataset.
- Generates coherent text based on input sequences.
- Trained models are saved in the `models` folder.

## Setup 🔧

1. **Clone the repository**:
    ```bash
    git clone https://github.com/bibasrairockz/chatgpt.git
    cd chatgpt
    ```

2. **Install dependencies**:
    ```bash
    pip install torch
    ```

3. **Prepare your dataset**:  
    Add a text file named `input.txt` for training.

## Training the Model 🏋️

Run the training script:
```bash
python gpt.py
```
Text Generation 📝
After training, generate text using:

```bash
python gpt.py --generate
```

Example Output 🌟
ROMEO:
What light through yonder window breaks?
It is the east, and Juliet is the sun.

![image](https://github.com/user-attachments/assets/ac4ca37c-4f4a-4e51-80ed-137d2ed0013d)  

  
