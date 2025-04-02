# 🛒 MyPersonalEcommerce - Secure Django E-commerce Platform

<p align="center">
  <em>An evolving e-commerce platform built with security and scalability in mind using Django.</em>
  <br><br>
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Django-4.x-darkgreen?logo=django&logoColor=white" alt="Django"/>
  <img src="https://img.shields.io/badge/Database-PostgreSQL-blue?logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/Status-Under%20Development-orange" alt="Status"/>
  <br>
  <img src="https://komarev.com/ghpvc/?username=Owono2001&style=flat-square&color=7DF9FF" alt="Profile Views"/>
  <br>
  <sub style="font-family: 'Space Mono', monospace; color: #7DF9FF;">Your visit sparks innovation! 🔥</sub>
</p>

---

## 🚀 Project Overview

`MyPersonalEcommerce` is a **secure and actively developing** e-commerce platform built using the **Django framework**. The core focus is on integrating robust security measures while providing a foundation for essential e-commerce functionalities tailored for Admin, Merchant, and Customer roles.

⚠️ **Please Note:** This project is currently **under heavy development**. Features are being added and refined regularly. Stay tuned for updates!

---

## 🛡️ Security First Approach

Security is paramount in this project. Key implemented measures include:

* 🔑 **Authentication & Authorization:** Robust role-based access control (Admin, Merchant, Customer).
* 🔒 **Data Encryption:** Utilization of **Fernet encryption** to protect sensitive user data (e.g., passwords, personal info) at rest.
* 🛡️ **Input Validation & Sanitization:** Server-side checks to actively prevent common web vulnerabilities like SQL Injection (SQLi), Cross-Site Scripting (XSS), and mitigate brute-force login attempts.
* 🤖 **CAPTCHA Integration:** Leveraging **Google reCAPTCHA** (v2/v3 - specify if known) to shield forms (like registration, login) from bots and automated spam.
* 📩 **OTP Authentication:** An additional layer of security via One-Time Passwords for critical actions (e.g., password recovery, high-value transactions).

---

## 🎥 Project Demo

Check out a quick glimpse of the current functionality:

*(Ensure the `demo.gif` file is present in a `videos` folder within your repository for this link to work, or update the path)*
![E-commerce Demo GIF](videos/demo.gif)

---

## 💻 Tech Stack

This project is built with a focus on robust and scalable technologies:

* **Backend Framework:** `Django` (Python)
* **Programming Language:** `Python`
* **Database:** `PostgreSQL`
* **Security Libraries:** `Cryptography (Fernet)`, `django-recaptcha` (or specific library used), OTP library (e.g., `django-otp`)
* **Frontend:** `HTML`, `CSS`, `JavaScript` (Currently basic, full frontend interface is planned)
* **Deployment (Planned):** `Docker` & `Docker Compose` for containerization.

---

## 🗺️ Development Roadmap (Future Enhancements)

The journey continues! Key features planned or in progress:

* ✅ **Payment Gateway Integration:** Securely process payments via Stripe / PayPal / other providers.
* ⏳ **Product & Inventory Management:** Enhanced features for merchants to manage stock levels, variations, etc.
* 🎨 **Modern Frontend UI/UX:** Develop a responsive and appealing user interface (potentially using a framework like React/Vue or Django templates with HTMX/Alpine.js).
* 📊 **User Analytics Dashboard:** Insights for admins/merchants on sales, traffic, and user behavior.
* 🚢 **Dockerized Deployment:** Streamline setup and ensure consistent environments.
* 🤖 *(Optional)* **AI-Powered Fraud Detection:** Implement ML models to identify potentially fraudulent activities.
* 📱 *(Optional)* **Progressive Web App (PWA) Support:** Enhance mobile experience and offline capabilities.

---

## 💡 Contributing

Passionate about e-commerce or Django security? Contributions are highly welcome!

1.  **Fork** the repository.
2.  Create your **Feature Branch** (`git checkout -b feature/YourAmazingFeature`).
3.  **Commit** your Changes (`git commit -m 'feat: Add YourAmazingFeature'`). *Following Conventional Commits is appreciated!*
4.  **Push** to the Branch (`git push origin feature/YourAmazingFeature`).
5.  Open a **Pull Request** detailing your changes.

Let's build a secure and robust e-commerce platform together! 🚀

---

## 📞 Contact

* **Developer:** Pedro Fabian Owono Ondo Mangue
* **GitHub:** [![GitHub Badge](https://img.shields.io/badge/-Owono2001-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Owono2001)
* For bug reports, feature requests, or other inquiries, please **create an issue** on this repository.

---
