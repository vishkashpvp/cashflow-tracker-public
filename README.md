# Cashflow Tracker

> **Note:** This README is for the public version of the `Cashflow Tracker` project. The actual project source code and additional details are in a private repository.

**`Cashflow Tracker`** is a web app designed to help users track their expenses and earnings, providing insights into their expenditure, spending, or profits across various categories such as food, travel, investments, and more.

## Project Overview

The Cashflow Tracker empowers users with the following features:

- **User Authentication:** Utilizes `Google` and `Facebook` `OAuth` for seamless user login, eliminating the need for additional signup.
- **Expense Tracking:** Easily categorize and track expenses.
- **Earnings Management:** Add and manage earnings for a comprehensive financial view.
- **Entry Modification/Deletion:** Flexibility to modify or delete existing entries.
- **Manual Operation:** Operates on a manual basis, ensuring user control without intrusive permissions.

## Tech Stack

- **Frontend:**

  - [Angular](https://angular.io/)
  - [TailwindCSS](https://tailwindcss.com/)

- **Backend:**

  - [Go](https://go.dev/)
    - [Gin](https://gin-gonic.com/)

- **Database:**

  - [MongoDB](https://www.mongodb.com/)
  - [Firebase](https://firebase.google.com/docs/database)

- **Containerization:**

  - [Docker](https://www.docker.com/)

## Development Server

To set up the development environment:

1. **Frontend (Client):**

   - Navigate to the `client` directory and run `npm start` for a dev server.
   - Visit [http://localhost:4200/](http://localhost:4200/) to access the frontend.

2. **Backend (Server):**
   - Navigate to the `server` directory and run `go run main.go` or `go run .` for a dev server.
   - Visit [http://localhost:8080/ping](http://localhost:8080/ping) to ensure the backend is running.

### Prerequisites

Make sure you have the following installed on your local machine:

- [Node.js](https://nodejs.org/)
- [Angular CLI](https://angular.dev/tools/cli)
- [Go](https://go.dev/)
- [MongoDB](https://www.mongodb.com/)

## Usage

End users can directly use the app at [https://cashflow-tracker.vercel.app](https://cashflow-tracker.vercel.app)

## Directories

This repo contains two directories `client` and `server` which are basically frontend and backend of the app respectively.

## Production

The Cashflow Tracker is deployed in a production environment, ensuring accessibility to users. The frontend is hosted on [Vercel](https://vercel.com), and the backend is hosted on [Railway](https://railway.app).

### Deployment Details

- **Frontend (Client):**

  - Hosted on [Vercel](https://vercel.com)
  - Access the deployed frontend at [https://cashflow-tracker.vercel.app](https://cashflow-tracker.vercel.app)

- **Backend (Server):**

  - Hosted on [Railway](https://railway.app)
  - Dockerfile included for containerization

Feel free to explore and experience the live application!
