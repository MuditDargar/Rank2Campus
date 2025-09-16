# 🎓 Rank2Campus – College Predictor App  

Rank2Campus is an intelligent **college prediction and recommendation web app** built with **Streamlit**.  
It helps students explore, filter, and predict college cut-offs based on their **EAMCET rank, caste, gender, branch, and tuition fee preferences**.  

---

## 📝 Usage  

- **Select filters** from the sidebar to view **Top 5 eligible colleges**.  
- **Visualize tuition fees and closing ranks** with interactive bar charts.  
- Use the **Predict Closing Rank** section to get **ML-based predictions**.  
- Get **Top N Colleges** and **personalized recommendations** tailored to your preferences.  

---

## 📊 Dataset  

The app uses a cleaned dataset containing college cut-off data:  

- **Institute Name**  
- **Branch**  
- **Caste**  
- **Gender**  
- **Tuition Fee**  
- **Closing Rank**  

## 🚀 Features  

- 🔍 **Filter Colleges:** Select caste, gender, branch, rank, and tuition fee to view eligible colleges.  
- 📊 **Visualize Data:** Interactive bar charts for tuition fees and closing ranks.  
- 🤖 **ML Predictions:** Predict the closing rank for your desired branch using a pre-trained ML model.  
- 💡 **Recommendations:** Get top 3 personalized college recommendations based on your rank and preferences.  
- 🏆 **Top Colleges:** See Top 10/15/20 unique colleges you may be eligible for based on rank.  
- 📚 **All Colleges:** Option to view all unique colleges in the dataset.  

---

## 🛠️ Tech Stack  

- [Streamlit](https://streamlit.io/) – Interactive frontend  
- [Pandas](https://pandas.pydata.org/) – Data handling  
- [Plotly Express](https://plotly.com/python/plotly-express/) – Data visualization  
- [Joblib](https://joblib.readthedocs.io/) – Model loading  
- [NumPy](https://numpy.org/) – Numerical operations  
- Pre-trained ML Model (RandomForest)  

---

## ⚙️ Installation & Setup  

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/your-username/rank2campus.git
   cd rank2campus

2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt

3. **Run the App**
   ```bash
   streamlit run app.py

