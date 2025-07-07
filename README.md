# 📇 MongoDB CLI Contact Book

A beginner-friendly **command-line contact manager** built with **Python** and **MongoDB**.

This simple project helps you learn how to:
- Connect Python to MongoDB using PyMongo
- Perform basic **CRUD** operations
- Build interactive CLI applications

---

## ✅ Features

- 📝 Add new contacts
- 📋 View all saved contacts
- 🔍 Search for a contact by name
- 🗃️ Data stored in MongoDB `contact_db` database

---

## 📁 Project Structure

```

mongo-cli-contact-book/
├── contact\_book.py        # Main CLI app
├── requirements.txt       # Required Python packages
└── README.md              # You are here!

````

---

## 🧱 Requirements

- Python 3.8+
- MongoDB (running locally)
- pip (Python package installer)

---

## 🔧 Setup Instructions

### 1. Clone This Repository

```bash
git clone https://github.com/yourusername/mongo-cli-contact-book.git
cd mongo-cli-contact-book
````

### 2. Install Python Packages

```bash
pip install -r requirements.txt
```

### 3. Start MongoDB

Make sure MongoDB is running on your machine:

```bash
mongod
# after: Starts MongoDB server (usually on localhost:27017)
```

### 4. Run the App

```bash
python contact_book.py
```

---

## 🧪 How to Use It

You'll see a simple menu:

```
1. Add Contact
2. View Contacts
3. Search Contact
4. Exit
```

### ➕ Add a Contact

```
Enter name: Alice
Enter phone number: 012-3456789
✅ Contact added!
```

### 📋 View All Contacts

```
👤 Alice - 📞 012-3456789
👤 Bob   - 📞 011-2222333
```

### 🔍 Search Contact

```
Search name: Alice
👤 Alice - 📞 012-3456789
```

---

## 🧠 What You'll Learn

* How to use **PyMongo** to interact with MongoDB
* How to build and structure CLI apps
* How to store and retrieve data using **NoSQL**

---

## 💡 Ideas for Improvement

* ✅ Add email, address, or birthday fields
* ✏️ Edit or delete existing contacts
* 🕒 Add creation timestamps
* 🌐 Connect to MongoDB Atlas (cloud)

---

## 📚 Technologies Used

* **Python** — programming language
* **MongoDB** — NoSQL database
* **PyMongo** — MongoDB Python driver

---

## 📦 Install Requirements (for reference)

```bash
pip install pymongo
```

---

## 🏁 Final Notes

This project is perfect for beginners who want to:

* Practice working with MongoDB and Python
* Build useful tools from the command line
* Understand database concepts without web frameworks

---

Happy hacking! 💻

```

---

Let me know if you'd like a:
- GUI version with **Tkinter**
- JSON **import/export**
- **Dockerfile** to containerize the app

I can generate the next step for you!
```
