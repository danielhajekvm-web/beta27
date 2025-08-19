# Business Manager (Import App)

Vite + React + Tailwind + Firebase + Recharts.

## Local development

1. Copy `.env.example` to `.env` and fill your values:
   - `VITE_APP_ID` – your app id used in Firestore paths.
   - `VITE_FIREBASE_CONFIG` – full Firebase web config JSON on one line.
   - `VITE_INITIAL_AUTH_TOKEN` – optional; if empty, the app uses anonymous auth.

2. Install and run:
```bash
npm install
npm run dev
```

## Deploy (e.g., Vercel)

Set the same variables in project **Environment Variables**:
- `VITE_APP_ID`
- `VITE_FIREBASE_CONFIG` (JSON on one line)
- `VITE_INITIAL_AUTH_TOKEN` (optional)

> Never commit real secrets.
