# Divi Express LLC — Corporate Website

Corporate website for **Divi Express LLC**, a company specialized in the sale, importation, and commercialization of high-quality vehicles. Content in English, with a formal tone suitable for banking analysis and compliance.

## About the Project

- **Single-page website** with sections: Company Overview, Our Services, End-to-End Process, Transparency and Compliance, Mission and Vision, About Us, How We Operate, Core Values, and Our Commitment.
- **Objective language**, no financial claims; explicit disclaimer that the company does not provide financing, credit services, or act as a lender.
- **Legal identification** in the footer (LLC registered in the United States) and **JSON-LD schema** (`LimitedLiabilityCompany`) for classification and SEO.

## Repository Structure

```
souzaglobal/
├── index.html      # Main page
├── styles.css      # Global styles, responsiveness, theme
├── main.js         # Mobile menu, back-to-top button, scroll reveal
├── assets/
│   ├── logo.jpeg       # Company logo
│   └── hero-index.png  # Hero background image
└── README.md
```

## Technologies

- **HTML5** — Semantic, accessible (ARIA, skip link)
- **CSS3** — CSS variables, responsive layout, `prefers-reduced-motion` support
- **JavaScript** — Mobile menu, back-to-top button, scroll reveal animations

## Running Locally

No build process required. Simply open `index.html` in a browser or use a local server:

```bash
# Option 1: Python 3
python3 -m http.server 8000

# Option 2: Node.js (npx)
npx serve .

# Option 3: PHP
php -S localhost:8000
```

Access `http://localhost:8000` (or the indicated port).

## SEO and Metadata

- Meta description, Open Graph, and Twitter Cards configured
- Canonical URL defined
- JSON-LD with `@type`: `LimitedLiabilityCompany`, `areaServed`, `knowsAbout`

## Accessibility

- "Skip to main content" link
- ARIA attributes on menu and buttons
- Animations respect `prefers-reduced-motion: reduce`

## License and Rights

© Divi Express LLC. All rights reserved.
