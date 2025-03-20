# 🚀 Flask Session & Cookie Management

Welcome to this simple Flask project that demonstrates how to manage **sessions** and **cookies** effectively. 📝

---

## 📂 Project Structure
```
│── app.py             # Flask application file
│── /templates         # Folder containing HTML templates
│   │── base.html      # Base template
│   │── index.html     # Main page with links to session & cookie actions
```

---

## 🏗 Features
✅ Manage **session data** (store and retrieve values) 🔐  
✅ Manage **cookies** (set, get, and remove cookies) 🍪  
✅ Dynamic HTML rendering using Flask & Jinja2 🎨  

---

## 📜 How It Works
### 1️⃣ **Session Management**
- **Set Session Data** ➝ Stores a name and a message in the session
- **Get Session Data** ➝ Retrieves stored session values
- **Clear Session** ➝ Deletes all session data

### 2️⃣ **Cookie Management**
- **Set Cookie** ➝ Creates a cookie with a predefined value
- **Get Cookie** ➝ Fetches the stored cookie value
- **Remove Cookie** ➝ Deletes the stored cookie

---

## 🛠 Setup & Run
### 🔧 **Requirements**
Ensure you have Python installed. Then install Flask:
```sh
pip install flask
```

### ▶ **Run the App**
```sh
python app.py
```
The app will run at **http://127.0.0.1:5000/** 🚀

---

## 📌 Routes
| Route              | Description |
|-------------------|-------------|
| `/`              | Home page with interactive links |
| `/set_data`      | Sets session data |
| `/get_data`      | Retrieves session data |
| `/clear_session` | Clears session data |
| `/set_cookie`    | Sets a cookie |
| `/get_cookie`    | Retrieves cookie value |
| `/remove_cookie` | Deletes the cookie |

---

## 🎨 UI Preview
📌 The project has a simple **HTML UI** using Jinja2 templating.
✅ Interactive links to trigger session & cookie actions.

---

## 🤝 Contribution
Feel free to fork and improve the project! 🚀

---

Made with ❤️ using Flask 🐍
