# 🏠 HomeFind

A free, lightweight web app that connects **property owners directly with buyers and tenants** — no brokers, no commission, no middlemen.

Built as a single-page HTML app, hosted free on GitHub Pages, and monetized through ads and affiliate links.

---

## ✨ Features

- 🔍 **Search & Filter** — by city, locality, BHK, type (Rent/Sale), and max price
- 📱 **Direct Contact** — one-tap WhatsApp and Call buttons for each listing
- 🏘️ **Owner Listings** — owners post their own properties for free
- 💸 **No Brokers** — buyers deal directly with owners
- 📱 **Mobile-First Design** — works perfectly on phones
- 🚀 **Zero Backend** — runs entirely on GitHub Pages (free hosting)
- 💰 **Monetization Ready** — built-in slots for Google AdSense + affiliate links

---

## 🚀 Live Demo

👉 **[View HomeFind Live](https://YOUR-USERNAME.github.io/homefind/)**

*(Replace `YOUR-USERNAME` with your GitHub username after deployment.)*

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| Hosting | GitHub Pages (free) |
| Data | Static JSON array inside `index.html` |
| Monetization | Google AdSense + Affiliate links |

No frameworks. No dependencies. No build step.

---

## 📂 Project Structure

---

## 🚀 How to Deploy (GitHub Pages)

1. **Fork or clone** this repository
2. Go to **Settings → Pages**
3. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
4. Click **Save**
5. Wait 1–2 minutes. Your site will be live at:
6. 
---

## ✏️ How to Customize

### Add a new property listing

Open `index.html` and find the `properties` array in the `<script>` section. Add a new object:

```javascript
{
  title: "2 BHK Apartment in Anna Nagar",
  city: "Chennai",
  locality: "Anna Nagar",
  type: "Rent",              // "Rent" or "Sale"
  price: 18000,
  bhk: 2,
  area: 950,
  image: "https://your-image-url.jpg",
  owner: "Ramesh",
  phone: "919999999999"      // country code + number, no + sign
}
<div class="ad-slot" id="ad-slot-top">...</div>
<div class="ad-slot" id="ad-slot-bottom">...</div>
