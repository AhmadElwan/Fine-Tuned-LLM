# Fine-Tuned Llama2 on a single dataset using LoRA and QLoRA techniques


# LoRA:
Efficiently adapts pre-trained models by updating a smaller subset of parameters, reducing computational cost and memory usage while preserving model performance.

# QLoRA:
Enhances LoRA by applying quantization, further minimizing resource consumption and enabling deployment on hardware with limited capabilities without sacrificing accuracy.


# How they work:

LoRA: LoRA inserts small, trainable matrices (low-rank matrices) into the model. These matrices are much smaller than the full set of model parameters.

QLoRA: After applying LoRA's technique of using low-rank matrices, QLoRA compresses these matrices using quantization. This further reduces the model size and resource requirements.


# Dataset used in training:

Dataset Name: PiyushLavaniya/HTML_Dataset_for_LLama2_Finetuning.
Dataset Link: https://huggingface.co/datasets/PiyushLavaniya/HTML_Dataset_for_LLama2_Finetuning/viewer/default/train

- It's a small dataset (2k rows). I couldn't use a larger dataset because of the limited computational resources.
- Ii found a dataset (501k rows) to improve python coding and I tried to use it to fine-tune Llama2 using LoRA and QLoRA but I ran out of computational resources on Colab so I had to use the HTML (2k rows) dataset.
- Buying extra resources from Colab or subscribing in the pro version isn't available in Jordan.

