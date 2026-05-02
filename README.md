# 📦 DTDC Label Generator (Flask App)

A simple and clean **DTDC-style courier label generator** built using Flask. This app allows users to input shipment details and generate a professional-looking label with a barcode.

---

## 🚀 Live Demo

👉 **Render Deployment Link:**
[https://your-app-name.onrender.com](https://dtdc-label-app.onrender.com/)

*(Replace with your actual Render URL)*

---

## ✨ Features

* 📄 Clean DTDC-style label UI
* 🧾 Input form for shipment details
* 📦 Automatic barcode generation
* 🖼️ Barcode rendered as image (base64 embedded)
* ⚡ Fast and lightweight Flask backend
* 📱 Responsive design

---

## 🛠️ Tech Stack

* **Backend:** Flask (Python)
* **Frontend:** HTML + CSS (inline templates)
* **Barcode Generation:** python-barcode
* **Deployment:** Render

---

## 📂 Project Structure

```
project/
│── app.py          # Main Flask application
│── requirements.txt
│── README.md
```

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/dtdc-label-generator.git
cd dtdc-label-generator
```

### 2. Create virtual environment (optional but recommended)

```bash
python -m venv venv
venv\Scripts\activate   # Windows
source venv/bin/activate # Mac/Linux
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the app

```bash
python app.py
```

### 5. Open in browser

```
http://127.0.0.1:5000
```

---

## 📦 requirements.txt

```txt
Flask
python-barcode
pillow
```

---

## 🌐 Deploy on Render

1. Push code to GitHub
2. Go to https://render.com
3. Create a new **Web Service**
4. Connect your GitHub repo
5. Use these settings:

* **Build Command:**

```bash
pip install -r requirements.txt
```

* **Start Command:**

```bash
python app.py
```

* **Environment:**

```
Python 3.x
```

---

## 📸 Output

* Generates a **DTDC-style shipping label**
* Includes barcode dynamically generated from input

---

## 💡 Future Improvements

* PDF download option
* Database storage (MongoDB / SQLite)
* Authentication system
* Bulk label generation
* QR code support

---

## 👨‍💻 Author

**Parth Manocha**
B.Tech CSE Student

---

## ⭐ Contribute

Feel free to fork this repo and improve it!

---

## 📜 License

This project is open-source and free to use.
