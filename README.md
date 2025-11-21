# 📊 Sentiment Analysis of Public Works Projects using Transformer Models

### A Comparative Study for Monitoring Government Accountability

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Framework](https://img.shields.io/badge/Framework-PyTorch-orange.svg)
![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Transformers-yellow.svg)

---

## 📝 Project Overview

In an effort to enhance government transparency and align with Sustainable Development Goal 16, this project explores the application of Natural Language Processing (NLP) to monitor public sentiment regarding government infrastructure. By analyzing a dataset of tweets about the **Department of Public Works and Highways (DPWH) 🇵🇭 flood control projects**, we aim to provide a scalable framework for gauging public perception and fostering accountability.

The core of this research is a rigorous comparative analysis of three distinct Transformer-based models to determine the optimal balance between predictive accuracy and computational efficiency for this specific civic technology application.

---

## 🤖 Models Explored

This study fine-tunes, evaluates, and compares three different models, each serving a unique purpose in the analysis:

1.  **RoBERTa Baseline Model**
    -   **Model:** `jcblaise/roberta-tagalog-base`
    -   **Purpose:** A general-domain model pretrained on the Tagalog language to establish a robust performance benchmark.

2.  **Domain-Adapted Model**
    -   **Model:** `mapsoriano/Roberta-tagalog-Hatespeech`
    -   **Purpose:** A model already fine-tuned on Philippine socio-political discourse to test the hypothesis that sequential transfer learning provides a performance advantage.

3.  **Lightweight Distilled Model**
    -   **Model:** `distilbert-base-multilingual-cased`
    -   **Purpose:** A smaller, faster model evaluated for its viability in resource-constrained or real-time deployment scenarios where efficiency is critical.

---

## 📁 Repository Structure

The repository is organized as follows:


---

## 🔧 Installation & Setup

To replicate this project, please follow the steps below.

1.  **Clone the Repository**
    ```bash
    git clone https://github.com/your-username/your-repository-name.git
    cd your-repository-name
    ```

2.  **Install Dependencies**
    A `pip` command is provided to install all necessary libraries. It is recommended to use a virtual environment.
    ```bash
    pip install transformers datasets accelerate optuna scikit-learn matplotlib seaborn pandas numpy -U
    ```

---

## 🚀 Usage

All experimental procedures are encapsulated within the **`Sentiment_Analysis_DPWH_Final.ipynb`** notebook.

To run the project:
1.  Open the notebook in a compatible environment (e.g., JupyterLab, Google Colab).
2.  Ensure the dataset path in the notebook is correctly pointing to the `data/` directory.
3.  Execute the cells sequentially to perform data loading, preprocessing, model training, hyperparameter optimization, and final evaluation.

---

## 🙏 Acknowledgement

We would like to express our sincere gratitude for the opportunity to develop this project for the **ITE Elective: Machine Learning** course.

Our deepest appreciation goes to our adviser, **Dr. Rodolfo Raga Jr.** His expert guidance and profound knowledge of modern NLP architectures were instrumental to the success of this research. His mentorship on designing a rigorous comparative methodology, establishing a reliable ground truth dataset, and interpreting the results of our hyperparameter search significantly enhanced the quality and academic rigor of our work.

We are also thankful for the academic resources provided throughout the course, which enabled us to bridge the gap between complex theory and practical application.

This research was completed by:
*   **Shan Hiro Rosario**
*   **Joshua Anoos**

Any errors or shortcomings in this work are entirely our own.

---

## 📜 License

This project is licensed under the **MIT License**. See the `LICENSE` file for more details.

