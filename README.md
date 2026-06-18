# 🧑‍🤝‍🧑 Discover Customers Gender

A web-based machine learning application that predicts the **gender of customers** based on behavioral and demographic data. Built with Python for the ML backend and HTML for the frontend interface, with a database layer for storing and querying customer records.

---

## 📌 Overview

Understanding customer demographics is critical for businesses to personalize their services and improve targeting strategies. This project uses machine learning to infer customer gender from available data, presented through a clean web interface that interacts with a backend database.

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | HTML, CSS |
| Backend / ML | Python |
| Database | SQL (relational database) |

---

## 📁 Project Structure

```
Discover_Customers_Gender/
│
├── Database/                        # Database schema and data files
├── discover_customers_gender/       # Core application (ML model + web logic)
└── README.md
```

---

## ⚙️ Setup & Installation

### Prerequisites
- Python **3.7 or above**
- A web browser (Chrome, Firefox, etc.)
- A SQL-compatible database (MySQL, SQLite, etc.)

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/akashkadambala/Discover_Customers_Gender.git
   cd Discover_Customers_Gender
   ```

2. **Install Python dependencies**
   ```bash
   pip install -r requirements.txt
   ```
   *(If no requirements.txt, install commonly used packages: `pip install flask scikit-learn pandas numpy`)*

3. **Set up the database**
   - Import the SQL files from the `Database/` folder into your database system
   - Update the database connection settings in the application config if needed

4. **Run the application**
   ```bash
   python app.py
   ```
   *(or the main entry-point script inside `discover_customers_gender/`)*

5. **Open in browser**
   ```
   http://localhost:5000
   ```

---

## 🖥️ Features

- Input customer attributes through a web form
- Predict customer gender using a trained ML model
- Store and retrieve customer records from a database
- Clean, browser-based interface

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
