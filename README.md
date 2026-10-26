# BillBahi GST Invoice

A free, no-signup GST tax invoice generator for Indian freelancers and small businesses.
One static file (`index.html`), so hosting is free.

## What it does
- Seller and buyer details, GSTIN format and check-digit validation
- Picks CGST + SGST (same state) or IGST (different state) from the place of supply
- GST slabs 0, 0.25, 3, 5, 12, 18, 28 and 40% (old and new GST 2.0 rates)
- Tax summary per slab, round-off, amount in words in the Indian system (lakh, crore)
- Logo upload, bank and UPI details, notes
- "Save my business details" and auto-incrementing invoice numbers (stored only in the browser)
- Download PDF through the browser's print dialog (A4 layout)

## Put it online (free, about 10 minutes)
1. Create a public GitHub repo, for example `billbahi`.
2. Upload `index.html` to it.
3. Settings → Pages → Deploy from branch → `main` / root. Site goes live at `https://<you>.github.io/billbahi/`.
4. Optional: buy a domain (around ₹800/year, e.g. billbahi.in) and add it under Pages → Custom domain.
5. Open `index.html`, find `CONFIG` near the top of the script and set `siteUrl` (the credit line on every invoice), `premiumUrl` and `supportUpi`.

## How it earns
| Source | When | Realistic range |
|---|---|---|
| Google AdSense in the `#adslot` box | After the site has content and some traffic (AdSense approval) | ₹50–₹150 per 1,000 visits in India |
| Premium pack (quotation, delivery challan, proforma, branded templates) on Gumroad or Razorpay Payment Pages | Once 50+ people a day use it | ₹199–₹499 one-time, 1–3% of regular users buy |
| UPI support link | Any time | Small, occasional |
| Credit line on every invoice | Built in | Free marketing: each invoice shows your site to another business |

Honest expectation: ₹0 in month one, a few hundred to a few thousand rupees a month by month 4–6 if you get search traffic. It grows only if people find it.

## Getting traffic
- Add 5–10 short guide pages that people search for: "GST invoice format for freelancers", "CGST vs IGST explained", "HSN code for graphic design services", "invoice format for unregistered dealers". Each links to the tool.
- Submit the site to Google Search Console.
- Share in r/IndiaInvestments, r/developersIndia, freelancer WhatsApp/Telegram groups, LinkedIn. Post a short "I built a free GST invoice tool" story.
- List on Product Hunt and IndieHackers.

## Next features worth building
1. Quotation / proforma / delivery challan modes (good premium pack)
2. UPI QR code on the invoice
3. Invoice history list and CSV export for GSTR-1 filing
4. Hindi and Telugu labels
