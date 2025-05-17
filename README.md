# 📚 Book Recommendation System using Logistic Regression

## 📌 Project Overview

This is a **Book Recommendation System** built using **Logistic Regression**, which recommends books to users based on past preferences and input features. It demonstrates how classification techniques can be applied to predict user interests and suggest relevant books.

---

## 🛠️ Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **Matplotlib / Seaborn (optional - for visualization)**
- **Jupyter Notebook / VS Code**

---

## 🎯 Objectives

- To implement a **machine learning-based recommendation system**.
- To train a **logistic regression model** on book-related user data.
- To predict and recommend books based on user inputs or preferences.

---

## 📁 Dataset Description

The dataset includes information such as:

- User ID
- Book Title
- Book Genre
- Book Ratings
- User Preferences (optional feature-engineered)

> You can use public datasets like **Book-Crossing Dataset** or a custom dataset collected for academic purposes.

---

## 🔍 How It Works

1. **Data Preprocessing**  
   - Handling missing values  
   - Encoding categorical features (like genres or titles)  
   - Normalizing the data if necessary  

2. **Feature Selection**  
   - Selecting features like genre, user preference, and rating  

3. **Model Training**  
   - Logistic Regression model is trained to classify whether a user would like a book or not (`1` = Recommend, `0` = Not Recommend)

4. **Evaluation**  
   - Model is evaluated using accuracy, precision, recall, and confusion matrix  

5. **Prediction**  
   - The model predicts whether a particular book should be recommended to a user

---

## 📊 Sample Output

```bash
Enter Book Genre: Fantasy  
Enter User's previous rating score (1-5): 4  
[✔️] Recommended Book: "Harry Potter and the Goblet of Fire"
