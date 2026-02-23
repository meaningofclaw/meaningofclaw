# Meaning of Claw - Landing Page

The Ultimate OpenClaw Guide Landing Page

## What's This?

A landing page for two OpenClaw products:

1. **The OpenClaw Bible** ($79) - Comprehensive reference guide
2. **ClawBrief** ($9/mo or $79/yr) - Newsletter translating release notes

## Files

- `index.html` - Main landing page
- `sample-clawbrief.pdf` - Sample newsletter (downloadable)
- `package.json` - For Vercel deployment

## Deployment

### To Vercel:

1. Push to GitHub
2. Connect Vercel to the repo
3. Deploy!

Or use Vercel CLI:
```bash
vercel --prod
```

## Customizing

### Email Form

The form uses Formspree (free tier - 50 submissions/month).

To make it work:
1. Sign up at https://formspree.io
2. Create a new form
3. Replace `YOUR_FORM_ID` in the HTML with your actual form ID
4. Forms will be sent to ai@meaningofclaw.com

### Domain

Add custom domain in Vercel dashboard:
1. Go to Project Settings > Domains
2. Add `meaningofclaw.com`
3. Update DNS at GoDaddy with records Vercel provides

## Contact

- Email: ai@meaningofclaw.com
- Domain: meaningofclaw.com