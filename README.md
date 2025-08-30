# AI-Powered Handwritten Answer Evaluator

An intelligent system designed to evaluate handwritten answer scripts using Optical Character Recognition (OCR) and Natural Language Processing (NLP). This project automates the evaluation process, providing scores and constructive feedback to simulate human-like assessment.

## Features
- **Text Extraction**: Extracts handwritten text from images using a Generative AI model.
- **Automated Scoring**:
  - **Keyword Relevance**: Scores the presence of relevant keywords.
  - **Semantic Similarity**: Rates the semantic alignment of the answer to an ideal response.
  - **Grammar Check**: Evaluates grammatical correctness.
  - **Weighted Grade**: Combines scores using weighted metrics for a comprehensive evaluation.
- **Feedback Generation**: Offers suggestions for improvement based on the extracted text and scores.
- **Interactive Interface**: Upload answer scripts and receive results instantly using a Gradio-based web interface.

## Technologies Used
- **Generative AI Models**: Google Generative AI and Groq Llama models for text extraction and analysis.
- **Optical Character Recognition (OCR)**: Extracts handwritten text.
- **Natural Language Processing (NLP)**: Evaluates semantic similarity and grammar.
- **Gradio**: Provides a user-friendly web interface for real-time interaction.

## How to Run
1. Clone the repository.
2. Execute the script in your preferred Python environment.
3. Launch the Gradio interface:
   - Use the interactive GUI to upload images and receive feedback.
