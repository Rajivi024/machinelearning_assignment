Project Title

Understanding Hierarchical Feature Learning in Convolutional Neural Networks Through Visualization and Experimentation

Overview

This project investigates how convolutional neural networks (CNNs) learn internal representations from image data. The objective is to understand how features evolve across layers and how architectural choices influence learning and generalization.

The study focuses on:

visualising feature maps across multiple convolutional layers
analysing learned filters in early layers
comparing different filter sizes (3×3 vs 5×5)
evaluating the impact of pooling on model performance

The experiments are conducted using the CIFAR-10 dataset.                   Requirements

Install dependencies using:

pip install -r requirements.txt

Main libraries used:

torch
torchvision
matplotlib
numpy
pandas
scikit-learn
How to Run
Clone the repository:
https://github.com/Rajivi024/machinelearning_assignment.git 

Install dependencies:
pip install -r requirements.txt
Run the notebook:
rajivi_ml_code.ipynb
Execute all cells to:
train models
generate figures
save results
Outputs

Running the notebook will produce:

Figures (saved in /figures)
training and validation curves
feature maps (multiple layers)
learned filters
filter size comparison
pooling comparison
Results (saved in /results)
model comparison tables
experiment outputs
Key Findings
CNNs learn hierarchical representations, with deeper layers producing more selective activations
Pooling significantly improves generalization and reduces overfitting
Increasing filter size does not provide a clear performance benefit in this setting
Reproducibility
Random seeds are fixed for consistent results
All experiments can be reproduced by running the notebook
No external dependencies beyond those listed are required
Accessibility

This project includes:

clearly labelled figures with descriptive captions
colour-blind friendly visualisations
structured notebook layout for readability
concise explanations to support understanding
License

This project is licensed under the MIT License. See the LICENSE file for details.
