


# ✈️ Travel Recommendation System

This project is a **Travel Recommendation System** built using **Flask**, **Machine Learning**, and **Collaborative Filtering** techniques. It suggests personalized travel destinations to users based on their past preferences and behavior.

---

## 📌 Features

- 🧠 ML-powered personalized travel destination recommendations
- 📊 Collaborative filtering using user history and reviews
- 💬 Clean UI built with HTML and Flask backend
- 📁 Integration with preprocessed travel data and trained model

---

## 🛠️ Technologies Used

- Python 🐍
- Flask 🌐
- Scikit-learn ⚙️
- Pandas 📊
- HTML/CSS 🖥️
- Pickle (for model and label encoding serialization)

---

## 🧩 Project Structure

```
.
├── app.py                            # Flask backend
├── Travel Recommendation System.ipynb  # Main ML notebook
├── model.pkl                         # Trained recommendation model
├── label_encoders.pkl                # Serialized label encoders
├── index.html                        # Home page
├── recommendation.html               # Result page
├── Final_Updated_Expanded_Users.csv  # User data
├── Final_Updated_Expanded_UserHistory.csv  # User travel history
├── Final_Updated_Expanded_Reviews.csv      # User reviews
├── Expanded_Destinations.csv         # Destination information
├── final_df.csv                      # Combined and cleaned dataset
└── Travel Agency Logo Advert.mp4     # Optional promo video
```

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

If you don’t have a `requirements.txt`, install manually:
```bash
pip install flask pandas scikit-learn
```

### 3. Run the app
```bash
python app.py
```

Visit `http://127.0.0.1:5000` in your browser.

---

## 🎯 How It Works

- Users are matched to similar users based on historical travel patterns.
- A recommendation engine filters and ranks destinations using collaborative filtering.
- Trained model and encoders are loaded via pickle for quick runtime predictions.

---

## 📷 Screenshots

> Add UI screenshots here if you'd like! (index.html & recommendation.html pages)

---

## 🙋‍♂️ Author

**Ritish Sharma**  
3rd Year B.Tech IT, NIT Srinagar  
📧 [Add your email or LinkedIn here]

---

## 📜 License

This project is open-source and free to use under the MIT License.
