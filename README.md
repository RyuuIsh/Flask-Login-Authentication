# Flask-Login-Authentication
This is a Flask-based login authentication system that uses Flask-WTF (WTForms) for form validation and Flask-Bootstrap for styling. Users can enter their credentials, and if they match the predefined admin login, they gain access to a "Top Secret" page—otherwise, access is denied.

## Features
- Flask Web App with Authentication 🏗
- Form Handling with Flask-WTF 📝
- Bootstrap Integration for Styling 🎨
- Login Validation with Error Handling ⚠
- Secret Page for Authorized Users 🔓

## Tech Stack
- Flask (Python Web Framework) 🐍
- Flask-WTF (Form Handling & Validation) ✅
- Bootstrap-Flask (Frontend Styling) 🎨
- Jinja2 (Templating Engine) 🏗

## Project Structure
```
/flask_login
│── /templates
│   │── base.html         # Base Template
│   │── index.html        # Home Page
│   │── login.html        # Login Page
│   │── success.html      # Secret Page for Authorized Users
│   │── denied.html       # Access Denied Page
│── app.py                # Flask App with Login Logic
│── README.md             # Documentation
```

## Setup & Usage
### 1️⃣ Clone the Repository
```
git clone https://github.com/yourusername/Flask-Login-Authentication.git
cd Flask-Login-Authentication
```

### 2️⃣ Install Dependencies
```
pip install flask flask-wtf flask-bootstrap
```

### 3️⃣ Run the App
```
python app.py
```

💡 Open `http://127.0.0.1:5000/` in your browser!

## Customization
- Change admin credentials in `app.py`
- Modify CSS styles for better UI
- Add database support for real authentication

## Future Enhancements
- Use Flask-Login for user authentication 🔑
- Store user credentials in a database 🗄
- Deploy on Render / Vercel / Railway 🚀

💙 Secure Your Flask App with Authentication Today! 🚀
