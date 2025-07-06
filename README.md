# Kerokan Docker App

A full-stack CRUD web application for managing tutorials using:

* **Backend**: Node.js, Express, Sequelize, MySQL
* **Frontend**: React.js, Bootstrap
* **Deployment**: Docker & Docker Compose

## Features

* Create, Read, Update, Delete tutorials
* Search tutorials by title
* Filter published tutorials
* Responsive React UI
* Dockerized for easy deployment

---

## Project Structure

```
root/
├── kerokan-api/         # Node.js backend (Express + Sequelize + MySQL)
│   ├── app/
│   ├── Dockerfile
│   └── server.js
├── kerokan-ui/          # React frontend
│   ├── public/
│   ├── src/
│   └── Dockerfile
├── .env                 # Environment variables
├── docker-compose.yml   # Multi-container setup
```

---

## Prerequisites

* [Docker](https://www.docker.com/)
* [Docker Compose](https://docs.docker.com/compose/)

---

## Setup and Deployment

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/kerokan-docker-app.git
cd kerokan-docker-app
```

### 2. Configure Environment Variables

```bash
cp .env.sample .env
```

Make sure to modify the `.env` file if needed.

### 3. Run with Docker Compose

```bash
docker-compose up --build
```

### 4. Access the App

* Frontend: [http://localhost:8888](http://localhost:8888)
* Backend API: [http://localhost:6868/api/tutorials](http://localhost:6868/api/tutorials)

---

## Tech Stack

### Backend

* Node.js
* Express
* Sequelize
* MySQL

### Frontend

* React.js
* Bootstrap 4
* Axios

### Deployment

* Docker
* Docker Compose

---

## Authors

* Indrasworo Suryo Prayogo
* \Anastasya Selena Anandita Adnan
