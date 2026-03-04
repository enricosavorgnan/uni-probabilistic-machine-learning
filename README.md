# Probabilistic Machine Learning - University of Trieste (UniTS)

Welcome to the repository for the **Probabilistic Machine Learning** course at the University of Trieste. This repository contains the complete set of materials for the course, including theoretical notes, lecture slides, and practical laboratory notebooks.

## 📁 Repository Structure
```markdown
├── notes/
├── slides/
├── labs/
│
├── .gitignore
└── README.md
```
* **`notes/`**: Contains comprehensive PDF notes detailing the theoretical foundations of the course. Topics range from the basics of probability and statistics to advanced topics like Variational Inference and Gaussian Processes.
* **`slides/`**: Contains the PDF presentation slides used during the lectures (e.g., Intro, ERM, PGM, HMM).
* **`labs/`**: Contains Jupyter Notebooks (`.ipynb`) for the hands-on laboratory sessions. These notebooks allow you to practically implement and test the models and concepts (e.g., VC-dimension, Rademacher Complexity, Double Descent) discussed in class.

## 📚 Topics Covered

The materials in this repository cover the following key areas of Probabilistic Machine Learning:
* Empirical Risk Minimization (ERM) & PAC Learning
* Probabilistic Graphical Models (PGM) and Inference
* Hidden Markov Models (HMM)
* Bayesian Regression and Bayesian Classification
* Markov Chain Monte Carlo (MCMC)
* Expectation-Maximization (EM)
* Variational Inference (VI)
* Generative Modelling
* Kernels and Gaussian Processes (GP)

---

## 🚀 Code Initialization and Setup

To run the Jupyter notebooks in the `labs/` directory, you will need a working Python environment. It is highly recommended to use a virtual environment to manage the required dependencies.

1. Clone the repository
First, clone the repository to your local machine and navigate into it:
```bash
git clone [https://github.com/enricosavorgnan/uni-probabilistic-machine-learning.git](https://github.com/enricosavorgnan/uni-probabilistic-machine-learning.git)
cd uni-probabilistic-machine-learning
```
2. Create and activate a virtual environment
Create a clean Python virtual environment to prevent package conflicts:

```bash
python -m venv venv
```
3. Activate the virtual environment:
    - On Linux / macOS:
    ```bash
    source venv/bin/activate
    ```
    - On Windows:
    
    ```bash
    venv\Scripts\activate
    ```
4. Install the required dependencies
The laboratory notebooks require standard scientific computing and machine learning libraries (such as numpy, matplotlib, scikit-learn, lightgbm, and skimage). Install them using pip:

```bash
pip install jupyterlab numpy scipy matplotlib scikit-learn scikit-image lightgbm
```