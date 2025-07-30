# DVWA-Docker-Lab
 Simple lab environment for practicing web application security using [DVWA – Damn Vulnerable Web App](http://www.dvwa.co.uk/), deployed in Docker.




Clone the repository and run the environment using Docker Compose: (I will add repository later - sory)

```bash
git clone https://github.com/CyberFaust55/dvwa-docker-lab.git
cd dvwa-docker-lab
docker-compose up -d
```

Then open your browser at:

```
http://localhost:8080
```

### 🧑‍💻 Default Credentials

- **Username**: `admin`
- **Password**: `password`

After login, go to `Setup / Reset DB` to initialize the database.

## 🛠️ What’s Included

- **DVWA**: A PHP/MySQL vulnerable web app
- **MySQL 5.7**: Required backend DB
- **Pre-configured for local testing and Wazuh integration**

## 📚 Use Cases

- Practice OWASP Top 10 attacks
- Test Wazuh detection rules (e.g., brute-force alerts)
- Blue Team training lab

---

⚠️ **Warning**: Do not expose this to the internet. For local testing only!
```bash
git clone https://github.com/CyberFaust55/dvwa-docker-lab.git
cd dvwa-docker-lab
docker-compose up -d
```

Then open your browser at:

```
http://localhost:8080
```

### 🧑‍💻 Default Credentials

- **Username**: `admin`
- **Password**: `password`

After login, go to `Setup / Reset DB` to initialize the database.

## 🛠️ What’s Included

- **DVWA**: A PHP/MySQL vulnerable web app
- **MySQL 5.7**: Required backend DB
- **Pre-configured for local testing and Wazuh integration**

## 📚 Use Cases

- Practice OWASP Top 10 attacks
- Test Wazuh detection rules (e.g., brute-force alerts)
- Blue Team training lab

---

⚠️ **Warning**: Do not expose this to the internet. For local testing only!
