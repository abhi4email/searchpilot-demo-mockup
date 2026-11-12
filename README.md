# SearchPilot interactive demo

A responsive, static single-page application prototype for the SearchPilot AI Search Growth Platform. It includes all 16 product flows, client-side navigation, interactive filters, tabs, forms, simulated workflow actions and sample charts.

## Important demo limitations

- `example.com` is a reserved example domain, not a commercial business.
- All business insights, competitors, provider visibility, questions, mentions, citations, traffic, leads, scores, invoices, prices and history are synthetic illustrative data.
- No AI provider, analytics, CMS, billing, email or publishing integrations are connected.
- Actions are local UI demonstrations only. Nothing is sent to a backend or persisted after refresh.

## Run locally

No build step or dependencies are required. Open `index.html` in a browser, or run a local static server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy to Vercel

### Option A — GitHub (recommended)
1. Create a new GitHub repository, for example `searchpilot-demo`.
2. Upload the contents of this folder to the repository root (`index.html`, `styles.css`, `app.js`, `README.md`).
3. In Vercel, choose **Add New → Project**, import the repository.
4. Select **Other** as the framework preset. Leave Build Command and Output Directory empty; the app is static and `index.html` is at the root.
5. Click **Deploy**. Vercel will provide a public `*.vercel.app` URL.

### Option B — Vercel CLI
1. Install Node.js and the Vercel CLI: `npm i -g vercel`
2. In this folder run: `vercel`
3. Follow the prompts, choosing the default static deployment settings.
4. Run `vercel --prod` when ready to publish the production URL.

## Files
- `index.html` — application shell
- `styles.css` — responsive design system
- `app.js` — page content, navigation and demo interactions
