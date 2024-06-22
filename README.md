# Fine-Tuned Llama2 on a single dataset using LoRA and QLoRA techniques


# LoRA:
Efficiently adapts pre-trained models by updating a smaller subset of parameters, reducing computational cost and memory usage while preserving model performance.

# QLoRA:
Enhances LoRA by applying quantization, further minimizing resource consumption and enabling deployment on hardware with limited capabilities without sacrificing accuracy.


# How they work:

LoRA: LoRA inserts small, trainable matrices (low-rank matrices) into the model. These matrices are much smaller than the full set of model parameters.

QLoRA: After applying LoRA's technique of using low-rank matrices, QLoRA compresses these matrices using quantization. This further reduces the model size and resource requirements.
