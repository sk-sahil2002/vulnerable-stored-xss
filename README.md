# 🧪 XSS Lab - Java Web App (by Sahil)

This is a simple vulnerable Java web application designed for demonstrating **Stored Cross-Site Scripting (XSS)** attacks. It includes:

- A basic login system (`sahil` and `vivek`)
- A comment board with a **stored XSS vulnerability**
- Java servlet-based backend using **Tomcat** and `JSESSIONID` for sessions
- Easy deployment using **Docker**
- Clean UI for realistic testing

---

## 🔥 Live Features

- ✅ Login with session support
- 🗨️ Comment section that stores malicious scripts
- 🚨 Simulated real-world XSS vulnerability
- 🛠 Built with JSP, Servlets (no frameworks!)
- 🐳 Containerized with Docker + Tomcat 9

---

## 🧑‍💻 Demo Users

| Username | Password |
|----------|----------|
| sahil    | password |
| vivek    | password |

---

## 🚀 Deployment Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/ak-sahil2002/vulnerable-stored-xss.git
unzip the file
cd xss-lab-java
docker build -t xss-lab-java .
docker run -p 8080:8080 xss-lab-java

