---

# Amazon Alexa Reviews Sentiment Analysis

## Overview
This project involves creating a classification model to predict the sentiment of Amazon Alexa reviews (positive or negative). The dataset includes customer reviews, star ratings, and product variations.

## Setup

### Prerequisites
- Python 3.6 or later
- Required libraries

### Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Samyukkthaa-N-K/DS-Amazon-Alexa-reviews-
   cd DS-Amazon-Alexa-reviews-
   ```

2. **Create a Virtual Environment (Optional but Recommended):**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

### Data

1. **Download the Dataset:**

   Download the dataset from [this link](https://drive.google.com/file/d/1aZQrOhL5pllbNHNJHI2VbUTQIRA9Ugyr/view?usp=sharing).

2. **Save the Dataset:**

   Save the downloaded file as `amazon_alexa_data.csv` in the project directory.

### Running the Code

1. Open a Jupyter Notebook or Python script.
2. Execute the following code to perform the analysis:

   ```python
   import pandas as pd

   # Load and Inspect Data
   reviews = pd.read_csv('amazon_alexa_data.csv', sep='\t')
   
   # Perform Data Exploration and Cleaning

   # Train and Evaluate the Model
   ```

   For a complete code walkthrough, refer to `main.py` or `notebook.ipynb` in the project.

### Model Evaluation

After training the model, evaluate its performance using accuracy, classification report, and confusion matrix.

---
