Plant Leaf Disease Detection - CPU vs GPU Performance Analysis

Overview
This repository contains the implementation of a Convolutional Neural Network (CNN) for plant leaf disease detection. The model is tested on both CPU and GPU, and performance metrics such as inference time and accuracy are compared.

Implementation Details
Framework: TensorFlow / Keras
Model: CNN trained for corn leaf disease classification
Comparison Metrics:
Inference time on CPU vs. GPU
Model accuracy

Installation & Usage
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
2. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
3. Run Inference on CPU
bash
Copy
Edit
python scripts/cpu_inference.py
4. Run Inference on GPU
bash
Copy
Edit
python scripts/gpu_inference.py
