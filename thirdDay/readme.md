# 🚀 Flask Web App

![Flask Logo](https://upload.wikimedia.org/wikipedia/commons/3/3c/Flask_logo.svg)

Welcome to the **Flask Web Application**! This project is a simple yet powerful demonstration of how to use Flask for building dynamic web applications with Jinja2 templating and custom filters. 🎉

## 📂 Project Structure

- **`app.py`** - The main Flask application file.
- **`templates/`** - Directory containing HTML templates (`index.html`, `other.html`).
- **`static/`** - (Optional) Folder for CSS, JavaScript, and images.

## 🛠 Features

✅ **Dynamic Routing**: Multiple routes to serve different pages.
✅ **Jinja2 Templating**: Rendering dynamic content.
✅ **Custom Template Filters**:
  - 🔄 Reverse a string
  - 🔁 Repeat a string multiple times
  - 🔠 Alternate case of a string
✅ **Redirection**: Navigate between pages smoothly.

## 📜 Routes & Functionalities

| Route            | Functionality |
|-----------------|--------------|
| `/`             | Displays a greeting, a calculated result, and a list. |
| `/other`        | Shows a different page with dynamic content. |
| `/redirect_url` | Redirects to the `/other` route. |

## 🎨 Custom Jinja2 Filters

🌀 **Reverse String**: `{{ "hello" | reverse_string }}` → `"olleh"`
🔂 **Repeat String**: `{{ "hello" | repeat(3) }}` → `"hellohellohello"`
🔠 **Alternate Case**: `{{ "hello world" | alternate_case }}` → `"HeLlO WoRlD"`

## 🖥️ Tech Stack

- 🐍 **Python** (Flask)
- 🌐 **HTML & Jinja2** (Templating)
- 🚀 **Flask Routing & Filters**

## 🤝 Contributing

Feel free to fork and enhance this project! PRs are welcome. 😊


Happy Coding! 🚀🔥
