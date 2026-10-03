# vishal_electronics_and_perfumes-OFFICIAL-WEBSITE
A real-world project for firm named "VISHAL ELECTRONICS AND PERFUMES" located in Gujarat(KUTCH) ,City: Gandhidham

# Vishal Electronics and Perfumes: official website

Static site (no server, no database). Files: `index.html`, `config.js`, `images/`.

## Change details, links, offers, products
Open **config.js**. Everything is there: address, phone, hours, all links (WhatsApp, Google Business, Google Review, Maps, Justdial, IndiaMART), the 10% offer text and terms, the birthday text, the About text, and the product list.
- **Add a product:** copy one `{ ... }` line in `PRODUCTS`, change name/desc/price/availability, and put the photo in `images/` (use a `.jpg` under ~200 KB) and set `image: "images/yourfile.jpg"`. Leave `price: ""` to hide the price.
- **Google review link:** in Google Business Profile, choose "Get more reviews", copy the link, paste into `GOOGLE_REVIEW_URL`. Until then it uses your Google Business link.
- **Maps link:** currently a search link built from your address. Replace with your exact Maps share link if you like.
- **WhatsApp:** uses the number from your visiting card (wa.me/919825314179). Replace if your WhatsApp Business link is different.
- **Still to fill:** `BUSINESS_HOURS`, `OFFER_TERMS`, `SITE_URL` (after publishing).

## Feedback form
Without a backend the form opens WhatsApp with the feedback prefilled; it does not store anything. To receive feedback by email for free: create a form at formspree.io (or web3forms.com), copy its URL, paste into `FEEDBACK_FORM_ENDPOINT`.

## Publish for free (Netlify, easiest)
1. Go to app.netlify.com/drop and sign up free.
2. Drag the whole site folder onto the page. You get a live link instantly.
Alternatives: GitHub Pages (upload files to a repo, Settings > Pages) or Cloudflare Pages (connect repo, no build command).

## Notes
- Product photos are the manufacturers' brand images. Replace with your own shop photos when possible.
- Add a `robots.txt` and `sitemap.xml` with your final address after publishing.
