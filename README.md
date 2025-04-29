# Introduction to Ragas

This repository contains a series of Jupyter notebooks designed to introduce and demonstrate the usage of the Ragas framework for evaluating Retrieval Augmented Generation (RAG) systems and AI agents.

## Notebooks

The repository includes the following notebooks:

1.  **01_Introduction_to_Ragas.ipynb**: Provides a basic introduction to the Ragas framework, its concepts, and core components.
2.  **02_Basic_Evaluation_Workflow_with_Ragas.ipynb**: Demonstrates a fundamental workflow for evaluating RAG systems using Ragas metrics.
3.  **04_Synthetic_Data_Generation.ipynb**: Explores techniques for generating synthetic data to aid in the evaluation process. (Note: Notebook 03 seems to be missing).
4.  **05_Advanced_Metrics_and_Customization.ipynb**: Dives into more advanced Ragas metrics and shows how to customize the evaluation process.
5.  **06_Evaluating_AI_Agents.ipynb**: Focuses on applying Ragas or similar evaluation techniques to assess the performance of AI agents.

## Prerequisites

Before running the notebooks, ensure you have the following installed:

*   Python (version 3.8 or higher recommended)
*   Jupyter Notebook or JupyterLab
*   `uv` (or `pip`) for package management

## Setup Instructions

1.  **Clone the repository:**
    ```bash
    git clone <repository-url>
    cd intro-to-ragas
    ```

2.  **Create a virtual environment (recommended):**
    ```bash
    python -m venv .venv
    source .venv/bin/activate  # On Windows use `.venv\Scripts\activate`
    ```

3.  **Install dependencies using uv:**
    ```bash
    uv sync
    ```



## Running the Notebooks

1.  **Start Jupyter:**
    ```bash
    jupyter notebook
    # or
    jupyter lab
    ```

2.  **Open and run the notebooks:**
    Navigate through the Jupyter interface, open the `.ipynb` files in numerical order (or as desired), and execute the cells step-by-step.

## Data

The `data/` directory contains sample markdown files used as context documents in some notebooks.

## Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues.