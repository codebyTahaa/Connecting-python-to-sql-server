# 🔗 Python + SQL Server Integration Project

This project demonstrates how to connect a Python application with a Microsoft SQL Server database. It showcases how to establish a database connection using `pyodbc`, execute SQL queries, and perform basic operations like data retrieval.

---

## 📌 Project Overview

- ✅ Establish a secure connection between Python and SQL Server  
- ✅ Perform `SELECT` and `INSERT` operations  
- ✅ Use environment variables to protect sensitive credentials  
- ✅ Practical use case for data engineering and backend development  

---

## 🧰 Tech Stack

| Component     | Technology           |
|---------------|----------------------|
| Language       | Python 3.x           |
| Database       | Microsoft SQL Server |
| Connector      | pyodbc               |
| Security       | python-dotenv        |

---

## 🗂️ Folder Structure

```
sql-server-connection-project/
│
├── connect.py            # DB connection setup using pyodbc
├── fetch_data.py         # SQL SELECT query execution
├── insert_data.py        # Insert records into SQL Server
├── .env                  # Secure credentials (ignored by Git)
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation
```

---

## ⚙️ Setup Instructions

### 1. Clone this repository

```bash
git clone https://github.com/your-username/sql-server-connection-project.git
cd sql-server-connection-project
```

### 2. Create and activate virtual environment (optional)

```bash
python -m venv venv
venv\Scripts\activate      # Windows
# or
source venv/bin/activate  # macOS/Linux
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure environment variables

Create a `.env` file in the project root:

```
DRIVER={ODBC Driver 17 for SQL Server}
SERVER=your_server_name
DATABASE=your_database_name
UID=your_username
PWD=your_password
```

> ℹ️ Make sure you have the correct ODBC driver installed on your system.

### 5. Run a sample script

```bash
python fetch_data.py
```

---

## 📌 Example Output

```
Connection successful!
Customer ID: 101 | Name: Ali Khan | Email: ali@example.com
Customer ID: 102 | Name: Sana Malik | Email: sana@example.com
```

---

## 🚀 Use Cases

- ETL pipelines in Data Engineering  
- Backend apps interacting with SQL Server  
- Admin dashboards using Python-based scripts  
- Learning purpose for database connectivity  

---

## 🙋‍♂️ Author

**Muhammad Taha**  
Cloud Data Engineer | Python Developer  
📍 Saylani Mass IT Training  
📧 taha.bilal20303821@gmail.com*  
🔗 www.linkedin.com/in/muhammad-taha-023a89287*

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).
