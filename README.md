# Semantic Analysis of Research Documents Using DL Techniques

## Project Overview
This project performs semantic analysis and summarization of research papers using deep learning models (Pegasus and T5). It can extract sections like Abstract, Introduction, Methodology, Results, and Conclusion, and generate a concise summary for each section.

## Features
- Extract text from multi-column PDFs
- Clean and preprocess text
- Summarize each section using Pegasus and refine using T5
- Combine section summaries into a final summary
- Calculate ROUGE scores for evaluation

## Files
- `t5_v2.ipynb` : Main notebook containing code for extraction, summarization, and evaluation  

> **Note:** The pretrained models and dataset used in this project are **not included** due to large file size. You need to provide your own models in the specified paths.

## Requirements
- Python 3.x
- Libraries: `transformers`, `torch`, `pdfplumber`, `nltk`, `rouge-score`, `ipywidgets`, `google.colab`

Install dependencies using:
```bash
pip install transformers[torch] accelerate pdfplumber rouge-score nltk ipywidgets


Usage:
1. Open t5_v2.ipynb in Google Colab.
2. Mount your Google Drive.
3. Place your PDF files in the folder: /content/drive/MyDrive/Papers
4. Run all cells to process and summarize the papers.
