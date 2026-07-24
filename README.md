# Tidely — Waitlist Landing Page

> **Tidely** is a working placeholder name for a trust-based, fixed-price residential
> cleaning marketplace for Waterloo Region. This first piece is a **landing page** whose
> only job is to test real interest and collect a **waitlist** of customers and cleaners
> before we build anything heavier — exactly the "manual-first" launch the business plan
> recommends.

This is **Version 1**. It has no login, no payments, and no database — on purpose. It is
the cheapest, fastest way to answer the most important question: *do people actually want
this, at these prices, in this area?*

---

## 📁 What's in here

| File | What it is |
|------|------------|
| `index.html` | The entire landing page — one self-contained file. Open it in any browser to see it. |
| `netlify.toml` | A tiny settings file that makes putting the site online effortless. |
| `README.md` | This guide. |

That's it. One page, no complicated setup.

---

## 👀 How to see the page right now

Two easy ways:

1. **The clickable preview** I shared in our chat — click it to explore the whole page.
2. **Open the file:** double-click `index.html` and it opens in your web browser. Everything
   works locally (the waitlist form will show its "thank you" message, but signups are only
   *recorded* once the site is online — see below).

---

## 🌐 How to put it online (so real people can visit)

The easiest path costs **$0** and takes about 5 minutes. You don't need to touch any code.

### Option A — Netlify drag-and-drop (recommended, no technical steps)

1. Go to **[netlify.com](https://www.netlify.com)** and create a free account.
2. Click **"Add new site" → "Deploy manually."**
3. Drag the whole project folder (the one containing `index.html`) onto the page.
4. Done — Netlify gives you a live web address instantly (like `tidely-abc123.netlify.app`).
5. You can later connect your own domain name (e.g. `tidely.ca`) in Netlify's settings.

### Option B — Connect to GitHub (auto-updates when we make changes)

If you'd like the site to update automatically every time we improve it, connect this
GitHub repository to Netlify (**"Add new site" → "Import from Git"**). Every change we push
goes live on its own. I can walk you through this whenever you're ready.

---

## 📥 Where do the waitlist signups go?

Once the site is live **on Netlify**, form signups are captured automatically — **no code,
no database to manage.**

- In your Netlify dashboard, open **Forms**. You'll see two lists:
  - **customer-waitlist** — people who want their home cleaned
  - **provider-waitlist** — cleaners who want to work with us
- Turn on **email notifications** (Netlify → Site settings → Forms → Notifications) so a new
  signup lands in your inbox the moment it happens.
- You can export any list to a spreadsheet with one click.

> **Nothing is lost before launch:** every submission is also saved in the visitor's own
> browser as a backup, and once you're on Netlify it's all captured centrally.

---

## ✏️ How to change the common things

You don't need to know how to code to update text and prices — just tell me what to change
and I'll do it. But if you ever want to peek, here's where things live in `index.html`:

| You want to change… | Look for… |
|---------------------|-----------|
| The **brand name** ("Tidely") | Search for `Tidely` — it appears in the logo, headline area, and footer |
| The **prices / tiers** | The section marked `<!-- PRICING -->` |
| **What's included** in a clean | The section marked `<!-- INCLUDED -->` |
| The **contact email** | Search for `hello@example.com` (currently a placeholder) |
| The **colours** | Near the very top, the block that starts with `--primary:` |

**Before you launch, update the placeholder email** (`hello@example.com`) to a real address.

---

## 🎨 About the placeholder brand

"Tidely," the logo, and the colours are a clean, professional **placeholder** so nothing is
blocked on naming. When you decide on a real name and brand, renaming takes minutes.

---

## 🧭 What comes next (when you're ready)

This landing page is step one. Based on what your business plan lays out, the natural next
pieces — each only worth building once this page proves interest — are:

1. **The 4-step booking flow** (home details → add-ons → fixed price → pick a time).
2. **A simple admin dashboard** to see and manage bookings (your digital "spreadsheet").
3. **Provider onboarding & vetting** tools.
4. **Online card payments** (Stripe), recurring plans, and the $20 referral credit.

We'll build them one at a time, and only after the evidence says "go." That's your plan's
own philosophy — earn the right to grow.

---

*Questions about any of this? Just ask in our chat — no question is too basic.*
