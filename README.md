# 📈 InstagramData_Prediction using  — Naive Bayes 

This project determines how to implement **Naive Bayes Algorithm** to predict **Instagram posts** based on their instagram **UserId**. The goal of this notebook is to accurately predict the data while optimizing the number of features used. In addition to achieving high accuracy, this notebook will explore whether similar evaluation metrics can be maintained with a distint feature set.

---

## 📂 Dataset

Complete Dataset consists of 6 CSV file. Each CSV file has data which is related to instagram. 

These files are mapped to  classify the set of data related to user and their posts.

## 🔧 Libraries Used

- `pandas` — Data loading and manipulation  
- `numpy` — Numerical operations  
- `matplotlib`, `seaborn` — Data visualization  
- `sklearn` — Machine learning (model, training, evaluation)

---

## 🛠️ Steps Performed

1. **Import Libraries**  
2. **Upload and Read CSV Dataset**
3. **Data Cleaning**  
   - Checked for null values  
4. **Exploratory Data Analysis (EDA)**  
   - Data visualization using seaborn  
5. **Train-Test Split**  
   - Using `train_test_split()`  
6. **Model Creation**  
   - Using `GaussianNB` from scikit-learn  
7. **Prediction**  
   - Predicted users and thei posts for test data  
8. **Evaluation Metrics**
   - F1_score 
   - Accuracy_score 
   - Precision_score  
   - Recall_score
   - Confusion_Matrix
9. **Visualization**  
   - plot of **Symptoms vs Prognosis**

---

## 📊 Evaluation Output

```  
Accuracy_score ....
F1_score ..... 
precision_score .... 
recall_score .... 
```

This indicates a good accuracy prediction model.

---

## 📌 Visualization

A plot is generated to show the **UserID vs Posts** values with a reference bar:

- X-axis → UserID  
- Y-axis → Posts  

---

## 🙏 Acknowledgement

This project was created under the guidance of [Surekha Kanwar](https://www.linkedin.com/in/surekha-kanwar-81002076/), as part of my machine learning learning journey. I am thankful for her feverish support and knowledge.

---

## 🚀 Run the Code

You can run this project by copying the code into a new notebook and uploading your dataset.

---

## 📬 Contact

For any suggestions or collaborations, feel free to connect on [](https://www.linkedin.com/in/aditya-saraswat-51257b256ar-81002076/), or mail me.
