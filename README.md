# Detoxifying-Text-Generation-with-Reinforcement-Learning

This project comes from coursea "Generative AI with Large Language Model"

In this project, I utilized the PyTorch framework along with HuggingFace's Transformers library to build a system for generating text based on reinforcement learning principles. The core of this system was the Proximal Policy Optimization (PPO) algorithm.

To ensure the safety of the generated content, a toxicity detection model was integrated into the system. This model was then fine-tuned to reduce the toxicity levels of the outputs, creating a 'detoxified' language model.

The performance of the original model and the detoxified model was assessed using both quantitative and qualitative techniques. These evaluations involved comparison of toxicity scores before and after the detoxification process, helping to ascertain the effectiveness of the fine-tuning techniques.

Finally, for handling the dataset and model training, I leveraged libraries like PyTorch, Transformers, and Hugging Face's Datasets library. This combination of tools enabled efficient data handling, model training, and evaluation, resulting in a more robust and safer text generation system.
