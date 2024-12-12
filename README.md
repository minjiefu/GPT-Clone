# Title
Replicate the GPT-2 Model, including Implementation, Training,  Evaluation and Sampling

# Purpose 
This project aims at developing a GPT-2-like model from scratch using Python and PyTorch

# Highlights
- Ensured proper initialization of parameters and configuration of optimizer, global gradient clipping, learning rate schedule, weight decay, and other key settings by referencing the original GPT-2 and GPT-3 papers
- Implemented a gradient accumulation strategy to address computing resource limitations
- Trained the model on the FineWeb-Edu dataset, comprising approximately 10 billion tokens
- Evaluated and sampled from the model, visualized loss metrics using Pyplot, and compared the results with those of the original GPT-2 124M model, achieving a match with the GPT-2 124M model’s 3.29 baseline after 6 hours and 7000 training steps
- Utilized Distributed Data Parallel to accelerate training, ultimately achieving a training loss of 2.92 and a validation loss of 3.07 after 2 hours and a single epoch of training.

# Reference
https://github.com/karpathy/build-nanogpt
