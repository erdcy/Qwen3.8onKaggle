This project deploys the Qwen3.8 27B Q4 model on Kaggle, achieving an inference speed of approximately 20~23 tokens/s with a context length of 28,672. It generates a temporary public link, enabling API calls from third-party platforms.

Deployment Process

Step 0

Sign up for a Kaggle account and verify your phone number to unlock access to GPU T4 x2.

Step 1
Create a new notebook, copy the content from Qwen3.8_Initial, and run it. This will generate two datasets:
Qwen3.8-27B-AWQ-Weights
vLLM-Offline-Wheels

Step 2
Create a new notebook and copy the content from Qwen3.8_API_Start.
In the Input section, select "Add Input".
Filter by "Your Work" and "Dataset", then add Qwen3.8-27B-AWQ-Weights and vLLM-Offline-Wheels.
In Session options, select GPU T4 x2 as the Accelerator.
Turn Internet on.
Run the notebook and wait for about 15 minutes untill the API link to appear.