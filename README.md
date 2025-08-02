## 📚 Book Recommendation System (KNN)

This project builds a simple **book recommender** using **K-Nearest Neighbors (KNN)** based on user ratings.

---

### 🔧 Features

* Filters active users and popular books
* Merges ratings with book titles
* Creates a user-item matrix (`pivot table`)
* Uses **cosine similarity** to recommend similar books

---

### 🛠 Tech Stack

* Python, Pandas, scikit-learn

---

### 🚀 How to Use

1. Load `books.csv` and `ratings.csv`
2. Run the notebook: `book_recommender_knn.ipynb`
3. Enter a book title → get similar book recommendations

---

### 📌 Example

```text
Input: "1984"
Output: ["Animal Farm", "Brave New World", "Fahrenheit 451", ...]
```

---

### 📂 Files

* `book_recommender_knn.ipynb` – Main notebook
* `books.csv` – Book metadata
* `ratings.csv` – User ratings


