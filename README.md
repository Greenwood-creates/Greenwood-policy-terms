# Greenwood-policy-terms

Static GitHub Pages site hosting policy documents for multiple apps.

## Structure

```
/
  index.html              → Root landing page listing all apps
  assets/
    style.css             → Shared stylesheet for all pages
  quiz-wiz/
    index.html            → Quiz-Wiz landing with links to policies
    privacy-policy.html   → Privacy Policy
    terms-of-service.html → Terms of Service
    support.html          → Support / FAQ
  vibeseek/
    index.html            → VibeSeek landing with links to policies
    privacy-policy.html   → Privacy Policy
    terms-of-service.html → Terms of Service
    support.html          → Support / FAQ
```

## Publishing

Set the repository Pages source to deploy from the branch and folder containing these files (for example, `main` / root).

## Adding a New App

1. Create a new subdirectory (e.g. `/my-app/`)
2. Copy the pages from an existing app's folder as templates
3. Customize the app name, support email, features, and monetization details
4. Add a link card on the root `index.html`
