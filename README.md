# PEFT Adapters Fine-Tuning Comparison

Welcome to the **PEFT Adapters Fine-Tuning Comparison** repository! This project explores the performance and efficiency of various Parameter-Efficient Fine-Tuning (PEFT) methods, including LoRA, AdaLoRA, IA3, LoHa, and LoKr, using Vision Transformer (ViT) models on different datasets.

Check out my blog on how you can use these and results:
- https://medium.com/predict/beyond-lora-a-comprehensive-guide-to-efficient-model-fine-tuning-5983bb4899fb
- https://medium.com/predict/battle-of-the-adapters-efficient-fine-tuning-methods-compared-e9fac9e4f10d

## 📂 Repository Structure

- **finetuned-model1-adalora**: Fine-tuned Model 1 using AdaLoRA adapter.
- **finetuned-model1-ia3**: Fine-tuned Model 1 using IA3 adapter.
- **finetuned-model1-loha**: Fine-tuned Model 1 using LoHa adapter.
- **finetuned-model1-lokr**: Fine-tuned Model 1 using LoKr adapter.
- **finetuned-model1-lora**: Fine-tuned Model 1 using LoRA adapter.
- **finetuned-model2-adalora**: Fine-tuned Model 2 using AdaLoRA adapter.
- **finetuned-model2-ia3**: Fine-tuned Model 2 using IA3 adapter.
- **finetuned-model2-loha**: Fine-tuned Model 2 using LoHa adapter.
- **finetuned-model2-lokr**: Fine-tuned Model 2 using LoKr adapter.
- **finetuned-model2-lora**: Fine-tuned Model 2 using LoRA adapter.
- **README.md**: This file, providing an overview of the repository and instructions.
- **in_depth_working_peft.ipynb**: Jupyter Notebook with detailed analysis of PEFT methods and their working principles.
- **model1_metrics_comparison.png**: Performance comparison graph of Model 1 across different adapters.
- **model2_metrics_comparison.png**: Performance comparison graph of Model 2 across different adapters.
- **peft_methods_compared.ipynb**: Jupyter Notebook with in-depth comparison of PEFT methods applied to the models.

## 🚀 Project Overview

This project aims to evaluate various PEFT methods' impact on the performance of Vision Transformer models. We focus on:

- **LoRA (Low-Rank Adaptation)**
- **AdaLoRA (Adaptive Low-Rank Adaptation)**
- **IA3 (Infused Adapter by Inhibiting and Amplifying Inner Activations)**
- **LoHa (Low-Rank Hadamard Product)**
- **LoKr (Low-Rank Kronecker Product)**

Each adapter was applied to two datasets:

1. **Human Action Recognition Dataset**: 15 classes of human activities with over 12,000 labeled images.
2. **UC Merced Land Use Dataset**: 21 classes of land use images, each with 100 images.

## 📊 Results

The repository includes fine-tuned models and performance metrics for each adapter on both datasets. The comparison images (`model1_metrics_comparison.png` and `model2_metrics_comparison.png`) provide a visual representation of accuracy, precision, recall, and F1 scores across different adapters.

## 📘 Notebooks

1. **in_depth_working_peft.ipynb**: A detailed breakdown of how each adapter works, with code snippets and explanations.
2. **peft_methods_compared.ipynb**: An in-depth comparison of the PEFT methods, highlighting their strengths and weaknesses.

## 🔧 Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/REDDITARUN/PEFT-Adapters-Fine-Tuning.git
   ```
2. Navigate to the repository folder:
   ```bash
   cd PEFT-Adapters-Fine-Tuning
   ```
3. Run the Jupyter Notebooks to explore the models and results:
   ```bash
   jupyter notebook in_depth_working_peft.ipynb
   jupyter notebook peft_methods_compared.ipynb
   ```

## 📧 Contact

If you have any questions or suggestions, feel free to reach out:

- **Author**: Tarun Reddi
- **LinkedIn**: [linkedin.com/in/tarun-reddi](https://linkedin.com/in/tarun-reddi)
- **GitHub**: [REDDITARUN](https://github.com/REDDITARUN)

Check out my personal side at [Bento](https://bento.me/tarunreddi).
Peek at my journey at [Portfolio](https://redditarun.github.io/).


Thank you for checking out this repository! If you found this project helpful, please star the repository and follow for more content. Happy coding! 🌟
