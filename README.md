# Tulip Holding Website

Een moderne, statische website voor Tulip Holding, gebouwd met Jekyll en gehost op GitHub Pages.

## 🚀 Features

- **Statische website** - Snel, veilig en betrouwbaar
- **Responsive design** - Werkt perfect op alle apparaten
- **SEO geoptimaliseerd** - Gebouwd voor zoekmachines
- **Gratis hosting** - Via GitHub Pages
- **Eenvoudig onderhoud** - Markdown content management

## 📁 Project Structuur

```
├── _config.yml          # Jekyll configuratie
├── _layouts/            # HTML templates
├── _includes/           # Herbruikbare componenten
├── _pages/              # Statische pagina's
├── _projects/           # Project portfolio
├── _sass/               # SCSS stylesheets
├── assets/              # Afbeeldingen, CSS, JS
├── index.html           # Homepage
└── Gemfile              # Ruby dependencies
```

## 🛠️ Lokale Development

### Vereisten
- Ruby 2.7 of hoger
- Bundler gem

### Installatie
```bash
# Clone de repository
git clone <repository-url>
cd tulip-holding-website

# Installeer dependencies
bundle install

# Start de development server
bundle exec jekyll serve
```

De website is dan beschikbaar op `http://localhost:4000`

## 📝 Content Toevoegen

### Nieuwe Pagina
1. Maak een nieuw `.md` bestand in `_pages/`
2. Voeg de pagina toe aan `header_pages` in `_config.yml`
3. Gebruik Markdown syntax voor content

### Nieuw Project
1. Maak een nieuw `.md` bestand in `_projects/`
2. Gebruik de volgende front matter:
```yaml
---
title: "Project Naam"
description: "Korte beschrijving"
image: "/assets/images/project-image.jpg"
---
```

## 🎨 Styling Aanpassen

- **Hoofdstyles**: `assets/css/style.scss`
- **Variabelen**: Aan het begin van het SCSS bestand
- **Responsive**: Media queries onderaan het bestand

## 🚀 Deployment

De website wordt automatisch gehost op GitHub Pages wanneer je code pusht naar de `main` branch.

### GitHub Pages Setup
1. Ga naar repository Settings
2. Scroll naar "Pages" sectie
3. Selecteer "Deploy from a branch"
4. Kies "main" branch en "/ (root)" folder

## 📞 Contact

Voor vragen over de website of content updates, neem contact op via:
- Email: info@tulipholding.cz
- Website: https://tulipholding.cz

## 📄 Licentie

Dit project is eigendom van Tulip Holding.

