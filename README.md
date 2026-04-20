# Understanding Customer Dissatisfaction Using Amazon Reviews

## Overview
This project analyzes Amazon customer reviews to understand the main reasons behind customer dissatisfaction. The analysis focuses on text mining, term frequency patterns, and topic modelling to identify recurring themes in negative reviews and compare them with positive reviews.

## Objectives
- Clean and preprocess Amazon review text
- Compare 1-star reviews with 4–5 star reviews
- Build document-term matrices
- Identify frequent words linked to dissatisfaction
- Apply topic modelling to uncover major complaint themes

## Dataset
The dataset consists of Amazon customer reviews containing:
- Review text
- Rating information

The analysis mainly uses:
- **1-star reviews** for dissatisfaction analysis
- **4–5 star reviews** for comparison

## Methods Used
- Data cleaning and preprocessing
- Lowercasing, punctuation removal, number removal, stopword removal, and lemmatization
- Document-Term Matrix creation
- Sparse term removal
- Frequency-based comparison of terms across rating groups
- LDA topic modelling

## Tools and Libraries
### Python
- pandas
- numpy
- matplotlib
- scikit-learn
- nltk

## Key Analysis Steps
1. Load and clean the review dataset  
2. Create rating groups:
   - 1-star
   - 4–5 star  
3. Preprocess review text  
4. Build document-term matrices  
5. Remove sparse terms  
6. Extract frequent terms  
7. Compare terms across rating groups  
8. Apply LDA topic modelling to identify dissatisfaction themes  

## Results
The analysis highlights words and themes that appear more often in dissatisfied customer reviews, such as issues related to:
- delivery
- refund
- service
- order
- account
- package

It also identifies words more associated with satisfied reviews, such as:
- great
- good
- best
- fast
- easy

These findings help explain the major drivers of customer dissatisfaction.

## Project Structure

project-folder/

│── data/

│   └── Amazon_Reviews.csv

│── Code.ipynb

│── README.md

## How to Run
1. Clone the repository
```

git clone https://github.com/your-username/your-repo-name.git

```
2. Move into project folder
```

cd your-repo-name

```
3. Install Dependencies
```

pip install pandas numpy matplotlib scikit-learn nltk

```

