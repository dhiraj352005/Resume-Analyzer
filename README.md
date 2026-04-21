# Resume Analyzer

[![Live App](https://img.shields.io/badge/Live-App-brightgreen)](https://resume-analyser-kp0f.onrender.com/)

---

## Description

**Resume Analyzer** is a full-stack AI-powered web application that analyzes resumes and provides meaningful insights such as skill extraction, resume evaluation, and improvement suggestions.

The system leverages **Google Gemini AI** for intelligent resume analysis and integrates secure authentication features like email verification and password reset. It also provides job recommendations using external APIs.

---

##  Tech Stack

* **Frontend:** HTML, CSS, React.js
* **Backend:** Spring Boot
* **Database:** MySQL

---

##  Preview

<p align="center">
  <img width="30%" src="https://github.com/user-attachments/assets/df7bb0c1-1f10-478d-b8c9-c2b1bf2369f4" />
  <img width="30%" src="https://github.com/user-attachments/assets/1c65a0cc-c915-4103-a7fe-30a975639ab0" />
  <img width="30%" src="https://github.com/user-attachments/assets/b8ca21ad-7c2f-470d-ad5d-73119b8fd9f1" />
</p>

<p align="center">
  <img width="30%" src="https://github.com/user-attachments/assets/3f945bf1-84dd-4052-9c65-709f512ae0a4" />
  <img width="30%" src="https://github.com/user-attachments/assets/d04af8b7-4e12-4948-94c6-3b1f15340180" />
  <img width="30%" src="https://github.com/user-attachments/assets/a0c6f513-2108-41c8-98b5-91e86d27d398" />
</p>

---

## 🔗 Frontend & Backend Integration

* React frontend is built and served by the Spring Boot backend
* Production build files are placed inside the backend **static** directory

### 📁 Structure

* `static/` → React build files
* `templates/` → Email templates (OTP verification & password reset)

---

## ⚙️ How to Run Locally

### 1. Clone Repository

```bash
git clone https://github.com/dhiraj352005/Resume-Analyzer.git
```

---

### 2. Open in IDE

* Open project in **IntelliJ IDEA / Eclipse**
* Load `pom.xml` and install dependencies

---

### 3. Configure `application.properties`

#### Database (MySQL)

```properties
spring.datasource.url=your_DB_URL
spring.datasource.username=your_DB_USERNAME
spring.datasource.password=your_DB_PASSWORD
```

#### Google OAuth

```properties
spring.security.oauth2.client.registration.google.client-id=your_GCP_ID
spring.security.oauth2.client.registration.google.client-secret=your_GCP_SECRET
```

#### Gemini AI

```properties
genKey=your_GEMINI_API_KEY
```

#### Mail Service

```properties
apiKey=your_MAIL_API_KEY
```

#### Job API

```properties
application-id=your_APP_ID
application-api-key=your_API_KEY
```

---

### 4. Run Backend

Run:

```
ResumeAnalyserApplication.java
```

---

### 5. Open in Browser

```
http://localhost:8080/
```

---

## ⚠️ Important Notes

* Gemini AI is used for resume analysis
* Mail service is required for authentication features
* Update API keys before running

---

## 🎨 Modifying Frontend

### Run Frontend (Dev Mode)

```bash
cd "frontend src"
npm install
npm run dev
```

---

### Build Frontend

```bash
npm run build
```

Replace files inside:

```
static/
```

---

##  Disclaimer

* This project is for educational purposes
* AI-generated insights may not always be accurate

---

## 👨‍💻 Author

**Dhiraj Umesh Raut**
📧 [dhiraj352005@gmail.com](mailto:dhiraj352005@gmail.com)

---
