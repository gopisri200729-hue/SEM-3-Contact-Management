# Contact Management System

A full-stack contact manager built with React + Vite, Node.js + Express and SQLite.

## Features
- 7 initial contacts
- Add unlimited contacts (400+ supported)
- Permanent SQLite storage
- Search contacts
- Favorites
- Edit and delete
- Contact details
- Call / SMS / WhatsApp / Email / LinkedIn / GitHub quick actions when data exists
- Photo URL or image upload
- Responsive modern UI
- Saved contacts remain after refresh, server restart and reopening the project

## Run
Open Command Prompt in this folder:

```cmd
npm run install:all
npm run dev
```

Then open the Vite URL shown in the terminal (usually http://localhost:5173).

The API runs on http://localhost:5000.

## Important
The two WhatsApp `blob:` image references supplied for some contacts are temporary browser URLs, so they are intentionally not stored as permanent photo URLs. Those contacts use an initials fallback until an actual image file is uploaded.
