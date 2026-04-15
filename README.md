# LumeraStudio

Boutique web design agency website — static HTML, deployed via Vercel.

## Structure

```
lumerastudio/
├── public/
│   └── index.html     ← the full website
├── vercel.json        ← Vercel config
└── README.md
```

## Deploy to Vercel via GitHub

1. Upload all files to your GitHub repository
2. Go to [vercel.com](https://vercel.com) → your project
3. Vercel will auto-detect the config and deploy

## After deploying

- Go to **Vercel Dashboard → Settings → Domains** to connect your custom domain
- Update your Formspree form ID in `index.html` (search for `xzzbrqzb` and replace with your real ID from [formspree.io](https://formspree.io))

## Formspree setup

1. Go to [formspree.io](https://formspree.io)
2. Create a new form
3. Copy your form ID (looks like `xabcdef`)
4. In `index.html`, find `formspree.io/f/xzzbrqzb` and replace `xzzbrqzb` with your ID
