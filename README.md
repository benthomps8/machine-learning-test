# machine-learning-test
Analyzing income data and attempting to classify adults as high income or low income. Uses logistic regression, support vector machines, decision trees, random forest classifiers, and a neural network.


---
output: github_document
---

# Machine Learning with Python Test

## Overview
This project served as a wrap-up for my Machine Learning class, DSCI 372 at the University of Oregon. In the class, we learned how different machine learning algorithms such as support vector machines, decision trees, and neural networks work. We also learned how to implement them in Python, from scratch and via librarires such as Scikit-learn and PyTorch. The project focuses on one dataset, being the Adult Income Dataset from the University of California, Irvine. The goal of the project was to classify adults as high-income or low-income (above or below $50,000 yearly income) using five different techniques in order to practice my skills, but also to see what method was mot effective for the task at hand. 

---

## Dataset
The dataset I used was the Adult Income Dataset, otherwise known as the Census Income Dataset. The data is captured form the 1994 census, and contains fourteen features including age, education, and sex, with over 48,000 columns or instances. Cleaning I did included dropping missing values, renaming columns, dropping useless (for my analysis) columns, and splitting into different CSVs for training and testing.
Source:  https://archive.ics.uci.edu/dataset/2/adult

### Results
My analysis found that decision trees were the most effective classifier for this specific task, surprisingly even more effective than random forests, even after testing a whole bunch of different criterion and tree depths. I believe this is because the random forest algorithm is more prone to overfitting, especially with this dataset which is not very complex. This project also really taught me that often times, simpler is better. The complicated neural network class that I coded, with lots of hyperparameters and functions, was actually the least effective for the task, even losing out to a simple default Scikit-learn model for example. 


