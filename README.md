# LSTM From Scratch: Two Implementations

A comprehensive project exploring Long Short-Term Memory (LSTM) neural networks through two distinct implementations—one using a simple numeric sequence and another using a text-based approach. This repository is designed for educational purposes and is fully integrated with Kaggle notebooks for hands-on experimentation.

<img src="https://github.com/user-attachments/assets/ad08fae1-95e2-410b-8d9f-d7a39eaca2f8" width="290" height="400">

---

## Overview

This project demonstrates the inner workings of LSTM networks via two different examples:

1. **Simple Numeric LSTM Example**  
   - Uses a numeric sequence `[10, 20, 30]` to illustrate the step-by-step computations of LSTM gates (forget, input, candidate, and output).  
   - Provides clear visualizations of the evolution of hidden and cell states.  
   - Ideal for understanding the core mechanics of LSTM cells without the complexity of training.

2. **Text-based LSTM with WordCloud and Training**  
   - Implements a character-level language model using a text excerpt from *A Tale of Two Cities* by Charles Dickens.  
   - Includes data preprocessing, dictionary creation, forward and backward propagation, and a complete training loop.  
   - Visualizes training loss and generates a WordCloud from the text data.  
   - Demonstrates a practical application in natural language processing tasks.

---

## Features

- **Step-by-Step LSTM Computations:**  
  Provides a detailed breakdown of how each LSTM gate is calculated in the numeric example.

- **Visualizations:**  
  - Plots showing the evolution of hidden and cell states.  
  - Bar charts for gate activations over time.  
  - Training loss curves and WordClouds for text-based modeling.

- **Practical NLP Application:**  
  A complete workflow for character-level language modeling, from data preprocessing to training and visualization.

- **Kaggle Integration:**  
  Designed to be seamlessly linked with Kaggle kernels for interactive exploration and further research.

---

## Installation and Setup

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/your_username/LSTM-From-Scratch.git
   cd LSTM-From-Scratch
   ```

2. **Install Dependencies**  
   This project requires Python 3 and the following libraries:
   - numpy
   - matplotlib
   - pandas
   - wordcloud

   Install them with:
   ```bash
   pip install -r requirements.txt
   ```

3. **Kaggle Integration**  
   - Upload the notebooks from the `notebooks` folder to Kaggle.  
   - Link your GitHub repository with Kaggle for version control and collaborative work.

---

## Usage

- **LSTM_Numeric_Example.ipynb**  
  Run this notebook to see a detailed numeric demonstration of LSTM cell operations on the sequence `[10, 20, 30]`. Visualizations include plots of hidden state and cell state evolution, as well as bar charts of gate activations.

- **LSTM_Text_Example.ipynb**  
  This notebook shows how to build and train a character-level LSTM model using a text excerpt. It covers data preprocessing, forward and backward propagation, and visualizations such as training loss curves and WordClouds.

---

## Contact

For any questions or feedback, please reach out to [arwaabouattia@gmail.com].
