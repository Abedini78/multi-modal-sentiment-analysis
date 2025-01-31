#Multi-Modal Sentiment Analysis

Overview

This project focuses on multi-modal sentiment analysis, leveraging both text and image data to predict emotions accurately. We utilize CLIP (Contrastive Language-Image Pretraining), a powerful pre-trained model developed by OpenAI, to extract meaningful features from both modalities and analyze sentiment in a unified manner.

Features

Multi-modal Approach: Combines textual and visual data for comprehensive sentiment analysis.

CLIP Model Integration: Uses OpenAI's CLIP for feature extraction from both text and images.

Deep Learning Pipeline: Processes multi-modal inputs to enhance sentiment prediction.

Jupyter Notebook Implementation: Fully reproducible with step-by-step code in multiModalSentimentAnalysis.ipynb.

Installation

To set up the project, follow these steps:

# Clone the repository
git clone https://github.com/abedini78/multi-modal-sentiment-analysis.git
cd multi-modal-sentiment-analysis

# Create a virtual environment
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`

# Install dependencies
pip install -r requirements.txt

Usage

Run the Jupyter Notebook to analyze text and images for sentiment detection:

jupyter notebook

Open multiModalSentimentAnalysis.ipynb and execute the cells step by step.

Dependencies

Python 3.8+

OpenAI CLIP

PyTorch

Transformers

Jupyter Notebook

NumPy, Pandas, Matplotlib

Results

The model predicts sentiment labels based on both text and images, showcasing the effectiveness of a multi-modal approach.

Contributing

Feel free to fork the repository and contribute. Open issues for any suggestions or improvements.



