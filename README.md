[readme_md.md](https://github.com/user-attachments/files/33980522/readme_md.md)
# Matthews Operations Labs: Supply-Chain Reality Checker

> **Point-of-Sale Consumer Intelligence & Corporate Accountability Engine**  
> Direct, verified, client-side auditing designed for mobile devices in store aisles and shopping centers.

---

## 🎯 Project Overview

The **Supply-Chain Reality Checker** is an open-source, mobile-first web tool operated by **Matthews Operations Labs**. 

Modern global retail relies heavily on supply-chain opacity. Consumers rarely see that deep retail discounts are routinely subsidized by forced labor, violence, hazardous conditions, and sub-living wages. 

This tool serves two direct goals:
1. **Incentivize Ethical Commerce (Positive-First Architecture):** Whenever a shopper searches an everyday item (e.g., bananas, basketball shoes, chocolate, seafood), the tool immediately highlights verified ethical brands and certifications first. This rewards businesses adhering to transparent, fair-wage practices.
2. **Unfiltered Accountability:** Following the ethical alternatives, the tool presents unvarnished factual documentation of labor extraction metrics, corporate atrocities, and specific conglomerate brands to avoid.

---

## 🏛️ The Legislative Link: The Matthew 25 Act

While voluntary consumer choices create vital economic demand for ethical brands, consumer boycotts alone cannot solve systemic trade loopholes. 

The site features a permanent policy anchor for **The Matthew 25 Act**, an upcoming federal legislative framework designed to:
- Establish enforceable sliding-scale social tariffs on imported goods produced below international labor baselines.
- Close enforcement loopholes in Section 307 of the Tariff Act of 1930.
- Mandate strict supply-chain transparency and liability standards before foreign products can clear U.S. ports of entry.

---

## 🛠️ Architecture & Features

- **Single-File Deployment (`index.html`):** Zero external build tools, bundlers, or package managers required. All markup, responsive CSS, and JavaScript logic reside in one performant file.
- **Embedded Client-Side Database:** The dossier catalog runs directly in the user's browser memory. There is zero network latency, making it instantly responsive even on weak cellular connections inside grocery stores or malls.
- **Instant Search & Quick-Select Tags:** Real-time keyword filtering across product names, categories, alternative brands, and corporate offenders.
- **Information Hierarchy:**
  1. `[✓] Vetted Ethical Alternatives (The Buy List)`
  2. `[$] Documented Extraction Metric`
  3. `[!] Documented Atrocities & Systemic Violations`
  4. `[✕] Major Offending Brands & Supply Lines`

---

## 📂 Repository Structure

```text
├── index.html     # Complete single-page application (UI, styles, and embedded database)
└── README.md      # Project documentation, methodology, and deployment guide
```

---

## 🚀 Quick Start & Deployment

### 1. Run Locally
Because this project uses vanilla web standards, you can preview it instantly:
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
   ```
2. Open `index.html` directly in any web browser:
   - Double-click the file in your file explorer, or
   - Run a quick local server:
     ```bash
     python3 -m http.server 8000
     ```
   - Open `http://localhost:8000` in your mobile or desktop browser.

### 2. Deploy to GitHub Pages
1. Push `index.html` to your repository's default branch (`main`).
2. Go to your GitHub repository settings: **Settings $\rightarrow$ Pages**.
3. Under **Build and deployment**:
   - **Source:** Deploy from a branch
   - **Branch:** `main` / `root`
4. Click **Save**. Your site will be live within seconds at:
   `https://<your-username>.github.io/<repo-name>/`

---

## 🔍 Data Sourcing & Methodology

All dossiers in the catalog are compiled from public records and verified non-governmental reporting, including:
- **U.S. Department of Labor (ILAB):** *List of Goods Produced by Child Labor or Forced Labor*
- **International Labour Organization (ILO):** Sectoral labor standards and conventions
- **U.S. Federal Court Filings:** Corporate guilty pleas and civil litigation settlements
- **Special Rapporteur Reports:** United Nations Human Rights Council documentation
- **Independent On-the-Ground Investigations:** Coalition of Immokalee Workers (CIW), international investigative journalism consortia, and verified fair-trade certifiers.

---

## 🤝 Contributing

We welcome community contributions to expand the product index. To submit additions or corrections:
1. Fork the repository.
2. Locate the `catalog` array in `index.html`.
3. Add or update a product dossier using the following schema:
   ```javascript
   {
     id: "unique-slug",
     title: "Product Title",
     category: "Industry / Department",
     keywords: ["tag1", "tag2", "brand"],
     ethical_alternatives: [
       { name: "Brand Name", note: "Specific certification or ethical justification" }
     ],
     extraction_metric: "Audited worker wage share vs retail price",
     atrocities: "Verified factual summary of labor abuses or supply-chain violence",
     avoid: [
       "Brand A (Documented infraction)",
       "Brand B (Documented infraction)"
     ]
   }
   ```
4. Open a Pull Request citing primary-source documentation for all claims.

---

## ⚖️ License & Attribution

Maintained by **Matthews Operations Labs**. Distributed under the MIT License.
