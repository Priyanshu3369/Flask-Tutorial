# 🚀 Flask Web Application

![Flask Logo](https://upload.wikimedia.org/wikipedia/commons/3/3c/Flask_logo.svg)

## 📌 Overview

This is a simple Flask web application that provides multiple routes for basic functionalities such as greeting users, performing addition, and handling URL parameters.

## 📂 What's Inside?

- `index` ➝ Returns a simple "Hello World" message.
- `/hello` ➝ Another route that returns "Hello World".
- `/greet/<name>` ➝ Greets the user with the provided name.
- `/add/<int:number1>/<int:number2>` ➝ Adds two numbers and returns the result.
- `/handle_url_params?greeting=Hello&name=John` ➝ Uses query parameters to form a greeting.

## 🎯 API Endpoints

| Route                          | Method | Description                          | Example Request |
|--------------------------------|--------|--------------------------------------|----------------|
| `/`                            | GET    | Returns "Hello World"               | `/` |
| `/hello`                       | GET    | Returns "Hello World"               | `/hello` |
| `/greet/<name>`                | GET    | Greets the user with the given name | `/greet/Priyanshu` |
| `/add/<int:number1>/<int:number2>` | GET    | Adds two numbers and returns result | `/add/5/10` |
| `/handle_url_params`           | GET    | Uses query parameters for greeting  | `/handle_url_params?greeting=Hi&name=Alex` |

## 🌟 Features

✅ Simple and lightweight  
✅ Supports dynamic routing  
✅ Handles query parameters  
✅ Runs on Flask  

---

Feel free to modify it as per your needs! 🚀
