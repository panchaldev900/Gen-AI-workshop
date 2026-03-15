# Fine-Tuning Notebooks

This directory contains hands-on Jupyter notebooks demonstrating fine-tuning techniques for Large Language Models (LLMs) and Sentence Transformers as part of the Gen-AI Workshop.

## Overview

These notebooks provide practical examples of how to fine-tune pre-trained models for specific tasks, building on foundational concepts from the workshop's coverage of LLMs, SLMs (Small Language Models), RAG (Retrieval-Augmented Generation), and fine-tuning.

---

## Notebook 1: `Notebook_1.ipynb`

### Purpose
This notebook serves as an introduction to fine-tuning concepts and establishes the foundational techniques for adapting pre-trained models to custom datasets.

### Key Features
- **GPU Support**: Configured with T4 GPU acceleration via Google Colab
- **Sentence Transformers Integration**: Uses `sentence-transformers` library for semantic embedding tasks
- **Model Utilities**: Loads pre-trained models and their configurations
- **Progress Tracking**: Implements progress bars for monitoring long-running operations

### What You'll Learn
- How to load and initialize pre-trained transformer models
- Basics of preparing data for fine-tuning
- Understanding model configurations and architectures
- Setting up training infrastructure with GPU support

### Technical Stack
- **Environment**: Google Colab with T4 GPU
- **Python Version**: Python 3
- **Key Libraries**:
  - `sentence-transformers`: For transformer-based sentence embeddings
  - `torch`/`transformers`: Core deep learning framework
  - `tqdm`: Progress visualization

---

## Notebook 2: `Notebook_2.ipynb`

### Purpose
This notebook extends the concepts from Notebook 1 with more advanced fine-tuning techniques and practical implementations for real-world scenarios.

### Key Features
- **GPU Support**: Also configured with T4 GPU acceleration
- **Advanced Transformers**: Builds on sentence-transformer models with deeper customization
- **Enhanced Training Loops**: Implements more sophisticated training strategies
- **Performance Monitoring**: Includes tools for tracking training metrics

### What You'll Learn
- Advanced fine-tuning strategies for LLMs
- Custom training loops and optimization techniques
- Evaluation metrics for fine-tuned models
- Best practices for production-ready models

### Technical Stack
- **Environment**: Google Colab with T4 GPU
- **Python Version**: Python 3
- **Key Libraries**:
  - `sentence-transformers`: For advanced embedding tasks
  - `torch`/`transformers`: Deep learning framework
  - `tqdm`: Progress tracking

---

## Prerequisites

Before running these notebooks, ensure you have:
- Access to Google Colab or a local Jupyter environment
- GPU access (recommended for faster training)
- Basic understanding of:
  - Python and Jupyter notebooks
  - Machine learning concepts
  - Transformer models (covered in workshop basics)

## Installation

The notebooks automatically install required dependencies. Key packages include:
```bash
pip install torch
pip install transformers
pip install sentence-transformers
pip install tqdm
