# README — DokimionTech.Cloud

## 🚀 Overview
DokimionTech.Cloud is part of the **Digital Doki / Dokimion Solutions** ecosystem — offering rotating cloud-based access to premium creative and productivity tools such as Adobe Creative Cloud and Microsoft 365 through an AI-automated platform.

The system provides short-term license rentals via secured virtual environments (Remote Desktop Services or browser-based containers) to allow verified users to access powerful software without the traditional cost barrier.

---

## 🧱 Project Structure
```
/ (root)
├── index.html              → Microsoft 365 landing page
├── adobe.html              → Adobe Creative Cloud landing page
├── assets/                 → Images, logos, and CSS files
├── CNAME                   → Custom domain: dokimiontech.cloud
├── README.md               → This file
└── security.txt            → Security contact and disclosure policy
```

---

## ⚙️ Deployment (Free Hosting)
1. Create a GitHub repo named **dokimiontech-cloud**.
2. Push your HTML/CSS files.
3. Enable **GitHub Pages** under Settings → Pages.
4. Set your custom domain to **dokimiontech.cloud**.
5. Point Porkbun DNS to GitHub’s IPs:
   - 185.199.108.153
   - 185.199.109.153
   - 185.199.110.153
   - 185.199.111.153

Once propagation completes, enforce HTTPS and your live site will load from `https://dokimiontech.cloud`.

---

## 🤖 Automation Stack
- **Zapier** / **Make (Integromat)** — automates license provisioning, payment confirmation, and access expiry.
- **Stripe / Gumroad API** — manages payments and subscriptions.
- **Google Sheets or Notion** — tracks active users, seats, and rotations.
- **GitHub Actions** — automatically deploys any site updates.

---

## 💡 Monetization Model
- Offer one-month access tiers (e.g., Adobe or Microsoft suites).
- Base licenses on volume pricing (Teams or Enterprise agreements).
- Margin targets: 40–60% net after infrastructure costs.
- Upsells: Cloud storage, premium AI tools, or enterprise bundles.

---

## 🛡️ Security & Compliance
All users are bound by the original vendor license terms (Adobe, Microsoft). DokimionTech.Cloud acts only as a **managed access facilitator**.

**Key policies:**
- Each account operates in its own isolated VM container.
- No persistent local storage between sessions.
- All logs and credentials are encrypted in transit and at rest.
- Incident response handled through `security@dokimiontech.cloud`.

For full disclosure and vulnerability reporting, see `/.well-known/security.txt`.

---

## 📄 License
All web content, brand assets, and automation scripts © Digital Doki / Dokimion Solutions, 2025.
Open-source libraries within this repo are governed by their respective licenses (MIT, Apache-2.0, BSD-3-Clause, etc.).
