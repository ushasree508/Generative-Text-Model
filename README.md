# Generative-Text-Model


## Company Details  
**Company:** CODTECH IT SOLUTIONS  
**Intern Name:** ORSU USHA SREE  
**Intern ID:** CT08TMH  
**Domain:** ARTIFICIAL INTELLIGENCE  
**Duration:** 4 WEEKS  
**Mentor:** NEELA SANTOSH  

## Overview  
This project demonstrates how to use a pre-trained GPT-2 model to generate text based on a user-provided prompt. The script loads the GPT-2 model, processes user input, and generates coherent text.  

## Requirements  
Ensure you have Python installed and install the necessary dependencies using:  

```bash
pip install torch transformers
```

## Files  
- `generate_text.py`: The main script for loading the GPT-2 model and generating text.  

## How to Use  
1. Run the script using:  

   ```bash
   python generate_text.py
   ```  

2. Modify the `user_prompt` variable in the script to test with different inputs.  

## Features  
- Uses the `transformers` library to load GPT-2.  
- Generates text with customizable parameters like `max_length`, `temperature`, and `top_p`.  
- Prevents repetitive phrases using `no_repeat_ngram_size=2`.  

