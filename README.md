# My_finetuned_Phi-4
Phi-4 was fine-tuned by cosmopedia dataset (https://huggingface.co/datasets/HuggingFaceTB/cosmopedia/viewer/auto_math_text/train?row=25)
# 🚀 My Hugging Face Project

[![Hugging Face](https://img.shields.io/badge/🤗-Hugging%20Face-yellow)]https://huggingface.co/Anabury/My_Finetuned_Phi-4
[![GitHub](https://img.shields.io/badge/GitHub-Repository-blue)] https://github.com/AyeniOluwatosinOlawale/My_finetuned_Phi-4

## 📌 Project Overview
This project demonstrates a fine-tuned **[My_finetuned_Phi-4]** using the **[cosmopedia dataset ]**.  
It performs **[task: e.g., text generation, classification, summarization]** efficiently.

## 💻 Model & Dataset Links
- **Hugging Face Model:** [View Model]https://huggingface.co/Anabury/My_Finetuned_Phi-4
- **Hugging Face Dataset:** [View Dataset] https://huggingface.co/datasets/Anabury/conv_dataset

## ⚙️ Installation
Clone this repo and install dependencies:
```bash
git clone [https://github.com/AyeniOluwatosinOlawale/My_finetuned_Phi-4]
cd My_finetuned_Phi-4
pip install -r requirements.txt


from transformers import AutoTokenizer, AutoModelForCausalLM

tokenizer = AutoTokenizer.from_pretrained("Anabury/My_finetuned_Phi-4")
model = AutoModelForCausalLM.from_pretrained("Anabury/My_finetuned_Phi-4")

inputs = tokenizer("Hello world!", return_tensors="pt")
outputs = model.generate(**inputs, max_length=50)
print(tokenizer.decode(outputs[0], skip_special_tokens=True))

git add README.md
git commit -m "https://huggingface.co/Anabury/My_Finetuned_Phi-4"
git push
