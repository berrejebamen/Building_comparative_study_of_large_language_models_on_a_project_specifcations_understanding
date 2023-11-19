# Comparative Study of Transformers in Understanding Project Specifications

This project, conducted at **M&C IT Consulting**, offers an in-depth analysis of Transformers-based language models, emphasizing their proficiency in comprehending project specifications.

## Introduction

In the realm of Natural Language Processing (NLP), Transformers have shown significant promise. This project delves into their capabilities, particularly in understanding and interpreting project specifications.

## Objectives

- Evaluate the efficacy of various Transformers-based language models.
- Extract questions and answer them from ADAD (M&C's project ) specifications.
- Provide a comprehensive overview of  research papers for each model.

## Models Analyzed

The following state-of-the-art Transformers-based models have been analyzed:

- BERT (Bidirectional Encoder Representations from Transformers)
- ALBERT (A Lite Bert) 
- T5 (Text-to-Text Transfer Transformer)
- GPT-3 (with a special use case of deploying it on a Streamlit app using the OpenAI key)

## Evaluation Metrics

The models were evaluated using the following metrics:

- BLEU Score
- ROUGE-2 Score

## Repository Structure
-**To check similarity between user question and question in json file** : check_similarity.ipynb
- **BERT**: `trying_BERT.ipynb`
- **ALBERT**: `trying_ALBERT.ipynb`
- **T5**: `trying_T5.ipynb`
- **GPT-3**: 
  - Terminal prompt version: `chatgpt.py`
  - Streamlit deployed version: `streamlit_chatgpt.py`
- **Simple Chatbot using PyTorch**: `third_step.ipynb`
- **Research Methodology**: An image showcasing the research method and different steps.
- **CSV Outputs**: Multiple CSV files for each model's output (except GPT-3).
- **Report**: Detailed report written using Overleaf.

## Research Papers Overview

A curated list of research papers associated with each model is provided, offering insights into their foundational concepts and advancements.

## Getting Started

1. Clone the repository.
2. Install the required dependencies.
3. Navigate to the respective `.ipynb` or `.py` file and run the provided scripts.

## Contributors

- **Amen Allah Berrejeb** - Intern
- **Under the supervision of**: Mr. Mohamed Aziz Atitallah - Product Manager

