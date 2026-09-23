# 🏏 IPL Analytics

A **Python-based IPL Analytics Dashboard** built with **FastAPI** for the backend and **Streamlit** for the interactive frontend.

The project analyzes IPL match and ball-by-ball delivery data to provide useful cricket statistics and insights through a user-friendly dashboard.

## 🚀 Tech Stack

* **Python**
* **FastAPI** – Backend API
* **Streamlit** – Interactive dashboard
* **Pandas** – Data analysis and processing
* **Uvicorn** – ASGI server
* **CSV** – Data source

## 📂 Project Structure

```text
IPL-Analytics/
│
├── backend/
│   └── main.py
│
├── frontend/
│   └── app.py
│
├── data/
│   ├── matches.csv
│   └── deliveries.csv
│
├── requirements.txt
└── README.md
```

## 📊 Dataset

Place the following IPL datasets inside the `data/` directory:

```text
data/
├── matches.csv
└── deliveries.csv
```

* `matches.csv` – Contains IPL match-level information.
* `deliveries.csv` – Contains ball-by-ball delivery information.

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/IPL-Analytics.git
cd IPL-Analytics
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the virtual environment

**Windows:**

```bash
venv\Scripts\activate
```

**macOS/Linux:**

```bash
source venv/bin/activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

## ▶️ Run FastAPI Backend

Start the FastAPI server using:

```bash
uvicorn backend.main:app --reload
```

The API will be available at:

```text
http://127.0.0.1:8000
```

FastAPI documentation:

```text
http://127.0.0.1:8000/docs
```

## 📈 Run Streamlit Dashboard

Open a new terminal and run:

```bash
streamlit run frontend/app.py
```

The Streamlit dashboard will open in your browser.

## ✨ Features

* 📊 IPL match data analysis
* 🏏 Player performance analysis
* 👥 Team-wise statistics
* 📈 Interactive visualizations
* 🔎 Data-driven cricket insights
* ⚡ FastAPI backend APIs
* 🖥️ Streamlit interactive dashboard
* 📁 CSV-based data processing

## 🔮 Future Enhancements

* Add advanced player performance metrics
* Add team comparison features
* Add IPL season-wise analysis
* Add player prediction models
* Add interactive filters
* Deploy the application using cloud services
* Integrate real-time cricket data APIs

## 👨‍💻 Author

**Pranav Sandbhor**

GitHub: [https://github.com/Pranav-Sandbhor-008]

LinkedIn: [https://www.linkedin.com/in/pranavsandbhor/]

## 📄 License

This project is intended for **educational and learning purposes**.
