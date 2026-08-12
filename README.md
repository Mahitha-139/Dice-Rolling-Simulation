# 🎲 Visual Dice Rolling Simulator

A beginner-friendly web application that simulates rolling a six-sided die. This project connects a backend **Python (Flask)** script with a styled **HTML & CSS** user interface.

---

## 🚀 Features
* **Interactive UI:** A clean, modern dark-themed web interface.
* **Dynamic Generation:** Uses Python's `random` module to pick numbers instantly.
* **Responsive Button:** A styled button with active click animations.

---

## 🛠️ Tech Stack
* **Backend:** Python 3, Flask Framework
* **Frontend:** HTML5, CSS3

---

## 📂 Project Structure
```text
dice_app/
│
├── app.py             # Python Flask backend logic
├── README.md          # Project documentation
└── templates/
    └── index.html     # HTML frontend layout and CSS styling
```

---

## 📦 Installation & Setup

Follow these steps to run the project locally on your machine:

### 1. Clone or Download the Project
If you have Git installed, clone this repository:
```bash
git clone https://github.com
cd YOUR-REPO-NAME
```
*(Alternatively, just download the ZIP file and open the folder in your terminal).*

### 2. Install Dependencies
Make sure you have Python installed. Then, install Flask using pip:
```bash
pip install flask
```

### 3. Run the Application
Start the local development server by running:
```bash
python app.py
```

### 4. Open in Your Browser
Once the server is running, open your web browser and navigate to:
```text
http://127.0.0
```

---

## 🧠 What I Learned
* Setting up a basic **Flask** server and handling routing (`@app.route`).
* Managing data exchange between Python logic and HTML templates using **Jinja syntax** `{{ dice_value }}`.
* Building a responsive UI container centered with **CSS Flexbox**.
* Handling user interaction with HTML forms and `POST` methods.
