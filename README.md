# Single-Property Listing Site — Bhoomi Realty Header

This is a one-file static site for a home listing, pre-filled with Bhoomi Realty contact details.

## Quick start
1. Create a new GitHub repo (public is simplest).
2. Upload/commit **index.html** and (optionally) a **CNAME** file containing just your domain (e.g., `123maplelane.online`).
3. In **Settings → Pages**, set the *Branch* to `main` and the folder to `/ (root)`. Save.
4. Under **Custom domain**, add your domain (e.g., `123maplelane.online`) and save.
5. Turn on **Enforce HTTPS** once the certificate is issued.

## DNS (GitHub Pages)
A records (apex):
- 185.199.108.153
- 185.199.109.153
- 185.199.110.153
- 185.199.111.153
(Optionally AAAA for IPv6.)

CNAME for `www`: `YOUR-USERNAME.github.io`

## Customize
- Replace address, price, photos, map embed URL.
- If you prefer a headshot or logo, swap the image in the hero.
- Form action uses Formspree; replace with your inbox or CRM.
