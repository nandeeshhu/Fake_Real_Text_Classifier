Here is a revised version of the `README.md` file according to your instructions:

---

# 🧠 AI Generated and Real Text Classifier using DeBERTaV3 + KerasCore + KerasNLP

This project implements a text classification model aimed at distinguishing between AI-generated and human-written science exam text. The model is built using the DeBERTaV3 architecture, leveraging KerasCore and KerasNLP libraries, with TPU acceleration for efficient training.

## 🌟 Project Highlights

- **Model**: Utilizes the pre-trained DeBERTaV3 model for advanced text representation.
- **Task**: Binary classification of multiple-choice exam text to identify AI-generated vs. real text.
- **TPU Acceleration**: Optimized for faster training using TPU hardware.
- **K-Fold Cross-Validation**: Implements a robust triple stratified K-Fold validation for model generalization.
- **Experiment Tracking**: Integrated with Weights & Biases (wandb) for tracking metrics and results.

## 🛠️ Tools & Techniques

- **DeBERTaV3**: State-of-the-art transformer model for text classification.
- **KerasCore + KerasNLP**: Leveraging the power of these libraries for model development and NLP tasks.
- **Loss Function**: Binary cross-entropy loss with label smoothing to improve prediction stability.
- **Optimizer**: AdamW optimizer with a cosine learning rate schedule for better convergence.

## 🔍 Model Outcome

The model outputs binary predictions, classifying whether a given text is AI-generated or written by a human. The primary metric used for evaluation is the **Area Under the Curve (AUC)**, tracked during the training process, ensuring high performance on unseen data.

## 📊 Outcome Summary

The project demonstrates the capability of modern transformer models to effectively classify exam text as either AI-generated or human-written, showcasing the potential applications of large language models (LLMs) in real-world exam settings. 
