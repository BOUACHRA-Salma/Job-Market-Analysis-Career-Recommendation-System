

# Job Market Analysis & Career Recommendation System 🚀

This Data Science project analyzes job market trends and provides personalized career recommendations based on user skills. By leveraging Natural Language Processing (NLP) and Unsupervised Machine Learning, we map professional profiles to the most relevant job categories.

## 🛠️ Technical Stack
- **Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Machine Learning:** Scikit-Learn
- **NLP:** TF-IDF Vectorization
- **Clustering:** K-Means
- **Visualization:** Matplotlib, Seaborn

## 📊 Methodology
1. **Data Preprocessing:** - Cleaned salary ranges and calculated average annual compensation.
   - Normalized text data (job titles, locations, and categories) for consistency.
2. **Feature Engineering:** - Converted "skills_required" text into numerical vectors using **TF-IDF Vectorization** (ignoring English stop words).
   - Performed binary encoding for remote work availability.
3. **Clustering Model:** - Implemented a **K-Means algorithm** to group similar job profiles into clusters based on skill sets.
4. **Recommendation Engine:** - Developed a system that identifies a user's cluster based on their input skills and recommends the top 10 most frequent job titles within that specific market segment.

## 📈 Key Insights
Our model successfully identified distinct professional clusters. For instance, in the "Technology & Development" cluster, the most recommended roles include:
1. DevOps Engineer
2. Data Scientist
3. Frontend Developer
4. Backend Developer

## 🚀 How to Run
1. Clone the repository: `git clone https://github.com/your-username/your-repo-name.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Open `Job Market Analysis & Career Recommendation System.ipynb` in Jupyter Notebook or Google Colab.

---
Developed with 💡 by Bouachra Salma & Bel mahjoube Nadia
