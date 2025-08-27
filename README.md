
# 💻 Yt2mp3

Web application that converts YouTube videos to mp3 files.<br/>

---

## 🛠️ Tech Stack

- **Back-end:** Kotlin • Spring Boot • Coroutines • Stomp • Gradle
- **Front-end:** Angular • TypeScript • HTML • CSS
- **Containerization:** Docker • Docker Compose  

---

## 🔧 Prerequisites

- [Java 21](https://www.oracle.com/java/technologies/downloads/#java21) (for local build)  
- [Docker & Docker Compose](https://docs.docker.com/get-started/get-docker/)
- [Git](https://github.com/git-guides/install-git)

---

## 🚀 Quick Start with Docker Compose

1. **Clone the repo**  
   ```bash
   git clone --recurse-submodules https://github.com/MihaelMajetic141/yt2mp3
   cd yt2mp3
   ```

2. **Build & run**

   ```bash
   docker-compose up --build
   ```

3. **Open Web App**

    * Open `http://localhost:4200` in browser.
    * Paste YouTube link and download the file.

4. **Reset & rebuild** (fresh DB)

   ```bash
   docker-compose down -v
   docker-compose up --build
   ```

---

## 🔍 API Reference

| Method | Endpoint                                                                  | Description                                                          |
| :----: |:--------------------------------------------------------------------------|:---------------------------------------------------------------------|
|  GET   | `/api/download/{id}`                                                      | Download mp3 file. `{id}` is generated after conversion.             |

---
