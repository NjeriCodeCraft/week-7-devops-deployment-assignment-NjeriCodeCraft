# Real-Time Chat App

## Project Overview
This is a real-time chat application built with React (client) and Node.js/Express/Socket.io (server). It supports public and private messaging, file/image sharing, reactions, notifications, and more. The app demonstrates bidirectional communication and real-time features suitable for modern chat platforms.

---

## Setup Instructions

1. Clone the repository and install dependencies for both `server` and `client`.
2. Copy `.env.example` to `.env` in both folders and fill in your environment variables.
3. Run the backend and frontend locally for development.

---

## Deployment Summary

- **Backend deployed on Render:**
  - [Live Backend API](https://week-7-devops-deployment-assignment-sibf.onrender.com)
- **Frontend deployed on Netlify:**
  - [Live Frontend App](<your-frontend-netlify-url>)

---

## CI/CD Pipeline
- Automated with GitHub Actions (`.github/workflows/ci.yml`).
- Runs build and test steps for both backend and frontend on every push or pull request.
- ![CI/CD Pipeline Screenshot](./ci-cd-screenshot.png)

---

## Monitoring & Maintenance
- **Monitoring:** [Describe your monitoring tools, e.g., UptimeRobot, Sentry, etc.]
- **Health check endpoint:** `/health` (if implemented)
- **Performance tracking:** [Describe any tools or methods used]
- **Maintenance plan:** [Describe your plan for updates, patches, and backups]

---

## Submission Notes
- Both client and server code are included in this repository.
- All environment variable templates are provided as `.env.example` files.
- Screenshots and documentation are included as required.

---

## Credits
- Built with [React](https://reactjs.org/), [Express](https://expressjs.com/), [Socket.io](https://socket.io/), [Render](https://render.com/), and [Netlify](https://www.netlify.com/). 