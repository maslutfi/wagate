# WAGate Landing Page Documentation

## Overview
This is the official landing page for **WAGate**, a self-hosted WhatsApp Gateway bridge designed for developers and automation platforms like n8n.

## Deployment
The page is deployed using **GitHub Pages**.

### Deployment Steps:
1. Ensure `index.html`, `style.css`, `app.js`, and the `assets/` folder are in the root directory.
2. Push the changes to the `main` branch of the GitHub repository.
3. In GitHub Settings -> Pages, select the `main` branch as the source.

## SEO Configuration
- **Meta Tags**: Optimized for WhatsApp API, Gateway, and n8n keywords.
- **Open Graph**: Configured for rich sharing previews on Facebook and LinkedIn.
- **Twitter Cards**: Configured for Twitter sharing.
- **Schema.org**: Includes `SoftwareApplication` JSON-LD for better search engine indexing.
- **Sitemap & Robots**: Verified for a standard GitHub Pages subdirectory (`/wagate/`).
- **Docs Link**: Updated to point to the official Docker Hub repository for accurate documentation.

## Project Structure
- `index.html`: Main structure with SEO and Schema.
- `style.css`: Modern, responsive styling using CSS variables.
- `app.js`: Lightweight JavaScript for interactions.
- `assets/`: Contains images and icons.
- `sitemap.xml`: XML sitemap for search engines.
- `robots.txt`: Search engine crawling instructions.
