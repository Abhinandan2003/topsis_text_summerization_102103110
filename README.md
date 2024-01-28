# TOPSIS for Text Summarization Models

This repository contains an implementation of TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution) for evaluating and ranking text summarization models. The goal is to provide a systematic approach to compare the performance of various pre-trained models based on key criteria such as Semantic Coherence, Factual Accuracy, Content Coverage, and Fluency.

## Models

The following pre-trained models are considered for evaluation:

1. [facebook/bart-large-cnn](https://huggingface.co/facebook/bart-large-cnn)
2. [t5-large](https://huggingface.co/t5-large)
3. [sshleifer/distilbart-cnn-12-6](https://huggingface.co/sshleifer/distilbart-cnn-12-6)
4. [google/pegasus-large](https://huggingface.co/google/pegasus-large)
5. [allenai/led-large-16384-arxiv](https://huggingface.co/allenai/led-large-16384-arxiv)
6. [sshleifer/bart-tiny-random](https://huggingface.co/sshleifer/bart-tiny-random)

## Installation

Clone the repository and install the required dependencies:

```bash
git clone https://github.com/your_username/topsis-text-summarization.git
cd topsis-text-summarization
pip install -r requirements.txt
