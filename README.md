# 📚 Top 100 Best-Selling Books on Amazon — EDA & Genre Prediction

This project involves data preprocessing, exploratory data analysis (EDA), and predictive modeling on a dataset of the top 100 best-selling books on Amazon. The goal is to extract insights from the data and build a model that predicts whether a book is Fiction or Non-Fiction based on various attributes.

---

## 🧾 Dataset
- **Name:** Top 100 Best-Selling Books on Amazon  
- **Attributes Include:** Title, Author, Price, Number of Reviews, Ratings, Cover Type, Rank, Genre, etc.

---

## 📊 Exploratory Data Analysis

The EDA section visualizes trends and patterns in the dataset through various charts:

- 🥧 **Pie Chart**: Shows the composition of Fiction vs Non-Fiction books.
- 📈 **Bar Chart - Top Authors**: Displays authors with the most books in the top 100 list.
- 📈 **Bar Chart - Top Rated Books**: Ranks books based on the highest number of reviews.
- 💸 **Most Expensive Books**: Highlights the books with the highest prices.
- 🏅 **Highest Rated Books**: Identifies top-rated books based on their rank.

---

## 🤖 Predictive Modeling

The final section of the project focuses on building a **Logistic Regression** model to predict the **genre** of a book (Fiction or Non-Fiction) using attributes like:

- Price  
- Number of Reviews  
- Ratings  
- Rank  
- Cover Type  

📌 Steps involved:
- Preprocessing and feature encoding using `LabelEncoder` and `OneHotEncoder`
- Feature scaling with `StandardScaler`
- Model training using `LogisticRegression`
- Evaluation via accuracy score, classification report, and confusion matrix

---

## 🛠 Technologies Used

- Python 🐍
- Pandas, NumPy
- Matplotlib, Seaborn (for data visualization)
- Scikit-learn (for modeling and preprocessing)

---



