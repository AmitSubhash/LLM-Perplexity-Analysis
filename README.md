# Language-Model-Perplexity-and-Evidence-Analysis
This project investigates language modeling through the lens of perplexity and evidence evaluation, aiming to understand how different estimation methods perform across varying training sizes and data sources. Developed as a machine learning programming assignment under the guidance of Dr. Roni Khardon

Task 1:
Construct a vocabulary from training and test text files, estimate word probabilities using Maximum Likelihood (ML), Maximum A Posteriori (MAP), and Predictive (Dirichlet smoothed) methods, and analyze the impact of training set size on model perplexity. This task emphasizes the trade-off between training data volume and model performance.
Task 2:
Introduce a custom log gamma function to calculate log evidence. This task explores the effect of varying the hyperparameter α' on both the model's log evidence and test set perplexity. It offers insights into the model's uncertainty and the robustness of different smoothing strategies.
Task 3:
Extend the evaluation by applying the predictive model to new text datasets (sourced from Project Gutenberg). This step demonstrates the generalization capability of the language model by comparing perplexities on distinct corpora.
By combining theoretical concepts with practical implementations, the project offers a comprehensive analysis of language model performance under different settings, making it a valuable resource for those interested in statistical language modeling and Bayesian methods.

Repository Structure

RK_PgmAssgn1_Amit.ipynb: The primary Jupyter Notebook containing the full code, organized into the three tasks described above.
Data Files: <Cannot reveal as it's for the class>

Requirements

Python 3.x
NumPy
Matplotlib
You can install the necessary libraries using pip:

pip install numpy matplotlib

How to Run

Download the Repository:
Clone the repository to your local machine:
git clone https://github.com/yourusername/Language-Model-Perplexity-Evidence-Analysis.git

Set Up the Working Directory:
Ensure that all required data files (Training testing files in txt, if you have boook pages or any of that in txt too, please clean before running) are in the working directory before executing the notebook.
Run the Notebook:
Open RK_PgmAssgn1_Amit.ipynb using Jupyter Notebook or Google Colab, and run all cells to see the analysis and plots generated for each task.
Project Overview

This project is provided for educational purposes. Feel free to use and learn from the code as needed.

