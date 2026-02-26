# HouseNest — Deploy to Netlify

## What's included
- `index.html` — The complete single-page application
- `netlify.toml` — Netlify configuration for SPA routing

## Deploy in 3 steps

### Option A: Drag & Drop (Fastest)
1. Go to [netlify.com](https://netlify.com) and create a free account
2. Go to your dashboard and click **"Add new site → Deploy manually"**
3. Drag this entire folder onto the Netlify drop zone
4. Done — you'll get a live URL like `https://housenest-xyz123.netlify.app`

### Option B: Via GitHub (Recommended for ongoing work)
1. Push this folder to a GitHub repository
2. In Netlify: **Add new site → Import from Git → GitHub**
3. Select your repo — Netlify auto-detects settings from `netlify.toml`
4. Click Deploy

## Demo Accounts
The platform seeds demo data automatically. To test as a landlord:
- Email: `landlord@housenest.ng`
- Password: `demo1234`

Or create your own account via the Sign Up button.

## Features Working in This Demo
- ✅ User sign-up and login (stored in browser localStorage)
- ✅ Role selection: Corper, Tenant, Landlord, Student, Association, Agent
- ✅ Browse 8 pre-seeded listings across all 5 states
- ✅ Filter by category, state, property type, price
- ✅ Full listing detail pages with Google Maps embed
- ✅ Star reviews — write and submit reviews
- ✅ Save/favourite listings
- ✅ Apply to properties
- ✅ Landlord dashboard with listing management
- ✅ Add new listings with real image uploads (base64 stored locally)
- ✅ Tenant dashboard: saved, applications, reviews
- ✅ Profile editing and password change
- ✅ Responsive — works on mobile

## Notes for Production
- Replace `localStorage` with a real backend (Supabase/Firebase recommended)
- Replace base64 image storage with Cloudinary
- Add real payment processing via Paystack or Flutterwave
- Add the real Google Maps API key for better map performance
- Wire up email notifications (Mailgun/Brevo)

## States Covered
- Ondo (Akure)
- Ekiti (Ado-Ekiti)
- Oyo (Ibadan)
- Osun (Osogbo)
- Kwara (Ilorin)
