# Q-and-A-with-T5

This project fine-tunes a T5-small model to perform question answering on a custom dataset of famous personalities. Given a question about a person, the model generates concise and contextually accurate answers.

# Methodology
Preprocessing: Converted CSV data into Q&A pairs (source_text, target_text).
Model: Fine-tuned T5-small using Hugging Face’s Seq2SeqTrainer.
Evaluation: Generated answers compared against ground truth contexts.

Example:

Q: Who is known as the father of the Indian constitution?
A: Dr. B. R. Ambedkar
