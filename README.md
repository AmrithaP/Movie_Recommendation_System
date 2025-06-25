# 🎬 Movie Recommendation System using SVD

This project implements a **collaborative filtering-based movie recommendation system** using the [MovieLens 100K dataset](https://grouplens.org/datasets/movielens/100k/) and the `Surprise` library. The model is built using the **Singular Value Decomposition (SVD)** algorithm and evaluated using industry-standard metrics such as **RMSE** and **MAE**.

---

## 📂 Project Structure

```
📁  
├── README.md                                    # Project documentation
└── 📁 movie-recommender-svd/
      ├──  movie_recommendation_svd.ipynb        # Jupyter Notebooks for EDA and model training
      └── requirements.txt                       # Python dependencies
```

---

## 📚 Dataset

* **Name:** MovieLens 100K
* **Size:** 100,000 ratings from 943 users on 1,682 movies
* **Source:** [MovieLens official website](https://grouplens.org/datasets/movielens/100k/)

---

## 🛠️ Technologies Used

* **Python**
* **Surprise (scikit-surprise)**
* **Pandas**
* **Matplotlib / Seaborn** (for visualization, optional)
* **Jupyter Notebook**

---

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/movie-recommender-svd.git
   cd movie-recommender-svd
   ```

2. (Optional) Create and activate a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the notebook:
   Open `movie_recommendation_svd.ipynb` in Jupyter Notebook or Jupyter Lab.

---

## 🔍 Methodology

* **Step 1:** Load MovieLens 100K dataset using Surprise.
* **Step 2:** Convert raw ratings to DataFrame for inspection.
* **Step 3:** Split data into training and testing sets.
* **Step 4:** Use **GridSearchCV** to find the best hyperparameters for SVD.
* **Step 5:** Train the best model and evaluate using **RMSE** and **MAE**.
* **Step 6:** Predict ratings for individual user-item pairs and review model predictions.

---

## 📈 Results

| Metric | Score  |
| ------ | ------ |
| RMSE   | 0.9183 |
| MAE    | 0.7279 |

These scores indicate that the model can predict user ratings with reasonable accuracy, generally deviating less than 1 star from actual ratings on a 1–5 scale.

---

## 💡 Key Learnings

* Implemented collaborative filtering using matrix factorization.
* Gained experience tuning hyperparameters with cross-validation.
* Evaluated models with relevant metrics like RMSE and MAE.
* Developed a practical understanding of building a recommender system pipeline.

---

## 📌 Future Work

* Incorporate **content-based filtering** using movie metadata (e.g., genres, release year).
* Explore **hybrid recommendation systems** combining collaborative and content-based approaches.
* Try more advanced algorithms like **SVD++**, **KNNBaseline**, or **neural network-based models**.
* Add **top-N recommendations** and precision/recall-based evaluation.

---

## 👩‍💼 About Me

I’m [Amritha Prakash](https://www.linkedin.com/in/amritha-prakash), a graduate student in Applied Data Science, passionate about machine learning and building data-driven solutions.

---

## 📨 Contact

Have feedback or want to collaborate? Reach out to me:

* 📧 [amrithaprakash17@gmail.com](mailto:amrithaprakash17@gmail.com)
* 💼 [LinkedIn](https://www.linkedin.com/in/amritha-prakash)

---

## ⭐️ If you found this useful, please consider giving it a star!
