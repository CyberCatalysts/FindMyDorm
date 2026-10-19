# FindMyDorm — GitHub Pages package

## Publish on GitHub Pages
1. Create or open your GitHub repository.
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. Wait for the published URL shown in Settings → Pages.

## What's included
- FindMyDorm accommodation search prototype and existing pages.
- Math & Java page with 1–5 input validation, repeat-order loop, daily/monthly/annual conversions, summary statistics, and a Java console example.
- Existing revenue/expense/loss charts embedded in the Revenue page.
- Browser calculator and fallback accommodation assistant.

## Important hosting notes
- GitHub Pages is static hosting. The built-in assistant uses a local fallback unless `BACKEND_URL` is configured. Do not put an AI provider API key in this file. For genuine AI responses, deploy the secure backend separately and configure its public HTTPS endpoint.
- Account, message and prototype data are stored in the visitor's browser; this is a demonstration, not production-grade authentication or payment processing. The checkout is a demo and does not take payments.
- Listing verification claims and example financial figures should be checked and updated before a public launch.
