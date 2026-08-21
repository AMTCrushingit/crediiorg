# Credii Foundation website

Production-ready Phase 1 public website for Credii Foundation.

## Stack

- Next.js 15
- React 19
- TypeScript
- Plain CSS, with no CSS framework dependency

## Run locally

```bash
npm install
npm run dev
```

Open http://localhost:3000.

## Build

```bash
npm run build
npm start
```

## Deploy to Vercel

1. Create a new GitHub repository.
2. Add this project and push the main branch.
3. Import the repository into Vercel.
4. Use the default Next.js build settings.
5. Add crediifoundation.org in the Vercel project Domains settings.
6. Follow the DNS records shown by Vercel at the domain registrar.

## Before public launch

- Replace the placeholder contact details in `app/contact/page.tsx`.
- Point the Launch platform links to the future application URL.
- Add approved governance information, privacy policy and terms.
- Add verified impact figures only after reportable program results exist.
- Add social links when official accounts are confirmed.

## Brand assets

The supplied Credii logo is stored at `public/brand/credii-logo.png`.
