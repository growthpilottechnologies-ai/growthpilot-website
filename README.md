# GrowthPilot Technologies — Next.js website

## Included
- Responsive, mobile-friendly corporate website
- GrowthPilot navy/gold branding and supplied logo
- Home, About, Pricing, Contact and Privacy Policy
- Individual SEO-friendly pages for all 18 listed services
- Contact form with server route
- Email notification support through Resend
- Sitemap and robots.txt
- Social links, phone, email, WhatsApp and Skype
- Unsplash service/hero imagery

## Run locally
1. Install Node.js 18.18+.
2. Run `npm install`
3. Run `npm run dev`
4. Open http://localhost:3000

## Deploy to Vercel
Import this folder/repository into Vercel. The included `package.json` is ready for a Next.js deployment.

## Contact form notifications
For actual email notifications, create a Resend account/API key and add these Vercel Environment Variables:
- `RESEND_API_KEY`
- `NOTIFY_EMAIL` (optional; defaults to growthpilottechnologies@gmail.com)

The form is intentionally configured so it can be deployed before the email provider is configured. Once the key is added, enquiries are emailed to the notification address.

## Before launch
- Replace the temporary Vercel URL in `app/layout.tsx`, `app/sitemap.ts` and `app/robots.ts` with your final custom domain.
- Add your final favicon/OG image if desired.
- Review pricing and service wording before publishing.
- If you use the supplied Unsplash images commercially, verify each image's current license/usage requirements.
