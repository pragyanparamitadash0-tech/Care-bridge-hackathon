# CareBridge

A React + Vite hackathon prototype connecting patients and clinics through appointment-request demos, a wellness area, an informational chatbot fallback, and an SOS information screen.

## Run locally
1. Install Node.js.
2. Run `npm install`.
3. Run `npm run dev`.

## Deploy
Import this repository into Vercel and use the default Vite build settings:
- Build command: `npm run build`
- Output directory: `dist`

## Prototype limitations
- Login is simulated; any non-empty email/password can start a demo session.
- Request and patient data are stored in browser local storage and are not shared securely across users or devices.
- The chatbot currently provides local demo responses; it does not call Gemini. Add a server-side API endpoint and store any API key in server-side environment variables before enabling live AI.
- The SOS screen is only a visual aid. It does not notify contacts or dispatch services.
- Do not enter real patient or medical information. This is not a production healthcare system.