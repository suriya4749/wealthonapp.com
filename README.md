# wealthonapp.com

The one-page website for WealthOn and its privacy policy. Plain HTML, no build step.

- `index.html`: the page (hero, features, privacy questions, Free vs Pro, footer).
- `privacy.html`: the privacy policy (same text as `store/privacy-policy.html` and the app). Use `https://wealthonapp.com/privacy.html` as the privacy policy link in Play Console.
- `img/`: app screenshots (US dollars, dark theme, sample person "Alex"): safe, due, afford, debtfree, yearly, firstlook, trust; the icon and the social preview image. The hero and feature words switch "loans" → "EMIs" for visitors in India (`data-t`).

When the app is live on Google Play, replace the "Coming soon on Google Play" button in `index.html` with the official "Get it on Google Play" badge linking to the store page.
When the privacy policy changes, update `store/privacy-policy.html`, `src/lib/privacy.ts` and `privacy.html` together.
