# 🚀 Flask Web App  

A simple Flask-based web application using HTML templates, Bootstrap, and static assets.  

---

## 📂 Project Structure  

/project-root
│
├── app.py # 💻 Main Flask application
│
├── templates/ # 📁 HTML Templates
│ ├── base.html # 🎨 Base template with Bootstrap & CSS
│ ├── index.html # 🏠 Main page extending base.html
│
├── static/ # 📁 Contains assets (not uploaded)
│ ├── css/ # 🎨 Bootstrap & Custom Styles
│ ├── js/ # ⚙️ Bootstrap JS & Scripts
│ ├── img/ # 🖼️ Images folder (Contains 'download.jpeg')

---

## ⚙️ How It Works  
1. **Flask Application (`app.py`)**  
   - Initializes a simple Flask server.  
   - Renders `index.html` when accessed at `/`.  

2. **Templates (`base.html`, `index.html`)**  
   - `base.html` provides a common structure for all pages.  
   - `index.html` extends `base.html` and displays:  
     - 🖼️ An image (`download.jpeg`)  
     - 🎨 A Bootstrap-styled button  
     - 📝 A sample text `"Hello World"`  

3. **Static Files (Stored in `static/`)**  
   - `css/` → Contains **Bootstrap & Custom CSS**  
   - `js/` → Contains **Bootstrap & Custom Scripts**  
   - `img/` → Stores images  

---
