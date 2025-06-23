## Counterfactual Explanations for MNIST

I wanted to explore the concepts of Explainable AI and counterfactual reasoning. This project provides insights into the same using the MNIST dataset. Counterfactual explanations, in simple terms, aim to answer the question:

	"What minimal change to this input would flip the model’s decision?"

By counterfactual maps, we can better understand what features the model relies on for its predictions. Thus, this serves as a great tool for understanding the decisions made by also keeping them factually correct and also at the same time helping in bias detection for deep learning systems.

## Objective
To design and evaluate a pipeline that:

	1) Predicts MNIST digit classes using a deep neural network.

	2) Generates counterfactual images for given inputs that would cause the model to change its classification.

	3) Visualizes original, counterfactual, and difference maps.

## Sample Output
<div style="text-align: center;">
  <img src="https://github.com/user-attachments/assets/5422515b-f7a3-4550-b1a5-c3d979c56fee" />
</div>

## Applications
Though demonstrated on MNIST, this framework has applications in real-world domains as well like clinical diagnosis (best example being Alzheimer's detection from MRIs

## Reference and citations
This project structure and explanation format is inspired by OmniXAI, an open-source library by Salesforce Research for Explainable AI.

Idea Adapted from:

	1) Wachter, S., Mittelstadt, B., & Russell, C. (2017). Counterfactual Explanations without Opening the Black Box. arXiv:1711.00399
	2) Xuhong Zhang, Huan Wang, etc. (2022).
