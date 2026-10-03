# MediVault - Full Stack

MediVault is a React + Node/Express + MySQL medication management project.

## Reminder behavior
Reminders are stored in MySQL. The frontend checks saved reminders and shows an in-app MediVault reminder popup when the date and time are reached. No Twilio, MSG91, browser notification, or external SMS service is required.

## Backend
```bash
cd backend
npm install
npm run dev
```

## Frontend
```bash
cd frontend
npm install
npm run dev
```

Create `backend/.env` using the database values for your local MySQL setup.
