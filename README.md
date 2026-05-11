# svm-mushroom-classifier
#  Mushroom Classification using SVM

## Project Overview
This project aims to classify mushrooms as either **edible** or **poisonous** based on their physical characteristics. Using a Support Vector Machine (SVM) model, the project analyzes various features such as cap shape, color, odor, and gill spacing to make highly accurate predictions about mushroom toxicity.

## Dataset Information
The dataset used in this project is `mushrooms.csv`, which contains descriptions of hypothetical samples corresponding to 23 species of gilled mushrooms. 

- **Target Variable:** `class` (e = edible, p = poisonous)
- **Features Include:** - `cap-shape` (bell, conical, convex, flat, knobbed, sunken)
  - `cap-surface` (fibrous, grooves, scaly, smooth)
  - `cap-color` (brown, buff, cinnamon, gray, green, etc.)
  - `odor` (almond, anise, creosote, fishy, foul, musty, none, pungent, spicy)
  - *And several other stalk, veil, and ring attributes.*

## Technologies & Libraries Used
- **Python 3.x**
- **Jupyter Notebook**
- **Pandas** (Data manipulation and cleaning)
- **Scikit-Learn** (Model building, preprocessing, and evaluation)
- **Matplotlib / Seaborn** (Data visualization)

## Model & Performance
The primary machine learning algorithm used here is the **Support Vector Classifier (SVC)** from `sklearn.svm`. 

- The data was preprocessed (encoding categorical variables).
- The dataset was split into training and testing sets.
- The `SVC()` model was fitted to the training data.
- **Accuracy:** The model performs exceptionally well, achieving an accuracy score of **~99.1%** on the testing dataset.

## Repository Structure
- `SVM_MODEL.ipynb`: The main Jupyter Notebook containing data exploration, preprocessing, model training, and evaluation.
- `mushrooms.csv`: The dataset used for training and testing the model.
- `README.md`: Project documentation.

## 💻 How to Run Locally
1. Clone this repository to your local machine:
   ```bash
   git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
