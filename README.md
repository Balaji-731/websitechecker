# 🛡️ Phishing URL Detection System  
### AI-powered Cybersecurity Web Application (Flask + Machine Learning + Strict Feature Extractor)

This project is a complete **phishing URL detection system** built using:

- 🚀 **Machine Learning**
- 🕵️ **Advanced Feature Engineering (30 URL features)**
- 🔥 **Strict Phishing Detection Layer**
- 🌐 **Flask Web Application**
- 🎨 **Modern Cyber-Themed UI**

The system classifies URLs as **SAFE** or **UNSAFE** with extremely high accuracy and catches modern phishing attacks that traditional ML models often miss.

---

# ✨ Features

- 🔍 **ML-Based Detection** using 30 handcrafted URL features  
- 🔥 **Strict Mode** — detects brand impersonation, suspicious TLDs, high-entropy domains, URL shorteners, IP-based URLs, etc.  
- 🖥️ **Cyber-Themed UI** with animations, neon effects, and spinner  
- 📌 **Accurate even against modern phishing attacks**  
- ⚡ **Fast response** (single-page output, no repeated result on refresh)  
- 🚀 **Works with your existing model — no changes required**

---

## 🛑 What Attacks It Detects

✔ Fake login pages  
✔ Brand impersonation (PayPal, Google, banks…)  
✔ Shortened phishing links  
✔ IP-based phishing servers  
✔ High-entropy (random char) domains  
✔ Suspicious TLDs (.xyz, .buzz, .tk, .zip…)  
✔ Delivery / banking scam URLs  


---

## ⚙️ Setup & Installation

1️⃣ Clone Repository
git clone https://github.com/Balaji-731/networksecurity.git

cd networksecurity

2️⃣ Create Virtual Environment
python -m venv venv

venv\Scripts\activate        # Windows

source venv/bin/activate     # Mac/Linux

3️⃣ Install Dependencies

pip install -r requirements.txt

4️⃣ Add .env file

MONGO_DB_URL=your_url

SESSION_KEY=your_secret_key

5️⃣ Run Application

python app.py


Now open 👇
👉 http://127.0.0.1:5000/

🧪 Try Sample URLs

🟥 Phishing URLs

    <!-- https://security-paypal-com.us/login
    http://bit.ly/secure-update-login
    https://google.com.security-alert.xyz
    http://192.168.0.77/login.php
    https://dhl.track-delivery-alert.shop -->


🟦 Safe URLs

    https://www.google.com
    https://www.github.com
    https://www.microsoft.com
    https://www.sbi.co.in
    https://www.amazon.com

🤝 Contribution

    Feel free to contribute by:

    Opening issues

    Creating pull requests

    Suggesting new strict detection rules

    Improving dataset or model performance

🛡️ Disclaimer

    This project is ONLY for educational and cybersecurity research.
    Do not open phishing URLs in your browser.

👤 Author

    P Balaji

    GitHub: https://github.com/Balaji-731
    Email: poralabalaji@gmail.com


