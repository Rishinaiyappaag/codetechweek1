# codetechweek1

## 🚀 Objective

Build a movie recommendation system using collaborative filtering techniques that can suggest movies to users based on historical user-item interaction data.

## 🧠 Techniques Used

- **Collaborative Filtering** using matrix factorization
- **SVD (Singular Value Decomposition)** algorithm from the `surprise` library
- **Train-Test Split**, RMSE for evaluation

## 🛠️ Tools and Libraries

- Python
- Jupyter Notebook
- `pandas`
- `surprise` (for collaborative filtering)
- `matplotlib` (optional, for visualization)

## 📊 Dataset

The notebook uses the built-in **MovieLens 100k dataset** available in the `surprise` library.

## 📈 Evaluation

The system is evaluated using **RMSE (Root Mean Squared Error)** on the test data to check the accuracy of the predicted ratings.

## ▶️ How to Run

1. Clone this repository or download the notebook.
2. Install required packages:
    ```bash
    pip install scikit-surprise pandas
    ```
3. Run the Jupyter Notebook:
    ```bash
    jupyter notebook Task1.ipynb
    ```

## 💡 Output

The notebook trains the model and provides sample movie recommendations for a given user ID.

## 📜 License

This project is for educational purposes only.

---

