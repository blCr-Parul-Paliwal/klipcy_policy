# Klipcy Privacy Policy

Static privacy-policy page for the Klipcy Shopify app, deployed on [Vercel](https://vercel.com).

## Structure

```
.
├── index.html      # the privacy policy page (served at /)
├── vercel.json     # Vercel static-site config (clean URLs + security headers)
└── .gitignore
```

## Deployment

This is a zero-build static site. Vercel serves `index.html` from the repository
root automatically — no framework, build command, or output directory needed.

1. Import this repository into Vercel.
2. Leave **Framework Preset** as **Other** and all build settings empty.
3. Deploy. The policy is served at the project root URL.
