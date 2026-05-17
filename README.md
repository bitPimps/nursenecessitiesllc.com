# Nurse Necessities LLC — Website

Static website for [Nurse Necessities LLC](https://nursenecessitiesllc.com), a retail boutique offering fashionable scrubs, apparel, and accessories for nurses. Hosted via GitHub Pages.

## Stack

- Plain HTML/CSS/JavaScript — no build step, no framework
- Single-page layout with anchor-based navigation
- Deployed automatically from `main` via GitHub Pages (CNAME: `nursenecessitiesllc.com`)

## Structure

```
index.html          # Entire site — hero, about, products, gallery, contact
images/
  gallery/          # img001.jpg – img018.jpg (product/style showcase)
  logos/            # nurse-necessities.jpg, lyriq.jpg
  history.jpg       # Owner photo
  nurse-necessities.jpg
  products.jpg
robots.txt
CNAME
```

## Schema.org Structured Data

Three JSON-LD blocks are embedded in `<head>` of `index.html`:

| Block | Type | Purpose |
|-------|------|---------|
| 1 | `ClothingStore` | Local business rich results — address, hours, phone, founder |
| 2 | `WebSite` | Canonical web identity, Sitelinks Searchbox eligibility |
| 3 | `Product` | "Listen with Lyriq's" stethoscope covers — brand, in-store availability |

Validate at [search.google.com/test/rich-results](https://search.google.com/test/rich-results) or [validator.schema.org](https://validator.schema.org/).

## Business Info

| Field | Value |
|-------|-------|
| Address | 4138 Dr Martin Luther King, St. Louis, MO 63113 |
| Phone | (314) 669-9551 |
| Cell | (314) 312-0178 |
| Email | nursenecessitiesllc@gmail.com |
| Hours | Mon–Fri 10:00 AM – 4:30 PM · Sat 12:00 PM – 5:00 PM · Sun by appointment |
| Founded | 2018 |
| Owner | Chimere Marshall |

## Making Changes

Edit `index.html` directly — CSS and JS are inlined. Images go in `images/` or `images/gallery/`. Push to `main` to deploy.
