# ⚡ Electrical Load Forecasting & Energy Optimization (Green AI)

A region-specific electric load forecasting app that combines AI-based prediction with real-time energy-saving recommendations. Built using Prophet, Random Forest, and Streamlit, this project promotes sustainable consumption through interpretable and lightweight modeling.

---

## 🌍 Overview

India’s growing electricity demands make forecasting regional load crucial for grid stability and sustainability. This project helps visualize short-term load trends and offers actionable tips to reduce unnecessary power use — a step toward energy-efficient, Green AI solutions.

---

## 🚀 Features

- 📊 Region-wise hourly electric load forecasting
- 🔮 Prophet-based time series modeling
- 🌡️ Weather-integrated model with monthly temperature correlation
- 📈 Random Forest baseline for comparison
- ✅ MAE, RMSE, and R² metrics
- 💡 Dynamic energy-saving recommendations
- 🧠 Green AI compliant: lightweight, interpretable, sustainable
- 🌐 Streamlit frontend for user interaction

---

## 📁 Project Structure

```
Electrical-Load-Forecasting/
│
├── Dataset/
│   ├── hourlyLoadDataIndia.xlsx       # Hourly load per region
│   └── monthly_temp.xlsx              # Monthly avg. temperature
│
├── Load Forecast.ipynb                # Notebook with model training & results
├── streamlit_app.py                   # Streamlit UI
├── requirements.txt                   # Python dependencies
└── README.md                          # This file
```

---

## 🔧 Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/Electrical-Load-Forecasting.git
cd Electrical-Load-Forecasting
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the app:
```bash
streamlit run streamlit_app.py
```

4. Ensure the datasets are in the path:
```
./Dataset/hourlyLoadDataIndia.xlsx
./Dataset/monthly_temp.xlsx
```

---

## 🧠 Models Used

| Model           | Description                             |
|-----------------|-----------------------------------------|
| Prophet         | For trend/seasonality decomposition and forecasting |
| Random Forest   | Baseline supervised learning comparison |

---

## 📊 Sample Metrics (Replace with actual values)

| Model         | MAE      | RMSE     | R² Score |
|---------------|----------|----------|----------|
| Random Forest | 1723.56  | 3012.85  | 0.87     |
| Prophet       | 1480.12  | 2679.43  | 0.90     |

---

## 🧩 Green AI Approach

- ✅ Low-compute models (Prophet ≠ deep learning)
- ✅ Regional selection avoids overtraining
- ✅ Encourages real-world energy efficiency
- ✅ Transparent + interpretable forecasting

---

## 📸 Screenshots

Add screenshots here showing the:
- Region selector
- Forecast graph
- Recommendation card
- Accuracy metrics

---

## 📌 Future Enhancements

- [ ] Real-time weather API integration
- [ ] Daily retraining with new load data
- [ ] Mobile-friendly dashboard
- [ ] Deploy on Streamlit Cloud

---

## 👥 Author

- Akshat D (your name / institution)
- Feel free to update with contributors or link to your paper/report

---

## 📜 License

MIT License – see LICENSE file for details.