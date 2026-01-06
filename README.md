# Secret Santa Matcher

## Overview
**Problem:** Manually assigning Secret Santa matches is time-consuming, error-prone, and risks breaking anonymity in larger groups.

**Solution:** Secret Santa Matcher is a full-stack web application that allows users to create groups for Secret Santa events and automatically assigns anonymous matches, removing manual coordination entirely.

---

## Features
- User authentication (Sign Up / Log In)
- User profiles and group creation
- Anonymous Secret Santa assignment logic
- Event dashboard for managing exchanges
- Secure backend with PostgreSQL persistence

---

## Tech Stack
**Frontend**
- React
- React Router (v6)
- TypeScript
- Webpack

**Backend**
- Node.js
- Express
- PostgreSQL

---

## Implementation Details
- Built dynamic routing and navigation using `react-router-dom`
- Managed component state and lifecycle with `useState` and `useEffect`
- Implemented programmatic navigation with `useNavigate`
- Designed relational schemas in PostgreSQL to ensure data integrity
- Structured frontend and backend as separate services for scalability

---

## Getting Started

### Prerequisites
- Node.js
- npm
- PostgreSQL

### Installation
```bash
git clone https://github.com/Tpolite4/secret-santa-matcher
cd secret-santa-matcher
npm install

### Installation
