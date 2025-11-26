# RateMyStore

RateMyStore is a full-stack web application that allows users to rate and review registered stores. The platform supports three user roles: **Admin**, **Store Owner**, and **Normal User**, each with their own set of features and dashboards.

---

## Live Links & Repositories

### Live Deployment:
- Frontend (React): https://rate-my-store-frontend-sable.vercel.app
- Backend (Express API): https://ratemystore-backend.onrender.com

### GitHub Repositories:
- Frontend Repo: https://github.com/RounakRajSingh620/RateMyStore-Frontend
- Backend Repo: https://github.com/RounakRajSingh620/RateMyStore-Backend

---

## Tech Stack

- **Frontend**: ReactJS
- **Backend**: NodeJS, ExpressJS
- **Database**: MySQL
- **Hosting**: Vercel (frontend), Render (backend)

---

## Features

### Admin
- Add users (admin or normal), add stores
- Dashboard: total users, ratings, stores
- Filter/sort users and stores by name, email, address, role
- View users and their role (including average rating for store owners)
- Logout

### Normal User
- Signup/login
- View all stores
- Search by name/address
- View:
  - Store name
  - Store address
  - Overall rating
  - Own submitted rating
- Submit or update rating (1–5)
- Change password
- Logout

### Store Owner
- Login/logout
- Change password
- View average rating of owned store
- View users who submitted ratings

---

## Prerequisites

- Node.js and npm
- MySQL Server
- Git CLI

---

## Setup Instructions for clone

### 1. Clone the Repositories

```bash
git clone https://github.com/RounakRajSingh620/RateMyStore-Frontend
git clone https://github.com/RounakRajSingh620/RateMyStore-Backend
