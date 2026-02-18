# Nexus CRM

A modern CRM frontend prototype built with React + Vite.

## Quick Start (Local Development)

```bash
npm install
npm run dev
```

## Deploy to Vercel (Recommended — Free)

### Option A: Via GitHub (Easiest)
1. Push this folder to a new GitHub repo
2. Go to [vercel.com](https://vercel.com) → Sign up / Log in
3. Click **"Add New Project"** → Import your GitHub repo
4. Vercel auto-detects Vite — just click **Deploy**
5. Done! Your site is live at `your-project.vercel.app`

### Option B: Via Vercel CLI
```bash
npm install -g vercel
vercel
```

## Connect Your Custom Domain

1. In your Vercel dashboard, go to your project → **Settings** → **Domains**
2. Type your domain (e.g., `yourdomain.com`) and click **Add**
3. Vercel will show you DNS records to add at your domain registrar:
   - Usually an **A record** pointing to `76.76.21.21`
   - Or a **CNAME record** pointing to `cname.vercel-dns.com`
4. Add those records where you bought your domain (GoDaddy, Namecheap, etc.)
5. Wait a few minutes for DNS propagation — Vercel auto-provisions SSL/HTTPS

That's it! Your CRM will be live at your custom domain.

## Tech Stack
- React 18
- Vite 5
- No external UI libraries — pure custom CSS-in-JS
