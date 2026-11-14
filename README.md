# GreenBack — AI Collective Hackathon

A React + Vite + Tailwind demo built from the Gemini-generated `App` component.

## Run locally

1. Install Node.js (version 18+).
2. Open a terminal in this folder.
3. Run `npm install`.
4. Run `npm run dev` and open the local URL shown.

## Deploy

Upload the **contents** of this folder (not the outer folder) to the GitHub repository. For live hosting, connect the repository to Vercel or Netlify, using `npm run build` and publish directory `dist`.

## Important demo limitations

- The QuickBooks, Xero, and HubSpot integrations are UI demonstrations and do not implement an OAuth connection.
- Email notifications are displayed in UI state; no backend email delivery exists.
- Grant records, scores, approval predictions, financial numbers, and verification timestamps are prefilled demonstration values, **not independently verified live results**. Do not present them as verified to users.
- The Gemini AI call uses an empty API key and falls back to a hardcoded answer. A production implementation requires a secure backend for any API keys and user data. Never place production secrets in frontend code.
- Application submission changes only local UI state; it does not submit an application to any grant agency.
- The Grants.gov fetch may be blocked by CORS and doesn't constitute a complete grant-checking integration.
