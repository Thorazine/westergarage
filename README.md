# Westergarage Website

Dit is de officiële website voor **Westergarage**, een lokaal garagebedrijf gerund door Jan. De website is ontworpen met een "bad ass", industriële en zakelijke uitstraling, passend bij een no-nonsense garage.

## 🚀 Technologie

Deze website is gebouwd met moderne, lichtgewicht technologieën voor maximale snelheid en eenvoud:

-   **Vite**: Supersnelle development server en bundler.
-   **Tailwind CSS 4**: De nieuwste versie van het populaire utility-first CSS framework.
-   **Vanilla HTML/JS**: Geen zware frameworks (zoals React of Vue), gewoon pure, snelle code.
-   **CSS Variabelen**: Voor eenvoudige thema-aanpassingen (kleuren, fonts).

## 🛠️ Installatie & Gebruik

Zorg dat je [Node.js](https://nodejs.org/) (versie 20 of hoger) geïnstalleerd hebt.

1.  **Installeer afhankelijkheden:**

    ```bash
    npm install
    ```

2.  **Start de development server:**
    ```bash
    npm run dev
    ```
    Ga naar de url die in de terminal verschijnt (meestal `http://localhost:5173`). Wijzigingen in de code worden direct zichtbaar.

## 📦 Bouwen voor Productie

Om de website live te zetten, moet je deze eerst "bouwen". Dit optimaliseert de bestanden voor snelheid.

1.  **Maak de productie-versie:**

    ```bash
    npm run build
    ```

2.  **Het resultaat:**
    De bestanden verschijnen in de map `dist/`.
    -   Upload de **inhoud** van de `dist/` map naar je webhosting (via FTP of een dashboard).
    -   Dit zijn statische bestanden (`index.html`, `.css`, `.js`), dus ze werken op elke server.

## 🎨 Aanpassingen

### Inhoud

Alle tekst staat in `index.html`. Je kunt dit bestand direct aanpassen om teksten, telefoonnummers of diensten te wijzigen.

### Kleuren & Stijl

De styling wordt geregeld in `src/style.css`. Hier vind je de "Theme Configuration" bovenin het bestand:

```css
:root {
    --color-brand-primary: #d90429; /* Het felle rood */
    --color-brand-secondary: #edf2f4; /* De lichte achtergrond */
    --color-brand-dark: #2b2d42; /* Het donkere blauw/grijs */
    /* ... */
}
```

Wijzig deze hex-codes om het kleurenpalet van de hele website direct aan te passen.

### Lettertypes

We gebruiken Google Fonts:

-   **Titels**: `Russo One` (Stoer, industrieel)
-   **Tekst**: `Inter` (Leesbaar, zakelijk)

## 📁 Structuur

-   `index.html`:De hoofdpagina.
-   `src/style.css`: Alle stylingregels.
-   `src/main.js`: Javascript entry point (minimaal).
-   `public/`: Bestanden die niet verwerkt hoeven te worden (zoals `favicon.svg` en `robots.txt`).

---

_Gemaakt met ❤️ en bandenvet voor Westergarage._
