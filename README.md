# Savage Concierge

Live deployment: https://savage-concierge.vercel.app

This is the Savage Mobile Detailing MVP with:

- AI-style appointment setter
- Problem-based booking
- Smart package recommendation
- Live quote range
- Appointment POST endpoint at `/api/appointments`
- Admin command-board mockup
- Dark/red automotive brand direction

## Local run

```bash
npm install
npm run dev
```

## GitHub repo setup

```bash
git init
git add .
git commit -m "Initial Savage Concierge MVP"
gh repo create 4twentydev/savage-concierge --private --source=. --remote=origin --push
```

## Next backend work

1. Add Supabase or Neon tables for appointment requests.
2. Replace the `console.info` in `app/api/appointments/route.js` with a database insert.
3. Add UploadThing or Cloudinary photo uploads.
4. Add Resend owner/customer emails.
5. Protect the admin section.
