# Full Stack Open - Part 5 Project

This repository contains my solutions for Part 5

### Folder Structure

- `bloglist-backend/`: The backend server from Part 4.
- `bloglist-frontend/`: The React frontend application (Exercises 5.1 - 5.16).
- `e2e-tests-playwright/`: The end-to-end tests using Playwright (Exercises 5.17 - 5.23).

---

### How to Run Everything

**Step 1: Run the Backend**

```bash
cd bloglist-backend
npm install
npm run dev
# Make sure you have a .env file with your MONGODB_URI
```

**Step 2:Run the Frontend**

```bash
cd bloglist-frontend
npm install
npm run dev
```

**How to Run the Tests**

```bash
Component Tests (inside the frontend )
Bash
cd bloglist-frontend
npm test
```

**End-to-End Tests (Playwright)**

```bash
(Make sure the backend and frontend are running first and you should run the backend with npm run start:test)
Bash
cd e2e-tests-playwright
npm install
npm test
```
