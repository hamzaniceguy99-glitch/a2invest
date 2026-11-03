# A2 Invest — a2 invest srl

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `a2invest.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/a2invest.mjs`).
> To change the content, edit that file and run `node build.mjs a2invest` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@a2invest.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($€[AMOUNT] / $€[AMOUNT] / $€[AMOUNT]) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
We are A2 Invest, based in Deinze in East Flanders since 2010, working in passenger water transport, the hire of leisure and sports equipment, and business advisory work. On the water there is one distinction that decides everything and that almost no customer is told about, which is whether you are being carried or whether you are in charge. If you are carried as a passenger, the vessel has to be certified for carrying passengers and the person at the helm has to hold the professional qualification for it, and a pleasure licence does not cover any of that. If you hire a boat without a crew, you become the person in charge, which means you need the licence yourself and the insurance position changes with it. There is also a number worth knowing, because it is a legal threshold rather than a question of seating: carry more than twelve passengers at sea and the vessel is a passenger ship in law, under an entirely different certification regime. We tell you which of these you are buying before you pay for it, and the skipper's decision not to sail is always refunded in full. Site: a2invest.shop
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
