# 💊 MediSearch  
A Medicine Recommendation and Search Engine built with **Streamlit** + **MySQL**.  

---

## 🚀 Overview  
MediSearch is a web-based application that allows users to search for medicines, get personalized recommendations, and explore purchase history in a simple, interactive interface.  

It uses:  
- **Streamlit** for the user interface  
- **MySQL** for data storage  
- **Pandas & NumPy** for data handling  
- **Python Dotenv** for secure environment variable management  

---

## ✨ Features  
- 🔍 Search medicines by **name** or **symptoms**  
- ⭐ View **top-rated medicines**  
- 🧑‍⚕️ Get **personalized recommendations** based on purchase history  
- 📊 Explore the **database interactively**  

---

## 🛠️ Tech Stack  
- Python (Streamlit, Pandas, NumPy)  
- MySQL  
- Python Dotenv  

---

## ⚙️ Installation & Setup  

### 1️⃣ Clone the repository  
```bash
git clone <repo_url>
cd MediSearch
```

### 2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Setup environment variables
Create a file named .env in the root folder and add:
```bash
MYSQL_HOST=localhost
MYSQL_USER=root
MYSQL_PASSWORD=yourpassword
MYSQL_DATABASE=medisearch_db
```
### 4️⃣ Setup the database
Run the SQL schema file:
```bash
mysql -u root -p medisearch_db < db/schema.sql
```

### 5️⃣ Run the app
```bash
streamlit run app.py
```
### 🗄️ Database Schema

medicines → stores medicine details

users → stores user information

purchase_history → tracks user purchases

### 📸 Screenshots 
**1️⃣ Home Page** 
![Image](https://github.com/user-attachments/assets/24bfed85-aa81-4dce-a120-d6b56fe4b0b5)
**2️⃣ Search Results** 
![Image](https://github.com/user-attachments/assets/c3e24d88-7187-4ae3-a38c-203e88df6f43)
**3️⃣ Recommendations Page** 
![Image](https://github.com/user-attachments/assets/aae5f605-0ca9-4d71-98dc-a72cb7a7c8a7)

