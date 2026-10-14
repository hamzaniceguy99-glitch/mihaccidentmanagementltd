# MIH Accident Management — mih accident management ltd

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `mihaccidentmanagementltd.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/mihaccidentmanagementltd.mjs`).
> To change the content, edit that file and run `node build.mjs mihaccidentmanagementltd` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@mihaccidentmanagementltd.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($No cost if recovered / $Per claim / $Referral) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
MIH Accident Management Ltd, a private limited company registered in England and Wales (company number 09869121), provides accident management services to drivers involved in non-fault road traffic accidents: notifying and handling the claim with the insurers involved, arranging vehicle recovery, storage and inspection, managing repairs through approved repairers, and arranging a replacement vehicle where the driver is entitled to one. Before any replacement vehicle is supplied the driver is told in writing that they remain personally liable for the hire charges if the claim is unsuccessful or the charges are not recovered in full. The company is not an insurer, an insurance broker or a firm of solicitors. Site: mihaccidentmanagementltd.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
